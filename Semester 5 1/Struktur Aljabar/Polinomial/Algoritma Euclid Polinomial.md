#Teorema 
Misalkan $R$ adalah gelanggang komutatif dengan unit. Misalkan $f(x), g(x) \in R[x]$ sehingga koefisien utama dari $g(x)$ adalah **unit**. Maka terdapat $q(x), r(x) \in R[x]$ **secara tunggal** sehingga
$$
f(x) = g(x)q(x) + r(x)
$$
dengan $\deg r(x) < \deg g(x)$.

---
## Bukti
Akan ditunjukkan eksistensi $q(x)$ dan $r(x)$. 
* **Jika** $\deg f < \deg g$.
	Pilih $q(x) = 0$ dan $r(x) = f(x)$. Maka $\deg r = \deg f < \deg g$. Lebih lanjut
	$$
f(x) = g(x) \cdot 0 + f(x) = g(x) q(x) + r(x)
$$
	Terbukti, terdapat $q(x)$ dan $r(x)$ yang memenuhi.
* **Jika** $\deg f \ge \deg g$. 
	Jelas karena koefisien utama dari $g(x)$ adalah unit maka $g(x)$ bukan nol. Maka $0 \le \deg g \le \deg f$. Definisikan
	$$
P(n) := \text{Jika } \deg f = n \text{ dan } \deg g \le \deg f \text{ maka terdapat } r(x), q(x) \text{ yang memenuhi.} 
$$
	Akan ditunjukkan untuk setiap $n \in \mathbb{N}_{0}: P(n)$ benar.
	* **Kasus Basis**
		Misalkan $\deg f = 0$. Telah ditunjukkan bahwa $\deg g \ge 0$, maka $\deg g = 0$. Tulis $f(x) = a$ dan $g(x) = b$ dengan $a, b \in R$. Berdasarkan hipotesa teorema, $b$ adalah unit di $R$. Artinya terdapat $b^{-1}\in R$ sehinga $b^{-1}b = 1$.
		
		Pilih $q(x) = b^{-1}a$ dan $r(x) = 0$. Jelas $\deg r = -\infty < 0 = \deg g$. Lebih lanjut
		$$
f(x) = a = bb^{-1}a + 0 = g(x)q(x) + r(x)
$$
		Terbukti, terdapat $q(x), r(x)$ yang memenuhi.
		
	* **Langkah Induksi**
		Misalkan terdapat $n \in \mathbb{N}$ sehingga untuk setiap $k < n$ berlaku $P(k)$ benar. Akan ditunjukkan $P(n)$ benar. 
		
		Misalkan $f(x) = a_{0}+a_{1}x + a_{2}x^2 + \dots + a_nx^n$ dan $g(x) = b_{0}+b_{1}x+b_{2}x^2+\dots+b_mx^m$ dengan $m \le n$ dan $a_n, b_m \neq 0$. Perhatikan bahwa $b_m$ adalah unit. Tinjau $h(x) = a_nb_m^{-1}x^{n-m}$. Perhatikan bahwa
		$$
\begin{align*}
h(x) g(x) &= a_{n}b_m^{-1}b_0x^{n-m} + a_{n}b_m^{-1}b_1x^{n-m+1} a_{n}b_m^{-1}b_2x^{n-m+2}  + \dots + a_{n}b_m^{-1}b_{m-1}x^{n-1}  + a_{n}b_m^{-1}b_mx^{n} \\
&= a_{n}b_m^{-1}b_0x^{n-m} + a_{n}b_m^{-1}b_1x^{n-m+1} a_{n}b_m^{-1}b_2x^{n-m+2}  + \dots + a_{n}b_m^{-1}b_{m-1}x^{n-1} + a_{n}x^{n}
\end{align*}
$$
	Misalkan $F(x) = f(x) - h(x)g(x)$. Perhatikan bahwa $\deg F < n$. Berdasarkan hipotesa induksi maka terdapat $Q(x)$ dan $r(x)$ dengan $\deg r(x) < g(x)$ sehingga
	$$
\begin{align*}
F(x) &= g(x)Q(x) + r(x) \\
f(x) - g(x)h(x) &= g(x)Q(x) + r(x) \\
f(x) &= g(x)\left( Q(x) + h(x) \right)  + r(x)
\end{align*}
$$
		Pilih $q(x) = Q(x) + h(x)$ maka didapatkan
		$$
f(x) = g(x)q(x) + r(x)
$$
	Terbukti terdapat $q(x), r(x)$ yang memenuhi

	Berdasarkan [[Prinsip Induksi Matematika]] maka $P(n)$ benar untuk setiap $n \in \mathbb{N}$. Artinya terbukti jika $\deg g \le \deg f$ terdapat $q(x)$ dan $r(x)$ yang memenuhi.


Maka untuk kedua kasus, telah ditunjukkan eksistensi $q(x)$ dan $r(x)$ yang memenuhi. Akan ditunjukkan terkait dengan ketunggalan $q(x)$ dan $r(x)$. Misalkan
$$
f(x) = g(x)q_{1}(x) + r_{1}(x) = g(x)q_{2}(x) + r_{2}(x)
$$
dengan $\deg r_{1}, \deg r_{2} < \deg g$. Perhatikan bahwa
$$
\begin{align*}
g(x)q_{1}(x) - g_{}(x)q_{2}(x) &= r_{2}(x) - r_{1}(x)\\
g(x)(q_{1}(x) - q_{2}(x)) &= r_{2}(x) - r_{1}(x)
\end{align*}
$$
Andaikan $q_{1}(x) \neq q_{2}(x)$. Artinya $q_{1}(x) - q_{2}(x) \neq 0$. Perhatikan bahwa $g(x)$ memiliki koefisien utama unit. Maka
$\deg g(q_{1}-q_{2}) = \deg(g) + \deg(q_{1}+q_{2}) \ge \deg(g) > \deg r_{2}, \deg r_{1} \ge \deg (r_{2}-r_{1})$. Kontradiksi, dengan kesamaan.
Maka $q_{1}(x) = q_{2}(x)$. Lebih lanjut, 
$$
r_{1}(x) = f(x)  -g(x)q_{1}(x) = f(x) - g(x)q_{2}(x) = r_{2}(x)
$$
Terbukti ketunggalan.

***
## Definition Used 
 * [[Algoritma Pembagian]]
 * [[Gelanggang Polinomial]]
 * [[Unsur Unit (Ring)]]
 * [[Gelanggang Komutatif]]
 * [[Gelanggang Unit]]