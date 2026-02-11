#Teorema 

Misalkan $G$ suatu grup dan $a \in G$ dengan $\text{ord}\left({a}\right) = t$ dan $u \in \mathbb{N}$. Maka berlaku
$$
\text{ord}\left({a^u}\right) = \frac{t}{(t, u)}
$$
---
## Bukti
Misalkan $(t, u) = d$ dan $\text{ord}\left({a^u}\right) = k$. Tulis $t = dt_1$ dan $u = du_{1}$ dengan $t_{1},u_{1} \in \mathbb{N}$. Perhatikan [[Hasil Bagi FPB Relatif Prima|bahwa]] $(t_{1}, u_{1})=1$. Perhatikan bahwa
$$
(a^u)^{t_{1}} = (a^{du_{1}})^{t_{1}} = a^{du_{1}t_{1}} = a^{tu_{1}} = e^{u_{1}} = e
$$
Berdasarkan [[Pangkat Identitas|teorema]] maka $k \mid t_{1}$. Lebih lanjut, perhatikan bahwa
$$
(a^u)^k = e \quad\implies\quad a^{du_{1}k} = e
$$
Berdasarkan [[Pangkat Identitas|teorema]] maka $t = dt_{1} \mid du_{1}k$. [[Sifat Keterbagian|Artinya]] $t_{1} \mid u_{1}k$. Karena $(t_{1}, u_{1}) = 1$ berdasarkan [[Hukum Pembatalan Keterbagian|teorema]] maka $t_{1}\mid k$.

Karena $k \mid t_{1}$ dan $t_{1}\mid k$ maka $t_{1} = k$. Artinya, terbukti bahwa 
$$
\text{ord}\left({a^u}\right) = \frac{t}{(t, u)}
$$
***
## Definition Used 
 * [[Grup]]
 * [[Pangkat (Grup)]]
 * [[Order Unsur Grup]]