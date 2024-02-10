Med mongodb bruker vi datasettene for værdata og magasindata.

Dette kan brukes f.eks. til å se på hvordan nedbør henger sammen med fyllingsgraden i magasinene.

Vi antar at:
- Det er for det meste kommersielle og privatpersoner som kommer til å bruke databasen.
- Det betyr at folk er mest interessert i de dataene tilhørende det elspotområdet de selv bor i.
- Vi antar også at brukerne kommer til å svært sjeldent være interessert i værdataene sammen med magasindataene
- og at de nesten aldri kommer til å være interessert i værdataene for seg selv.



Først kan man tenke seg to dokumenter for hvert datasett.
```python
magasin_data [
				{
				dato: ...
				OmrType: ...
				Fyllingsgrad: ...
				Kapasitet_Twh: ...
				Fylling_Twh: ...
				Fyllingsgrad_forrige_uke: ...
				Endring_i_fyllingsgrad: ...
				Neste_pub_Dato: ...
				}


]

værdata [
			{
			navn: 'navn på stasjon'
			Nedbør: ...
			Middelvind: ...
			Middeltemperatur: ...
			Maksimumstemperatur: ...
			Minimumstemperatur: ...
			Fylke: ...
			Område_nr: ...
			}


]

```

Men det blir svært vansklig å hente ut data fra dette oppsettet

Det blir jobb å filtrere for hvilket magasinområde det er snakk om.
Siden værdataene og magasindataene er i forskjellige dokumenter uten noen kobling, betyr det at spørringene kan bli litt vriende for å hente ut data.

Istedenfor kan man legge dataene fra værstasjoner for en dag sammen med magasin_dataene for en dag
```python
magasin_data [
				{
				dato: ...
				OmrType: ...
				Fyllingsgrad: ...
				Kapasitet_Twh: ...
				Fylling_Twh: ...
				Fyllingsgrad_forrige_uke: ...
				Endring_i_fyllingsgrad: ...
				Neste_pub_Dato: ...
				værdata [
					{
					navn: 'navn på stasjon'
					Nedbør: ...
					Middelvind: ...
					Middeltemperatur: ...
					Maksimumstemperatur: ...
					Minimumstemperatur: ...
					Fylke: ...
					Område_nr: ...
					}
				]
				}
]
```

Men det er forsatt sånn at man gjerne må filtrere på magasinområdet det er snakk om.
Istedenfor kan man lage et dokument for hvert magasinområde:
```python

område_1 [
				{
				dato: ...
				OmrType: ...
				Fyllingsgrad: ...
				Kapasitet_Twh: ...
				Fylling_Twh: ...
				Fyllingsgrad_forrige_uke: ...
				Endring_i_fyllingsgrad: ...
				Neste_pub_Dato: ...
				værdata [
					{
					navn: 'navn på stasjon'
					Nedbør: ...
					Middelvind: ...
					Middeltemperatur: ...
					Maksimumstemperatur: ...
					Minimumstemperatur: ...
					Fylke: ...
					Område_nr: ...
					}
				]
				}
]

```

Men et problem er at man får med veldig mye værdata når man skal hente ut magasindata. Det er ikke alltid man er interessert i all den dataen.

Man kan ha værdataene lagret i et annet dokument, så kan man bruke en foreign key til å referere til værdataene for et område på en dato.

```python
område_1 [
				{
				dato: ...
				OmrType: ...
				Fyllingsgrad: ...
				Kapasitet_Twh: ...
				Fylling_Twh: ...
				Fyllingsgrad_forrige_uke: ...
				Endring_i_fyllingsgrad: ...
				Neste_pub_Dato: ...
				værdata_id: ...
				}
]

værdata_område_1 [
				{
				_id: ...   // værdata_id
				dag {
					værstasjoner [
						{
							navn: 'navn på stasjon'
							Nedbør: ...
							Middelvind: ...
							Middeltemperatur: ...
							Maksimumstemperatur: ...
							Minimumstemperatur: ...
							Fylke: ...
							}
						]
					}
				}
]
```
Da er databasen i mål.
Nå kan man lett filtrere dataene for dager, etter elspotområde, og man kan lett benytte værdataene, uten å få dem med når de er uinterresange.



```python
INSERT INTO Viken (id, created_at, fylke_navn, fylke_nr, dag)
VALUES (
    uuid(),
    toTimestamp(now()),
    'Viken',
    1,
    {
        '2021-01-01': {id: uuid(), created_at: toTimestamp(now()), tariffgruppe: 'Husholdning', kvantum_per_fylke: 2106950, snittEnergiEKs: 12.49985, snittEnergInk: 36.487064, snittEffektEks: 0, snittEffektInk: 0, snittFastLeddEks: 2999.964, snittFastleddInk: 3749.955, snittOmregnetOreEks: 27.49967, snittOmregnetOreInk: 55.23684},
        '2021-05-01': {id: uuid(), created_at: toTimestamp(now()), tariffgruppe: 'Husholdning', kvantum_per_fylke: 4054046, snittEnergiEKs: 19.15, snittEnergInk: 44.800003, snittEffektEks: 0, snittEffektInk: 0, snittFastLeddEks: 1104, snittFastleddInk: 1380, snittOmregnetOreEks: 24.67, snittOmregnetOreInk: 51.700005},
        '2021-07-01': {id: uuid(), created_at: toTimestamp(now()), tariffgruppe: 'Husholdning', kvantum_per_fylke: 1921971, snittEnergiEKs: 16.278221, snittEnergInk: 41.20976, snittEffektEks: 2.666944, snittEffektInk: 3.33368, snittFastLeddEks: 2338.1055, snittFastleddInk: 2922.6318, snittOmregnetOreEks: 28.608816, snittOmregnetOreInk: 56.623},
        '2022-01-01': {id: uuid(), created_at: toTimestamp(now()), tariffgruppe: 'Husholdning', kvantum_per_fylke: 2040645, snittEnergiEKs: 12.499838, snittEnergInk: 34.887047, snittEffektEks: 0, snittEffektInk: 0, snittFastLeddEks: 2999.961, snittFastleddInk: 3749.9512, snittOmregnetOreEks: 27.499643, snittOmregnetOreInk: 53.636803}
    }
);
```


```python
CREATE TABLE Viken (
			id UIID,
			created_at TIMESTAMP,
			fylke_navn STRING,
			fylke_nr INT,
			dag MAP<DATE, Dag_nettleie>,
			PRIMARY KEY (fylke_navn, fylke_nr, id)
)

CREATE TYPE Dag_nettleie (
			id UIID,
			created_at TIMESTAMP,
			tariffgruppe STRING,
			kvantum_per_fylke INT,
			snittEnergiEKs FLOAT,
			snittEnergInk FLOAT,
			snittEffektEks FLOAT,
			snittEffektInk FLOAT,
			snittFastLeddEks FLOAT,
			snittFastleddInk FLOAT,
			snittOmregnetOreEks FLOAT,
			snittOmregnetOreInk FLOAT,
			PRIMARY KEY (id)	
)


CREATE TABLE værstatistikk_fylke (
				id UIID,
				created_at TIMESTAMP,
				fylke_navn STRING,
				fylke_nr INT,
				dag MAP<DATE, Dag_værdata>
				PRIMARY KEY (fylke_navn, fylke_nr, id)	
)

CREATE TYPE Dag_værdata (
				id UIID,
				created_at TIMESTAMP,
				stasjon_navn STRING,
				stasjon_id STRING,
				middel_av_middelvind FLOAT,
				maksmumstemperatur FLOAT,
				minimumstemperatur FLOAT
				nedbør FLOAT
				PRIMARY KEY (id)
)


```