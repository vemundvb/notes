## Oppgave 1
$A(0,0)$
$B(t,0)$
$C(t, f(t) )$
$D(0, f(t) )$

$f(x)= \frac{8}{x^{2}+4}$

Hva må t være for at rektangelet blir størst mulig?
Da må rektangelet være av en slik størrelse at produktet av $t\cdot f(t)$ blir størst mulig.

$A(t)= t\cdot f(t)$
$A'(t)=\left(  \frac{8t}{t^{2}+4}  \right)'= -\frac{8(t^{2}-4)}{(t^{2}+4)^{2}}$

Så løser jeg for når $A'(t)=0$.
Hele ligningen vil være 0 når telleren er 0, så jeg trenger bare å tenke på telleren.
Hele ligningen er 0 hvis en av produktene i telleren er 0, så jeg trenger bare å tenke på $t^{2}-4$
$t^{2}-4=0 \to t=\sqrt{ 4 }\to t=2$

Siden funksjonen er negativ, så vil:
for lavere verdier enn 2, så blir funksjonen positiv
for høyere verdier enn 2, så blir funksjonen negativ.
Punktet er altså et maksimal punkt.

Svar: $t=2$ for at rektangelet skal være størst mulig.

## Oppgave 2
$V=\pi r^{2}h$
$A=2\pi r^{2}+2\pi rh$

Volumet til sylinderen er $1000cm^{3}$
Da vil formelen for volum bestemme forholdet mellom h og r.
For hvis sylinderen skal romme samme volum hele tiden, så må det være sånn at hvis en verdi øker, så må den andre synke.

Volum løst for h:
$V=\pi r^{2}h$
$h=\frac{V}{\pi r^{2}}$

Putter inn i formel for areal:
$A=2\pi r^{2}+2\pi r \frac{V}{\pi r^{2}}=2\pi r^{2}+\frac{2V}{r}$

Deriverer for å finne den optimale verdien for radius:
$A'(r)=0\cdot r^{2} + 2\pi\cdot 2r + \frac{0\cdot r - 2V\cdot 1}{r^{2}}=4\pi r-\frac{2V}{r^{2}}$

Løser for når $A'(r)=0$
$4\pi r-\frac{2V}{r^{2}}=0$
$4\pi r=\frac{2V}{r^{2}}$
$4\pi r^{3}=2V$
$r^{3}=\frac{2V}{4\pi}$
$r=\frac{2V}{4\pi}^{1/3}$
$r=\frac{V}{2\pi}^{1/3}$

$r=\frac{1000}{2\pi}^{1/3}$
$r=\frac{500}{\pi}^{1/3}=5.4$


Løser for h:
$h=\frac{V}{\pi r^{2}}$
$h=\frac{1000}{\pi 5.4^{2}}$
$h=10.8$

Svar:
$r=5.4$, $h=10.8$



## Oppgave 3

Formel for ellipsen:
$\frac{x^{2}}{5^{2}}+\frac{y^{2}}{3^{2}}=1$

Formel for areal av rektangel:
$x\cdot y$

Hva er sammenhengen mellom formelen for en ellipse, og formelen for et rektangel?
Man ser at punktene $(a,b)$ ligger et sted på ellipsen.
Siden lengdene av a og b kun dekker en kvadrant, må man skrive formelen for areal av rektangel som $2a\cdot 2b$

Løser formel for ellipse for a:
$\frac{a^{2}}{5^{2}}+\frac{b^{2}}{3^{2}}=1$
$\frac{a^{2}}{5^{2}}=1-\frac{b^{2}}{3^{2}}$
$a^{2} = \frac{1- \frac{b^{2}}{3^{2}} }{5^{2}}$
$a^{2} = \frac{1- \frac{b^{2}}{3^{2}} }{5^{2}}$
$a = \sqrt{    \frac{1- \frac{b^{2}}{3^{2}} }{5^{2}}}$

$a=\frac{5\sqrt{ 9-b^{2} }}{3}$

Putter inn a i formel for areal:
$2a\cdot 2b$
$A(b)=2\frac{5 \sqrt{ 9-b^{2} }}{3} \cdot 2b$



Deriverer formel:
Jeg ser at formelen er virker slitsom å derivere.
Derfor tar jeg først logaritmen av formelen, så deriverer jeg:
$A(b)=2\frac{5 \sqrt{ 9-b^{2} }}{3} \cdot 2b$

$\ln(A(b))=\ln(2\frac{5 \sqrt{ 9-b^{2} }}{3} \cdot 2b)$
$\ln(A(b))=\ln(2) + \ln(\frac{5 \sqrt{ 9-b^{2} }}{3}) + \ln(2b))$
$\ln(A(b))=\ln2 + \ln5 \sqrt{ 9-b^{2}}  - \ln3+ \ln2b$

$\ln(A(b))=\ln2 + \ln5 +\ln\sqrt{ 9-b^{2}}  - \ln3+ \ln2b$



Ganger med kjernen, for å oppløse logaritmen
$A'(b)=(0+0+\frac{2b}{9-b^{2}}-0+0)\cdot 2\frac{5 \sqrt{ 9-b^{2} }}{3} \cdot 2b$
$A'(b)=(\frac{2b}{9-b^{2}})\cdot (2\frac{5 \sqrt{ 9-b^{2} }}{3} \cdot 2b)$
$A'(b)=-\frac{40b^{2}-180}{3\sqrt{ 9-b^{2} }}$

Løser for $A'(b)=0$
$40b^{2}-180$
$b^{2}=\frac{180}{40}$
$b=\sqrt{ \frac{9}{2} }$
$b=\frac{ 3 }{ \sqrt{ 2 } }$

Løser for a
$\frac{a^{2}}{5^{2}}+\frac{b^{2}}{3^{2}}=1$
$\frac{a^{2}}{5^{2}}+\frac{\left( \frac{3}{\sqrt{ 2 }} \right)^{2}}{3^{2}}=1$
$\frac{a^{2}}{5^{2}}=1-\frac{\left( \frac{3}{\sqrt{ 2 }} \right)^{2}}{3^{2}}$
$\frac{a^{2}}{5^{2}}=\frac{1}{2}$
$a=\sqrt{ \frac{5^{2}\cdot 1}{2} }$
$a=\frac{5}{\sqrt{ 2 }}$


Svar:
$x=\frac{5}{\sqrt{ 2 }}$, $y=\frac{3}{\sqrt{ 2 }}$

## Oppgave 4

Formel for $f(x)$
$f(x)=x^{2}+8$

Formel for $f'(x)$
$f'(x)=2x$

Bruker $x_{0}=3$

$x_{n+1}=x_{n}- \frac{f(x_{n})}{f'(x)}$

$x_{1}=3-\frac{3^{2}-8}{2\cdot 3}=\frac{17}{6}=2.8333$
$x_{2}=2.8333-\frac{f(2.8333)}{f'(2.8333)}=2.8284$
$x_{3}=2.8284427$

Vi ser at desimalene ikke endrer seg.
Vi kan derfor si at vi har kommet i mål.

Svar: $2.8284$



## Oppgave 5
Kurver:
$y=x^{2}(x+1)$
$y=\frac{1}{x}$


Hvor de vil skjære:
De vil skjære hverandre der y er lik.
Altså der ligningene har samme verdi.
Så jeg setter metodene lik hverandre, så putter jeg de på samme side.


Setter ligningene lik hverandre:
$x^{2}(x+1)=\frac{1}{x}$
$x^{2}(x+1)-\frac{1}{x}=0$


Løser for x:
$x^{3}+x^{2}-\frac{1}{x}=0$

Hvis løsningen skal ligge i 1 kvadrant, så må x være positiv.
Jeg gjetter på $x_{0}=1$

Den deriverte av $f(x)$ blir:
$f'(x)=3x^{2}+2x+\frac{1}{x^{2}}$


$x_{1}=1-\frac{f(1)}{f'(1)}=0.833333$
Jeg fikk ikke at telleren ble 0, derfor er ikke 0.8 løsningen.
Jeg trenger mer nøyaktighet, så jeg renger videre:

$x_{2}=0.819239$
Jeg fikk heller ikke nå at telleren ble lik 0, så jeg regner videre.

$x_{3}=0.822884=x_{2}-\frac{f(x_{2})}{f'(x_{2})}=0.819173$
Dette svaret er litt forskjellig fra fasiten.
Jeg tror at vi bare skal finne noe som er i nærheten av svaret, og ikke den eksakte verdien.
Tross alt gir ikke ligningen $f(0.8192)\neq 0$, $f(0.8192)=0.000141$

Så jeg sier at $x=0.8192$, som jeg fikk fra $x_{2}$.


Løser en av ligningene for y:
$y=x^{3}+x^{2}=0.8192^{3}+0.8192^{2}=1.220844$
$1.220844$ er ganske nærme fasiten: $1.2207$


Svar:
$(0.819173, 1.220844)$ eller $(0.8192,1.2207)$






