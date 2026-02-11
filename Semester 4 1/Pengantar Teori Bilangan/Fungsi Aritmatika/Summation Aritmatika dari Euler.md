#Teorema 

Misalkan $n \in \mathbb{N}$ maka
$$
\sum_{d \mid n} \phi(d) = n
$$

---
## Bukti
Perhatikan bahwa berdasarkan [[Hasil Bagi FPB Relatif Prima]] berlaku
$$
d = (a, b) \iff \left(\frac{a}{d}, \frac{b}{d}\right) = 1
$$
Perhatikan bahwa $(k, n) = d \mid n$. Artinya, kita dapat mempartisi bilangan asli kurang dari $n$ sesuai [[Faktor Persekutuan Terbesar]] dengan $n$. Lebih lanjut, $(k, n) = d \iff (\frac{k}{d}, \frac{n}{d}) = 1$. Artinya, besar partisi $d$ adalah $\phi\left( \frac{n}{d} \right)$. Terbukti
$$
n = \sum_{d \mid n} \phi\left( \frac{n}{d} \right) = \sum_{d\mid n} \phi(d)
$$

***
## Definition Used 
 * [[Bilangan Asli]]
 * [[Fungsi Summation Aritmatika]]
 * [[Fungsi Euler-Phi]]