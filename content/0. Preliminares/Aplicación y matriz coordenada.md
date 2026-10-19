---
title: Aplicación y matriz coordenada
---
Sea $f : V \rightarrow W$ una [[Aplicación lineal|aplicación lineal]] y sean $B_V$ y $B_W$ [[Base o sistema generador minimal|bases]] de $V$ y $W$ de tamaño $n$ y $m$ respectivamente, denotamos su ==aplicación coordenada== asociada
$$
\begin{align*}
[f]_{B_W B_V}: \mathbb{F}_n &\rightarrow \mathbb{F}_m\\
[u]_{B_V} &\rightarrow [f]_{B_W B_V} \cdot [u]_{B_V} = [f(u)]_{B_W}
\end{align*}
$$

>[!tip] Técnica: Matriz coordenada de una aplicación lineal
>Sea $B_V = \{v_1, \dots , v_n\}$ y $B_W$ [[Base o sistema generador minimal|bases]] de $V$ y $W$, y sea $f : V \rightarrow W$ [[Aplicación lineal|lineal]]. Entonces la matriz asociada a $f$ en las [[Base o sistema generador minimal|bases]] de salida $B_V$ y llegada $B_W$ tiene en su columna $i$-ésima el valor $[f(v_i)]_{B_W}$ , es decir, la ==matriz coordenada== queda de tamaño $m \times n$ con valores
>$$
>[f]_{B_W B_V} =([f(v_1)]_{B_W}\quad[f(v_2)]_{B_W}\quad[f(v_3)]_{B_W}\quad\dots\quad[f(v_n)]_{B_W})
>$$

>[!abstract] Lema
>Sea $A$ la matriz asociada a una [[Aplicación lineal|aplicación lineal]] $f : V \rightarrow W$ en [[Base o sistema generador minimal|bases]] $B_V$ y $B_W$ respectivamente tal que $\text{dim }V = n$, tenemos que:
>- las coordenadas de los [[Conjunto de elementos|elementos]] de $\text{ker }f$ en $B_V$ son $\text{Nul }A$, donde 
>  $$
> \text{Nul }A := \{x \in \mathbb{F}^n: Ax = 0\}.
> $$
>- las coordenadas de los [[Conjunto de elementos|elementos]] de $\text{Im }f$ en $B_W$ son $\text{Col }A$, donde 
>  $$
>  \text{Col }A := \{Ax : x \in \mathbb{F}^n\} = \text{Gen}⟨\text{Col}_1A, \dots , \text{Col}_nA⟩,
>  $$
>  siendo $\text{Col}_iA$ el vector correspondiente con la $i$-ésima columna de la matriz $A$.
>- si es [[Aplicación lineal|biyectiva]], $f^{-1}: V \rightarrow W$ tiene por matriz, en las mismas [[Base o sistema generador minimal|bases]] pero intercambiando orden salida-llegada, $A^{-1}$.