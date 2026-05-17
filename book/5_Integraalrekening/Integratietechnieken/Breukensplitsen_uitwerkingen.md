# 6.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

## Opgave 6.3.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{7x+1}{x^2-4} \, dx = \dfrac{15}{4} \ln|x - 2 | + \dfrac{13}{4} \ln| x + 2| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{7x+1}{x^2-4} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{7x+1}{(x-2)(x+2)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 2 } \\
    &= \dfrac{ A(x + 2) }{ (x - 2 ) (x + 2) } + \dfrac{ B(x - 2) }{ (x - 2 ) (x + 2) } \\
    &= \dfrac{ A(x + 2) + B(x - 2) }{ (x - 2) (x + 2) } \\
    &= \dfrac{ Ax + 2A + Bx - 2B }{ (x - 2) (x + 2) } \\
    &= \dfrac{ (A + B)x + 2A - 2B }{ (x - 2) (x + 2) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{7x + 1}{(x-2)(x+2)} = \dfrac{ (A + B)x + 2A - 2B }{ (x - 2) (x + 2) } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   7x+1 = (A + B)x + 2A - 2B
$$

Hieruit volgt:

$$
\begin{align}
   A+B &= 7 \\
   2A - 2B &= 1
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 7 - B \\
   2(7-B) - 2B &= 1 \\
   14 - 2B - 2B &= 1 \\
   -4B &= -13 \\
   B &= \dfrac{13}{4}
\end{align}
$$

B invullen geeft:

$$
\begin{align}
   A &= 7 - \dfrac{13}{4} \\
   A &= \dfrac{28}{4} - \dfrac{13}{4} \\
   A &= \dfrac{15}{4}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{7x+1}{x^2-4} \, dx & = \int \dfrac{7x+1}{(x-2)(x+2)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 2 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ x + 2 } \, dx\\
   &= \int \dfrac{ 15/4 }{ x - 2 } \, dx + \int \dfrac{ 13/4 }{ x + 2 } \, dx\\
   &= \dfrac{15}{4} \int \dfrac{ 1 }{ x - 2 } \, dx + \dfrac{13}{4} \int \dfrac{ 1 }{ x + 2 } \, dx\\
   &= \dfrac{15}{4} \ln|x - 2 | + \dfrac{13}{4} \ln| x + 2| + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2b

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{5x - 2}{x^2 + x - 12} \, dx = \dfrac{13}{7} \ln|x - 3 | + \dfrac{22}{7} \ln| x + 4| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{5x - 2}{x^2 + x - 12} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{5x - 2}{(x - 3)(x + 4)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 3 } + \dfrac{ B }{ x + 4 } \\
    &= \dfrac{ A(x + 4) }{ (x - 3 ) (x + 4) } + \dfrac{ B(x - 3) }{ (x - 3 ) (x + 4) } \\
    &= \dfrac{ A(x + 4) + B(x - 3) }{ (x - 3) (x + 4) } \\
    &= \dfrac{ Ax + 4A + Bx - 3B }{ (x - 3) (x + 4) } \\
    &= \dfrac{ (A + B)x + 4A - 3B }{ (x - 3) (x + 4) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{5x - 2}{(x-3)(x+4)} = \dfrac{ (A + B)x + 4A - 3B }{ (x - 3) (x + 4) } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   5x - 2 = (A + B)x + 4A - 3B
$$

Hieruit volgt:

$$
\begin{align}
   A+B &= 5 \\
   4A - 3B &= -2
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 5 - B \\
   4(5 - B) - 3B &= -2 \\
   20 - 4B - 3B &= -2 \\
   -7B &= -22 \\
   B &= \dfrac{22}{7}
\end{align}
$$

B invullen geeft:

$$
\begin{align}
   A &= 5 - \dfrac{22}{7} \\
   A &= \dfrac{35}{7} - \dfrac{22}{7} \\
   A &= \dfrac{13}{7}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{5x - 2}{x^2 + x - 12} \, dx & = \int \dfrac{5x - 2}{(x - 3)(x + 4)} \, dx\\
   &= \int \dfrac{ A }{ x - 3 } + \dfrac{ B }{ x + 4 } \, dx\\
   &= \int \dfrac{ A }{ x - 3 } \, dx + \int \dfrac{ B }{ x + 4 } \, dx\\
   &= \int \dfrac{ 13/7 }{ x - 3 } \, dx + \int \dfrac{ 22/7 }{ x + 4 } \, dx\\
   &= \dfrac{13}{7} \int \dfrac{ 1 }{ x - 3 } \, dx + \dfrac{22}{7} \int \dfrac{ 1 }{ x + 4 } \, dx\\
   &= \dfrac{13}{7} \ln|x - 3 | + \dfrac{22}{7} \ln| x + 4| + C\\
\end{align}
$$
:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2c

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{8x + 11}{x^2 - 5x + 6} \, dx = -27 \ln|x - 2 | + 35 \ln| x - 3| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{8x + 11}{x^2 - 5x + 6} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{8x + 11}{(x - 2)(x - 3)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x - 3 } \\
    &= \dfrac{ A(x - 3) }{ (x - 2 ) (x - 3) } + \dfrac{ B(x - 2) }{ (x - 2 ) (x - 3) } \\
    &= \dfrac{ A(x - 3) + B(x - 2) }{ (x - 2) (x - 3) } \\
    &= \dfrac{ Ax - 3A + Bx - 2B }{ (x - 2) (x - 3) } \\
    &= \dfrac{ (A + B)x - 3A - 2B }{ (x - 2) (x - 3) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{8x + 11}{(x - 2)(x - 3)} = \dfrac{ (A + B)x - 3A - 2B }{ (x - 2) (x - 3) } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   8x + 11 = (A + B)x - 3A - 2B
$$

Hieruit volgt:

$$
\begin{align}
   A+B &= 8 \\
   -3A - 2B &= 11
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 8 - B \\
   -3(8 - B) - 2B &= 11 \\
   -24 + 3B - 2B &= 11 \\
   B &= 35 \\
\end{align}
$$

B invullen geeft:

$$
\begin{align}
   A &= 8 - 35 \\
   A &= -27
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{8x + 11}{x^2 - 5x + 6} \, dx & = \int \dfrac{8x + 11}{(x - 2)(x - 3)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ -27 }{ x - 2 } \, dx + \int \dfrac{ 35 }{ x - 3 } \, dx\\
   &= -27 \int \dfrac{ 1 }{ x - 2 } \, dx + 35 \int \dfrac{ 1 }{ x - 3 } \, dx\\
   &= -27 \ln|x - 2 | + 35 \ln| x - 3| + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{6x + 13}{x^2 + 2x - 15} \, dx = \dfrac{17}{8} \ln|x + 5 | + \dfrac{31}{8} \ln| x - 3| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{6x + 13}{x^2 + 2x - 15} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{6x + 13}{(x + 5)(x - 3)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 3 } \\
    &= \dfrac{ A(x - 3) }{ (x + 5 ) (x - 3) } + \dfrac{ B(x + 5) }{ (x + 5 ) (x - 3) } \\
    &= \dfrac{ A(x - 3) + B(x + 5) }{ (x + 5) (x - 3) } \\
    &= \dfrac{ Ax - 3A + Bx + 5B }{ (x + 5) (x - 3) } \\
    &= \dfrac{ (A + B)x - 3A + 5B }{ (x + 5) (x - 3) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{6x + 13}{(x + 5)(x - 3)} = \dfrac{ (A + B)x - 3A + 5B }{ (x + 5) (x - 3) } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   6x + 13 = (A + B)x - 3A + 5B
$$

Hieruit volgt:

$$
\begin{align}
   A+B &= 6 \\
   -3A + 5B &= 13
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 6 - B \\
   -3(6 - B) + 5B &= 13 \\
   -18 + 3B + 5B &= 13 \\
   8B &= 31 \\
   B &= \dfrac{31}{8}
\end{align}
$$

B invullen geeft:
$$

\begin{align}
   A &= 6 - \dfrac{31}{8} \\
   A &= \dfrac{48}{8} - \dfrac{31}{8} \\
   A &= \dfrac{17}{8}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{6x + 13}{x^2 + 2x - 15} \, dx & = \int \dfrac{6x + 13}{(x + 5)(x - 3)} \, dx\\
   &= \int \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ A }{ x + 5 } \, dx + \int \dfrac{ B }{ x - 3 } \, dx\\
   &= \int \dfrac{ 17/8 }{ x + 5 } \, dx + \int \dfrac{ 31/8 }{ x - 3 } \, dx\\
   &= \dfrac{17}{8} \int \dfrac{ 1 }{ x + 5 } \, dx + \dfrac{31}{8} \int \dfrac{ 1 }{ x - 3 } \, dx\\
   &= \dfrac{17}{8} \ln|x + 5 | + \dfrac{31}{8} \ln| x - 3| + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{10x + 19}{x^2 + 3x - 10} \, dx = \dfrac{31}{7} \ln|x + 5 | + \dfrac{39}{7} \ln| x - 2| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{10x + 19}{x^2 + 3x - 10} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{10x + 19}{(x + 5)(x - 2)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 2 } \\
    &= \dfrac{ A(x - 2) }{ (x + 5 ) (x - 2) } + \dfrac{ B(x + 5) }{ (x + 5 ) (x - 2) } \\
    &= \dfrac{ A(x - 2) + B(x + 5) }{ (x + 5) (x - 2) } \\
    &= \dfrac{ Ax - 2A + Bx + 5B }{ (x + 5) (x - 2) } \\
    &= \dfrac{ (A + B)x - 2A + 5B }{ (x + 5) (x - 2) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{10x + 19}{(x + 5)(x - 2)} = \dfrac{ (A + B)x - 2A + 5B }{ (x + 5) (x - 2) } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   10x + 19 = (A + B)x - 2A + 5B
$$

Hieruit volgt:

$$
\begin{align}
   A+B &= 10 \\
   -2A + 5B &= 19
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 10 - B \\
   -2(10 - B) + 5B &= 19 \\
   -20 + 2B + 5B &= 19 \\
   7B &= 39 \\
   B &= \dfrac{39}{7}
\end{align}
$$

B invullen geeft:

$$
\begin{align}
   A &= 10 - \dfrac{39}{7} \\
   A &= \dfrac{70}{7} - \dfrac{39}{7} \\
   A &= \dfrac{31}{7}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{10x + 19}{x^2 + 3x - 10} \, dx & = \int \dfrac{10x + 19}{(x + 5)(x - 2)} \, dx\\
   &= \int \dfrac{ A }{ x + 5 } + \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ A }{ x + 5 } \, dx + \int \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ 31/7 }{ x + 5 } \, dx + \int \dfrac{ 39/7 }{ x - 2 } \, dx\\
   &= \dfrac{31}{7} \int \dfrac{ 1 }{ x + 5 } \, dx + \dfrac{39}{7} \int \dfrac{ 1 }{ x - 2 } \, dx\\
   &= \dfrac{31}{7} \ln|x + 5 | + \dfrac{39}{7} \ln| x - 2| + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{4x + 9}{x^2 + 5x + 6} \, dx = \ln|x + 2 | + 3\ln| x + 3| + C\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
\int \dfrac{4x + 9}{x^2 + 5x + 6} \, dx
$$

De teller ontbinden in factoren:

$$
\int \dfrac{4x + 9}{(x + 2)(x + 3)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
&= \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 3 } \\
&= \dfrac{ A(x + 3) }{ (x + 2 ) (x + 3) } + \dfrac{ B(x + 2) }{ (x + 2 ) (x + 3) } \\
&= \dfrac{ A(x + 3) + B(x + 2) }{ (x + 2) (x + 3) } \\
&= \dfrac{ Ax + 3A + Bx + 2B }{ (x + 2) (x + 3) } \\
&= \dfrac{ (A + B)x + 3A + 2B }{ (x + 2) (x + 3) } \
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
\dfrac{4x + 9}{(x + 2)(x + 3)} = \dfrac{ (A + B)x + 3A + 2B }{ (x + 2) (x + 3) }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
4x + 9 = (A + B)x + 3A + 2B
$$

Hieruit volgt:

$$
\begin{align}
A+B &= 4 \\
3A + 2B &= 9
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
A &= 4 - B \\
3(4 - B) + 2B &= 9 \\
12 - 3B + 2B &= 9 \\
-B &= -3 \\
B &= 3
\end{align}
$$

B invullen geeft:

$$
\begin{align}
A &= 4 - 3 \\
A &= 1
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
\int \dfrac{4x + 9}{x^2 + 5x + 6} , dx & = \int \dfrac{4x + 9}{(x + 2)(x + 3)} , dx\\
&= \int \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 3 } , dx\\
&= \int \dfrac{ A }{ x + 2 } , dx + \int \dfrac{ B }{ x + 3 } , dx\\
&= \int \dfrac{ 1 }{ x + 2 } , dx + \int \dfrac{ 3 }{ x + 3 } , dx\\
&= \int \dfrac{ 1 }{ x + 2 } , dx + 3 \int \dfrac{ 1 }{ x + 3 } , dx\\
&= \ln|x + 2 | + 3\ln| x + 3| + C\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{3x + 5}{x^2 + 7x + 10} \, dx = -\dfrac{1}{3} \ln|x + 2 | + \dfrac{10}{3} \ln| x + 5| + C
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
\int \dfrac{3x + 5}{x^2 + 7x + 10} \, dx
$$

De teller ontbinden in factoren:

$$
\int \dfrac{3x + 5}{(x + 2)(x + 5)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
&= \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 5 } \\
&= \dfrac{ A(x + 5) }{ (x + 2 ) (x + 5) } + \dfrac{ B(x + 2) }{ (x + 2 ) (x + 5) } \\
&= \dfrac{ A(x + 5) + B(x + 2) }{ (x + 2) (x + 5) } \\
&= \dfrac{ Ax + 5A + Bx + 2B }{ (x + 2) (x + 5) } \\
&= \dfrac{ (A + B)x + 5A + 2B }{ (x + 2) (x + 5) }
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
\dfrac{3x + 5}{(x + 2)(x + 5)} = \dfrac{ (A + B)x + 5A + 2B }{ (x + 2) (x + 5) }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
3x + 5 = (A + B)x + 5A + 2B
$$

Hieruit volgt:

$$
\begin{align}
A+B &= 3 \\
5A + 2B &= 5
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
A &= 3 - B \\
5(3 - B) + 2B &= 5 \\
15 - 5B + 2B &= 5 \\
-3B &= -10 \\
B &= \dfrac{10}{3}
\end{align}
$$

B invullen geeft:

$$
\begin{align}
A &= 3 - \dfrac{10}{3} \\
A &= \dfrac{9}{3} - \dfrac{10}{3} \\
A &= -\dfrac{1}{3}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
\int \dfrac{3x + 5}{x^2 + 7x + 10} \, dx & = \int \dfrac{3x + 5}{(x + 2)(x + 5)} \, dx\\
&= \int \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 5 } \, dx\\
&= \int \dfrac{ -1/3 }{ x + 2 } \, dx + \int \dfrac{ 10/3 }{ x + 5 } \, dx\\
&= -\dfrac{1}{3} \int \dfrac{ 1 }{ x + 2 } \, dx + \dfrac{10}{3} \int \dfrac{ 1 }{ x + 5 } \, dx\\
&= -\dfrac{1}{3} \ln|x + 2 | + \dfrac{10}{3} \ln| x + 5| + C
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{5x + 4}{x^2 + 6x + 8} \, dx = -3 \ln|x + 2 | + 8\ln| x + 4| + C\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
\int \dfrac{5x + 4}{x^2 + 6x + 8} \, dx
$$

De teller ontbinden in factoren:

$$
\int \dfrac{5x + 4}{(x + 2)(x + 4)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
&= \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 4 } \\
&= \dfrac{ A(x + 4) }{ (x + 2 ) (x + 4) } + \dfrac{ B(x + 2) }{ (x + 2 ) (x + 4) } \\
&= \dfrac{ A(x + 4) + B(x + 2) }{ (x + 2) (x + 4) } \\
&= \dfrac{ Ax + 4A + Bx + 2B }{ (x + 2) (x + 4) } \\
&= \dfrac{ (A + B)x + 4A + 2B }{ (x + 2) (x + 4) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
\dfrac{5x + 4}{(x + 2)(x + 4)} = \dfrac{ (A + B)x + 4A + 2B }{ (x + 2) (x + 4) }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
5x + 4 = (A + B)x + 4A + 2B
$$

Hieruit volgt:

$$
\begin{align}
A+B &= 5 \\
4A + 2B &= 4
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
A &= 5 - B \\
4(5 - B) + 2B &= 4 \\
20 - 4B + 2B &= 4 \\
-2B &= -16 \\
B &= 8
\end{align}
$$

B invullen geeft:

$$
\begin{align}
A &= 5 - 8 \\
A &= -3
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
\int \dfrac{5x + 4}{x^2 + 6x + 8} \, dx & = \int \dfrac{5x + 4}{(x + 2)(x + 4)} \, dx\\
&= \int \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 4 } \, dx\\
&= \int \dfrac{ -3 }{ x + 2 } \, dx + \int \dfrac{ 8 }{ x + 4 } \, dx\\
&= -3 \int \dfrac{ 1 }{ x + 2 } \, dx + 8 \int \dfrac{ 1 }{ x + 4 } \, dx\\
&= -3 \ln|x + 2 | + 8\ln| x + 4| + C\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">


## Opgave 6.3.2i

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{-5x + 6}{x^2 + 6x + 8} \, dx = 8 \ln|x + 2 | - 13\ln| x + 4| + C\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
\int \dfrac{-5x + 6}{x^2 + 6x + 8} \, dx
$$

De teller ontbinden in factoren:

$$
\int \dfrac{-5x + 6}{(x + 2)(x + 4)} \ dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
&= \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 4 } \\
&= \dfrac{ A(x + 4) }{ (x + 2 ) (x + 4) } + \dfrac{ B(x + 2) }{ (x + 2 ) (x + 4) } \\
&= \dfrac{ A(x + 4) + B(x + 2) }{ (x + 2) (x + 4) } \\
&= \dfrac{ Ax + 4A + Bx + 2B }{ (x + 2) (x + 4) } \\
&= \dfrac{ (A + B)x + 4A + 2B }{ (x + 2) (x + 4) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
\dfrac{-5x + 6}{(x + 2)(x + 4)} = \dfrac{ (A + B)x + 4A + 2B }{ (x + 2) (x + 4) }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
-5x + 6 = (A + B)x + 4A + 2B
$$

Hieruit volgt:

$$
\begin{align}
A+B &= -5 \\
4A + 2B &= 6
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
A &= -5 - B \\
4(-5 - B) + 2B &= 6 \\
-20 - 4B + 2B &= 6 \\
-2B &= 26 \\
B &= -13
\end{align}
$$

B invullen geeft:

$$
\begin{align}
A &= -5 - (-13) \\
A &= -5 + 13 \\
A &= 8
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
\int \dfrac{-5x + 6}{x^2 + 6x + 8} \, dx & = \int \dfrac{-5x + 6}{(x + 2)(x + 4)} \, dx\\
&= \int \dfrac{ A }{ x + 2 } + \dfrac{ B }{ x + 4 } \, dx\\
&= \int \dfrac{ A }{ x + 2 } \, dx + \int \dfrac{ B }{ x + 4 } \, dx\\
&= \int \dfrac{ 8 }{ x + 2 } \, dx + \int \dfrac{ -13 }{ x + 4 } \, dx\\
&= 8 \int \dfrac{ 1 }{ x + 2 } \, dx - 13 \int \dfrac{ 1 }{ x + 4 } \, dx\\
&= 8 \ln|x + 2 | - 13\ln| x + 4| + C
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.2j

::::{admonition} Antwoord
:class: important, dropdown

$$
\int \dfrac{7x - 1}{x^2 + 3x - 10} \, dx = \dfrac{13}{7} \ln|x - 2 | + \dfrac{36}{7} \ln| x + 5| + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
\int \dfrac{7x - 1}{x^2 + 3x - 10} \, dx
$$

De teller ontbinden in factoren:

$$
\int \dfrac{7x - 1}{(x - 2)(x + 5)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
&= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 5 } \\
&= \dfrac{ A(x + 5) }{ (x - 2 ) (x + 5) } + \dfrac{ B(x - 2) }{ (x - 2 ) (x + 5) } \\
&= \dfrac{ A(x + 5) + B(x - 2) }{ (x - 2) (x + 5) } \\
&= \dfrac{ Ax + 5A + Bx - 2B }{ (x - 2) (x + 5) } \\
&= \dfrac{ (A + B)x + 5A - 2B }{ (x - 2) (x + 5) } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
\dfrac{7x - 1}{(x - 2)(x + 5)} = \dfrac{ (A + B)x + 5A - 2B }{ (x - 2) (x + 5) }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
7x - 1 = (A + B)x + 5A - 2B
$$

Hieruit volgt:

$$
\begin{align}
A+B &= 7 \\
5A - 2B &= -1
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
A &= 7 - B \\
5(7 - B) - 2B &= -1 \\
35 - 5B - 2B &= -1 \\
-7B &= -36 \\
B &= \dfrac{36}{7}
\end{align}
$$

B invullen geeft:

$$
\begin{align}
A &= 7 - \dfrac{36}{7} \\
A &= \dfrac{49}{7} - \dfrac{36}{7} \\
A &= \dfrac{13}{7}
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
\int \dfrac{7x - 1}{x^2 + 3x - 10} \, dx & = \int \dfrac{7x - 1}{(x - 2)(x + 5)} \, dx\\
&= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ x + 5 } \, dx\\
&= \int \dfrac{ 13/7 }{ x - 2 } \, dx + \int \dfrac{ 36/7 }{ x + 5 } \, dx\\
&= \dfrac{13}{7} \int \dfrac{ 1 }{ x - 2 } \, dx + \dfrac{36}{7} \int \dfrac{ 1 }{ x + 5 } \, dx\\
&= \dfrac{13}{7} \ln|x - 2 | + \dfrac{36}{7} \ln| x + 5| + C\\
\end{align}
$$

:::
::::

## Opgave 6.3.3a

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{4x + 7}{x^2 + 6x + 9} \, dx = 4\ln|x + 3 | + \dfrac{5}{x + 3} + C
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{4x + 7}{x^2 + 6x + 9} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{4x + 7}{(x + 3)(x + 3)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align*}
&= \dfrac{ A }{ x + 3 } + \dfrac{ B }{ (x + 3)^2 } \\
&= \dfrac{ A(x + 3) }{ (x + 3) (x + 3) } + \dfrac{ B }{ (x + 3 )^2 } \\
&= \dfrac{ A(x + 3) + B }{ (x + 3)^2 } \\
&= \dfrac{ Ax + 3A + B  }{ (x + 3)^2 } \\
&= \dfrac{ Ax + 3A + B }{ (x + 3)^2 } \\
\end{align*}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{4x + 7}{(x + 3)^2} = \dfrac{ Ax + 3A + B }{ (x + 3)^2 }
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
    4x  + 7 = Ax + 3A + B
$$

Hieruit volgt:

$$
\begin{align*}
A &= 4 \\
3A + B &= 7
\end{align*}
$$

Oplossen en substitueren geeft:

$$
\begin{align*}
A &= 4\\
3 \cdot 4 + B &= 7 \\
12 + B &= 7 \\
B &= -5
\end{align*}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align*}
\int \dfrac{4x + 7}{x^2 + 6x + 9} \, dx & = \int \dfrac{4x + 7}{(x + 3)(x + 3)} \, dx\\
&= \int \dfrac{ A }{ x + 3 } + \dfrac{ B }{ (x + 3)^2 } \, dx\\
&= \int \dfrac{ A }{ x + 3 } \, dx + \int \dfrac{ B }{ (x + 3)^2 } \, dx\\
&= \int \dfrac{ 4 }{ x + 3 } \, dx + \int \dfrac{ -5 }{ (x + 3)^2 } \, dx\\
&= 4 \int \dfrac{ 1 }{ x + 3 } \, dx - 5 \int \dfrac{ 1 }{ (x + 3)^2 } \, dx\\
&= 4\ln|x + 3 | + \dfrac{5}{x + 3} + C\
\end{align*}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3b

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{3x - 5}{x^2 - 4x + 4} \, dx = 3\ln|x - 2 | - \dfrac{1}{x - 2} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{3x - 5}{x^2 - 4x + 4} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{3x - 5}{(x - 2)(x - 2)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ (x - 2)^2 } \\
    &= \dfrac{ A(x - 2) }{ (x - 2) (x - 2) } + \dfrac{ B }{ (x - 2 )^2 } \\
    &= \dfrac{ A(x - 2) + B }{ (x - 2)^2 } \\
    &= \dfrac{ Ax - 2A + B  }{ (x - 2)^2 } \\
    &= \dfrac{ Ax - 2A + B }{ (x - 2)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{3x - 5}{(x - 2)^2} = \dfrac{ Ax - 2A + B }{ (x - 2)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   3x  - 5 = Ax - 2A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= 3 \\
   -2A + B &= -5
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 3\\
   -2 \cdot 3 + B &= -5 \\
   -6 + B &= -5 \\
   B &= 1
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{3x - 5}{x^2 - 4x + 4} \, dx & = \int \dfrac{3x - 5}{(x - 2)(x - 2)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ (x - 2)^2 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ (x - 2)^2 } \, dx\\
   &= \int \dfrac{ 3 }{ x - 2 } \, dx + \int \dfrac{ 1 }{ (x - 2)^2 } \, dx\\
   &= 3 \int \dfrac{ 1 }{ x - 2 } \, dx + \int \dfrac{ 1 }{ (x - 2)^2 } \, dx\\
   &= 3\ln|x - 2 | - \dfrac{1}{x - 2} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3c

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{-2x + 9}{x^2 + 8x + 16} \, dx = -2\ln|x + 4 | - \dfrac{17}{x + 4} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{-2x + 9}{x^2 + 8x + 16} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{-2x + 9}{(x + 4)(x + 4)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x + 4 } + \dfrac{ B }{ (x + 4)^2 } \\
    &= \dfrac{ A(x + 4) }{ (x + 4) (x + 4) } + \dfrac{ B }{ (x + 4 )^2 } \\
    &= \dfrac{ A(x + 4) + B }{ (x + 4)^2 } \\
    &= \dfrac{ Ax + 4A + B  }{ (x + 4)^2 } \\
    &= \dfrac{ Ax + 4A + B }{ (x + 4)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{-2x + 9}{(x + 4)^2} = \dfrac{ Ax + 4A + B }{ (x + 4)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   -2x+9 = Ax + 4A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= -2 \\
   4A + B &= 9
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= -2\\
   4 \cdot -2 + B &= 9 \\
   -8 + B &= 9 \\
   B &= 17
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{-2x + 9}{x^2 + 8x + 16} \, dx & = \int \dfrac{-2x + 9}{(x + 4)(x + 4)} \, dx\\
   &= \int \dfrac{ A }{ x + 4 } + \dfrac{ B }{ (x + 4)^2 } \, dx\\
   &= \int \dfrac{ A }{ x + 4 } \, dx + \int \dfrac{ B }{ (x + 4)^2 } \, dx\\
   &= \int \dfrac{ -2 }{ x + 4 } \, dx + \int \dfrac{ 17 }{ (x + 4)^2 } \, dx\\
   &= -2 \int \dfrac{ 1 }{ x + 4 } \, dx + 17 \int \dfrac{ 1 }{ (x + 4)^2 } \, dx\\
   &= -2\ln|x + 4 | - \dfrac{17}{x + 4} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3d

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{5x - 6}{x^2 - 2x + 1} \, dx = 5\ln|x - 1 | - \dfrac{1}{x - 1} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{5x - 6}{x^2 - 2x + 1} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{5x - 6}{(x - 1)(x - 1)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 1 } + \dfrac{ B }{ (x - 1)^2 } \\
    &= \dfrac{ A(x - 1) }{ (x - 1) (x - 1) } + \dfrac{ B }{ (x - 1 )^2 } \\
    &= \dfrac{ A(x - 1) + B }{ (x - 1)^2 } \\
    &= \dfrac{ Ax - A + B  }{ (x - 1)^2 } \\
    &= \dfrac{ Ax - A + B }{ (x - 1)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{5x - 6}{(x - 1)^2} = \dfrac{ Ax - A + B }{ (x - 1)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   5x-6 = Ax - A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= 5 \\
   -A + B &= -6
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 5\\
   -5 + B &= -6 \\
   B &= -1
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{5x - 6}{x^2 - 2x + 1} \, dx & = \int \dfrac{5x - 6}{(x - 1)(x - 1)} \, dx\\
   &= \int \dfrac{ A }{ x - 1 } + \dfrac{ B }{ (x - 1)^2 } \, dx\\
   &= \int \dfrac{ A }{ x - 1 } \, dx + \int \dfrac{ B }{ (x - 1)^2 } \, dx\\
   &= \int \dfrac{ 5 }{ x - 1 } \, dx + \int \dfrac{ -1 }{ (x - 1)^2 } \, dx\\
   &= 5 \int \dfrac{ 1 }{ x - 1 } \, dx - \int \dfrac{ 1 }{ (x - 1)^2 } \, dx\\
   &= 5\ln|x - 1 | + \dfrac{1}{x - 1} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3e

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{-3x + 8}{x^2 + 2x + 1} \, dx = -3\ln|x + 1 | + \dfrac{11}{x + 1} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{-3x + 8}{x^2 + 2x + 1} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{-3x + 8}{(x + 1)(x + 1)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \\
    &= \dfrac{ A(x + 1) }{ (x + 1) (x + 1) } + \dfrac{ B }{ (x + 1 )^2 } \\
    &= \dfrac{ A(x + 1) + B }{ (x + 1)^2 } \\
    &= \dfrac{ Ax + A + B  }{ (x + 1)^2 } \\
    &= \dfrac{ Ax + A + B }{ (x + 1)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{-3x + 8}{(x + 1)^2} = \dfrac{ Ax + A + B }{ (x + 1)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   -3x+8 = Ax + A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= -3 \\
   A + B &= 8
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= -3\\
   -3 + B &= 8 \\
   B &= 11
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{-3x + 8}{x^2 + 2x + 1} \, dx & = \int \dfrac{-3x + 8}{(x + 1)(x + 1)} \, dx\\
   &= \int \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int \dfrac{ A }{ x + 1 } \, dx + \int \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int \dfrac{ -3 }{ x + 1 } \, dx + \int \dfrac{ 11 }{ (x + 1)^2 } \, dx\\
   &= -3 \int \dfrac{ 1 }{ x + 1 } \, dx + 11 \int \dfrac{ 1 }{ (x + 1)^2 } \, dx\\
   &= -3\ln|x + 1 | - \dfrac{11}{x + 1} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3f

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{7x + 3}{x^2 - 6x + 9} \, dx = 7\ln|x - 3 | - \dfrac{18}{x - 3} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{7x + 3}{x^2 - 6x + 9} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{7x + 3}{(x - 3)(x - 3)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 3 } + \dfrac{ B }{ (x - 3)^2 } \\
    &= \dfrac{ A(x - 3) }{ (x - 3) (x - 3) } + \dfrac{ B }{ (x - 3 )^2 } \\
    &= \dfrac{ A(x - 3) + B }{ (x - 3)^2 } \\
    &= \dfrac{ Ax - 3A + B  }{ (x - 3)^2 } \\
    &= \dfrac{ Ax - 3A + B }{ (x - 3)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{7x + 3}{(x - 3)^2} = \dfrac{ Ax - 3A + B }{ (x - 3)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   7x+3 = Ax - 3A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= 7 \\
   -3A + B &= 3
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 7\\
   -21 + B &= 3 \\
   B &= 24
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{7x + 3}{x^2 - 6x + 9} \, dx & = \int \dfrac{7x + 3}{(x - 3)(x - 3)} \, dx\\
   &= \int \dfrac{ A }{ x - 3 } + \dfrac{ B }{ (x - 3)^2 } \, dx\\
   &= \int \dfrac{ A }{ x - 3 } \, dx + \int \dfrac{ B }{ (x - 3)^2 } \, dx\\
   &= \int \dfrac{ 7 }{ x - 3 } \, dx + \int \dfrac{ 24 }{ (x - 3)^2 } \, dx\\
   &= 7 \int \dfrac{ 1 }{ x - 3 } \, dx + 24 \int \dfrac{ 1 }{ (x - 3)^2 } \, dx\\
   &= 7\ln|x - 3 | - \dfrac{24}{x - 3} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3g

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{6x - 5}{x^2 + 10x + 25} \, dx = 6\ln|x + 5 | + \dfrac{35}{x + 5} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{6x - 5}{x^2 + 10x + 25} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{6x - 5}{(x + 5)(x + 5)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x + 5 } + \dfrac{ B }{ (x + 5)^2 } \\
    &= \dfrac{ A(x + 5) }{ (x + 5) (x + 5) } + \dfrac{ B }{ (x + 5 )^2 } \\
    &= \dfrac{ A(x + 5) + B }{ (x + 5)^2 } \\
    &= \dfrac{ Ax + 5A + B  }{ (x + 5)^2 } \\
    &= \dfrac{ Ax + 5A + B }{ (x + 5)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{6x - 5}{(x + 5)^2} = \dfrac{ Ax + 5A + B }{ (x + 5)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   6x-5 = Ax + 5A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= 6 \\
   5A + B &= -5
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= 6\\
   30 + B &= -5 \\
   B &= -35
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{6x - 5}{x^2 + 10x + 25} \, dx & = \int \dfrac{6x - 5}{(x + 5)(x + 5)} \, dx\\
   &= \int \dfrac{ A }{ x + 5 } + \dfrac{ B }{ (x + 5)^2 } \, dx\\
   &= \int \dfrac{ A }{ x + 5 } \, dx + \int \dfrac{ B }{ (x + 5)^2 } \, dx\\
   &= \int \dfrac{ 6 }{ x + 5 } \, dx + \int \dfrac{ -35 }{ (x + 5)^2 } \, dx\\
   &= 6 \int \dfrac{ 1 }{ x + 5 } \, dx - 35 \int \dfrac{ 1 }{ (x + 5)^2 } \, dx\\
   &= 6\ln|x + 5 | + \dfrac{35}{x + 5} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

## Opgave 6.3.3h

::::{admonition} Antwoord
:class: important, dropdown

$$
    \int \dfrac{-4x + 1}{x^2 - 4x + 4} \, dx = -4\ln|x - 2 | - \dfrac{7}{x - 2} + C\\
$$

:::{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:

$$
    \int \dfrac{-4x + 1}{x^2 - 4x + 4} \, dx
$$

De teller ontbinden in factoren:

$$
    \int \dfrac{-4x + 1}{(x - 2)(x - 2)} \, dx
$$

Toepassen van de regel voor breukensplitsen geeft:

$$
\begin{align}
    &= \dfrac{ A }{ x - 2 } + \dfrac{ B }{ (x - 2)^2 } \\
    &= \dfrac{ A(x - 2) }{ (x - 2) (x - 2) } + \dfrac{ B }{ (x - 2 )^2 } \\
    &= \dfrac{ A(x - 2) + B }{ (x - 2)^2 } \\
    &= \dfrac{ Ax - 2A + B  }{ (x - 2)^2 } \\
    &= \dfrac{ Ax - 2A + B }{ (x - 2)^2 } \\
\end{align}
$$

Gelijk stellen aan elkaar geeft:

$$
    \dfrac{-4x + 1}{(x - 2)^2} = \dfrac{ Ax - 2A + B }{ (x - 2)^2 } 
$$

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.

$$
   -4x+1 = Ax - 2A + B
$$

Hieruit volgt:

$$
\begin{align}
   A &= -4 \\
   -2A + B &= 1
\end{align}
$$

Oplossen en substitueren geeft:

$$
\begin{align}
   A &= -4\\
   -2(-4) + B &= 1 \\
   8 + B &= 1 \\
   B &= -7
\end{align}
$$

A en B invullen in de integraal en oplossen geeft:

$$
\begin{align}
   \int \dfrac{-4x + 1}{x^2 - 4x + 4} \, dx & = \int \dfrac{-4x + 1}{(x - 2)(x - 2)} \, dx\\
   &= \int \dfrac{ A }{ x - 2 } + \dfrac{ B }{ (x - 2)^2 } \, dx\\
   &= \int \dfrac{ A }{ x - 2 } \, dx + \int \dfrac{ B }{ (x - 2)^2 } \, dx\\
   &= \int \dfrac{ -4 }{ x - 2 } \, dx + \int \dfrac{ -7 }{ (x - 2)^2 } \, dx\\
   &= -4 \int \dfrac{ 1 }{ x - 2 } \, dx - 7 \int \dfrac{ 1 }{ (x - 2)^2 } \, dx\\
   &= -4\\ln|x - 2 | + \dfrac{7}{x - 2} + C\\
\end{align}
$$

:::
::::

<hr style="border:1px solid #9EA700">

