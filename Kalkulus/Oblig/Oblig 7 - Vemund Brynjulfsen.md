## Oppgave 1
### a)
$\int \frac{5}{\sqrt{ 4-2x^{2} }} \, dx$
$5 \int \frac{1}{\sqrt{ 4-2x^{2} }} \, dx$

$\sqrt{ 4-2x^{2} }=\sqrt{ 4 } \sqrt{ 1-\frac{1}{2}x^{2} }$

$u^{2}=\frac{1}{2}x^{2}$
$u=\frac{1}{\sqrt{ 2 }}x$

$\frac{du}{dx}=\frac{1}{\sqrt{ 2 }}$
$dx=\sqrt{ 2 }du$

$5 \int \frac{1}{\sqrt{ 4 } \sqrt{ 1-u^{2} }} \, \sqrt{ 2 }du$
$5 \int \frac{1}{\sqrt{ 2 } \sqrt{ 1-u^{2} }} \, du$
$\frac{5}{\sqrt{ 2 }} \int \frac{1}{\sqrt{ 1-u^{2} }} \, du$
$\frac{5}{\sqrt{ 2 }} \arcsin \frac{x}{\sqrt{ 2 }}+C$


Svar:
$\frac{5}{\sqrt{ 2 }} \arcsin \frac{x}{\sqrt{ 2 }}+C$



### Oppgave 2

$\int \frac{1}{x^{2}+4x+13} \, dx$
$\int \frac{1}{(x+2)^{2}+9} \, dx$

$u=\frac{x+2}{3}$
$dx=3du$

$\int \frac{3}{9u^{2}+9} \, dx$
$\frac{1}{3} \int \frac{1}{u^{2}+1} \, dx$
$\frac{1}{3} \arctan u$
$\frac{\arctan u}{3}$
$\frac{\arctan\left( \frac{x+2}{3} \right)}{3}+C$

Svar:
$\frac{\arctan\left( \frac{x+2}{3} \right)}{3}+C$


## Oppgave 3
### a)
$\int (3x-2)e^{x} \, dx$

$u'=e^{x} \to e^{x}$
$v=2x-2 \to v' =2$

$(3x-2)e^{x}-\int 2x e^{x} \, dx$

Må bruke delvis integrasjon igjen
$u'=e^{x}\to u= e^{x}$
$v=3x-2\to v'=3$

$(3x-2)e^{x}-\int 3e^{x} \, dx$
$(3x-2)e^{x}-3e^{x}$
$(3xe^{x}-2e^{x}-3e^{x})$
$3xe^{x}-5e^{x}$
$(3x-5)e^{x}+C$

Svar:
$(3x-5)e^{x}+C$



### b)
$\int x^{2}e^{x} \, dx$

$u'=e^{x}\to u=e^{x}$
$v=x^{2}\to v'=2x$

$x^{2}e^{x}-\int 2xe^{x} \, dx$

$u=e^{x}\to u'=e^{x}$
$v=2x\to v'=2$

$x^{2}e^{x}-2xe^{x}-\int 2e^{x} \, dx$
$x^{2}e^{x}-2xe^{x}-2e^{x}+C$

$(x^{2}-2x-2)e^{x}+C$

Svar:
$(x^{2}-2x-2)e^{x}+C$



### c)
$\int (2x^{2}-3x)\cos x \, dx$

$u'=\cos x \to u=\sin x$
$v=(2x^{2}-3x)\to v'=4x-3$

$(2x^{2}-3x)\sin x-\int (4x-3)\sin x \, dx$

$u'=\sin x\to u=-\cos x$
$v=4x-3\to v'=4$

$(2x^{2}-3x)\sin x-(4x-3)(-\cos x)-\int -4\cos x \, dx$

$(2x^{2}-3x)\sin x-(4x-3)(-\cos x)-4\int \cos x \, dx$
$(2x^{2}-3x)\sin x-(4x-3)(-\cos x)-4\sin x+C$
$(2x^{2}-3x-4)\sin x+(4x-3)\cos x$

Svar:
$(2x^{2}-3x-4)\sin x+(4x-3)\cos x$


### d)
$\int \ln(x+1) \, dx$

$u=x+1$
$\frac{du}{dx}=1$
$1du=dx$

$\int \ln u \, 1du$

$u'=1\to u=u$
$v=\ln u\to v'=\frac{1}{u}$

$\ln u\cdot u-\int \frac{1}{u}\cdot u \, du=\ln u\cdot u-\int 1 \, dx$
$u\ln u-1$
$(x+1)\ln(x+1)-x+C$

Svar:
$(x+1)\ln(x+1)-x+C$



### e)
$\int \arctan x \, dx$

$u=x$
$\frac{du}{dx}=1$
$1du=dx$

$\int \arctan u \, 1du$

$u'=1\to u=x$
$v=\arctan x\to v'=\frac{1}{x^{2}+1}$

$x\arctan x-\int \frac{1}{x^{2}+1}x \, dx$

$u=x^{2}+1$
$\frac{du}{dx}=2x$
$dx=\frac{1}{2x}du$

$u=2x$
$\frac{dx}{du}=2$
$\frac{1}{2}du=dx$

$\frac{1}{2}\int \frac{1}{u} \, du$
$=\frac{\ln u}{2}$
$=\frac{\ln(x^{2}+1)}{2}$

$x\arctan- \frac{\ln(x^{2}+1)}{2} +C$

Svar:
$x\arctan- \frac{\ln(x^{2}+1)}{2} +C$


### f)
$\int e^{x} \cos x \, dx$

$u'=e^{x}\to u=e^{x}$
$v=\cos x\to v'=-\sin x$

$e^{x}\cos x-\int -\sin xe^{x} \, dx$

$u'=e^{x}\to v=e^{x}$
$v=-\sin x=-\cos x$

$e^{x}\cos x-e^{x}(-\sin x)-\int e^{x}(\cos x) \, dx$

$\int e^{x}\cos x=e^{x}\cos x-e^{x}(-\sin x) -\int e^{x}\cos x \, dx$
$2\int e^{x}\cos x=e^{x}\cos x-e^{x}(-\sin x)+C$
$\int e^{x}\cos x=\frac{1}{2}(e^{x}\cos x-e^{x}(-\sin x))+C$

Svar:
$\frac{1}{2}e^{x}(\cos x+\sin x)+C$



### g)
$\int \cos (\ln x) \, dx$


$u=\ln x$
$\frac{du}{dx}=\frac{1}{x}$
$du=\frac{1}{x}dx$

$x=e^{x}$

$\int e^{u}\cos u \, du$

$a'=e^{u}\to a=e^{u}$
$b=\cos u\to b'=-\sin u$
$e^{u}\cos u-\int e^{u}(-\sin u) \, dx$

$a'=-\sin u\to a=-\cos u$
$b'=e^{u}\to b=e^{u}$

$e^{u}\cos u-e^{u}(-\sin u)+\int e^{u}\cos u \, dx$
$\int e^{u}\cos u \, dx=e^{u}\cos u-e^{u}(-\sin u)+\int e^{u}\cos u \, dx$

$\int e^{u}\cos u=\frac{1}{2}(e^{u}\cos u-e^{u}(-\sin u))+C$
$\frac{1}{2}(x\cos (\ln x)+x\sin (\ln x))+C$
$\frac{1}{2}x(\cos(\ln x)+\sin(\ln x))+C$


Svar:
$\frac{1}{2}x(\cos(\ln x)+\sin(\ln x))+C$



## Oppgave 4

$\int \frac{3x+3}{x^{2}-9} \, dx$

$x^{2}-9$
$x^{2}=9$
$x=\sqrt{ 9 }=\pm 3$

$x$ har to løsninger:
$x=3$ og $x=-3$

$\frac{3x+3}{x^{2}-9}=\frac{A}{x+3}+\frac{B}{x-3}$
$3x+3=A(x+3)+B(x-3)$

Setter inn for $x=3$
$3\cdot 3 + 3 = A(3+3)+B(3-3)$
$12=A 6$
$A=2$

Setter inn for $x=-3$
$3\cdot -3+3 = A(-3+3) + B(-3-3)$
$-6=-6B$
$-1=B$

$\frac{3x+3}{x^{2}-9}=\frac{2}{x+3}+ \frac{1}{x-3}$
$2\int \frac{1}{x+3} \, dx + \int \frac{1}{x-3} \, dx$

$u=x+3$
$\frac{du}{dx}=1$
$du=dx$

$i=x-3$
$\frac{di}{dx}=1$
$di=dx$

$2 \int \frac{1}{u} \, du+\int \frac{1}{i} \, di$
$2 \ln u + \ln i+C$
$2\ln(x-3)+\ln(x+3)+C$

Svar:
$2\ln(x-3)+\ln(x+3)+C$



### b)
$\frac{x^{2}+x+1}{x^{3}+x}$

$x^{3}+x=x(x^{2}+1)$

$\frac{x^{2}+x+1}{x^{3}+x}=\frac{A}{x}+\frac{B}{x^{2}+1}$
$x^{2}+x+1=A(x^{2}+1) + B(x)$

$x=0$
$1=A$

$x=1$
$3=2+B$
$1=B$

$\frac{x^{2}+x+1}{x^{3}+x}=\int \frac{1}{x} \, dx+\int \frac{1}{x^{2}+1} \, dx$
$=\ln x+\arctan x+C$

Svar:
$=\ln x+\arctan x+C$





## Oppgave 5
### a)
$\int_{1}^{2} (x^{3}-x^{2}) \, dx$
$=[\frac{1}{4}x^{4}-\frac{1}{3}x^{3}]_{1}^{2}$
$=(\frac{2^{4}}{4}-\frac{2^{3}}{3})-(\frac{1^{4}}{4}-\frac{1^{3}}{3})=\frac{17}{12}$

Svar:
$\frac{17}{12}$



Fikk ikke til oppgave 5b og 5c
### b)
$\int_{-4}^{-1} \frac{1}{1-4x} \, dx$



$u=1-4x$
$\frac{du}{dx}=-4$
$du=-4dx$
$-\frac{du}{4}=dx$


$\int_{-4}^{-1} \frac{1}{u} \, -\frac{1}{4}du=[\ln|1-4x|-\frac{x}{4}]_{-4}^{-1}$
$=(\ln|1-4(-1)|-\frac{-1}{4})-(\ln|1-4(-4)|-\frac{-4}{4})=0.026$



### c)
$\int_{1}^{e} x^{4} \cdot \ln x \, dx$
$(\ln x)'=\frac{1}{x}$
$x^{4}=\frac{x^{5}}{5}$











