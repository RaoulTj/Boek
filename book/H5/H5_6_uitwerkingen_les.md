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