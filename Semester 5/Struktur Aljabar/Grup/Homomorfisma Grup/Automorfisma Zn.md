#Teorema 

Misalkan $n,k \in \mathbb{N}$ dengan $(n, k) = 1$. Maka fungsi $\phi:\mathbb{Z}_{n} \to \mathbb{Z}_{n}$ dengan
$$
\phi([x]_{n}) = [kx]_{n}
$$
merupakan automorfisma pada $\mathbb{Z}_{n}$. Lebih lanjut, misalkan $f: \mathbb{Z}_{n} \to \mathbb{Z}_{n}$ adalah automorfisma pada $\mathbb{Z}_{n}$ maka
$$
f([x]_{n}) = [\alpha x]_{n}
$$
untuk suatu $[\alpha] \in \mathbb{Z}_{n}$ sehingga $(a,n) = 1$.

---
## Bukti 1
Perhatikan bahwa $n \mid nk$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma Zn|Teorema]], maka $\phi$ adalah homomorfisma. 

Misalkan $[a]_{n}, [b]_{n} \in \mathbb{Z}_{n}$ sedemikian sehingga $\phi([a]_{n}) = \phi([b]_{n})$. Artinya
$$
[ka]_{n} = [kb]_{n} \quad\implies\quad n \mid ka - kb = k(a - b)
$$
Karena $(n, k) = 1$ dan $n \mid k(a - b)$ [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Hukum Pembatalan Keterbagian|maka]] $n \mid a - b$. Akibatnya $[a]_{n} = [b]_{n}$. Artinya $\phi$ bersifat injektif.

Ambil $[a]_{n}\in \mathbb{Z}_{n}$. Karena $(n, k) = 1$, berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Teorema Bezout]] maka terdapat $p, q \in \mathbb{Z}$ sehingga
$$
np + qk = 1 \quad\implies\quad anp + aqk = a 
$$
Pilih $[x]_{n} = [aq]_{n}$ maka
$$
kx - a = -anp \quad\implies\quad n \mid kx-a \quad\implies\quad [kx]_{n} = [a]_{n}
$$
Didapatkan $\phi([x]_{n}) = [a]_{n}$. Terbukti $\phi$ bersifat surjektif. 

Karena $\phi$ homomorfisma yang injektif dan surjektif, terbukti $\phi$ adalah isomorfisma.

## Bukti 2
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma Zn|Teorema]], maka $f([x]_{n}) = [kx]_{n}$ untuk suatu $k \in \mathbb{Z}$. Lebih lanjut karena $f$ isomorfisma maka terdapat $a \in \mathbb{Z}$ sehingga $f([a]_{n}) = [ka]_{n} = [1]_{n}$. Artinya $n \mid ka - 1$. Dengan kata lain, terdapat $p \in \mathbb{Z}$ sehingga
$$
ka - 1 = np \quad\implies\quad ka - np = 1
$$
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Karakterisasi Relatif Prima]] maka $(n, k) = 1$. Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Penjumlahan Zn]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Automorfisma Grup]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]
