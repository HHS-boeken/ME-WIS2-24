## 5.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 5.3.1a

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \ln(x+1)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \ln(x+1) \\
  f'(x) &= \dfrac{1}{x+1} \\
  f''(x) &= -\dfrac{1}{(x+1)^2} \\
  f'''(x) &= \dfrac{2}{(x+1)^3}
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= \ln(1) = 0 \\
  f'(0) &= 1 \\
  f''(0) &= -1 \\
  f'''(0) &= 2
\end{align*}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{-1}{2!}x^2 + \dfrac{2}{3!}x^3 \\
  f(x) &\approx x + \dfrac{-1}{2}x^2 + \dfrac{2}{6}x^3 \\
  f(x) &\approx x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1b

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx 1 - x^2 + x^4 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \dfrac{1}{1+x^2}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \dfrac{1}{1+x^2} \\
  f'(x) &= \dfrac{-2x}{(1+x^2)^2} \\
  f''(x) &= \dfrac{-2(1+x^2)^2 + 8x^2(1+x^2)}{(1+x^2)^4} \\
        &= \dfrac{-2(1+x^2) + 8x^2}{(1+x^2)^3} \\
        &= \dfrac{-2 + 6x^2}{(1+x^2)^3} \\
  f'''(x) &= \text{Zie noot hieronder (alleen evaluatie bij } x=0 \text{ nodig)}
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= \dfrac{1}{1+0} = 1 \\
  f'(0) &= 0 \\
  f''(0) &= \dfrac{-2}{1^3} = -2 \\
  f'''(0) &= 0
\end{align*}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 1 + 0 \cdot x + \dfrac{-2}{2}x^2 + 0 \cdot x^3 \\
  f(x) &\approx 1 - x^2 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1c

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{1}{16}x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \sqrt{1+x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= (1+x)^{1/2} \\
  f'(x) &= \dfrac{1}{2}(1+x)^{-1/2} \\
  f''(x) &= \dfrac{-1}{4}(1+x)^{-3/2} \\
  f'''(x) &= \dfrac{3}{8}(1+x)^{-5/2}
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= 1 \\
  f'(0) &= \dfrac{1}{2} \\
  f''(0) &= -\dfrac{1}{4} \\
  f'''(0) &= \dfrac{3}{8}
\end{align*}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 1 + \dfrac{1}{2}x + \dfrac{-\dfrac{1}{4}}{2}x^2 + \dfrac{\dfrac{3}{8}}{6}x^3 \\
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{3}{48}x^3 \\
  f(x) &\approx 1 + \dfrac{1}{2}x - \dfrac{1}{8}x^2 + \dfrac{1}{16}x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1d

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx x - x^2 + x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x \cdot \dfrac{1}{1+x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \dfrac{x}{1+x} \\
  f'(x) &= \dfrac{(1+x)(1) - x(1)}{(1+x)^2} = \dfrac{1 + x - x}{(1+x)^2} = \dfrac{1}{(1+x)^2} \\
  f''(x) &= \dfrac{-2(1+x)}{(1+x)^4} = \dfrac{-2}{(1+x)^3} \\
  f'''(x) &= \dfrac{6}{(1+x)^4}
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= 0 \\
  f'(0) &= 1 \\
  f''(0) &= -2 \\
  f'''(0) &= 6
\end{align*}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{-2}{2}x^2 + \dfrac{6}{6}x^3 \\
  f(x) &\approx x - x^2 + x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1e

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx x + x^2 + \dfrac{1}{2}x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x \cdot e^x
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= x \cdot e^x \\
  f'(x) &= e^x + x \cdot e^x \\
  f''(x) &= e^x + (e^x + x \cdot e^x) = 2e^x + x \cdot e^x \\
  f'''(x) &= 2e^x + (e^x + x \cdot e^x) = 3e^x + x \cdot e^x
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= 0 \cdot e^0 = 0 \\
  f'(0) &= e^0 + 0 = 1 \\
  f''(0) &= 2e^0 + 0 = 2 \\
  f'''(0) &= 3e^0 + 0 = 3
\end{align*}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 1 \cdot x + \dfrac{2}{2}x^2 + \dfrac{3}{6}x^3 \\
  f(x) &\approx x + x^2 + \dfrac{1}{2}x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1f

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx x^3 - \dfrac{1}{2}x^4 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 2e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x^2 \cdot \ln(1+x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 2e orde:
\begin{align*}
  f(x) &= x^2 \cdot \ln(1+x) \\
  f'(x) &= 2x \cdot \ln(1+x) + \dfrac{x^2}{1+x} \quad \text{(productregel)} \\
  f''(x) &= 2 \ln(1+x) + \dfrac{2x}{1+x} + \dfrac{2x(1+x) - x^2}{(1+x)^2}
\end{align*}

Evalueer de afgeleide bij $x = 0$:
\begin{align*}
  f(0) &= 0 \\
  f'(0) &= 0 \\
  f''(0) &= 0
\end{align*}

Omdat de termen tot en met de tweede afgeleide bij \( x = 0 \) allemaal nul zijn, moeten we verder kijken naar hogere orde termen. We kunnen dit makkelijker doen door de Maclaurin-reeks van \( \ln(1+x) \) te gebruiken:

\begin{align*}
  \ln(1+x) &= x - \dfrac{1}{2}x^2 + \dfrac{1}{3}x^3 - \dots \\
  x^2 \cdot \ln(1+x) &= x^3 - \dfrac{1}{2}x^4 + \dfrac{1}{3}x^5 - \dots
\end{align*}

We nemen de termen tot en met \( x^4 \), want dat levert een Maclaurin-reeks **tot 2e orde in \( f(x) \)** (dwz tot de 2e afgeleide van \( f(x) \)):

\begin{align*}
  f(x) &\approx x^3 - \dfrac{1}{2}x^4
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1g

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx 2x - 2x^2 + \dfrac{8}{3}x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \ln(1+2x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \ln(1+2x) \\
  f'(x) &= \dfrac{2}{1+2x} \\
  f''(x) &= \dfrac{-4}{(1+2x)^2} \\
  f'''(x) &= \dfrac{16}{(1+2x)^3}
\end{align*}

Evalueer de afgeleide bij $x= 0$:
\begin{align*}
  f(0) &= \ln(1) = 0 \\
  f'(0) &= 2 \\
  f''(0) &= -4 \\
  f'''(0) &= 16
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 2x + \dfrac{-4}{2}x^2 + \dfrac{16}{6}x^3 \\
  f(x) &\approx 2x - 2x^2 + \dfrac{8}{3}x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1h

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx 1 + x - x^2 + \dfrac{5}{4}x^3 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \sqrt{1+2x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= (1+2x)^{1/2} \\
  f'(x) &= \dfrac{1}{2}(1+2x)^{-1/2} \cdot 2 = (1+2x)^{-1/2} \\
  f''(x) &= -\dfrac{1}{2}(1+2x)^{-3/2} \cdot 2 = - (1+2x)^{-3/2} \\
  f'''(x) &= \dfrac{3}{2}(1+2x)^{-5/2} \cdot 2 = 3(1+2x)^{-5/2}
\end{align*}

Evalueer de afgeleide bij $x = 0$:
\begin{align*}
  f(0) &= 1 \\
  f'(0) &= 1 \\
  f''(0) &= -1 \\
  f'''(0) &= 3
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 1 + x + \dfrac{-1}{2}x^2 + \dfrac{3}{6}x^3 \\
  f(x) &\approx 1 + x - \dfrac{1}{2}x^2 + \dfrac{1}{2}x^3 \\
  f(x) &\approx 1 + x - x^2 + \dfrac{5}{4}x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.1i

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  f(x) &\approx x^2 + 2x^3 + \dfrac{3}{2}x^4 \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = x^2 \cdot e^x
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= x^2 \cdot e^x \\
  f'(x) &= 2x \cdot e^x + x^2 \cdot e^x = (2x + x^2)e^x \\
  f''(x) &= (2 + 2x)e^x + (2x + x^2)e^x = (2 + 4x + x^2)e^x \\
  f'''(x) &= (4 + 2x)e^x + (2 + 4x + x^2)e^x = (6 + 6x + x^2)e^x
\end{align*}

Evalueer de afgeleide bij $x = 0$:
\begin{align*}
  f(0) &= 0 \\
  f'(0) &= 0 \\
  f''(0) &= 2 \\
  f'''(0) &= 6
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
  f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 0 \cdot x + \dfrac{2}{2}x^2 + \dfrac{6}{6}x^3 \\
  f(x) &\approx x^2 + x^3 \\
\end{align*}
:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
  f(x) \approx (x-1) - \dfrac{1}{2}(x-1)^2 + \dfrac{1}{3}(x-1)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=1$ van
\begin{align*}
    f(x) = \ln(x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \ln(x) \\
  f'(x) &= \dfrac{1}{x} \\
  f''(x) &= -\dfrac{1}{x^2} \\
  f'''(x) &= \dfrac{2}{x^3}
\end{align*}

Evalueer de afgeleide bij $x=1$:
\begin{align*}
  f(1) &= \ln(1) = 0 \\
  f'(1) &= 1 \\
  f''(1) &= -1 \\
  f'''(1) &= 2
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=1$ geeft:

\begin{align*}
  f(x) &\approx f(1) + f'(1)(x-1) + \dfrac{f''(1)}{2!}(x-1)^2 + \dfrac{f'''(1)}{3!}(x-1)^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx 0 + 1(x-1) + \dfrac{-1}{2}(x-1)^2 + \dfrac{2}{6}(x-1)^3 \\
  f(x) &\approx (x-1) - \dfrac{1}{2}(x-1)^2 + \dfrac{1}{3}(x-1)^3 \\
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2.b

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx 1 + \dfrac{1}{2}(x-1) - \dfrac{1}{8}(x-1)^2 + \dfrac{1}{16}(x-1)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=1$ van
\begin{align*}
f(x) = \sqrt{x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= \sqrt{x} = x^{\frac{1}{2}} \\
f'(x) &= \dfrac{1}{2}x^{-\frac{1}{2}} = \dfrac{1}{2\sqrt{x}} \\
f''(x) &= -\dfrac{1}{4}x^{-\frac{3}{2}} = -\dfrac{1}{4x^{\frac{3}{2}}} \\
f'''(x) &= \dfrac{3}{8}x^{-\frac{5}{2}} = \dfrac{3}{8x^{\frac{5}{2}}}
\end{align*}

Evalueer de afgeleide bij $x=1$:
\begin{align*}
f(1) &= \sqrt{1} = 1 \\
f'(1) &= \dfrac{1}{2} \\
f''(1) &= -\dfrac{1}{4} \\
f'''(1) &= \dfrac{3}{8}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=1$ geeft:

\begin{align*}
f(x) &\approx f(1) + f'(1)(x-1) + \dfrac{f''(1)}{2!}(x-1)^2 + \dfrac{f'''(1)}{3!}(x-1)^3
\end{align*}

\begin{align*}
f(x) &\approx 1 + \dfrac{1}{2}(x-1) + \dfrac{-\frac{1}{4}}{2}(x-1)^2 + \dfrac{\frac{3}{8}}{6}(x-1)^3 \\
f(x) &\approx 1 + \dfrac{1}{2}(x-1) - \dfrac{1}{8}(x-1)^2 + \dfrac{1}{16}(x-1)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2c

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx e^2 + 2e^2(x-1) + 2e^2(x-1)^2 + \dfrac{4}{3}e^2(x-1)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=1$ van
\begin{align*}
f(x) = e^{2x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= e^{2x} \\
f'(x) &= 2e^{2x} \\
f''(x) &= 4e^{2x} \\
f'''(x) &= 8e^{2x}
\end{align*}

Evalueer de afgeleide bij $x=1$:
\begin{align*}
f(1) &= e^2 \\
f'(1) &= 2e^2 \\
f''(1) &= 4e^2 \\
f'''(1) &= 8e^2
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=1$ geeft:

\begin{align*}
f(x) &\approx f(1) + f'(1)(x-1) + \dfrac{f''(1)}{2!}(x-1)^2 + \dfrac{f'''(1)}{3!}(x-1)^3 
\end{align*}

\begin{align*}
f(x) &\approx e^2 + 2e^2(x-1) + \dfrac{4e^2}{2}(x-1)^2 + \dfrac{8e^2}{6}(x-1)^3 \\
f(x) &\approx e^2 + 2e^2(x-1) + 2e^2(x-1)^2 + \dfrac{4}{3}e^2(x-1)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \dfrac{1}{2} - \dfrac{1}{2}(x-1) + \dfrac{1}{4}(x-1)^2
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=1$ van
\begin{align*}
f(x) = \dfrac{1}{x^2+1}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= (x^2+1)^{-1} \\
f'(x) &= -1(x^2+1)^{-2} \cdot 2x = -\dfrac{2x}{(x^2+1)^2} \\
f''(x) &= -\dfrac{2}{(x^2+1)^2} + \dfrac{8x^2}{(x^2+1)^3} \\
f'''(x) &= \dfrac{24x}{(x^2+1)^3} - \dfrac{48x^3}{(x^2+1)^4}
\end{align*}

Evalueer de afgeleide bij $x=1$:
\begin{align*}
f(1) &= \dfrac{1}{1^2+1} = \dfrac{1}{2} \\
f'(1) &= -\dfrac{2}{(1+1)^2} = -\dfrac{1}{2} \\
f''(1) &= -\dfrac{2}{(1+1)^2} + \dfrac{8}{(1+1)^3} = -\dfrac{1}{2} + 1 = \dfrac{1}{2} \\
f'''(1) &= \dfrac{24}{(1+1)^3} - \dfrac{48}{(1+1)^4} = 3 - 3 = 0
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=1$ geeft:

\begin{align*}
f(x) &\approx f(1) + f'(1)(x-1) + \dfrac{f''(1)}{2!}(x-1)^2 + \dfrac{f'''(1)}{3!}(x-1)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \dfrac{1}{2} - \dfrac{1}{2}(x-1) + \dfrac{\frac{1}{2}}{2}(x-1)^2 + \dfrac{0}{6}(x-1)^3 \\
f(x) &\approx \dfrac{1}{2} - \dfrac{1}{2}(x-1) + \dfrac{1}{4}(x-1)^2
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
  f(x) \approx \dfrac{5}{2} + \dfrac{3}{4}(x-2) + \dfrac{1}{8}(x-2)^2 - \dfrac{1}{16}(x-2)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
\begin{align*}
    f(x) = \dfrac{x^2+1}{x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
  f(x) &= \dfrac{x^2+1}{x} = x + \dfrac{1}{x} \\
  f'(x) &= 1 - \dfrac{1}{x^2} \\
  f''(x) &= \dfrac{2}{x^3} \\
  f'''(x) &= -\dfrac{6}{x^4}
\end{align*}

Evalueer de afgeleide bij $x=2$:
\begin{align*}
  f(2) &= 2 + \dfrac{1}{2} = \dfrac{5}{2} \\
  f'(2) &= 1 - \dfrac{1}{4} = \dfrac{3}{4} \\
  f''(2) &= \dfrac{2}{8} = \dfrac{1}{4} \\
  f'''(2) &= -\dfrac{6}{16} = -\dfrac{3}{8}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=2$ geeft:

\begin{align*}
  f(x) &\approx f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 \\
\end{align*}

\begin{align*}
  f(x) &\approx \dfrac{5}{2} + \dfrac{3}{4}(x-2) + \dfrac{\frac{1}{4}}{2}(x-2)^2 + \dfrac{-\frac{3}{8}}{6}(x-2)^3 \\
  f(x) &\approx \dfrac{5}{2} + \dfrac{3}{4}(x-2) + \dfrac{1}{8}(x-2)^2 - \dfrac{1}{16}(x-2)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \dfrac{\pi}{2} + \left(x-\dfrac{\pi}{2}\right) - \dfrac{\pi}{4}\left(x-\dfrac{\pi}{2}\right)^2 - \dfrac{1}{2}\left(x-\dfrac{\pi}{2}\right)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=\dfrac{\pi}{2}$ van
\begin{align*}
f(x) = x \cdot \sin(x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= x\sin(x) \\
f'(x) &= \sin(x) + x\cos(x) \\
f''(x) &= 2\cos(x) - x\sin(x) \\
f'''(x) &= -3\sin(x) - x\cos(x)
\end{align*}

Evalueer de afgeleide bij $x=\dfrac{\pi}{2}$:
\begin{align*}
f\left(\dfrac{\pi}{2}\right) &= \dfrac{\pi}{2}\sin\left(\dfrac{\pi}{2}\right) = \dfrac{\pi}{2} \\
f'\left(\dfrac{\pi}{2}\right) &= \sin\left(\dfrac{\pi}{2}\right) + \dfrac{\pi}{2}\cos\left(\dfrac{\pi}{2}\right) = 1 \\
f''\left(\dfrac{\pi}{2}\right) &= 2\cos\left(\dfrac{\pi}{2}\right) - \dfrac{\pi}{2}\sin\left(\dfrac{\pi}{2}\right) = -\dfrac{\pi}{2} \\
f'''\left(\dfrac{\pi}{2}\right) &= -3\sin\left(\dfrac{\pi}{2}\right) - \dfrac{\pi}{2}\cos\left(\dfrac{\pi}{2}\right) = -3
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=\dfrac{\pi}{2}$ geeft:

\begin{align*}
f(x) &\approx f\left(\dfrac{\pi}{2}\right) + f'\left(\dfrac{\pi}{2}\right)\left(x-\dfrac{\pi}{2}\right) + \dfrac{f''\left(\dfrac{\pi}{2}\right)}{2!}\left(x-\dfrac{\pi}{2}\right)^2 + \dfrac{f'''\left(\dfrac{\pi}{2}\right)}{3!}\left(x-\dfrac{\pi}{2}\right)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \dfrac{\pi}{2} + 1\left(x-\dfrac{\pi}{2}\right) + \dfrac{-\frac{\pi}{2}}{2}\left(x-\dfrac{\pi}{2}\right)^2 + \dfrac{-3}{6}\left(x-\dfrac{\pi}{2}\right)^3 \\
f(x) &\approx \dfrac{\pi}{2} + \left(x-\dfrac{\pi}{2}\right) - \dfrac{\pi}{4}\left(x-\dfrac{\pi}{2}\right)^2 - \dfrac{1}{2}\left(x-\dfrac{\pi}{2}\right)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \dfrac{3}{4} + \dfrac{1}{16}(x-3) - \dfrac{1}{64}(x-3)^2 + \dfrac{1}{256}(x-3)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=3$ van
\begin{align*}
f(x) = \dfrac{x}{x+1}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= \dfrac{x}{x+1} = 1 - \dfrac{1}{x+1} \\
f'(x) &= \dfrac{1}{(x+1)^2} \\
f''(x) &= -\dfrac{2}{(x+1)^3} \\
f'''(x) &= \dfrac{6}{(x+1)^4}
\end{align*}

Evalueer de afgeleide bij $x=3$:
\begin{align*}
f(3) &= \dfrac{3}{3+1} = \dfrac{3}{4} \\
f'(3) &= \dfrac{1}{(3+1)^2} = \dfrac{1}{16} \\
f''(3) &= -\dfrac{2}{(3+1)^3} = -\dfrac{2}{64} = -\dfrac{1}{32} \\
f'''(3) &= \dfrac{6}{(3+1)^4} = \dfrac{6}{256} = \dfrac{3}{128}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=3$ geeft:

\begin{align*}
f(x) &\approx f(3) + f'(3)(x-3) + \dfrac{f''(3)}{2!}(x-3)^2 + \dfrac{f'''(3)}{3!}(x-3)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \dfrac{3}{4} + \dfrac{1}{16}(x-3) + \dfrac{-\frac{1}{32}}{2}(x-3)^2 + \dfrac{\frac{3}{128}}{6}(x-3)^3 \\
f(x) &\approx \dfrac{3}{4} + \dfrac{1}{16}(x-3) - \dfrac{1}{64}(x-3)^2 + \dfrac{1}{256}(x-3)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx 2e^2 + 3e^2(x-2) + 2e^2(x-2)^2 + \dfrac{5}{6}e^2(x-2)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
\begin{align*}
f(x) = x \cdot e^x
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= xe^x \\
f'(x) &= e^x + xe^x = (x+1)e^x \\
f''(x) &= e^x + (x+1)e^x = (x+2)e^x \\
f'''(x) &= e^x + (x+2)e^x = (x+3)e^x
\end{align*}

Evalueer de afgeleide bij $x=2$:
\begin{align*}
f(2) &= 2e^2 \\
f'(2) &= 3e^2 \\
f''(2) &= 4e^2 \\
f'''(2) &= 5e^2
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=2$ geeft:

\begin{align*}
f(x) &\approx f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 \
\end{align*}

\begin{align*}
f(x) &\approx 2e^2 + 3e^2(x-2) + \dfrac{4e^2}{2}(x-2)^2 + \dfrac{5e^2}{6}(x-2)^3 \\
f(x) &\approx 2e^2 + 3e^2(x-2) + 2e^2(x-2)^2 + \dfrac{5}{6}e^2(x-2)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2i

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx 4\ln(2) + \left(4\ln(2)+2\right)(x-2) + \left(\ln(2)+\dfrac{3}{2}\right)(x-2)^2 + \dfrac{1}{6}(x-2)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
\begin{align*}
f(x) = x^2 \cdot \ln(x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= x^2\ln(x) \\
f'(x) &= 2x\ln(x) + x^2 \cdot \dfrac{1}{x} = 2x\ln(x) + x \\
f''(x) &= 2\ln(x) + 2x \cdot \dfrac{1}{x} + 1 = 2\ln(x) + 3 \\
f'''(x) &= \dfrac{2}{x}
\end{align*}

Evalueer de afgeleide bij $x=2$:
\begin{align*}
f(2) &= 2^2\ln(2) = 4\ln(2) \\
f'(2) &= 2\cdot 2\ln(2) + 2 = 4\ln(2) + 2 \\
f''(2) &= 2\ln(2) + 3 \\
f'''(2) &= \dfrac{2}{2} = 1
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=2$ geeft:

\begin{align*}
f(x) &\approx f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 \
\end{align*}

\begin{align*}
f(x) &\approx 4\ln(2) + \left(4\ln(2)+2\right)(x-2) + \dfrac{2\ln(2)+3}{2}(x-2)^2 + \dfrac{1}{6}(x-2)^3 \\
f(x) &\approx 4\ln(2) + \left(4\ln(2)+2\right)(x-2) + \left(\ln(2)+\dfrac{3}{2}\right)(x-2)^2 + \dfrac{1}{6}(x-2)^3
\end{align*}

:::
::::

<hr style="border:1px solid #9EA700">

### Opgave 5.3.2j

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \dfrac{1}{5} - \dfrac{1}{25}(x-3) + \dfrac{1}{125}(x-3)^2 - \dfrac{1}{625}(x-3)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=3$ van
\begin{align*}
f(x) = \dfrac{1}{x+2}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= (x+2)^{-1} \\
f'(x) &= -(x+2)^{-2} = -\dfrac{1}{(x+2)^2} \\
f''(x) &= 2(x+2)^{-3} = \dfrac{2}{(x+2)^3} \\
f'''(x) &= -6(x+2)^{-4} = -\dfrac{6}{(x+2)^4}
\end{align*}

Evalueer de afgeleide bij $x=3$:
\begin{align*}
f(3) &= \dfrac{1}{3+2} = \dfrac{1}{5} \\
f'(3) &= -\dfrac{1}{(3+2)^2} = -\dfrac{1}{25} \\
f''(3) &= \dfrac{2}{(3+2)^3} = \dfrac{2}{125} \\
f'''(3) &= -\dfrac{6}{(3+2)^4} = -\dfrac{6}{625}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=3$ geeft:

\begin{align*}
f(x) &\approx f(3) + f'(3)(x-3) + \dfrac{f''(3)}{2!}(x-3)^2 + \dfrac{f'''(3)}{3!}(x-3)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \dfrac{1}{5} - \dfrac{1}{25}(x-3) + \dfrac{\frac{2}{125}}{2}(x-3)^2 + \dfrac{-\frac{6}{625}}{6}(x-3)^3 \\
f(x) &\approx \dfrac{1}{5} - \dfrac{1}{25}(x-3) + \dfrac{1}{125}(x-3)^2 - \dfrac{1}{625}(x-3)^3
\end{align*}

:::
::::
