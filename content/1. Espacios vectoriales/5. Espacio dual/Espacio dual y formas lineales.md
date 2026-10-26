---
title: Espacio dual y formas lineales
---
Sea $V$ un [[Espacio vectorial|espacio vectorial]], definimos su ==espacio dual== como
$$
V^∗ := \{f : V \rightarrow \mathbb{F} : f\text{ es lineal}\}.
$$

Las aplicaciones de $V ^∗$, que van a $\mathbb{F}$, reciben el nombre de ==formas lineales==.

Como el dual se compone de [[Aplicación lineal|aplicaciones lineales]] podemos operarlas:
- Sumarlas: $(f + g)(v) = f(v) + g(v)$
- Multiplicarlas por un escalar: $(\alpha \cdot f)(v) = \alpha \cdot f(v)$

Y su resultado vuelve a estar en $V^∗$. Esto nos lleva a poder hacer la siguiente afirmación:

>[!example] Proposición
>Sea $V$ un espacio vectorial, su dual $V^∗$ es también espacio vectorial.