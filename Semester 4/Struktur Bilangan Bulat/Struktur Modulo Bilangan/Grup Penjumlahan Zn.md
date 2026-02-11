#Teorema

Himpunan $\mathbb{Z}_{n}$ dengan operasi penjumlahan pada $\mathbb{Z}_{n}$ membentuk grup komutatif.

## Bukti
Jelas $(\mathbb{Z}_{n}, +)$ terdefinisi dengan baik. Akan ditunjukkan $(\mathbb{Z}_{n}, +)$ membentuk grup.
### Asosiatif
Ambil $[a]_n,  [b]_n, [c]_n\in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
\begin{align*}
[a]_n + \left(  [b]_n + [c]_n\right) &= [a]_{n} + [b+c]_{n} = [a+(b+c)]_{n} \\
&= [(a+b)+c]_{n} = [a+b]_{n} + [c]_{n} \\
&= \left([a]_{n} + [b]_{n}  \right) + [c]_{n}
\end{align*}
$$
Terbukti $(\mathbb{Z}_{n}, +)$ bersifat asosiatif

### Identitas
Jelas $[0]_n\in \mathbb{Z}_{n}$. Lebih lanjut, untuk setiap $[a]_n\in \mathbb{Z}_{n}$ berlaku 
	$$
	\quad [a]_n + [0]_n = [a+0]_{n} = [a]_{n} = [0]_{n} + [a]_{n}
	$$
    Maka, $\mathbb{Z}_{n}$ memiliki identitas yakni $[0]_{n}$.
### Invers
Ambil $[a]_n\in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
\begin{align*}
[a]_{n} + [-a]_{n} = [a + (-a)]_{n} = [0]_{n} = [-a]_{n} + [a]_{n}
\end{align*}
$$
Berarti $[-a]_{n}$ adalah invers dari $[a]_n$ di $(\mathbb{Z}_{n}, +)$
### Komutatif
Ambil $[a]_{n},  [b]_{n} \in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
[a]_{n}+[b]_{n} = [a+b]_{n} = [b+a]_{n} = [b]_{n}+[a]_{n}
$$
Terbukti $\mathbb{Z}_{n}$ membentuk grup komutatif.
***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Zn]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Komutatif]]
