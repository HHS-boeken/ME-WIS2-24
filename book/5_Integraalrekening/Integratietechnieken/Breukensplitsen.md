# 6.3 Breukensplitsen

````{admonition} Theorie: Breukensplitsen
:class: tip, dropdown open

Breukensplitsen gebruik je bij het berekenen van primitieve van **gebroken functies**.

Het gaat dan om integralen van de vorm:

\begin{align*}
    \int \dfrac{\text{veelterm}}{\text{veelterm}} \, dx
\end{align*}

Het idee is dat je de breuk herschrijft als een som van eenvoudigere breuken. Die losse breuken kun je daarna apart primitiveren.

---

## Wanneer gebruik je breukensplitsen?

Je gebruikt breukensplitsen als:
- de teller en noemer uit veeltermen bestaan
- de noemer ontbonden kan worden in factoren
- de losse breuken daarna eenvoudiger te primitiveren zijn

Let daarbij op het volgende:
- Is de **graad van de teller kleiner** dan de graad van de noemer, dan kun je direct beginnen met breukensplitsen
- Is de **graad van de teller groter dan of gelijk aan** de graad van de noemer, dan moet je **eerst een staartdeling** uitvoeren

---

## Stappenplan bij breukensplitsen

### Situatie 1: noemer heeft twee verschillende lineaire factoren

Bijvoorbeeld:

\begin{align*}
    \dfrac{ax+b}{(x-p)(x-q)}
\end{align*}

Dan schrijf je:

\begin{align*}
    \dfrac{ax+b}{(x-p)(x-q)} = \dfrac{A}{x-p} + \dfrac{B}{x-q}
\end{align*}

Daarna werk je de rechterkant uit tot één breuk en stel je de tellers aan elkaar gelijk. Zo kun je $A$ en $B$ berekenen.

Als je $A$ en $B$ hebt gevonden, vul je deze weer in en primitiveer je beide losse breuken apart.

---

### Situatie 2: noemer heeft een dubbele factor

Bijvoorbeeld:

\begin{align*}
    \dfrac{ax+b}{(x-p)^2}
\end{align*}

Dan schrijf je:

\begin{align*}
    \dfrac{ax+b}{(x-p)^2} = \dfrac{A}{x-p} + \dfrac{B}{(x-p)^2}
\end{align*}

Ook hier werk je de rechterkant uit tot één breuk en stel je daarna de tellers aan elkaar gelijk. Zo bereken je $A$ en $B$.

Daarna primitiveer je beide losse breuken apart.

---

### Situatie 3: teller groter dan noemer

Als de teller groter is dan de noemer, dan kun je niet direct breukensplitsen.

Je begint dan met een **staartdeling**. Daarmee schrijf je de breuk als:

\begin{align*}
    \dfrac{\text{teller}}{\text{noemer}} = \text{veelterm} + \dfrac{\text{rest}}{\text{noemer}}
\end{align*}

De veelterm primitiveer je direct.  
De overgebleven breuk splits je daarna verder met breukensplitsen.

---

## Waar moet je op letten?

- Ontbind de noemer eerst volledig in factoren
- Schrijf de juiste vorm van de breuksplitsing op
- Werk de rechterkant netjes uit tot één breuk
- Noemers zijn gelijk, dus daarna moeten de tellers ook gelijk zijn
- Vergelijk de coëfficiënten bij de teller om de onbekenden te vinden
- Primitiveer daarna elke losse term apart

---

## Handige standaardvormen

Bij deze paragraaf gebruik je vooral:

\begin{align*}
    \dfrac{ax+b}{(x-p)(x-q)} &= \dfrac{A}{x-p} + \dfrac{B}{x-q} \\
    \dfrac{ax+b}{(x-p)^2} &= \dfrac{A}{x-p} + \dfrac{B}{(x-p)^2}
\end{align*}

En als de teller groter is dan de noemer:

\begin{align*}
    \dfrac{\text{teller}}{\text{noemer}} = \text{staartdeling} + \text{breukensplitsing}
\end{align*}

---

## Primitiveer daarna de losse breuken

Na het splitsen ontstaan breuken zoals:

\begin{align*}
    \int \dfrac{1}{x-a} \, dx
\end{align*}

en

\begin{align*}
    \int \dfrac{1}{(x-a)^2} \, dx
\end{align*}

Deze kun je primitiveren met de standaardregels.

---
````



## 6.3.1 Noemer is lineair

## 6.3.2 Noemer is kwadratisch ($b^2-4ac > 0$)

````{admonition} Voorbeeld 1: 
:class: dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{2x-1}{x^2+4x+3} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align*}
    \int \dfrac{2x-1}{(x+1)(x+3)} \, dx
\end{align*}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align*}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ x + 3 } \\
    &= \dfrac{ A(x + 3) }{ (x + 1) (x + 3) } + \dfrac{ B(x + 1) }{ (x + 1 ) (x + 3) } \\
    &= \dfrac{ A(x + 3) + B(x + 1) }{ (x + 1) (x + 3) } \\
    &= \dfrac{ Ax + 3A + Bx + 1B }{ (x + 1) (x + 3) } \\
    &= \dfrac{ (A + B)x + 3A + 1B }{ (x + 1) (x + 3) } \\
\end{align*}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{2x-1}{(x+1)(x+3)} = \dfrac{ (A + B)x + 3A + 1B }{ (x + 1) (x + 3) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   2x-1 = (A + B)x + 3A + 1B
\end{align}

Hieruit volgt:
\begin{align*}
   A+B &= 2 \\
   3A + B &= -1
\end{align*}

Oplossen en substitueren geeft:
\begin{align*}
   A &= 2 -B \\
   3(2-B) + B &= -1 \\
   6-3B +B &= -1 \\
   6-2B &= -1 \\
   -2B &=-7 \\
   B &= \dfrac{7}{2}
\end{align*}

B invullen geeft:
\begin{align*}
   A &= 2 -B \\
   A &= 2 - \dfrac{7}{2} \\
   A &= -\dfrac{3}{2}
\end{align*}

A en B invullen in de integraal en oplossen geeft:
\begin{align*}
   \int \dfrac{2x-1}{x^2+4x+3} \, dx & = \int \dfrac{2x-1}{(x+1)(x+3)} \, dx\\
   &= \int \dfrac{ A }{ x + 1 } + \dfrac{ B }{ x + 3 } \, dx\\
   &= \int \dfrac{ A }{ x + 1 } \, dx + \int \dfrac{ B }{ x + 3 } \, dx\\
   &= \int \dfrac{ -\frac{3}{2} }{ x + 1 } \, dx + \int \dfrac{ \frac{7}{2} }{ x + 3 } \, dx\\
   &= -\frac{3}{2} \int \dfrac{ 1 }{ x + 1 } \, dx + \frac{7}{2} \int \dfrac{ 1 }{ x + 3 } \, dx\\
   &= -\frac{3}{2} \ln|x + 1 | + \frac{7}{2} \ln| x + 3 | + C\\
\end{align*}
````

````{admonition} Oefening 1
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
     \int \dfrac{9x+7}{x^2+x-6} \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{9x+7}{x^2+x-6} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{9x+7}{(x+3)(x-2)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 3 } + \dfrac{ B }{ x - 2 } \\
    &= \dfrac{ A(x - 2) }{ (x + 3 ) (x - 2) } + \dfrac{ B(x + 3) }{ (x + 3 ) (x - 2) } \\
    &= \dfrac{ A(x - 2) + B(x + 3) }{ (x + 3) (x - 2) } \\
    &= \dfrac{ Ax - 2A + Bx + 3B }{ (x + 3) (x - 2) } \\
    &= \dfrac{ (A + B)x -2A + 3B }{ (x + 3) (x - 2) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{9x + 7}{(x+3)(x-2)} = \dfrac{ (A + B)x - 2A + 3B }{ (x + 3) (x - 2) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   9x+7 = (A + B)x - 2A + 3B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= 9 \\
   -2A + 3B &= 7
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 9 - B \\
   -2(9-B) + 3B &= 7 \\
   -18 + 2B + 3B &= 7 \\
   5B &= 25 \\
   B &= 5
\end{align}

B invullen geeft:
\begin{align}
   A &= 9 - B \\
   A &= 9 - 5 \\
   A &= 4
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{9x+7}{x^2+x-6} \, dx & = \int \dfrac{9x+7}{(x+3)(x-2)} \, dx\\
   &= \int \dfrac{ A }{ x + 3 } + \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ A }{ x + 3 } \, dx + \int \dfrac{ B }{ x - 2 } \, dx\\
   &= \int \dfrac{ 4 }{ x + 3 } \, dx + \int \dfrac{ 5 }{ x - 2 } \, dx\\
   &= 4 \int \dfrac{ 1 }{ x + 3 } \, dx + 5 \int \dfrac{ 1 }{ x - 2 } \, dx\\
   &= 4 \ln|x + 3 | + 5 \ln| x - 2| + C\\
\end{align}
```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
     \int \dfrac{-6x+14}{x^2+2x-3} \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{-6x+14}{x^2+2x-3}  \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{-6x+14}{(x+3)(x-1)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 3 } + \dfrac{ B }{ x - 1 } \\
    &= \dfrac{ A(x - 1) }{ (x + 3 ) (x - 1) } + \dfrac{ B(x + 3) }{ (x + 3 ) (x - 1) } \\
    &= \dfrac{ A(x - 1) + B(x + 3) }{ (x + 3) (x - 1) } \\
    &= \dfrac{ Ax - A + Bx + 3B }{ (x + 3) (x - 1) } \\
    &= \dfrac{ (A + B)x -A + 3B }{ (x + 3) (x - 1) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{-6x + 14}{(x+3)(x-1)} = \dfrac{ (A + B)x - A + 3B }{ (x + 3) (x - 1) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   -6x+14 = (A + B)x - A + 3B
\end{align}

Hieruit volgt:
\begin{align}
   A+B &= -6 \\
   -A + 3B &= 14
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= -6 - B \\
   -1(-6-B) + 3B &= 14 \\
   6 + B + 3B &= 14 \\
   4B &= 8 \\
   B &= 2
\end{align}

B invullen geeft:
\begin{align}
   A &= -6 - 2 \\
   A &= -8
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{-6x+14}{x^2+2x-3} \, dx & = \int \dfrac{-6x+14}{(x + 3)(x - 1)} \, dx\\
   &= \int \dfrac{ A }{ x + 3 } + \dfrac{ B }{ x - 1 } \, dx\\
   &= \int \dfrac{ A }{ x + 3 } \, dx + \int \dfrac{ B }{ x - 1 } \, dx\\
   &= \int \dfrac{ -8 }{ x + 3 } \, dx + \int \dfrac{ 2 }{ x - 1 } \, dx\\
   &= -8 \int \dfrac{ 1 }{ x + 3 } \, dx + 2 \int \dfrac{ 1 }{ x - 1 } \, dx\\
   &= -8 \ln|x + 3 | + 2 \ln| x - 1| + C\\
\end{align}
```
````

## 6.3.3 Noemer is kwadratisch ($b^2-4ac = 0$)

````{admonition} Voorbeeld 2: 
:class: dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{2x + 5}{x^2 + 2x + 1} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{2x + 5}{(x + 1)(x + 1)} \, dx
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
    \dfrac{2x + 5}{(x+1)^2} = \dfrac{ Ax + A + B }{ (x + 1)^2 } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   2x  + 5 = Ax + A + B
\end{align}

Hieruit volgt:
\begin{align}
   A &= 2 \\
   A + B &= 5
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 2\\
   2 + B &= 5 \\
   B &= 3
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{2x + 5}{x^2 + 2x + 1} \, dx & = \int \dfrac{2x + 5}{(x+1)(x+1)} \, dx\\
   &= \int \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int \dfrac{ A }{ x + 1 } \, dx + \int \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int \dfrac{ 2 }{ x + 1 } \, dx + \int \dfrac{ 3 }{ (x + 1)^2 } \, dx\\
   &= 2 \int \dfrac{ 1 }{ x + 1 } \, dx + 3 \int \dfrac{ 1 }{ (x + 1)^2 } \, dx\\
   &= 2 \ln|x + 1 | - \frac{3}{ x + 1}  + C\\
\end{align}
````


````{admonition} Oefening 3
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{3x - 14}{x^2 - 8x + 16} \, dx
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{3x - 14}{x^2 - 8x + 16} \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{3x - 14 }{(x - 4)(x - 4)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x - 4 } + \dfrac{ B }{ (x - 4)^2 } \\
    &= \dfrac{ A(x - 4) }{ (x - 4) (x - 4) } + \dfrac{ B }{ (x - 4 )^2 } \\
    &= \dfrac{ A(x - 4) + B }{ (x - 4)^2 } \\
    &= \dfrac{ Ax - 4A + B  }{ (x - 4)^2 } \\
    &= \dfrac{ Ax - 4A + B }{ (x - 4)^2 } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{3x - 14}{(x - 4)^2} = \dfrac{ Ax - 4A + B }{ (x - 4)^2 } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   3x  - 14 = Ax - 4A + B
\end{align}

Hieruit volgt:
\begin{align}
   A &= 3 \\
   -4A + B &= -14
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 3\\
   -4 \cdot 3 + B &= -14 \\
   -12 + B &= -14 \\
   B &= -2
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{3x - 14}{x^2 - 8x + 16} \, dx & = \int \dfrac{3x - 14}{(x - 4)(x - 4)} \, dx\\
   &= \int \dfrac{ A }{ x - 4 } + \dfrac{ B }{ (x - 4)^2 } \, dx\\
   &= \int \dfrac{ A }{ x - 4 } \, dx + \int \dfrac{ B }{ (x - 4)^2 } \, dx\\
   &= \int \dfrac{ 3 }{ x - 4 } \, dx + \int \dfrac{ -2 }{ (x - 4)^2 } \, dx\\
   &= 3 \int \dfrac{ 1 }{ x - 4 } \, dx - 2 \int \dfrac{ 1 }{ (x - 4)^2 } \, dx\\
   &= 3 \ln|x - 4 | + \frac{2}{ x - 4}  + C\\
\end{align}
```
````

````{admonition} Oefening 4
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{2x - 1}{x^2 + 4x + 4 } \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown
Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{2x - 1}{x^2 + 4x + 4 } \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{2x - 1 }{(x + 2)(x + 2)} \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 2 } + \dfrac{ B }{ (x + 2)^2 } \\
    &= \dfrac{ A(x + 2) }{ (x + 2) (x + 2) } + \dfrac{ B }{ (x + 2 )^2 } \\
    &= \dfrac{ A(x + 2) + B }{ (x + 2)^2 } \\
    &= \dfrac{ Ax + 2A + B  }{ (x + 2)^2 } \\
    &= \dfrac{ Ax + 2A + B }{ (x + 2)^2 } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{2x - 1 }{(x + 2)^2} = \dfrac{ Ax + 2A + B }{ (x + 2)^2 } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   2x  - 1 = Ax + 2A + B
\end{align}

Hieruit volgt:
\begin{align}
   A &= 2 \\
   2A + B &= -1
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 2\\
   2 \cdot 2 + B &= -1 \\
   4 + B &= -1 \\
   B &= -5
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{2x - 1}{x^2 + 4x + 4} \, dx & = \int \dfrac{2x - 1}{(x + 2)(x + 2)} \, dx\\
   &= \int \dfrac{ A }{ x + 2 } + \dfrac{ B }{ (x + 2)^2 } \, dx\\
   &= \int \dfrac{ A }{ x + 2 } \, dx + \int \dfrac{ B }{ (x + 2)^2 } \, dx\\
   &= \int \dfrac{ 2 }{ x + 2 } \, dx + \int \dfrac{ -5 }{ (x + 2)^2 } \, dx\\
   &= 2 \int \dfrac{ 1 }{ x + 2 } \, dx - 5 \int \dfrac{ 1 }{ (x + 2)^2 } \, dx\\
   &= 2 \ln|x + 2 | + \frac{5}{ x + 2}  + C\\
\end{align}
```
````

## 6.3.4 Noemer is kwadratisch ($b^2-4ac < 0$)

````{admonition} Voorbeeld 3: 
:class: dropdown

Slaan we dit jaar `2024-2025` over.

````

````{admonition} Oefening 5
:class: important, dropdown

Slaan we dit jaar `2024-2025` over.

```{admonition} Uitwerking
:class: important, dropdown

Slaan we dit jaar `2024-2025` over.

```
````

````{admonition} Oefening 6
:class: important, dropdown

Slaan we dit jaar `2024-2025` over.

```{admonition} Uitwerking
:class: important, dropdown

Slaan we dit jaar `2024-2025` over.

```
````

## 6.3.5 Teller > Noemer 

````{admonition} Voorbeeld 4: 
:class: dropdown

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
````

````{admonition} Oefening 7
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{x^4 }{x^2 + 4x + 3}  \, dx
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{x^4 }{x^2 + 4x + 3}  \, dx
\end{align*}

De teller is groter dan de noemer, dus staartdeling maken.

\begin{align}
 x^2 + 4x + 3 \quad / &x^4 \quad \quad \quad \quad \quad \quad \quad \quad  \backslash \quad x^2 - 4x + 13\\
&x^4 + 4x^3 + 3x^2 \\
&------------- \quad -\\
&\quad \quad -4x^3 - 3x^2 \\
&\quad \quad -4x^3 - 16x^2 - 12x \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad  13x^2 + 12x \\
&\quad \quad \quad \quad \quad \quad  13x^2 + 52x + 39 \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad \quad \quad  -40x - 39 \\
\end{align}

De rest is $-40x-39$, dus de uiteindelijke uitkomst is:
\begin{align}
& x^2 - 4x + 13 + \dfrac{-40x-39}{x^2 + 4x + 3} = \\
& x^2 - 4x + 13 - \dfrac{40x + 39 }{x^2 + 4x + 3} \\
\end{align}

Dit geeft:
\begin{align}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &=  \int x^2 - 4x + 13 - \dfrac{40x + 39 }{x^2 + 4x + 3}  \, dx \\
\end{align}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{40x + 39 }{x^2 + 4x + 3}  \, dx
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 3) } \\
    &= \dfrac{ A(x + 3) }{ (x + 1) (x + 3) } + \dfrac{ B(x + 1) }{(x + 1) (x + 3 ) } \\
    &= \dfrac{ A(x + 3) + B(x + 1) }{ (x + 1)(x + 3) } \\
    &= \dfrac{ Ax + 3A + Bx + B  }{ (x + 1)(x + 3) } \\
    &= \dfrac{ (A + B)x + 3A + B }{ (x + 1)(x + 3) } \\
\end{align}

Gelijk stellen aan elkaar geeft:
\begin{align}
    \dfrac{40x + 39}{(x + 1)(x + 3)} = \dfrac{ (A+B)x + 3A + B }{ (x + 1)(x + 3) } 
\end{align}

Noemers zijn gelijk dus ook tellers moeten gelijk zijn aan elkaar.
\begin{align}
   40x  + 39 = (A + B)x + 3A + B
\end{align}

Hieruit volgt:
\begin{align}
   A + B &= 40 \\
   3A + B &= 39
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 40 - B\\
   3 (40 - B) + B &= 39 \\
   120 - 3B + B &= 39
   -2B &= -81
    B &= 40\dfrac{1}{2}
\end{align}

B invullen geeft:
\begin{align*}
   A &= 40 - B \\
   A &= 40 - 40\dfrac{1}{2} \\
   A &= -\dfrac{1}{2}
\end{align*}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{x^4 }{x^2 + 4x + 3} \, dx &= \int x^2 - 4x + 13 - \dfrac{40x + 39}{x^2 + 4x + 3} \, dx \\
   &= \int x^2 - 4x + 13 - \dfrac{40x + 39}{(x+1)(x+3)} \, dx\\
   &= \int (x^2 - 4x + 13) \, dx - \int \dfrac{40x + 39}{(x+1)(x+3)} \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ A }{ (x + 1) } + \dfrac{ B }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ A }{ (x + 1) } \, dx - \int \dfrac{ B }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx -\int \dfrac{ -\frac{1}{2} }{ x + 1 } \, dx - \int \dfrac{ 40\dfrac{1}{2} }{ (x + 3) } \, dx\\
   &= \int (x^2 - 4x + 13) \, dx + \frac{1}{2} \int \dfrac{ 1 }{ x + 1 } \, dx - 40\dfrac{1}{2} \int \dfrac{ 1 }{ (x + 3) } \, dx\\
   &= \dfrac{1}{3}x^3 - 2x^2 + 13x + \frac{1}{2}  \ln|x + 1 | - 40\frac{1}{2}  \ln|x + 3 |  + C\\
\end{align}
```
````

````{admonition} Oefening 8
:class: important, dropdown



```{admonition} Uitwerking
:class: important, dropdown

x
```
````
