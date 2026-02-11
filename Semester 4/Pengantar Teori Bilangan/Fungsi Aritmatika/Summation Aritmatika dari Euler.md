#Teorema 

Misalkan $n \in \mathbb{N}$ maka
$$
\sum_{d \mid n} \phi(d) = n
$$

---
## Bukti
Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Hasil Bagi FPB Relatif Prima]] berlaku
$$
d = (a, b) \iff \left(\frac{a}{d}, \frac{b}{d}\right) = 1
$$
Perhatikan bahwa $(k, n) = d \mid n$. Artinya, kita dapat mempartisi bilangan asli kurang dari $n$ sesuai [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]] dengan $n$. Lebih lanjut, $(k, n) = d \iff (\frac{k}{d}, \frac{n}{d}) = 1$. Artinya, besar partisi $d$ adalah $\phi\left( \frac{n}{d} \right)$. Terbukti
$$
n = \sum_{d \mid n} \phi\left( \frac{n}{d} \right) = \sum_{d\mid n} \phi(d)
$$

***
## Definition Used 
 * [[Buat Backup/Prerquested/Bilangan Asli]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Summation Aritmatika]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]