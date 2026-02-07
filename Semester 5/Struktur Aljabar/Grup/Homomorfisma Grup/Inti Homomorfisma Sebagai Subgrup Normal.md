#Teorema 

Misalkan $A, B$ adalah grup dengan identitas $e_A$ dan $e_B$ berturut-turut serta $f:A \to B$ adalah homomorfisma grup. Maka $\text{Inti} f$ membentuk subgrup normal dari $A$.

---
## Bukti

Jelas $f(e_A) = e_B$. Artinya $\text{Inti} f \neq \emptyset$. Lebih lanjut, ambil $a_{1}, a_{2} \in \text{Inti} f$. Artinya $f(a_{1}) = f(a_{2}) = e_B$. Lebih lanjut, berdasarkan [[Sifat Homomorfisma Grup]] berlaku
$$
f(a_{1}a_{2}^{-1}) = f(a_{1})f(a_{2})^{-1} = e_B \cdot e_B^{-1} = e_B
$$
Maka $a_{1}a_{2}^{-1} \in \text{Inti} f$. Maka $\text{Inti} f$ membentuk subgrup dari $A$. 

Lebih lanjut, ambil $a \in \text{Inti} f$ dan $g \in A$. Perhatikan bahwa
$$
f(gag^{-1}) = f(g)f(a)f(g^{-1}) = f(g) \cdot e_B \cdot(f(g^{-1})) = e_B
$$
Artinya $gag^{-1} \in A$. Berdasarkan definisi [[Subgrup Normal]] maka $\text{Inti} f$ adalah subgrup normal dari $A$.

***
## Definition Used 
 * [[Grup]]
 * [[Homomorfisma (Grup)]]
 * [[Inti Homomorfisma Grup]]
 * [[Subgrup Normal]]