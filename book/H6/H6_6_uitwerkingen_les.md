# 5.5 Uitwerkingen les 7

$
\newcommand{\R}{100}
\newcommand{\L}{2}
\newcommand{\C}{0.2}
\newcommand{\U}{24}
\newcommand{\CC}{5}
\newcommand{\LC}{3}
\newcommand{\Leen}{-49.95}
\newcommand{\Ltwee}{-0.05}
\newcommand{\Ceen}{0.007}
\newcommand{\Ctwee}{0.239}
\newcommand{\A}{500}
\newcommand{\B}{500}
$

## Opgave 1

````{admonition} Antwoord
:class: dropdown
De stroomsterkte, I (t) als functie van tijd is:
\begin{align}
 I &= 0.1199e^{-0.010x} -0.0959e^{-9.989x} + 0.0429\sin(x) + 0.476\cos(x)
\end{align}

```{dropdown} Uitwerking

Bepaal de stroomsterkte $I(t)$ in een RLC-netwerk als de volgende parameters zijn gegeven:

$R = \R$ $\Omega$, $L=\L$H, $$C =\C$F, $U(t)=\U \cos(t)$V, $I(0)=0.5$A en $I'(0)=1.0$A/s

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
  \lambda_{1} &= \Leen\\
 \lambda_{2} &=  \Ltwee
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 I_h = C_1e^{\lambda_1 x} + C_2e^{\lambda_1 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}
\begin{align}
 I_h = C_1e^{\Leen x} + C_2e^{ \Ltwee x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  C_1\sin(x) + C_2\cos(x)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \L \cdot(-C_1\sin(x) - C_2\cos(x)) + \R \cdot (C_1\cos(x) - C_2\sin(x)) + \CC \cdot (C_1\sin(x) + C_2\cos(x)) &= - \U \sin(x) \\
 - \L C_1\sin(x) - \L C_2\cos(x)  + \R C_1\cos(x) - \R C_2\sin(x)) + \CC C_1\sin(x) + \CC C_2\cos(x)  = - \U \sin(x) \\
 (- \L C_1 + \CC C_1 - \R C_2) \sin(x) + (\R C_1+ \CC C_2- \L C_2)\cos(x)   = - \U \sin(x) \\
  (-\LC C_1 - \R C_2) \sin(x) + (\R C_1- \LC C_2)\cos(x)   = - \U \sin(x)
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 - \LC C_1 - \R C_2 &= - \U \\
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
 -\LC \cdot 0.03C_2 - \R C_2 &= - \U\\
- 0.09C_2 - \R C_2 &= - \U \\
  -100.09C_2 &= - \U\\
  C_2 &= \Ctwee
\end{align}

$C_2 $ invullen geeft:
\begin{align}
 C_1 &= 0.03C_2 \\
 C_1 &= 0.03 \cdot \Ctwee \\
 C_1 &= \Ceen
\end{align}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align}
  I_p = \Ceen \sin(x) + \Ctwee \cos(x)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= C_1e^{ \Leen x} + C_2e^{ \Ltwee x} + \Ceen \sin(x) + \Ctwee \cos(x)   \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegevenvoorwaarden gebruiken om $C_1$ en $C_2$ te bepalen.  $I(0) = 0$ en $I'(0) = 1$

Dus invullen geeft voor $I(0) = 0$:
\begin{align}
 0 &= C_1e^{ \Leen \cdot 0} + C_2e^{ \Ltwee \cdot 0} + \Ceen \sin(0) + \Ctwee \cos(0)  \\
 0 &= C_1e^{0} + C_2e^{0} + 0 + \Ctwee \\
 0 &= C_1  + C_2  + \Ctwee \\
 - \Ctwee &= C_1 + C_2
\end{align}

Hieruit volgt:
\begin{align}
 C_1 &= - \Ctwee -C_2
\end{align}

Dus invullen geeft voor $I'(0) = 1$:
\begin{align}
 1 &= \Leen C_1e^{ \Leen \cdot 0}  \Ltwee e^{ \Ltwee \cdot 0} + \Ceen \cos(0) - \Ctwee \sin(0) \\
 1 &= \Leen C_1e^{0}  \Ltwee C_2e^{0} + \Ceen - 0  \\
 1 &= \Leen C_1  \Ltwee C_2 + \Ceen  \\
 0.993 &= \Leen C_1  \Ltwee C_2
\end{align}

$C_1$ invullen geeft:
\begin{align}
 0.993 &= \Leen (- \Ctwee -C_2)  \Ltwee C_2  \\
 0.993 &= 2.4\cdot 10^{-4} - \Leen C_2  \Ltwee C_2 \\
 0.993 &= -9.979C_2\\
 C_2 &=  \B
\end{align}

$C_2$ invullen geeft:
\begin{align}
 C_1 &= 0.024 - -0.0959\\
 C_1 &= \A
\end{align}

Dus $C_1$ en $C_2$ invullen in de totale oplossing geeft:
\begin{align}
 I &= 0.1199e^{ \Leen x} -0.0959e^{\Ltwee x} + \A \sin(x) + \B \cos(x)
\end{align}
```
````