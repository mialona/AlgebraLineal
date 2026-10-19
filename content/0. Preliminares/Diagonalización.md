---
title: Diagonalización
---
>[!quote] Teorema del criterio de diagonalización
>Una matriz $A \in \mathcal{M}_{n \times n}(\mathbb{F})$ o [[Aplicación lineal|aplicación]] $f$ es ==diagonalizable== cuando
>- todas las [[Polinomio|raíces]] de $p_A(x)$ o de $p_f(x)$ están en $\mathbb{F}$.
>- en todos los [[Valores y vectores propios|valores propios]] coinciden las [[Multiplicidad y subespacio fundamental|multiplicidades algebraica y geométrica]].

> [!info] Ejemplo
> Sea la aplicación lineal
> $$
> \begin{align*}
> f : \mathbb{R}_2[x] &\rightarrow \mathbb{R}_2[x]\\
> a + bx + cx^2 &\rightarrow 2a + (a + 2b + c)x + (c - a)x^2
> \end{align*}
> $$
> Encuentra una base $B$ donde $f$ sea diagonal.
> 
> El primer paso es encontrar la matriz asociada a $f$ en bases canónicas.
> $$
> A = [f]_{B_c} =
> \begin{pmatrix}  
> 2 & 0 & 0\\  
> 1 & 2 & 1\\
> -1 & 0 & 1  
> \end{pmatrix}.
> $$
> En este caso $p_A(x) = |xI_3 - A| = (x - 1)(x - 2)^2$ así que los valores propios son $\lambda_1 = 1$ y $\lambda_2 = 2$, con multiplicidades algebraicas $m_a(1) = 1$ y $m_a(2) = 2$ respectivamente. El siguiente paso es calcular que
> $$
> \text{Nul}(I_3 − A) = \text{Gen}⟨(0, 1, -1)⟩,
> $$
> $$
> \text{Nul}(2I_3 - A) = \text{Gen}⟨(0, 1, 0),(1, 0, -1)⟩.
> $$
> Como en ambos casos las multiplicidades algebraicas coinciden con las geométricas, la matriz es diagonalizable. Así $A = P DP^{-1}$ con
> $$
> P=
> \begin{pmatrix}  
> 0 & 0 & 1\\  
> 1 & 1 & 0\\
> -1 & 0 & -1  
> \end{pmatrix},
> \quad\quad D=
> \begin{pmatrix}  
> 1 & 0 & 0\\  
> 0 & 2 & 0\\
> 0 & 0 & 2  
> \end{pmatrix}
> $$
> Esto significa que la base $B$ es $\{x − x^2 , x, 1 - x^2\}$, aquella que tiene por coordenadas en $B_c$ las columnas de $P$.