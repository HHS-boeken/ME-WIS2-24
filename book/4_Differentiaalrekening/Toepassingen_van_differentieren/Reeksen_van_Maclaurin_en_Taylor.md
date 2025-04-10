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
  f(x) &\approx =  f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 \\
\end{align}

\begin{align}
  f(x) &\approx =  2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2!}x^2 + \dfrac{\dfrac{500}{27}}{3!}x^3  \\
  f(x) &\approx =  2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2}x^2 + \dfrac{\dfrac{500}{27}}{6}x^3  \\
  f(x) &\approx =  2\ln(3) + \dfrac{10}{3}x + \dfrac{-50}{18}x^2 + \dfrac{500}{162}x^3  \\
  f(x) &\approx =  2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{500}{162}x^3  \\
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
  f''(0) &= -9
  f'''(0) &= -33e^0 \cos(2 \cdot 0) + 6e^0 \sin(2 \cdot 0) \\
  f'''(0) &= -33
  f''''(0) &= -21e^0 \cos(2 \cdot 0) + 72e^0 \sin(2 \cdot 0)
  f''''(0) &= -21
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx =  f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 + \dfrac{f''''(0)}{4!}x^4 \\
\end{align}

\begin{align}
  f(x) &\approx =  3 + 3x + \dfrac{-9}{2!}x^2 + \dfrac{-33}{3!}x^3 + \dfrac{-21}{4!}x^4 \\
  f(x) &\approx =  3 + 3x + \dfrac{-9}{2}x^2 + \dfrac{-33}{6}x^3 + \dfrac{-21}{24}x^4 \\
  f(x) &\approx =  3 + 3x - \dfrac{9}{2}x^2 - \dfrac{11}{2}x^3 - \dfrac{7}{8}x^4 \\
\end{align}
```
````


# 5.3.2 Reeksen Taylor

```{admonition} Voorbeeld 1: productregel
:class: dropdown

Bereken de afgeleide van de volgende functie:


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


```
````
