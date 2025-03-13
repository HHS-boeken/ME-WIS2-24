# De productregel

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

---

````

```{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van:
\begin{align*}
  f(x) = (x^2-4)(x^3+7x-5)
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align*}
  u &= (x^2-4) \\
  v &= (x^3+7x-5)
\end{align*}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align*}
  \dfrac{du}{dx} &= 2x^2 \\
  \dfrac{dv}{dx} &= 3x^2+7
\end{align*}

Toepassen van de productregel:
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= 2x^2 \cdot (x^3+7x-5) + (x^2-4) \cdot (3x^2+7)
\end{align*}
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
\begin{align*}
  u &= e^x \\
  v &= (2x^3+x^2+3x)
\end{align*}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align*}
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 6x^2+2x+3
\end{align*}

Toepassen van de productregel:
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= e^x \cdot (2x^3+x^2+3x) + e^x \cdot (6x^2+2x+3) \\
   &= e^x \left( (2x^3 + x^2 + 3x) + (6x^2 + 2x + 3) \right) \\
   &= e^x (2x^3 + 7x^2 + 5x + 3 )
\end{align*}

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
\begin{align*}
  u &= \ln(x) \\
  v &= \cos(x)
\end{align*}

Differentier de functies $u(x)$ en $v(x)$:
\begin{align*}
  \dfrac{du}{dx} &= \dfrac{1}{x} \\
  \dfrac{dv}{dx} &= -\sin(x)
\end{align*}

Toepassen van de productregel:
\begin{align*}
  \dfrac{df}{dx} = \dfrac{d}{dx}(u \cdot v) &= \dfrac{du}{dx} \cdot v + u \cdot \dfrac{dv}{dx} \\
   &= \dfrac{1}{x} \cdot \cos(x) + \ln(x) \cdot -\sin(x) \\
   &= \dfrac{\cos(x)}{x} - \ln(x)\sin(x)
\end{align*}

```
````


# 4.3 Opgaven

## Opgave 4.1a

Bepaal de afgeleide van de volgende functie.
\begin{align*}
 f(x) = x^2 e^x
\end{align*}

## Opgave 4.1b

Differentieer de volgende functie.
\begin{align*}
 g(x) = (x + 1) \cos x
\end{align*}

## Opgave 4.1c

Toon aan dat de afgeleide van \( h(x) = x \ln x \) gelijk is aan:
\begin{align*}
 h'(x) = \ln x + 1
\end{align*}

## Opgave 4.1d

Differentieer de volgende functie.
\begin{align*}
 p(x) = (e^x + x^2)(\cos x)
\end{align*}

## Opgave 4.1e

Bepaal de afgeleide van de volgende functie.
\begin{align*}
 q(x) = x^4 \ln x
\end{align*}

## Opgave 4.2a

Bereken de afgeleide van de volgende functie met de productregel.
\begin{align*}
 f(x) = (2x^3 + 3x) e^{4x}
\end{align*}

## Opgave 4.2b

Differentieer de volgende functie en schrijf het resultaat zo eenvoudig mogelijk.
\begin{align*}
 g(x) = (x^2 + 1)(\ln x)
\end{align*}

## Opgave 4.2c

Bereken de afgeleide van:
\begin{align*}
 h(x) = (x^4 - 2x^2) e^x
\end{align*}

## Opgave 4.2d

Toon aan dat de afgeleide van de functie \( p(x) = x^n e^x \) wordt gegeven door:
\begin{align*}
 p'(x) = n x^{n-1} e^x + x^n e^x
\end{align*}

## Opgave 4.2e

Bereken de afgeleide van de functie:
\begin{align*}
 q(x) = (\ln x + x^2)(e^x)
\end{align*}

## Opgave 4.3a

Bereken de afgeleide van de volgende functie.
\begin{align*}
 f(x) = (x^3 + e^x)(\ln x)
\end{align*}

## Opgave 4.3b

Differentieer de volgende functie, die relevant is voor trillingsanalyse.
\begin{align*}
 y(t) = e^{-\alpha t} \cos(\omega t)
\end{align*}

## Opgave 4.3c

Bereken de afgeleide van de volgende functie.
\begin{align*}
 f(x) = (\ln x + e^x)(\cos x + x)
\end{align*}

## Opgave 4.3d

Differentieer de volgende functie.
\begin{align*}
 z(t) = (t^2 + 1) e^{-t}
\end{align*}

## Opgave 4.3e

Differentieer:
\begin{align*}
 v(t) = (e^{-t} + \ln (t+1)) (\cos \omega t)
\end{align*}

# Uitwerkingen

## Opgave 4.1a

Bepaal de afgeleide van de volgende functie.
\begin{align*}
 f(x) = x^2 e^x
\end{align*}

**Uitwerking:**

Deze functie is een **product** van twee **factoren**:
- \( u = x^2 \)
- \( v = e^x \)

We passen de **productregel** toe:
\begin{align*}
 (uv)' = u' v + u v'
\end{align*}

### Stap 1: Bereken de afgeleiden
- De afgeleide van \( u = x^2 \) is:
  \begin{align*}
  u' = 2x
  \end{align*}
- De afgeleide van \( v = e^x \) is:
  \begin{align*}
  v' = e^x
  \end{align*}

### Stap 2: Pas de productregel toe
\begin{align*}
 f'(x) &= (2x \cdot e^x) + (x^2 \cdot e^x)
\end{align*}

### Stap 3: Factoriseer waar mogelijk
\begin{align*}
 f'(x) &= e^x (2x + x^2)
\end{align*}

**Eindantwoord:**
\begin{align*}
 f'(x) = (2x + x^2)e^x
\end{align*}



