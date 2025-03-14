# 1.2 De productregel

````{admonition} Theorie
:class: tip, dropdown open

De **productregel** is een afgeleide regel die wordt gebruikt bij het differentiëren van een functie die het product is van twee differentieerbare functies. Als een functie  $f(x)$ bestaat uit het product van twee functies $u(x)$ en $v(x)$, dan geldt:

\begin{align*}
  f(x) = u(x) \cdot v(x)
\end{align*}

De afgeleide van $f(x)$ wordt dan gegeven door:

\begin{align*}
  \dfrac{df(x)}{dx} = \dfrac{du(x)}{dx} \cdot v(x) + u(x) \cdot \dfrac{dv(x)}{dx}
\end{align*}

Dit betekent dat je eerst de afgeleide van de eerste functie neemt en deze vermenigvuldigt met de tweede functie, en daarna de eerste functie vermenigvuldigt met de afgeleide van de tweede functie.

````{admonition} Standaard afgeleiden
:class: warning

| Functie $f(x)$ | Afgeleide $\dfrac{df(x)}{dx}$ |
|--------------------|-------------------|
| \( c \) (constante) | $0$ |
| $x^n$ | $n x^{n-1}$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x \ln a$ |
| $\ln x$ | $\frac{1}{x}$ |
| $\log_a$  | $\frac{1}{x \ln a}$ |
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |

````

## 1.2.1 De productregel

```{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = (x^2-4)(x^3+7x-5)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= (x^2-4) \\
  v &= (x^3+7x-5)
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
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

Bereken de afgeleide van:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = e^x(2x^3+x^2+3x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^x \\
  v &= (2x^3+x^2+3x)
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
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

Bereken de afgeleide van:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = \ln(x)\cos(x)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \ln(x) \\
  v &= \cos(x)
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
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

## 1.2.2 De productregel + kettingregel

```{admonition} Voorbeeld 2: productregel + kettingregel
:class: dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = \sin(7x)(3x-1)^4
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \sin(7x) \\
  v &= (3x-1)^4
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 7\cos(7x) \\
  \dfrac{dv}{dx} &= 4(3x-1)^3 \cdot 3 \\
  &=12(3x-1)^3
\end{align}

Toepassen van de productregel:
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= 7\cos(7x) \cdot (3x-1)^4 + \sin(7x) \cdot 12(3x-1)^3
\end{align*}
```

````{admonition} Oefening 3
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = -5e^{-4x}4^{2x}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = -5e^{-4x}4^{2x}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= -5e^{-4x} \\
  v &= 4^{2x}
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= -5e^{-4x} \cdot -4 \\
  &= 20e^{-4x} \\
  \dfrac{dv}{dx} &= 4^{2x} \cdot \ln(4) \cdot 2
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= 20e^{-4x} \cdot 4^{2x} + -5e^{-4x} \cdot 4^{2x} \cdot \ln(4) \cdot 2 \\
   &= -5e^{-4x} \cdot 4^{2x}  ( -4 + 2 \ln(4))
\end{align}

```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) =  \log(4x-3) \sqrt{x^2-6}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = \log(4x-3) \sqrt{x^2-6}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= \log(4x-3) \\
  v &= \sqrt{x^2-6} \\
  &=  (x^2-6)^{\frac{1}{2}}
\end{align}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= \dfrac{1}{(4x-3) \ln(10)} \cdot 4 \\
  &= \dfrac{4}{(4x-3) \ln(10)} \\
  \dfrac{dv}{dx} &= \dfrac{1}{2}(x^2 -6)^{-\frac{1}{2}} \cdot 2x \\
  &= \dfrac{x}{ \sqrt{x^2-6} }
\end{align}

Toepassen van de productregel:
\begin{align}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
  &= \dfrac{4}{(4x-3) \ln(10)} \cdot \sqrt{x^2-6} + \log(4x-3) \cdot \dfrac{x}{ \sqrt{x^2-6} } \\
  &= \dfrac{4\sqrt{x^2-6}}{(4x-3) \ln(10)}  + \dfrac{x\log(4x-3)}{ \sqrt{x^2-6} }
\end{align}

```
````
