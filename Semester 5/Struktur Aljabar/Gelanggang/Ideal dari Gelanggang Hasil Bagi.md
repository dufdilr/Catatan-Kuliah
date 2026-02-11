#Teorema 
Misalkan $R$ adalah gelanggang dan $I$ ideal dari $R$ maka setiap ideal dari $R/I$ adalah $J/I$ dengan $J$ adalah ideal dari $R$ memenuhi $I \subseteq J \subseteq R$.

---
## Bukti
Misalkan $J$ ideal dari $R$ dengan $I \subseteq J \subseteq R$. Akan ditunjukkan $J/I$ ideal dari $R/I$.

Ambil $j_{1}+I, j_{2}+I \in J/I$ dan $r+I \in R/I$. Perhatikan bahwa
$$
\begin{align*}
(j_{1}+I) - (j_{2}+I) &= (j_{1}-j_{2}) + I \\
(r+I) \cdot (j_{1}+I) &= (rj_{1}) + I
\end{align*}
$$
Karena $J$ ideal dari $R$ maka $j_{1}-j_{2}, rj_{1} \in J$. Akibatnya, $(j_{1}-j_{2}) + I, (rj_{1}) + I \in J/I$. Maka $J/I$ ideal dari $R/I$.

Lebih lanjut, misalkan $\mathcal{A}$ ideal dari $R/I$. Tulis $J = \{ j \in R \ \mid \ j+I \in \mathcal{A} \}$. Akan ditunjukkan $J$ ideal dari $R$.

Ambil $x, y \in J$ dan $r \in R$. Perhatikan bahwa $x+I, y+I \in \mathcal{A} \subseteq R/I$ artinya
$$
\begin{align*}
(x+I) - (y+I) &= (x-y) + I \in \mathcal{A} = J/I \\
&\Rightarrow x-y \in J \\
(r+I)(x+I) &= (rx) + I \in \mathcal{A} = J/I \\
& \Rightarrow rx \in J
\end{align*}
$$
Jelas bahwa $I \subseteq J$ karena $0+I \in \mathcal{A}$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Ideal]] maka $J$ ideal dari $R$. Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]