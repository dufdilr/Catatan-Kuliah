#Teorema 

Misalkan $A$ adalah grup. Himpunan $\mathrm{Inn}(A)$ dilengkapi dengan operasi komposisi membentuk **Subgrup Normal** dari $\text{Aut}\left({A}\right)$. Dengan kata lain
$$
\mathrm{Inn}(A) \unlhd \text{Aut}\left({A}\right)
$$
---
## Bukti
### Well-Defined
Ambil $f_a, f_b \in \mathrm{Inn}(A)$. Ambil $x \in A$. Perhatikan bahwa
$$
f_b \circ f_a (x) = f_b(f_a(x)) = f_b(axa^{-1}) = baxa^{-1}b^{-1} = (ba)x(ba)^{-1} = f_{ba}(x)
$$
Maka komposisi terdefinisi dengan baik di $\mathrm{Inn}(A)$.

### Asosiatif
Jelas berdasarkan [[Buat Backup/Prerquested/Relasi dan Fungsi/Komposisi Asosiatif]].
### Identitas
Jelas $i_A(x) = x = exe^{-1} f_e(x)$. Artinya $i_A \in \mathrm{Inn}(A)$. Lebih lanjut, telah ditunjukkan $i_A$ identitas di $\text{Aut}\left({A}\right)$ maka $i_A$ juga identitas di $\mathrm{Inn}(A)$
### Inverse
Ambil $f_a \in \mathrm{Inn}(A)$. Tinjau $f_{a^{-1}} \in \mathrm{Inn}(A)$. Ambil $x \in A$. Perhatikan bahwa
$$
f_a \circ f_{a^{-1}} = f_a(f_{a^{-1}}(x)) = aa^{-1}xaa^{-1} = x = i_A(x)
$$
$$
f_{a^{-1}} \circ f_a = f_{a^{-1}}(f_a(x)) = a^{-1}axa^{-1}a = x = i_A(x)
$$
Maka setiap unsur di $\mathrm{Inn}(A)$ memiliki invers di $\mathrm{Inn}(A)$.

### Sifat Normal
Ambil $f_a \in \mathrm{Inn}(A)$ dan $g \in \text{Aut}\left({A}\right)$. Ambil $x \in A$. Perhatikan bahwa
$$
g\circ f_a\circ g^{-1}(x) = g \circ f_a(g^{-1}(x)) = g(a \cdot g^{-1}(x) \cdot a^{-1}) = g(a) x g(a^{-1}) = (g(a)) x (g(a))^{-1} = f_{g(a)} (x)
$$
Maka $g\circ f_a \circ g^{-1} \in \mathrm{Inn}(A)$. 

Terbukti $\mathrm{Inn}(A)$ merupakan subgrup normal dari $\text{Aut}\left({A}\right)$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Grup Automorfisma]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inner Automorfisma]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal]]