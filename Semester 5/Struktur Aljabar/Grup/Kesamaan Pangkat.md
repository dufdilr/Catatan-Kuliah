#Teorema 
Misalkan $G$ suatu grup dengan identitas $e$ dan $a \in G$ sehingga $\text{ord}\left({a}\right) = k < \infty$. Berlaku
$$
a^i = a^j \quad \iff \quad i \equiv j \mod \text{ord}\left({a}\right)
$$

---
## Bukti
### $\Leftarrow$
Misalkan $i \equiv j \mod \text{ord}\left({a}\right)$, artinya $i = k \cdot \text{ord}\left({a}\right) + j$ untuk suatu $k \in \mathbb{Z}$. Perhatikan bahwa
$$
a^i = a^{k \cdot \text{ord}\left({a}\right) + j} = a^{k \cdot \text{ord}\left({a}\right)} \cdot a^j = e \cdot a^j = a^j
$$

### $\Rightarrow$
Misalkan $a^i = a^j$ maka $a^{i-j} = e$. Berdasarkan [[Pangkat Identitas|Teorema]] maka $\text{ord}\left({a}\right) \mid i - j$. Terbukti $i \equiv j \mod \text{ord}\left({a}\right)$

***
## Definition Used 
 * [[Grup]]
 * [[Order Unsur Grup]]
 * [[Pangkat (Grup)]]
 * [[Kongruensi Modulo]]
