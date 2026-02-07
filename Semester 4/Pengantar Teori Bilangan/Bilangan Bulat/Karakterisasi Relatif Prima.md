#Teorema

Misalkan $a, b \in \mathbb{Z}$. Maka berlaku $(a, b) = 1$ jika dan hanya jika terdapat $m, n \in \mathbb{Z}$ sehingga $am + bn = 1$

---

## Bukti

* **($\Rightarrow$):**
    Jelas berdasarkan [[Teorema Bezout]].

* **($\Leftarrow$):**
    Misalkan $k_1a + k_2b = 1$. Akan dibuktikan $(a, b) = 1$.

    Misalkan $c = (a, b)$. Karena $c \mid a$ dan $c \mid b$, maka berdasarkan[[Sifat Keterbagian#^ab6a93| Sifat Kelinearan Keterbagian]], $c$ harus membagi kombinasi linear dari $a$ dan $b$.
    $$c \mid (k_1a+k_2b)$$
    Ini berarti $c \mid 1$. Karena $c$ adalah bilangan asli (berdasarkan definisi FPB), satu-satunya kemungkinan adalah $c=1$.
    Sehingga terbukti $(a, b) = 1$.


***
## Definition Used:
* [[Aksioma Bilangan Bulat]]
* [[Faktor Persekutuan Terbesar]]
