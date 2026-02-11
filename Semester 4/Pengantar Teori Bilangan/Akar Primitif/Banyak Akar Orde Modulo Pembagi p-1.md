#Teorema 

Misalkan $p$ bilangan prima dan $d \mid p-1$ maka
$$
\left|\{ k \in \mathbb{N}, k\le \ |\  \text{ord}_{p}(k) = d\}\right| = \varphi(d)
$$

***
## Bukti
Misalkan $F(d)$ adalah banyak bilangan asli $k < p$ sehingga $\text{ord}_{p}(k) = d$.  Perhatikan bahwa jika $(a, p) = 1$ [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Teorema Euler (Modulo)|maka]] $a^{p-1} \equiv 1 \mod p$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat|teorema]] maka
$$
\text{ord}_{p}(a) \mid p-1
$$
Perhatikan bahwa untuk setiap $k < p$ berlaku $(p, k) = 1$. Artinya setiap bilangan asli kurang dari sama dengan $p-1$ berlaku $\text{ord}_{p}(k) = d \mid p$. Maka berlaku
$$
\sum_{d\mid p-1}F(d) = p - 1
$$
Perhatikan pula bahwa [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Summation Aritmatika dari Euler|teorema]]
$$
\sum_{d \mid p-1} \varphi(d) = p-1
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Teorema Inversi Mobius]] maka $F(d) = \varphi(d)$. Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Orde Modulo]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Summation Aritmatika]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Teorema Inversi Mobius]]