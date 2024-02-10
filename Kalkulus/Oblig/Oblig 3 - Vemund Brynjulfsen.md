## Oppgave 1
$y=f(x)=\frac{2x^{3}+1}{x^{2}+2}$

Skjekker om vertikal asymptote:
Løser nevneren for $x$:
$x^{2}+2$
$x^{2}=-2$
$x=\sqrt{ -2 }$
Opererer bare med reelle røtter.
Det er altså ingen vertikal asymptote

Man ser at graden i telleren er 1 høyere enn den i nevneren. Funksjonen har altså en skrå asymptote.
Hvis den har en skrå asymptote, så kan den ikke ha en horisontal asymptote.

Finner asymptoten:
$x^{2}+2 | 2x^{3}+1$ -> $2x$

## Oppgave 2
$y=f(x)=\frac{4x^{3}-8x^{2}}{(x-1)^{2}}, x \neq 1$

Skjekker om vertikal asymptote:
Løser for x i nevneren.
$(x-1)^{2}=0$
$x^{2}-x-x+1=x^{2}-2x+1=0$
Fra abc-formelen får man at $x=1$
Men 1 er ikke en løsning i funksjonen.
Funksjonen har altså ikke en vertikal asymptote

Sjekker om funksjonen har en horisontal asymptote:
Nevneren og telleren har ikke samme grad. Så det er ikke en horisontal asymptote.

Man ser at graden i telleren er 1 høyere enn i nevneren. Det er altså en skrå asymptote.

Finner asymptoten:
![[Pasted image 20230911141051.png]]

Skråasymptoten er: $y=4x$


## Oppgave 3

For en funksjon så skal det være sånn at hvis man putter inn y-koordinaten, så får man ut x-koordinaten.
$4x^{4}+5x^{3}-2 \to 4(-1)^{4}+5(-1)^{3}-2=-3$
Punktet $P(-1,-3)$ er altså et punkt på funksjonen.

Finner ligningen til tangenten i punktet:
Funksjonen må være på formen $ax+b$
Deriverer $f(x)$ for å finne stigningstallet til funksjonen.
$f'(x)=4\cdot 4x^{3}+5\cdot 3x^{2}=16x^3+15x^{2}$

Løser for -1 for å finne $a$, som er stigningstallet i punktet der er snakk om.
$f'(-1)=16(-1)^{3}+15(-1)^{2}=-16+15=-1$

Man har at $y=-3$, og $a=-1$, og man setter inn for $x=-1$
finner $b$
$y=ax+b \to -3=-1\cdot -1+b$
$-3=1+b$
$-4=b$

Så funksjonen blir
$y =-1x+(-4)=-x-4$

Svar: $y=-x-4$


## Oppgave 4
#### a)
$f'(x)=5\cdot 6x^{6-1}+2\cdot 3x^{3-1}-3\cdot 1x^{1-1}$
$f'(x)=30x^{5}+6x^{2}-3$

#### b)
$f(x)=\frac{x^{7}}{7}+\frac{x^{4}}{2}-\frac{x}{3}+\frac{7}{5}$
$f'(x)=\frac{(x^{7})'\cdot 7-x^{7}\cdot (7)'}{7^{2}}+\frac{(x^{4})'\cdot 2 - x^{4}\cdot (x^{4})'}{2^{2}}-\frac{(x)'\cdot 3 -x\cdot (3)'}{3^{2}}+\frac{(7)'\cdot 5-7\cdot (5)'}{5^{2}}$
$f'(x)=\frac{7x^{6} \cdot 7- x^{7}\cdot 0}{7^{2}}+\frac{4x^{3}\cdot 2 - x^{4}\cdot 0}{2^{2}}-\frac{1\cdot 3-x\cdot 0}{3^{2}}+\frac{0\cdot 5- 7\cdot 0}{5^{2}}$
$f'(x)=\frac{7x^{6}\cdot 7}{7^{2}}+\frac{4x^{3}\cdot 2 }{2^{2}}-\frac{1\cdot 3}{3^{2}}$
$f'(x)=\frac{49x^{6}}{49}+\frac{8x^{3}}{4}-\frac{3}{9}$
$f'(x)=x^{6}+2x^{3}-\frac{1}{3}$

#### c)
$f(x)=(x^{2}-1)(x+6)$
$f'(x)=(x^{2}-1)'\cdot (x+6)+(x^{2}-1)\cdot (x+6)'$
$f'(x)=(2x)\cdot (x+6)+ (x^{2}-1)\cdot (1)$
$f'(x)=2x^{2}+12x+x^{2}-1$
$f'(x)=3x^{2}+12x-1$

#### d)
$f(x)=\frac{2}{x^{3}}+\frac{3}{x^{2}}-\frac{6}{x}$
$f'(x)=\frac{0\cdot x^{3}+2\cdot 3x^{2}}{x^{6}}+  \frac{0\cdot x^{2}+3\cdot 2x}{x^{4}}-     \frac{0\cdot x + 6\cdot 1}{x^{2}}$
$f'(x)=\frac{6x^{2}}{x^{6}}+  \frac{6x}{x^{4}}-     \frac{6}{x^{2}}$
$f'(x)=-6x^{-4}-6x^{-3}-6x^{-2}$

#### e)
$f(x)=(-4x^{3}+5x^{2}+3)^{7}$
$f'(x)=7u^{6}\cdot u'$
$f'(x)=7(-4x^{3}+5x^{2}+3)^{6} \cdot (-12x^{2}+10x)$


## Oppgave 5
#### a)
$(2x^{3}-4x^{2})^{5}$

$u=2x^{3}-4x^{2}$
$u'=6x^{2}-8x$

$f'(x)=u^{5}\cdot u'$
$5u^{4} \cdot u'$
$5(2x^{3}-4x^{2})^{4}\cdot (6x^{2}-8x)$

Svar: $5(2x^{3}-4x^{2})^{4}\cdot (6x^{2}-8x)$

#### b)
$f(x)=(\frac{2x-3}{2x-1})^{3}$
$u=\frac{2x-3}{2x-1}$
$u'=\frac{2(2x-1)-(2x-3)2}{(2x-1)^{2}}=\frac{-4}{(2x-1)^{2}}$


$f'(x)=3u^{2}\cdot (u')$
$f'(x)=3(\frac{2x-3}{2x-1})^{2}\cdot \frac{-4}{(2x-1)^{2}}$
$f'(x)=\frac{3\cdot(2x-3)^{2}}{(2x-1)^{2}}\cdot \frac{-4}{(2x-1)^{2}}$
$f'(x)=\frac{12(2x-3)^{2}}{(2x-1)^{4}}$

Svar: $\frac{12(2x-3)^{2}}{(2x-1)^{4}}$

#### c)
$f(x)=\frac{1}{\cos x}$

$\frac{1}{u(x)}=-\frac{u'(x)}{u(x)^{2}}$

$f'(x)=-\frac{-\sin x}{(\cos x)^{2}}$
$f'(x)=\frac{\sin x}{(\cos x)^{2}}$

Svar: $\frac{\sin x}{(\cos x)^{2}}$

#### d)
$f(x)=\frac{\cos^{2}x}{\sin x}=\frac{(\cos x)^{2}}{\sin x}$
$a=(\cos x)^{2}$
$b=\sin x$

$u=\cos x$
$u'=-\sin x$

$f'(x)=\frac{a'\cdot u' \cdot b-a\cdot b'}{b^{2}}$
$f'(x)=\frac{2\cos x(-\sin x)\sin x-(\cos x)^{2}\cdot \cos x}{(\sin x)^{2}}$
$f'(x)=\frac{2\cos x-(\sin x)^{2}-(\cos x)^{3}}{(\sin x)^{2}}$

#### e)
$f(x)=x^{4}\cdot \arccos x$

$f'(x)=4x^{3}\cdot \arccos x+x^{4}\cdot - \frac{1}{\sqrt{ 1 - x^{2} }}$
$f'(x)=4x^{3}\cdot \arccos x - \frac{x^{4}}{\sqrt{ 1 - x^{2} }}$

Svar: $4x^{3}\cdot \arccos x - \frac{x^{4}}{\sqrt{ 1 - x^{2} }}$

#### f)
$f(x)=\frac{\sqrt{ \cos(3x^{2}) }\cdot \sin ^{3}4x}{e^{x}}$

$\ln f(x)=\ln (\frac{\sqrt{ \cos(3x^{2}) }\cdot \sin ^{3}4x}{e^{x}})$
$\ln f(x)=\ln(\sqrt{ \cos(3x^{2}) }\cdot \sin ^{3}4x)-\ln e^{x}$,               tar vekk deletegnet 
$\ln f(x)=\ln(  (\cos(3x^{2}))^{1/2}   \cdot (\sin 4x)^{4}    )-\ln e^{x}$,         tar vekk roten
$\ln f(x)=\ln(\cos(3x^{2}))^{1/2}) +  \ln(\sin 4x)^{4} -\ln e^{x}$,      putter ln inn i parentesen
$\ln f(x)=    \frac{1}{2}\ln \cos(3x^{2})+4\ln \sin (4 x)-\ln e^{x}$,          putter graden foran ln
$\ln f(x)=    \frac{1}{2}\ln \cos(3x^{2})+4\ln \sin (4 x)-x$,               forenkler $\ln e^{x}$

Høyreside
$\frac{1}{f'(x)}\cdot f(x)$

Venstreside
$-\frac{1}{2}\cdot \frac{1}{\cos 3x^{2}}\cdot (\cos 3x^{2})' \cdot (3x^{2})'      +4 \frac{1}{\sin 4x}\cdot (\sin 4x)' \cdot (4x)' -1$
$-\frac{1}{2}\cdot \frac{1}{\cos 3x^{2}}\cdot -\sin 3x^{2} \cdot 6x     +4 \frac{1}{\sin 4x}\cdot \cos 4x \cdot 4 -1$

$f'(x)=(  -\frac{3x \sin 3x^{2}}{\cos 3x^{2}} + \frac{12 \cos 4x}{\sin 4x}-1) \cdot f(x)$

Svar: $(  -\frac{3x \sin 3x^{2}}{\cos 3x^{2}} + \frac{12 \cos 4x}{\sin 4x}-1) \cdot f(x)$

#### g)
$f(x)=\frac{(x-2)^{4}(x+3)^{2/3}e^{x^{2}-x}}{(x-1)^{2}}$

$\ln f(x)=\ln(\frac{(x-2)^{4}(x+3)^{2/3}e^{x^{2}-x}}{(x-1)^{2}})$
$\ln f(x)=\ln((x-2)^{4}(x+3)^{2/3}e^{x^{2}-x})-\ln{(x-1)^{2}}$,                         Tar vekk deletegnet               
$\ln f(x)=\ln(x-2)^{4}+\ln(x+3)^{2/3}+\ln e^{x^{2}-x}-\ln{(x-1)^{2}}$,            Putter ln inn i parentesen   
$\ln f(x)=4\ln(x-2)+ \frac{2}{3} \ln(x+3)+   (x^{2}-x) \ln e   - 2\ln(x-1)$,     Putter graden foran ln  
$\ln f(x)=4\ln(x-2)+ \frac{2}{3} \ln(x+3)+   x^{2}-x   - 2\ln(x-1)$,              Forenkler $e^{x^{2}-x}$

$f'(x) = (\frac{4}{x-2}+ \frac{2}{3(x+3)}+2x-1-\frac{2}{x-1})    \cdot f(x)$

Svar: $(\frac{4}{x-2}+ \frac{2}{3(x+3)}+2x-1-\frac{2}{x-1})    \cdot f(x)$


## Oppgave 6
Fikk ikke løst denne.


## Oppgave 7
$f(36-1)=\sqrt{ 36 } -1\implies f(36-1)+f'(36)\cdot 1$
$f(x)=\sqrt{ x }=x^{1/3}, f'(x)=\frac{1}{2}x^{-1/2}=\frac{1}{2\sqrt{ x }}$
$\sqrt{ 36}-\frac{1}{2\sqrt{ 36 }} 1$
$6=\frac{1}{2\cdot 6}=6-0.08333=5.92$

Svar: $5.92$

## Oppgave 8
$f(x)=x^{3}\sin x$
$f'(x)=3x^{2}\sin x+x^{3}\cos x$

$f''(x)=6x\sin x+3x^{2}\cos x+3x^{2}\cos x+x^{3}(-\sin x)$
Trekker sammen: $f''(x)=-x^{3}\sin x+6x^{2}\cos x+6x\sin x$

$f'''(x)=-3x^{2}\sin x-x^{3}\cos x+12x\cos x-6x^{2}\sin x+6\sin x+6x\cos x$
Trekker sammen leddene:
$x^{2}\sin x: -9x^{2}\sin x$
$x^{3}\cos x:-x^{3}\cos x$
$x\cos x:18\cos x$
$\sin x:6\sin x$

$f'''(x)=-9x^{2}\sin x-x^{2}\cos x+18x\cos x+6\sin x$
Trekker sammen: $\sin x(2-3x^{2})3+x(18-x^{2})\cos x$

Svar: $\sin x(2-3x^{2})3+x(18-x^{2})\cos x$






