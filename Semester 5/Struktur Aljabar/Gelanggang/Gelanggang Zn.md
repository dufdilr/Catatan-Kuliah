#Definisi #Teorema 

Sistem $(\mathbb{Z}_{n}, +, \cdot)$ membentuk struktur **Gelanggang Komutatif dengan Unit**

## Bukti
### Grup Komutatif
Telah ditunjukkan $(\mathbb{Z}_{n}, +)$ membentuk [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Penjumlahan Zn|Grup Komutatif Zn]].

### Asosiatif
Ambil $[a]_{n}, [b]_{n}, [c]_{n}\in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
\begin{align*}
\left( [a]_{n}\cdot[b]_{n} \right) \cdot[c]_{n} &= [ab]_{n}\cdot[c]_{n} = [(ab)c]_{n}\\
&= [a(bc)]_{n} = [a]_{n} \cdot [bc]_{n} \\
&= [a]_{n} \cdot \left( [b]_{n}\cdot[c]_{n} \right) 
\end{align*}
$$
Terbukti $(\mathbb{Z}_{n}, \cdot)$ asosiatif
### Distributif
$$
\begin{align*}
\left( [a]_{n} + [b]_{n} \right) \cdot[c]_{n} &= [a+b]_{n}\cdot[c]_{n} = [(a+b)c]_{n}\\
&= [ac + bc]_{n} = [ac]_{n} + [bc]_{n} \\
&= \left( [a]_{n}\cdot[c]_{n} \right)  + \left( [b]_{n}\cdot[c]_{n} \right) \\
\\
[a]_{n} \cdot \left(  [b]_{n} + [c]_{n}\right)  &= [a]_{n}\cdot[b+c]_{n} = [a(b+c)]_{n}\\
&= [ab + ac]_{n} = [ab]_{n} + [ac]_{n} \\
&= \left( [a]_{n}\cdot[b]_{n} \right)  + \left( [a]_{n}\cdot[c]_{n} \right) 
\end{align*}
$$
Terbukti $(\mathbb{Z}_{n}, +, \cdot)$ distributif. 

### Komutatif Perkalian
Ambil $[a]_{n}, [b]_{n}\in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
[a]_{n}\cdot[b]_{n} = [ab]_{n} = [ba]_{n} = [b]_{n}\cdot[a]_{n}
$$
Terbukti $(\mathbb{Z}_{n}, \cdot)$ komutatif
### Identitas Perkalian
Ambil $[a]_{n}\in \mathbb{Z}_{n}$. Perhatikan bahwa
$$
[a]_{n} \cdot [1]_{n} = [a \cdot 1]_{n} = [a]_{n} = [1 \cdot a]_{n} = [1]_{n} \cdot[a]_{n}
$$
Maka, $[1]_{n}$ adalah elemen identitas perkalian dari $(\mathbb{Z}_{n}, \cdot)$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Komutatif]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Unit]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Zn]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Operasi di Zn]]
