---
title: Dimensión de un espacio vectorial
---
La ==dimensión== de un [[Espacio vectorial|espacio vectorial]] es el número de [[Conjunto de elementos|elementos]] que tiene una cualquiera de sus [[Base o sistema generador minimal|bases]].

>[!warning] Observación
>Sea $S \leq V$ un [[Subespacio vectorial|subespacio]] definido por $n$ ecuaciones implícitas [[Familia libre|independientes]], entonces $\text{dim }S = \text{dim }V - n$. Es decir, cada ecuación implícita reduce en uno la dimensión. Podemos comprobar si un [[Sistema de ecuaciones lineales|sistema de ecuaciones lineales]] es [[Familia libre|independiente]] estudiando el [[Rango y traza de una matriz|rango]] de su matriz de coeficientes.

> [!info] Ejemplos
> - El espacio vectorial $\{0\}$ tiene dimensión cero y su base es $\{\} = \varnothing$.
> - La siguiente matriz de coeficientes define un subespacio 2-dimensional dentro de $\mathbb{R}^3$ .
> $$
> \begin{pmatrix}
> 1 & 2 & 0\\  
> 0 & 1 & -1\\
> 1 & 0 & 2  
> \end{pmatrix}
> \rightarrow
> \begin{pmatrix}
> 1 & 2 & 0\\  
> 0 & 1 & -1\\
> 0 & 0 & 0 
> \end{pmatrix}
> \rightarrow
> \begin{pmatrix}
> 1 & 0 & 2\\  
> 0 & 1 & -1\\
> 0 & 0 & 0 
> \end{pmatrix}
> $$
> No lo conocemos, pero vendrá definido por una ecuación implícita.