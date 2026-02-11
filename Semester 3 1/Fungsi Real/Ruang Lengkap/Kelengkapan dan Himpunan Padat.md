#Teorema 

Misalkan $X$ himpunan padat di $Y$. Jika setiap barisan cauchy di $X$ konvergen di $Y$ maka $Y$ lengkap.

---

## Bukti

Ambil barisan cauchy $\{y_n\} \subseteq Y$. Karena $\overline{X} = Y$ maka untuk setiap $y_n$ dapat dipilih $x_n\in X$ sehingga $d(x_n, y_n) < \frac1n$

Ambil $\varepsilon > 0$. Karena $\{y_n\}$ barisan cauchy dan $\frac1n \to 0$ maka
$$
\begin{align*}
\exists N_1\in \mathbb{N},\ \forall m, n > N_1:& \ d(y_m, y_n) < \frac\varepsilon3 \\
\exists N_2\in \mathbb{N},\ \forall n > N_2:& \ \frac1n < \frac\varepsilon3
\end{align*}
$$
Pilih $N = \max(N_1, N_2)$. Perhatikan bahwa untuk setiap $m, n > N$ berlaku
$$d(x_m, x_n) \le d(x_m, y_m) + d(y_m, y_n) + d(y_n, x_n) < \frac{1}{m} + \frac{\varepsilon}{3} + \frac{1}{n} < \frac\varepsilon3 + \frac\varepsilon3 + \frac\varepsilon3 = \varepsilon$$
Maka, $x_n$ barisan cauchy di $X$. Berdasarkan premis maka terdapat $y \in Y$ sehingga $x_n \to y$.

Akan ditunjukkan $y_n \to y$. Ambil $\varepsilon > 0$. Karena $x_n \to y$ dan $\frac1n \to 0$ maka
$$
\begin{align*}
\exists M_1\in \mathbb{N},\ \forall n > M_1:& \ d(x_n, y) < \frac\varepsilon2 \\
\exists M_2\in \mathbb{N},\ \forall n > M_2:& \ \frac1n < \frac\varepsilon2
\end{align*}
$$
Pilih $M = \max(M_1, M_2)$. Perhatikan bahwa untuk setiap $n > M$
$$d(y_n, y) \le d(y_n, x_n) + d(x_n, y) < \frac1n + \frac\varepsilon2 < \frac\varepsilon2 + \frac\varepsilon2 = \varepsilon$$
Maka $y_n \to y$. Artinya setiap barisan cauchy di $Y$ konvergen. Terbukti bahwa $Y$ lengkap.


***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Himpunan Padat]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
