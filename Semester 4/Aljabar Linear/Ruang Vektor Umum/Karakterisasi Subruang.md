#Teorema


Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $U$ subhimpunan takkosong $U \subseteq V$. $U$ membentuk **subruang** dari $V$ jika dan hanya jika untuk setiap ${u},{w} \in U$ dan $\lambda \in \mathbb{F}$ berlaku 
1. ${u}+ {w} \in U$
2. $\lambda \overline{u} \in U$

---
## Bukti
Karena $U$ tak kosong, pilih sebarang $u \in U$. Berdasarkan aturan (2), [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor#^fb9b94|maka]] $0u = 0 \in U$. Lebih lanjut, berdasarkan aturan (1) dan (2) maka operasi $+$ dan $\cdot$ terdefinisi dengan baik di $U$.

Ambil $u, v, w \in U$ dan $\alpha, \beta \in \mathbb{F}$. Karena $U \subseteq V$ maka $u, v, w \in V$. Artinya berlaku:
1.  **Sifat Asosiatif Penjumlahan**:
    $(u + v) + w = u + (v + w)$
2.  **Sifat Komutatif Penjumlahan**:
    $u + v = v + u$
3.  **Eksistensi Elemen Identitas (Vektor Nol)**:
    Terdapat elemen $\mathbf{0} \in V$, yang disebut **vektor nol**, sedemikian sehingga $v + \mathbf{0} = v$ untuk setiap $v \in V$.
4.  **Eksistensi Elemen Invers (Invers Aditif)**:
    Untuk setiap $v \in V$, terdapat elemen $-v \in V$, yang disebut **invers aditif** dari $v$, sedemikian sehingga $v + (-v) = \mathbf{0}$.
5.  **Sifat Distributif (Skalar terhadap Penjumlahan Vektor)**:
    $\alpha (u + v) = \alpha u + \alpha v$
6.  **Sifat Distributif (Vektor terhadap Penjumlahan Skalar)**:
    $(\alpha + \beta) v = \alpha v + \beta v$
7.  **Sifat Asosiatif Perkalian Skalar**:
    $(\alpha\beta) v = \alpha (\beta v)$
8.  **Eksistensi Elemen Identitas Perkalian**:
    $1v = v$, di mana $1$ adalah elemen identitas perkalian dalam lapangan $F$.

Terbukti, bahwa $U$ membentuk ruang vektor atas lapangan $\mathbb{F}$. Maka, $U$ adalah subruang dari $V$.


***

## Definition Used
* [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
* [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]