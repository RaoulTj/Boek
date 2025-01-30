# 2425 - WIS1-T3: Uitwerkingen

## Opgave 1 (4 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

 \begin{align*}
  S(t) &= b \cdot g^t \quad {\color{blue}   \text{(1p)}} \\
     &= 500 \cdot 1.05^{t/12} \quad {\color{blue}   \text{(1p)}} \\
     &= 500 \cdot 1.004^{t} \quad {\color{blue}   \text{(1p)}}
 \end{align*}
 \begin{align*}
  S(5) &= 500 \cdot 1.004^{5}\\
     &= 510.27  
 \end{align*}
 
 Dus na 5 maanden is er $510.27$ euro aan spaargeld. $\quad {\color{blue}   \text{(1p)}}$
 
 Of $510.08$ bij vroegtijdige afronding
````
`````



## Opgave 2 (9 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

Los de volgende vergelijking op:
\begin{align*}
  \log \left( \sqrt{x}+6 \right) &= \log \left (\dfrac{x}{4} \right )+ 2 \cdot \log \left(2 \right) \\
  \log \left( \sqrt{x}+6 \right) &= \log \left (\dfrac{x}{4} \right )+ \log \left(4 \right) \quad {\color{blue}   \text{(1p)}}\\
  \log \left( \sqrt{x}+6 \right) &= \log \left (x \right )\quad {\color{blue}   \text{(1p)}}\\
  \sqrt{x}+6 &= x \quad {\color{blue}   \text{(1p)}}\\
  \sqrt{x} &= x-6 \quad {\color{blue}   \text{(1p)}}\\
  x &= x^2 - 12x + 36 \quad {\color{blue}   \text{(1p)}}\\
  x^2 - 13x + 36 &= 0 \quad {\color{blue}   \text{(1p)}}
\end{align*}

Oplossen geeft:
\begin{align*}
  (x-9)&(x+4) =0 \quad {\color{blue}   \text{(1p)}}\\
  x=9 &\vee x=-4 \quad {\color{blue}   \text{(1p + 1p) }} \\
  \text{voldoet} &\vee \text{voldoet niet}  \quad {\color{blue}   \text{niet gecontroleerd is (-1p)}}
\end{align*}
````
`````

## Opgave 3 (2 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

Gegeven de functie:
\begin{align*}
  f(x) &= e^{\sin(x)}
\end{align*}

Bereken de afgeleiden van functie $f(x)$.

\begin{align*}
  \dfrac{df(x)}{dx} &= e^{\sin(x)} \cdot \cos(x) \quad {\color{blue}   \text{(1p + 1p)}}
\end{align*}
````
`````

## Opgave 4 (2 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

Gegeven de functie:
\begin{align*}
  g(x) &= \ln(3x)
\end{align*}
 
Bereken de afgeleiden van functie $g(x)$. 
 
\begin{align*}
  \dfrac{dg(x)}{dx} &= \dfrac{1}{3x} \cdot 3 \quad {\color{blue}   \text{(2p)}} \\
  \dfrac{dg(x)}{dx} &= \dfrac{1}{x} 
\end{align*}
````
`````

## Opgave 5 (6 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

 \begin{align*}
  q(x)=a \cdot \cos(cx)
 \end{align*}

 beginwaarde: $a=3$ $\quad {\color{blue}   \text{(1p)}}$
 periode: $\dfrac{2\pi}{c} = 8$ geeft $c = \dfrac{\pi}{4}$ $\quad {\color{blue}   \text{(1p)}}$

 \begin{align*}
  q(x)=3 \cdot \cos(\dfrac{\pi}{4}x)
 \end{align*}
 
 \begin{align*}
  F &=. \sum_{i=1}^{4} q(x_i) \cdot \Delta x\quad {\color{blue}   \text{(1p)}}\\ 
   &=( q(0)+q(\dfrac{1}{2})+q(1)+q(\dfrac{3}{2})) \cdot \dfrac{1}{2}\quad {\color{blue}   \text{(1p)}}\\
   &\approx (3 + 2.77+2.12+1.15) \cdot \dfrac{1}{2}\quad {\color{blue}   \text{(1p)}}\\
   &\approx 4.52 \quad {\color{blue}   \text{(1p)}}
 \end{align*}
````
`````

## Opgave 6 (5 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

 Gegeven de verdeelde belasting:
 \begin{align*}
  q(x) &= 5 \cdot \cos \left (\dfrac{\pi}{2}x \right)
 \end{align*}
 
 Bereken exact met behulp van een integraal het oppervlak onder de verdeelde belasting, $q(x)$.

 Beredeneer welke grootheid dit oppervlak voorstelt. 
 
 \begin{align*}
  F &= \int_{0}^{2} q(x) dx \quad {\color{blue}   \text{(1p)}} \\
    &= \int_{0}^{2} 5 \cdot \cos \left( \dfrac{\pi}{2}x \right) dx \quad {\color{blue}   \text{(1p)}} \\
    &= \left[ \dfrac{10}{\pi} \sin \left( \dfrac{\pi}{2}x \right) \right]^2_0 \quad {\color{blue}   \text{(1p)}}  \\
    &= 0 - 0  \\
    &= 0 \quad {\color{blue}   \text{(1p)}}
 \end{align*}

 Het oppervlak heeft de eenheid $N/m \cdot m = N$, dus kracht. \quad {\color{blue}   \text{(1p)}}

Gegeven de verdeelde belasting:
 \begin{align*}
  q(x) &= 3 \cdot \cos \left (\dfrac{\pi}{4}x \right)
 \end{align*}
 
Bereken exact met behulp van een integraal het oppervlak onder de verdeelde belasting, $q(x)$.

Beredeneer welke grootheid dit oppervlak voorstelt. 

 \begin{align*}
  F &= \int_{0}^{2} q(x) dx \quad {\color{blue}   \text{(1p)}} \\
    &= \int_{0}^{2} 3 \cdot \cos \left( \dfrac{\pi}{4}x \right) dx \quad {\color{blue}   \text{(1p)}} \\
    &= \left[ \dfrac{12}{\pi} \sin \left( \dfrac{\pi}{4}x \right) \right]^2_0 \quad {\color{blue}   \text{(1p)}}  \\
    &= \dfrac{12}{\pi} - 0  \\
    &= \dfrac{12}{\pi} \quad {\color{blue}   \text{(1p)}}
 \end{align*}
````
`````

## Opgave 7 (11 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

 Gegeven de functies:
 \begin{align*}
  f(x) &= 2 \cdot \cos(x) \qquad \text{ en} \\
  g(x) &= \sqrt{3}  
 \end{align*}
 
 Bereken exact de oppervlakte van het gebied tussen de grafieken van $f(x)$ en $g(x)$ tussen $0 \leq x \leq \pi$. 
 
 Snijpunt berekenen geeft:
 \begin{align*}
  f(x) &= g(x) \\
  2 \cdot \cos(x) &=  \sqrt{3} \quad {\color{blue}   \text{(1p)}} \\
  \cos(x) &=  \dfrac{1}{2}\sqrt{3} \quad {\color{blue}   \text{(1p)}}
 \end{align*}

 Dus,
 \begin{align*}
   x = \dfrac{\pi}{6} + k \cdot 2\pi \quad \vee \quad x = -\dfrac{\pi}{6} + k \cdot 2\pi  \quad {\color{blue}   \text{(1p + 1p)}}
 \end{align*}
 
 Bepaal oppervlakte:
 \begin{align*}
  Opp &= \int_{0}^{\frac{\pi}{6}} (f(x)-g(x)) dx + \int_{\frac{\pi}{6}}^{\pi} (g(x)-f(x)) dx \\
  &= \int_{0}^{\frac{\pi}{6}} (2 \cdot \cos(x)-\sqrt{3}) dx + \int_{\frac{\pi}{6}}^{\pi} (\sqrt{3}-2 \cdot \cos(x)) dx \quad {\color{blue}   \text{(1p + 1p)}}\\
  &= \left[ 2 \cdot \sin(x) -\sqrt{3}x \right]^{\frac{\pi}{6}}_{0} + \left[ \sqrt{3}x - 2 \cdot \sin(x)  \right]_{\frac{\pi}{6}}^{\pi}\quad {\color{blue}   \text{(1p+1p)}}\\
  &=(1-\dfrac{\sqrt{3}}{6}\pi) + (\sqrt{3}\pi -\dfrac{\sqrt{3}}{6}\pi +1)\quad {\color{blue}   \text{(1p+1p)}}\\
  &=2 + \sqrt{3}\pi \quad {\color{blue}   \text{(1p)}}
 \end{align*}
````
`````

## Opgave 8 (4 punten)

`````{admonition} Antwoord
:class: dropdown


````{dropdown} Uitwerking

Bereken de volgende onbepaalde integraal: 
\begin{align*}
  \int sin(x) \cdot \cos^3(x) dx
\end{align*}

Herschrijven tot;
\begin{align*}
  \int \cos^3(x) \cdot sin(x)  dx
\end{align*}

\begin{align*}
\dfrac{d \cos(x)}{dx} &= -\sin(x)\\
 d \cos(x)&=-\sin(x) dx\\
 -d \cos(x) &= \sin(x) dx
\end{align*}

Dus,
\begin{align*}
  &\int \cos^3(x) \cdot sin(x)  dx  \\
  &=\int -\cos^3(x) d \cos(x) \quad {\color{blue}   \text{(1p)}}
\end{align*}

Stel: $\cos(x)=u$
\begin{align*}
  &\int -u^3 du  \quad {\color{blue}   \text{(1p)}} \\
  &= -\dfrac{1}{4}u^4 + C \quad {\color{blue}   \text{(1p)}}\\
  &= -\dfrac{1}{4}\cos^4(x) + C \quad {\color{blue}   \text{(1p)}}
\end{align*}
````
`````