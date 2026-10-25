---
title: Base y dimensión del espacio dual
---
Una [[Aplicación lineal|aplicación lineal]] se puede definir de manera inequívoca a partir de las [[Imagen, preimagen y núcleo|imágenes]] de una [[Base o sistema generador minimal|base]] aplicando linealidad.

>[!quote] Teorema
>Sea $\mathcal{B} = \{v_1, \dots , v_n\}$ base de $V$ definimos $v^∗_i$ como la aplicación lineal tal que
>$$
>v^∗_i(v_j) = \delta_{i,j} =
>\begin{cases}
> 1 \quad \text{si }i=j\\
> 0 \quad \text{si }i\neq j
> \end{cases}
>$$
>Entonces $\mathcal{B}^∗ = \{v^∗_1 , \dots , v^∗_n\}$ es una base de $V^∗$ y $\text{dim }V^∗ = \text{dim }V$.

>[!warning] Observación
>Si $\{e_1, \dots , e_n\}$ es la [[Base canónica|base canónica]], $\{e ^∗ _1 , \dots , e^∗_n\}$ es la base canónica del [[Espacio dual y formas|dual]].

>[!tip] Técnica: Coordenadas en el dual
>Sean $\mathcal{B} = \{v_1, \dots , v_n\}$ y $\mathcal{B}^∗ = \{v^∗_1 , \dots , v^∗_n\}$ bases de $V$ y $V^∗$. Si $f \in V^∗$, se tiene que $[f]_{\mathcal{B}^∗} = (f(v_1), \dots , f(v_n))$.