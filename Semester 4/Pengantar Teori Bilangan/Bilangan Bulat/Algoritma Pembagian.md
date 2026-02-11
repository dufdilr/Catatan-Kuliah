#Teorema
**Teorema (Algoritma Pembagian)**

Jika $m, n \in \mathbb{Z}$ dan $n > 0$, maka terdapat secara tunggal $q, r \in \mathbb{Z}$ sehingga
$$m = qn + r \quad \text{dan} \quad 0 \le r < n.$$

---

## Bukti:

### 1. Eksistensi (Existence)

Misalkan $m, n \in \mathbb{Z}$ dengan $n > 0$. Tinjau himpunan:
$$S = \{ m - kn \mid k \in \mathbb{Z}\}$$
Lebih lanjut, tinjau $S^* = S \cap \mathbb{N}$. Perhatikan bahwa $m - (-m^2) n = m^2n +m \ge m^2 + m \ge0$. Artinya $m^2n+m \in S^*$. Berarti $S^*$ tak-kosong. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]] terdapat unsur terkecil $a = m - t_{1}n$.

Akan ditunjukkan bahwa $a \le n$ dengan kontradiksi. Andaikan $a > n$. Tinjau $a^* = a - n$. Perhatikan bahwa 
$$a^* = a - n = m - (t_{1}+1)n$$
Artinya $a^* \in S$. Lebih lanjut, karena $a \le n$ maka $a^* = a - n \ge 0$. Artinya $a^* \in S^*$. Jelas $a^* < a$, maka $a$ bukan elemen terkecil dari $A$. Kontradiksi.

* Jika $a = n$, maka $n = m - t_1n$ sehingga $m = (t_1 + 1)n$. Pilih $q = t_1 + 1, r = 0$ maka $m = qn + r$.
* Jika $a < n$, pilih $q = t_1, r = a$ maka $m = qn + r$ 

Terbukti keberadaan $p, q$.
### 2. Ketunggalan (Uniqueness)

Misalkan ada dua pasang bilangan bulat, $(q_1, r_1)$ dan $(q_2, r_2)$, yang memenuhi
1.  $m = q_1n + r_1$, dengan $0 \le r_1 < n$
2.  $m = q_2n + r_2$, dengan $0 \le r_2 < n$

Perhatikan bahwa $q_1n + r_{1} = m = q_{2}n + r_{2}$, artinya
$$
r_{1} - r_{2} = n(q_{2} - q_{1})
$$
Perhatikan bahwa
$$
\begin{align*}
-n < r_2 - r_1 < n \\
-n < n(q_2 - q_1) < n
\end{align*}
$$
Berarti $-1 < q_2 - q_1 < 1$, sehingga $q_2 - q_1 = 0$. Didapatkan $q_1 = q_2$.

Lebih lanjut, $r_1 = m - q_1n = m - q_2n = r_2$. Berarti $r_1 = r_2$.
Karena $r_1 = r_2$ dan $q_1 = q_2$, maka pasangan $(q, r)$ adalah tunggal. ■

***
## Definition Used
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Bilangan Bulat]]