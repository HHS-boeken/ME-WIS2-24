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

### Opgave 5.2c

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{\sin(x)-x}{x^3} = -\frac{1}{6}
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\sin(x)-x}{x^3}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
\sin(0) - 0 &= 0 - 0 = 0 \\
x^3 &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\sin(x)-x) &= \cos(x) - 1 \\
\frac{d}{dx}(x^3) &= 3x^2
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\cos(x)-1}{3x^2}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
\cos(0)-1 &= 1-1=0 \\
3x^2 &= 0
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\cos(x)-1) &= -\sin(x) \\
\frac{d}{dx}(3x^2) &= 6x
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{-\sin(x)}{6x}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
-\sin(0) &= 0 \\
6x &= 0
\end{align*}

We krijgen opnieuw:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nog een derde keer toe.

**Derde keer differentiëren:**
\begin{align*}
\frac{d}{dx}(-\sin(x)) &= -\cos(x) \\
\frac{d}{dx}(6x) &= 6
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{-\cos(x)}{6}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\frac{-\cos(0)}{6} = \frac{-1}{6}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{\sin(x)-x}{x^3} = -\frac{1}{6}
\end{align*}

:::
::::


### Opgave 5.2d

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{\sqrt{1+x}-1}{x} = \frac{1}{2}
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\sqrt{1+x}-1}{x}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
\sqrt{1+0} - 1 &= 1 - 1 = 0 \\
x &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'H'opital toepassen. Differentieer de teller en de noemer:
\begin{align*}
\frac{d}{dx}(\sqrt{1+x}-1) &= \frac{1}{2\sqrt{1+x}} \\
\frac{d}{dx}(x) &= 1
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\sqrt{1+x}-1}{x} = \lim_{x \to 0} \frac{\frac{1}{2\sqrt{1+x}}}{1}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\lim_{x \to 0} \frac{1}{2\sqrt{1+x}} = \frac{1}{2\sqrt{1}} = \frac{1}{2}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{\sqrt{1+x}-1}{x} = \frac{1}{2}
\end{align*}

:::
::::

### Opgave 5.2e

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to \infty} \frac{x^2}{\ln(x)} = \infty
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to \infty} \frac{x^2}{\ln(x)}
\end{align*}

Bekijk eerst het gedrag van de teller en noemer voor $x \to \infty$:
\begin{align*}
x^2 &\to \infty \\
\ln(x) &\to \infty
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{\infty}{\infty}
\end{align*}

We mogen daarom de regel van L'H'opital toepassen. Differentieer de teller en de noemer:
\begin{align*}
\frac{d}{dx}(x^2) &= 2x \\
\frac{d}{dx}(\ln(x)) &= \frac{1}{x}
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{x^2}{\ln(x)} = \lim_{x \to \infty} \frac{2x}{\frac{1}{x}}
\end{align*}

Herschrijf de breuk:
\begin{align*}
\frac{2x}{\frac{1}{x}} = 2x^2
\end{align*}

Neem nu de limiet:
\begin{align*}
\lim_{x \to \infty} 2x^2 = \infty
\end{align*}

Dus:
\begin{align*}
\lim_{x \to \infty} \frac{x^2}{\ln(x)} = \infty
\end{align*}

:::
::::

### Opgave 5.2f

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{\cos(x) - \cos(2x)}{x^2} = \frac{3}{2}
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\cos(x) - \cos(2x)}{x^2}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
\cos(0) - \cos(0) &= 1 - 1 = 0 \\
x^2 &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'H'opital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\cos(x) - \cos(2x)) &= -\sin(x) + 2\sin(2x) \\
\frac{d}{dx}(x^2) &= 2x
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{-\sin(x) + 2\sin(2x)}{2x}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
-\sin(0) + 2\sin(0) &= 0 \\
2x &= 0
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'H'opital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}(-\sin(x) + 2\sin(2x)) &= -\cos(x) + 4\cos(2x) \\
\frac{d}{dx}(2x) &= 2
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{-\cos(x) + 4\cos(2x)}{2}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\frac{-\cos(0) + 4\cos(0)}{2} = \frac{-1 + 4}{2} = \frac{3}{2}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{\cos(x) - \cos(2x)}{x^2} = \frac{3}{2}
\end{align*}

:::
::::

### Opgave 5.2g

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{1 - \cos(x)}{x^2} = \frac{1}{2}
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{1 - \cos(x)}{x^2}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
1 - \cos(0) &= 1 - 1 = 0 \\
x^2 &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(1 - \cos(x)) &= \sin(x) \\
\frac{d}{dx}(x^2) &= 2x
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\sin(x)}{2x}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
\sin(0) &= 0 \\
2x &= 0
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\sin(x)) &= \cos(x) \\
\frac{d}{dx}(2x) &= 2
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\cos(x)}{2}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\frac{\cos(0)}{2} = \frac{1}{2}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{1 - \cos(x)}{x^2} = \frac{1}{2}
\end{align*}

:::
::::

### Opgave 5.2h

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to \infty} \frac{\ln^2(x)}{x} = 0
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to \infty} \frac{\ln^2(x)}{x}
\end{align*}

Bekijk eerst het gedrag van de teller en noemer voor $x \to \infty$:
\begin{align*}
\ln^2(x) &\to \infty \\
x &\to \infty
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{\infty}{\infty}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\ln^2(x)) &= 2\ln(x) \cdot \frac{1}{x} = \frac{2\ln(x)}{x} \\
\frac{d}{dx}(x) &= 1
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{\ln^2(x)}{x} = \lim_{x \to \infty} \frac{\frac{2\ln(x)}{x}}{1} = \lim_{x \to \infty} \frac{2\ln(x)}{x}
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{\infty}{\infty}
\end{align*}

We passen L'Hôpital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}(2\ln(x)) &= \frac{2}{x} \\
\frac{d}{dx}(x) &= 1
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{2\ln(x)}{x} = \lim_{x \to \infty} \frac{2/x}{1}
\end{align*}

Neem nu de limiet:
\begin{align*}
\lim_{x \to \infty} \frac{2}{x} = 0
\end{align*}

Dus:
\begin{align*}
\lim_{x \to \infty} \frac{\ln^2(x)}{x} = 0
\end{align*}

:::
::::

### Opgave 5.2i

::::{admonition} Antwoord
:class: important, dropdown

$$
\lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \frac{1}{2}
$$

:::{dropdown} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1 - x}{x^2}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
e^0 - 1 - 0 &= 1 - 1 - 0 = 0 \\
x^2 &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(e^x - 1 - x) &= e^x - 1 \\
\frac{d}{dx}(x^2) &= 2x
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \lim_{x \to 0} \frac{e^x - 1}{2x}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
e^0 - 1 &= 1 - 1 = 0 \\
2x &= 0
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}(e^x - 1) &= e^x \\
\frac{d}{dx}(2x) &= 2
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{e^x}{2}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\frac{e^0}{2} = \frac{1}{2}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{e^x - 1 - x}{x^2} = \frac{1}{2}
\end{align*}

:::
::::


