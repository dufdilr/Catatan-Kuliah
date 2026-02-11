#Teorema 

Jika $a \mid bc$ maka
$$
\frac{a}{(a, b)} \mid c
$$

## Bukti


Misalkan $a \mid bc$ dan $(a, b) = d$. Tulis $a = dm, \ b = dn$ untuk suatu $m \in \mathbb{Z}$. Berdasarkan [[Teorema Bezout]], terdapat $k_{1}, k_{2} \in \mathbb{Z}$  sehingga
$$ak_1 + bk_2 = d \quad \Rightarrow \quad dmk_{1} + dnk_{2} = d \quad \Rightarrow \quad mk_{1} + nk_{2} = 1$$Karena $a \mid bc$ maka terdapat $k_3 \in \mathbb{Z}$ sehingga 
$$
bc = ak_3 \quad \Rightarrow \quad dnc = dmk_3 \quad \Rightarrow \quad nc = mk_3
$$
Perhatikan bahwa
$$c = c(mk_1 + nk_2) = mck_1 + nck_2 = m(ck_1 + k_2k_3)$$
Maka, terbukti $m = \frac{a}{(a, b)} \mid c$.

***
## Definition Used 
 * [[Keterbagian]]
 * [[Faktor Persekutuan Terbesar]]