#Teorema 
Misalkan $r, n \in \mathbb{N}$ dan $r$ adalah **akar primitif** dari $n$. Maka himpunan
$$
R = \{ r, r^2, r^3, \cdots, r^{\varphi(n)} \}
$$
membentuk **Sistem Residu Tereduksi**

---

## Bukti
Perhatikan bahwa $|R| = \varphi(n) = |U_n|$. Agar $R$ adalah sistem residu tereduksi maka harus ditunjukkan $R\subseteq U_n$ dan $R$ saling relatif prima.

Karena $r$ akar primitif dari $n$ maka perdefinisi $(r, n) = 1$. Berdasarkan [[Perkalian Relatif Prima|Teorema]], maka $(r^k, n) = 1$ untuk setiap $k \in \mathbb{N}$. Maka $R \subseteq U_n$.

Lebih lanjut, perhatikan bahwa untuk setiap $r^i, r^j \in R$ dengan $i < j$ maka $0 < i < j \le \varphi(n)$. Jelas tidak mungkin $\varphi(n) \mid i - j$. Berdasarkan [[Kongruensi Modulo Pangkat|Teorema]] maka $r^i \neq r^j$.

***
## Definition Used 
 * [[Kongruensi Modulo]]
 * [[Akar Primitif]]
 * [[Sistem Residu Tereduksi]]
 * [[Fungsi Euler-Phi]]