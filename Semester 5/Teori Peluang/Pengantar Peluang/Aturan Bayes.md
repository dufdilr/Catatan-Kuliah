#Teorema 

Misalkan $(S, \mathcal{A}, P)$ adalah ruang peluang dan $B_{1}, B_{2}, \cdots, B_{n}$ adalah partisi dari $S$. Untuk setiap $A \in \mathcal{A}$ berlaku
$$
P(B_{i}|A) = \frac{P(A|B_{i}) \cdot P(B_{i})}{\sum_{k=1}^nP(A|B_{k}) \cdot P(B_{k})} 
$$

## Bukti
Perhatikan bahwa untuk setiap $i \in \{ 1, 2, \cdots, n \}$
$$
P(E|F) = \frac{P(E \cap F)}{P(F)} \quad \Rightarrow \quad P(E \cap F) = P(E|F) \cdot P(F)
$$
[[Peluang Bersyarat Berpartisi|Lebih lanjut,]]
$$
P(A) = \sum_{k=1}^n P(A \cap B_{k}) = \sum_{k=1}^nP(A|B_{k}) \cdot P(B_{k})
$$
Maka dapat disimpulkan,
$$
P(B_{i}|A) = \frac{P(B_{i}\cap A)}{P(A)} = \frac{P(A|B_{i}) \cdot P(B_{i})}{\sum_{k=1}^nP(A|B_{k}) \cdot P(B_{k})}  \quad \blacksquare
$$

***
## Definition Used
* [[Ruang Peluang]]
* [[Peluang Bersyarat]]