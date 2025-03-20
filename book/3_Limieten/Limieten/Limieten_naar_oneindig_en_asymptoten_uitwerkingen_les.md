# 3.1 Uitwerkingen les

### Opgave 1

````{admonition} Antwoord
:class: dropdown

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{4x^3 + x}{7x^5 - 9x^2 + 2} = 0
\end{align*}  
$$  

```{admonition} Uitwerking
:class: dropdown

Bereken de limiet  

$$  
\begin{align*}  
\lim_{x \to -\infty} \dfrac{4x^3 + x}{7x^5 - 9x^2 + 2}  
\end{align*}  
$$  

Deel de teller en de noemer door de hoogste macht $x^5$ in de noemer:  

$$  
\begin{align}  
&= \lim_{x \to -\infty} \dfrac{\dfrac{4x^3}{x^5} + \dfrac{x}{x^5}}{\dfrac{7x^5}{x^5} - \dfrac{9x^2}{x^5} + \dfrac{2}{x^5}}  \\  
&= \lim_{x \to -\infty} \dfrac{\dfrac{4}{x^2} + \dfrac{1}{x^4}}{7 - \dfrac{9}{x^3} + \dfrac{2}{x^5}}  
\end{align}  
$$  

Gebruik de standaardlimiet,
$
\lim_{x \to -\infty} \dfrac{a}{x^n} = 0
$
Dit geeft:

$$  
\begin{align}  
&= \dfrac{0 + 0}{7 - 0 + 0}  \\  
&= \dfrac{0}{7} = 0  
\end{align}  
$$  

```  
````  

<hr style="border:1px solid #9EA700">


