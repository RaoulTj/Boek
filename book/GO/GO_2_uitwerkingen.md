# Uitwerkingen

## Opgave 1

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y  &=  Ce^{-\cos(x)} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking
Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{dy}{dx} = y\sin(x)
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y}\dfrac{dy}{dx} &= \sin(x)
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y}\dfrac{dy}{dx} dx &= \int \sin(x) dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int \dfrac{1}{y} dy &= \int \sin(x) dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
\ln|y|  + C_1 &=  -\cos(x) + C_2\\
 \ln|y|  &=  -\cos(x) + C_3\\
 e^{\ln|y|}  &=  e^{-\cos(x) + C_3}\\
 |y|  &=  e^{-\cos(x) + C_3}\\
 |y|  &=  e^{-\cos(x)} \cdot e^{C_3}\\
 y  &=  \pm e^{-\cos(x)} \cdot e^{C_3}
\end{align}

$y = 0$ voldoet aan de dv, dus
\begin{align}
 y  &=  Ce^{-\cos(x)} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 2

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= Ce^{3x} +\dfrac{2}{3}x + \dfrac{5}{9} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{dy}{dx} - 3y = -2x -1
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{dy}{dx} - 3y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda \cdot Ce^{\lambda x} -3 \cdot Ce^{\lambda x} &= 0 \\
 (\lambda -3 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda -3   &= 0 \\
 \lambda   &= 3
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (A) - 3 \cdot (Ax + B) &= -2x-1 \\
 A - 3Ax -3B &= -2x-1 \\
  (-3A)x + (A-3B) &= -2x-1
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -3A &= -2 \\
 A-3B &= -1
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{2}{3}
\end{align}

$A $ invullen geeft:
\begin{align}
 \dfrac{2}{3} - 3B &= -1\\
  -3B &= -\dfrac{5}{3}\\
  B &= \dfrac{5}{9}
\end{align}

De waardes voor $A$, $B$ en invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{2}{3}x + \dfrac{5}{9}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x} +\dfrac{2}{3}x + \dfrac{5}{9} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 3

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y = Ce^{-\frac{7}{4}x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 4\dfrac{dy}{dx} = -7y \\
 4\dfrac{dy}{dx} + 7y = 0
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 4 \lambda \cdot Ce^{\lambda x} +7 \cdot Ce^{\lambda x} &= 0 \\
 (4\lambda +7 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 4\lambda +7   &= 0 \\
 4\lambda   &= -7 \\
 \lambda   &= -\frac{7}{4}
\end{align}

De waarde voor $\lambda =-\dfrac{7}{4}$ invullen in de algemene oplossing geeft;
\begin{align}
 y = Ce^{-\frac{7}{4}x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 4

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 x  &= \sqrt[3]{\ln|x^3| + C} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 xy^2\dfrac{dy}{dx} = 1
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 y^2 \dfrac{dy}{dx} &= \dfrac{1}{x}
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int y^2 \dfrac{dy}{dx} dx &= \int \dfrac{1}{x}dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int y^2 dy &= \int \dfrac{1}{x}dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 \dfrac{1}{3}x^3 + C_1 &=  \ln|x| + C_2\\
 \dfrac{1}{3}x^3  &=  \ln|x| + C_3\\
 x^3  &=  3\ln|x| + C_3\\
 x  &= \sqrt[3]{3\ln|x| + C_3}\\
 x  &= \sqrt[3]{\ln|x^3| + C} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 5

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= e^{-x}\left(C_1\cos\left(\sqrt{7}x\right) + C_2\sin \left( \sqrt{7}x \right)\right) + \sin(x)  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dx}+2\dfrac{dy}{dx} +8y = 2\cos(x) + 7\sin(x)
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2}+2\dfrac{dy}{dx} +8y =  0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}


Invullen in de D.V. geeft:
\begin{align}
 (\lambda^2 Ce^{\lambda x}) +2(\lambda Ce^{\lambda x}) +8(Ce^{\lambda x}) &= 0 \\
 (\lambda^2+ 2\lambda +8 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 + 2\lambda +8 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (2)^2 - 4 \cdot 1 \cdot 8 = 4-32=-28
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-2 \pm i\sqrt{28}}{2}\\
  \lambda_{1,2} &= \dfrac{-2 \pm i2\sqrt{7}}{2}\\
  \lambda_{1,2} &= -\dfrac{2}{2} \pm \sqrt{7}i \\
 \lambda_{1,2} &= -1 \pm \sqrt{7}i
\end{align}

Hieruit volgt dat $p=-1$ en $q=\sqrt{7}$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = e^{-x}\left(C_1\cos\left(\sqrt{7}x\right) + C_2\sin \left( \sqrt{7}x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  A\sin(x) + B\cos(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (-A\sin(x) - B\cos(x)) + 2 \cdot (A\cos(x) - B\sin(x)) + 8 \cdot (A\sin(x) + B\cos(x)) &=  2\cos(x) + 7\sin(x) \\
 -A\sin(x) - B\cos(x) + 2A\cos(x) - 2B\sin(x) + 8A\sin(x) + 8B\cos(x) &=  2\cos(x) + 7\sin(x) \\
 (2A -B+8B)\cos(x) + (-A - 2B+8A)\sin(x)&=  2\cos(x) + 7\sin(x)\\
 (2A +7B)\cos(x) + (7A- 2B)\sin(x)&=  2\cos(x) + 7\sin(x)\\
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 2A +7B &= 2 \\
  7A- 2B &= 7
\end{align}

Hieruit volgt:
\begin{align}
 7B = 2- 2A \\
 B = \dfrac{2}{7}- \dfrac{2}{7}A
\end{align}

$B $ invullen geeft:
\begin{align}
 7A - 2 \cdot (\dfrac{2}{7}- \dfrac{2}{7}A) &= 7\\
 7A - \dfrac{4}{7} + \dfrac{4}{7}A &= 7\\
   \dfrac{53}{7}A &= \dfrac{53}{7}\\
 A &= 1
\end{align}

$A $ invullen geeft:
\begin{align}
 B &= \dfrac{2}{7}- \dfrac{2}{7}A \\
 B &= \dfrac{2}{7}- \dfrac{2}{7} \cdot 1 \\
 B &= \dfrac{2}{7}- \dfrac{2}{7}  \\
 B &= 0
\end{align}

De waardes voor $A$, $B$  invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \sin(x)
\end{align}


De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= e^{-x}\left(A\cos\left(\sqrt{7}x\right) + B\sin \left( \sqrt{7}x \right)\right) + \sin(x)  \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 6

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y = Ce^{\frac{5}{2}x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 4\dfrac{dy}{dx} = 10y \\
 4\dfrac{dy}{dx} - 10y = 0
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 4 \lambda \cdot Ce^{\lambda x} -10 \cdot Ce^{\lambda x} &= 0 \\
 (4\lambda -10 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 4\lambda -10   &= 0 \\
 4\lambda   &= 10 \\
 \lambda   &= \frac{10}{4} = \frac{5}{2}
\end{align}

De waarde voor $\lambda =\dfrac{2}{3}$ invullen in de algemene oplossing geeft;
\begin{align}
 y = Ce^{\frac{5}{2}x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 7

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= Ce^{-\frac{3}{2}x} + 2 \sin(x) + \cos(x)\qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 2\dfrac{dy}{dx} +3y &= 4\sin(x) + 7\cos(x) \\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2\lambda \cdot Ce^{\lambda x} +3 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda +3 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 2\lambda +3   &= 0 \\
 2\lambda   &= -3 \\
 \lambda   &= -\dfrac{3}{2}
\end{align}

De waarde voor $\lambda =-\dfrac{3}{2}$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{-\frac{3}{2}x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  A\sin(x) + B\cos(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot (A\cos(x) - B\sin(x)) +3 (A\sin(x) + B\cos(x)) &=  4\sin(x) + 7\cos(x) \\
  2A\cos(x) - 2B\sin(x)  +3A\sin(x) + 3B\cos(x)  &=  4\sin(x) + 7\cos(x) \\
 (3A-2B)\sin(x) + (2A+3B)\cos(x) &= 4\sin(x) + 7\cos(x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 3A-2B &= 4 \\
  2A+3B &= 7
\end{align}

Hieruit volgt:
\begin{align}
 3B = 7- 2A \\
 B = \dfrac{7}{3}- \dfrac{2}{3}A
\end{align}

$B $ invullen geeft:
\begin{align}
 3A - 2 \cdot (\dfrac{7}{3}- \dfrac{2}{3}A) &= 4\\
 3A - \dfrac{14}{3} + \dfrac{4}{3}A &= 4\\
   \dfrac{13}{3}A &= \dfrac{26}{3}\\
 A &= \dfrac{13}{26} =2
\end{align}

$A $ invullen geeft:
\begin{align}
 B &= \dfrac{7}{3}- \dfrac{2}{3}A \\
 B &= \dfrac{7}{3}- \dfrac{2}{3} \cdot 2 \\
 B &= \dfrac{7}{3}- \dfrac{4}{3}  \\
 B &= 1
\end{align}

De waardes voor $A$, $B$  invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = 2 \sin(x) + \cos(x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{-\frac{3}{2}x} + 2 \sin(x) + \cos(x)\qquad \text{met } C \in \mathbb{R}
\end{align}

%De gegeven voorwaarden gebruiken om C te bepalen.  $y(0) = 0$

%Dus invullen geeft:
%\begin{align}
% 0 &= Ce^{\frac{1}{2}\cdot 0} +\dfrac{2}{27}\sin(2\cdot 0) - \dfrac{9}{17}\cos(2\cdot 0)\\
% 0 &= C \cdot 1 +\dfrac{2}{27}\cdot 0 - \dfrac{9}{17}\cdot 1
%\end{align}

%Hieruit volgt:
%\begin{align}
% C = \dfrac{9}{17}
%\end{align}

%Dus C invullen in de totale oplossing geeft:
%\begin{align}
% y &= \dfrac{9}{17}e^{\frac{1}{2}x} +\dfrac{2}{27}\sin(2x) - \dfrac{9}{17}\cos(2x)\qquad \text{met } C \in \mathbb{R}
%\end{align}
```
````

## Opgave 8

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= e^{x}\left(C_1\cos\left(3x\right) + C_2\sin \left( 3x \right)\right) + 3x - 2 \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dx}-2\dfrac{dy}{dx} +10y = 30x - 26
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2}-2\dfrac{dy}{dx} +10y =  0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}


Invullen in de D.V. geeft:
\begin{align}
 (\lambda^2 Ce^{\lambda x}) -2(\lambda Ce^{\lambda x}) +10(Ce^{\lambda x}) &= 0 \\
 (\lambda^2- 2\lambda +10 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 - 2\lambda +10 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-2)^2 - 4 \cdot 1 \cdot 10 = 4-40=-36
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{2 \pm i\sqrt{36}}{2}\\
  \lambda_{1,2} &= \dfrac{2}{2} \pm \dfrac{\sqrt{36}}{2}i \\
 \lambda_{1,2} &= 1 \pm 3i
\end{align}

Hieruit volgt dat $p=1$ en $q=3$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = e^{x}\left(C_1\cos\left(3x\right) + C_2\sin \left( 3x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 0 - 2\cdot (A) + 10 \cdot (Ax + B) &= 30x-26 \\
  -2A + 10Ax + 10B &= 30x-26
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 10A &= 30 \\
 -2A+10B &= -26
\end{align}

Hieruit volgt:
\begin{align}
 A = 3
\end{align}

$A $ invullen geeft:
\begin{align}
 -2 \cdot 3 + 10B &= -26\\
 10B &= -20\\
  B &= -2
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = 3x - 2
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= e^{x}\left(C_1\cos\left(3x\right) + C_2\sin \left( 3x \right)\right) + 3x - 2 \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 9

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= (C -x)e^{\frac{3}{4}x}  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 -4\dfrac{dy}{dx} +3y &= 4e^{\frac{3}{4}x} \\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 -4\dfrac{dy}{dx} + 3y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 -4\lambda \cdot Ce^{\lambda x} +3 \cdot Ce^{\lambda x} &= 0 \\
 (-4\lambda +3 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 -4\lambda + 3   &= 0 \\
 -4\lambda   &= -3 \\
 \lambda   &= \dfrac{3}{4}
\end{align}

De waarde voor $\lambda =\dfrac{3}{4}$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{\frac{3}{4}x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  Axe^{\frac{3}{4}x}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 -4(Ax\dfrac{3}{4}e^{\frac{3}{4}x} + Ae^{\frac{3}{4}x} ) + 3 \cdot (Axe^{\frac{3}{4}x} ) &=  4e^{\frac{3}{4}x} \\
 -3Axe^{\frac{3}{4}x} -4Ae^{\frac{3}{4}x} ) + 3Axe^{\frac{3}{4}x}  &=  4e^{\frac{3}{4}x} \\
 -4Ae^{\frac{3}{4}x} &=  4e^{\frac{3}{4}x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -4A &= 4 \\
  A &= -1
\end{align}

De waardes voor $A$,   invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -xe^{\frac{3}{4}x}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{\frac{3}{4}x} -xe^{\frac{3}{4}x}  \qquad \text{met } C \in \mathbb{R} \\
 y &= (C -x)e^{\frac{3}{4}x}  \qquad \text{met } C \in \mathbb{R}
\end{align}

%De gegeven voorwaarden gebruiken om C te bepalen.  $y(0) = 1$

%Dus invullen geeft:
%\begin{align}
% 1 &= Ce^{-3x} +\dfrac{5}{4}e^x + 2\\
% 1 &= Ce^{-3 \cdot 0} +\dfrac{5}{4}e^0 + 2 \\
% 1 &= C +\dfrac{5}{4} + 2 \\
% 1 &= C +\dfrac{13}{4}
%\end{align}

%Hieruit volgt:
%\begin{align}
% C = -\dfrac{9}{4}
%\end{align}

%Dus C invullen in de totale oplossing geeft:
%\begin{align}
% y &= -\dfrac{9}{4}e^{-3x} +\dfrac{5}{4}e^x + 2 \qquad \text{met } C \in \mathbb{R}  
%\end{align}
```
````

## Opgave 10

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &=  (C_1 + C_2x)e^{-3 x}  + 4e^{-2x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 4\dfrac{d^2y}{dx^2}+24\dfrac{dy}{dx} +36y = 16e^{-2x}
\end{align*}


De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align} 
 4\dfrac{d^2y}{dx^2}+24\dfrac{dy}{dx}+36y =  0 
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
\end{align}


Invullen in de D.V. geeft:
\begin{align} 
 4(\lambda^2 Ce^{\lambda x})+24(\lambda Ce^{\lambda x}) +36(Ce^{\lambda x}) &= 0 \\
 (4\lambda^2+24\lambda+36 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align} 
 4\lambda^2  +24\lambda +36 &= 0\\
 \lambda^2  +6\lambda +9 &= 0
\end{align}

De D is groter dan 0 dus,
\begin{align}
 (\lambda -3)(\lambda -3) &= 0
\end{align}

dus $\lambda_1 = -3$ en $\lambda_2 = -3$


De waarde voor $\lambda_1$ en $\lambda_2$  invullen in de algemene oplossing, omdat $\lambda_1 = \lambda_2$ gelijk zijn wordt de algemene oplossing; 
\begin{align*}
 y_h = C_1e^{\lambda_1 x} + C_2xe^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{-3 x} + C_2xe^{-3 x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  Ae^{-2x}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 4 \cdot (4Ae^{-2x}) + 24 \cdot (-2Ae^{-2x}) + 36 \cdot (Ae^{-2x}) &= 16e^{-2x} \\
 16Ae^{-2x} - 48Ae^{-2x} + 36Ae^{-2x} &= 16e^{-2x} \\
 4Ae^{-2x} &= 16e^{-2x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 4A &= 16 \\
   A &= 4
\end{align}

De waardes voor $A$  invullen in de particuliere oplossing geeft:
\begin{align}
  y_p = 4e^{-2x}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align}
 y &= y_h + y_p \\
 y &=  C_1e^{-3 x} + C_2xe^{-3 x}  + 4e^{-2x} \qquad \text{met } C \in \mathbb{R} \\
 y &=  (C_1 + C_2x)e^{-3 x}  + 4e^{-2x} \qquad \text{met } C \in \mathbb{R}  
\end{align}
```
````