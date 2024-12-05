# 1.5 Uitwerkingen

Toon aan dat de gegeven oplossing voldoet aan de differentiaalvergelijking.

## Opgave 1.1a

```{admonition} Uitwerkingen
:class: dropdown

Geef van de volgende differentiaalvergelijking aan of dit een lineaire differentiaalvergelijking is of niet. Geef als het een lineaire differentiaalvergelijking betreft ook aan of deze homogeen of inhomogeen is.  Toon vervolgens aan dat de gegeven oplossing voldoet aan de differentiaalvergelijking.

\begin{align*}
 \dfrac{dy}{dx} - 2y &= e^{3x} \qquad \text{geeft} \qquad y(x)= e^{3x} + Ce^{2x}
\end{align*}

De differentiaalvergelijking staat al in de goede vorm. Hieruit volgt dat de vergelijking lineair is. De differentiaalvergelijking is ongeljik aan 0, dus de vergelijking is inhomogeen.

Gegeven de differentiaalvergelijking:
\begin{align}
 \dfrac{dy}{dx} - 2y &= e^{3x}
\end{align}

Stel de diﬀerentiaalvergelijking heeft als oplossing:
\begin{align}
 y(x)= e^{3x} + Ce^{2x}
\end{align}

Diﬀerentiëren van de functie geeft:
\begin{align}
 \dfrac{dy}{dx} &= 3e^{3x} + 2Ce^{2x} \\
\end{align}

Substitutie in de D.V. geeft dan:
\begin{align}
 \dfrac{dy}{dx} - 2y &= e^{3x} \\
 3e^{3x} + 2Ce^{2x} - 2 (e^{3x} + Ce^{2x}) &= e^{3x}\\
 3e^{3x} + 2Ce^{2x} - 2e^{3x} - 2Ce^{2x} &= e^{3x}\\
 3e^{3x} - 2e^{3x} &= e^{3x}\\
 e^{3x} &= e^{3x}
\end{align}

Oftewel $e^{3x}$ = $e^{3x}$ dus deze functie voldoet aan de diﬀerentiaalvergelijking en is
een oplossing.
```

## Opgave 1.1b

```{admonition} Uitwerkingen
:class: dropdown

Geef van de volgende differentiaalvergelijking aan of dit een lineaire differentiaalvergelijking is of niet. Geef als het een lineaire differentiaalvergelijking betreft ook aan of deze homogeen of inhomogeen is.  Toon vervolgens aan dat de gegeven oplossing voldoet aan de differentiaalvergelijking.

\begin{align*}
 \dfrac{1}{t}\dfrac{dx}{dt} + 2x &= 1 \qquad \text{geeft} \qquad x(t)= \dfrac{1}{2} + Ce^{-t^2}
\end{align*}

De differentiaalvergelijking staat al in de goede vorm. Hieruit volgt dat de vergelijking lineair is. De differentiaalvergelijking is ongeljik aan 0, dus de vergelijking is inhomogeen.

Gegeven de differentiaalvergelijking:
\begin{align}
 \dfrac{1}{t}\dfrac{dx}{dt} + 2x &= 1
\end{align}

Stel de diﬀerentiaalvergelijking heeft als oplossing:
\begin{align}
 x(t)= \dfrac{1}{2} + Ce^{-t^2}
\end{align}

Diﬀerentiëren van de functie geeft:
\begin{align}
 \dfrac{dy}{dx} &= -2tCe^{-t^2} \\
\end{align}

Substitutie in de D.V. geeft dan:
\begin{align}
 \dfrac{1}{t}\dfrac{dx}{dt} + 2x &= 1\\
 \dfrac{1}{t} (-2tCe^{-t^2}) + 2 (\dfrac{1}{2} + Ce^{-t^2}) &= 1 \\
 -2Ce^{-t^2} + 2 \cdot \dfrac{1}{2} + 2Ce^{-t^2}) &= 1 \\
 1 &= 1
\end{align}

Oftewel $1$ = $1$ dus deze functie voldoet aan de diﬀerentiaalvergelijking en is
een oplossing.
```

## Opgave 1.1c

```{admonition} Uitwerkingen
:class: dropdown

Geef van de volgende differentiaalvergelijking aan of dit een lineaire differentiaalvergelijking is of niet. Geef als het een lineaire differentiaalvergelijking betreft ook aan of deze homogeen of inhomogeen is.  Toon vervolgens aan dat de gegeven oplossing voldoet aan de differentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dt^2} + \dfrac{dy}{dt} - 2y &= 4t \qquad \text{geeft} \qquad y(x)= -2t - 1 + C_1e^{t} + C_2e^{-2t}
\end{align*}

De differentiaalvergelijking staat al in de goede vorm. Hieruit volgt dat de vergelijking lineair is. De differentiaalvergelijking is ongeljik aan 0, dus de vergelijking is inhomogeen.

Gegeven de differentiaalvergelijking:
\begin{align}
 \dfrac{d^2y}{dt^2} + \dfrac{dy}{dt} - 2y &= 4t
\end{align}

Stel de diﬀerentiaalvergelijking heeft als oplossing:
\begin{align}
 y(x)= -2t - 1 + C_1e^{t} + C_2e^{-2t}
\end{align}

Diﬀerentiëren van de functie geeft:
\begin{align}
 \dfrac{dy}{dx} &= -2 + C_1e^{t} -2C_2e^{-2t} \\
 \dfrac{d^2y}{dx^2} &= + C_1e^{t} + 4C_2e^{-2t}
\end{align}

Substitutie in de D.V. geeft dan:
\begin{align}
 \dfrac{d^2y}{dt^2} - \dfrac{dy}{dt} - 2y &= 4t \\
 (C_1e^{t} + 4C_2e^{-2t}) + (-2 + C_1e^{t} -2C_2e^{-2t} ) - 2(-2t - 1 + C_1e^{t} + C_2e^{-2t}) &= 4t  \\
(C_1e^{t} + 4C_2e^{-2t}) - 2 + C_1e^{t} - 2C_2e^{-2t}  + 4t + 2  - 2C_1e^{t} - 2C_2e^{-2t} &= 4t  \\
C_1e^{t} + C_1e^{t}  - 2C_1e^{t}  + 4C_2e^{-2t} - 2C_2e^{-2t} - 2C_2e^{-2t} - 2  + 2 + 4t   &= 4t \\
 4t &= 4t
\end{align}

Oftewel $4t$ = $4t$ dus deze functie voldoet aan de diﬀerentiaalvergelijking en is
een oplossing.
```

## Opgave 1.1d

```{admonition} Uitwerkingen
:class: dropdown

Geef van de volgende differentiaalvergelijking aan of dit een lineaire differentiaalvergelijking is of niet. Geef als het een lineaire differentiaalvergelijking betreft ook aan of deze homogeen of inhomogeen is.  Toon vervolgens aan dat de gegeven oplossing voldoet aan de differentiaalvergelijking.

\begin{align*}
 \dfrac{dy}{dx} + y^2\sin(x) &= 0 \qquad \text{geeft} \qquad y(x)= \dfrac{1}{1-\cos(x)}
\end{align*}

De differentiaalvergelijking staat al in de goede vorm. Hieruit volgt dat de vergelijking niet-lineair is.

Gegeven de differentiaalvergelijking:
\begin{align}
 \dfrac{dy}{dx} + y^2\sin(x) &= 0
\end{align}

Stel de diﬀerentiaalvergelijking heeft als oplossing:
\begin{align}
 y(x)= \dfrac{1}{1-\cos(x)} \\
 y(x)= (1-\cos(x))^{-1}
\end{align}

Diﬀerentiëren van de functie geeft:
\begin{align}
 \dfrac{dy}{dx} &= -(1-\cos(x))^{-2} \cdot sin(x) \\
 \dfrac{dy}{dx} &= - \dfrac{sin(x)}{ (1-\cos(x))^{2}}
\end{align}

Substitutie in de D.V. geeft dan:
\begin{align}
 - \dfrac{sin(x)}{ (1-\cos(x))^{2}} + (\dfrac{1}{1-\cos(x)})^2 \cdot  \sin(x) &= 0 \\
  - \dfrac{sin(x)}{ (1-\cos(x))^{2}} + \dfrac{\sin(x)}{(1-\cos(x))^{2}} \cdot  \sin(x) &= 0 \\
 0 &= 0
\end{align}

Oftewel $0$ = $0$ dus deze functie voldoet aan de diﬀerentiaalvergelijking en is
een oplossing.
```

## Opgave 1.2a

```{admonition} Uitwerkingen
:class: dropdown

Bepaal door integratie de algemene oplossing van de volgende
diﬀerentiaalvergelijking.

\begin{align*}
 \dfrac{dy}{dx} &= -3x^2
\end{align*}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 y &= \int( -3x^2) dx \\
 y &= -x^3 + C \qquad \text{met } C \in \mathbb{R}
\end{align}
```

## Opgave 1.2b

```{admonition} Uitwerkingen
:class: dropdown

Bepaal door integratie de algemene oplossing van de volgende
diﬀerentiaalvergelijking.

\begin{align*}
 \dfrac{d^2y}{dx^2} &= - \cos(2x)
\end{align*}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \dfrac{dy}{dx} &= \int (- \cos(2x)) dx \\
 \dfrac{dy}{dx} &= -\dfrac{1}{2} \sin(2x) + C_1 \\
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 y &= \int (-\dfrac{1}{2} \sin(2x) + C_1) dx \\
 y &= \dfrac{1}{4} \cos(2x) + C_1x + C_2 \qquad \text{met } C_{1,2} \in \mathbb{R}
\end{align}
```

## Opgave 1.2c

```{admonition} Uitwerkingen
:class: dropdown

Bepaal door integratie de algemene oplossing van de volgende
diﬀerentiaalvergelijking.

\begin{align*}
 \dfrac{1}{x}\dfrac{dy}{dx} = e^x
\end{align*}

Herschrijf de vergelijking.
\begin{align*}
 \dfrac{dy}{dx} = x \cdot  e^x
\end{align*}

Oplossen door partieel integreren.
De algemene methode voor partieel integreren is;
\begin{align*}
 & \int f \cdot g' dx \\
 &= \int f  dg \\
 &= f \cdot g - \int g \cdot df
\end{align*}

Dit invullen voor de vergelijking geeft;
\begin{align*}
y&= \int x \cdot e^x dx \\
&= \int x \cdot  de^x \\
&= x \cdot e^x - \int e^x \cdot d1 \\
&= x \cdot e^x - \int e^x \cdot 1 dx \\
y&= x \cdot e^x - e^x + C \qquad \text{met } C \in \mathbb{R}
\end{align*}
```

## Opgave 1.2d

```{admonition} Uitwerkingen
:class: dropdown

Bepaal door integratie de algemene oplossing van de volgende
diﬀerentiaalvergelijking.

\begin{align*}
 \dfrac{d^3y}{dx^3}  &= 0
\end{align*}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \dfrac{d^2y}{dx^2} &= \int 0 dx \\
 \dfrac{d^2y}{dx^2} &= C_1 \\
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \dfrac{dy}{dx} &= \int C_1 dx \\
 \dfrac{dy}{dx} &= C_1x + C_2 \\
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 y &= \int (C_1x + C_2) dx \\
 y &= \dfrac{1}{2}C_1x^2 + C_2x + C_3 \\
 y &= C_1x^2 + C_2x + C_3 \qquad \text{met } C_{1,2,3} \in \mathbb{R}
\end{align}
```
