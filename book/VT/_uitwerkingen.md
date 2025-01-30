# Opgaven

## Opgave 1 (2 punten)


## Opgave 2 (3 punten)

## Opgave 3 (8 punten)

\begin{align*} 
	(x-5)\dfrac{dy}{dx} = 2(y-3) 
\end{align*} 
			
Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align*} 
	\frac{1}{(y-3)} \dfrac{dy}{dx} &= \dfrac{2}{(x-5)} \quad {\color{blue}   \text{(1p)}}
\end{align*} 

Aan beide kanten de integraal nemen naar $dx$.
\begin{align*} 
	\int \frac{1}{(y-3)} \dfrac{dy}{dx} dx &= \int \dfrac{2}{(x-5)}dx \quad {\color{blue}   \text{(1p)}}
\end{align*} 

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align*} 
	\int \frac{1}{(y-3)} dy &= \int \dfrac{2}{(x-5)}dx \quad {\color{blue}   \text{(1p)}}
\end{align*} 

De primitieven nemen van beide kanten.
\begin{align*} 	
	\ln|y-3| + C_1 &=  2\ln|x-5| + C_2 \quad {\color{blue}   \text{(2p)}} \\
	\ln|y-3|  &=  2\ln|x-5| + C_3\\
	e^{\ln|y-3|} &=  e^{2\ln|x-5| + c_3}\\
	|y-3| &=  e^{2\ln|x-5| + c_3}\\
	|y-3| &=  e^{\ln(x-5)^2 + c_3}\\
	|y-3| &=  e^{\ln(x-5)^2} \cdot  e^{c_3}\\
	|y-3| &=  (x-5)^2 \cdot  e^{c3}\\
	y-3 &=  \pm (x-5)^2 \cdot  e^{c3} \quad {\color{blue}   \text{(2p)}}
\end{align*} 

$y-3 = 0$ voldoet aan de dv, dus
\begin{align*}	
	y-3 &=  C\cdot  (x-5)^2  &\qquad \text{met } C \in \mathbb{R} \\
	y &=  C\cdot  (x-5)^2 + 3 &\qquad \text{met } C \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}

## Opgave 4 (6 punten)

\begin{align*} 
	\dfrac{dy}{dx} = \dfrac{4^x}{y^2}
\end{align*} 
			
Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align*} 
y^2 \dfrac{dy}{dx} &= 4^x \quad {\color{blue}   \text{(1p)}}
\end{align*} 

Aan beide kanten de integraal nemen naar $dx$.
\begin{align*} 
	\int y^2 \dfrac{dy}{dx} dx &= \int  4^x dx \quad {\color{blue}   \text{(1p)}}
\end{align*} 

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align*} 
	\int y^2 dy &= \int 4^x dx \quad {\color{blue}   \text{(1p)}}
\end{align*} 

De primitieven nemen van beide kanten.
\begin{align*} 	
	\dfrac{1}{3} y^3 + C_1 &=  \dfrac{1}{\ln(4)} 4^x + C_2 \quad {\color{blue}   \text{(2p)}} \\
	\dfrac{1}{3} y^3  &=  \dfrac{1}{\ln(4)} 4^x + C_3\\
	 y^3 &=  \dfrac{3}{\ln(4)} 4^x + C_3 \\
	  y &= \sqrt[3]{\dfrac{3}{\ln(4)} 4^x + C_3}  
\end{align*} 

dus,
\begin{align*} 	
	  y &= \sqrt[3]{\dfrac{3}{\ln(4)} 4^x + C} \qquad \text{met } C \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}\end{align*}

## Opgave 5 (11 punten)

	\begin{align*} 
		7\dfrac{dy}{dx} +6y &= 8\cos(3x)
	\end{align*}

	De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
	\begin{align*}
		y = y_h + y_p 
	\end{align*}

	De homogene D.V. wordt:
	\begin{align*} 
		7\dfrac{dy}{dx} + 6y = 0 \quad {\color{blue}   \text{(1p)}}
	\end{align*}

	Als oplossing voor de homogene D.V. stel:
	\begin{align*}
		y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
	\end{align*}

	Invullen in de D.V. geeft:
	\begin{align*} 
		7\lambda \cdot Ce^{\lambda x} - 6\cdot Ce^{\lambda x} &= 0 \\
		(7\lambda +6 )\cdot Ce^{\lambda x}  &= 0
	\end{align*}

	De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
	Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
	\begin{align*} 
		7\lambda +6   &= 0 \quad {\color{blue}   \text{(1p)}} \\	
		7\lambda   &= -6 \\
		\lambda   &= -\dfrac{6}{7} \quad {\color{blue}   \text{(1p)}}
	\end{align*}

	De waarde voor $\lambda =-\dfrac{6}{7}$ invullen in de homogene oplossing geeft;
	\begin{align*} 
		y_h = Ce^{-\frac{6}{7}x} \qquad \text{met } C \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}
	\end{align*}

	Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
	Als vorm voor de particuliere oplossing stel:
	\begin{align*}
		y_p &=  C_1\sin(3x) + C_2\cos(3x) \quad {\color{blue}   \text{(1p)}}\\
		y'_p &= 3 C_1\cos(3x) - 3C_2\sin(3x) \\
	\end{align*}

	Invullen in de D.V. geeft:
	\begin{align*} 
		7 \cdot (3C_1\cos(3x) - 3C_2\sin(3x)) + 6\cdot  (C_1\sin(3x) + C_2\cos(3x)) &=  8\cos(3x) \\
		21C_1\cos(3x) - 21C_2\sin(3x)  + 6C_1\sin(3x) +6C_2\cos(3x)  &=  8\cos(3x) \\
		(6C_1-21C_2)\sin(2x) + (21C_1+6C_2)\cos(2x) &= 8\cos(3x) \quad {\color{blue}   \text{(1p)}}
	\end{align*}

	De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
	\begin{align*} 
		6C_1-21C_2 &= 0 \\
	 	21C_1+6C_2 &= 8  \quad {\color{blue}   \text{(1p) voor beide samen}} \\	
	\end{align*}

	Hieruit volgt:
	\begin{align*} 
		6C_1 &= 21C_2 \\
		C_1 &= \dfrac{21}{6}C_2
	\end{align*}

	$C_1$ invullen geeft:
	\begin{align*} 
		21 \cdot \dfrac{21}{6}C_2 +6C_2 &= 8\\
		\dfrac{441}{6}C_2 +\dfrac{36}{6}C_2  &= 8\\
		\dfrac{477}{6}C_2 &= 8\\
	 	C_2 &= \dfrac{48}{477} = \dfrac{16}{159}  \quad {\color{blue}   \text{(1p)}}
	\end{align*}

	$C_2 $ invullen geeft:
	\begin{align*} 
		C_1 &= \dfrac{21}{6}C_2  \\
		C_1 &= \dfrac{21}{6} \cdot \dfrac{48}{477} \\
		C_1 &= \dfrac{168}{477} = \dfrac{56}{159} \quad {\color{blue}   \text{(1p)}}
	\end{align*}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align*}
	y_p = \dfrac{56}{159}\sin(3x) + \dfrac{16}{159}\cos(3x) \quad {\color{blue}   \text{(1p)}}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align*}
	y &= y_h + y_p \\
	y &= Ce^{-\frac{6}{7}x} + \dfrac{56}{159}\sin(3x) + \dfrac{16}{159}\cos(3x)\qquad \text{met } C \in \mathbb{R}   \quad {\color{blue}   \text{(1p) alleen als beide goed}}
\end{align*}

## Opgave 6 (11 punten)

\begin{align*} 
	2\dfrac{d^2y}{dx^2} +10y = e^{4x}+1
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align*}
	y = y_h + y_p 
\end{align*}

De homogene D.V. wordt:
\begin{align*} 
	2\dfrac{d^2y}{dx^2} +10y =  0 \quad {\color{blue}   \text{(1p)}}
\end{align*}

Als oplossing voor de homogene D.V. stel:
\begin{align*}
	y_h = Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
\end{align*}

Dus,
\begin{align*}
	 \dfrac{dy_h}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
	 \dfrac{d^2y_h}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R} 
\end{align*}


Invullen in de D.V. geeft:
\begin{align*} 
	2(\lambda^2 Ce^{\lambda x}) +10(Ce^{\lambda x}) &= 0 \\
	(2\lambda^2 +10 )\cdot Ce^{\lambda x}  &= 0
\end{align*}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align*} 
	2\lambda^2 +10 &= 0 \quad {\color{blue}   \text{(1p)}}
\end{align*}

Dus de discriminant is, 
\begin{align*}  
	D = (0)^2 - 4 \cdot 2 \cdot 10 = - 80 = -80	
\end{align*}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align*}  
	 \lambda_{1,2} &= \dfrac{0 \pm i\sqrt{80}}{2 \cdot 2}\\
	 \lambda_{1,2} &= \dfrac{0 \pm 4\sqrt{5}i}{4}\\
	 \lambda_{1,2} &= 0 \pm \sqrt{5}\cdot i \quad {\color{blue}   \text{(1p)}}
\end{align*}

Hieruit volgt dat $p=0$ en $q=\sqrt{5}$

De waarde voor $p$ en $q$ invullen in de algemene oplossing geeft;
\begin{align*} 
	y_h &= e^{px}(C_1\cos(qx) + C_2\sin(qx)) \\
	y_h &= e^{0x}(C_1\cos(\sqrt{5}x) + C_2\sin ( \sqrt{5}x ) ) \\ 
	y_h &= C_1\cos(\sqrt{5}x) + C_2\sin ( \sqrt{5}x ) \qquad  \text{met } C_{1,2} \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}
\end{align*}


Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align*}
	y_p =  Ae^{4x} + B  \quad {\color{blue}   \text{(1p)}}
\end{align*}

Dus,
\begin{align*}
	 \dfrac{dy_p}{dx} &= 4Ae^{4x}  \\
	 \dfrac{d^2y_p}{dx^2} &= 16Ae^{4x} \\ 
\end{align*}

Invullen in de D.V. geeft:
\begin{align*} 
	2 \cdot (16Ae^{4x})  + 10 \cdot (Ae^{4x} + B)  &= e^{4x} + 1\\
	32Ae^{x}  + 10Ae^{x} + 10B   &= e^{4x} +1 \\
	42Ae^{x} +10B  &= e^{4x} +1 \quad {\color{blue}   \text{(1p)}}
\end{align*}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align*} 
	52A &= 1 \\
	10B &= 1 \quad {\color{blue}   \text{(1p) voor beide samen}}
\end{align*}

Hieruit volgt:
\begin{align*} 
	52A &= 1 \\
	A &= \dfrac{1}{42} \quad {\color{blue}   \text{(1p)}}
\end{align*}

\begin{align*} 
	10B &= 1 \\
	B &= \dfrac{1}{10} \quad {\color{blue}   \text{(1p)}}
\end{align*}

De waardes voor $C_1$ en $C_2$  invullen in de particuliere oplossing geeft:
\begin{align*}
		y_p = \dfrac{1}{42}e^{4x} +  \dfrac{1}{10} \quad {\color{blue}   \text{(1p)}}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align*}
	y &= y_h + y_p \\
	y &=  C_1\cos(\sqrt{5}x) + C_2\sin ( \sqrt{5}x ) + \dfrac{1}{42}e^{4x} +  \dfrac{1}{10}  \qquad \text{met } C_{1,2} \in \mathbb{R}  \quad {\color{blue}   \text{(1p) alleen als beide goed}}
\end{align*}

## Opgave 7 (17 punten)

		Voor een RL-kring geldt:
		\begin{align*}
			U(t) &= U_L + U_r  \quad {\color{blue}   \text{(1p)}} \\
				 &= L \cdot \dfrac{dI}{dt} + R \cdot I  \quad {\color{blue}   \text{(1p)}}
		\end{align*}
				
		De gegevens invullen in de DV geeft:
		\begin{align*}
			U(t) &= 2 \cdot \dfrac{dI}{dt} + 20 \cdot  I\\
			30 \sin(t) &= 2 \cdot \dfrac{dI}{dt} + 20 \cdot  I \\
			30 \sin(t) &= 2 \cdot \dfrac{dI}{dt} + 20 \cdot  I \quad {\color{blue}   \text{(1p)}}
		\end{align*}	
De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align*}
	I = I_h + I_p 
\end{align*}

De homogene D.V. wordt:
\begin{align*} 
	2\dfrac{dI}{dt} + 20I = 0 \quad {\color{blue}   \text{(1p)}}
\end{align*}

Als oplossing voor de homogene D.V. stel:
\begin{align*}
	I_h = Ce^{\lambda t} \text{ met } C \in \mathbb{R} 
\end{align*}

Invullen in de D.V. geeft:
\begin{align*} 
	2\lambda \cdot Ce^{\lambda t} + 20\cdot Ce^{\lambda t} &= 0 \\
	(2\lambda +20 )\cdot Ce^{\lambda t}  &= 0
\end{align*}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda t} \neq 0 $ dus,
\begin{align*} 
	2\lambda +20   &= 0 \quad {\color{blue}   \text{(1p)}} \\	
	2\lambda   &= -20 \\
	\lambda   &= -10 \quad {\color{blue}   \text{(1p)}}
\end{align*}

De waarde voor $\lambda =-10$ invullen in de homogene oplossing geeft;
\begin{align*} 
	I_h = Ce^{-10t} \qquad \text{met } C \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}
\end{align*}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.  
Als vorm voor de particuliere oplossing stel:
\begin{align*}
	I_p &=  C_1\cos(t) + C_2\sin(t) \quad {\color{blue}   \text{(1p)}}\\
	I'_p &= -C_1\sin(t) + C_2\cos(t) \\
\end{align*}

Invullen in de D.V. geeft:
\begin{align*} 
	2 \cdot (-C_1\sin(t) + C_2\cos(t)) +  20 (C_1 \cos(t)+C_2 \sin(t)) &=  30\sin(t) \\
	(20C_1+2C_2)\cos(t) + (-2C_1+20C_2)\sin(t) &= 30\sin(t) \quad {\color{blue}   \text{(1p)}}
\end{align*}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align*} 
	20C_1+2C_2 &= 0 \\
	-2C_1+20C_2 &= 30  \quad {\color{blue}   \text{(1p) voor beide samen}} \\	
\end{align*}

Hieruit volgt:
\begin{align*} 
	2C_2 &= -20C_1 \\
	C_2 &= -10C_1
\end{align*}

$C_2 $ invullen geeft:
\begin{align*} 
	-2C_1 + 20 \cdot (-10C_1) &= 30\\
	-2C_1 -200C_1 &= 30\\
	 C_1 &= -\dfrac{30}{202} = -\dfrac{15}{101} \quad {\color{blue}   \text{(1p)}}
\end{align*}

$C_1 $ invullen geeft:
\begin{align*} 
	C_2 &= -10C_1  \\
	C_2 &= -10 \cdot -\dfrac{30}{202} \\
	C_2 &= \dfrac{300}{202} =  \dfrac{150}{101} \quad {\color{blue}   \text{(1p)}}
\end{align*}

De waardes voor $C_1$, $C_2$  invullen in de particuliere oplossing geeft:
\begin{align*}
	I_p = \dfrac{150}{101}\sin(t) - \dfrac{15}{101}\cos(t) \quad {\color{blue}   \text{(1p)}}
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing. 
\begin{align*}
	I &= I_h + I_p \\
	I &= Ce^{-10t} + \dfrac{150}{101}\sin(t) - \dfrac{15}{101}\cos(t) \qquad \text{met } C \in \mathbb{R}   \quad {\color{blue}   \text{(1p)}}
\end{align*}

De gegeven voorwaarden gebruiken om C te bepalen.  $I(0) = 2$

Dus invullen geeft:
\begin{align*}
	2 &= Ce^{- \cdot 0} +\dfrac{150}{101}\sin(0) - \dfrac{15}{101}\cos(0)  \quad {\color{blue}   \text{(1p)}}\\
	2 &= C \cdot 1 +\dfrac{150}{101}\cdot 0 - \dfrac{15}{101}\cdot 1	
\end{align*}

Hieruit volgt:
\begin{align*}
	C &= 2 + \dfrac{15}{101} \\
	C &= \dfrac{217}{101}  \quad {\color{blue}   \text{(1p)}}
\end{align*}

Dus C invullen in de totale oplossing geeft:
\begin{align*}
	I &= \dfrac{217}{101}e^{-10t} + \dfrac{150}{101}\sin(t) - \dfrac{15}{101}\cos(t)  \quad {\color{blue}   \text{(1p) goed of fout}}
\end{align*}


## Opgave 8 (10 punten)

Voor een massa-veer-systeem geldt:
\begin{align*} 
F_{res} &= - F_v \quad {\color{blue}   \text{(1p)}}
\\
F_{res}	&=  - c\cdot u\\
m \cdot a &= - c\cdot u \\
m \cdot \dfrac{d^2 u}{dt^2} &= - c\cdot u\quad {\color{blue}   \text{(1p)}}
\end{align*}

De gegevens invullen in de D.V. geeft:
\begin{align*} 
m \cdot \dfrac{d^2 u}{dt^2} &=  - c\cdot u \\
10 \cdot \dfrac{d^2 u}{dt^2} &=  -640 \cdot u
\end{align*}

De homogene D.V. wordt:
\begin{align*} 
	10\dfrac{d^2u}{dt^2} +640u =  0 \quad {\color{blue}   \text{(1p)}} 
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
	10(\lambda^2 Ce^{\lambda x}) + 640(Ce^{\lambda x}) &= 0 \\
	(10\lambda^2+640 )\cdot Ce^{\lambda x}  &= 0
\end{align*}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \\
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align*} 
	10\lambda^2 + 640 &= 0 \quad {\color{blue}   \text{(1p)}}
\end{align*}

Dus de discriminant is, 
\begin{align*}  
	D = (0)^2 - 4 \cdot 10 \cdot 640 = -25600 	
\end{align*}

De oplossingen van de karakteristieke vergelijking zijn:
\begin{align*}  
	 \lambda_{1,2} &= \dfrac{0 \pm i\sqrt{25600}}{2 \cdot 10}\\
	 \lambda_{1,2} &= \dfrac{0 \pm 160i}{2 \cdot 10}\\
	 \lambda_{1,2} &= -0 \pm 8 \cdot i \quad {\color{blue}   \text{(1p)}}
\end{align*}

Hieruit volgt dat $p=0$ en $q=8$

De waarde voor $p$ en $q$ invullen in de homogene oplossing geeft;
\begin{align*} 
	u_h &= e^{px}(C_1\cos(qt) + C_2\sin(qt)) \\
	u_h &= e^{0\cdot x}(C_1\cos(8t) + C_2\sin (8t ) ) \\
	u_h &= C_1\cos(8t) + C_2\sin (8t )  \qquad  \text{met } C_{1,2} \in \mathbb{R} \quad {\color{blue}   \text{(1p)}}
\end{align*}

De gegeven voorwaarden gebruiken om $C_1$ en $C_2$ te bepalen, $u(0) = 0.05$ en $u'(0) = 0$\\
\\

Dus invullen geeft:
\begin{align*}
	u &=  C_1\cos(8t) + C_2\sin (8t )  \\
	0.05 &=  C_1\cos(8 \cdot 0 ) + C_2\sin (8 \cdot 0) \\
	0.05 &= C_1 \cdot 1 + 0	
\end{align*}

Hieruit volgt:
\begin{align*}
	C_1 = 0.05 \quad {\color{blue}   \text{(1p)}}
\end{align*}

$C_1 $ invullen geeft:
\begin{align*}
	u' &= -8 C_1\sin(8t) + 8 C_2\cos (8t )  \quad {\color{blue}   \text{(1p)}} \\
	0 &= -8 C_1\sin(8 \cdot 0) + 8 C_2\cos (8 \cdot 0 )   \\
	0 &= 0 + 8 \cdot C_2 \cdot 1	
\end{align*}

Hieruit volgt:
\begin{align*}
	C_2 &=  0  \quad {\color{blue}   \text{(1p)}}
\end{align*}

Dus $C_1$ en $C_2$ invullen in de totale oplossing geeft:
\begin{align*}
	u &=  C_1\cos(8t) + C_2\sin (8t ) \\
	u &= 0.05 \cos(8t)  \quad {\color{blue}   \text{(1p)}}
\end{align*}

