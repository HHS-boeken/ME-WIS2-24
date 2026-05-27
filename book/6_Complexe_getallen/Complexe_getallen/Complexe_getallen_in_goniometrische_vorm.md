# 7.3 Complexe getallen in goniometrische vorm (poolvorm)

::::{admonition} Theorie
:class: tip, dropdown open

Een complex getal $z$ kan worden geschreven in **algebraïsche vorm / cartesische vorm**:

\begin{align*}
    z = a + bi
\end{align*}

met:
\begin{align*}
    a &=\text{ het reële deel} \\
    b &=\text{ het imaginaire deel} \\
    i &=\text{ de imaginaire eenheid, met }  i^2 = -1
\end{align*}

**Poolvorm (goniometrische vorm)**

Een complex getal kan ook worden uitgedrukt in termen van een modulus en een hoek. Dat noemen we de **poolvorm** of **goniometrische vorm**:

\begin{align*}
    z = r \left( \cos \theta + i \sin \theta \right)
\end{align*}

met:
\begin{align*}
    r &= |z| = \sqrt{a^2 + b^2} \quad \text{ de modulus van  $z$ } \\
    \theta &= \arg(z) \quad \text{het argument (de hoek die $z$ maakt met de positieve reële as, in radialen) }
\end{align*}

**Modulus en argument berekenen**

Voor een complex getal $z = a + bi$ geldt:

\begin{align*}
    r &= \sqrt{a^2 + b^2} \\
    \theta &= \arctan\left( \frac{b}{a} \right)
\end{align*}

Let op: de uitkomst van de tangens is afhankelijk van het kwadrant waarin  $z$ ligt. Gebruik daarom een schets voor de juiste hoek.

**Overgang naar poolvorm**

Om $z = a + bi$ om te zetten naar de poolvorm:

1. Bereken $r = \sqrt{a^2 + b^2}$
1. Bepaal de hoek $\theta = \arg(z)$, eventueel als negatieve of positieve waarde
1. Vul in: $z = r(\cos \theta + i \sin \theta)$

Als $z_1 = r_1(\cos \theta_1 + i \sin \theta_1)$ en $z_2 = r_2(\cos \theta_2 + i \sin \theta_2)$, dan geldt:

**Vermenigvuldigen**

\begin{align*}
    z_1 \cdot z_2 = r_1 r_2 \left[ \cos(\theta_1 + \theta_2) + i \sin(\theta_1 + \theta_2) \right]
\end{align*}

**Delen**

\begin{align*}
    \frac{z_1}{z_2} = \frac{r_1}{r_2} \left[ \cos(\theta_1 - \theta_2) + i \sin(\theta_1 - \theta_2) \right]
\end{align*}
::::

<iframe
  src="complex_vlak1.html"
  width="100%"
  height="850px"
  style="border:none;">
</iframe>

## 7.3.1 Complexe getallen in goniometrische vorm (poolvorm)

::::{admonition} Voorbeeld 1:
:class: dropdown

Schrijf in goniometrische vorm

$$
    z = 1 + \sqrt{3}i
$$

De modulus is:

$$
\begin{align*}
    r = |z| &= \sqrt{ (1)^2 + (\sqrt{3})^2} \\
    &= \sqrt{4} \\
    &= 2
\end{align*}
$$

Het argument is:

$$
\begin{align*}
    \theta = arg(z) &= \tan^{-1} \left( \dfrac{ \sqrt{3} }{1} \right) \\
    &= \dfrac{\pi}{3}
\end{align*}
$$

Schrijf in goniometrische vorm:

$$
\begin{align*}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2 \left( \cos \left( \dfrac{\pi}{3} \right)  + i \sin \left( \dfrac{\pi}{3} \right) \right)
\end{align*}
$$
::::

::::{admonition} Oefening 1
:class: important, dropdown

Schrijf in goniometrische vorm

$$
    z = -\sqrt{3} + i
$$

:::{dropdown} Uitwerking

Schrijf in goniometrische vorm

$$
    z = -\sqrt{3} + i
$$

De modulus is:

$$
\begin{align*}
    r = |z| &= \sqrt{ (-\sqrt{3})^2 + (1)^2}  \\
    &= \sqrt{ 3 + 1  } \\
    &= \sqrt{4}  \\
    &= 2
\end{align*}
$$

Het argument is:

$$
\begin{align*}
    \theta = arg(z) &=  \tan^{-1} \left( \dfrac{1}{ -\sqrt{3} } \right) \\
    &= -\dfrac{ \pi}{6}
\end{align*}
$$

Omdat $z$ in het tweede kwadrant ligt:

$$
\begin{align*}
    \phi    &= \pi - \dfrac{\pi}{6} \\
            &= \dfrac{5\pi}{6}
\end{align*}
$$

Schrijf in goniometrische vorm:

$$
\begin{align*}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2 \left( \cos \left( \dfrac{5\pi}{6} \right)  + i \sin \left( \dfrac{5\pi}{6} \right) \right)
\end{align*}
$$
:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Schrijf in goniometrische vorm

$$
    z = -2 - 2i
$$

:::{dropdown} Uitwerking

Schrijf in goniometrische vorm

$$
    z = -2 - 2i
$$

De modulus is:

$$
\begin{align*}
    r = |z| &= \sqrt{ (-2)^2 + (-2)^2}  \\
    &= \sqrt{ 4 + 4  } \\
    &= \sqrt{8}  \\
    &= 2\sqrt{2}
\end{align*}
$$

Het argument is:

$$
\begin{align*}
    \theta = arg(z) &=  \tan^{-1} \left( \dfrac{-2}{ -2 } \right) \\
    &=  \tan^{-1} (1)\\
    &= \dfrac{\pi}{4}
\end{align*}
$$

Omdat $z$ in het derde kwadrant ligt:

$$
\begin{align*}
    \phi    &= -\pi + \dfrac{\pi}{4} \\
            &= -\dfrac{3\pi}{4}
\end{align*}
$$

Schrijf in goniometrische vorm:

$$
\begin{align*}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2\sqrt{2} \left( \cos \left( -\dfrac{3\pi}{4} \right)  + i \sin \left( -\dfrac{3\pi}{4} \right) \right)
\end{align*}
$$
:::
::::
