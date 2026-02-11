#Teorema 

Misalkan $n \in \mathbb{N}$ memiliki akar primitif maka $n$ memiliki sebanyak $\varphi(\varphi(n))$ akar primitif berbeda (up to modulo).

---

## Bukti
Misalkan $A$ adalah himpunan semua akar primitif dari $n$. Per definisi, setiap unsur di $A$ haruslah relatif prima dengan $n$. Perhatikan pula bahwa berdasarkan [[Buat Backup/Semester 4 1/Pengantar Teori Bilangan/Akar Primitif/Sistem Residu Akar Primitif|teorema]], untuk suatu akar primitif $r$
$$
R = \{ r, r^2, r^3, \cdots, r^{\varphi(n)} \}
$$
membentuk sistem residu tereduksi. Artinya $A \subseteq R$. Lebih lanjut, berdasarkan [[Buat Backup/Semester 4 1/Pengantar Teori Bilangan/Akar Primitif/Akar Primitif Pangkat|teorema]], $r^k$ juga pangkat jika dan hanya jika $(\varphi(n), k) = 1$. Maka, banyak akar primitif sama dengan banyak $k$ yang relatif prima dengan $\varphi(n)$ yakni