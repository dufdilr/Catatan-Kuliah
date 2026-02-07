#Teorema 
Misalkan $a, b, c \in \mathbb{Z}$ dan $(a, b) = d$. Tinjau persamaan $ax + by = c$, maka berlaku
1. Jika $d \nmid c$ maka **tidak ada solusi bulat** $(x, y)$ yang memenuhi persamaan $ax + by = c$.
2. Jika $d \mid c$ maka terdapat **tak hingga banyak solusi bulat** $(x, y)$ yang memenuhi persamaan $ax+by = c$. 
	Lebih  lanjut, jika $(x_0, y_0)$ adalah salah satu solusi bulat dari $ax +by = c$ maka solusi bulat lainnya berbentuk
	$$
	x = \frac{b}{d} n + x_0 \quad \text{ dan } \quad y = - \frac{a}{d}n + y_0
	$$
	untuk setiap $n \in \mathbb{N}$

## Bukti
### 1.
Misalkan $(a, b) = d \nmid c$. Andaikan terdapat solusi bulat $(x, y)$ yang memenuhi $ax + by = c$. Per definisi, $d \mid a$ dan $d \mid b$. Berdasarkan [[Sifat Keterbagian#^ab6a93|sifat kelinearan keterbagian]] maka $d \mid ax +by = c$, kontradiksi dengan $d \nmid c$. Maka pengandaian salah. Terbukti, tidak ada solusi bulat $(x, y)$ yang memenuhi.
### 2.
Misalkan $(a, b) = d \mid c$. Tulis $c = dm$ untuk suatu $m \in \mathbb{Z}$. Berdasarkan [[Teorema Bezout]] maka
$$ d = ap + bq$$
untuk suatu $p, q \in \mathbb{Z}$. Maka, $apm + bqm = dm = c$. Terbukti terdapat solusi bulat.

Lebih lanjut, misalkan $x_0, y_0 \in \mathbb{Z}$ dengan $ax+by = c$
Ambil $n \in \mathbb{N}$, Tinjau $x = \frac{b}{d} n + x_0, y = - \frac{a}{d}n + y_0$. Perhatikan bahwa $d \mid b$ dan $d \mid a$ maka $x, y$ adalah bilangan bulat. Perhatikan bahwa
$$
ax + by = a\left(\frac{b}{d} n + x_0\right) + b \left(- \frac{a}{d} + y_0 \right) =  \frac{abn}{d} + ax_0 - \frac{abn}{d} + by_0 = ax_0 + by_0 = c
$$
maka, $x, y$ tersebut adalah solusi bulat dari $ax + by = c$.

Lebih lanjut, misalkan $x, y$ adalah solusi bulat dari persamaan $ax + by = c$. Perhatikan bahwa $ax_0 + by_0 = c$, maka didapatkan
$$
a(x - x_0) + b(y - y_0) = 0 \quad \Rightarrow \quad a(x - x_0) = -b (y - y_0) \quad \Rightarrow \quad \frac{a}{d}(x - x_0) = - \frac{b}{d} (y - y_0)
$$
Perhatikan bahwa $(a, b) = d$ [[Hasil Bagi FPB Relatif Prima|maka]] $\left(\dfrac{a}{d}, \dfrac{b}{d}\right) = 1$. Perhatikan bahwa $\dfrac{b}{d} \mid  \dfrac{a}{d}(x - x_0)$. Karena $\left(\dfrac{a}{d}, \dfrac{b}{d}\right) = 1$ maka haruslah $\dfrac{b}{d} \mid (x - x_0)$. Berarti
$$
x - x_0 = \frac{b}{d} n \quad \Rightarrow \quad x = x_0 + \frac{b}{d}n
$$
Perhatikan bahwa 
$$
\begin{align*}
\frac{a}{d}(x - x_0) &= - \frac{b}{d} (y - y_0) \\ \frac{ab}{d^2}n &= - \frac{b}{d} (y - y_0) \\
y - y_0 &= - \frac{a}{d} n \\
y &= - \frac{a}{d} n + y_0
\end{align*}
$$
Terbukti bahwa solusi bulat selalu berbentuk
$$	x = \frac{b}{d} n + x_0 \quad \text{ dan } \quad y = - \frac{a}{d}n + y_0
	$$

***
## Definition Used 
 * [[Faktor Persekutuan Terbesar]]
 * [[Keterbagian]]
