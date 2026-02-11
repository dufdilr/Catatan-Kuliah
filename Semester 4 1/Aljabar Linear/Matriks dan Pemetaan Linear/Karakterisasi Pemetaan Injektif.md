#Teorema 

Misalkan $V, W$ ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Pemetaan $T$ bersifat **injektif** jika dan hanya jika $\text{Ker}\left({T}\right) = \{ \mathbf{0_V} \}$

---
## Bukti
### $\Rightarrow$
Misalkan $T$ injektif. Berdasarkan [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear Vektor Nol|teorema]], $T(\mathbf{0_V}) = \mathbf{0_W}$. Lebih lanjut, ambil $v \in \text{Ker}\left({T}\right)$. Artinya, $T(v) = \mathbf{0_W}$. Karena $T$ injektif maka $v =\mathbf{0_V}$. Terbukti $\text{Ker}\left({T}\right)= \mathbf{0_V}$.

### $\Leftarrow$
Misalkan $\text{Ker}\left({T}\right) = \{ \mathbf{0_V} \}$. Andaikan $T$ tidak injektif. Maka, terdapat $u, v \in V$ dengan $u \neq v$ sehingga $T(u) = T(v)$. Perhatikan bahwa $u - v \neq \mathbf{0_V}$ namun
$$
T(u-v) = T(u) - T(v) = \mathbf{0_W}
$$
Maka $u-v \in \text{Ker}\left({T}\right)$, kontradiksi dengan hipotesa awal bahwa $\text{Ker}\left({T}\right) = \{ \mathbf{0_V} \}$. Artinya pengandaian salah. Terbukti $T$ injektif.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range dan Kernel Pemetaan Linear]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Injektif]]