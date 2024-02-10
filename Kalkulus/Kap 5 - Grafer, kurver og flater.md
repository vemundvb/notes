QD- [[#5.1 Grenseverdier og kontinuitet|5.1 Grenseverdier og kontinuitet]]
	- [[#5.1 Grenseverdier og kontinuitet#Grenseverdier|Grenseverdier]]
	- [[#5.1 Grenseverdier og kontinuitet#Genseverdi definisjon|Genseverdi definisjon]]
	- [[#5.1 Grenseverdier og kontinuitet#Regler for grenseverdier:|Regler for grenseverdier:]]
	- [[#5.1 Grenseverdier og kontinuitet#Ensidige grenseverdier|Ensidige grenseverdier]]
	- [[#5.1 Grenseverdier og kontinuitet#Kontinuitet|Kontinuitet]]
	- [[#5.1 Grenseverdier og kontinuitet#Kontinuitet - definisjon|Kontinuitet - definisjon]]
		- [[#Kontinuitet - definisjon#Eksempel|Eksempel]]
	- [[#5.1 Grenseverdier og kontinuitet#Egenskaper ved kontinuerlige funksjoner|Egenskaper ved kontinuerlige funksjoner]]
		- [[#Egenskaper ved kontinuerlige funksjoner#Ekstremalverdisetningen|Ekstremalverdisetningen]]
		- [[#Egenskaper ved kontinuerlige funksjoner#Skjæringssetningen|Skjæringssetningen]]
- [[#5.2 Grunnfunksjoner|5.2 Grunnfunksjoner]]
	- [[#5.2 Grunnfunksjoner#Inverse funksjoner|Inverse funksjoner]]
	- [[#5.2 Grunnfunksjoner#Metodikk for å finne invers funksjon|Metodikk for å finne invers funksjon]]
		- [[#Metodikk for å finne invers funksjon#Eksempel|Eksempel]]
- [[#Grunnfunksjoner|Grunnfunksjoner]]
		- [[#Metodikk for å finne invers funksjon#a) Lineær funksjoner|a) Lineær funksjoner]]
		- [[#Metodikk for å finne invers funksjon#Kvadratiske funksjoner|Kvadratiske funksjoner]]
- [[#Trigonometriske funksjoner|Trigonometriske funksjoner]]
- [[#Inverse trigonometriske funksjoner|Inverse trigonometriske funksjoner]]
- [[#Eksponential- og logaritmefunksjoner|Eksponential- og logaritmefunksjoner]]
	- [[#Eksponential- og logaritmefunksjoner#Eksponentialfunksjoner|Eksponentialfunksjoner]]
		- [[#Eksponentialfunksjoner#Eksempel - Penger i banken|Eksempel - Penger i banken]]
	- [[#Eksponential- og logaritmefunksjoner#$e$|$e$]]
	- [[#Eksponential- og logaritmefunksjoner#Logaritmer|Logaritmer]]
	- [[#Eksponential- og logaritmefunksjoner#Omregning:|Omregning:]]
- [[#Noen egenskaper ved logaritmer|Noen egenskaper ved logaritmer]]
		- [[#Omregning:#Eksempel - forenkling|Eksempel - forenkling]]
- [[#5.3 Symmetri og asymptoter|5.3 Symmetri og asymptoter]]
	- [[#5.3 Symmetri og asymptoter#Translasjon av grafer|Translasjon av grafer]]
		- [[#Translasjon av grafer#Eksempel|Eksempel]]
	- [[#5.3 Symmetri og asymptoter#Symmetri|Symmetri]]
		- [[#Symmetri#Symmetrisk om y-aksen|Symmetrisk om y-aksen]]
		- [[#Symmetri#Eksempel - cos x|Eksempel - cos x]]
		- [[#Symmetri#Symmetrisk om origo|Symmetrisk om origo]]
		- [[#Symmetri#Eksempel - sinus x|Eksempel - sinus x]]
		- [[#Symmetri#En funksjon kan ikke være symmetrisk om origo og y-aksen|En funksjon kan ikke være symmetrisk om origo og y-aksen]]
		- [[#Symmetri#Eksempel - undersøk symmetri forhold|Eksempel - undersøk symmetri forhold]]
	- [[#5.3 Symmetri og asymptoter#Asymptoter|Asymptoter]]
		- [[#Asymptoter#Vertikale asymptoter|Vertikale asymptoter]]
		- [[#Asymptoter#Horisontale asymptoter|Horisontale asymptoter]]
		- [[#Asymptoter#Skrå asymptoter|Skrå asymptoter]]
		- [[#Asymptoter#Eksempel|Eksempel]]
		- [[#Asymptoter#Eksempel|Eksempel]]


## 5.1 Grenseverdier og kontinuitet
Funksjon:
![[Pasted image 20230828095636.png]]
Kan skrives sånn: $f A \to B$
A er definisjonsmengde, B er kodomene
Man sier at a avbildes av et element i b.
Man sier at $b = f (a)$
b er funksjonsverdien til a, eller at b er bildet av a under $f$
Man setter inn a, og får b ut

Når vi lar x gjennomløpe alle mulige verdier i definisjonsmengden $D_{f}$, vil mengden av alle bildene utgjøre verdimengden $V_{f}$

Dersom $V_{f} = B$, er f surjektiv
injektiv: ulike elementer i a, treffer ulike elementer i b, det er altså ikke to elementer i A, som treffer samme element i B

Eksempel:
$f(x) = x^{2} - 3$, $D_{f} = R$
Setter man inn tall for x, får man denne grafen
![[Pasted image 20230829144451.png]]
Verdimengen er alle de verdiene som funksjonen kan produsere. $V_{f} = [-3, \to >$

### Grenseverdier
Gitt en funksjon $f(x) = \frac{x^{2}+2x-8}{2x-4}$, $D_{f} = R - \{2\}$ , 2 gir null i nevneren
![[Pasted image 20230829145129.png]]

Verdier nær x=2
$f(1.8) = 2.9$
$f(2.02) = 3.01$
$f(2.2) = 3.1$
Hva antyder dette?
Hvis man går nært til 2 på x-aske, så nærmer man seg 3 på y-akse.
Dette betyr at vi kan få f(x) så nær 3 vi ønsker dersom vi lar x bli tilstrekkelig nær 2.
Hvis vi vil ha funksjonen så nærme 3 så  mulig, så lar vi x være så nærme 2 så mulig
Skrives slik:
$\lim_{ x \to 2 } f(x) = 3$
Vi kan da definere $f(2)=3$
Leses:
Grenseverdien til f(x) når x går mot 2, er 3.


### Genseverdi definisjon
La $f$ være en funksjon definert i nærheten av $a$,
da er grenseverdien til $f$, når x går mot $a$. Da er:
$\lim_{ x \to a } f(x) = L$
grenseverdien til $f$, når x går mot $a$ 
dersom det til et hvert tall $\epsilon > 0$ finnes tall $\nabla > 0$, slik at $\mid f(x) - L \mid < \epsilon$ for alle  som er nærmere $a$ enn $\nabla$, altså slik at $\mid x - a \mid < \nabla$
![[Pasted image 20230829153250.png]]

Eksempel med $f(x) = \frac{x^{2} + 2x - 8}{2x - 4}$
Velger $\epsilon$ = 0.01
Hvis man vil at grenseverdien skal være nærmere enn 0.01, hva må delta være?
Da må $\nabla$ være 0.02.


### Regler for grenseverdier:
Hvis $\lim_{ x \to a } f(x) = L$ og $\lim_{ x \to a } g(x) = M$
så er $\lim_{ x \to a } (f + g) = L + M$
$\lim_{ x \to a } (f * g) = L * M$
$\lim_{ x \to a } \left( \frac{f}{g} \right) = \frac{L}{M}$, $M \neq 0$

$\lim_{ x \to a } (kf) = k * \lim_{ x \to a } = k*L$, $k c R$

### Ensidige grenseverdier
![[Pasted image 20230829154043.png]]
$\lim_{ x \to a^{-} } f(x)$

EKsempel:
$f(x) = \begin{bmatrix} 2x^{2} ,for, x<1  \\ x^{2} + 3,for,\geq 1 \end{bmatrix}$
![[Pasted image 20230829154352.png]]
Grenseverdien til x går mot 1,
$\lim_{ x \to 1^- } f(x) = 2*1^{2} = 2$
Vi kan få funksjonsverdien så nær 2 vi vil, ved å la x bli tilstrekkelig nær 1.
Når man går fra venstre mot 1, bruker man $2x^{2}$, går man fra høyre mot 1, bruker man $x^{2} + 3$

Siden høyreside og venstreside grenseverdi ikke er like
$\lim_{ x \to 1^- } f(x) \neq \lim_{ x \to 1^+ } f(x)$
sier vi at grenseverdien $\lim_{ x \to 1 } f(x)$ ikke eksisterer





Oftest brukes l'hopitals regel når grenseverdier skal finnes

For polynombrøker med samme grad i teller og nevner, 
når x går mot $\infty^+$ eller $\infty^-$,
Del alle ledd med x opphøyd i høyeste potens som finnes

Eksempel:
$f(x) = \frac{10x^{4} + 3x^{2} - 4}{-2x^{4} + x^{3} - 3x}$
Finn $\lim_{ x \to \infty } f(x)$

Her er høyeste potens $x^{4}$
$\lim_{ x \to \infty } f(x) = \frac{10+\frac{3}{x^{2}} - \frac{4}{x^{4}}}{-2+\frac{1}{x}-\frac{3}{x^{2}}}$
Det kan hende at tallene opphøyd er feil, så ikke tavla helt.
Men poenget er at alle x'ene forsvinner
$\frac{10}{-2} = -5$


### Kontinuitet
Grafen til funksjonen er sammenhengende
![[Pasted image 20230901102245.png]]

### Kontinuitet - definisjon
La $f$ være en funksjon definert
i et intervall omkring $x=a$ (i nærheten av a).
$f$ er kontinuerlig i $x=a$ dersom 
grenseverdien $\lim_{ x \to a^- } f(x) = \lim_{ x \to a^+ } f(x) = f(a)$

I motsattfall:
Diskontinuerlig eller ikke kontinuerlig.

#### Eksempel
Er funksjonen $f(x) = \begin{bmatrix} x^{2} - 1, x \geq 2 \\ x^{3} - x - 3, x < 2  \end{bmatrix}$
Er denne funksjonen kontinuerlig for $x = 2$?
Må se om
$\lim_{ x \to 2^- } f(x) = \lim_{ x \to 2^+ } f(x) = f(2)$

$lim_{ x \to 2^- } f(x^{3} - x - 3) = 2^{3}-2-3=3$
$lim_{ x \to 2^+ } f(x^{2}-1)=2^{2}-1 = 3$
$f(2) = 2^{2} - 1 = 3$
Siden man får samme svar på alle ligningene, ser man at funksjonen er kontinuerlig.

Dersom $f$ og $g$ er kontinuerlige i $x=a$, vil også $f+g, f-g, f \cdot g, \frac{f}{g}$ være kontinuerlig i $x=a$


### Egenskaper ved kontinuerlige funksjoner

#### Ekstremalverdisetningen
Hvis en funksjon er definert på et lukket intervall.
Da har $f$ både et minimum og et maksimum på intervallet.
![[Pasted image 20230901105053.png]]





#### Skjæringssetningen
La $f$ være en kontinuerlig funksjon. 
Definert på intervallet $[a, b]$.
Dersom $f(a)$ har ulike fortegn, så finnes det en $c$, hvor $a < c < b$,
slik at $f(c) = 0$

Hvis funksjonsverdien i a er positiv, og funksjonsverdien i b er negativ.
De har altså ulike fortegn.
Da vil det finnes et sted det funksjonen krysser x-aksen.
Der funksjonen krysser x-aksen vil være punktet c.
Altså så lenge den er kontinuerlig. Hvis den er diskontinuerlig kan det jo hende at den "hopper" akkurat der x-aksen er.
![[Pasted image 20230901110755.png]]



## 5.2 Grunnfunksjoner
Strengt voksende og strengt avtagende funksjoner. (monotone funksjoner)

En strengt voksende funksjon er en funksjon som vokser og vokser etterhvert som man går mot høyre. Hvis den hadde hatt en "dipp", så er den ikke strengt voksende.

Strengt avtagende er en funksjon som bare avtar og avtar.
![[Pasted image 20230913090925.png]]


### Inverse funksjoner
(Omvendte funksjoner)

Altså man har en funksjon fra A til B. $f A \to B$
Den inverse funksjonen går fra B til A $f^{-1} B \to A$
Så a er lik $a=f^{-1}(b)$

For at den skal ha en invers, må den være injektiv og surjektiv.
Injektiv/en-entydig:
Hvis to ulike elementer avbildes på to ulike bilder, så er den injektiv.
Hvis to ulike elementer avbildes på samme element, så er den ikke injektiv.

Surjektiv/på:
Verdimengden til f er lik kodomene $V_{f} = B$, altså elementene i A er i B.

![[Pasted image 20230913090140.png]]




Man setter inn en x i funksjonen, og får ut en y-verdi.
I en invers funksjon setter man inn i y-verdi, så får man ut en x-verdi.
Den x-verdien vil være den inverse funksjonen med den innsatte y-verdien.

Dersom funksjonen ikke er injektiv, vil ikke den inverse funksjonen eksistere.

![[Pasted image 20230913090237.png]]




### Metodikk for å finne invers funksjon
1. Begrens $D_{f}$ slik at f er injektiv. (dersom den ikke alt er det)
2. Erstatt x med y i funksjonsuttrykket.
3. Løs ligningen du får med hensyn på y.


Generelt
- En funksjon m være injektiv (monoton), for at den skal ha invers
- $D_{f}^{-1} = V_{f}, V_{f^-1} = D_{f}$
- Grafen til $f$ og $f^{-1}$ vil symmetrisk om linja y = x
- $f^{-1}sammensatt f(x)=f^{-1}(f(x)) = x$
- $fsammensatt f^{-1} = f(f^{-1}(x))=x$

#### Eksempel
$f(x) = 2x^{2}-4, D_{f} = R$
Denne er i utgangspunktet ikke injektiv
![[Pasted image 20230901114934.png]]

1. Skal vi finne $f^{-1}$. Må vi først begrense $D_{f}$
$D_{f} = [0, \to>$
Vår nye f: $f: D_{f} = [-4, \to>$
![[Pasted image 20230901115047.png]]

2. Må bytte om fra x til y
$y = 2x^{2} - 4 \to x=2y^{2}-4$

Vansligvis i løsningsforlsag er det heller "erstatt f(x) med y"
$y = 2^{2}-4$

3. Løs denne med hensyn på y
$x = 2y^{2} - 4$
$y = \pm \sqrt{ \frac{x+4}{2} }$
+- skylles at funksjonen i utgangspunktet ikke er injektiv.
Men det er bare en av svarene man skal bruke.

Vanligvis i løsningsforlsag er det heller "Løs ligningen med hensyn på x"
$\sqrt{ \frac{y+4}{2} }=x$
Hvis man har x som opphøyd i to, så kan man bruke "andre kvadratsetning"
Eks:
$y = x^{2}-2x-1$
$y=(x-1)^{2}$
Man føyer på -2, så man får det over
så $x^{2}-2x+1-2 = x^{2}-2x-1$
Så da blir det
$(x-1)^{2} - 2$
$y+2=(x-1)^{2}$
$\pm \sqrt{ y+2 } = x-1$
$1 \pm \sqrt{ y+2 } = x$


4. Vanligvis er det "Erstatt y med x, og x med $f^{-1}(x)$"
$f^{-1}(x)=\pm \sqrt{ \frac{x+4}{2} }$
Må begrense til et svar.
Man har $D_{f} = [0,\to> = V_{f^{-1}}$

Så da blir det:
$f^{-1}(x)= \sqrt{ \frac{x+4}{2} }, D_{f^{-1}}$
$V_{f} = [-4,\to>$
$D_{f^{-1}} = [-4,\to>$
$V_{f^{-1}}=[0,\to>$



{bilde}




## Grunnfunksjoner



#### a) Lineær funksjoner
Funksjoner som kan skrives slik: $f(x) = a_{1}x + a_{0}$        $a_{1},a_{0}$   c   $R$
![[Pasted image 20230904085348.png]]


#### Kvadratiske funksjoner
$f(x)=a_{2}x^{2}+a_{1}x+a_{0}$
Funksjoner der den høyeste potensen er 2, gir en parabel
![[Pasted image 20230904085617.png]]

Kvadratsetninger
$(a+b)^{2}=a^{2}+2ab+b^{2}$
$(a-b)^{2}=a^{2}-2ab+b^{2}$
$(a+b)(a-b)=a^{2}-b^{2}$


## Trigonometriske funksjoner
cosinus
![[Pasted image 20230913090400.png]]

sinus
![[Pasted image 20230913090414.png]]


både cos og sin er periodiske funksjoner med periode $2\pi$
VI kan si at
$\cos(x+n 2\pi)=\cos x$    ,    $n$  c  $Z$
$\sin(x+n 2\pi)=\sin x$   ,   $n$  c  $Z$

$\sin x = \cos\left( x - \frac{\pi}{2} \right)$
$\cos x = \sin\left( x+ \frac{\pi}{2} \right)$


## Inverse trigonometriske funksjoner
Begresner $D_{f}$ for sin x slik at vi kan definere invers sinus, kalt arcsin x eller $\sin ^{-1} x$.
Velger $D_{f}=\left[  - \frac{\pi}{2}, \frac{\pi}{2}  \right]$
![[Pasted image 20230913090513.png]]

Sånn ser arcsin x ut (det i rødt)
![[Pasted image 20230913090527.png]]



For cos x begrenser vi $D_{f}$ til $[0,\pi]$
Dette er inverse av cos x, altså arccos x eller $\cos^{-1}x$ (det i rødt)
![[Pasted image 20230913090558.png]]
![[Pasted image 20230913090618.png]]

Tangens
$\tan x = \frac{\sin x}{\cos x}$
![[Pasted image 20230904100013.png]]




## Eksponential- og logaritmefunksjoner
### Eksponentialfunksjoner
Ser slik ut: $f(x) = a^{x}$ med $a>0$, og $D_{f} = R$
a kalles grunntall
![[Pasted image 20230913090701.png]]


#### Eksempel - Penger i banken
Renta er 4%.
$K=K_{0}\cdot 1.04^{t}$
K er kapital, K_0 er startkapital

Dette er en eksponentialfunksjon


### $e$
$e=\lim_{ n \to \infty } \left( 1+\frac{1}{n} \right)^{n} =2.71828$
$f(x)=e^{x}$
$D_{f}=R$
$V_{f}=< 0,\to>$


Siden e er større en null, er den strengt voksende.
![[Pasted image 20230905144122.png]]


Enhver eksponentialfunksjon
$N_{0}a^{x}$ kan skrives $N_{0}e^{\lambda x}$, hvor $\lambda=\ln a$


### Logaritmer
Den inverse funksjonen til $e^{x}$ kalles $\ln x$ (den naturlige logaritmen)
![[Pasted image 20230905144913.png]]
$D_{f} = <0, \to>$
$V_{f} = R$ (altså bare positive verdier)

Den inverse funksjonen til $a^{x}$ er logaritmen med grunntall $a$, altså $\log_{a} x$

De to viktigste:
$\log_{10} x = \log x = \lg x$ (Den briggske logaritmen)
Den inverse funksjonen til $10^{x}$

$\log_{2} x=lb x$ (Den binære logaritmen)
Den inverse til $2^{x}$

### Omregning:
$\log_{a} x = \frac{\ln x}{\ln a}$



## Noen egenskaper ved logaritmer
$e^{\ln x} = x$
$\ln e^{x} = x$
$\ln a^{b}=b\cdot \ln a$
$\ln(ab) = \ln a + \ln b$
$\ln \frac{a}{b} = \ln a - \ln b$
$\ln1 = 0$
$\ln e = 1$

Men:
$\ln (a+b)$ kan ikke forenkles/skrives annerledes
Her må man legge sammen først, så ta logaritmen

#### Eksempel - forenkling
$e^{3\ln x} = e^{\ln x^{3}} = x^{3}$
$e^{-2 \ln x} = e^{\ln x^{-2}} = x^{-2} = \frac{1}{x}$
$e^{\ln 2 + \ln x} =e^{\ln 2x} = 2x$, kan også gjøre: $e^{\ln 2x}=e^{\ln x} \cdot e^{\ln x} = 2x$
$e^{-\ln\left(  \frac{1}{x^{2}}  \right)} = e^{\ln\left( \frac{1}{x^{2}} \right)^{-1}}=\left( \frac{1}{x^{2}} \right)^{-1}=x^{2}$
$e^{e^{\ln(\ln x)}}=e^{\ln x}=x$



## 5.3 Symmetri og asymptoter
### Translasjon av grafer
Det vil si forflytting uten rotasjon

#### Eksempel
$f(x)=x^{2}$
![[Pasted image 20230905153020.png]]
La oss si man vil flytte grafen 2 enheter nedover, ned til -2 på y-aksen.
Da gjør man $x^{2}-2$

La oss si man vil flytte 3 trinn til høyre, altså +3 på x-aksen.
$(x-3)^{2}$, hold rede på at minus drar grafen til høyre, altså ikke venstre

Hva hvis man vil flytte 2 ned og 3 til høyre?
$(x-3)^{2}-2=$    $x^{2}-6x+9-2=$   $x^{2}-6+7$




### Symmetri
Begrenser oss til to typer symmetri:
Symmetri om y-aksen
Symmetri om origo

#### Symmetrisk om y-aksen
Symmetrisk om y-aksen, den speiles om y-aksen
Man har også her at $f(-x) = f(x)$, altså man kommer til samme funksjonsverdi på funksjonen uansett om man går opp fra 2 eller -2
Kalles "Like funksjon"
![[Pasted image 20230905154521.png]]


#### Eksempel - cos x
cos x er en Like funksjon
![[Pasted image 20230905154629.png]]

Man ser at man får samme verdi på y-aksen, fra både f.eks. $\frac{-2\pi}{5}$ og $\frac{2\pi}{5}$


#### Symmetrisk om origo
Man har her at $f(-x) = -f(x)$
Dette kalles oddefunksjoner
![[Pasted image 20230913090857.png]]


#### Eksempel - sinus x
![[Pasted image 20230905155012.png]]
Man ser at når man går fra $- \frac{\pi}{2}$ og $\frac{\pi}{2}$ fra x-aksen, til punktet på y-aksen,
så får man samme tall men med motsatt fortegn.


#### En funksjon kan ikke være symmetrisk om origo og y-aksen
En funksjon kan ikke både være symmetrisk om y-aksen og symmetrisk om origo.
Men den kan være ingen av delene.

#### Eksempel - undersøk symmetri forhold
$f(x) = -x^{3}+3x$
Undersøk symmetri forholdene

Setter inn -x og ser hva vi får
$f(-x) = -(-x)^{3}+3(-x)$
$-x^{3}-3x$
$x^{3}-3x$
Den er ikke lik $f(x)$

Men er den lik $-f(x)$?
$-f(x)=-(-x^{3}+3x)=x^{3}-3x$

Man ser at $f(-x)$ og $-f(x)$ er like. 
Vi ser at $f(-x)=-f(x)$. Funksjonen er en oddefunksjon
Funksjonen er symmetrisk om origo







### Asymptoter
En asymptote er en rett linje som funksjonen nærmer seg, men aldri når.
Disse er:
- Vertikale
- Horinsontale
- Skrå

#### Vertikale asymptoter
![[Pasted image 20230908103044.png]]
Den rød linja går igjennom et punkt.
Man ser de til svarte linjene nærmer seg den røde linja, men de når aldri fram. La oss si man kaller punktet der den rød linja går igjennom x-aksen for c:
$\lim_{ x \to c } f(x) = \pm \infty$

For polynombrøker:
Opptrer der nevneren er lik 0, så fremt ikke også telleren er 0.

Men ikke kun ved polynombrøker.
Annet eksempel:
$\ln x$
![[Pasted image 20230908103454.png]]
Den blå linja overlapper aldri y-aksen

#### Horisontale asymptoter
En horisontal linje
$y = d$,   $d$ $c$ $R$ 
som grafen nærmer seg når $x \to \pm \infty$
![[Pasted image 20230908103800.png]]
Funksjonen krysser aldri den blå linja.

For polynombrøker: opptrer der teller og nevner har samme grad.
Eks $\frac{x^{2}+4}{2x^{2}-4x+2}$
Annet eksempel:
$e^{x}$
![[Pasted image 20230908103940.png]]
Funksjonene krysser aldri x-aksen


#### Skrå asymptoter
Når $f(x)$ nærmer seg en rett linje $ax+b$, når x går mot pluss eller minus uendelig:
![[Pasted image 20230908104223.png]]
Funksjonen krysser aldri den skrå røde linja

For polynombrøker opptrer der teller har grad som er 1 høyere enn nevner.

Annet eksempel:
$f(x) = x+\sqrt{ x^{2} +4 }$
Denne har en skrå asymptote 2x når x går mot uendelig
$y=2x$ når $x \to \infty$




#### Eksempel
$f(x) = \frac{3x^{2}}{x^{2}+1}$

Kombineres ofte med spørsmål om symmetri:
$f(-x) = \frac{-3x^{2}}{-x^{2}+1} =\frac{3x^{2}}{x^{2}+1}$
Vi ser at $f(-x) = f(x)$ er lik. Dette er altså en "Like" funksjon. Den er symmetrisk om y-aksen.

Sjekker asymptote:
Vertikale?: Sjekker om nevneren er null
$x^{2}+1=0$
$x^{2}=-1$
$x= \pm i$
Vi operer ikke med funksjoner av komplekse tall. Bare med reelle tall.
Det er en løsning, men den har ingen reelle røtter i nevner.
Det er altså ingen vertikal asymptote


Horisontal eller skrå?:
En funksjon kan ikke være både horisontal og skrå.
Vi ser at graden er lik i teller og nevner.
Den er altså horisontal.

Finner den horisontale ved å la x gå mot pluss eller minus uendelig.
Hva blir den når den går mot pluss uendelig:
$\lim_{ x \to \infty } \frac{3x^{2}}{x^{2}+1}$
Deler alle ledd med $x^{2}$: $\lim_{ x \to \infty } \frac{3}{\frac{1}{x^{2}}+1}$
Jeg ser at når x går mot uendelig, blir nevneren veldig stor. Så det blir: $3$
Svar: $y=3$
Når $x$ går mot $- \infty$ må være den samme, fordi $f(x)$ er symmetrisk om y-aksen.
![[Pasted image 20230908110005.png]]
![[Pasted image 20230908110021.png]]


#### Eksempel
$f(x) = \frac{x^{3}}{x^{2}-1}$, $D_{f}=R=\{-1,1\}$
$x$ kan ikke være 1 eller -1, fordi da blir nevner 0.

Vertikale asymptoter er der nevneren er 0.
$x^{2}-1=0$
$x^{2}=1$
$x= \pm \sqrt{ 1 } = \pm 1$
Selv om verdien er utenfor definisjonsområde, kan den fortsatt være vertikal. 
Er teller lik 0 for $x = \pm 1$?
For x = 1 og x = -1, så blir den ikke 0. Så nei.
Funksjonen har følgelig vertikale asymptoter for $x=-1$
og $x=1$

Skrå asymptote:
Fordi graden til telleren er 1 større enn graden til nevneren, har $f(x)$ en skrå asymptote, og ingen horisontal.

Finner denne ved polynomdivisjon:
$x^{3}: x^{2}-1=x$ så ganger x med $x^{2}$
 $-(x^{3}-x)$, så trekker fra
       $x$
x blir rest, x bak = bli koisient.
Dette betyr at $\frac{x^{3}}{x^{2}-1}=x+\frac{x}{x^{2}-1}$
altså $koisient+\frac{rest}{nevner}$
$\frac{x(x^{2}-1)}{x^{2}-1}+\frac{x}{x^{2}-1}=\frac{x^{3}-x+x}{x^{2}-1}$
x som tilsier koisientent er altså den skrå aymptoten, frodi for rest øver nevneren raskere enn telleren, slik at rest vil etterhvert forsvinne når $x \to \pm \infty$
Det som står igjen er koisienten.

Følgelig har $f(x)$ skrå-asymptoten $y=x$
![[Pasted image 20230908113623.png]]
![[Pasted image 20230908113635.png]]















----------------------------
$\lim_{ x \to a } f(x)$
$\infty$
$\epsilon$
$\delta$
$\cdot$