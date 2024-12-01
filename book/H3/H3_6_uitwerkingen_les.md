# 3.6 Uitwerkingen les 3

## Opgave 1

```{admonition} Uitwerkingen
:class: dropdown

\begin{align*}
 \dfrac{dy}{dx} - 7y = 2x^2 + 4x
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{dy}{dx} - 7y = 0
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
 \lambda -7   &= 0 \\
 \lambda   &= 7
\end{align}

De waarde voor $\lambda =7$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{7x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax^2 + Bx + D
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = 2Ax + B
\end{align}


Invullen in de D.V. geeft:
\begin{align}
 (2Ax +B) - 7 \cdot (Ax^2 + Bx + D) &= 2x^2 + 4x \\
 (2Ax +B) - 7Ax^2 - 7Bx - 7D&= 2x^2+ 4x \\
  7Ax^2 +(2A-7B)x + (B-7D) &= 2x^2 + 4x
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -7A &= 2 \\
 2A-7B &= 4 \\
 B - 7D &= 0
\end{align}

Hieruit volgt:
\begin{align}
 A = -\dfrac{2}{7}
\end{align}

$A $ invullen geeft:
\begin{align}
 2 \cdot -\dfrac{2}{7} - 7B &= 0\\
 -\dfrac{4}{7} - 7B &= 4\\
  -7B &= 4 + \dfrac{4}{7}\\
  -7B &= \dfrac{32}{7}\\
  B &= -\dfrac{32}{49}
\end{align}

$B $ invullen geeft:
\begin{align}
 -\dfrac{32}{49} - 7D &= 0\\
 7D &= -\dfrac{32}{49} \\
 D &= -\dfrac{32}{343}
\end{align}

De waardes voor $A$, $B$ en $D$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{2}{7}x^2 - \dfrac{32}{49}x - \dfrac{32}{343}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{7x} - \dfrac{2}{7}x^2 - \dfrac{32}{49}x - \dfrac{32}{343} \qquad \text{met } C \in \mathbb{R}
\end{align}
```

## Opgave 2

```{admonition} Uitwerkingen
:class: dropdown

\begin{align*}
 3\dfrac{dy}{dx} +9y &= 4e^{-3x}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{dy}{dx} + 9y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3 \lambda \cdot Ce^{\lambda x} +9 \cdot Ce^{\lambda x} &= 0 \\
 (3\lambda +9 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 3\lambda + 9   &= 0 \\
 3\lambda   &= -9\\
 \lambda   &= -\dfrac{9}{3} = -3\\
\end{align}

De waarde voor $\lambda =-3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{-3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{-3x}
\end{align}

Gelijk aan homogene oplossing dus kies,
\begin{align}
 y_p = Ae^{-3x} \cdot x
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = -3Ae^{-3x} \cdot x + Ae^{-3x} \cdot 1
\end{align}



Invullen in de D.V. geeft:
\begin{align}
 3 ( -3Ae^{-3x}x + Ae^{-3x} \cdot 1)   + 9 ( Ae^{-3x}x) = 4e^{-3x} \\
 -9Ae^{-3x}x + 3Ae^{-3x} + 9Ae^{-3x}x = 4e^{-3x}\\
 3Ae^{-3x} = 4e^{-3x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  3A &= 4 \\
    A &= \dfrac{4}{3}
\end{align}


De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{4}{3} e^{-3x} x
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{-3x} + \dfrac{4}{3} e^{-3x} x  \qquad \text{met } C \in \mathbb{R}
\end{align}
```

## Opgave 3

```{admonition} Uitwerkingen
:class: dropdown

\begin{align*}
 3\dfrac{dy}{dx} - 5y &= 2 + \sin(3x)\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{dy}{dx} - 5y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3\lambda \cdot Ce^{\lambda x} -5 \cdot Ce^{\lambda x} &= 0 \\
 (3\lambda -5 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 3\lambda -5   &= 0 \\
 3\lambda   &= 5
 \lambda   &= \dfrac{5}{3}
\end{align}

De waarde voor $\lambda =\dfrac{5}{3}$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{\dfrac{5}{3}x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = A\sin(3x) + B\cos(3x) + D
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} = 3A\cos(x) - 3B\sin(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3(3A\cos(x) - 3B\sin(x)) - 5( A\sin(3x) + B\cos(3x) + D)  &= 2 + \sin(3x) \\
 9A\cos(3x) - 9B\sin(3x) - 5A\sin(3x) - 5B\cos(3x) - 5D  &= 2+ \sin(3x) \\
 (-9B-5A)\sin(x) + (9A-5B)\cos(x) - 5D &= 2 + \sin(3x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -9B-5A &= 1 \\
  9A-5B &= 0 \\
  -5D &= 2
\end{align}

Hieruit volgt:
\begin{align}
 D = -\dfrac{2}{5}
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
  A &= -\dfrac{5}{106}
\end{align}

$A $ invullen geeft:
\begin{align}
 B &= \dfrac{9}{5}A \\
 B &= \dfrac{9}{5}\cdot -\dfrac{5}{106} \\
 B &= -\dfrac{9}{106}
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{5}{106}\sin(x) -\dfrac{9}{106}\cos(x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{\dfrac{5}{3}x} -\dfrac{5}{106}\sin(x) -\dfrac{9}{106}\cos(x) \qquad \text{met } C \in \mathbb{R}
\end{align}
```
