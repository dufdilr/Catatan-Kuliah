#Teorema 
Misalkan $A$ adalah grup dan $B \le A$ dan $N \unlhd A$. Maka berlaku
$$
(B\cap N) \unlhd B \quad \text{ dan } \quad BN \unlhd N
$$
---
## Bukti
### Statement Pertama
Berdasarkan [[Irisan Subruang]] maka $B\cap N$ membentuk subruang dari $B$. Lebih lanjut, ambil $b \in B \subseteq A$ dan $n \in B\cap N \subseteq N$. Karena $N$ adalah subruang normal maka $bnb^{-1} \in N$. Karena $b,n \in B$ maka $bnb^{-1}\in B$. Akibatnya 
$$
bnb^{-1} \in B\cap N
$$
Terbukti $(B\cap N) \unlhd B$.

### Statement Kedua
Ambil $bn_{1} \in BN$ dan $n_{2} \in N$. Perhatikan bahwa karena $N$ adalah subgrup normal [[Karakterisasi Subgrup Normal|akibatnya]] $bN = Nb$. Artinya $n_{2}b = bn_{3}$ untuk suatu $n_{3}\in N$. Perhatikan bahwa
$$
n_{2}bn_{1}n_{2}^{-1} = bn_{3}n_{1}n_{2}^{-1} \in bN \subseteq BN
$$
Terbukti $BN \unlhd N$.

***
## Definition Used 
 * [[Grup]]
 * [[Subgrup Normal]]