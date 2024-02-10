vanlig 50,25,25 eller 80,10,10


#### what are the features and feature types?
bruk .info()
typen er det under "Dtype"

#### show statistics using text and visual plots:
kan bruke .describe() for statistikk

#### hvordan se distribusjon og outliers:
fra describe():
quartile - man kan se om 50% er lik mean
for outliers kan man se alt mellom quartile og min og max for å se etter en "hale" på distribusjonen
man ser at eks chol har veldig høy max, så den har en stor outlier.
for harde kategoriske verdier (eks sex) kan man se om eks mean er på 0.5, hvilket tilsier like mange kvinner som menn.


####  sex og cp er kategorier, de må bli konvertert:
Dette burde gjøes helt på starten
features['sex'] = features['sex'].asType('category')
da burde man se på features.info() burde man se at sex har blitt til category

#### plots
Man kan eks bruke histogram og boxplots for å finne outliers.
Da vil man se på histogram om: Det er en spesielt stor kolonne, eller om distribusjonen har en hale
eks chol ser man en veldig lang hale.
boxplot: se etter sirkler. 
det kan være at en lang hale er naturlig (eks trestbps kan være naturlig, at distribusjonen er mer av en one-sided, men f.eks chol er veldig suspect.

#### hvordan håndtere outliers:
F.eks. med sensordata så er det nesten alltid outliers.
De representerer kanskje ikke en realitet, så de kan fjernes.
Men hvis det er outliers som faktisk representerer riktig data, så er det ikke sikkert de burde fjernes.
Man kan bruke eks normalization til å håndtere tilfellet der man har outliers som representerer en faktisk realitet. Man kan feks sentere dataene rundt 0 med standard normalization. En det tilfellet kan det være at eks min-max normalization ville vært mer problematisk, fordi veldig få verdier kommer på toppenden. eks chol kan det være om man burde skippe verdier, eller bruke standard normalization.



#### Se etter korrelasjon
Man kan bruke features.corr()
Man kan f.eks. også bruke matrix heatmap
1 er at de er helt overlappende
-1 er at de er inverse
Verdier i nærheten av -1 og 1 burde ses nærmere på
på heatmap så er det spesielt slope og oldpeak som burde ses mer på.
man burde da se på beskrivelsen i dokumentasjonen til kolonnene for å se om dataene faktisk korrelerer.

#### se på target fordeling i prosent og antall
targets.value_counts()
og
targets.value_counts()/len(targets)


#### splitte data
tenke over ration av klassen fra det over
man burde alltid bruke stratified hvis man kan
test settet må kunne representere datasette.
test burde være være representativt av alle features.
Man kan se på hvordn test måler opp mot målingen av features

























