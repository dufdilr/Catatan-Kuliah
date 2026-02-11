#Teorema

Misalkan $n \in \mathbb{N}$ dan $[a]_{n} \in \mathbb{Z}_n$. Jika $(a, n) = 1$ maka ada $[b]_{n}\in\mathbb{Z}_n$ sehingga 
$$[a]_{n}\cdot[b]_{n} = [1]_{n}$$

---
## Bukti
Misalkan suatu bilangan asli $n$ dan $[a]_{n} \in \mathbb{Z}_n$ dengan $(a, n) = 1$.

Berdasarkan **[[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout|Identitas Bezout]]**, karena $(a,n)=1$, maka ada bilangan bulat $k_1$ dan $k_2$ sehingga:
$$ak_1 + nk_2 = 1 \quad \Rightarrow \quad
ak_1 - 1 = (-k_2)n$$
Berarti $n \mid (ak_1 - 1)$ atau dengan kata lain $ak_1 \equiv 1 \pmod{n}$. Akibatnya
$$[ak_{1}]_{n} = [a]_{n}[k_{1}]_{n} = [1]_{n}$$
Pilih $b = k_{1}$, sehingga terbukti memenuhi $[a]_n [b]_n = [1]_n$. $\blacksquare$

***
## Definition Used:
* [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Zn]]
* [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]
