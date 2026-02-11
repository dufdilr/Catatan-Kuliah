#Teorema 
Misalkan $r, n \in \mathbb{N}$ dan $r$ adalah **akar primitif** dari $n$. Maka himpunan
$$
R = \{ r, r^2, r^3, \cdots, r^{\varphi(n)} \}
$$
membentuk **Sistem Residu Tereduksi**

---

## Bukti
Perhatikan bahwa $|R| = \varphi(n) = |U_n|$. Agar $R$ adalah sistem residu tereduksi maka harus ditunjukkan $R\subseteq U_n$ dan $R$ saling relatif prima.

Karena $r$ akar primitif dari $n$ maka perdefinisi $(r, n) = 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima|Teorema]], maka $(r^k, n) = 1$ untuk setiap $k \in \mathbb{N}$. Maka $R \subseteq U_n$.

Lebih lanjut, perhatikan bahwa untuk setiap $r^i, r^j \in R$ dengan $i < j$ maka $0 < i < j \le \varphi(n)$. Jelas tidak mungkin $\varphi(n) \mid i - j$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Kongruensi Modulo Pangkat|Teorema]] maka $r^i \neq r^j$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Kongruensi Modulo]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Akar Primitif]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Kongruensi Modulo/Sistem Residu Tereduksi]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]