---
title: Bases alternativas en subespacios f-invariantes maximales
---
Podemos encontrar [[Bases alternativas en subespacios f-invariantes maximales|bases alternativas]], dentro de subespacios $f$-[[Subespacio invariante|invariantes]] maximales, que mejoren la estructura por bloques al permitirnos romperla aún más.

>[!quote] Teorema
>Sea $v \in V$ tal que $m_v(x) = q(x)^k$ con $q(x)$ [[Polinomio|irreducible]] en $\mathbb{F}[x]$ y siendo
>$$
>q(x) = a_0 + a_1x + \dots + a_{n-1}x^{n-1} + x^n
>$$
>$$
>q(x)^k = b_0 + b_1x + \dots + b_{m-1}x^{m-1} + x^m.
>$$
>entonces $\mathcal{B}_1 = \{v, f(v), \dots , f_{m-1} (v)\}$ y
>$$
>\mathcal{B}_2 = \{v, f(v), \dots , f^{n-1} (v),\\ q(f)(v), f(q(f)(v)), \dots , f^{n-1} (q(f)(v)), \dots ,\\ q(f)^{k-1} (v), f(q(f)^{k-1} (v)), \dots , f^{n-1} (q(f)^{k-1} (v))\}
>$$
>son ambas bases de $S = \mathbb{F}[x](f)(v)$ y en ellas la [[Aplicación y matriz coordenada|matriz coordenada]] de $f|_S$ es
>$$
>[f|_S]_{\mathcal{B}_1} = C_{q(x)^k},\quad[f|_S]_{\mathcal{B}_2} = 
> \begin{pmatrix}  
> C_{q(x)} & 0_n & 0_n & \dots & 0_n & 0_n\\  
> M_n & C_{q(x)} & 0_n & \dots & 0_n & 0_n\\
> 0_n & M_n & C_{q(x)} & \dots & 0_n & 0_n\\
> \vdots & \vdots & \vdots & \ddots & \vdots & \vdots\\
> 0_n & 0_n & 0_n & \dots & M_n & C_{q(x)}
> \end{pmatrix},
>$$
>donde $M_n$ es la matriz $n \times n$ donde todas las entradas son cero, excepto la entrada $(1, n)$ que es $1$, $0_n$ representa a la matriz nula $n \times n$ y $C_{q(x)}$ es la [[Matriz compañera de un polinomio|matriz compañera]] asociada al polinomio $q(x)$.
