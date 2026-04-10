# 5.2 De stelling van L'Hopital


::::{admonition} Theorie
:class: tip, dropdown open

De **stelling van L’Hôpital** wordt gebruikt bij het bepalen van limieten waarbij directe invulling leidt tot een **onbepaalde vorm**.

Als voor een limiet geldt dat zowel de teller als de noemer naar nul gaan, of beide naar oneindig gaan, dan spreken we van de vormen:

\begin{align*}
    \frac{0}{0} \quad \text{of} \quad \frac{\infty}{\infty}
\end{align*}

Als een functie $f(x)$ geschreven kan worden als een breuk van twee differentieerbare functies $u(x)$ en $v(x)$, dan geldt:

$$
    f(x) = \frac{u(x)}{v(x)}
$$

De limiet van $f(x)$ kan dan bepaald worden door zowel de teller als de noemer te differentiëren:

$$
    \lim_{x \to a} \frac{u(x)}{v(x)} = \lim_{x \to a} \frac{\dfrac{du}{dx}}{\dfrac{dv}{dx}}
$$

Dit betekent dat je eerst controleert of er sprake is van een onbepaalde vorm. Is dat het geval, dan differentieer je de teller en de noemer en bepaal je daarna opnieuw de limiet.

:class: warning

- De vorm moet zijn $\frac{0}{0}$ of $\frac{\infty}{\infty}$  
- De functies moeten differentieerbaar zijn  
- Na differentiëren moet de limiet bestaan (of opnieuw met L’Hôpital bepaald kunnen worden)  

::::
