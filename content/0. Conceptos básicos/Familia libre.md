---
title: Familia libre
---
Un [[Conjunto de elementos|conjunto]] de vectores $\{v_1, v_2, \dots, v_m\}$ es ==linealmente independiente== o una ==familia libre== si la única solución a la [[Ecuación lineal|ecuación]]:
$$
\lambda_{1}v_{1}+\lambda _{2}v_{2}+\dots +\lambda _{m}v_{m}=0
$$
es que todos los escalares sean iguales a cero $(\lambda_1 = \lambda_2 = \dots = \lambda_m = 0)$.

Si existe al menos un escalar distinto de cero que cumpla la ecuación, los vectores son ==linealmente dependientes==.

>[!example] Proposición
>Sea $f : V \rightarrow W$ [[Aplicación lineal|lineal]] y $v_i \in V$ entonces:
>- Si $\{v_1, \dots , v_n\}$ es una familia libre y $f$ es [[Aplicación lineal|inyectiva]] entonces la familia $\{f(v_1), \dots, f(v_n)\}$ es libre.
>- Si $\{v_1, \dots , v_n\}$ es un [[Sistema generador|sistema generador]] de $V$ y $f$ es [[Aplicación lineal|suprayectiva]] entonces $\{f(v_1), \dots, f(v_n)\}$ es un [[Sistema generador|sistema generador]] de $W$.
>- Si $\{v_1, \dots , v_n\}$ es [[Base o sistema generador minimal|base]] de V y f es [[Aplicación lineal|biyectiva]] entonces $\{f(v_1), \dots, f(v_n)\}$ es [[Base o sistema generador minimal|base]] de W.