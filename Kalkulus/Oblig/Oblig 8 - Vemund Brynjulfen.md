
## Oppgave 1

$\int_{0}^{\pi/3} \frac{3\sin x}{\cos ^{4} x} \, dx$

$u=\cos x$
$\frac{du}{dx}=-\sin x$
$dx=-\frac{1}{\sin x}$

$\int \frac{3\sin u}{u^{4}} \, (-\frac{1}{\sin u})du$
$\int -\frac{3\sin u}{u^{4}\sin u}$
$\int -\frac{3}{u^{4}} \, dx$
$-3 \int \frac{1}{u^{4}} \, dx$
$-3 \cdot \frac{1}{-4+1}u^{-4+1}=\frac{1}{u^{3}}$

$\int \frac{3\sin x}{\cos ^{4}x} \, dx=\frac{1}{\cos ^{3}x}$

$\left[ \frac{1}{\cos ^{3}x} \right]_{0}^{\pi/3}=\frac{1}{\cos ^{3} \left( \frac{\pi}{3} \right)}-\frac{1}{\cos ^{3} (0)}$
$=8-1=7$

Svar:
$7$




## Oppgave 2

$\int \frac{2e^{2x}}{1+e^{2x}} \, dx$

$u=1+e^{2x}$
$\frac{du}{dx}=2e^{2x}$
$\frac{1}{2e^{2x}}du=dx$

$=\int \frac{1}{u} \, du$
$=\ln u$
$\ln(e^{2x}+1)$

$[\ln (e^{2x}+1)]_{0}^{1}$
$=\ln(e^{2\cdot1}+1)-\ln(e^{2\cdot 0}+1)=1.43$

Svar:
1.43




## Oppgave 3
$\int \frac{3x^{2}-13x+16}{(x-2)^{3}} \, dx$

$=\frac{A}{(x-2)^{3}}+\frac{B}{(x-2)^{2}}+\frac{C}{x-2}$

$=3x^{2}-13x+16=A+B(x-2)+C(x-2)^{2}$

Setter inn x=2, da forsvinner B og C
$3\cdot2^{2} - 13\cdot2 + 16 = A + B(0) + C(0)^{2}$
$3\cdot 2^{2} - 13\cdot2 + 16=A$
$2=A$

Vet ikke hvordan jeg skal gå videre...



## Oppgave 4

$y=f(x)=3x^{2}$

### a)
Finne arealet:
![[Pasted image 20231019190630.png]]


$A=\int_{0}^{2} 3x^{2} \, dx$
$=[x^{3}]=2^{3}-0^{3}=8$

Svar:
8

### b)
![[Pasted image 20231019191418.png]]

$V=\pi \int_{0}^{2} (3x^{2})^{2}  \, dx$

$\int (3x^{2})^{2} \, dx=\int 9x^{4} \, dx=\frac{9}{5}x^{5}$
$\pi[\frac{9}{5}x^{5}]_{0}^{2}$
$\pi\left( \frac{9}{5}2^{5}-\frac{9}{5}0^{5} \right)=\pi\left( \frac{288}{5} \right)$

Svar:
$\frac{288\pi}{5}$


### c)
![[Pasted image 20231019192436.png]]


Må finne hva høyden til funksjonen er ved x=0 og x=2

$3\cdot 0^{2}=0$
$3\cdot 2^{2}=12$

Man skal altså finne volumet mellom y=0 og y=12
Så må jeg finne funksjonen med hensyn på y, istedenfor x

$y=3x^{2}$
$-\sqrt{ \frac{y}{3}  }=x$

$V=\pi \int_{12}^{0} \sqrt{ \frac{y}{3} } \, dy$
$V=\pi[\frac{2y^{3/2}}{3^{3/2}}]_{12}^{0}$
$V=\pi(16)$

Svar:
$\pi 16$



## Oppgave 5


### a)
For å finne avgrensningen må jeg finne hvor grafene skjærer hverandre.

$4-x^{2}=x+2$
$x^{2}-x+2$
$(-x+1)(x+2)$

Fra dette ser man at løsningene på funksjonene er 1 og -2

Arealet blir da:
$A=\int_{-2}^{1} f(x) \, dx-\int_{-2}^{1} g(x) \, dx$
$A=\int_{-2}^{1} 4-x^{2} \, dx-\int_{-2}^{1} x+2 \, dx$
$A=\int_{2}^{1} 4-x^{2}-x-2) \, dx$
$A=\int_{2}^{1} -x^{2}-x+2) \, dx$
$A=[- \frac{x^{3}}{3}-\frac{x^{2}}{2}+2x]_{-2}^{1}$

$A=4.5$


Svar: 
$4.5=\frac{9}{2}$


### b)
![[Pasted image 20231020185012.png]]

Det blir altså volumet av begge funksjonene satt lik hverandre

$A=\int_{-2}^{1} 4-x^{2}-x-2) \, dx$



$V=\pi \int_{-2}^{1} 4-x^{2}-x-2) \, dx$


$V=\pi\cdot \frac{9}{2}$


...

## Oppgave 6
Finner x-verdien for y=2
$2=3x^{2}$
$\frac{2}{3}=x^{2}$
$\sqrt{ \frac{2}{3} }=x$

for y=0
$3x^{2}=0$
$x=0$

$V = \int_{\sqrt{ \frac{2}{3} }}^{0} 2\pi x (3x^{2}) \, dx$

Må integrere dette:
$\int 2\pi x (3x^{2}) \, dx$
$2\pi\int x(3x^{2}) \, dx$
$2\pi \int 3x^{3} \, dx$
$6\pi \int x^{3} \, dx$
$6\pi\cdot \frac{x^{4}}{4} +C$
$\frac{3\pi x^{4}}{2}+C$

Kan nå regne ut innenfor intervallet
$[\frac{3\pi x^{4}}{2}]_{\sqrt{ \frac{2}{3} }}^{0}$
$\frac{3\cdot \pi \cdot \sqrt{ \frac{2}{3} }^{4} }{2}- 0$
$=\frac{2\pi}{3}$

Svar:
$\frac{2\pi}{3}$



## Oppgave 7
$t=0$, $v=3$, $a=t^{1/3}$

$t(0)=3$
$a(t)=t^{1/3}$

$v(t)=\int t^{1/3} \, dx=\frac{3t^{4/3}}{4}+C$
$v(t)=\int \frac{3t^{4/3}}{4} \, dx$
$s(t)=\frac{9t^{7/3}}{28}+C$

Siden startfarten er 3. så blir det:

$s(t)=\frac{9t^{7/3}}{28}+3t$

Svar:
$s(t)=\frac{9t^{7/3}}{28}+3t$



## Oppgave 8
$f(x)=\frac{1}{3}(x^{2}+2)^{3/2}$

Deriverer først $f(x)$
$(\frac{1}{3}(x^{2}+2)^{3/2})'=x\sqrt{ x^{2}+2 }$

$\int_{a}^{b} \sqrt{ 1+(x\sqrt{ x^{2}+2 })^{2} } \, dx=\int_{a}^{b} (x^{2}+1) \, dx=\left[ \frac{x^{3}}{3}+x+C \right]_{0}^{1}=\frac{4}{3}+0=\frac{4}{3}$

Svar:
$\frac{4}{3}$
