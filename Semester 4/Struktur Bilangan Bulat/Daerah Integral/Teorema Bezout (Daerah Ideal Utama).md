#Teorema 

Misalkan $D$ Daerah Ideal Utama, maka $\forall a, b \in D$ ada $d \in D$ secara unik (hingga sekawan) sehingga $d = (a, b)$ dan
$$d = sa + tb \quad \exists s, t \in D$$
Dengan kata lain jika $d = (a, b) = d'$ maka $d \sim d'$.

---

## Bukti

Ambil $a, b \in D$. Tulis $I = \langle a, b \rangle$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Terbangun|teorema]] maka $I$ ideal dari $D$. Karena $D$ Daerah Ideal Utama maka $I = \langle d \rangle$ untuk suatu $d \in I$. Akan ditunjukkan bahwa $d = (a, b)$.

1.  Karena $d \in I = \langle a, b \rangle$ maka $d = s_1a + t_1b \quad \exists s_1, t_1 \in D$.
2.  Jelas $a \in \langle a, b\rangle = \langle d \rangle$. Maka $a = dk \quad \exists k \in D$. Artinya $d \mid a$.
    Serupa, $b \in \langle a, b\rangle = \langle d \rangle$. Maka $b = dl \quad \exists l \in D$. Artinya $d \mid b$.
3.  Misalkan $c \mid a$ dan $c \mid b$, maka $c \mid (s_1a+t_1b) = d$

Maka terbukti untuk setiap $a, b \in D$ memiliki Pembagi Persekutuan Terbesar yakni $d$.

Lebih lanjut akan ditunjukkan ketunggalan. Misalkan $d = (a, b) = d'$. Berdasarkan definisi, maka $d \mid a, \ d \mid b, \ d' \mid a$ dan $d' \mid b$. Karena $d = (a, b)$ maka $d \mid d'$. Berarti $d' = du$ untuk suatu $u \in D$. Serupa, karena $d' = (a, b)$ maka $d' \mid d$. Berarti $d = d'v = duv$. Perhatikan bahwa
$$
d - duv = d(1 - uv) = 0
$$
maka $uv = 1$. Berarti $u$ adalah unsur unit. Terbukti $d \sim d'$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Terbangun]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Faktor Persekutuan Terbesar (Daerah Integral)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Unit (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Sekawan (Ring)]]