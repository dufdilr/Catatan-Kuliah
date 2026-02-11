#Definisi #Teorema 

Misalkan $x \in \mathbb{R}$. Definisikan
$$
\begin{align*}
\lfloor x \rfloor  &:= \max \{ n \in \mathbb{Z} \ | \ n \le x \} \\
\lceil x \rceil  & := \min \{ n \in \mathbb{Z} \ | \ n \ge x \}
\end{align*}
$$
Fungsi tersebut terdefinisi dengan baik.

---
## Bukti

### Eksistensi Floor
Tinjau himpunan 
$$
S := \{ n \in \mathbb{Z} \ | \ n \le x \}
$$
Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Sifat Archimedean]], terdapat bilangan bulat $k$ sedemikian sehingga $k < x$. Karena $k \in \mathbb{Z}$ dan $k \le x$, maka $k \in S$. Jadi $S \neq \emptyset$.

Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Sifat Archimedean]], terdapat bilangan bulat $M$ sedemikian sehingga $M > x$.
Untuk setiap $n \in S$, berlaku $n \le x < M$.
Karena $S \subseteq \mathbb{Z}$ dan $S$ terbatas di atas maka berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Kelengkapan Bilangan Bulat]] $S$ memiliki unsur maksimum. Karena unsur maksimum pada himpunan terurut selalu tunggal, maka nilai $\lfloor x \rfloor$ ada dan tunggal.

### Eksistensi Ceiling
Tinjau himpunan 
$$
T := \{ n \in \mathbb{Z} \ | \ n \ge x \}
$$
Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Sifat Archimedean]], terdapat bilangan bulat $N$ sedemikian sehingga $N > x$. Karena $N \in \mathbb{Z}$ dan $N \ge x$, maka $N \in T$. Jadi $T \neq \emptyset$.

Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Sifat Archimedean]], terdapat bilangan bulat $j$ sedemikian sehingga $j < x$.
Untuk setiap $n \in T$, berlaku $n \ge x > j$.
Karena $T \subseteq \mathbb{Z}$ dan $T$ terbatas di bawah maka berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Kelengkapan Bilangan Bulat]], $T$ memiliki unsur minimum. Karena unsur minimum pada himpunan terurut selalu tunggal, maka nilai $\lceil x \rceil$ ada dan tunggal.

Terbukti.

***
## Definition Used
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Bilangan Bulat]]
* [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]]
* [[Buat Backup/Prerquested/Naive Set/Himpunan]]