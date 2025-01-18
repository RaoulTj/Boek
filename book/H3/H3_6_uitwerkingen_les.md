# 3.6 Uitwerkingen les 3

## Opgave 1


````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
  y  &=  C \cdot e^{-6x}  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 \dfrac{dy}{dx} + 6y \\
 \dfrac{dy}{dx} = -6y\\
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y}\dfrac{dy}{dx} &= -6 \qquad {\color{blue} \text{(1p)}}
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y}\dfrac{dy}{dx} dx &= \int -6 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int  \dfrac{1}{y} dy &= \int -6 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 \ln|y| + C_1 &=  -6x + C_2 \qquad {\color{blue} \text{(2p)}}\\
 \ln|y|  &=  -6x  + C_3\\
 e^{\ln|y|}  &=  e^{-6x + C_3}\\
 |y|  &=  e^{-6x + C_3}\\
 |y|  &=  e^{-6x} \cdot e^{C_3}\\
 y  &=  \pm e^{-6x} \cdot e^{C_3}
\end{align}

y=0 voldoet aan de dv dus,
\begin{align}
  y  &=  C \cdot e^{-6x}  \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````

## Opgave 2

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
  y  &=  C \cdot e^{13x}  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking
\begin{align*}
 \dfrac{dy}{dx} - 13y \\
 \dfrac{dy}{dx} = 13y\\
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y}\dfrac{dy}{dx} &= 13 \qquad {\color{blue} \text{(1p)}}
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y}\dfrac{dy}{dx} dx &= \int 13 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int  \dfrac{1}{y} dy &= \int 13 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 \ln|y| + C_1 &=  13x + C_2 \qquad {\color{blue} \text{(2p)}}\\
 \ln|y|  &=  13x  + C_3\\
 e^{\ln|y|}  &=  e^{13x + C_3}\\
 |y|  &=  e^{13x + C_3}\\
 |y|  &=  e^{13x} \cdot e^{C_3}\\
 y  &=  \pm e^{13x} \cdot e^{C_3}
\end{align}

y=0 voldoet aan de dv dus,
\begin{align}
  y  &=  C \cdot e^{13x}  \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````

## Opgave 3

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
  y  &=  C \cdot e^{2x}  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking
\begin{align*}
 3\dfrac{dy}{dx} - 6y \\
 3\dfrac{dy}{dx} = 6y\\
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{3}{y}\dfrac{dy}{dx} &= 6 \qquad {\color{blue} \text{(1p)}}
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{3}{y}\dfrac{dy}{dx} dx &= \int 6 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int  \dfrac{3}{y} dy &= \int 6 dx \qquad {\color{blue} \text{(1p)}}
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 3\ln|y| + C_1 &=  6x + C_2 \qquad {\color{blue} \text{(2p)}}\\
 3 \ln|y|  &=  6x  + C_3\\
 e^{\ln|y|}  &=  e^{2x + C_3}\\
 |y|  &=  e^{2x + C_3}\\
 |y|  &=  e^{2x} \cdot e^{C_3}\\
 y  &=  \pm e^{2x} \cdot e^{C_3}
\end{align}

y=0 voldoet aan de dv dus,
\begin{align}
  y  &=  C \cdot e^{2x}  \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````

## Opgave 4

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= Ce^{7x} - \dfrac{2}{7}x^2 - \dfrac{32}{49}x - \dfrac{32}{343} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 \dfrac{dy}{dx} - 7y = 2x^2 + 4x
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{dy}{dx} - 7y = 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda \cdot Ce^{\lambda x} -7 \cdot Ce^{\lambda x} &= 0 \\
 (\lambda -7 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 \lambda -7   &= 0  \qquad {\color{blue} \text{(1p)}} \\
 \lambda   &= 7 \qquad {\color{blue} \text{(1p)}}
\end{align}

De waarde voor $\lambda =7$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{7x} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax^2 + Bx + D \qquad {\color{blue} \text{(1p)}}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = 2Ax + B
\end{align}


Invullen in de D.V. geeft:
\begin{align}
 (2Ax +B) - 7 \cdot (Ax^2 + Bx + D) &= 2x^2 + 4x \\
 (2Ax +B) - 7Ax^2 - 7Bx - 7D&= 2x^2+ 4x \\
  7Ax^2 +(2A-7B)x + (B-7D) &= 2x^2 + 4x \qquad {\color{blue} \text{(1p)}}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -7A &= 2 \\
 2A-7B &= 4 \\
 B - 7D &= 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Hieruit volgt:
\begin{align}
 A = -\dfrac{2}{7} \qquad {\color{blue} \text{(1p)}}
\end{align}

$A $ invullen geeft:
\begin{align}
 2 \cdot -\dfrac{2}{7} - 7B &= 0\\
 -\dfrac{4}{7} - 7B &= 4\\
  -7B &= 4 + \dfrac{4}{7}\\
  -7B &= \dfrac{32}{7}\\
  B &= -\dfrac{32}{49} \qquad {\color{blue} \text{(1p)}}
\end{align}

$B $ invullen geeft:
\begin{align}
 -\dfrac{32}{49} - 7D &= 0\\
 7D &= -\dfrac{32}{49} \\
 D &= -\dfrac{32}{343} \qquad {\color{blue} \text{(1p)}}
\end{align}

De waardes voor $A$, $B$ en $D$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{2}{7}x^2 - \dfrac{32}{49}x - \dfrac{32}{343} \qquad {\color{blue} \text{(1p)}}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{7x} - \dfrac{2}{7}x^2 - \dfrac{32}{49}x - \dfrac{32}{343} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````

## Opgave 5

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= Ce^{-3x} + \dfrac{4}{3} e^{-3x} x  \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 3\dfrac{dy}{dx} +9y &= 4e^{-3x}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{dy}{dx} + 9y = 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3 \lambda \cdot Ce^{\lambda x} +9 \cdot Ce^{\lambda x} &= 0 \qquad {\color{blue} \text{(1p)}} \\
 (3\lambda +9 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 3\lambda + 9   &= 0 \\
 3\lambda   &= -9\\
 \lambda   &= -\dfrac{9}{3} = -3 \qquad {\color{blue} \text{(1p)}}
\end{align}

De waarde voor $\lambda =-3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{-3x} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{-3x} 
\end{align}

Gelijk aan homogene oplossing dus kies,
\begin{align}
 y_p = Ae^{-3x} \cdot x \qquad {\color{blue} \text{(1p)}}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = -3Ae^{-3x} \cdot x + Ae^{-3x} \cdot 1
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3 ( -3Ae^{-3x}x + Ae^{-3x} \cdot 1)   + 9 ( Ae^{-3x}x) = 4e^{-3x} \\
 -9Ae^{-3x}x + 3Ae^{-3x} + 9Ae^{-3x}x = 4e^{-3x}\\
 3Ae^{-3x} = 4e^{-3x} \qquad {\color{blue} \text{(1p)}}
\end{align}

De coëefficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  3A &= 4 \\
    A &= \dfrac{4}{3} \qquad {\color{blue} \text{(1p)}}
\end{align}


De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{4}{3} e^{-3x} x \qquad {\color{blue} \text{(1p)}}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{-3x} + \dfrac{4}{3} e^{-3x} x  \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````

## Opgave 6

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:

\begin{align*}
 y &= Ce^{\dfrac{5}{3}x} -\dfrac{5}{106}\sin(x) -\dfrac{9}{106}\cos(x) - \dfrac{2}{5} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 3\dfrac{dy}{dx} - 5y &= 2 + \sin(3x)\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{dy}{dx} - 5y = 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3\lambda \cdot Ce^{\lambda x} -5 \cdot Ce^{\lambda x} &= 0 \\ \qquad {\color{blue} \text{(1p)}}
 (3\lambda -5 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 3\lambda -5   &= 0 \\
 3\lambda   &= 5 \\
 \lambda   &= \dfrac{5}{3} \qquad {\color{blue} \text{(1p)}}
\end{align}

De waarde voor $\lambda =\dfrac{5}{3}$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{\dfrac{5}{3}x} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = A\sin(3x) + B\cos(3x) + D \qquad {\color{blue} \text{(1p)}}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = 3A\cos(x) - 3B\sin(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3(3A\cos(x) - 3B\sin(x)) - 5( A\sin(3x) + B\cos(3x) + D)  &= 2 + \sin(3x) \\
 9A\cos(3x) - 9B\sin(3x) - 5A\sin(3x) - 5B\cos(3x) - 5D  &= 2+ \sin(3x) \\
 (-9B-5A)\sin(x) + (9A-5B)\cos(x) - 5D &= 2 + \sin(3x) \qquad {\color{blue} \text{(1p)}}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -9B-5A &= 1 \\
  9A-5B &= 0 \\
  -5D &= 2 \qquad {\color{blue} \text{(1p)}}
\end{align}

Hieruit volgt:
\begin{align}
 D = -\dfrac{2}{5} \qquad {\color{blue} \text{(1p)}}
\end{align}

Hieruit volgt:
\begin{align}
 B = \dfrac{9}{5}A
\end{align}

$B $ invullen geeft:
\begin{align}
 -9(\dfrac{9}{5}A) - 5A &= 1\\
 -\dfrac{81}{5}A - \dfrac{25}{5}A &= 1\\
  -\dfrac{81}{5}A - \dfrac{25}{5}A &= 1\\
 -\dfrac{106}{5}A &= 1\\
  A &= -\dfrac{5}{106} \qquad {\color{blue} \text{(1p)}}
\end{align}

$A $ invullen geeft:
\begin{align}
 B &= \dfrac{9}{5}A \\
 B &= \dfrac{9}{5}\cdot -\dfrac{5}{106} \\
 B &= -\dfrac{9}{106} \qquad {\color{blue} \text{(1p)}}
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{5}{106}\sin(x) -\dfrac{9}{106}\cos(x) - \dfrac{2}{5} \qquad {\color{blue} \text{(1p)}}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{\dfrac{5}{3}x} -\dfrac{5}{106}\sin(x) -\dfrac{9}{106}\cos(x) - \dfrac{2}{5} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}
```
````
