#Teorema 
Misalkan $R$ adalah gelanggang komutatif unit dan $I$ adalah ideal dari $R$. Maka berlaku
$$
R/I \text{ lapangan} \quad \iff \quad I \text{ ideal maksimal}
$$

---
## Bukti

### $\Rightarrow$
Misalkan $R/I$ adalah lapangan. Tinjau ideal $J \supsetneq I$. Ambil $x \in J$ namun $x \not\in I$. Tinjau $x + I \in R/I$. Karena $x \notin I$ maka $x+I \neq I$, karena $R/I$ adalah lapangan, maka terdapat $y+I \in R/I$ sehingga $xy + I = 1+ I$. Berdasarkan [[Kesamaan Koset]] maka $xy = 1 + i$, untuk suatu $i \in I$. 

Perhatikan bahwa $x \in J$ dan $i \in I \subseteq J$. Karena $J$ ideal maka $xy, i \in J$. Akibatnya
$$
1 = xy - i \in J
$$
Berdasarkan [[Ideal dengan Unit|teorema]], maka $J = R$. Terbukti $I$ adalah ideal maksimal.

### $\Leftarrow$
Misalkan $I$ adalah ideal maksimal. Akan ditunjukkan $R/I$ adalah lapangan. Ambil $x+I \in R/I$ dengan $x+I \neq I$. Artinya $x \notin I$.

Tinjau $J = I + \left< x \right>$. Perhatikan bahwa $\left< x \right>$ adalah [[Ideal Utama]] di $R$. Berdasarkan [[Jumlah Ideal]] maka $J$ juga ideal di $R$. Lebih lanjut, perhatikan bahwa $x = 0 + x \in I + \left< x \right> = J$. Artinya
$$
I \subsetneq J
$$
Karena $I$ adalah ideal maksimal maka $J = R$. Perhatikan bahwa $1 \in J$. Artinya
$$
1 = i + rx \quad\implies\quad rx = 1 - i
$$
untuk suatu $i \in I$ dan $r \in R$. Perhatikan bahwa $rx = 1 - i$ maka $rx \in 1 + I$. Berdasarkan [[Kesamaan Koset]] maka
$$
rx + I = (r + I) \cdot (x + I) = 1 + I
$$
Maka $r+I$ adalah inverse perkalian dari $x+I$. Maka, dapat disimpulkan $R/I$ adalah lapangan.

***
## Definition Used 
 * [[Gelanggang Komutatif]]
 * [[Gelanggang Unit]]
 * [[Ideal (Ring)]]
 * [[Ideal Maksimal]]
 * [[Gelanggang Hasil Bagi]]
 * [[Lapangan]]