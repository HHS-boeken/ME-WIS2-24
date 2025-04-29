## Voorbeeld Toets1 - T2: Uitwerkingen

### Opgave 1

````{admonition} Antwoord
:class: dropdown

De vorm wordt:
\begin{align*}
\frac{7}{3} - \frac{17}{3(3x + 2)}
\end{align*}

```{admonition} Uitwerking
:class: dropdown

Schrijf in de vorm $\dfrac{m}{x - p} = q$:
\begin{align*}
 \dfrac{7x - 1}{3x + 2}
\end{align*}

Voeg de factor $(3x + 2)$ toe aan de teller en corrigeer de teller:
\begin{align}
 = \dfrac{\frac{7}{3} (3x + 2) - \frac{14}{3} - 1}{3x + 2}
\end{align}

Vereenvoudig de teller:
\begin{align}
 = \dfrac{\frac{7}{3}(3x + 2) - \frac{17}{3}}{3x + 2}
\end{align}

Splits de breuk:
\begin{align}
 = \dfrac{\frac{7}{3}(3x + 2)}{3x + 2} - \dfrac{\frac{17}{3}}{3x + 2}
\end{align}

Vereenvoudig de breuk:
\begin{align}
 = \frac{7}{3} - \frac{17}{3(3x + 2)}
\end{align}
```
````
---

### Opgave 2

Bereken de limiet:

\begin{align*}
\lim_{x \uparrow 3} \frac{ x-9  }{ 12 - 4x }
\end{align*}

---

### Opgave 3

Bereken de limiet

\begin{align*}
    \lim_{x \to 0} \frac{\sin(x)-x}{x^3}
\end{align*}

---

### Opgave 4

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
  \dfrac{df}{dx} &= \frac{ 2 \sin(x)\cos(x)(\ln(3x+5)) - \dfrac{3\sin^2(x)}{3x+5} }{ \ln^2(3x+5)} 
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(3x+5)}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align*}
  u &=  \sin^2(x) \\
  v &=  \ln(3x+5) \\
\end{align*}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align*}
  \dfrac{du}{dx} &= 2 \sin(x)\cos(x) {\color{blue} \quad  \text{(1p)}}\\
  \dfrac{dv}{dx} &= \dfrac{1}{3x+5} \cdot 3  {\color{blue} \quad  \text{(1p)}}\\
                &= \dfrac{3}{3x+5} \\
\end{align*}

Toepassen van de quotiëntregel:
\begin{align*}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (\ln(3x+5)) \cdot 2 \sin(x)\cos(x)  - \sin^2(x) \cdot  \dfrac{3}{3x+5} }{ (\ln(3x+5))^2} {\color{blue} \quad  \text{(1p)}}\\
  &= \frac{ 2 \sin(x)\cos(x)(\ln(3x+5)) - \dfrac{3\sin^2(x)}{3x+5} }{ \ln^2(3x+5)} {\color{blue} \quad  \text{(1p)}}
\end{align*}
```
````

---

### Opgave 5

---

### Opgave 6

````{admonition} Antwoord
:class:  dropdown 

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) &\approx   2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{250}{81}x^3  \\
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
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2!}x^2 + \dfrac{\dfrac{500}{27}}{3!}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2}x^2 + \dfrac{\dfrac{500}{27}}{6}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-50}{18}x^2 + \dfrac{500}{162}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{250}{81}x^3  \\
\end{align}
```
````

---

### Opgave 7

````{admonition} Antwoord
:class:  dropdown 

Bereken de onbepaalde integraal:
\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx &= -\dfrac{1}{3} \cos(x^3) + C \\
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align}
    u(x) = x^3
\end{align}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align}
    \dfrac{du}{dx} &= 3x^2 \\
    du &= 3x^2 \, dx
\end{align}

In de originele functie staat $(x^2)$ dus:
\begin{align}
    \dfrac{1}{3}du &= x^2 \, dx
\end{align}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align}
    &\int \sin(x^3) \cdot x^2  \, dx \\
    &= \int \sin(u) \, \dfrac{1}{3}du \\
    &= \dfrac{1}{3} \int \sin(u) \, du 
\end{align}

Integreren geeft:
\begin{align}
    &= \dfrac{1}{3} \cdot -\cos(u) + C \\
     &= -\dfrac{1}{3} \cos(u) + C \\
\end{align}

Terugsubstitueren geeft:
\begin{align}
    &= -\dfrac{1}{3} \cos(x^3) + C \\
\end{align}
```
````

---

### Opgave 8

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
    F(x) &= \dfrac{1}{4}x^2 \cdot \sin(x) + \dfrac{1}{2}x \cdot \cos(x) - \dfrac{1}{2} \sin(x) + C
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) = \dfrac{1}{4}x^2\cos(x)
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx
\end{align*}

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \dfrac{1}{4}x^2 \\
    dv &= \cos(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{2}x \\
    du &= \dfrac{1}{2}x \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= \cos(x) \, dx  \\
    \dfrac{dv}{dx} &= \cos(x) \\
    v &= \sin(x)
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int \sin(x) \dfrac{1}{2}x \, dx\\
     &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
\end{align*}

De integraal $\int \dfrac{1}{2}x \sin(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.
\begin{align*}
   \int \dfrac{1}{2}x \sin(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \dfrac{1}{2}x \\
    dv &= \sin(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{2} \\
    du &= \dfrac{1}{2} \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= \sin(x) \, dx  \\
    \dfrac{dv}{dx} &= \sin(x) \\
    v &= -\cos(x)
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \dfrac{1}{2}x \cdot -\cos(x) - \int -\cos(x) \dfrac{1}{2} \, dx\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \int \cos(x)  \, dx\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - (-\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C) \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) + \dfrac{1}{2}x \cdot \cos(x) - \dfrac{1}{2} \sin(x) + C
\end{align*}
```
````

---

### Opgave 9

````{admonition} Antwoord
:class:  dropdown

\begin{align*}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1}  \, dx &= \dfrac{1}{3}x^3 - x^2 + 3x - 4 \ln|x + 1 | - \frac{2}{ x + 1}  + C\\
\end{align*}

```{admonition} Uitwerking
:class:  dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int  \dfrac{x^4 + 1}{x^2 + 2x + 1}  \, dx
\end{align*}

De teller is groter dan de noemer, dus staartdeling maken.

\begin{align}
 x^2 + 2x + 1 \quad / &x^4 \quad \quad \quad \quad \quad \quad \quad \quad + 1 \backslash \quad x^2 - 2x + 3\\
&x^4 + 2x^3 + x^2 \\
&------------- \quad -\\
&\quad \quad -2x^3 - x^2 + 2x + 1\\
&\quad \quad -2x^3 - 4x^2 - 2x \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad  3x^2 + 2x + 1 \\
&\quad \quad \quad \quad \quad \quad  3x^2 + 6x + 3 \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad \quad \quad  -4x - 2 \\
\end{align}

De rest is $-4x-2$, dus de uiteindelijke uitkomst is:
\begin{align}
& x^2 - 2x + 3 + \dfrac{-4x-2}{x^2+2x+1} = \\
& x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} \\
\end{align}

Dit geeft:
\begin{align}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &=  \int x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} \, dx \\
\end{align}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{4x + 2}{(x + 1)(x + 1)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \\
    &= \dfrac{ A(x + 1) }{ (x + 1) (x + 1) } + \dfrac{ B }{ (x + 1 )^2 } \\
    &= \dfrac{ A(x + 1) + B }{ (x + 1)^2 } \\
    &= \dfrac{ Ax + A + B  }{ (x + 1)^2 } \\
    &= \dfrac{ Ax + A + B }{ (x + 1)^2 } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{4x + 2}{(x+1)^2} = \dfrac{ Ax + A + B }{ (x + 1)^2 } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   4x  + 2 = Ax + A + B
\end{align}

Hieruit volgt:
\begin{align}
   A &= 4 \\
   A + B &= 2
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 4\\
   4 + B &= 2 \\
   B &= -2
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &= \int x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} \, dx \\
   &= \int x^2 - 2x + 3 - \dfrac{4x + 2}{(x+1)(x+1)} \, dx\\
   &= \int (x^2 - 2x + 3) \, dx - \int \dfrac{4x + 2}{(x+1)(x+1)} \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ A }{ x + 1 } \, dx - \int \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ 4 }{ x + 1 } \, dx - \int \dfrac{ -2 }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx - 4 \int \dfrac{ 1 }{ x + 1 } \, dx + 2 \int \dfrac{ 1 }{ (x + 1)^2 } \, dx\\
   &= \dfrac{1}{3}x^3 - x^2 + 3x - 4 \ln|x + 1 | - \frac{2}{ x + 1}  + C\\
\end{align}
```
````

---

### Opgave 10


