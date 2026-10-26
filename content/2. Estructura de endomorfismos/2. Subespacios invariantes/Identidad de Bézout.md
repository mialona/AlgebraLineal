---
title: Identidad de Bézout
---
La ==Identidad de Bézout== dice que dados [[Polinomio|polinomios]] $p_1(x)$, $p_2(x)$ existen $q_1(x)$, $q_2(x)$ tales que 
$$
p_1(x)q_1(x)+p_2(x)q_2(x)=\text{mcd}(p_1(x),p_2(x)).
$$
>[!tip] Técnica: Algoritmo euclídeo
>Una forma de calcular los polinomios que aparecen en la Identidad de Bezout es emplear el algoritmos euclídeo el cual consiste en hacer divisiones de polinomios hasta que el resto sea cero
>$$
>\begin{split}
>p_1(x)=c_2(x)p_2(x)+r_2(x) &\Rightarrow r_2(x)=p_1(x)-c_2(x)p_2(x),\\
>p_2(x)=c_3(x)r_2(x)+r_3(x) &\Rightarrow r_3(x)=p_2(x)-c_3(x)r_2(x),\\
>r_2(x)=c_4(x)r_3(x)+r_4(x) &\Rightarrow r_4(x)=r_2(x)-c_4(x)r_3(x),\\
>&\vdots\\
>r_{k-1}(x)=c_{k+1}(x)r_k(x)+r_{k+1}(x) &\Rightarrow r_{k+1}(x)=r_{k-1}(x)-c_{k+1}(x)r_k(x),\\
>r_k(x)=c_{k+2}(x)r_{k+1}(x)+0
>\end{split}
>$$
>Una vez acabada la serie de divisiones debemos aplicar sustitución regresiva en la última expresión
>$$
>\text{mcd}(p_1(x),p_2(x))=r_{k+1}(x)=r_{k-1}(x)-c_{k+1}(x)r_k(x).
>$$
>En esta expresión sustituimos $r_k(x)$ y operamos. En la nueva sustituimos $r_{k-1}(x)$ y así sucesivamente hasta $r_{k+1}(x)=p_1(x)q_1(x)+p_2(x)q_2(x)$.

>[!warning] Observación
>Podemos aplicar la Identidad de Bézout de forma encadenada. Así, por ejemplo, si tenemos $\text{mcd}(p_1(x),p_2(x),p_3(x))=1$ entonces la Identidad de Bézout nos dice que existen $q_1(x)$, $q_2(x)$ tales que
>$$
>\text{mcd}(p_1(x),p_2(x))=p_1(x)q_1(x)+p_2(x)q_2(x)
>$$
>y $\bar{q_1}(x)$, $q_3(x)$ tales que
>$$
>\begin{split}
>1&=\text{mcd}(p_1(x),p_2(x),p_3(x))=\text{mcd}(\text{mcd}(p_1(x),p_2(x)),p_3(x))\\
>&=\bar{q_1}(x)\text{mcd}(p_1(x),p_2(x))+p_3(x)q_3(x)\\
>&=p_1(x)q_1(x)\bar{q_1}(x)+p_2(x)q_2(x)\bar{q_1}(x)+p_3(x)q_3(x).
>\end{split}
>$$
>Es decir, se aplica a cualquier número de polinomios, no necesariamente dos.





