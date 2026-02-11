#Teorema 

Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$. Berlaku
$$
\text{Ker}\left({T - \lambda I_V}\right) = \text{Eig}_{\lambda}(T)
$$

---
## Bukti
Perhatikan bahwa
$$
\begin{align*}
v \in \text{Ker}\left({T - \lambda I_V}\right) & \iff& (T - \lambda I_V)(v) &= \mathbf{0} \\
& \iff& T(v) - \lambda I_V(v) &= \mathbf{0}\\
& \iff& T(v) - \lambda v &= 
\mathbf{0_V} \\
&\iff&T(v) &= \lambda v \\
&\iff& v &\in \text{Eig}_{\lambda}(T)
\end{align*}
$$
Terbukti
$$
\text{Ker}\left({T - \lambda I_V}\right) = \text{Eig}_{\lambda}(T)
$$
***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Ruang Eigen]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range dan Kernel Pemetaan Linear]]