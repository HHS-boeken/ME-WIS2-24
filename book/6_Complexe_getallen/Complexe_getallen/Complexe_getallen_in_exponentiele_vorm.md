# 7.5 Complexe getallen in Exponentiële vorm

Een complex getal $z$ kan worden geschreven in \textit{algebraïsche vorm / cartesische vorm}:

\begin{align*}
    z = a + bi
\end{align*}
met $a$ het reële deel en $b$ het imaginaire deel.

In \textit{goniometrische vorm of poolvorm} wordt hetzelfde getal geschreven als:
\begin{align*}
    z = r(\cos \theta + i \sin \theta)
\end{align*}

\begin{itemize}
    \item \( r = |z| = \sqrt{a^2 + b^2} \) de modulus,
    \item \( \theta = \arg(z) \) het argument (de hoek met de positieve reële as, in radialen).
\end{itemize}

\subsection*{Euler’s formule}

De Eulerformule legt het verband tussen de goniometrische en exponentiële vormen van een complex getal:

\begin{align*}
    e^{i\theta} = \cos \theta + i \sin \theta
\end{align*}

Hiermee kunnen we een complex getal ook schrijven als:
\begin{align*}
    z = r e^{i\theta}
\end{align*}
Deze vorm heet de \textbf{exponentiële vorm} van een complex getal.

---
**Voordelen van de exponentiële vorm**

De exponentiële vorm is vooral handig bij vermenigvuldigen, delen, machtsverheffen en worteltrekken van complexe getallen.

\begin{align*}
z_1 = r_1 e^{i\theta_1}  \quad z_2 = r_2 e^{i\theta_2} 
\end{align*}

**Vermenigvuldigen**
\[
\Rightarrow z_1 \cdot z_2 = r_1 r_2 e^{i(\theta_1 + \theta_2)}
\]

**Delen**
\[
\frac{z_1}{z_2} = \frac{r_1}{r_2} e^{i(\theta_1 - \theta_2)}
\]

**Macht van een complex getal (De Moivre)**
\[
z^n = (r e^{i\theta})^n = r^n e^{in\theta}
\]

**Wortel (n-de machtswortel)**
\[
\sqrt[n]{z} = \sqrt[n]{r} \cdot e^{i\left(\frac{\theta + 2k\pi}{n}\right)} \quad \text{voor } k = 0, 1, \dots, n-1
\]

\subsection*{Voorbeeld 1: schrijf \( z = 1 + i \) in exponentiële vorm}

\begin{align*}
r &= |z| = \sqrt{1^2 + 1^2} = \sqrt{2} \\
\theta &= \arg(z) = \arctan\left(\frac{1}{1}\right) = \frac{\pi}{4} \\
z &= \sqrt{2} e^{i\pi/4}
\end{align*}

\subsection*{Voorbeeld 2: vermenigvuldig \( z_1 = 2 e^{i\pi/3} \) en \( z_2 = 3 e^{i\pi/6} \)}

\begin{align*}
z_1 z_2 &= 2 \cdot 3 \cdot e^{i\left(\frac{\pi}{3} + \frac{\pi}{6}\right)} \\
&= 6 e^{i\pi/2}
\end{align*}
