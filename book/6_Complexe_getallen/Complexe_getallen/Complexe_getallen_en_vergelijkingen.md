# 7.7 Complexe getallen en vergelijkingen

## 7.7.1 Kwadratische vergelijkingen met complexe oplossingen

````{admonition} Theorie
:class: tip, dropdown open

Een kwadratische vergelijking heeft de vorm:

\begin{align*}
    az^2 + bz + c = 0
\end{align*}

waarbij $a, b, c \in \mathbb{R}$ (reële getallen), en $a \ne 0$.

De oplossingen worden gegeven door de **abc-formule**:

\begin{align*}
    z = \frac{-b \pm \sqrt{D}}{2a}, \quad \text{waarbij} \quad D = b^2 - 4ac
\end{align*}

**Gevallen van de discriminant**

|Discriminant $D$| Soort oplossingen | Aantal oplossingen|
|----|-----|---|
| $D>0$ | Twee verschillende reële oplossingen|2|
| $D=0$ | Eén reële oplossing (dubbel)  |1|
| $D<0$ | Twee complexe geconjugeerde oplossingen |2|


**Bij $D < 0$: complexe oplossingen**

Als $D < 0$, dan is:

\begin{align*}
    \sqrt{D} = \sqrt{-d} = i\sqrt{d}, \quad \text{waarbij } d = -D > 0
\end{align*}

De oplossingen zijn dan:
\begin{align*}
    z = \frac{-b \pm i\sqrt{d}}{2a}
\end{align*}

Dit levert een complex geconjugeerd paar:
\begin{align*}
    z_1 = x + iy, \quad z_2 = x - iy
\end{align*}

```{admonition} Veelvoorkomende fouten
:class: warning

\begin{enumerate}
    \item Vergeten dat \( \sqrt{-D} = i\sqrt{D} \).\\
    Bijvoorbeeld: \( \sqrt{-36} \neq -6 \), maar \( \sqrt{-36} = 6i \)

    \item Denken dat complexe oplossingen niet kunnen.\\
    In technische contexten zijn complexe oplossingen juist belangrijk (zoals bij trillingen of signalen).

    \item \textbf{Ongeldig splitsen van breuken.}\\
    Bijvoorbeeld:
    \[
    \frac{-4 \pm 6i}{2} \Rightarrow \text{fout: } -4 \pm \frac{6i}{2}
    \]
    \textbf{Correct is:}
    \[
    \frac{-4 \pm 6i}{2} = \frac{-4}{2} \pm \frac{6i}{2} = -2 \pm 3i
    \]
\end{enumerate}



\section*{7. Belangrijk inzicht}
Als een kwadratische vergelijking reële coëfficiënten heeft, dan zijn complexe oplossingen altijd elkaars geconjugeerden.\\

Dus als \( z = a + bi \) een oplossing is, dan is ook \( \bar{z} = a - bi \) een oplossing.

\section*{8. Samenvatting}
\begin{itemize}
    \item Gebruik altijd de abc-formule
    \item Bij \( D < 0 \): gebruik \( \sqrt{D} = i\sqrt{-D} \)
    \item De oplossingen zijn dan complex geconjugeerd
    \item Controleer je antwoord door terug te substitueren
\end{itemize}
```
````



````{admonition} Voorbeeld 1: Kwadratische vergelijkingen met complexe oplossingen
:class: dropdown

los op in $\mathbb{C}$:
\begin{align*}
    z^2 + 4z + 13 = 0
\end{align*}

Bereken de discriminant $D$:
\begin{align}
    D & = b^2 - 4ac \\
    &= 4^2 - 4 \cdot 1 \cdot 13  \\
    &= 16 - 52 \\
    &= -36
\end{align}

Gebruik de ABC-formule:
\begin{align}
    z &= \dfrac{-4 \pm \sqrt{-36} }{2 \cdot 1} \\
    z &= \dfrac{-4 \pm \sqrt{-36} }{ 2 } \\
    z &= \dfrac{-4 \pm i\sqrt{36} }{2} \\
    z &= \dfrac{-4 \pm 6i }{2}
\end{align}

Dus:
\begin{align}
    z_1 &= \dfrac{-4}{2} + \dfrac{6i }{2} = -2 + 3i \\
    z_2 &= \dfrac{-4}{2} - \dfrac{6i }{2} = -2 - 3i
\end{align}
````

````{admonition} Oefening 1
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    2z^2 + 3z + 5 = 0
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    2z^2 + 3z + 5 = 0
\end{align*}

Bereken de discriminant $D$:
\begin{align}
    D & = b^2 - 4ac \\
    &= 3^2 - 4 \cdot 2 \cdot 5  \\
    &= 9 - 40 \\
    &= -31
\end{align}

Gebruik de ABC-formule:
\begin{align}
    z &= \dfrac{-3 \pm \sqrt{-31} }{2 \cdot 2} \\
    z &= \dfrac{-3 \pm \sqrt{-31} }{ 4 } \\
    z &= \dfrac{-3 \pm i\sqrt{31} }{ 4 } 
\end{align}

Dus:
\begin{align}
    z_1 &= -\dfrac{3}{4} + \dfrac{i\sqrt{31} }{4} \\
    z_2 &= -\dfrac{3}{4} - \dfrac{i\sqrt{31}  }{4}
\end{align}
```
````


````{admonition} Oefening 2
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    -3z^2 + 6z - 10 = 0
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    -3z^2 + 6z - 10 = 0
\end{align*}

Bereken de discriminant $D$:
\begin{align}
    D & = b^2 - 4ac \\
    &= 6^2 - 4 \cdot (-3) \cdot -10  \\
    &= 36 - 120 \\
    &= -84
\end{align}

Gebruik de ABC-formule:
\begin{align}
    z &= \dfrac{-6 \pm \sqrt{-84} }{2 \cdot -3} \\
    z &= \dfrac{-6 \pm \sqrt{-84} }{ -6 } \\
    z &= \dfrac{-6 \pm i\sqrt{84} }{ -6 } \\
    z &= \dfrac{-6 \pm i2\sqrt{21} }{ -6 } 
\end{align}

Dus:
\begin{align}
    z_1 &= \dfrac{6}{6} + \dfrac{i2\sqrt{21} }{6} = 1 + \dfrac{i\sqrt{21} }{3}  \\
    z_2 &= \dfrac{6}{6} - \dfrac{i2\sqrt{21}  }{6} = 1 - \dfrac{i\sqrt{21} }{3}
\end{align}
```
````

## 7.7.2 

````{admonition} Voorbeeld 2: 
:class: dropdown

los op in $\mathbb{C}$:
\begin{align*}
    z^3 = 8
\end{align*}

Schrijf $8+0i$ in poolvorm:

De modulus is:
\begin{align}
    r = |8| &= \sqrt{ 8^2 + 0^2 } \\
    &= \sqrt{64} \\
    &= 8
\end{align}

Het argument is:
\begin{align}
    \phi = arg( 8+0i ) &= \tan^{-1} \left( \dfrac{0}{8} \right) \\
     &= 0 + k \cdot 2\pi
\end{align}

Dus:
\begin{align}
    z^3 = 8 \left( \cos\left( k \cdot 2\pi \right) + i\sin\left( k \cdot 2\pi \right) \right)
\end{align}

We zoeken de derde machtswortels, dat zijn:
\begin{align}
    z_k = \sqrt[3]{8} \cdot \left( \cos\left( \frac{   k \cdot 2\pi}{3} \right) + i \sin\left( \frac{ k \cdot 2\pi}{3} \right) \right)
\quad \text{voor } k = 0, 1, 2
\end{align}

Omdat $\sqrt[3]{8} = 2$, wordt dit:
\begin{align}
    z_k = 2 \left( \cos\left( \frac{ k \cdot 2\pi}{3} \right) + i \sin\left( \frac{ k \cdot 2\pi}{3} \right) \right)
\end{align}

Bereken de drie wortels:

Voor $k = 0$:
\begin{align}
    \theta = 0 \Rightarrow z_0 &= 2\left( \cos\left( 0 \right) + i \sin\left( 0 \right) \right) \\
    &= 2\left( 1 + i \cdot 0 \right) \\
    &= 2
\end{align}

Voor $k = 1$:
\begin{align}
    \theta = \frac{2\pi}{3} \Rightarrow z_1 &= 2\left( \cos\left( \frac{2\pi}{3} \right) + i \sin\left( \frac{2\pi}{3} \right) \right) \\
    &= 2\left( -\frac{1}{2} + i \cdot \frac{\sqrt{3}}{2} \right) \\
    &= -1 + i \cdot \sqrt{3}
\end{align}

Voor $k = 2$:
\begin{align}
    \theta = \frac{4\pi}{3} \Rightarrow z_2 &= 2\left( \cos\left( \frac{4\pi}{3} \right) + i \sin\left( \frac{4\pi}{3} \right) \right) \\
    &= 2\left( -\frac{1}{2} - i \cdot \frac{\sqrt{3}}{2} \right) \\
    &= -1 - i \cdot \frac{\sqrt{3}}{2}
\end{align}

````

````{admonition} Oefening 3
:class: important, dropdown

los op in $\mathbb{C}$:
\begin{align*}
    z^4 = -16
\end{align*}

Schrijf $8+0i$ in poolvorm:

De modulus is:
\begin{align}
    r = |-16| &= \sqrt{ (-16)^2 + 0^2 } \\
    &= \sqrt{256} \\
    &= 16
\end{align}

Het argument is:
\begin{align}
    \phi = arg( -16+0i ) &= \tan^{-1} \left( \dfrac{0}{-16} \right) \\
     &= \pi + k \cdot 2\pi
\end{align}

Dus:
\begin{align}
    z^4 = 16 \left( \cos\left( \pi + k \cdot 2\pi \right) + i\sin\left( pi + k \cdot 2\pi \right) \right)
\end{align}

We zoeken de vierde machtswortels, dat zijn:
\begin{align}
    z_k = \sqrt[4]{16} \cdot \left( \cos\left( \pi\frac{  \pi + k \cdot 2\pi}{4} \right) + i \sin\left( \frac{ \pi + k \cdot 2\pi}{4} \right) \right)
    \quad \text{voor } k = 0, 1, 2, 3
\end{align}

Omdat $\sqrt[4]{16} = 2$, wordt dit:
\begin{align}
    z_k = 2 \left( \cos\left( \frac{ \pi + k \cdot 2\pi}{4} \right) + i \sin\left( \frac{ \pi + k \cdot 2\pi}{4} \right) \right)
\end{align}

Bereken de drie wortels:

Voor $k = 0$:
\begin{align}
    \theta = \frac{\pi}{4}  \Rightarrow z_0 &= 2\left( \cos\left(  \frac{\pi}{4}  \right) + i \sin\left(  \frac{\pi}{4}  \right) \right) \\
   &= 2\left( \frac{ \sqrt{2}}{2} + i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= \sqrt{2} + i \cdot \sqrt{2}
\end{align}

Voor $k = 1$:
\begin{align}
    \theta = \frac{3\pi}{4} \Rightarrow z_1 &= 2\left( \cos\left( \frac{3\pi}{4} \right) + i \sin\left( \frac{3\pi}{4} \right) \right) \\
   &= 2\left( -\frac{ \sqrt{2}}{2} + i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= -\sqrt{2} + i \cdot \sqrt{2}
\end{align}

Voor $k = 2$:
\begin{align}
    \theta = \frac{5\pi}{4} \Rightarrow z_2 &= 2\left( \cos\left( \frac{5\pi}{4} \right) + i \sin\left( \frac{5\pi}{4} \right) \right) \\
   &= 2\left( -\frac{ \sqrt{2}}{2} - i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= -\sqrt{2} - i \cdot \sqrt{2}
\end{align}

Voor $k = 3$:
\begin{align}
    \theta = \frac{7\pi}{4} \Rightarrow z_2 &= 2\left( \cos\left( \frac{7\pi}{4} \right) + i \sin\left( \frac{7\pi}{4} \right) \right) \\
   &= 2\left( \frac{ \sqrt{2}}{2} - i \cdot \frac{\sqrt{2}}{2} \right) \\
    &= \sqrt{2} - i \cdot \sqrt{2}
\end{align}

````