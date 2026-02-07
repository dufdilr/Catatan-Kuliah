#Teorema

Misalkan $G$ suatu grup. $G$ adalah **grup siklik** jika dan hanya jika terdapat $a \in G$ sehingga
$$
\text{ord}(a) = o(G)
$$

***
## Bukti
### $\Rightarrow$
Misalkan $G = \left< a \right>$ grup siklik. Berdasarkan [[Order Unsur Pembangun|Teorema]], maka $\text{ord}(a) = \text{ord}(G)$. Terbukti.

### $\Leftarrow$
Misalkan terdapat $a \in G$ sehingga $\text{ord}(a) = \text{ord}(G) = k$. Tinjau
$$
\left< a \right>  = \{ e, a, a^2, \dots, a^{k-1} \}
$$
Jelas bahwa $\left< a \right> \subseteq G$. [[Order Unsur Pembangun|Karena]] $|a| = k = |G| < \infty$ maka $\left< a \right> = G$. Terbukti $G$ adalah grup siklik.

***

## Definition Used 
 * [[Grup]]
 * [[Grup Siklik]]
 * [[Orde Grup]]
 * [[Order Unsur Grup]]
