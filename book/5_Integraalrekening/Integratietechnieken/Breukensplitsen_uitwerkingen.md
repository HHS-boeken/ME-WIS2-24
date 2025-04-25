# 6.3 Uitwerkingen

<hr style="border:2px solid #9EA700">

### Opgave 6.3.1a

````{admonition} Antwoord
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:  
\begin{align}
\int \frac{7x + 1}{x^2 - 4} \, dx
\end{align}

De noemer ontbinden in factoren:  
\begin{align}
\int \frac{7x + 1}{(x - 2)(x + 2)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:  
\begin{align}
= \frac{A}{x - 2} + \frac{B}{x + 2}
\end{align}
\begin{align}
= \frac{A(x + 2) + B(x - 2)}{(x - 2)(x + 2)}
\end{align}
\begin{align}
= \frac{(A + B)x + (2A - 2B)}{(x - 2)(x + 2)}
\end{align}

Gelijkstellen van tellers:  
\begin{align}
7x + 1 = (A + B)x + (2A - 2B)
\end{align}

Stelsel opstellen:  
\begin{align}
A + B = 7 \\
2A - 2B = 1
\end{align}

Oplossen:  
\begin{align}
A = 4, \quad B = 3
\end{align}

Substitueren:  
\begin{align}
\int \frac{7x + 1}{x^2 - 4} \, dx = \int \frac{4}{x - 2} \, dx + \int \frac{3}{x + 2} \, dx
\end{align}
\begin{align}
= 4 \ln|x - 2| + 3 \ln|x + 2| + C
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