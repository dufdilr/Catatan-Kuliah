#Rangkuman #NotFinished 

# Grup
## Definisi dan Sifat Grup
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup|Aksioma Grup]]
Suatu sistem $(G, *)$ disebut **grup** jika
1.  **Asosiatif**: $\forall a, b, c \in G: \quad (a*b)*c=a*(b*c)$
2.  **Identitas**: $\exists e \in G$ sehingga $\forall a \in G: \quad a*e = e*a = a$
3.  **Invers**: $\forall a \in G, \exists b \in G : \quad a * b = b * a = e$. Selanjutnya ditulis $b = a^{-1}$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Komutatif]]
Suatu grup $(G, *)$ disebut **Grup Komutatif** atau **Abel** jika untuk setiap $a, b \in G$ berlaku
$$a*b = b*a$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Orde Grup]]
Misalkan suatu grup $(G, *)$, definisikan **orde grup**
$$o(G) = |G|$$

Lebih lanjut, jika $o(G) < \infty$ maka $G$ disebut **Grup Hingga**.
Jika $o(G) = \infty$ maka $G$ disebut **Grup Tak Hingga**

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Unsur Grup]]
Misalkan $G$ suatu grup dengan unsur identitas $e$. Didefinisikan untuk setiap $a \in G$
$$
\text{ord}(a) := \min\{n \in \mathbb{N} | a^n = e\}
$$
Jika untuk setiap $n \in \mathbb{N}$ berlaku $a^n \neq e$ maka dituliskan $\text{ord}(a) = \infty$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Sifat Grup]]
Misalkan suatu grup $(G, *)$, berlaku:
1.  **Ketunggalan Identitas**. Jika $e, e'$ adalah identitas dari $G$ maka $e = e'$
2.  **Ketunggalan Invers**. Jika $b_1$ dan $b_2$ adalah invers dari $a$ maka $b_1 = b_2$
3.  **Invers dari Invers**. $(a^{-1})^{-1} = a$
4.  **Invers**. $(a*b)^{-1} = b^{-1} * a^{-1}$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pangkat (Grup)]]
Misalkan $(G, *)$ suatu grup dengan identitas $e$ dan $a \in G$. Untuk setiap bilangan bulat $n$ didefinisikan

$$
a^n =
\begin{cases}
e & \text{jika $n =0$}\\
\underbrace{a*a*\cdots*a}_{\text{sebanyak $n$ kali}} & \text{jika $n > 0$}\\
\underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $|n|$ kali}} & \text{jika $n < 0$}\\
\end{cases}
$$
Lebih khusus, untuk grup dengan operasi $+$ dengan identitas 0 biasa dituliskan sebagai

$$
na =
\begin{cases}
0 & \text{jika $n =0$}\\
\underbrace{a+a+\cdots+a}_{\text{sebanyak $n$ kali}} & \text{jika $n > 0$}\\
\underbrace{(-a)+(-a)+\cdots+(-a)}_{\text{sebanyak $|n|$ kali}} & \text{jika $n < 0$}\\
\end{cases}
$$
#### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Operasi Pangkat (Grup)]]
Misalkan $(G, *)$ suatu grup dengan unsur identitas $e$ dan $a \in G$. Maka berlaku
* $a^m * a^n = a^{m+n}$
* $(a^m)^{-1} = a^{-m}$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Hukum Pembatalan Grup]]
Misalkan $(G, *)$ membentuk suatu grup. Misalkan $a, b, c \in G$. Berlaku
1. **Pembatalan Kiri**: Jika $ab = ac$ maka $b = c$
2. **Pembatalan Kanan**: Jika $ba = ca$ maka $b = c$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Pembatalan Grup]]
Misalkan $G$ himpunan berhingga tak-kosong sehingga $(G, *)$ merupakan sistem asosiatif. $(G, *)$ membentuk grup **Jika dan Hanya Jika** untuk setiap $a, b, c \in G$ berlaku
$$
(ab = ac \implies b = c) \quad \text{ dan } \quad (ba = ca \implies b = c)
$$

## Contoh Grup
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Zn]]
Misalkan $n$ suatu bilangan asli dan relasi [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Kongruensi Modulo]] $\sim_n$. Karena $\sim_n$ adalah [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]] maka terdapat [[Buat Backup/Prerquested/Relasi dan Fungsi/Kelas Ekuivalen]] dari relasi tersebut. Misalkan
$$[a]_{n} = \{ b \in \mathbb{Z} : a \sim_{n} b \}$$
adalah kelas ekuivalen dari $a$. Definisikan
$$\mathbb{Z}_n = \{[a]_{n} : a \in \mathbb{Z}\}$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Penjumlahan Zn]]
Himpunan $\mathbb{Z}_{n}$ dengan operasi penjumlahan pada $\mathbb{Z}_{n}$ membentuk grup komutatif.
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Un]]
Untuk suatu bilangan asli $n$, didefinisikan
$$U_n = \{[a]_{n} \in \mathbb{Z}_n \quad | \quad (a, n) = 1\}$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Perkalian Un]]
Himpunan $U_n$ dengan operasi perkalian pada $\mathbb{Z} _n$ membentuk grup.

### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]
Definisikan $\varphi: \mathbb{N} \to \mathbb{N}$ sebagai
    $$\varphi(n) = |U_n|$$
## Subgrup
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup|Definisi Subgrup]]
Misalkan $(G, *)$ suatu grup dan subhimpunan tak-kosong $H \subseteq G$. $H$ disebut **subgrup** dari $G$ (notasi: $H \le G$) jika $(H, *)$ membentuk grup.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Subgrup]]
Misalkan $G$ suatu dan subhimpunan tak-kosong $A \subseteq G$. $A$ adalah **[[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup|subgrup]]** dari $G$ jika dan hanya jika untuk setiap $a, b \in A$ berlaku

$$
ab^{-1} \in A
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pusat Grup]]
Misalkan $G, *$ suatu grup. Didefinisikan **pusat** dari grup $G$ adalah
$$
Z(G) := \{ x \in G\ |\ \forall g \in G: \ xg = gx \}
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pemusat Grup]]
Misalkan $(G, *)$ membentuk grup dan $H \leq G$. Definisikan **pemusat** $H$ di $G$ sebagai
$$
C_H(G) := \{ g \in G \ |\ \forall h \in H:\ gh = hg  \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Pemusat]]
Misalkan $(G, *)$ membentuk grup dan $H \leq G$. Himpunan pemusat $H$ di $G$ yakni $C_H(G)$ membentuk subgrup dari $G$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Perkalian Unsur dan Subgrup]]
Misalkan $G$ adalah grup dan $A \subseteq G$. Untuk setiap $g \in G$, 
$$
gAg^{-1} := \{ gag^{-1} \ \mid \ a \in A \}
$$
membentuk subgrup dari $G$.


## Grup Siklik
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subhimpunan Terbangun]]
Misalkan $(G, *)$ suatu grup. Didefinisikan untuk setiap $a \in G$
$$

\langle a \rangle := \{a^n : n \in \mathbb{Z}\}

$$

$a$ disebut unsur pembangun dari  $\langle a \rangle$.
Lebih lanjut, untuk setiap $A \subseteq G$ didefinisikan
$$
\langle A \rangle := \{a_1^{n_1}*a_2^{n_2}*\cdots*a_k^{n_k} : n_i \in \mathbb{Z}, a_i \in A\}
$$
$A$ disebut himpunan pembangun dari  $\langle A \rangle$.
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Terbangun]]
Misalkan $(G, *)$ suatu grup dan $A \subseteq G$ maka $\langle A \rangle$ adalah **subgrup** dari $G$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]
Misalkan $(G, *)$ suatu grup. $G$ disebut **Grup Siklik** jika terdapat $a \in G$ sehingga
$$
G = \langle a \rangle
$$


### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Unsur Pembangun]]
Jika $G = \left< a \right>$ grup siklik maka
$$
\text{ord}(a) = \text{ord}(G)
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Grup Siklik]]
Misalkan $G$ suatu grup berhingga. $G$ adalah **grup siklik** jika dan hanya jika terdapat $a \in G$ sehingga
$$
\text{ord}(a) = \text{ord}(G)
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik Zn]]
Misalkan $n \in \mathbb{N}$ dengan $n > 1$. $\mathbb{Z}_{n}$ adalah grup siklik. Lebih lanjut, $[x]_{n} \in \mathbb{Z}_{n}$ adalah pembangun dari $\mathbb{Z}_{n}$ jika dan hanya jika $(x, n) = 1$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pangkat Pembangun]]
Misalkan $A$ adalah grup siklik dengan $|A| = n$ dan pembangun $a$. Unsur $a^k$ adalah pembangung dari $A$ jika dan hanya jika $(n, k) = 1$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pangkat Identitas]]
Misalkan $G$ suatu grup dengan elemen identitas $e$ dan $a \in G$. Berlaku
$$
a^n = e \quad \iff \quad \text{ord}\left({a}\right) \mid n
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Kesamaan Pangkat]]
Misalkan $G$ suatu grup dengan identitas $e$ dan $a \in G$ sehingga $\text{ord}\left({a}\right) = k < \infty$. Berlaku
$$
a^i = a^j \quad \iff \quad i \equiv j \mod \text{ord}\left({a}\right)
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Pangkat]]
Misalkan $G$ suatu grup dan $a \in G$ dengan $\text{ord}\left({a}\right) = t$ dan $u \in \mathbb{N}$. Maka berlaku
$$
\text{ord}\left({a^u}\right) = \frac{t}{(t, u)}
$$

## Grup Permutasi

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Himpunan Sn]]
Untuk setiap bilangan asli $n$, misalkan $\mathbb{N}_{n} := \{ 1, 2, \cdots n \}$. Definisikan
$$
S_n := \{ \sigma:\mathbb{N}_{n} \to \mathbb{N}_{n} \quad|\quad \sigma \text{ bijeksi}  \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Grup Permutasi Sn]]
Himpunan $(S_n, \circ)$ dengan operasi komposisi membentuk **grup**

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Siklus Permutasi]]
Siklus $(a_1, \ a_2, \ \cdots \ , \ a_k) \in S_n$ didefinisikan sebagai permutasi $\sigma \in S_n$ dengan
$$
\sigma(a_i) = a_{i+1}
$$
dengan $a_{k + 1} =a_1$. Jika terdapat elemen yang tidak ada di array maka elemen tersebut adalah elemen tetap artinya $\sigma(b) = b$ jika $b \notin [\sigma]$. 

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Grup Permutasi S(G)]]
Misalkan $G$ adalah suatu himpunan. Definisikan
$$
S(G) := \{ \sigma:G \to G \quad|\quad \sigma \text{ bijeksi}  \}
$$
Himpunan $(S(G), \circ)$ dengan operasi komposisi membentuk **grup**.

## Relasi Subgrup dan Koset
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Relasi Subgrup]]
Misalkan $G$ suatu grup dan $S \le G$. Definisikan relasi $\sim_S$ di $G$ sebagai
$$
a \sim_S b \quad\iff\quad a^{-1}b \in S
$$
Relasi ini membentuk relasi ekuivalen di $G$.
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Himpunan Hasil Bagi]]
Misalkan $G$ suatu grup dan $S \le G$. Definisikan
$$
G/S = G/\sim_S
$$
yakni kelas-kelas ekivalen yang didapatkan dari [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Relasi Subgrup]].

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Koset Grup]]
Misalkan $G$ suatu grup dan $S \le G$. Definisikan untuk $a \in G$
$$
\begin{align*}
aS &= \{ as \ | \ s \in S \} \\
Sa &= \{ sa\ | \ s \in S \}
\end{align*}
$$
Himpunan $aS$ disebut **koset kiri** dari $S$ sedangkan $Sa$ disebut **koset kanan** dari $S$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Himpunan Hasil Bagi dan Koset Grup]]
Misalkan $[a]$ adalah kelas hasil bagi dari [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Relasi Subgrup]]. Maka berlaku
$$
[a] = aS
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Kesamaan Koset]]
Misalkan grup $G$ dan $S \le G$. Misalkan pula $aS, bS \in G/S$. 
$$
aS = bS \quad \iff \quad a^{-1}b \in S
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Perkalian Subgrup]]
Misalkan $G$ suatu grup dan $S \le G$. Untuk setiap $a \in G$ berlaku
$$
\text{ord} (aS) = \text{ord}(S)
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Indeks Subgrup]]
Misalkan $G$ suatu grup dan $S \le G$. Banyak koset kiri di $G/S$ disebut sebagai **Indeks** dari subgrup $S$ dan dinotasikan sebagai
$$
[G:S] := |G/S|
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Teorema Lagrange]]

Misalkan $G$ suatu grup dan $S \le G$. Maka
$$
\text{ord}(S) | \text{ord}(G)
$$
Lebih lanjut
$$
\text{ord}(G) = [G:S] \cdot\text{ord}(S)
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Order Unsur Lagrange]]
Misalkan $a \in G$ maka
$$
\text{ord}(a) \mid \text{ord}(G)
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Grup Siklik Orde Prima]]
Misalkan $G$ adalah grup dengan $\text{ord}(G) = p$ untuk suatu bilangan prima $p$. Maka, $G$ adalah grup siklik.

## Subgrup Normal

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal|Definisi Subgrup Normal]]
Misalkan $G$ adalah suatu grup dan $N \le G$. $N$ disebut **Subgrup Normal** dari $G$ jika untuk setiap $g\in G$ dan $n \in N$ berlaku
$$
g n g^{-1} \in N
$$
dan dinotasikan sebagai $N \unlhd G$ .

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Karakterisasi Subgrup Normal]]
Misalkan $G$ adalah suatu grup dan $N \le G$. Pernyataan berikut ekuivalen:
1. $N$ adalah subgrup normal dari $G$.
2. $g ^{-1} N g \subseteq N$ untuk setiap $g \in G$.
3. $g^{-1}Ng = N$ untuk setiap $g \in G$.
4. $Ng = gN$ untuk setiap $g \in G$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal dari Grup Komutatif]]
Jika $G$ adalah grup komutatif maka setiap subgrup $H \le G$ adalah subgrup normal dari $G$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Pusat Grup Sebagai Subgrup Normal]]
Misalkan $G$ adalah suatu grup, maka $Z(G) \unlhd G$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Orde Tunggal Sebagai Subgrup Normal]]
Misalkan $G$ suatu grup dan $A \le G$ adalah satu-satunya subgrup dari $G$ berorde $n$. Maka
$$
A \unlhd G
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal dari Subgrup]]
Misalkan $A$ adalah grup dan $B \le A$ dan $N \unlhd A$. Maka berlaku
$$
(B\cap N) \unlhd B \quad \text{ dan } \quad BN \unlhd N
$$


## Grup Hasil Bagi
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Grup Hasil Bagi]]
Misalkan $G$ grup dan $N \unlhd G$, maka $G/N$ dilengkapi dengan operasi
$$
aN * bN  = (a*b)N
$$
membentuk suatu grup.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Pemusat Siklik dan Grup Komutatif]]
Misalkan $A$ adalah suatu grup dan $Z(A)$ adalah pusat $A$. Jika $A/Z(A)$ adalah grup siklik maka $A$ adalah grup komutatif.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Teorema Lagrange/Eksistensi Unsur Order Prima di Grup Komutatif]]
Misalkan $A$ grup komutatif. Jika $p$ bilangan prima sehingga $p \mid \text{ord}(A)$ maka terdapat $a \in A$ sehingga
$$
\text{ord}(a) = p
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Subgrup Normal dari Grup Hasil Bagi]]
Misalkan $G$ grup dan $N \unlhd G$ maka setiap subgrup normal dari $G/N$ adalah $K/N$ dengan $K \unlhd G$ dan $N \subseteq K \subseteq G$.

# Homomorfisma dan Isomorfisma Grup
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma (Grup)]]
Misalkan $(G_1, *)$ dan $(G_2, \cdot)$ adalah grup. Fungsi $f:R_1 \to R_2$ disebut **homomorfisma** jika $\forall a, b \in G_1$:
$$
f(a *b) = f(a) \cdot f(b)
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Sifat Homomorfisma Grup]]
Misalkan $A$ dan $B$ adalah grup dengan identitas $e_A$ dan $e_B$ berturut turut. Misalkan pula $f:A \to B$ adalah **homomorfisma grup** dan $S \le A$. Maka berlaku
1. $f(e_A) = e_B$
2. Untuk setiap $a \in A$ berlaku $f(a^{-1}) = \left( f(a) \right)^{-1}$
3. $f(S)$ merupakan subgrup dari $B$
4. Untuk setiap $a \in A$ dan $n \in \mathbb{N}$ berlaku $f(a^n) = (f(a))^n$
5. Jika $S$ adalah grup komutatif maka $f(S)$ juga grup komutatif.
6. Jika $S$ adalah grup siklik maka $f(S)$ juga grup siklik.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Komposisi Homomorfisma Grup]]
Misalkan $A, B, C$ grup serta $f:A \to B$ dan $g:B \to C$ keduanya adalah homomorfisma grup. Maka
$$
g\circ f : A \to C
$$
juga merupakan homomorfisma grup.
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inti Homomorfisma Grup]]
Misalkan $A$ dan $B$ adalah grup dengan identitas $e_A$ dan $e_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma grup. Definisikan
$$
\text{Inti} (f) = \text{Ker}\left({f}\right) := \{ a \in A \ \mid \ f(a) = e_B \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inti Homomorfisma Sebagai Subgrup Normal]]
Misalkan $A, B$ adalah grup dengan identitas $e_A$ dan $e_B$ berturut-turut serta $f:A \to B$ adalah homomorfisma grup. Maka $\text{Inti} f$ membentuk subgrup normal dari $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Subgrup Normal Sebagai Inti Homomorfisma]]
Misalkan $A$ suatu grup dengan elemen identitas $e_A$ dan $N \unlhd A$. Maka, terdapat grup $B$ dengan identitas $e_B$ dan homomorfisma $f:A \to B$ sedemikian sehingga
$$
\text{Inti} f = N
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma Zn]]
Misalkan $m, n,k \in \mathbb{N}$ dengan $n \mid km$. Maka fungsi $\phi:\mathbb{Z}_{m} \to \mathbb{Z}_{n}$ dengan
$$
\phi([x]_{m}) = [kx]_{n}
$$
merupakan homomorfisma. Lebih lanjut, misalkan $f: \mathbb{Z}_{m} \to \mathbb{Z}_{n}$ adalah homomorfisma maka
$$
f([x]_{m}) = [\alpha x]_{n}
$$
untuk suatu $[\alpha] \in \mathbb{Z}_{n}$ sehingga $n \mid \alpha m$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Karakterisasi Homomorfisma Injektif]]
Misalkan $A, B$ grup dengan unsur identitas $e_A$ dan $e_B$ berturut-turut serta $f:A \to B$ adalah homomorfisma grup. Fungsi $f$ adalah homomorfisma injektif jika dan hanya jika
$$
\mathrm{Inti}(f) = \{ e_A \}
$$

## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma (Grup)]]

Misalkan $(G_1, *)$ dan $(G_2, \cdot)$ adalah grup. Fungsi $f:R_1 \to R_2$ disebut **isomorfisma** jika $f$ homomorfisma grup yang bijektif. Dengan kata lain $\forall a, b \in G_1$:
1. $f(a *b) = f(a) \cdot f(b)$
2. Jika $f(a) = f(b)$ maka $a = b$.
3. Untuk setiap $c \in G_2$ terdapat $g \in G_1$ sehingga $f(g) = c$.

Kemudian, jika terdapat fungsi isomorfisma dari grup $G_1$ ke grup $G_2$ maka $G_1$ isomorfik dengan $G_2$ (notasi: $G_1 \cong G_2$)

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Sifat Isomorfisma Grup]]
Misalkan $A, B$ grup dan $f:A \to B$ adalah **isomorfisma grup**. Maka
1. Jika $A$ siklik maka $B$ juga siklik.
2. Jika $A$ komutatif maka $B$ juga komutatif.
3. $f(Z(A)) = Z(B)$
4. Untuk setiap $a \in A$ berlaku $\text{ord}(a) = \text{ord}(f(a))$


### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma Grup Siklik]]
Misalkan $A$ adalah grup siklik dengan $\text{ord}(A) = n$ maka
$$
A \cong \mathbb{Z}_{n}
$$
Jika $\text{ord}(A) = \infty$ maka
$$
A \cong \mathbb{Z}
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Automorfisma Grup]]
Misalkan $G$ adalah suatu grup. Fungsi isomorfisma $f: G \to G$ disebut **Automorfisma** dari $G$. Definisikan himpunan seluruh automorfisma pada $G$ sebagai
$$
\text{Aut}\left({G}\right) = \{f: G \to G \mid f \text{ isomorfisma grup}\}
$$
Lebih lanjut, himpunan $\text{Aut}\left({G}\right)$ dilengkapi dengan operasi komposisi membentuk [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Permutasi/Grup Automorfisma]].

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inner Automorfisma]]
Misalkan $A$ suatu grup dan $a \in A$. Definisikan **Automorfisma Dalam** pada $A$ dengan indeks $a$ adalah pemetaan $f_a: A \to A$ dengan
$$
f_a (x) = axa^{-1}
$$
untuk setiap $x \in A$. Pemetaan ini membentuk automorfisma pada $A$. Lebih lanjut, himpunan
$$
\mathrm{Inn}(A) := \{ f_a(x) \mapsto axa^{-1} \ | \ a \in A \} \subseteq \text{Aut}\left({A}\right)
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Inner Automorfisma Sebagai Subgrup Normal]]
Misalkan $A$ adalah grup. Himpunan $\mathrm{Inn}(A)$ dilengkapi dengan operasi komposisi membentuk **Subgrup Normal** dari $\text{Aut}\left({A}\right)$. Dengan kata lain
$$
\mathrm{Inn}(A) \unlhd \text{Aut}\left({A}\right)
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Titik Tetap Automorfisma Grup]]
Misalkan $A$ suatu grup dan $\phi:A \to A$ adalah suatu automorfisma pada $A$. Himpunan
$$
H := \{ a \in A \ \mid \ \phi(a) = a \}
$$
membentuk subgrup dari $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Automorfisma Zn]]
Misalkan $n,k \in \mathbb{N}$ dengan $(n, k) = 1$. Maka fungsi $\phi:\mathbb{Z}_{n} \to \mathbb{Z}_{n}$ dengan
$$
\phi([x]_{n}) = [kx]_{n}
$$
merupakan automorfisma pada $\mathbb{Z}_{n}$. Lebih lanjut, misalkan $f: \mathbb{Z}_{n} \to \mathbb{Z}_{n}$ adalah automorfisma pada $\mathbb{Z}_{n}$ maka
$$
f([x]_{n}) = [\alpha x]_{n}
$$
untuk suatu $[\alpha] \in \mathbb{Z}_{n}$ sehingga $(a,n) = 1$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Automorfisma Zn dan Un]]
Misalkan $n \in \mathbb{N}$ berlaku
$$
\text{Aut}\left({\mathbb{Z}_{n}}\right) \cong U_n
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Teorema Cayley]]
Misalkan $G$ adalah suatu grup. Maka berlaku
$$
G \cong H \le S\left({G}\right)
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Teorema Isomorfisma Pertama (Grup)]]
Misalkan $f:A \to B$ adalah homomorfisma maka
$$
A/\mathrm{Inti}(f) \cong f(A)
$$

```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}[row sep=huge, column sep=huge]
    % Top left node (G) to Top right node (H)
    A \arrow[r, "f"] \arrow[d, "\pi"'] 
    & f(A) \\
    % Bottom left node (Quotient Group)
    A/\ker(f) \arrow[ur, dashed, "\phi"']
\end{tikzcd}
\end{document}
```
## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Teorema Isomorfisma Kedua (Grup)]]
Misalkan $A$ adalah grup dan $B \le A$ dan $C \unlhd A$. Maka berlaku
$$
B/(B \cap N)  \cong BN/N
$$

## [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Teorema Isomorfisma Ketiga (Grup)]]
Misalkan $A$ suatu grup dan $C \unlhd B \unlhd A$. Maka berlaku
$$
(A/C)/(B/C) \cong A/B
$$

***
# Gelanggang

## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang|Definisi Gelanggang]]
Sistem $(R, +, \cdot)$ disebut **gelanggang** jika memenuhi
1.  $(R, +)$ membentuk Grup Komutatif
2.  $(R, \cdot)$ membentuk Sistem Asosiatif.
3.  $(R, +, \cdot)$ berlaku distributif kiri dan kanan yakni
    1.  $\forall a, b, c \in \mathbb{Z}: \quad (a + b)\cdot c=a\cdot c + b\cdot c$
    2.  $\forall a, b, c \in \mathbb{Z}: \quad a\cdot(b + c) = a\cdot b + a\cdot c$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Unit]]
Misalkan $(R, +, \cdot)$ suatu gelanggang. $R$ dikatakan *gelanggang unit* (atau *gelanggang dengan unsur satuan*) jika terdapat unsur $1 \in R/\{0\}$ sehingga untuk setiap $a \in R$ berlaku
$$
a \cdot 1 = 1 \cdot a = a
$$
Lebih lanjut, unsur $1$ yang memenuhi sifat tersebut disebut sebagai *unsur satuan*.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Komutatif]]
Misalkan $(R, +, \cdot)$ suatu gelanggang. $R$ dikatakan *gelanggang komutatif* jika untuk setiap $a, b \in R$ berlaku
$$
a \cdot b = b \cdot a
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Sifat Gelanggang]]
Misalkan $(R, +, \cdot)$ suatu gelanggang. Maka berlaku
1. **Perkalian Nol:** Untuk setiap $a \in R$ berlaku $a\cdot 0 = 0 \cdot a = 0$
2. **Perkalian Inverse Penjumlahan:** Untuk setiap $a, b \in R$ berlaku $a(-b) = (-a)b = -(ab)$
3. **Perkalian Dua Inverse:** Untuk setiap $a, b, c \in R$ berlaku $(-a)(-b) = ab$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Gelanggang Komutatif]]
Misalkan $R$ adalah suatu gelanggang. $R$ adalah gelanggang komutatif jika dan hanya jika untuk setiap $a, b \in R$ berlaku
$$
a^2 - b^2 = (a+b)(a-b)
$$


## Contoh Gelanggang
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Mn(R)]]
Misalkan $R$ suatu gelanggang. Sistem $(M_n({R}), +, \cdot)$ membentuk struktur gelanggang.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Z]]
Sistem $(\mathbb{Z}, +, \cdot)$ membentuk struktur gelanggang.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Zn]]
Sistem $(\mathbb{Z}_{n}, +, \cdot)$ membentuk struktur Gelanggang Komutatif dengan Unit
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Subgelanggang]]
Misalkan $(R, +, \cdot)$ adalah suatu gelanggang. Himpunan tak-kosong $K \subseteq R$ disebut **subgelanggang** dari $R$ jika $(K, + , \cdot)$ juga membentuk gelanggang.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang]]
Misalkan $(R, +, \cdot)$ suatu gelanggang dan $K \subseteq R$ subhimpunan tak-kosong. $K$ adalah *subgelanggang* dari $R$ jika dan hanya jika untuk setiap $x, y \in K$ berlaku
1. $x - y \in K$
2. $xy \in K$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Annihilator Gelanggang]]
Misalkan $R$ suatu gelanggang dan $a \in R$. Himpunan *annihilator* didefinisikan sebagai
$$
\text{ann}(a) := \{ r \in R \ \mid \ ra = 0 \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Annihilator Sebagai Subgelanggang]]
Misalkan $R$ suatu gelanggang dan $a \in R$. Himpunan $\text{ann}(a)$ membentuk subgelanggang dari $R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Pusat Gelanggang]]
Misalkan $R$ adalah suatu gelanggang. Definisikan
$$
Z(R) := \{ r \in R \ | \ \forall x \in R: xr = rx \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Pusat Gelanggang Sebagai Subgelanggang]]
Misalkan $R$ adalah suatu gelanggang. Maka $Z(R)$ membentuk subgelanggang dari $R$.

# Daerah Integral dan Lapangan

## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Integral]]
Suatu gelanggang Komutatif dengan Unsur Kesatuan $(R, +, \cdot)$. Gelanggang $R$ disebut **Daerah Integral** jika setiap unsur tak-nol bukan pembagi nol. Dengan kata lain, untuk setiap $a, b \in R$ dengan $ab = 0$ maka $a = 0$ atau $b = 0$.

### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Unsur Pembagi Nol (Ring)]]
Misalkan suatu gelanggang $(R, +, \cdot)$ dan $a \in R$. Elemen $a \neq 0$ disebut **pembagi nol kiri** jika terdapat $x \in R$ dengan $x \neq 0$ sehingga
$$
ax= 0
$$
Serupa, elemen $a$ disebut **pembagi nol kanan** jika terdapat $y \in R$ dengan $y \neq 0$ sehingga
$$
ya = 0
$$
Jika $a$ adalah pembagi nol kiri dan pembagi nol kanan maka $a$ disebut **pembagi nol dua-sisi**.

Jika $R$ gelanggang komutatif maka kita sebut **pembagi nol** jika memenuhi salah satu (maka ketiganya).

### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Unsur Nilpoten (Ring)]]
Misalkan suatu gelanggang $(R, +, \cdot)$ dan $a \in R$. Elemen $a$ disebut **nilpoten** jika terdapat $n \in \mathbb{N}$ sehingga
$$
a^n = 0
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Unit (Ring)]]
Misalkan $(R, +, \cdot)$ suatu gelanggang dengan unsur satuan $1$. Suatu unsur $u \in R$ dikatakan *unsur unit* jika terdapat $u^{-1} \in R$ sehingga
$$
u \cdot u^{-1} = u^{-1} \cdot u = 1
$$
Lebih lanjut, himpunan semua unit di $R$ dinotasikan sebagai
$$
R^\times := \{ u \in R \ | \ u \text{ merupakan unit di } R \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Prima (Ring)]]
Misalkan ($R, +, \cdot$) suatu gelanggang komutatif dengan unit. Elemen $p$ disebut **unsur prima** jika:
1.  $p$ tak nol dan bukan unsur unit
2.  Jika $p \mid ab$ maka $p \mid a$ atau $p \mid b$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Tak Tereduksi (Ring)]]
Misalkan ($R, +, \cdot$) suatu gelanggang komutatif dengan unit. Elemen $p$ disebut **unsur tak tereduksi** jika berlaku
$$
\text{Jika } p = ab \quad \text{ maka } \quad a \text{ unit atau } b \text{ unit}
$$
Lebih lanjut, elemen $q$ disebut **unsur tereduksi** jika terdapat $a, b$ bukan unit sehingga $q = ab$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Sekawan (Ring)]]
Misalkan suatu gelanggang komutatif dengan unsur satuan $(R, +, \cdot)$. Elemen $a, b \in R$ dikatakan **sekawan** (notasi: $a \sim b$) jika
$$a = b \cdot u$$
untuk suatu $u$ unit dari $R$.

### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Hukum Pembatalan (Daerah Integral)]]
Misalkan $D$ suatu gelanggang komutatif unit. Gelanggang $D$ membentuk **daerah integral** jika dan hanya jika untuk setiap $a, b, c \in D$ dengan $a \neq 0$ berlaku
$$ab = ac \quad \Rightarrow \quad b = c$$

## [[Buat Backup/Semester 5/Struktur Aljabar/Lapangan/Lapangan]]
Suatu gelanggang komutatif dengan unit $(F, +, \cdot)$ disebut **lapangan** setiap unsur taknol di $F$ memiliki invers perkalian.
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Lapangan Sebagai Daerah Integral]]
Jika $(R, +, \cdot)$ suatu lapangan maka $(R, +, \cdot)$ membentuk Daerah Integral.
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Integral Berhingga Sebagai Lapangan]]
Setiap daerah integral yang berhingga adalah lapangan.
### [[Buat Backup/Semester 5/Struktur Aljabar/Lapangan/Lapangan Zp]]
Gelanggang $\mathbb{Z}_{p}$ adalah **Lapangan** jika dan hanya jika $p$ adalah bilangan prima.

# [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Homomorfisma (Ring)]]
Misalkan $R_1, R_2$ gelanggang. Fungsi $f:R_1 \to R_2$ disebut **homomorfisma** jika $\forall a, b \in R_1$:
1.  $f(a + b) = f(a) + f(b)$
2.  $f(a\cdot b) = f(a) \cdot f(b)$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Sifat Homomorfisma Gelanggang]]
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Maka berlaku
1. $f(0_A) = 0_B$
2. $f(A)$ membentuk subgelanggang dari $B$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Inti Homomorfisma Gelanggang]]
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Definisikan
$$
\text{Inti} (f) = \text{Ker}\left({f}\right) := \{ a \in A \ \mid \ f(a) = 0_B \}
$$
# [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal (Ring)]]
Misalkan $(R, +, \cdot)$ adalah suatu gelanggang. Suatu himpunan tak-kosong $I \subseteq R$ disebut **ideal kiri** apabila untuk setiap $r \in R$ dan $x, y \in I$ berlaku
1. $x + y \in I$
2. $-x \in I$
3. $rx \in I$

Serupa, $I$ disebut **ideal kanan** apabila untuk setiap $r \in R$ dan $x, y \in I$ berlaku
1. $x + y \in I$
2. $-x \in I$
3. $xr \in I$

Lebih lanjut, $I$ disebut **ideal** apabila $I$ adalah *ideal kiri* dan *ideal kanan*.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Sejati]]
Misalkan $R$ suatu gelanggang dan $I$ adalah ideal dari $R$. Ideal $I$ disebut **Ideal Sejati** jika $I \neq  R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Trivial]]
Misalkan $R$ adalah suatu gelanggang. Himpunan nol $\{ 0 \}$ membentuk ideal dari $R$ dan disebut sebagai **Ideal Trivial** dari $R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Sebagai Subgelanggang]]
Jika $I$ ideal dari gelanggang $R$ maka $I$ adalah subgelanggang dari $R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal dengan Unit]]
Misalkan $I$ suatu ideal dari gelanggang unit $R$. Jika terdapat $u \in I$ dengan $u$ adalah elemen [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Unit (Ring)|unit]] dari $R$ maka $I = R$.

### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Ideal Lapangan]]
Ideal dari Lapangan $\mathbb{F}$ adalah $\{0\}$ dan $\mathbb{F}$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Annihilator Sebagai Ideal]]
Misalkan $R$ suatu gelanggang komutatif dan $a \in R$. Himpunan $\text{ann}(a)$ membentuk ideal dari $R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Inti Homomorfisma Sebagai Ideal]]
Misalkan $A$ dan $B$ adalah gelanggang dengan identitas nol $0_A$ dan $0_B$ berturut turut. Misalkan pula $f:A \to B$ adalah homomorfisma gelanggang. Maka $\mathrm{Inti}(f)$ membentuk ideal dari $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Irisan Ideal]]
Misalkan $A$ adalah gelanggang dan $I_{1}, I_{2}$ keduanya adalah ideal dari $A$. Maka
$$
I = I_{1} \cap I_{2}
$$
juga merupakan ideal bagi $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Jumlah Ideal]]
Misalkan $A$ adalah gelanggang dan $I_{1}, I_{2}$ keduanya adalah ideal dari $A$. Maka
$$
I = I_{1} + I_{2} := \{ i_{1}+i_{2} \ | \ i_{1} \in I_{1}, i_{2} \in I_{2} \}
$$
juga merupakan ideal bagi $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Perkalian Ideal]]
Misalkan $A$ adalah gelanggang dan $I_{1}, I_{2}$ keduanya adalah ideal dari $A$. Maka
$$
I = I_{1} I_{2} := \left\{  \sum_{k=1}^n x_k y_k \ | \ n \in \mathbb{N}, \  x_k \in I_{1}, y_{k} \in I_{2}  \right\}
$$
juga merupakan ideal bagi $A$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal dari Subgelanggang]]
Misalkan $A$ adalah gelanggang dan $B$ adalah subgelanggang dari $A$. Jika $I$ adalah ideal dari $A$ maka $(B \cap I)$ adalah ideal dari $B$. Lebih lanjut, $I$ juga ideal dari $I + B$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Terbangun]]
Misalkan $(R, +, \cdot)$ suatu gelanggang komutatif $r_1, r_2, r_3, \cdots , r_n \in R$ maka
$$I = \langle r_1, r_2, \cdots, r_n \rangle = \{s_1r_1+s_2r_2 + \cdots + s_nr_n \quad | \quad s_1, s_2, \cdots, s_n \in R\}$$
juga membentuk ideal dari $R$. Kita sebut $I$ sebagai ideal yang dibangun oleh himpunan $\{ r_1, r_2, r_3, \cdots , r_n  \}$

## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Utama]]
Misalkan suatu gelanggang komutatif $(R, +, \cdot)$. Misalkan $r \in R$. Definisikan
$$\langle r \rangle = \{sr \quad | \quad s \in R\}$$
$\langle r \rangle$ adalah ideal dari $R$. Lebih lanjut $I = \langle r \rangle$ disebut sebagai ideal utama.
## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]]
Suatu daerah integral $D$ disebut **Daerah ideal Utama** jika setiap ideal $I$ dari $D$ dibangun oleh satu unsur. Dengan kata lain jika $I$ suatu ideal dari $D$ maka
$$I = \langle d\rangle = \{dk \quad | \quad k \in D \}\quad \exists \ d \in D$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Kesamaan Ideal Utama]]
Misalkan $D$ adalah daerah integral dan $p, q \in D$. Maka berlaku
$$
\left< p \right>  = \left< q \right>  \iff p, q \text{ sekawan}
$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Teorema Bezout (Daerah Ideal Utama)]]
Misalkan $D$ Daerah Ideal Utama, maka $\forall a, b \in D$ ada $d \in D$ secara unik (hingga sekawan) sehingga $d = (a, b)$ dan
$$d = sa + tb \quad \exists s, t \in D$$
Dengan kata lain jika $d = (a, b) = d'$ maka $d \sim d'$.
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Unsur Prima Daerah Ideal Utama]]
Misalkan $D$ Daerah Ideal Utama dan $p \in D$ unsur taknol bukan unit.
$$p \text{ prima} \quad \iff \quad \text{Jika }\ p = ab \ \text{ maka } \ a\ \text{ unit atau } \ b\ \text{ unit}$$
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Rantai Ideal Sejati]]
Misalkan $D$ Daerah Ideal Utama dan $\{I_n\}$ adalah ideal-ideal **sejati** dari $D$ dengan
$$I_1 \subseteq I_2 \subseteq I_3 \subseteq \cdots $$
maka terdapat $n \in \mathbb{N}$ sehingga $I_k = I_n \quad \forall k \ge n$.
## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Faktorisasi Tunggal]]
Suatu daerah integral $D$ disebut **Daerah Faktorisasi Tunggal** jika untuk setiap $a\in D$ taknol, bukan unit
$$a = u \cdot p_1 \cdot p_2 \cdots p_n$$
dengan $u$ unit dan $p_i$ prima secara tunggal (tanpa memperdulikan urutan atau sekawan). Dengan kata lain jika
$$a = u \cdot p_1 \cdot p_2 \cdots p_n = v \cdot q_1 \cdot q_2 \cdots q_m$$
dengan $v$ unit dan $q_i$ prima maka $n = m$ dan $p_i \sim q_{\sigma(i)}$ untuk suatu permutasi-n $\sigma$.
### [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Faktorisasi Tunggal di Daerah Ideal Utama]]
Setiap Daerah Ideal Utama adalah Daerah Faktorisasi Tunggal
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Prima]]
Misalkan $R$ adalah suatu gelanggang dan $I \subsetneq$ adalah Ideal Sejati dari $R$. $I$ disebut **Ideal Prima** jika untuk setiap $x, y \in R$ dengan $xy \in I$ maka $x \in I$ atau $y \in I$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Prima Z]]
Misalkan $\emptyset \neq I \subseteq \mathbb{Z}$. $I$ adalah **Ideal Prima** dari $\mathbb{Z}$ jika dan hanya jika
$$
I = p \mathbb{Z} \quad\text{ atau } \quad I = \{ 0 \}
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Ideal Prima]]
Misalkan $R$ adalah gelanggang komutatif dan $I$ adalah ideal dari $R$. Maka berlaku
$$
R/I \text{ daerah integral} \quad \iff \quad I \text{ ideal prima}
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Karakterisasi Unsur Prima Daerah Integral]]
Misalkan $R$ adalah daerah integral dan $p \in R$. Maka berlaku
$$
p \text{ unsur prima } \iff \left< p \right>  \text{ ideal prima}
$$


## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Maksimal]]
Misalkan $R$ suatu gelanggang dan $I$ adalah ideal sejati dari $R$. $I$ disebut ideal maksimal dari $R$ apabila berlaku
$$
\text{Untuk setiap ideal } M \text{ dengan } I \subsetneq M \text{ maka } M = R
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Maksimal Sebagai Ideal Prima]]
Misalkan $R$ adalah gelanggang komutatif unit dan $I$ adalah ideal maksimum dari $R$. Maka, $I$ adalah ideal prima dari $R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Ideal Maksimal]]
Misalkan $R$ adalah gelanggang komutatif unit dan $I$ adalah ideal dari $R$. Maka berlaku
$$
R/I \text{ lapangan} \quad \iff \quad I \text{ ideal maksimal}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Karakterisasi Unsur Tak Tereduksi DIU]]
Misalkan $R$ adalah Daerah Ideal Utama dan $q \in R$. Maka berlaku
$$
q \text{ unsur tak-tereduksi } \iff \left< q \right>  \text{ ideal maksimal}
$$


---
# Gelanggang Hasil Bagi dan Isomorfisma
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Koset Gelanggang]]
Misalkan $R$ adalah gelanggang dan $I$ adalah ideal dari $R$. Definisikan koset gelanggang $R$ sebagai  koset dari $(R, +)$ terhadap $I$ yakni
$$
R/I := \{ r + I \ | \ r \in R \}
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Hasil Bagi]]
Definisikan operasi penjumlahan dan operasi perkalian di $R/I$ sebagai
$$
\begin{align*}
(a_{1}+I) + (a_{2}+I) &= (a_{1}+a_{2})+I \\
(a_{1}+I) \cdot (a_{2}+I) &= (a_{1}a_{2})+I
\end{align*}
$$
Himpunan $R/I$ dilengkapi kedua operasi di atas membentuk struktur **Gelanggang**.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal dari Gelanggang Hasil Bagi]]
Misalkan $R$ adalah gelanggang dan $I$ ideal dari $R$ maka setiap ideal dari $R/I$ adalah $J/I$ dengan $J$ adalah ideal dari $R$ memenuhi $I \subseteq J \subseteq R$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Sebagai Inti Homomorfisma]]
Misalkan $A$ adalah suatu gelanggang dan $I$ adalah ideal dari $A$. Maka, terdapat gelanggang $B$ dan homomorfisma gelanggang $f:A \to B$ sehingga $\mathrm{Inti}(f) = I$.

## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Teorema Isomorfisma Pertama (Ring)]]
Misalkan $f:A \to B$ adalah homomorfisma gelanggang maka
$$
A/\mathrm{Inti}(f) \cong f(A)
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Teorema Isomorfisma Kedua (Ring)]]
Misalkan $R$ adalah gelanggang dan $S$ subgelanggang dari $R$ dan $I$ ideal dari $S$. Maka berlaku
$$
S/(S\cap I) \cong (S+I)/I
$$
## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Teorema Isomorfisma Ketiga (Ring)]]
Misalkan $R$ adalah gelanggang, $I, J$ adalah ideal dari $R$ sehingga $I \subseteq J \subseteq R$. Maka berlaku
$$
(R/I)/(J/I) \cong R/J
$$

# Polinomial

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial]]
Misalkan $R$ adalah gelanggang komutatif. **Polinomial** dalam variabel $x$ dengan koefisien di $R$ adalah suatu ekspresi formal berbentuk
$$
f(x) = \sum_{i=0}^{\infty} a_{i}x^{i} = a_{0} + a_{1}x + a_{2}x^{2} + \dots
$$
di mana $a_{i} \in R$ dan $a_{i} = 0$ untuk hampir semua $i$ (artinya, hanya berhingga banyaknya koefisien $a_{i}$ yang tidak nol).

Himpunan semua polinomial dengan koefisien di $R$ dinotasikan dengan $R[x]$.

Lebih lanjut, jika $n$ adalah bilangan bulat terbesar sedemikian sehingga $a_{n} \neq 0$, maka:
1.  **Derajat:** $n$ disebut derajat dari $f(x)$, dinotasikan $\deg(f)$. Jika $f(x)=0$ (polinomial nol), derajatnya didefinisikan sebagai $-\infty$.
2.  **Koefisien Utama:** $a_{n}$ disebut koefisien utama (*leading coefficient*).
3.  **Polinomial Konstan:** Polinomial dengan $a_{i}=0$ untuk semua $i \ge 1$.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Operasi Polinomial]]
Misalkan $R$ adalah gelanggang komutatif. Operasi penjumlahan dan perkalian pada $R[x]$ didefinisikan sebagai berikut. Misalkan $f(x) = \sum a_{i}x^{i}$ dan $g(x) = \sum b_{i}x^{i}$:
1. **Penjumlahan Polinomial**
$$
f(x) + g(x) = \sum_{i=0}^{\infty} (a_{i} + b_{i})x^{i}
$$
2. **Perkalian Polinomial**
	Definisikan $f(x) \cdot g(x) = h(x) = \sum_{i=0}^{\infty} c_ix^i$ dengan
$$
\begin{align*}
c_i = \sum_{j=0}^{i} a_{j}b_{i-j}
\end{align*}
$$

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Gelanggang Polinomial]]
Misalkan $R$ suatu gelanggang komutatif. Sistem $(R[x], +, \cdot)$ membentuk struktur *gelanggang*.

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial Daerah Integral]]
Misalkan $R$ adalah daerah integral maka $R[x]$ juga membentuk daerah integral.

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial]]

Jika $R$ adalah Daerah Integral dan $f(x), g(x) \in R[x]$ dengan $f(x) \neq 0$ dan $g(x) \neq 0$, maka berlaku:
1. $\deg(f(x) + g(x)) \le \max(\deg f(x), \deg g(x))$
2. $\deg(f(x)g(x)) = \deg f(x) + \deg g(x)$

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Subgelanggang Sebagai Subgelanggang Polinomial]]
Jika $R$ adalah gelanggang komutatif dan $S$ adalah subgelanggang dari $R$ maka 
$$
S[x] := \{ s_0+s_{1}x+s_{2}x^2+\dots+s_nx^n \in R[x] \ | \ n \in \mathbb{N_0}, \text{ dan }\ s_0, s_1, \dots,s_n \in S \}
$$
membentuk subgelanggang dari $R[x]$.
### [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Gelanggang Sebagai Ideal Polinomial]]
Jika $R$ adalah gelanggang komutatif dan $I$ adalah ideal dari $R$ maka 
$$
I[x] := \{ i_0+i_{1}x+i_{2}x^2+\dots+i_nx^n \in R[x] \ | \ n \in \mathbb{N_0}, \text{ dan }\ i_0, i_1, \dots,i_n \in I \}
$$
membentuk ideal dari $R[x]$.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Algoritma Euclid Polinomial]]
Misalkan $R$ adalah gelanggang komutatif dengan unit. Misalkan $f(x), g(x) \in R[x]$ sehingga koefisien utama dari $g(x)$ adalah **unit**. Maka terdapat $q(x), r(x) \in R[x]$ **secara tunggal** sehingga
$$
f(x) = g(x)q(x) + r(x)
$$
dengan $\deg r(x) < \deg g(x)$.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Teorema Faktor Polinomial]]
Misalkan $R$ adalah gelanggang komutatif dengan unit. Misalkan $f(x) \in R[x]$ dan $c \in R$. Berlaku
$$
f(c) = 0 \iff f(x) = q(x) (x - c), \ \exists q(x) \in R[x]
$$

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Akar Polinomial]]
Misalkan $R$ suatu gelanggang komutatif dengan unit. Misalkan pula $f(x) \in R[x]$. Unsur $c \in R[x]$ dikatakan **akar** dari $f(x)$ dengan **multisiplitas** $m$ jika terdapat $q(x) \in R[x]$ sehingga
$$
f(x) = q(x) \cdot (x-c)^m
$$
dengan $q(c) \neq 0$.

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Banyak Akar Polinomial]]
Misalkan $R$ daerah integral dan $f(x) \in R[x]$ taknol. Banyak akar dari $f(x)$ (jumlah multisiplitasnya) tidak lebih dari $\deg f(x)$.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial Lapangan Sebagai Daerah Ideal Utama]]
Misalkan $\mathbb{F}$ adalah lapangan maka gelanggang polinomial $\mathbb{F}[x]$ adalah [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]].

### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Unit dari Polinomial Lapangan]]
Misalkan $\mathbb{F}$ adalah lapangan dan $f(x) \in \mathbb{F}[x]$. Maka berlaku
$$
f(x) \text{ unit dari } \mathbb{F}[x] \iff \deg(f) = 0
$$
### [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial Lapangan Sebagai Daerah Faktorisasi Tunggal]]
Misalkan $\mathbb{F}$ adalah lapangan dan $f(x) \in \mathbb{F}[x]$ tak-nol. Maka $f(x)$ dapat dituliskan sebagai
$$
f(x) = u \cdot p_{1}(x) \cdot p_{2}(x) \cdots p_k(x)
$$
dengan $u$ adalah unit di $\mathbb{F}[x]$ dan $p_1, p_{2}, \cdots,p_k$ unsur tak-tereduksi di $\mathbb{F}[x]$ secara tunggal.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Ketereduksian di Polinomial Lapangan]]
Misalkan $\mathbb{F}$ suatu lapangan dan $f(x) \in \mathbb{F}[x]$ berderajat 2 atau 3. Maka berlaku
$$
f(x) \text{ tak-tereduksi di } \mathbb{F}[x] \iff f(x) \text{ tidak memiliki akar di} \mathbb{F}[x]
$$

# Daerah Euclid

## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid|Aksioma Daerah Euclid]]
Suatu daerah integral $D$ disebut **daerah euclid** jika terdapat pemetaan $\delta: D/\{0\} \to \mathbb{N}$ sehingga
1.  $\delta(a) \le \delta(ab)$
2.  $\forall a, b \in D, \ a \neq 0$ ada $q, r \in D$ sehingga
    $$b = qa + r$$
    dengan $r = 0$ atau $\delta(r) < \delta(a)$

## [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Bilangan Bulat Gauss]]
Bilangan Bulat Gauss $\mathbb{Z}[i]$ dilengkapi dengan Operasi Bilangan Bulat Gauss membentuk gelanggang komutatif.
## [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid Bilangan Bulat Gauss]]
Gelanggang Bilangan Bulat Gauss $(\mathbb{Z}[i], +, \cdot)$ adalah daerah euclid.

## [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial Lapangan Sebagai Daerah Euclid]]
Misalkan $\mathbb{F}$ adalah lapangan maka gelanggang polinomial $\mathbb{F}[x]$ adalah [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid]].