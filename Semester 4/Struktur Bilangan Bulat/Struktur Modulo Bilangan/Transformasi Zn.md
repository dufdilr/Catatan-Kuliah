#Teorema 
Misalkan $a, b, n \in \mathbb{N}$. Definisikan
$$
H = a \mathbb{Z}_{n} + b := \{ a[z]_{n} + [b]_{n}\  :\ [z]_{n} \in \mathbb{Z}_{n}  \}
$$
Berlaku $H = \mathbb{Z}_{n}$ jika dan hanya jika $(a, n) = 1$

---
## Bukti
### $\Rightarrow$
Misalkan $H = \mathbb{Z}_{n}$. Artinya $[b+1]_{n} \in H$. Berarti terdapat $z \in \mathbb{Z}$ sehingga $[az + b]_{n} = [b+1]_{n}$. Artinya terdapat $k \in \mathbb{Z}$ sehingga
$$
az + b = b + 1 + nk \quad \Rightarrow \quad az - nk = 1
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Relatif Prima]], maka $(a, n) = 1$.
### $\Leftarrow$
Misalkan $(a, n) = 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]], terdapat $p, q \in \mathbb{Z}$ memenuhi
$$
ap + nq = 1 \quad \Rightarrow \quad [ap]_{n} = [1]_{n}
$$
Berdasarkan definisi [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]], jelas $H \subseteq \mathbb{Z}_{n}$. Ambil $[z]_{n} \in \mathbb{Z}_{n}$. Perhatikan bahwa $[y]_{n} = [p(z-b)]_{n} \in \mathbb{Z}_{n}$. Lebih lanjut, perhatikan bahwa
$$
a[y]_{n} + [b]_{n} = a[p(z - b)]_{n} + [b]_{n} = [ap(z-b) + b]_{n} = [z-b+b]_{n} = [z]_{n}
$$
maka $[z]_{n} \in H$. Berarti $H \supseteq \mathbb{Z}_{n}$.

Terbukti bahwa $H = \mathbb{Z}_{n}$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Penjumlahan Zn]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Relatif Prima]]