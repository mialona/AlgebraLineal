---
title: Aplicaciones normales
---
Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio euclídeo o unitario]] y $f\colon V\to V$ una [[Aplicación lineal|aplicación lineal]]. La aplicación $f$ se dice ==normal== si $f\circ f^*=f^*\circ f$, donde $f^*$ es su [[Aplicación adjunta|aplicación adjunta]].

>[!example] Proposición
>La aplicación lineal $f\colon V\to V$ es normal si y solamente si la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$ respecto de una [[Ortogonalidad en productos escalares|base ortonormada]] cumple que
>$$
>A\overline{A^t}=\overline{A^t}A.
>$$

>[!quote] Teorema espectral generalizado
>Sea $f\colon V\to V$ una aplicación normal. Se tiene que existe una [[Ortogonalidad en productos escalares|base ortonormada]] donde la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$
>- (Caso [[Isometría y espacio euclídeo y unitario|unitario]]) es diagonal.
>- (Caso [[Isometría y espacio euclídeo y unitario|euclídeo]]) es $\text{diag}(\lambda_1,\dots,\lambda_m,A_1,\dots,A_k)$ y $a_i>0$ con
>$$
>A_i=\begin{pmatrix}a_i&b_i\\-b_i&a_i\end{pmatrix}
>$$
>y $b_1,\dots,b_k>0$ y $\lambda_1\geq\cdots\geq \lambda_m$.

>[!success] Corolario
>- Si $A\in\mathcal{M}_n(\mathbb{C})$ cumple que $A\overline{A^t}=\overline{A^t}A$ entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|unitaria]] tal que
>$$
>PA\overline{P^t}=\text{diag}(\alpha_1,\dots,\alpha_n)
>$$
>- Si $A\in\mathcal{M}_n(\mathbb{R})$ cumple que $AA^t=A^tA$ entonces existe una matriz $P$ [[Ortogonalidad en productos escalares|ortogonal]] tal que
>$$
>PA\overline{P^t}=\text{diag}(\lambda_1,\dots,\lambda_m,A_1,\dots,A_k)
>$$
>con
>$$
>A_i=\begin{pmatrix}a_i&b_i\\-b_i&a_i\end{pmatrix}
>$$
>y $b_1,\dots,b_k>0$ y $\lambda_1\geq\cdots\geq \lambda_m$.

