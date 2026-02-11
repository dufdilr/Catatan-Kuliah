#Teorema
Misalkan $G$ suatu dan subhimpunan tak-kosong $A \subseteq G$. $A$ adalah **[[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup|subgrup]]** dari $G$ jika dan hanya jika untuk setiap $a, b \in A$ berlaku

$$ab^{-1} \in A$$  
***
## Bukti

Misalkan $(G, *)$ grup dengan unsur identitas $e$.
### Asosiatif
Jelas karena setiap anggota $A$ adalah anggota $G$ dan $*$ asosiatif di $G$. Maka $*$ juga asosiatif di $A$.
### Identitas

Karena $A$ tak-kosong, pilih sembarang $a \in A$. Perhatikan bahwa
$$
e = a * (a^{-1})
$$
Karena $a \in A$, berdasarkan premis didapatkan $e \in A$. Terbukti $A$ mengandung $e$ dan untuk setiap $g \in A$ berlaku
$$
e*g = g*e = g
$$
### Invers
Ambil sembarang $a \in A$. Telah ditunjukkan $e \in A$. Berdasarkan premis
$$
a^{-1} = e * a^{-1} \in A
$$
Terbukti untuk setiap $a \in A$ terdapat $a^{-1} \in A$.
### Ketertutupan
Ambil sembarang $a, b \in A$. Telah ditunjukkan $b^{-1} \in A$. Berdasarkan premis
$$
a * b = a * (b^{-1})^{-1} \in A
$$

Terbukti $(A, *)$ benar membentuk sistem.
Karena memenuhi syarat grup maka terbukti $A$ adalah subgrup dari $G$.
***
## Definition Used
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup]]