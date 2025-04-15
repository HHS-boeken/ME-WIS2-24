# 6.1 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 6.1.1a

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int \sqrt{5 + x^2} \cdot 2x \, dx
\end{align*}

Kies de functie $u$:
\begin{align*}
    u = 5 + x^2
\end{align*}

Differentieer de functie $u$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &  \int \sqrt{5 + x^2} \cdot 2x \, dx \\
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
    &= \dfrac{2}{3} \cdot (5+x^2)^{\frac{3}{2}} + C \\
    &= \dfrac{2}{3} \cdot \sqrt{5+x^2}(5+x^2) + C
\end{align*}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.1.1b

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     &= \dfrac{2}{3} \cdot \sqrt{1+y^2}(1+y^2) + C
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
   \int \ln(x^2 + 4) \cdot 2x \, dx
\end{align*}

Kies de functie $u$:
\begin{align*}
    u = x^2 + 4
\end{align*}

Differentieer de functie $u$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &  \int \ln(x^2 + 4) \cdot 2x \, dx
    &=  \int \ln(u)  \, du
\end{align*}

Integreren geeft:
\begin{align*}
    &= u \ln(u) - u + C
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= (x^2 + 4) \ln(x^2 + 4) - (x^2 + 4) + C
\end{align*}
```
````

<hr style="border:1px solid #9EA700">