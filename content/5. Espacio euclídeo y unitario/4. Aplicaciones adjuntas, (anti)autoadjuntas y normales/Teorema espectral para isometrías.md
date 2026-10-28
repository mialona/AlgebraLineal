---
title: Teorema espectral para isometrías
---
>[!example] Proposición
>Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]]. La [[Aplicación lineal|aplicación lineal]] $\varphi\colon V\to V$ es una [[Isometría y espacio euclídeo y unitario|isometría]] si y solamente si la [[Aplicación y matriz coordenada|matriz coordenada]] de $\varphi$ respecto de una [[Ortogonalidad en productos escalares|base ortonormada]] cumple que
>$$
>A\overline{A^t}=I_n=\overline{A^t}A.
>$$

>[!warning] Observación
>Toda isometría es una [[Aplicaciones normales|aplicación normal]].

>[!success] Corolario. Teorema espectral para isometrías
>Sea $\varphi\colon V\to V$ una isometría. Se tiene que existe una [[Ortogonalidad en productos escalares|base ortonormada]] donde la [[Aplicación y matriz coordenada|matriz coordenada]] de $\varphi$
>- (Caso [[Isometría y espacio euclídeo y unitario|unitario]]) es $\text{diag}(\alpha_1,\dots,\alpha_n)$ con $\lvert \alpha_i\rvert=1$ para $i=1,\dots,n$.
>- (Caso [[Isometría y espacio euclídeo y unitario|euclídeo]]) es $\text{diag}(1,\dots,1,-1,\dots,-1,A_1,\dots,A_k)$ y $a_i>0$ con
>$$
>A_i=\begin{pmatrix}\cos\alpha_i&\sin\alpha_i\\-\sin\alpha_i&\cos\alpha_i\end{pmatrix}
>$$
>con $\alpha_i\in(0,\pi)$ e $i=1,\dots,k$.

>[!success] Corolario
>- Sea $Q\in\mathcal{M}_n(\mathbb{C})$ una matriz [[Ortogonalidad en productos escalares|unitaria]]. Existe otra matriz unitaria $P$ tal que
>$$
>PQ\overline{P^t}=\text{diag}(\alpha_1,\dots,\alpha_n)
>$$
>con $\lvert \alpha_i\rvert=1$ para $i=1,\dots,n$.
>- Sea $Q\in\mathcal{M}_n(\mathbb{R})$ una matriz [[Ortogonalidad en productos escalares|ortogonal]]. Existe otra matriz ortogonal $P$ tal que
>$$
>PA\overline{P^t}=\text{diag}(1,\dots,1,-1,\dots,-1,A_1,\dots,A_k)
>$$
>con
>$$
>A_i=\begin{pmatrix}\cos\alpha_i&\sin\alpha_i\\-\sin\alpha_i&\cos\alpha_i\end{pmatrix}
>$$
>con $\alpha_i\in(0,\pi)$ e $i=1,\dots,k$.

>[!warning] Observación
>Notar que tomamos $\alpha_i\in(0,\pi)$ para que $\sin\alpha_i>0$, pero es un convenio.

