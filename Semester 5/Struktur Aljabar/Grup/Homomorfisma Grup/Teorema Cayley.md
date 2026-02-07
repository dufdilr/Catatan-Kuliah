#Teorema 

Misalkan $G$ adalah suatu grup. Maka berlaku
$$
G \cong H \le S\left({G}\right)
$$

---
## Bukti
Definisikan $\phi:G \to S\left({G}\right)$ dengan $\phi(g) = \phi_g : G \to G$ sedemikian sehingga
$$
\phi_g(x) = gx
$$
untuk setiap $x \in G$ untuk setiap $g \in G$. Akan ditunjukkan $\phi$ adalah homomorfisma yang injektif.

### Terdefinisi dengan Baik
Ambil $g\in G$. Akan ditunjukkan $\phi_g \in S(G)$. Misalkan $x_{1}, x_{2} \in G$ sehingga $\phi_g(x_{1}) = \phi_g(x_{2})$. Berdasarkan [[Hukum Pembatalan Grup]] maka
$$
\phi_g(x_{1}) = \phi_g(x_{2}) \quad\implies\quad gx_{1} = gx_{2} \quad\implies\quad x_{1} = x_{2}
$$
Maka $\phi_g$ bersifat injektif. Lebih lanjut ambil $y \in G$. Pilih $x = g^{-1}y$. Perhatian bahwa
$$
\phi_g(x) = gg^{-1}y = y
$$
maka $\phi_g$ bersifat surjektif. Dapat disimpulkan $\phi_g \in S(G)$. Artinya, $\phi$ terdefinisi dengan baik.

### Homomorfisma
Ambil $g_{1}, g_{2} \in G$. Perhatikan bahwa untuk setiap $x \in G$ berlaku
$$
\phi_{g_{1}}\circ \phi_{g_{2}}(x) = g_{1}(\phi_{g_{2}}(x)) = g_{1}g_{2}x = \phi_{g_{1}g_{2}}(x)
$$
Terbukti $\phi(g_{1}) \circ \phi(g_{2}) = \phi_{g_{1}}\circ \phi_{g_{2}} = \phi_{g_{1}g_{2}} = \phi(g_{1}g_{2})$.

### Injektif
Misalkan $\phi(g_{1}) = \phi_{g_{1}} = \phi_{g_{2}} = \phi(g_{2})$. Perhatikan bahwa
$$
g_{1} = g_{1}e = \phi_{g_{1}}(e) = \phi_{g_{2}}(e) = g_{2}e = g_{2}
$$
Maka $\phi$ bersifat injektif.

Misalkan $H = \phi(G)$. Jelas $\phi$ surjektif pada $H$. Artinya jika kita pandang $\phi:G \to H$ adalah isomorfisma, akibatnya
$$
G \cong H
$$
Berdasarkan [[Sifat Homomorfisma Grup#^bf256b|Sifat Peta Homomorfisma]] maka $H = \phi(G) \le S(G)$. Terbukti
$$
G \cong H \le S\left({G}\right)
$$
***
## Definition Used 
 * [[Grup]]
 * [[Subgrup]]
 * [[Grup Permutasi S(G)]]