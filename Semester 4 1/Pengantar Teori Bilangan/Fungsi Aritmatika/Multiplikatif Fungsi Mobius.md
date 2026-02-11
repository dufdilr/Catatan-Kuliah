#Teorema 

[[Fungsi Mobius]] adalah fungsi [[Fungsi Multiplikatif|multiplikatif]]

---
## Bukti
Misalkan $m, n \in \mathbb{N}$ dengan $(m, n) = 1$. Perhatikan bahwa
* Jika $m = 1$ jelas 
$$
\mu (mn) = \mu(n) = 1 \mu(n) = \mu(m)\mu(n)
$$Hal serupa juga berlaku jika $n = 1$.
* Jika $p_i^2 \mid m$ untuk suatu bilangan prima $p_i$. Perhatikan bahwa jelas $p_i^2 \mid mn$. Artinya
 $$
 \mu(mn) = 0 = 0 \mu(n) = \mu(m) \mu(n)
 $$
 Hal serupa juga berlaku jika $p_j^2 \mid n$ untuk suatu bilangan prima $p_j$
* Jika $m, n \neq 1$ dan tidak ada bilangan prima $p_i$ sehingga $p_i^2 \mid m$ atau $p_i^2 \mid n$. Tulis faktorisasi prima dari $m$ dan $n$ sebagai
	$$
	m = p_1 p_2 \cdots p_k \quad \text{dan} \quad n = q_1q_2\cdots q_l
$$
Perhatikan bahwa karena $(m, n) = 1$ maka tidak ada faktor prima yang membagi keduanya. Artinya
$$
mn =  p_1 p_2 \cdots p_k  q_1q_2\cdots q_l
$$
Berarti
$$
\mu(mn) = (-1)^{k + l} = (-1)^k \cdot (-1)^l = \mu(m) \mu(n)
$$

Terbukti untuk semua kasus, berlaku $\mu(mn) = \mu(m) \mu(n)$. Berarti fungsi mobius adalah **fungsi multiplikatif**.
***
## Definition Used 
 * [[Fungsi Mobius]]
 * [[Fungsi Multiplikatif]]
