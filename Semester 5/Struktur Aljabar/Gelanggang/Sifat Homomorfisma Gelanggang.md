#Teorema 
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Maka berlaku
1. $f(0_A) = 0_B$
2. $f(A)$ membentuk subgelanggang dari $B$

---
## Bukti
### 1.
Pandang grup $(A, +), (B, +)$ dan $f:A \to B$ sebagai homomorfisma grup. Jelas berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Sifat Homomorfisma Grup#^5884b9|Sifat Homomorfisma Grup]].
### 2.
Pandang grup $(A, +), (B, +)$ dan $f:A \to B$ sebagai homomorfisma grup. Jelas berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Sifat Homomorfisma Grup#^5884b9|Sifat Homomorfisma Grup]], $(f(A),+)$ membentuk subgrup. Sifat komutatif penjumlahan diwariskan dari $(B, +)$.

Lebih lanjut, ambil $b_{1}, b_{2} \in f(A)$. Maka $b_{1} = f(a_{1})$ dan $b_{2} =f(a_{2})$ untuk $a_{1}, a_{2} \in A$. Perhatikan bahwa
$$
b_{1}b_{2} = f(a_{1})f(a_{2}) = f(a_{1}a_{2})
$$
Karena $A$ adalah gelanggang maka $a_{1}a_{2} \in A$. Artinya $b_{1}b_{2} \in f(A)$.

Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang]] maka $f(A)$ membentuk subgelanggang dari $B$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Homomorfisma (Ring)]]