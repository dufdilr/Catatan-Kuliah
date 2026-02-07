#Teorema #Definisi 


Misalkan $(X, d)$ ruang metrik dan $E \subseteq X$. Definisikan $\overline{E} = E \cup E'$. Himpunan $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$. Himpunan $\overline{E}$ biasa disebut sebagai **Penutup Himpunan (closure)** $E$.

---

## Bukti

Untuk membuktikan bahwa $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$ maka harus dibuktikan 3 hal:
1.  Jelas $E \subseteq E \cup E' = \overline{E}$

2.  Akan ditunjukkan bahwa $\overline{E}$ adalah himpunan tutup. Berdasarkan [[Sifat Himpunan Titik Limit#^f98d7f|Teorema]], $E'$ adalah himpunan tutup. Berdasarkan [[Sifat Himpunan Titik Limit#^c3b08e|Teorema]] karena $E' \subseteq E$ maka $(E')' \subseteq E'$.
    
    Berdasarkan [[Sifat Himpunan Titik Limit#^a3c017|Teorema]] didapatkan
    $$\overline{E}' = (E \cup E')' = E' \cup (E')' \subseteq E' \cup E' = E' \subseteq E \cup E' = \overline{E}$$
    Berdasarkan [[Himpunan Tutup dan Himpunan Titik Limit|teorema]] terbukti bahwa $\overline{E}$ adalah himpunan tutup.

3.  Misalkan $F$ himpunan tutup sehingga $E \subseteq F$. Akan ditunjukkan $\overline{E} = E \cup E'\subseteq F$.
    
    Karena $E \subseteq F$, berdasarkan [[Sifat Himpunan Titik Limit|sifatnya]], $E' \subseteq F'$. Karena $F$ himpunan tutup, berdasarkan [[Sifat Himpunan Titik Limit#^c3b08e|sifat titik limit]] $F' \subseteq F$. Artinya $E' \subseteq F' \subseteq F$ sehingga
    $$\overline{E} = E \cup E'\subseteq F$$
    Terbukti himpunan $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$.

***

## Definition Used 
 * [[Ruang Metrik]]
 * [[Himpunan Tutup]]
 * [[Titik Limit]]