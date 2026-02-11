#Teorema 
Misalkan $V, W$ ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$ pemetaan **injektif**. Jika $\{ v_{1}, v_{2}, \dots , v_n \}$ adalah Himpunan yang Bebas Linear maka
$$
\{ T(v_{1}), T(v_{2}), \dots, T(v_n) \}
$$
juga membentuk himpunan bebas linear.

---
## Bukti
Andaikan $\{ T(v_{1}), T(v_{2}), \dots, T(v_n) \}$ bergantung linear. Maka terdapat $\alpha_1, \alpha_{2}, \dots, \alpha_n$ memenuhi
$$
\begin{align*}
\alpha_{1} T(v_{1}) + \alpha_{2}T(v_{2}) + \dots + \alpha_n T(v_n) &= \mathbf{0_W} \\
T(\alpha_{1}v_{1}+\alpha_{2}v_{2}+\dots+\alpha_n v_n) = \mathbf{0_W}
\end{align*}
$$
Karena $T$ adalah pemetaan injektif [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Karakterisasi Pemetaan Injektif|maka]] $\alpha_{1}v_{1} + \alpha_{2}v_{2} + \dots + \alpha_n v_n = \mathbf{0_V}$. Artinya $\{ v_{1}, v_{2}, \dots , v_n \}$ bergantung linear, kontradiksi dengan hipotesis awal. Maka pengandaian salah.

Terbukti bahwa $\{ T(v_{1}), T(v_{2}), \dots, T(v_n) \}$ bebas linear.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Basis dan Koordinat/Bebas Linear]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Injektif]]