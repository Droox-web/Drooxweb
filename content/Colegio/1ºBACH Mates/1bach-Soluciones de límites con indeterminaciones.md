Preparados para 1ºBACH

Ver: [[Límites]]

Enunciados en: [[Límites con indeterminaciones]]

---


### 1. $\lim_{x \to \infty} \frac{x^2 + 3x + 1}{2x^2 - 5x + 4}$

**Solución**

Dividimos numerador y denominador por $x^2$ (el término de mayor grado):

$$\lim_{x \to \infty} \frac{\frac{x^2}{x^2} + \frac{3x}{x^2} + \frac{1}{x^2}}{\frac{2x^2}{x^2} - \frac{5x}{x^2} + \frac{4}{x^2}} = \lim_{x \to \infty} \frac{1 + \frac{3}{x} + \frac{1}{x^2}}{2 - \frac{5}{x} + \frac{4}{x^2}}.$$

Al tomar el límite cuando $x \to \infty$, los términos que contienen $\frac{1}{x}$ y $\frac{1}{x^2}$ tienden a $0$, así que:

$$\lim_{x \to \infty} \frac{x^2 + 3x + 1}{2x^2 - 5x + 4} = \frac{1}{2}.$$

---

### 2. $\lim_{x \to 1} \frac{x^2 - 1}{x - 1}$

**Solución**

Factorizamos el numerador como una diferencia de cuadrados:

$$\lim_{x \to 1} \frac{x^2 - 1}{x - 1} = \lim_{x \to 1} \frac{(x - 1)(x + 1)}{x - 1}.$$

Cancelamos el factor $(x - 1)$ (válido para $x \neq 1$):

$$\lim_{x \to 1} (x + 1) = 1 + 1 = 2.$$

---

### 3. $\lim_{x \to \infty} \frac{\sqrt{x^2 + 1} - x}{2}$

**Solución**

Racionalizamos el numerador:

$$\frac{\sqrt{x^2 + 1} - x}{2} = \frac{\left(\sqrt{x^2 + 1} - x\right)\left(\sqrt{x^2 + 1} + x\right)}{2\left(\sqrt{x^2 + 1} + x\right)} = \frac{x^2 + 1 - x^2}{2\left(\sqrt{x^2 + 1} + x\right)}.$$

Simplificando el numerador:

$$\lim_{x \to \infty} \frac{1}{2\left(\sqrt{x^2 + 1} + x\right)}.$$

Para $x \to \infty$, $\sqrt{x^2 + 1} \approx x$, entonces:

$$\lim_{x \to \infty} \frac{1}{2\left(\sqrt{x^2 + 1} + x\right)} = \frac{1}{2(2x)} = 0.$$

---

### 4. $\lim_{x \to \infty} \frac{3^x}{x^3}$

**Solución**

La exponencial $3^x$ crece mucho más rápido que cualquier polinomio. Por lo tanto:

$$\lim_{x \to \infty} \frac{3^x}{x^3} = \infty.$$

---

### 5. $\lim_{x \to 0^+} \log_3(x)$

**Solución**

El logaritmo base $3$ de $x$ tiende a $-\infty$ cuando $x \to 0^+$:

$$\lim_{x \to 0^+} \log_3(x) = -\infty.$$

---

### 6. $\lim_{x \to \infty} \frac{x + \sin(x)}{x}$

**Solución**

Dividimos cada término del numerador por $x$:

$$\lim_{x \to \infty} \frac{x + \sin(x)}{x} = \lim_{x \to \infty} \left(1 + \frac{\sin(x)}{x}\right).$$

Sabemos que $\frac{\sin(x)}{x} \to 0$ cuando $x \to \infty$, entonces:

$$\lim_{x \to \infty} \frac{x + \sin(x)}{x} = 1.$$
