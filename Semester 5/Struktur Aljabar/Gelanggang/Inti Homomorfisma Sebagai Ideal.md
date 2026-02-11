#Teorema 
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Maka $\mathrm{Inti}(f)$ membentuk ideal dari $A$

---
## Bukti

Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Sifat Homomorfisma Gelanggang]], $f(0_A) = 0_B$. Artinya $0_A \in \mathrm{Inti}(f)$. Berarti $\mathrm{Inti}(f) \neq \emptyset$.

Lebih lanjut, ambil $a_{1}, a_{2} \in \mathrm{Inti}(f)$. Artinya $f(a_{1}) = f(a_{2})= 0$. Perhatikan bahwa
$$
\begin{align*}
f(a_{1}-a_{2}) &= f(a_{1})-f(a_{2}) = 0 - 0 = 0\\
f(a_{1}a_{2}) &= f(a_{1})f(a_{2}) = 0 \cdot 0 = 0
\end{align*}
$$
Maka $a_{1}-a_{2}, a_{1}a_{2} \in \mathrm{Inti}(f)$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang]] maka $\mathrm{Inti}(f)$ membentuk subgelanggang dari $A$.

Lebih lanjut, ambil $r \in \mathrm{Inti}(f)$ dan $a \in A$. Perhatikan bahwa berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Sifat Gelanggang#^1e044a|Sifat Perkalian Nol Gelanggang]]
$$
\begin{align*}
f(ar) &= f(a) f(r) = f(a)\cdot 0 = 0 \\
f(ra) &= f(r) f(a) = 0 \cdot f(a) = 0
\end{align*}
$$
Maka $ra, ar \in \mathrm{Inti}(f)$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Ideal]], maka $\mathrm{Inti}(f)$ merupakan ideal dari $A$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Subgelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Homomorfisma (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Inti Homomorfisma Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]