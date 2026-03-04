# 3.2 Oneindige limieten, $\lim_{x\to a }  f(x)= \pm \infty$ ,  verticale asymptoot

````{admonition} Theorie
:class: tip, dropdown open

Dat $f(x)=\dfrac{1}{x}$ onbeperkt groot wordt als $x$ steeds dichter bij $0$ komt van de **rechterkant**, noteren we als:
$
\lim_{x\to 0^+} \dfrac{1}{x} = +\infty
$

Dit wordt uitgesproken als: $\quad$ *de limiet van $\dfrac{1}{x}$ voor $x$ naar nul van rechts is plus oneindig.*


Dat $f(x)=\dfrac{1}{x}$ onbeperkt groot wordt als $x$ steeds dichter bij $0$ komt van de **linkerkant**, noteren we als:
$
\lim_{x\to 0^-} \dfrac{1}{x} = -\infty
$

Dit wordt uitgesproken als: $\quad$ *de limiet van $\dfrac{1}{x}$ voor $x$ naar nul van links is min oneindig.*

```{admonition} Oneindige limiet
:class: warning

$
\lim_{x\to a^+}  f(x)=+\infty
$

betekent:
$f(x)$ wordt onbeperkt groot positief als $x$ $a$ nadert van rechts.

$
\lim_{x\to a^-}  f(x)=-\infty
$

betekent:
$f(x)$ wordt onbeperkt groot negatief als $x$ $a$ nadert van links.
```


Uit 
$
\lim_{x\to 0^+} \dfrac{1}{x} =+\infty 
$
volgt bijvoorbeeld:

$
\lim_{x\to 2^+} \dfrac{1}{x-2} =+\infty
$
en

$
\lim_{x\to 2^-} \dfrac{1}{x-2} =-\infty
$
.

Algemener geldt:

$$
\lim_{x\to a^+} \dfrac{1}{x-a} = +\infty
\quad \text{en} \quad
\lim_{x\to a^-} \dfrac{1}{x-a} = -\infty
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
\lim_{x\to a^+} f(x) = \pm\infty 
\quad \text{of} \quad
\lim_{x\to a^-} f(x) = \pm\infty
\end{align*}
$$
```
````

## 3.2.1
:class: dropdown

Bereken de limieten

\begin{align*}
\lim_{x \to 3^-} \dfrac{2}{x-3}
\quad \text{en} \quad
\lim_{x \to 3^+} \dfrac{2}{x-3}
\end{align*}

Voor $x \to 3^-$ geldt:  
$x-3$ is een klein **negatief** getal.

\begin{align}
\dfrac{2}{\text{negatief}} \rightarrow -\infty
\end{align}

Dus:

\begin{align}
\lim_{x \to 3^-} \dfrac{2}{x-3} = -\infty
\end{align}

Voor $x \to 3^+$ geldt:  
$x-3$ is een klein **positief** getal.

\begin{align}
\dfrac{2}{\text{positief}} \rightarrow +\infty
\end{align}

Dus:

\begin{align}
\lim_{x \to 3^+} \dfrac{2}{x-3} = +\infty
\end{align}

Hieruit volgt dat $x=3$ een verticale asymptoot is.

# 