
-17\
数列$\left\{ c_n \right\}_{n=0}^{\infty}$を

$$
c_n:=a_n-\alpha
$$

によって定めると

$$
\lim_{n \to \infty}  c_n= 0
$$

である． 
$$
\begin{aligned}
b_n 
&=\, \dfrac{\left(\alpha +c_1\right) +2^l\left(\alpha +c_2\right) +\dots+n^l\left(\alpha +c_n\right) }{n^{l+1}}\\
&=\, \alpha \dfrac{1+2^l+\dots+n^l}{n^{l+1}}+\dfrac{c_1+2^lc_2+\dots+n^lc_n}{n^{l+1}}\\
&=\, d_n+e_n%
\end{aligned}
$$
 とおく． 
 $$
\begin{aligned}
d_n 
&=\, \alpha \dfrac{1}{n}\sum_{k=1}^{n} \left(\dfrac{k}{n}\right) ^l \to \alpha \int_{0}^{1} x^l \, dx=\dfrac{\alpha }{l+1} 　\left(n\to \infty\right) \end{aligned}
$$


$$
\begin{aligned}
\left|e_n\right| &=\left|\dfrac{1^lc_1+2^lc_2+\dots+n^lc_n}{n^{l+1}}\right|\\ 
&\leq \dfrac{1^l\left|c_1\right|+2^l\left|c_2\right|+\dots+n^l\left|c_n\right|}{n^{l+1}}\\
&\leq\, \dfrac{n^l\left|c_1\right|+n^l\left|c_2\right|+\dots+n^l\left|c_n\right|}{n^{l+1}}
\\
&=\, 
\dfrac{\left|c_1\right|+\left|c_2\right|+\dots+\left|c_n\right|}{n}\to 0　　　\left(n\to \infty\right) \end{aligned}
$$

より 
$$
\begin{aligned}
\lim_{n \to \infty}e_n=0 \end{aligned}
$$

（最後の矢印ではチェザロ平均の性質を用いた．）したがって

$$
\begin{aligned}
\lim_{n \to \infty}b_n=\lim_{n \to \infty}\left(d_n+e_n\right) = \dfrac{\alpha }{l+1} \end{aligned}
$$

となって数列$\left\{ b_n \right\}_{n=0}^{\infty}$は収束することが示された．$\square$
