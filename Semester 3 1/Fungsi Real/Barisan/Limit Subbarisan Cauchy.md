#Teorema

Misalkan $(x_n)$ adalah barisan Cauchy. Jika terdapat subbarisan yang konvergen, maka barisan tersebut juga konvergen ke nilai yang sama.

---
## Bukti
Misalkan $(x_n) \subseteq \mathbb{X}$ adalah barisan Cauchy dan terdapat subbarisan $(x_{n_k})$ sehingga $x_{n_k} \to x$ untuk suatu $x \in \mathbb{X}$.

Ambil $\varepsilon > 0$. Karena $(x_n)$ adalah barisan Cauchy, maka:
$$\exists N_1 \in \mathbb{N} \text{ sehingga } \forall m, n > N_1 \text{ berlaku } d(x_m, x_n) < \frac{\varepsilon}{2}$$Karena subbarisan $(x_{n_k})$ konvergen ke $x$, maka:$$\exists K \in \mathbb{N} \text{ sehingga } \forall k > K \text{ berlaku } d(x_{n_k}, x) < \frac{\varepsilon}{2}$$
Pilih $N = \max\{N_1, n_K\}+1$. Ambil $m > N$. Perhatikan bahwa karena $(x_{n_k})_k$ subbarisan dari $(x_{n})$ maka
$$\forall \ m \in \mathbb{N}, \ \exists \ k \in \mathbb{N}: \ n_k > m$$
Lebih lanjut perhatikan bahwa
$$d(x_m, x) \le d(x_m, x_{n_k}) + d(x_{n_k}, x) < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = {\varepsilon} $$
Artinya $\forall \ n>N: \ d(x_n, x) < \varepsilon$. Terbukti bahwa $(x_{n})$ barisan konvergen ke $x$.

***
## Definition Used:
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Subbarisan]]