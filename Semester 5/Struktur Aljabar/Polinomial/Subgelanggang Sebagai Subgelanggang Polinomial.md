#Teorema 
Jika $R$ adalah gelanggang komutatif dan $S$ adalah subgelanggang dari $R$ maka 
$$
S[x] := \{ s_0+s_{1}x+s_{2}x^2+\dots+s_nx^n \in R[x] \ | \ n \in \mathbb{N_0}, \text{ dan }\ s_0, s_1, \dots,s_n \in S \}
$$
membentuk subgelanggang dari $R[x]$.

---
## Bukti
Jelas polinomial nol ada di $S[x]$. Maka $S[x]$ dan jelas $S[x] \subseteq R[x]$.

Ambil $f(x), g(x) \in S[x]$. Tulis 
$$
f(x) = a_{0}+a_{1}x+a_{2}x^2+\cdots \quad \text{dan} \quad g(x) = b_{0}+b_{1}x+b_{2}x^2 + \cdots
$$
dengan $a_i, b_j \in S$ untuk setiap $i, j \in \mathbb{N}$. Misalkan $k(x) = f(x) - g(x) = c_{0} + c_{1}x + c_{2}x^2 + \dots$ dan $h(x) = f(x)g(x) = d_{0} + d_{1}x + d_{2}x^2 + \dots$. Perhatikan bahwa
$$
\begin{align*}
c_k &= a_k - b_k \\
d_k &= \sum_{i = 0}^k a_ib_{k-i}
\end{align*}
$$
Perhatikan bahwa $S$ adalah subgelanggang dari $R$ dan $a_i, b_j \in S$ untuk setiap $i, j \in \mathbb{N}$. Artinya $a_k-b_k, \sum a_ib_{k-i} \in S$. Maka $c_k, d_k \in S$ untuk setiap $k \in \mathbb{N}$. Artinya $f(x)-g(x), f(x)g(x) \in S$.

Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang]] maka $S[x]$ membentuk subgelanggang dari $R[x]$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Komutatif]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Subgelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Gelanggang Polinomial]]