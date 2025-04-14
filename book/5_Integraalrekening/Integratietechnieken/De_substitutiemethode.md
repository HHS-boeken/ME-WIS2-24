# 6.1 De substitutiemethode bij integreren

````{admonition} Theorie
:class: tip, dropdown open

De substitutiemethode is een techniek om een moeilijke integraal te vereenvoudigen door een slimme variabeleverandering. Het idee is dat je een deel van de functie vervangt door een nieuwe variabele (meestal $u$), waardoor de integraal makkelijker wordt om op te lossen.

Stel je hebt een integraal van de vorm:

\begin{align*}
    \int{f(g(x)) \cdot g'(x)dx}
\end{align*}

Dan kun je  met substitutie:

\begin{align*}
    u = g(x)
\end{align*}

ook de afgeleide meenemen:

\begin{align*}
    \dfrac{du}{dx} &= g'(x)\\
    du & = g'(x) dx
\end{align*}

Als je deze vervanging netjes uitvoert, verandert de integraal in:

\begin{align*}
    \int{f(u) du}
\end{align*}

en die is vaak veel makkelijker op te lossen.

```{admonition} Stappenplan substitutiemethode
:class: warning

1. **Kies een substitutie** $u = g(x)$, waarbij een deel van de oorspronkelijke integraal wordt vervangen.
1. **Bereken de afgeleide** $\frac{du}{dx} = g'(x)$ en herschrijf $dx$ in termen van $du$.
1. **Vervang alles** in de oorspronkelijke integraal door $u$ en $du$.
1. **Los de nieuwe integraal op** in termen van $u$.
1. **Substitueer terug** naar de oorspronkelijke variabele $x$.

```
````

## 6.1.1 De substitutiemethode

````{admonition} Voorbeeld 1: substitutiemethode
:class: dropdown

Bereken de onbepaalde integraal:

\begin{align*}
    \int 2x \cdot \cos(x^2) \, dx
\end{align*}

Kies de functie $u(x)$:

\begin{align*}
    u(x) = x^2
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:

\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx 
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:

\begin{align*}
   &\int \cos(x^2) \cdot  2x \, dx \\
    &= \int \cos(u) \, du \\
\end{align*}

Integreren geeft:

\begin{align*}
    &= \sin(u) + C \\
\end{align*}

Terugsubstitueren geeft:

\begin{align*}
    &= \sin(x^2) + C
\end{align*}

````

````{admonition} Oefening 1
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot e^{3x^2} \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot e^{3x^2} \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align*}
    u(x) = 3x^2
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 6x \\
    du &= 6x \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
   &\int e^{3x^2} \cdot  6x \, dx \\
    &= \int e^{u} \, du \\
\end{align*}

Integreren geeft:
\begin{align*}
    &= e^u + C \\
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= e^{3x^2} + C
\end{align*}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot (x^2+1)^5 \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot (x^2+1)^5 \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align*}
    u(x) = x^2 + 1
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &\int 3 \cdot (x^2+1)^5 \cdot  2x \, dx \\
    &= \int 3 \cdot u^5 \, du \\
\end{align*}

Integreren geeft:
\begin{align*}
    &= \dfrac{3}{6} u^6 + C \\
    &= \dfrac{1}{2} u^6 + C 
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= \dfrac{1}{2} (x^2+1)^6 + C 
\end{align*}

```
````

## 6.1.2 De substitutiemethode met aanpassing coëfficiënten

````{admonition} Voorbeeld 2: substitutiemethode met aanpassing coëfficiënten

:class: dropdown

Bereken de onbepaalde integraal:

\begin{align*}
    \int (x^2+2x-3)^2 (x+1) \, dx
\end{align*}

Kies de functie $u(x)$:

\begin{align*}
    u(x) = x^2+2x-3
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:

\begin{align*}
    \dfrac{du}{dx} &= 2x+2 \\
    du &= (2x+2) \, dx 
\end{align*}

In de originele functie staat $(x+1)$ dus:
\begin{align*}
    \dfrac{1}{2}du &= (x+1) \, dx 
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:

\begin{align*}
    &\int (x^2+2x-3)^2 (x+1) \, dx \\
    &= \int u^2 \, \dfrac{1}{2}du \\
    &= \dfrac{1}{2} \int u^2 \, du \\
\end{align*}

Integreren geeft:

\begin{align*}
    &= \dfrac{1}{2} \cdot \dfrac{1}{3}u^3 + C \\
    &= \dfrac{1}{6}u^3 + C \\
\end{align*}

Terugsubstitueren geeft:

\begin{align*}
    &= \dfrac{1}{6}(x^2+2x-3)^3 + C \\
\end{align*}

````

````{admonition} Oefening 3
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align*}
    u(x) = x^3
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 3x^2 \\
    du &= 3x^2 \, dx
\end{align*}

In de originele functie staat $(x^2)$ dus:
\begin{align*}
    \dfrac{1}{3}du &= x^2 \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &= \int u^2 \, \dfrac{1}{2}du \\
    &= \dfrac{1}{2} \int u^2 \, du \\
\end{align*}

Integreren geeft:
\begin{align*}
    &= e^u + C \\
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= e^{3x^2} + C
\end{align*}

```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot (x^2+1)^5 \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int 6x \cdot (x^2+1)^5 \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align*}
    u(x) = x^2 + 1
\end{align*}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align*}
    &\int 3 \cdot (x^2+1)^5 \cdot  2x \, dx \\
    &= \int 3 \cdot u^5 \, du \\
\end{align*}

Integreren geeft:
\begin{align*}
    &= \dfrac{3}{6} u^6 + C \\
    &= \dfrac{1}{2} u^6 + C 
\end{align*}

Terugsubstitueren geeft:
\begin{align*}
    &= \dfrac{1}{2} (x^2+1)^6 + C 
\end{align*}

```
````