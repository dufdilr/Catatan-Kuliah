#Teorema 

Misalkan $G$ suatu grup dengan elemen identitas $e$ dan $a \in G$. Berlaku
$$
a^n = e \quad \iff \quad \text{ord}\left({a}\right) \mid n
$$
---
## Bukti
### $\Leftarrow$ 
Misalkan $\text{ord}\left({a}\right) \mid n$ maka $n = \text{ord}\left({a}\right) \cdot k$ untuk suatu $k \in \mathbb{N}$. Perhatikan bahwa
$$
a^n = a^{\text{ord}\left({a}\right) \cdot k} = \left( a^{\text{ord}\left({a}\right)} \right) ^k = e^k = e
$$
### $\Rightarrow$
Misalkan $a^n = e$. Berdasarkan [[Algoritma Pembagian]] maka $n = q \cdot \text{ord}\left({a}\right) + r$ untuk suatu $q, r \in \mathbb{Z}$ dengan $0 \le r < \text{ord}\left({a}\right)$. Perhatikan bahwa
$$
e = a^n = a^{q \cdot \text{ord}\left({a}\right) + r} = a^{q \cdot \text{ord}\left({a}\right)} \cdot a^r = e^q \cdot a^r = e \cdot a^r = a^r
$$
maka $a^r = e$. Perhatikan bahwa $r < \text{ord}\left({a}\right)$. Per definisi $\text{ord}\left({a}\right)$, tidak mungkin $r \in \mathbb{N}$. Artinya $r \not\in \mathbb{N}$, sehingga pastilah $r = 0$. Terbukti bahwa $\text{ord}\left({a}\right) \mid n$.

***
## Definition Used 
 * [[Grup]]
 * [[Order Unsur Grup]]