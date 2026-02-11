#Teorema 
Misalkan $A$ adalah gelanggang dan $B$ adalah subgelanggang dari $A$. Jika $I$ adalah ideal dari $A$ maka $(B \cap I)$ adalah ideal dari $B$. Lebih lanjut, $I$ juga ideal dari $I + B$.

---
## Bukti 1
Ambil $x, y \in (B\cap I)$ dan $r \in B$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Irisan Subgelanggang]] maka $B\cap I$ juga subgelanggang $A$, artinya $x - y \in (B\cap I)$. Lebih lanjut, perhatikan bahwa $x, r \in B$. Artinya $rx, xr \in B$. Karena $I$ ideal dan $x \in I$ maka $xr, rx \in I$. Artinya
$$
rx, xr \in B \cap I
$$
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Ideal]] maka $(B\cap I)$ adalah ideal dari $B$.

## Bukti 2
Jelas $i = i+0 \in I+B$ untuk setiap $i \in I$. Maka $I \subseteq I+B$. 

Ambil $x, y \in I$ dan $r \in I+B$. Maka $r = i+b$ untuk suatu $i\in I$ dan $b \in B$. Perhatikan bahwa jelas $x-y \in I$. Lebih lanjut, karena $I$ ideal maka $xr, rx \in I$. Terbukti $I$ juga ideal dari $I+B$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
