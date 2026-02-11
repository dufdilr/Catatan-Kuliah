#Teorema 

Misalkan $(G, *)$ membentuk grup dan $H \leq G$. Himpunan pemusat $H$ di $G$ yakni $C_H(G)$ membentuk subgrup dari $G$.

---
## Bukti
Jelas untuk setiap $h \in H$ berlaku $eh = h = he$. Artinya $e \in C_H(G)$. Maka $C_H(G)\neq \emptyset$.

Lebih lanjut, ambil $g_1, g_2 \in C_H(G)$ dan $h \in H$. Perhatikan bahwa
$$
\begin{align*}
g_1h &= hg_1 \\
g_1^{-1}(g_1h)g_1^{-1} &= g_{1}^{-1}(g_{1}h)g_{1}^{-1} \\
hg_{1}^{-1} &= g_{1}^{-1}h
\end{align*}
$$
Maka, $g_{1}^{-1}\in G$. Lebih lanjut,
$$
(g_1^{-1}g_2)h = g_1^{-1}(g_2h) = g_1^{-1}(hg_2) = (g_1^{-1}h)g_2 = (hg_1^{-1})g_2 = h (g_1^{-1}g_2)
$$
Maka $g_1^{-1}g_2 \in C_H(G)$.  Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Subgrup]], maka $C_H(G)$ membentuk subgrup dari $G$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pemusat Grup]]