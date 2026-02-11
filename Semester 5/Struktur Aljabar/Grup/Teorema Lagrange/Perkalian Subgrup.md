#Teorema 
Misalkan $G$ suatu grup dan $S \le G$. Untuk setiap $a \in G$ berlaku
$$
|aS| = |S|
$$
---
## Bukti
Definisikan $\phi : S \to aS$ dengan $\phi(s) = as$ untuk setiap $s \in S$. Jelas fungsi tersebut terdefinisi dengan baik. Akan ditunjukkan fungsi tersebut adalah fungsi bijektif.
### Surjektif
Ambil $g \in aS$. Pilih $x = a^{-1}g$. Perhatikan bahwa $\phi(x) = a a^{-1}g = g$. Terbukti$\phi$ bersifat surjektif.
### Injektif
Ambil $s_{1},s_{2}\in S$ sehingga $\phi(s_{1})=\phi(s_{2})$. Artinya $as_{1}=as_{2}$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Hukum Pembatalan Grup]], maka $s_{1}=s_{2}$.

Maka $\phi$ adalah fungsi bijektif. Terbukti bahwa $|aS| = |S|$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup]]
 * [[Buat Backup/Prerquested/Naive Set/Kardinalitas Himpunan]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Bijektif]]