#Teorema 

Misalkan $G$ adalah grup dan $A \subseteq G$. Untuk setiap $g \in G$, 
$$
gAg^{-1} := \{ gag^{-1} \ \mid \ a \in A \}
$$
membentuk subgrup dari $G$.

---
## Bukti
Jelas $e = geg^{-1} \in gAg ^{-1}$, maka $A \neq \emptyset$. Ambil $x, y \in gAg^{-1}$. Maka $x=ga_{1}g^{-1},y= ga_{2}g^{-1}$ untuk suatu $a_{1}, a_{2}\in A$. Perhatikan bahwa
$$
\begin{align*}
x-y &= ga_{1}g^{-1}-ga_{2}g^{-1} =g(a_{1}-a_{2})g^{-1} \\
xy &= ga_{1}g^{-1} ga_{2}g^{-1} = g(a_{1}a_{2})g^{-1}
\end{align*}
$$
Karena $A$ adalah subgrup dari $G$ maka $a_{1}-a_{2},a_{1}a_{2} \in A$. Akibatnya $x-y, xy \in gAg^{-1}$. Berdasarkan [[Karakterisasi Subgrup]] maka $gAg^{-1}$ membentuk subgrup dari $G$.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup]]