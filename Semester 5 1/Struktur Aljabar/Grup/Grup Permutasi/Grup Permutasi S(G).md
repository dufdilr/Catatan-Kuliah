#Teorema 
Misalkan $G$ adalah suatu himpunan. Definisikan
$$
S(G) := \{ \sigma:G \to G \quad|\quad \sigma \text{ bijeksi}  \}
$$
Himpunan $(S(G), \circ)$ dengan operasi komposisi membentuk **grup**.

---
## Bukti
### Well Defined
Ambil $f, g \in S(G)$. Berdasarkan [[Komposisi Fungsi Bijeksi]], maka $g \circ f$ juga fungsi bijeksi. 
$$
g\circ f \in S(G)
$$
Terbukti, komposisi terdefinisi dengan baik pada $S(G)$.

### Asosiatif
Jelas berdasarkan [[Komposisi Asosiatif]]

### Identitas
Tinjau $i_G:G \to G$ dengan $i_G(g) = g$ untuk setiap $g \in G$. Jelas untuk setiap $f \in S(G)$ berlaku
$$
f\circ i_G = f = i_G \circ f
$$
Maka, $i_G$ adalah identitas di $S(G)$.

### Invers
Berdasarkan [[Fungsi Bijektif Invertibel]], maka terdapat $g:G \to G$ sedemikian sehingga
$$
f\circ g = g\circ f = i_G
$$
Terbukti setiap unsur di $S(G)$ memiliki invers.

Perdefinisi, terbukti $S(G)$ membentuk grup.

***
## Definition Used 
 * [[Himpunan]]
 * [[Fungsi Bijektif]]
