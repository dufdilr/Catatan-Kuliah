#Teorema 
Misalkan $\mathbb{F}$ adalah lapangan dan $f(x) \in \mathbb{F}[x]$. Maka berlaku
$$
f(x) \text{ unit dari } \mathbb{F}[x] \iff \deg(f) = 0
$$
---
## Bukti
### $\Rightarrow$
Misalkan $f(x)$ adalah unit dari $\mathbb{F}[x]$. Artinya, terdapat $g(x) \in \mathbb{F}[x]$ sehingga
$$
f(x)g(x)=1(x)
$$
Perhatikan bahwa $1(x)$ adalah polinomial konstan, maka $\deg1(x) = 0$. Karena $\mathbb{F}[x]$ lapangan [[Lapangan Sebagai Daerah Integral|maka]] $\mathbb{F}[x]$ daerah integral. Akibatnya
$$
\deg(fg) = \deg(f) +\deg(g) = 0
$$
Karena $f$ unit maka $f, g$ tak-nol. Akibatnya $\deg f, \deg g \ge 0$. Dapat disimpulkan $\deg f = 0$. Terbukti.
### $\Leftarrow$
Jika $\deg(f) = 0$ maka $f(x) = u$ untuk suatu $u \in \mathbb{F}$. Karena $\mathbb{F}$ lapangan, maka terdapat $u^{-1}\in \mathbb{F}$ sehingga $uu ^{-1} = u^{-1}u = 1$. Tinjau $g(x) = u^{-1} \in \mathbb{F}[x]$. Perhatikan bahwa
$$
\begin{align*}
f(x) g(x) &= u u^{-1} = 1 = 1(x) \\
g(x)f(x)&= u^{-1}u = 1(x)
\end{align*}
$$
Terbukti $f(x)$ adalah unit di $\mathbb{F}[x]$.

***
## Definition Used 
 * [[Lapangan]]
 * [[Gelanggang Polinomial]]
 * [[Unsur Unit (Ring)]]
 * [[Polinomial]]