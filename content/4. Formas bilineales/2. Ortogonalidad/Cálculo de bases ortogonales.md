---
title: Cálculo de bases ortogonales
---
>[!quote] Teorema
>Todo [[Forma bilineal|espacio vectorial ortogonal]] posee [[Ortogonalidad|bases ortogonales]] (si $\text{car}\,\mathbb{F}\neq 2$).

>[!warning] Observación
>Una forma de obtener una base ortogonal del espacio ortogonal $(V,f)$ consiste en formar la [[Forma cuadrática|forma cuadrática]] $Q(v)=f(v,v)$ con [[Forma cuadrática|matriz de Gram]] $M$ en una [[Base o sistema generador minimal|base]] $\mathcal{B}$ y [[Base ortogonal y completar cuadrados|completar cuadrados]] para llegar a una matriz $P$ tal que
>$$
>P^tMP=\text{diag}(\alpha_1,\dots,\alpha_r,0,\dots,0).
>$$
>Si $\mathcal{B}'$ es la base tal que $P=c_{\mathcal{B}\mathcal{B}'}$ es la [[Cambio de base|matriz de cambio de base]], entonces $\mathcal{B}'$ es ortogonal.

> [!info] Ejemplo. Calculando una base ortogonal mediante complementos ortogonales
> Sea $f\colon \mathbb{R}^3\times\mathbb{R}^3\to\mathbb{R}$ la forma bilineal con matriz coordenada en $\mathcal{B}=\{e_1,e_2,e_3\}$
> $$
> A=\begin{pmatrix}
> 2&2&-1\\
> 2&-1&2\\
> -1&2&2\end{pmatrix}
> $$
> 1. Buscamos un vector [[Ortogonalidad|anisótropo]]. Por ejemplo $v_1=e_1$ y definimos $S_1=\text{Gen}\langle v_1\rangle$. Calculamos
> $$
> \begin{split}
> S_1^\perp&=\{xe_1+ye_2+ze_3\in\mathbb{R}^2 : (1,0,0)\cdot A\cdot(x,y,z)^t=0\}\\
> &=\{e_1+ye_2+ze_3 :2x+2y-z=0\}=\text{Gen}\langle e_1+2e_3,e_2+2e_3\rangle.
> \end{split}
> $$
> 2. Buscamos un vector $v_2\in S_1^\perp$ anisótropo (si existe). Puesto que $f(e_1+2e_3,e_1+2e_3)=6$ entonces tomamos $v_2=e_1+2e_3$, definimos $S_2=\text{Gen}\langle v_1,v_2\rangle$ y calculamos
> $$
> S_2^\perp=\{xe_1+ye_2+ze_3 : 2x+2y-z=2y+z=0\}=\text{Gen}\langle -2e_1+e_2-2e_3\rangle.
> $$
> 3. Definimos $v_3=-2e_1+e_2-2e_3$. Una base ortogonal es $\{e_1,e_1+2e_3,-2e_1+e_2-2e_3\}$. La [[Matriz de Gram de una forma bilineal|matriz coordenada]] de $f$ en esta base es
> $$
> \begin{pmatrix}
> 2&0&0\\
> 0&6&0\\
> 0&0&-9
> \end{pmatrix}.
> $$