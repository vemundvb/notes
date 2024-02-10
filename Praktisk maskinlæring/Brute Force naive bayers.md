
- [[#Brute force|Brute force]]
- [[#Uttak fra workshop fredagslecture|Uttak fra workshop fredagslecture]]

## Brute force
Bruker datasettet "should we play tennis?"

må kunne forklare hvordan algoritmene funker
class = klasse innenfor target? eks play og ikke play? eller target?
tror det er resultatet i en target

Man har en testdata nederst


brute force naive bayers
P(C=yes)=6/10
P(C=no)=4/10
Den siste raden testes mot, s den inkluderes ikke

P(outlook=sunny|C=yes)=1/6
P(outlook=sunny|C=no)=3/4
P(outlook=overcast|C=yes)=2/6
P(outlook=overcast|C=no)=0
P(outlook=rain|C=yes)=3/6
P(outlook=overcast|C=no)=1/4

P(tmp=cool|C=yes)=3/6
P(tmp=cool|C=no)=1/4
P(tmp=mild|C=yes)=2/6
P(tmp=mild|C=no)=1/4
P(tmp=hot|C=yes)=1/6
P(tmp=hot|C=no)=2/4

P(humidity=normal|C=yes)=4/6
P(humidity=normal|C=no)=1/4
P(humidity=high|C=yes)=2/6
P(humidity=high|C=no)=3/4

P(wind=strong|C=yes)=1/6
P(wind=strong|C=no)=2/4
P(wind=weak|C=yes)=5/6
P(wind=strong|C=no)=2/4





Kan nå kalkulere:
Tester nå mot verdiene i testen (nederste rad)

$P(yes) * P(outlook=sunny|yes) * P(tmp=mild|yes) * P(humidity=normal|yes) * P(wind=strong|yes)$$\frac{6}{10} \cdot \frac{1}{6}\cdot \frac{1}{3} \cdot \frac{2}{3} \cdot \frac{1}{6}=\frac{12}{3240}=\frac{1}{270}$
Dette er sannsynligheten for at klassen er "yes"

$P(no) * P(outlook=sunny|no) * P(tmp=mild|no) * P(humidity=normal|no) * P(wind=strong|no)$$\frac{4}{10} \cdot \frac{3}{4} \cdot \frac{1}{4}\cdot \frac{1}{4} \cdot \frac{1}{2}=\frac{12}{1280}=\frac{3}{320}$
Detter er sannsynligheten for at klassen er "no"

Vi ser at sannsynligheten for "no" er større.
Men det faktiske svaret er "yes"
Hvorfor gikk det feil?
Man har ikke nok data.
Man trenger gjerne ikke så mye data med denne formelen, kanskje hvis man hadde 100 instanser istedenfor.
En annen ting kan være at man har en "overfitted" model, som betyr at modellen er "overtuned" for treningsdataen.




Cathegorical naive bayes
Hva er "smoothing" $a$ faktor?
x=t sannsynlighet for at x har en vedi
Sannsynlighet for at target har verdi
man kan bruke det for å fikse overfitting, og mer general (mer brukbar på forskjellige data)
Man gjør dataene litt mindre accurate, noe som faktisk gjør resultatet litt bedre.




Gaussian funker best på normalt fordelt data




eks på hyperparameter:
smoothing $a$

-----
## Uttak fra workshop fredagslecture
Med gaussian burde man:
bruke parametere
normalisere
bruke pca(num) hvis det er høy korrelasjon
kan bruke cv for mer treningsdata

se dokumentasjon fro PCA og gaussian.

hvis en split er 60/20/20,
så lar cv deg bruke mer treningsdata med 80/20

Bruk en modell på kategori og en på gaussian,
multipliser sammen resultatet?
bruk kanskje encoder på de kategoriske dataene.


1. Calculate the probability from the categorical variables.
2. Calculate the probability from the continuous variables.
3. Multiply 1. and 2. **AND**

?
4. Divide 3. by the sum of the product of 1. and 2. **EDIT:** What I actually mean is that the denominator should be (probability of the event given the hypotnesis is _yes_) + (probability of evidence given the hypotnesis is _no_) (asuming a binary problem, without loss of generality). Thus, the probabilities of the hypotheses (_yes_ or _no_) given the evidence would sum to 1.



```python
cathegorical_nb = CathegoricalNB()
gaussian_nb = GaussianNB()

dataset = nb.read_csv(...)

categorical_names = ['age',...]
non_categorical_names = ['cp',...]
```








