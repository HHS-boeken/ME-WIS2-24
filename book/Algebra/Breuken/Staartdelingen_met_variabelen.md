# 1.7 Staartdelingen

````{admonition} Theorie
:class: tip, dropdown open

#### **Wat is een staartdeling?**
Een staartdeling is een methode om een deling uit te voeren waarbij je stapsgewijs deelt, vermenigvuldigt en aftrekt. Deze methode wordt gebruikt bij **lange delingen**, zowel met getallen als met algebraïsche uitdrukkingen.

Bij algebraïsche delingen, zoals het delen van een **veelterm** door een **binomiaal** (bijvoorbeeld $\frac{6x^2 + 11x + 3}{2x + 1}$ ), gebruiken we een staartdeling om termen systematisch te elimineren.

---

#### **Stappenplan voor een staartdeling**
Een staartdeling bij een algebraïsche uitdrukking bestaat uit de volgende stappen:

1. **Schrijf de deling op als staartdeling**  
   De deler (de term waar je door deelt) wordt buiten de staartdeling gezet, en de deeltal (de veelterm die gedeeld wordt) staat binnen de staartdeling.

2. **Deel de eerste term van de deeltal door de eerste term van de deler**  
   - Dit geeft de eerste term van het quotiënt (de uitkomst).
   - Noteer deze boven de staartdeling.

3. **Vermenigvuldig deze term met de deler**  
   - Trek het resultaat af van de deeltal.

4. **Herhaal de stappen voor de resterende termen**  
   - Deel opnieuw de grootste term door de eerste term van de deler.
   - Blijf herhalen tot je de rest overhoudt.

5. **Schrijf de rest op als een breuk**  
   - Als er een rest overblijft, noteer deze als een breuk met de deler als noemer.
````


```{admonition} Voorbeeld 1: Teller ontbinden in factoren
:class: dropdown


Berekenen door middel van een staartdeling:

$$
\frac{6x^2 + 11x + 3}{2x + 1}
$$

Zet de staartdeling op:

$$
\begin{align*}
 2x + 1 \quad / 6x^2 + 11x + 3 |
\end{align*}
$$

Deel de eerste term $6x^2$ door $2x$ dit geeft:

$$
\frac{6x^2}{2x} = 3x
$$

Dus,

$$
\begin{align*}
 2x + 1 \quad / &6x^2 + 11x + 3 | \quad 3x\\
&6x^2 + 3x \\
&------ \quad -\\
&\quad \quad \quad   8x + 3
\end{align*}
$$

Deel $8x$ door $2x$:
$$
\frac{8x}{2x} = 4
$$

Dus,

$$
\begin{align*}
 2x + 1 \quad / &6x^2 + 11x + 3 | \quad 3x + 4\\
&6x^2 + 3x \\
&------ \quad -\\
&\quad \quad \quad   8x + 3\\
&\quad \quad \quad   8x + 4\\
&------ \quad -\\
&\quad \quad \quad \quad  -1\\
\end{align*}
$$

Noteer de rest als een breuk De rest is -1, dus de uiteindelijke uitkomst is:

$$
\begin{align*}
3x+4 - \dfrac{1}{2x+1}
\end{align*}
$$
```

````{admonition} Oefening 1
:class: important, dropdown

Berekenen door middel van een staartdeling:
$$
\frac{x^2 + 9x - 4}{x + 2}
$$

```{dropdown} Uitwerking
Berekenen door middel van een staartdeling:
$$
\frac{x^2 + 6x - 4}{x + 2}
$$

Zet de staartdeling op:

$$
\begin{align*}
 x + 2 \quad / x^2 + 6x - 4 |
\end{align*}
$$

Deel de eerste term $x^2$ door $x$ dit geeft:

$$
\frac{x^2}{x} = x
$$

Dus,

$$
\begin{align*}
 x + 2 \quad / &x^2 + 6x - 4 | \quad x\\
&x^2 + 2x \\
&------ \quad -\\
&\quad \quad \quad   4x - 4
\end{align*}
$$

Deel $4x$ door $x$:
$$
\frac{4x}{x} = 4
$$

Dus,

$$
\begin{align*}
 x + 2 \quad / &x^2 + 6x - 4 | \quad x + 4\\
&x^2 + 2x \\
&------ \quad -\\
&\quad \quad \quad   4x - 4\\
&\quad \quad \quad   4x + 8\\
&------ \quad -\\
&\quad \quad \quad \quad  -12\\
\end{align*}
$$

Noteer de rest als een breuk De rest is $-12$, dus de uiteindelijke uitkomst is:

$$
\begin{align*}
x+4 - \dfrac{12}{x+2}
\end{align*}
$$
```
````

````{admonition} Oefening 2
:class: important, dropdown

Berekenen door middel van een staartdeling:
$$
\frac{x^4 + 6x^3 - x+6}{x^2 + 4}
$$

```{dropdown} Uitwerking

Berekenen door middel van een staartdeling:
$$
\frac{x^4 + 6x^3 - x+6}{x^2 + 4}
$$

Zet de staartdeling op:

$$
\begin{align*}
 x^2 + 4 \quad / x^4 + 6x^3 - \quad \quad x+6 |
\end{align*}
$$

Deel de eerste term $x^4$ door $x^2$ dit geeft:

$$
\frac{x^4}{x^2} = x^2
$$

Dus,

$$
\begin{align*}
 x^2 + 4 \quad / &x^4 + 6x^3 - \quad \quad x+6 | \quad x^2\\
&x^2 + \quad \quad \quad 4x^2 \\
&------ \quad -\\
&\quad \quad \quad   6x^3 - 4x^2-x+6
\end{align*}
$$

Deel $6x^3$ door $x^2$:
$$
\frac{6x^3}{x^2} = 6x
$$

Dus,

$$
\begin{align*}
 x^2 + 4 \quad / &x^4 + 6x^3 - \quad \quad x+6 | \quad x^2 + 6x\\
&x^2 + \quad \quad \quad 4x^2 \\
&----------- \quad -\\
&\quad \quad \quad   6x^3 - 4x^2-x+6 \\
&\quad \quad \quad   6x^3 \quad \quad \quad + 24x \\
&----------- \quad -\\
&\quad \quad \quad   \quad - 4x^2-25x + 6
\end{align*}
$$

Deel $4x^2$ door $x^2$:
$$
\frac{-4x^2}{x^2} = -4
$$

---

$$
\begin{align*}
 x^2 + 4 \quad / &x^4 + 6x^3 - \quad \quad x+6 | \quad x^2 + 6x - 4\\
&x^2 + \quad \quad \quad 4x^2 \\
&----------- \quad -\\
&\quad \quad \quad   6x^3 - 4x^2-x+6 \\
&\quad \quad \quad   6x^3 \quad \quad \quad + 24x \\
&----------- \quad -\\
&\quad \quad \quad   \quad - 4x^2-25x + 6 \\
&\quad \quad \quad   \quad - 4x^2 \quad \quad \quad -16\\
&----------- \quad -\\
&\quad \quad \quad   \quad \quad \quad \quad -25x -36\\

\end{align*}
$$

Noteer de rest als een breuk De rest is $-25x -36$, dus de uiteindelijke uitkomst is:

$$
\begin{align*}
x^2+6x-4 + \dfrac{-25x -36}{x^2+4}
\end{align*}
$$
```
````