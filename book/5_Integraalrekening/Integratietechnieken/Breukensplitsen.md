# Breukensplitsen


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
