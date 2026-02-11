#Teorema 

Jika $R$ adalah Daerah Integral dan $f(x), g(x) \in R[x]$ dengan $f(x) \neq 0$ dan $g(x) \neq 0$, maka berlaku:
1. $\deg(f(x) + g(x)) \le \max(\deg f(x), \deg g(x))$
2. $\deg(f(x)g(x)) = \deg f(x) + \deg g(x)$

---
## Bukti
Misalkan $f(x)$ berderajat $n$ dan $g(x)$ berderajat $m$. Tuliskan polinomial tersebut sebagai:
$$
f(x) = \sum_{i=0}^{n} a_i x^i = a_0 + a_1 x + \dots + a_n x^n, \quad \text{dengan } a_n \neq 0
$$
$$
g(x) = \sum_{j=0}^{m} b_j x^j = b_0 + b_1 x + \dots + b_m x^m, \quad \text{dengan } b_m \neq 0
$$

### 1. Derajat Penjumlahan
Misalkan $h(x) = f(x) + g(x)$.
Koefisien dari $x^k$ pada $h(x)$ adalah $c_k = a_k + b_k$.
Tanpa mengurangi keumuman, asumsikan $n \ge m$.
$$
h(x) = (a_0+b_0) + (a_1+b_1)x + \dots + (a_m+b_m)x^m + \dots + a_n x^n
$$
Perhatikan suku dengan pangkat tertinggi:
* **Kasus $n > m$**: Suku tertinggi adalah $a_n x^n$. Karena $a_n \neq 0$, maka $\deg(h) = n = \max(n, m)$.
* **Kasus $n = m$**: Suku tertinggi adalah $(a_n + b_n)x^n$. Derajat $h(x)$ adalah $n$ jika $a_n + b_n \neq 0$, atau kurang dari $n$ jika $a_n = -b_n$. Sehingga $\deg(h) \le n = \max(n, m)$.

Dalam semua kasus, terbukti bahwa:
$$
\deg(f(x) + g(x)) \le \max(\deg f(x), \deg g(x))
$$

### 2. Derajat Perkalian
Misalkan $p(x) = f(x)g(x)$.
Koefisien dari $x^k$ pada $p(x)$ diberikan oleh konvolusi:
$$
c_k = \sum_{i+j=k} a_i b_j
$$
Kita ingin mencari koefisien untuk pangkat $n+m$, yaitu $c_{n+m}$.
Satu-satunya pasangan $(i, j)$ yang memenuhi $i+j = n+m$ dengan syarat $0 \le i \le n$ dan $0 \le j \le m$ adalah $i=n$ dan $j=m$.
Maka:
$$
c_{n+m} = a_n b_m
$$
Karena $R$ adalah **Daerah Integral**, maka $R$ tidak memuat pembagi nol.
Diketahui $a_n \neq 0$ dan $b_m \neq 0$, maka hasil kalinya haruslah:
$$
a_n b_m \neq 0
$$
Sedangkan untuk sebarang $k > n+m$, koefisien $c_k$ akan bernilai 0 karena salah satu dari $a_i$ atau $b_j$ pasti 0 (di luar derajat masing-masing).

Oleh karena itu, suku dengan pangkat tertinggi pada $f(x)g(x)$ adalah $x^{n+m}$ dengan koefisien tak nol $a_n b_m$.
Jadi,
$$
\deg(f(x)g(x)) = n + m = \deg f(x) + \deg g(x)
$$
Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Integral]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Gelanggang Polinomial]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial]]