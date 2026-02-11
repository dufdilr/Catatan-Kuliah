#Teorema 


Misalkan $(X, d)$ suatu ruang metrik dan $E, F$ subhimpunan dari $X$, berlaku:
1.  Jika $E \subseteq F$ maka $E^o \subseteq F^o$
2.  $\left(E\cap F\right)^o = E^o \cap F^o$
3.  $\left(E \cup F\right)^o \supseteq E^o \cup F^o$

---

## Bukti

### Sifat 1
Misalkan $E\subseteq F$. Ambil $x \in E^o$. Artinya terdapat $r>0$ sehingga
    $$B(a, r) \subseteq E \subseteq F$$
    Maka $x \in F^o$. Terbukti bahwa $E^o \subseteq F^o$.

### Sifat 2
#### $\subseteq$:
Ambil $a \in \left(E\cap F\right)^o$. Artinya terdapat $r>0$ sehingga
        $$B(a, r) \subseteq E\cap F \subseteq E \quad \text{dan}\quad B(a, r) \subseteq E\cap F \subseteq F$$Artinya $a \in E^o \cap F^o$. Terbukti bahwa $\left(E\cap F\right)^o \subseteq E^o \cap F^o$
    
####  $\supseteq$:
 Ambil $a \in E^o \cap F^o$. Artinya terdapat $r_1>0$ dan $r_2>0$ sehingga
        $$B(a, r_1) \subseteq E\quad \text{dan}\quad B(a, r_2) \subseteq F$$
        Pilih $r = \min\{r_1, r_2\}$ maka
        $$a\in B(a, r)\subseteq B(a, r_1) \subseteq E\quad \text{dan}\quad a\in B(a, r)\subseteq B(a, r_2) \subseteq F$$
        Artinya $a \in \left(E\cap F\right)^o$.
        Terbukti bahwa $\left(E\cap F\right)^o \supseteq E^o \cap F^o$.

### Sifat 3
Ambil $a \in E^o \cup F^o$. Tanpa mengurangi keumuman, misalkan $a \in E^o$. Artinya terdapat $r >0$ sehingga
    $$B(a, r) \subseteq E \subseteq E\cup F$$
    Artinya $a \in \left(E \cup F\right)^o$. Terbukti bahwa $\left(E \cup F\right)^o \supseteq E^o \cup F^o$.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
* [[Buat Backup/Semester 3/Fungsi Real/Topologi/Titik Interior]]

