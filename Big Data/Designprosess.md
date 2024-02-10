Vi bestemmte oss for å bruke datasettene for magasinfylling og spotpris.
Først lagde vi en oversikt over kolonnene i magasinfyllingsdatasettet og spotprisdatasettet.
![[Pasted image 20230925164110.png]]

Så tenkte vi for oss hvordan de to datasettene henger sammen.
De henger sammen ved at de begge har en kolonne som refererer til elspotområde:
omr_nr for magasinstatistikk,
Area for spotpris.

Da kan man tenke seg et design som dette:
![[Pasted image 20230925164506.png]]
Problemet med denne databasen er at magasinstatistikk og spotpris vil inneholde utrolig mye data. Hvis man skal ha en spotpris for en dag i et elspotområde, så må man se igjennom veldig mye data før man finner fram.

Det blir lettere hvis man kan splitte opp noden for magasinstatistikk dagvis, og splitte opp spotpris timesvis:
![[Pasted image 20230925165306.png]]

Men databasen har fortsatt problemer.
Spotpris og magasinstatistikk vil inneholde data for alle elspotområdene for hver dag/time.
Man er gjerne kun interessert til data for det elspotområdet man selv bor i, så det blir unødvendig mye data å se igjennom.
Istedenfor kan vi skille dagene etter elspotområde:
![[Pasted image 20230925165733.png]]
Nå begynner databasen å se mer ferdig ut.
Men man kan fortsatt gjøre noen justeringer.
Hvis vi har relasjonen fra elspotområde til dag være en eksakt dato, og relasjonen for time til spotpris være en eksakt time, så blir databasen bedre. Da kan man hoppe mellom noedene etter relasjonstypen istedenfor å skjekke en dato/time verdi for alle de 360$\cdot$(mengde år) eller 24 (timer) relasjonene.
![[Pasted image 20230925170541.png]]


