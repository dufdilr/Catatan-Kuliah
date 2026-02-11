#Teorema #NotFinished 

Misalkan $G$ himpunan berhingga tak-kosong sehingga $(G, *)$ merupakan sistem asosiatif. $(G, *)$ membentuk grup **Jika dan Hanya Jika** untuk setiap $a, b, c \in G$ berlaku
$$
(ab = ac \implies b = c) \quad \text{ dan } \quad (ba = ca \implies b = c)
$$
---
## Bukti
Misalkan $\text{ord}(G) = n$. Ambil $a \in G$. Tinjau $A = \{ a, a^2, a^3, \dots, a^n, a^{n+1} \}$. Jelas $A \subseteq G$. Artinya $|A| \le n$. Berdasarkan [[Prinsip Sarang Merpati]], maka terdapat $i, j$ dengan $i \neq j$ sehingga $a^i = a^j$.
Tanpa mengurangi keumuman, misalkan $i > j$. Misalkan pula $k = i - j$. Misalkan $e = a^k$. Akan ditunjukkan $e$ adalah elemen identitas.