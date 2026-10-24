---
title: Subespacio trasladado
---
Similar a la suma de [[Espacio vectorial|espacios vectoriales]], definimos la ==suma de dos conjuntos== como
$$
A + B := \{a + b : a \in A, b \in B\}.
$$
En general, la suma de [[Conjunto de elementos|conjuntos]] es otro conjunto, pero sin estructura adicional.

Dado $S \leq V$ y un vector $v \in V$, podemos definir un nuevo [[Subespacio vectorial|subespacio]] como el ==subespacio trasladado== de $S$ por $v$
$$
v + S = \{v + s : s \in S\}.
$$

>[!warning] Observación
>El trasladado $v + S$ no es un espacio vectorial en general, es un simple conjunto.

>[!quote] Teorema: Igualdad de trasladados
>Dados $S \leq V$ y $v, w \in V$ , se tiene que $v + S = w + S$ si y solo si $w \in v + S$, es decir, si y solo si $v - w \in S$.