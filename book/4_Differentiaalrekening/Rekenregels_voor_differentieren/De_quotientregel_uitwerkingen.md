## 4.3 Uitwerkingen

### Opgave 4.3a

::::{admonition} Antwoord
:class: important, dropdown

$$
  \dfrac{df}{dx} = 2x e^x + x^2 e^x
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

### Opgave 4.2b