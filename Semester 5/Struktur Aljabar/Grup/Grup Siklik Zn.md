#Teorema 

Misalkan $n \in \mathbb{N}$ dengan $n > 1$. $\mathbb{Z}_{n}$ adalah grup siklik. Lebih lanjut, $[x]_{n} \in \mathbb{Z}_{n}$ adalah pembangun dari $\mathbb{Z}_{n}$ jika dan hanya jika $(x, n) = 1$.

---
## Bukti

Jelas $[x]_{n}\in \mathbb{Z}_{n}$ berlaku
$$
[x]_{n} = [x\cdot1]_{n}
$$
maka $\mathbb{Z}_{n} = \left< [1]_{n} \right>$. Terbukti $\mathbb{Z}_{n}$ adalah grup siklik.

Lebih lanjut, misalkan $[a]_{n}$ adalah pembangun dari $\mathbb{Z}_{n}$. Artinya $[1]_{n} = [ka]_{n}$ untuk suatu $k \in \mathbb{Z}_{n}$. Berarti $n \mid ka -1$, terdapat $p \in \mathbb{Z}$ sehingga
$$
ka - 1 = np \quad\implies\quad ka - np = 1
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Relatif Prima]] maka $(n, k) = 1$.

Lebih lanjut, misalkan $(a, n) = 1$. Ambil $[x]_{n} \in \mathbb{Z}_{n}$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]], terdapat $p, q \in \mathbb{Z}_{n}$ sedemikian sehingga
$$
np + aq = 1 \quad\implies\quad npx + aqx = x \quad\implies\quad n \mid aqx - x \quad\implies\quad [aqx]_{n} = [x]_{n}
$$
Maka, $[x]_{n}$ dibangun oleh $[a]_{n}$. Terbukti $[a]_{n}$ adalah pembangun dari $\mathbb{Z}_{n}$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Penjumlahan Zn]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Relatif Prima]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Terbangun]]