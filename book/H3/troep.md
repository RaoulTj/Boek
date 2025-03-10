---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# 3.2 Inhomogene vergelijkingen

```{admonition} Theorie
:class: tip, dropdown
De volgende stap is het oplossen van inhomogene eerste orde lineaire differentiaalvergelijkingen met constante coëfficiënten:

\begin{align*}
 \dfrac{dy}{dx} + ay = f(x) dx
\end{align*}

Belangrijk hierbij is realiseren dat bij een oplossing van de inhomogene vergelijking altijd een oplossing van de homogene vergelijking opgeteld kan worden. De algemene oplossing van de inhomogene vergelijking kan dus gevonden worden door de volgende stappen te doorlopen:

1. Vind de algemene oplossing van de corresponderende homogene vergelijking; $y_h$.
2. Vind een oplossing van de inhomogene vergelijking; $y_p$. Dit wordt een particuliere oplossing genoemd.
3. De algemene oplossing wordt gegeven door $y = y_h + y_p$.

Het vinden van een particuliere oplossing is de grootste uitdaging bij het oplossen van inhomogene eerste orde lineaire differentiaalvergelijkingen met constante coëfficiënten. De vorm van het rechterlid van de vergelijking $f(x)$ is een belangrijke aanwijzing voor de vorm van de particuliere oplossing. In het algemeen worden vormen gekozen die in het rechterlid voorkomen en hun afgeleiden. Door invullen in de differentiaalvergelijking worden de coëfficiënten bepaald. Deze methode wordt ook wel de methode van onbepaalde coëfficiënten genoemd. Een aantal concrete richtlijnen voor de particuliere oplossing zijn:

- Als $f(x)$ een polynoom is, dat wil zeggen $f(x) = b_nx^n + b_{n−1}x^{n−1} + ...+b_1x+b_0$, kies dan $y_p =A_nx^n+B_{n−1}x^{n−1}+...+Dx+E$.

- Als $f(x) = b1 \cos(ωx)+b2 \sin(ωx)$, kies dan $y_p = A \cos(ωx)+  B \sin(ωx)$.

- Als $f(x) = be^{kx}$, en dit geen oplossing is van de homogene vergelijking, neem dan $y_p = Ae^{kx}$. Als $e^{kx}$ een oplossing is van de homogene vergelijking neem dan $y_p = Axe^{kx}$.
```

## 3.2.1 $f(x) = ax^2 + bx + c $

```{admonition} Voorbeeld 1: Polynoom
:class: dropdown

Vind de algemene oplossing van de volgende differentiaalvergelijking:

\begin{align*}
 \dfrac{dy}{dx} + 2y = 3x
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 \dfrac{dy}{dx} + 2y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 \lambda \cdot Ce^{\lambda x} +2 \cdot Ce^{\lambda x} &= 0 \\
 (\lambda +2 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 \lambda +2   &= 0 \\
 \lambda   &= -2
\end{align}

De waarde voor $\lambda =-2$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{-2x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ax + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 A + 2 \cdot (Ax + B) &= 3x \\
 A + 2Ax + 2B &= 3x \\
  2Ax + A+2B  &= 3x
\end{align}

De co\"effici\"enten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
 2A &= 3 \\
 A+2B &= 0 \\
\end{align}

Hieruit volgt:
\begin{align}
 A = \dfrac{3}{2}
\end{align}

$A$ invullen geeft:
\begin{align}
 \cdot \dfrac{3}{2} + 2B &= 0\\
  2B &= -\dfrac{3}{2}\\
  B &= -\dfrac{3}{4}
\end{align}

De waardes voor $A$, $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = \dfrac{3}{2}x - \dfrac{3}{4}x
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{-2x} + \dfrac{3}{2}x - \dfrac{3}{4}x  \qquad \text{met } C \in \mathbb{R}
\end{align}
```



## 3.2.2 $f(x) = ae^{bx}$

```{admonition} Voorbeeld 2: Karakteristieke vergelijking
:class: dropdown

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - 6y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \lambda \cdot Ce^{\lambda x} -6 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda -6 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 2\lambda -6   &= 0 \\
 2\lambda   &= 6\\
 \lambda   &= 3\\
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{2x} + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot 2Ae^{2x}   - 6 \cdot (Ae^{2x} +B) = e^{2x} + 2 \\
 4Ae^{2x}   - 6Ae^{2x} - 6B = e^{2x} + 2 \\
 - 2Ae^{2x} - 6B = e^{2x} + 2 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  -2A &= 1 \\
  -6B &= 2
\end{align}

Hieruit volgt:
\begin{align}
 A &= -\dfrac{1}{2}\\
 B &= -\dfrac{2}{6} = -\dfrac{1}{3}
\end{align}

De waarde voor $A$ en $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x}  -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}  \qquad \text{met } C \in \mathbb{R}
\end{align}
```

````{admonition} Oefening 1
:class: important, dropdown

Bepaal de oplossing van de volgende differentiaalvergelijking:

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - 6y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \lambda \cdot Ce^{\lambda x} -6 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda -6 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 2\lambda -6   &= 0 \\
 2\lambda   &= 6\\
 \lambda   &= 3\\
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{2x} + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot 2Ae^{2x}   - 6 \cdot (Ae^{2x} +B) = e^{2x} + 2 \\
 4Ae^{2x}   - 6Ae^{2x} - 6B = e^{2x} + 2 \\
 - 2Ae^{2x} - 6B = e^{2x} + 2 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  -2A &= 1 \\
  -6B &= 2
\end{align}

Hieruit volgt:
\begin{align}
 A &= -\dfrac{1}{2}\\
 B &= -\dfrac{2}{6} = -\dfrac{1}{3}
\end{align}

De waarde voor $A$ en $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x}  -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}  \qquad \text{met } C \in \mathbb{R}
\end{align}
```
```` 

````{admonition} Oefening 2
:class: important, dropdown

Bepaal de oplossing van de volgende differentiaalvergelijking:

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - 6y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \lambda \cdot Ce^{\lambda x} -6 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda -6 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 2\lambda -6   &= 0 \\
 2\lambda   &= 6\\
 \lambda   &= 3\\
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{2x} + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot 2Ae^{2x}   - 6 \cdot (Ae^{2x} +B) = e^{2x} + 2 \\
 4Ae^{2x}   - 6Ae^{2x} - 6B = e^{2x} + 2 \\
 - 2Ae^{2x} - 6B = e^{2x} + 2 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  -2A &= 1 \\
  -6B &= 2
\end{align}

Hieruit volgt:
\begin{align}
 A &= -\dfrac{1}{2}\\
 B &= -\dfrac{2}{6} = -\dfrac{1}{3}
\end{align}

De waarde voor $A$ en $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x}  -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}  \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

## 3.2.3 $f(x) = a\sin(x) + b\cos(x)$

## 3.2.4 Combinaties

````{admonition} Oefening 1
:class: important, dropdown

Bepaal de oplossing van de volgende differentiaalvergelijking:

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - 6y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \lambda \cdot Ce^{\lambda x} -6 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda -6 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 2\lambda -6   &= 0 \\
 2\lambda   &= 6\\
 \lambda   &= 3\\
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{2x} + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot 2Ae^{2x}   - 6 \cdot (Ae^{2x} +B) = e^{2x} + 2 \\
 4Ae^{2x}   - 6Ae^{2x} - 6B = e^{2x} + 2 \\
 - 2Ae^{2x} - 6B = e^{2x} + 2 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  -2A &= 1 \\
  -6B &= 2
\end{align}

Hieruit volgt:
\begin{align}
 A &= -\dfrac{1}{2}\\
 B &= -\dfrac{2}{6} = -\dfrac{1}{3}
\end{align}

De waarde voor $A$ en $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x}  -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}  \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````

````{admonition} Oefening 1
:class: important, dropdown

Bepaal de oplossing van de volgende differentiaalvergelijking:

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

```{dropdown} Uitwerking

\begin{align*}
 2\dfrac{dy}{dx} - 6y &= e^{2x} + 2\\
\end{align*}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y = y_h + y_p
\end{align}

De homogene D.V. wordt:
\begin{align}
 2\dfrac{dy}{dx} - 6y = 0
\end{align}

Als oplossing voor de homogene D.V. stel:
\begin{align}
 y_h = Ce^{\lambda x} \qquad \text{ met } C \in \mathbb{R}
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \lambda \cdot Ce^{\lambda x} -6 \cdot Ce^{\lambda x} &= 0 \\
 (2\lambda -6 )\cdot Ce^{\lambda x}  &= 0
\end{align}

De vergelijking moet gelden voor alle waardes van C dus ook voor $C \neq 0$. \
Verder geldt dat $e^{\lambda x} \neq 0 $.

Dus de karakteristieke vergelijking wordt gegeven door:
\begin{align}
 2\lambda -6   &= 0 \\
 2\lambda   &= 6\\
 \lambda   &= 3\\
\end{align}

De waarde voor $\lambda =3$ invullen in de homogene oplossing geeft;
\begin{align}
 y_h = Ce^{3x} \qquad \text{met } C \in \mathbb{R}
\end{align}

Kies als vorm voor de particuliere oplossing een vorm die gelijk is aan het rechterlid van de D.V.
Als vorm voor de particuliere oplossing stel:
\begin{align}
 y_p = Ae^{2x} + B
\end{align}

Invullen in de D.V. geeft:
\begin{align}
 2 \cdot 2Ae^{2x}   - 6 \cdot (Ae^{2x} +B) = e^{2x} + 2 \\
 4Ae^{2x}   - 6Ae^{2x} - 6B = e^{2x} + 2 \\
 - 2Ae^{2x} - 6B = e^{2x} + 2 \\
\end{align}

De coëfficiënten moeten links en rechts gelijk zijn dus volgt:
\begin{align}
  -2A &= 1 \\
  -6B &= 2
\end{align}

Hieruit volgt:
\begin{align}
 A &= -\dfrac{1}{2}\\
 B &= -\dfrac{2}{6} = -\dfrac{1}{3}
\end{align}

De waarde voor $A$ en $B$ invullen in de particuliere oplossing geeft:
\begin{align}
 y_p = -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}
\end{align}

De algemene oplossing bestaat uit een optelling van de homogene oplossing en de particuliere oplossing.
\begin{align}
 y &= y_h + y_p \\
 y &= Ce^{3x}  -\dfrac{1}{2} e^{2x} - \dfrac{1}{3}  \qquad \text{met } C \in \mathbb{R}
\end{align}
```
````


```{code-cell} ipython3
:tags: ["hide-output","remove-input"]
%pip install plotly
```

```{code-cell} ipython3
:tags: ["hide-output","hide-input"]

import numpy as np
from scipy.integrate import odeint

import plotly.figure_factory as ff
import plotly.graph_objs as go
import plotly.io as pio
pio.renderers.default = 'notebook'

def dy_dx(y,x):
  return (-5/2)*y

y0 = 2

def odeint_oplossing(ode_func, y0, t):
  y = odeint(ode_func, y0, t)
  return y

x_current = np.linspace(0,10,100)
y_an = odeint_oplossing(dy_dx, y0, x_current)

y_an2=y_an.reshape(-1)

# Generate a grid of x,y values
x = np.linspace(-6, 6, 60)
y = np.linspace(-6, 6, 60)

X, Y = np.meshgrid(x, y)
U = 1  # Constant unit vector for slope field
V = dy_dx(Y, X)

# Normalize the arrow length
N = np.sqrt(U**2 + V**2)
U = U / N
V = V / N

fig = ff.create_quiver(X, Y, U, V, scale=0.15, arrow_scale=.4)

fig.add_trace(go.Scatter(
                    x=x_current,
                    y=y_an2,
                    mode='lines',
                    )
)

fig.update_layout(height=800,
                  width=800,
                  yaxis_range=[-3,3],
                  yaxis_title='y-as',
                  xaxis_range=[-3,3],
                  xaxis_title='x-as',
                  title = 'Richtingsveld'
)
fig
```

```{code-cell} ipython3
:tags: ["remove-output","remove-input"]

import numpy as np 
import matplotlib.pyplot as plt 
from myst_nb import glue

#plt.rcParams['text.usetex'] = True

# Functie definitie
def f(x):
    return (4*x - 3) / (5*x - 4)

# Domein splitsen rond de verticale asymptoot x = 4/5
x1 = np.linspace(-2, 0.79, 400)  # Linker tak (voor x < 4/5)
x2 = np.linspace(0.81, 3, 400)   # Rechter tak (voor x > 4/5)

# Functiewaarden berekenen
y1 = f(x1)
y2 = f(x2)

# Grafiek plotten
fig, ax = plt.subplots()
#plt.figure(figsize=(8, 6))
ax.plot(x1, y1, 'b', label=r'$y = \frac{4x - 3}{5x - 4}$')  # Linker tak
ax.plot(x2, y2, 'b')  # Rechter tak

# Asymptoten
ax.axvline(x=4/5, color='r', linestyle='--', label=r'Asymptoot $x=\frac{4}{5}$')  # Verticale asymptoot
ax.axhline(y=4/5, color='g', linestyle='--', label=r'Asymptoot $y=\frac{4}{5}$')  # Horizontale asymptoot

# Labels en titel
ax.set_xlabel('x')
ax.set_ylabel('f(x)')
ax.set_xlim(-2,3)
ax.set_ylim(-3,5)
ax.set_title('Grafiek van $f(x) = \\frac{4x - 3}{5x - 4}$')
ax.legend()
ax.grid()

# Weergeven
#ax.show()

#fig.savefig("test.png")
glue("voorbeeld1", fig, display=False)
```

```{glue:} voorbeeld1
```