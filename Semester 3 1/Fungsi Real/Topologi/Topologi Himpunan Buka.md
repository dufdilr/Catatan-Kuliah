#Teorema 


Misalkan $(X, d)$ ruang metrik
1.  $\emptyset$ dan $X$ adalah himpunan buka
2.  Jika $\{G_\alpha\}_\alpha$ adalah kumpulan himpunan buka maka $\displaystyle \bigcup_\alpha G_\alpha$ juga himpunan buka
3.  Jika $\{G_1, G_2, \cdots, G_n\}$ adalah kumpulan berhingga himpunan buka maka $\displaystyle \bigcap_{i=1}^n G_i$ juga himpunan buka

---

## Bukti

1.  Untuk $\emptyset$ trivial. Untuk $X$, jelas $\forall \ a\in X:\ B(a, 1) \subseteq X$. Maka $X$ juga himpunan buka.

2.  Misalkan $\{G_\alpha\}_\alpha$ adalah kumpulan himpunan buka.
    
    Ambil $a \in \displaystyle \bigcup_\alpha G_\alpha$. Artinya $\exists \ \beta$ sehingga $a \in G_\beta$. Karena $G_\beta$ himpunan buka maka terdapat
    $$B(a, r) \subseteq G_\beta \subseteq \displaystyle \bigcup_\alpha G_\alpha$$
    Terbukti bahwa $\displaystyle \bigcup_\alpha G_\alpha$ juga himpunan buka.

3.  Misakan $\{G_1, G_2, \cdots, G_n\}$ adalah kumpulan berhingga himpunan buka.
    
    Ambil $a \in \displaystyle \bigcap_{i=1}^n G_i$. Artinya $a \in G_i, \ \forall i \in [1, n]_\mathbb{N}$. Ambil $i \in [1, n]_\mathbb{N}$. Karena $G_i$ himpunan buka maka terdapat $r_i$ sehingga $B(a, r_i) \subseteq G_i$
    
    Perhatikan bahwa $\{r_i\}$ berhingga. Pilih $r = \min\{r_i\}$. Perhatikan bahwa untuk setiap $i \in [1, n]_\mathbb{N}$
    $$B(a, r) \subseteq B(a, r_i) \subseteq G_i$$
    Artinya
    $$B(a, r) \subseteq \bigcap_{i=1}^n G_i$$
    Terbukti bahwa $\bigcap_{i=1}^n G_i$ juga himpunan buka.


***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Buka]]
