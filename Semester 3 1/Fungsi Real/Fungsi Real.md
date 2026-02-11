#Rangkuman #NotFinished 

# Ruang Metrik

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Metrik|Definisi Ruang Metrik]]
Misalkan $X$ suatu himpunan tak-kosong. Suatu fungsi $d:\ X\times X \to \mathbb{R}$ disebut **metrik** jika untuk setiap $x, y, z \in X$ berlaku
1. $d(x, y) = d(y, x)$
2. $d(x, y) \ge 0$
3. $d(x, y) = 0 \space \iff \space x = y$
4. $d(x, y) \le d(x, z) + d(y, z)$
Kemudian $(X, d)$ disebut **ruang metrik**.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Metrik Standar]]
$(\mathbb{R}, d)$ dengan $d(x, y) := |x - y|$ untuk setiap $x, y \in \mathbb{R}$ merupakan [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Metrik|ruang metrik]] dan biasa disebut sebagai **metrik standar**.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Bernorm]]
Misalkan $\mathbb{V}$ adalah Ruang Vektor atas $\mathbb{R}$. Suatu fungsi $\|\cdot\|: \ \mathbb{V} \to \mathbb{R}$ disebut **norm** jika untuk setiap $u, v \in \mathbb{V}$ dan $\alpha \in \mathbb{R}$ memenuhi aksioma berikut:
1.  **Sifat Definit Positif**: $\|v\| \ge 0$, dan $\|v\| = 0$ jika dan hanya jika $v = \mathbf{0}$.
2.  **Sifat Homogenitas Absolut**: $\|\alpha v\| = |\alpha| \|v\|$.
3.  **Ketaksamaan Segitiga**: $\|u + v\| \le \|u\| + \|v\|$.

Lebih lanjut, pasangan $(\mathbb{V}, \|\cdot\|)$ disebut sebagai **Ruang Bernorm**.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Metrik Norm|Ruang Bernorm Sebagai Metrik]]
Misalkan $(\mathbb{V}, \|\cdot\|)$ adalah ruang bernorm. Definisikan 
$$d_{\|\cdot\|} (x, y) = \|x - y\|$$
untuk setiap $x, y \in \mathbb{V}$. Maka, $(\mathbb{V}, d_{\|\cdot\|})$ adalah ruang metrik.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Hasil Kali Dalam]]
Misalkan $\mathbb{V}$ adalah Ruang Vektor atas $\mathbb{R}$. Suatu fungsi $\langle\cdot,\cdot\rangle: \ \mathbb{V} \times \mathbb{V} \to \mathbb{R}$ disebut **Hasil Kali Dalam** (Inner Product) jika untuk setiap $u, v, w \in \mathbb{V}$ dan $\alpha \in \mathbb{R}$ memenuhi aksioma berikut:

1.  **Sifat Simetri**: $\langle u, v \rangle = \langle v, u \rangle$
2.  **Sifat Aditivitas**: $\langle u+v, w \rangle = \langle u, w \rangle + \langle v, w \rangle$
3.  **Sifat Homogenitas**: $\langle \alpha u, v \rangle = \alpha \langle u, v \rangle$
4.  **Sifat Definit Positif**: $\langle v, v \rangle \ge 0$, dan $\langle v, v \rangle = 0$ jika dan hanya jika $v = \mathbf{0}$

Lebih lanjut, pasangan $(\mathbb{V}, \langle\cdot,\cdot\rangle)$ disebut sebagai **Ruang Hasil Kali Dalam**.
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Norm Hasil Kali Dalam]]
Misalkan $\langle\cdot,\cdot\rangle$ adalah **hasil kali dalam** pada $\mathbb{V}$. Maka
$$\|u\| = \sqrt{\langle u,u\rangle}$$
adalah suatu **norm** pada $\mathbb{V}$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ketaksamaan Cauchy-Schwarz]]
Misalkan $V$ adalah ruang hasil kali dalam atas $\mathbb{R}$. Untuk setiap $x, y \in V$ berlaku
$$|\langle x, y\rangle | \ \le \ \|x\| \cdot \|y\|$$
---
# Barisan
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan (Metrik)]]
Misalkan $X$ suatu himpunan tak-kosong. Suatu fungsi $a:\mathbb{N} \to X$ disebut sebagai **barisan**. Barisan biasa ditulis sebagai $(a_n)$ dengan $a_n = a(n)$ untuk setiap bilangan asli $n$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Terbatas (Metrik)]]
Misalkan $(\mathbb{X}, d)$ adalah ruang metrik. Barisan $(x_{n}) \subseteq \mathbb{X}$ disebut **terbatas** jika terdapat suatu titik $c \in \mathbb{X}$ dan sebuah bilangan riil $M > 0$ sehingga 
$$\forall n \in \mathbb{N} : \ d(x_n, c) \le M$$
Artinya, semua anggota barisan tersebut berada di dalam sebuah bola dengan pusat $c$ dan jari-jari $M$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]
Misalkan $(\mathbb{X}, d)$ adalah ruang metrik. Barisan $(x_n) \subseteq \mathbb{X}$ disebut **barisan Cauchy** jika
$$\forall\varepsilon >0, \ \exists N \in \mathbb{N}\ \text{ sehingga }\ \forall m, n>N: \ d(x_n, x_m) < \varepsilon$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
Misalkan $(X, d)$ suatu **ruang metrik** dan $(x_n)$ suatu barisan di $X$ serta $x \in X$. $(x_n)$ dikatakan **konvergen** ke $x$ jika dan hanya jika
	Untuk setiap $\varepsilon > 0$ terdapat $N \in \mathbb{N}$ sehingga untuk setiap $n \ge N$ berlaku
	$$d(x_{n}, x) < \varepsilon$$
Jika barisan $(x_n)$ konvergen ke $x$ maka dapat dituliskan $x_n \to x$.
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Ketunggalan Limit]]
Misalkan $(x_{n}) \subseteq \mathbb{X}$ adalah barisan yang [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|konvergen]]. Jika $x_n \to x$ dan $x_n \to x'$, maka haruslah $x = x'$.
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Cauchy Terbatas]]
Jika $(x_n) \subseteq \mathbb{X}$ adalah barisan cauchy maka $(x_{n})$ merupakan barisan terbatas.
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen Cauchy]]
Jika $(x_n) \subseteq \mathbb{X}$ adalah barisan konvergen ke $x \in \mathbb{X}$ maka $(x_n)$ merupakan barisan cauchy.
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Kesetaraan Limit Barisan]]
Misalkan $(x_n)$ dan $(y_n)$ adalah barisan konvergen di $\mathbb{X}$ dengan $x_n \to x$ dan $y_n \to y$. Maka, $x = y$ jika dan hanya jika 
$$\lim_{n\to\infty} d(x_n, y_n) = 0$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Subbarisan]]
Misalkan $(x_n)$ suatu barisan. $(x_{n_k})_k$ disebut subbarisan dari $x_n$ dimana $n_k$ adalah barisan bilangan asli monoton naik.
## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Limit Subbarisan]]
Setiap subbarisan dari suatu barisan konvergen juga konvergen ke nilai yang sama.

## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Limit Subbarisan Cauchy]]
Misalkan $(x_n)$ adalah barisan Cauchy. Jika terdapat subbarisan yang konvergen, maka barisan tersebut juga konvergen ke nilai yang sama.

## [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Kekonvergenan di Rn]]
Tinjau $(\mathbb{R}^n, \| \cdot \|_p)$ dan $\{x_n\}\subseteq \mathbb{R}^k$ dengan $x_i = (x_i(1),\ x_i(2),\ \cdots ,\ x_i(k))$ untuk setiap $i \in \mathbb{N}$.
$$x_n \to x \quad \iff \quad x_n(j) \to x(j) \ \ \forall j \in [1, k]_\mathbb{N}$$

---
# Topologi
## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Bola Buka]]
Misalkan $(X, d)$ adalah [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Metrik|ruang metrik]]. Misalkan pula $a \in X$ dan $r > 0$. Definisikan **bola buka** berpusat di $a$ dengan jari-jari $r$ sebagai
$$
B(a, r) = \left\{ x \in X \ | \ d(a, x) < r \right\}
$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Titik Interior]]
Misalkan ruang metrik $(X, d)$ dan subhimpunan $E \subseteq X$. Elemen $a \in X$ disebut **titik interior** jika terdapat $r > 0$ sehingga 
$$B(a, r) \subseteq E$$
Kemudian, himpunan titik interior dari $E$ biasa dituliskan sebagai $E^o$

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Buka]]
Misalkan metrik $(X, d)$ dan subhimpunan $E \subseteq X$. Himpunan $E$ dikatakan **himpunan buka** (di $X$) jika untuk setiap $a \in E$, $a$ merupakan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Titik Interior]] dari $E$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Tutup]]
Misalkan metrik $(X, d)$ dan subhimpunan $F \subseteq X$. Himpunan $F$ dikatakan **himpunan tutup** (di $X$) jika $F^c$ merupakan [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Buka|himpunan buka]].

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Topologi Himpunan Buka]]
Misalkan $(X, d)$ ruang metrik
1.  $\emptyset$ dan $X$ adalah himpunan buka
2.  Jika $\{G_\alpha\}_\alpha$ adalah kumpulan himpunan buka maka $\displaystyle \bigcup_\alpha G_\alpha$ juga himpunan buka
3.  Jika $\{G_1, G_2, \cdots, G_n\}$ adalah kumpulan berhingga himpunan buka maka $\displaystyle \bigcap_{i=1}^n G_i$ juga himpunan buka

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Topologi Himpunan Tutup]]
Misalkan $(X, d)$ ruang metrik
1.  $\emptyset$ dan $X$ adalah himpunan tutup
2.  Jika $\{G_\alpha\}_\alpha$ adalah kumpulan himpunan tutup maka $\displaystyle \bigcap_\alpha G_\alpha$ juga himpunan tutup
3.  Jika $\{G_1, G_2, \cdots, G_n\}$ adalah kumpulan berhingga himpunan tutup maka $\displaystyle \bigcup_{i=1}^n G_i$ juga himpunan tutup

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Interior]]
Misalkan $(X, d)$ suatu ruang metrik dan $E, F$ subhimpunan dari $X$, berlaku:
1.  Jika $E \subseteq F$ maka $E^o \subseteq F^o$
2.  $\left(E\cap F\right)^o = E^o \cap F^o$
3.  $\left(E \cup F\right)^o \supseteq E^o \cup F^o$
### [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Subhimpunan Buka Maksimum]]
Misalkan $(X, d)$ suatu metrik dan subhimpunan $E \subseteq X$. Himpunan semua *titik interior* dari $E$, (notasi: $E^o$) adalah himpunan buka terbesar yang termuat di dalam $E$

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Titik Limit]]
Misalkan $(X, d)$ adalah ruang metrik dan $A \subseteq X$. Elemen $x \in X$ disebut **titik limit** dari $A$ jika
$$\forall \ \varepsilon >0: \ B(x, \varepsilon) \cap\left(A/ \{x\}\right) \neq \emptyset$$
Titik limit disebut juga **titik kluster**. Kemudian, himpunan titik limit dari $A$ biasa dituliskan sebagai $A'$.
### [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Titik Limit]]
Misalkan $(x, d)$ suatu ruang metrik dan $E$ subhimpunan dari $X$. Maka ketiga pernyataan berikut ekuivalen:
1.  $x$ adalah titik limit dari $E$
2.  $\exists \{x_n\} \subseteq E, \ x_n \neq x$ sehingga $x_n \to x$. 
3.  $\forall \varepsilon>0, |B(x, \varepsilon) \cap E| = \infty$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Himpunan Titik Limit]]
Misalkan $E, F$ himpunan serta $E', F'$ adalah himpunan semua titik limit dari $E, F$ berturut-turut. Berlaku:
1.  $E'$ adalah himpunan tutup. 
2.  Jika $E \subseteq F$ maka $E' \subseteq F'$. 
3.  $(E\cup F)' = E'\cup F'$. 
4.  $(E \cap F)' \subseteq E' \cap F'$ 
### [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Himpunan Tutup dan Himpunan Titik Limit]]
Misalkan $(X, d)$ ruang metrik dan $A \subseteq X$. Himpunan $A$ adalah *himpunan tutup* **jika dan hanya** jika $A' \subseteq A$

## [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Penutup Himpunan]]
Misalkan $(X, d)$ ruang metrik dan $E \subseteq X$. Definisikan $\overline{E} = E \cup E'$. Himpunan $\overline{E}$ adalah *himpunan tutup terkecil* yang memuat $E$. Himpunan $\overline{E}$ biasa disebut sebagai **Penutup Himpunan (closure)** $E$.
### [[Buat Backup/Semester 3 1/Fungsi Real/Topologi/Sifat Penutup Himpunan]]
Misalkan $(X, d)$ ruang metrik. Misalkan pula $E, F$ subhimpunan $X$ serta $\overline{E}, \overline{F}$ adalah himpunan penutup dari $E, F$ berturut-turut. Maka berlaku
1. $E$ himpunan tutup jika dan hanya jika $E = \overline{E}$ 
2.  Jika $E \subseteq F$ maka $\overline{E} \subseteq \overline{F}$ 
3.  $\overline{E \cup F} = \overline{E} \cup \overline{F}$
4.  $\overline{E \cap F} \subseteq \overline{E} \cap \overline{F}$

---
# Fungsi
## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Limit Fungsi]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$ serta titik limit $c \in A'$. Fungsi $f$ dikatakan **memiliki limit** di titik $c$ (pada himpunan $A$) jika terdapat $L \in Y$ sehingga
$$\forall \varepsilon >0, \ \exists \delta>0, \text{ sehingga } \forall x \in A: \ \left(0<d_X(x, c)<\delta \Rightarrow d_Y(f(x), L) < \varepsilon\right)$$
Lebih lanjut, dituliskan
$$
\lim_{ x \to c } f(x) = L
$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$ serta titik limit $c \in A'$. Fungsi $f$ dikatakan **kontinu di titik** $c$ (pada himpunan $A$) jika
$$\forall \varepsilon >0, \ \exists \delta>0, \text{ sehingga } \forall x \in A: \ \left(d_X(x, c)<\delta \Rightarrow d_Y(f(x), f(c)) < \varepsilon\right)$$
Lebih lanjut, $f$ dikatakan **kontinu pada himpunan $A$** jika
$$\forall c \in A, \ \forall \varepsilon >0, \ \exists \delta>0, \text{ sehingga } \forall x \in A: \ \left(d_X(x, c)<\delta \Rightarrow d_Y(f(x), f(c)) < \varepsilon\right)$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Limit Fungsi dan Barisan]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$ serta titik limit $c \in A'$. Berlaku $\displaystyle \lim_{x \to c} f(x) = L$ **jika dan hanya jika**
$$\forall \{x_n\} \subseteq A, x_n \neq c:\ x_n \to c \ \Rightarrow \ f\{x_n\} \to L$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu dan Barisan]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$ serta titik limit $c \in A'$. Fungsi $f$ kontinu di titik $c$ **jika dan hanya jika**
$$\forall \{x_n\} \subseteq A:\ x_n \to c \ \Rightarrow \ f\{x_n\} \to f(c)$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu dan Himpunan Buka]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$.  Fungsi $f$ kontinu pada himpunan $A$ **jika dan hanya jika** berlaku
$$\forall \ \mathcal{O} \subseteq Y \text{ himpunan buka di } Y \text{ maka } f^{-1}(\mathcal{O}) \text{ adalah himpunan buka relatif di } A$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu dan Himpunan Tutup]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$.  Fungsi $f$ kontinu pada himpunan $A$ **jika dan hanya jika** berlaku
$$\forall \ \mathcal{F} \subseteq Y \text{ himpunan tutup di } Y \text{ maka } f^{-1}(\mathcal{F}) \text{ adalah himpunan tutup relatif di } A$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu dan Himpunan Penutup]]
Misalkan $f: X \to Y$ maka ketiga pernyataan berikut ekivalen
1.  $f$ fungsi kontinu
2.  untuk setiap $E\subseteq X$ berlaku $f(\overline{E}) \subseteq \overline{f(E)}$
3.  untuk setiap $F \subseteq Y$ berlaku $f^{-1}(\overline{F}) \supseteq \overline{f^{-1}(F)}$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Kontinu Seragam]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik. Misalkan pula himpunan $A \subseteq X$ dan fungsi $f:  A \to Y$. $f$ dikatakan **kontinu uniform** (pada himpunan $A$) jika
$$\forall \varepsilon >0, \ \exists \delta>0, \text{ sehingga } \forall x, y \in A: \ \left(d_X(x, y)<\delta \Rightarrow d_Y(f(x), f(y)) < \varepsilon\right)$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Barisan Fungsi Konvergen Titik Demi Titik]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $\{f_n\}$ barisan fungsi $f_n: X \to Y$. Barisan fungsi $f_n$ dikatakan **konvergen titik demi titik** ke $f$ (notasi: $f_n \to f$) jika
$$\forall x \in X, \ \forall \varepsilon>0, \ \exists N \in \mathbb{N}\ \text{ sehingga }\ \forall n > N: \ d_Y(f_n(x), f(x)) < \varepsilon$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Barisan Fungsi Konvergen Seragam]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $\{f_n\}$ barisan fungsi $f_n: X \to Y$. Barisan fungsi $f_n$ dikatakan **konvergen seragam** ke $f$ (notasi: $f_n \xrightarrow{u}f$) jika
$$\forall \varepsilon>0, \ \exists N \in \mathbb{N}\ \text{ sehingga }\ \forall n > N,\ \forall x \in X: \ d_Y(f_n(x), f(x)) < \varepsilon$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Kekontinuan Limit Barisan Fungsi Kontinu]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik. Misalkan pula $\{f_n\}$ barisan fungsi kontinu  $f_n: X \to Y$ dan $f_n\xrightarrow{u}f$. Fungsi $f: X \to Y$ adalah kontinu.

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Pertukaran Limit]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik. Misalkan pula $\{f_n\}$ barisan fungsi kontinu  $f_n: X \to Y$ dan $f_n\xrightarrow{u}f$. Berlaku
$$\lim_{x \to c} f(x)=\lim_{n\to\infty} \lim_{x \to c} f_n(x)$$
---
# Ruang Metrik Lengkap
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Ruang Metrik Lengkap]]
Misalkan $(X, d)$ suatu ruang metrik. $X$ disebut **ruang metrik lengkap** (*Complete Metric*) jika setiap barisan cauchy konvergen di $X$.
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Subruang Lengkap]]
Misalkan $(X, d)$ suatu ruang metrik. Subhimpunan $Y \subseteq X$ disebut **subruang** lengkap dari $X$ apabila $(Y, d)$ membentuk ruang lengkap.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Subruang Lengkap Tutup]]
Misalkan $(X,d)$ suatu metrik dan $A \subseteq X$. Jika $A$ adalah subruang lengkap maka $A$ himpunan tutup.
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Subhimpunan Tutup di Ruang Lengkap]]
Misalkan $(X, d)$ ruang metrik lengkap. Jika $Y \subseteq X$ adalah himpunan tutup maka $Y$ subruang lengkap dari $X$

## [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontraksi]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ adalah ruang metrik. Fungsi $f: X \to Y$ disebut **kontraksi** jika terdapat $\alpha \in [0, 1)$ sehingga untuk setiap $x_1, x_2 \in X$
$$d_Y(f(x_1),f(x_2) ) \le \alpha \cdot d_X(x_1, x_2)$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Teorema Kontraksi Banach]]
Misalkan $X$ adalah ruang metrik lengkap dan suatu fungsi $f: X \to X$. Jika $f$ fungsi kontraksi maka terdapat tepat satu titik tetap dari $f$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Diameter Himpunan]]
Misalkan $(X, d)$ suatu ruang metrik dan $F$ suatu himpunan tak-kosong maka didefinisikan
$$\text{diam}(F) := \sup\left\{\ d(x, y)\ \ |\ \ x, y \in F\ \right\}$$
### [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Diameter Himpunan Penutup]]
Misalkan $(X, d)$ suatu ruang metrik dan himpunan tak-kosong $F$ maka berlaku
$$\text{diam}(F) = \text{diam}(\overline{F})$$

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Teorema Perpotongan Cantor]]
Ruang metrik $X$ lengkap jika dan hanya jika untuk setiap barisan himpunan tutup takkosong $\{F_n\}$ dengan $F_{n} \supseteq F_{n+1}$ dan $\displaystyle\lim_{n \to \infty} \text{diam}(F_n) = 0$ terdapat $a \in X$ sehingga
$$\bigcap_{n = 1}^\infty F_n = \{a\}$$
---
# Pelengkap Ruang Metrik
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Himpunan Padat]]
Misalkan $X$ suatu ruang metrik. Subhimpunan $E$ disebut **padat** pada $X$ jika $\overline{E} = X$

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Isometri Ruang Metrik]]
Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik. Fungsi $f: X \to Y$ dikatakan **isometri** jika
$$\forall x, y \in X: \quad d_X(x, y) = d_Y(f(x), f(y))$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Pelengkap Ruang Metrik]]
Misalkan $X$ suatu ruang metrik. $Y$ dikatakan **pelengkap** ruang metrik dari $X$ jika
1.  $Y$ ruang metrik lengkap dan
2.  Terdapat isometri $f:X \to Y$ sehingga $\overline{f(X)} = Y$.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Kelengkapan dan Himpunan Padat]]
Misalkan $X$ himpunan padat di $Y$. Jika setiap barisan cauchy di $X$ konvergen di $Y$ maka $Y$ lengkap.
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Lengkap/Teorema Pelengkap Cantor]]
Setiap ruang metrik memiliki pelengkap.

---
# Ruang Banach

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Banach/Ruang Banach|Definisi Ruang Banach]]
Suatu ruang norm $(X, \|\cdot\|)$ disebut **ruang banach** jika $X$ lengkap.

## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Banach/Deret Konvergen]]
Misalkan $(V, \|\cdot\|)$ ruang bernorm dan $\textbf{x} = \{x_1, x_2, \cdots\}$ adalah barisan di $V$. Definisikan barisan *jumlah parsial* sebagai
$$
S_n = \sum_{k = 1}^n x_k
$$
Jika barisan jumlah parsial konvergen $S_n \to S$ maka deret tersebut konvergen dan dituliskan
$$
\sum_{k=1}^{\infty} x_k = \lim_{ n \to \infty } S_n =  S
$$
## [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Banach/Deret Konvergen Mutlak]]
Misalkan $(V, \|\cdot\|)$ ruang bernorm dan $\textbf{x} = \{x_1, x_2, \cdots\}$ adalah barisan di $V$. Deret
$$
\sum_{k=1}^{\infty} x_k
$$
disebut **deret konvergen mutlak** jika deret
$$
\sum_{k=1}^{\infty}\|x_k\|
$$
adalah deret konvergen.

---
# Kekompakan
