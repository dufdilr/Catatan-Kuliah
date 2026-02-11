#Teorema 

Untuk setiap bilangan asli $a, b, m \in \mathbb{Z}$ berlaku
$$
FPB(a, b) = FPB(a, am + b)
$$

## Bukti

Misal $c = (a, am + b)$. Akan ditunjukkan $c = (a, b)$.

Karena $c = (a, am + b)$ maka $c \mid a$ dan $c \mid am + b$ sehingga $c \mid (am - (am + b)) = b$. Maka $c | a$ dan $c | b$.

Lebih lanjut, Misal $d$ suatu bilangan bulat sehingga $d \mid b$ dan $d \mid r$. Maka, $d \mid (bq + r) = a$    Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout|Identitas Bezout]], terdapat $s, t \in \mathbb{Z}$ sehingga $c = sa + tb$. Karena $d \mid a$ dan $d \mid b$ maka $d \mid (sa + tb) = c$.
Artinya, jika $d \mid b$ dan $d \mid r$ maka $d \mid c$.

Terbukti $FPB(a, b) = c = FPB(a, am + b)$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]