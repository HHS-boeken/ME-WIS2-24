# 1.2 Breuken splitsen

````{admonition} Theorie
:class: tip, dropdown open

Het splitsen van breuken is een algebraïsche techniek waarbij een breuk wordt herschreven als een som of verschil van meerdere eenvoudigere breuken. Dit is vooral nuttig bij algebraïsche manipulaties, integralen en limieten.

In dit geval kijken we specifiek naar breuken van de vorm: 

\begin{align*}
 \dfrac{a+b}{c}
\end{align*}

waarbij $a, b, c$ algebraïsche expressies kunnen zijn.

De hoofdregel voor het splitsen van een breuk in termen van optellen of aftrekken in de teller is:

\begin{align*}
 \dfrac{a+b}{c} =  \dfrac{a}{c} + \dfrac{b}{c}
\end{align*}

Dit geldt ook voor verschillen:

\begin{align*}
 \dfrac{a-b}{c} =  \dfrac{a}{c} - \dfrac{b}{c}
\end{align*}

```{admonition} Toepassingen
:class: warning

1. Breuken makkelijker manipuleren: Door een breuk te splitsen, kunnen termen afzonderlijk worden bewerkt.
1. Integreren en differentiëren: Vaak wordt breukensplitsing gebruikt om ingewikkelde functies eenvoudiger te maken.
1. Limieten en reeksontwikkeling: In limietberekeningen kunnen gesplitste breuken eenvoudiger uit te rekenen zijn.
```
````

```{admonition} Voorbeeld 1: Teller ontbinden in factoren
:class: dropdown

Herleid:
\begin{align*}
 \dfrac{3x^2-3xy}{x-y}
\end{align*}

Ontbind de teller in factoren:

\begin{align}
 =  \dfrac{3x(x-y)}{x-y}
\end{align}

Wegdelen van de gemeenschappelijke factor in de teller en de noemer:

\begin{align}
 = \dfrac{3x}{1} = 3x \quad \text{als } x\neq y
\end{align}

```

````{admonition} Oefening 1
:class: important, dropdown

Splits de volgende breuk indien mogelijk en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^3 + 2x^2 - x + 4}{x^2}
\end{align*}

```{dropdown} Uitwerking

Splits de volgende breuk indien mogelijk en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^3 + 2x^2 - x + 4}{x^2}
\end{align*}

Splitsen van de breuk:

\begin{align}
 &= = \frac{x^3}{x^2} + \frac{2x^2}{x^2} - \frac{x}{x^2} + \frac{4}{x^2}
\end{align}

Vereenvoudigen:

\begin{align}
 &= x + 2 - \frac{1}{x} + \frac{4}{x^2}
\end{align}

Gesplitste en vereenvoudigde vorm:

\begin{align}
 & x + 2 - \frac{1}{x} + \frac{4}{x^2}
\end{align}
```
````

````{admonition} Oefening 2
:class: important, dropdown

Splits de volgende breuk indien mogelijk en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2y + xy^2 - y^3}{xy}
\end{align*}

```{dropdown} Uitwerking

Splits de volgende breuk indien mogelijk en vereenvoudig zo ver mogelijk:
\begin{align*}
 \dfrac{x^2y + xy^2 - y^3}{xy}
\end{align*}

Splitsen van de breuk:

\begin{align}
 &= \frac{x^2y}{xy} + \frac{xy^2}{xy} - \frac{y^3}{xy}
\end{align}

Vereenvoudigen:

\begin{align}
 &= x + y - \frac{y^2}{x}
\end{align}

Gesplitste en vereenvoudigde vorm:

\begin{align}
x + y - \frac{y^2}{x}, \quad x \neq 0, y \neq 0
\end{align}
```
````