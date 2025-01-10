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

## Opgave 2

`````{admonition} Antwoord
:class: dropdown

Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 50$$\Omega$, $C =0.4$F, $U(t)=200\cos(t)$V en $I(0)=2.0$A

````{dropdown} Uitwerking
Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 50$$\Omega$, $C =0.4$F, $U(t)=200\cos(t)$V en $I(0)=2.0$A

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
 B &= 20 \cdot \dfrac{200}{997.5}  \\
 B &= \dfrac{4000}{997.5}
\end{align}

De waardes voor $A$, $B$  invullen in de particuliere oplossing geeft:
\begin{align}
 I_p = -\dfrac{200}{997.5}\sin(t) + \dfrac{4000}{997.5}\cos(t)
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= Ce^{-\frac{1}{20}t}  -\dfrac{200}{997.5}\sin(t) + \dfrac{4000}{997.5}\cos(t) \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $I(0) = 2$

Dus invullen geeft:
\begin{align}
 2 &= Ce^{-\frac{1}{20} \cdot 0}  -\dfrac{200}{997.5}\sin(0) + \dfrac{4000}{997.5}\cos(0) \\
 2 &= C \cdot 1  -\dfrac{200}{997.5} \cdot 0 + \dfrac{4000}{997.5} \cdot 1 \\
\end{align}

Hieruit volgt:
\begin{align}
 C &= 2 - \dfrac{4000}{997.5} \\
 C &= -2.01
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 I &=  -2.01e^{-\frac{1}{20}t}  -\dfrac{200}{997.5}\sin(t) + \dfrac{400}{997.5}\cos(t) 
\end{align}
````
`````

## Opgave 3

`````{admonition} Antwoord
:class: important, dropdown

Bepaal de stroomsterkte $I(t)$ in een RL-netwerk als de volgende parameters zijn gegeven:

$R = 100$$\Omega$, $L =15$H, $U(t)=200$V en $I(0)=0.0$A

````{dropdown} Uitwerking
Bepaal de stroomsterkte $I(t)$ in een RL-netwerk als de volgende parameters zijn gegeven:

$R = 100$$\Omega$, $L =15$H, $U(t)=200$V en $I(0)=0.0$A

Voor een RL-kring geldt:
  \begin{align}
   U(t) &= U_L + U_c   \\
     &= L \cdot \dfrac{dI}{dt} +  R \cdot I
  \end{align}

  De gegevens invullen in de DV geeft:
  \begin{align}
    U(t) &= 15 \cdot \dfrac{dI}{dt} + 100 \cdot  I\\
    200 &= 15 \cdot \dfrac{dI}{dt} + 100 \cdot  I
  \end{align}

De homogene D.V. wordt:
\begin{align}
 15\dfrac{dI}{dt} + 100I = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 I = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 15\lambda \cdot Ce^{\lambda t} + 100\cdot Ce^{\lambda t} &= 0 \\
 (15\lambda +100 )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 15\lambda + 100   &= 0  \\
 15\lambda   &= -100 \\
 \lambda   &= -\dfrac{100}{15} = -\dfrac{20}{3}
\end{align}

De waarde voor $\lambda$ invullen in de homogene oplossing geeft;
\begin{align}
 I_h = Ce^{-\dfrac{20}{3}t} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.

Als vorm voor de particuliere oplossing stel:
\begin{align}
 I_p &=  A \\
 I_p' &= 0
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 15 \cdot ( 0 ) +  100 ( A ) &=  200 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 100A &= 200 \\
 A &= \dfrac{200}{100} = 2
\end{align}

De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 I_p = 2
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 I &= I_h + I_p \\
 I &= Ce^{-\dfrac{20}{3}t}  + 2 \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $I(0) = 0$

Dus invullen geeft:
\begin{align}
 0 &= Ce^{-\dfrac{20}{3}t}   + 2 \\
 0 &= C \cdot 1  + 2 \\
 C &= - 2
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 I &=  - 2e^{-\dfrac{20}{3}t}  + 2
\end{align}
````
`````

## Opgave 4
`````{admonition} Antwoord
:class: dropdown

Bepaal de uiteindelijke valsnelheid van een voorwerp als deze vanaf een hoogte van 3000m naar beneden valt, als de volgende parameters zijn gegeven:

Het voorwerp met een massa van $m = 150 kg$ valt met een beginsnelheid van $0 m/s$. Neem aan dat de luchtweerstand $F_w$ evenredig is met de valsnelheid.  De evenredigheidsconstante $k=35 Ns/m$. Neem voor de gravitatieconstante $g=9.81$ $m/s^2$

````{dropdown} Uitwerking
Bepaal de uiteindelijke valsnelheid van een voorwerp als deze vanaf een hoogte van 3000m naar beneden valt, als de volgende parameters zijn gegeven:

Het voorwerp met een massa van $m = 150 kg$ valt met een beginsnelheid van $0 m/s$. Neem aan dat de luchtweerstand $F_w$ evenredig is met de valsnelheid.  De evenredigheidsconstante $k=35 Ns/m$. Neem voor de gravitatieconstante $g=9.81$ $m/s^2$

Volgens de tweede wet van Newton geldt:
\begin{align}
 F_{res} &= F_z - F_w\\
 m \cdot a &= m \cdot g - k \cdot v\\
 a &=   g - \dfrac{k}{m} \cdot v
\end{align}

Dit kan omgeschreven worden naar de volgende DV;
\begin{align}
 \dfrac{dV}{dt} &= g - \dfrac{k}{m} \cdot v \\
 \dfrac{dV}{dt} + \dfrac{k}{m} \cdot v &= g \\
 \dfrac{dV}{dt} + \dfrac{35}{150} \cdot v &= 9.81
\end{align}

De homogene D.V. wordt:
\begin{align}
  \dfrac{dV}{dt} + \dfrac{7}{30} \cdot v &= 0 \\
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 V_h = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda \cdot Ce^{\lambda t} +  \dfrac{7}{30}\cdot Ce^{\lambda t} &= 0 \\
 (\lambda +\dfrac{7}{30} )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 \lambda + \dfrac{7}{30}   &= 0  \\
 \lambda   &= -\dfrac{7}{30}
\end{align}

De waarde voor $\lambda$ invullen in de homogene oplossing geeft;
\begin{align}
 V_h = Ce^{-\dfrac{7}{30}t} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.

Als vorm voor de particuliere oplossing stel:
\begin{align}
 V_p &=  A \\
 V_p' &= 0
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 1 \cdot ( 0 ) +  \dfrac{7}{30} ( A ) &=  9.81 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 \dfrac{7}{30}A &= 9.81 \\
 A &= 9.81 \cdot \dfrac{30}{7} \\
 A &= 42.04
\end{align}

De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 V_p = 42.04
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 V &= V_h + V_p \\
 V &= Ce^{-\dfrac{7}{30}t} + 42.04 \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $V(0) = 0$

Dus invullen geeft:
\begin{align}
 0 &= Ce^{-\dfrac{7}{30} \cdot 0} + 42.04 \\
 0 &= C \cdot 1  + 42.04 \\
 C &= 0 - 42.04 \\
 C &= -42.04
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 V &=  -42.04e^{-\dfrac{7}{30}t} + 42.04
\end{align}

dus 42.04 m/s
````
`````

## Opgave 5

`````{admonition} Antwoord
:class: dropdown

Wat is de temperatuur van een warm bad na 15 minuten als de volgende parameters zijn gegeven:

Een bad met een temperatuur van 65$^{\circ}$ C staat in een ruimte gelegd waar de temperatuur 19$^{\circ}$ C is. Na 2 minuten is het bad afgekoelt tot een temperatuur van 55$^{\circ}$ C.

````{dropdown} Uitwerking

Wat is de temperatuur van een warm bad na 15 minuten als de volgende parameters zijn gegeven:

Een bad met een temperatuur van 65$^{\circ}$ C staat in een ruimte gelegd waar de temperatuur 19$^{\circ}$ C is. Na 2 minuten is het bad afgekoelt tot een temperatuur van 55$^{\circ}$ C.


Voor de afkoelingswet geldt:
\begin{align}
 \dfrac{dT}{dt} = -k(T-T_0)
\end{align}

Dit kan omgeschreven worden naar de volgende DV;
\begin{align}
 \dfrac{dT}{dt} &= -k(T-T_0) \\
 \dfrac{dT}{dt} + kT &= kT_0 \\
 \dfrac{dT}{dt} + kT &= 19k
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
 1 \cdot ( 0 ) +  k ( A ) &=  19k \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 kA &= 19k \\
 A &= 19
\end{align}

De waarde voor $A$ invullen in de particuliere oplossing geeft:
\begin{align}
 T_p = 19
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 T &= T_h + T_p \\
 T &= Ce^{-kt}  + 19 \qquad \text{met } C \in \mathbb{R}
\end{align}

De gegeven voorwaarden gebruiken om C te bepalen.  $T(0) = 65$

Dus invullen geeft:
\begin{align}
 65 &= Ce^{-k \cdot 0 }  + 19 \\
 65 &= C \cdot 1  + 19 \\
 C &= 46
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 T &=  46e^{-kt}  + 19
\end{align}

De gegeven voorwaarden gebruiken om k te bepalen.  $T(2) = 55$
Dus invullen geeft:
\begin{align}
 55 &=  46e^{-2k}  + 19 \\
 36 &=  46e^{-2k} \\
 \dfrac{36}{46} &= e^{-2k} \\
 \ln(\dfrac{9}{13} ) &= -2k \\
 k &= -\dfrac{1}{2} \cdot \ln(\dfrac{36}{46}) \\
 k &= 0.123
\end{align}

Dus k invullen in de totale oplossing geeft:
\begin{align}
 T &=  46e^{-0.123t}  + 19
\end{align}

Wat is de temperatuur na 15 minuten:
\begin{align}
  T &=  46e^{-0.123 \cdot 15}  + 19
  T &= 
\end{align}
````
`````

## Opgave 6

`````{admonition} Antwoord
:class: dropdown

Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 100$$\Omega$, $C =0.1$F, $U(t)=100$V en $I(0)=1.0$A

````{dropdown} Uitwerking
Bepaal de stroomsterkte $I(t)$ in een RC-netwerk als de volgende parameters zijn gegeven:

$R = 100$$\Omega$, $C =0.1$F, $U(t)=100$V en $I(0)=1.0$A

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
   \dfrac{dU(t)}{dt} &= 100 \cdot \dfrac{dI}{dt} + \dfrac{1}{0.1} \cdot  I\\
   \dfrac{d}{dt}(100 ) &= 100 \cdot \dfrac{dI}{dt} + \dfrac{1}{0.1} \cdot  I \\
   0 &= 100 \cdot \dfrac{dI}{dt} + 10 \cdot  I
  \end{align}

De homogene D.V. wordt:
\begin{align}
 100\dfrac{dI}{dt} + 10I = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 I_h = Ce^{\lambda t} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 100\lambda \cdot Ce^{\lambda t} + 10\cdot Ce^{\lambda t} &= 0 \\
 (100\lambda +10 )\cdot Ce^{\lambda t}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align}
 100\lambda + 10   &= 0  \\
 100\lambda   &= -10 \\
 \lambda   &= -\dfrac{10}{100} = -\dfrac{1}{21}
\end{align}

De waarde voor $\lambda$ invullen in de homogene oplossing geeft;
\begin{align}
 I_h = Ce^{-\frac{1}{10}t} \qquad \text{met } C \in \mathbb{R}
\end{align}


De gegeven voorwaarden gebruiken om C te bepalen.  $I(0) = 1$

Dus invullen geeft:
\begin{align}
 1 &= Ce^{-\frac{1}{10} \cdot 0}   \\
 2 &= C \cdot 1  \\
\end{align}

Hieruit volgt:
\begin{align}
 C &= 2  \\
 C &= 2
\end{align}

Dus C invullen in de totale oplossing geeft:
\begin{align}
 I &=  2e^{-\frac{1}{10}t}
\end{align}
````
`````