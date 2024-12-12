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

## Opgave 2

```{admonition} Uitwerkingen
:class: dropdown

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 4\dfrac{d^2y}{dx^2}+\dfrac{dy}{dx} +4y = 5x
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 4(\lambda^2 Ce^{\lambda x}) + (\lambda Ce^{\lambda x}) +4 (Ce^{\lambda x}) &= 0 \\
 (4\lambda^2 + \lambda +4 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 4\lambda^2 + \lambda +4 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = 1^2 - 4 \cdot 4 \cdot 4 =1 - 64= -63
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-1 \pm i\sqrt{63}}{2 \cdot 4}\\
  \lambda_{1,2} &= -\dfrac{1}{8} \pm \dfrac{3\sqrt{7}}{8} \\
 \lambda_{1,2} &= -\dfrac{1}{8} \pm \dfrac{3\sqrt{7}}{8}
\end{align}

Hieruit volgt dat $p=-\dfrac{1}{8}$ en $q=\dfrac{3\sqrt{7}}{8}$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = e^{-\frac{1}{8}x}\left(C_1\cos\left(\dfrac{3\sqrt{7}}{8}x\right) + C_2\sin \left( \dfrac{3\sqrt{7}}{8}x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V. 
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax + B
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= A  \\
 \dfrac{d^2y_p}{dx^2} &= 0
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 4 \cdot (0) + (A) + 4 \cdot (Ax + B) &= 5x \\
 A + 4Ax + 4B &= 5x
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 4A &= 5 \\
 A + 4B &= 0 
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{5}{4}
\end{align}

$A $ invullen geeft:
\begin{align}
 \dfrac{5}{4} + 4B &= 0\\
  4B &= -\dfrac{5}{4}\\
  B &= -\dfrac{5}{16}
\end{align}


De waardes voor $C_1$, $C_2$ en $C_3$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{5}{4}x - \dfrac{5}{16}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= e^{-\frac{1}{8}x}\left(C_1\cos\left(\dfrac{3\sqrt{7}}{8}x\right) + C_2\sin \left( \dfrac{3\sqrt{7}}{8}x \right)\right)   +  \dfrac{5}{4}x - \dfrac{5}{16} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```

## Opgave 3

```{admonition} Uitwerkingen
:class: dropdown

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dx^2}-3\dfrac{dy}{dx} = 3x-2
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (\lambda^2 Ce^{\lambda x}) -3 (\lambda Ce^{\lambda x}) &= 0 \\
 (\lambda^2 -3 \lambda  )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 -3 \lambda &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-3)^2 - 4 \cdot 1 \cdot 0 =9
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{3 \pm i\sqrt{9}}{2 \cdot 1}\\
  \lambda_{1,2} &= \dfrac{3}{2} \pm \dfrac{\sqrt{9}}{2} \\
 \lambda_{1,2} &= \dfrac{3}{2} \pm \dfrac{3}{2}
\end{align}

Hieruit volgt dat $\lambda_1=0$ en $\lambda_2=3$

De waarde voor $\lambda_1$ en $\lambda_2$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h &= C_1e^{\lambda_1x} + C_2e^{\lambda_2x} \qquad \text{met } C \in \mathbb{R}
 y_h &= C_1e^{0 \cdot x} + C_2e^{3x} \qquad \text{met } C \in \mathbb{R}
 y_h &= C_1 + C_2e^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align*}


Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V. 
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax + B
\end{align}

B is al een oplossing van de homogene oplossing dus, 
\begin{align}
 y_p &= (Ax + B)x
 y_p &= Ax^2 + Bx
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= 2Ax + B  \\
 \dfrac{d^2y_p}{dx^2} &= 2A
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (2A) -3 (2Ax +B)  &= 3x -2 \\
 - 6Ax + 2A - 3B &= 3x -2
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -6A &= 3 \\
 2A - 3B &= -2
\end{align}

Hieruit volgt:
\begin{align}
 A = -\dfrac{3}{6} = -\dfrac{1}{2}
\end{align}

$A $ invullen geeft:
\begin{align}
 2 \cdot -\dfrac{1}{2} - 3B &= 2 \\
  -3B &= -1 \\
  B &= \dfrac{1}{3}
\end{align}


De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2}x^2 + \dfrac{1}{3}x
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= C_1 + C_2e^{3x} -\dfrac{1}{2}x^2 + \dfrac{1}{3}x  \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```

## Opgave 4

```{admonition} Uitwerkingen
:class: dropdown

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dx^2}-6\dfrac{dy}{dx} +9y = 5xe^{3x}
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (\lambda^2 Ce^{\lambda x}) -6 (\lambda Ce^{\lambda x})  +9 (Ce^{\lambda x}) &= 0 \\
 (\lambda^2 -6 \lambda + 9  )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 -6 \lambda + 9 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-6)^2 - 4 \cdot 1 \cdot 9 =36 - 36 =0
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{6 \pm i\sqrt{0}}{2 \cdot 1}\\
  \lambda_{1,2} &= \dfrac{6}{2} \pm \dfrac{\sqrt{0}}{2} \\
 \lambda_{1,2} &= \dfrac{6}{2} \pm \dfrac{0}{2}
\end{align}

Hieruit volgt dat $\lambda_1=3$ en $\lambda_2=3$

De waarde voor $\lambda_1$ en $\lambda_2$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h &= C_1e^{\lambda_1x} + C_2e^{\lambda_2x} \qquad \text{met } C \in \mathbb{R} \\
 y_h &= C_1e^{3x} + C_2e^{3x}x \qquad \text{met } C \in \mathbb{R} \\
 y_h &= (C_1 + C_2x)e^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align*}


Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V. 
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Axe^{3x} + Be^{3x}
\end{align}

Axe^{3x} is al een oplossing van de homogene oplossing dus,
\begin{align}
 y_p &= (Axe^{3x} + Be^{3x})x \\
 y_p &= Ax^2e^{3x} + Bxe^{3x}
\end{align}

Bxe^{3x} is al een oplossing van de homogene oplossing dus,
\begin{align}
 y_p &= (Ax^2e^{3x} + Bxe^{3x})x \\
 y_p &= Ax^3e^{3x} + Bx^2e^{3x}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &=   3Ax^2e^{3x} + 3Ax^3e^{3x}  + 2Bxe^{3x} + 3Bx^2e^{3x} \\
 \dfrac{d^2y_p}{dx^2} &= 6Axe^{3x} + 9Ax^2e^{3x} + 9Ax^2e^{3x} + 9Ax^3e^{3x} + 2Be^{3x} + 6Bxe^{3x} + 6Bxe^{3x} + 9Bx^2e^{3x} \\
 \dfrac{d^2y_p}{dx^2} &= 9Ax^3e^{3x} + 18Ax^2e^{3x} + 6Axe^{3x} + 9Bx^2e^{3x} + 12Bxe^{3x}+2Be^{3x}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (9Ax^3e^{3x} + 18Ax^2e^{3x} + 6Axe^{3x} + 9Bx^2e^{3x} + 12Bxe^{3x} + 2Be^{3x}) -6 (3Ax^2e^{3x} + 3Ax^3e^{3x}  + 2Bxe^{3x} + 3Bx^2e^{3x}) + 9(Ax^3e^{3x} + Bx^2e^{3x}) &= 5xe^{3x} \\
 6Axe^{3x} + 2Be^{3x} = 5xe^{3x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 6A &= 5 \\
 2B &= 0
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{5}{6}
\end{align}

Hieruit volgt:
\begin{align}
 B = 0
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{5}{6}x^3e^{3x}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= (C_1 + C_2x)e^{3x} + \dfrac{5}{6}x^3e^{3x} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```

## Opgave 5

```{admonition} Uitwerkingen
:class: dropdown

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.

\begin{align*}
 2\dfrac{d^2y}{dx^2}+8y = 2\sin(2x)
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2(\lambda^2 Ce^{\lambda x}) +8 (Ce^{\lambda x}) &= 0 \\
 (2\lambda^2 + 8 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 2\lambda^2 +8 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = 0^2 - 4 \cdot 2 \cdot 8 = - 64
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
 \lambda_{1,2} &= \dfrac{0 \pm i\sqrt{64}}{2 \cdot 2}\\
 \lambda_{1,2} &=  \pm \dfrac{\sqrt{64}}{4} \\
 \lambda_{1,2} &=   \pm \dfrac{8}{4}
 \lambda_{1,2} &=   \pm 2
\end{align}

Hieruit volgt dat $p=0$ en $q=2$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = e^{0x}(C_1\cos(2x) + C_2\sin(2x)) \qquad  \text{met } C \in \mathbb{R} \\
 y_h = C_1\cos(2x) + C_2\sin(2x) \qquad  \text{met } C \in \mathbb{R} \\
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V. 
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = A\sin(2x) + B\cos(2x)
\end{align}

A\sin(2x) is al een oplossing van de homogene oplossing dus,
\begin{align}
 y_p &= (A\sin(2x) + B\cos(2x))x
 y_p &= Ax\sin(2x) + Bx\cos(2x)
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= A\sin(2x) + 2Ax\cos(2x) + Bcos(2x) - 2Bx\sin(2x)  \\
 \dfrac{d^2y_p}{dx^2} &= 2A\cos(2x) + 2A\cos(2x) - 4Ax\sin(2x) -2B\sin(2x) -2B\sin(2x) - 4Bx\cos(2x)
 \dfrac{d^2y_p}{dx^2} &= 4A\cos(2x) - 4Ax\sin(2x) -4B\sin(2x) - 4Bx\cos
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot (4A\cos(2x) - 4Ax\sin(2x) -4B\sin(2x) - 4Bx\cos)  + 8 \cdot (Ax\sin(2x) + Bx\cos(2x)) &= 2\sin(2x) \\
 (8A\cos(2x) - 8Ax\sin(2x) -8B\sin(2x) - 8Bx\cos)  + (8Ax\sin(2x) + 8Bx\cos(2x)) &= 2\sin(2x) \\
 8A\cos(2x) - 8Ax\sin(2x) &= 2\sin(2x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -8A &= 2 \\
 8B  &= 0
\end{align}

Hieruit volgt:
\begin{align}
 A = -\dfrac{2}{8} = -\dfrac{1}{4}
\end{align}

Hieruit volgt:
\begin{align}
 B = 0
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{4}\sin(2x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &=  C_1\cos(2x) + C_2\sin(2x) -\dfrac{1}{4}\sin(2x) \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
