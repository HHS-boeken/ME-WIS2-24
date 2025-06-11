# 7.7 Complexe getallen en vergelijkingen

## 7.7.1 Kwadratische vergelijkingen met complexe oplossingen


Een kwadratische vergelijking heeft de vorm:

\begin{align*}
    az^2 + bz + c = 0
\end{align*}

waarbij \( a, b, c \in \mathbb{R} \) (reële getallen), en \( a \ne 0 \).

De oplossingen worden gegeven door de \textbf{abc-formule}:

\begin{align*}
    z = \frac{-b \pm \sqrt{D}}{2a}, \quad \text{waarbij} \quad D = b^2 - 4ac
\end{align*}

**Gevallen van de discriminant**

\begin{center}
\begin{tabular}{@{}lll@{}}
\toprule
\textbf{Discriminant \( D \)} & \textbf{Soort oplossingen} & \textbf{Aantal oplossingen} \\
\midrule
\( D > 0 \) & Twee verschillende reële              & 2 \\
\( D = 0 \) & Eén reële oplossing (dubbel)         & 1 \\
\( D < 0 \) & Twee complexe geconjugeerde          & 2 \\
\bottomrule
\end{tabular}
\end{center}

\subsection*{Bij \( D < 0 \): complexe oplossingen}
Als \( D < 0 \), dan is:
\[
\sqrt{D} = \sqrt{-d} = i\sqrt{d}, \quad \text{waarbij } d = -D > 0
\]
De oplossingen zijn dan:
\[
z = \frac{-b \pm i\sqrt{d}}{2a}
\]
Dit levert een complex geconjugeerd paar:
\[
z_1 = x + iy, \quad z_2 = x - iy
\]

\section*{4. Voorbeeld 1}
Los op:
\[
z^2 + 4z + 13 = 0
\]
Discriminant:
\[
D = 4^2 - 4 \cdot 1 \cdot 13 = 16 - 52 = -36
\]
Oplossingen:
\[
z = \frac{-4 \pm \sqrt{-36}}{2} = \frac{-4 \pm 6i}{2} = -2 \pm 3i
\]
\textbf{Antwoord:} \( z_1 = -2 + 3i \), \( z_2 = -2 - 3i \)

\section*{5. Veelvoorkomende fouten}
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

\section*{6. Voorbeeld 2 (met parameter)}
Los op:
\[
2z^2 + 3z + k = 0
\]
Geef voorwaarden voor \( k \) zodat de oplossingen complex maar niet reëel zijn.

Voorwaarde: \( D < 0 \)
\[
D = 3^2 - 4 \cdot 2 \cdot k = 9 - 8k < 0 \Rightarrow k > \frac{9}{8}
\]

Dus: voor \( k > \frac{9}{8} \) zijn de oplossingen complex (niet-reëel).

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

\end{document}



````{admonition} Voorbeeld 1:
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