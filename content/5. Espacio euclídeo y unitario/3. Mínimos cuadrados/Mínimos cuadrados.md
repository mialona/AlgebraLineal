---
title: Mínimos cuadrados
---
A veces, un [[Sistema de ecuaciones lineales|sistema de ecuaciones]]
$$
AX=b
$$
puede ser incompatible, pero aún así nos interese dar una "solución aproximada". Por ejemplo, en física, la ==ley de Hook== establece que un resorte se contrae proporcionalmente a la fuerza aplicada, es decir
$$
F=a+kx,
$$
donde $x$ es la longitud del resorte al aplicarse una fuerza $F$ y $a$ y $k$ son dos constantes que dependen de dicho resorte las cuales podemos averiguar aplicando distintas fuerzas y midiendo. Por ejemplo en un experimento podemos obtener los valores
$$
\begin{array}{c|cccc}
F&0&2&4&6\\\hline
x&6.1&7.6&8.7&10.4
\end{array}
$$
Sin embargo, al plantear el sistema
$$
\begin{split}
a+6.1x&=0,\\
a+7.6x&=2,\\
a+8.7x&=4,\\
a+10.4x&=6,
\end{split}
$$
nos queda incompatible. En la práctica, esto es muy frecuente y se debe a errores experimentales de medición. Sería, por tanto, deseable encontrar los valores de $a$ y $k$ tales que $a+6.1x$; $a+7.6x$; $a+8.7x$ y $a+10.4x$ estuviesen lo más cerca posible de $0,2,4$ y $6$ respectivamente. Es decir
$$
(a+6.1x-0)^2+(a+7.6x-2)^2+(a+8.7x-4)^2+(a+10.4x-6)^2
$$
sea mínimo. Buscamos, por tanto, una solución por ==mínimos cuadrados==. Si planteamos un sistema general
$$
AX=b,
$$
estamos buscando el vector $X_0$ que cumpla que
$$
\lVert AX_0-b\rVert\leq\lVert Ax-b\rVert
$$
sea mínimo, es decir, para todo $x\in\mathbb{F}^n$ y con $\lVert\cdot\rVert$ la [[Norma de un vector|norma]] usual. Si $\text{Col}\, A$ es el espacio de columnas de $A$, es decir, el [[Espacio vectorial|espacio vectorial]] generado por sus vectores columna. Cuando $X$ recorre $\mathbb{F}^n$, $Y=AX$ recorre $\text{Col}\, A$, así buscamos $Y_0=AX_0\in\text{Col}\, A$ tal que
$$
\lVert Y_0-b\rVert
$$
sea mínimo. Este $Y_0$ es la [[Subespacios ortogonales|proyección ortogonal]] de $b$ en $\text{Col}\, A$.

>[!example] Proposición
>Las soluciones por mínimos cuadrados de $AX=b$ son exactamente las soluciones de
>$$
>\overline{A^t}AX=\overline{A^t}b.
>$$

>[!success] Corolario
>Sea $A\in\mathcal{M}_{m\times n}(\mathbb{F})$ con $\text{rang}(A)=n$ y $b\in\mathbb{F}^n$. Existe una única solución por mínimos cuadrados del sistema $AX=b$.

