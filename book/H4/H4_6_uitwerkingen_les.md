# 4.6 Uitwerkingen les 4

## Opgave 1

```{admonition} Uitwerkingen
:class: dropdown

\begin{align*}
 \dfrac{d^2y}{dx^2} + 7\dfrac{dy}{dx} +12 y = 10\cos(2x)
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2} + 7\dfrac{dy}{dx} +12 y = 0
\end{align}

Als algemene oplossing voor de D.V. stel:
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
 \lambda^2 Ce^{\lambda x} +7 (\lambda Ce^{\lambda x}) +12 (Ce^{\lambda x}) &= 0 \\
 (\lambda^2 +7 \lambda +12 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 +7 \lambda +12 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (7)^2 - 4 \cdot 1 \cdot 12 = 49 - 48 = 1
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= -\dfrac{7 \pm \sqrt{1}}{2 \cdot 1}\\
  \lambda_{1,2} &= -\dfrac{7 \pm 1}{2}\\
  \lambda_{1} = -4 &\vee \lambda_{2} = -3
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = C_1e^{\lambda_1 x} + C_2e^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{-4 x} + C_2e^{-3 x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V. 
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  C_1\sin(2x) + C_2\cos(2x)
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &=  2C_1\cos(2x) - 2C_2\sin(2x) \\
 \dfrac{d^2y_p}{dx^2} &=  -4C_1\sin(2x) - 4C_2\cos(2x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
  (-4C_1\sin(2x) - 4C_2\cos(2x))  +7 \cdot (2C_1\cos(2x) - 2C_2\sin(2x)) +12 \cdot (C_1\sin(2x) + C_2\cos(2x))  &= 10\cos(2x) \\
 -4C_1\sin(2x) - 4C_2\cos(2x)  + 14C_1\cos(2x) - 14C_2\sin(2x)) +  12 C_1\sin(2x) +12 C_2\cos(2x)  &= 10\cos(2x) \\
 (-4C_1  + 12C_1 - 14C_2) \sin(2x) + (14C_1-4C_2+12C_2)\cos(2x))   &= 10\cos(2x)\\
  (8C_1 - 14C_2) \sin(2x) + (14C_1+8C_2)\cos(2x))   &= 10\cos(2x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 8C_1 - 14C_2 &= 0 \\
 14C_1 + 8C_2 &= 10
\end{align}

Hieruit volgt:
\begin{align}
8 C_1 - 14 C_2 &= 0 \\
8 C_1 &= 14C_2 \\
 C_1 &= \dfrac{14}{8}C_2
\end{align}

$C_1 $ invullen geeft:
\begin{align}
 14 \cdot \dfrac{14}{8}C_2 + 8C_2 &= 10\\
  \dfrac{98}{4}C_2 + 8 C_2 &= 10\\
  \dfrac{130}{4}C_2 &= 10\\
  C_2 &= \dfrac{40}{130} = \dfrac{4}{13}
\end{align}

$C_2 $ invullen geeft:
\begin{align}
 C_1 &= \dfrac{14}{8}C_2
 C_1 &= \dfrac{14}{8} \cdot \dfrac{4}{13}
 C_1 &=  \dfrac{7}{13}
\end{align}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align}
  y_p = \dfrac{7}{13}\sin(2x) + \dfrac{4}{13}\cos(2x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= C_1e^{-4 x} + C_2e^{-3 x} + \dfrac{7}{13}\sin(2x) + \dfrac{4}{13}\cos(2x)  \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
