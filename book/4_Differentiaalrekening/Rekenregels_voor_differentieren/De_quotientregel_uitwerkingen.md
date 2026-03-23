## 4.3 Uitwerkingen

### Opgave 4.3a

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  xe^x }{ (x + 1)^2}
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{e^x}{x+1}
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= e^x \\
  v &= x + 1\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x + 1) \cdot e^x - e^x \cdot  1 }{ (x + 1)^2} \\
  &= \frac{  xe^x }{ (x + 1)^2}
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 4.3b

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  x(1-2\ln(x)) }{ x ^4 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{ \ln(x) }{ x^2 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \ln(x) \\
  v &= x^2\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= 2x
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ x^2 \cdot \dfrac{1}{x}  - \ln(x)  \cdot  2x }{ (x^2)^2} \\
  &= \frac{  x(1-2\ln(x)) }{ x ^4 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">


### Opgave 4.3c

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = \frac{  (x+2) \cdot \sin(x)  - \cos(x) }{ (x+2)^2 }
$$

:::{dropdown} Uitwerking
Bereken de afgeleide van de volgende functie:

$$
  f(x) =  \dfrac{ \sin(x) }{ x+2 }
$$

Kies de functies $u(x)$ en $v(x)$:

$$
\begin{align}
  u &= \sin(x) \\
  v &= x+2\\
\end{align}
$$

Differentieer de functies $u(x)$ en $v(x)$:

$$
  \dfrac{du}{dx} &= \cos(x) \\
  \dfrac{dv}{dx} &= 1
$$

Toepassen van de quotiëntregel:

$$
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (x+2) \cdot \sin(x)  - \cos(x)  \cdot 1 }{ (x+2)^2} \\
  &= \frac{  (x+2) \cdot \sin(x)  - \cos(x) }{ (x+2)^2 }
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">