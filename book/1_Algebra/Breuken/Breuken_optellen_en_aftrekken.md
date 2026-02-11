# 1.3 Breuken optellen en aftrekken

::::{admonition} Theorie
:class: tip, dropdown open

Breuken zijn een fundamenteel onderdeel van algebra en worden veel gebruikt in wiskunde en techniek. Bij het optellen en aftrekken van breuken met variabelen is het belangrijk om de regels van breukrekenen correct toe te passen. Dit vereist onder andere het bepalen van een gemeenschappelijke noemer en het correct verwerken van algebraïsche termen.

Basisregel voor optellen en aftrekken van breuken

Bij het optellen en aftrekken van breuken geldt de volgende algemene regel:

$$
\frac{a}{c} + \frac{b}{c}  \frac{a + b}{c}, \quad \text{mits } c \neq 0, \\
\frac{a}{c} - \frac{b}{c}  \frac{a - b}{c}, \quad \text{mits } c \neq 0.
$$

Deze regel geldt alleen als de noemers gelijk zijn. Als de noemers verschillen, moet er eerst een ***gemeenschappelijke noemer*** worden gevonden.

Wanneer de noemers verschillend zijn, moeten we deze eerst gelijknamig maken. Dit doen we door de ***kleinste gemene noemer (kgv)*** te bepalen. Dit is het kleinste getal (of uitdrukking) dat door beide noemers deelbaar is. In de praktijk werkt het ook om de teller en de noemer van de ene breuk te vermenigvuldigen met de noemer van de andere breuk.

$$
\frac{a}{c} + \frac{b}{d}  \frac{a \cdot d}{c \cdot d} + \frac{b \cdot c}{d \cdot c} = \frac{a \cdot d + b \cdot c}{c \cdot d}, \\
\frac{a}{c} - \frac{b}{d}  \frac{a \cdot d}{c \cdot d} - \frac{b \cdot c}{d \cdot c} = \frac{a \cdot d - b \cdot c}{c \cdot d}.
$$

::::

## 1.3.1 Optellen en aftrekken met gelijknamige noemers

:::{admonition} Voorbeeld 1: Optellen met gelijknamige noemers
:class: dropdown

**Voorbeeld 1a:**
Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{3+2x}{x+1} + \dfrac{2}{x + 1}
$$

Optellen van de breuken:

$$
= \dfrac{(3+2x)+2}{x+1}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \dfrac{2x+5}{x+1}
$$

**Voorbeeld 1b:**
Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{2x^2}{x^2-3x} + \dfrac{x^2+5x}{x^2 - 3x}
$$

Optellen van de breuken:

$$
= \dfrac{2x^2+(x^2+5x)}{x^2 - 3x}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \dfrac{3x^2+5x}{x^2 - 3x}
$$

Ontbind de teller en de noemer in factoren:

$$
= \dfrac{x(3x+5)}{x(x - 3)}
$$

Wegdelen van de gemeenschappelijke factor in de teller en de noemer:

$$
= \dfrac{(3x+5)}{(x - 3)}
$$

:::

::::{admonition} Oefening 1
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x^2}{2x^3 - 2} + \dfrac{x^2+2}{2x^3 - 2}
$$

:::{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x^2}{2x^3 - 2} + \dfrac{x^2+2}{2x^3 - 2}
$$

Optellen van de breuken:

$$
= \dfrac{x^2+(x^2+2)}{2x^3 - 2}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \dfrac{2x^2+2}{2x^3 - 2}\\
$$

Ontbind de teller en de noemer in factoren:

$$
= \dfrac{2(x^2+1)}{2(x^3 - 1)}
$$

Wegdelen van de gemeenschappelijke factor in de teller en de noemer:

$$
= \dfrac{x^2+1}{x^3 - 1}
$$

:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig:

$$
\frac{x^3 - 4x^2 + 2x}{x^2 - x} + \frac{x^3 - 2x^2 + 3x}{x^2 - x}
$$

:::{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig:

$$
\frac{x^3 - 4x^2 + 2x}{x^2 - x} + \frac{x^3 - 2x^2 + 3x}{x^2 - x}
$$

Optellen van de breuken:

$$
= \frac{(x^3 - 4x^2 + 2x) + (x^3 - 2x^2 + 3x) }{x^2 - x}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{x^3 - 4x^2 + 2x + x^3 - 2x^2 + 3x }{x^2 - x} \\
= \frac{2x^3 - 6x^2 + 5x}{x^2 - x} \\
= \frac{x(2x^2 - 6x + 5)}{x(x - 1)} \\
= \frac{(2x - 5)(x - 1)}{x - 1} \\
= 2x - 5
$$

:::
::::

:::{admonition} Voorbeeld 2: Aftrekken met gelijknamige noemers
:class: dropdown

**Voorbeeld 2a:**

$$
\frac{x + 3}{x^2 + 2x + 1} - \frac{2x - 1}{x^2 + 2x + 1}
$$

Aftrekken van de breuken:

$$
= \frac{(x + 3) - (2x - 1)}{x^2 + 2x + 1}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{x + 3 - 2x + 1}{x^2 + 2x + 1}
= \frac{-x + 4}{x^2 + 2x + 1}
$$

**Voorbeeld 2b:**

$$
= \frac{x^2 + 2x}{x^2 - 4} - \frac{x + 1}{x^2 - 4}
$$

Aftrekken van de breuken:

$$
= \frac{(x^2 + 2x) - (x + 1)}{x^2 - 4}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{x^2 + 2x - x - 1}{x^2 - 4} \\
= \frac{x^2 + x - 1}{x^2 - 4}
$$
:::

::::{admonition} Oefening 3
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
= \frac{x^2 + 3x + 2}{x^2 - 4} - \frac{x^2 + x}{x^2 - 4}
$$

:::{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
= \frac{x^2 + 3x + 2}{x^2 - 4} - \frac{x^2 + x}{x^2 - 4}
$$

Aftrekken van de breuken:

$$
=\frac{(x^2 + 3x + 2)-(x^2 + x)}{x^2 - 4} \\
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{x^2 + 3x + 2-x^2 - x}{x^2 - 4}
= \frac{2x + 2}{x^2 - 4}
=\frac{2(x + 1)}{(x - 2)(x + 2)}
$$

:::
::::

::::{admonition} Oefening 4
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\frac{2x^2 + 3x - 1}{x^2 - x} - \frac{x - 2}{x^2 - x}
$$

:::{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\frac{2x^2 + 3x - 1}{x^2 - x} - \frac{x - 2}{x^2 - x}
$$

Aftrekken van de breuken:

$$
= \frac{(2x^2 + 3x - 1) - (x - 2)}{x^2 - x}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{2x^2 + 3x - 1 - x + 2}{x^2 - x}
= \frac{2x^2 + 2x + 1}{x^2 - x}
$$

:::
::::

## 1.3.2 Optellen en aftrekken met verschillende noemers

:::{admonition} Voorbeeld 3: Optellen met verschillende noemers
:class: dropdown

$$
\frac{3}{x} + \frac{2}{x + 1}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $x(x + 1)$.

Herschrijf de breuken

$$
= \frac{3}{x}  \frac{3(x + 1)}{x(x + 1)}, \\
= \frac{2}{x + 1}  \frac{2x}{x(x + 1)}
$$

Optellen van de breuken

$$
= \frac{3(x + 1)+2x}{x(x + 1)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \frac{3x + 3 + 2x}{x(x + 1)}
= \frac{5x + 3}{x(x + 1)}
$$
:::

::::{admonition} Oefening 5
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x}{x + 3} + \dfrac{2}{x + 5}
$$

:::{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x}{x + 3} + \dfrac{2}{x + 5}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 3)(x + 5)$.

Herschrijf de breuken

$$
= \dfrac{x}{x + 3}  \dfrac{x(x + 5)}{(x + 3)(x + 5)}
= \dfrac{2}{x + 5}  \dfrac{2(x + 3)}{(x + 3)(x + 5)}
$$

Optellen van de breuken

$$
= \dfrac{x(x + 5) + 2(x + 3)}{(x + 3)(x + 5)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \dfrac{x^2 + 5x + 2x + 6}{(x + 3)(x + 5)}
= \dfrac{x^2 + 7x + 6}{(x + 3)(x + 5)}
$$

:::
::::

::::{admonition} Oefening 6
:class: important, dropdown

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x + 2}{x + 4} + \dfrac{x}{x + 6}
$$

:::{dropdown} Uitwerking

Tel de volgende breuk op en vereenvoudig zo ver mogelijk:

$$
\dfrac{x + 2}{x + 4} + \dfrac{x}{x + 6}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 4)(x + 6)$.

Herschrijf de breuken

$$
= \dfrac{x + 2}{x + 4} = \dfrac{(x + 2)(x + 6)}{(x + 4)(x + 6)}
= \dfrac{x}{x + 6} = \dfrac{x(x + 4)}{(x + 4)(x + 6)}
$$

Optellen van de breuken

$$
= \dfrac{(x + 2)(x + 6) + x(x + 4)}{(x + 4)(x + 6)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
= \dfrac{x^2 + 6x + 2x + 12 + x^2 + 4x}{(x + 4)(x + 6)}
= \dfrac{2x^2 + 12x + 12}{(x + 4)(x + 6)}
= \dfrac{2(x^2 + 6x + 6)}{(x + 4)(x + 6)}
$$

:::
::::

:::{admonition} Voorbeeld 4: Aftrekken met verschillende noemers
:class: dropdown

$$
\frac{5}{x - 2} - \frac{3}{x + 2}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x - 2)(x + 2)$.

Herschrijf de breuken:

$$
= \dfrac{5}{x - 2} = \dfrac{5(x + 2)}{(x - 2)(x + 2)}, \\
= \dfrac{3}{x + 2} = \dfrac{3(x - 2)}{(x - 2)(x + 2)}
$$

Aftrekken van de breuken:

$$
\dfrac{5(x + 2)-3(x - 2)}{(x - 2)(x + 2)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
\dfrac{5x + 10 - (3x - 6)}{(x - 2)(x + 2)} \\
\dfrac{5x + 10 - 3x + 6}{(x - 2)(x + 2)} \\
\dfrac{2x + 16}{(x - 2)(x + 2)}
$$

:::

::::{admonition} Oefening 7
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\dfrac{x + 5}{x + 2} - \dfrac{x - 1}{x + 3}
$$

:::{dropdown} Uitwerking

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\dfrac{x + 5}{x + 2} - \dfrac{x - 1}{x + 3}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 2)(x + 3)$.

Herschrijf de breuken:

$$
\dfrac{x + 5}{x + 2}  \dfrac{(x + 5)(x + 3)}{(x + 2)(x + 3)}, \\
\dfrac{x - 1}{x + 3}  \dfrac{(x - 1)(x + 2)}{(x + 2)(x + 3)}
$$

Aftrekken van de breuken:

$$
\dfrac{(x + 5)(x + 3) - (x - 1)(x + 2)}{(x + 2)(x + 3)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
\dfrac{(x^2 + 5x + 3x + 15)- (x^2 -x + 2x -2)}{(x + 2)(x + 3)} \\
\dfrac{x^2 + 5x + 3x + 15- x^2 +x - 2x +2}{(x + 2)(x + 3)} \\
\dfrac{7x + 17}{(x + 2)(x + 3)}
$$

:::
::::

::::{admonition} Oefening 8
:class: important, dropdown

Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\dfrac{x^2 + 3}{x + 1} - \frac{x}{x + 4}
$$

:::{dropdown} Uitwerking
Trek de volgende breuk af en vereenvoudig zo ver mogelijk:

$$
\dfrac{x^2 + 3}{x + 1} - \frac{x}{x + 4}
$$

Bepaal de kleinste gemene noemer:
De kleinste gemene noemer is $(x + 1)(x + 4)$.

Herschrijf de breuken:

$$
\dfrac{x^2 + 3}{x + 1} = \dfrac{(x^2 + 3)(x + 4)}{(x + 1)(x + 4)} \\
\dfrac{x}{x + 4} = \dfrac{x(x + 1)}{(x + 1)(x + 4)}
$$

Aftrekken van de breuken:

$$
\dfrac{(x^2 + 3)(x + 4) - x(x + 1)}{(x + 1)(x + 4)}
$$

Uitwerken van de tellers en vereenvoudigen:

$$
 \dfrac{(x^3 + 3x + 4x^2 + 12) - (x^2 + x)}{(x + 1)(x + 4)} \\
 \dfrac{x^3 + 3x + 4x^2 + 12 - x^2 - x}{(x + 1)(x + 4)} \\
 \dfrac{x^3 + 3x^2 + 2x + 12}{(x + 1)(x + 4)} \\
 \dfrac{x^2(x + 3) + 2(x + 6)}{(x + 1)(x + 4)}
$$

:::
::::
