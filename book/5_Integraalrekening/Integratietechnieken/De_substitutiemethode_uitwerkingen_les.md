# 6.1 Uitwerkingen Les

<hr style="border:2px solid #9EA700">

### Opgave 1

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int \sqrt{1+y^2} \cdot 2y \, dy
\end{align*}

Kies de functie $u(y)$:
\begin{align*}
    u(y) = 1 + y^2
\end{align*}

Differentieer de functie $u(y)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dy} &= 2y \\
    du &= 2y \, dy
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    & \int \sqrt{1+y^2} \cdot 2y \, dy \\
    &=  \int \sqrt{u}  \, du \\
    &=  \int (u)^\dfrac{1}{2}  \, du
\end{align*}

Integreren geeft:
\begin{align*}
    &= \dfrac{1}{\frac{3}{2}} \cdot u^{\frac{3}{2}} + C \\
    &= \dfrac{2}{3} \cdot u^{\frac{3}{2}} + C
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= \dfrac{2}{3} \cdot (1+y^2)^{\frac{3}{2}} + C \\
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 2

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int \cos(t) \sin^4(t) \, dt
\end{align*}

Kies de functie $u(t)$:
\begin{align*}
    u(t) = \sin(t)
\end{align*}

Differentieer de functie $u(t)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dt} &= \cos(t) \\
    du &= \cos(t) \, dt
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &  \int \sin^4(t) \cos(t) \, dt\\
    &=  \int u^4  \, du
\end{align*}

Integreren geeft:
\begin{align*}
    &= \dfrac{1}{5} \cdot u^{5} + C
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= \dfrac{1}{5} \cdot \sin^{5}(t) + C
\end{align*}

```
````

<hr style="border:1px solid #9EA700">


### Opgave 3

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int \cos(7\theta + 4) \, d\theta
\end{align*}

Kies de functie $u(\theta)$:
\begin{align*}
    u(\theta) = 7\theta + 4
\end{align*}

Differentieer de functie $u(\theta)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{d\theta} &= 7 \\
    du &= 7 \, d\theta
\end{align*}

In de originele functie staat $( d\theta)$ dus:
\begin{align*}
    \dfrac{1}{7}du &=  \, d\theta
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &  \int \cos(7\theta + 4) \, d\theta \\
    &=  \int \cos(u)  \, \dfrac{1}{7} du \\
    &=  \dfrac{1}{7} \int \cos(u)  \,  du
\end{align*}

Integreren geeft:
\begin{align*}
    &= \dfrac{1}{7} \sin(u) + C
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &=  \dfrac{1}{7} \sin(7\theta + 4) + C
\end{align*}

```
````
