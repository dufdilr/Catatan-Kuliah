Misalkan $(X, d)$ ruang metrik dan $A \subseteq X$. Himpunan $A$ adalah *himpunan tutup* **jika dan hanya** jika $A' \subseteq A$

---

## Bukti

### **$\Rightarrow:$** 
Misalkan $A$ himpunan tutup. Akan ditunjukkan $A' \subseteq A$ dengan kontradiksi.   Andaikan $A' \nsubseteq A$. Artinya ada $x \in A'$ sehingga $x \in A^c$.
    Karena  himpunan tutup maka terdapat $r > 0$ sehingga $B(x, r) \subseteq A^c$. Artinya $B(x, r) \cap A = \emptyset$, kontradiksi dengan fakta $x \in A'$. Artinya pengandaian salah.
    Terbukti bahwa $A' \subseteq A$

## **$\Leftarrow:$** 
Misalkan $A' \nsubseteq A$. Akan ditunjukkan $A$ himpunan tutup.
    
 Ambil $a \in A^c$. Karena $A' \subseteq A$ dan $a \in A^c$ maka $a \notin A'$. Berarti ada $r > 0$ sehingga $B(x, r) \cap A = \emptyset$. Didapatkan $B(x, r) \subseteq A^c$. Artinya $A^c$ himpunan buka.
 
Terbukti bahwa $A$ himpunan tutup.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Himpunan Tutup]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Titik Limit|Titik Limit]]