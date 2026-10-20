---
title: Imagen, preimagen y núcleo
---
Sea $f : V \rightarrow W$ una [[Aplicación lineal|aplicación lineal]] y sean $X \subseteq V$ e $Y \subseteq W$ se define:
- ==Imagen== de $f$ y se escribe $\text{Im }f$ a $f(V)$, a los valores que puede tomar $f$, es decir,
$$
\text{Im }f = f(V) = \{f(v) : v \in V\}
$$
- ==Preimagen== de $f$ a
$$
f^{-1}(Y) = \{v \in V : f(v) \in f(X)\}
$$
- ==Núcleo== de $f$ y se escribe $\text{ker }f$ a la preimagen del cero, es decir a aquellos [[Conjunto de elementos|elementos]] que tienen al cero por imagen:
$$
\text{ker }f = f^{-1}(0) = \{v \in V : f(v) = 0\}
$$

>[!warning] Observación
>Esta notación nos lleva a que $f(Gen⟨v_1, \dots , v_n⟩) = Gen⟨f(v_1), \dots , f(v_n)⟩$