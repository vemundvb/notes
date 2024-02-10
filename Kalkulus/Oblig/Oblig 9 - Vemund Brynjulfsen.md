
$\int_{0}^{\pi} \sin x \, dx$

### a)
$\nabla x=\frac{\pi}{6}$

$x_{0}=0$
$x_{1}=\frac{\pi}{6}$
$x_{2}=\frac{\pi}{3}$
$x_{3}=\frac{\pi}{2}$
$x_{4}=\frac{2 \pi}{3}$
$x_{5}=\pi$

$\frac{\pi}{6}(\sin(\frac{0+\frac{\pi}{6}}{2})+ \sin(\frac{\frac{\pi}{6}+\frac{\pi}{3}}{2})+ \sin(\frac{\frac{\pi}{3}+\frac{\pi}{2}}{2})+ \sin(\frac{\frac{\pi}{2}+\frac{2\pi}{3}}{2})+ \sin(\frac{\frac{2\pi}{3}+\frac{\pi}{1}}{2})$
1.779072

### b)
$n=6$

$\frac{\nabla x}{ 2}= \frac{\pi}{12}$

$\frac{\pi}{12} (0+ 2 \frac{\pi}{6} + 2 \frac{\pi}{3} 2 \frac{\pi}{2} + 2\frac{2\pi}{3} +\pi)$

$\frac{\pi}{12} (\sin(0)+ 2\sin( \frac{\pi}{6}) + 2\sin( \frac{\pi}{3})+2\sin(  \frac{\pi}{2}) +2\sin( \frac{2\pi}{3}) +\sin(\pi))$
$1.692298$

### c)

$\frac{\pi}{6}(0+4 \sin(\frac{\pi}{6})+ 2 \sin(\frac{\pi}{3})+ 4 \sin( \frac{\pi}{2}) + 2 \sin(\frac{2\pi}{3})+\sin(\pi))$
4.955392

### d)
$\int_{0}^{\pi} \sin x \, dx$

$[-\cos x]_{0}^{\pi}=-\cos \pi +\cos0=2$

Den nærmeste verdien er fra rektangelmetoden.

## Oppgave 2
### a)
$\int_{0}^{3} \frac{t}{\sqrt{ 9-t^{2} }} \, dt$

Dette blir som: $\int_{0}^{\infty} \frac{t}{\sqrt{ 9-t^{2} }} \, dt$
Man kan gå rett frem å løse denne.

$u=9-t^{2}$
$\frac{du}{dt}=-2t$
$dt=-\frac{1}{2t}$

$\int \frac{t}{\sqrt{ u }} (-\frac{1}{2t})$
$\int \frac{-t}{2t \sqrt{ u }}$
$\int -\frac{1}{2 \sqrt{ u }}$
$-\frac{1}{2} \int \frac{1}{\sqrt{ u }}$

$-\frac{1}{2} \cdot 2\sqrt{ u }+C$
$- \sqrt{ u }+C$
$-\sqrt{ 9-t^{2} }+C$

$[-\sqrt{ 9-t^{2} }]_{0}^{3}=(-\sqrt{ 9-3^{2} })-(-\sqrt{ 9-0^{2} })=\sqrt{ 9 }=3$

Svar:
$3$

### b)
$\int_{0}^{1} x^{2} \cdot \ln x \, dx$

Denne er uløselig under 0.
Løser denne rett fram

$u'=x^{2} \to u=\frac{x^{3}}{3}$
$v=\ln x \to v'=\frac{1}{x}$

$\frac{x^{3}}{3} \ln x-\int \frac{1}{x} \frac{x^{3}}{3} \, dx=\frac{x^{3}}{3} \ln x-\int \frac{x^{2}}{3} \, dx$
$\frac{x^{3}}{3} \ln x-\frac{1}{3} \int x^{2} \, dx=\frac{x^{3}\ln x}{3}-\frac{1}{3}\cdot \frac{x^{3}}{3}+C$
$\frac{x^{3}\ln x}{3}-\frac{x^{3}}{9}+C$

$\left[ \frac{x^{3}\ln x}{3}-\frac{x^{3}}{9} \right]_{0}^{1}=\frac{1^{3}\ln 1}{3}-\frac{1^{3}}{9}-\frac{0^{3}\ln x}{0}-\frac{0^{3}}{9}=-\frac{1}{9}$

Svar:
$-\frac{1}{9}$

### c)
$\int_{0}^{2} \frac{1}{x^{2}-1}  \, dx$

Denne blir uendelig ved $\pm1$
Må derfor splitte funksjonen for før og etter 1.
$\int_{0}^{1} \frac{1}{x^{2}-1}  \, dx+\int_{1}^{2} \frac{1}{x^{2}-1}  \, dx$

$\int \frac{1}{x^{2}-1} \, dx$

$u=x^{2}-1$
$\frac{du}{dx}=2x$
$dx=\frac{1}{2x}du$

$\int \frac{1}{u} \frac{1}{2x}du$
$\int \frac{1}{2ux} \, du$
$\frac{1}{2} \int \frac{1}{ux} \, dx$

Vet ikke..
Men etter å ha løst integralet ville man gjort slik:
$[a]_{0}^{1}+[a]_{1}^{2}$



### d)
$\int_{0}^{\infty} 5^{-x}  \, dx$

$\int 5^{-x} \, dx$

$u=-x$
$\frac{du}{dx}=-1$
$dx=-1 du$

$-\int 5^{u} \, du$

$-\frac{5^{-x}}{\ln5}+C$
$-\frac{1}{\ln(5)\cdot 5^{x}}+C$

$-\frac{1}{\ln5\cdot 5^{0}}=-\frac{1}{\ln 5}$

Svar:
$- \frac{1}{\ln 5}$


### e)
$\int^{0}_{-\infty} \frac{1}{1-x}  \, dx$

$u=1-x$
$\frac{du}{dx}=-1$
$dx=-1 du$

$-\int \frac{1}{u}  du$
$-\ln|x|+C$
$-\ln | 0 | = \infty$
Integralet divergerer.

Svar:
Integralet divergerer

### f)
$\int_{-\infty}^{\infty} x\cdot e^{-x^{2}} \, dx$

$u'=x \to u=\frac{x^{2}}{2}$
$v=e^{-x^{2}} \to v'=-2xe^{-x^{2}}$

$x e^{-x^{2}} - \int x \cdot -2xe^{-x^{2}} \, dx$
$xe^{-x^{2}}+2\int x^{2} e^{-x^{2}} \, dx$

$xe^{-x^{2}}=-2\int x^{2} e^{-x^{2}} \, dx$
$-\frac{xe^{-x^{2}}}{2}=\int x^{2} e^{-x^{2}} \, dx$

Jeg tror ligningen $x\cdot e^{-x^{2}}$ går mot uendelig når $x=0$. Putter derfor $x=0$ inn i den integrerte ligningen:
$-\frac{0e^{-0^{2}}}{2}=0$

Svar:
0

## Oppgave 3
### a)
$y'-7y=0$

KL: $\lambda - 7=0$
KR: $\lambda = 7$

Generell løsning:
$y=Ce^{7x}$

### b)
$y'' + y' - 6y = 0$

KL: $\lambda^{2} + \lambda - 6=0$

$\lambda= \frac{- 1 \pm \sqrt{ 1^{2} - 4\cdot 1\cdot -6 }}{2\cdot 1}$
$\frac{-1 \pm 5}{2} = 2, -3$
$\lambda_{1}=2$
$\lambda_{2} =-3$

Generell løsning:
$y=C_{1} e^{2x} + C_{2} e^{-3x}$

### c)
$y''+6y'+9y=0$

KL: $\lambda^{2} + 6 \lambda + 9$

$\lambda= \frac{-6 \pm \sqrt{ 6^{2} - 4\cdot 1\cdot 9 }}{2\cdot 1}$
$\lambda=-3$

Generell løsning:
$y= C_{1} e^{-3x}+C_{2} xe^{-3x}$






