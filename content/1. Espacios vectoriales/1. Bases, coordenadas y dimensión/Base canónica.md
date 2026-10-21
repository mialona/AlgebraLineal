---
title: Base canónica
---
Una ==matriz escalonada== es aquella en la que el número de ceros a la izquierda del primer elemento distinto de cero (llamado ==pivote==) aumenta en cada fila.

Una matriz está en forma ==escalonada reducida== (por filas) cuando cumple las condiciones de una matriz escalonada y, además, cada pivote es igual a $1$ y es el único número distinto de $0$ en su columna.

> [!info] Ejemplo
> Para transformar una matriz a forma escalonada reducida utilizamos el método de Gauss-Jordan.
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

La [[Base o sistema generador minimal|base]] escalonada reducida de un [[Espacio vectorial|espacio vectorial]] total es la ==base canónica==.

> [!info] Ejemplos
> - En $\mathbb{F}^n$ la base canónica es $\{e_1, \dots , e_n\}$ donde $e_i$ es el vector nulo al que le ponemos un uno en la posición $i$.
> - En $\mathcal{M}_{n,m}$ la base canónica es $\{e_{ij} : 1 \leq i \leq n, 1 \leq j \leq m\}$. Aquí $e_{ij}$ es la matriz nula a la que le hemos puesto un uno en el elemento de la posición $(i, j)$.
> - En $\mathbb{F}_n[x]$ la base canónica es $\{1, x, \dots , x^n\}$.
