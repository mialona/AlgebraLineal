---
title: Adjunta de una aplicación
---
Si $f\colon V\to W$ es una [[Aplicación lineal|aplicación lineal]] entre dos [[Espacio vectorial|espacios vectoriales]], definimos su ==aplicación adjunta== como
$$
\begin{split}
f^\times\colon W^\circ&\to V^\circ\\
w&\mapsto w\circ f
\end{split}
$$
>[!quote] Teorema. Propiedades de la adjunta
>- Es lineal, $(\alpha f+\beta g)^\times=\alpha f^\times+\beta g^\times$.
>- Conmuta el orden de la composición, $(f\circ g)^\times=g^\times\circ f^\times$.
>- Preserva la inversa (cuando exista), $(f^{-1})^\times=(f^\times)^{-1}$.
>- Se tiene que $\ker(f^\times)=(\text{Im}\, f)^\circ$, $\text{Im}(f^\times)=(\ker\, f)^\circ$ y $\text{rang}(f^\times)=\text{rang}(f)$.