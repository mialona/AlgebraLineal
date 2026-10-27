---
title: Isometrías entre espacios simplecticos
---
>[!quote] Teorema
>Si $(V,f)$ es un [[Forma bilineal|espacio vectorial simpléctico]] de [[Dimensión de un espacio vectorial|dimensión]] $n$, entonces existe una [[Base o sistema generador minimal|base]] $\mathcal{B}$ de $V$ de tal modo que la [[Matriz de Gram de una forma bilineal|matriz coordenada]] en dicha base es (expresada en bloques)
>$$
>\begin{pmatrix}
>0_s&I_s&0_{s\times k}\\
>-I_s&0_s&0_{s\times k}\\
>0_{k\times s}&0_{k\times s}&0_{k\times k}
>\end{pmatrix},
>$$
>con $k=n-2s$. O lo que es lo mismo
>$$
>f(v,w)=x_1y_{s+1}-y_1x_{s+1}+\cdots+x_sy_{2s}-y_sx_{2s}
>$$
>si $v$ y $w$ tienen coordenadas $(x_1,\dots,x_n)$ e $(y_1,\dots,y_n)$ en $\mathcal{B}$.

>[!warning] Observación
>Según el teorema, el [[Cambio de coordenadas en una forma bilineal|rango]] de $f$ es par (vale $2s$). Por lo tanto, ningún espacio vectorial simpléctico de dimensión impar puede ser [[Cambio de coordenadas en una forma bilineal|regular]].

Si en el teorema la matriz se obtiene en la base $\{v_1,\dots,v_s,w_1,\dots,w_s,z_1,\dots,z_k\}$ y la cambiamos por $\mathcal{B}'=\{v_1,w_1,\dots,v_s,w_s,z_1,\dots,z_s\}$ obtenemos una matriz diagonal por bloques $\begin{pmatrix}0&1\\-1&0\end{pmatrix}$
$$
\left(\begin{array}{cc|c|cc|ccc}
0&1&\cdots&0&0&0\cdots&0\\
-1&0&\cdots&0&0&0\cdots&0\\\hline
\vdots&\vdots&\ddots&\vdots&\vdots&\vdots&\ddots&\vdots\\\hline
0&0&\cdots&0&1&0&\cdots&0\\
0&0&\cdots&-1&0&0\cdots&0\\\hline
0&0&\cdots&0&0&0&\cdots&0\\
\vdots&\vdots&\ddots&\vdots&\vdots&\vdots&\ddots&\vdots\\
0&0&\cdots&0&0&0&\cdots&0
\end{array}\right)
$$
Esta es una base de ==planos hiperbólicos== donde cada $S_i=\langle v_i,w_i\rangle$ conforma cada uno de estos planos.

>[!success] Corolario
>Dos espacios vectoriales simplécticos $(V,f)$ y $(V',f')$ son isométricos si y solo si $\text{dim}\, V=\text{dim}\, V'$ y $\text{rang}(f)=\text{rangl}(f')$.

>[!success] Corolario
>Todo espacio vectorial simpléctico $(V,f)$ de dimensión $n$ es isométrico a $(\mathbb{F}^n,f')$con
>$$
>f'((x_1,\dots,x_n),(y_1,\dots,y_n))=x_1y_{s+1}-y_1x_{s+1}+\cdots+x_sy_{2s}-y_sx_{2s}
>$$
>y $2s=\text{rang}(f)$.

>[!success] Corolario
>Dada $A\in\mathcal{M}_{n\times n}(\mathbb{F})$ antisimétrica, entonces existe $P$ invertible tal que
>$$
>PAP^t=\begin{pmatrix}
>0_s&I_s&0_{s\times k}\\
>-I_s&0_s&0_{s\times k}\\
>0_{k\times s}&0_{k\times s}&0_{k\times k}
>\end{pmatrix}
>$$
>con $\text{rang}(A)=2s$ y $k=n-2s$.
