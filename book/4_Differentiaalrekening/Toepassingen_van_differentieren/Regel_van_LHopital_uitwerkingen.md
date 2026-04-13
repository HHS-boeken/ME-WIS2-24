## 5.2 Uitwerkingen

### Opgave 5.2a

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{e^x - 1}{x} = 1
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1}{x}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
e^0 - 1 &= 1 - 1 = 0 \\
x &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:
\begin{align*}
\frac{d}{dx}(e^x - 1) &= e^x \\
\frac{d}{dx}(x) &= 1
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1}{x} = \lim_{x \to 0} \frac{e^x}{1}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\lim_{x \to 0} \frac{e^x}{1} = \frac{e^0}{1} = \frac{1}{1} = 1
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1}{x} = 1
\end{align*}

:::
::::

### Opgave 5.2b

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to \infty} \frac{\sqrt{x}}{\ln(x)} = \infty
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to \infty} \frac{\sqrt{x}}{\ln(x)}
\end{align*}

Bekijk eerst het gedrag van de teller en noemer voor $x \to \infty$:
\begin{align*}
\sqrt{x} &\to \infty \\
\ln(x) &\to \infty
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{\infty}{\infty}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:
\begin{align*}
\frac{d}{dx}(\sqrt{x}) &= \frac{1}{2\sqrt{x}} \\
\frac{d}{dx}(\ln(x)) &= \frac{1}{x}
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{\sqrt{x}}{\ln(x)} = \lim_{x \to \infty} \frac{\frac{1}{2\sqrt{x}}}{\frac{1}{x}}
\end{align*}

Herschrijf de breuk:
\begin{align*}
\frac{\frac{1}{2\sqrt{x}}}{\frac{1}{x}} = \frac{x}{2\sqrt{x}} = \frac{\sqrt{x}}{2}
\end{align*}

Neem nu de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{\sqrt{x}}{2} = \infty
\end{align*}

Dus:
\begin{align*}
\lim_{x \to \infty} \frac{\sqrt{x}}{\ln(x)} = \infty
\end{align*}

:::
::::
