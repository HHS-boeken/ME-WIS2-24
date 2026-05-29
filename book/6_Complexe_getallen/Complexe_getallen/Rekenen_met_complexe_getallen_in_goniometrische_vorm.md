# 7.4 Rekenen met complexe getallen in goniometrische vorm

## 7.4.1 De stelling van De Moivre

::::{admonition} Voorbeeld 1:
:class: dropdown

Bereken de volgende uitdrukking exact en schrijf het antwoord in de vorm $z = a + bi$:

$$
    z = (1+i)^8
$$

Schrijf $1+1i$ in poolvorm:

De modulus is:

$$
\begin{align}
    r = |z| &= \sqrt{ (1)^2 + (1)^2 } \\
    &= \sqrt{2}
\end{align}
$$

Het argument is:

$$
\begin{align}
    \theta = arg( z ) &= \tan^{-1} \left( \dfrac{1}{1} \right) \\
     &= \dfrac{\pi}{4}
\end{align}
$$

Dus:

$$
    z = \left( \sqrt{2} \left( \cos\left( \dfrac{\pi}{4} \right) + i\sin\left( \dfrac{\pi}{4} \right) \right) \right)^8
$$

Gebruik de formule van De Moivre:

$$
\begin{align}
    z &= (\sqrt{2})^8 \left( \cos\left( 8 \cdot \dfrac{\pi}{4} \right) + i\sin\left( 8 \cdot \dfrac{\pi}{4} \right) \right)  \\
    z &=  2^4 \left( \cos\left( 2\pi \right) + i\sin\left( 2\pi \right) \right)  \\
    z &=  16 \left( \cos\left( 2\pi \right) + i\sin\left( 2\pi \right) \right)  \\
    z &=  16 \left( \cos\left( 0 \right) + i\sin\left( 0 \right) \right)  \\
    z &= 16(1 + 0i) \\
    z &= 16
\end{align}
$$
::::

::::{admonition} Oefening 1
:class: important, dropdown

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm $z = a + bi$. Rond af op gehele getallen:

$$
    z = (2+3i)^6
$$

:::{Uitwerking}

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm z = a + bi. Rond af op gehele getallen:

$$
    z = (2+3i)^6
$$

Schrijf $2+3i$ in poolvorm:

De modulus is:

$$
\begin{align}
    r = |z| &= \sqrt{ (2)^2 + (3)^2 } \\
    &= \sqrt{4 + 9}\\
    &= \sqrt{13}
\end{align}
$$

Het argument is:

$$
\begin{align}
    \theta = arg( z ) &= \tan^{-1} \left( \dfrac{3}{2} \right) \\
     &= 0.983
\end{align}
$$

Dus:

$$
    z = \left( \sqrt{13} \left( \cos\left( 0.983 \right) + i\sin\left( 0.983 \right) \right) \right)^6
$$

Gebruik de formule van De Moivre:

$$
\begin{align}
    z &= (\sqrt{13})^6 \left( \cos\left( 6 \cdot 0.983 \right) + i\sin\left( 6 \cdot 0.983 \right) \right)  \\
    z &=  13^3 \left( \cos\left( 5.898 \right) + i\sin\left( 5.898 \right) \right)  \\
    z &=  2197 \left( \cos\left( 5.898 \right) + i\sin\left( 5.898 \right) \right)  \\
    z &\approx 2025 - 828i
\end{align}
$$

:::
::::

::::{admonition} Oefening 2
:class: important, dropdown

Bereken de volgende uitdrukking exact en schrijf het antwoord in de vorm $z = a + bi$:

$$
    z = (1+\sqrt{3}i)^6
$$

:::{Uitwerking}

Bereken de volgende uitdrukking en schrijf het antwoord in de vorm $z = a + bi$. Rond af op gehele getallen:

$$
    z = (1+\sqrt{3}i)^6
$$

Schrijf $1+\sqrt{3}i$ in poolvorm:

De modulus is:

$$
\begin{align*}
    r = |z| &= \sqrt{ (1)^2 + (\sqrt{3})^2 } \\
    &= \sqrt{1 + 3}\\
    &= \sqrt{4} \\
    &= 2
\end{align*}
$$

Het argument is:

$$
\begin{align*}
    \theta = arg( z ) &= \tan^{-1} \left( \dfrac{\sqrt{3}}{1} \right) \\
     &= \dfrac{\pi}{3}
\end{align*}
$$

Dus:

$$
    z = \left( 2 \left( \cos\left( \dfrac{\pi}{3} \right) + i\sin\left( \dfrac{\pi}{3}\right) \right) \right)^6
$$

Gebruik de formule van De Moivre:

$$
\begin{align*}
    z &= (2)^6 \left( \cos\left( 6 \cdot \dfrac{\pi}{3} \right) + i\sin\left( 6 \cdot \dfrac{\pi}{3} \right) \right)  \\
    z &= 64 \left( \cos\left( 2\pi \right) + i\sin\left( 2 \pi \right) \right)  \\
    z &= 64 \left( 1 + 0i \right)  \\
    z &= 64
\end{align*}
$$

:::
::::
