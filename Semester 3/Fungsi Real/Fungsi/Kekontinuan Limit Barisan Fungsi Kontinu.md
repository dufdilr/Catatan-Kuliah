#Teorema 

Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik. Misalkan pula $\{f_n\}$ barisan fungsi kontinu  $f_n: X \to Y$ dan $f_n\xrightarrow{u}f$. Fungsi $f: X \to Y$ adalah kontinu.

---

## Bukti

Misalkan $\{f_n\}$ barisan fungsi kontinu dan $f_n\xrightarrow{u}f$. Ambil $\varepsilon > 0$. Terdapat $N \in \mathbb{N}$ sehingga untuk setiap $n > N$ berlaku
$$
\begin{align*}
\forall n > N, \ \forall x \in X:& \ \ d_Y(f_n(x), f(x)) < \frac\varepsilon3
\end{align*}
$$
Ambil $c \in X$. Pilih $N_1 = N+1 > N$. Karena $\{f_n\}$ barisan fungsi kontinu maka
$$\exists \delta>0:\ \ d_X(x, c) < \delta \ \Rightarrow \ d_Y(f_{N_1}(x), f_{N_1}(c)) < \frac\varepsilon3 $$
Perhatikan bahwa jika $d_X(x, c) < \delta$ maka
$$
\begin{align*}
d_Y(f(x), f(c)) &\le d_Y(f(x), f_{N_1}(x)) + d_Y(f(c), f_{N_1}(x)) \\
&\le d_Y(f(x), f_{N_1}(x)) + d_Y(f(c), f_{N_1}(c)) + d_Y(f_{N_1}(x), f_{N_1}(c)) \\
&< \frac\varepsilon3 + \frac\varepsilon3 + \frac\varepsilon3 = \varepsilon
\end{align*}
$$
Terbukti $f$ kontinu.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Fungsi/Barisan Fungsi Konvergen Seragam]]
 * [[Buat Backup/Semester 3/Fungsi Real/Fungsi/Fungsi Kontinu]]