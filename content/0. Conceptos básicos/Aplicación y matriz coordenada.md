---
title: Aplicación y matriz coordenada
---
Sea $f : V \rightarrow W$ una [[Aplicación lineal|aplicación lineal]] y sean $\mathcal{B}_V$ y $\mathcal{B}_W$ [[Base o sistema generador minimal|bases]] de $V$ y $W$ de tamaño $n$ y $m$ respectivamente, denotamos su ==aplicación coordenada== asociada
$$
\begin{align*}
[f]_{\mathcal{B}_W \mathcal{B}_V}: \mathbb{F}_n &\rightarrow \mathbb{F}_m\\
[u]_{\mathcal{B}_V} &\rightarrow [f]_{\mathcal{B}_W \mathcal{B}_V} \cdot [u]_{\mathcal{B}_V} = [f(u)]_{\mathcal{B}_W}
\end{align*}
$$

>[!tip] Técnica: Matriz coordenada de una aplicación lineal
>Sea $\mathcal{B}_V = \{v_1, \dots , v_n\}$ y $\mathcal{B}_W$ bases de $V$ y $W$, y sea $f : V \rightarrow W$ lineal. Entonces la matriz asociada a $f$ en las bases de salida $\mathcal{B}_V$ y llegada $\mathcal{B}_W$ tiene en su columna $i$-ésima el valor $[f(v_i)]_{\mathcal{B}_W}$ , es decir, la ==matriz coordenada== queda de tamaño $m \times n$ con valores
>$$
>[f]_{\mathcal{B}_W \mathcal{B}_V} =([f(v_1)]_{\mathcal{B}_W}\quad[f(v_2)]_{\mathcal{B}_W}\quad[f(v_3)]_{\mathcal{B}_W}\quad\dots\quad[f(v_n)]_{\mathcal{B}_W})
>$$

>[!abstract] Lema
>Sea $A$ la matriz asociada a una aplicación lineal $f : V \rightarrow W$ en bases $\mathcal{B}_V$ y $\mathcal{B}_W$ respectivamente tal que $\text{dim }V = n$, tenemos que:
>- las coordenadas de los [[Conjunto de elementos|elementos]] de $\text{ker }f$ en $\mathcal{B}_V$ son $\text{Nul }A$, donde 
>  $$
> \text{Nul }A := \{x \in \mathbb{F}^n: Ax = 0\}.
> $$
>- las coordenadas de los elementos de $\text{Im }f$ en $\mathcal{B}_W$ son $\text{Col }A$, donde 
>  $$
>  \text{Col }A := \{Ax : x \in \mathbb{F}^n\} = \text{Gen}⟨\text{Col}_1A, \dots , \text{Col}_nA⟩,
>  $$
>  siendo $\text{Col}_iA$ el vector correspondiente con la $i$-ésima columna de la matriz $A$.
>- si es [[Aplicación lineal|biyectiva]], $f^{-1}: V \rightarrow W$ tiene por matriz, en las mismas bases pero intercambiando orden salida-llegada, $A^{-1}$.