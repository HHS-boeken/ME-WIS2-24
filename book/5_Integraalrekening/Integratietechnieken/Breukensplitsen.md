# 6.3 Breukensplitsen

````{admonition} Theorie: Partieel Integreren
:class: tip, dropdown open

# 🧠 Wanneer gebruik je breuksplitsen?

Breuksplitsen gebruik je bij het berekenen van **integralen van rationale functies**: breuken waarin zowel de teller als de noemer **veeltermen** zijn. Het doel is om de breuk te herschrijven als een som van **eenvoudige standaardbreuken** die makkelijk te integreren zijn.

Bijvoorbeeld:


Breuksplitsen maakt zulke integralen overzichtelijk en oplosbaar.

Je gebruikt breuksplitsen als:
- De **graad van de teller lager is dan die van de noemer** (anders eerst polynoomdeling).
- De **noemer ontbindbaar is** in lineaire en/of kwadratische factoren.

---

## 📐 De hoofdgedachte

Je schrijft:


Zodat de rechterkant bestaat uit **losse, eenvoudige breuken** die makkelijk te integreren zijn.

Voorbeeld:

\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{A}{x + 1} + \frac{B}{x - 3}
\]

---

## 🔢 Stappenplan

1. **Controleer de graad** van teller en noemer:
   - Als \( \deg(\text{teller}) \geq \deg(\text{noemer}) \): eerst **polynoomdeling**.
2. **Ontbind de noemer** in factoren (lineair en/of irreducibel kwadratisch).
3. **Kies de juiste vorm** van de breuksplitsing (zie tabel hieronder).
4. **Werk de breuksplitsing uit**:
   - Vermenigvuldig met de noemer om de breuken weg te werken.
   - Los de constanten op via:
     - **Slimme waarden** van \( x \), of
     - **Coëfficiënten vergelijken**
5. **Integreer elke losse breuk** apart.

---

## 🧭 Hulpmiddel: Tabel van breukvormen

| Type factor in de noemer                    | Vorm van de breuk                         |
|---------------------------------------------|--------------------------------------------|
| \( (x - a) \)                                | \( \frac{A}{x - a} \)                      |
| \( (x - a)^n \)                              | \( \frac{A_1}{x - a} + \cdots + \frac{A_n}{(x - a)^n} \) |
| \( x^2 + bx + c \) (niet ontbindbaar)        | \( \frac{Ax + B}{x^2 + bx + c} \)          |
| \( (x^2 + bx + c)^n \)                       | \( \frac{A_1x + B_1}{x^2 + bx + c} + \cdots + \frac{A_nx + B_n}{(x^2 + bx + c)^n} \) |

---

## 💡 Tips & aandachtspunten

- ❗ **Tellergraad checken** is cruciaal. Anders levert breuksplitsen geen vereenvoudiging op.
- ✏️ Begin bij lineaire factoren met **slimme waarden voor \( x \)** (die factoren laten wegvallen).
- 🤓 Bij kwadratische factoren heb je **altijd een teller van vorm \( Ax + B \)**.
- 🔁 Herhaalde factoren krijgen meerdere breuken met oplopende machten.
- ⛔ Niet alle noemers zijn te ontbinden met reële getallen — gebruik dan irreducibele vormen.

---

## ✅ Voorbeeld

Splits:
\[
\frac{5x + 2}{(x + 1)(x - 3)}
\]

Stel:
\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{A}{x + 1} + \frac{B}{x - 3}
\]

Maal links en rechts met de noemer:
\[
5x + 2 = A(x - 3) + B(x + 1)
\]

Kies:
- \( x = 3 \Rightarrow 5(3) + 2 = 0A + 4B \Rightarrow B = \frac{17}{4} \)
- \( x = -1 \Rightarrow 5(-1) + 2 = -4A + 0 \Rightarrow A = -\frac{3}{4} \)

Oplossing:
\[
\frac{5x + 2}{(x + 1)(x - 3)} = \frac{-\frac{3}{4}}{x + 1} + \frac{\frac{17}{4}}{x - 3}
\]
```

````{admonition} Voorbeeld 1: Partieel integreren
:class: dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int (2x+3)\cos(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= 2x+3 \\
    dv &= \cos(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2 \\
    du &= 2 \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= \cos(x) \, dx  \\
    \dfrac{dv}{dx} &= \cos(x) \\
    v &= \sin(x)
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= (2x+3) \cdot \sin(x) - \int \sin(x) 2 \, dx\\
    &= (2x+3) \cdot \sin(x) - 2 \int \sin(x) \, dx\\
    &= (2x+3) \cdot \sin(x) + 2 \cos(x) + C
\end{align*}
````

````{admonition} Oefening 1
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x \cdot e^{2x} \, dx
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Bereken de onbepaalde integraal:
\begin{align*}
    \int x \cdot e^{2x} \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= x \\
    dv &= e^{2x} \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 1 \\
    du &=  \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= e^{2x} \, dx  \\
    \dfrac{dv}{dx} &= e^{2x} \\
    v &= \dfrac{1}{2}e^{2x}
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= x \cdot \dfrac{1}{2}e^{2x} - \int \dfrac{1}{2}e^{2x} \, dx\\
    &= x \cdot \dfrac{1}{2}e^{2x} - \dfrac{1}{2} \int e^{2x} \, dx\\
    &= x \cdot \dfrac{1}{2}e^{2x} - \dfrac{1}{2} \cdot  \dfrac{1}{2}e^{2x} + C \\
    &= \dfrac{1}{2}xe^{2x} - \dfrac{1}{4}e^{2x} + C \\
\end{align*}

```
````

````{admonition} Oefening 2
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) =  x^3\ln(x) + 3
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) =  x^3\ln(x) + 3
\end{align*}

Dus,
\begin{align*}
    F(x) &=  \int (x^3\ln(x) + 3) \, dx \\
    F(x) &= \int (x^3\ln(x)) \, dx + \int  (3) \, dx \\
    F(x) &= \int (x^3\ln(x)) \, dx + 3x + C
\end{align*}

Voor het eerste gedeelte gebruik partieel integreren.
Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \ln(x) \\
    dv &= x^3 \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{x} \\
    du &=  \dfrac{1}{x} \, dx \\
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= x^3 \, dx  \\
    \dfrac{dv}{dx} &= x^3 \\
    v &= \dfrac{1}{4}x^4
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^4 \dfrac{1}{x} \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \int \dfrac{1}{4}x^3 \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \int x^3 \, dx \\
    &= \ln(x) \cdot \dfrac{1}{4}x^4 - \dfrac{1}{4} \cdot \dfrac{1}{4} x^4 + C \\
    &= \dfrac{1}{4}x^4\ln(x) - \dfrac{1}{16} x^4 + C \\
\end{align*}
```
````
