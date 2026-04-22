# 5.2 De stelling van L'Hopital


::::{admonition} Theorie
:class: tip, dropdown open

De **stelling van L’Hôpital** wordt gebruikt bij het bepalen van limieten waarbij directe invulling leidt tot een **onbepaalde vorm**.

Als voor een limiet geldt dat zowel de teller als de noemer naar nul gaan, of beide naar oneindig gaan, dan spreken we van de vormen:

$$
    \frac{0}{0} \quad \text{of} \quad \frac{\infty}{\infty}
$$

Als een functie $f(x)$ geschreven kan worden als een breuk van twee differentieerbare functies $u(x)$ en $v(x)$, dan geldt:

$$
    f(x) = \frac{u(x)}{v(x)}
$$

De limiet van $f(x)$ kan dan bepaald worden door zowel de teller als de noemer te differentiëren:

$$
    \lim_{x \to a} \frac{u(x)}{v(x)} = \lim_{x \to a} \frac{\dfrac{du}{dx}}{\dfrac{dv}{dx}}
$$

Dit betekent dat je eerst controleert of er sprake is van een onbepaalde vorm. Is dat het geval, dan differentieer je de teller en de noemer en bepaal je daarna opnieuw de limiet.

:::{admonition} Standaard afgeleiden
:class: warning

- De vorm moet zijn $\frac{0}{0}$ of $\frac{\infty}{\infty}$  
- De functies moeten differentieerbaar zijn  
- Na differentiëren moet de limiet bestaan (of opnieuw met L’Hôpital bepaald kunnen worden)  

:::
::::

## 5.2.1 De stelling van L'Hopital

::::{admonition} Voorbeeld: De stelling van L'Hopital
:class: dropdown

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\ln(1+x)}{x}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
\ln(1+0) &= \ln(1) = 0 \\
x &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:
\begin{align*}
\frac{d}{dx}(\ln(1+x)) &= \frac{1}{1+x} \\
\frac{d}{dx}(x) &= 1
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\ln(1+x)}{x} = \lim_{x \to 0} \frac{\frac{1}{1+x}}{1}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\lim_{x \to 0} \frac{1}{1+x} = \frac{1}{1+0} = 1
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{\ln(1+x)}{x} = 1
\end{align*}

::::

::::
{admonition} Oefening 1
:class: important, dropdown

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\tan(x)-x}{x^3}
\end{align*}

:::{admonition} Uitwerking

Bereken de limiet
\begin{align*}
\lim_{x \to 0} \frac{\tan(x)-x}{x^3}
\end{align*}

Vul eerst $x=0$ in in de teller en de noemer:
\begin{align*}
\tan(0) - 0 &= 0 - 0 = 0 \\
x^3 &= 0
\end{align*}

Dus er ontstaat de onbepaalde vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We mogen daarom de regel van L'Hôpital toepassen. Differentieer de teller en de noemer:

**Eerste keer differentiëren:**
\begin{align*}
\frac{d}{dx}(\tan(x)-x) &= \frac{1}{\cos^2(x)} - 1 \\
\frac{d}{dx}(x^3) &= 3x^2
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\frac{1}{\cos^2(x)} - 1}{3x^2}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
\frac{1}{\cos^2(0)} - 1 &= 1 - 1 = 0 \\
3x^2 &= 0
\end{align*}

We krijgen opnieuw de vorm:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nogmaals toe.

**Tweede keer differentiëren:**
\begin{align*}
\frac{d}{dx}\left(\frac{1}{\cos^2(x)} - 1\right) &= \frac{2\sin(x)}{\cos^3(x)} \\
\frac{d}{dx}(3x^2) &= 6x
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\frac{2\sin(x)}{\cos^3(x)}}{6x}
\end{align*}

Vul opnieuw $x=0$ in:
\begin{align*}
\frac{2\sin(0)}{\cos^3(0)} &= 0 \\
6x &= 0
\end{align*}

We krijgen opnieuw:
\begin{align*}
\frac{0}{0}
\end{align*}

We passen L'Hôpital nog een derde keer toe.

**Derde keer differentiëren:**
\begin{align*}
\frac{d}{dx}\left(\frac{2\sin(x)}{\cos^3(x)}\right) &= \frac{2}{\cos^2(x)} + \frac{6\sin^2(x)}{\cos^4(x)} \\
\frac{d}{dx}(6x) &= 6
\end{align*}

Dan wordt de limiet:
\begin{align*}
\lim_{x \to 0} \frac{\frac{2}{\cos^2(x)} + \frac{6\sin^2(x)}{\cos^4(x)}}{6}
\end{align*}

Vul nu $x=0$ in:
\begin{align*}
\frac{\frac{2}{\cos^2(0)} + \frac{6\sin^2(0)}{\cos^4(0)}}{6}
= \frac{2 + 0}{6}
= \frac{1}{3}
\end{align*}

Dus:
\begin{align*}
\lim_{x \to 0} \frac{\tan(x)-x}{x^3} = \frac{1}{3}
\end{align*}

:::
::::