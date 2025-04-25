# 6.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 6.3.1a

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{7x+1}{x^2-4} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{7x+1}{(x-2)(x+2)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 2 } \\
    &= \dfrac{ A(x + 2) }{ (x - 2 ) (x + 2) } + \dfrac{ B(x - 2) }{ (x - 2 ) (x + 2) } \\
    &= \dfrac{ A(x + 2) + B(x - 2) }{ (x - 2) (x + 2) } \\
    &= \dfrac{ Ax + 2A + Bx - 2B }{ (x - 2) (x + 2) } \\
    &= \dfrac{ (A + B)x + 2A - 2B }{ (x - 2) (x + 2) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{7x + 1}{(x-2)(x+2)} = \dfrac{ (A + B)x + 2A - 2B }{ (x - 2) (x + 2) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   7x+1 = (A + B)x + 2A - 2B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 7 \\
   2A - 2B &= 1
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 7 - B \\
   2(7-B) - 2B &= 1 \\
   14 - 2B - 2B &= 1 \\
   -4B &= -13 \\
   B &= \dfrac{13}{4}
\end{align}

B invullen geeft:
\begin{align}
   A &= 7 - \dfrac{13}{4} \\
   A &= \dfrac{28}{4} - \dfrac{13}{4} \\
   A &= \dfrac{15}{4}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{7x+1}{x^2-4} \, dx & = \int \dfrac{7x+1}{(x-2)(x+2)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 2 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ x + 2 } \, dx\\
   &= \int \dfrac{ 15/4 }{ x - 2 } \, dx + \int \dfrac{ 13/4 }{ x + 2 } \, dx\\
   &= \dfrac{15}{4} \int \dfrac{ 1 }{ x - 2 } \, dx + \dfrac{13}{4} \int \dfrac{ 1 }{ x + 2 } \, dx\\
   &= \dfrac{15}{4} \ln|x - 2 | + \dfrac{13}{4} \ln| x + 2| + C\\
\end{align}

```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1b

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{5x - 2}{x^2 + x - 12} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{5x - 2}{(x - 3)(x + 4)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x - 3 } + \dfrac{ B }{ x + 4 } \\
    &= \dfrac{ A(x + 4) }{ (x - 3 ) (x + 4) } + \dfrac{ B(x - 3) }{ (x - 3 ) (x + 4) } \\
    &= \dfrac{ A(x + 4) + B(x - 3) }{ (x - 3) (x + 4) } \\
    &= \dfrac{ Ax + 4A + Bx - 3B }{ (x - 3) (x + 4) } \\
    &= \dfrac{ (A + B)x + 4A - 3B }{ (x - 3) (x + 4) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{5x - 2}{(x-3)(x+4)} = \dfrac{ (A + B)x + 4A - 3B }{ (x - 3) (x + 4) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   5x - 2 = (A + B)x + 4A - 3B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 5 \\
   4A - 3B &= -2
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 5 - B \\
   4(5 - B) - 3B &= -2 \\
   20 - 4B - 3B &= -2 \\
   -7B &= -22 \\
   B &= \dfrac{22}{7}
\end{align}

B invullen geeft:
\begin{align}
   A &= 5 - \dfrac{22}{7} \\
   A &= \dfrac{35}{7} - \dfrac{22}{7} \\
   A &= \dfrac{13}{7}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{5x - 2}{x^2 + x - 12} \, dx & = \int \dfrac{5x - 2}{(x - 3)(x + 4)} \, dx\\
   &= \int \dfrac{ A }{ x - 3 } + \dfrac{ B }{ x + 4 } \, dx\\
   &= \int \dfrac{ A }{ x - 3 } \, dx + \int \dfrac{ B }{ x + 4 } \, dx\\
   &= \int \dfrac{ 13/7 }{ x - 3 } \, dx + \int \dfrac{ 22/7 }{ x + 4 } \, dx\\
   &= \dfrac{13}{7} \int \dfrac{ 1 }{ x - 3 } \, dx + \dfrac{22}{7} \int \dfrac{ 1 }{ x + 4 } \, dx\\
   &= \dfrac{13}{7} \ln|x - 3 | + \dfrac{22}{7} \ln| x + 4| + C\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1c

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{8x + 11}{x^2 - 5x + 6} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{8x + 11}{(x - 2)(x - 3)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x - 3 } \\
    &= \dfrac{ A(x - 3) }{ (x - 2 ) (x - 3) } + \dfrac{ B(x - 2) }{ (x - 2 ) (x - 3) } \\
    &= \dfrac{ A(x - 3) + B(x - 2) }{ (x - 2) (x - 3) } \\
    &= \dfrac{ Ax - 3A + Bx - 2B }{ (x - 2) (x - 3) } \\
    &= \dfrac{ (A + B)x - 3A - 2B }{ (x - 2) (x - 3) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{8x + 11}{(x - 2)(x - 3)} = \dfrac{ (A + B)x - 3A - 2B }{ (x - 2) (x - 3) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   8x + 11 = (A + B)x - 3A - 2B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 8 \\
   -3A - 2B &= 11
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 8 - B \\
   -3(8 - B) - 2B &= 11 \\
   -24 + 3B - 2B &= 11 \\
   B &= 35 \\
\end{align}

B invullen geeft:
\begin{align}
   A &= 8 - 35 \\
   A &= -27
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{8x + 11}{x^2 - 5x + 6} \, dx & = \int \dfrac{8x + 11}{(x - 2)(x - 3)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ -27 }{ x - 2 } \, dx + \int \dfrac{ 35 }{ x - 3 } \, dx\\
   &= -27 \int \dfrac{ 1 }{ x - 2 } \, dx + 35 \int \dfrac{ 1 }{ x - 3 } \, dx\\
   &= -27 \ln|x - 2 | + 35 \ln| x - 3| + C\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1d

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{6x + 13}{x^2 + 2x - 15} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{6x + 13}{(x + 5)(x - 3)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 3 } \\
    &= \dfrac{ A(x - 3) }{ (x + 5 ) (x - 3) } + \dfrac{ B(x + 5) }{ (x + 5 ) (x - 3) } \\
    &= \dfrac{ A(x - 3) + B(x + 5) }{ (x + 5) (x - 3) } \\
    &= \dfrac{ Ax - 3A + Bx + 5B }{ (x + 5) (x - 3) } \\
    &= \dfrac{ (A + B)x - 3A + 5B }{ (x + 5) (x - 3) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{6x + 13}{(x + 5)(x - 3)} = \dfrac{ (A + B)x - 3A + 5B }{ (x + 5) (x - 3) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   6x + 13 = (A + B)x - 3A + 5B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 6 \\
   -3A + 5B &= 13
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 6 - B \\
   -3(6 - B) + 5B &= 13 \\
   -18 + 3B + 5B &= 13 \\
   8B &= 31 \\
   B &= \dfrac{31}{8}
\end{align}

B invullen geeft:
\begin{align}
   A &= 6 - \dfrac{31}{8} \\
   A &= \dfrac{48}{8} - \dfrac{31}{8} \\
   A &= \dfrac{17}{8}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{6x + 13}{x^2 + 2x - 15} \, dx & = \int \dfrac{6x + 13}{(x + 5)(x - 3)} \, dx\\
   &= \int \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ A }{ x + 5 } \, dx + \int \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ 17/8 }{ x + 5 } \, dx + \int \dfrac{ 31/8 }{ x - 3 } \, dx\\
   &= \dfrac{17}{8} \int \dfrac{ 1 }{ x + 5 } \, dx + \dfrac{31}{8} \int \dfrac{ 1 }{ x - 3 } \, dx\\
   &= \dfrac{17}{8} \ln|x + 5 | + \dfrac{31}{8} \ln| x - 3| + C\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1e

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{10x + 19}{x^2 + 3x - 10} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{10x + 19}{(x + 5)(x - 2)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 2 } \\
    &= \dfrac{ A(x - 2) }{ (x + 5 ) (x - 2) } + \dfrac{ B(x + 5) }{ (x + 5 ) (x - 2) } \\
    &= \dfrac{ A(x - 2) + B(x + 5) }{ (x + 5) (x - 2) } \\
    &= \dfrac{ Ax - 2A + Bx + 5B }{ (x + 5) (x - 2) } \\
    &= \dfrac{ (A + B)x - 2A + 5B }{ (x + 5) (x - 2) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{10x + 19}{(x + 5)(x - 2)} = \dfrac{ (A + B)x - 2A + 5B }{ (x + 5) (x - 2) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   10x + 19 = (A + B)x - 2A + 5B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 10 \\
   -2A + 5B &= 19
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 10 - B \\
   -2(10 - B) + 5B &= 19 \\
   -20 + 2B + 5B &= 19 \\
   7B &= 39 \\
   B &= \dfrac{39}{7}
\end{align}

B invullen geeft:
\begin{align}
   A &= 10 - \dfrac{39}{7} \\
   A &= \dfrac{70}{7} - \dfrac{39}{7} \\
   A &= \dfrac{31}{7}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{10x + 19}{x^2 + 3x - 10} \, dx & = \int \dfrac{10x + 19}{(x + 5)(x - 2)} \, dx\\
   &= \int \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ A }{ x + 5 } \, dx + \int \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ 31/7 }{ x + 5 } \, dx + \int \dfrac{ 39/7 }{ x - 2 } \, dx\\
   &= \dfrac{31}{7} \int \dfrac{ 1 }{ x + 5 } \, dx + \dfrac{39}{7} \int \dfrac{ 1 }{ x - 2 } \, dx\\
   &= \dfrac{31}{7} \ln|x + 5 | + \dfrac{39}{7} \ln| x - 2| + C\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">