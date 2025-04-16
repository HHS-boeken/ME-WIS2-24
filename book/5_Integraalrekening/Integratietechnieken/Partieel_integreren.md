# 6.2 Partieel integreren

````{admonition} Theorie
:class: tip, dropdown open



```
````

## 6.2.1 Partieel integreren

````{admonition} Voorbeeld 1: Partieel integreren
:class: dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int (2x+3)\cos(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= 2x+3 \\
    dv &= \cos(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2 \\
    du &= 2 \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= \cos(x) \, dx  \\
    \dfrac{dv}{dx} &= \cos(x) \\
    v &= \sin(x)
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= (2x+3) \cdot \sin(x) - \int \sin(x) 2 \, dx\\
    &= (2x+3) \cdot \sin(x) - 2 \int \sin(x) \, dx\\
    &= (2x+3) \cdot \sin(x) + 2 \cos(x) + C
\end{align*}
````

````{admonition} Oefening 1
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x \cdot e^{2x} \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x \cdot e^{2x} \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= x \\
    dv &= e^{2x} \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 1 \\
    du &=  \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= e^{2x} \, dx  \\
    \dfrac{dv}{dx} &= e^{2x} \\
    v &= \dfrac{1}{2}e^{2x}
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= x \cdot \dfrac{1}{2}e^{2x} - \int \dfrac{1}{2}e^{2x} \, dx\\
    &= x \cdot \dfrac{1}{2}e^{2x} - \dfrac{1}{2} \int e^{2x} \, dx\\
    &= x \cdot \dfrac{1}{2}e^{2x} - \dfrac{1}{2} \cdot  \dfrac{1}{2}e^{2x} + C \\
    &= \dfrac{1}{2}xe^{2x} - \dfrac{1}{4}e^{2x} + C \\
\end{align*}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) =  x^3\ln(x) + 3
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) =  x^3\ln(x) + 3
\end{align*}

Dus,
\begin{align*}
    F(x) &=  \int (x^3\ln(x) + 3) \, dx \\
    F(x) &= \int (x^3\ln(x)) \, dx + \int  (3) \, dx \\
    F(x) &= \int (x^3\ln(x)) \, dx + 3x + C
\end{align*}

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \ln(x) \\
    dv &= x^3 \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{x} \\
    du &=  \dfrac{1}{x} \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= x^3 \, dx  \\
    \dfrac{dv}{dx} &= x^3 \\
    v &= \dfrac{1}{4}x^4
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^4 \dfrac{1}{x} \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^3 \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \int x^3 \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \cdot \dfrac{1}{4} x^4 + C \\
    &= \dfrac{1}{4}x^4\ln(x) - \dfrac{1}{16} x^4 + C \\
\end{align*}



```
````

## 6.2.2 Herhaald partieel integreren

````{admonition} Voorbeeld 2: Herhaald partieel integreren
:class: dropdown



````

````{admonition} Oefening 3
:class: important, dropdown




```{admonition} Uitwerking
:class: important, dropdown


```
````

````{admonition} Oefening 4
:class: important, dropdown



```{admonition} Uitwerking
:class: important, dropdown


```
````