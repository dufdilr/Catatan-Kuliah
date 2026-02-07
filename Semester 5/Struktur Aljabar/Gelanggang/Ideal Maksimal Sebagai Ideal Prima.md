#Teorema 

Misalkan $R$ adalah gelanggang komutatif unit dan $I$ adalah ideal maksimum dari $R$. Maka, $I$ adalah ideal prima dari $R$.

---
## Bukti

Misalkan $I$ adalah ideal maksimum dari $R$. Akan ditunjukkan $I$ adalah ideal prima.

Ambil $x, y \in R$ dengan $x \notin I$ namun $xy \in I$. Tinjau $J = I + \left< x \right>$. Perhatikan bahwa $\left< x \right>$ adalah [[Ideal Utama]]. Lebih lanjut, berdasarkan [[Jumlah Ideal]] maka $J$ juga ideal dari $R$. 
Perhatikan bahwa $x = 0 + x \in J$, namun $x \notin I$. Berarti $I \subsetneq J$. Karena $I$ adalah ideal maksimum, maka $J = R$. Karena $R$ gelanggang komutatif dengan unit maka $1 \in R = J$

Perhatikan bahwa
$$
1 \in J \quad\implies\quad 1 = i + rx \quad\implies\quad y = yi + yrx = yi +xyr
$$
untuk suatu $i \in I, r \in R$. Perhatikan bahwa $I$ adalah ideal dan $i, xy \in I$. Artinya $yi, xyr \in I$. Terbukti $y \in I$.

Maka, $I$ adalah ideal prima dari $R$.

***
## Definition Used 
 * [[Gelanggang Komutatif]]
 * [[Gelanggang Unit]]
 * [[Ideal Maksimal]]
 * [[Ideal Prima]]