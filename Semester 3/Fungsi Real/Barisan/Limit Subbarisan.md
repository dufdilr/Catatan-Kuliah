#Teorema

Setiap subbarisan dari suatu barisan konvergen juga konvergen ke nilai yang sama.

---
## Bukti
Misalkan $(x_n)$ adalah barisan dalam $\mathbb{X}$ yang konvergen ke $x$, yaitu $x_n \to x$. Ambil sembarang subbarisan $(x_{n_k})$ dari $(x_n)$.

Ambil $\varepsilon > 0$. Karena $x_n \to x$, maka terdapat suatu bilangan asli $N$ sehingga untuk setiap $n > N$, berlaku:
$$d(x_n, x) < \varepsilon$$
Perhatikan bahwa $n_k$ monoton naik. Artinya, terdapat $K \in \mathbb{N}$ sehingga untuk setiap $k > K: \ n_K > N$. Sehingga untuk setiap $k >K$ berlaku $d(x_{n_k}, x) < \varepsilon$

Terbukti bahwa subbarisan $(x_{n_k})$ konvergen ke limit yang sama, yaitu $x$. ■

***
## Definition Used:
* [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
* [[Buat Backup/Semester 3/Fungsi Real/Barisan/Subbarisan]]