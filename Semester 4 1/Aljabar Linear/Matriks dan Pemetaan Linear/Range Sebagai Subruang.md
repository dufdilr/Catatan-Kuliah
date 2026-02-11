#Teorema 
Misalkan $V, W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Himpunan $\text{Im}\left({T}\right)$ membentuk **Subruang Vektor** dari $W$.

---
## Bukti

Berdasarkan [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear Vektor Nol]] maka $T(\mathbf{0_V}) = \mathbf{0_W}$. Artinya $\mathbf{0_W} \in \text{Im}\left({T}\right)$. Berarti $\text{Ker}\left({T}\right) \neq 0$. Lebih lanjut, ambil $x, y \in \text{Im}\left({(T)}\right)$ dan $\alpha \in \mathbb{F}$. Karena $x, y \in \text{Im}\left({(T)}\right)$, misalkan $T(u) = x$ dan $T(v) = y$ untuk suatu $u, v \in V$. Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor]] berlaku
$$
\begin{align*}
x+y &= T(u) + T(v) = T(u+v) \\
\alpha x &= \alpha T(u) = T(\alpha u)
\end{align*}
$$
Jelas $u+v, \alpha u \in V$. Artinya $x+y, \alpha x \in \text{Im}\left({T}\right)$. Berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Subruang]] maka $\text{Im}\left({T}\right)$ adalah subruang dari $W$.

***
## Definition Used 
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range dan Kernel Pemetaan Linear]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]
