#Teorema 
Misalkan $A$ adalah grup siklik dengan $|A| = n$ dan pembangun $a$. Unsur $a^k$ adalah pembangung dari $A$ jika dan hanya jika $(n, k) = 1$.

---
## Bukti
Berdasarkan [[Order Unsur Pembangun]], maka $\text{ord}(a) = \text{ord}(A) = n$. 

Perhatikan bahwa berdasarkan [[Order Pangkat|Teorema]] maka $\text{ord}\left({a^k}\right) = \frac{n}{(n, k)}$. Maka berlaku
$$
\begin{align*}
a^k \text{ unsur pembangun dari } A &\ \iff \text{ord}(a^k) = n \\
&\ \iff \frac{n}{(n,k)} = n \\
& \ \iff (n, k) = 1
\end{align*}
$$

***
## Definition Used 
 * [[Grup Siklik]]
 * [[Orde Grup]]
 * [[Relatif Prima]]
