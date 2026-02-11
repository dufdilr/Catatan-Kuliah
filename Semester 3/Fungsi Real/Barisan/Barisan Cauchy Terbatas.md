#Teorema

Jika $(x_n) \subseteq \mathbb{X}$ adalah barisan cauchy maka $(x_{n})$ merupakan barisan terbatas.

---
## Bukti
Misalkan $(x_{n}) \subseteq \mathbb{X}$ adalah barisan cauchy. Dengan memilih $\varepsilon = 1$, maka ada $N \in \mathbb{N}$ sehingga 
$$\forall\ m, n > N: \ d(x_m, x_n) < 1$$
Pilih $c = x_{N+1}$. Berdasarkan kondisi di atas, berarti $\forall \ n > N:\ d(x_n, c) < 1$.

Tinjau himpunan jarak dari suku-suku awal ke $c$:
$$H = \left\{d(x_1, c), \ d(x_2, c), \ \cdots\ ,\ d(x_{N}, c)\right\}$$
Perhatikan bahwa $H$ adalah himpunan berhingga, sehingga terdapat elemen maksimum. Misalkan $R = \max(H)$. Ini berarti $\forall \ n \le N:\ d(x_n, c) \le R$.

Pilih $M = \max\{1, R\} + 1$. Maka untuk setiap $n \in \mathbb{N}$:
* Jika $n > N$, maka $d(x_n, c) < 1 < M$.
* Jika $n \le N$, maka $d(x_n, c) \le R < M$.

Karena $\forall n \in \mathbb{N}$ berlaku $d(x_n, c) < M$, artinya $(x_{n})$ terbatas. ■

***
## Definition Used:
* [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]
* [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Terbatas (Metrik)]]