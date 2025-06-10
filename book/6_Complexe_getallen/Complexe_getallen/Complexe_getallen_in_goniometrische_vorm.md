# 7.3 Complexe getallen in goniometrische vorm (poolvorm)

Een complex getal $z$ wordt meestal geschreven als:

\begin{align*}
    z = a + bi
\end{align*}

met:
\begin{itemize}
    \item \( a \in \mathbb{R} \): het reële deel,
    \item \( b \in \mathbb{R} \): het imaginaire deel,
    \item \( i \): de imaginaire eenheid, met \( i^2 = -1 \).
\end{itemize}

**Poolvorm (goniometrische vorm)**

Een complex getal kan ook worden uitgedrukt in termen van een modulus en een hoek. Dat noemen we de \textbf{poolvorm} of \textbf{goniometrische vorm}:

\begin{align*}
    z = r \left( \cos \theta + i \sin \theta \right)
\end{align*}

met:
\begin{itemize}
    \item \( r = |z| = \sqrt{a^2 + b^2} \): de modulus van \( z \),
    \item \( \theta = \arg(z) \): het argument (de hoek die \( z \) maakt met de positieve reële as, in radialen).
\end{itemize}

**Modulus en argument berekenen**

Voor een complex getal $z = a + bi$ geldt:

\begin{align*}
    r &= \sqrt{a^2 + b^2} \\
    \theta &= \arctan\left( \frac{b}{a} \right)
\end{align*}

Let op: de uitkomst van de tangens is afhankelijk van het kwadrant waarin  $z$ ligt. Gebruik daarom een schets voor de juiste hoek.

\subsection*{Overgang naar poolvorm}

Om \( z = a + bi \) om te zetten naar de poolvorm:
\begin{enumerate}
    \item Bereken \( r = \sqrt{a^2 + b^2} \)
    \item Bepaal de hoek \( \theta = \arg(z) \), eventueel als negatieve of positieve waarde
    \item Vul in: \( z = r(\cos \theta + i \sin \theta) \)
\end{enumerate}

\subsection*{Vermenigvuldigen en delen in poolvorm}

Als \( z_1 = r_1(\cos \theta_1 + i \sin \theta_1) \) en \( z_2 = r_2(\cos \theta_2 + i \sin \theta_2) \), dan geldt:

\paragraph{Vermenigvuldigen:}
\[
z_1 \cdot z_2 = r_1 r_2 \left[ \cos(\theta_1 + \theta_2) + i \sin(\theta_1 + \theta_2) \right]
\]

\paragraph{Delen:}
\[
\frac{z_1}{z_2} = \frac{r_1}{r_2} \left[ \cos(\theta_1 - \theta_2) + i \sin(\theta_1 - \theta_2) \right]
\]

\subsection*{Voorbeeld: Zet \( z = 1 + i\sqrt{3} \) om naar de poolvorm}

\begin{align*}
a &= 1, \quad b = \sqrt{3} \\
r &= \sqrt{1^2 + (\sqrt{3})^2} = \sqrt{1 + 3} = \sqrt{4} = 2 \\
\theta &= \arctan\left( \frac{\sqrt{3}}{1} \right) = \frac{\pi}{3} \\
z &= 2 \left( \cos\left( \frac{\pi}{3} \right) + i \sin\left( \frac{\pi}{3} \right) \right)
\end{align*}
