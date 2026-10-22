---
title: Cambio de base
---
En un [[Espacio vectorial|espacio vectorial]] pueden existir diferentes [[Base o sistema generador minimal|bases]], luego diferentes sistemas de [[Coordenadas en una base|coordenadas]]. Esto nos puede lleva a querer buscar una [[Aplicación lineal|aplicación]] que convierta las coordenadas en una base $\mathcal{B}_1$ a coordenadas en otra base $\mathcal{B}_2$.

Sean $\mathcal{B}_1 = \{u_1, \dots , u_n\}$, $\mathcal{B}_2 = \{v_1, \dots , v_n\}$ la aplicación $c_{\mathcal{B}_2\mathcal{B}_1}$ que convierte coordenadas en $\mathcal{B}_1$ en coordenadas en $\mathcal{B}_2$ tiene por matriz a derecha
$$
([u_1]_{\mathcal{B}_2}\quad[u_2]_{\mathcal{B}_2}\quad\dots\quad[u_n]_{\mathcal{B}_2}).
$$
Donde los $[u_i]_{\mathcal{B}_2}$ se ponen en columnas. Esto viene a decirnos que para cambiar de base $\mathcal{B}_1$ a base $\mathcal{B}_2$ basta con saber qué coordenadas tienen en $\mathcal{B}_2$ los elementos de la base $\mathcal{B}_1$. De forma análoga, $c_{\mathcal{B}_1\mathcal{B}_2} = (c_{\mathcal{B}_2\mathcal{B}_1} )^{-1}$ tiene por expresión matricial
$$
([v_1]_{\mathcal{B}_1}\quad[v_2]_{\mathcal{B}_1}\quad\dots\quad[v_n]_{\mathcal{B}_1}).
$$

>[!tip] Técnica: Cambio de base
>Las definiciones anteriores nos dan un buen procedimiento para calcular dichas matrices de cambio. Sin embargo, a veces cambiar de $\mathcal{B}_1$ a $\mathcal{B}_2$ directamente es complejo. En esos casos puede ser mejor cambiar a una base intermedia auxiliar. Una muy útil suele ser la base canónica $\mathcal{B}_c$. Así
>$$
>c_{\mathcal{B}_1\mathcal{B}_2} = c_{\mathcal{B}_1\mathcal{B}_c} \circ c_{\mathcal{B}_c\mathcal{B}_2} = (c_{\mathcal{B}_c\mathcal{B}_1} )^{-1} \circ c_{\mathcal{B}_c\mathcal{B}_2}
>$$
>De donde deducimos que $P = N^{-1}M$. Aplicando propiedades también obtenemos $NP = M$, $P^{-1} = M^{-1}N$, $N = MP^{-1}, ...