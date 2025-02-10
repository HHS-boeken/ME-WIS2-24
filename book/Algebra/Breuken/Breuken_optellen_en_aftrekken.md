# 1.3 Breuken optellen en aftrekken

````{admonition} Theorie
:class: tip, dropdown open

Breuken zijn een fundamenteel onderdeel van algebra en worden veel gebruikt in wiskunde en techniek. Bij het optellen en aftrekken van breuken met variabelen is het belangrijk om de regels van breukrekenen correct toe te passen. Dit vereist onder andere het bepalen van een gemeenschappelijke noemer en het correct verwerken van algebraïsche termen.

Basisregel voor optellen en aftrekken van breuken

Bij het optellen en aftrekken van breuken geldt de volgende algemene regel:

\begin{align*}
\frac{a}{c} + \frac{b}{c} &= \frac{a + b}{c}, \quad \text{mits } c \neq 0, \\
\frac{a}{c} - \frac{b}{c} &= \frac{a - b}{c}, \quad \text{mits } c \neq 0.
\end{align*}

Deze regel geldt alleen als de noemers gelijk zijn. Als de noemers verschillen, moet er eerst een **gemeenschappelijke noemer** worden gevonden.

2. Optellen en aftrekken met dezelfde noemer

Als de breuken dezelfde noemer hebben, dan kunnen de tellers direct bij elkaar opgeteld of van elkaar afgetrokken worden.

Voorbeeld 1: Eenvoudige som
\begin{align*}
\frac{x}{5} + \frac{3}{5} &= \frac{x + 3}{5}
\end{align*}

Voorbeeld 2: Aftrekken van breuken
\begin{align*}
\frac{7x}{9} - \frac{2x}{9} &= \frac{(7x - 2x)}{9} = \frac{5x}{9}
\end{align*}

3. Optellen en aftrekken met verschillende noemers

Wanneer de noemers verschillend zijn, moeten we eerst de \textbf{kleinste gemene noemer (kgv)} bepalen. Dit is het kleinste getal (of uitdrukking) dat door beide noemers deelbaar is.

\begin{align*}
\frac{a}{c} + \frac{b}{d} &= \frac{a \cdot d}{c \cdot d} + \frac{b \cdot c}{c \cdot d} = \frac{a \cdot d + b \cdot c}{c \cdot d}, \\
\frac{a}{c} - \frac{b}{d} &= \frac{a \cdot d}{c \cdot d} - \frac{b \cdot c}{c \cdot d} = \frac{a \cdot d - b \cdot c}{c \cdot d}.
\end{align*}
````

## Optellen en aftrekken met gemeenschappelijke noemers

Voorbeeld 3: Optellen met verschillende noemers
\begin{align*}
\frac{x}{4} + \frac{2}{6}
\end{align*}
\textbf{Stap 1: Bepaal de kleinste gemene noemer (kgv)} \\
De kgv van 4 en 6 is 12.

\textbf{Stap 2: Herschrijf de breuken met 12 als noemer}
\begin{align*}
\frac{x}{4} &= \frac{3x}{12}, \quad \frac{2}{6} = \frac{4}{12}
\end{align*}

\textbf{Stap 3: Optellen van de breuken}
\begin{align*}
\frac{3x}{12} + \frac{4}{12} &= \frac{3x + 4}{12}
\end{align*}

Voorbeeld 4: Aftrekken met verschillende noemers
\begin{align*}
\frac{x}{5} - \frac{3}{7}
\end{align*}
\textbf{Stap 1: Bepaal de kleinste gemene noemer (kgv)} \\
De kgv van 5 en 7 is 35.

\textbf{Stap 2: Herschrijf de breuken met 35 als noemer}
\begin{align*}
\frac{x}{5} &= \frac{7x}{35}, \quad \frac{3}{7} = \frac{15}{35}
\end{align*}

\textbf{Stap 3: Aftrekken van de breuken}
\begin{align*}
\frac{7x}{35} - \frac{15}{35} &= \frac{7x - 15}{35}
\end{align*}

4. Optellen en aftrekken met algebraïsche noemers

Wanneer de noemers algebraïsch zijn, gebruiken we het \textbf{kleinste gemene veelvoud (kgv)}, net zoals bij getallen.

## Optellen en aftrekken met verschillende noemers

```{admonition} Voorbeeld 5: Algebraïsche noemers
:class: dropdown

\begin{align*}
\frac{3}{x} + \frac{2}{x + 1}
\end{align*}

Bepaal de kleinste gemene noemer \\
De kleinste gemene noemer is \( x(x + 1) \).

Herschrijf de breuken
\begin{align*}
\frac{3}{x} &= \frac{3(x + 1)}{x(x + 1)}, \\
\frac{2}{x + 1} &= \frac{2x}{x(x + 1)}
\end{align*}

Optellen van de breuken
\begin{align*}
\frac{3(x + 1)}{x(x + 1)} + \frac{2x}{x(x + 1)}
\end{align*}

Uitwerken van de tellers en vereenvoudigen:
\begin{align*}
\frac{3x + 3 + 2x}{x(x + 1)} &= \frac{5x + 3}{x(x + 1)}
\end{align*}
```

```{admonition} Voorbeeld 6: Aftrekken van algebraïsche breuken
:class: dropdown

\begin{align*}
\frac{5}{x - 2} - \frac{3}{x + 2}
\end{align*}

Stap 1: Bepaal de kleinste gemene noemer \\
De kgv van \( (x - 2) \) en \( (x + 2) \) is \( (x - 2)(x + 2) \).

Herschrijf de breuken:
\begin{align*}
\frac{5}{x - 2} &= \frac{5(x + 2)}{(x - 2)(x + 2)}, \\
\frac{3}{x + 2} &= \frac{3(x - 2)}{(x - 2)(x + 2)}
\end{align*}

Aftrekken van de breuken:
\begin{align*}
\frac{5(x + 2)}{(x - 2)(x + 2)} - \frac{3(x - 2)}{(x - 2)(x + 2)}
\end{align*}

Uitwerken van de tellers en vereenvoudigen:
\begin{align*}
& \frac{5x + 10 - (3x - 6)}{(x - 2)(x + 2)} \\
&= \frac{5x + 10 - 3x + 6}{(x - 2)(x + 2)} \\
&= \frac{2x + 16}{(x - 2)(x + 2)}
\end{align*}
```

\section*{5. Samenvatting}
\begin{itemize}
    \item Bij dezelfde noemers: tel of trek de tellers af.
    \item Bij verschillende noemers: zoek het kgv en herschrijf de breuken.
    \item Bij algebraïsche noemers: gebruik factorisatie en kgv-regels.
\end{itemize}


