# 5.5 Uitwerkingen les 7

$
\newcommand{\R}{100}
\newcommand{\L}{2}
\newcommand{\C}{0.2}
\newcommand{\CC}{5}
\newcommand{\LC}{3}
\newcommand{\Labda_een}{-49.95}
\newcommand{\Labda_twee}{-0.05}
$

## Opgave 1

````{admonition} Antwoord
:class: dropdown
De stroomsterkte, I (t) als functie van tijd is:
\begin{align}
 I &= 0.1199e^{-0.010x} -0.0959e^{-9.989x} + 0.0429\sin(x) + 0.476\cos(x)
\end{align}

```{admonition} Uitwerkingen
:class: dropdown

Bepaal de stroomsterkte $I(t)$ in een RLC-netwerk als de volgende parameters zijn gegeven:

$R = \R$ $\Omega$, $L=\L$H, $$C =\C$F, $U(t)=24 \cos(t)$V, $I(0)=0.5$A en $I'(0)=1.0$A/s

Voor een RLC-kring geldt:
  \begin{align}
   U(t) &= U_L + U_r +  U_c    \\
     &=  L \cdot \dfrac{dI}{dt} + R \cdot I +\dfrac{1}{C} \int I dt
  \end{align}

  Beide zijdes differenti\"eren geeft de gevraagde DV.:
  \begin{align}
   \dfrac{dU(t)}{dt} &= L \cdot \dfrac{d^2I}{dt^2} + R \cdot \dfrac{dI}{dt} + \dfrac{1}{C} \cdot  I
  \end{align}

  De gegevens invullen in de DV geeft:
  \begin{align}
   \dfrac{dU(t)}{dt} &= \L \cdot \dfrac{d^2I}{dt^2} + \R \cdot \dfrac{dI}{dt} + \dfrac{1}{\C} \cdot  I\\
   -24\sin(t) &= \L \cdot \dfrac{d^2I}{dt^2} + \R \cdot \dfrac{dI}{dt} + \dfrac{1}{\C} \cdot  I\\
   -24\sin(t) &= \L \cdot  \dfrac{d^2I}{dt^2} + \R \cdot \dfrac{dI}{dt} + \CC \cdot  I
  \end{align}

%De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
%\begin{align*}
% I = I_h + I_p
%\end{align*}

De homogene D.V. wordt:
\begin{align}
 \L \dfrac{d^2I}{dt^2} + \R \dfrac{dI}{dt} + \CC I = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 I = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \L \lambda^2 \cdot Ce^{\lambda t} +\R \lambda \cdot Ce^{\lambda t} + \CC \cdot Ce^{\lambda t} &= 0 \\
 (\L \lambda^2 + \R \lambda +\CC )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 \L \lambda^2 + \R \lambda + \CC   &= 0 \\
 10\lambda^2 + 100\lambda +1   &= 0
\end{align}

Dus de discriminant is,
\begin{align}
 D = (\R)^2 - 4 \cdot \L \cdot \CC = 10000-40=9960
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-\R \pm \sqrt{9960}}{2 \cdot \L }\\
  \lambda_{1} &= \Labda_een\\
 \lambda_{2} &=  \Labda_twee
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 I_h = C_1e^{\lambda_1 x} + C_2e^{\lambda_1 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}
\begin{align}
 I_h = C_1e^{\Labda_een x} + C_2e^{ \Labda_twee x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  C_1\sin(x) + C_2\cos(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \L \cdot(-C_1\sin(x) - C_2\cos(x)) + \R \cdot (C_1\cos(x) - C_2\sin(x)) + \CC \cdot (C_1\sin(x) + C_2\cos(x)) &= -48\sin(x) \\
 - \L C_1\sin(x) - \L C_2\cos(x)  + \R C_1\cos(x) - \R C_2\sin(x)) + \CC C_1\sin(x) + \CC C_2\cos(x)  = -48\sin(x) \\
 (- \L C_1 + \CC C_1 - \R C_2) \sin(x) + (\R C_1+ \CC C_2- \L C_2)\cos(x)   = -48\sin(x) \\
  (-\LC C_1 - \R C_2) \sin(x) + (\R C_1- \LC C_2)\cos(x)   = -48\sin(x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 - \LC C_1 - \R C_2 &= -48 \\
 \R C_1- \LC C_2 &= 0
\end{align}

Hieruit volgt:
\begin{align}
\R C_1- \LC C_2 &= 0 \\
\R C_1 &= \LC C_2 \\
 C_1 &= 0.03C_2
\end{align}

$C_1 $ invullen geeft:
\begin{align}
 -\LC \cdot 0.03C_2 - \R C_2 &= -48\\
  0.81C_2 + 100 C_2 &= -48\\
  100.81C_2 &= -48\\
  C_2 &= 0.476
\end{align}

$C_2 $ invullen geeft:
\begin{align}
 C_1 &= 0.03C_2 \\
 C_1 &= 0.03 \cdot 0.476\\
 C_1 &= 0.0429
\end{align}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align}
  I_p = 0.0429\sin(x) + 0.476\cos(x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= C_1e^{-0.010x} + C_2e^{-9.989x} + 0.0429\sin(x) + 0.476\cos(x)   \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om $C_1$ en $C_2$ te bepalen.  $I(0) = 0$ en $I'(0) = 1$

Dus invullen geeft voor $I(0) = 0.5$:
\begin{align}
 0.5 &= C_1e^{-0.010 \cdot 0} + C_2e^{-9.989 \cdot 0} + 0.0429\sin(0) + 0.476\cos(0)  \\
 0.5 &= C_1e^{0} + C_2e^{0} + 0 + 0.476\\
 0.5 &= C_1  + C_2  + 0.476 \\
 0.024 &= C_1 + C_2
\end{align}

Hieruit volgt:
\begin{align}
 C_1 &= 0.024 -C_2
\end{align}

Dus invullen geeft voor $I'(0) = 1$:
\begin{align}
 1 &= -0.010C_1e^{-0.010 \cdot 0}  -9.989C_2e^{-9.989 \cdot 0} + 0.0429\cos(0) - 0.476\sin(0) \\
 1 &= -0.010C_1e^{0}  -9.989C_2e^{0} + 0.0429 - 0  \\
 1 &= -0.010C_1  -9.989C_2 + 0.0429  \\
 0.9571 &= -0.010C_1  -9.989C_2
\end{align}

$C_1$ invullen geeft:
\begin{align}
 0.9571 &= -0.010(0.024-C_2)  -9.989C_2  \\
 0.9571 &= 2.4\cdot 10^{-4} + 0.010C_2  -9.989C_2 \\
 0.95676 &= -9.979C_2\\
 C_2 &=  -0.0959
\end{align}

$C_2$ invullen geeft:
\begin{align}
 C_1 &= 0.024 - -0.0959\\
 C_1 &= 0.1199
\end{align}

Dus $C_1$ en $C_2$ invullen in de totale oplossing geeft:
\begin{align}
 I &= 0.1199e^{-0.010x} -0.0959e^{-9.989x} + 0.0429\sin(x) + 0.476\cos(x)
\end{align}
```
````