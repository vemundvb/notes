




Hvordan kommer databasen til å brukes:
Men henter ut forskjellige info
Ikke hyppige oppdateringer



{
	dag_id: 
}

Dokument magasin
{
	dato_id:
	omrtype: eks 1
	iso_arr:
	iso_uke
	fyllingsgrad:
	kapasitetThw
	nest
	forrige
	endring
}

dokument stasjon
{
	navn
	stasjon
	tid
	middelvind
	mid.temps
	maks temp
	min temp
	nedbør
	fylke
}



id_ - Når det er mye data



```python
{
	områdenr 1 {
			dag {
					værstasjoner: []	
					magasindata 
				}
	}
}
```

```python
{
	 områdenr 1: [
	 dag Date(...) {
		 magasindataer {
			 fyllingsgrad...
			 kapasitet...
		 }
	 }
	 
	 ],
}
......
værdata_i_område_1: {
	dager: [
		værstasjon_navn_data: {}
	]
}
----------

{
	værstasjon_id: [
		fylke: ...
		navn: ...
		område_nr: ...
		dag_id Dato(..) {
			værdata: {}
		}
		dag Dato(...) {
			værdata: {}
		}
	]
}
................
{
	 værstasjon2: [
		dag_id Dato(..) {
			værdata: {}
		}
		dag_id Dato(...) {
			værdata: {}
		}
	 ]
}

.................
{
	 områdenr 2: {}
}


```


fyllingsgrad over tid
fyllingsgrad nå

Samlet nedbør og fyllingsgrad på et visst område på en viss tid
Fylke med mest kapasitet Thw
Endring i nedbør og endring i fyllingsgrad
Gjennomsnittlig nedbør per år
Fyllingsgrad, nedbør og thw over tid






dag hentes ut med forelder
værdata: 


værdata og magasindata hentes ofte ut med dato


```python

dager [
	dag: {
		område_nr1_id: [
			magasindata: {}	
		
	
	
		}
	
	}





]




```



















