#Definisi #Teorema 

Misalkan $G$ grup dan $N \unlhd G$, maka $G/N$ dilengkapi dengan operasi
$$
aN \cdot bN  = (a\cdot b)N
$$
membentuk suatu grup.

---
## Bukti
### Well-Defined Operasi
Berdasarkan [[Karakterisasi Subgrup Normal]], $bN = Nb$. Artinya, untuk setiap $n_{1} \in N$, terdapat $n_{3} \in N$ sehingga $n_{1}b = bn_{3}$. Perhatikan bahwa
$$
\begin{align*}
x \in aN\cdot bN &\ \iff x = an_{1}bn_{2}, \ \exists n_{1}, n_{2} \in N \\
&\ \iff x = abn_{3}n_{2}, \ \exists n_{3}, n_{2} \in N \\ 
&\ \iff x \in (ab)N
\end{align*}
$$
Terbukti operasi tersebut well-defined.

### Asosiatif
Ambil $aN, bN, cN \in G/N$. Perhatikan bahwa
$$
\begin{align*}
(aN\cdot bN)\cdot cN &= (ab)N \cdot cN = ((ab)c)N \\
&= (a(bc))N = aN \cdot (bc)N \\
&= aN \cdot \left( bN \cdot cN \right) 
\end{align*}
$$
Terbukti operasi tersebut bersifat asosiatif.

### Identitas
Tinjau $N = eN \in G/N$. Ambil $aN \in G/N$. Perhatikan bahwa
$$
\begin{align*}
aN \cdot eN &= (ae)N = aN \\
eN \cdot aN &= (ea)N = aN
\end{align*}
$$
Terbukti $N$ adalah identitas di $G/N$.

### Inverse
Ambil $aN \in G/N$. Tinjau $a^{-1}N \in G/N$. Perhatikan bahwa
$$
\begin{align*}
aN \cdot a^{-1}N &= (aa^{-1})N = eN = N \\
a^{-1}N \cdot aN &= (a^{-1}a)N = eN = N
\end{align*}
$$
Terbukti setiap unsur di $N$ memiliki inverse.


Per definisi, terbukti $G/N$ membentuk grup dengan operasi yang telah didefinisikan di atas.
***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]
 * [[Himpunan Hasil Bagi]]