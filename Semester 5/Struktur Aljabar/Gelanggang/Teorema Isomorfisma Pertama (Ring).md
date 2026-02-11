#Teorema 

Misalkan $f:A \to B$ adalah homomorfisma maka
$$
A/\mathrm{Inti}(f) \cong f(A)
$$
---
## Bukti

Tulis $\mathrm{Inti}(f) = C$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Inti Homomorfisma Sebagai Ideal|teorema]], maka $C$ membentuk ideal dari $A$. Artinya, $A/C$ terdefinisi dengan baik sebagai [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]. Tinjau pemetaan
$$
\phi:A/C \to f(A)
$$
dengan $\phi(aC) = f(a)$. Akan ditunjukkan $\phi$ adalah isomorfisma.

Ambil $a_{1}+C, a_{2}+C \in A/C$. Perhatikan bahwa
$$
\begin{align*}
\phi((a_{1}+C) +( a_{2}+C)) &= \phi((a_{1}+a_{2})+C) = f(a_{1}+a_{2}) = f(a_{1}) + f(a_{2}) \\
&= \phi(a_{1}+C) + \phi(a_{2}+C)\\
\phi((a_{1}+C) \cdot (a_{2}+C)) &= \phi((a_{1}a_{2})+C) = f(a_{1}a_{2}) = f(a_{1})\cdot f(a_{2}) \\
&= \phi(a_{1}+C) \cdot \phi(a_{2}+C)
\end{align*}
$$
Maka $\phi$ adalah homomorfisma.

Lebih lanjut, ambil $a_{1}C, a_{2}C \in A/C$ sedemikian sehingga $\phi(a_{1}+C) = \phi(a_{2}+C)$. Artinya
$$
f(a_{1}) = f(a_{2}) \quad\implies\quad f(a_{1})-(f(a_{2}))=f(a_{1}-a_{2}) = 0_B \quad\implies\quad a_{1}-a_{2} \in \mathrm{Inti}(f) = C
$$
Karena $a_{1}-a_{2} \in C$, maka $a_{1}+C = a_{2}+C$. Terbukti $\phi$ bersifat injektif.

Lebih lanjut, ambil $b \in f(A)$. Per definisi maka terdapat $a \in A$ sehingga $f(a) = b$. Perhatikan bahwa
$$
\phi(a+C) = f(a) = b
$$
Maka $\phi$ bersifat surjektif.

Karena $\phi$ adalah homomorfisma yang injektif dan surjektif maka $\phi$ adalah isomorfisma gelanggang. Terbukti bahwa
$$
A/\mathrm{Inti}(f) \cong f(A)
$$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Homomorfisma (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Isomorfisma (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Inti Homomorfisma Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Koset Gelanggang]]