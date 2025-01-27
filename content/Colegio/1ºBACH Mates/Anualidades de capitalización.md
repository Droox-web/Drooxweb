Las **anualidades de capitalización** son cantidades fijas que se depositan cada año a un interés compuesto durante un número fijo de años. Al final se consigue el capital más los intereses generados.

Si _A_ es la cantidad fija ingresada durante _t_ años y _r_ el tipo de [[Interés|interés]] compuesto en tanto por uno:

- Al final del primer año tendremos un capital $C=A(1+r)$ pues nuestra inversión $A$ lleva un año invertida a un interés de $r$.

- Al final del segundo año tendremos $C=A(1+r)+A(1+r)^2$ pues el dinero ingresado el primer año ya llevará 2 años al interés compuesto y el dinero ingresado este año llevará únicamente un año.

- Al final del tercer año tendremos $C=A(1+r)+A(1+r)^2+A(1+r)^3$ y podemos ver que en general tendremos
$$C=A(1+r)+A(1+r)^2+A(1+r)^3+ . . . + A(1+r)^t$$
Que es una suma de términos de [[Progresión geométrica|progresión geométrica]]. Esta suma puede hallarse y en este caso se obtiene $$C=\frac{A[(1+r)^{t+1}-(1+r)]}{r}$$
Puede interesarnos despejar el tiempo de esta ecuación. Si lo hacemos se obtiene

$$t=\log_{1+r}\left(\frac{C\cdot r}{A}+1+r\right)-1$$

Estas fórmulas están desarrolladas para interés anual y capitalización anual. Si nos ofrecen un producto con un periodo de capitalización distinto (semanal, mensual, trimestral, semestral...), necesitamos tener en cuenta que el rédito (o tipo de interés anual) debe dividirse por el número de intervalos en que se divida el año en cada caso (54 semanas, 12 meses, 4 trimestres, 2 semestres...) y que el tiempo debe medirse en el periodo de capitalización que se marque en cada caso.

[[Ejercicios de Anualidades de capitalización]]
