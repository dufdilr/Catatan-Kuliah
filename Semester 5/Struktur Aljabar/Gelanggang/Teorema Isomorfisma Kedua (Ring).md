#Teorema

Misalkan $R$ adalah gelanggang, $S$ subgelanggang dari $R$, dan $I$ ideal dari $R$. Maka berlaku
$$
S/(S\cap I) \cong (S+I)/I
$$

---
## Bukti
Berdasarkan sifat ideal dan subgelanggang, diketahui $S \cap I$ ideal dari $S$ dan $I$ ideal dari $S+I$. Maka $S/(S\cap I)$ dan $(S+I)/I$ terdefinisi dengan baik sebagai [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]].

Lebih lanjut, tinjau $\phi: S \to (S+I)/I$ dengan $\phi(s) = s + I$ untuk setiap $s \in S$. Karena $0 \in I$ maka jelas $s = s+0 \in S+I$. Artinya $\phi$ terdefinisi dengan baik.

Ambil $s_{1}, s_{2} \in S$. Perhatikan bahwa
$$
\begin{align*}
\phi(s_{1} + s_{2}) &= (s_{1} + s_{2}) + I = (s_{1} + I) + (s_{2} + I) = \phi(s_{1}) + \phi(s_{2}) \\
\phi(s_{1}s_{2}) &= (s_{1}s_{2}) + I = (s_{1} + I)(s_{2} + I) = \phi(s_{1})\phi(s_{2})
\end{align*}
$$
Maka $\phi$ adalah homomorfisma gelanggang.

Lebih lanjut, ambil elemen sebarang $y \in (S+I)/I$. Elemen $y$ dapat ditulis sebagai $(s+i) + I$ dengan $s \in S$ dan $i \in I$.
Perhatikan bahwa $i \in I$ artinya $(s+i) + I = s + I$. Tinjau $s \in S$.
$$
\phi(s) = s + I = (s+i) + I = y
$$
Maka $\phi$ bersifat surjektif. Akibatnya $\mathrm{Im}(\phi) = (S+I)/I$.

Perhatikan kernel dari $\phi$:
$$
\begin{align*}
s \in \mathrm{Inti}(\phi) &\iff \phi(s) = 0 + I \\
&\iff s + I = I \\
&\iff s \in I \\
&\iff s \in S \cap I \quad (\text{karena } s \in S)
\end{align*}
$$
Terbukti $\mathrm{Inti}(\phi) = S \cap I$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Teorema Isomorfisma Pertama (Ring)]] maka
$$
S/(S\cap I) \cong (S+I)/I
$$
***
## Definition Used
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Isomorfisma (Ring)]]