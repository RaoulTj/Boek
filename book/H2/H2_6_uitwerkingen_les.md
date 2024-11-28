# 2.6 Uitwerkingen les 2

## Opgave 1
\begin{align*}
 \dfrac{dy}{dx} = \dfrac{y^2}{x-3}
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y^2}\dfrac{dy}{dx} &= \dfrac{1}{x-3}
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y^2}\dfrac{dy}{dx} dx &= \int \dfrac{1}{x-3} dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int \dfrac{1}{y^2} dy &= \int \dfrac{1}{x-3} dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 -\dfrac{1}{y}  + C_1 &=  \ln|x-3|  + C_2\\
 -\dfrac{1}{y}  &=  \ln|x-3| + C_3\\
 y &=  \dfrac{-1}{\ln|x-3|  + C_3}
\end{align}

dus,
\begin{align}
 y &=  \dfrac{-1}{\ln|x-3|  + C} \qquad \text{met } C \in \mathbb{R}
\end{align}

## Opgave 2

\begin{align*}
 \dfrac{dy}{dx} = y^3
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y^3}\dfrac{dy}{dx} &= 1
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y^3}\dfrac{dy}{dx} dx &= \int 1 dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int \dfrac{1}{y^3} dy &= \int 1 dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align
 -\dfrac{1}{2}\dfrac{1}{y^2}  + C_1 &=  x  + C_2\\
 -\dfrac{1}{2}\dfrac{1}{y^2}  &=  x  + C_3\\
  \dfrac{1}{y^2}  &=  -2x  + C_4\\
  y^2  &=  \dfrac{1}{-2x  + C_4}\\
  y  &= \pm \sqrt{\dfrac{1}{-2x  + C_4}}
\end{align}

dus,
\begin{align}
 y  &= \pm \sqrt{\dfrac{1}{-2x  + C}} \qquad \text{met } C \in \mathbb{R}
\end{align}

## Opgave 3

\begin{align*}
 \dfrac{dy}{dx} = 3x^2e^{-y}
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{e^{-y}}\dfrac{dy}{dx} &= 3x^2\\
 e^{y}\dfrac{dy}{dx} &= 3x^2
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int e^{y}\dfrac{dy}{dx} dx &= \int 3x^2 dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int  e^{y} dy &= \int 3x^2 dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 e^{y} + C_1 &=  x^3  + C_2\\
 e^{y} &=  x^3  + C_3\\
 \ln(e^{y}) &= \ln( x^3  + C_3)\\
 y &= \ln( x^3  + C_3)
\end{align}

dus,
\begin{align}
 y &= \ln( x^3  + C) \qquad \text{met } C \in \mathbb{R}
\end{align}

## Opgave 4

\begin{align*}
 ydx + xdy = 0
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 xdy &= -ydx\\
 \dfrac{-1}{y}dy &= \dfrac{1}{x}dx
\end{align}

Aan beide kanten de integraal nemen.
\begin{align}
 \int \dfrac{-1}{y}dy &= \int \dfrac{1}{x}dx
\end{align}

%De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
%\begin{align}
% \int  e^{y} dy &= \int 3x^2 dx
%\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 -\ln|y| + C_1 &=  \ln|x|  + C_2\\
 -\ln|y| &=  \ln|x|  + C_3\\
 \ln|y| &=  -\ln|x|  + C_3\\
 |y| &= e^{-\ln|x|  + C_3}\\
 |y| &= e^{-\ln|x|} \cdot   e^{C_3}\\
 |y| &= e^{\ln|x^{-1}|} \cdot   e^{C_3}\\
 y &= \pm e^{\ln|x^{-1}|} \cdot   e^{C_3}\\
 y &= \pm \dfrac{1}{x} \cdot   e^{C_3}\\
\end{align}

y=0 voldoet aan de dv dus,
\begin{align}
 y &= C \cdot \dfrac{1}{x}  \qquad \text{met } C \in \mathbb{R}
\end{align}

## Opgave 5

\begin{align*}
 \dfrac{dy}{dx} = 6x^5y+y\\
 \dfrac{dy}{dx} = (6x^5+1)y\\
\end{align*}

Alle variabelen met een $y$ naar links en variabelen met een $x$ naar rechts.
\begin{align}
 \dfrac{1}{y}\dfrac{dy}{dx} &= 6x^5+1\\
\end{align}

Aan beide kanten de integraal nemen naar $dx$.
\begin{align}
 \int \dfrac{1}{y}\dfrac{dy}{dx} dx &= \int  (6x^5+1) dx
\end{align}

De integraal $\dfrac{dy}{dx}dx$ vereenvoudigen tot $dy$.
\begin{align}
 \int  \dfrac{1}{y} dy &= \int (6x^5+1) dx
\end{align}

De primitieven nemen van beide kanten.
\begin{align}
 \ln|y| + C_1 &=  x^6 + x  + C_2\\
 \ln|y|  &=  x^6 + x  + C_3\\
 e^{\ln|y|}  &=  e^{x^6 + x  + C_3}\\
 |y|  &=  e^{x^6 + x  + C_3}\\
 |y|  &=  e^{x^6 + x} \cdot e^{C_3}\\
 y  &=  \pm e^{x^6 + x} \cdot e^{C_3}
\end{align}

y=0 voldoet aan de dv dus,
\begin{align}
  y  &=  C \cdot e^{x^6 + x}  \qquad \text{met } C \in \mathbb{R}
\end{align}
