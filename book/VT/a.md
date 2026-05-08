## Opgave 8 (8 punten)

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    F(x) &= x^2 \ln(x) - \dfrac{1}{2}x^2 + C
\end{align*}

:::{dropdown} Uitwerking

Primitiveer:
\begin{align*}
    f(x) = 2x\ln(x)
\end{align*}

Dus, 
\begin{align}
    F(x) &=  \int 2x\ln(x) \, dx
\end{align}

Gebruik partieel integreren om deze onbepaalde integraal te berekenen.

Kies de functie $u$ en $dv$:
\begin{align}
    u &= \ln(x) \\
    dv &= 2x \, dx
\end{align}

Bepaal $du$:
\begin{align}
    \dfrac{du}{dx} &= \dfrac{1}{x} \\
    du &= \dfrac{1}{x} \, dx  {\color{blue} \quad  \text{(1p)}}
\end{align}

Bepaal de functie $v$:
\begin{align}
    dv &= 2x \, dx  \\
    \dfrac{dv}{dx} &= 2x \\
    v &= x^2 {\color{blue} \quad  \text{(1p)}}
\end{align}

Toepassen van de regel voor partieel integreren geeft:
\begin{align}
   \int u \, dv &= uv - \int v \, du \\
    &= x^2 \ln(x) - \int x^2 \cdot \dfrac{1}{x} \, dx {\color{blue} \quad  \text{(1p)}}\\
     &= x^2 \ln(x) - \int x \, dx\\
\end{align}

Integreren geeft:
\begin{align}
    &= x^2 \ln(x) - \dfrac{1}{2}x^2 + C {\color{blue} \quad  \text{(1p)}}
\end{align}

Dus,
\begin{align}
    F(x) &= x^2 \ln(x) - \dfrac{1}{2}x^2 + C {\color{blue} \quad  \text{(1p)}}
\end{align}
:::
::::

## Opgave 3 (3 punten)

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    \lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \dfrac{1}{2}
\end{align*}

:::{dropdown} Uitwerking

Bereken de limiet:
\begin{align*}
    \lim_{x \to 0} \frac{e^x - 1 - x}{x^2}
\end{align*}

Invullen van $x=0$ geeft:
\begin{align}
    &\lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \dfrac{0}{0} = ? \quad \text{gebruik L'Hopital} \\
    &\lim_{x \to 0} \frac{e^x - 1}{2x} = \dfrac{0}{0} =  ? \quad \text{gebruik L'Hopital} \quad {\color{blue} \text{(1p)}}\\
    &\lim_{x \to 0} \frac{e^x}{2} = \dfrac{1}{2} \quad {\color{blue} \text{(1p)}}\\
\end{align}

Dus:
\begin{align}
    \lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \dfrac{1}{2} \quad {\color{blue} \text{(1p)}}
\end{align}

:::
::::

## Opgave 4 (4 punten)

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  \dfrac{df}{dx} &= \frac{ -2 \sin(x)\cos(x)(\ln(2x+5)) - \dfrac{2\cos^2(x)}{2x+5} }{ \ln^2(2x+5)} 
\end{align*}

:::{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \cos^2(x) }{ \ln(2x+5)}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &=  \cos^2(x) \\
  v &=  \ln(2x+5) \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= -2 \sin(x)\cos(x) {\color{blue} \quad  \text{(1p)}}\\
  \dfrac{dv}{dx} &= \dfrac{1}{2x+5} \cdot 2  {\color{blue} \quad  \text{(1p)}}\\
                &= \dfrac{2}{2x+5} \\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (\ln(2x+5)) \cdot -2 \sin(x)\cos(x)  - \cos^2(x) \cdot  \dfrac{2}{2x+5} }{ (\ln(2x+5))^2} {\color{blue} \quad  \text{(1p)}}\\
  &= \frac{ -2 \sin(x)\cos(x)(\ln(2x+5)) - \dfrac{2\cos^2(x)}{2x+5} }{ \ln^2(2x+5)} {\color{blue} \quad  \text{(1p)}}
\end{align}

:::
::::

## Opgave 6 (6 punten)

::::{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    f(x) &\approx   1 + 2x + 4x^2 + 8x^3  \\
\end{align*}

:::{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = \dfrac{1}{1-2x}
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 3e orde:
\begin{align}
  f(x) &= (1-2x)^{-1} \\
  f'(x) &= 2(1-2x)^{-2}  {\color{blue} \quad  \text{(1p)}}\\
  f''(x) &= 8(1-2x)^{-3}  {\color{blue} \quad  \text{(1p)}}\\
  f'''(x) &= 48(1-2x)^{-4}  {\color{blue} \quad  \text{(1p)}}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 1 \\
  f'(0) &=  2 \\
  f''(0) &= 8 \\
  f'''(0) &= 48  {\color{blue} \quad  \text{(2p) voor alle 4, 1 fout 1p, 2 of meer fout 0p}}\\
\end{align}

Invullen van de waardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx   1 + 2x + \dfrac{8}{2!}x^2 + \dfrac{48}{3!}x^3  \\
  f(x) &\approx   1 + 2x + \dfrac{8}{2}x^2 + \dfrac{48}{6}x^3  \\
  f(x) &\approx   1 + 2x + 4x^2 + 8x^3 {\color{blue} \quad  \text{(1p)}}
\end{align}

:::
::::