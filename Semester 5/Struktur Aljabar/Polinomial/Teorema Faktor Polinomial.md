#Teorema 

Misalkan $R$ adalah gelanggang komutatif dengan unit. Misalkan $f(x) \in R[x]$ dan $c \in R$. Berlaku
$$
f(c) = 0 \iff f(x) = q(x) (x - c), \ \exists q(x) \in R[x]
$$
---
## Bukti

### $\Rightarrow$
Tinjau $g(x) = x - c \in R[x]$. Perhatikan bahwa $g$ memiliki leading koefisien 1 / unit. Berdasarkan [[Algoritma Euclid Polinomial]] maka terdapat $q(x), r(x) \in R[x]$ dengan $\deg r(x) < \deg g = 1$ sedemikian sehingga
$$
f(x) = q(x)(x-c) + r(x)
$$
Perhatikan bahwa $\deg r \le 0$. Tulis $r(x) = a$ dengan $a \in R$. Perhatikan bahwa
$$
\begin{align*}
f(c) &= q(c)(c - c) + a \\
0 &= q(c) \cdot 0 + a = a
\end{align*}
$$
Maka $a = 0$. Terbukti terdapat $q(x) \in R[x]$ sehingga $f(x) = q(x)(x-c)$.

### $\Leftarrow$
Misalkan terdapat $q(x) \in R[x]$ sehingga
$$
f(x) = q(x)(x-c)
$$
Berdasarkan [[Sifat Gelanggang]] maka
$$
f(c) = q(c)\cdot(c - c) = q(c) \cdot 0 = 0
$$
Terbukti.

***
## Definition Used 
 * [[Gelanggang Komutatif]]
 * [[Gelanggang Unit]]
 * [[Gelanggang Polinomial]]