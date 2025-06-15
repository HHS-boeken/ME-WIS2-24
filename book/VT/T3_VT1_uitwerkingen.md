## T3 - Voorbeeld Toets 1: Uitwerkingen

### Opgave 1 ( punten)
````{admonition} Antwoord
:class: dropdown

De uitkomst is:


\begin{align*}
    3x^2 + \frac{12}{5} - \dfrac{6}{5(5x + 3)}
\end{align*}


```{admonition} Uitwerking
:class: dropdown

Berekenen door middel van een staartdeling:

$
\frac{15x^3 + 9x^2 + 12x + 6}{5x + 3}
$

Zet de staartdeling op:


\begin{align*}
    5x + 3 \quad / 15x^3 + 9x^2 + 12x + 6 \backslash
\end{align*}


Deel de eerste term $15x^3$ door $5x$ dit geeft:

$
\frac{15x^3}{5x} = 3x^2
$

Dus,

\begin{align*}
 5x + 3 \quad / &15x^3 + 9x^2 + 12x + 6 \backslash \quad 3x^2\\
&15x^3 + 9x^2 \\
&------ \quad -\\
&\quad \quad \quad 0 + 12x + 6
\end{align*}


Deel $12x$ door $5x$:

$
\frac{12x}{5x} = \frac{12}{5}
$

Dus,

\begin{align*}
    5x + 3 \quad / &15x^3 + 9x^2 + 12x + 6 \backslash \quad 3x^2 + \frac{12}{5}\\
    &15x^3 + 9x^2 \\
    &---------- \quad -\\
    &\quad \quad \quad 0 + 12x + 6 \\
    &\quad \quad \quad 0 + 12x + \frac{36}{5} \\
    &---------- \quad -\\
    &\quad \quad \quad \quad \quad \quad - \frac{6}{5} \\
\end{align*}


De rest is $-\frac{6}{5}$, dus de uiteindelijke uitkomst is:


\begin{align*}
    3x^2 + \frac{12}{5} - \dfrac{6}{5(5x + 3)}
\end{align*}


```
````

<hr style="border:1px solid #9EA700">

### Opgave 2 ( punten)

````{admonition} Antwoord
:class: dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(5x+1)}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(5x+1)}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &=  \sin^2(x) \\
  v &=  \ln(5x+1) \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2 \sin(x)\cos(x) \\
  \dfrac{dv}{dx} &= \dfrac{1}{5x+1} \cdot 5 \\
                &= \dfrac{5}{5x+1} \\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (\ln(5x+1)) \cdot 2 \sin(x)\cos(x)  - \sin^2(x) \cdot  \dfrac{5}{5x+1} }{ (\ln(5x+1))^2} \\
  &= \frac{ 2 \sin(x)\cos(x)(\ln(5x+1)) - \dfrac{5\sin^2(x)}{5x+1} }{ \ln^2(5x+1)} \\
\end{align}

```
````