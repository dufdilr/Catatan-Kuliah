#Teorema 
Misalkan $A, B$ grup dengan unsur identitas $e_A$ dan $e_B$ berturut-turut serta $f:A \to B$ adalah homomorfisma grup. Fungsi $f$ adalah homomorfisma injektif jika dan hanya jika
$$
\mathrm{Inti}(f) = \{ e_A \}
$$
---
## Bukti
### $\Rightarrow$
Misalkan $f$ adalah homomorfisma injektif. Berdasarkan [[Sifat Homomorfisma Grup]], maka $f(e_A) = e_B$. Karena $f$ injektif maka
$$
x \in \mathrm{Inti}(f) \iff f(x) = e_B \iff f(x) = f(e_A) \iff x = e_A
$$
Terbukti $\mathrm{Inti}(f) = \{ e_A \}$.

### $\Leftarrow$
Misalkan $\mathrm{Inti}(f) = \{ e_A \}$. Ambil $a_{1},a_{2}\in A$ dengan $f(a_{1}) = f(a_{2})$. Perhatikan bahwa
$$
f(a_{1}a_{2}^{-1}) = f(a_{1})f(a_{2}^{-1}) = f(a_{1}) (f(a_{1}))^{-1} = e_B
$$
Artinya $a_{1}a_{2}^{-1} \in \mathrm{Inti}(f) = \{ e_A \}$. Maka $a_{1}a_{2}^{-1}=e$ sehingga $a_{1} = a_{2}$. Terbukti $f$ adalah fungsi injektif.

***
## Definition Used 
 * [[Grup]]
 * [[Homomorfisma (Grup)]]
 * [[Fungsi Injektif]]
 * [[Inti Homomorfisma Grup]]