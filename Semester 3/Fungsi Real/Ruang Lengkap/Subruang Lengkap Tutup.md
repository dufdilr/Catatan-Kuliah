#Teorema 

Misalkan $(X,d)$ suatu metrik dan $A \subseteq X$. Jika $A$ adalah subruang lengkap maka $A$ himpunan tutup.

---

## Bukti

Misalkan $A$ subruang lengkap dari $X$. Ambil $x \in \overline{A}$. Artinya [[Sifat Titik Limit#^c17a86|terdapat barisan]] $\{x_n\} \subseteq A$ sehingga $x_n \to x$. Berdasarkan [[Barisan Konvergen Cauchy|Teorema]] maka $\{x_n\}$ barisan cauchy.

Karena $A$ subruang lengkap dan $\{x_n\} \subseteq A$ barisan cauchy maka terdapat $x' \in A$ sehingga $x_n \to x'$. Karena [[Ketunggalan Limit|ketunggalan limit]] maka $x = x' \in A$. Artinya $\overline{A} \subseteq A$.

Jelas $A \subseteq \overline{A}$. Maka dapat disimpulkan bahwa $A = \overline{A}$.
Berdasarkan [[Sifat Penutup Himpunan#^e1ad0a|teorema]] terbukti bahwa $A$ himpunan tutup.

***
## Definition Used 
 * [[Ruang Metrik]]
 * [[Ruang Metrik Lengkap]]
 * [[Himpunan Tutup]]
 * [[Barisan Cauchy (Metrik)]]
 * [[Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
