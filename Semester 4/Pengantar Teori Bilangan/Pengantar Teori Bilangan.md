#Rangkuman #NotFinished 
# Teori Bilangan Dasar

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Bilangan Bulat]]
Bilangan Bulat adalah himpunan yang dilengkapi dengan operasi $+$ dan $\times$ yang memenuhi
* **Sifat Penjumlahan**
	1. **Asosiatif:** $\forall a, b, c \in \mathbb{Z}: \quad (a+b)+c=a+(b+c)$
	2. **Komutatif:** $\forall a, b \in \mathbb{Z}: \quad a+b=b+a$
	3. **Identitas Penjumlahan:** $\exists 0 \in \mathbb{Z}$ sehingga $\forall a \in \mathbb{Z}: \quad a+0 = 0+a = a$
	4. **Invers Penjumlahan:** $\forall a \in \mathbb{Z}, \exists b \in \mathbb{Z} : \quad a + b = b + a = 0$
* **Sifat Perkalian**
	1. **Asosiatif:** $\forall a, b, c \in \mathbb{Z}: \quad (a+b)+c=a+(b+c)$
	2. **Komutatif:** $\forall a, b \in \mathbb{Z}: \quad a+b=b+a$
	3. **Identitas Penjumlahan:** $\exists 0 \in \mathbb{Z}$ sehingga $\forall a \in \mathbb{Z}: \quad a+0 = 0+a = a$
* **Sifat Distributif:** 
	$\forall a, b, c \in \mathbb{Z}: \quad (a + b)\cdot c=a\cdot c + b\cdot c$
* **Sifat Keterurutan**
	Terdapat $\mathbb{N} \subseteq \mathbb{Z}$ sehingga untuk setiap $a, b \in \mathbb{N}$ dan $x \in \mathbb{Z}$ berlaku
	1. $a + b \in \mathbb{N}$
	2. $a \times b \in \mathbb{N}$
	3. $z \in \mathbb{N}$ xatau $-z \in \mathbb{N}$ xatau $z = 0$ (Tepat satu yang benar)
* **[[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]]**
	Untuk setiap himpunan $A \subseteq \mathbb{N}$ terdapat unsur terkecil di $A$. Dengan kata lain, terdapat $u \in A$ sehingga untuk setiap $a \in A$ berlaku $u \le a$.

## [[Buat Backup/Prerquested/Relasi dan Fungsi/Prinsip Sarang Merpati]]
Jika terdapat $k$ merpati yang didistribusikan ke $n$ sarang dengan $n > k$ secara acak maka **terdapat dua merpati berbeda** yang menempati sarang yang sama.

## [[Buat Backup/Prerquested/Prinsip Induksi Matematika]]
Misalkan $S \subseteq \mathbb{N}$ dengan:
1. $1 \in S$ 
2. Jika $n \in S$ maka $n + 1 \in S$ 
Maka $S = \mathbb{N}$.


## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Algoritma Pembagian|Algoritma Pembagian]]
Jika $m, n \in \mathbb{Z}$ dan $n > 0$, maka terdapat secara tunggal $q, r \in \mathbb{Z}$ sehingga
$$m = qn + r \quad \text{dan} \quad 0 \le r < n.$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Keterbagian|Keterbagian]]
Misalkan $a, b \in \mathbb{Z}$ dan $a \neq 0$. Unsur $a$ dikatakan membagi $b$ (notasi: $a \mid b$) jika 
    $$\exists \ c \in \mathbb{Z}: \quad b = ca$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian]]
Untuk setiap $m, n \in \mathbb{Z}$ berlaku
1.  $\forall n \in \mathbb{Z}: \quad 1 \mid n$
2.  Jika $m \neq 0$, maka $m \mid 0$
3.  Jika $m \mid n$ dan $n \mid q$, maka $m \mid q$ (**Sifat Transitif**) 
4.  Jika $d \mid m$ dan $d \mid n$, maka $d \mid (tm + sn)$ untuk setiap $t, s \in \mathbb{Z}$ (**Sifat Kelinieran**) 
5.  Jika $m \mid 1$, maka $m = 1$ atau $m = -1$
6.  Jika $m \mid n$ dan $n \mid m$, maka $m = \pm n$ 



## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]
Misalkan $a, b \in \mathbb{Z}$. Suatu bilangan asli $c$ dikatakan **Pembagi Bersama Terbesar** dari $a, b$ (notasi: $c = (a, b)$), jika:
* $c \mid a$ dan $c \mid b$
* Jika $d \mid a$ dan $d \mid b$, maka $d \mid c$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aturan Pembagian Keterbagian]]
Jika $a \mid bc$ maka
$$
\frac{a}{(a, b)} \mid c
$$


## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]]
Jika $a, b \in \mathbb{Z}$, tidak keduanya nol, maka ada bilangan asli **tunggal** $c$ sehingga $c = (a, b)$ dan
$$
c = sa + tb, \quad \text{untuk suatu } s, t \in \mathbb{Z}.
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Euclid FPB|Algortma Euclid]]
Untuk setiap bilangan asli $a, b, m \in \mathbb{Z}$ berlaku
$$
FPB(a, b) = FPB(a, am + b)
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Relatif Prima]]
Bilangan bulat $a, b$ dikatakan relatif prima jika $(a, b) = 1$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Relatif Prima]]
Misalkan $a, b \in \mathbb{Z}$. Maka berlaku $(a, b) = 1$ jika dan hanya jika terdapat $m, n \in \mathbb{Z}$ sehingga $am + bn = 1$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima]]
Jika $a, b, c$ bilangan asli berlaku
    $$(a, c) = 1 \text{ dan } (b, c) = 1 \quad 
    \iff \quad (ab, c) = 1$$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Hasil Bagi FPB Relatif Prima]]
Misalkan $a, b \in \mathbb{N}$ dan $d = (a, b)$ maka
$$
\left(\frac{a}{d}, \frac{b}{d}\right) = 1
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]
Suatu bilangan asli $p > 1$ disebut **prima** jika $\forall a \in \mathbb{Z}$ berlaku
    $$p \mid a \quad \text{atau} \quad (p, a) = 1$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Bilangan Prima]]
Misalkan $p \in \mathbb{N}$ dengan $p > 1$. Bilangan $p$ adalah bilangan prima jika dan hanya jika berlaku "Jika $p \mid (a_1a_2\cdots a_n)$, maka $p \mid a_i$ untuk suatu $i \in \{1, 2, \dots, n\}$".

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor dari Bilangan Prima|Karakterisasi Prima (Faktor)]]
Misalkan suatu bilangan asli $p>1$. Bilangan $p$ adalah bilangan *prima* jika dan hanya jika $p$ memiliki tepat dua faktor positif yakni $1$ dan .

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Komposit]]
Bilangan asli $n > 1$ disebut komposit apabila $n$ bukan bilangan prima.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Prime Checking]]
Misalkan $n \in \mathbb{N}$. Bilangan $n$ merupakan bilangan *komposit* jika dan hanya jika $n$ memiliki faktor prima $p$ dengan $p \le \sqrt{ n }$.

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Dekomposisi Prima]]
Untuk setiap bilangan asli $n > 1$ maka $n$ bilangan prima atau perkalian bilangan prima.

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Fundamental Aritmatika]]

Untuk setiap bilangan asli $n>1$ dapat dituliskan sebagai
$$n = p_1^{a_1} \cdot p_2^{a_2} \cdot p_3^{a_3} \cdots p_k^{a_k}$$
dengan $p_i$ bilangan prima dan $a_i$ bilangan asli secara **tunggal**.

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Ketakhinggaan Bilangan Prima]]
Terdapat tak hingga banyaknya bilangan prima.

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Persamaan Diophantine Linear]]
Misalkan $a, b, c \in \mathbb{Z}$ dan $(a, b) = d$. Tinjau persamaan $ax + by = c$, maka berlaku
1. Jika $d \nmid c$ maka **tidak ada solusi bulat** $(x, y)$ yang memenuhi persamaan $ax + by = c$.
2. Jika $d \mid c$ maka terdapat **tak hingga banyak solusi bulat** $(x, y)$ yang memenuhi persamaan $ax+by = c$. 
	Lebih  lanjut, jika $(x_0, y_0)$ adalah salah satu solusi bulat dari $ax +by = c$ maka solusi bulat lainnya berbentuk
	$$
	x = \frac{b}{d} n + x_0 \quad \text{ dan } \quad y = - \frac{a}{d}n + y_0
	$$
	untuk setiap $n \in \mathbb{N}$


***

# Kongruensi Modulo
## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Kongruensi Modulo]]
Misalkan $n$ suatu bilangan asli. Didefinisikan suatu [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi|relasi]] $a \sim_n b$ jika dan hanya jika $n \mid (a - b)$. Biasanya dinotasikan
$$a \equiv b \mod n$$

Lebih lanjut, relasi ini merupakan [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]].

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Sistem Residu Lengkap]]
Himpunan $S \subseteq \mathbb{N}$ disebut **Sistem Residu Lengkap** modulo $m$ jika untuk setiap $n \in \mathbb{N}$ terdapat **tepat satu** $a \in S$ sehingga $n \equiv a \mod m$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Transformasi Linear Sistem Residu Lengkap]]
Misalkan $S$ membentuk Sistem Residu Lengkap modulo $n$. Definisikan 
$$H = aS + b = \{ as + b \ : \ s \in S \}$$
$H$ membentuk Sistem Residu Lengkap modulo $n$ jika dan hanya jika $(a, n) = 1$


## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Sistem Residu Tereduksi]]
Himpunan $S \subseteq \mathbb{N}$ disebut **Sistem Residu Tereduksi** modulo $m$ jika untuk setiap $n \in \mathbb{N}$ dengan $(a, n) = 1$ terdapat **tepat satu** $a \in S$ sehingga $n \equiv a \mod m$

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Transformasi Sistem Residu Tereduksi]]
Misalkan $S$ membentuk Sistem Residu Tereduksi modulo $n$. Definisikan 
$$H = aS = \{ as \ : \ s \in S \}$$
$H$ membentuk Sistem Residu Tereduksi modulo $n$ jika dan hanya jika $(a, n) = 1$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Operasi Modulo]]
Jika $a, b, c, d, k \in \mathbb{Z}$ dan $n \in \mathbb{N}$ dengan $a \equiv b \mod n$ dan $c \equiv d \mod n$ maka
1. $a + c \equiv b + d \mod n$
2. $a - c \equiv b - d \mod n$
3. $ac \equiv bd \mod n$
4. $a^k \equiv b^k \mod n$
5. $\dfrac{a}{c} \equiv \dfrac{b}{d} \mod \dfrac{n}{(n, c)}$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Kongruensi Linear]]
Misalkan $a, b \in \mathbb{Z}$; $m \in \mathbb{N}$ dan $(a, m) = d$. Tinjau persamaan
$$
ax \equiv b \mod m
$$
maka berlaku:
1. Jika $d \nmid b$ maka persamaan tersebut **tidak memiliki solusi**.
2. Jika $d \mid b$ maka persamaan tersebut memiliki tepat $d$ solusi.


***
# Fungsi Aritmatika

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Aritmatika|Definisi Fungsi Aritmatika]]
Fungsi yang terdefinisi di bilangan Asli $f: \mathbb{N} \to \mathbb{R}$ disebut sebagai **fungsi aritmatika**

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Multiplikatif]]
Misalkan $f$ suatu [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Aritmatika]]. Fungsi $f$ disebut **fungsi multiplikatif** jika untuk setiap $m, n \in \mathbb{N}$ dengan $(m, n) = 1$ berlaku
$$
f(mn) = f(m) \cdot f(n)
$$
Fungsi tersebut dikatakan **fungsi multiplikatif kuat** jika untuk sembarang $m, n \in \mathbb{N}$ berlaku
$$
f(mn) = f(m) \cdot f(n)
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Perkalian Fungsi Multiplikatif]]
Jika $f$ dan $g$ adalah fungsi multiplikatif maka $fg$ juga fungsi multiplikatif.

## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]
Definisikan $\varphi: \mathbb{N} \to \mathbb{N}$ sebagai banyak bilangan asli $k$ dengan $k \le n$ sehingga
$$
(n, k) =1
$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Multiplikatif Fungsi Euler-Phi]]
Fungsi Euler-Phi $\varphi$ adalah fungsi multiplikatif.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Euler-Phi Prima]]
Jika $p$ bilangan prima dan $k \in \mathbb{N}$ maka
$$
\varphi(p^k) = p^k - p^{k-1}
$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Rumus Fungsi Euler-Phi]]
Jika $n = p_{1}^{a_{1}}p_{2}^{a_{2}}\cdots p_k^{a_k}$ adalah [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Fundamental Aritmatika|Faktorisasi Prima]] dari $n$ maka
$$
\varphi(n) = \left(p_{1}^{a_{1}}-p_{1}^{a_{1}-1}\right)\left( p_{2}^{a_{2}}-p_{2}^{a_{2}-1} \right)  \cdots \left( p_k^{a_k}-p_k^{a_k-1} \right) 
$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Teorema Euler (Modulo)]]
Jika $(a, n) = 1$ maka 
$$a^{\varphi(n)} \equiv 1 \pmod{n}$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Teorema Kecil Fermat]]
Jika $a \in \mathbb{N}$ dan $p$ bilangan prima maka
$$
a^p \equiv a \mod p
$$


## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Summation Aritmatika]]
Misalkan $f$ fungsi aritmatika. Definisikan fungsi Summation Aritmatika dari $f$ sebagai
$$
F(n) = \sum_{d \mid n} f(d)
$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Multiplikatif Fungsi Summation Aritmatika]]
Jika $f$ adalah fungsi multiplikatif maka Summation Aritmatika dari $f$ juga **multiplikatif**.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Summation Aritmatika dari Euler]]
Misalkan $n \in \mathbb{N}$ maka
$$
\sum_{d \mid n} \phi(d) = n
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Mobius]]
Untuk setiap $n \in \mathbb{N}$, didefinisikan fungsi mobius
$$
\mu(n) := 
\begin{cases}
1 & ; n = 1  \\
(-1)^r & ; n = p_1 p_2 \cdots p_r \\
0 &; p_i^2 \mid n \text{ untuk suatu bilangan prima } p_i
\end{cases}
$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Multiplikatif Fungsi Mobius]]
Fungsi mobius adalah fungsi multiplikatif

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Summation Aritmatika dari Mobius]]
Untuk setiap bilangan asli $n$ berlaku summation aritmatika dari fungsi mobius
$$
F(n) = \sum_{d \mid n} \mu(d) = 
\begin{cases}
1 & \text{ jika } n = 1; \\
0 & \text{ jika } n \neq 1
\end{cases}
$$

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Teorema Inversi Mobius]]
Misalkan $F$ adalah suatu fungsi multiplikatif, maka terdapat fungsi multiplikatif $f$ sehingga
$$
F(n) = \sum_{d \mid n} f(d)
$$
Lebih lanjut, $f$ multiplikatif dan berbentuk
$$
f(n) = \sum_{d\mid n} \mu(d) F\left(\frac{n}{d}\right)
$$

***

# Akar Primitif

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Orde Modulo]]
Misalkan $a, n \in \mathbb{N}$ dengan $(a, n) = 1$. Definisikan
$$
\text{ord}_{n}\left({a}\right) := \min \{ x \in \mathbb{N} : a^x \equiv 1 \mod n\}
$$
Eksistensi dijamin oleh [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Teorema Euler (Modulo)]] dan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]].

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat]]
Misalkan $a, n \in \mathbb{N}$. Bilangan $x \in \mathbb{N}$ adalah solusi persamaan
$$
a^x \equiv 1 \mod n
$$
jika dan hanya jika $\text{ord}_{n}\left({a}\right) \mid x$.

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Kongruensi Modulo Pangkat]]
Misalkan $a, n \in \mathbb{N}$ dengan $(a, n) = 1$. Berlaku
$$
a^i \equiv a^j \mod n \quad\iff\quad \text{ord}_{n}\left({a}\right) \mid (i - j)
$$
## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Akar Primitif]]
Misalkan $n, r \in \mathbb{N}$ dengan $(n, r) = 1$. $r$ disebut **Akar Primitif** dari $n$ apabila 
$$
\text{ord}_{n}\left({r}\right) = \varphi(n)
$$
Lebih lanjut, jika terdapat bilangan asli $r$ yang memenuhi maka $n$ disebut **memiliki akar primitif**

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Sistem Residu Akar Primitif]]
Misalkan $r, n \in \mathbb{N}$ dan $r$ adalah **akar primitif** dari $n$. Maka himpunan
$$
R = \{ r, r^2, r^3, \cdots, r^{\varphi(n)} \}
$$
membentuk **Sistem Residu Tereduksi**

## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Orde Modulo Pangkat]]
Misalkan $a, n, u \in \mathbb{N}$ dengan $\text{ord}_{n}\left({a}\right) = t$. Maka berlaku
$$
\text{ord}_{n}\left({a^u}\right) = \frac{t}{(t, u)}
$$
## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Akar Primitif Pangkat]]
Misalkan $n \in \mathbb{N}$ dan $r$ adalah akar primitif dari $n$. Maka
$$
r^u \text{ akar primitif } n \quad\iff\quad (u, \varphi(n)) = 1
$$
## [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Banyak Akar Primitif]]
Misalkan $n \in \mathbb{N}$ memiliki akar primitif maka $n$ memiliki sebanyak $\varphi(\varphi(n))$ akar primitif berbeda (up to modulo).

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Teorema Lagrange Polinomial Bulat]]
Misalkan $p$ bilangan prima dan polinomial
$$
f(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_1x + a_{0}
$$
dengan $a_0, a_1, a_2, \dots, a_n \in \mathbb{Z}$ dan $a_n$ tidak habis dibagi $p$ maka $f(x)$ memiliki paling banyak $n$ akar berbeda dalam modulo $p$ sehingga $p \mid f(x)$.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Banyak Akar Orde Modulo Pembagi p-1]]
Misalkan $p$ bilangan prima dan $d \mid p$ maka
$$
\left|\{ k \in \mathbb{N}, k\le \ |\  \text{ord}_{p}(k) = d\}\right| = \varphi(d)
$$
### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Eksistensi Akar Primitif Prima]]
Setiap Bilangan Prima memiliki Akar Primitif.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Eksistensi Akar Primitif Prima Kuadrat]]
Misalkan $p$ adalah bilangan prima ganjil dan $r$ adalah akar primitif dari $p$. Maka $r$ atau $r+p$ adalah akar primitif dari $p^2$.

### [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Eksistensi Akar Primitif Pangkat Prima]]
Misalkan $p$ adalah bilangan prima ganjil dan $k \in \mathbb{N}$ maka $p^k$ memiliki akar primitif.