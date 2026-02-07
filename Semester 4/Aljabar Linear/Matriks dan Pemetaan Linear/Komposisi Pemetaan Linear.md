#Teorema 

Misalkan $U, V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $S \in \mathcal{L}(U, V) ;\ T \in \mathcal{L}(V, W)$. Fungsi 
$$
ST = S \circ T : U \to V
$$
adalah pemetaan linear.

---
## Bukti
Ambil $u_{1},u_{2} \in U$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa
$$
\begin{align*}
ST(u_{1} + u_{2}) &= S \left( T(u_{1}u_{2}) \right)  = S \left( T(u_{1}) + T(u_{2}) \right) \\
&= ST(u_{1}) + ST(u_{2}) \\
\\
ST(\alpha u_{1}) &= S\left( \alpha T(u_{1}) \right)  = \alpha ST(u_{1})
\end{align*}
$$
Terbukti $ST$ juga pemetaan linear.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Pemetaan Linear]]
 * [[Komposisi Fungsi]]