---
title: Producto escalar
---
Sea $V$ un [[Espacio vectorial|espacio vectorial]] real o complejo. Un ==producto escalar== es una aplicación $⟨\cdot, \cdot⟩: V \times V \rightarrow \mathbb{F}$ que satisface las siguientes condiciones:
- $⟨\alpha u + \beta v, w⟩ = \alpha⟨u, w⟩ + \beta⟨v, w⟩$, es [[Aplicación lineal|lineal]] en la primera componente,
- $⟨u, w⟩ = ⟨w, u⟩$, al intercambiar el orden se conjuga,
- $⟨v, v⟩ > 0$ si $v \neq 0$, es [[Clasificación de formas cuadráticas|definida positiva]],
donde $u, v, w \in V$ , $\alpha \in \mathbb{F}$ y $\bar{\alpha}$ denota el ==conjugado complejo== de $\alpha$.

>[!warning] Observación
>Aunque no se diga en la definición explícitamente, como consecuencia directa de combinar la dos primeras propiedades, tenemos que
>- $⟨u, v + w⟩ = ⟨u, v⟩ + ⟨u, w⟩$
>- $⟨u, \alpha v⟩ = \alpha⟨u, v⟩$.

El producto escalar en $\mathbb{R}$ es una aplicación bilineal. Sin embargo, en $\mathbb{C}$ no lo es. En este caso se denomina ==sesquilineal== respecto a la conjugación.

>[!warning] Observación
>Aunque estemos en $\mathbb{C}$ y $⟨u, v⟩ \in \mathbb{F}$, siempre se tendrá que $⟨u, u⟩ \in \mathbb{R}$.

> [!info] Ejemplo. Producto escalar usual en $\mathbb{C}^n$
> Tomando $V=\mathbb{C}^n$ y $\mathbb{F}=\mathbb{C}$ encontramos el ==producto escalar usual== de $\mathbb{C}^n$
> $$
> (x_1,\dots,x_n)\bullet (y_1,\dots,y_n)=x_1\overline{y_1}+\cdots+x_n\overline{y_n}.
> $$

