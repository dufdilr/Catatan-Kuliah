#Teorema 

Misalkan $a, n, u \in \mathbb{N}$ dengan $\text{ord}_{n}\left({a}\right) = t$. Maka berlaku
$$
\text{ord}_{n}\left({a^u}\right) = \frac{t}{(t, u)}
$$

---
## Bukti

Misalkan $(t, u) = d$ dan $\text{ord}_{n}\left({a^u}\right) = k$. Tulis $t = dt_1$ dan $u = du_{1}$ dengan $t_{1},u_{1} \in \mathbb{N}$. Perhatikan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Hasil Bagi FPB Relatif Prima|bahwa]] $(t_{1}, u_{1})=1$. Perhatikan bahwa
$$
(a^u)^{t_{1}} = (a^{du_{1}})^{t_{1}} = a^{du_{1}t_{1}} = a^{tu_{1}} \equiv 1^{u_{1}} \equiv 1 \mod n
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat|teorema]] maka $k \mid t_{1}$. Lebih lanjut, perhatikan bahwa
$$
(a^u)^k \equiv 1 \mod n \quad\implies\quad a^{du_{1}k} \equiv 1 \mod n
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat|teorema]] maka $t = dt_{1} \mid du_{1}k$. [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian|Artinya]] $t_{1} \mid u_{1}k$. Karena $(t_{1}, u_{1}) = 1$ berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Hukum Pembatalan Keterbagian|teorema]] maka $t_{1}\mid k$.

Karena $k \mid t_{1}$ dan $t_{1}\mid k$ maka $t_{1} = k$. Artinya, terbukti bahwa 
$$
\text{ord}_{n}\left({a^u}\right) = \frac{t}{(t, u)}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Orde Modulo]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]