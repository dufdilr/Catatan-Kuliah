#Teorema 

Misalkan $G$ suatu grup dan $A \le G$ adalah satu-satunya subgrup dari $G$ berorde $n$. Maka
$$
A \unlhd G
$$
---
## Bukti
Ambil $g \in G$. Berdasarkan [[Subgrup Perkalian Unsur dan Subgrup|teorema]], maka $gAg^{-1}$ membentuk subgrup dari $G$. Akan ditunjukkan $\text{ord}(gAg^{-1}) = \text{ord}(A)$. Tinjau pemetaan $\phi: A \to gAg^{-1}$ dengan
$$
\phi(a) = gag^{-1}
$$
untuk setiap $a \in A$. Akan ditunjukkan $\phi$ adalah bijeksi.
* **Surjektif**:
	Ambil $y \in gAg^{-1}$. Artinya $y = gag^{-1}$ untuk suatu $a \in A$. Perhatikan bahwa
	$$
\phi(a) = gag^{-1} = y
$$
Maka $\phi$ bersifat surjektif
* **Injektif**
Ambil $a_{1},a_{2} \in A$ sehingga $\phi(a_{1}) = \phi(a_{2})$. Artinya, berdasarkan [[Hukum Pembatalan Grup]],
$$
\begin{align*}
ga_{1}g^{-1}&=ga_{2}g^{-1} \\
a_{2} &= a_{2}
\end{align*}
$$
Maka $\phi$ bersifat injektif


Karena $\phi$ bersifat injektif dan surjektif maka $\phi$ adalah bijeksi. Akibatnya
$$
\text{ord}(A) = \text{ord}(gAg^{-1}) \quad\implies\quad A = gAg^{-1}
$$
Berdasarkan [[Karakterisasi Subgrup Normal]], maka $A$ adalah subgrup normal dari $G$.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup]]
 * [[Orde Grup]]
 * [[Subgrup Normal]]