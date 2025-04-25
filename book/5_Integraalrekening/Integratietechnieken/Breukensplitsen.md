# 6.3 Breukensplitsen

````{admonition} Theorie: Breukensplitsen
:class: tip, dropdown open

# 🧠 Wanneer gebruik je breuksplitsen?

Breuksplitsen gebruik je bij het berekenen van **integralen van rationale functies**: breuken waarin zowel de teller als de noemer **veeltermen** zijn. Het doel is om de breuk te herschrijven als een som van **eenvoudige standaardbreuken** die makkelijk te integreren zijn.

Bijvoorbeeld:


Breuksplitsen maakt zulke integralen overzichtelijk en oplosbaar.

Je gebruikt breuksplitsen als:
- De **graad van de teller lager is dan die van de noemer** (anders eerst polynoomdeling).
- De **noemer ontbindbaar is** in lineaire en/of kwadratische factoren.

---

## 📐 De hoofdgedachte

Je schrijft:


Zodat de rechterkant bestaat uit **losse, eenvoudige breuken** die makkelijk te integreren zijn.

Voorbeeld:

\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{A}{x + 1} + \frac{B}{x - 3}
\]

---

## 🔢 Stappenplan

1. **Controleer de graad** van teller en noemer:
   - Als \( \deg(\text{teller}) \geq \deg(\text{noemer}) \): eerst **polynoomdeling**.
2. **Ontbind de noemer** in factoren (lineair en/of irreducibel kwadratisch).
3. **Kies de juiste vorm** van de breuksplitsing (zie tabel hieronder).
4. **Werk de breuksplitsing uit**:
   - Vermenigvuldig met de noemer om de breuken weg te werken.
   - Los de constanten op via:
     - **Slimme waarden** van \( x \), of
     - **Coëfficiënten vergelijken**
5. **Integreer elke losse breuk** apart.

---

## 🧭 Hulpmiddel: Tabel van breukvormen

| Type factor in de noemer                    | Vorm van de breuk                         |
|---------------------------------------------|--------------------------------------------|
| \( (x - a) \)                                | \( \frac{A}{x - a} \)                      |
| \( (x - a)^n \)                              | \( \frac{A_1}{x - a} + \cdots + \frac{A_n}{(x - a)^n} \) |
| \( x^2 + bx + c \) (niet ontbindbaar)        | \( \frac{Ax + B}{x^2 + bx + c} \)          |
| \( (x^2 + bx + c)^n \)                       | \( \frac{A_1x + B_1}{x^2 + bx + c} + \cdots + \frac{A_nx + B_n}{(x^2 + bx + c)^n} \) |

---

## 💡 Tips & aandachtspunten

- ❗ **Tellergraad checken** is cruciaal. Anders levert breuksplitsen geen vereenvoudiging op.
- ✏️ Begin bij lineaire factoren met **slimme waarden voor \( x \)** (die factoren laten wegvallen).
- 🤓 Bij kwadratische factoren heb je **altijd een teller van vorm \( Ax + B \)**.
- 🔁 Herhaalde factoren krijgen meerdere breuken met oplopende machten.
- ⛔ Niet alle noemers zijn te ontbinden met reële getallen — gebruik dan irreducibele vormen.

---

## ✅ Voorbeeld

Splits:
\[
\frac{5x + 2}{(x + 1)(x - 3)}
\]

Stel:
\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{A}{x + 1} + \frac{B}{x - 3}
\]

Maal links en rechts met de noemer:
\[
5x + 2 = A(x - 3) + B(x + 1)
\]

Kies:
- \( x = 3 \Rightarrow 5(3) + 2 = 0A + 4B \Rightarrow B = \frac{17}{4} \)
- \( x = -1 \Rightarrow 5(-1) + 2 = -4A + 0 \Rightarrow A = -\frac{3}{4} \)

Oplossing:
\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{-\frac{3}{4}}{x + 1} + \frac{\frac{17}{4}}{x - 3}
\]
```

````{admonition} Voorbeeld 1: Partieel integreren
:class: dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int (2x+3)\cos(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= 2x+3 \\
    dv &= \cos(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2 \\
    du &= 2 \, dx \\
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
    &= (2x+3) \cdot \sin(x) - \int \sin(x) 2 \, dx\\
    &= (2x+3) \cdot \sin(x) - 2 \int \sin(x) \, dx\\
    &= (2x+3) \cdot \sin(x) + 2 \cos(x) + C
\end{align*}
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
     \int \dfrac{9x+7}{x^2+x-6} \, dx &= 4 \ln|x + 3 | + 5 \ln| x - 2| + C\\
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
     \int \dfrac{-6x+14}{x^2+2x-3} \, dx &= -8 \ln|x + 3 | + 2 \ln| x - 1| + C\\\\
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
    \int \dfrac{3x - 14}{x^2 - 8x + 16} \, dx   &= 3 \ln|x - 4 | + \frac{2}{ x - 4}  + C\\
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
    \int \dfrac{2x - 1}{x^2 + 4x + 4 } \, dx &= 2 \ln|x + 2 | + \frac{5}{ x + 2}  + C\\
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

````{admonition} Voorbeeld 4: 
:class: dropdown

Slaan we dit jaar `2024-2025` over.

````

````{admonition} Oefening 5
:class: important, dropdown

Slaan we dit jaar (2024-2025) over.

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

````{admonition} Voorbeeld 5: 
:class: dropdown

$$
\begin{align*}
 x^2 + 2x + 1 \quad / &x^4 \quad \quad \quad  + 1 \backslash \quad x^2 - 2x + 3\\
&18x^4 + 2x^3 + 2x \\
&--------- \quad -\\
&\quad \quad \quad -2x^2 + 9x + 7\\
&\quad \quad \quad 12x^2 + 6x \\
&--------- \quad -\\
&\quad \quad \quad \quad \quad \quad  3x + 7 \\
&\quad \quad \quad \quad \quad \quad  3x + \frac{3}{2} \\
&--------- \quad -\\
&\quad \quad \quad \quad \quad \quad \quad \quad  \frac{11}{2} \\
\end{align*}
$$

De rest is $\frac{11}{2}$, dus de uiteindelijke uitkomst is:

$$
\begin{align*}
& 3x^2 + 2x + \frac{1}{2} + \dfrac{11}{2(6x + 3)} = \\
& 3x^2 + 2x + \frac{1}{2} + \dfrac{11}{6(2x + 1)}
\end{align*}
$$

````

````{admonition} Oefening 7
:class: important, dropdown



```{admonition} Uitwerking
:class: important, dropdown
x

```
````

````{admonition} Oefening 8
:class: important, dropdown



```{admonition} Uitwerking
:class: important, dropdown

x
```
````
