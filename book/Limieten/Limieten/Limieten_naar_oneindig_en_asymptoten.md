# 1.1 Eindige limiet, $\lim_{x\to \pm \infty}  f(x)=L$ ,  horizontale asymptoot

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

\begin{align*}
    \lim_{x \to \infty} \dfrac{4x + 3}{5x - 4}
\end{align*}

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
\begin{align*}
    \lim_{x \to \infty} \dfrac{3x^2 + 7}{7x^2 - 12x}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align*}
    \lim_{x \to \infty} \dfrac{3x^2 + 7}{7x^2 - 12x}
\end{align*}

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
\begin{align*}
    \lim_{x \to \infty} \dfrac{2x^3 + 5}{x^3 - x^2 + x + 6}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align*}
    \lim_{x \to \infty} \dfrac{2x^3 + 5}{x^3 - x^2 + x + 6}
\end{align*}

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

Bereken de limiet

\begin{align*}
    \lim_{x \to \infty} \dfrac{11x + 2}{2x^3 - 1}
\end{align*}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^3$:

\begin{align}
    &= \lim_{x \to \infty} \dfrac{ \dfrac{11}{x^2} + \dfrac{2}{x^3}}{ 2 - \dfrac{1}{x^3}} \\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
    \lim_{x \to \infty} \dfrac{a}{x} = 0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{0 + 0}{2 - 0} \\
    &= \dfrac{0}{2}=0
\end{align}
```

````{admonition} Oefening 3
:class: important, dropdown

Bereken de limiet
\begin{align*}
    \lim_{x \to \infty} \dfrac{1}{x^3 - 4x + 1}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align*}
    \lim_{x \to \infty} \dfrac{1}{x^3 - 4x + 1}
\end{align*}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^3$:

\begin{align}
    &= \lim_{x \to \infty} \dfrac{ \dfrac{1}{x^3} }{ 1 - \dfrac{4}{x^2} + \dfrac{1}{x^3} }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to \infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{0}{1 - 0 + 0} \\
    &= \dfrac{0}{1} = 0
\end{align}
```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to -\infty} \dfrac{x^4 - 50x}{2x + x^5}
\end{align}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to -\infty} \dfrac{x^4 - 50x}{2x + x^5}
\end{align}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^5$:

\begin{align}
    &= \lim_{x \to -\infty} \dfrac{ \dfrac{1}{x} + \dfrac{50}{x^4} }{ \dfrac{2}{x^4} + 1 }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to -\infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{0 +  0}{  0 + 1} \\
    &= \dfrac{0}{1} = 0
\end{align}
```
````

## De graad van de teller is groter dan de graad van de noemer

```{admonition} Voorbeeld 3:
:class: dropdown

Bereken de limiet

\begin{align*}
    \lim_{x \to -\infty} \dfrac{ 3x^2 - 6x }{ 4x - 8 }
\end{align*}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x$:

\begin{align*}
    &= \lim_{x \to -\infty} \dfrac{ 3x - 6 }{ 4 - \dfrac{8}{x}} \\
\end{align*}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
    \lim_{x \to -\infty} \dfrac{a}{x} = 0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{ -\infty - 6 }{ 4 - 0 } \\
    &= -\infty
\end{align}
```

````{admonition} Oefening 5
:class: important, dropdown

Bereken de limiet
\begin{align*}
    \lim_{x \to -\infty} \dfrac{2x^4 - x^3 - 10}{10x^3 + 8x^2}
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align*}
      \lim_{x \to -\infty} \dfrac{2x^4 - x^3 - 10}{10x^3 + 8x^2}
\end{align*}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^3$:

\begin{align}
    &= \lim_{x \to -\infty} \dfrac{ 2x - 1 - \dfrac{10}{x^3} }{ 10 + \dfrac{8}{x} }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to -\infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{-\infty - 1 - 0}{ 10 + 0} \\
    &= - \infty
\end{align}
```
````

````{admonition} Oefening 6
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to -\infty} \dfrac{-4x^3 + 7x }{2x^2 - 3x - 8 }
\end{align}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de limiet
\begin{align}
    \lim_{x \to -\infty} \dfrac{-4x^3 + 7x }{2x^2 - 3x - 8 }
\end{align}

Deel de teller en de noemer door de hoogste macht $x$ van de noemer, dus $x^2$:

\begin{align}
    &= \lim_{x \to -\infty} \dfrac{ -4x + \dfrac{7}{x} }{ 2 - \dfrac{3}{x} - \dfrac{8}{x^2} }\\
\end{align}

Maak gebruik van de standaardlimiet,
$
\begin{aligned}
\lim_{x \to -\infty} \dfrac{a}{x} =0
\end{aligned}
$, dit geeft:

\begin{align}
    &= \dfrac{ \infty +  0}{2 - 0 - 0 } \\
    &= \infty
\end{align}
```
````

