---
title: Producto tensorial de aplicaciones
---
Sean $V_1,\dots,V_n,W_1,\dots,W_n$ $\mathbb{F}$-[[Espacio vectorial|espacios vectoriales]] y sean
$$
\varphi_i\colon V_i\to W_i,
$$
[[Aplicación lineal|aplicaciones lineales]]. A partir de ellas podemos definir una [[Aplicación multilineal|aplicación multilineal]]
$$
\begin{split}
V_1\times\cdots\times V_n&\to W_1\otimes\cdots\otimes W_n\\
(v_1,\dots,v_n)&\mapsto\varphi_1(v_1)\otimes\cdots\otimes\varphi_n(v_n)
\end{split}
$$
Por tanto, por la [[Producto tensorial|propiedad universal]] del [[Producto tensorial|producto tensor]], induce una única aplicación lineal
$$
\begin{split}
\varphi_1\otimes\cdots\otimes\varphi_n\colon V_1\otimes\cdots\otimes V_n&\to W_1\otimes\cdots\otimes W_n\\
v_1\otimes\cdots\otimes v_n&\mapsto\varphi_1(v_1)\otimes\cdots\otimes\varphi_n(v_n).
\end{split}
$$
A la aplicación $\varphi_1\otimes\cdots\otimes\varphi_n$ se le llama ==producto tensorial de las aplicaciones lineales== $\varphi_1,\dots,\varphi_n$.

>[!example] Proposición. Propiedades
>Sean $f,f_1,f_2\colon V_1\to W_1$ y $g,g_1,g_2\colon V_2\to W_2$ aplicaciones lineales. Se tiene que
>- $(f_1+f_2)\otimes g=f_\otimes g+f_2\otimes g$,
>- $f\otimes(g_1+g_2)=f\otimes g_1+f\otimes g_2$,
>- $(\alpha f)\otimes g=\alpha(f\otimes g)=f\otimes(\alpha g)$,
>- y si $h_1\colon W_1\to Z_1$, $h_2\colon W_2\to Z_2$ son lineales, entonces
>$$
>(h_1\otimes h_2)\circ(f\otimes g)=(h_1\circ f)\otimes(h_2\circ g).
>$$

>[!example] Proposición. Producto de Kronecker
>Sean $f_i\colon V_i\to W_i$ aplicaciones lineales para $i=1,2$ y $\text{dim}\, V_i=n_i$ y $\text{dim}\, W_i=m_i$ con matrices coordenadas
>$$
>[f_1]_{\mathcal{B}_{W_1}\mathcal{B}_{V_1}}=C_1=\begin{pmatrix}
>\alpha_{11}&\cdots&\alpha_{1n_1}\\
>\vdots&\ddots&\vdots\\
>\alpha_{m_11}&\cdots&\alpha_{m_1n_1}
>\end{pmatrix},\quad[f_2]_{\mathcal{B}_{W_2}\mathcal{B}_{V_2}}=C_2=\begin{pmatrix}
>\beta_{11}&\cdots&\beta_{1n_2}\\
>\vdots&\ddots&\vdots\\
>\beta_{m_21}&\cdots&\beta_{m_2n_2}
>\end{pmatrix}.
>$$
>Entonces la [[Aplicación y matriz coordenada|matriz coordenada]] de $f_1\otimes f_2$ en base de salida $\mathcal{B}_{V_1}\otimes\mathcal{B}_{V_2}$ y llegada $\mathcal{B}_{W_1}\otimes\mathcal{B}_{W_2}$  es de orden $(m_1m_2)\times(n_1n_2)$ y vale
>$$
>[f_1\otimes f_2]_{\mathcal{B}_{W_1}\otimes\mathcal{B}_{W_2},\mathcal{B}_{V_1}\otimes\mathcal{B}_{V_2}}=C_1\otimes C_2=\begin{pmatrix}
>\alpha_{11}C_2&\cdots&\alpha_{1n_1}C_2\\
>\vdots&\ddots&\vdots\\
>\alpha_{m_11}C_2&\cdots&\alpha_{m_1n_1}C_2
>\end{pmatrix}.
>$$
>A este producto de matrices se le llama ==producto de Kronecker== de las matrices $C_1$ y $C_2$.



