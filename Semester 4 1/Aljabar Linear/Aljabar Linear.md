#Rangkuman #NotFinished 
# Ruang Vektor Umum

## [[Buat Backup/Semester 5/Struktur Aljabar/Lapangan/Lapangan]]
Misalkan $F$ adalah sebuah himpunan yang dilengkapi dengan dua operasi biner, yaitu penjumlahan ($+$) dan perkalian ($\cdot$). Himpunan $(F, +, \cdot)$ disebut **Lapangan (Field)** jika untuk setiap $a, b, c \in F$:
1.  **Asosiatif Penjumlahan:**
    $(a + b) + c = a + (b + c)$
2.  **Komutatif Penjumlahan:**
    $a + b = b + a$
3.  **Identitas Aditif (Nol):**
    Terdapat elemen $0 \in F$ sehingga $a + 0 = a$ untuk setiap $a \in F$.
4.  **Invers Aditif (Negatif):**
    Untuk setiap $a \in F$, terdapat elemen $-a \in F$ sehingga $a + (-a) = 0$.
5.  **Asosiatif Perkalian:**
    $(a \cdot b) \cdot c = a \cdot (b \cdot c)$
6.  **Komutatif Perkalian:**
    $a \cdot b = b \cdot a$
7.  **Identitas Multiplikatif (Satu):**
    Terdapat elemen $1 \in F$ (dengan $1 \neq 0$) sehingga $a \cdot 1 = a$ untuk setiap $a \in F$.
8.  **Invers Multiplikatif:**
    Untuk setiap $a \in F$ yang *taknol* ($a \neq 0$), terdapat elemen $a^{-1} \in F$ sehingga $a \cdot a^{-1} = 1$.
9.  **Distributif:**
    $a \cdot (b + c) = (a \cdot b) + (a \cdot c)$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor|Aksioma Ruang Vektor]]
Misalkan $V$ adalah suatu himpunan tak kosong dan $F$ adalah suatu *lapangan*. Himpunan $V$ disebut **Ruang Vektor** (Vector Space) atas lapangan $F$ jika pada $V$ didefinisikan dua operasi:
1.  **Penjumlahan Vektor**: Operasi biner $+ : V \times V \to V$
2.  **Perkalian Skalar**: Operasi $\cdot : F \times V \to V$

sehingga untuk setiap $u, v, w \in V$ dan $\alpha, \beta \in F$ berlaku

1.  **Sifat Asosiatif Penjumlahan**:
    $(u + v) + w = u + (v + w)$
2.  **Sifat Komutatif Penjumlahan**:
    $u + v = v + u$
3.  **Eksistensi Elemen Identitas (Vektor Nol)**:
    Terdapat elemen $\mathbf{0} \in V$, yang disebut **vektor nol**, sedemikian sehingga $v + \mathbf{0} = v$ untuk setiap $v \in V$.
4.  **Eksistensi Elemen Invers (Invers Aditif)**:
    Untuk setiap $v \in V$, terdapat elemen $-v \in V$, yang disebut **invers aditif** dari $v$, sedemikian sehingga $v + (-v) = \mathbf{0}$.
5.  **Sifat Distributif (Skalar terhadap Penjumlahan Vektor)**:
    $\alpha (u + v) = \alpha u + \alpha v$
6.  **Sifat Distributif (Vektor terhadap Penjumlahan Skalar)**:
    $(\alpha + \beta) v = \alpha v + \beta v$
7.  **Sifat Asosiatif Perkalian Skalar**:
    $(\alpha\beta) v = \alpha (\beta v)$
8.  **Eksistensi Elemen Identitas Perkalian**:
    $1v = v$, di mana $1$ adalah elemen identitas perkalian dalam lapangan $F$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Sifat Ruang Vektor]]
Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$. Maka berlaku
1. **Ketunggalan Identitas Penjumlahan** 
2. **Ketunggalan Inverse Penjumlahan**
3. **Perkalian dengan Nol** $\forall a \in \mathbb{F}, \ {v} \in V: \ a{v} = \mathbf{0} \quad \iff \quad a = 0 \text{ atau } {v} = \mathbf{0}$ ^fb9b94
4. **Perkalian Inverse Penjumlahan** $\forall {v} \in V: \ (-1){v} =  {-v}$
5. **Inverse dari Inverse** $\forall {v} \in V: \ -\left(-{v}\right) = {v}$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Lapangan Sebagai Ruang Vektor]]
Misalkan $\mathbb{F}$ adalah suatu lapangan. Maka, $\mathbb{F}$ adalah Ruang Vektor atas lapangan $\mathbb{F}$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Perkalian Kartesian Ruang Vektor]]
Misalkan $V_1, V_2, \cdots , V_n$ adalah ruang vektor atas lapangan $\mathbb{F}$. Misalkan
$$
W = V_{1} \times V_{2} \times \cdots \times V_n = \{ (v_1, v_{2}, \cdots, v_n) \ : \ v_i \in V_i \}
$$
Definisikan operasi di $W$ untuk setiap $\lambda \in \mathbb{F}$ dan $(v_1,v_{2}, \cdots , v_n), (w_1,w_{2}, \cdots , w_n) \in W$ berlaku
$$
(v_1,v_{2}, \cdots , v_n) + (w_1,w_{2}, \cdots , w_n) = (v_1 + w_{1},v_{2} + w_{2}, \cdots , v_n + w_n) 
$$
$$
\lambda \cdot (v_1,v_{2}, \cdots , v_n) = (\lambda v_1, \lambda v_{2}, \cdots , \lambda v_n)
$$
Himpunan $W$ dengan operasi tersebut membentuk **ruang vektor**.

## Contoh Ruang Vektor Standar

### [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Lapangan Sebagai Ruang Vektor|Ruang Vektor F]]
Misalkan $\mathbb{F}$ adalah suatu lapangan. Maka, $\mathbb{F}$ adalah Ruang Vektor atas lapangan $\mathbb{F}$.
### [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor Fn]]
Himpunan $\mathbb{F}^n$ dengan operasi $+$ dan perkalian skalar $\cdot$ standar membentuk **Ruang Vektor**
## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$. Subhimpunan takkosong $U \subseteq V$ disebut **subruang** dari $V$ jika $U$ membentuk ruang vektor atas $F$ dengan operasi yang sama.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Subruang]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $U$ subhimpunan takkosong $U \subseteq V$. $U$ membentuk **subruang** dari $V$ jika dan hanya jika untuk setiap ${u},{w} \in U$ dan $\lambda \in \mathbb{F}$ berlaku 
1. ${u}+ {w} \in U$
2. $\lambda \overline{u} \in U$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Kombinasi Linear dan Span]]
Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$. Misalkan pula $v_{1}, v_{2}, \cdots, v_n \in V$. Vektor $v \in V$ disebut **Kombinasi Linear** dari $v_{1}, v_{2}, \cdots, v_n$ jika terdapat $c_{1}, c_{2}, \cdots, c_n \in \mathbb{F}$ sehingga
$$
v = c_{1}v_{1} + c_{2}v_{2} + \cdots + c_nv_n = \sum_{i=1}^n c_iv_i
$$
Lebih lanjut, himpunan semua kombinasi Linear dari $v_{1}, v_{2}, \cdots, v_n$ disebut **Span**, disimbolkan
$$
\left< v_{1}, v_{2}, \cdots, v_n \right> := \left\{ \sum_{i=1}^n c_iv_i \ : \ c_{1}, c_{2}, \cdots, c_n \in \mathbb{F} \right\} 
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Span Sebagai Subruang]]
Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$. Misalkan pula $v_{1}, v_{2}, \cdots, v_n \in V$. Maka himpunan **Span** 
$$
\left< v_{1}, v_{2}, \cdots, v_n \right>
$$
membentuk **Subruang** dari $V$


## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Irisan Subruang]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2$ adalah subruang dari $V$. Maka, himpunan
$$
W = V_{1} \cap V_{2}
$$
juga membentuk subruang dari $V$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Jumlah Subruang]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$. Definisikan himpunan
$$
V_1 + V_2 + \cdots + V_n := \{ {v_1} + {v_2} + \cdots + {v_n} \ : \ {v_i} \in V_i \text{ untuk setiap } i = 1, 2, \dots , n\}
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Jumlah Subruang Sebagai Supruang Terkecil|Jumlah Subruang Sebagai Subruang V]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$. Himpunan $V_1 + V_2 + \cdots + V_n$ merupakan **Subruang Terkecil** dari $V$ yang memuat $V_1, V_2, ... , V_n$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Jumlah Langsung Subruang]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$.  Himpunan $V_1 + V_2 + \cdots + V_n$ disebut **Jumlah Langsung** apabila setiap elemen hanya dapat dituliskan **secara tunggal**.
Lebih lanjut, dituliskan jumlah langsung sebagai
$$
V_1 \oplus V_2 \oplus \cdots \oplus V_n
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Jumlah Langsung]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$.  Berlaku $V_1 + V_2 + \cdots + V_n$ adalah **Jumlah Langsung** jika dan hanya jika berlaku 
"Jika $\mathbf{0} = v_{1} + v_{2} + \cdots + v_n$ dengan $v_i \in V_i$ maka $v_i = \mathbf{0}$ untuk setiap $i$"

## [[Buat Backup/Semester 4 1/Aljabar Linear/Ruang Vektor Umum/Jumlah Langsung Dua Subruang]]
Misalkan $V$ ruang vektor atas $\mathbf{F}$ dan $U, W$ adalah subruang dari $V$. Berlaku
$$
U + W \text{ adalah Jumlah Langsung} \quad \iff \quad U\cap W = \{\overline{0}\}
$$

***
# Matriks dan Pemetaan Linear

## [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
Matriks $\mathbf{A} = [a]_{i, j}$ berukuran $m \times n$ didefinisikan sebagai **Array** 2 dimensi dengan elemen baris ke-$i$ kolom ke-$j$ adalah $a_{i,j}$, dituliskan
$$
\mathbf{A} = 
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & a_{1, 3} & \cdots  & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & a_{2, 3} & \cdots  & a_{2, n} \\
a_{3, 1} & a_{3, 2} & a_{3, 3} & \cdots  & a_{3, n} \\
& &\cdots \\
a_{m, 1} & a_{m, 2} & a_{m, 3} & \cdots  & a_{m, n}
\end{bmatrix}
$$
Himpunan matriks berukuran $m \times n$ dengan setiap elemen merupakan anggota dari lapangan $\mathbb{F}$ dinotasikan sebagai $M_{m \times n}(\mathbb{F})$.

Jika $\mathbf{A} \in M_{n \times n}(\mathbb{F})$ maka $\mathbf{A}$ disebut **Matriks Persegi**. Jika $a_{i, j} = 0$ untuk setiap $i \neq j$ maka $\mathbf{A}$ disebut **Matriks Diagonal**. Jika $a_{i, j} = 0$ untuk setiap $i > j$ maka $\mathbf{A}$ disebut **Matriks Segitiga Atas**. Jika $a_{i, j} = 0$ untuk setiap $i < j$ maka $\mathbf{A}$ disebut **Matriks Segitiga Bawah**.

### [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Operasi Matriks]]
Misalkan suatu lapangan $\mathbb{F}$. Misalkan $\mathbf{A}, \mathbf{B} \in M_{m \times n}(\mathbb{F})$. Definisikan operasi **penjumlahan matriks**
$$
\begin{align*}
\mathbf{A} + \mathbf{B} &= 
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & \cdots  & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & \cdots  & a_{2, n} \\
& &\cdots \\
a_{m, 1} & a_{m, 2} & \cdots  & a_{m, n}
\end{bmatrix}
+
\begin{bmatrix}
b_{1, 1} & b_{1, 2} & \cdots  & b_{1, n} \\ 
b_{2, 1} & b_{2, 2} & \cdots  & b_{2, n} \\
& &\cdots \\
b_{m, 1} & b_{m, 2} & \cdots  & b_{m, n}
\end{bmatrix} \\
\\
&= 
\begin{bmatrix}
a_{1, 1} + b_{1, 1} & a_{1, 2} + b_{1, 2} & \cdots  & a_{1, n} + b_{1, n} \\ 
a_{2, 1} + b_{2, 1} & a_{2, 2} + b_{2, 2} & \cdots  & a_{2, n} + b_{2, n} \\
& &\cdots \\
a_{m, 1} + b_{m, 1} & a_{m, 2} + b_{m, 2} & \cdots  & a_{m, n} + b_{m, n}
\end{bmatrix}
\end{align*}
$$
Misalkan $\mathbf{A} \in M_{m \times n}(\mathbb{F}),\ \mathbf{B} \in M_{n \times k}(\mathbb{F})$ dan $\lambda \in \mathbb{F}$. Definisikan operasi **perkalian matriks** $\mathbf{A} \cdot \mathbf{B} = \mathbf{C} = [c]_{i,j}$ dengan $\mathbf{C} \in M_{m \times k}(\mathbb{F})$ dan
$$
c_{i, j} = a_{i,1}\cdot b_{1,j} + a_{i,2}\cdot b_{2, j} + \cdots + a_{i, n} \cdot b_{n, j} = \sum_{l = 1}^n a_{i, n} \cdot b_{n, j}
$$
Didefinisikan pula operasi **perkalian skalar** 
$$
\begin{align*}
\lambda \cdot\mathbf{A} &= \lambda \cdot
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & \cdots  & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & \cdots  & a_{2, n} \\
& &\cdots \\
a_{m, 1} & a_{m, 2} & \cdots  & a_{m, n}
\end{bmatrix}
=
\begin{bmatrix}
\lambda \cdot a_{1, 1} & \lambda \cdot a_{1, 2} & \cdots  & \lambda \cdot a_{1, n} \\ 
\lambda \cdot a_{2, 1} & \lambda \cdot a_{2, 2} & \cdots  & \lambda \cdot a_{2, n} \\
& &\cdots \\
\lambda \cdot a_{m, 1} & \lambda \cdot a_{m, 2} & \cdots  & \lambda \cdot a_{m, n}
\end{bmatrix}

\end{align*}
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Identitas dan Matriks Nol]]

[[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Sifat Operasi Matriks]]
### [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Ruang Vektor Matriks]]
Misalkan suatu lapangan $\mathbb{F}$. Himpunan $M_{m \times n}(\mathbb{F})$ dengan operasi penjumlahan $+$ dan perkalian skalar $\cdot$ membentuk **Ruang Vektor** atas lapangan $\mathbb{F}$.
## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$. Fungsi $T: V \to W$ dikatakan **Pemetaan Linear** apabila
1. **Aditif**: Untuk setiap $u, v \in V$ berlaku $T(u+v) = T(u) + T(v)$
2. **Homogen**: Untuk setiap $u \in V$ dan $\alpha \in \mathbb{F}$ berlaku $T(\alpha \cdot v) = \alpha \cdot T(v)$ 

Lebih lanjut, himpunan semua pemetaan Linear dari $V$ ke $W$ dinotasikan sebagai 
$$
\mathcal{L}(V, W) := \{ T:V \to W \ \mid \ T \text{ pemetaan Linear}\}
$$
Jika $V = W$ maka dinotasikan sebagai $\mathcal{L}(V) = \mathcal{L}(V, V)$.


## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Isomorfisma (Ruang Vektor)]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$. Pemetaan Linear $T: V \to W$ dikatakan **Isomorfisma** ruang vektor apabila $T$ adalah fungsi bijektif. 

Apabila terdapat isomorfisma ruang vektor dari $V$ ke $W$ maka $V$ dan $W$ disebut **isomorfik** (Notasi: $V \cong W$).
### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear Vektor Nol]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Berlaku
$$
T(\mathbf{0_V}) = \mathbf{0_W}
$$
### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear Invers Vektor]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Untuk setiap $v \in V$ berlaku
$$
T(-v) = -T(v)
$$
### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Invers Pemetaan Linear]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Jika $T$ memiliki invers maka $T^{-1}:W \to V$ juga pemetaan Linear.

### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Komposisi Pemetaan Linear]]
Misalkan $U, V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $S \in \mathcal{L}(U, V) ;\ T \in \mathcal{L}(V, W)$. Fungsi 
$$
ST = S \circ T : U \to V
$$
adalah pemetaan linear.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear]]
Misalkan $\mathbf{A} \in M_{m \times n}(\mathbb{F})$. Kita dapat memandang matriks $\mathbf{A}$ sebagai $A: \mathbb{F}^n \to \mathbb{F}^m$ dengan
$$
A(v) := \mathbf{A}v
$$
untuk setiap $v \in \mathbb{F}^n$ dengan $\mathbf{A}v$ adalah perkalian matriks memandang yang $v \in M_{n \times 1} (\mathbb{F})$. Pemetaan yang didefinisikan di atas merupakan **pemetaan Linear**.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn]]
Misalkan $T \in \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m)$. Maka terdapat matriks $\mathbf{A_T} \in M_{m \times n}(\mathbb{F})$ sehingga untuk setiap $v \in \mathbb{F}$ berlaku
$$
T(v) = \mathbf{A_T}\cdot v
$$


## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Operasi pada Pemetaan Linear]]
Misalkan $V$ dan $W$ adalah ruang vektor atas lapangan $\mathbb{F}$. Definisikan operasi penjumlahan $+$ dan perkalian skalar $\cdot$ pada $\mathcal{L}(V, W)$ dimana untuk setiap $S, T \in \mathcal{L}(V, W)$ dan $\alpha \in \mathbb{F}$ didefinisikan
$$
\begin{align*}
(S+T)(v) &:= S(v) + T(v) \\
(\alpha \cdot T)(v) & := \alpha  T(v)
\end{align*}
$$
untuk setiap $v \in V$.
**[[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Sifat Operasi Pemetaan Linear]]**

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Ruang Vektor Pemetaan Linear]]
Misalkan $U, V$ ruang vektor atas lapangan $\mathbb{F}$. Himpunan $\mathcal{L}(U,V)$ dengan operasi penjumlahan $+$ dan perkalian skalar $\cdot$ membentuk **Ruang Vektor** atas lapangan $\mathbb{F}$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Isomorfisma Ruang Matriks dan Pemetaan Linear]]
Misalkan $C : \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m) \to M_{m \times n}(\mathbb{F})$ yang memetakan pemetaan linear ke [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn|Matriks Representasi]]. Fungsi $C$ adalah fungsi **Isomorfisma** Ruang Vektor.


## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Dekomposisi Perkalian Matriks]]
Misalkan suatu lapangan $\mathbb{F}$, $\mathbf{A} \in M_{m \times n}(\mathbb{F})$ dan $\mathbf{B} \in M_{n \times k}(\mathbb{F})$ dengan
$$
\mathbf{B} = 
\begin{bmatrix}
\mathbf{b}_{1} & \mathbf{b}_{2} & \dots & \mathbf{b}_{k}
\end{bmatrix}
$$
dimana $\mathbf{b}_{i}$ adalah vektor kolom ke $i$ dari matriks $\mathbf{B}$. Berlaku
$$
\mathbf{AB} =
\begin{bmatrix}
\mathbf{Ab}_{1} & \mathbf{Ab}_{2} & \dots & \mathbf{Ab}_{k}
\end{bmatrix}
$$
## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Representasi Komposisi L(Fn, Fm)]]
Misalkan $S \in \mathcal{L} (\mathbb{F}^n, \mathbb{F}^m)$ dan $T \in \mathcal{L}(\mathbb{F}^m, \mathbb{F}^k)$ maka
$$
\mathbf{A_TS} = \mathbf{A_T} \cdot \mathbf{A_S}
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Transpose]]
Misalkan suatu lapangan $\mathbb{F}$ dan $\mathbf{A} \in M_{m \times n} (\mathbb{F})$ dengan $\mathbf{A}_{{i, j}} = a_{i, j}$. Definisikan **Transpose** dari matriks $\mathbf{A}$ sebagai
$$
\mathbf{A}^T_{i,j} = a_{j, i}
$$
### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Sifat Transpose]]
Misalkan suatu lapangan $\mathbb{F}$, $\mathbf{A} \in M_{m \times n}(\mathbb{F})$ dan $\mathbf{B} \in M_{n \times k}(\mathbb{F})$. Berlaku:
1. $\left(\mathbf{A}^T\right)^T = \mathbf{A}$
2. $\left( \mathbf{AB} \right)^T = \mathbf{B}^T \mathbf{A}^T$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Inverse Matriks]]
Misalkan $\mathbf{A} \in M_n(\mathbb{F})$. Matriks $\mathbf{B} \in M_n(\mathbb{F})$ disebut **inverse** matriks dari matriks $\mathbf{A}$ jika
$$
\mathbf{A}\mathbf{B} = \mathbf{B}\mathbf{A} = \mathbf{I_n}
$$
Dinotasikan $\mathbf{A}^{-1} = \mathbf{B}$.

Jika terdapat $\mathbf{B}$ yang memenuhi maka $\mathbf{A}$ disebut matriks **Invertibel** atau **Nonsingular**. Jika tidak ada $\mathbf{B}$ yang memenuhi maka $\mathbf{A}$ disebut matriks **Singular**.

Kasus lain, misalkan $\mathbf{\mathbb{F}} \in M_{m \times n}(\mathbb{F})$. Matriks $\mathbf{L} \in M_{m\times n}(\mathbb{F})$ disebut **inverse kiri** dari matriks $\mathbf{A}$ jika
$$
\mathbf{L}\mathbf{A} = \mathbf{I_m}
$$
Matriks $\mathbf{R} \in M_{m\times n}(\mathbb{F})$ disebut **inverse kanan** dari matriks $\mathbf{A}$ jika
$$
\mathbf{A}\mathbf{R} = \mathbf{I_n}
$$
### [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Sifat Inverse Matriks]]
Misalkan $\mathbf{A}, \mathbf{B} \in M_n(\mathbb{F})$ invertibel maka
1. **Ketunggalan Inverse Matriks**
2. **Invers Perkalian Matriks** 
$$
(\mathbf{A}\mathbf{B})^{-1} = \mathbf{B}^{-1} \mathbf{A}^{-1}
$$
3. **Invers dari Invers**
$$
\left(\mathbf{A}^{-1}\right)^{-1} = \mathbf{A}
$$
## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Inverse Matriks Pemetaan Linear]]
Misalkan $\mathbf{A} \in M_n(\mathbb{F})$ dan $T: \mathbb{F}^n \to \mathbb{F}^n$ dengan $T(u) = \mathbf{A}u$ untuk setiap $u \in \mathbb{F}^n$. Berlaku
$$
\mathbf{A} \text{ invertibel } \iff T \text{ invertibel }
$$
Lebih lanjut, jika $\mathbf{A}$ invertibel maka $T^{-1}(u) = \mathbf{A}^{-1}u$ untuk setiap $u \in \mathbb{F}^n$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range dan Kernel Pemetaan Linear]]
Misalkan $V, W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Definisikan
$$
\ker(T) := \{ v \in V \ | \ T(v) = \mathbf{0_W} \}
$$
Secara khusus, untuk $\mathbf{A} \in M_{m \times n}(\mathbb{F})$, definisikan $\ker(\mathbf{A}) = \ker(T_A)$ dengan $T_A$ adalah pemetaan linear yang [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear|didefinisikan]] oleh $\mathbf{A}$.

Definisikan pula range dari $T$ sebagai
$$
\mathrm{Im}(T) := \{ w \in W \ | \ w = T(v), \exists v \in V \}
$$
Secara khusus, untuk $\mathbf{A} \in M_{m \times n}(\mathbb{F})$, definisikan $\text{Im}(\mathbf{A}) = \text{Im}(T_A)$ dengan $T_A$ adalah pemetaan linear yang [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear|didefinisikan]] oleh $\mathbf{A}$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range Sebagai Subruang]]
Misalkan $V, W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Himpunan $\text{Im}\left({T}\right)$ membentuk **Subruang Vektor** dari $W$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Kernel Sebagai Subruang]]
Misalkan $V, W$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Himpunan $\text{Ker}\left({T}\right)$ membentuk **Subruang Vektor** dari $V$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Range Matriks]]
Misalkan suatu lapangan $\mathbb{F}$ dan $\mathbf{A} \in M_{m \times n}(\mathbb{F})$. $\mathrm{Im}(\mathbf{A})$ adalah himpunan **Kombinasi Linear** dari vektor kolom $\mathbf{A}$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Karakterisasi Pemetaan Injektif]]
Misalkan $V, W$ ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$. Pemetaan $T$ bersifat **injektif** jika dan hanya jika $\text{Ker}\left({T}\right) = \{ \mathbf{0_V} \}$

# Vektor Eigen dan Nilai Eigen
## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Vektor dan Nilai Eigen]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$. Suatu $\lambda \in \mathbb{F}$ disebut **nilai eigen** dari transformasi $T$ apabila terdapat vektor *taknol* $v \in V$ sehingga
$$
T(v) = \lambda \cdot v
$$
Vektor $v$ disebut **vektor eigen** dari $T$ dengan nilai eigen $\lambda$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Ruang Eigen]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$ . Definisikan **Ruang Eigen-$\lambda$** sebagai
$$
\text{Eig}_{\lambda}(T) := \{ v \in V \ | \ T(v) = \lambda v \}
$$
Untuk matriks $\mathbf{A} \in M_n(\mathbb{F})$, Ruang Eigen-$\lambda$ dari $\mathbf{A}$ didefinisikan sebagai Ruang Eigen-$\lambda$ dari [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear|Pemetaan Linear yang direpresentasikan]].

Lebih lanjut, ruang eigen membentuk **Subruang Vektor** dari $V$.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Ruang Eigen Sebagai Kernel]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$. Berlaku
$$
\text{Ker}\left({T - \lambda I_V}\right) = \text{Eig}_{\lambda}(T)
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Karakterisasi Nilai Eigen]]
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$. Berlaku
$$
\lambda \text{ nilai eigen dari } T \quad \iff \quad \text{Eig}_{\lambda}(T) \neq \{ \mathbf{0_V} \}
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Nilai Eigen Pangkat]]
Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V)$. Misalkan pula $\lambda$ adalah nilai eigen dari $T$. Maka, $\lambda^k$ adalah nilai eigen dari $T^k$ dan
$$
\text{Eig}_{\lambda}(T) \subseteq \text{Eig}_{{\lambda^k}}(T^k)
$$

# Kebebaslinearan
## [[Buat Backup/Semester 4 1/Aljabar Linear/Basis dan Koordinat/Bergantung Linear]]
Misalkan $V$ ruang vektor atas lapangan $\mathbb{F}$. Suatu subhimpunan $W \subseteq V$ disebut **Bergantung Linear** jika terdapat subhimpunan berhingga $\{ \mathbf{v} _{1}, \mathbf{v} _{2},  \cdots , \mathbf{v} _n \} \subseteq W$ sehingga terdapat $a_1, a_{2}, \dots , a_n \in \mathbb{F}$ yang tak-semuanya-nol memenuhi
$$
a_{1}\mathbf{v}_{1} + a_{2}\mathbf{v}_{2}+\cdots+a_n \mathbf{v}_{n} = \mathbf{0_V}
$$
## [[Buat Backup/Semester 4 1/Aljabar Linear/Basis dan Koordinat/Bebas Linear]]
Misalkan $V$ ruang vektor atas lapangan $\mathbb{F}$. Suatu subhimpunan $W \subseteq V$ disebut **Bebas Linear** jika tidak Bergantung Linear.

## [[Buat Backup/Semester 4 1/Aljabar Linear/Basis dan Koordinat/Vektor Kolinear]]
Misalkan $V$ ruang vektor atas lapangan $\mathbb{F}$ dan $v, w \in V$. Vektor $v$ dan $w$ dikatakan **kolinear** jika terdapat $\alpha \in \mathbb{F}$ sehingga
$$
v = cw \quad \text{ atau } \quad w = cv
$$

## [[Buat Backup/Semester 4 1/Aljabar Linear/Basis dan Koordinat/Kebebaslinearan Pemetaan Injektif]]
Misalkan $V, W$ ruang vektor atas lapangan $\mathbb{F}$ dan $T \in \mathcal{L}(V, W)$ pemetaan **injektif**. Jika $\{ v_{1}, v_{2}, \dots , v_n \}$ adalah Himpunan yang Bebas Linear maka
$$
\{ T(v_{1}), T(v_{2}), \dots, T(v_n) \}
$$
juga membentuk himpunan bebas linear.