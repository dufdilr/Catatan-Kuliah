#Rangkuman #NotFinished 

# Aksioma Bilangan Real
## [[Aksioma Bilangan Real]]
Himpunan $\mathbb{R}$ dilengkapi dengan operasi $+$ dan $\times$ didefinisikan sebagai himpunan yang memenuhi aksioma berikut:
1. **Aksioma Lapangan**
	1. **Asosiatif Penjumlahan**
		Untuk setiap $a, b, c \in \mathbb{R}$ berlaku
		$$(a+b)+c = a+ (b+c)$$
	2. **Komutatif Penjumlahan**
		Untuk setiap $a, b \in \mathbb{R}$ berlaku
		$$a+b = b+a$$
	3. **Identitas Penjumlahan**
		Terdapat $0 \in \mathbb{R}$ sehingga untuk setiap $a \in \mathbb{R}$ berlaku
		$$a + 0 = a$$
	4. **Inverse Penjumlahan**
		Untuk setiap $a \in \mathbb{R}$ terdapat $-a \in \mathbb{R}$ sehingga
		$$a+(-a) = 0$$
	5. **Asosiatif Perkalian**
		Untuk setiap $a, b, c \in \mathbb{R}$ berlaku
		$$(a\times b)\times c = a\times (b\times c)$$
	6. **Komutatif Perkalian**
		Untuk setiap $a, b \in \mathbb{R}$ berlaku
		$$a\times b = b\times a$$
	7. **Identitas Perkalian**
		Terdapat $1 \in \mathbb{R}-\{0\}$ sehingga untuk setiap $a \in \mathbb{R}$ berlaku
		$$a \times 1 = a$$
	8. **Inverse Perkalian**
		Untuk setiap $a \in \mathbb{R}-\{0\}$ terdapat $a^{-1} \in \mathbb{R}-\{0\}$ sehingga
		$$a \times a^{-1} = 1$$
	9.  **Distributif Penjumlahan-Perkalian**
	Untuk setiap $a, b, c \in \mathbb{R}$ berlaku
	$$
	a \times (b+c) = (a\times b) + (a\times c)
	$$
2. **Aksioma Urutan**
	Terdapat $\mathbb{P} \subseteq \mathbb{R}$ dengan
	1. Untuk setiap $a, b \in \mathbb{P}$ berlaku $a + b \in \mathbb{P}$.
	2. Untuk setiap $a, b \in \mathbb{P}$ berlaku $a \times b \in \mathbb{P}$.
	3. Untuk setiap $a \in \mathbb{R}$ berlaku tepat satu: $a \in \mathbb{P}$, atau $-a \in \mathbb{P}$, atau $a = 0$.

3. **Aksioma Kelengkapan**
	Untuk setiap $A \subseteq \mathbb{R}$ yang terbatas di bawah maka terdapat $a \in \mathbb{R}$ sehingga $a = \inf(A)$. 

## [[Urutan Bilangan Real]]
Berdasarkan aksioma, misalkan $\mathbb{P} \subseteq \mathbb{R}$  adalah himpunan yang memenuhi aksioma urutan. Definisikan relasi 
$$
a < b \iff b-a \in \mathbb{P}
$$
Lebih lanjut, didefinisikan pula $\mathbb{P}_{0} = \mathbb{P}\cup \{ 0 \}$
$$
\begin{align*}
a>b & \iff a - b \in \mathbb{P} \\
a\le b & \iff b - a \in \mathbb{P}_{0}  \\
a\ge b & \iff a - b \in \mathbb{P}_{0} 
\end{align*}
$$
Lebih lanjut, $(\mathbb{R}, \le)$ membentuk *urutan parsial*, yakni
1. **Refleksif**: Untuk setiap $a \in \mathbb{R}$ berlaku $a \le a$
2. **Anti-simetris**: Untuk setiap $a, b \in \mathbb{R}$ berlaku: Jika $a \le b$ dan $b \le a$ maka $a = b$.
3. **Transitif**: Untuk setiap $a, b, c \in \mathbb{R}$ berlaku: Jika $a \le b$ dan $b \le c$ maka $a \le c$

### [[Sifat Urutan Keras Bilangan Real]]
Misalkan $a, b, c \in \mathbb{P}$ maka berlaku
1. **Transitif:** Jika $a > b$ dan $b > c$ maka $a > c$.
2. **Penjumlahan:** Jika $a > b$ maka $a + c > b + c$
3. **Perkalian Positif:** Jika $a > b$ dan $c > 0$ maka $ac > bc$
4. **Perkalian Negatif:** Jika $a > b$ dan $c < 0$ maka $ac < bc$

### [[Ketaksamaan Trivial Kuadrat]]
Untuk setiap $x \in \mathbb{R}$ berlaku $x^2 \ge 0$. Lebih lanjut, $x^2 = 0$ jika dan hanya jika $x = 0$.

## [[Nilai Mutlak]]
Misalkan $x \in \mathbb{R}$. Definisikan nilai mutlak dari $x$ sebagai
$$
|x| := 
\begin{cases}
x, & \text{ jika } x \ge 0 \\ \\
-x, & \text{ jika } x < 0
\end{cases}
$$
### [[Sifat Nilai Mutlak]]
Untuk setiap $x, y \in \mathbb{R}$ dan $a > 0$ berlaku
1. $|x| \ge 0$
2. $|x|\cdot |y| = |xy|$
3. $|x| \le a \iff -a \le x \le a$
4. $-|x|\le x \le |x|$

### [[Ketaksamaan Segitiga Nilai Mutlak]]
Misalkan $x, y \in \mathbb{R}$. Berlaku
$$
|x + y| \le |x| + |y|
$$

### [[Generalisasi Ketaksamaan Segitiga Nilai Mutlak]]
Misalkan $x_{1}, x_{2}, x_{3}, \dots , x_n \in \mathbb{R}$ maka
$$
|x_{1}+x_{2}+x_{3}+\dots+x_n| \le |x_{1}| + |x_{2}|+\cdots + |x_n|
$$

## [[Himpunan Terbatas di Atas]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Himpunan $A$ disebut **terbatas di atas** jika terdapat $u \in \mathbb{R}$ sehingga untuk setiap $x \in A$ berlaku
$$
u \ge x
$$
Lebih lanjut $u$ disebut **batas atas** dari $A$.

### [[Himpunan Terbatas di Bawah]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Himpunan $A$ disebut **terbatas di bawah** jika terdapat $a \in \mathbb{R}$ sehingga untuk setiap $x \in A$ berlaku
$$
a \le x
$$
Lebih lanjut, $a$ disebut **batas bawah** dari $A$.

### [[Himpunan Terbatas]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Himpunan $A$ disebut **terbatas** jika $A$  terbatas di atas dan terbatas di bawah.

### [[Supremum]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Elemen $a \in \mathbb{R}$ disebut **supremum** dari $A$ (notasi: $a = \sup(A)$) apabila
1. Elemen $a$ adalah batas atas dari $A$ dengan kata lain, untuk setiap $x \in A$ berlaku
$$
a \ge x
$$
2. Jika $b$ adalah batas atas dari $A$ maka berlaku $a \le b$.

Dengan kata lain, supremum adalah *batas atas terkecil*.

### [[Infimum]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Elemen $a \in \mathbb{R}$ disebut **infimum** dari $A$ (notasi: $a = \inf(A)$) apabila
1. Elemen $a$ adalah batas bawah dari $A$ dengan kata lain, untuk setiap $x \in A$ berlaku
$$
a \le x
$$
2. Jika $b$ adalah batas bawah dari $A$ maka berlaku $a \ge b$.

Dengan kata lain, infimum adalah *batas bawah terbesar*

### [[Eksistensi Supremum dan Infimum]]
Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Jika $A$ terbatas di bawah maka $A$ memiliki infimum. Lebih lanjut, jika $A$ terbatas di atas maka $A$ memiliki supremum.

### [[Perbandingan Infimum dan Supremum]]
Misalkan $A, B$ subhimpunan tak-kosong dari $\mathbb{R}$. Jika untuk setiap $a\in A$ dan $b\in B$ berlaku
$$
a \le b
$$
Maka $A$ memiliki supremum dan $B$ memiliki infimum dengan $\sup A \le \inf B$.

## [[Fungsi Real Terbatas]]
Misalkan $A$ subhimpunan tak-kosong dari $\mathbb{R}$ dan fungsi $f: A \to \mathbb{R}$. 
1. Fungsi $f$ disebut **terbatas di atas** jika $f(A)$ terbatas di atas. Lebih lanjut, $\sup f = \sup f(A)$.
2. Fungsi $f$ disebut **terbatas di bawah** jika $f(A)$ terbatas di bawah. Lebih lanjut, $\inf f = \inf f(A)$.
3. Fungsi $f$ disebut **terbatas** jika $f(A)$ terbatas.
### [[Supremum dan Infimum Fungsi]]
Misalkan $A$ subhimpunan takkosong dari $\mathbb{R}$ dan $f, g:A \to \mathbb{R}$ fungsi terbatas dengan 
$$
f(x) \le g(x)
$$
untuk setiap $x \in A$. Maka
1. $\sup f \le \sup g$
2. $\inf f \le \inf g$


## [[Sifat Archimedean]]
Untuk setiap bilangan real $x, y \in \mathbb{R}$ dengan $x > 0$ terdapat $M \in \mathbb{N}$ sehingga $Mx > y$.

### [[Fungsi Tangga]]
Misalkan $x \in \mathbb{R}$. Definisikan
$$
\begin{align*}
\lfloor x \rfloor  &:= \max \{ n \in \mathbb{Z} \ | \ n \le x \} \\
\lceil x \rceil  & := \min \{ n \in \mathbb{Z} \ | \ n \ge x \}
\end{align*}
$$

