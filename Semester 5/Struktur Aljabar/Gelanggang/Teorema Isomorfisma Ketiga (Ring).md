#Teorema 

Misalkan $R$ adalah gelanggang, $I, J$ adalah ideal dari $R$ sehingga $I \subseteq J \subseteq R$. Maka berlaku
$$
(R/I)/(J/I) \cong R/J
$$

---
## Bukti
Jelas $R/I, J/I$ dan $R/J$ terdefinisi dengan baik. Lebih lanjut, tinjau $\phi: R/I \to R/J$ dengan
$$
\phi(r+I) = r+J
$$
untuk setiap $r \in R$.

Ambil $r_{1}+I, r_{2}+I \in R/I$ dengan $r_{1}, r_{2} \in R$. Perhatikan bahwa
$$
\begin{align*}
\phi((r_{1}+I) + (r_{2}+I)) &= \phi((r_{1}+r_{2}) + I) = (r_{1}+r_{2}) + J \\
&= (r_{1}+J) + (r_{2}+J) = \phi(r_{1}+I) + \phi(r_{2}+I) \\
\phi((r_{1}+I)(r_{2}+I)) &= \phi((r_{1}r_{2}) + I) = (r_{1}r_{2}) + J \\
&= (r_{1}+J)(r_{2}+J) = \phi(r_{1}+I)\phi(r_{2}+I)
\end{align*}
$$
Maka $\phi$ adalah homomorfisma.

Ambil $r+J \in R/J$ dengan $r \in R$. Tinjau $r+I$. Perhatikan bahwa
$$
\phi(r+I) = r+J
$$
Maka $\phi$ bersifat surjektif. Artinya $\phi(R/I) = R/J$.

Lebih lanjut, perhatikan bahwa
$$
\begin{align*}
r+I \in \mathrm{Inti}(\phi) &\ \iff \phi(r+I) = J \quad (\text{elemen nol di } R/J) \\
&\ \iff r+J = J \\
&\ \iff r \in J \\
&\ \iff r+I \in J/I
\end{align*}
$$
Maka $\mathrm{Inti}(\phi) = J/I$.

Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Teorema Isomorfisma Pertama (Ring)]] maka
$$
(R/I)/(J/I) \cong R/J
$$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Isomorfisma (Ring)]]