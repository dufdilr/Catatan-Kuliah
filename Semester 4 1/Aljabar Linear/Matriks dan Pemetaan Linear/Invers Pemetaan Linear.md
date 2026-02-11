#Teorema 

Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Jika $T$ memiliki invers maka $T^{-1}:W \to V$ juga pemetaan Linear.

Lebih lanjut, jika $T$ memiliki invers maka $T$ disebut **invertibel**. Himpunan semua pemetaan $\mathcal{L}(V)$ yang **invertibel** dinotasikan sebagai $GL(V)$.

---

## Bukti
Ambil $w_1, w_2 \in W$ dan $\alpha \in \mathbb{F}$. Misalkan $T^{-1}(w_1) = v_1$ dan $T^{-1}(w_2) = v_2$. Perhatikan bahwa
$$
\begin{align*}
T(v_1 + v_2) &= T(v_1) + T(v_2) = w_1 + w_2 \\
T^{-1}(w_{1}+w_{2}) &= v_{1} + v_{2} \\
&= T^{-1}(w_{1}) + T^{-1}(w_2) \\
\\
T(\alpha v_{1}) &= \alpha T(v_{1}) = \alpha w_{1}  \\
T^{-1}(\alpha w_1) &= \alpha v_{1} \\
&= \alpha T^{-1}(w_{1})
\end{align*}
$$
Terbukti $T^{-1}$ juga pemetaan Linear.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Bijektif]]
 

