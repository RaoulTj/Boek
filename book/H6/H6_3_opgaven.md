---
title: Opgave 4.1a
substitutions:
  waarde: "18"
---

# 6.3 Opgaven

## Opgave 6.1a

Bepaal de stroomsterkte $I(t)$ in een RLC-netwerk als de volgende parameters zijn gegeven:

$R = 20$$\Omega$, $L=1$H, $$C =0.1$F, $U(t)=100$V, $I(0)=0.0$A en $I'(0)=1.0$A/s

## Opgave 6.1b

Bepaal de stroomsterkte $I(t)$ in een RLC-netwerk als de volgende parameters zijn gegeven:

$R = 50$$\Omega$, $L=5$H, $$C =2$F, $U(t)=24 \cos(t)$V, $I(0)=0.5$A en $I'(0)=1.0$A/s




# 5.4 Uitwerkingen

{{ waarde }}

## Opgaven 4.1a

```{math}
\frac{{d^2y}}{{dx^2}} + 3\frac{{dy}}{{dx}} - {{ waarde }}y = 0
```

```{admonition} Uitwerkingen
:class: dropdown

\begin{align*}
 \dfrac{d^2y}{dx^2} + 3\dfrac{dy}{dx} - {{waarde}}y = 0
\end{align*}

Als algemene oplossing voor de D.V. stel:
\begin{align}
 y = Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Dus,
\begin{align}
  \dfrac{dy}{dx} &= \lambda Ce^{\lambda x} \text{ met } C \in \mathbb{R} \\
  \dfrac{d^2y}{dx^2} &= \lambda^2 Ce^{\lambda x} \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda^2 Ce^{\lambda x} + 3(\lambda Ce^{\lambda x}) - 18(Ce^{\lambda x}) &= 0 \\
 (\lambda^2 +3\lambda-18 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $ dus,
\begin{align}
 \lambda^2 +3\lambda-18 &= 0
\end{align}

De D is groter dan 0 dus,
\begin{align}
 (\lambda +6)(\lambda -3) &= 0
\end{align}

dus $\lambda_1 = -6$ en $\lambda_2 = 3$

De waarde voor $\lambda$ invullen in de algemene oplossing geeft;
\begin{align*}
 y = C_1e^{\lambda_1 x} + C_2e^{\lambda_2 x} \qquad \text{met } C \in \mathbb{R}
\end{align*}

\begin{align}
 y = C_1e^{-6 x} + C_2e^{3 x} \qquad \text{met } C \in \mathbb{R}
\end{align}
```
