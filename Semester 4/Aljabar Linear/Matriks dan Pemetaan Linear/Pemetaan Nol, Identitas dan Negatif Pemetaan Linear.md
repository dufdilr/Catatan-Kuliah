#Definisi #Teorema 
Misalkan $U, V$ ruang vektor atas lapangan $\mathbb{F}$. Pandang himpunan $\mathcal{L}(U,V)$. Definisikan 
$$
\mathbf{0_UV} : U \to V \quad \text{ dengan } \quad \mathbf{0_UV}(u) = \mathbf{0_V}, \ \forall u \in U
$$
Lebih lanjut, untuk setiap $T \in \mathcal{L}(U, V)$, definisikan 
$$
-T : U \to V \quad \text{ dengan } \quad (-T)(u) = -T(u), \ \forall u \in U
$$
Kedua pemetaan tersebut adalah pemetaan linear dari $U$ ke $V$.

Definisikan pula $I_U : U \to U$ dengan $I_U(u) = u, \forall u \in U$. Pemetaan ini adalah pemetaan linear dari $U$ ke $U$


***

## Bukti
### Pemetaan Nol
Ambil $u_{1}, u_{2} \in U$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor]] berlaku
$$
\begin{align*}
\mathbf{0_UV} (u_{1}+u_{2}) &= \mathbf{0_V} = \mathbf{0_V} + \mathbf{0_V} \\
&= \mathbf{0_UV} (u_{1}) + \mathbf{0_UV} (u_{2})\\
\\
\mathbf{0_UV} (\alpha u_{1}) &= \mathbf{0_V} = \alpha \mathbf{0_V} = \alpha \mathbf{0_UV}(u_{1})
\end{align*}
$$
Terbukti $\mathbf{0_UV}$ juga pemetaan linear.
### Negatif Pemetaan Linear
Misalkan $T \in \mathcal{L}(U, V)$. Ambil $u_{1}, u_{2} \in U$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor]] berlaku
$$
\begin{align*}
(-T)(u_{1}+u_{2}) &= -(T(u_{1}+u_{2})) = -\left( T(u_{1}) + T(u_{2}) \right) \\
&= -T(u_{1}) - T(u_{2}) = (-T)(u_{1}) + (-T)(u_{2})\\
\\
(-T)(\alpha u_{1}) &= -(T(\alpha u_{1})) = -(\alpha T(u_{1})) \\
&= \alpha (-T(u_{1})) = \alpha (-T)(u_{1})
\end{align*}
$$
Terbukti $(-T)$ juga pemetaan linear.

### Pemetaan Identitas
Ambil $u_{1}, u_{2} \in U$ dan $\alpha \in \mathbb{F}$. Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor]] berlaku
$$
\begin{align*}
I_U(u_{1}+u_{2}) &= u_{1}+u_{2} = I_U(u_{1}) + I_U(u_{2}) \\
I_U(\alpha u_{1}) &= \alpha u_{1} = \alpha I_U(u_{1})
\end{align*}
$$
Terbukti $I_U$ adalah pemetaan linear.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]