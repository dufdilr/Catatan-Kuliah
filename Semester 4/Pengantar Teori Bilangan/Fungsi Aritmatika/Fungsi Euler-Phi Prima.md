#Teorema 

Jika $p$ bilangan prima dan $k \in \mathbb{N}$ maka
$$
\varphi(p^k) = p^k - p^{k-1}
$$
---
## Bukti
Jelas jika $p \mid n$ maka $p \mid (n, p^k)$ sehingga $(p^k, n) \neq 1$. Lebih lanjut, jika $p \not\mid m$ maka $(p, m) = 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima]] maka $(p^k, m) = 1$.

Artinya $(p^k, m) = 1 \iff p \not\mid m$ . Perhatikan bahwa banyak bilangan yang habis dibagi $p$ yang tidak lebih dari $p^{k}$ adalah $p^{k-1}$. Artinya
$$
\varphi(p^k) = p^k - p^{k-1}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]