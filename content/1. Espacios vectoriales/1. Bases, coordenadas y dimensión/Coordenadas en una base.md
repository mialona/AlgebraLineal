Llamamos ==coordenadas== de $v$ en la [[Base o sistema generador minimal|base]] $\mathcal{B} = \{v_1, . . . , v_n\}$, y lo denotamos como $[v]_{\mathcal{B}}$, a la $n$-tupla de escalares $(\alpha_1, . . . , \alpha_n)$ tal que
$$\alpha_11 \cdot v_1 + \cdots + \alpha_n \cdot v_n = v.$$
>[!abstract] Lema
>Sea $V$ un $\mathbb{F}$-[[Espacio vectorial|espacio vectorial]] $n$-dimensional con base $\mathcal{B}$, la [[Aplicación y matriz coordenada|aplicación coordenada]] $c_\mathcal{B} : V \rightarrow F^n$ tal que $c_\mathcal{B}(v) = [v]_\mathcal{B}$ es [[Aplicación lineal|aplicación lineal biyectiva]].

> [!info] Ejemplo
> Sea $V=\mathbb{R}^{3}$ y $\mathcal{B}_c=\{(1,0,0),(0,1,0),(0,0,1)\}$ su base canónica. Podemos escribir el vector $(1,2,3)$ como
> $$(1,2,3)=1\cdot(1,0,0)+2(0,1,0)+3(0,0,1).$$
> Por tanto $[(1,2,3)]_{\mathcal{B}_c}=(1,2,3)$. En general 
> $$(x,y,z)=x(1,0,0)+y(0,1,0)+z(0,0,1).$$
> Por tanto la aplicación coordenada $c_{\mathcal{B}_c}\colon \mathbb{R}^{3}\to\mathbb{R}^{3}$ está dada por
> $$c_{\mathcal{B}_c}((x,y,z))=(x,y,z).$$

> [!info] Ejemplo
> Sea $V=\mathbb{R}_{3}$ el espacio de polinomios de grado menor o igual a $3$ y consideremos la base $\mathcal{B}=\{1,1+x,1+x+x^2,1+x+x^2+x^3\}$.