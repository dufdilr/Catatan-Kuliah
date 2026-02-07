#Definisi #Teorema 
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$ . Definisikan **Ruang Eigen-$\lambda$** sebagai
$$
\text{Eig}_{\lambda}(T) := \{ v \in V \ | \ T(v) = \lambda v \}
$$
Untuk matriks $\mathbf{A} \in M_n(\mathbb{F})$, Ruang Eigen-$\lambda$ dari $\mathbf{A}$ didefinisikan sebagai Ruang Eigen-$\lambda$ dari [[Matriks Sebagai Pemetaan Linear|Pemetaan Linear yang direpresentasikan]].

Lebih lanjut, ruang eigen membentuk **Subruang Vektor** dari $V$.

---
## Bukti
[[Sifat Ruang Vektor#^fb9b94|Jelas]] $T(\mathbf{0_V}) = \mathbf{0_V}= \lambda \mathbf{0_V}$. Artinya $\mathbf{0_V} \in \text{Eig}_{\lambda}(T)$. Maka $\text{Eig}_{\lambda}(T) \neq \emptyset$^de6d31

Lebih lanjut, ambil $u, v \in \text{Eig}_{\lambda}(T)$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa 
$$
\begin{align*}
T(u+v)&= T(u) + T(v) = \lambda u + \lambda v = \lambda(u+v) \\
T(\alpha u) &= \alpha T(u) = \alpha \lambda u = \lambda(\alpha u)
\end{align*}
$$
Artinya $u+v, \alpha u\in \text{Eig}_{\lambda}(T)$. Berdasarkan [[Karakterisasi Subruang]] maka $\text{Eig}_{\lambda}(T)$ membentuk subruang dari $V$.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Pemetaan Linear]]
 * [[Matriks]]
 * [[Subruang Vektor]]