# Soluciones a ecuaciones logarítmicas

## 1. Ecuación: 
$$
\log_x(128) = 7
$$
Reescribimos en forma exponencial:
$$
x^7 = 128
$$
Calculamos $128$ como $2^7$:
$$
x^7 = 2^7
$$
Por lo tanto, 
$$
x = 2.
$$

---

## 2. Ecuación: 
$$
\log_3(2x) = \frac{3}{2}
$$
Reescribimos en forma exponencial:
$$
2x = 3^{\frac{3}{2}}
$$
Calculamos $3^{\frac{3}{2}}$:
$$
3^{\frac{3}{2}} = \sqrt{3^3} = \sqrt{27} = 3\sqrt{3}
$$
Entonces, tenemos:
$$
2x = 3\sqrt{3}
$$
Despejamos $x$:
$$
x = \frac{3\sqrt{3}}{2}.
$$

---

## 3. Ecuación: 
$$
\log_{12}(13) = x
$$
Reescribimos en forma exponencial:
$$
12^x = 13
$$
Para resolver esta ecuación, tomamos logaritmo en base 10 o natural:
$$
x = \log_{12}(13) \quad (\text{Esto es el resultado en forma logarítmica, } x \text{ se queda así.})
$$
Si se desea calcular el valor numérico:
$$
x = \frac{\log(13)}{\log(12)} \quad \text{(usando la propiedad del cambio de base)}
$$

---

## 4. Ecuación: 
$$
\log_x(x) = 25
$$
Reescribimos en forma exponencial:
$$
x^{25} = x
$$
Esto implica dos casos:
- Si $x \neq 0$, podemos dividir ambos lados entre $x$:
$$
x^{24} = 1
$$
Las soluciones para esta ecuación son:
$$
x = 1 \quad \text{o} \quad x = -1 \quad (\text{si consideramos números reales})
$$
(Sin embargo, logaritmos no están definidos para bases negativas).

---

# Resumen de soluciones:
1. $x = 2$
2. $x = \frac{3\sqrt{3}}{2}$
3. $x = \log_{12}(13)$ (o $x \approx 1.05$ numéricamente)
4. $x = 1$ (el valor negativo no es válido para logaritmos)# Cálculo de Logaritmos


# Soluciones a expresiones logarítmicas
## 1. Halla $2\log_2(7) + \log_2(8) - \log_2(98)$

**Paso 1:** Simplificamos la expresión utilizando propiedades de logaritmos:
$$
\log_2(8) = \log_2(2^3) = 3
$$
Así que:
$$
\log_2(98) = \log_2(7^2 \cdot 2) = 2\log_2(7) + \log_2(2)
$$

**Paso 2:** Entonces la expresión se convierte en:
$$
2\log_2(7) + 3 - (2\log_2(7) + \log_2(2))
$$
$$
= \cancel{2\log_2(7)} + 3 - \cancel{2\log_2(7)} - \log_2(2))=3-1=2
$$

## 2. Halla $3\log(10^2) - \log(160) - \log(625)$

**Paso 1:** Simplificamos la expresión:
$$
3\log(10^2) = 6
$$
$$
\log(160) + \log(625) = \log(160 \cdot 625) = \log(100000)
$$

**Paso 2:** Entonces:
$$
3\log(10^2) - \log(160) - \log(625) = 6 - 5 = 1
$$

## 3. Halla $\log_3(9) + \log_2(4) + \log_5(125) - \log_7(7)$

**Paso 1:** Calculamos cada logaritmo:
- $\log_3(9) = \log_3(3^2) = 2$
- $\log_2(4) = \log_2(2^2) = 2$
- $\log_5(125) = \log_5(5^3) = 3$
- $\log_7(7) = 1$

**Paso 2:** Sustituimos estos valores en la expresión:
$$
2 + 2 + 3 - 1 = 6
$$

## Resultados Finales:
1. $2\log_2(7) + \log_2(8) - \log_2(98)=2$
2. $3\log(10^2) - \log(160) - \log(625) = 1$
3. $\log_3(9) + \log_2(4) + \log_5(125) - \log_7(7) = 6$

Relacionado con [[Logaritmos]]