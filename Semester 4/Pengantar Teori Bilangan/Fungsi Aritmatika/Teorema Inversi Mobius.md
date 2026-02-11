#Teorema 
Misalkan $F$ adalah suatu fungsi multiplikatif, maka terdapat fungsi multiplikatif $f$ sehingga
$$
F(n) = \sum_{d \mid n} f(d)
$$
Lebih lanjut, $f$ multiplikatif dan berbentuk
$$
f(n) = \sum_{d\mid n}\left( \mu(d) F\left(\frac{n}{d}\right)\right)
$$
---
## Bukti
Perhatikan bahwa
$$
\begin{align*}
\sum_{d\mid n} \left(\mu(d) F\left(\frac{n}{d}\right)\right) &= \sum_{d\mid n} \left(\mu(d) \sum_{k \mid \left( \frac{n}{d} \right)} f(k) \right)\\
&= \sum_{d\mid n} \left(\sum_{k \mid \left( \frac{n}{d} \right)} \mu(d)f(k) \right)
\end{align*}
$$
Perhatikan bahwa himpunan tupel $(d, k)$ dengan $d \mid n$ dan $k \mid (\frac{n}{d})$ sama dengan tupel $(k, d)$ dengan $k \mid n$ dan $d \mid \left( \frac{n}{k} \right)$. Artinya, kita dapat tuliskan
$$
\begin{align*}
\sum_{d\mid n} \left(\sum_{k \mid \left( \frac{n}{d} \right)} \mu(d)f(k) \right) &= \sum_{k\mid n}\left( \sum_{d \mid \left( \frac{n}{k} \right)} \mu(d)f(k)  \right)\\
&= \sum_{k\mid n}\left( f(k) \sum_{d \mid \left( \frac{n}{k} \right)} \mu(d)\right)
\end{align*}
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Summation Aritmatika dari Mobius|teorema]], berlaku
$$
\begin{align*}
\sum_{d \mid \left( \frac{n}{k} \right)} \mu(d) = 
\begin{cases}
1 & ; k = n \\
0 & ; k \text{ lainnya}
\end{cases}
\end{align*}
$$
sehingga dapat disimpulkan
$$
\begin{align*}
\sum_{k\mid n} f(k) \sum_{d \mid \left( \frac{n}{k} \right)} \mu(d) &= f(n) \cdot 1 = f(n)
\end{align*}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Mobius]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Multiplikatif]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Summation Aritmatika]]
