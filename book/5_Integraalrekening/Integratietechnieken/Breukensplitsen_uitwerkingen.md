# 6.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 6.3.1a

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

### Opgave 1  
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
\begin{align}
\int \frac{5x - 2}{x^2 + x - 12} \, dx
\end{align}

Ontbinden van de noemer:  
\begin{align}
= \int \frac{5x - 2}{(x - 3)(x + 4)} \, dx
\end{align}

Breukensplitsen:  
\begin{align}
= \frac{A}{x - 3} + \frac{B}{x + 4}
\end{align}
\begin{align}
= \frac{A(x + 4) + B(x - 3)}{(x - 3)(x + 4)}
\end{align}
\begin{align}
= \frac{(A + B)x + (4A - 3B)}{(x - 3)(x + 4)}
\end{align}

Gelijkstellen van tellers:  
\begin{align}
5x - 2 = (A + B)x + (4A - 3B)
\end{align}

Stelsel:  
\begin{align}
A + B = 5 \\
4A - 3B = -2
\end{align}

Oplossen:  
\begin{align}
A = 1, \quad B = 4
\end{align}

Substitueren:  
\begin{align}
= \int \frac{1}{x - 3} \, dx + \int \frac{4}{x + 4} \, dx
\end{align}
\begin{align}
= \ln|x - 3| + 4 \ln|x + 4| + C
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1c

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

\begin{align}
\int \frac{8x + 11}{x^2 - 5x + 6} \, dx
\end{align}

Ontbinden van de noemer:  
\begin{align}
= \int \frac{8x + 11}{(x - 2)(x - 3)} \, dx
\end{align}

Breukensplitsen:  
\begin{align}
= \frac{A}{x - 2} + \frac{B}{x - 3}
\end{align}
\begin{align}
= \frac{A(x - 3) + B(x - 2)}{(x - 2)(x - 3)}
\end{align}
\begin{align}
= \frac{(A + B)x - 3A - 2B}{(x - 2)(x - 3)}
\end{align}

Gelijkstellen:  
\begin{align}
8x + 11 = (A + B)x - 3A - 2B
\end{align}

Stelsel:  
\begin{align}
A + B = 8 \\
-3A - 2B = 11
\end{align}

Oplossen:  
\begin{align}
A = 5, \quad B = 3
\end{align}

Substitueren:  
\begin{align}
= \int \frac{5}{x - 2} \, dx + \int \frac{3}{x - 3} \, dx
\end{align}
\begin{align}
= 5 \ln|x - 2| + 3 \ln|x - 3| + C
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1d

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

\begin{align}
\int \frac{6x + 13}{x^2 + 2x - 15} \, dx
\end{align}

Ontbinden van de noemer:  
\begin{align}
= \int \frac{6x + 13}{(x + 5)(x - 3)} \, dx
\end{align}

Breukensplitsen:  
\begin{align}
= \frac{A}{x + 5} + \frac{B}{x - 3}
\end{align}
\begin{align}
= \frac{A(x - 3) + B(x + 5)}{(x + 5)(x - 3)}
\end{align}
\begin{align}
= \frac{(A + B)x - 3A + 5B}{(x + 5)(x - 3)}
\end{align}

Gelijkstellen:  
\begin{align}
6x + 13 = (A + B)x - 3A + 5B
\end{align}

Stelsel:  
\begin{align}
A + B = 6 \\
-3A + 5B = 13
\end{align}

Oplossen:  
\begin{align}
A = 1, \quad B = 5
\end{align}

Substitueren:  
\begin{align}
= \int \frac{1}{x + 5} \, dx + \int \frac{5}{x - 3} \, dx
\end{align}
\begin{align}
= \ln|x + 5| + 5 \ln|x - 3| + C
\end{align}
```
````

<hr style="border:1px solid #9EA700">

### Opgave 6.3.1e

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

\begin{align}
\int \frac{10x + 19}{x^2 + 3x - 10} \, dx
\end{align}

Ontbinden van de noemer:  
\begin{align}
= \int \frac{10x + 19}{(x + 5)(x - 2)} \, dx
\end{align}

Breukensplitsen:  
\begin{align}
= \frac{A}{x + 5} + \frac{B}{x - 2}
\end{align}
\begin{align}
= \frac{A(x - 2) + B(x + 5)}{(x + 5)(x - 2)}
\end{align}
\begin{align}
= \frac{(A + B)x - 2A + 5B}{(x + 5)(x - 2)}
\end{align}

Gelijkstellen:  
\begin{align}
10x + 19 = (A + B)x - 2A + 5B
\end{align}

Stelsel:  
\begin{align}
A + B = 10 \\
-2A + 5B = 19
\end{align}

Oplossen:  
\begin{align}
A = 3, \quad B = 7
\end{align}

Substitueren:  
\begin{align}
= \int \frac{3}{x + 5} \, dx + \int \frac{7}{x - 2} \, dx
\end{align}
\begin{align}
= 3 \ln|x + 5| + 7 \ln|x - 2| + C
\end{align}
```
````

<hr style="border:1px solid #9EA700">