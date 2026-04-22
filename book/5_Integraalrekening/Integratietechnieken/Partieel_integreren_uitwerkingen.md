# 6.2 Uitwerkingen

<hr style="border:2px solid #9EA700">

## Opgave 6.2.1a

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x\cos(x) \, dx = x \cdot \sin(x) + \cos(x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x\cos(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= \cos(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &= \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(x) \, dx  \\
\dfrac{dv}{dx} &= \cos(x) \\
v &= \sin(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x \cdot \sin(x) - \int \sin(x) \, dx\\
&= x \cdot \sin(x) + \cos(x) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1b

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x e^{3x} \, dx = \dfrac{1}{3}xe^{3x} - \dfrac{1}{9}e^{3x} + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x e^{3x} \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= e^{3x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &= \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{3x} \, dx  \\
\dfrac{dv}{dx} &= e^{3x} \\
v &= \dfrac{1}{3}e^{3x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x \cdot \dfrac{1}{3}e^{3x} - \int \dfrac{1}{3}e^{3x} \, dx\\
&= x \cdot \dfrac{1}{3}e^{3x} - \dfrac{1}{3} \int e^{3x} \, dx\\
&= x \cdot \dfrac{1}{3}e^{3x} - \dfrac{1}{3} \cdot \dfrac{1}{3}e^{3x} + C \\
&= \dfrac{1}{3}xe^{3x} - \dfrac{1}{9}e^{3x} + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1c

::::{admonition} Antwoord
:class: important, dropdown

$$
F(x) = \int x^2 \ln(x) \, dx =  \dfrac{1}{3}x^3\ln(x) - \dfrac{1}{9} x^3 + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^2 \ln(x)
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 \ln(x) \, dx
\end{align*}
$$

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(x) \\
dv &= x^2 \, dx
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
dv &= x^2 \, dx  \\
\dfrac{dv}{dx} &= x^2 \\
v &= \dfrac{1}{3}x^3
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{x} \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^2 \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \int x^2 \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \cdot \dfrac{1}{3} x^3 + C \\
&= \dfrac{1}{3}x^3\ln(x) - \dfrac{1}{9} x^3 + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1d

::::{admonition} Antwoord
:class: important, dropdown

$$
\int (3x-2)\sin(x) \, dx =  -(3x-2) \cdot \cos(x) + 3 \sin(x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int (3x-2)\sin(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 3x-2 \\
dv &= \sin(x) \, dx
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
dv &= \sin(x) \, dx  \\
\dfrac{dv}{dx} &= \sin(x) \\
v &= -\cos(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= (3x-2) \cdot -\cos(x) - \int -\cos(x) 3 \, dx\\
&= -(3x-2) \cdot \cos(x) + 3 \int \cos(x) \, dx\\
&= -(3x-2) \cdot \cos(x) + 3 \sin(x) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1e

::::{admonition} Antwoord
:class: important, dropdown

$$
F(x) = \int x \ln(2x) \, dx = \dfrac{1}{2}x^2\ln(2x) - \dfrac{1}{4} x^2 + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x \ln(2x)
$$

Dus,

$$
F(x) = \int x \ln(2x) \, dx
$$

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(2x) \\
dv &= x \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x \, dx  \\
\dfrac{dv}{dx} &= x \\
v &= \dfrac{1}{2}x^2
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \int \dfrac{1}{2}x^2 \dfrac{1}{x} \, dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \int \dfrac{1}{2}x \, dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \dfrac{1}{2} \int x \, dx \\
&= \ln(2x) \cdot \dfrac{1}{2}x^2 - \dfrac{1}{2} \cdot \dfrac{1}{2} x^2 + C \\
&= \dfrac{1}{2}x^2\ln(2x) - \dfrac{1}{4} x^2 + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1f

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x\cos(2x) \, dx = \dfrac{1}{2}x\sin(2x) + \dfrac{1}{4}\cos(2x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x\cos(2x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= \cos(2x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &= \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(2x) \, dx  \\
\dfrac{dv}{dx} &= \cos(2x) \\
v &= \dfrac{1}{2}\sin(2x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x \cdot \dfrac{1}{2}\sin(2x) - \int \dfrac{1}{2}\sin(2x) \, dx\\
&= x \cdot \dfrac{1}{2}\sin(2x) - \dfrac{1}{2} \int \sin(2x) \, dx\\
&= x \cdot \dfrac{1}{2}\sin(2x) + \dfrac{1}{2} \cdot \dfrac{1}{2}\cos(2x) + C \\
&= \dfrac{1}{2}x\sin(2x) + \dfrac{1}{4}\cos(2x) + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1g

::::{admonition} Antwoord
:class: important, dropdown

$$
F(x) = \int (2x+1)e^{-x} , dx = -(2x+3)e^{-x} + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = (2x+1)e^{-x}
$$

Dus,

$$
\begin{align*}
F(x) &= \int (2x+1)e^{-x} \, dx
\end{align*}
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 2x+1 \\
dv &= e^{-x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2 \\
du &= 2 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{-x} , dx  \\
\dfrac{dv}{dx} &= e^{-x} \\
v &= -e^{-x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= (2x+1) \cdot -e^{-x} - \int -e^{-x} 2 \, dx\\
&= -(2x+1)e^{-x} + 2 \int e^{-x} \, dx\\
&= -(2x+1)e^{-x} + 2(-e^{-x}) + C \\
&= -(2x+1)e^{-x} - 2e^{-x} + C \\
&= -(2x+3)e^{-x} + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1h

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^4 \ln(x) \, dx = \dfrac{1}{5}x^5\ln(x) - \dfrac{1}{25} x^5 + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^4 \ln(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(x) \\
dv &= x^4 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^4 \, dx  \\
\dfrac{dv}{dx} &= x^4 \\
v &= \dfrac{1}{5}x^5
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln(x) \cdot \dfrac{1}{5}x^5 - \int \dfrac{1}{5}x^5 \dfrac{1}{x} \, dx \\
&= \ln(x) \cdot \dfrac{1}{5}x^5 - \int \dfrac{1}{5}x^4 \, dx \\
&= \ln(x) \cdot \dfrac{1}{5}x^5 - \dfrac{1}{5} \int x^4 \, dx \\
&= \ln(x) \cdot \dfrac{1}{5}x^5 - \dfrac{1}{5} \cdot \dfrac{1}{5} x^5 + C \\
&= \dfrac{1}{5}x^5\ln(x) - \dfrac{1}{25} x^5 + C
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.2.1i

## Opgave 6.2.1j

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \ln(3x) \, dx = x \cdot \ln(3x) - x + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int \ln(3x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(3x) \\
dv &= \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \, dx  \\
\dfrac{dv}{dx} &= 1 \\
v &= x
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x \cdot \ln(3x) - \int x \cdot \dfrac{1}{x} \, dx\\
&= x \cdot \ln(3x) - \int 1 \, dx\\
&= x \cdot \ln(3x) - x + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 e^{2x} \, dx = \left(\dfrac{1}{2}x^2 - \dfrac{1}{2}x + \dfrac{1}{4}\right)e^{2x} + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^2 e^{2x} \, dx
$$

Dus,

$$
F(x) = \int x^2 e^{2x} \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^2 \\
dv &= e^{2x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{2x} \, dx  \\
\dfrac{dv}{dx} &= e^{2x} \\
v &= \dfrac{1}{2}e^{2x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x^2 \cdot \dfrac{1}{2}e^{2x} - \int \dfrac{1}{2}e^{2x} 2x \, dx\\
&= \dfrac{1}{2}x^2 e^{2x} - \int x e^{2x} \, dx
\end{align*}
$$

De integraal $\int x e^{2x} \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int x e^{2x} \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= e^{2x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &=  \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{2x} \, dx  \\
\dfrac{dv}{dx} &= e^{2x} \\
v &= \dfrac{1}{2}e^{2x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int x e^{2x} \, dx &= x \cdot \dfrac{1}{2}e^{2x} - \int \dfrac{1}{2}e^{2x} \, dx \\
&= \dfrac{1}{2}x e^{2x} - \dfrac{1}{2} \int e^{2x} \, dx\\
&= \dfrac{1}{2}x e^{2x} - \dfrac{1}{2} \cdot \dfrac{1}{2}e^{2x} + C\\
&= \dfrac{1}{2}x e^{2x} - \dfrac{1}{4}e^{2x} + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 e^{2x} \, dx \\
&= \dfrac{1}{2}x^2 e^{2x} - \int x e^{2x} \, dx \\
&= \dfrac{1}{2}x^2 e^{2x} - \left( \dfrac{1}{2}x e^{2x} - \dfrac{1}{4}e^{2x} + C \right) \\
&= \dfrac{1}{2}x^2 e^{2x} - \dfrac{1}{2}x e^{2x} + \dfrac{1}{4}e^{2x} + C \\
&= \left(\dfrac{1}{2}x^2 - \dfrac{1}{2}x + \dfrac{1}{4}\right)e^{2x} + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2b

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \sin(x) \, dx = -x^2\cos(x) + 2x\sin(x) + 2\cos(x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^2 \sin(x) \, dx
$$

Dus,

$$
F(x) = \int x^2 \sin(x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^2 \\
dv &= \sin(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \sin(x) \, dx  \\
\dfrac{dv}{dx} &= \sin(x) \\
v &= -\cos(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u , dv &= uv - \int v \, du \\
&= x^2 \cdot -\cos(x) - \int -\cos(x) 2x \, dx \\
&= -x^2\cos(x) + \int 2x\cos(x) \, dx
\end{align*}
$$

De integraal $\int 2x\cos(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int 2x\cos(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 2x \\
dv &= \cos(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2 \\
du &= 2 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(x) \, dx  \\
\dfrac{dv}{dx} &= \cos(x) \\
v &= \sin(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int 2x\cos(x) \, dx &= 2x \cdot \sin(x) - \int \sin(x) 2 \, dx \\
&= 2x\sin(x) - 2 \int \sin(x) \, dx \\
&= 2x\sin(x) + 2\cos(x) + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 \sin(x) \, dx \\
&= -x^2\cos(x) + \int 2x\cos(x) \, dx \\
&= -x^2\cos(x) + (2x\sin(x) + 2\cos(x) + C) \\
&= -x^2\cos(x) + 2x\sin(x) + 2\cos(x) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2c

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \ln(x) \, dx = \dfrac{1}{3}x^3\ln(x) - \dfrac{1}{9}x^3 + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^2 \ln(x)
$$

Dus,

$$
F(x) = \int x^2 \ln(x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(x) \\
dv &= x^2 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^2 \, dx  \\
\dfrac{dv}{dx} &= x^2 \\
v &= \dfrac{1}{3}x^3
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{x} \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^2 \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \int x^2 \, dx \\
&= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \cdot \dfrac{1}{3}x^3 + C \\
&= \dfrac{1}{3}x^3\ln(x) - \dfrac{1}{9}x^3 + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \cos(2x) , dx = \dfrac{1}{2}x^2\sin(2x) + \dfrac{1}{2}x\cos(2x) - \dfrac{1}{4}\sin(2x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^2 \cos(2x) \, dx
$$

Dus,

$$
F(x) = \int x^2 \cos(2x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^2 \\
dv &= \cos(2x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(2x) \, dx  \\
\dfrac{dv}{dx} &= \cos(2x) \\
v &= \dfrac{1}{2}\sin(2x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x^2 \cdot \dfrac{1}{2}\sin(2x) - \int \dfrac{1}{2}\sin(2x) 2x \, dx\\
&= \dfrac{1}{2}x^2\sin(2x) - \int x\sin(2x) \, dx
\end{align*}
$$

De integraal $\int x\sin(2x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int x\sin(2x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \
dv &= \sin(2x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &=  \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \sin(2x) \, dx  \\
\dfrac{dv}{dx} &= \sin(2x) \\
v &= -\dfrac{1}{2}\cos(2x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int x\sin(2x) , dx &= x \cdot -\dfrac{1}{2}\cos(2x) - \int -\dfrac{1}{2}\cos(2x) \, dx \\
&= -\dfrac{1}{2}x\cos(2x) + \dfrac{1}{2} \int \cos(2x) \, dx\\
&= -\dfrac{1}{2}x\cos(2x) + \dfrac{1}{2} \cdot \dfrac{1}{2}\sin(2x) + C\\
&= -\dfrac{1}{2}x\cos(2x) + \dfrac{1}{4}\sin(2x) + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 \cos(2x) \, dx \\
&= \dfrac{1}{2}x^2\sin(2x) - \int x\sin(2x) \, dx \\
&= \dfrac{1}{2}x^2\sin(2x) - \left(-\dfrac{1}{2}x\cos(2x) + \dfrac{1}{4}\sin(2x) + C\right) \\
&= \dfrac{1}{2}x^2\sin(2x) + \dfrac{1}{2}x\cos(2x) - \dfrac{1}{4}\sin(2x) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^3 e^{-x} \, dx = \left(-x^3 - 3x^2 - 6x - 6\right)e^{-x} + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^3 e^{-x}
$$

Dus,

$$
F(x) = \int x^3 e^{-x} \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^3 \\
dv &= e^{-x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 3x^2 \\
du &= 3x^2 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{-x} \, dx  \\
\dfrac{dv}{dx} &= e^{-x} \\
v &= -e^{-x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x^3 \cdot -e^{-x} - \int -e^{-x} 3x^2 , dx\\
&= -x^3e^{-x} + \int 3x^2e^{-x} \, dx
\end{align*}
$$

De integraal $\int 3x^2e^{-x} \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int 3x^2e^{-x} \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 3x^2 \\
dv &= e^{-x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 6x \\
du &= 6x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{-x} \, dx  \\
\dfrac{dv}{dx} &= e^{-x} \\
v &= -e^{-x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int 3x^2e^{-x} \, dx &= 3x^2 \cdot -e^{-x} - \int -e^{-x} 6x \, dx \\
&= -3x^2e^{-x} + \int 6xe^{-x} \, dx
\end{align*}
$$

De integraal $\int 6xe^{-x} \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int 6xe^{-x} \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 6x \\
dv &= e^{-x} \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 6 \\
du &= 6 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= e^{-x} \, dx  \\
\dfrac{dv}{dx} &= e^{-x} \\
v &= -e^{-x}
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int 6xe^{-x} \, dx &= 6x \cdot -e^{-x} - \int -e^{-x} 6 \, dx \\
&= -6xe^{-x} + 6 \int e^{-x} \, dx\\
&= -6xe^{-x} + 6(-e^{-x}) + C\\
&= -6xe^{-x} - 6e^{-x} + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^3 e^{-x} \, dx \\
&= -x^3e^{-x} + \int 3x^2e^{-x} \, dx \\
&= -x^3e^{-x} + \left(-3x^2e^{-x} + \int 6xe^{-x} , dx\right) \\
&= -x^3e^{-x} - 3x^2e^{-x} + \left(-6xe^{-x} - 6e^{-x} + C\right) \\
&= -x^3e^{-x} - 3x^2e^{-x} - 6xe^{-x} - 6e^{-x} + C \\
&= \left(-x^3 - 3x^2 - 6x - 6\right)e^{-x} + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \ln(2x) \, dx = \dfrac{1}{3}x^3\ln(2x) - \dfrac{1}{9}x^3 + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^2 \ln(2x) \, dx
$$

Dus,

$$
F(x) = \int x^2 \ln(2x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(2x) \\
dv &= x^2 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^2 \, dx  \\
\dfrac{dv}{dx} &= x^2 \\
v &= \dfrac{1}{3}x^3
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln(2x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{x} \, dx \\
&= \ln(2x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^2 \, dx \\
&= \ln(2x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \int x^2 \, dx \\
&= \ln(2x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \cdot \dfrac{1}{3}x^3 + C \\
&= \dfrac{1}{3}x^3\ln(2x) - \dfrac{1}{9}x^3 + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \arctan(x) \, dx = \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{6}x^2 + \dfrac{1}{6}\ln(1+x^2) + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^2 \arctan(x)
$$

Dus,

$$
F(x) = \int x^2 \arctan(x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \arctan(x) \\
dv &= x^2 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{1+x^2} \\
du &= \dfrac{1}{1+x^2} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^2 \, dx  \\
\dfrac{dv}{dx} &= x^2 \\
v &= \dfrac{1}{3}x^3
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \arctan(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{1+x^2} \, dx \\
&= \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{3} \int \dfrac{x^3}{1+x^2} \, dx
\end{align*}
$$

Herschrijf de breuk:

$$
\begin{align*}
\dfrac{x^3}{1+x^2} = x - \dfrac{x}{1+x^2}
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{3} \int \left(x - \dfrac{x}{1+x^2}\right) \, dx \\
&= \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{3} \int x , dx + \dfrac{1}{3} \int \dfrac{x}{1+x^2} \, dx
\end{align*}
$$

Bereken beide integralen:

$$
\begin{align*}
\int x \, dx &= \dfrac{1}{2}x^2 \\
\int \dfrac{x}{1+x^2} \, dx &= \dfrac{1}{2}\ln(1+x^2)
\end{align*}
$$

Invullen geeft:

$$
\begin{align*}
F(x) &= \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{3} \cdot \dfrac{1}{2}x^2 + \dfrac{1}{3} \cdot \dfrac{1}{2}\ln(1+x^2) + C \
&= \dfrac{1}{3}x^3\arctan(x) - \dfrac{1}{6}x^2 + \dfrac{1}{6}\ln(1+x^2) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^3 \cos(x) \, dx = x^3\sin(x) + 3x^2\cos(x) - 6x\sin(x) - 6\cos(x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^3 \cos(x) \, dx
$$

Dus,

$$
F(x) = \int x^3 \cos(x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^3 \\
dv &= \cos(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 3x^2 \\
du &= 3x^2 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(x) \, dx  \\
\dfrac{dv}{dx} &= \cos(x) \\
v &= \sin(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x^3 \cdot \sin(x) - \int \sin(x) 3x^2 \, dx\\
&= x^3\sin(x) - \int 3x^2\sin(x) \, dx
\end{align*}
$$

De integraal $\int 3x^2\sin(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int 3x^2\sin(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 3x^2 \\
dv &= \sin(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 6x \\
du &= 6x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \sin(x) \, dx  \\
\dfrac{dv}{dx} &= \sin(x) \\
v &= -\cos(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int 3x^2\sin(x) \, dx &= 3x^2 \cdot -\cos(x) - \int -\cos(x) 6x \, dx \\
&= -3x^2\cos(x) + \int 6x\cos(x) \, dx
\end{align*}
$$

De integraal $\int 6x\cos(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int 6x\cos(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= 6x \\
dv &= \cos(x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 6 \\
du &= 6 \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(x) \, dx  \\
\dfrac{dv}{dx} &= \cos(x) \\
v &= \sin(x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int 6x\cos(x) \, dx &= 6x \cdot \sin(x) - \int \sin(x) 6 \, dx \\
&= 6x\sin(x) - 6 \int \sin(x) \, dx\\
&= 6x\sin(x) + 6\cos(x) + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^3 \cos(x) \, dx \\
&= x^3\sin(x) - \int 3x^2\sin(x) \, dx \\
&= x^3\sin(x) - \left(-3x^2\cos(x) + \int 6x\cos(x) \, dx\right) \\
&= x^3\sin(x) + 3x^2\cos(x) - \left(6x\sin(x) + 6\cos(x) + C\right) \\
&= x^3\sin(x) + 3x^2\cos(x) - 6x\sin(x) - 6\cos(x) + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2i

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^3 \ln^2(x) \, dx = \dfrac{1}{4}x^4\ln^2(x) - \dfrac{1}{8}x^4\ln(x) + \dfrac{1}{32}x^4 + C
$$

:::{dropdown} Uitwerking

Primitiveer:

$$
f(x) = x^3 \ln^2(x)
$$

Dus,

$$
F(x) = \int x^3 \ln^2(x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln^2(x) \\
dv &= x^3 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2\ln(x) \cdot \dfrac{1}{x} \\
du &= 2\ln(x) \cdot \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^3 \, dx  \\
\dfrac{dv}{dx} &= x^3 \\
v &= \dfrac{1}{4}x^4
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= \ln^2(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^4 2\ln(x) \cdot \dfrac{1}{x} \, dx\\
&= \ln^2(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{2} \int x^3\ln(x) \, dx
\end{align*}
$$

De integraal $\int x^3\ln(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int x^3\ln(x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= \ln(x) \\
dv &= x^3 \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= \dfrac{1}{x} \\
du &= \dfrac{1}{x} \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= x^3 \, dx  \\
\dfrac{dv}{dx} &= x^3 \\
v &= \dfrac{1}{4}x^4
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int x^3\ln(x) , dx &= \ln(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^4 \dfrac{1}{x} \, dx \\
&= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \int x^3 \, dx\\
&= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \cdot \dfrac{1}{4}x^4 + C\\
&= \dfrac{1}{4}x^4\ln(x) - \dfrac{1}{16}x^4 + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^3 \ln^2(x) \, dx \\
&= \ln^2(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{2} \int x^3\ln(x) \, dx \\
&= \ln^2(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{2} \left(\dfrac{1}{4}x^4\ln(x) - \dfrac{1}{16}x^4 + C\right) \\
&= \dfrac{1}{4}x^4\ln^2(x) - \dfrac{1}{8}x^4\ln(x) + \dfrac{1}{32}x^4 + C
\end{align*}
$$

:::
::::

## Opgave 6.2.2j

::::{admonition} Antwoord
:class: important, dropdown

$$
\int x^2 \sin(3x) \, dx = -\dfrac{1}{3}x^2\cos(3x) + \dfrac{2}{9}x\sin(3x) + \dfrac{2}{27}\cos(3x) + C
$$

:::{dropdown} Uitwerking

Bereken de onbepaalde integraal:

$$
\int x^2 \sin(3x) \, dx
$$

Dus,

$$
F(x) = \int x^2 \sin(3x) \, dx
$$

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x^2 \
dv &= \sin(3x) , dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 2x \\
du &= 2x \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \sin(3x) \, dx  \\
\dfrac{dv}{dx} &= \sin(3x) \\
v &= -\dfrac{1}{3}\cos(3x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
&= x^2 \cdot -\dfrac{1}{3}\cos(3x) - \int -\dfrac{1}{3}\cos(3x) 2x \, dx\\
&= -\dfrac{1}{3}x^2\cos(3x) + \dfrac{2}{3} \int x\cos(3x) \, dx
\end{align*}
$$

De integraal $\int x\cos(3x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.

$$
\int x\cos(3x) \, dx
$$

Kies de functie $u$ en $dv$:

$$
\begin{align*}
u &= x \\
dv &= \cos(3x) \, dx
\end{align*}
$$

Bepaal $du$:

$$
\begin{align*}
\dfrac{du}{dx} &= 1 \\
du &=  \, dx
\end{align*}
$$

Bepaal de functie $v$:

$$
\begin{align*}
dv &= \cos(3x) \, dx  \\
\dfrac{dv}{dx} &= \cos(3x) \\
v &= \dfrac{1}{3}\sin(3x)
\end{align*}
$$

Toepassen van de regel voor partieel integreren geeft:

$$
\begin{align*}
\int u \, dv &= uv - \int v \, du \\
\int x\cos(3x) , dx &= x \cdot \dfrac{1}{3}\sin(3x) - \int \dfrac{1}{3}\sin(3x) \, dx \\
&= \dfrac{1}{3}x\sin(3x) - \dfrac{1}{3} \int \sin(3x) \, dx\\
&= \dfrac{1}{3}x\sin(3x) + \dfrac{1}{3} \cdot \dfrac{1}{3}\cos(3x) + C\\
&= \dfrac{1}{3}x\sin(3x) + \dfrac{1}{9}\cos(3x) + C
\end{align*}
$$

Dus,

$$
\begin{align*}
F(x) &= \int x^2 \sin(3x) \, dx \\
&= -\dfrac{1}{3}x^2\cos(3x) + \dfrac{2}{3} \int x\cos(3x) \, dx \\
&= -\dfrac{1}{3}x^2\cos(3x) + \dfrac{2}{3} \left( \dfrac{1}{3}x\sin(3x) + \dfrac{1}{9}\cos(3x) + C \right) \\
&= -\dfrac{1}{3}x^2\cos(3x) + \dfrac{2}{9}x\sin(3x) + \dfrac{2}{27}\cos(3x) + C
\end{align*}
$$

:::
::::
