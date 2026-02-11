#Teorema 

Misalkan $A$ suatu grup dengan elemen identitas $e_A$ dan $N \unlhd A$. Maka, terdapat grup $B$ dengan identitas $e_B$ dan homomorfisma $f:A \to B$ sedemikian sehingga
$$
\text{Inti} f = N
$$

---
## Bukti
Karena $N \unlhd A$ maka $A/N$ membentuk [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Grup Hasil Bagi]]. Tinjau pemetaan $f:A \to A/N$ dengan
$$
f(a) = aN
$$
untuk setiap $a \in A$. Akan ditunjukkan $f$ homomorfisma. Ambil $a_{1}, a_{2} \in A$ perhatikan bahwa
$$
f(a_{1}a_{2}) = (a_{1}a_{2})N = a_{1}N \cdot a_{2}N = f(a_{1})f(a_{2})
$$
Maka $f$ adalah homomorfisma. Lebih lanjut akan ditunjukkan $N = \text{Inti} f$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Kesamaan Koset]] berlaku
$$
\begin{align*}
x \in N & \ \iff f(x) = xN = N = eN
\end{align*}
$$
Terbukti $N = \text{Inti} f$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma (Grup)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inti Homomorfisma Grup]]