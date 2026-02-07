#Teorema 
Misalkan grup $G$ dan $S \le G$. Misalkan pula $aS, bS \in G/S$. 
$$
aS = bS \quad \iff \quad a^{-1}b \in S
$$
---
## Bukti
### $\Rightarrow$
Misalkan $aS = bS$. Perhatikan bahwa $a \in aS = bS$. Artinya $a = bs$ untuk suatu $b \in S$. Perhatikan bahwa
$$
a=bs \quad\implies\quad b^{-1}a = s \quad\implies\quad a^{-1}b = s ^{-1}
$$
Karena $s \in S$ maka $s ^{-1} = a^{-1}b \in S$. 

### $\Rightarrow$
Misalkan $a^{-1}b \in S$. Artinya $a^{-1}b = s$ untuk suatu $s \in S$. 
$$
\begin{align*}
x \in aS &\ \iff x = as_{1},\ \exists s_{1} \in S \\
&\ \iff x = aa^{-1}bs^{-1}s_{1},\ \exists s_{1} \in S \\
& \ \iff x = bs ^{-1}s_{1}, \ \exists s_{1}\in S \\
&\ \iff x = bs_{2}, \ \exists s_{2}\in S \\
&\ \iff x \in bS
\end{align*}
$$
Terbukti $aS = bS$

***
## Definition Used 
 * [[Koset Grup]]
 * [[Grup]]
 * [[Relasi Subgrup]]