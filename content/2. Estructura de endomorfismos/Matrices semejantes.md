---
title: Matrices semejantes
---
Dos matrices $A$ y $B$ de tamaño $n\times n$ se dicen ==semejantes== si existe una matriz invertible $P$ tal que 
$$
A=PBP^{-1}.
$$

>[!warning] Observación
>Dos matrices $A$ y $B$ semejantes son también [[Matrices semejantes|semejantes]]. Además dos matrices son equivalentes si y solo si las dos son [[Aplicación y matriz coordenada|matrices coordenadas]] de un mismo [[Aplicación lineal|endomorfismo]] en diferentes [[Base o sistema generador minimal|bases]]. Es decir, si existe $f\colon V\to V$ y bases $\mathcal{B}_1,\,\mathcal{B}_2$ tales que
>$$
>A=[f]_{\mathcal{B}_1\mathcal{B}_1},\quad B=[f]_{\mathcal{B}_2\mathcal{B}_2}.
>$$
>Además en este caso la matriz $P$ será la [[Cambio de base|matriz de cambio de base]] $P=c_{\mathcal{B}_2\mathcal{B}_1}$.

>[!warning] Observación
>Dos matrices $A$ y $B$ comparten muchas propiedades entre ellas el determinante y la traza:
>$$
>\det(A)=\det(B),\quad \text{tr}\,(A)=\text{tr}\,(B).
>$$