## Oppgave 1
### a)
$z=f(x,y)=x^{3}y-x^{2}y^{2}$

$f_{x}=3x^{2}y-2xy^{2}$
$f_{y}=x^{3}-x^{2}2y$

### b)
$z=f(x,y)=x^{2}y-e^{2xy}$

$f_{x}=2xy-2e^{2xy}$
$f_{y}=x^{2}-e^{2xy}$



### c)

$z=f(x,y)=\arctan\left( \frac{x}{y} \right)$

$f_{x}=\frac{1}{1+ \left( \frac{x}{y} \right)^{2}}\cdot \frac{y}{y^{2}}$
$f_{y}=\frac{1}{1+\left( \frac{x}{y} \right)^{2}}\cdot - \frac{x}{y^{2}}$



### d)
$z=f(x,y)=\frac{1}{\sqrt{ x^{2}+y^{2} }}$

$f_{x}=(x^{2}+y^{2})^{-1/2}$
$f_{x}=-\frac{1}{2}(x^{2}+y^{2})\cdot 2x$
$f_{x}=-\frac{2x(x^{2}+y^{2})}{2}$
$f_{x}=-x(x^{2}+y^{2})$


$f_{y}=(x^{2}+y^{2})^{-1/2}$
$f_{y}=-\frac{1}{2}(x^{2}+y^{2})\cdot 2y$
$f_{y}=-\frac{2y(x^{2}+y^{2})}{2}$
$f_{y}=-y(x^{2}+y^{2})$



## Oppgave 2
$z=f(x,y)=\sin(\pi xy+\ln y)$

Punkt: $(0,1)$
tilnærmet verdi for funksjonsverdien i punktet $(0.01,1.05)$

$f(x+0.1,y+0.5)=f(x,y) + f_{x}(x,y)\cdot 0.1 + f_{y}(x,y)\cdot 0.5$

$f_{x}=\cos(\pi xy+\ln y)\cdot \pi y$
$f_{y}=\cos(\pi xy+\ln y)\cdot (\pi x+\frac{1}{y})$


$f_{x}(0,1)\cdot 0.1$
$=\cos(\pi \cdot 0\cdot 1 + \ln(0))\cdot \pi 1 \cdot 0.01$
$=1\cdot \pi \cdot 0.01$
$=\frac{\pi}{100}$

$f_{y}(0,1)\cdot 0.05$
$=\cos(\pi 0 \cdot 1 + \ln 1)\cdot \left( \pi 0 + \frac{1}{1} \right)\cdot 0.05$
$1\cdot 0.05$
$=0.05$

$f(0,1)=\sin(\pi 0 \cdot 1 + \ln1)$
$=0$



$0+0.05+\frac{\pi}{100}$
$=0.08$


Svar:
0.08




## Oppgave 3
$z=f(x,y)=e^{xy}\sin y$


$f_{x}=ye^{xy} \sin y + e^{xy} 0=ye^{xy}\sin y$
$f_{y}=xe^{xy} \sin y +e^{xy}\cos y$


$f_{xy}=1e^{xy}\sin y+y\cdot ye^{xy}\sin y+ye^{xy} \cos y$
$f_{xx}=0 e^{xy} \cos y+ y xe^{xy} \sin y+ ye^{xy} 0=yxe^{xy}\sin y$
$f_{yy}=0e^{xy}\sin y+xye^{xy}\sin y+xe^{xy} \cos y+ye^{xy} \cos y + e^{xy} \sin y$




## Oppgave 4
$z=f(x,y)=2x-8y-x^{2}-2xy^{2}$     $D_{f}=R^{2}$

$f_{x}=2-2x-2y^{2}$
$f_{y}=-8-4xy$

$f_{xx}=-2$
$f_{yy}=-4y$
$f_{xy}=-4y$



Finner $f_{x}=0$
$2-2y^{2}=2x$
$1-y^{2}=x$


$2-2x-2$


Finner $f_{y}=0$
$-8=4xy$
$-4=xy$
$-\frac{4}{x}=y$


Et kritisk punkt:
Fikk ikke til denne. ☹️
Skal se på løsningsforslaget






## Oppgave 5
### a)
$\int (2x^{3}-3x^{2}+4x-1) \, dx$

$\frac{2x^{5}}{5}-\frac{3x^{3}}{3}+\frac{4x^{2}}{2}-x$
$\frac{2}{5}x^{5}-x^{3}+2x^{2}-x$

Svar:
$\frac{2}{5}x^{5}-x^{3}+2x^{2}-x$


### b)
$\int (-\frac{5}{x^{4}}+\frac{1}{x^{2}}+\frac{1}{x}+\frac{2}{\sqrt{ x }}-3) \, dx$
$\int \left( -\frac{5}{x^{4}} \right) \, dx + \int (\frac{1}{x^{2}}) \, dx+\int \left( \frac{1}{x} \right) \, dx+\int \left( \frac{2}{\sqrt{ x }} \right) \, dx+\int 3 \, dx$
$-5\int \left( \frac{1}{x^{4}} \right) \, dx+\int \frac{1}{x^{2}} \, dx+\int \left( \frac{1}{x} \right) \, dx+2\int (1\sqrt{ x }) \, dx+\int 3 \, dx$
$\frac{5}{3}x^{-3}-\frac{1}{1}x^{-1}+\ln(|x|)+2\cdot2\sqrt{ x }+3x+C$
$\frac{5}{3}x^{-3}-x^{-1}+\ln(|x|)+4\sqrt{ x }+3x+C$


Svar:
$\frac{5}{3}x^{-3}-x^{-1}+\ln(|x|)+4\sqrt{ x }+3x+C$


### c)
$\int -4e^{x} \, dx$
$-4\int e^{x} \, dx$
$-4e^{x}+C$


Svar:
$-4e^{x}+C$


### d)
$\int 5^{x} \, dx$
$\frac{5^{x}}{\ln a}+C$

Svar:
$\frac{5^{x}}{\ln a}+C$





## Oppgave 6

### a)
$\int 9(4x-3)^{8} \, dx$

$u = 4x-3$
$\frac{du}{dx}=4$
$du=4dx$
$\frac{1}{4}du=dx$

$\int 9u^{8} \, \frac{1}{4}du$
$\frac{9}{4} \int u^{8} \, du$
$\frac{9}{4}\frac{1}{8+1}u^{8+1}+C$
$\frac{9}{4} \frac{1}{9} u^{9}+C$
$\frac{1}{4}u^{9}+C$
$\frac{1}{4}(4x-3)^{9}+C$

Svar:
$\frac{1}{4}(4x-3)^{9}+C$


### b)
$\int e^{2x} \, dx$

$u=2x$
$\frac{du}{dx}=2$
$du=2dx$
$\frac{1}{2}du=dx$

$\int e^{u} \, \frac{1}{2}du$
$\frac{1}{2} \int e^{u} \, du$
$\frac{1}{2} e^{u}+C$
$\frac{1}{2}e^{2x}+C$

Svar:
$\frac{1}{2}e^{2x}+C$



### c)
$\int \cos 4x \, dx$

$u=4x$
$\frac{du}{dx}=4$
$du=4dx$
$\frac{1}{4}du=dx$

$\int \cos u \, \frac{1}{4}du$
$\frac{1}{4} \int \cos u \, du$
$\frac{1}{4} \sin 4x+C$

Svar:
$\frac{1}{4} \sin 4x+C$


### d)
$\int xe^{x^{2}-1} \, dx$

$u=x^{2}-1$
$\frac{du}{dx}=2x$
$du=2x \, dx$
$\frac{1}{2x}du=dx$

$\int xe^{u} \, \frac{1}{2x}du$
$\frac{1}{2} \int e^{u} \, du$
$\frac{1}{2} e^{x^{2}-1}+C$

Svar:
$\frac{1}{2} e^{x^{2}-1}+C$


### e)
$\int (x-1)\sin (x^{2} -2x +1) \, dx$

$u=x^{2}-2x+1$
$\frac{du}{dx}=2x-2$
$du=(2x-2)dx$
$\frac{1}{2x-2}du=dx$

$(x-1) \int \sin u \, \frac{1}{2x-2}du$
$\frac{x-1}{2x-2} \int \sin u \, du$
$-\frac{1}{2} \int \sin u \, du$
$-\frac{1}{2} \cos(x^{2}-2x+1)+C$

Svar:
$-\frac{1}{2} \cos(x^{2}-2x+1)+C$



### f)
$\int \frac{\sin \sqrt{ x }}{\sqrt{ x }} \, dx$

$u=\sqrt{ x }$
$\frac{du}{dx}=2\sqrt{ x }$
$dx=\frac{1}{2\sqrt{ x }}du$

$\int \frac{\sin u}{u} \, \frac{1}{2\sqrt{ x }}du$
$2 \int \sin u \, du$
$-2\cos (\sqrt{ x })+C$

Svar:
$-2\cos (\sqrt{ x })+C$



### g)
$\int e^{-3\cos x}\sin x \, dx$

$u=-3\cos x$
$\frac{du}{dx}=0\cos x+3\sin x=3\sin x$
$dx=\frac{1}{3\sin x}$

$\int e^{-3\cos x}\sin x \, \frac{1}{3\sin x}du$
$\frac{\sin x}{3\sin x} \int e^{-3\cos x} \, du$
$\frac{1}{3} e^{-3\cos x}+C$

Svar:
$\frac{1}{3} e^{-3\cos x}+C$













