#Teorema 

Misalkan $X$ adalah ruang metrik lengkap dan suatu fungsi $f: X \to X$. Jika $f$ fungsi kontraksi maka terdapat tepat satu titik tetap dari $f$.

---

## Bukti

Misalkan $f$ suatu fungsi kontraksi di $X$. Artinya terdapat $\alpha \in [0, 1)$ sehingga
$$d(f(x), f(y)) \le \alpha\cdot d(x, y)$$
Ambil $x_0 \in X$. Akan ditunjukkan barisan $f^n(x_0)$ adalah barisan cauchy di $X$.

Misalkan $d_0 = d(f(x_0), x_0)$.
Ambil $\varepsilon > 0$. Perhatikan untuk sembarang bilangan asli $n$
$$
\begin{align*}
d\left(f^n(x_0), f^{n+1}(x_0)\right) &\le \alpha \cdot d\left(f^{n-1}(x_0), f^{n}(x_0)\right) \le \alpha^2 \cdot d\left(f^{n-2}(x_0), f^{n-1}(x_0)\right) \\
&\le \cdots\\
& \le \alpha^{n} \cdot d\left(x_0, f(x_0)\right) = \alpha^n\cdot d_0
\end{align*}
$$
Karena $\alpha \in [0, 1)$ maka
$$
\begin{align*}
\sum_{k = 0}^\infty d\left(f^{k}(x_0), f^{k+1}(x_0)\right) &\le \sum_{k = 0}^\infty \alpha^k\cdot d_0 = \frac{d_0}{1 - \alpha}
\end{align*}
$$
Artinya deret tersebut konvergen. Berarti barisan jumlah parsialnya konvergen sehingga cauchy. Berarti, terdapat bilangan asli $N \in \mathbb{N}$ sehingga
$$\left|\sum_{k = 0}^n d\left(f^{k}(x_0), f^{k+1}(x_0)\right) - \sum_{k = 0}^{m} d\left(f^{k}(x_0), f^{k+1}(x_0)\right)\right| = \left|\sum_{k = m+1}^n d\left(f^{k}(x_0), f^{k+1}(x_0)\right)\right| < \varepsilon$$
untuk setiap $n \ge m > N$. Perhatikan bahwa untuk setiap $n > m > N+1$ berlaku (dengan ketaksamaan segitiga)
$$
\begin{align*}
d\left(f^{m}(x_0), f^{n}(x_0)\right) &\le \sum_{k = m}^{n-1} d\left(f^{k}(x_0), f^{k+1}(x_0)\right) \\
&\le \sum_{k = m+1}^n d\left(f^{k}(x_0), f^{k+1}(x_0)\right) < \varepsilon
\end{align*}
$$
Berarti barisan $f^n(x_0)$ barisan cauchy di $X$. Karena $X$ metrik lengkap maka terdapat $x^* \in X$ sehingga $f^n(x_0) \to x^*$. Perhatikan bahwa
$$f(x^*) = f\left(\lim_{n\to\infty} f^{n}(x_0)\right) = \lim_{n\to\infty} f^{n+1}(x_0) = \lim_{n\to\infty} f^n(x_0) = x^*$$
Artinya $x^*$ adalah titik tetap dari $f$. Lebih lanjut, misalkan $x'$ titik tetap dari $f$ maka
$$d\left(x^*, x'\right) =d\left(f(x^*), f(x')\right) \le \alpha \cdot d\left(x^*, x'\right)$$
Karena $\alpha \in [0, 1)$ maka haruslah $d(x^*, x') = 0$. Artinya $x^* = x'$. Terbukti ketunggalan dan eksistensi dari titik tetap $f$.

***

## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
 * [[Buat Backup/Semester 3/Fungsi Real/Fungsi/Fungsi Kontraksi]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Titik Tetap]]