#Teorema #Definisi 


Misalkan $(X, d)$ ruang metrik dan $E \subseteq X$. Definisikan $\overline{E} = E \cup E'$. Himpunan $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$. Himpunan $\overline{E}$ biasa disebut sebagai **Penutup Himpunan (closure)** $E$.

---

## Bukti

Untuk membuktikan bahwa $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$ maka harus dibuktikan 3 hal:
1.  Jelas $E \subseteq E \cup E' = \overline{E}$

2.  Akan ditunjukkan bahwa $\overline{E}$ adalah himpunan tutup. Berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit#^f98d7f|Teorema]], $E'$ adalah himpunan tutup. Berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit#^c3b08e|Teorema]] karena $E' \subseteq E$ maka $(E')' \subseteq E'$.
    
    Berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit#^a3c017|Teorema]] didapatkan
    $$\overline{E}' = (E \cup E')' = E' \cup (E')' \subseteq E' \cup E' = E' \subseteq E \cup E' = \overline{E}$$
    Berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Tutup dan Himpunan Titik Limit|teorema]] terbukti bahwa $\overline{E}$ adalah himpunan tutup.

3.  Misalkan $F$ himpunan tutup sehingga $E \subseteq F$. Akan ditunjukkan $\overline{E} = E \cup E'\subseteq F$.
    
    Karena $E \subseteq F$, berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit|sifatnya]], $E' \subseteq F'$. Karena $F$ himpunan tutup, berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit#^c3b08e|sifat titik limit]] $F' \subseteq F$. Artinya $E' \subseteq F' \subseteq F$ sehingga
    $$\overline{E} = E \cup E'\subseteq F$$
    Terbukti himpunan $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$.

***

## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Tutup]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Titik Limit]]