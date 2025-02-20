# 5.5 Uitwerkingen les 7

## Opgave 1

$
\newcommand{\R}{100}
\newcommand{\L}{2}
\newcommand{\C}{0.2}
\newcommand{\U}{24}
\newcommand{\CC}{5}
\newcommand{\LC}{3}
\newcommand{\Leen}{-49.95}
\newcommand{\Ltwee}{-0.05}
\newcommand{\Ceen}{-0.007}
\newcommand{\Ctwee}{0.239}
\newcommand{\A}{-0.02}
\newcommand{\B}{ -0.219}
$

````{admonition} Antwoord
:class: dropdown
De stroomsterkte, I (t) als functie van tijd is:
\begin{align}
 I &= \A e^{ \Leen x} + \B e^{\Ltwee x} + \Ceen \sin(x) + \Ctwee \cos(x)
\end{align}

```{dropdown} Uitwerking

Bepaal de stroomsterkte $I(t)$ in een RLC-netwerk als de volgende parameters zijn gegeven:

$R = \R$ $\Omega$, $L=\L$H, $$C =\C$F, $U(t)=\U \cos(t)$V, $I(0)=0.0$A en $I'(0)=1.0$A/s

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
 10\lambda^2 + 100\lambda +1   &= 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Dus de discriminant is,
\begin{align}
 D = (\R)^2 - 4 \cdot \L \cdot \CC = 10000-40=9960
\end{align}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align}
  \lambda_{1,2} &= \dfrac{-\R \pm \sqrt{9960}}{2 \cdot \L }\\
  \lambda_{1} &= \Leen\\
 \lambda_{2} &=  \Ltwee \qquad {\color{blue} \text{(1p)}}
\end{align}

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 I_h = C_1e^{\lambda_1 x} + C_2e^{\lambda_1 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}
\begin{align}
 I_h = C_1e^{\Leen x} + C_2e^{ \Ltwee x} \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p =  A\sin(x) + B\cos(x) \qquad {\color{blue} \text{(1p)}}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \L \cdot(-A\sin(x) - B\cos(x)) + \R \cdot (A\cos(x) - B\sin(x)) + \CC \cdot (A\sin(x) + B\cos(x)) &= - \U \sin(x) \\
 - \L A\sin(x) - \L B\cos(x)  + \R A\cos(x) - \R B\sin(x)) + \CC A\sin(x) + \CC B\cos(x)  = - \U \sin(x) \\
 (- \L A + \CC A - \R B) \sin(x) + (\R A+ \CC B- \L B)\cos(x)   = - \U \sin(x) \\
  (\LC A - \R B) \sin(x) + (\R A + \LC B)\cos(x)   = - \U \sin(x) \qquad {\color{blue} \text{(1p)}}
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  \LC A - \R B &= - \U \\
 \R A +  \LC B &= 0 \qquad {\color{blue} \text{(1p)}}
\end{align}

Hieruit volgt:
\begin{align}
\R A + \LC B &= 0 \\
\R A &= -\LC B \\
 A &= -0.03B
\end{align}

$A $ invullen geeft:
\begin{align}
 \LC \cdot -0.03B - \R B &= - \U\\
- 0.09B - \R B &= - \U \\
  -100.09B &= - \U\\
  B &= \Ctwee \qquad {\color{blue} \text{(1p)}}
\end{align}

$B $ invullen geeft:
\begin{align}
 A &= -0.03B \\
 A &= 0.03 \cdot \Ctwee \\
 A &= \Ceen \qquad {\color{blue} \text{(1p)}}
\end{align}

De waardes voor $A$, $B$  invullen in de particuliere oplossing geeft:
\begin{align}
  I_p = \Ceen \sin(x) + \Ctwee \cos(x) \qquad {\color{blue} \text{(1p)}}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= C_1e^{ \Leen x} + C_2e^{ \Ltwee x} + \Ceen \sin(x) + \Ctwee \cos(x)   \qquad \text{met } C \in \mathbb{R} \qquad {\color{blue} \text{(1p)}}
\end{align}

De gegeven voorwaarden gebruiken om $C_1$ en $C_2$ te bepalen.  $I(0) = 0$ en $I'(0) = 1$

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
 1.007 &= \Leen C_1  \Ltwee C_2
\end{align}

$C_1$ invullen geeft:
\begin{align}
 1.007 &= \Leen (- \Ctwee -C_2)  \Ltwee C_2  \\
 1.007 &= 11.938 - \Leen C_2  \Ltwee C_2 \\
 -10.931 &= 49.90C_2\\
 C_2 &=  \B
\end{align}

$C_2$ invullen geeft:
\begin{align}
 C_1 &= - \Ctwee - \B\\
 C_1 &= \A
\end{align}

Dus $C_1$ en $C_2$ invullen in de totale oplossing geeft:
\begin{align}
 I &= \A e^{ \Leen x} + \B e^{\Ltwee x} + \Ceen \sin(x) + \Ctwee \cos(x)
\end{align}
```
````

## Opgave 2

$
\newcommand{\m}{10}
\newcommand{\c}{50}
\newcommand{\q}{5}
\newcommand{\Unul}{0.25}
\newcommand{\Ceen}{0.007}
\newcommand{\Ctwee}{0.239}
$

````{admonition} Antwoord
:class: dropdown


```{dropdown} Uitwerking

Voor een massa-veer-systeem geldt:
\begin{align*}
F_{res} &= - F_v \\
F_{res}	&=  - c\cdot u\\
m \cdot a &= - c\cdot u \\
m \cdot \dfrac{d^2 u}{dt^2} &= - c\cdot u\quad
\end{align*}

De gegevens invullen in de D.V. geeft:
\begin{align*}
 m \cdot \dfrac{d^2 u}{dt^2} &=  - c \cdot u \\
 \m \cdot \dfrac{d^2 u}{dt^2} &=  -  \c \cdot u
\end{align*}

De homogene D.V. wordt:
\begin{align*}
 \m \dfrac{d^2u}{dt^2} + \c u =  0
\end{align*}

Als oplossing voor de homogene D.V. stel:
\begin{align*}
 u_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align*}

Dus,
\begin{align*}
 \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
 \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
\end{align*}


Invullen in de D.V. geeft:
\begin{align*}
 \m (\lambda^2 Ce^{\lambda x}) + \c (Ce^{\lambda x}) &= 0 \\
 ( \m \lambda^2+ \c )\cdot Ce^{\lambda x}  &= 0
\end{align*}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align*}
 \m \lambda^2 + \c &= 0
\end{align*}

Dus de discriminant is,
\begin{align*}
 D = (0)^2 - 4 \cdot \m \cdot \c = -2000
\end{align*}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align*}
 \lambda_{1,2} &= \dfrac{0 \pm i\sqrt{2000}}{2 \cdot \m }\\
 \lambda_{1,2} &= \dfrac{0 \pm 4\sqrt{15}i}{2 \cdot \m }\\
 \lambda_{1,2} &= -0 \pm \sqrt{ \q } \cdot i
\end{align*}

Hieruit volgt dat $p=0$ en $q=\sqrt{ \q }$

De waarde voor $p$ en $q$ invullen in de homogene oplossing geeft;
\begin{align*}
 u_h &= e^{px}(C_1\cos(qt) + C_2\sin(qt)) \\
 u_h &= e^{0\cdot x}(C_1\cos(\sqrt{ \q }t) + C_2\sin (\sqrt{ \q }t ) ) \\
 u_h &= C_1\cos(\sqrt{ \q }t) + C_2\sin (\sqrt{ \q }t )  \qquad  \text{met } C_{1,2} \in \mathbb{R}
\end{align*}

De gegeven voorwaarden gebruiken om $C_1$ en $C_2$ te bepalen, $u(0) = 0.25$ en $u'(0) = 0$\\

Dus invullen geeft:
\begin{align*}
 u &=  C_1\cos(\sqrt{ \q }t) + C_2\sin (\sqrt{ \q }t )  \\
 \Unul &=  C_1\cos(\sqrt{ \q } \cdot 0 ) + C_2\sin (\sqrt{ \q } \cdot 0) \\
 \Unul &= C_1 \cdot 1 + 0
\end{align*}

Hieruit volgt:
\begin{align*}
 C_1 = \Unul
\end{align*}

$C_1 $ invullen geeft:
\begin{align*}
 u' &= -\sqrt{ \q } C_1\sin(\sqrt{ \q }t) + \sqrt{15} C_2\cos (\sqrt{ \q }t )   \\
 0 &= -\sqrt{ \q } C_1\sin(\sqrt{ \q } \cdot 0) + \sqrt{ \q } C_2\cos (\sqrt{ \q } \cdot 0 )   \\
 0 &= 0 + \sqrt{ \q } \cdot C_2 \cdot 1
\end{align*}

Hieruit volgt:
\begin{align*}
 C_2 &=  0
\end{align*}

Dus $C_1$ en $C_2$ invullen in de totale oplossing geeft:
\begin{align*}
 u &=  C_1\cos(\sqrt{ \q }t) + C_2\sin (\sqrt{ \q  }t ) \\
 u &= \Unul \cos(\sqrt{ \q }t)
\end{align*}
```
````
