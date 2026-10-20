---
title: Rango y traza de una matriz
---
El ==rango== de una matriz $A$, habitualmente denotado como $\text{rg}(A)$ o $\text{rango}(A)$, es el número máximo de filas o de columnas de $A$ que son [[Familia libre|linealmente independientes]].

Si una matriz es de dimensión $m \times n$, su rango nunca puede ser mayor que el menor entre sus filas y sus columnas: $0 \leq \text{rg}(A) \leq \min(m, n)$.

>[!tip] Técnica: Obtención del rango de una matriz
>El rango de una matriz se puede obtener mediante:
>- **El método de Gauss**: Aplicar operaciones elementales por filas para escalonar la matriz; el rango es el número de filas no nulas restantes.
>- **Menores determinantes**: Buscar el orden del mayor menor no nulo dentro de la matriz.

---

La ==traza== de una matriz $A$ de orden $n \times n$ es la suma de los elementos que pertenecen a la diagonal principal de la matriz:
$$
\text{tr}(A)=\sum _{i=1}^{n}a_{ii}=a_{11}+a_{22}+\dots +a_{nn}
$$

>[!example] Proposición
>Propiedades de la traza de dos matrices $A$ y $B$:
>- $\text{tr}(A) = \text{tr}(A^T)$ (la traza es igual a la de su matriz traspuesta).
>- $\text{tr}(A + B) = \text{tr}(A) + \text{tr}(B)$
>- $\text{tr}(AB) = \text{tr}(BA)$