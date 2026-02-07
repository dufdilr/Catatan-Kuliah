#Teorema 
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Maka $\mathrm{Inti}(f)$ membentuk ideal dari $A$

---
## Bukti

Berdasarkan [[Sifat Homomorfisma Gelanggang]], $f(0_A) = 0_B$. Artinya $0_A \in \mathrm{Inti}(f)$. Berarti $\mathrm{Inti}(f) \neq \emptyset$.

Lebih lanjut, ambil $a_{1}, a_{2} \in \mathrm{Inti}(f)$. Artinya $f(a_{1}) = f(a_{2})= 0$. Perhatikan bahwa
$$
\begin{align*}
f(a_{1}-a_{2}) &= f(a_{1})-f(a_{2}) = 0 - 0 = 0\\
f(a_{1}a_{2}) &= f(a_{1})f(a_{2}) = 0 \cdot 0 = 0
\end{align*}
$$
Maka $a_{1}-a_{2}, a_{1}a_{2} \in \mathrm{Inti}(f)$. Berdasarkan [[Karakterisasi Subgelanggang]] maka $\mathrm{Inti}(f)$ membentuk subgelanggang dari $A$.

Lebih lanjut, ambil $r \in \mathrm{Inti}(f)$ dan $a \in A$. Perhatikan bahwa berdasarkan [[Sifat Gelanggang#^1e044a|Sifat Perkalian Nol Gelanggang]]
$$
\begin{align*}
f(ar) &= f(a) f(r) = f(a)\cdot 0 = 0 \\
f(ra) &= f(r) f(a) = 0 \cdot f(a) = 0
\end{align*}
$$
Maka $ra, ar \in \mathrm{Inti}(f)$. Berdasarkan [[Karakterisasi Ideal]], maka $\mathrm{Inti}(f)$ merupakan ideal dari $A$.

***
## Definition Used 
 * [[Gelanggang]]
 * [[Subgelanggang]]
 * [[Homomorfisma (Ring)]]
 * [[Inti Homomorfisma Gelanggang]]
 * [[Ideal (Ring)]]