#Teorema 

Misalkan $(X,d)$ suatu metrik dan $A \subseteq X$. Jika $A$ adalah subruang lengkap maka $A$ himpunan tutup.

---

## Bukti

Misalkan $A$ subruang lengkap dari $X$. Ambil $x \in \overline{A}$. Artinya [[Buat Backup/Semester 3/Fungsi Real/Topologi/Sifat Titik Limit#^c17a86|terdapat barisan]] $\{x_n\} \subseteq A$ sehingga $x_n \to x$. Berdasarkan [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen Cauchy|Teorema]] maka $\{x_n\}$ barisan cauchy.

Karena $A$ subruang lengkap dan $\{x_n\} \subseteq A$ barisan cauchy maka terdapat $x' \in A$ sehingga $x_n \to x'$. Karena [[Buat Backup/Semester 3/Fungsi Real/Barisan/Ketunggalan Limit|ketunggalan limit]] maka $x = x' \in A$. Artinya $\overline{A} \subseteq A$.

Jelas $A \subseteq \overline{A}$. Maka dapat disimpulkan bahwa $A = \overline{A}$.
Berdasarkan [[Buat Backup/Semester 3/Fungsi Real/Topologi/Sifat Penutup Himpunan#^e1ad0a|teorema]] terbukti bahwa $A$ himpunan tutup.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Himpunan Tutup]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
