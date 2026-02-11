#Teorema 

Misalkan $\mathbb{F}$ adalah lapangan maka gelanggang polinomial $\mathbb{F}[x]$ adalah [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid]].

---
## Bukti

Tinjau $\delta : \mathbb{F}[x]\backslash\{ 0 \} \to \mathbb{N}$ dengan $\delta(f(x)) = \deg (f)$. 

Karena $\mathbb{F}$ adalah lapangan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Lapangan Sebagai Daerah Integral| maka]] $\mathbb{F}$ adalah daerah integral. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial|teorema]] maka
$$
\delta(fg) = \deg(fg) = \deg(f) + \deg(g) \ge \deg(f) = \delta (f)
$$
Lebih lanjut, karena setiap unsur dari $\mathbb{F}$ adalah unit maka berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Algoritma Euclid Polinomial]], terdapat $q(x), r(x) \in \mathbb{F}[x]$ sehingga
$$
f(x) = g(x)q(x) + r(x)
$$
dengan $\delta (r) = \deg r <  \deg g = \delta (g)$.

Per definisi, terbukti $\mathbb{F}[x]$ membentuk Daerah Euclid.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Lapangan/Lapangan]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Gelanggang Polinomial]]