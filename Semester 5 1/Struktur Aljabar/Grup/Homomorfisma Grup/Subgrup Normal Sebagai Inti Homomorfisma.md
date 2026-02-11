#Teorema 

Misalkan $A$ suatu grup dengan elemen identitas $e_A$ dan $N \unlhd A$. Maka, terdapat grup $B$ dengan identitas $e_B$ dan homomorfisma $f:A \to B$ sedemikian sehingga
$$
\text{Inti} f = N
$$

---
## Bukti
Karena $N \unlhd A$ maka $A/N$ membentuk [[Grup Hasil Bagi]]. Tinjau pemetaan $f:A \to A/N$ dengan
$$
f(a) = aN
$$
untuk setiap $a \in A$. Akan ditunjukkan $f$ homomorfisma. Ambil $a_{1}, a_{2} \in A$ perhatikan bahwa
$$
f(a_{1}a_{2}) = (a_{1}a_{2})N = a_{1}N \cdot a_{2}N = f(a_{1})f(a_{2})
$$
Maka $f$ adalah homomorfisma. Lebih lanjut akan ditunjukkan $N = \text{Inti} f$. Berdasarkan [[Kesamaan Koset]] berlaku
$$
\begin{align*}
x \in N & \ \iff f(x) = xN = N = eN
\end{align*}
$$
Terbukti $N = \text{Inti} f$.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]
 * [[Homomorfisma (Grup)]]
 * [[Inti Homomorfisma Grup]]