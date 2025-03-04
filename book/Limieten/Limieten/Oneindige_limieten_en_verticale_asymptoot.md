---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---
# 1.2 Oneindige limieten, $\lim_{x\to a }  f(x)= \pm \infty$ ,  verticale asymptoot

```{code-cell} ipython3
:tags: ["remove-output","remove-input"]

import numpy as np 
import matplotlib.pyplot as plt 
from myst_nb import glue

#plt.rcParams['text.usetex'] = True

# Functie definitie
def f(x):
    return (4*x - 3) / (5*x - 4)

# Domein splitsen rond de verticale asymptoot x = 4/5
x1 = np.linspace(-2, 0.79, 400)  # Linker tak (voor x < 4/5)
x2 = np.linspace(0.81, 3, 400)   # Rechter tak (voor x > 4/5)

# Functiewaarden berekenen
y1 = f(x1)
y2 = f(x2)

# Grafiek plotten
fig, ax = plt.subplots()
#plt.figure(figsize=(8, 6))
ax.plot(x1, y1, 'b', label=r'$y = \frac{4x - 3}{5x - 4}$')  # Linker tak
ax.plot(x2, y2, 'b')  # Rechter tak

# Asymptoten
ax.axvline(x=4/5, color='r', linestyle='--', label=r'Asymptoot $x=\frac{4}{5}$')  # Verticale asymptoot
ax.axhline(y=4/5, color='g', linestyle='--', label=r'Asymptoot $y=\frac{4}{5}$')  # Horizontale asymptoot

# Labels en titel
ax.set_xlabel('x')
ax.set_ylabel('f(x)')
ax.set_xlim(-2,3)
ax.set_ylim(-3,5)
ax.set_title('Grafiek van $f(x) = \\frac{4x - 3}{5x - 4}$')
ax.legend()
ax.grid()

# Weergeven
#ax.show()

#fig.savefig("test.png")
glue("voorbeeld1", fig, display=False)

```

mmmm

```{glue:} voorbeeld1
```