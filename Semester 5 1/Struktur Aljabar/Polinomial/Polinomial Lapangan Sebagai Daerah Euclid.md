#Teorema 

Misalkan $\mathbb{F}$ adalah lapangan maka gelanggang polinomial $\mathbb{F}[x]$ adalah [[Daerah Euclid]].

---
## Bukti

Tinjau $\delta : \mathbb{F}[x]\backslash\{ 0 \} \to \mathbb{N}$ dengan $\delta(f(x)) = \deg (f)$. 

Karena $\mathbb{F}$ adalah lapangan [[Lapangan Sebagai Daerah Integral| maka]] $\mathbb{F}$ adalah daerah integral. Berdasarkan [[Derajat Hasil Operasi Polinomial|teorema]] maka
$$
\delta(fg) = \deg(fg) = \deg(f) + \deg(g) \ge \deg(f) = \delta (f)
$$
Lebih lanjut, karena setiap unsur dari $\mathbb{F}$ adalah unit maka berdasarkan [[Algoritma Euclid Polinomial]], terdapat $q(x), r(x) \in \mathbb{F}[x]$ sehingga
$$
f(x) = g(x)q(x) + r(x)
$$
dengan $\delta (r) = \deg r <  \deg g = \delta (g)$.

Per definisi, terbukti $\mathbb{F}[x]$ membentuk Daerah Euclid.

***
## Definition Used 
 * [[Daerah Euclid]]
 * [[Lapangan]]
 * [[Gelanggang Polinomial]]