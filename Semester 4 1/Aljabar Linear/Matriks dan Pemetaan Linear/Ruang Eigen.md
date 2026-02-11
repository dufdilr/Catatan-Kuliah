#Definisi #Teorema 
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$ . Definisikan **Ruang Eigen-$\lambda$** sebagai
$$
\text{Eig}_{\lambda}(T) := \{ v \in V \ | \ T(v) = \lambda v \}
$$
Untuk matriks $\mathbf{A} \in M_n(\mathbb{F})$, Ruang Eigen-$\lambda$ dari $\mathbf{A}$ didefinisikan sebagai Ruang Eigen-$\lambda$ dari [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear|Pemetaan Linear yang direpresentasikan]].

Lebih lanjut, ruang eigen membentuk **Subruang Vektor** dari $V$.

---
## Bukti
[[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor#^fb9b94|Jelas]] $T(\mathbf{0_V}) = \mathbf{0_V}= \lambda \mathbf{0_V}$. Artinya $\mathbf{0_V} \in \text{Eig}_{\lambda}(T)$. Maka $\text{Eig}_{\lambda}(T) \neq \emptyset$^de6d31

Lebih lanjut, ambil $u, v \in \text{Eig}_{\lambda}(T)$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa 
$$
\begin{align*}
T(u+v)&= T(u) + T(v) = \lambda u + \lambda v = \lambda(u+v) \\
T(\alpha u) &= \alpha T(u) = \alpha \lambda u = \lambda(\alpha u)
\end{align*}
$$
Artinya $u+v, \alpha u\in \text{Eig}_{\lambda}(T)$. Berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Subruang]] maka $\text{Eig}_{\lambda}(T)$ membentuk subruang dari $V$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]