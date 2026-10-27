---
title: Clasificación de formas cuadráticas
---
Una [[Forma cuadrática|forma cuadrática]] $Q\colon V\to\mathbb{R}$ se dice
- ==definida positiva== si $Q(v)>0$ para todo $v\neq 0$,
- ==definida negativa== si $Q(v)<0$ para todo $v\neq 0$,
- ==semidefinida positiva== si $Q(v)\geq 0$ para todo $v$,
- ==semidefinida negativa== si $Q(v)\leq 0$ para todo $v$,
- ==indefinida== si no es de ninguna de los tipos anteriores.

>[!tip] Técnica: Clasificar una forma cuadrática
>[[Base ortogonal y completar cuadrados|Formando cuadrados]] se puede saber el tipo de $Q(v)=\alpha_1x_1^2+\cdots+\alpha_rx_r^2$:
>- definida positiva si $\alpha_1,\dots,\alpha_r>0$ y $r=\text{dim}\, V$,
>- definida negativa si $\alpha_1,\dots,\alpha_r<0$ y $r=\text{dim}\, V$,
>- semidefinida positiva si $\alpha_1,\dots,\alpha_r\geq 0$,
>- semidefinida negativa si $\alpha_1,\dots,\alpha_r\leq 0$,
>- indefinida si existe $\alpha_i>0$ y $\alpha_j<0$.

>[!example] Proposición. Criterio de Sylvester
>Sea $Q$ una forma cuadrática con [[Forma cuadrática|matriz de Gram]] $A$ de orden $n\times n$, definimos para $i=1,\dots, n$ las submatrices de la parte superior izquierda
>$$
>A_i=\begin{pmatrix}
>\alpha_{11}\cdots&\alpha_{1i}\\
>\vdots&\ddots&\vdots\\
>\alpha_{i1}&\cdots&\alpha_{ii}
>\end{pmatrix}
>$$
>- $Q$ es definida positiva si y solo si $\lvert A_i\rvert >0$ para $i=1,\dots,n$.
>- $Q$ es definida negativa si y solo si $(-1)^i\lvert A_i\rvert>0$ para $i=1,\dots,n$.