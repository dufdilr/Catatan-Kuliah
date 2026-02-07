#Teorema
Misalkan $A$ suatu grup dan $C \unlhd B \unlhd A$. Maka berlaku
$$
(A/C)/(B/C) \cong A/B
$$
---
## Bukti
Jelas $A/C, B/C$ dan $A/B$ terdefinisi dengan baik. Lebih lanjut, tinjau $\phi:A/C \to A/B$ dengan
$$
\phi(aC) = aB
$$
untuk setiap $a\in A$. 

Ambil $a_{1}C, a_{2}C \in A/C$ dengan $a_{1}, a_{2} \in A$. Perhatikan bahwa
$$
\phi(a_{1}C \cdot a_{2}C) = \phi((a_{1}a_{2})C) = (a_{1}a_{2})B = a_{1}B \cdot a_{2}B = \phi(a_{1}C) \cdot \phi(a_{2}C)
$$
Maka $\phi$ adalah homomorfisma.

Ambil $aB \in A/B$ dengan $a \in A$. Tinjau $aC$. Perhatikan bahwa
$$
\phi(aC) = aB
$$
Maka $\phi$ bersifat surjektif. Artinya $\phi(A/C) = A/B$.

Lebih lanjut, perhatikan bahwa
$$
\begin{align*}
aC \in \mathrm{Inti}(\phi) &\ \iff \phi(aC) = B \\
&\ \iff aB = B \\
&\ \iff a \in B \\
&\ \iff aC \in B/C
\end{align*}
$$
Maka $\mathrm{Inti}(\phi) = B/C$.

Berdasarkan [[Teorema Isomorfisma Pertama (Grup)]] maka
$$
(A/C)/(B/C) \cong A/B
$$

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]
 * [[Grup Hasil Bagi]]
 * [[Isomorfisma (Grup)]]