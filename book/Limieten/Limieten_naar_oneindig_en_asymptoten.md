# limiet $x \rightarrow  \pm\infty$, horizontale asymptoot TEST

````{admonition} Theorie
:class: tip, dropdown open

Dat $f(x)=\dfrac{1}{x}$ nadert tot $0$ als $x$ heel groot wordt gekozen noteren we als:

$$
\begin{aligned}
\lim_{x\to\infty} \dfrac{1}{x} =0
\end{aligned}
$$

Dit wordt uitgesproken als: $\quad$ *de limiet van $\dfrac{1}{x}$ voor $x$ naar oneindig is nul.*

<br>
<br>

$
\begin{aligned}
\lim_{x\to\infty}  f(x)=L
\end{aligned}
$ 
betekent:

$f(x)$ kan onbeperkt tot $L$ naderen door $x$ maar groot genoeg te nemen.

$
\begin{aligned}
\lim_{x\to-\infty}  f(x)=L
\end{aligned}
$ 
betekent:

$f(x)$ kan onbeperkt tot $L$ naderen door $x$ maar groot genoeg te nemen.<br>

<br>
<br>

Uit 
$
\begin{aligned}
\lim_{x\to\infty} \dfrac{1}{x} =0 
\end{aligned}
$
volgt 
$
\begin{aligned}
\lim_{x\to\infty} \dfrac{a}{x} = \lim_{x\to\infty} ( a\cdot\dfrac{1}{x} ) =a \cdot 0=0
\end{aligned}
$
.

Dit geeft de standaardlimieten:

$$
\begin{aligned}
\lim_{x\to\infty} \dfrac{a}{x} =0 \quad \text{en} \quad \lim_{x\to-\infty} \dfrac{a}{x} =0
\end{aligned}
$$

Nog algemener volgt:

$
\begin{aligned}
\lim_{x\to\infty} \dfrac{a}{x^3} = \lim_{x\to\infty} ( a\cdot\dfrac{1}{x}\cdot\dfrac{1}{x}\cdot\dfrac{1}{x} ) =a \cdot 0\cdot 0\cdot 0=0
\end{aligned}
$ en

$
\begin{aligned}
\lim_{x\to\infty} \dfrac{a}{x^6} = \lim_{x\to\infty} ( a\cdot\dfrac{1}{x}\cdot\dfrac{1}{x}\cdot\dfrac{1}{x} \cdot\dfrac{1}{x}\cdot\dfrac{1}{x}\cdot\dfrac{1}{x} ) =a \cdot 0\cdot 0\cdot 0\cdot 0\cdot 0\cdot 0=0
\end{aligned}
$ en

Bij het berekenen van limieten van het quotiënt van twee veeltermfuncties deel je de teller en de noemer door de hoogste macht $x$ van de noemer. Afhankelijk van de graad van de veeltermfuncties zijn drie situaties te onderscheiden:

1. De graad van de teller en de noemer zijn gelijk 
$
\begin{aligned}
 \dfrac{2x^3+4x-4}{x^3+2x^2+7}
\end{aligned}
$.

1. De graad van de teller is kleiner dan de graad van de noemer
$
\begin{aligned}
 \dfrac{5x^2-x+3}{x^3-4x^2-2x+2}
\end{aligned}
$.

1. De graad van de teller is groter dan de graad van de noemer
$
\begin{aligned}
 \dfrac{x^3-6x^2-2}{x^2+9x-4}
\end{aligned}
$.



$
\begin{aligned}
\lim_{x\to\infty} \dfrac{a}{x} =0
\end{aligned}
$.

Drie verschillende situaties 
````

## De graad van de tellen en de noemer zijn gelijk

```{admonition} Voorbeeld 1:
:class: dropdown

Bereken de limiet

\begin{align}
    \lim_{x \to \infty} \dfrac{4x + 3}{5x - 4}
\end{align}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x$:

\begin{align}
    &= \lim_{x \to \infty} \dfrac{4 + \dfrac{3}{x}}{5 - \dfrac{4}{x}} \\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
    \lim_{x \to \infty} \dfrac{a}{x} = 0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{4 + 0}{5 - 0} \\
    &= \dfrac{4}{5}
\end{align}

<iframe scrolling="no" title="boek limiet" src="https://www.geogebra.org/material/iframe/id/e3bc9ay9/width/1440/height/812/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="600px" height="800px" style="border:0px;"> </iframe>

```

````{admonition} Oefening 1
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to \infty} \dfrac{3x^2 + 7}{7x^2 - 12x}
\end{align}

```{admonition} Uitwerking
:class: important, dropdown


Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^2$:

\begin{align}
    &= \lim_{x \to \infty} \dfrac{ 3 + \dfrac{7}{x^2} }{ 7 - \dfrac{12}{x} }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to \infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{3 +  0}{7 - 0} \\
    &= \dfrac{3}{7}
\end{align}
```
````

````{admonition} Oefening 2
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to \infty} \dfrac{2x^3 + 5}{x^3 - x^2 + x + 6}
\end{align}

```{admonition} Uitwerking
:class: important, dropdown

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^3$:

\begin{align}
    &= \lim_{x \to \infty} \dfrac{ 2 + \dfrac{5}{x^3} }{ 1 - \dfrac{1}{x} + \dfrac{1}{x^2} + \dfrac{6}{x^3} }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to \infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{2 +  0}{1 - 0 + 0 + 0} \\
    &= \dfrac{2}{1} = 2
\end{align}
```
````

## De graad van de teller is kleiner dan de graad van de noemer

```{admonition} Voorbeeld 2:
:class: dropdown

```

## De graad van de teller is groter dan de graad van de noemer

```{admonition} Voorbeeld 3:
:class: dropdown

```

\begin{align}
 &= \lim_{x\to\infty} \dfrac{3x^2+7}{7x^2-12x}\\
 &= \lim_{x\to\infty} \dfrac{3+\dfrac{7}{x^2}}{7-\dfrac{12}{x}} \\
 &= \dfrac{3+0}{7-0} \\
 &= \dfrac{3}{7}
\end{align}
