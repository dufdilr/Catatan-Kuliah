#Teorema 
Misalkan $A, B, C$ grup serta $f:A \to B$ dan $g:B \to C$ keduanya adalah homomorfisma grup. Maka
$$
g\circ f : A \to C
$$
juga merupakan homomorfisma grup.

---
## Bukti
Ambil $a_{1},a_{2} \in A$. Perhatikan bahwa
$$
g\circ f(a_{1}a_{2}) = g \left( f(a_{1}a_{2}) \right)  = g(f(a_{1})f(a_{2})) = g(fa_{1}) g(f(a_{2})) = (g\circ f(a_{1})) \cdot (g\circ f(a_{2}))
$$
Maka $g \circ f$ adalah homomorfisma grup.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma (Grup)]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Komposisi Fungsi]]