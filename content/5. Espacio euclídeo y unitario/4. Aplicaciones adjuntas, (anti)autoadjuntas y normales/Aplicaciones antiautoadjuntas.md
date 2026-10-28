---
title: Aplicaciones antiautoadjuntas
---
>[!example] Proposición
>Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]]. La [[Aplicación lineal|aplicación lineal]] $f\colon V\to V$ es [[Aplicación adjunta|antiautoadjunta]] si y solamente si la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$ respecto de una [[Ortogonalidad en productos escalares|base ortonormada]] es anti[[Matriz hermitiana|hermitiana]] ($\overline{A^t}=-A$).

>[!example] Proposición
>Los [[Valor y vector propio|valores propios]] de una matriz antihermitiana son siempre imaginarios puros.

>[!quote] Teorema espectral para aplicaciones antiautoadjuntas
>Dada una aplicación lineal $f\colon V\to V$ antiautoadjunta existe una base ortonormada donde la matriz coordenada de $f$
>- (Caso [[Isometría y espacio euclídeo y unitario|unitario]]) es diagonal.
>- (Caso [[Isometría y espacio euclídeo y unitario|euclídeo]]) es $\text{diag}(0,\dots,0,A_1,\dots,A_k)$ y $a_i>0$ para $i=1,\dots,k$ con
>$$
>A_i=\begin{pmatrix}0&a_i\\-a_i&0\end{pmatrix}.
>$$

>[!success] Corolario
>- Si $A\in\mathcal{M}_n(\mathbb{C})$ es una matriz antihermitiana ($\overline{A^t}=-A$) entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|unitaria]] tal que
>$$
>PA\overline{P^t}=\text{diag}(\alpha_1,\dots,\alpha_n)
>$$
>con $\alpha_j=a_j i$ imaginarios puros.
>- Si $A\in\mathcal{M}_n(\mathbb{R})$ es una matriz antisimétrica ($A^t=-A$) entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|ortogonal]] tal que
>$$
>PA\overline{P^t}=\text{diag}(0,\dots,0,A_1,\dots,A_k)
>$$
>con
>$$
>A_i=\begin{pmatrix}0&a_i\\-a_i&0\end{pmatrix}
>$$
>para $i=1,\dots,k$ y $a_i>0$.