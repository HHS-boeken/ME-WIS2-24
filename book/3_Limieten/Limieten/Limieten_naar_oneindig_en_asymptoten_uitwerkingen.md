# 1.1 Uitwerkingen

### Opgave 1.1a

````{admonition} Antwoord
:class:  dropdown

$$
\begin{align*}
    \lim_{x \to -\infty} \dfrac{4x^3 + x}{7x^5 - 9x^2 + 2} =0
\end{align*}
$$

```{admonition} Uitwerking
:class:  dropdown

Bereken de limiet

$$
\begin{align*}
    \lim_{x \to -\infty} \dfrac{4x^3 + x}{7x^5 - 9x^2 + 2}
\end{align*}
$$

Deel de teller en de noemer door de hoogste macht van de noemer, dus $x^5$:

$$
\begin{align}
    &= \lim_{x \to -\infty} \dfrac{\dfrac{4x^3}{x^5} + \dfrac{x}{x^5}}{\dfrac{7x^5}{x^5} - \dfrac{9x^2}{x^5} + \dfrac{2}{x^5}}  \\
    &= \lim_{x \to -\infty} \dfrac{\dfrac{4}{x^2} + \dfrac{1}{x^4}}{7 - \dfrac{9}{x^3} + \dfrac{2}{x^5}}
\end{align}
$$

Maak gebruik van de standaardlimiet,
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0
$
Dit geeft:

$$
\begin{align}
    &= \dfrac{0 + 0}{7 - 0 + 0}  \\
    &= \dfrac{0}{7} = 0
\end{align}
$$
```
````

<hr style="border:1px solid #9EA700">

### Opgave 1.1b

````{admonition} Antwoord
:class:  dropdown

$$
\begin{align*}
    \lim_{x \to \infty} \dfrac{x^3 + 5x}{x^2 - 2x + 1} = \infty  
\end{align*}
$$

```{admonition} Uitwerking
:class:  dropdown

Bereken de limiet

$$
\begin{align*}
    \lim_{x \to \infty} \dfrac{x^3 + 5x}{x^2 - 2x + 1}
\end{align*}
$$

Deel de teller en de noemer door de hoogste macht van de noemer, dus $x^2$:

$$
\begin{align}
    &= \lim_{x \to \infty} \dfrac{\dfrac{x^3}{x^2} + \dfrac{5x}{x^2}}{\dfrac{x^2}{x^2} - \dfrac{2x}{x^2} + \dfrac{1}{x^2}}  \\
    &= \lim_{x \to \infty} \dfrac{x + \dfrac{5}{x}}{ 1 - \dfrac{2}{x} + \dfrac{1}{x^2}}
\end{align}
$$

Maak gebruik van de standaardlimiet,
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0
$
Dit geeft:

$$
\begin{align}
    &= \dfrac{\infty   + 0}{1 - 0 + 0}  \\
    &= \infty
\end{align}
$$
```
````

<hr style="border:1px solid #9EA700">

### Opgave 1.1c

````{admonition} Antwoord
:class:  dropdown

$$
\begin{align*}
    \lim_{x \to \infty} \dfrac{4x^3 + x + 9}{x^3 - 2x + 5} = 4
\end{align*}
$$

```{admonition} Uitwerking
:class:  dropdown

Bereken de limiet

$$
\begin{align*}
    \lim_{x \to \infty} \dfrac{4x^3 + x + 9}{x^3 - 2x + 5}
\end{align*}
$$

Deel de teller en de noemer door de hoogste macht $x^3$ van de noemer:

$$
\begin{align}
    &= \lim_{x \to \infty} \dfrac{\dfrac{4x^3}{x^3} + \dfrac{x}{x^3} + \dfrac{9}{x^3}}{\dfrac{x^3}{x^3} - \dfrac{2x}{x^3} + \dfrac{5}{x^3}}  \\
    &= \lim_{x \to \infty} \dfrac{4 + \dfrac{1}{x^2} + \dfrac{9}{x^3}}{1 - \dfrac{2}{x^2} + \dfrac{5}{x^3}}  
\end{align}
$$

Gebruik de standaardlimiet,
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0
$
Dit geeft:

$$
\begin{align}
    &= \dfrac{4 + 0 + 0}{1 - 0 + 0}  \\
    &= \dfrac{4}{1} = 4
\end{align}
$$
```
````

<hr style="border:1px solid #9EA700">

### Opgave 1.1d

````{admonition} Antwoord
:class:  dropdown

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{5x^6 + 2x^3 - 8}{4x^4 + 3x^2 - 1} = -\infty
\end{align*}  
$$  

```{admonition} Uitwerking
:class:  dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{5x^6 + 2x^3 - 8}{4x^4 + 3x^2 - 1}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht van de noemer, dus $x^4$:  

$$  
\begin{align}  
&= \lim_{x \to -\infty} \dfrac{\dfrac{5x^6}{x^4} + \dfrac{2x^3}{x^4} - \dfrac{8}{x^4}}{\dfrac{4x^4}{x^4} + \dfrac{3x^2}{x^4} - \dfrac{1}{x^4}}  \\  
&= \lim_{x \to -\infty} \dfrac{5x^2 + \dfrac{2}{x} - \dfrac{8}{x^4}}{ 4 + \dfrac{3}{x^2} - \dfrac{1}{x^4}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{-\infty + 0 - 0}{4 + 0 - 0}  \\  
&= -\infty  
\end{align}  
$$  
```
````

### Opgave 1.1e

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{x^2 - 7}{x^3 + 2x - 1} = 0
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{x^2 - 7}{x^3 + 2x - 1}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^3$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to \infty} \dfrac{\dfrac{x^2}{x^3} - \dfrac{7}{x^3}}{\dfrac{x^3}{x^3} + \dfrac{2x}{x^3} - \dfrac{1}{x^3}}  \\  
&= \lim_{x \to \infty} \dfrac{\dfrac{1}{x} - \dfrac{7}{x^3}}{1 + \dfrac{2}{x^2} - \dfrac{1}{x^3}}  
\end{align}  
$$  

Gebruik de standaardlimiet,
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{0 - 0}{1 + 0 - 0}  \\  
&= \dfrac{0}{1} = 0  
\end{align}  
$$  
```
````

<hr style="border:1px solid #9EA700">

### Opgave 1.1f

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{x^4 - 3x^2 + 1}{x^2 + x} = \infty
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{x^4 - 3x^2 + 1}{x^2 + x}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^2$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to -\infty} \dfrac{\dfrac{x^4}{x^2} - \dfrac{3x^2}{x^2} + \dfrac{1}{x^2}}{\dfrac{x^2}{x^2} + \dfrac{x}{x^2}}  \\  
&= \lim_{x \to -\infty} \dfrac{x^2 - 3 + \dfrac{1}{x^2}}{1 + \dfrac{1}{x}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{x^2 - 3 + 0}{1 + 0}  \\  
&= x^2 - 3  
\end{align}  
$$  

Omdat \( x^2 \) naar oneindig gaat wanneer \( x \to -\infty \), volgt:  

$$  
\begin{align}  
\lim_{x \to -\infty} \dfrac{x^4 - 3x^2 + 1}{x^2 + x} = \infty  
\end{align}  
$$  
```
````

<hr style="border:1px solid #9EA700">


### Opgave 1.1g

````{admonition} Antwoord
:class: dropdown

$$
\begin{align*}
    \lim_{x \to \infty} \dfrac{3x^5 - x^2 + 2}{2x^3 + 7x - 5} = \infty
\end{align*}
$$

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet

$$
\begin{align*}  
    \lim_{x \to \infty} \dfrac{3x^5 - x^2 + 2}{2x^3 + 7x - 5}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^3$ in de noemer:  

$$  
\begin{align}  
    &= \lim_{x \to \infty} \dfrac{\dfrac{3x^5}{x^3} - \dfrac{x^2}{x^3} + \dfrac{2}{x^3}}{\dfrac{2x^3}{x^3} + \dfrac{7x}{x^3} - \dfrac{5}{x^3}}  \\  
    &= \lim_{x \to \infty} \dfrac{3x^2 - \dfrac{1}{x} + \dfrac{2}{x^3}}{ 2 + \dfrac{7}{x^2} - \dfrac{5}{x^3}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$
\begin{align}
    &= \dfrac{3x^2 - 0 + 0}{2 + 0 - 0} \\
    &= \dfrac{3}{2}x^2
\end{align}
$$

Omdat \( x^2 \) naar oneindig gaat wanneer \( x \to \infty \), volgt:  

$$  
\begin{align}  
    \lim_{x \to \infty} \dfrac{3x^5 - x^2 + 2}{2x^3 + 7x - 5} = \infty
\end{align}  
$$  

```  
````  

<hr style="border:1px solid #9EA700">

### Opgave 1.1h

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{-7x^5 + 2x^3 - x}{3x^5 + x^2 + 4} = -\dfrac{7}{3}
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{-7x^5 + 2x^3 - x}{3x^5 + x^2 + 4}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^5$ van de noemer:  

$$  
\begin{align}  
&= \lim_{x \to -\infty} \dfrac{\dfrac{-7x^5}{x^5} + \dfrac{2x^3}{x^5} - \dfrac{x}{x^5}}{\dfrac{3x^5}{x^5} + \dfrac{x^2}{x^5} + \dfrac{4}{x^5}}  \\  
&= \lim_{x \to -\infty} \dfrac{-7 + \dfrac{2}{x^2} - \dfrac{1}{x^4}}{3 + \dfrac{1}{x^3} + \dfrac{4}{x^5}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0  
$ 
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{-7 + 0 - 0}{3 + 0 + 0}  \\  
&= \dfrac{-7}{3}  
\end{align}  
$$  

```  
````  

<hr style="border:1px solid #9EA700">

### Opgave 1.1i

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{3x^2 + 5x - 7}{2x^2 - x + 4} = \dfrac{3}{2}
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{3x^2 + 5x - 7}{2x^2 - x + 4}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^2$ van de noemer:  

$$  
\begin{align}  
&= \lim_{x \to \infty} \dfrac{\dfrac{3x^2}{x^2} + \dfrac{5x}{x^2} - \dfrac{7}{x^2}}{\dfrac{2x^2}{x^2} - \dfrac{x}{x^2} + \dfrac{4}{x^2}}  \\  
&= \lim_{x \to \infty} \dfrac{3 + \dfrac{5}{x} - \dfrac{7}{x^2}}{2 - \dfrac{1}{x} + \dfrac{4}{x^2}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{3 + 0 - 0}{2 - 0 + 0}  \\  
&= \dfrac{3}{2}  
\end{align}  
$$  

```  
````  

<hr style="border:1px solid #9EA700">

### Opgave 1.1j

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{x + 3}{x^2 - 5x + 6} = 0
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{x + 3}{x^2 - 5x + 6}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^2$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to \infty} \dfrac{\dfrac{x}{x^2} + \dfrac{3}{x^2}}{\dfrac{x^2}{x^2} - \dfrac{5x}{x^2} + \dfrac{6}{x^2}}  \\  
&= \lim_{x \to \infty} \dfrac{\dfrac{1}{x} + \dfrac{3}{x^2}}{1 - \dfrac{5}{x} + \dfrac{6}{x^2}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{0 + 0}{1 - 0 + 0}  \\  
&= \dfrac{0}{1} = 0  
\end{align}  
$$  

```  
````  

<hr style="border:1px solid #9EA700">

### Opgave 1.1k

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{2x^4 - x}{x^6 + 3x^3 + 4} = 0
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{2x^4 - x}{x^6 + 3x^3 + 4}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^6$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to -\infty} \dfrac{\dfrac{2x^4}{x^6} - \dfrac{x}{x^6}}{\dfrac{x^6}{x^6} + \dfrac{3x^3}{x^6} + \dfrac{4}{x^6}}  \\  
&= \lim_{x \to -\infty} \dfrac{\dfrac{2}{x^2} - \dfrac{1}{x^5}}{1 + \dfrac{3}{x^3} + \dfrac{4}{x^6}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{0 - 0}{1 + 0 + 0}  \\  
&= \dfrac{0}{1} = 0  
\end{align}  
$$  
```  
````  

<hr style="border:1px solid #9EA700">

### Opgave 1.1l

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{5x^4 - 3x^2 + 7}{-2x^4 + x + 1} = -\dfrac{5}{2}
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to \infty} \dfrac{5x^4 - 3x^2 + 7}{-2x^4 + x + 1}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^4$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to \infty} \dfrac{\dfrac{5x^4}{x^4} - \dfrac{3x^2}{x^4} + \dfrac{7}{x^4}}{\dfrac{-2x^4}{x^4} + \dfrac{x}{x^4} + \dfrac{1}{x^4}}  \\  
&= \lim_{x \to \infty} \dfrac{5 - \dfrac{3}{x^2} + \dfrac{7}{x^4}}{-2 + \dfrac{1}{x^3} + \dfrac{1}{x^4}}  
\end{align}  
$$  

Gebruik de standaardlimiet,  
$
\lim_{x \to \infty} \dfrac{a}{x^n} = 0  
$
Dit geeft:  

$$  
\begin{align}  
&= \dfrac{5 - 0 + 0}{-2 + 0 + 0}  \\  
&= \dfrac{5}{-2} = -\dfrac{5}{2}  
\end{align}  
$$  

```  
````  
