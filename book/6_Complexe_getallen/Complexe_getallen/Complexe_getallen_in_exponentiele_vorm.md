# 7.5 Complexe getallen in Exponentiële vorm

````{admonition} Theorie
:class: tip, dropdown open

Een complex getal $z$ kan worden geschreven in **algebraïsche vorm / cartesische vorm**:

\begin{align*}
    z = a + bi
\end{align*}
met $a$ het reële deel en $b$ het imaginaire deel.

In **goniometrische vorm of poolvorm** wordt hetzelfde getal geschreven als:
\begin{align*}
    z = r(\cos \theta + i \sin \theta)
\end{align*}

\begin{align*}
    r = |z| = \sqrt{a^2 + b^2} \text{de modulus} \\
    \theta = \arg(z) \text{het argument (de hoek met de positieve reële as, in radialen)} \\
\end{align*}

**Euler’s formule**

De Eulerformule legt het verband tussen de goniometrische en exponentiële vormen van een complex getal:

\begin{align*}
    e^{i\theta} = \cos \theta + i \sin \theta
\end{align*}

Hiermee kunnen we een complex getal ook schrijven als:
\begin{align*}
    z = r e^{i\theta}
\end{align*}
Deze vorm heet de **exponentiële vorm** van een complex getal.

```{admonition} Voordelen van de exponentiële vorm
:class: warning

De exponentiële vorm is vooral handig bij vermenigvuldigen, delen, machtsverheffen en worteltrekken van complexe getallen.

\begin{align*}
    z_1 = r_1 e^{i\theta_1},  \quad z_2 = r_2 e^{i\theta_2}
\end{align*}

**Vermenigvuldigen:**
\begin{align*}
    z_1 \cdot z_2 = r_1 r_2 e^{i(\theta_1 + \theta_2)}
\end{align*}

**Delen:**
\begin{align*}
    \frac{z_1}{z_2} = \frac{r_1}{r_2} e^{i(\theta_1 - \theta_2)}
\end{align*}

**Macht van een complex getal (De Moivre):**
\begin{align*}
    z^n = (r e^{i\theta})^n = r^n e^{in\theta}
\end{align*}

**Wortel (n-de machtswortel):**
\begin{align*}
    \sqrt[n]{z} = \sqrt[n]{r} \cdot e^{i\left(\frac{\theta + 2k\pi}{n}\right)} \quad \text{voor} \quad k = 0, 1, \dots, n-1
\end{align*}

```
````

## 7.5.1

````{admonition} Voorbeeld 1:
:class: dropdown
Schrijf in exponentiële vorm
\begin{align*}
    z = 1 + i
\end{align*}

De modulus is:
\begin{align*}
    r = |z| = \sqrt{1^2 + 1^2} = \sqrt{2}
\end{align*}

Het argument is:
\begin{align*}
    \phi = arg(z) = \tan^{-1} (\dfrac{1}{2}) = \dfrac{\pi}{4}
\end{align*}

Schrijf $z=1+i$ in exponentiële vorm:
\begin{align*}
    z &= r \cdot e^{\phi i} \\
    z &= \sqrt{2} e^{\frac{\pi}{4} i}
\end{align*}
````

````{admonition} Oefening 1
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

```
````

````{admonition} Oefening 2
:class: important, dropdown

```{admonition} Uitwerking
:class: important, dropdown

```
````