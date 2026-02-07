#Teorema 
Misalkan $G$ grup dan $N \unlhd G$ maka setiap subgrup normal dari $G/N$ adalah $K/N$ dengan $K \unlhd G$ dan $N \subseteq K \subseteq G$.

---
## Bukti
Misalkan $K \unlhd G$ dengan $N \subseteq K \subseteq G$. Akan ditunjukkan $K/N \unlhd G/N$.

Ambil $k_{1}N, k_{2}N \in K/N$ dan $gN \in G/N$. Perhatikan bahwa
$$
\begin{align*}
k_{1}N \cdot (k_{2}N)^{-1} &= (k_{1}k_{2}^{-1})N \\
gN \cdot (k_{1}N) \cdot(gN)^{-1} &= (gk_{1}g^{-1})N
\end{align*}
$$
Karena $K \unlhd G$ maka $k_{1}k_{2}^{-1}, gk_{1}g^{-1} \in K$. Akibatnya, $k_{1}N \cdot (k_{2}N)^{-1}, gN \cdot (k_{1}N) \cdot(gN)^{-1} \in K/N$. Maka $K/N \unlhd G/N$.

Lebih lanjut, misalkan $H \unlhd G/N$. Tulis $K = \{ k\in G \ | \ kN \in H \}$. Akan ditunjukkan $K \unlhd G$.

Ambil $k_{1}, k_{2} \in K$ dan $g \in G$. Perhatikan bahwa $k_{1}N, k_{2}N \in H \unlhd G/N$ artinya
$$
\begin{align*}
(k_{1}N)(k_{2}N)^{-1} &= (k_{1}k_{2}^{-1})N \in H = K/N \\
&\Rightarrow k_{1}k_{2}^{-1} \in N \\
(gN)(k_{1}N)(gN)^{-1} &= (gk_{1}g^{-1})N \in H = K/N \\
& \Rightarrow gk_{1}g^{-1} \in K
\end{align*}
$$
Berdasarkan [[Karakterisasi Subgrup Normal]] maka $K \unlhd G$. Terbukti.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]
 * [[Grup Hasil Bagi]]