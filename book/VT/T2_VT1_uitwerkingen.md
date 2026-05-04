# Voorbeeldtoets 1: Uitwerkingen

## Opgave 1 (3 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
\frac{7}{3} - \frac{17}{3(3x + 2)}
\end{align*}

```{dropdown} Uitwerking

Schrijf in de vorm $\dfrac{m}{x - p} + q$:
\begin{align*}
 \dfrac{7x - 1}{3x + 2}
\end{align*}

Voeg de factor $(3x + 2)$ toe aan de teller en corrigeer de teller:
\begin{align}
 = \dfrac{\frac{7}{3} (3x + 2) - \frac{14}{3} - 1}{3x + 2}
\end{align}

Vereenvoudig de teller:
\begin{align}
 = \dfrac{\frac{7}{3}(3x + 2) - \frac{17}{3}}{3x + 2}  {\color{blue} \quad  \text{(1p)}}
\end{align}

Splits de breuk:
\begin{align}
 = \dfrac{\frac{7}{3}(3x + 2)}{3x + 2} - \dfrac{\frac{17}{3}}{3x + 2}  {\color{blue} \quad  \text{(1p)}}
\end{align}

Vereenvoudig de breuk:
\begin{align}
 = \frac{7}{3} - \frac{17}{3(3x + 2)}  {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 2 (3 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align}
    \lim_{x \uparrow 3} \frac{ x-9  }{ 12 - 4x } = - \infty
\end{align}

```{dropdown} Uitwerking

Bereken de limiet:

\begin{align*}
    \lim_{x \uparrow 3} \frac{ x-9  }{ 12 - 4x }
\end{align*}

Invullen van $x=3$ geeft:
\begin{align}
    \lim_{x \uparrow 3} \frac{ x-9  }{ 12 - 4x } = \dfrac{3-9}{12 - 4 \cdot 3} = \dfrac{-6}{0} {\color{blue} \quad  \text{(1p)}}\\
\end{align}

De noemer wordt 0 de teller −6, dus hebben te maken met een oneindige limiet (mogelijk $\pm \infty$). 

Onderzoek het teken van voor de teller en de noemer als $x$ van onder naar boven 3 nadert:
stel $x = 2,9$;

teller: 
\begin{align}
    x - 9 = 2.9 - 9 = -6,1
\end{align}

Noemer:
\begin{align}
    12 - 4x = 12 - 4 \cdot 2.9 =  0.4
\end{align}

Dus, 
\begin{align}
    \frac{ x-9  }{ 12 - 4x } = \dfrac{-6.1}{ 0.4} = \dfrac{-}{+} = -  {\color{blue} \quad  \text{(1p)}}
\end{align}

Dit geeft:
\begin{align}
    \lim_{x \uparrow 3} \frac{ x-9  }{ 12 - 4x } = - \infty  {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 3 (3 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    \lim_{x \to 0} \frac{\sin(x)-x}{x^3} = -\dfrac{1}{6}
\end{align*}

```{dropdown} Uitwerking

Bereken de limiet:
\begin{align*}
    \lim_{x \to 0} \frac{\sin(x)-x}{x^3}
\end{align*}

Invullen van $x=0$ geeft:
\begin{align}
    &\lim_{x \to 0} \frac{\sin(x)-x}{x^3} = \dfrac{0}{0} = ? \quad \text{gebruik L'Hopital} \\
    &\lim_{x \to 0} \frac{\cos(x)-1}{3x^2} = \dfrac{1-1}{0} = \dfrac{0}{0} =  ? \quad \text{gebruik L'Hopital} \quad {\color{blue} \text{(1p)}}\\
    &\lim_{x \to 0} \frac{-sin(x)}{6x} =  \dfrac{0}{0} =  ? \quad \text{gebruik L'Hopital}  \quad {\color{blue} \text{(1p)}}\\
    &\lim_{x \to 0} \frac{-\cos(x)}{6} = \dfrac{-1}{6} =  -\dfrac{1}{6}  \quad {\color{blue} \text{(1p)}}\\
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 4 (4 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
  \dfrac{df}{dx} &= \frac{ 2 \sin(x)\cos(x)(\ln(3x+5)) - \dfrac{3\sin^2(x)}{3x+5} }{ \ln^2(3x+5)} 
\end{align*}

```{dropdown} Uitwerking

Bereken de afgeleide van de volgende functie:
\begin{align*}
  f(x) =  \dfrac{ \sin^2(x) }{ \ln(3x+5)}
\end{align*}

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &=  \sin^2(x) \\
  v &=  \ln(3x+5) \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= 2 \sin(x)\cos(x) {\color{blue} \quad  \text{(1p)}}\\
  \dfrac{dv}{dx} &= \dfrac{1}{3x+5} \cdot 3  {\color{blue} \quad  \text{(1p)}}\\
                &= \dfrac{3}{3x+5} \\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ (\ln(3x+5)) \cdot 2 \sin(x)\cos(x)  - \sin^2(x) \cdot  \dfrac{3}{3x+5} }{ (\ln(3x+5))^2} {\color{blue} \quad  \text{(1p)}}\\
  &= \frac{ 2 \sin(x)\cos(x)(\ln(3x+5)) - \dfrac{3\sin^2(x)}{3x+5} }{ \ln^2(3x+5)} {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 5 (10 punten)

````{admonition} Antwoord
:class: important, dropdown

Het buigpunt is (4.48 ; 3.35).

```{dropdown} Uitwerking

Bereken het buigpunt van de grafiek van $f$.
\begin{align*}
    f(x) = \dfrac{10 \ln(x)}{x}
\end{align*}

Bereken de eerste afgeleide:

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= 10 \ln(x) \\
  v &=  x \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= \dfrac{10}{x} {\color{blue} \quad  \text{(1p)}}\\
  \dfrac{dv}{dx} &=  1 {\color{blue} \quad  \text{(1p)}}\\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ x \cdot \dfrac{10}{x} -  10 \ln(x) \cdot 1 } { x^2}  {\color{blue} \quad  \text{(1p)}}\\
  &= \frac{ 10 -  10 \ln(x) } { x^2}  
\end{align}

Bereken de tweede afgeleide:

Kies de functies $u(x)$ en $v(x)$:
\begin{align}
  u &= 10- 10 \ln(x) \\
  v &=  x^2 \\
\end{align}

Differentieer de functies $u(x)$ en $v(x)$:
\begin{align}
  \dfrac{du}{dx} &= -\dfrac{10}{x} {\color{blue} \quad  \text{(1p)}}\\
  \dfrac{dv}{dx} &=  2x {\color{blue} \quad  \text{(1p)}}\\
\end{align}

Toepassen van de quotiëntregel:
\begin{align}
  \dfrac{df(x)}{dx} &= \frac{ v\dfrac{du}{dx} - u \dfrac{dv}{dx} }{v^2} \\
  &= \frac{ x^2 \cdot -\dfrac{10}{x} -  (10 -10 \ln(x) \cdot 2x) } { (x^2)^2 }  {\color{blue} \quad  \text{(1p)}}\\
  &= \frac{ -10x -  (10 -10 \ln(x) \cdot 2x) } { (x^2)^2 }  \\
  &= \frac{ -10x -  (20x -20x \ln(x) ) } { (x^2)^2 }  \\
  &= \frac{ -10x -  20x + 20x \ln(x)  } { (x^2)^2 }  \\
  &= \frac{ - 30x + 20x \ln(x)  } { (x^2)^2 }  \\
  &= \frac{ - 30 + 20 \ln(x)  } { x^3 }  {\color{blue} \quad  \text{(1p)}}\\
\end{align}

Bereken x-coördinaat van het Buigpunt:
\begin{align}
  \dfrac{d^2f(x)}{dx^2} &= 0 {\color{blue} \quad  \text{(1p)}}\\
   0 &= \frac{ - 30 + 20 \ln(x)  } { x^3 } 
\end{align}

Dus, 
\begin{align}
   0 &= - 30 + 20 \ln(x) \\
   30 &= 20 \ln(x) \\
   \dfrac{3}{2} &= \ln(x) \\
   x &= e^{\frac{3}{2}} {\color{blue} \quad  \text{(1p)}}
\end{align}

Bereken y-coördinaat van het Buigpunt:
\begin{align}
    f(x) &= \dfrac{10 \ln(x)}{x} \\
    f(e^{\frac{3}{2}}) &= \dfrac{10 \ln(e^{\frac{3}{2}})}{e^{\frac{3}{2}}} \\
    f(e^{\frac{3}{2}}) &= 3.35 {\color{blue} \quad  \text{(1p)}}\\
\end{align}

Dus buigpunt is (4.48 ; 3.35).

```
````

<hr style="border:1px solid #9EA700">

## Opgave 6 ( 6 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    f(x) &\approx   2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{250}{81}x^3  \\
\end{align*}

```{dropdown} Uitwerking

Bepaal de 3e orde Maclaurin-reeks van
\begin{align*}
    f(x) = 2\ln(5x+3)
\end{align*}

Bereken de afgeleide van $f(x)$  tot de 3e orde:
\begin{align}
  f(x) &= 2\ln(5x+3) \\
  f'(x) &= \dfrac{10}{5x+3}  {\color{blue} \quad  \text{(1p)}}\\
  f''(x) &= -\dfrac{50}{(5x+3)^2}  {\color{blue} \quad  \text{(1p)}}\\
  f'''(x) &= \dfrac{500}{(5x+3)^3}  {\color{blue} \quad  \text{(1p)}}
\end{align}

Evalueer de afgeleide bij $x= 0$:
\begin{align}
  f(0) &= 2\ln(3) \\
  f'(0) &=  \dfrac{10}{3} \\
  f''(0) &= -\dfrac{50}{9} \\
  f'''(0) &= \dfrac{500}{27}  {\color{blue} \quad  \text{(2p) voor alle 4, 1 fout 1p, 2 of meer fout 0p}}\\
\end{align}

Invullen van de waaardes in de Maclaurin-reeks geeft:

\begin{align}
  f(x) &\approx   f(0) + f'(0)x + \dfrac{f''(0)}{2!}x^2 + \dfrac{f'''(0)}{3!}x^3 \\
\end{align}

\begin{align}
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2!}x^2 + \dfrac{\dfrac{500}{27}}{3!}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-\dfrac{50}{9} }{2}x^2 + \dfrac{\dfrac{500}{27}}{6}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x + \dfrac{-50}{18}x^2 + \dfrac{500}{162}x^3  \\
  f(x) &\approx   2\ln(3) + \dfrac{10}{3}x - \dfrac{25}{9}x^2 + \dfrac{250}{81}x^3   {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 7 (4 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx &= -\dfrac{1}{3} \cos(x^3) + C \\
\end{align*}

```{dropdown} Uitwerking

Bereken de onbepaalde integraal:
\begin{align*}
    \int x^2 \cdot \sin(x^3) \, dx
\end{align*}

Kies de functie $u(x)$:
\begin{align}
    u(x) = x^3
\end{align}

Differentieer de functie $u(x)$ en bepaal $du$:
\begin{align}
    \dfrac{du}{dx} &= 3x^2 \\
    du &= 3x^2 \, dx
\end{align}

In de originele functie staat $(x^2)$ dus:
\begin{align}
    \dfrac{1}{3}du &= x^2 \, dx  {\color{blue} \quad  \text{(1p)}}
\end{align}

Herschrijf de integraal door substitutie van $u$ en $du$:
\begin{align}
    &\int \sin(x^3) \cdot x^2  \, dx \\
    &= \int \sin(u) \, \dfrac{1}{3}du \\
    &= \dfrac{1}{3} \int \sin(u) \, du  {\color{blue} \quad  \text{(1p)}}
\end{align}

Integreren geeft:
\begin{align}
    &= \dfrac{1}{3} \cdot -\cos(u) + C \\
     &= -\dfrac{1}{3} \cos(u) + C  {\color{blue} \quad  \text{(1p)}}
\end{align}

Terugsubstitueren geeft:
\begin{align}
    &= -\dfrac{1}{3} \cos(x^3) + C  {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 8 (8 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    F(x) &= \dfrac{1}{4}x^2 \cdot \sin(x) + \dfrac{1}{2}x \cdot \cos(x) - \dfrac{1}{2} \sin(x) + C
\end{align*}

```{dropdown} Uitwerking

Primitiveer:
\begin{align*}
    f(x) = \dfrac{1}{4}x^2\cos(x)
\end{align*}

Dus, 
\begin{align}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx
\end{align}

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:
\begin{align}
    u &= \dfrac{1}{4}x^2 \\
    dv &= \cos(x) \, dx
\end{align}

Bepaal $du$:
\begin{align}
    \dfrac{du}{dx} &= \dfrac{1}{2}x \\
    du &= \dfrac{1}{2}x \, dx  {\color{blue} \quad  \text{(1p)}}
\end{align}

Bepaal de functie $v$:
\begin{align}
    dv &= \cos(x) \, dx  \\
    \dfrac{dv}{dx} &= \cos(x) \\
    v &= \sin(x) {\color{blue} \quad  \text{(1p)}}
\end{align}

Toepassen van de regel voor partieel integreren geeft:
\begin{align}
   \int u \, dv &= uv - \int v \, du \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int \sin(x) \dfrac{1}{2}x \, dx {\color{blue} \quad  \text{(1p)}}\\
     &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
\end{align}

De integraal $\int \dfrac{1}{2}x \sin(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.
\begin{align}
   \int \dfrac{1}{2}x \sin(x) \, dx
\end{align}

Kies de functie $u$ en $dv$:
\begin{align}
    u &= \dfrac{1}{2}x \\
    dv &= \sin(x) \, dx
\end{align}

Bepaal $du$:
\begin{align}
    \dfrac{du}{dx} &= \dfrac{1}{2} \\
    du &= \dfrac{1}{2} \, dx  {\color{blue} \quad  \text{(1p)}}
\end{align}

Bepaal de functie $v$:
\begin{align}
    dv &= \sin(x) \, dx  \\
    \dfrac{dv}{dx} &= \sin(x) \\
    v &= -\cos(x)  {\color{blue} \quad  \text{(1p)}}
\end{align}

Toepassen van de regel voor partieel integreren geeft:
\begin{align}
   \int u \, dv &= uv - \int v \, du \\
    &= \dfrac{1}{2}x \cdot -\cos(x) - \int -\cos(x) \dfrac{1}{2} \, dx {\color{blue} \quad  \text{(1p)}}\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \int \cos(x)  \, dx\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C  {\color{blue} \quad  \text{(1p)}}
\end{align}

Dus,
\begin{align}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - (-\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C) \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) + \dfrac{1}{2}x \cdot \cos(x) - \dfrac{1}{2} \sin(x) + C  {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 9 (7 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
    \int \dfrac{-6x+14}{x^2+2x-3}  \, dx &= -8 \ln|x + 3 | + 2 \ln| x - 1| + C\\
\end{align*}

```{dropdown} Uitwerking

Bepaal de onbepaalde integraal:
\begin{align*}
    \int \dfrac{-6x+14}{x^2+2x-3}  \, dx
\end{align*}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{-6x+14}{(x+3)(x-1)} \, dx  {\color{blue} \quad  \text{(1p)}}
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
   A+B &= -6  {\color{blue} \quad  \text{(1p)}}\\
   -A + 3B &= 14  {\color{blue} \quad  \text{(1p)}}
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= -6 - B \\
   -1(-6-B) + 3B &= 14 \\
   6 + B + 3B &= 14 \\
   4B &= 8 \\
   B &= 2  {\color{blue} \quad  \text{(1p)}}
\end{align}

B invullen geeft:
\begin{align}
   A &= -6 - 2 \\
   A &= -8  {\color{blue} \quad  \text{(1p)}}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{-6x+14}{x^2+2x-3} \, dx & = \int \dfrac{-6x+14}{(x + 3)(x - 1)} \, dx\\
   &= \int \dfrac{ A }{ x + 3 } + \dfrac{ B }{ x - 1 } \, dx  {\color{blue} \quad  \text{(1p)}}\\
   &= \int \dfrac{ A }{ x + 3 } \, dx + \int \dfrac{ B }{ x - 1 } \, dx\\
   &= \int \dfrac{ -8 }{ x + 3 } \, dx + \int \dfrac{ 2 }{ x - 1 } \, dx\\
   &= -8 \int \dfrac{ 1 }{ x + 3 } \, dx + 2 \int \dfrac{ 1 }{ x - 1 } \, dx\\
   &= -8 \ln|x + 3 | + 2 \ln| x - 1| + C  {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````

<hr style="border:1px solid #9EA700">

## Opgave 10 (11 punten)

````{admonition} Antwoord
:class: important, dropdown

\begin{align*}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1}  \, dx &= \dfrac{1}{3}x^3 - x^2 + 3x - 4 \ln|x + 1 | - \frac{2}{ x + 1}  + C\\
\end{align*}

```{dropdown} Uitwerking

Bepaal de onbepaalde integraal:
\begin{align*}
    \int  \dfrac{x^4 + 1}{x^2 + 2x + 1}  \, dx
\end{align*}

De teller is groter dan de noemer, dus staartdeling maken.

\begin{align}
 x^2 + 2x + 1 \quad / &x^4 \quad \quad \quad \quad \quad \quad \quad \quad + 1 \backslash \quad x^2 - 2x + 3\\
&x^4 + 2x^3 + x^2 \\
&------------- \quad -\\
&\quad \quad -2x^3 - x^2 + 2x + 1 {\color{blue} \quad  \text{(1p)}} \\
&\quad \quad -2x^3 - 4x^2 - 2x \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad  3x^2 + 2x + 1 {\color{blue} \quad  \text{(1p)}} \\
&\quad \quad \quad \quad \quad \quad  3x^2 + 6x + 3 \\
&------------- \quad -\\
&\quad \quad \quad \quad \quad \quad \quad \quad  -4x - 2 {\color{blue} \quad  \text{(1p)}} \\
\end{align}

De rest is $-4x-2$, dus de uiteindelijke uitkomst is:
\begin{align}
& x^2 - 2x + 3 + \dfrac{-4x-2}{x^2+2x+1} = \\
& x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} {\color{blue} \quad  \text{(1p)}}
\end{align}

Dit geeft:
\begin{align}
 \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &=  \int x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} \, dx \\
\end{align}

De teller ontbinden in factoren:
\begin{align}
    \int \dfrac{4x + 2}{(x + 1)(x + 1)} \, dx {\color{blue} \quad  \text{(1p)}}
\end{align}

Toepassen van de regel voor breukensplitsen geeft:
\begin{align}
    &= \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } {\color{blue} \quad  \text{(1p)}} \\
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
   A &= 4 {\color{blue} \quad  \text{(1p)}} \\
   A + B &= {\color{blue} \quad  \text{(1p)}}
\end{align}

Oplossen en substitueren geeft:
\begin{align}
   A &= 4\\
   4 + B &= 2 \\
   B &= -2 {\color{blue} \quad  \text{(1p)}}
\end{align}

A en B invullen in de integraal en oplossen geeft:
\begin{align}
   \int \dfrac{x^4 + 1}{x^2 + 2x + 1} \, dx &= \int x^2 - 2x + 3 - \dfrac{4x+2}{x^2+2x+1} \, dx {\color{blue} \quad  \text{(1p)}}\\
   &= \int x^2 - 2x + 3 - \dfrac{4x + 2}{(x+1)(x+1)} \, dx\\
   &= \int (x^2 - 2x + 3) \, dx - \int \dfrac{4x + 2}{(x+1)(x+1)} \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ A }{ x + 1 } + \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ A }{ x + 1 } \, dx - \int \dfrac{ B }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx -\int \dfrac{ 4 }{ x + 1 } \, dx - \int \dfrac{ -2 }{ (x + 1)^2 } \, dx\\
   &= \int (x^2 - 2x + 3) \, dx - 4 \int \dfrac{ 1 }{ x + 1 } \, dx + 2 \int \dfrac{ 1 }{ (x + 1)^2 } \, dx\\
   &= \dfrac{1}{3}x^3 - x^2 + 3x - 4 \ln|x + 1 | - \frac{2}{ x + 1}  + C {\color{blue} \quad  \text{(1p)}}
\end{align}
```
````