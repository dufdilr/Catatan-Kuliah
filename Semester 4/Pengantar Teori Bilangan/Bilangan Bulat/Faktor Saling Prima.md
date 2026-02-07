#Teorema 

Misalkan $m, n \in \mathbb{N}$. Definisikan
$$
D_n := \{ k \in \mathbb{N} : k \mid n \}
$$
himpunan faktor dari $n$. Jika $m, n \in \mathbb{N}$ dengan $(m, n) = 1$ maka fungsi $f: D_m \times D_n \to D_{mn}$ yang didefinisikan sebagai
$$
f(d_1, d_2) = d_1 d_2
$$
adalah fungsi bijeksi.

## Bukti
### Terdefinisi Dengan Baik
Ambil $d_1 \in D_m, \ d_2 \in D_n$. Artinya $m = d_1 k_1$ dan $n = d_2k_2$ untuk suatu $k_1, k_2 \in \mathbb{Z}$. Perhatikan bahwa
$$
mn = d_1k_{1}d_{2}k_{2} = (d_{1}d_{2})k_{1}k_{2}
$$
Artinya $d_1d_2 \in D_{mn}$.

### Injektif
Misalkan $(d_1, d_2), (d_1', d_2') \in D_m \times D_n$ sehingga $d_{1}d_{2} = d_{1}'d_{2}'$. Perhatikan bahwa $d_{1}\mid d_{1}' d_{2}'$. Karena $d_{1}\mid m$ dan $d_{2}' \mid n$ serta $(m, n) = 1$ [[Perkalian Relatif Prima|maka]] $(d_1, d_2') = 1$. [[Hukum Pembatalan Keterbagian|Akibatnya]], $d_1 \mid d_1'$. Dengan alasan serupa didapatkan $d_{1}' \mid d_{1}$. Maka haruslah $d_1 = d_1'$. Konsekuensi lebih lanjut, $d_2 = d_2'$. Maka $(d_1, d_2), = (d_1', d_2')$. Terbukti $f$ injektif.

### Surjektif
Ambil sebarang $k \in D_{mn}$. Maka $k \mid mn$. Pilih $d_1 = (k, m)$ dan $d_2 = (k, n)$. Per definisi [[Faktor Persekutuan Terbesar|FPB]], maka $d_1 \mid m$ dan $d_2 \mid n$. Berarti $(d_1, d_2) \in D_m \times D_n$. Lebih lanjut, berdasarkan [[Teorema Bezout]], terdapat $p_1, q_1, p_2, q_2 \in \mathbb{Z}$ sehingga
$$
d_1 = kp_1 + mq_1 \quad \text{ dan } \quad d_2 = kp_2 + nq_2
$$
Perhatikan bahwa
$$
d_{1}d_{2} = (kp_1 + mq_1)(kp_2 + nq_2) = k(kp_{1}p_{2} + np_{1}q_{2} +mp_{2}q_{1}) + mnq_{1}q_{2}
$$
Karena $k \mid mn$ maka $k \mid d_{1}d_{2}$.
Lebih lanjut, karena $(m, n) = 1$ [[Perkalian Relatif Prima|maka]] $(d_1, d_2) = 1$, berdasarkan [[Teorema Bezout]], terdapat $p, q \in \mathbb{Z}$ sehingga
$$
pd_{1} + qd_{2} =1
$$
Jelas $d_{1} \mid k$ dan $d_{2} \mid k$, maka $k = d_1m_{1} = d_{2}m_{2}$ untuk suatu $m_{1}, m_{2}\in \mathbb{Z}$. Perhatikan bahwa
$$
k = k(pd_{1} + qd_{2}) = pd_{1}d_{2}m_{2} + qd_{2}d_{1}m_{1} = d_{1}d_{2}(pm_{2} + qm_{1})
$$
maka $d_{1}d_{2} \mid k$. Karena $k \mid d_{1}d_{2}$ dan $d_{1}d_{2} \mid k$ terbukti $f(d_{1}, d_{2}) = d_{1}d_{2} = k$



***
## Definition Used 
 * [[Keterbagian]]
 * [[Relatif Prima]]
 * [[Fungsi Bijektif]]