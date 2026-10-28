---
title: Aplicación adjunta
---
>[!example] Proposición
>Sea $(V,\langle\cdot,\cdot\rangle)$ un [[Isometría y espacio euclídeo y unitario|espacio vectorial euclídeo o unitario]]. Dada una [[Aplicación lineal|aplicación lineal]] siempre existe otra aplicación lineal (única) $f^*\colon V\to V$ tal que
>$$
>\langle f(v),w\rangle=\langle v,f^*(w)\rangle.
>$$
>Si la [[Aplicación y matriz coordenada|matriz coordenada]] de $f$ respecto de una [[Base o sistema generador minimal|base]] $T$ [[Ortogonalidad en productos escalares|ortonormada]] es $A$ entonces la de $f^*$ es $A^*=\overline{A^t}$.
>

La aplicación lineal $f^*$ tal que $\langle f(v),w\rangle=\langle v,f^*(w)\rangle$ se dice ==adjunta== de $f$. Si $f=f^*$ entonces $f$ se dice ==autoadjunta== o ==hermitiana== ,y si $f^*=-f$ se dice ==antiautoadjunta==.

>[!warning] Observación
>Notar que el operador "adjunta" se comporta de forma muy práctica
>- $\text{rang}\, f=\text{rang}\, f^*$, preserva el [[Rango y traza de una matriz|rango]],
>- $(f^*)^*=f$, es autoinverso,
>- $(f+g)^*=f^*+g^*$, respeta la suma,
>- $(\alpha f)^*=\overline{\alpha}f^*$, conjuga el producto por escalar,
>- $(f\circ g)^*=g^*\circ f^*$ e invierte el orden de la composición.
>Además $\ker f^*=(\text{Im}\, f)^\perp$.

