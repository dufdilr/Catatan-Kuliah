#Teorema 

Misalkan $(S, \mathcal{A}, P)$ adalah ruang peluang dan $B_{1}, B_{2}, \cdots, B_{n}$ adalah partisi dari $S$. Untuk setiap $A \in \mathcal{A}$ berlaku
$$
P(A) = \sum_{i=1}^n P(A \cap B_{i})
$$
## Bukti
Karena $B_1, B_2, \cdots, B_n$ adalah partisi dari $S$ maka berlaku
$$
\bigcup_{i=1}^n B_{i} = S
$$
dan $B_i \cap B_j = \emptyset$ untuk setiap $i \neq j$. Perhatikan bahwa jika $i \neq j$ berlaku
$$
(A \cap B_{i}) \cap (A \cap B_{j}) = A \cap (B_{i} \cap B_{j}) = A \cap \emptyset = \emptyset
$$
Perhatikan [[Distributif Irisan dan Gabungan|bahwa]] 
$$
\begin{align*}
P(A) &= P(A \cap S) = P\left(A \cap \left(\bigcup_{i=1}^n B_{i}\right)\right) \\
\\
&= P\left(\bigcup_{i=1}^n (A\cap B_{i})\right) \\
\\
&= \sum_{i=1}^n P(A\cap B_{i}) \quad \quad \blacksquare
\end{align*}
$$
***
## Definition Used
* [[Ruang Peluang]]
* [[Partisi Himpunan]]