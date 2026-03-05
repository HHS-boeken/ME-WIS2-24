# 3.2 Oneindige limieten, $\lim_{x\to a }  f(x)= \pm \infty$ ,  verticale asymptoot

````{admonition} Theorie
:class: tip, dropdown open

Dat $f(x)=\dfrac{1}{x}$ onbeperkt groot wordt als $x$ steeds dichter bij $0$ komt van de **rechterkant**, noteren we als:
$$
\lim_{x \downarrow 0} \dfrac{1}{x} = +\infty
$$

Dit wordt uitgesproken als: $\quad$ *de limiet van $\dfrac{1}{x}$ voor $x$ naar nul van rechts is plus oneindig.*

Dat $f(x)=\dfrac{1}{x}$ onbeperkt groot wordt als $x$ steeds dichter bij $0$ komt van de **linkerkant**, noteren we als:
$$
\lim_{x \uparrow 0} \dfrac{1}{x} = -\infty
$$

Dit wordt uitgesproken als: $\quad$ *de limiet van $\dfrac{1}{x}$ voor $x$ naar nul van links is min oneindig.*

```{admonition} Oneindige limiet
:class: warning

$$
\lim_{x \downarrow a}  f(x)=+\infty
$$

betekent:
$f(x)$ wordt onbeperkt groot positief als $x$ $a$ nadert van rechts.

$$
\lim_{x \uparrow a}  f(x)=-\infty
$$

betekent:
$f(x)$ wordt onbeperkt groot negatief als $x$ $a$ nadert van links.
```


Uit 
$$
\lim_{x \downarrow 0} \dfrac{1}{x} =+\infty 
$$
volgt bijvoorbeeld:

$$
\lim_{x \downarrow 2} \dfrac{1}{x-2} =+\infty
$$
en

$$
\lim_{x \uparrow 2} \dfrac{1}{x-2} =-\infty
$$


Algemener geldt:

$$
\lim_{x \downarrow a} \dfrac{1}{x-a} = +\infty
\quad \text{en} \quad
\lim_{x \uparrow a} \dfrac{1}{x-a} = -\infty
$$

<br>
<br>

Bij het berekenen van oneindige limieten bij rationale functies onderzoek je:

- Waar wordt de **noemer nul**?
- Wat is het **teken van de teller**?
- Wat is het **teken van de noemer** links en rechts van dat punt?

Afhankelijk van het teken ontstaan vier mogelijke situaties:

1. $+\infty$ links en $-\infty$ rechts  
2. $-\infty$ links en $+\infty$ rechts  
3. $+\infty$ aan beide kanten  
4. $-\infty$ aan beide kanten  

```{admonition} Verticale asymptoot
:class: warning

De lijn $x = a$ is een **verticale asymptoot** van de grafiek van de functie $f(x)$ als;

$$
\begin{align*}
\lim_{x \downarrow a} f(x) = \pm\infty 
\quad \text{of} \quad
\lim_{x \uparrow a} f(x) = \pm\infty
\end{align*}
$$
```
````

## 3.2.1 Verschillende tekens links en rechts

```{admonition} Voorbeeld 1a:
:class: dropdown

Bereken de limiet

$$
\lim_{x \uparrow 3} \dfrac{2}{x-3}
$$

Kijk wanneer de noemer 0 wordt:

$$
x-3 = 0 
$$

dus 

$$
x=3
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \uparrow 3 \quad x \text{ komt van links van } 3
$$

Dan geldt:

$$
x-3 < 0
$$

Dus,

$$
negatief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \uparrow 3 \quad x \text{ komt van links van } 3
$$

$$
2 > 0
$$

Dus,

$$
positief
$$

Bepaal de limiet:

$$
\dfrac{positief}{negatief} = negatief
$$

Hieruit volgt:

$$
\lim_{x \uparrow 3} \dfrac{2}{x-3} = -\infty
$$

```

```{admonition} Voorbeeld 1b:
:class: dropdown

Bereken de limiet

$$
\lim_{x \downarrow 3} \dfrac{2}{x-3}
$$

Kijk wanneer de noemer 0 wordt:

$$
x-3 = 0
$$

dus 

$$
x=3
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \downarrow 3 \quad x \text{ komt van rechts van } 3
$$

Dan geldt:

$$
x-3 > 0
$$

Dus,

$$
positief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \downarrow 3 \quad x \text{ komt van rechts van } 3
$$

$$
2 > 0
$$

Dus,

$$
positief
$$

Bepaal de limiet:

$$
\dfrac{positief}{positief} = positief
$$

Hieruit volgt:

$$
\lim_{x \downarrow 3} \dfrac{2}{x-3} = \infty
$$

```

````{admonition} Oefening 1a:
:class:  important, dropdown

Bereken de limiet

$$
\lim_{x \uparrow -2} \dfrac{4x}{5x+10}
$$

```{dropdown} Uitwerking

Bereken de limiet

$$
\lim_{x \uparrow -2} \dfrac{4x}{5x+10}
$$

Kijk wanneer de noemer 0 wordt:

$$
5x+10 = 0
$$

$$
5(x+2) = 0
$$

dus 

$$
x=-2
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \uparrow -2 \quad x \text{ komt van links van } -2
$$

Dan geldt:

$$
5x+10 < 0
$$

Dus,

$$
negatief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \uparrow -2 \quad x \text{ komt van links van } -2
$$

Dan geldt:

$$
4x < 0
$$

Dus,

$$
negatief
$$

Bepaal de limiet:

$$
\dfrac{negatief}{negatief} = positief
$$

Hieruit volgt:

$$
\lim_{x \uparrow -2} \dfrac{4x}{5x+10}= +\infty
$$

```
````


````{admonition} Oefening 1b:
:class:  important, dropdown

Bereken de limiet

$$
\lim_{x \downarrow -2} \dfrac{4x}{5x+10}
$$

```{dropdown} Uitwerking

Bereken de limiet

$$
\lim_{x \downarrow -2} \dfrac{4x}{5x+10}
$$

Kijk wanneer de noemer 0 wordt:

$$
5x+10 = 0
$$

$$
5(x+2) = 0
$$

dus 

$$
x=-2
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \downarrow -2 \quad x \text{ komt van rechts van } -2
$$

Dan geldt:

$$
5x+10 > 0
$$

Dus,

$$
positief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \downarrow -2 \quad x \text{ komt van rechts van } -2
$$

Dan geldt:

$$
4x < 0
$$

Dus,

$$
negatief
$$

Bepaal de limiet:

$$
\dfrac{positief}{negatief} = negatief
$$

Hieruit volgt:

$$
\lim_{x \uparrow -2} \dfrac{4x}{5x+10}= -\infty
$$

```
````

````{admonition} Oefening 2a:
:class:  important, dropdown

Bereken de limiet

$$
\lim_{x \downarrow -3} \dfrac{x^2-4}{x^2+5x+6}
$$

```{dropdown} Uitwerking

Bereken de limiet

$$
\lim_{x \downarrow -3} \dfrac{x^2-4}{x^2+5x+6}
$$

Vereenvoudig de breuk:

$$
\lim_{x \downarrow -3} \dfrac{(x-2)(x+2)}{(x+2)(x+3)}
$$

Geeft:

$$
\lim_{x \downarrow -3} \dfrac{(x-2)}{(x+3)}
$$

Kijk wanneer de noemer 0 wordt:

$$
x+3 = 0
$$

dus,

$$
x=-3
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \downarrow -3 \quad x \text{ komt van rechts van } -3
$$

Dan geldt:

$$
x+3 > 0
$$

Dus,

$$
positief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \downarrow -3 \quad x \text{ komt van rechts van } -3
$$

Dan geldt:

$$
x-2 < 0
$$

Dus,

$$
negatief
$$

Bepaal de limiet:

$$
\dfrac{positief}{negatief} = negatief
$$

Hieruit volgt:

$$
\lim_{x \downarrow -3} \dfrac{x^2-4}{x^2+5x+6}= -\infty
$$

```
````


````{admonition} Oefening 2b:
:class:  important, dropdown

Bereken de limiet

$$
\lim_{x \uparrow -3} \dfrac{x^2-4}{x^2+5x+6}
$$

```{dropdown} Uitwerking

Bereken de limiet

$$
\lim_{x \uparrow -3} \dfrac{x^2-4}{x^2+5x+6}
$$

Vereenvoudig de breuk:

$$
\lim_{x \uparrow -3} \dfrac{(x-2)(x+2)}{(x+2)(x+3)}
$$

Geeft:

$$
\lim_{x \uparrow -3} \dfrac{(x-2)}{(x+3)}
$$

Kijk wanneer de noemer 0 wordt:

$$
x+3 = 0
$$

dus,

$$
x=-3
$$

Onderzoek het teken van de noemer:

$$
\text{Als } x \uparrow -3 \quad x \text{ komt van links van } -3
$$

Dan geldt:

$$
x+3 < 0
$$

Dus,

$$
negatief
$$

Onderzoek het teken van de teller:

$$
\text{Als } x \uparrow -3 \quad x \text{ komt van links van } -3
$$

Dan geldt:

$$
x-2 < 0
$$

Dus,

$$
negatief
$$

Bepaal de limiet:

$$
\dfrac{negatief}{negatief} = positief
$$

Hieruit volgt:

$$
\lim_{x \downarrow -3} \dfrac{x^2-4}{x^2+5x+6}= \infty
$$

```
````

## 3.2.2 Zelfde tekens links en rechts

