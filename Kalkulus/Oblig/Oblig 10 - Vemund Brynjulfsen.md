


## Oppgave 1

Differanseligning av 2 orden, med konstante koeffisienter


$y'' + 4y' + 13y=0$


Karakteristisk løsning:
$\lambda^{2} + 4 \lambda +13$

Finner $\lambda$
$\lambda= \frac{ -4 \pm \sqrt{ 4^{2} - 4\cdot 1 \cdot 13 }  }{2\cdot 1}$
$=\frac{-4 \pm -6i }{2}$

Det under roten er negativt, så man får to komplekse løsninger.
$\lambda_{1}= -2 + 3i$
$\lambda_{2}= -2 - 3i$

$\alpha = -2$
$\beta i = 3 i$

Generell løsning blir da:
$y = e^{-2x}(C_{1} \cos 3 x + C_{2} \sin 3 x)$


## Oppgave 2

$y'' + 5y' - 6y = 0$
$y(0)=7$ og $y'(0)=-7$


$\lambda^{2} + 5 \lambda - 6$


$\lambda = \frac{  -5 \pm \sqrt{ 5^{2} - 4\cdot 1\cdot -6 } }{ 2\cdot 1 }$
$=\frac{-5 \pm 7}{2}$

$\lambda_{1}=1$
$\lambda_{2}=-6$

Generell løsning
$C_{1} e^{1 x} + C_{2} e^{-6 x}=0$

Initialbetingelsen:
$y(0)=7$ og $y'(0)=-7$

$y(0)=7$
$C_{1} + C_{2} = 7$

$y'(0)=-7$
$C_{1} e^{x} - C_{2} 6 e^{-6}$
$C_{1} - 6C_{2} =-7$

$C_{2} = 2$
$C_{1} = 5$


$2 e^{x}+ 5 e^{-6x}$


## Oppgave 3

$y'' - 4y' + 5y = 0$
$y(0)=3, y'(0)=6$

$\lambda^{2} - 4 \lambda + 5=0$


$\lambda= \frac{  4 \pm \sqrt{ -4^{2} - 4\cdot 1\cdot 5 } }{2\cdot 1}$
$=\frac{4 \pm -2i}{2}$


$\alpha = 2$
$\beta i = i$

Generell løsning:
$e^{2x} (C_{1} \cos x + C_{2} \sin x)$


Initialbetingelser:
$y(0)$

$e^{2 \cdot 0} (C_{1} \cos 0 + C_{2} \sin 0)=3$
$C_{1} \cdot 1 + C_{2} \cdot 0 = 3$
$C_{1} = 3$

$y'(0)$


$(e^{2x} (C_{1} \cos x + C_{2} \sin x))'$

$e^{2x} \cdot (( 2C_{2}-C_{1}) \sin x + (C_{2} + 2 C_{1}) \cos x))$
$e^{20} \cdot (( 2C_{2}-C_{1}) \sin 0 + (C_{2} + 2 C_{1}) \cos 0))=6$
$1\cdot (( 0 + C_{2} + 2C_{1}))=6$
$C_{2}+2C_{1}=6$

$C_{2}+2\cdot3 = 6$
$C_{2} = 0$

$C_{1} = 3$
$C_{2} = 0$


$e^{2x} (3 \cos x + 0 \sin x)$

$e^{2x}3 \cos x$


## Oppgave 4

$25y'' = 4y$


$25y'' - 4y + 0y$


$25 \lambda^{2} - 4\lambda + 0 \lambda$


$\lambda = \frac{ 4 \pm \sqrt{ -4^{2} - 4\cdot 25 \cdot 0 }}{ 2\cdot 25}$


$\frac{4 \pm -116 i}{ 50}$

Vet ikke hvordan man skal fortsette...


## Oppgave 5

$y'-2y=4e^{2x}$ 
$y(0)=6$

THL: $y'-2y=0$
KL: $\lambda-2=0$
$KR: \lambda=2$

$y_{h}=C_{1}e^{2x}$
---
Deriverer 1 gang:
$y=K_{1}e^{x}$
$y'=K_{1}e^{x}$

Setter inn
$K_{1}e^{x}-2K_{1}e^{x}=4e^{2x}$
$K_{1}=-4$

$y=y_{h}+y_{p}=C_{1} e^{2x}-4e^{2x}$


$y(0)=C_{1}e^{2\cdot 0} - 4e^{2\cdot0}=6$

Her får man at $K=10$, noe som ikke stemmer med fasiten.
I fasiten står det $K=6$. Det får man hvis det er en $x$ ved siden av $4$.
Men jeg får ikke ligningen til å bli på den måten.

$10 e^{2x}-4e^{2x}=0\to6e^{2x}$



## Oppgave 6

$y''-3y'=18e^{3t}$

KL: $\lambda^{2}-3\lambda=0$
KR: $\lambda_{0}=0$, $\lambda_{1}=3$


$y_{h}=C_{1}e^{0\cdot t}+C_{2}e^{3t}\to C_{1}+C_{2}e^{3t}$


$y=K_{1} t e^{3t}$
$y'=K_{1} e^{3t} + K_{1}t \cdot3e^{3t}$
$y''=9K_{1}te^{3t}+3K_{1}e^{3t}$

Setter inn
$9K_{1}te^{3t}+3K_{1}e^{3t} - 3(K_{1} e^{3t} + K_{1}t \cdot3e^{3t})=18e^{3t}$

$9K_{1}te^{3t}+3K_{1}e^{3t} - 3K_{1} e^{3t} + 3K_{1}t \cdot3e^{3t}=18e^{3t}$



$9K_{1}te^{3t}+3K_{1}e^{3t} - 3K_{1} e^{3t} + 9K_{1}t e^{3t}=18e^{3t}$


$18K_{1}te^{3t}=18e^{3t}$
























