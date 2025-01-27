# Soluciones a Ecuaciones Logarítmicas

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
4. $x = 1$ (el valor negativo no es válido para logaritmos)

# Expresiones Logarítmicas

## 1. Expresión: 
$$
3\log(10^2) - \log(160) - \log(625)
$$

**Paso 1:** Simplificamos $3\log(10^2)$:
$$
3\log(10^2) = 3 \cdot 2\log(10) = 6\log(10) = 6 \quad (\text{ya que } \log(10) = 1)
$$

**Paso 2:** Usamos las propiedades de los logaritmos para simplificar:
$$
\log(160) + \log(625) = \log(160 \cdot 625)
$$

**Paso 3:** Calculamos $160 \cdot 625$:
$$
160 \cdot 625 = 100000
$$

**Paso 4:** Así que:
$$
\log(100000) = 5 \quad (\text{ya que } 100000 = 10^5)
$$

**Paso 5:** Finalmente, sustituimos en la expresión:
$$
6 - 5 = 1
$$

### Resultado:
$$
3\log(10^2) - \log(160) - \log(625) = 1
$$

---

## 2. Expresión: 
$$
\log_3(9) + \log_2(4) + \log_5(125) - \log_7(7)
$$

**Paso 1:** Calculamos cada logaritmo:
- $\log_3(9) = \log_3(3^2) = 2$
- $\log_2(4) = \log_2(2^2) = 2$
- $\log_5(125) = \log_5(5^3) = 3$
- $\log_7(7) = 1$

**Paso 2:** Sustituimos estos valores en la expresión:
$$
2 + 2 + 3 - 1
$$

**Paso 3:** Sumamos y restamos:
$$
2 + 2 + 3 - 1 = 6
$$

### Resultado:
$$
\log_3(9) + \log_2(4) + \log_5(125) - \log_7(7) = 6
$$

---

# Resumen de Resultados:
1. $3\log(10^2) - \log(160) - \log(625) = 1$
2. $\log_3(9) + \log_2(4) + \log_5(125) - \log_7(7) = 6$

# Cálculo de Logaritmos

Dado que $\log_5(7) \approx 1.2$, hallamos los valores de las siguientes expresiones.

## 1. Halla $\log_5(0.07)$

Primero, notamos que:
$$
0.07 = \frac{7}{100} = \frac{7}{10^2}
$$
Usando propiedades de logaritmos:
$$
\log_5(0.07) = \log_5\left(\frac{7}{10^2}\right) = \log_5(7) - \log_5(10^2)
$$
Luego, aplicamos la propiedad de logaritmos:
$$
\log_5(10^2) = 2\log_5(10)
$$
Dado que $\log_5(10)$ se puede encontrar usando el cambio de base:
$$
\log_5(10) = \frac{\log_{10}(10)}{\log_{10}(5)} = \frac{1}{\log_{10}(5)} \approx \frac{1}{0.699} \approx 1.43 \quad (\text{aproximadamente})
$$
Ahora calculamos:
$$
\log_5(0.07) = \log_5(7) - 2\log_5(10) \approx 1.2 - 2 \cdot 1.43 \approx 1.2 - 2.86 \approx -1.66
$$

## 2. Halla $\log_5(35)$

Para la segunda expresión, notamos que:
$$
35 = 5 \cdot 7
$$
Usamos propiedades de logaritmos:
$$
\log_5(35) = \log_5(5 \cdot 7) = \log_5(5) + \log_5(7)
$$
Sabemos que $\log_5(5) = 1$, por lo que:
$$
\log_5(35) = 1 + \log_5(7) \approx 1 + 1.2 \approx 2.2
$$

## Resultados Finales:
1. $\log_5(0.07) \approx -1.66$
2. $\log_5(35) \approx 2.2$

Relacionado con [[Logaritmos]]