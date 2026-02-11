#Teorema 
Jika $a, b, c, d, k \in \mathbb{Z}$ dan $n \in \mathbb{N}$ dengan $a \equiv b \mod n$ dan $c \equiv d \mod n$ maka
1. $a + c \equiv b + d \mod n$
2. $a - c \equiv b - d \mod n$
3. $ac \equiv bd \mod n$
4. $a^k \equiv b^k \mod n$
5. Jika $am \equiv bm \mod n$ maka $a \equiv b \mod \dfrac{n}{(n, m)}$.

Operasi 1 - 4 serupa dengan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]
## Bukti
Karena $a \equiv b \mod n$ dan $c \equiv d \mod n$ maka $n \mid (a - b)$ dan $n \mid (c -d)$
### 1.
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|Sifat Keterbagian]] maka
$$
n \mid (a - b) + (c - d) = (a + c) - (b + d)
$$
Berarti, $a + c \equiv b + d \mod n$

### 2.
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|Sifat Keterbagian]] maka
$$
n \mid (a - b) - (c - d) = (a - c) - (b + d)
$$
Berarti, $a - c \equiv b - d \mod n$

### 3.
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|Sifat Keterbagian]] maka
$$
n \mid (a - b)c + (c - d)b = (ac) - (bd)
$$
Berarti, $ac \equiv bd \mod n$

### 4.
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|Sifat Keterbagian]] maka
$$
n \mid (a - b)(a^{k-1} + a^{k-2}b + \cdots + ab^{k-2} + b^{k-1}) = a^k - b^k
$$
Berarti, $a^k\equiv b^k \mod n$


### 5.
Karena $am \equiv bm \mod n$ maka $n \mid am - bm = m(a - b)$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aturan Pembagian Keterbagian]] maka
$$
\frac{n}{(n, m)} \mid (a - b) \quad \Rightarrow \quad a \equiv b \mod \frac{n}{(n, m)}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Kongruensi Modulo]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Keterbagian]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]