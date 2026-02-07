#Teorema 
Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V)$. Misalkan pula $\lambda$ adalah nilai eigen dari $T$. Maka, $\lambda^k$ adalah nilai eigen dari $T^k$ dan
$$
\text{Eig}_{\lambda}(T) \subseteq \text{Eig}_{{\lambda^k}}(T^k)
$$
---
## Bukti
Ambil $v \in \text{Eig}_{\lambda}(T)$ dengan $v \neq \mathbf{0_V}$. Lebih lanjut
$$
\begin{align*}
T^k(v) &= T^{k-1}(T(v)) = T^{k-1}(\lambda v) = \lambda T^{k-1}(v) \\
&=\lambda T^{k-2}(T(v)) = \lambda T^{k-2}(\lambda v) = \lambda^2 T^{k-2}(v) \\
&= \cdots \\
&= \lambda^{k-1}T(v) = \lambda^k v
\end{align*}
$$
Berarti $v \in \text{Eig}_{\lambda^k}(T^k)$. Lebih lanjut, karena terdapat $v \neq 0$ sehingga $T^k(v) = \lambda^k v$ maka $\lambda^k$ adalah nilai eigen dari $T^k$.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Pemetaan Linear]]
 * [[Vektor dan Nilai Eigen]]
 * [[Ruang Eigen]]