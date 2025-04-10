# 5.3 Reeksen van Maclaurin en Taylor

## 5.3.1 Reeksen van Maclaurin

```{admonition} Voorbeeld 1: Maclaurin
:class: dropdown

Bepaal de 4e orde Maclaurin-reeks van
\begin{align*}
    f(x) = e^{3x}
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 4e orde:
\begin{align}
  f(x) &= e^{3x} \\
  f'(x) &= 3e^{3x} \\
  f''(x) &= 9e^{3x} \\
  f'''(x) &= 27e^{3x} \\
  f''''(x) &= 81e^{3x}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 1 \\
  f'(0) &=  3 \\
  f''(0) &= 9 \\
  f'''(0) &= 27 \\
  f''''(0) &= 81
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 \\
\end{align}

\begin{align}
  f(x) &\approx   1 + 3x + \dfrac{9}{2!}x^2 + \dfrac{27}{3!}x^3 +  \dfrac{81}{4!}x^4    \\
  f(x) &\approx   1 + 3x + \dfrac{9}{2}x^2 + \dfrac{27}{6}x^3 +  \dfrac{81}{24}x^4    \\
  f(x) &\approx   1 + 3x + \dfrac{9}{2}x^2 + \dfrac{9}{2}x^3 +  \dfrac{27}{8}x^4    \\
\end{align}

```

````{admonition} Oefening 1
:class: important, dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 2\ln(5x+3)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 2\ln(5x+3)
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 3e orde:
\begin{align}
  f(x) &= 2\ln(5x+3) \\
  f'(x) &= \dfrac{10}{5x+3} \\
  f''(x) &= -\dfrac{50}{(5x+3)^2} \\
  f'''(x) &= \dfrac{500}{(5x+3)^3}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 2\ln(3) \\
  f'(0) &=  \dfrac{10}{3} \\
  f''(0) &= -\dfrac{50}{9} \\
  f'''(0) &= \dfrac{500}{27}
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 \\
\end{align}

\begin{align}
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2!}x^2 + \dfrac{\dfrac{500}{27}}{3!}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2}x^2 + \dfrac{\dfrac{500}{27}}{6}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-50}{18}x^2 + \dfrac{500}{162}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{250}{81}x^3  \\
\end{align}
```
````

````{admonition} Oefening 2
:class: important, dropdown

Bepaal de 4e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 3e^x \cos(2x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de 4e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 3e^x \cos(2x)
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 4e orde:
\begin{align}
  f(x) &= 3e^x \cos(2x) \\
  f'(x) &= 3e^x \cos(2x) - 6e^x \sin(2x) \\
  f''(x) &= 3e^x \cos(2x) - 6e^x \sin(2x) - 6e^x \sin(2x) - 12e^x \cos(2x)  \\
  f''(x) &= -9e^x \cos(2x) - 12e^x \sin(2x) \\
  f'''(x) &= -9e^x \cos(2x) + 18e^x \sin(2x) - 12e^x \sin(2x) - 24e^x \cos(2x)  \\
  f'''(x) &= -33e^x \cos(2x) + 6e^x \sin(2x) \\
  f''''(x) &= -33e^x \cos(2x) + 66e^x \sin(2x) + 6e^x \sin(2x) +  12e^x \cos(2x) \\
  f''''(x) &= -21e^x \cos(2x) + 72e^x \sin(2x)
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 3e^0 \cos(2\cdot 0) \\
  f(0) &= 3\\
  f'(0) &= 3e^0 \cos(2 \cdot 0) - 6e^0 \sin(2 \cdot 0) \\
  f'(0) &=  3 \\
  f''(0) &= -9e^0 \cos(2 \cdot 0) - 12e^0 \sin(2 \cdot 0) \\
  f''(0) &= -9 \\
  f'''(0) &= -33e^0 \cos(2 \cdot 0) + 6e^0 \sin(2 \cdot 0) \\
  f'''(0) &= -33 \\
  f''''(0) &= -21e^0 \cos(2 \cdot 0) + 72e^0 \sin(2 \cdot 0) \\
  f''''(0) &= -21
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 
\end{align}

\begin{align}
  f(x) &\approx 3 + 3x + \dfrac{-9}{2!}x^2 + \dfrac{-33}{3!}x^3 + \dfrac{-21}{4!}x^4 \\
  f(x) &\approx 3 + 3x + \dfrac{-9}{2}x^2 + \dfrac{-33}{6}x^3 + \dfrac{-21}{24}x^4 \\
  f(x) &\approx 3 + 3x - \dfrac{9}{2}x^2 - \dfrac{11}{2}x^3 - \dfrac{7}{8}x^4 
\end{align}
```
````

## 5.3.2 Reeksen Taylor

```{admonition} Voorbeeld 2: Taylor
:class: dropdown

Bepaal de 3e orde Taylor-reeks rond $x=5$ van
\begin{align*}
    f(x) = \sin(3x-15)
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 3e orde:
\begin{align}
  f(x) &= \sin(3x-15) \\
  f'(x) &= 3\cos(3x-15) \\
  f''(x) &= -9\sin(3x-15) \\
  f'''(x) &= -27\cos(3x-15)
\end{align}

Evalueer de afgeleide bij $x= 5$:
\begin{align}
  f(5) &= 0 \\
  f'(5) &=  3 \\
  f''(5) &= 0 \\
  f'''(5) &= -27
\end{align}

Invullen van de waaardes in de Taylor-reeks rond $x=5$ geeft:

\begin{align}
  f(x) &\approx   f(5) + f'(5)(x-5) + \dfrac{f''(5)}{2!}(x-5)^2 + \dfrac{f'''(5)}{3!}(x-5)^3 + \dfrac{f''''(5)}{4!}(x-5)^4
\end{align}

\begin{align}
  f(x) &\approx   0 + 3(x-5) + \dfrac{0}{2!}(x-5)^2 + \dfrac{-27}{3!}(x-5)^3   \\
  f(x) &\approx   0 + 3(x-5) + 0 + \dfrac{-27}{6}(x-5)^3    \\
  f(x) &\approx   3(x-5) - \dfrac{9}{2}(x-5)^3
\end{align}

```

````{admonition} Oefening 3
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
  f(x) &\approx   f(2) + f'(2)(x-2) + \dfrac{f''(2)}{2!}(x-2)^2 + \dfrac{f'''(2)}{3!}(x-2)^3 + \dfrac{f''''(2)}{4!}(x-2)^4 \\
\end{align}

\begin{align}
  f(x) &\approx   e^9 + 4e^9(x-2) + \dfrac{18e^9}{2!}(x-2)^2 + \dfrac{88e^9}{3!}(x-2)^3   \\
  f(x) &\approx   e^9 + 4e^9(x-2) + \dfrac{18e^9}{2}(x-2)^2 + \dfrac{88e^9}{6}(x-2)^3   \\
  f(x) &\approx   e^9 + 4e^9(x-2) + 9e^9(x-2)^2 + \dfrac{44e^9}{3}(x-2)^3   \\
  f(x) &\approx   e^9(1 + 4(x-2) + 9(x-2)^2 + \dfrac{44}{3}(x-2)^3)   \\
\end{align}
```
````

````{admonition} Oefening 4
:class: important, dropdown

Bepaal de 4e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 3e^x \cos(2x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de 4e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 3e^x \cos(2x)
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 4e orde:
\begin{align}
  f(x) &= 3e^x \cos(2x) \\
  f'(x) &= 3e^x \cos(2x) - 6e^x \sin(2x) \\
  f''(x) &= 3e^x \cos(2x) - 6e^x \sin(2x) - 6e^x \sin(2x) - 12e^x \cos(2x)  \\
  f''(x) &= -9e^x \cos(2x) - 12e^x \sin(2x) \\
  f'''(x) &= -9e^x \cos(2x) + 18e^x \sin(2x) - 12e^x \sin(2x) - 24e^x \cos(2x)  \\
  f'''(x) &= -33e^x \cos(2x) + 6e^x \sin(2x) \\
  f''''(x) &= -33e^x \cos(2x) + 66e^x \sin(2x) + 6e^x \sin(2x) +  12e^x \cos(2x) \\
  f''''(x) &= -21e^x \cos(2x) + 72e^x \sin(2x)
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 3e^0 \cos(2\cdot 0) \\
  f(0) &= 3\\
  f'(0) &= 3e^0 \cos(2 \cdot 0) - 6e^0 \sin(2 \cdot 0) \\
  f'(0) &=  3 \\
  f''(0) &= -9e^0 \cos(2 \cdot 0) - 12e^0 \sin(2 \cdot 0) \\
  f''(0) &= -9 \\
  f'''(0) &= -33e^0 \cos(2 \cdot 0) + 6e^0 \sin(2 \cdot 0) \\
  f'''(0) &= -33 \\
  f''''(0) &= -21e^0 \cos(2 \cdot 0) + 72e^0 \sin(2 \cdot 0) \\
  f''''(0) &= -21
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 
\end{align}



\begin{align}
  f(x) &\approx 3 + 3x + \dfrac{-9}{2!}x^2 + \dfrac{-33}{3!}x^3 + \dfrac{-21}{4!}x^4 \\
  f(x) &\approx 3 + 3x + \dfrac{-9}{2}x^2 + \dfrac{-33}{6}x^3 + \dfrac{-21}{24}x^4 \\
  f(x) &\approx 3 + 3x - \dfrac{9}{2}x^2 - \dfrac{11}{2}x^3 - \dfrac{7}{8}x^4
\end{align}

</div>
