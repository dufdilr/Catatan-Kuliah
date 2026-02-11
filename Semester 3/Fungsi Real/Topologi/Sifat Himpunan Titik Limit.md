#Teorema 

Misalkan $E, F$ himpunan serta $E', F'$ adalah himpunan semua titik limit dari $E, F$ berturut-turut. Berlaku:
1.  $E'$ adalah himpunan tutup. ^f98d7f
2.  Jika $E \subseteq F$ maka $E' \subseteq F'$. ^c3b08e
3.  $(E\cup F)' = E'\cup F'$. ^a3c017
4.  $(E \cap F)' \subseteq E' \cap F'$ ^69421e

---

## Bukti

### Sifat 1
Akan ditunjukkan dengan kontradiksi. Andaikan $(E')^c$ tidak buka. Artinya terdapat $a \in (E')^c$ sehingga untuk setiap $r > 0$, terdapat $a\neq x \in B(a, r)$ sehingga $x \in E'$. Karena $a \in (E')^c$ maka terdapat $\varepsilon >0$ sehingga
    $$B(a, \varepsilon) \cap\left(E/ \{a\}\right) = \emptyset$$
    Kontradiksi dengan fakta bahwa $x \in B(a, \varepsilon) \cap\left(E/ \{a\}\right)$. Artinya pengandaian salah.
    
Terbukti bahwa $E'$ himpunan tutup.

### Sifat 2
Misalkan $E \subseteq F$. Ambil $x \in E'$. Maka, untuk setiap $\varepsilon > 0:$
    $$B(x, \varepsilon) \cap\left(E/ \{x\}\right) \neq \emptyset$$
    Perhatikan bahwa
    $$B(x, \varepsilon) \cap\left(F/ \{x\}\right) \supseteq B(x, \varepsilon) \cap\left(E/ \{x\}\right) \neq \emptyset$$
    Maka, $x \in F'$. Terbukti bahwa $E' \subseteq F'$.

### Sifat 3
####  **$\subseteq:$**
Ambil $x \in (E \cup F)'$. Artinya, untuk setiap $\varepsilon > 0:$
        $$B(x, \varepsilon) \cap\left(E\cup F/ \{x\}\right) = \left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right) \cup \left(B(x, \varepsilon) \cap\left(F/ \{x\}\right) \right)\neq \emptyset$$
        Artinya
        $$\left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right)\neq \emptyset \quad \text{atau} \quad \left(B(x, \varepsilon) \cap\left(F/ \{x\}\right) \right)\neq \emptyset$$
        Dengan kata lain $x \in E'$ atau $x \in F'$. Terbukti bahwa $(E \cup F)' \subseteq E' \cup F'$
    
#### **$\supseteq:$**
Ambil $x \in E' \cup F'$. Artinya $x \in E'$ atau $x \in F'$. Tanpa mengurangi keumuman, misalkan $x \in E'$. Artinya
        $$\left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right)\neq \emptyset$$
        Perhatikan bahwa
        $$
        \begin{align*}
        B(x, \varepsilon) \cap\left(E\cup F/ \{x\}\right) &= \left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right) \cup \left(B(x, \varepsilon) \cap\left(F/ \{x\}\right) \right) \\
        &\supseteq \left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right)\neq \emptyset
        \end{align*}
        $$
        Artinya $x \in (E\cup F)'$. Terbukti bahwa $(E \cup F)' \supseteq E' \cup F'$

### Poin 4
 Ambil $x \in (E \cap F)'$. Artinya
    $$B(x, \varepsilon) \cap\left(E\cap F/ \{x\}\right) = \left(B(x, \varepsilon) \cap\left(E/ \{x\}\right) \right) \cap \left(B(x, \varepsilon) \cap\left(F/ \{x\}\right) \right) \neq \emptyset$$
    Artinya terdapat $a$ sehingga $a \in (B(x, \varepsilon) \cap\left(E/ \{x\}\right)$ dan $a \in (B(x, \varepsilon) \cap\left(F/ \{x\}\right)$. Berarti $x \in E'$ dan $x \in F'$. Terbukti bahwa $(E \cap F)' \subseteq E' \cap F'$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Himpunan Tutup]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Titik Limit|Titik Limit]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Bola Buka]]
