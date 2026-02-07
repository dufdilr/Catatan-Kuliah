#Teorema

Misalkan $A$ adalah grup dan $B \le A$ dan $N \unlhd A$. Maka berlaku
$$
B/(B \cap N)  \cong BN/N
$$

---
## Bukti
Berdasarkan [[Subgrup Normal dari Subgrup|teorema]], maka $B\cap N\unlhd B$ dan $BN \unlhd N$. Maka $B/(B \cap N)$ dan $BN/N$ terdefinisi dengan baik sebagai [[Grup Hasil Bagi]].

Lebih lanjut, tinjau $\phi:B \to BN/N$ dengan $\phi(b) = bN$ untuk setiap $b \in B$. Karena $e \in N$ maka jelas $b = be \in BN$. Artinya $\phi$ terdefinisi dengan baik.

Ambil $b_{1}, b_{2} \in B$. Perhatikan bahwa
$$
\phi(b_{1}b_{2}) = (b_{1}b_{2})N = b_{1}N b_{2}N = \phi(b_{1}) \phi(b_{2})
$$
Maka $\phi$ adalah homomorfisma.

Lebih lanjut, ambil $bnN \in BN/N$. Perhatikan bahwa $nN = N$ artinya $bnN = bN$. Tinjau $b \in B$.
$$
\phi(b) = bN = bnN
$$
Maka $\phi$ bersifat surjektif. Akibatnya $\phi(B) = BN/N$.

Perhatikan bahwa
$$
\begin{align*}
\phi(b) = N &\ \iff bN = N \\
&\ \iff b\in N \\
&\ \iff b \in B\cap N
\end{align*}
$$
Terbukti $\mathrm{Inti}(\phi) = B\cap N$. Berdasarkan [[Teorema Isomorfisma Pertama (Grup)]] maka
$$
B/(B \cap N)  \cong BN/N
$$
***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]
 * [[Grup Hasil Bagi]]
 * [[Isomorfisma (Grup)]]