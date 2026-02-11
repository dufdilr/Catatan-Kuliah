# No. 1
## Soal

 Suatu ring $R$ dikatakan lokal jika $R$ mempunyai tepat satu ideal maksimal. Diberikan ring komutatif $R$ dengan elemen identitas. Buktikan bahwa $R$ ring lokal jika dan hanya jika himpunan semua elemen bukan unit merupakan ideal.

## Solusi

### Klaim 1

Misalkan $R$ suatu ring komutatif dengan elemen identitas $e$ dan $I$ suatu ideal dari $R$. Jika terdapat $u \in I$ sehingga $u$ adalah unit di $R$ maka $I = R$

#### Bukti

Jelas $I \subseteq R$. Lebih lanjut, ambil $r \in R$. Perhatikan bahwa
$$
r = ru^{-1}u \in I
$$
karena $u \in I$ dan $I$ adalah ideal dari $R$. Berarti $R \subseteq I$. Terbukti $R = I$.
### $\Rightarrow$
Misalkan $R$ suatu ring komutatif dengan elemen identitas $e$ yang bersifat lokal. Tinjau
$$
K := \{ k \in R\  |\  k \text{ bukan unit} \}
$$
Akan ditunjukkan $K$ merupakan ideal. Andaikan $K$ bukan ideal. Artinya, terdapat $k \in K$ dan $x \in R$ sehingga $kx = u \not\in K$. Karena $u \not\in K$ maka $u$ adalah unit di $R$. Perhatikan bahwa
$$
kxu^{-1} = uu^{-1} = e
$$
Artinya $xu^{-1}$ adalah invers dari $k$. Berarti $k$ adalah unit di $R$. Kontradiksi dengan pemilihan $k$ bukan unit. Berarti pengandaian salah.

Terbukti himpunan semua elemen bukan unit $K$ merupakan ideal.

### $\Leftarrow$
Misalkan $R$ suatu ring komutatif dengan elemen identitas $e$ sehingga
$$
K := \{ k \in R\  |\  k \text{ bukan unit} \}
$$
merupakan ideal. Akan ditunjukkan $R$ merupakan Ring Lokal. 

Akan ditunjukkan $K$ adalah ideal maksimal. Andaikan $K$ bukan ideal maksimal. Maka, terdapat ideal sejati $M$ dengan $K \subsetneq M \subsetneq R$. Berarti terdapat $u \in M$ namun $u \not\in K$. Berarti $u$ adalah unit. Berdasarkan [[Final KOALA 2025#Klaim 1|Klaim 1]] maka $M = R$, kontradiksi dengan $M \neq R$. Berarti pengandaian salah. Terbukti $K$ adalah ideal maksimal.

Lebih lanjut, akan ditunjukkan $K$ satu-satunya ideal maksimal di $R$. Misalkan $I$ adalah suatu ideal sejati di $R$. Andaikan terdapat $u \in I$ sehingga $u \not\in K$. Berarti $u$ adalah unit. Berdasarkan [[Final KOALA 2025#Klaim 1|Klaim 1]] maka $I = R$, kontradiksi dengan $I$ adalah ideal sejati dari $R$. Berarti pengandaian salah. Terbukti $K$ adalah satu-satunya ideal maksimal di $R$.

Karena $R$ memiliki tepat satu ideal maksimal maka $R$ adalah ring lokal.

## Definition Used

* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Lokal]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Maksimal]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Komutatif]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Unit]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Unit (Ring)]]



# No. 2
## Soal

Diberikan grup $G$ dengan sifat $Z(\text{Aut}\left({G}\right))$ merupakan subgrup nontrivial dari $\text{Aut}(G)$.
    (a) Buktikan bahwa $Z(G)$ merupakan subgrup nontrivial dari $G$.
    (b) Buktikan bahwa terdapat homomorfisma nontrivial dari $G$ ke $Z(G)$.

**Catatan:** Untuk grup $H$, $\text{Aut}\left({H}\right) = \{f: H \to H \mid f \text{ isomorfisma grup}\}$, grup terhadap komposisi fungsi, dan $Z(H) = \{x \in H \mid xh = hx \text{ untuk setiap } h \in H\}$.

## Solusi

## Definition Used

* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pusat Grup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma (Grup)]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Grup Automorfisma]]
# No. 3

## Soal

Diberikan ruang vektor $V$ atas lapangan $F$ dan transformasi linear $T: V \to V$.
    (a) Jika $\{x_1, x_2, \dots, x_k\} \subseteq V$ serta berlaku $T^m(x_m) \neq 0$ dan $T^m(x_m) = 0$ untuk setiap $m$ dengan $1 \le m \le k$, tunjukkan bahwa $\{x_1, x_2, \dots, x_k\}$ merupakan himpunan bebas linear.
    (b) Jika $V$ berdimensi hingga, tunjukkan bahwa ada bilangan bulat positif $m$ sedemikian sehingga $\text{Ker}\left({T^m}\right) \cap \mathrm{Im}(T^m) = \{0\}$.

## Solusi


## Definition Used

* [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]

# No. 4

## Soal

Misalkan $A$ dan $B$ adalah matriks-matriks berukuran $3 \times 3$ dengan entri real yang memenuhi $A^2 B + BA^2 = 2ABA$. Buktikan bahwa $(AB - BA)^3 = O_3$ dengan $O_3$ adalah matriks berukuran $3 \times 3$ yang setiap entrinya bernilai 0.

## Solusi