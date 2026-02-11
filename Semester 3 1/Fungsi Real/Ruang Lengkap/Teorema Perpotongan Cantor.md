#Teorema 


Ruang metrik $X$ lengkap jika dan hanya jika untuk setiap barisan himpunan tutup takkosong $\{F_n\}$ dengan $F_{n} \supseteq F_{n+1}$ dan $\displaystyle\lim_{n \to \infty} \text{diam}(F_n) = 0$ terdapat $a \in X$ sehingga
$$\bigcap_{n = 1}^\infty F_n = \{a\}$$

---

## Bukti

### ($\Rightarrow:$)
Misalkan $X$ suatu ruang metrik lengkap. Misalkan pula suatu barisan himpunan tutup takkosong $\{F_n\}$ dengan $F_{n} \supseteq F_{n+1}$ dan $\displaystyle\lim_{n \to \infty} \text{diam}(F_n) = 0$.
    
Ambil $x_n \in F_n$. Akan ditunjukkan $\{x_n\}$ cauchy. Ambil $\varepsilon > 0$. Karena $\text{diam}(F_n) \to 0$ maka terdapat $N \in \mathbb{N}$ sehingga
    $$\forall n > N: \ \text{diam}(F_n) = \sup\left\{\ d(x, y)\ \ |\ \ x, y \in F_n\ \right\}< \varepsilon$$
    Perhatikan bahwa $\forall n, m > N+1:\ x_n \in F_n \subseteq F_N$ dan $x_m \in F_m \subseteq F_N$ sehingga
    $$d(x_n, x_m) \le \sup\left\{\ d(x, y)\ \ |\ \ x, y \in F_N\ \right\}< \varepsilon$$
    Maka $\{x_n\}$ cauchy. Karena $X$ lengkap maka terdapat $a \in X$ sehingga $x_n \to a$.
    
Kemudian akan ditunjukkan $\displaystyle \bigcap F_n = \{a\}$
    
Perhatikan bahwa untuk setiap $m \in \mathbb{N}: \ \{x_n\}_{n \ge m} \subseteq F_m$. Karena $x_n \to a$ maka subbarisan $\{x_n\}_{n \ge m}$ [[Buat Backup/Semester 3/Fungsi Real/Barisan/Limit Subbarisan|juga konvergen ke]] $a$. Berarti $a \in \overline{F_m}$. Karena $F_m$ himpunan tutup berarti $a \in F_m$. Karena berlaku untuk setiap $m \in \mathbb{N}$ maka
    $$a \in \bigcap F_n$$
    
Misalkan $a' \in \bigcap F_n$. Perhatikan bahwa $d(a, a') \ge 0$. Ambil $r > 0$. Karena $\text{diam}(F_n) \to 0$ maka terdapat $N_2 \in \mathbb{N}$ sehingga $\text{diam}(F_n) \le r$ untuk setiap $n > N_2$. Karena $a, a' \in \bigcap F_n$ maka $a, a' \in F_{N_2+1}$. Artinya, $d(a, a') \le r$.
    
Karena $0 \le d(a, a')$ dan untuk setiap $r>0$ berlaku $d(a, a') \le r$ maka $d(a, a') = 0$. Artinya $a = a'$. Terbukti bahwa
    $$\bigcap_{n = 1}^\infty F_n = \{a\}$$

### ($\Leftarrow:$)
Misalkan berlaku untuk setiap barisan himpunan tutup takkosong $\{F_n\}$ dengan $F_{n} \supseteq F_{n+1}$ dan $\displaystyle\lim_{n \to \infty} \text{diam}(F_n) = 0$ terdapat $a \in X$ sehingga
    $$\bigcap_{n = 1}^\infty F_n = \{a\}$$
    
Ambil suatu barisan cauchy $\{x_n\}\subseteq X$. Tinjau barisan himpunan $E_n := \{x_k \ | \ k \ge n\}$. Jelas $E_{n +1} \subseteq E_n$. Berdasarkan [[Buat Backup/Semester 3/Fungsi Real/Topologi/Sifat Penutup Himpunan#^738419|teorema]] didapatkan $\overline{E_{n+1}} \subseteq\overline{E_n}$
    
Lebih lanjut, ambil $\varepsilon > 0$. Karena $\{x_n\}$ cauchy maka terdapat $N \in \mathbb{N}$ sehingga $d(x_m, x_n) < \frac\varepsilon2$ untuk setiap $m, n > N$. Misalkan $N_3 = N +1$.
    $$\text{diam}(E_{N_3}) = \sup\{d(x_n, x_m) \ | \ n, m \ge N_3\} \le \frac\varepsilon2 < \varepsilon$$
Berarti $\text{diam}(E_n) \to 0$. Berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Diameter Himpunan Penutup|teorema]] maka $\text{diam}(\overline{E_n}) \to 0$
    
Karena $\left\{\overline{E_n}\right\}$ barisan himpunan tutup dengan $\overline{E_{n+1}} \subseteq\overline{E_n}$ dan $\text{diam}\left(\overline{E_n}\right) \to 0$ maka berdasarkan premis terdapat $a \in X$ sehingga
    $$\bigcap_{n = 1}^\infty \overline{E_n} = \{a\}$$
    Akan ditunjukkan bahwa $x_n \to a$. Ambil $\varepsilon > 0$. Karena $\text{diam}\left(\overline{E_n}\right) \to 0$ maka terdapat $N_4$ sehingga $\text{diam}\left(\overline{E_{N_4}}\right) <\varepsilon$. Perhatikan bahwa $a \in \overline{E_{N_4}}$ dan $\{x_n\}_{n \ge N_4} \subseteq \overline{E_{N_4}}$. Berarti untuk setiap $n > N_4$ berlaku
    $$d(a, x_n) < \varepsilon$$
    Terbukti $x_n \to a$. Karena setiap barisan cauchy konvergen maka $X$ lengkap.
    
***

## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Himpunan Tutup]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Diameter Himpunan]]