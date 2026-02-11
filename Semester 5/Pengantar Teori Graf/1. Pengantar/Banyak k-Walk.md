#Teorema 

Misalkan $G$ suatu graf dengan $V(G) = v_{1}, v_{2}, \cdots , v_{n}$ dan matriks ketetanggaan **$A$**. Banyak $(v_i, v_j)-$walk dengan panjang $k$ adalah entri $(i, j)$ pada matriks $A^k$.

## Bukti
Akan dibuktikan dengan [[Buat Backup/Prerquested/Prinsip Induksi Matematika|induksi]]
### Kasus Basis
Jelas untuk $k = 0$ banyak $k$-walk hanyalah dari titik ke titik tersebut. Artinya $A^0 = I$.

### Langkah Induksi
Asumsikan benar untuk suatu $k = n$. Perhatikan bahwa
$$
[A^{k+1}]_{i, j} = \sum_{l = 1}^n[A^k]_{i, l} \cdot [A]_{l, j}
$$
yang tidak lain banyak jalan dengan panjang $k+1$ dari $v_i$ ke $v_j$.

***
## Definition Used
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Graf]]
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Matriks Ketetanggaan]]
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Walk (Graf)]]
