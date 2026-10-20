---
title: Aplicación lineal
---
Dados dos $\mathbb{F}$-[[Espacio vectorial|espacios vectoriales]] $V$ (salida) y $W$ (llegada), $f : V \rightarrow W$ se dice ==aplicación lineal== u [[Homomorfismos|homomorfismo]] si respeta la suma interna de $V$ y el producto por escalar, es decir, si cumple que:
- $f(v_1 + v_2) = f(v_1) + f(v_2)$ para todo $v_1, v_2 \in V$
- $f(\alpha v) = \alpha f(v)$ para todo $v \in V$ y $\alpha \in F$

Además, se dice que:
- $f$ es ==inyectiva== si $f(v_1) = f(v_2)$ implica que $v_1 = v_2$
- $f$ es ==suprayectiva== o sobreyectiva si para todo $w \in W$ existe al menos un $-v \in V$ tal que $f(v) = w$
- f es ==biyectiva== si es inyectiva y suprayectiva a la vez

>[!example] Proposición
>Sea $f : V \rightarrow W$ una aplicación lineal se tiene que
>- $f$ es inyectiva si y solo si el núcleo $\text{ker }f = \{0\}$
>- $f$ es suprayectiva si y solo si la imagen $\text{Im }f = W$

>[!warning] Observación
>En la práctica si $V = Gen⟨v_1, \dots , v_n⟩$, $\text{Im }f = f(V) = Gen⟨f(v_1), \dots , f(v_n)⟩$