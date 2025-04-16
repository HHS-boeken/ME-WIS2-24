# 6.2 Partieel integreren

````{admonition} Theorie: Partieel Integreren
:class: tip, dropdown open

## 🧠 Wanneer gebruik je partieel integreren?

Partiële integratie gebruik je bij het berekenen van integralen van een **product** van twee functies, bijvoorbeeld:

```
∫ x e^x dx,    ∫ x sin(x) dx,    ∫ ln(x) dx
```

De techniek is nuttig als:
- De afgeleide van één van de factoren **eenvoudiger** is dan het origineel.
- Of als één van de factoren **niet direct integreerbaar** is (zoals `ln(x)`).

---

## 📐 Formule van partiële integratie

De formule is gebaseerd op de productregel uit de differentiaalrekening:

```
d/dx [u(x) · v(x)] = u'(x)v(x) + u(x)v'(x)
```

Daaruit volgt de formule voor integreren per partie:

```
∫ u dv = uv - ∫ v du
```

waarbij:
- `u` = een functie die je **differentieert** (wordt eenvoudiger),
- `dv` = de rest (de functie die je **integreert**).

---

## 🔢 Stappenplan

1. **Kies** `u` en `dv` in de integraal `∫ u dv`.
   - Tip: gebruik de LIATE-regel als hulpmiddel (zie hieronder).
2. **Bereken** `du` (de afgeleide van `u`) en `v` (de primitieve van `dv`).
3. **Pas de formule toe**:
   ```
   ∫ u dv = uv - ∫ v du
   ```
4. **Herhaal indien nodig** (als de nieuwe integraal nog niet oplosbaar is).
5. **Voeg de constante `C`** toe.

---

## 🧭 Hulpmiddel: LIATE-regel (keuzehulp voor `u`)

Een veelgebruikte volgorde voor het kiezen van `u` (de functie die je differentieert) is:

**L I A T E**
1. **L**ogarithmic: `ln(x), log(x), ...`
2. **I**nverse trig: `arctan(x), arcsin(x), ...`
3. **A**lgebraic: `x, x², ...`
4. **T**rigonometric: `sin(x), cos(x), ...`
5. **E**xponential: `e^x, a^x, ...`

Je kiest bij voorkeur als `u` degene die het eerst in deze lijst voorkomt.

---

## ⚠️ Belangrijke opmerkingen

- Als de integraal na toepassen van de formule **lastiger** wordt, kies dan andere `u` en `dv`.
- Soms moet je **herhaald** partieel integreren (bijv. bij `x² e^x`).
- Bij producten zoals `x ln(x)` kun je géén substitutie gebruiken, dan is partieel integreren de manier.
- In sommige gevallen kom je na twee stappen terug bij de oorspronkelijke integraal. Dan moet je **algebraïsch oplossen** (bijv. bij `∫ e^x cos(x) dx`).

````

## 6.2.1 Partieel integreren

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

## 6.2.2 Herhaald partieel integreren

````{admonition} Voorbeeld 2: Herhaald partieel integreren
:class: dropdown

Bereken de primitieve van:
\begin{align*}
    f(x) = x^2e^x
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int x^2e^x \, dx
\end{align*}

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= x^2 \\
    dv &= e^x \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2x \\
    du &= 2x \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= e^x \, dx  \\
    \dfrac{dv}{dx} &= e^x \\
    v &= e^x
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= x^2 \cdot e^x - \int e^x 2x \, dx\\
    &= x^2 \cdot e^x - \int 2xe^x \, dx
\end{align*}

De integraal $\int 2xe^x \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.
\begin{align*}
   \int 2xe^x \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= 2x \\
    dv &= e^x \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2 \\
    du &= 2 \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= e^x \, dx  \\
    \dfrac{dv}{dx} &= e^x \\
    v &= e^x
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
   \int 2xe^x \, dx &= 2x \cdot e^x - \int e^x 2 \, dx\\
    &= 2x \cdot e^x - 2 \int e^x  \, dx\\
    &= 2x \cdot e^x - 2e^x + C
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int x^2e^x \, dx \\
    &= x^2 \cdot e^x - \int 2xe^x \, dx \\
    &= x^2 \cdot e^x - (2x \cdot e^x - 2e^x + C) \\
    &= x^2 \cdot e^x - 2x \cdot e^x + 2e^x + C \\
    &= (x^2 - 2x + 2)e^x + C \\
\end{align*}



````

````{admonition} Oefening 3
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) = \dfrac{1}{4}x^2\cos(x)
\end{align*}


```{admonition} Uitwerking
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) = \dfrac{1}{4}x^2\cos(x)
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx
\end{align*}

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \dfrac{1}{4}x^2 \\
    dv &= \cos(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{2}x \\
    du &= \dfrac{1}{2}x \, dx
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
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int \sin(x) \dfrac{1}{2}x \, dx\\
     &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
\end{align*}

De integraal $\int \dfrac{1}{2}x \sin(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.
\begin{align*}
   \int \dfrac{1}{2}x \sin(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \dfrac{1}{2}x \\
    dv &= \sin(x) \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{2} \\
    du &= \dfrac{1}{2} \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= \sin(x) \, dx  \\
    \dfrac{dv}{dx} &= \sin(x) \\
    v &= -\cos(x)
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \dfrac{1}{2}x \cdot -\cos(x) - \int -\cos(x) \dfrac{1}{2} \, dx\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \int \cos(x)  \, dx\\
    &= -\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int \dfrac{1}{4}x^2\cos(x) \, dx \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - \int  \dfrac{1}{2}x \sin(x) \, dx\\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) - (-\dfrac{1}{2}x \cdot \cos(x) + \dfrac{1}{2} \sin(x) + C) \\
    &= \dfrac{1}{4}x^2 \cdot \sin(x) + \dfrac{1}{2}x \cdot \cos(x) - \dfrac{1}{2} \sin(x) + C
\end{align*}

```
````

````{admonition} Oefening 4
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) = x^2 \ln^2(x)
\end{align*}

```{admonition} Uitwerking
:class: important, dropdown

Primitiveer:
\begin{align*}
    f(x) = x^2 \ln^2(x)
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int x^2 \ln^2(x) \, dx
\end{align*}

Gebruik partieel integreren om deze onbepaalde integraal te brekenen.

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \ln^2(x) \\
    dv &= x^2 \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= 2 \ln(x) \cdot \dfrac{1}{x} \\
    du &= 2 \ln(x) \cdot \dfrac{1}{x} \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= x^2 \, dx  \\
    \dfrac{dv}{dx} &= x^2 \\
    v &= \dfrac{1}{3}x^3
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \ln^2(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 2 \ln(x) \cdot \dfrac{1}{x} \, dx\\
     &= \ln^2(x) \cdot \dfrac{1}{3}x^3 - \dfrac{2}{3} \int x^3  \ln(x) \cdot \dfrac{1}{x} \, dx\\
     &= \ln^2(x) \cdot \dfrac{1}{3}x^3 - \dfrac{2}{3} \int x^2  \ln(x) \, dx\\
\end{align*}

De integraal $\int x^2  \ln(x) \, dx$ is nog niet in een vorm dat deze op te lossen is, dus doorgaan met partieel integreren.
\begin{align*}
   \int x^2  \ln(x) \, dx
\end{align*}

Kies de functie $u$ en $dv$:
\begin{align*}
    u &= \ln(x) \\
    dv &= x^2 \, dx
\end{align*}

Bepaal $du$:
\begin{align*}
    \dfrac{du}{dx} &= \dfrac{1}{x} \\
    du &= \dfrac{1}{x} \, dx
\end{align*}

Bepaal de functie $v$:
\begin{align*}
    dv &= x^2 \, dx  \\
    \dfrac{dv}{dx} &= x^2 \\
    v &= \dfrac{1}{3}x^3
\end{align*}

Toepassen van de regel voor partieel integreren geeft:
\begin{align*}
   \int u \, dv &= uv - \int v \, du \\
    &= \ln(x) \cdot \dfrac{1}{3}x^3 - \int \dfrac{1}{3}x^3 \dfrac{1}{x} \, dx\\
    &= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \int x^2 \, dx\\
    &= \ln(x) \cdot \dfrac{1}{3}x^3 - \dfrac{1}{3} \cdot \dfrac{1}{3} x^3 + C \\
    &= \ln(x) \cdot \dfrac{1}{3}x^3 -  \dfrac{1}{9} x^3 + C
\end{align*}

Dus, 
\begin{align*}
    F(x) &=  \int x^2 \ln^2(x) \, dx \\
    &= \ln^2(x) \cdot \dfrac{1}{3}x^3 - \dfrac{2}{3} \int x^2  \ln(x) \, dx\\
    &= \ln^2(x) \cdot \dfrac{1}{3}x^3 - \dfrac{2}{3} (\ln(x) \cdot \dfrac{1}{3}x^3 -  \dfrac{1}{9} x^3 + C) \\
    &= \dfrac{1}{3}x^3\ln^2(x) - \dfrac{2}{9}x^3\ln(x)  +  \dfrac{2}{27} x^3 + C \\
\end{align*}

```
````