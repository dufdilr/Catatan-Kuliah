#Teorema 

Misalkan $G$ adalah suatu grup dan $N \le G$. Pernyataan berikut ekuivalen:
1. $N$ adalah subgrup normal dari $G$.
2. $g ^{-1} N g \subseteq N$ untuk setiap $g \in G$.
3. $g^{-1}Ng = N$ untuk setiap $g \in G$.
4. $Ng = gN$ untuk setiap $g \in G$.

---
## Bukti
### $1 \Rightarrow 2$
Misalkan $N$ adalah subgrup normal dari $G$. Ambil $g \in G$. Ambil $x \in g^{-1}Ng$. Artinya $x = g^{-1}ng$ untuk suatu $n \in N$. Karena $g \in G$ maka $g ^{-1} \in G$. Per definisi [[Subgrup Normal]] maka
$$
x = g^{-1}ng \in N \quad\implies\quad g^{-1}Ng \subseteq N
$$
### $2 \Rightarrow 3$
Ambil $g \in G$. Perhatikan bahwa $g ^{-1} N g \subseteq N$. Akan ditunjukkan $g ^{-1} N g \supseteq N$.
Ambill $n \in N$. Karena $g \in G$ maka $g^{-1} \in G$. Berdasarkan hipotesis, $(g^{-1})^{-1}Ng^{-1} = g N g^{-1} \subseteq N$. Artinya, $gng^{-1} \in N$. Lebih lanjut,
$$
n = g^{-1}(gng^{-1})g \in g^{-1}Ng \quad\implies\quad g^{-1}Ng \supseteq N
$$
Terbukti $g ^{-1} N g = N$ untuk setiap $g \in G$.

### $3 \Rightarrow 4$
Ambil $g \in G$. Perhatikan bahwa $g^{-1}\in G$, berdasarkan hipotesa maka $N = (g^{-1})^{-1}Ng^{-1} = gNg^{-1}$. Artinya untuk setiap $n_{1} \in N$, terdapat $n_{2}\in N$ sehingga $gn_{2}g^{-1}$. Perhatikan pula bahwa
$$
\begin{align*}
x \in Ng & \ \iff x = n_{1}g, \ \exists n_{1} \in N \\
&\ \iff x = gn_{2}g^{-1}g, \ \exists n_{2} \in N \\
&\ \iff x = gn_{2}, \ \exists n_{2} \in N \\
&\ \iff x \in gN
\end{align*}
$$
Terbukti $Ng = gN$.

### $4 \Rightarrow 1$
Ambil $g \in G$ dan $n \in N$. Perhatikan bahwa $gN = Ng$, artinya $gn = n_{1}g$ untuk suatu $n_{1} \in N$. Perhatikan bahwa
$$
gng^{-1} = g_{1} \in N
$$
Per definisi [[Subgrup Normal]] maka $N \unlhd G$.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]