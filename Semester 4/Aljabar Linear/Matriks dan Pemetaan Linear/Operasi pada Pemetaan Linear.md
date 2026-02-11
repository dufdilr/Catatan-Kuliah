#Definisi #Teorema 

Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$. Definisikan operasi penjumlahan $+$ dan perkalian skalar $\cdot$ pada $\mathcal{L}(V, W)$ dimana untuk setiap $S, T \in \mathcal{L}(V, W)$ dan $\alpha \in \mathbb{F}$ didefinisikan
$$
\begin{align*}
(S+T)(v) &:= S(v) + T(v) \\
(\alpha \cdot T)(v) & := \alpha  T(v)
\end{align*}
$$
untuk setiap $v \in V$. Kedua operasi tersebut **terdefinisi dengan baik** di $\mathcal{L}(V, W)$.

---
## Bukti
Ambil $S, T \in \mathcal{L}(V, W)$ dan $\alpha \in \mathbb{F}$. Akan ditunjukkan fungsi $S+T$ dan $\alpha \cdot T$ adalah pemetaan linear dari $V$ ke $W$. Ambil $u, v \in V$. Perhatikan bahwa
$$
\begin{align*}
(S+T)(u+v) &= S(u+v) + T(u+v) = S(u) + S(v) + T(u) + T(v) \\
&= S(u) + T(u) + S(v) + T(v) \\
&= (S+T)(u) + (S+T)(v)\\
\\
(\alpha T)(u+v) &= \alpha T(u+v) = \alpha \left( T(u) + T(v) \right) \\
&= \alpha T(u) + \alpha T(v) \\
&= (\alpha T)(u) + (\alpha T)(v)
\end{align*}
$$
Terbukti bahwa $S+T, \ \alpha T \in \mathcal{L}(V, W)$. Maka kedua operasi tersebut terdefinisi dengan baik.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Operasi]]