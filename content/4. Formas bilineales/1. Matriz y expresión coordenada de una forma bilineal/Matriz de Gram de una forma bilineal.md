---
title: Matriz de Gram de una forma bilineal
---
Dada una [[Forma bilineal|forma bilineal]] $f\colon V\times V\to\mathbb{F}$ y una [[Base o sistema generador minimal|base]] $\mathcal{B}=\{v_1,\dots,v_n\}$ usando la bilinealidad de $f$ tenemos que
$$
f(v,w)=f(x_1v_1+\cdots+x_nv_n,y_1v_1+\cdot+y_nv_n)=\sum_{i=1}^n\sum_{j=1}^nx_if(v_i,v_j)y_j=(x_1,\dots,x_n)\begin{pmatrix}
f(v_1,v_1)&\cdots&f(v_1,v_n)\\
\vdots&\ddots&\vdots\\
f(v_n,v_1)&\cdots&f(v_n,v_n)
\end{pmatrix}\begin{pmatrix}
y_1\\\vdots\\ y_n\end{pmatrix}.
$$
La matriz
$$
M=[f]_{\mathcal{B}}=\begin{pmatrix}
f(v_1,v_1)&\cdots&f(v_1,v_n)\\
\vdots&\ddots&\vdots\\
f(v_n,v_1)&\cdots&f(v_n,v_n)
\end{pmatrix}
$$
se llama ==matriz de Gram== o ==matriz coordenada== de la forma bilineal $f$ respecto de la base $\mathcal{B}$. Además, si denotamos $X^t=(x_1,\dots,x_n)$ e $Y^t=(y_1,\dots,y_n)$ la expresión se puede escribir como
$$
f(v,w)=X^tMY.
$$

>[!warning] Observación
>Si tomamos una matriz cuadrada cualquiera $M$ y definimos $f(v,w)=X^t MY$, donde $X$ son las [[Coordenadas en una base|coordenadas]] de $v$ e $Y$ las de $w$, entonces $f$ cumple automáticamente todas las condiciones para ser una forma bilinea.

>[!abstract] Lema
>Sea $f\colon V\times V\to\mathbb{F}$ una forma bilineal y $\mathcal{B}$ una base de $V$. Si $\alpha_{ij}$ son constantes tales que $f(v,w)=\sum_{i=1}^n\sum_{j=1}^n x_i\alpha_{ij}y_j$ siempre que $[v]_{\mathcal{B}}=(x_1,\dots,x_n)$ y $[w]_{\mathcal{B}}=(y_1,\dots,y_n)$, entonces $\alpha_{ij}=f(v_i,v_j)$ son las entradas de la matriz coordenada de $f$ respecto de la base $\mathcal{B}$.

>[!example] Proposición
>Si $f\colon V\times V\to\mathbb{F}$ una forma bilineal con matriz coordenada $M$ en $\mathcal{B}$. Entonces:
>- $f$ es una forma bilineal [[Forma bilineal|simétrica]] si y solamente si la matriz $M$ es simétrica.
>- $f$ es una forma bilineal [[Forma bilineal|antisimétrica]] si y solamente si la matriz $M$ es antisimétrica.