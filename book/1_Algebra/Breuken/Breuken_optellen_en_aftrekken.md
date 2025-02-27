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

Deze regel geldt alleen als de noemers gelijk zijn. Als de noemers verschillen, moet er eerst een ***gemeenschappelijke noemer*** worden gevonden.

Wanneer de noemers verschillend zijn, moeten we deze eerst gelijknamig maken. Dit doen we door de ***kleinste gemene noemer (kgv)*** te bepalen. Dit is het kleinste getal (of uitdrukking) dat door beide noemers deelbaar is. In de praktijk werkt het ook om de teller en de noemer van de ene breuk te vermenigvuldigen met de noemer van de andere breuk.

\begin{align*}
 \frac{a}{c} + \frac{b}{d} &= \frac{a \cdot d}{c \cdot d} + \frac{b \cdot c}{d \cdot c} = \frac{a \cdot d + b \cdot c}{c \cdot d}, \\
 \frac{a}{c} - \frac{b}{d} &= \frac{a \cdot d}{c \cdot d} - \frac{b \cdot c}{d \cdot c} = \frac{a \cdot d - b \cdot c}{c \cdot d}.
\end{align*}
````

## 1.3.1 Optellen en aftrekken met gelijknamige noemers

```{admonition} Voorbeeld 1: Optellen met gelijknamige noemers
:class: dropdown

**Voorbeeld 1a:**
Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{3+2x}{x+1} + \dfrac{2}{x + 1}
\end{align*}

Optellen van de breuken:
\begin{align}
 &= \dfrac{(3+2x)+2}{x+1}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \dfrac{2x+5}{x+1}
\end{align}

**Voorbeeld 1b:**
Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{2x^2}{x^2-3x} + \dfrac{x^2+5x}{x^2 - 3x}
\end{align*}

Optellen van de breuken:
\begin{align}
 & = \dfrac{2x^2+(x^2+5x)}{x^2 - 3x}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 & = \dfrac{3x^2+5x}{x^2 - 3x} \\
 & = \dfrac{x(3x+5)}{x(x - 3)} \\
 & = \dfrac{(3x+5)}{(x - 3)} \\
\end{align}
```

````{admonition} Oefening 1
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2}{2x^3 - 2} + \dfrac{x^2+2}{2x^3 - 2}
\end{align*}

```{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2}{2x^3 - 2} + \dfrac{x^2+2}{2x^3 - 2}
\end{align*}

Optellen van de breuken:
\begin{align}
& = \dfrac{x^2+(x^2+2)}{2x^3 - 2}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 & = \dfrac{2x^2+2}{2x^3 - 2}\\
 & = \dfrac{2(x^2+1)}{2(x^3 - 1)}\\
 & = \dfrac{x^2+1}{x^3 - 1}
\end{align}
```
````

````{admonition} Oefening 2
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig:
\begin{align*}
 \frac{x^3 - 4x^2 + 2x}{x^2 - x} + \frac{x^3 - 2x^2 + 3x}{x^2 - x}
\end{align*}

```{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig:
\begin{align*}
 \frac{x^3 - 4x^2 + 2x}{x^2 - x} + \frac{x^3 - 2x^2 + 3x}{x^2 - x}
\end{align*}

Optellen van de breuken:
\begin{align}
 &= \frac{(x^3 - 4x^2 + 2x) + (x^3 - 2x^2 + 3x) }{x^2 - x}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \frac{x^3 - 4x^2 + 2x + x^3 - 2x^2 + 3x }{x^2 - x} \\
 &= \frac{2x^3 - 6x^2 + 5x}{x^2 - x} \\
 &= \frac{x(2x^2 - 6x + 5)}{x(x - 1)} \\
 &= \frac{(2x - 5)(x - 1)}{x - 1} \\
 &= 2x - 5
\end{align}
```
````

```{admonition} Voorbeeld 2: Aftrekken met gelijknamige noemers
:class: dropdown

**Voorbeeld 2a:**
\begin{align*}
 \frac{x + 3}{x^2 + 2x + 1} - \frac{2x - 1}{x^2 + 2x + 1}
\end{align*}

Aftrekken van de breuken:
\begin{align}
 &= \frac{(x + 3) - (2x - 1)}{x^2 + 2x + 1}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \frac{x + 3 - 2x + 1}{x^2 + 2x + 1} \\
 &= \frac{-x + 4}{x^2 + 2x + 1}
\end{align}

**Voorbeeld 2b:**
\begin{align*}
\frac{x^2 + 2x}{x^2 - 4} - \frac{x + 1}{x^2 - 4}
\end{align*}

Aftrekken van de breuken:
\begin{align}
 &= \frac{(x^2 + 2x) - (x + 1)}{x^2 - 4}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \frac{x^2 + 2x - x - 1}{x^2 - 4} \\
 &= \frac{x^2 + x - 1}{x^2 - 4}
\end{align}
```

````{admonition} Oefening 3
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
 \frac{x^2 + 3x + 2}{x^2 - 4} - \frac{x^2 + x}{x^2 - 4}
\end{align*}

```{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align}
 \frac{x^2 + 3x + 2}{x^2 - 4} - \frac{x^2 + x}{x^2 - 4}
\end{align}

Aftrekken van de breuken:
\begin{align}
 &= \frac{(x^2 + 3x + 2)-(x^2 + x)}{x^2 - 4} \\
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \frac{x^2 + 3x + 2-x^2 - x}{x^2 - 4} \\
 &= \frac{2x + 2}{x^2 - 4} \\
 &= \frac{2(x + 1)}{(x - 2)(x + 2)}
\end{align}
```
````

````{admonition} Oefening 4
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
\frac{2x^2 + 3x - 1}{x^2 - x} - \frac{x - 2}{x^2 - x}
\end{align*}

```{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align}
\frac{2x^2 + 3x - 1}{x^2 - x} - \frac{x - 2}{x^2 - x}
\end{align}

Aftrekken van de breuken:
\begin{align}
\frac{(2x^2 + 3x - 1) - (x - 2)}{x^2 - x}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 &= \frac{2x^2 + 3x - 1 - x + 2}{x^2 - x} \\
 &= \frac{2x^2 + 2x + 1}{x^2 - x}
\end{align}
```
````

## 1.3.2 Optellen en aftrekken met verschillende noemers

```{admonition} Voorbeeld 3: Optellen met verschillende noemers
:class: dropdown

\begin{align*}
\frac{3}{x} + \frac{2}{x + 1}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $x(x + 1)$.

Herschrijf de breuken
\begin{align}
\frac{3}{x} &= \frac{3(x + 1)}{x(x + 1)}, \\
\frac{2}{x + 1} &= \frac{2x}{x(x + 1)}
\end{align}

Optellen van de breuken
\begin{align}
&= \frac{3(x + 1)+2x}{x(x + 1)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
&= \frac{3x + 3 + 2x}{x(x + 1)}\\
&= \frac{5x + 3}{x(x + 1)}
\end{align}
```

````{admonition} Oefening 5
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x}{x + 3} + \dfrac{2}{x + 5}
\end{align*}

```{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x}{x + 3} + \dfrac{2}{x + 5}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 3)(x + 5)$.

Herschrijf de breuken
\begin{align}
 \dfrac{x}{x + 3} &= \dfrac{x(x + 5)}{(x + 3)(x + 5)}, \\
 \dfrac{2}{x + 5} &= \dfrac{2(x + 3)}{(x + 3)(x + 5)}
\end{align}

Optellen van de breuken
\begin{align}
 &= \dfrac{x(x + 5) + 2(x + 3)}{(x + 3)(x + 5)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
& = \dfrac{x^2 + 5x + 2x + 6}{(x + 3)(x + 5)} \\
& = \dfrac{x^2 + 7x + 6}{(x + 3)(x + 5)}
\end{align}
```
````

````{admonition} Oefening 6
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x + 2}{x + 4} + \dfrac{x}{x + 6}
\end{align*}

```{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x + 2}{x + 4} + \dfrac{x}{x + 6}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 4)(x + 6)$.

Herschrijf de breuken
\begin{align}
 \dfrac{x + 2}{x + 4} = \dfrac{(x + 2)(x + 6)}{(x + 4)(x + 6)}, \\
 \dfrac{x}{x + 6} = \dfrac{x(x + 4)}{(x + 4)(x + 6)}
\end{align}

Optellen van de breuken
\begin{align}
 &= \dfrac{(x + 2)(x + 6) + x(x + 4)}{(x + 4)(x + 6)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
 & = \dfrac{x^2 + 6x + 2x + 12 + x^2 + 4x}{(x + 4)(x + 6)}\\
 & = \dfrac{2x^2 + 12x + 12}{(x + 4)(x + 6)}\\
 & = \dfrac{2(x^2 + 6x + 6)}{(x + 4)(x + 6)}
\end{align}
```
````

```{admonition} Voorbeeld 4: Aftrekken met verschillende noemers
:class: dropdown

\begin{align*}
\frac{5}{x - 2} - \frac{3}{x + 2}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x - 2)(x + 2)$.

Herschrijf de breuken:
\begin{align}
 \dfrac{5}{x - 2} = \dfrac{5(x + 2)}{(x - 2)(x + 2)}, \\
 \dfrac{3}{x + 2} = \dfrac{3(x - 2)}{(x - 2)(x + 2)}
\end{align}

Aftrekken van de breuken:
\begin{align}
 &= \dfrac{5(x + 2)-3(x - 2)}{(x - 2)(x + 2)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
&= \dfrac{5x + 10 - (3x - 6)}{(x - 2)(x + 2)} \\
&= \dfrac{5x + 10 - 3x + 6}{(x - 2)(x + 2)} \\
&= \dfrac{2x + 16}{(x - 2)(x + 2)}
\end{align}
```

````{admonition} Oefening 7
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x + 5}{x + 2} - \dfrac{x - 1}{x + 3}
\end{align*}

```{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x + 5}{x + 2} - \dfrac{x - 1}{x + 3}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 2)(x + 3)$.

Herschrijf de breuken:
\begin{align}
 \dfrac{x + 5}{x + 2} &= \dfrac{(x + 5)(x + 3)}{(x + 2)(x + 3)}, \\
 \dfrac{x - 1}{x + 3} &= \dfrac{(x - 1)(x + 2)}{(x + 2)(x + 3)}
\end{align}

Aftrekken van de breuken:
\begin{align}
 &= \dfrac{(x + 5)(x + 3) - (x - 1)(x + 2)}{(x + 2)(x + 3)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
&= \dfrac{(x^2 + 5x + 3x + 15)- (x^2 -x + 2x -2)}{(x + 2)(x + 3)} \\
&= \dfrac{x^2 + 5x + 3x + 15- x^2 +x - 2x +2}{(x + 2)(x + 3)} \\
&= \dfrac{7x + 17}{(x + 2)(x + 3)}
\end{align}
```
````

````{admonition} Oefening 8
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2 + 3}{x + 1} - \frac{x}{x + 4}
\end{align*}

```{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2 + 3}{x + 1} - \frac{x}{x + 4}
\end{align*}

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 1)(x + 4)$.

Herschrijf de breuken:
\begin{align}
 \dfrac{x^2 + 3}{x + 1} = \dfrac{(x^2 + 3)(x + 4)}{(x + 1)(x + 4)} \\
 \dfrac{x}{x + 4} = \dfrac{x(x + 1)}{(x + 1)(x + 4)}
\end{align}

Aftrekken van de breuken:
\begin{align}
 &= \dfrac{(x^2 + 3)(x + 4) - x(x + 1)}{(x + 1)(x + 4)}
\end{align}

Uitwerken van de tellers en vereenvoudigen:
\begin{align}
&= \dfrac{(x^3 + 3x + 4x^2 + 12) - (x^2 + x)}{(x + 1)(x + 4)} \\
&= \dfrac{x^3 + 3x + 4x^2 + 12 - x^2 - x}{(x + 1)(x + 4)} \\
&= \dfrac{x^3 + 3x^2 + 2x + 12}{(x + 1)(x + 4)} \\
&= \dfrac{x^2(x + 3) + 2(x + 6)}{(x + 1)(x + 4)}
\end{align}
```
````

