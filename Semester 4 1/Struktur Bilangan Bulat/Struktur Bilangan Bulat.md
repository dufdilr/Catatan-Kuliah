#Rangkuman #Aljabar
 
# Teori Bilangan Dasar

## [[Aksioma Bilangan Bulat]]
Bilangan Bulat adalah himpunan yang dilengkapi dengan operasi $+$ dan $\times$ yang memenuhi
* **Sifat Penjumlahan**
	1. **Asosiatif:** $\forall a, b, c \in \mathbb{Z}: \quad (a+b)+c=a+(b+c)$
	2. **Komutatif:** $\forall a, b \in \mathbb{Z}: \quad a+b=b+a$
	3. **Identitas Penjumlahan:** $\exists 0 \in \mathbb{Z}$ sehingga $\forall a \in \mathbb{Z}: \quad a+0 = 0+a = a$
	4. **Invers Penjumlahan:** $\forall a \in \mathbb{Z}, \exists b \in \mathbb{Z} : \quad a + b = b + a = 0$
* **Sifat Perkalian**
	1. **Asosiatif:** $\forall a, b, c \in \mathbb{Z}: \quad (a+b)+c=a+(b+c)$
	2. **Komutatif:** $\forall a, b \in \mathbb{Z}: \quad a+b=b+a$
	3. **Identitas Penjumlahan:** $\exists 0 \in \mathbb{Z}$ sehingga $\forall a \in \mathbb{Z}: \quad a+0 = 0+a = a$
* **Sifat Distributif:** 
	$\forall a, b, c \in \mathbb{Z}: \quad (a + b)\cdot c=a\cdot c + b\cdot c$
* **Sifat Keterurutan**
	Terdapat $\mathbb{N} \subseteq \mathbb{Z}$ sehingga untuk setiap $a, b \in \mathbb{N}$ dan $x \in \mathbb{Z}$ berlaku
	1. $a + b \in \mathbb{N}$
	2. $a \times b \in \mathbb{N}$
	3. $z \in \mathbb{N}$ xatau $-z \in \mathbb{N}$ xatau $z = 0$ (Tepat satu yang benar)
* **[[Aksioma Urutan Sempurna]]**
	Untuk setiap himpunan $A \subseteq \mathbb{N}$ terdapat unsur terkecil di $A$. Dengan kata lain, terdapat $u \in A$ sehingga untuk setiap $a \in A$ berlaku $u \le a$.

## [[Algoritma Pembagian|Algoritma Pembagian]]
Jika $m, n \in \mathbb{Z}$ dan $n > 0$, maka terdapat secara tunggal $q, r \in \mathbb{Z}$ sehingga
$$m = qn + r \quad \text{dan} \quad 0 \le r < n.$$

## [[Keterbagian|Keterbagian]]
Misalkan $a, b \in \mathbb{Z}$ dan $a \neq 0$. Unsur $a$ dikatakan membagi $b$ (notasi: $a \mid b$) jika 
    $$\exists \ c \in \mathbb{Z}: \quad b = ca$$
### [[Sifat Keterbagian]]
Untuk setiap $m, n \in \mathbb{Z}$ berlaku
1.  $\forall n \in \mathbb{Z}: \quad 1 \mid n$
2.  Jika $m \neq 0$, maka $m \mid 0$
3.  Jika $m \mid n$ dan $n \mid q$, maka $m \mid q$ (**Sifat Transitif**) 
4.  Jika $d \mid m$ dan $d \mid n$, maka $d \mid (tm + sn)$ untuk setiap $t, s \in \mathbb{Z}$ (**Sifat Kelinieran**) 
5.  Jika $m \mid 1$, maka $m = 1$ atau $m = -1$
6.  Jika $m \mid n$ dan $n \mid m$, maka $m = \pm n$ 

## [[Faktor Persekutuan Terbesar]]
Misalkan $a, b \in \mathbb{Z}$. Suatu bilangan asli $c$ dikatakan **Pembagi Bersama Terbesar** dari $a, b$ (notasi: $c = (a, b)$), jika:
* $c \mid a$ dan $c \mid b$
* Jika $d \mid a$ dan $d \mid b$, maka $d \mid c$

## [[Teorema Bezout]]
Jika $a, b \in \mathbb{Z}$, tidak keduanya nol, maka ada bilangan asli **tunggal** $c$ sehingga $c = (a, b)$ dan
$$
c = sa + tb, \quad \text{untuk suatu } s, t \in \mathbb{Z}.
$$

## [[Sifat Euclid FPB|Algortma Euclid]]
Untuk setiap bilangan asli $a, b, m \in \mathbb{Z}$ berlaku
$$
FPB(a, b) = FPB(a, am + b)
$$

## [[Relatif Prima]]
Bilangan bulat $a, b$ dikatakan relatif prima jika $(a, b) = 1$

## [[Karakterisasi Relatif Prima]]
Misalkan $a, b \in \mathbb{Z}$. Maka berlaku $(a, b) = 1$ jika dan hanya jika terdapat $m, n \in \mathbb{Z}$ sehingga $am + bn = 1$

## [[Bilangan Prima]]
Suatu bilangan asli $p > 1$ disebut **prima** jika $\forall a \in \mathbb{Z}$ berlaku
    $$p \mid a \quad \text{atau} \quad (p, a) = 1$$

## [[Karakterisasi Bilangan Prima]]
Misalkan $p \in \mathbb{N}$ dengan $p > 1$. Bilangan $p$ adalah bilangan prima jika dan hanya jika berlaku "Jika $p \mid (a_1a_2\cdots a_n)$, maka $p \mid a_i$ untuk suatu $i \in \{1, 2, \dots, n\}$".

## [[Teorema Fundamental Aritmatika]]

Untuk setiap bilangan asli $n>1$ dapat dituliskan sebagai
$$n = p_1^{a_1} \cdot p_2^{a_2} \cdot p_3^{a_3} \cdots p_k^{a_k}$$
dengan $p_i$ bilangan prima dan $a_i$ bilangan asli secara **tunggal**.

## [[Ketakhinggaan Bilangan Prima]]
Terdapat tak hingga banyaknya bilangan prima.


***
# Kongruensi Modulo

## [[Kongruensi Modulo|Relasi Kongruensi Modulo]]
Misalkan $n$ suatu bilangan asli. Didefinisikan suatu [[Relasi|relasi]] $a \sim_n b$ jika dan hanya jika $n \mid (a - b)$. Biasanya dinotasikan
$$a \equiv b \mod n$$

Lebih lanjut, relasi ini merupakan [[Relasi Ekuivalen]].

## [[Himpunan Zn]]
Misalkan $n$ suatu bilangan asli dan relasi [[Kongruensi Modulo]] $\sim_n$. Karena $\sim_n$ adalah [[Relasi Ekuivalen]] maka terdapat [[Kelas Ekuivalen]] dari relasi tersebut. Misalkan
$$[a]_{n} = \{ b \in \mathbb{Z} : a \sim_{n} b \}$$
adalah kelas ekuivalen dari $a$. Definisikan
$$\mathbb{Z}_n = \{[a]_{n} : a \in \mathbb{Z}\}$$
Kemudian, definisikan [[Operasi di Zn|operasi]] penjumlahan dan perkalian di $\mathbb{Z}_{n}$ sebagai
$$
\begin{align*}
[a]_{n} + [b]_{n} &= [a+b]_{n} \\
[a]_{n}\cdot [b]_{n} &= [ab]_{n}
\end{align*}
$$

## [[Himpunan Un]]
Untuk suatu bilangan asli $n$, didefinisikan
$$U_n = \{[a]_{n} \in \mathbb{Z}_n \quad | \quad (a, n) = 1\}$$

## [[Teorema Euler (Modulo)]]

Jika $(a, n) = 1$ maka 
$$a^{\varphi(n)} \equiv 1 \pmod{n}$$

## [[Chinese Remainder Theorem]]
Jika $(m, n) = 1$ maka $\forall a, b \in \mathbb{N}$, sistem persamaan
$$x \equiv a \pmod{m} \quad \text{dan} \quad x \equiv b \pmod{n}$$
memiliki **solusi tunggal** dalam modulo $mn$.

## [[Multiplikatif Fungsi Euler-Phi]]
Jika $(m, n) = 1$ maka
$$\varphi(mn)= \varphi(m)\varphi(n)$$

***
# Grup

## [[Grup|Definisi Grup]]
Suatu sistem $(G, *)$ disebut **grup** jika
1.  **Asosiatif**: $\forall a, b, c \in G: \quad (a*b)*c=a*(b*c)$
2.  **Identitas**: $\exists e \in G$ sehingga $\forall a \in G: \quad a*e = e*a = a$
3.  **Invers**: $\forall a \in G, \exists b \in G : \quad a * b = b * a = e$. Selanjutnya ditulis $b = a^{-1}$

## [[Sifat Grup]]
Misalkan suatu grup $(G, *)$, berlaku:
1.  **Ketunggalan Identitas**. Jika $e, e'$ adalah identitas dari $G$ maka $e = e'$
2.  **Ketunggalan Invers**. Jika $b_1$ dan $b_2$ adalah invers dari $a$ maka $b_1 = b_2$
3.  **Invers dari Invers**. $(a^{-1})^{-1} = a$
4.  **Invers**. $(a*b)^{-1} = b^{-1} * a^{-1}$


***

# Gelanggang
## [[Gelanggang|Definisi Gelanggang]]
Sistem $(R, +, \cdot)$ disebut **gelanggang** jika memenuhi
1.  $(R, +)$ membentuk Grup Komutatif
2.  $(R, \cdot)$ membentuk Sistem Asosiatif.
3.  $(R, +, \cdot)$ berlaku distributif kiri dan kanan yakni
    1.  $\forall a, b, c \in \mathbb{Z}: \quad (a + b)\cdot c=a\cdot c + b\cdot c$
    2.  $\forall a, b, c \in \mathbb{Z}: \quad a\cdot(b + c) = a\cdot b + a\cdot c$

## [[Gelanggang Unit]]
Misalkan $(R, +, \cdot)$ suatu gelanggang. $R$ dikatakan *gelanggang unit* (atau *gelanggang dengan unsur satuan*) jika terdapat unsur $1 \in R/\{0\}$ sehingga untuk setiap $a \in R$ berlaku
$$
a \cdot 1 = 1 \cdot a = a
$$
Lebih lanjut, unsur $1$ yang memenuhi sifat tersebut disebut sebagai *unsur satuan*.

## [[Gelanggang Komutatif]]
Misalkan $(R, +, \cdot)$ suatu gelanggang. $R$ dikatakan *gelanggang komutatif* jika untuk setiap $a, b \in R$ berlaku
$$
a \cdot b = b \cdot a
$$

## [[Subgelanggang]]
Misalkan $(R, +, \cdot)$ adalah suatu gelanggang. Himpunan tak-kosong $K \subseteq R$ disebut **subgelanggang** dari $R$ jika $(K, + , \cdot)$ juga membentuk gelanggang.

### [[Karakterisasi Subgelanggang]]
Misalkan $(R, +, \cdot)$ suatu gelanggang dan $K \subseteq R$ subhimpunan tak-kosong. $K$ adalah *subgelanggang* dari $R$ jika dan hanya jika untuk setiap $x, y \in K$ berlaku
1. $x - y \in K$
2. $xy \in K$

### [[Subgelanggang Z]]
Misalkan $S \subseteq \mathbb{Z}$. $S$ subgelanggang jika dan hanya jika $S = n\mathbb{Z}$ untuk suatu $n \in \mathbb{Z}$.

***

# Ideal Gelanggang
## [[Ideal (Ring)|Definisi Ideal]]
Misalkan $(R, +, \cdot)$ adalah suatu gelanggang. Suatu himpunan tak-kosong $I \subseteq R$ disebut **ideal kiri** apabila untuk setiap $r \in R$ dan $x, y \in I$ berlaku
1. $x + y \in I$
2. $-x \in I$
3. $rx \in I$

Serupa, $I$ disebut **ideal kanan** apabila untuk setiap $r \in R$ dan $x, y \in I$ berlaku
1. $x + y \in I$
2. $-x \in I$
3. $xr \in I$


Lebih lanjut, $I$ disebut **ideal** apabila $I$ adalah *ideal kiri* dan *ideal kanan*.

## [[Karakterisasi Ideal]]
Misalkan suatu gelanggang $(R, +, \cdot)$. $I$ subhimpunan takkosong dari $R$ adalah ideal jika dan hanya jika
1.  $\forall a, b \in I: \quad a + b \in I$
2.  $\forall i \in I, \ \forall r \in R: \quad ir, \ ri \in I$

## [[Ideal Sebagai Subgelanggang]]
Jika $I$ ideal dari gelanggang $R$ maka $I$ adalah subgelanggang dari $R$.

## [[Ideal Terbangun]]
Misalkan $(R, +, \cdot)$ suatu gelanggang komutatif $r_1, r_2, r_3, \cdots , r_n \in R$ maka
$$I = \langle r_1, r_2, \cdots, r_n \rangle = \{s_1r_1+s_2r_2 + \cdots + s_nr_n \quad | \quad s_1, s_2, \cdots, s_n \in R\}$$
juga membentuk ideal dari $R$. Kita sebut $I$ sebagai ideal yang dibangun oleh himpunan $\{ r_1, r_2, r_3, \cdots , r_n  \}$

## [[Ideal Utama]]
Misalkan suatu gelanggang komutatif $(R, +, \cdot)$. Misalkan $r \in R$. Definisikan
$$\langle r \rangle = \{sr \quad | \quad s \in R\}$$
$\langle r \rangle$ adalah ideal dari $R$. Lebih lanjut $I = \langle r \rangle$ disebut sebagai ideal utama.

***

# Homomorfisma Gelanggang
## [[Homomorfisma (Ring)]]
Misalkan $R_1, R_2$ gelanggang. Fungsi $f:R_1 \to R_2$ disebut **homomorfisma** jika $\forall a, b \in R_1$:
1.  $f(a + b) = f(a) + f(b)$
2.  $f(a\cdot b) = f(a) \cdot f(b)$

### [[Isomorfisma (Ring)]]
Misalkan $R_1, R_2$ gelanggang. Fungsi $f:R_1 \to R_2$ disebut **isomorfisma** jika $f$ merupakan homomorfisma gelanggang yang bijektif. Dengan kata lain $\forall a, b \in R_1$ dan $c \in R_2$:
1.  $f(a + b) = f(a) + f(b)$
2.  $f(a\cdot b) = f(a) \cdot f(b)$
3. Jika $f(a) = f(b)$ maka $a = b$
4. Untuk setiap $c \in R_2$ terdapat $r \in R_1$ sehingga $f(r) = c$.

Kemudian, jika terdapat fungsi isomorfisma dari gelanggang $R_1$ ke gelanggang $R_2$ maka $R_1$ isomorfik dengan $R_2$ (notasi: $R_1 \cong R_2$)

***

# Daerah Integral
## [[Daerah Integral]]
Suatu gelanggang Komutatif dengan Unsur Kesatuan $(R, +, \cdot)$. Gelanggang $R$ disebut **Daerah Integral** jika setiap unsur tak-nol bukan pembagi nol. Dengan kata lain, untuk setiap $a, b \in R$ dengan $ab = 0$ maka $a = 0$ atau $b = 0$.

## [[Faktor Persekutuan Terbesar (Daerah Integral)]]
Misalkan $D$ suatu daerah integral dan $a, b \in D$ unsur tak-nol. Elemen $d$ disebut Faktor Persekutuan Terbesar (dituliskan sebagai $c = (a, b)$), jika:
* $c \mid a$ dan $c \mid b$
* Jika $d \mid a$ dan $d \mid b$, maka $d \mid c$

## [[Unsur Unit (Ring)]]
Misalkan $(R, +, \cdot)$ suatu gelanggang dengan unsur satuan $1$. Suatu unsur $u \in R$ dikatakan *unsur unit* jika terdapat $u^{-1} \in R$ sehingga
$$
u \cdot u^{-1} = u^{-1} \cdot u = 1
$$

## [[Unsur Prima (Ring)]]
Misalkan ($R, +, \cdot$) suatu gelanggang komutatif dengan unit. Elemen $p$ disebut **unsur prima** jika:
1.  $p$ tak nol dan bukan unsur unit
2.  Jika $p \mid ab$ maka $p \mid a$ atau $p \mid b$


## [[Unsur Tak Tereduksi (Ring)]]
Misalkan ($R, +, \cdot$) suatu gelanggang komutatif dengan unit. Elemen $p$ disebut **unsur tak tereduksi** jika berlaku
$$
\text{Jika } p = ab \quad \text{ maka } \quad a \text{ unit atau } b \text{ unit}
$$
Lebih lanjut, elemen $q$ disebut **unsur tereduksi** jika terdapat $a, b$ bukan unit sehingga $q = ab$.

## [[Unsur Sekawan (Ring)]]
Misalkan suatu gelanggang komutatif dengan unsur satuan $(R, +, \cdot)$. Elemen $a, b \in R$ dikatakan **sekawan** (notasi: $a \sim b$) jika
$$a = b \cdot u$$
untuk suatu $u$ unit dari $R$.

## [[Unsur Prima Daerah Integral]]
Misalkan $D$ suatu daerah integral dan $p$ unsur prima $D$. Jika $p = ab$ maka $a$ unit atau $b$ unit


***
# Daerah Ideal Utama
## [[Daerah Ideal Utama]]
Suatu daerah integral $D$ disebut **Daerah ideal Utama** jika setiap ideal $I$ dari $D$ dibangun oleh satu unsur. Dengan kata lain jika $I$ suatu ideal dari $D$ maka
$$I = \langle d\rangle = \{dk \quad | \quad k \in D \}\quad \exists \ d \in D$$

## [[Teorema Bezout (Daerah Ideal Utama) |Teorema Bezout pada DIU]]
Misalkan $D$ Daerah Ideal Utama, maka $\forall a, b \in D$ ada $d \in D$ secara unik (hingga sekawan) sehingga $d = (a, b)$ dan
$$d = sa + tb \quad \exists s, t \in D$$
Dengan kata lain jika $d = (a, b) = d'$ maka $d \sim d'$.

## [[Unsur Prima Daerah Ideal Utama]]
Misalkan $D$ Daerah Ideal Utama, maka $p$ unsur prima jika dan hanya jika $p$ tak tereduksi.

## [[Daerah Faktorisasi Tunggal]]
Suatu daerah integral $D$ disebut **Daerah Faktorisasi Tunggal** jika untuk setiap $a\in D$ taknol, bukan unit
$$a = u \cdot p_1 \cdot p_2 \cdots p_n$$
dengan $u$ unit dan $p_i$ prima secara tunggal (tanpa memperdulikan urutan atau sekawan). Dengan kata lain jika
$$a = u \cdot p_1 \cdot p_2 \cdots p_n = v \cdot q_1 \cdot q_2 \cdots q_m$$
dengan $v$ unit dan $q_i$ prima maka $n = m$ dan $p_i \sim q_{\sigma(i)}$ untuk suatu permutasi-n $\sigma$.

## [[Faktorisasi Tunggal di Daerah Ideal Utama]]
Setiap Daerah Ideal Utama adalah Daerah Faktorisasi Tunggal

***

# Daerah Euclid

## [[Daerah Euclid]]
Suatu daerah integral $D$ disebut **daerah euclid** jika terdapat pemetaan $\delta: D/\{0\} \to \mathbb{N}$ sehingga
1.  $\delta(a) \le \delta(ab)$
2.  $\forall a, b \in D, \ a \neq 0$ ada $q, r \in D$ sehingga
    $$b = qa + r$$
    dengan $r = 0$ atau $\delta(r) < \delta(a)$

## [[Daerah Euclid sebagai DIU]]
Setiap Daerah Euclid adalah Daerah Ideal Utama

***

# Lapangan
## [[Lapangan|Definisi Lapangan]]
Suatu gelanggang komutatif dengan unit $(F, +, \cdot)$ disebut **lapangan** setiap unsur taknol di $F$ memiliki invers perkalian.

## [[Lapangan Daerah Euclid]]
Setiap lapangan membentuk Daerah Euclid

## [[Daerah Integral Berhingga Sebagai Lapangan|Lapangan Daerah Integral Berhingga]]
Setiap daerah integral yang berhingga adalah lapangan

## [[Karakterisasi Lapangan|Ideal di Lapangan]]
Misalkan $F$ suatu gelanggang komutatif dengan unit. Maka
$$\text{F lapangan} \quad \iff \quad \text{Ideal dari F hanyalah {0} dan F}$$
