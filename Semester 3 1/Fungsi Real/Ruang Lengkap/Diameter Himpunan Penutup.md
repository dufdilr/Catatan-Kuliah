#Teorema 

Misalkan $(X, d)$ suatu ruang metrik dan himpunan tak-kosong $F$ maka berlaku
$$\text{diam}(F) = \text{diam}(\overline{F})$$

---

## Bukti

Jelas $F \subseteq \overline{F}$. Berdasarkan definisi dan sifat supremum maka $\text{diam}(F) \le \text{diam}(\overline{F})$

Ambil $x, y \in\overline{F}$. Artinya terdapat $\{x_n\}, \{y_n\} \subseteq F$ dengan $x_n \to x$ dan $y_n \to y$. Artinya terdapat $x'\in \{x_n\}$ dan $y' \in \{y_n\}$ sehingga $d(x, x') < r$ dan $d(y, y')< r$ untuk sembarang $r > 0$. Perhatikan bahwa
$$d(x, y) \le d(x, x') + d(y, y') + d(x', y') < 2r + \text{diam}(F)$$
Karena berlaku untuk sembarang $r >0$ maka $d(x, y) \le \text{diam}(F)$. Berarti
$$\text{diam}(\overline{F}) = \sup\left\{\ d(x, y)\ \ |\ \ x, y \in \overline{F}\ \right\}\le \text{diam}(F)$$
Terbukti bahwa $\text{diam}(F) = \text{diam}(\overline{F})$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Diameter Himpunan]]