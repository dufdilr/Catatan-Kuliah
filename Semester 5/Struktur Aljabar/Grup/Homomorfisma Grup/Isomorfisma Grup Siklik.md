#Teorema 
Misalkan $A$ adalah grup siklik dengan $\text{ord}(A) = n$ maka
$$
A \cong \mathbb{Z}_{n}
$$
Jika $\text{ord}(A) = \infty$ maka
$$
A \cong \mathbb{Z}
$$

---
## Bukti
### Orde Berhingga
Misalkan $A = \left< a \right> = \{ e, a, a^2, a^3, \dots , a^n \}$. Definisikan pemetaan $\phi: \mathbb{Z}_{n} \to A$ dengan
$$
\phi([k]_{n}) = a^k
$$
Akan ditunjukkan $\phi$ isomorfisma.
#### Terdefinisi dengan Baik
Perhatikan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Unsur Pembangun|bahwa]] $\text{ord}(a) = \text{ord}(A) = n$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Kesamaan Pangkat]] maka jika $[x]_{n} = [y]_{n} \in \mathbb{Z}_{n}$ berlaku
$$
\phi([x]_{n}) = a^x = a^y = \phi([y]_{n})
$$
Maka $\phi$ terdefinisi dengan baik
#### Homomorfisma
Misalkan $[x]_{n}, [y]_{n} \in \mathbb{Z}_{n}$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Operasi Pangkat (Grup)]] maka
$$
\phi([x]_{n}+[y]_{n}) = a^{x+y} = a^x \cdot a^y = \phi([x]_{n}) \cdot \phi([y]_{n})
$$
Maka $\phi$ adalah homomorfisma.

#### Injektif
Misalkan $[x]_{n}, [y]_{n} \in \mathbb{Z}_{n}$ sedemikian sehingga $\phi([x]_{n}) = \phi([y]_{n})$. Perhatikan bahwa
$$
\phi([x]_{n}) = \phi([y]_{n}) \quad\implies\quad a^x = a^y
$$
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Kesamaan Pangkat]], maka $\text{ord}(a) = n \mid (x - y)$ artinya $[x]_{n} = [y]_{n}$. Maka $\phi$ bersifat injektif.

#### Surjektif
Ambil $x \in A$. Karena $A$ siklik maka $x = a^k$ untuk suatu $k \in \mathbb{Z}$. Tinjau $[k]_{n}$. Perhatikan bahwa
$$
\phi([k]_{n}) = a^k = x
$$
Maka $\phi$ bersifat surjektif

#### Kesimpulan
Karena $\phi$ isomorfisma maka terbukti
$$
A \cong \mathbb{Z}_{n}
$$
### Orde Tak Hingga
Misalkan $A = \left< a \right> = \{ \dots, a^{-2}, a^{-1}, e, a, a^2, a^3, \dots \}$. Definisikan pemetaan $\phi: \mathbb{Z} \to A$ dengan
$$
\phi(n) = a^n
$$
Untuk setiap $n \in \mathbb{Z}$. Akan ditunjukkan $\phi$ isomorfisma.
#### Terdefinisi dengan Baik
Jelas $\phi$ terdefinisi dengan baik, karena $\phi(n) = a^n \in A$ untuk setiap $n \in \mathbb{Z}$
#### Homomorfisma
Misalkan $m, n \in \mathbb{Z}$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Operasi Pangkat (Grup)]] maka
$$
\phi(m+n) = a^{m+n} = a^m \cdot a^n = \phi(m) \cdot \phi(n)
$$
Maka $\phi$ adalah homomorfisma.

#### Injektif
Misalkan $m, n \in \mathbb{Z}$ sedemikian sehingga $\phi(m) = \phi(n)$. Perhatikan bahwa
$$
\phi(m) = \phi(n) \quad\implies\quad a^m = a^n \quad\implies\quad a^{m - n} = e
$$
Karena $\text{ord}(a) = \infty$ maka haruslah $m - n = 0$. Artinya $m = n$. Maka $\phi$ bersifat injektif.

#### Surjektif
Ambil $x \in A$. Karena $A$ siklik maka $x = a^k$ untuk suatu $k \in \mathbb{Z}$. Perhatikan bahwa
$$
\phi(k) = a^k = x
$$
Maka $\phi$ bersifat surjektif

#### Kesimpulan
Karena $\phi$ isomorfisma maka terbukti
$$
A \cong \mathbb{Z}
$$
***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma (Grup)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik Zn]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Bilangan Bulat#^d2c3f4|Grup Bilangan Bulat]]
