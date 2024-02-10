- [[#Del 1|Del 1]]
- [[#Del 2|Del 2]]
	- [[#Del 2#3D-modellering|3D-modellering]]
		- [[#3D-modellering#Bakkassa|Bakkassa]]
		- [[#3D-modellering#Førerkassa|Førerkassa]]
		- [[#3D-modellering#Motorkassa|Motorkassa]]
		- [[#3D-modellering#Lasteholderen og lasten|Lasteholderen og lasten]]
		- [[#3D-modellering#Hjulene|Hjulene]]
		- [[#3D-modellering#Fillet|Fillet]]
	- [[#Del 2#Resultat|Resultat]]
- [[#Printing|Printing]]

## Del 1
### Medisinsk bruk
For medisinsk bruk kan 3D printing brukes til å lage medisinske verktøy.
For eksempel kan det brukes til å etterligne beinstrukturer, eller så kan man bruke en spesiell type bioprinter til å lage organer. Dette er kjekt fordi strukturene til disse organene og beinstrukturene kan være komplekse og vansklige å etterligne. Så tilgjengeligheten til f.eks. organplantasjoner blir mer tilgjengelig.
Dette er nyttig for passienter som trenger organtransplantasjon.
Det kan også være kjekt å kunne 3D printe organer for å lære opp helsepersonell

### Konstruksjon
Man kan bruke 3D printing til å generere konstruksjonsmateriale. Dette er bruktbart for å gjøre konsturksjonstiden mindre. Det kan også brukes i kriseområde til å generere deler for små hus i leire.
Dette er nyttig for konsturksjonsfirmaer, og folk som skal skaffe seg hus.

### Tannpleie
3D printing kan brukes til å generere tenner og gebiss. Det øker tilgjengeligheten av disse, og forbedrer tannlegers mulighet til å utføre tannpleie.
Dette er nyttig for folk som trenger tannpleie, og for tannleger.

Kile: [15 Major Uses of 3D Printing Changing Our Lives in 2023 - 3DSourced](https://www.3dsourced.com/guides/uses-of-3d-printing-applications/)



## Del 2

### 3D-modellering

Jeg skal lage en lastebil som 3d-modell. Dette kommer til å bli det endelig resultatet:
![[Pasted image 20231005102110.png]]


#### Bakkassa
Jeg starter med å lage kassen som er bak sjåførdelen av lastebilen.

Jeg starter meg "+create sketch"
![[Pasted image 20230917082233.png]]
Jeg klikker på "create sketch", og klikker på origo. Så velger jeg bakke-planet.
Så klikker jeg på 2-point rectangle.
![[Pasted image 20230917082346.png]]
Så klikker jeg på origo.
Dimensjonene jeg velger er 100x100.
![[Pasted image 20230917082449.png]]
Så klikker jeg på "finish sketch"

Så klikker jeg på "extrude".
![[Pasted image 20230917082600.png]]
Da får jeg automatisk opp en meny for å velge for langt opp jeg vil flaten skal bli ekspandert.
Jeg velger 100mm som verdi.
![[Pasted image 20230917082706.png]]

Kassa har en skrå topp over sjåførplassen.
Jeg velger en av topplinjene på toppen av kassa.
![[Pasted image 20230917083133.png]]
Så klikker jeg på modify $\to$ champfer
Verdien jeg bruker er 100/4
![[Pasted image 20230917083722.png]]

Nå skal jeg lage vinduer.
Jeg lager parametere for vinduene.
Jeg klikker solid $\to$ modify $\to$ Change parameters
Jeg klikker på "+" symbolet for å lage et parameter.

Jeg lager to parametere kalt "vindu_lengde" med verdi på 12mm,
og "vindu_høyde" med verdi 25mm.
![[Pasted image 20230917084915.png]]
Så klikker jeg "Ok"

Jeg klikker på en av sidene av kassa.
![[Pasted image 20230917085156.png]]
Så klikker jeg på "create sketch"


![[Pasted image 20230917085508.png]]
Jeg klikker på seksjoner fra siden, og 1 boks nede fra den høyden bokser har en skrå vinkel på.
Så putter jeg inn parameterene for vinduet.

Så skal jeg lage det neste vinduet rett over.
Vinduet er 2 bokser under toppen av kassa, og like langt inn som det første vinduet.
Vinduet er lengst langs x-aksen, så nå putter jeg vindu_høyde på x-aksen, og vindu_lengde på y-aksen.
![[Pasted image 20230917090144.png]]
Så klikker jeg "finish sketch"

Så skal jeg ha vinduene på den andre siden av bakkassa, så jeg gjør den samme prosessen der:





Så velger jeg begge vinduene samtidig og klikker på "extrude".
Verdien jeg setter inn er 1.
![[Pasted image 20230917091158.png]]

Så velger jeg overflaten på begge vinduene, og klikker "Shell"
![[Pasted image 20230917091246.png]]
Verdien jeg velger er 1
![[Pasted image 20230917091315.png]]
Så klikker jeg "Ok" på menyen som kommer opp.
Jeg synes at vinduene er litt små, så jeg vil endre parametervierdiene.
Jeg klikker på modify $\to$ change parameters, og endrer verdiene.
vindu_lengde får verdi 15mm, og vindu_høyde får verdi 35mm
![[Pasted image 20230917091629.png]]
Da blir vinduene litt større.
![[Pasted image 20230917091650.png]]

Så skal jeg lage vinduer på den skrå siden av kassa.
![[Pasted image 20230917092329.png]]
Jeg velger flaten og klikker "create sketch"
Jeg lager går to bokser inn, og en boks ned.
![[Pasted image 20230917092905.png]]
Jeg lager et lignende vindu på andre siden av den skrå flaten.
![[Pasted image 20230917093011.png]]

SÅ velger jeg begge vinduene
![[Pasted image 20230917093108.png]]
Så klikker jeg "extrude", og klikker 1 som verdi.
![[Pasted image 20230917093145.png]]
Så velger jeg begge overflatene på vinduene, og klikker "shell"
Så putter jeg inn 1 som verdi.
![[Pasted image 20230917093239.png]]
Deretter klikker jeg på finish sketch



I vinduene er det hull. Dette vil jeg ikke ha. Grunnen for hullene, er fordi jeg brukte "Shell".
Istedenfor skal jeg putte en sketch inn i vinduene, så bruke extrude nedover i vinduene.
Da vil jeg få rammer til vinduene, uten at det blir hull i førerkassa.
Jeg bruker tidslinjen til å gå tilbake til da jeg akuratt hadde brukt extrude på vinduene.
![[Pasted image 20230920122542.png]]

Jeg klikker på overflaten til det øvre vinduet, så klikker jeg på create sketch.
Jeg klikker i en av hjørnene til vinduet, så setter jeg høyden til "vindu_lengde-2" og "vindu_høyde-2". 
![[Pasted image 20230920123308.png]]

Så klikekr jeg på flaten til den nye sketchen. På sidemenyen har jeg "Sketch objetcs" som Move objects.
Jeg presser m på tastaturet, så klikker jeg på en av sidene til sketchen, og skriver inn verdier for hvor mye jeg vil flytte sketchen. Da skriver jeg 1mm som verdi.
![[Pasted image 20230920124149.png]]
På den nedre linjen velger jeg -1mm som verdi.
![[Pasted image 20230920124223.png]]

Jeg gjør det samme for nedre vindu
![[Pasted image 20230920124319.png]]

![[Pasted image 20230920124657.png]]


Så velger jeg begge overflatene
![[Pasted image 20230920124735.png]]
Så velger jeg extrude, og putter inn -1 som verdi
![[Pasted image 20230920124811.png]]
Jeg gjør det samme på den andre siden


#### Førerkassa
Jeg starter med å lage parametere.
For meg ser det ut som om:
Frontvinduet har en størrelse som deller halvparten av førerkassa, og en lengde som spenner over hele kassa.
Førerkassa har en bredde som er lik halvparten av bakkassa.
Førerkassa er litt smalere i lengden enn bakkassa. Kanskje 10mm smalere på hver side.

Jeg legger til disse parameterene.
Modify $\to$Change parameters $\to$ +
![[Pasted image 20230918175407.png]]

Jeg starter med å lage førerkassa.
Jeg klikker på fronten av bakkassa, så på create sketch.
Så klikker jeg på toppen av kassa rett under en av vinduene, under det ytre hjørnet.
Så klikker på bunnen av boksen rett under det ytte hjørnet på det andre vinduet.
![[Pasted image 20230918180103.png]]
Deretter klikker jeg "finish sketch"

Så klikker jeg på flaten av den nye sketchen, og klikker "extrude". Jeg putter inn "førerkasse_lengde" som verdi.
![[Pasted image 20230918180424.png]]


Nå skal jeg sette inn frontvinduet.
Jeg klikker på fronten av førerkassa, og velger det ene topphjørnet 2 bokser inn under og over, så for lengde velger jeg førerkassa_lengde, og for høyde velger jeg førerkasse_høyde.
Så klikker jeg på finish sketch
![[Pasted image 20230918180855.png]]

SÅ skal jeg lage dørvinduene på siden av førerkassa.
Jeg klikker på en av sideflatene av førerkassa, og velger create sketch.
Det ene topphjørnet er to bokser innover fra topp og siden.
Så velger jeg frontvindu_høyde for høyde, og 30mm som lengde.

![[Pasted image 20230918181145.png]]










Over frontvinduet er det en jernbøyle. 
For å lage denne gjør jeg følgende:
Jeg klikker på fronten av førerkassa, og klikker create sketch.
Så klikker jeg 2-point-rectangle. Jeg velger jeg et av de øvre hjørnene på førerkassa.
På lengde så velger jeg førerkasse_lengde, og på høyde velger jeg 8mm.
Så presser jeg enter og klikker fnish sketch.
![[Pasted image 20230918190339.png]]

På siden av førerkassa kan du se større sketches på sidene. DIsse var orginalt ment for å være en dør, men jeg valgte å ikke ta med dette alikevel. Så ignorer de større sketchene på sidene av førerkassa

Så klikker jeg på front-overflaten av sketchen til bøylen, og velger extrude. Som verdi putter jeg inn 10mm. 
![[Pasted image 20230918190540.png]]
Så klikker jeg Ok på menyen.
Så klikker jeg på linjen for toppkanten av bøylen:
![[Pasted image 20230918190623.png]]
Så klikker jeg på modify $\to$ champfer.
Så putter jeg inn 8mm som verdi
![[Pasted image 20230918190745.png]]
Så klikker jeg Ok på menyen.

Nå skal jeg gi former til førerkassa med hjelp av sketchene.

Jeg klikker på hvert vindu, og klikker på extrude for hver av dem, en-etter-en:
![[Pasted image 20230918191754.png]]
Så velger jeg fronten av hvert vindu, og klikker på shell. Som verdi putter jeg på 1mm
![[Pasted image 20230918191843.png]]
Så klikker jeg Ok på sidemenyen.


Nå er alle vinduene på førerkassa hulle. Jeg må fylle dem,
På en av sidevinduene, velger jeg den indre delen av en av siderammene
![[Pasted image 20231005101704.png]]
Så klikker jeg på extrude, og velger 28mm som verdi
![[Pasted image 20231005101758.png]]

Så velger jeg vindusoverflaten, klikker på extrude, og velger -1mm som verdi
![[Pasted image 20231005101847.png]]
![[Pasted image 20231005101909.png]]

Så gjør jeg akkurat det samme på det andre sidevinduet.



Det er også et hull i frontvinduet. Jeg vil ikke ha det på førerkassa. Jeg vil tette hullet.

Jeg klikker på den indre delen av en av sidene på frontvinduet
![[Pasted image 20231003122609.png]]

Så velger jeg Extrude, og velger 58mm som verdi
![[Pasted image 20231003123030.png]]
Så klikker jeg på Ok på sidemenyen.

Så velger jeg overflaten til frontvinduet, og klikker på extrude
Som verdi putter jeg inn -1mm
![[Pasted image 20231003123159.png]]

Så klikker jeg Ok i sidemenyen
![[Pasted image 20231003123242.png]]


#### Motorkassa
Nå skal jeg lage den delen av lastebilen der motoren ligger.
For meg ser det ut som om motorkassa er like lang som bakkassa
Høyden til motorkassa ser ut som å være halvparten av høyden til bakkassa.

Jeg klikker på fronten av førerkassa, og klikker på create sketch.
Jeg putter en av punktene nederst i hjørnet på førerkassa.
For høyde velger jeg 40mm, for lengde velger jeg 80mm.
Så klikker jeg finish sketch
![[Pasted image 20230918193340.png]]


Så klikker jeg på froten av motorkassa, og klikker på extrude.
Som verdi putter jeg inn 75mm, så klikker jeg Ok på sidemenyen.
![[Pasted image 20230918193518.png]]

På bildet av lastebilen ser det ut som om bredden på motorkassa minsker utover motorkassa.
Jeg klikker på sidelinjene på fronten av motorkassa, og velger modify $\to$ champfer.
![[Pasted image 20230918193714.png]]
I sidemenyen velger jeg Type som Two DIstance.
Jeg putter den første verdien til 10mm, og den andre verdien til 75mm.
![[Pasted image 20230918193902.png]]
Så klikker jeg Ok.

Nå skal jeg etterligne jernflaten som ligger foran motorkassa.
Jeg klikker på overflaten foran på motorkassa, og klikker create sketch
![[Pasted image 20230918195010.png]]
Så velger jeg 2-point rectangle, og lager rektangler rundt alle sidene av overlfaten, med bredde lik 1 boks. Så klikker jeg finish sketch.
Så velger jeg alle sidene, og klikker extrude. Jeg putter inn 1mm som verdi:
![[Pasted image 20230918195123.png]]
![[Pasted image 20230918195139.png]]

Så velger jeg overflaten av motorkassa
![[Pasted image 20230918195203.png]]
Så klikker jeg create sketch, og velger overlfaten på nytt.
Jeg velger 2-point rectangle.

Jeg putter det øvre punktet 1 boks inn og under rammen.
![[Pasted image 20230918195322.png]]
Så klikker jeg finish sketch.

Så klikker jeg på overflaten til den nye sketchen, og velger extrude. Jeg putter inn 1mm som verdi.
Så velger jeg hele baren, og klikker create $\to$ pattern $\to$ rectangular pattern
På quantity i sidemenyen putter jeg inn 5, og på distance putter jeg inn 35mm.
Så klikker jeg Ok på sidemenyen.
![[Pasted image 20230918195714.png]]

#### Lasteholderen og lasten
Jeg velger baksiden av bakkassa, og velger create sketch
![[Pasted image 20230918231926.png]]
Så klikker jeg 5 blokker ut fra sentrum på bunn.
Jeg gir sketchen en høyde på 5mm, og en lengde på 40mm. Så velger jeg finish sketch
![[Pasted image 20230918232119.png]]


Så trykker jeg på flaten til den nye sketchen og trykker på extrude.
Så strekker jeg overflaten ut til en lengde på 400mm

Så klikker jeg på en av sideflatene til det nye objektet, og lager en ny boks på den boksen rett bak 100mm markøren, høyden er på 5mm og lengden er på 50mm.
![[Pasted image 20230918232643.png]]
Så velger velger jeg hele den nye overflaten og presser ctrl+c.
Så på overflaten på lasteholderen foran den nye sketchen, presser jeg ctrl+v.
![[Pasted image 20230918233334.png]]
Så flytter jeg den kopierte sketchen -150mm fra startpunktet

Så velger jeg begge overflatene til de to nye sketchene, og presser ctrl+c
![[Pasted image 20230918233433.png]]

Så velger jeg overflaten på den andre siden av lasteholderen, og klikker edit sketch
![[Pasted image 20230918233532.png]]
så presser jeg ctrl+v.
Så flytter jeg de kopierte skecthene så de ligger rett bak de to orginale sketchene. ved å se rett mot flaten, kan jeg se de to orginale sketchene bak lasteholderen, og dermed gjøre et eksakt line-up.
![[Pasted image 20230918233827.png]]
Så klikker jeg finish sketch.
Så velger jeg overflaten til de nye 4 sketchene, og klikker på extrude.
![[Pasted image 20230918234005.png]]
Som verdi gir jeg 30mm.
![[Pasted image 20230918234044.png]]



Så velger jeg overflaten til bakdelen av bakkassa
![[Pasted image 20230918234243.png]]
Deretter klikker jeg på create sketch.
Jeg klikker med en distanse på 1 boks ut fra overflaten. Så gir jeg en lengde på 110mm, og en høyde på 100mm
![[Pasted image 20230918234518.png]]
Så klikker jeg finish sketch.
Så velger jeg overflaten til den nye sketchen.
![[Pasted image 20230918234619.png]]
Så velger jeg extrude, og gir en verdi på 410mm.
![[Pasted image 20230918234706.png]]
Så klikker jeg på Ok på sidemenyen.


#### Hjulene
Så klikker jeg på undersiden av lasteholderen, og klikker create sketch.
![[Pasted image 20230918235005.png]]

Så på hvert kryss av lasteholderen, lager jeg to linjer.
![[Pasted image 20230918235546.png]]
Jeg lager 4 sketcher. Hver sketch er plassert yterst på den kryssende delen av lasteholderen.
De har en lengde på 70mm og en bredde på 10mm. 
Ved å hovre over et hjørne på en sketch, får jeg en linje fra punktet som jeg kan bruke til å line-opp den neste sketchen.
Så klikker jeg finish sketch.

Så velger alle de nye sketchene.
![[Pasted image 20230918235701.png]]
Så klikker jeg på extrude, og gir 12mm som verdi.
![[Pasted image 20230918235916.png]]
Så velger jeg en av sideoverflatene til en av de nye stengene under lasteholderen.
Så klikker jeg på create sketch, og velger center diameter circle.
Jeg plasserer punktet på bunn på midten, og velger 24mm som verdi.
![[Pasted image 20230919000248.png]]
Jeg gjør det samme for resten av sideoverflatene til de andre stengene, på hver side.
![[Pasted image 20230919000632.png]]

På en av sidene velger jeg alle overflatene til sirklene.
![[Pasted image 20230919000801.png]]
Så klikker jeg på extrude, og velger 20mm som verdi.
![[Pasted image 20230919001009.png]]
Jeg gjør det samme på den andre siden.

Så velger jeg undersiden av bakkassa.
![[Pasted image 20230919001324.png]]
Jeg klikker så på create sketch, og på 2 point rectangle.
Jeg lager en ny stang for hjul. Denne skal være 10mm inn fra hjørnene. 10mm bred, og 80mm lang.
![[Pasted image 20230919001626.png]]
Jeg skal også lage en stang under motorkassa.
![[Pasted image 20230919001736.png]]![[Pasted image 20230919001737.png]]
Den er 20mm inn fra fronten på motokassa, og 10mm under fra det ytre punktet til hjørnekassa.
Den er 10mm bred og 40mm lang.
Så klikker jeg på finish sketch.

Deretter velger jeg overflatene til de nye sketchene, og klikker extrude. Jeg gir 12mm som verdi.
![[Pasted image 20230919001930.png]]
Så klikker jeg Ok i sidemenyen.

Så velger jeg en av sidene av understengene
![[Pasted image 20230919002032.png]]
Så klikker jeg på create sketch, velger center diameter circle, putter punktet i midten nederst på siden av stangen, og gir 24mm som verdi.
![[Pasted image 20230919002138.png]]

Jeg gjør det samme med de andre sidene av stengene.
![[Pasted image 20230919002331.png]]
Så klikker jeg på hver av sideoverflatene til hjulene, og klikker deretter på extrude. Jeg bruker 20mm som verdi.
![[Pasted image 20230919002413.png]]

![[Pasted image 20230919002509.png]]



#### Fillet
Nå ser lastebilen sånn ut.
![[Pasted image 20230919015253.png]]
Det siste jeg skal gjøre er å gjøre linjene smoothere.

Jeg velger topplinjene på førerkassa, så klikker jeg på fillet. Jeg gir 3mm som verdi.
![[Pasted image 20230919015950.png]]

Så klikker jeg fillet, og velger alle kantene på hjulene.
![[Pasted image 20230919020147.png]]
Deretter velger jeg 3mm som verdi.
![[Pasted image 20230919020229.png]]
Jeg gjør det samme på begge sider av lastebilen.
![[Pasted image 20230919020313.png]]

Jeg gjør det også på katene inn mot lastebilen.
![[Pasted image 20230919020355.png]]
![[Pasted image 20230919020412.png]]


Så velger jeg hver av de lange linjene på lasten.
![[Pasted image 20230919020538.png]]
Så klikker jeg på Fillet, og putter inn 3mm som verdi.
![[Pasted image 20230919020617.png]]
Så klikker jeg Ok på sidemenyen.

### Resultat
Nå sier jeg meg ferdig med 3d-modellen.
Dette er det endelige resultate:
![[Pasted image 20231005102110.png]]





## Printing
Nå som modellen er ferdig, så skal jeg eksportere modellen så jeg kan printe den.

Jeg vil eksportere filen i .stl format
For å gjøre det klikker jeg på:
File $\to$ Export...
I menyen som kommer opp velger jeg STL for Type, og jeg navngir filen "lastebil"
![[Pasted image 20231002100559.png]]
Så klikker jeg på Export

SÅ importerer jeg filen i PrusaSlicer ved å klikke:
File $\to$ Import $\to$ Import STL/3MF/STEP/OBJ/AMF

Etter å ha importert filen ser GUIen min slik ut:


Så endrer jeg Scale factors til 19 i sidemenyen:
![[Pasted image 20231012164112.png]]

Når lastebilen skal printes, er det noe jeg bekymrer meg for:
Vil printeren klare å legge lag slik at det formes hjul?
Vil printeren klare å printe lastebilen selv om det meste av det er over bakken?

Jeg klikker på Supports $\to$ Everywhere
Grunnen til at jeg velger everywhere, fordi jeg har veldig mange steder som så vidt henger ut, i tillegg til at det er viktig at printeren får til hjulene, for at hele lastebilen skal bli riktig.
Så klikker jeg på Slice now. Da ser modellen slik ut:
![[Pasted image 20231012164159.png]]

For infill velger jeg 25%. Det er kanskje litt høyere verdi en vanligere, meg jeg vil at printeren skal få til hjulene
Som materiale bruker jeg PLA

For printer velger jeg Original Prusa i3 MK3 & MK3S+

![[Pasted image 20231005115654.png]]
Nå som jeg er fornøyd med modellen så klikker jeg på File $\to$ Export $\to$ Export G-code...


På workspace er det flere 3d printere. Jeg finner en 3d printer for Prusa. 
Jeg tar ut kortet i printeren å putter kortet inn i min egen pc.
Så overfører jeg min gcode fil over til minnepennen.

Når jeg plugger minnepennen tilbake i printeren, kommer modellen automatisk opp på skjermen. Printeren står på "Print", så da trykker jeg inn knappen på siden av printeren.
På printeren står det at printen kommer til å ta litt over 2 timer å printe lastebilen.

Når lastebilen er ferdig printet ser den slik ut:
![[Pasted image 20231012164822.png]]
Etter å ha pelt av support materialet ser lastebilen slik ut:
![[Pasted image 20231012164944.png]]


## Hvorfor lastebilen er praktisk nyttig
Dette er praktisk nyttig fordi jeg kan gi det bort som gave. Det er tiltenkt som en gave til en njese.
