# 5.3 Reeksen van Maclaurin en Taylor


# 5.3.1 Reeksen van Maclaurin

```{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = (x^2-4)(x^3+7x-5)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= (x^2-4) \\
  v &= (x^3+7x-5)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x^2 \\
  \dfrac{dv}{dx} &= 3x^2+7
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= 2x^2 \cdot (x^3+7x-5) + (x^2-4) \cdot (3x^2+7)
\end{align}
```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^x \\
  v &= (2x^3+x^2+3x)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 6x^2+2x+3
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= e^x \cdot (2x^3+x^2+3x) + e^x \cdot (6x^2+2x+3) \\
   &= e^x \left( (2x^3 + x^2 + 3x) + (6x^2 + 2x + 3) \right) \\
   &= e^x (2x^3 + 7x^2 + 5x + 3 )
\end{align}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \ln(x) \\
  v &= \cos(x)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= -\sin(x)
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= \dfrac{1}{x} \cdot \cos(x) + \ln(x) \cdot -\sin(x) \\
   &= \dfrac{\cos(x)}{x} - \ln(x)\sin(x)
\end{align}

```
````


# 5.3.2 Reeksen Taylor

```{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = (x^2-4)(x^3+7x-5)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= (x^2-4) \\
  v &= (x^3+7x-5)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x^2 \\
  \dfrac{dv}{dx} &= 3x^2+7
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= 2x^2 \cdot (x^3+7x-5) + (x^2-4) \cdot (3x^2+7)
\end{align}
```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^x \\
  v &= (2x^3+x^2+3x)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 6x^2+2x+3
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= e^x \cdot (2x^3+x^2+3x) + e^x \cdot (6x^2+2x+3) \\
   &= e^x \left( (2x^3 + x^2 + 3x) + (6x^2 + 2x + 3) \right) \\
   &= e^x (2x^3 + 7x^2 + 5x + 3 )
\end{align}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \ln(x) \\
  v &= \cos(x)
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= -\sin(x)
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= \dfrac{1}{x} \cdot \cos(x) + \ln(x) \cdot -\sin(x) \\
   &= \dfrac{\cos(x)}{x} - \ln(x)\sin(x)
\end{align}

```
````
