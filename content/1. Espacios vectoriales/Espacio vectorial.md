---
title: Espacio vectorial
---
Un [[Conjunto de elementos|conjunto]] no vacío $V$ es un $\mathbb{F}$-espacio vectorial (o simplemente ==espacio vectorial== si podemos sobreentender el cuerpo $\mathbb{F}$) cuando sobre $V$ tenemos definidas dos [[Operación interna|operaciones]] cuyo resultado queda en $V$: una suma de sus elementos y un producto por escalares de $\mathbb{F}$.

Además, estas operaciones, dados $u, v, w \in V$ y $\alpha, \beta ∈ \mathbb{F}$, deben cumplir:
1. Propiedades de la suma (análogas a las de [[Cuerpo|cuerpo]]): propiedad asociativa, conmutativa, hay elemento neutro denotado por cero y todo elemento u tiene opuesto llamado $-u$:
2. Propiedades del producto:
	- Propiedad asociativa: $\alpha \cdot (\beta · u) = (\alpha \cdot \beta) · u$
	- Hay elemento neutro (denotado por $1$): $1 \cdot u = u$
3. Propiedad distributiva (que combina ambas operaciones):
	- Respecto a la suma de vectores: $\alpha \cdot (u + v) = \alpha \cdot u + \alpha \cdot v$
	- Respecto a la suma de escalares: $(\alpha + \beta) · u = \alpha \cdot u + \beta \cdot u$

A los elementos de un espacio vectorial se les llama ==vectores==.

>[!abstract] Lema
>El cuerpo $\mathbb{F}$ es un $\mathbb{F}$-espacio vectorial.

>[!info] Ejemplo
>El conjunto de matrices $\mathcal{M}_n = \{M : M\text{ es una matriz }n \times n\}$, con las operaciones clásicas de suma de matrices y producto por escalar es un espacio vectorial.