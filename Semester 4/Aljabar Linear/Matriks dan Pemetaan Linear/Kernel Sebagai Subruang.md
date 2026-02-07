#Teorema 
Misalkan $V, W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Himpunan $\text{Ker}\left({T}\right)$ membentuk **Subruang Vektor** dari $V$.

---
## Bukti

Berdasarkan [[Pemetaan Linear Vektor Nol]] maka $T(\mathbf{0_V}) = \mathbf{0_W}$. Artinya $\mathbf{0_V} \in \text{Ker}\left({T}\right)$. Berarti $\text{Ker}\left({T}\right) \neq 0$. Lebih lanjut, ambil $x, y \in \text{Ker}\left({(T)}\right)$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa berdasarkan [[Sifat Ruang Vektor]] berlaku
$$
\begin{align*}
T(x+y) &= T(x) + T(y) = \mathbf{0_W} + \mathbf{0_W} = \mathbf{0_W} \\
T(\alpha x) &= \alpha T(x) = \alpha \mathbf{0_W} = \mathbf{0_W}
\end{align*}
$$
Artinya $x+y, \alpha x \in \text{Ker}\left({T}\right)$. Berdasarkan [[Karakterisasi Subruang]] maka $\text{Ker}\left({T}\right)$ adalah subruang dari $V$.

***
## Definition Used 
 * [[Pemetaan Linear]]
 * [[Range dan Kernel Pemetaan Linear]]
 * [[Subruang Vektor]]
