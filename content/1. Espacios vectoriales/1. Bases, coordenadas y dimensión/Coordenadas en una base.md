Llamamos ==coordenadas== de $v$ en la [[Base o sistema generador minimal|base]] $\mathcal{B} = \{v_1, . . . , v_n\}$, y lo denotamos como $[v]_{\mathcal{B}}$, a la $n$-tupla de escalares $(\alpha_1, . . . , \alpha_n)$ tal que
$$
\alpha_11 \cdot v_1 + \cdots + \alpha_n \cdot v_n = v.
$$

>[!abstract] Lema
>Sea $V$ un $\mathbb{F}$-[[Espacio vectorial|espacio vectorial]] $n$-dimensional con base $\mathcal{B}$, la [[Aplicación y matriz coordenada|aplicación coordenada]]
> $c_\mathcal{B} : V \rightarrow F^n$ tal que $c_\mathcal{B}(v) = [v]_\mathcal{B}$ es una [[Aplicación lineal|aplicación lineal biyectiva]].

> [!info] Ejemplo
> Sea $V=\mathbb{R}^{3}$ y $\mathcal{B}_c=\{(1,0,0),(0,1,0),(0,0,1)\}$ su base canónica. Podemos escribir el vector $(1,2,3)$ como
> $$
> (1,2,3)=1\cdot(1,0,0)+2(0,1,0)+3(0,0,1).
> $$
> Por tanto $[(1,2,3)]_{\mathcal{B}_c}=(1,2,3)$. En general 
> $$
> (x,y,z)=x(1,0,0)+y(0,1,0)+z(0,0,1).
> $$
> Por tanto la aplicación coordenada $c_{\mathcal{B}_c}\colon \mathbb{R}^{3}\to\mathbb{R}^{3}$ está dada por
> $$
> c_{\mathcal{B}_c}((x,y,z))=(x,y,z).
> $$

> [!info] Ejemplo
> Sea $V=\mathbb{R}_3[x]$ el espacio de polinomios de grado menor o igual a $3$ y consideremos la base $\mathcal{B}=\{1,1+x,1+x+x^2,1+x+x^2+x^3\}$. Podemos escribir el polinomio $x-3x^2+3x^3$ como
> $$
> x-3x^2+3x^3=-1(1)+4(1+x)-6(1+x+x^2)+3(1+x+x^2+x^3).
> $$
> Por tanto $[(x-3x^2+3x^3)]_{\mathcal{B}}=(-1,4,-6,3)$. En general
> $$
> a+bx+cx^2+dx^3=(a-b)(1)+(b-c)(1+x)+(c-d)(1+x+x^2)+d(1+x+x^2+x^3).
> $$
> Por tanto la aplicación coordenada $c_\mathcal{B}\colon\mathbb{R}_{3}[x]\to\mathbb{R}^{4}$ está dada por
> $$
> c_{\mathcal{B}_c}(a+bx+cx^2+dx^3)=(b-a,c-b,d-c,d).
> $$

> [!info] Ejemplo
> Sea $V=\mathbb{C}^3$  y consideremos la base $\mathcal{B}=\left\{(i,0,0),\left(0,\frac{1}{\sqrt{2}},\frac{1}{\sqrt{2}}\right),\left(0,\frac{1}{\sqrt{2}},-\frac{1}{\sqrt{2}}\right)\right\}$. Podemos escribir el vector $(1+i,2,3i)$ como
> $$
> (1+i,2,3i)=(1-i)(i,0,0)+\dfrac{2+3i}{\sqrt{2}}\left(0,\frac{1}{\sqrt{2}},\frac{1}{\sqrt{2}}\right)+\dfrac{1-3i}{\sqrt{2}}\left(0,\frac{1}{\sqrt{2}},-\frac{1}{\sqrt{2}}\right).
> $$
> Por tanto $[(1+i,2,3i)]_{\mathcal{B}}=\left(1-i,\frac{2+3i}{\sqrt{2}},\frac{2-3i}{\sqrt{2}}\right)$. En general
> $$
> (x,y,z)=-xi(i,0,0)+\dfrac{y+z}{\sqrt{2}}\left(0,\frac{1}{\sqrt{2}},\frac{1}{\sqrt{2}}\right)+\dfrac{y-z}{\sqrt{2}}\left(0,\frac{1}{\sqrt{2}},-\frac{1}{\sqrt{2}}\right).
> $$
> Por tanto la aplicación coordenada $c_\mathcal{B}\colon\mathbb{C}^{3}\to\mathbb{C}^{3}$ está dada por
> $$
> c_{\mathcal{B}_c}((x,y,z))=\left(-xi,\dfrac{y+z}{\sqrt{2}},\dfrac{y-z}{\sqrt{2}}\right).
> $$