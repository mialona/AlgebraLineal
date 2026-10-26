---
title: Primer teorema de isomorfía
---
>[!quote] Teorema: Primer teorema de isomorfía
>Dada una [[Aplicación lineal|aplicación lineal]] $f : V \rightarrow W$ se tiene el siguiente [[Aplicación lineal|isomorfismo]]
>$$
>\begin{align*}
>\hat{f}: V/\text{ker }f &\rightarrow \text{Im }f\\
>v + \text{ker }f &\rightarrow \hat{f}(v + \text{ker }f) = f(v)
>\end{align*}
>$$

>[!success] Corolario
>Como conclusión directa podemos ver $\text{dim }V = \text{dim ker }f + \text{dim Im }f$.

>[!tip] Técnica: Calcular una base de la imagen
>Como los isomorfismos mandan [[Base o sistema generador minimal|bases]] a bases, una forma de calcular una base de $\text{Im }f$ es calculando una base $\{v_1, \dots , v_n\}$ de un [[Subespacios complementarios|complementario]] de $\text{ker }f$, que produce una base en $V/\text{ker }f$. En ese caso, la base de la [[Imagen, preimagen y núcleo|imagen]] será $\{f(v_1), \dots, f(v_n)\}$,