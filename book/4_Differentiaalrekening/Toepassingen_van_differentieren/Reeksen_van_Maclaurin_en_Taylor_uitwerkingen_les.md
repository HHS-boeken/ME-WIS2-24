## 5.3 Uitwerkingen les

<hr style="border:2px solid #9EA700">

### Opgave 5.3a

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx x - \dfrac{1}{6}x^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
f(x) = \sin(x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= \sin(x) \\
f'(x) &= \cos(x) \\
f''(x) &= -\sin(x) \\
f'''(x) &= -\cos(x)
\end{align*}

Evalueer de afgeleide bij $x=0$:
\begin{align*}
f(0) &= \sin(0) = 0 \\
f'(0) &= \cos(0) = 1 \\
f''(0) &= -\sin(0) = 0 \\
f'''(0) &= -\cos(0) = -1
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \
\end{align*}

\begin{align*}
f(x) &\approx 0 + 1 \cdot x + \dfrac{0}{2}x^2 + \dfrac{-1}{6}x^3 \\
f(x) &\approx x - \dfrac{1}{6}x^3
\end{align*}

:::
::::

### Opgave 5.3b

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx 1 - x + \dfrac{1}{2}x^2 - \dfrac{1}{6}x^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
f(x) = e^{-x}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= e^{-x} \\
f'(x) &= -e^{-x} \\
f''(x) &= e^{-x} \\
f'''(x) &= -e^{-x}
\end{align*}

Evalueer de afgeleide bij $x=0$:
\begin{align*}
f(0) &= e^0 = 1 \\
f'(0) &= -e^0 = -1 \\
f''(0) &= e^0 = 1 \\
f'''(0) &= -e^0 = -1
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \
\end{align*}

\begin{align*}
f(x) &\approx 1 - x + \dfrac{1}{2}x^2 - \dfrac{1}{6}x^3 \
\end{align*}

:::
::::

### Opgave 5.3c

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx x - x^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
f(x) = \dfrac{x}{1+x^2}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= x(1+x^2)^{-1} \\
f'(x) &= (1+x^2)^{-1} - 2x^2(1+x^2)^{-2} = \dfrac{1-x^2}{(1+x^2)^2} \\
f''(x) &= -\dfrac{2x}{(1+x^2)^2} - \dfrac{2x(1-x^2)}{(1+x^2)^3} = \dfrac{2x^3-6x}{(1+x^2)^3} \\
f'''(x) &= \dfrac{6x^4-12x^2-6}{(1+x^2)^4}
\end{align*}

Evalueer de afgeleide bij $x=0$:
\begin{align*}
f(0) &= 0 \\
f'(0) &= 1 \\
f''(0) &= 0 \\
f'''(0) &= -6
\end{align*}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align*}
f(x) &\approx f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \
\end{align*}

\begin{align*}
f(x) &\approx 0 + 1\cdot x + \dfrac{0}{2}x^2 + \dfrac{-6}{6}x^3 \\
f(x) &\approx x - x^3
\end{align*}

:::
::::

### Opgave 5.3d

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \ln(3) + \dfrac{1}{3}(x-2) - \dfrac{1}{18}(x-2)^2 + \dfrac{1}{81}(x-2)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=2$ van
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

Evalueer de afgeleide bij $x=2$:
\begin{align*}
f(2) &= \ln(2+1) = \ln(3) \\
f'(2) &= \dfrac{1}{3} \\
f''(2) &= -\dfrac{1}{9} \\
f'''(2) &= \dfrac{2}{27}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=2$ geeft:

\begin{align*}
f(x) &\approx f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \ln(3) + \dfrac{1}{3}(x-2) + \dfrac{-\frac{1}{9}}{2}(x-2)^2 + \dfrac{\frac{2}{27}}{6}(x-2)^3 \\
f(x) &\approx \ln(3) + \dfrac{1}{3}(x-2) - \dfrac{1}{18}(x-2)^2 + \dfrac{1}{81}(x-2)^3
\end{align*}

:::
::::

### Opgave 5.3e

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx -\pi - (x-\pi) + \dfrac{\pi}{2}(x-\pi)^2 + \dfrac{1}{2}(x-\pi)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=\pi$ van
\begin{align*}
f(x) = x \cdot \cos(x)
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= x\cos(x) \\
f'(x) &= \cos(x) - x\sin(x) \\
f''(x) &= -2\sin(x) - x\cos(x) \\
f'''(x) &= -3\cos(x) + x\sin(x)
\end{align*}

Evalueer de afgeleide bij $x=\pi$:
\begin{align*}
f(\pi) &= \pi\cos(\pi) = -\pi \\
f'(\pi) &= \cos(\pi) - \pi\sin(\pi) = -1 \\
f''(\pi) &= -2\sin(\pi) - \pi\cos(\pi) = \pi \\
f'''(\pi) &= -3\cos(\pi) + \pi\sin(\pi) = 3
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=\pi$ geeft:

\begin{align*}
f(x) &\approx f(\pi) + f'(\pi)(x-\pi) + \dfrac{f''(\pi)}{2!}(x-\pi)^2 + \dfrac{f'''(\pi)}{3!}(x-\pi)^3 \
\end{align*}

\begin{align*}
f(x) &\approx -\pi - (x-\pi) + \dfrac{\pi}{2}(x-\pi)^2 + \dfrac{3}{6}(x-\pi)^3 \\\
f(x) &\approx -\pi - (x-\pi) + \dfrac{\pi}{2}(x-\pi)^2 + \dfrac{1}{2}(x-\pi)^3
\end{align*}

:::
::::

### Opgave 5.3f

::::{admonition} Antwoord
:class: important, dropdown

$$
f(x) \approx \dfrac{1}{2} - \dfrac{1}{4}(x-1) + \dfrac{1}{8}(x-1)^2 - \dfrac{1}{16}(x-1)^3
$$

:::{dropdown} Uitwerking

Bepaal de 3e orde Taylor-reeks rond $x=1$ van
\begin{align*}
f(x) = \dfrac{1}{x+1}
\end{align*}

Bereken de afgeleide van $f(x)$ tot de 3e orde:
\begin{align*}
f(x) &= (x+1)^{-1} \\
f'(x) &= -(x+1)^{-2} = -\dfrac{1}{(x+1)^2} \\
f''(x) &= 2(x+1)^{-3} = \dfrac{2}{(x+1)^3} \\
f'''(x) &= -6(x+1)^{-4} = -\dfrac{6}{(x+1)^4}
\end{align*}

Evalueer de afgeleide bij $x=1$:
\begin{align*}
f(1) &= \dfrac{1}{1+1} = \dfrac{1}{2} \\
f'(1) &= -\dfrac{1}{(1+1)^2} = -\dfrac{1}{4} \\
f''(1) &= \dfrac{2}{(1+1)^3} = \dfrac{2}{8} = \dfrac{1}{4} \\
f'''(1) &= -\dfrac{6}{(1+1)^4} = -\dfrac{6}{16} = -\dfrac{3}{8}
\end{align*}

Invullen van de waardes in de Taylor-reeks rond $x=1$ geeft:

\begin{align*}
f(x) &\approx f(1) + f'(1)(x-1) + \dfrac{f''(1)}{2!}(x-1)^2 + \dfrac{f'''(1)}{3!}(x-1)^3 \
\end{align*}

\begin{align*}
f(x) &\approx \dfrac{1}{2} - \dfrac{1}{4}(x-1) + \dfrac{\frac{1}{4}}{2}(x-1)^2 + \dfrac{-\frac{3}{8}}{6}(x-1)^3 \\
f(x) &\approx \dfrac{1}{2} - \dfrac{1}{4}(x-1) + \dfrac{1}{8}(x-1)^2 - \dfrac{1}{16}(x-1)^3
\end{align*}

:::
::::
