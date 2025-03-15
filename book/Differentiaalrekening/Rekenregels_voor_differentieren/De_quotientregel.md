# 1.3 De quotiëntregel

````{admonition} Theorie
:class: tip, dropdown open

De **quotiëntregel** is een afgeleide regel die wordt gebruikt bij het differentiëren van een functie die een quotiënt (breuk) is van twee differentieerbare functies. Als een functie $f(x)$ geschreven kan worden als een quotiënt van $u(x)$ en $v(x)$, dan geldt:

\begin{align*}
    f(x) = \frac{u(x)}{v(x)}
\end{align*}

De afgeleide van $f(x)$ wordt dan gegeven door:

\begin{align*}
    \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
\end{align*}

Dit betekent dat je eerst de noemer neemt deze vermenigvuldigt met afgeleide van de teller, daarna de teller vermenigvuldigt met de afgeleide van de noemer, en vervolgens het verschil deelt door het kwadraat van de noemer.

````{admonition} Ezelsbruggetje voor de quotiëntregel
:class: warning

$\dfrac{N\cdot AT - T \cdot AN}{N^2}$

Noemer $\cdot$ Afgeleide van de Teller - Teller $\cdot$ Afgeleide van de Noemer gedeelt door noemer$^2$

````

## 1.3.1 De quotiëntregel

```{admonition} Voorbeeld 1: quotiëntregel
:class: dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{x^2}{x+1}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= x^2 \\
  v &= x+1 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= 1
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
  &= \frac{ (x + 1) \cdot 2x - x^2 \cdot  1 }{ (x + 1)^2} \\
  &= \frac{ 2x^2 + 2x - x^2 }{ (x + 1)^2} \\
  &= \frac{ x^2 + 2x }{ (x + 1)^2} \\
\end{align}

```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= e^x \\
  v &= x^2+5 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= e^x \\
  \dfrac{dv}{dx} &= 2x
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
  &= \frac{ (x^2 + 5) \cdot e^x - e^x \cdot  2x }{ (x^2 + 5)^2} \\
  &= \frac{  e^x(x^2 - 2x + 5) }{ (x^2 + 5)^2}
\end{align}


```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \log(4x-3) \sqrt{x^2-6}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown
Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= x^2 \\
  v &= x+1 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= 1
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
  &= \frac{ (x + 1) \cdot 2x - x^2 \cdot  1 }{ (x + 1)^2} \\
  &= \frac{ 2x^2 + 2x - x^2 }{ (x + 1)^2} \\
  &= \frac{ x^2 + 2x }{ (x + 1)^2} \\
\end{align}

```
````

## 1.3.2 De quotiëntregel + kettingregel

````{admonition} Oefening 3
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= x^2 \\
  v &= x+1 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= 1
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
  &= \frac{ (x + 1) \cdot 2x - x^2 \cdot  1 }{ (x + 1)^2} \\
  &= \frac{ 2x^2 + 2x - x^2 }{ (x + 1)^2} \\
  &= \frac{ x^2 + 2x }{ (x + 1)^2} \\
\end{align}

```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{e^x}{x^2+5}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= x^2 \\
  v &= x+1 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2x \\
  \dfrac{dv}{dx} &= 1
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} = \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2}
  &= \frac{ (x + 1) \cdot 2x - x^2 \cdot  1 }{ (x + 1)^2} \\
  &= \frac{ 2x^2 + 2x - x^2 }{ (x + 1)^2} \\
  &= \frac{ x^2 + 2x }{ (x + 1)^2} \\
\end{align}


```
````