#Teorema 

Misalkan $p$ bilangan prima dan $d \mid p-1$ maka
$$
\left|\{ k \in \mathbb{N}, k\le \ |\  \text{ord}_{p}(k) = d\}\right| = \varphi(d)
$$

***
## Bukti
Misalkan $F(d)$ adalah banyak bilangan asli $k < p$ sehingga $\text{ord}_{p}(k) = d$.  Perhatikan bahwa jika $(a, p) = 1$ [[Teorema Euler (Modulo)|maka]] $a^{p-1} \equiv 1 \mod p$. Berdasarkan [[Persamaan Diophantine Modulo Pangkat|teorema]] maka
$$
\text{ord}_{p}(a) \mid p-1
$$
Perhatikan bahwa untuk setiap $k < p$ berlaku $(p, k) = 1$. Artinya setiap bilangan asli kurang dari sama dengan $p-1$ berlaku $\text{ord}_{p}(k) = d \mid p$. Maka berlaku
$$
\sum_{d\mid p-1}F(d) = p - 1
$$
Perhatikan pula bahwa [[Summation Aritmatika dari Euler|teorema]]
$$
\sum_{d \mid p-1} \varphi(d) = p-1
$$
Berdasarkan [[Teorema Inversi Mobius]] maka $F(d) = \varphi(d)$. Terbukti.

***
## Definition Used 
 * [[Bilangan Prima]]
 * [[Orde Modulo]]
 * [[Fungsi Euler-Phi]]
 * [[Fungsi Summation Aritmatika]]
 * [[Teorema Inversi Mobius]]