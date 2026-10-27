---
title: Base ortogonal y completar cuadrados
---
Sea $Q$ una [[Forma cuadrática|forma cuadrática]] y $f$ su [[Forma polar|forma polar]]. Una [[Base o sistema generador minimal|base]] $\{v_1,\dots,v_n\}$ se dice ==base ortogonal== si
$$
f(v_i,v_j)=0,\quad i\neq j.
$$
Es decir, la [[Forma cuadrática|matriz de Gram]] de $Q$ respecto de esa base es diagonal.

>[!example] Proposición
>Existe una base $\mathcal{B}'$ y $\alpha_1,\dots,\alpha_r\in\mathbb{F}$ no nulos, $r=\text{rang}(Q)$, tales que
>$$
>Q(v)=\alpha_1\hat{x}_1^2+\cdots+\alpha_r\hat{x}_r^2
>$$
>con $[v]_{\mathcal{B}'}=(\hat{x}_1,\dots,\hat{x}_r,\hat{x}_{r+1},\dots,\hat{x}_n)$.

Uno de los procesos usados para obtener estas bases se llama ==completar cuadrados==.

>[!success] Corolario
>Sea $Q$ es una forma cuadrática con [[Matrices congruentes y cambio de coordenadas|rango]] $\text{rang}(Q)=r$.
>- Si $\mathbb{F}=\mathbb{R}$ entonces existe una base $\mathcal{B}'$ donde $[v]_{\mathcal{B}'}=(\hat{x}_,\dots,\hat{x}_n)$ y
>$$
>Q(v)=\hat{x}_1^2+\cdots+\hat{x}_p^2-\hat{x}_{p+1}^2-\cdots-\hat{x}_r^2.
>$$
>- Si $\mathbb{F}=\mathbb{C}$ entonces existe una base $\mathcal{B}'$ donde $[v]_{\mathcal{B}'}=(\hat{x}_,\dots,\hat{x}_n)$ y
>$$
>Q(v)=\hat{x}_1^2+\cdots+\hat{x}_r^2.
>$$

