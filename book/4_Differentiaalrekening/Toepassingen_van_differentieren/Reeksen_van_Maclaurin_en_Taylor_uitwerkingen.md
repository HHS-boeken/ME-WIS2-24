## 5.3 Uitwerkingen

### Opgave 5.3.1a

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \ln(x+1)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= \ln(x+1) \\
  f'(x) &= \dfrac{1}{x+1} \\
  f''(x) &= -\dfrac{1}{(x+1)^2} \\
  f'''(x) &= \dfrac{2}{(x+1)^3}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= \ln(1) = 0 \\
  f'(0) &= 1 \\
  f''(0) &= -1 \\
  f'''(0) &= 2
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{-1}{2!}x^2 + \dfrac{2}{3!}x^3 \\
  f(x) &\approx x + \dfrac{-1}{2}x^2 + \dfrac{2}{6}x^3 \\
  f(x) &\approx x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1b

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx 1 - x^2 + x^4 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \dfrac{1}{1+x^2}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= \dfrac{1}{1+x^2} \\
  f'(x) &= \dfrac{-2x}{(1+x^2)^2} \\
  f''(x) &= \dfrac{-2(1+x^2)^2 + 8x^2(1+x^2)}{(1+x^2)^4} \\
        &= \dfrac{-2(1+x^2) + 8x^2}{(1+x^2)^3} \\
        &= \dfrac{-2 + 6x^2}{(1+x^2)^3} \\
  f'''(x) &= \text{Zie noot hieronder (alleen evaluatie bij } x=0 \text{ nodig)}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= \dfrac{1}{1+0} = 1 \\
  f'(0) &= 0 \\
  f''(0) &= \dfrac{-2}{1^3} = -2 \\
  f'''(0) &= 0
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 1 + 0 \cdot x + \dfrac{-2}{2}x^2 + 0 \cdot x^3 \\
  f(x) &\approx 1 - x^2 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1c

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{1}{16}x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \sqrt{1+x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= (1+x)^{1/2} \\
  f'(x) &= \dfrac{1}{2}(1+x)^{-1/2} \\
  f''(x) &= \dfrac{-1}{4}(1+x)^{-3/2} \\
  f'''(x) &= \dfrac{3}{8}(1+x)^{-5/2}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 1 \\
  f'(0) &= \dfrac{1}{2} \\
  f''(0) &= -\dfrac{1}{4} \\
  f'''(0) &= \dfrac{3}{8}
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 1 + \dfrac{1}{2}x + \dfrac{-\dfrac{1}{4}}{2}x^2 + \dfrac{\dfrac{3}{8}}{6}x^3 \\
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{3}{48}x^3 \\
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{1}{16}x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1d

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx x - x^2 + x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x \cdot \dfrac{1}{1+x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= \dfrac{x}{1+x} \\
  f'(x) &= \dfrac{(1+x)(1) - x(1)}{(1+x)^2} = \dfrac{1 + x - x}{(1+x)^2} = \dfrac{1}{(1+x)^2} \\
  f''(x) &= \dfrac{-2(1+x)}{(1+x)^4} = \dfrac{-2}{(1+x)^3} \\
  f'''(x) &= \dfrac{6}{(1+x)^4}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 0 \\
  f'(0) &= 1 \\
  f''(0) &= -2 \\
  f'''(0) &= 6
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{-2}{2}x^2 + \dfrac{6}{6}x^3 \\
  f(x) &\approx x - x^2 + x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1e

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx x + x^2 + \dfrac{1}{2}x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x \cdot e^x
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= x \cdot e^x \\
  f'(x) &= e^x + x \cdot e^x \\
  f''(x) &= e^x + (e^x + x \cdot e^x) = 2e^x + x \cdot e^x \\
  f'''(x) &= 2e^x + (e^x + x \cdot e^x) = 3e^x + x \cdot e^x
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 0 \cdot e^0 = 0 \\
  f'(0) &= e^0 + 0 = 1 \\
  f''(0) &= 2e^0 + 0 = 2 \\
  f'''(0) &= 3e^0 + 0 = 3
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{2}{2}x^2 + \dfrac{3}{6}x^3 \\
  f(x) &\approx x + x^2 + \dfrac{1}{2}x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1f

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx x^3 - \dfrac{1}{2}x^4 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 2e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x^2 \cdot \ln(1+x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 2e orde:
\begin{align}
  f(x) &= x^2 \cdot \ln(1+x) \\
  f'(x) &= 2x \cdot \ln(1+x) + \dfrac{x^2}{1+x} \quad \text{(productregel)} \\
  f''(x) &= 2 \ln(1+x) + \dfrac{2x}{1+x} + \dfrac{2x(1+x) - x^2}{(1+x)^2}
\end{align}

Evalueer de afgeleide bij $x = 0$:
\begin{align}
  f(0) &= 0 \\
  f'(0) &= 0 \\
  f''(0) &= 0
\end{align}

Omdat de termen tot en met de tweede afgeleide bij \( x = 0 \) allemaal nul zijn, moeten we verder kijken naar hogere orde termen. We kunnen dit makkelijker doen door de Maclaurin-reeks van \( \ln(1+x) \) te gebruiken:

\begin{align}
  \ln(1+x) &= x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 - \dots \\
  x^2 \cdot \ln(1+x) &= x^3 - \dfrac{1}{2}x^4 + \dfrac{1}{3}x^5 - \dots
\end{align}

We nemen de termen tot en met \( x^4 \), want dat levert een Maclaurin-reeks **tot 2e orde in \( f(x) \)** (dwz tot de 2e afgeleide van \( f(x) \)):

\begin{align}
  f(x) &\approx x^3 - \dfrac{1}{2}x^4
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1g

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx 2x - 2x^2 + \dfrac{8}{3}x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \ln(1+2x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= \ln(1+2x) \\
  f'(x) &= \dfrac{2}{1+2x} \\
  f''(x) &= \dfrac{-4}{(1+2x)^2} \\
  f'''(x) &= \dfrac{16}{(1+2x)^3}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= \ln(1) = 0 \\
  f'(0) &= 2 \\
  f''(0) &= -4 \\
  f'''(0) &= 16
\end{align}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 0 + 2x + \dfrac{-4}{2}x^2 + \dfrac{16}{6}x^3 \\
  f(x) &\approx 2x - 2x^2 + \dfrac{8}{3}x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1h

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx 1 + x - x^2 + \dfrac{5}{4}x^3 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \sqrt{1+2x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= (1+2x)^{1/2} \\
  f'(x) &= \dfrac{1}{2}(1+2x)^{-1/2} \cdot 2 = (1+2x)^{-1/2} \\
  f''(x) &= -\dfrac{1}{2}(1+2x)^{-3/2} \cdot 2 = - (1+2x)^{-3/2} \\
  f'''(x) &= \dfrac{3}{2}(1+2x)^{-5/2} \cdot 2 = 3(1+2x)^{-5/2}
\end{align}

Evalueer de afgeleide bij $x = 0$:
\begin{align}
  f(0) &= 1 \\
  f'(0) &= 1 \\
  f''(0) &= -1 \\
  f'''(0) &= 3
\end{align}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 1 + x + \dfrac{-1}{2}x^2 + \dfrac{3}{6}x^3 \\
  f(x) &\approx 1 + x - \dfrac{1}{2}x^2 + \dfrac{1}{2}x^3 \\
  f(x) &\approx 1 + x - x^2 + \dfrac{5}{4}x^3 \\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1i

````{admonition} Antwoord
:class:  dropdown

\begin{align}
  f(x) &\approx x^2 + 2x^3 + \dfrac{3}{2}x^4 \\
\end{align}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x^2 \cdot e^x
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align}
  f(x) &= x^2 \cdot e^x \\
  f'(x) &= 2x \cdot e^x + x^2 \cdot e^x = (2x + x^2)e^x \\
  f''(x) &= (2 + 2x)e^x + (2x + x^2)e^x = (2 + 4x + x^2)e^x \\
  f'''(x) &= (4 + 2x)e^x + (2 + 4x + x^2)e^x = (6 + 6x + x^2)e^x
\end{align}

Evalueer de afgeleide bij $x = 0$:
\begin{align}
  f(0) &= 0 \\
  f'(0) &= 0 \\
  f''(0) &= 2 \\
  f'''(0) &= 6
\end{align}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx 0 + 0 \cdot x + \dfrac{2}{2}x^2 + \dfrac{6}{6}x^3 \\
  f(x) &\approx x^2 + x^3 \\
\end{align}
```
````


