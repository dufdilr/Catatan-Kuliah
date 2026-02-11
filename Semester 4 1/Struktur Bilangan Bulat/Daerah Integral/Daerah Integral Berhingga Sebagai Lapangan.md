#Teorema 

Setiap daerah integral yang berhingga adalah lapangan

---

## Bukti

Misalkan $D$ suatu daerah integral dengan banyak elemen $n$. Ambil $a\in D$ dengan $a$ tak-nol. Tinjau himpunan
$$\{a, a^2, a^3, \cdots, a^{n+1}\}$$
Berdasarkan [[Prinsip Sarang Merpati|prinsip sarang merpati]], ada $i < j$ (dengan $i, j \le n+1$) sehingga $a^i = a^j$. Perhatikan bahwa
$$
\begin{align*}
a^i &= a^j \\
a^i &= a^i \cdot a^{j - i} \\
1 &= a^{j - i} \quad \text{(Hukum pencoretan di daerah integral, $a^i \neq 0$)} \\
1 &= a \cdot a^{j - i - 1}
\end{align*}
$$
Maka, $a^{j-i-1}$ adalah invers perkalian dari $a$. Karena $a$ adalah sembarang unsur taknol di $D$, maka setiap unsur taknol di $D$ memiliki invers. Maka $D$ adalah lapangan.

---

## Definition Used 
 * [[Daerah Integral]]
 * [[Lapangan]]