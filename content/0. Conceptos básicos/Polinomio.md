---
title: Polinomio
---
Un ==polinomio== es una expresión algebraica formada por la suma finita de productos entre coeficientes [[Ecuación lineal|constantes]] y [[Ecuación lineal|variables]] elevadas a exponentes enteros no negativos (naturales).

> [!info] Ejemplo
> Expresión general de un polinomio de una variable:
> $$
> P(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0
> $$

El ==grado== del polinomio es mismo que el de su monomio de mayor grado (suma de los exponentes de las variables que la componen) con coeficiente no nulo, y se denota por $\text{gr}(p)$.

Llamaremos ==raíz== (o cero) de un polinomio $P(x)$ al valor $\alpha$ tal que al sustituirlo en la variable, el resultado es igual a cero: $P(\alpha) = 0$.

Además, diremos que un polinomio es ==mónico== cuando su ==coeficiente principal== (el que acompaña al término de mayor grado) es igual a $1$.

>[!warning] Observación
> El ==polinomio de Taylor== es una aproximación polinómica de una función, $f(x)$, derivable $n$ veces en un entorno de un punto concreto $a$. Utiliza los valores de las derivadas de la función en ese punto para replicar su comportamiento local:
> $$
> P_{n}(x)=\sum _{k=0}^{n}\frac{f^{(k)}(a)}{k!}(x-a)^{k}=f(a)+\frac{f^{\prime }(a)}{1!}(x-a)+\frac{f^{\prime \prime }(a)}{2!}(x-a)^{2}+\dots +\frac{f^{(n)}(a)}{n!}(x-a)^{n}
> $$
> 
> Cuando el punto es $a = 0$, la aproximación recibe el nombre de ==polinomio de Maclaurin==.