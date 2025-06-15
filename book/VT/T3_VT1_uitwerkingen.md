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

<hr style="border:1px solid #9EA700">

### Opgave 3 ( punten)
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
<hr style="border:1px solid #9EA700">

### Opgave 4 ( punten)
````{admonition} Antwoord
:class: important, dropdown

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
\begin{align*}
    f(x) = e^{x^2+5}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
\begin{align*}
    f(x) = e^{x^2+5}
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 3e orde:
\begin{align}
  f(x) &= e^{x^2+5} \\
  f'(x) &= 2xe^{x^2+5} \\
  f''(x) &= (4x^2+2)e^{x^2+5} \\
  f'''(x) &= (8x^3+12x)e^{x^2+5}
\end{align}

Evalueer de afgeleide bij $x= 2$:
\begin{align}
  f(2) &= e^9 \\
  f'(2) &=  4e^9 \\
  f''(2) &= 18e^9\\
  f'''(2) &= 88e^9
\end{align}

Invullen van de waaardes in de Taylor-reeks rond $x=2$ geeft:

\begin{align}
  f(x) &\approx   f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 \\
\end{align}

\begin{align}
  f(x) &\approx   e^9 + 4e^9(x-2) + \dfrac{18e^9}{2!}(x-2)^2 + \dfrac{88e^9}{3!}(x-2)^3   \\
  f(x) &\approx   e^9 + 4e^9(x-2) + \dfrac{18e^9}{2}(x-2)^2 + \dfrac{88e^9}{6}(x-2)^3   \\
  f(x) &\approx   e^9 + 4e^9(x-2) + 9e^9(x-2)^2 + \dfrac{44e^9}{3}(x-2)^3   \\
  f(x) &\approx   e^9(1 + 4(x-2) + 9(x-2)^2 + \dfrac{44}{3}(x-2)^3)   \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5 ( punten)
````{admonition} Antwoord
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{x^4 }{x^2 + 4x + 3}  \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{x^4 }{x^2 + 4x + 3}  \, dx
\end{align*}

De teller is groter dan de noemer, dus staartdeling maken.

\begin{align}
 x^2 + 4x + 3 \quad / &x^4 \quad \quad \quad \quad \quad \quad \quad \quad  \backslash \quad x^2 - 4x + 13\\
&x^4 + 4x^3 + 3x^2 \\
&------------- \quad -\\
&\quad \quad -4x^3 - 3x^2 \\
&\quad \quad -4x^3 - 16x^2 - 12x \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad  13x^2 + 12x \\
&\quad \quad \quad \quad \quad \quad  13x^2 + 52x + 39 \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad \quad \quad  -40x - 39 \\
\end{align}

De rest is $-40x-39$, dus de uiteindelijke uitkomst is:
\begin{align}
& x^2 - 4x + 13 + \dfrac{-40x-39}{x^2 + 4x + 3} = \\
& x^2 - 4x + 13 - \dfrac{40x + 39 }{x^2 + 4x + 3} \\
\end{align}

Dit geeft:
\begin{align}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &=  \int x^2 - 4x + 13 - \dfrac{40x + 39 }{x^2 + 4x + 3}  \, dx \\
\end{align}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{40x + 39 }{x^2 + 4x + 3}  \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 3) } \\
    &= \dfrac{ A(x + 3) }{ (x + 1) (x + 3) } + \dfrac{ B(x + 1) }{(x + 1) (x + 3 ) } \\
    &= \dfrac{ A(x + 3) + B(x + 1) }{ (x + 1)(x + 3) } \\
    &= \dfrac{ Ax + 3A + Bx + B  }{ (x + 1)(x + 3) } \\
    &= \dfrac{ (A + B)x + 3A + B }{ (x + 1)(x + 3) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{40x + 39}{(x + 1)(x + 3)} = \dfrac{ (A+B)x + 3A + B }{ (x + 1)(x + 3) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   40x  + 39 = (A + B)x + 3A + B
\end{align}

Hieruit volgt:
\begin{align}
   A + B &= 40 \\
   3A + B &= 39
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 40 - B\\
   3 (40 - B) + B &= 39 \\
   120 - 3B + B &= 39
   -2B &= -81
    B &= 40\dfrac{1}{2}
\end{align}

B invullen geeft:
\begin{align*}
   A &= 40 - B \\
   A &= 40 - 40\dfrac{1}{2} \\
   A &= -\dfrac{1}{2}
\end{align*}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{x^4 }{x^2 + 4x + 3} \, dx &= \int x^2 - 4x + 13 - \dfrac{40x + 39}{x^2 + 4x + 3} \, dx \\
   &= \int x^2 - 4x + 13 - \dfrac{40x + 39}{(x+1)(x+3)} \, dx\\
   &= \int (x^2 - 4x + 13) \, dx - \int \dfrac{40x + 39}{(x+1)(x+3)} \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ A }{ (x + 1) } + \dfrac{ B }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ A }{ (x + 1) } \, dx - \int \dfrac{ B }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ -\frac{1}{2} }{ x + 1 } \, dx - \int \dfrac{ 40\dfrac{1}{2} }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx + \frac{1}{2} \int \dfrac{ 1 }{ x + 1 } \, dx - 40\dfrac{1}{2} \int \dfrac{ 1 }{ (x + 3) } \, dx\\
   &= \dfrac{1}{3}x^3 - 2x^2 + 13x + \frac{1}{2}  \ln|x + 1 | - 40\frac{1}{2}  \ln|x + 3 |  + C\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6 ( punten)

<hr style="border:1px solid #9EA700">

### Opgave 7 ( punten)

<hr style="border:1px solid #9EA700">

### Opgave 8 ( punten)

<hr style="border:1px solid #9EA700">

### Opgave 9 ( punten)

<hr style="border:1px solid #9EA700">

### Opgave 10 ( punten)

````{admonition} Oefening 1
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    2z^2 + 3z + 5 = 0
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    2z^2 + 3z + 5 = 0
\end{align*}

Bereken de discriminant $D$:
\begin{align}
    D & = b^2 - 4ac \\
    &= 3^2 - 4 \cdot 2 \cdot 5  \\
    &= 9 - 40 \\
    &= -31
\end{align}

Gebruik de ABC-formule:
\begin{align}
    z &= \dfrac{-3 \pm \sqrt{-31} }{2 \cdot 2} \\
    z &= \dfrac{-3 \pm \sqrt{-31} }{ 4 } \\
    z &= \dfrac{-3 \pm i\sqrt{31} }{ 4 } 
\end{align}

Dus:
\begin{align}
    z_1 &= -\dfrac{3}{4} + \dfrac{i\sqrt{31} }{4} \\
    z_2 &= -\dfrac{3}{4} - \dfrac{i\sqrt{31}  }{4}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 11 ( punten)

````{admonition} Oefening 3
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    z^4 = -16
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    z^4 = -16
\end{align*}

Schrijf $8+0i$ in poolvorm:

De modulus is:
\begin{align}
    r = |-16| &= \sqrt{ (-16)^2 + 0^2 } \\
    &= \sqrt{256} \\
    &= 16
\end{align}

Het argument is:
\begin{align}
    \theta = arg( -16+0i ) &= \tan^{-1} \left( \dfrac{0}{-16} \right) \\
     &= \pi + k \cdot 2\pi
\end{align}

Dus:
\begin{align}
    z^4 = 16 \left( \cos\left( \pi + k \cdot 2\pi \right) + i\sin\left( pi + k \cdot 2\pi \right) \right)
\end{align}

We zoeken de vierde-machtswortels, dat zijn:
\begin{align}
    z_k = \sqrt[4]{16} \cdot \left( \cos\left( \pi\frac{  \pi + k \cdot 2\pi}{4} \right) + i \sin\left( \frac{ \pi + k \cdot 2\pi}{4} \right) \right)
    \quad \text{voor } k = 0, 1, 2, 3
\end{align}

Omdat $\sqrt[4]{16} = 2$, wordt dit:
\begin{align}
    z_k = 2 \left( \cos\left( \frac{ \pi + k \cdot 2\pi}{4} \right) + i \sin\left( \frac{ \pi + k \cdot 2\pi}{4} \right) \right)
\end{align}

Schrijf de oplossingen uit:

Voor $k = 0$:
\begin{align}
    \theta = \frac{\pi}{4}  \Rightarrow z_0 &= 2\left( \cos\left(  \frac{\pi}{4}  \right) + i \sin\left(  \frac{\pi}{4}  \right) \right) \\
   &= 2\left( \frac{ \sqrt{2}}{2} + i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= \sqrt{2} + i \cdot \sqrt{2}
\end{align}

Voor $k = 1$:
\begin{align}
    \theta = \frac{3\pi}{4} \Rightarrow z_1 &= 2\left( \cos\left( \frac{3\pi}{4} \right) + i \sin\left( \frac{3\pi}{4} \right) \right) \\
   &= 2\left( -\frac{ \sqrt{2}}{2} + i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= -\sqrt{2} + i \cdot \sqrt{2}
\end{align}

Voor $k = 2$:
\begin{align}
    \theta = \frac{5\pi}{4} \Rightarrow z_2 &= 2\left( \cos\left( \frac{5\pi}{4} \right) + i \sin\left( \frac{5\pi}{4} \right) \right) \\
   &= 2\left( -\frac{ \sqrt{2}}{2} - i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= -\sqrt{2} - i \cdot \sqrt{2}
\end{align}

Voor $k = 3$:
\begin{align}
    \theta = \frac{7\pi}{4} \Rightarrow z_2 &= 2\left( \cos\left( \frac{7\pi}{4} \right) + i \sin\left( \frac{7\pi}{4} \right) \right) \\
   &= 2\left( \frac{ \sqrt{2}}{2} - i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= \sqrt{2} - i \cdot \sqrt{2}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 12 ( punten)

<hr style="border:1px solid #9EA700">