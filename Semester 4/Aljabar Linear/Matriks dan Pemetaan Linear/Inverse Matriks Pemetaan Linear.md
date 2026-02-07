#Teorema 
Misalkan $\mathbf{A} \in M_n(\mathbb{F})$ dan $T: \mathbb{F}^n \to \mathbb{F}^n$ dengan $T(u) = \mathbf{A}u$ untuk setiap $u \in \mathbb{F}^n$. Berlaku
$$
\mathbf{A} \text{ invertibel } \iff T \text{ invertibel }
$$
Lebih lanjut, jika $\mathbf{A}$ invertibel maka $T^{-1}(u) = \mathbf{A}^{-1}u$ untuk setiap $u \in \mathbb{F}^n$.

---
## Bukti
### $\Rightarrow$
Misalkan $\mathbf{A}$ invertibel. Definisikan $T^{-1}(u) = \mathbf{A}^{-1}u$. Perhatikan bahwa $T^{-1}$ terdefinisi dengan baik, artinya $T$ invertibel.
### $\Leftarrow$
Misalkan $T$ invertibel. Tinjau $\mathbf{A_{T^{-1}}}$. Berdasarkan [[Matriks Representasi Komposisi L(Fn, Fm)|Teorema Perkalian Matriks]] maka
$$
\mathbf{A}\mathbf{A_{T^{-1}}} = \mathbf{A_T}\mathbf{A_{T^{-1}}} = \mathbf{I_n}
$$
Berdasarkan [[Sifat Inverse Matriks#^24898b|Ketunggalan Inverse Matriks]] maka terbukti $\mathbf{A}^{-1} = \mathbf{A_{T^{-1}}}$.

***
## Definition Used 
 * [[Matriks]]
 * [[Pemetaan Linear]]
 * [[Inverse Matriks]]
 * [[Invers Pemetaan Linear]]
 * [[Operasi Matriks]]
