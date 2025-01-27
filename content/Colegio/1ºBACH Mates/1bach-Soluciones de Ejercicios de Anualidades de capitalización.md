#### Ejercicio 1

Supón que deseas ahorrar para un fondo de emergencia y decides realizar depósitos mensuales de 500€ en una cuenta de ahorros que paga una tasa de interés mensual del 0.5%. Si planeas hacer estos depósitos durante 5 años, ¿Cuál será el valor futuro de esta anualidad al final del período?

**Datos:**

- Depósito mensual: 500€
- Tasa de interés mensual: 0.5% (o 0.005 en decimal)
- Período: 5 años (60 meses)

**Preguntas:**

1. ¿Cuál será el valor acumulado de los depósitos al cabo de 5 años?
2. Si decides no hacer más depósitos después de los 5 años, ¿Cuánto dinero tendrás en 10 años, suponiendo que la tasa de interés se mantiene constante?

**Solución**

El valor acumulado en 5 años se calcula mediante la fórmula de la [[Anualidades de capitalización|anualidad de capitalización]], teniendo en cuenta que al ser una capitalización mensual el tiempo debe medirse en meses (5 años son $5\times 12=60$ meses) y el rédito debe ser rédito mensual (el enunciado ya da el rédito mensual en este caso).

$$C=\frac{A[(1+r)^{t+1}-(1+r)]}{r}=\frac{500[(1+0.005)^{60+1}-(1+0.005)]}{0.005}=35.059, 44 \text{€}$$Para saber cuanto dinero tendrás en 10 años, debemos considerar ahora que estos 35.059,44€ se van a quedar en el depósito generando interés compuesto por 5 años (60 meses) más. Aplicando la fórmula para el interés compuesto se tiene $$C_f=C_i(1+r)^t=35.059,44\cdot(1+0,005)^{60}=47.289,93 \text{€}$$
**Aunque no lo pide el problema**, puedo calcular cuanto he aportado $$500 \text{€/mes}\cdot 60  \text{meses}=30.000 \text{€}$$Y cuantos intereses me ha generado el depósito tras 5 años $$35.059, 44\text{€}-30.000\text{€}=5.059,44\text{€}$$O cuantos intereses me ha generado tras 10 años $$47.289, 93\text{€}-30.000\text{€}=17.289,93\text{€}$$

--- 
#### Ejercicio 2

María quiere reunir 20.000€ para el pago inicial de un automóvil. Decide realizar depósitos mensuales de 300€ en una cuenta que ofrece una tasa de interés anual del 4,8%. ¿Cuánto tiempo le tomará alcanzar su objetivo de 20.000€?

**Datos:**

- Depósito mensual: 300€
- Tasa de interés anual: 4,8% (o 0.048 en decimal)
- Monto deseado: 20,000€

**Pregunta:**

- ¿Cuánto tiempo le tomará a María reunir los 20.000€?

**Solución**

Dado que queremos hallar el tiempo, debemos partir de la expresión para calcularlo en una anualidad de capitalización $$t=\log_{1+r}\left(\frac{C\cdot r}{A}+1+r\right)-1$$Y tener en cuenta que en este caso, al ser el interés anual, debemos dividirlo entre 12 para hallarlo en términos mensuales $$t=\log_{1+r/12}\left(\frac{C\cdot r/12}{A}+1+r/12\right)-1$$Sustituyendo los datos del problema $$t=\log_{1+0.048/12}\left(\frac{20000\cdot 0.048/12}{300}+1+0.048/12\right)-1=59, 00$$Recordamos que el resultado es en meses y si lo queremos en años veremos que, al dividir por 12 serán prácticamente 5 años.