#Teorema 

Misalkan $R$ adalah suatu gelanggang. Maka $Z(R)$ membentuk subgelanggang dari $R$.

---
## Bukti
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Sifat Gelanggang]], $0\cdot r = r\cdot 0 = 0$. Maka $0 \in Z(R)$, artinya $Z(R) \neq \emptyset$.

Ambil $a_{1}, a_{2} \in Z(R)$. Ambil $r \in R$. Perhatikan bahwa
$$
\begin{align*}
(a_{1}-a_{2})r &= a_{1}r - a_{2}r= ra_{1}-ra_{2} \\
&= r(a_{1}a_{2}) \\
(a_{1}a_{2})r &= a_{1}(a_{2}r) = a_{1}(ra_{2}) = (a_{1}r)a_{2} = (ra_{1})a_{2} \\
&= r(a_{1}a_{2})
\end{align*}
$$
Maka $a_{1}-a_{2}, a_{1}a_{2} \in Z(R)$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang]] maka $Z(R)$ adalah subgelanggang dari $R$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Subgelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Pusat Gelanggang]]