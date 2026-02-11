#Teorema 

Untuk setiap bilangan asli $n$ berlaku summation aritmatika dari fungsi mobius
$$
F(n) = \sum_{d \mid n} \mu(d) = 
\begin{cases}
1 & \text{ jika } n = 1; \\
0 & \text{ jika } n \neq 1
\end{cases}
$$
---

## Bukti
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Multiplikatif Fungsi Mobius]] dan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Multiplikatif Fungsi Summation Aritmatika]] maka $F(n)$ merupakan **fungsi multiplikatif**. 

Jelas bahwa
$$
F(1) = \mu(1) = 1
$$
Lebih lanjut, perhatikan untuk bilangan prima $p$ dan $k \in \mathbb{N}$, berlaku
$$
F(p^k) = \mu(1) + \mu(p) + \mu(p^2) + \cdots + \mu(p^{k}) = 1 + (-1)^1 + 0 + 0 + \cdots + 0 = 0
$$
Misalkan $n \neq 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Fundamental Aritmatika]], maka dapat dituliskan $n = p_1^{a_1} p_{2}^{a_{2}} \cdots p_k^{a_k}$ . Karena $F$ adalah fungsi multiplikatif maka
$$
F(n) = F(p_1^{a_1}) \cdot F(p_2^{a_2}) \cdots F(p_k^{a_k}) = 0 \cdot 0 \cdots 0 = 0
$$
Terbukti bahwa
$$
F(n) = \sum_{d \mid n} \mu(d) = 
\begin{cases}
1 & \text{ jika } n = 1; \\
0 & \text{ jika } n \neq 1
\end{cases}
$$

***

## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Mobius]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Summation Aritmatika]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Multiplikatif]]
