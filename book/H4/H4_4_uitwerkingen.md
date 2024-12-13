# 4.4 Uitwerkingen

## Opgave 4.1a

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y = C_1e^{-6 x} + C_2e^{3 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 \dfrac{d^2y}{dx^2} + 3\dfrac{dy}{dx} - 18y = 0
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
 \lambda^2 Ce^{\lambda x} + 3(\lambda Ce^{\lambda x}) - 18(Ce^{\lambda x}) &= 0 \\
 (\lambda^2 +3\lambda-18 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 +3\lambda-18 &= 0
\end{align}

De D is groter dan 0 dus,
\begin{align}
 (\lambda +6)(\lambda -3) &= 0
\end{align}

dus $\lambda_1 = -6$ en $\lambda_2 = 3$

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = C_1e^{\lambda_1 x} + C_2e^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = C_1e^{-6 x} + C_2e^{3 x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 4.1b

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y = C_1e^{-2 x} + C_2e^{2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 2\dfrac{d^2y}{dx^2} - 8y = 0
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
 2\lambda^2 Ce^{\lambda x} - 8(Ce^{\lambda x}) &= 0 \\
 (2\lambda^2 -8 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 2\lambda^2 -8 &= 0
\end{align}

De D is groter dan 0 dus,
\begin{align}
  \lambda^2 -4 &= 0 \\
 (\lambda -2)(\lambda +2) &= 0
\end{align}

dus $\lambda_1 = -2$ en $\lambda_2 = 2$

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = C_1e^{\lambda_1 x} + C_2e^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = C_1e^{-2 x} + C_2e^{2 x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 4.1c

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y = e^{-\frac{1}{3}x}\left(C_1\cos\left(\dfrac{\sqrt{2}}{3}x\right) + C_2\sin \left( \dfrac{\sqrt{2}}{3}x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 3\dfrac{d^2y}{dx^2}+2\dfrac{dy}{dx} +y = 0
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
 3(\lambda^2 Ce^{\lambda x}) + 2(\lambda Ce^{\lambda x}) +(Ce^{\lambda x}) &= 0 \\
 (3\lambda^2+ 2\lambda +1 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 3\lambda^2 + 2\lambda +1 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = 2^2 - 4 \cdot 3 \cdot 1=4-12=-8
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-2 \pm i\sqrt{8}}{2 \cdot 3}\\
  \lambda_{1,2} &= -\dfrac{2}{6} \pm \dfrac{\sqrt{8}}{6} \\
 \lambda_{1,2} &= -\dfrac{1}{3} \pm \dfrac{\sqrt{2}}{3}
\end{align}

Hieruit volgt dat $p=-\dfrac{1}{3}$ en $q=\dfrac{\sqrt{2}}{3}$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = e^{-\frac{1}{3}x}\left(C_1\cos\left(\dfrac{\sqrt{2}}{3}x\right) + C_2\sin \left( \dfrac{\sqrt{2}}{3}x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 4.1d

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y = C_1e^{4x} + C_2xe^{4x} \qquad \text{met } C \in \mathbb{R} \\
 y = (C_1 + C_2x)e^{4x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 \dfrac{d^2y}{dx}-8\dfrac{dy}{dx} +16y = 0
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 (\lambda^2 Ce^{\lambda x}) -8(\lambda Ce^{\lambda x}) +16(Ce^{\lambda x}) &= 0 \\
 (\lambda^2-8\lambda +16 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 -8\lambda +16 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-8)^2 - 4 \cdot 1 \cdot 16 = 64-64=0
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1} &= \dfrac{8 \pm \sqrt{0}}{2 \cdot 1}\\
  \lambda_{1} &= \dfrac{8}{2} \\
 \lambda_{1} &= 4
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = C_1e^{\lambda_1 x} + C_2xe^{\lambda_1 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = C_1e^{4x} + C_2xe^{4x} \qquad \text{met } C \in \mathbb{R} \\
 y = (C_1 + C_2x)e^{4x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## Opgave 4.2a

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y &= e^{x}\left(C_1\cos\left(2x\right) + C_2\sin \left( 2x \right)\right)  +  \dfrac{3}{5}x + \dfrac{16}{25} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 \dfrac{d^2y}{dx}-2\dfrac{dy}{dx} +5y = 3x + 2
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2}-2\dfrac{dy}{dx} +5y =  0
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
 (\lambda^2 Ce^{\lambda x}) -2(\lambda Ce^{\lambda x}) +5(Ce^{\lambda x}) &= 0 \\
 (\lambda^2- 2\lambda +5 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 - 2\lambda +5 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-2)^2 - 4 \cdot 1 \cdot 5 = 4-20=-16
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{2 \pm i\sqrt{16}}{2}\\
  \lambda_{1,2} &= \dfrac{2}{2} \pm \dfrac{\sqrt{16}}{2}i \\
 \lambda_{1,2} &= 1 \pm 2i
\end{align}

Hieruit volgt dat $p=1$ en $q=2$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = e^{x}\left(C_1\cos\left(2x\right) + C_2\sin \left( 2x \right)\right) \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = C_1x^2 + C_2x + C_3
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= 2C_1x + C_2 \\
 \dfrac{d^2y_p}{dx^2} &= 2C_1
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2(C_1) - 2\cdot (2C_1x+C_2) + 5 \cdot (C_1x^2 + C_2x + C_3) &= 3x+2 \\
 2C_1-4C_1x -2C_2 + 5C_1x^2 + 5C_2x + 5C_3&= 3x+2\\
  5C_1x^2 +(-4C_1+5C_2)x + (2C_1 - 2C_2+5C_3) &= 3x+2
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 5C_1 &= 0 \\
 -4C_1+5C_2 &= 3 \\
 2C_1-2C_2 + 5C_3 &= 2
\end{align}

Hieruit volgt:
\begin{align}
 C_1 = 0
\end{align}

$C_1 $ invullen geeft:
\begin{align}
 -4 \cdot 0 + 5C_2 &= 3\\
 0 + 5C_2 &= 3\\
  C_2 &= \dfrac{3}{5}
\end{align}

$C_2 $ invullen geeft:
\begin{align}
 2 \cdot 0 -2 \cdot \dfrac{3}{5}  + 5C_3 &= 2\\
   \dfrac{-6}{5}  + 5C_3 &= 2\\
      5C_3 &= 2 + \dfrac{6}{5} \\
 5C_3 &= \dfrac{16}{5} \\
 C_3 &= \dfrac{16}{25}
\end{align}

De waardes voor $C_1$, $C_2$ en $C_3$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{3}{5}x + \dfrac{16}{25}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= e^{x}\left(C_1\cos\left(2x\right) + C_2\sin \left( 2x \right)\right)  +  \dfrac{3}{5}x + \dfrac{16}{25} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
````

## Opgave 4.2b

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y &= C_1e^{- x} + C_2e^{2 x} -\dfrac{3}{40}\sin(2x) + \dfrac{1}{40}\cos(2x)  \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 2\dfrac{d^2y}{dx^2}-2\dfrac{dy}{dx} -4y = \sin(2x)
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{d^2y}{dx^2}-2\dfrac{dy}{dx} -4y =  0
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
 2(\lambda^2 Ce^{\lambda x}) -2(\lambda Ce^{\lambda x}) -4(Ce^{\lambda x}) &= 0 \\
 (2\lambda^2- 2\lambda -4 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 2\lambda^2 - 2\lambda -4 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-2)^2 - 4 \cdot 2 \cdot -4 = 4+32=36
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{2 \pm \sqrt{36}}{2 \cdot 2}\\
  \lambda_{1,2} &= \dfrac{2 \pm 6}{4}\\
  \lambda_{1} = -1 &\vee \lambda_{2} = 2
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = C_1e^{\lambda_1 x} + C_2e^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{- x} + C_2e^{2 x} \qquad \text{met } C \in \mathbb{R}
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
 2 \cdot(-4C_1\sin(2x) - 4C_2\cos(2x))  - 2 \cdot (2C_1\cos(2x) - 2C_2\sin(2x)) -  4 \cdot (C_1\sin(2x) + C_2\cos(2x))  &= \sin(2x) \\
 -8C_1\sin(2x) - 8C_2\cos(2x)  - 4C_1\cos(2x) + 4C_2\sin(2x)) -  4C_1\sin(2x) - 4C_2\cos(2x)  &= \sin(2x) \\
 (-8C_1 - 4C_1 + 4C_2) \sin(2x) + (-4C_1-4C_2-8C_2)\cos(2x))   &= \sin(2x) \\
  (-12C_1 + 4C_2) \sin(2x) + (-4C_1-12C_2)\cos(2x))   &= \sin(2x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -12C_1 + 4C_2 &= 1 \\
 -4C_1-12C_2 &= 0
\end{align}

Hieruit volgt:
\begin{align}
-4C_1-12C_2 &= 0 \\
-4C_1 &= 12C_2 \\
 C_1 &= -3C_2
\end{align}

$C_1 $ invullen geeft:
\begin{align}
 -12 \cdot -3C_2 + 4C_2 &= 1\\
  36C_2 + 4 C_2 &= 1\\
  40C_2 &= 1\\
  C_2 &= \dfrac{1}{40}
\end{align}

$C_2 $ invullen geeft:
\begin{align}
 C_1 &= -3C_2 \\
 C_1 &= -3 \cdot \dfrac{1}{40}\\
 C_1 &= - \dfrac{3}{40}
\end{align}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align}
  y_p = -\dfrac{3}{40}\sin(2x) + \dfrac{1}{40}\cos(2x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= C_1e^{- x} + C_2e^{2 x} -\dfrac{3}{40}\sin(2x) + \dfrac{1}{40}\cos(2x)  \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
````

## Opgave 4.2c

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align*}
 y &=  C_1e^{-4x} + C_2xe^{-4x} + \dfrac{1}{36}e^{2x} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align*}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 \dfrac{d^2y}{dx^2}+8\dfrac{dy}{dx} +16y = e^{2x}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2}+8\dfrac{dy}{dx} +16y =  0
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
 (\lambda^2 Ce^{\lambda x}) +8(\lambda Ce^{\lambda x}) +16(Ce^{\lambda x}) &= 0 \\
 (\lambda^2+8\lambda +16 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 +8\lambda +16 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (8)^2 - 4 \cdot 1 \cdot 16 = 64-64=0
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1} &= \dfrac{-8 \pm \sqrt{0}}{2 \cdot 1}\\
  \lambda_{1} &= \dfrac{-8}{2}\\
  \lambda_{1} &=  -4
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = C_1e^{\lambda_1 x} + C_2xe^{\lambda_1 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{-4 x} + C_2xe^{-4 x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  C_1e^{2x}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &=  2C_1e^{2x} \\
 \dfrac{d^2y_p}{dx^2} &=  4C_1e^{2x}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 1 \cdot (4C_1e^{2x})  + 8 \cdot (2C_1e^{2x}) + 16 \cdot (C_1e^{2x})  &= e^{2x} \\
 4C_1e^{2x}  + 16C_1e^{2x} + 16C_1e^{2x}  &= e^{2x} \\
 36C_1e^{2x} &= e^{2x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 36C_1 &= 1 \\
   C_1 &= \dfrac{1}{36}
\end{align}

De waardes voor $C_1$  invullen in de particuliere oplossing geeft:
\begin{align}
  y_p = \dfrac{1}{36}e^{2x}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &=  C_1e^{-4x} + C_2xe^{-4x} + \dfrac{1}{36}e^{2x} \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
````

## Opgave 4.2d

````{admonition} Antwoord
:class: dropdown

De algemene oplossing van de differentiaalvergelijking is:
\begin{align}
 y &= C_1e^{-\dfrac{1}{2}x} + C_2e^{4x} -\dfrac{1}{4}x^2 + \dfrac{7}{8}x -\dfrac{57}{32} + \dfrac{1}{9}e^{4x}x \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}

```{dropdown} Uitwerking

Bepaal analytisch de algemene oplossing van de volgende differentiaalvergelijking.
\begin{align*}
 2\dfrac{d^2y}{dx}-7\dfrac{dy}{dx} -4y = x^2 + e^{4x}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{d^2y}{dx^2}-7\dfrac{dy}{dx} -4y =  0
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
 2(\lambda^2 Ce^{\lambda x}) -7 (\lambda Ce^{\lambda x}) -4 (Ce^{\lambda x}) &= 0 \\
 (2\lambda^2 -7 \lambda -4 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 2\lambda^2 -7 \lambda -4 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-7)^2 - 4 \cdot 2 \cdot -4 = 49 + 32 = 81
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{7 \pm \sqrt{81}}{2 \cdot 2}\\
  \lambda_{1,2} &= \dfrac{7 \pm \sqrt{9}}{4}
\end{align}

Hieruit volgt dat $=\lambda_{1}= -\dfrac{1}{2} $ en $\lambda_{2} = 4$

De waarde voor $\lambda_{1}$ en $\lambda_{2}$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = C_1e^{\lambda_{1}x} + C_2e^{\lambda_{2}x}   \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{-\dfrac{1}{2}x} + C_2e^{4x} \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax^2 + Bx + D + Fe^{4x}
\end{align}

\begin{align}
 y_p = Ax^2 + Bx + D + Fe^{4x}x
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= 2Ax + B + Fe^{4x} + 4Fe^{4x}x \\
 \dfrac{d^2y_p}{dx^2} &= 2A + 4Fe^{4x} + 4Fe^{4x} + 16Fe^{4x}x
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2(2A + 4Fe^{4x} + 4Fe^{4x}  + 16Fe^{4x}x) - 7 \cdot (2Ax + B + Fe^{4x} + 4Fe^{4x}x) -4 \cdot (Ax^2 + Bx + D + Fe^{4x}x) &= x^2+e^{4x} \\
 (4A + 8Fe^{4x} + 8Fe^{4x} + 32Fe^{4x}x) + (-14Ax + -7B - 7Fe^{4x} - 28Fe^{4x}x) + (-4Ax^2  -4Bx  -4D  -4Fe^{4x}x) &= x^2+e^{4x} \\
 (4A + 16Fe^{4x} + 32Fe^{4x}x) + (-14Ax + -7B - 7Fe^{4x} - 28Fe^{4x}x) + (-4Ax^2  -4Bx  -4D  -4Fe^{4x}x) &= x^2+e^{4x} \\
 -4Ax^2 + (-14A-4B)x + (4A-7B -4D) + 9Fe^{4x} &= x^2+e^{4x}
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 -4A &= 1 \\
 -14A-4B &= 0 \\
 4A-7B-4D &= 0 \\
 9F = 1
\end{align}

Hieruit volgt:
\begin{align}
 A = -\dfrac{1}{4}
\end{align}

$A$ invullen geeft:
\begin{align}
 -14 \cdot  -\dfrac{1}{4} -4B= 0\\
 \dfrac{14}{4} -4B= 0\\
 -4B= \dfrac{14}{4} \\
  B= \dfrac{14}{16}  = \dfrac{7}{8}
\end{align}

$A$ en $B$ invullen geeft:
\begin{align}
 4 \cdot  -\dfrac{1}{4} -7 \cdot \dfrac{7}{8} -4D &= 0\\
 -1 -\cdot \dfrac{49}{8} -4D &= 0\\
 -4D &= 1 +\cdot \dfrac{49}{8} \\
 -4D &= \dfrac{57}{8} \\
 D &= -\dfrac{57}{32}
\end{align}

Hieruit volgt:
\begin{align}
 F = \dfrac{1}{9}
\end{align}

De waardes voor $A$, $B$ en $D$ en $F$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{4}x^2 + \dfrac{7}{8}x -\dfrac{57}{32} + \dfrac{1}{9}e^{4x}x
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= C_1e^{-\dfrac{1}{2}x} + C_2e^{4x} -\dfrac{1}{4}x^2 + \dfrac{7}{8}x -\dfrac{57}{32} + \dfrac{1}{9}e^{4x}x \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
````

## Opgave 4.3a



````{admonition} Antwoord
:class: dropdown


```{dropdown} Uitwerking

Los de volgende differentiaalvergelijking met aanvullende voorwaarden exact op.
\begin{align*}
 3\dfrac{d^2y}{dx^2} - 7\dfrac{dy}{dx} + 2y = x^2 + 4x \qquad \text{ met } y(0)=0, y'(0)=0
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{d^2y}{dx^2}-7\dfrac{dy}{dx} +2y =  0
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
 3(\lambda^2 Ce^{\lambda x}) -7 (\lambda Ce^{\lambda x}) +2 (Ce^{\lambda x}) &= 0 \\
 (3\lambda^2 -7 \lambda +2 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 3\lambda^2 -7 \lambda +2 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (-7)^2 - 4 \cdot 3 \cdot 2 = 49 + 24 = 25
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{7 \pm \sqrt{25}}{2 \cdot 6}\\
  \lambda_{1,2} &= \dfrac{7 \pm 5}{6}
\end{align}

Hieruit volgt dat $=\lambda_{1}= \dfrac{1}{3} $ en $\lambda_{2} = 2$

De waarde voor $\lambda_{1}$ en $\lambda_{2}$ invullen in de algemene oplossing geeft;
\begin{align*}
 y_h = C_1e^{\lambda_{1}x} + C_2e^{\lambda_{2}x}   \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y_h = C_1e^{\dfrac{1}{3}x} + C_2e^{2x} \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax^2 + Bx + D
\end{align}

\begin{align}
 y_p = Ax^2 + Bx + D
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &= 2Ax + B  \\
 \dfrac{d^2y_p}{dx^2} &= 2A 
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3(2A) - 7 \cdot (2Ax + B ) +2 \cdot (Ax^2 + Bx + D) &= x^2+e^{4x} \\
 (6A) +  (-14Ax - 14B ) + (2Ax^2 + 2Bx + 2D) &= x^2+4x \\
 2Ax^2 + (-14A + 2B)x + (6A-14B+2D)&= x^2+4x
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 2A &= 1 \\
 -14A + 2B &= 4 \\
 6A-14B+2D &= 0 \\
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{1}{2}
\end{align}

$A$ invullen geeft:
\begin{align}
 -14 \cdot  \dfrac{1}{2} +2B= 0\\
 -\dfrac{14}{2} +2B= 0\\
 2B= \dfrac{14}{2} \\
  B= \dfrac{14}{4}  = \dfrac{7}{2}
\end{align}

$A$ en $B$ invullen geeft:
\begin{align}
 6 \cdot  \dfrac{1}{2} -14 \cdot \dfrac{11}{2} +2D &= 0\\
 3 -\cdot \dfrac{154}{8} +2D &= 0\\
 2D &= -3 +\cdot \dfrac{154}{8} \\
 2D &= -\dfrac{64}{8} + \dfrac{154}{8} \\
 2D &= \dfrac{90}{8}
 end{align}

Hieruit volgt:
\begin{align}
 F = \dfrac{1}{9}
\end{align}

De waardes voor $A$, $B$ en $D$ en $F$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{4}x^2 + \dfrac{7}{8}x -\dfrac{57}{32} + \dfrac{1}{9}e^{4x}x
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= C_1e^{-\dfrac{1}{2}x} + C_2e^{4x} -\dfrac{1}{4}x^2 + \dfrac{7}{8}x -\dfrac{57}{32} + \dfrac{1}{9}e^{4x}x \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```
````

## Opgave 4.3b

```{admonition} Antwoord
:class: dropdown

\begin{align*}
 3\dfrac{d^2y}{dx^2}+6\dfrac{dy}{dx} +15y = 5e^{x}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 3\dfrac{d^2y}{dx^2}+6\dfrac{dy}{dx} +15y =  0
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
 3(\lambda^2 Ce^{\lambda x}) +6(\lambda Ce^{\lambda x}) +15(Ce^{\lambda x}) &= 0 \\
 (3\lambda^2+6\lambda +15 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 3\lambda^2 +6\lambda +15 &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (6)^2 - 4 \cdot 3 \cdot 15 = 36 - 180 = -144
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-6 \pm i\sqrt{144}}{2 \cdot 3}\\
  \lambda_{1,2} &= \dfrac{-6 \pm 12i}{6}\\
  \lambda_{1,2} &= -1 \pm 2i
\end{align}

Hieruit volgt dat $p=-1$ en $q=2$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = e^{px}(C_1\cos(qx) + C_2\sin(qx)) \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = e^{-x}(C_1\cos(2x) + C_2\sin ( 2x ) ) \qquad  \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  C_1e^{x}
\end{align}

Dus,
\begin{align}
 \dfrac{dy_p}{dx} &=  C_1e^{x} \\
 \dfrac{d^2y_p}{dx^2} &=  C_1e^{x}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 3 \cdot (C_1e^{x})  + 6 \cdot (C_1e^{x}) + 15 \cdot (C_1e^{x})  &= 5e^{x} \\
 3C_1e^{x}  + 6C_1e^{x} + 15C_1e^{x}  &= 5e^{x} \\
 24C_1e^{x} &= 5e^{x}
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 24C_1 &= 5 \\
   C_1 &= \dfrac{5}{24}
\end{align}

De waardes voor $C_1$  invullen in de particuliere oplossing geeft:
\begin{align}
  y_p = \dfrac{5}{24}e^{x}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &=  e^{-x}(C_1\cos(2x) + C_2\sin ( 2x ) ) + \dfrac{5}{24}e^{x} \qquad \text{met } C \in \mathbb{R}  
\end{align}
```
