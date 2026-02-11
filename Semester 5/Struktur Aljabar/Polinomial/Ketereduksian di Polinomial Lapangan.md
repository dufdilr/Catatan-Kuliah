#Teorema 
Misalkan $\mathbb{F}$ suatu lapangan dan $f(x) \in \mathbb{F}[x]$ berderajat 2 atau 3. Maka berlaku
$$
f(x) \text{ tak-tereduksi di } \mathbb{F}[x] \iff f(x) \text{ tidak memiliki akar di } \mathbb{F}[x]
$$

---
## Bukti
### $\Rightarrow$
Andaikan $f(x)$ memiliki akar. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Teorema Faktor Polinomial]] maka terdapat $q(x) \in \mathbb{F}[x]$ sehingga
$$
f(x)= q(x)(x-c)
$$
Karena $\mathbb{F}$ adalah lapangan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Lapangan Sebagai Daerah Integral|maka]] $\mathbb{F}$ adalah daerah integral. Sehingga [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial|berlaku]]
$$
\deg(q(x)(x-c)) = \deg(q(x)) + 1 = \deg f \ge 2
$$
maka $\deg q \ge 1$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Unit dari Polinomial Lapangan|teorema]] maka $q(x)$ dan $(x-c)$ keduanya bukan unit. Kontradiksi dengan hipotesa $f$ tak-tereduksi.

Artinya pengandaian salah. Terbukti $f$ tidak memiliki akar di $\mathbb{F}[x]$
### $\Leftarrow$
Andaikan $f(x)$ tereduksi. Maka 
$$
f(x) = g(x)h(x)
$$
dengan $g(x), h(x)$ keduanya bukan unit. Jelas $g(x), h(x)$ tak-nol. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Unit dari Polinomial Lapangan|teorema]] maka $\deg g, \deg h \ge 1$. Perhatikan bahwa $\deg f = 2$ atau $\deg f = 3$.
* **Jika $\deg f = 2$**
	Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial|teorema]] maka $\deg f = \deg(gh) = \deg g + \deg h = 2$. Karena $\deg g, \deg h \ge 1$ maka dapat disimpulkan $\deg g = \deg h = 1$. 
	
	Tulis $g(x) = a_{1}x + a_{0}$. Artinya $f(x) = (a_{1}x + a_{0})h(x)$. Perhatikan bahwa
    $$\begin{align*}
f(-a_{1}^{-1}a_{0}) &= a_{1}(-a_{1}^{-1}a_{0}) + a_{0} = - (a_{1}a_{1}^{-1}a_{0})+a_{0} = -a_{0} + a_{0} = 0
\end{align*}$$
	Maka $f(a_0) = 0$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Teorema Faktor Polinomial]] maka $a_{0}$ adalah akar dari $f$. Kontradiksi dengan hipotesis $f$ tidak memiliki akar
* **Jika $\deg f = 3$**
	Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial|teorema]] maka $\deg f = \deg(gh) = \deg g + \deg h = 3$. Karena $\deg g, \deg h \ge 1$, maka pasangan derajat yang mungkin adalah 1 dan 2.
	
	Tulis $g(x) = a_{1}x + a_{0}$. Artinya $f(x) = (a_{1}x + a_{0})h(x)$. Perhatikan bahwa $$\begin{align*}
f(-a_{1}^{-1}a_{0}) &= a_{1}(-a_{1}^{-1}a_{0}) + a_{0} = - (a_{1}a_{1}^{-1}a_{0})+a_{0} = -a_{0} + a_{0} = 0
\end{align*}$$
	Maka $f(a_0) = 0$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Teorema Faktor Polinomial]] maka $a_{0}$ adalah akar dari $f$. Kontradiksi dengan hipotesis $f$ tidak memiliki akar


Perhatikan bahwa untuk kedua kasus terjadi kontradiksi. Maka pengandaian salah. Terbukti $f$ tak-tereduksi di $\mathbb{F}[x]$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Lapangan/Lapangan]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Gelanggang Polinomial]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Tak Tereduksi (Ring)]]

