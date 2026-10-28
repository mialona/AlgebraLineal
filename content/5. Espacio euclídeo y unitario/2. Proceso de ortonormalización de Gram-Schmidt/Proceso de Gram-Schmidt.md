---
title: Proceso de Gram-Schmidth
---
>[!quote] Teorema. Proceso de Gram-Schmidt
>En cualquier [[Isometría y espacio euclídeo y unitario|espacio vectorial euclídeo o unitario]] $(V,\langle\cdot,\cdot\rangle)$ y para cualquier [[Familia libre|familia libre]] de vectores $\{v_1,\dots,v_n\}$ es posible encontrar una familia de vectores [[Ortogonalidad en productos escalares|ortonormada]] $\{w_1,\dots,w_n\}$ de modo que
>$$
>\text{Gen}\langle v_1,\dots,v_n\rangle=\text{Gen}\langle w_1,\dots,w_n\rangle,\quad k=1,\dots,m.
>$$

>[!warning] Observación
>Para evitar el uso de raíces hasta el final podemos ir construyendo
>$$
>w_{i+1}=v_{k+1}+\lambda_kw_k+\cdots+\lambda_1w_1,
>$$
>con
>$$
>\langle w_{i+1},w_j\langle=\langle v_{k+1},w_j\rangle+\lambda_j\langle w_j,w_j\rangle=0
>$$
>es decir $\lambda_i=\frac{\langle v_{k+1},w_j\rangle}{\langle w_j,w_j\rangle}$, $j=1,\dots,n$. Así $\{w_1,\dots,w_n\}$ será una familia ortogonal de vectores y para que sea ortonormada bastará tomar
>$$
>w_i'=\dfrac{w_i}{\lVert w_i\rVert}.
>$$

>[!success] Corolario
>Todo conjunto ortonormado de cualquier espacio euclídeo o unitario es libre y se puede completar hasta una base ortonormada.

