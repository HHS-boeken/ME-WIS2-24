# 7.3 Complexe getallen in goniometrische vorm (poolvorm)

````{admonition} Theorie
:class: tip, dropdown open

Een complex getal $z$ wordt meestal geschreven als:

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
````


## 7.3.1 Complexe getallen in goniometrische vorm (poolvorm)

````{admonition} Voorbeeld 1:
:class: dropdown
Schrijf in exponentiële vorm
\begin{align*}
    z = 1 + \sqrt{3}i
\end{align*}

De modulus is:
\begin{align*}
    r = |z| &= \sqrt{ (1)^2 + (\sqrt{3})^2} \\
    &= \sqrt{4} \\
    &= 2
\end{align*}

Het argument is:
\begin{align*}
    \phi = arg(z) &= \tan^{-1} (\dfrac{ \sqrt{3} }{1}) \\
    &= \dfrac{\pi}{3}
\end{align*}

Schrijf in goniometrische vorm:
\begin{align*}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2(\cos \left(\dfrac{\pi}{3} \right)  + i \sin(\dfrac{\pi}{3}) )
\end{align*}
````




\subsection*{Voorbeeld: Zet \( z = 1 + i\sqrt{3} \) om naar de poolvorm}

\begin{align*}
a &= 1, \quad b = \sqrt{3} \\
r &= \sqrt{1^2 + (\sqrt{3})^2} = \sqrt{1 + 3} = \sqrt{4} = 2 \\
\theta &= \arctan\left( \frac{\sqrt{3}}{1} \right) = \frac{\pi}{3} \\
z &= 2 \left( \cos\left( \frac{\pi}{3} \right) + i \sin\left( \frac{\pi}{3} \right) \right)
\end{align*}
