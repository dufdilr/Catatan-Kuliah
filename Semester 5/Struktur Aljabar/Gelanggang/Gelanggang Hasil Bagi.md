#Definisi #Teorema 

Misalkan $R$ adalah gelanggang dan $I$ adalah ideal dari $R$. Tinjau himpunan koset dari $(R, +)$ terhadap $I$ yakni
$$
R/I := \{ r + I \ | \ r \in R \}
$$
Definisikan operasi penjumlahan dan operasi perkalian di $R/I$ sebagai
$$
\begin{align*}
(a_{1}+I) + (a_{2}+I) &= (a_{1}+a_{2})+I \\
(a_{1}+I) \cdot (a_{2}+I) &= (a_{1}a_{2})+I
\end{align*}
$$
Himpunan $R/I$ dilengkapi kedua operasi di atas membentuk struktur **Gelanggang**.

---
## Bukti
### Well-Defined Operasi
Kita perlu membuktikan bahwa operasi tidak bergantung pada pemilihan wakil koset. Ambil $a, a', b, b' \in R$ sedemikian sehingga $a+I = a'+I$ dan $b+I = b'+I$. Artinya, $a' = a + i_{1}$ dan $b' = b + i_{2}$ untuk suatu $i_{1}, i_{2} \in I$.

**1. Penjumlahan**
$$
\begin{align*}
(a' + b') + I &= ((a+i_{1}) + (b+i_{2})) + I \\
&= ((a+b) + (i_{1}+i_{2})) + I
\end{align*}
$$
Karena $I$ adalah ideal (subgrup aditif), maka tertutup terhadap penjumlahan, sehingga $i_{1}+i_{2} \in I$. Maka, $((a+b) + (i_{1}+i_{2})) + I = (a+b) + I$.
Terbukti operasi penjumlahan *well-defined*.

**2. Perkalian**
$$
\begin{align*}
(a' \cdot b') + I &= ((a+i_{1})(b+i_{2})) + I \\
&= (ab + ai_{2} + i_{1}b + i_{1}i_{2}) + I
\end{align*}
$$
Karena $I$ adalah ideal, maka berlaku sifat penyerapan (absorption):
* $ai_{2} \in I$
* $i_{1}b \in I$
* $i_{1}i_{2} \in I$
Jumlah dari anggota ideal tetap berada di ideal, sebut saja $k = ai_{2} + i_{1}b + i_{1}i_{2} \in I$.
Maka, $(ab + k) + I = ab + I$.
Terbukti operasi perkalian *well-defined*.

### Grup Abelian (Penjumlahan)
Karena $(R, +)$ adalah grup abelian, sifat-sifat tersebut diwariskan ke $R/I$. Ambil $a+I, b+I, c+I \in R/I$.

**1. Asosiatif**
$$
\begin{align*}
((a+I) + (b+I)) + (c+I) &= ((a+b)+I) + (c+I) \\
&= ((a+b)+c) + I \\
&= (a+(b+c)) + I \quad (\text{sifat asosiatif di } R) \\
&= (a+I) + ((b+I) + (c+I))
\end{align*}
$$

**2. Identitas**
Elemen nol di $R/I$ adalah $0+I = I$.
$$
(a+I) + (0+I) = (a+0)+I = a+I
$$

**3. Invers**
Invers dari $a+I$ adalah $(-a)+I$ karena:
$$
(a+I) + ((-a)+I) = (a+(-a))+I = 0+I = I
$$

**4. Komutatif**
$$
(a+I) + (b+I) = (a+b)+I = (b+a)+I = (b+I) + (a+I)
$$
Terbukti $(R/I, +)$ adalah Grup Abelian.

### Asosiatif (Perkalian)
Ambil $a+I, b+I, c+I \in R/I$. Perhatikan bahwa
$$
\begin{align*}
((a+I)\cdot(b+I))\cdot(c+I) &= ((ab)+I)\cdot(c+I) \\
&= ((ab)c)+I \\
&= (a(bc))+I \quad (\text{sifat asosiatif di } R) \\
&= (a+I)\cdot((bc)+I) \\
&= (a+I)\cdot((b+I)\cdot(c+I))
\end{align*}
$$
Terbukti operasi perkalian bersifat asosiatif.

### Distributif
Ambil $a+I, b+I, c+I \in R/I$. Perhatikan distributif kiri:
$$
\begin{align*}
(a+I) \cdot ((b+I) + (c+I)) &= (a+I) \cdot ((b+c)+I) \\
&= (a(b+c)) + I \\
&= (ab + ac) + I \quad (\text{sifat distributif di } R) \\
&= ((ab)+I) + ((ac)+I) \\
&= ((a+I)\cdot(b+I)) + ((a+I)\cdot(c+I))
\end{align*}
$$
Dengan cara yang sama, sifat distributif kanan juga berlaku.

Per definisi, karena semua aksioma terpenuhi, terbukti $R/I$ membentuk struktur **Gelanggang**.

***
## Definition Used 
 * [[Gelanggang]]
 * [[Ideal (Ring)]]
 * [[Koset Gelanggang]]