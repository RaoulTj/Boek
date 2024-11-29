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
 \Dfrac{dy_p}{dx} = 2Ax + B
\end{align}


Invullen in de D.V. geeft:
\begin{align}
 (2Ax +B) - 7 \cdot (Ax^2 + Bx + D) &= 2x^2 + 4x \\
 (2Ax +B) - 7Ax^2 - 7Bx - 7D&= 2x^2+ 4x \\
  7Ax^2 +(2A-7B)x + (B-7D) &= 2x^2 + 4x
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 7A &= 2 \\
 2A-7B &= 4 \\
 B - 7D &= 0
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{2}{7}
\end{align}

$A $ invullen geeft:
\begin{align}
 2 \cdot \dfrac{2}{7} - 7B &= 0\\
 \dfrac{4}{7} - 7B &= 4\\
  -7B &= 4 - \dfrac{4}{7}\\
  -7B &= \dfrac{24}{7}\\
  B &= -\dfrac{24}{49} 
\end{align}

$B $ invullen geeft:
\begin{align}
 -\dfrac{24}{49} - 7D &= 0\\
 7D &= -\dfrac{24}{49} \\
 D &= -\dfrac{24}{343}
\end{align}

De waardes voor $A$, $B$ en $D$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{2}{7}x^2 - \dfrac{24}{49}x - \dfrac{24}{343}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{7x} + \dfrac{2}{7}x^2 - \dfrac{24}{49}x - \dfrac{24}{343} \qquad \text{met } C \in \mathbb{R}
\end{align}
```