#Teorema 

Misalkan $(x, d)$ suatu ruang metrik dan $E$ subhimpunan dari $X$. Maka ketiga pernyataan berikut ekuivalen:
1.  $x$ adalah titik limit dari $E$
2.  $\exists \{x_n\} \subseteq E, \ x_n \neq x$ sehingga $x_n \to x$. ^c17a86
3.  $\forall \varepsilon>0, |B(x, \varepsilon) \cap E| = \infty$.

---

## Bukti

###  **$1\Rightarrow 2$**:
Ambil $x \in E'$. Artinya $B(x,\ 1/n)\cap (E/\{x\}) \neq \emptyset$. Pilih
    $$x_n \in B\left(x,\ \frac{1}{n}\right)\cap (E/\{x\})$$
    Selanjutnya akan ditunjukkan . Ambil . Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Sifat Archimedean]], terdapat $N \in \mathbb{N}$ sehingga $N > 1/\varepsilon$. Perhatikan bahwa untuk setiap $n \ge N$
    $$d(x_n, x) < \frac{1}{n} \le \frac{1}{N} < \varepsilon$$
    Terbukti bahwa $x_n \to x$.

### **$2\Rightarrow 3$**:
Misalkan terdapat $\{x_n\} \subseteq E$ dengan $x_n \to x$. Andaikan $\exists \varepsilon_0 > 0$ sehingga
    $$|B(x, \varepsilon_0) \cap E| = k < \infty$$
    
Tinjau himpunan $D = \{d(x, y) \ | \ y \in B(x, \varepsilon_0) \cap E\}$. Karena $D$ berhingga maka terdapat $\varepsilon_1 = \min(D)$. Perhatikan bahwa $\forall y \in X: \ d(x, y) > \varepsilon_1/2$. Artinya
    $$B\left(x, \frac{\varepsilon_1}{2}\right) \cap (E/\{x\}) = \emptyset$$
    Karena $x_n \to x$ maka terdapat $x_N \in \{x_n\}$ sehingga $d(x, x_N) < \frac{\varepsilon_1}{2}$. Kontradiksi. Maka pengandaian salah.
    
Terbukti bahwa $\forall \varepsilon>0, |B(x, \varepsilon) \cap E| = \infty$

### **$3 \Rightarrow 1$**:
Ambil $\varepsilon > 0$. Karena $|B(x, \varepsilon) \cap E| = \infty$ maka $|B(x, \varepsilon) \cap (E/\{x\})| = \infty$ sehingga
    $$B(x, \varepsilon) \cap (E/\{x\}) \neq \emptyset$$
    Terbukti bahwa $x$ titik limit.

***

## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Titik Limit|Titik Limit]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Bola Buka]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
