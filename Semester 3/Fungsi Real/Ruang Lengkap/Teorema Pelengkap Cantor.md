#Teorema 

Setiap ruang metrik memiliki pelengkap.

---

## Bukti

Misalkan suatu ruang metrik $X$ dan $\Omega$ adalah himpunan semua barisan cauchy di $X$

### Relasi Ekuivalensi di $\Omega$
    
Definisikan $\{x_n\} \sim \{y_n\}$ jika dan hanya jika
    $$\lim_{n\to\infty}d(x_n, y_n) = 0$$
    Akan ditunjukkan relasi $\sim$ adalah relasi ekuivalen di $\Omega$:
    1. Ambil $\{x_n\}\in \Omega$. Perhatikan bahwa $d(x_n, x_n) = 0$. Jelas $d(x_n, x_n) \to 0$. Terbukti bahwa $\{x_n\} \sim \{x_n\}$
    2.  Misalkan $\{x_n\} \sim \{y_n\}$. Artinya $d(x_n, y_n) \to 0$. Perhatikan bahwa $d(y_n, x_n) = d(x_n, y_n) \to 0$. Terbukti bahwa $\{y_n\} \sim \{x_n\}$.
    3.  Misalkan $\{x_n\} \sim \{y_n\}$ dan $\{y_n\} \sim \{z_n\}$. Artinya $d(x_n, y_n) \to 0$ dan $d(y_n, z_n) \to 0$. Ambil $\varepsilon > 0$.
        $$
        \begin{align*}
        \exists N_1\in \mathbb{N},\ \forall n > N_1:& \ d(x_n, y_n) < \frac\varepsilon2 \\
        \exists N_2\in \mathbb{N},\ \forall n > N_2:& \ d(y_n, z_n) < \frac\varepsilon2
        \end{align*}
        $$
        Pilih $N = \max(N_1, N_2)$. Perhatikan bahwa untuk setiap $n > N:$
        $$d(x_n, z_n) \le d(x_n, y_n) + d(y_n, z_n) < \frac\varepsilon2+\frac\varepsilon2=\varepsilon$$
        Artinya $d(x_n, z_n) \to 0$. Terbukti bahwa $\{x_n\} \sim \{z_n\}$
    
Karena memenuhi ketiga sifat maka $\sim$ adalah relasi ekuivalen di $\Omega$. Kemudian definisikan kelas ekivalen
    $$\left[\{x_n\}\right] = \{\ \{y_n\} \in \Omega\ \ |\ \ \{x_n\} \sim \{y_n\}\ \}$$
untuk setiap $\{x_n\} \in \Omega$. Kemudian definisikan $X^* = \{\ [\{x_n\}] \ \ | \ \ \{x_n\} \in \Omega\ \}$

### Metric di $X^*$
    
Definisikan $d^*: \ X^* \times X^* \to \mathbb{R}$ dengan
    $$d^*([\{x_n\}], [\{y_n\}]) = \lim_{n\to \infty} d(x_n, y_n)$$
Akan ditunjukkan $d^*$ metrik yang terdefinisikan dengan baik.
    
#### Terdefinisi Dengan Baik
Misalkan $\{x_n\} \sim \{x'_n\}$ dan $\{y_n\} \sim \{y'_n\}$. Artinya $d(x_n, x'_n) \to 0$ dan $d(y_n, y'_n) \to 0$.
        
Misalkan $d^*([\{x_n\}], [\{y_n\}]) = L$. Artinya $d(x_n, y_n) \to L$. Akan ditunjukkan $$d^*([\{x'_n\}], [\{y'_n\}]) = L$$
        Ambil $\varepsilon>0$. Maka
        $$
        \begin{align*}
        \exists N_1 \in \mathbb{N}, \ \forall n>N_1: & \ \ \left|d(x_n, y_n) - L\right| < \frac\varepsilon3 \\
        \exists N_2 \in \mathbb{N}, \ \forall n>N_2: & \ \ d(x_n, x'_n) < \frac\varepsilon3 \\
        \exists N_3 \in \mathbb{N}, \ \forall n>N_3: & \ \ d(y_n, y'_n) < \frac\varepsilon3
        \end{align*}
        $$
        Pilih $N = \max(N_1, N_2, N_3)$. Perhatikan bahwa
        $$
        \begin{align*}
        |d(x'_n, y'_n) - d(x_n, y_n)| & \le d(x_n, x'_n) + d(y_n, y'_n)
        \end{align*}
        $$
        Sehingga untuk setiap $n > N$ berlaku
        $$
        \begin{align*}
        |d(x'_n, y'_n) - L| &= |d(x'_n, y'_n) - d(x_n, y_n) + d(x_n, y_n) - L| \\
        &\le |d(x'_n, y'_n) - d(x_n, y_n)| + |d(x_n, y_n) - L| \\
        & \le d(x_n, x'_n) + d(y_n, y'_n) + |d(x_n, y_n) - L| \\
        &< \frac\varepsilon3+\frac\varepsilon3+\frac\varepsilon3 = \varepsilon
        \end{align*}
        $$
        Terbukti $d^*([\{x'_n\}], [\{y'_n\}]) = L$. Artinya $d^*$ terdefinisi dengan baik.
    
#### Urutan
Jelas untuk setiap $[\{x_n\}], [\{y_n\}] \in X^*$ berlaku
        $$d^*([\{x_n\}], [\{y_n\}]) = \lim_{n \to \infty} d(x_n, y_n) =\lim_{n \to \infty} d(y_n, x_n) = d^*([\{y_n\}], [\{x_n\}]) $$
    
#### Non-negatif
Perhatikan bahwa untuk setiap $[\{x_n\}], [\{y_n\}] \in X^*$, $d(x_n, y_n) \ge 0$ sehingga
        $$d^*([\{x_n\}], [\{y_n\}]) = \lim_{n \to \infty} d(x_n, y_n) \ge 0 $$
    
#### Ke-Homogenan
##### $\Rightarrow$
Misalkan $d^*([\{x_n\}], [\{y_n\}]) = 0$. Artinya
            $$\lim_{n \to \infty} d(x_n, y_n) = 0$$
            Perhatikan bahwa $\{x_n\} \sim \{y_n\}$. Artinya $[\{x_n\}] = [\{y_n\}]$
##### $\Leftarrow$
Jelas untuk setiap $[\{x_n\}] \in X^*$ berlaku
            $$d^*([\{x_n\}], [\{x_n\}]) = \lim_{n \to \infty} d(x_n, x_n) = \lim_{n \to \infty}0 = 0$$
    
#### Ketaksamaan Segitiga
Perhatikan bahwa untuk setiap $[\{x_n\}], [\{y_n\}], [\{z_n\}] \in X^*$:
        $$
        \begin{align*}
        d^*([\{x_n\}], [\{y_n\}]) &= \lim_{n \to \infty} d(x_n, y_n) \\
        &\le \lim_{n \to \infty} (d(x_n, z_n) + d(z_n, y_n)) \\
        &= \lim_{n \to \infty} d(x_n, z_n) + \lim_{n \to \infty} d(z_n, y_n) \\
        &= d^*([\{x_n\}], [\{z_n\}]) + d^*([\{z_n\}], [\{y_n\}])
        \end{align*}
        $$

### Isometri $f: X \to X^*$
    
Definisikan suatu $f:X \to X^*$ dengan
    $$f(x) = [(x)]$$
    dimana $(x) := \{x_n\}$ dengan $x_n = x$ untuk setiap $n$. Perhatikan bahwa untuk setiap $x, y \in X$
    $$d^*(f(x), f(y)) = d^*([(x)], [(y)]) = \lim_{n \to \infty} d(x, y) = d(x, y)$$
    Maka $f$ adalah isometri.

### Kepadatan $f(X)$
    
Akan ditunjukkan $f(X)$ padat. Ambil $x^* = [\{x_n\}] \in X^*$. Ambil $\varepsilon>0$.  Karena $\{x_n\}$ barisan cauchy maka $\exists\ N \in \mathbb{N}$ sehingga 
$$
\forall m,n \ge N: \ d(x_n, x_m) < \varepsilon/2
$$    
Tinjau $f(x_N) = [(x_{N})]$. Perhatikan bahwa untuk setiap $n > N:\ d(x_n, x_N) < \varepsilon/2$ sehingga
    $$d^*(x^*, f(x_N)) = d^*([\{x_n\}], [(x_N)]) = \lim_{n\to\infty} d(x_n, x_N) \le \frac{\varepsilon}{2}< \varepsilon$$
    Artinya $f(x_N) \in B(x^*, \varepsilon)\cap f(X)$. Berarti $B(x^*, \varepsilon)\cap f(X) \neq \emptyset$.
    Berdasarkan [[Buat Backup/Semester 3/Fungsi Real/Topologi/Sifat Titik Limit|teorema]] maka $x^* \in \overline{f(X)}$. Karena $x^*$ sembarang, maka $X^* \subseteq \overline{f(X)}$. Terbukti $f(X)$ padat di $X^*$

### Kelengkapan
    
Akan dibuktikan setiap barisan cauchy di $f(X)$ konvergen ke suatu unsur $X^*$. Ambil barisan cauchy $\{y_n\} \subseteq f(X)$. Artinya terdapat barisan $\{x_n\} \subseteq X$ sehingga $f(x_n) = y_n$ untuk setiap bilangan asli $n$.

Akan ditunjukkan $\{x_n\}$ cauchy.
Ambil $\varepsilon > 0$. Artinya terdapat $N \in \mathbb{N}$ sehingga untuk setiap $m, n > N$ berlaku $d^*(y_m, y_n) < \varepsilon$. Karena $f$ isometri maka untuk setiap $m, n>N$ berlaku
    $$d(x_n, x_m) = d^*(f(x_n), f(x_m)) = d^*(y_m, y_n) < \varepsilon$$
Maka $\{x_n\}$ barisan cauchy. Misalkan $x^* = [\{x_n\}]$. Akan ditunjukkan $y_n \to x^*$.
    
Ambil $\varepsilon>0$. Terdapat $N \in \mathbb{N}$ sehingga $d(x_n, x_m) < \varepsilon$ untuk setiap $n, m \ge N$. Artinya
    $$d^*(x^*, y_n) = \lim_{m \to \infty} d(x_m, x_n) \le \varepsilon$$
Terbukti bahwa $y_n \to x^*$. Berarti, untuk setiap barisan cauchy $\{y_n\} \subseteq f(X)$ terdapat $x^* \in X^*$ sehingga $y_n \to x^*$.
    
Berdasarkan teorema terbukti $X^*$ lengkap. Lebih lanjut $X^*$ adalah **pelengkap** dari $X$.


***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Lengkap/Pelengkap Ruang Metrik]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Isometri Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Himpunan Padat]]