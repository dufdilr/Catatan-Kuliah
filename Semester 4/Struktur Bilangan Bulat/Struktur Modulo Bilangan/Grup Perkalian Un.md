#Teorema 

Himpunan $U_n$ dengan operasi perkalian pada $Z_n$ membentuk grup.

## Bukti
### Well-Defined Perkalian Un
Akan ditunjukkan $(U_n, \cdot)$ membentuk sistem. Ambil $[a]_n, [b]_n \in U_n$. Artinya $(a, n) = (b, n) = 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima|teorema]] maka $(ab, n) = 1$. Artinya $[ab]_n \in U_n$
### Asosiatif
Ambil $[a]_n,  [b]_n, [c]_n\in U_n$. Perhatikan bahwa
$$
[a]_n \cdot \left(  [b]_n \cdot [c]_n\right) = [a]_{n} \cdot [bc]_{n} = [a(bc)]_{n} = [(ab)c]_{n} = [ab]_{n} \cdot [c]_{n} = \left([a]_{n} \cdot [b]_{n}  \right) \cdot [c]_{n}
$$
Terbukti $(U_n, \cdot)$ bersifat asosiatif

### Identitas
Jelas $(1, n) = 1$ maka $[1]_n\in U_n$. Lebih lanjut, untuk setiap $[a]_n\in U_n$ berlaku 
	$$
	\quad [a]_n\cdot [1]_n = [1]_n \cdot [a]_n = [a]_n
	$$
    Maka, $U_n$ memiliki identitas yakni $[1]_{n}$.
### Invers
Ambil $[a]_n\in U_n$. Karena $(a, n) = 1$, berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout|Identitas Bezout]], ada $x, y \in \mathbb{Z}$ sehingga
    $ax + ny = 1$. Artinya $ax \equiv 1 \mod n$. Berarti
    $$[a]_n\cdot[x]_n = [x]_n[a]_n = [1]_n$$
    Lebih lanjut, karena $xa + ny = 1$ maka $(x, n) = 1$. Artinya $[x]_n\in U_n$ dan merupakan invers dari $[a]_n$

Terbukti $U_n$ membentuk grup.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Un]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
