# 5.6 Uitwerkingen les 6

## Opgave 1

`````{admonition} Antwoord
:class: dropdown

Na hoeveel minuten heeft een kop thee een temperatuur bereikt van 35$^{\circ}$ C als de volgende parameters zijn gegeven:

Een kop thee met een temperatuur van 90$^{\circ}$ C wordt op een tafel in een ruimte gelegd waar de  temperatuur 25$^{\circ}$ C is. Na 5 minuten is de thee afgekoelt tot een temperatuur van 70$^{\circ}$ C.

````{dropdown} Uitwerking

Na hoeveel minuten heeft een kop thee een temperatuur bereikt van 35$^{\circ}$ C als de volgende parameters zijn gegeven:

Een kop thee met een temperatuur van 90$^{\circ}$ C wordt op een tafel in een ruimte gelegd waar de  temperatuur 25$^{\circ}$ C is. Na 5 minuten is de thee afgekoelt tot een temperatuur van 70$^{\circ}$ C.


Voor de afkoelingswet geldt:
\begin{align}
 \dfrac{dT}{dt} = -k(T-T_0)
\end{align}

Dit kan omgeschreven worden naar de volgende DV;
\begin{align}
 \dfrac{dT}{dt} &= -k(T-T_0) \\
 \dfrac{dT}{dt} + kT &= kT_0 \\
 \dfrac{dT}{dt} + kT &= 25k
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{dT}{dt} + kT = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 T_h = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda \cdot Ce^{\lambda t} + k\cdot Ce^{\lambda t} &= 0 \\
 (\lambda +k )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 \lambda +k   &= 0  \\
 \lambda   &= -k 
\end{align}

De waarde voor $\lambda$ invullen in de homogene oplossing geeft;
\begin{align}
 T_h = Ce^{-kt} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.

Als vorm voor de particuliere oplossing stel:
\begin{align}
 T_p &=  A \\
 T_p' &= 0
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 1 \cdot ( 0 ) +  k ( A ) &=  25k \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 kA &= 25k \\
 A &= 25
\end{align}

De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 T_p = 25
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 T &= T_h + T_p \\
 T &= Ce^{-kt}  + 25 \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $T(0) = 98$

Dus invullen geeft:
\begin{align}
 90 &= Ce^{-k \cdot 0 }  + 25 \\
 90 &= C \cdot 1  + 25 \\
 C &= 65
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 T &=  65e^{-kt}  + 25
\end{align}

De gegeven voorwaarden gebruiken om k te bepalen.  $T(5) = 38$
Dus invullen geeft:
\begin{align}
 70 &=  65e^{-5k}  + 25 \\
 45 &=  65e^{-5k} \\
 \dfrac{45}{65} &= e^{-5k} \\
 \ln(\dfrac{9}{13} ) &= -5k \\
 k &= -\dfrac{1}{5} \cdot \ln(\dfrac{9}{13}) \\
 k &= 0.074
\end{align}

Dus k invullen in de totale oplossing geeft:
\begin{align}
 T &=  65e^{-0.074t}  + 25
\end{align}

Na hoeveel minuten is de temperatuur 35$^{\circ}$ C:
\begin{align}
 35 &=  65e^{-0.277t}  + 25 \\
 10 &=  65e^{-0.074k} \\
 \dfrac{10}{65} &= e^{-0.074t} \\
 \ln(\dfrac{2}{13} ) &= -0.074t \\
 t &= -\dfrac{1}{0.074} \cdot \ln(\dfrac{2}{13}) \\
 t &\approx 25.29 \text{ minuten}
\end{align}
````
`````

## Opgave 1

`````{admonition} Antwoord
:class: dropdown

Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 50$$\Omega$, $C =0.4$F, $U(t)=200\cos(t)$V en $I(0)=4.0$A

````{dropdown} Uitwerking
Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 50$$\Omega$, $C =0.4$F, $U(t)=200\cos(t)$V en $I(0)=4.0$A

Voor een RC-kring geldt:
  \begin{align}
   U(t) &= U_r + U_c   \\
     &= R \cdot I + \dfrac{1}{C} \int I dt
  \end{align}

  Beide zijdes differentiëren geeft de gevraagde DV.:
  \begin{align}
   \dfrac{dU(t)}{dt} &= R \cdot \dfrac{dI}{dt} + \dfrac{1}{C} \cdot  I
  \end{align}

  De gegevens invullen in de DV geeft:
  \begin{align}
   \dfrac{dU(t)}{dt} &= 50 \cdot \dfrac{dI}{dt} + \dfrac{1}{0.4} \cdot  I\\
   \dfrac{d}{dt}(200 \cos(t)) &= 50 \cdot \dfrac{dI}{dt} + \dfrac{1}{0.4} \cdot  I \\
   -200 \sin(t) &= 50 \cdot \dfrac{dI}{dt} + 2.5 \cdot  I
  \end{align}

De homogene D.V. wordt:
\begin{align}
 50\dfrac{dI}{dt} + 2.5I = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 I_h = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 50\lambda \cdot Ce^{\lambda t} + 2.5\cdot Ce^{\lambda t} &= 0 \\
 (50\lambda +2.5 )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 50\lambda + 2.5   &= 0  \\
 50\lambda   &= -2.5 \\
 \lambda   &= -\dfrac{2.5}{50} = -\dfrac{1}{20}
\end{align}

De waarde voor $\lambda$ invullen in de homogene oplossing geeft;
\begin{align}
 I_h = Ce^{-\frac{1}{20}t} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.

Als vorm voor de particuliere oplossing stel:
\begin{align}
 I_p &=  A \sin(t) + B \cos(t) \\
 I_p' &= A \cos(t) - B \sin(t)
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 50 \cdot (A \cos(t) - B \sin(t)) +  2.5 (A \sin(t) + B \cos(t)) &=  100\cos(t) \\
 (50A+2.5B)\cos(t) + (2.5A -50B)\sin(t) &= -200\sin(t)
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 2.5A-50B &= -200 \\
 50A+2.5B &= 0
\end{align}


Hieruit volgt:
\begin{align}
 2.5B &= -50A \\
 B &= -20A
\end{align}

$B $ invullen geeft:
\begin{align}
 2.5A  - 50 \cdot (-20A)  &= -200\\
 997.5A  &= -200\\
  A &= -\dfrac{200}{997.5} 
\end{align}


$A $ invullen geeft:
\begin{align}
 B &= -20A  \\
 B &= 20 \cdot \dfrac{20}{997.5}  \\
 B &= \dfrac{400}{997.5}
\end{align}

De waardes voor $A$, $B$  invullen in de particuliere oplossing geeft:
\begin{align}
 I_p = -\dfrac{200}{997.5}\sin(t) + \dfrac{400}{997.5}\cos(t)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= Ce^{-\frac{1}{20}t}  -\dfrac{200}{997.5}\sin(t) + \dfrac{400}{997.5}\cos(t) \qquad \text{met } C \in \mathbb{R}  
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $I(0) = 4$

Dus invullen geeft:
\begin{align}
 4 &= Ce^{-\frac{1}{20} \cdot 0}  -\dfrac{200}{997.5}\sin(0) + \dfrac{400}{997.5}\cos(0) \\
 4 &= C \cdot 1  -\dfrac{200}{997.5} \cdot 0 + \dfrac{400}{997.5} \cdot 1 \\
\end{align}

Hieruit volgt:
\begin{align}
 C &= 4 - \dfrac{400}{997.5} \\
 C &= 1.60
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 I &=  1.60e^{-\frac{1}{20}t}  -\dfrac{200}{997.5}\sin(t) + \dfrac{400}{997.5}\cos(t) 
\end{align}