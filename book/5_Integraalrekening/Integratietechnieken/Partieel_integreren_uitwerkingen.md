# 6.2 Uitwerkingen

<hr style="border:2px solid #9EA700">

## Opgave 6.2.1a

{admonition} Antwoord
:class: important, dropdown

Bereken de onbepaalde integraal:

$$
\int x\cos(x) , dx
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x\cos(x)\, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= \cos(x) , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &=  , dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(x) , dx  \\
\dfrac{dv}{dx} &= \cos(x) \\
v &= \sin(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v , du \\
&= x \cdot \sin(x) - \int \sin(x) , dx\\
&= x \cdot \sin(x) + \cos(x) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.1b

::::{admonition} Antwoord
:class: important, dropdown

Bereken de onbepaalde integraal:

$$
\int x e^{3x} , dx
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x e^{3x} , dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \
dv &= e^{3x} , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &= , dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{3x} , dx  \\
\dfrac{dv}{dx} &= e^{3x} \\
v &= \dfrac{1}{3}e^{3x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v , du \\
&= x \cdot \dfrac{1}{3}e^{3x} - \int \dfrac{1}{3}e^{3x} , dx\\
&= x \cdot \dfrac{1}{3}e^{3x} - \dfrac{1}{3} \int e^{3x} , dx\\
&= x \cdot \dfrac{1}{3}e^{3x} - \dfrac{1}{3} \cdot \dfrac{1}{3}e^{3x} + C \\
&= \dfrac{1}{3}xe^{3x} - \dfrac{1}{9}e^{3x} + C
\end{align*}
$$

:::
::::

## Opgave 6.2.1c

::::{admonition} Antwoord
:class: important, dropdown

Primitiveer:

$$
f(x) = x^2 \ln(x)
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^2 \ln(x)
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 \ln(x) , dx
\end{align*}
$$

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(x) \\
dv &= x^2 , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} , dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^2 , dx  \\
\dfrac{dv}{dx} &= x^2 \\
v &= \dfrac{1}{3}x^3
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v , du \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{x} , dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^2 , dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \int x^2 , dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \cdot \dfrac{1}{3} x^3 + C \\
&= \dfrac{1}{3}x^3\ln(x) - \dfrac{1}{9} x^3 + C
\end{align*}
$$

:::
::::

## Opgave 6.2.1d

::::{admonition} Antwoord
:class: important, dropdown

Bereken de onbepaalde integraal:

$$
\int (3x-2)\sin(x) , dx
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int (3x-2)\sin(x) , dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 3x-2 \\
dv &= \sin(x) , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 3 \\
du &= 3 , dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \sin(x) , dx  \\
\dfrac{dv}{dx} &= \sin(x) \\
v &= -\cos(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v , du \\
&= (3x-2) \cdot -\cos(x) - \int -\cos(x) 3 , dx\\
&= -(3x-2) \cdot \cos(x) + 3 \int \cos(x) , dx\\
&= -(3x-2) \cdot \cos(x) + 3 \sin(x) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.1e

::::{admonition} Antwoord
:class: important, dropdown

Primitiveer:

$$
f(x) = x \ln(2x)
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x \ln(2x)
$$

Dus,

$$
\begin{align*}
F(x) &= \int x \ln(2x) , dx
\end{align*}
$$

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(2x) \\
dv &= x , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} , dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x , dx  \\
\dfrac{dv}{dx} &= x \\
v &= \dfrac{1}{2}x^2
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v , du \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \int \dfrac{1}{2}x^2 \dfrac{1}{x} , dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \int \dfrac{1}{2}x , dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \dfrac{1}{2} \int x , dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \dfrac{1}{2} \cdot \dfrac{1}{2} x^2 + C \\
&= \dfrac{1}{2}x^2\ln(2x) - \dfrac{1}{4} x^2 + C
\end{align*}
$$

:::
::::
