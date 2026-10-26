---
title: Matrices equivalentes
---
Dos matrices $A$ y $B$ de tamaño $n\times m$ se dicen ==equivalentes== si existen matrices $P$ de tamaño $n\times n$ y $Q$ de tamaño $m\times m$, ambas invertibles, tales que 
$$
A=PBQ.
$$
>[!warning] Observación
>Dos matrices son equivalentes si y solo si son las [[Aplicación y matriz coordenada|matrices coordenadas]] de una misma [[Aplicación lineal|aplicación lineal]] $f\colon V\to W$ en diferentes [[Base o sistema generador minimal|bases]]. Es decir, si y solo si existen bases $\mathcal{B}_V,\,\mathcal{B}_V'$ de $V$ y $\mathcal{B}_W,\,\mathcal{B}_W'$ tales que
>$$
>A=[f]_{\mathcal{B}_W\mathcal{B}_V},\quad B=[f]_{\mathcal{B}'_W\mathcal{B}'_V}.
>$$
>En este caso además $P=c_{\mathcal{B}_W\mathcal{B}'_W}$ y $Q=c_{\mathcal{B}'_V\mathcal{B}_V}$ son las [[Cambio de base|matrices de cambio de base]] apropiadas y la relación entre las matrices se puede leer como
>$$
>[f]_{\mathcal{B}_W\mathcal{B}_V}=c_{\mathcal{B}_W\mathcal{B}'_W}\cdot[f]_{\mathcal{B}'_W\mathcal{B}'_V}\cdot c_{\mathcal{B}'_V\mathcal{B}_V}.
>$$

>[!warning] Observación
>Dos matrices son equivalentes también si podemos pasar de una a otra mediante las operaciones del método de Gauss-Jordan. En este caso la matriz $P$ se obtiene aplicando las mismas operaciones empleadas a las filas de la matriz identidad y $Q$ aplicando las operaciones a las columnas.