# 7.4 Rekenen met complexe getallen in goniometrische vorm

## 7.4.1 Vermenigvuldigen van complexe getallen

````{admonition} Voorbeeld 1:
:class: dropdown

Gegeven:

$z_1 = 2 + 6i$ en $z_2 = 3 + 4i$

Bereken $z_1 \cdot z_2$ en schrijf in de goniometrische vorm:

De modulus is:
\begin{align}
    r_1 = |z_1| &= \sqrt{ (2)^2 + (6)^2} \\
    &= \sqrt{40} \\
    &= 2\sqrt{10}
\end{align}

Het argument is:
\begin{align}
    \theta_1 = arg(z_1) &= \tan^{-1} \left( \dfrac{ 6 }{2} \right) \\
    &= 1.249
\end{align}

Schrijf in goniometrische vorm:
\begin{align}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2\sqrt{10} \left( \cos \left( 1.249 \right)  + i \sin \left( 1.249 \right) \right)
\end{align}

De modulus is:
\begin{align}
    r_2 = |z_2| &= \sqrt{ (2)^2 + (6)^2} \\
    &= \sqrt{40} \\
    &= 2\sqrt{10}
\end{align}

Het argument is:
\begin{align}
    \theta_2 = arg(z_2) &= \tan^{-1} \left( \dfrac{ 6 }{2} \right) \\
    &= 1.249
\end{align}

Schrijf in goniometrische vorm:
\begin{align}
    z &= r(\cos \theta + i \sin \theta)\\
    z &= 2\sqrt{10} \left( \cos \left( 1.249 \right)  + i \sin \left( 1.249 \right) \right)
\end{align}


\begin{align}
    z_1 \cdot z_2   &= (2 + 6i) \cdot (3 + 4i) \\
                &= 2 \cdot 3 + 6i \cdot 3 + 2 \cdot 4i + 6i \cdot 4i \\
                &= 6 + 18i + 8i + 24i^2 \\
                &= 6 + 26i + 24 \cdot (-1) \\
                &= 6 + 26i - 24 \\
                &= -18 + 26i
\end{align}

````

````{admonition} Oefening 1
:class: important, dropdown

$z_1 = 3 - 6i$ en $z_2 = 1 + 7i$

Bereken $z_1 \cdot z_2$ en schrijf in de vorm $a + bi$:

```{admonition} Uitwerking
:class: important, dropdown

Gegeven:

$z_1 = 3 - 6i$ en $z_2 = 1 + 7i$

Bereken $z_1 \cdot z_2$ en schrijf in de vorm $a + bi$:

\begin{align}
    z_1 \cdot z_2   &= (3 - 6i) \cdot (1 + 7i) \\
                &= 3 \cdot 1 - 6i \cdot 1 + 3 \cdot 7i - 6i \cdot 7i \\
                &= 3 - 6i + 21i - 42i^2 \\
                &= 3 + 15i - 42 \cdot (-1) \\
                &= 3 + 15i + 42 \\
                &= 45 + 15i
\end{align}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Gegeven:

$z_1 = -3 - 9i$ en $z_2 = 1 + 2i$

Bereken $z_1 \cdot z_2$ en schrijf in de vorm $a + bi$:

```{admonition} Uitwerking
:class: important, dropdown

Gegeven:

$z_1 = -3 - 9i$ en $z_2 = 1 + 2i$

Bereken $z_1 \cdot z_2$ en schrijf in de vorm $a + bi$:

\begin{align}
    z_1 \cdot z_2   &= (-3 - 9i) \cdot (1 + 2i) \\
                &= -3 \cdot 1 -9i \cdot 1 -3 \cdot 2i -9i \cdot 2i \\
                &= -3 -9i -6i -18i^2 \\
                &= -3 - 15i - 18 \cdot (-1) \\
                &= -3 -15i + 18 \cdot \\
                &= 15 - 15i
\end{align}
```
````

## 7.4.2 delen van complexe getallen

````{admonition} Voorbeeld 2:
:class: dropdown
6
````

````{admonition} Oefening 3
:class: important, dropdown

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm z = a + bi:

```{admonition} Uitwerking
:class: important, dropdown

```
````

````{admonition} Oefening 4
:class: important, dropdown

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm z = a + bi:

```{admonition} Uitwerking
:class: important, dropdown

```
````


## 7.4.3 De stelling van De Moivre

````{admonition} Voorbeeld 3:
:class: dropdown

Bereken de volgende uitdrukking exact en schrijf het antwoord in de vorm z = a + bi:

\begin{align*}
    z = (1+i)^8
\end{align*}

Schrijf $1+1i$ in poolvorm:

De modulus is:
\begin{align}
    r = |z| &= \sqrt{ (1)^2 + (1)^2 } \\
    &= \sqrt{2}
\end{align}

Het argument is:
\begin{align}
    \theta = arg( z ) &= \tan^{-1} \left( \dfrac{1}{1} \right) \\
     &= \dfrac{\pi}{4}
\end{align}

Dus:
\begin{align}
    z = \left( \sqrt{2} \left( \cos\left( \dfrac{\pi}{4} \right) + i\sin\left( \dfrac{\pi}{4} \right) \right) \right)^8
\end{align}

Gebruik de formule van De Moivre:
\begin{align}
    z = (\sqrt{2})^8 \left( \cos\left( 8 \cdot \dfrac{\pi}{4} \right) + i\sin\left( 8 \cdot \dfrac{\pi}{4} \right) \right)  \\
    z =  2^4 \left( \cos\left( 2\pi \right) + i\sin\left( 2\pi \right) \right)  \\
    z =  16 \left( \cos\left( 2\pi \right) + i\sin\left( 2\pi \right) \right)  \\
    z =  16 \left( \cos\left( 0 \right) + i\sin\left( 0 \right) \right)  \\
    z = 16(1_0i) \\
    z= 16
\end{align}
````

````{admonition} Oefening 5
:class: important, dropdown

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm z = a + bi. Rond af op gehele getallen:
\begin{align*}
    z = (2+3i)^6
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm z = a + bi. Rond af op gehele getallen:
\begin{align*}
    z = (2+3i)^6
\end{align*}

Schrijf $2+3i$ in poolvorm:

De modulus is:
\begin{align}
    r = |z| &= \sqrt{ (2)^2 + (3)^2 } \\
    &= \sqrt{4 + 9}\\
    &= \sqrt{13}
\end{align}

Het argument is:
\begin{align}
    \theta = arg( z ) &= \tan^{-1} \left( \dfrac{3}{2} \right) \\
     &= 0.983
\end{align}

Dus:
\begin{align}
    z = \left( \sqrt{13} \left( \cos\left( 0.983 \right) + i\sin\left( 0.983 \right) \right) \right)^6
\end{align}

Gebruik de formule van De Moivre:
\begin{align}
    z = (\sqrt{13})^6 \left( \cos\left( 6 \cdot 0.983 \right) + i\sin\left( 6 \cdot 0.983 \right) \right)  \\
    z =  13^3 \left( \cos\left( 5.898 \right) + i\sin\left( 5.898 \right) \right)  \\
    z =  2197 \left( \cos\left( 5.898 \right) + i\sin\left( 5.898 \right) \right)  \\
    z \approx 2025 - 828i
\end{align}
```
````

````{admonition} Oefening 6
:class: important, dropdown

Bereken de volgende uitdrukking exact en schrijf het antwoord in de vorm z = a + bi:

\begin{align*}
    z = (1+\sqrt{3}i)^6
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de volgende uitdrukking exact en schrijf het antwoord in de vorm z = a + bi:

\begin{align*}
    z = (1+\sqrt{3}i)^6
\end{align*}

```
````


