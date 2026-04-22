# 6.1 Uitwerkingen

<hr style="border:2px solid #9EA700">

## Opgave 6.1.1a

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \sqrt{5 + x^2} \cdot 2x \, dx = \dfrac{2}{3} \cdot \sqrt{5+x^2}(5+x^2) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
    \int \sqrt{5 + x^2} \cdot 2x \, dx
$$

Kies de functie $u$:

$$
    u = 5 + x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
    &  \int \sqrt{5 + x^2} \cdot 2x \, dx \\
    &=  \int \sqrt{u}  \, du \\
    &=  \int (u)^\dfrac{1}{2}  \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
    &= \dfrac{1}{\frac{3}{2}} \cdot u^{\frac{3}{2}} + C \\
    &= \dfrac{2}{3} \cdot u^{\frac{3}{2}} + C
\end{align*}
$$

Terug substitueren geeft:

$$
\begin{align*}
    &= \dfrac{2}{3} \cdot (5+x^2)^{\frac{3}{2}} + C \\
    &= \dfrac{2}{3} \cdot \sqrt{5+x^2}(5+x^2) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1b

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \ln(x^2 + 4) \cdot 2x \, dx = (x^2 + 4) \ln(x^2 + 4) - (x^2 + 4) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int \ln(x^2 + 4) \cdot 2x \, dx
$$

Kies de functie $u$:

$$
    u = x^2 + 4
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
    &  \int \ln(x^2 + 4) \cdot 2x \, dx \\
    &=  \int \ln(u)  \, du
\end{align*}
$$

Integreren geeft:

$$
    = u \ln(u) - u + C
$$

Terug substitueren geeft:

$$
    = (x^2 + 4) \ln(x^2 + 4) - (x^2 + 4) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1c

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \sin(x^2 + 2) \cdot 2x \, dx = -\cos(x^2 + 2) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int \sin(x^2 + 2) \cdot 2x \, dx
$$

Kies de functie $u$:

$$
    u = x^2 + 2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
    &  \int \sin(x^2 + 2) \cdot 2x \, dx \\
    &=  \int \sin(u)  \, du
\end{align*}
$$

Integreren geeft:

$$
    = -\cos(u) + C
$$

Terug substitueren geeft:

$$
    = -\cos(x^2 + 2) + C
$$

:::
::::
<hr style="border:1px solid #9EA700">

## Opgave 6.1.1d

::::{admonition} Antwoord
:class: important, dropdown

$$
     \int 2xe^{x^2} \, dx = e^{x^2} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int 2xe^{x^2} \, dx
$$

Kies de functie $u$:

$$
    u = x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
    &  \int 2x e^{x^2} \, dx \\
    &=  \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
    = e^u + C
$$

Terug substitueren geeft:

$$
    = e^{x^2} + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1e

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int 9x^2\cos(x^3 + 9) \, dx = 3 \sin(x^3 + 9) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int 9x^2\cos(x^3 + 9) \, dx
$$

Kies de functie $u$:

$$
    u = x^3 + 9
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 3x^2 \\
    du &= 3x^2 \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
    \int 9x^2 \cos(x^3 + 9) \, dx &= \int 3 \cdot (3x^2 \cos(u)) \, dx \\
    &= 3 \int \cos(u) \cdot 3x^2 \, dx \\
    &= 3 \int \cos(u) \, du
\end{align*}
$$

Integreren geeft:

$$
    = 3 \sin(u) + C
$$

Terug substitueren geeft:

$$
    = 3 \sin(x^3 + 9) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1f

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int 6(3x - 4)^3 \, dx = \dfrac{(3x - 4)^4}{2} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int 6(3x - 4)^3 \, dx
$$

Kies de functie $u$:

$$
    u = 3x - 4
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 3 \\
    du &= 3 \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $dx$:

$$
\begin{align*}
    \int 6(3x - 4)^3 \, dx &= \int 2 \cdot 3(3x - 4)^3 \, dx \\
    &= 2 \int \cdot (3x - 4)^3 \cdot 3\, dx \\
    &= 2 \int u^3 \, du
\end{align*}
$$

Integreren geeft:

$$
    = 2 \cdot \dfrac{u^4}{4} + C = \dfrac{u^4}{2} + C
$$

Terug substitueren geeft:

$$
    = \dfrac{(3x - 4)^4}{2} + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1g

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
     \int \dfrac{3\ln(x)}{x} \, dx = \dfrac{3}{2} \ln^2(x) + C
\end{align*}

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int \dfrac{3\ln(x)}{x} \, dx
$$

Kies de functie $u$:

$$
    u = \ln(x)
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{x} \\
    du &= \dfrac{1}{x} du
\end{align*}
$$

Herschrijf de integraal met substitutie:

$$
\begin{align*}
    \int \dfrac{3\ln(x)}{x} \, dx &= \int 3 \cdot \dfrac{\ln(x)}{x} \, dx \\
     &= \int 3 \cdot \ln(x) \cdot \dfrac{1}{x} \, dx \\
     &= 3 \int u \, du
\end{align*}
$$

Integreren geeft:

$$
    = 3 \cdot \dfrac{1}{2}u^2 + C
$$

Terug substitueren geeft:

$$
   =  \dfrac{3}{2} \ln^2(x) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1h

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int 12x e^{2x^2} \, dx = 3e^{2x^2} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
   \int 12x e^{2x^2} \, dx
$$

Kies de functie $u$:

$$
    u = 2x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
    \dfrac{du}{dx} &= 4x \\
    du &= 4x \, dx
\end{align*}
$$

Herschrijf de integraal met substitutie:

$$
\begin{align*}
    \int 12x e^{2x^2} \, dx &= \int 3 \cdot 4xe^{2x^2} \, dx\\
    &= \int 3 \cdot e^{2x^2} \cdot 4x \,  dx \\
    &= 3 \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
    = 3e^u + C
$$

Terug substitueren geeft:

$$
    = 3e^{2x^2} + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1i

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{\sin(\sqrt{x})}{\sqrt{x}} \, dx = -2\cos(\sqrt{x}) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int \dfrac{\sin(\sqrt{x})}{\sqrt{x}} , dx
$$

Kies de functie $u$:

$$
u = \sqrt{x}
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{2\sqrt{x}} \\
du &= \dfrac{1}{2\sqrt{x}} \, dx
\end{align*}
$$

Herschrijf de integraal met substitutie:

$$
\begin{align*}
\int \dfrac{\sin(\sqrt{x})}{\sqrt{x}} \, dx &= \int 2 \cdot \sin(\sqrt{x}) \cdot \dfrac{1}{2\sqrt{x}} \, dx \\
&= 2 \int \sin(u) \, du
\end{align*}
$$

Integreren geeft:

$$
= -2\cos(u) + C
$$

Terug substitueren geeft:

$$
=  -2\cos(\sqrt{x}) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.1j

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{e^{1/x}}{x^2} \, dx = -e^{1/x} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int \dfrac{e^{1/x}}{x^2} \, dx
$$

Kies de functie $u$:

$$
u = \dfrac{1}{x}
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= -\dfrac{1}{x^2} \\
du &= -\dfrac{1}{x^2} \, dx
\end{align*}
$$

Herschrijf de integraal met substitutie:

$$
\begin{align*}
\int \dfrac{e^{1/x}}{x^2} \, dx &= \int e^{1/x} \cdot \dfrac{1}{x^2} \, dx \\
&= - \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
= -e^u + C
$$

Terug substitueren geeft:

$$
=  -e^{1/x} + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot \cos(x^2) \, dx = \dfrac{1}{2}\sin(x^2) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot \cos(x^2) \, dx
$$

Kies de functie $u$:

$$
u = x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\dfrac{1}{2}du &= x \, dx
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int \cos(x^2) \cdot x \, dx \\
&= \int \cos(u) \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int \cos(u) \, du
\end{align*}
$$

Integreren geeft:

$$
= \dfrac{1}{2} \sin(u) + C
$$

Terugsubstitueren geeft:

$$
= \dfrac{1}{2} \sin(x^2) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2b

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot e^{x^2+1} \, dx = \dfrac{1}{2}e^{x^2+1} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot e^{x^2+1} \, dx
$$

Kies de functie $u$:

$$
u = x^2+1
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\dfrac{1}{2}du = x \, dx
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int e^{x^2+1} \cdot x \, dx \\
&= \int e^u \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
= \dfrac{1}{2} e^u + C
$$

Terugsubstitueren geeft:

$$
= \dfrac{1}{2} e^{x^2+1} + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2c

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot (x^2+3)^4 \, dx = \dfrac{1}{10}(x^2+3)^5 + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot (x^2+3)^4 \, dx
$$

Kies de functie $u$:

$$
u = x^2+3
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\begin{align*}
\dfrac{1}{2}du &= x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int (x^2+3)^4 \cdot x \, dx \\
&= \int u^4 \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int u^4 \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
&= \dfrac{1}{2} \cdot \dfrac{1}{5}u^5 + C \\
&= \dfrac{1}{10}u^5 + C
\end{align*}
$$

Terugsubstitueren geeft:

$$
= \dfrac{1}{10}(x^2+3)^5 + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
\int (2x+5) \cdot \ln(x^2+5x) , dx = (x^2+5x)\ln(x^2+5x) - (x^2+5x) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int (2x+5) \cdot \ln(x^2+5x) \, dx
$$

Kies de functie $u$:

$$
u = x^2+5x
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x+5 \\
du &= (2x+5) \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int \ln(x^2+5x) \cdot (2x+5) \, dx \\
&= \int \ln(u) \, du
\end{align*}
$$

Integreren geeft:

$$
= u\ln(u) - u + C
$$

Terugsubstitueren geeft:

$$
= (x^2+5x)\ln(x^2+5x) - (x^2+5x) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot \sin(3x^2) \, dx = -\dfrac{1}{6}\cos(3x^2) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot \sin(3x^2) \, dx
$$

Kies de functie $u$:

$$
u = 3x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 6x \\
du &= 6x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\begin{align*}
\dfrac{1}{6}du &= x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int \sin(3x^2) \cdot x \, dx \\
&= \int \sin(u) \cdot \dfrac{1}{6}du \\
&= \dfrac{1}{6} \int \sin(u) \, du
\end{align*}
$$

Integreren geeft:

$$
= -\dfrac{1}{6} \cos(u) + C
$$

Terugsubstitueren geeft:

$$
= -\dfrac{1}{6} \cos(3x^2) + C
$$

:::
::::

<hr style="border:1px solid #9EA700">


## Opgave 6.1.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
\int (x+1) \cdot e^{x^2+2x} \, dx = \dfrac{1}{2}e^{x^2+2x} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int (x+1) \cdot e^{x^2+2x} \, dx
$$

Kies de functie $u$:

$$
u = x^2+2x
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x+2 \\
du &= (2x+2) \, dx
\end{align*}
$$

In de originele functie staat $(x+1)$ dus:

$$
\dfrac{1}{2}du = (x+1) \, dx
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int e^{x^2+2x} \cdot (x+1) \, dx \\
&= \int e^u \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
= \dfrac{1}{2} e^u + C
$$

Terugsubstitueren geeft:

$$
= \dfrac{1}{2} e^{x^2+2x} + C
$$

:::
::::


<hr style="border:1px solid #9EA700">

## Opgave 6.1.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot \ln(x^2+2) \, dx = \dfrac{1}{2}((x^2+2)\ln(x^2+2) - (x^2+2)) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot \ln(x^2+2) \, dx
$$

Kies de functie $u$:

$$
u = x^2+2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\begin{align*}
\dfrac{1}{2}du &= x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int \ln(x^2+2) \cdot x \, dx \\
&= \int \ln(u) \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int \ln(u) \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
&= \dfrac{1}{2} (u\ln(u) - u) + C
\end{align*}
$$

Terugsubstitueren geeft:

$$
\begin{align*}
&= \dfrac{1}{2}((x^2+2)\ln(x^2+2) - (x^2+2)) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
\int (3x^2+6x) \cdot \cos(x^3+3x^2) \, dx = \sin(x^3+3x^2) + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int (3x^2+6x) \cdot \cos(x^3+3x^2) \, dx
$$

Kies de functie $u$:

$$
u = x^3+3x^2
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 3x^2+6x \\
du &= (3x^2+6x) \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int \cos(x^3+3x^2) \cdot (3x^2+6x) \, dx \\
&= \int \cos(u) \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
&= \sin(u) + C
\end{align*}
$$

Terugsubstitueren geeft:

$$
\begin{align*}
&= \sin(x^3+3x^2) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2i

::::{admonition} Antwoord
:class: important, dropdown

$$
\int (2x+1) \cdot (x^2+x)^5 \, dx = \dfrac{1}{6}(x^2+x)^6 + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int (2x+1) \cdot (x^2+x)^5 \, dx
$$

Kies de functie $u$:

$$
u = x^2+x
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x+1 \\
du &= (2x+1) \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int (x^2+x)^5 \cdot (2x+1) \, dx \\
&= \int u^5 \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
&= \dfrac{1}{6}u^6 + C
\end{align*}
$$

Terugsubstitueren geeft:

$$
\begin{align*}
&= \dfrac{1}{6}(x^2+x)^6 + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.1.2j

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x \cdot e^{x^2+4} \, dx = \dfrac{1}{2}e^{x^2+4} + C
$$

:::{dropdown} Uitwerking
Bereken de onbepaalde integraal:

$$
\int x \cdot e^{x^2+4} \, dx
$$

Kies de functie $u$:

$$
u = x^2+4
$$

Differentieer de functie $u$ en bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

In de originele functie staat $(x)$ dus:

$$
\begin{align*}
\dfrac{1}{2}du &= x \, dx
\end{align*}
$$

Herschrijf de integraal door substitutie van $u$ en $du$:

$$
\begin{align*}
&\int e^{x^2+4} \cdot x \, dx \\
&= \int e^u \cdot \dfrac{1}{2}du \\
&= \dfrac{1}{2} \int e^u \, du
\end{align*}
$$

Integreren geeft:

$$
\begin{align*}
&= \dfrac{1}{2} e^u + C
\end{align*}
$$

Terugsubstitueren geeft:

$$
\begin{align*}
&= \dfrac{1}{2} e^{x^2+4} + C
\end{align*}
$$

:::
::::