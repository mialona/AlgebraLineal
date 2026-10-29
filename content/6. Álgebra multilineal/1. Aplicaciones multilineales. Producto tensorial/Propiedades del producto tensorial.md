---
title: Propiedades del producto tensorial
---
>[!example] Proposición. Propiedades del producto tensorial
>Sean $V_1,\dots,V_n$ una serie de $\mathbb{F}$-[[Espacio vectorial|espacio vectoriales]] y consideramos su [[Producto tensorial|producto tensorial]] $V_1\otimes\cdots\otimes V_n$.
>1. Un modo de [[Sistema generador|generarlo]], que no de tener una [[Base o sistema generador minimal|base]], es
>$$
>V_1\otimes\cdots\otimes V_n=\text{Gen}\langle v_1\otimes\cdots\otimes v_N : v_i\in V,i=1,\dots,n\rangle.
>$$
>2. Dentro del producto tensor hay equivalencias debido a la naturaleza [[Aplicación multilineal|multilineal]]
>$$
>\begin{split}
>v_1\otimes\cdots v_{i-1}&\otimes(\alpha v_i+\beta v_i')\otimes v_{i+1}\otimes\cdots\otimes v_n\\
>&=\alpha v_1\otimes \cdots\otimes v_{i-1}\otimes v_i\otimes v_{i+1}\otimes\cdots\otimes v_n\\
>&+\beta v_1\otimes \cdots\otimes v_{i-1}\otimes v'_i\otimes v_{i+1}\otimes\cdots\otimes v_n.
>\end{split}
>$$
>3. Dada $f\colon V_1\times \cdots\times V_n\to V$ multilineal, existe una única $\overline{f}\colon V_1\otimes\cdots\otimes V_n\to V$ [[Aplicación lineal|lineal]] tal que $\overline{f}(v_1\otimes\cdots\otimes v_n)=f(v_1,\dots,v_n)$.

>[!example] Proposición. Asociatividad
>Sean $U,V,W$ tres $\mathbb{F}$-espacios vectoriales. Se tiene que
>$$
>(U\otimes V)\otimes W\cong U\otimes V\otimes W\cong U\otimes(V\otimes W).
>$$

>[!example] Proposición. Conmutatividad
>Sean $U,V$ dos $\mathbb{F}$-espacios vectoriales. Se tiene que
>$$
>U\otimes V\cong V\otimes U.
>$$

>[!example] Proposición. El cuerpo es neutro
>Sea $V$ un $\mathbb{F}$-espacio vectorial. Se tiene que
>$$
>V\cong\mathbb{F}\otimes V\cong V\otimes\mathbb{F}.
>$$

>[!example] Proposición. Distributividad
>Sean $V_1,V_2,V$ tres $\mathbb{F}$-espacios vectoriales. Se tiene que
>$$
>\begin{split}
>(V_1\otimes V)\oplus(V_2\otimes V)&\cong(V_1\oplus V_2)\otimes V,\\
>(V\otimes V_1)\oplus(V\otimes V_2)&\cong V\otimes(V_1\oplus V_2).
>\end{split}
>$$

>[!example] Proposición. Bases y dimensión
>Sea $\mathcal{B}_i=\{e_{i1},\dots,e_{in_i}\}$ una base de $V_i$, par $i=1,\dots,n$. Se tiene que
>$$
>\mathcal{B}=\mathcal{B}_1\otimes\cdots\otimes\mathcal{B}_n=\{e_{1j_1}\otimes\cdots\otimes e_{nj_n} : e_{ij_i}\in\mathcal{B}_i\}
>$$
>es base de $V_1\otimes\cdots\otimes V_n$. En particular,
>$$
>\text{dim}(V_1\otimes\cdots\otimes V_n)=\prod_{i=1}^n\text{dim}\, V_i=(\text{dim}\, V_1)\cdot(\text{dim}\, V_2)\cdots(\text{dim}\, V_n).
>$$

>[!example] Proposición. Dual
>Sean $V_1,\dots,V_n$ una serie de $\mathbb{F}$-espacios vectoriales de [[Dimensión de un espacio vectorial|dimensión]] finita. Se tiene que
>$$
>(V_1\otimes\cdots\otimes V_n)^*\cong V_1^*\otimes\cdots\otimes V_n^*.
>$$

