#Teorema 

Misalkan $a, b \in \mathbb{N}$ dan $d \in \mathbb{N}$ maka berlaku
$$
d = (a, b) \iff \left(\frac{a}{d}, \frac{b}{d}\right) = 1
$$
## Bukti
### $\Rightarrow$
Per definisi, $d \mid a$ dan $d \mid b$. Tulis $a = dm$ dan $b = dn$ dengan $m, n \in \mathbb{N}$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]] maka terdapat $p, q \in \mathbb{Z}$ sehingga
$$
ap + bq = d \quad \Rightarrow \quad dmp + dnq = d \quad \Rightarrow \quad mp + nq = 1
$$
Perhatikan bahwa $mp + nq =1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Relatif Prima]], maka $(m, n) = 1$. Terbukti bahwa
$$
\left(\frac{a}{d}, \frac{b}{d}\right) = 1
$$
### $\Leftarrow$
Agar terdefinisi $\frac{a}{d}$ dan $\frac{b}{d}$ adalah bilangan bulat, artinya $d \mid a$ dan $d \mid b$. Lebih lanjut, misalkan $c \mid a$ dan $c \mid b$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]] maka terdapat $p, q \in \mathbb{Z}$ sedemikian sehingga
$$
\begin{align*}
\frac{a}{d}p + \frac{b}{d}q &= 1 \\
ap + bq &= d
\end{align*}
$$
Karena $c \mid a$ dan $c \mid b$ [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|maka]] $c \mid ap + bq = d$. Per definisi, terbukti $d = (a, b)$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Relatif Prima]]