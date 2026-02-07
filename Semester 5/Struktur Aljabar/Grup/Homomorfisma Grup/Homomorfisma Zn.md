#Teorema 
Misalkan $m, n,k \in \mathbb{N}$ dengan $n \mid km$. Maka fungsi $\phi:\mathbb{Z}_{m} \to \mathbb{Z}_{n}$ dengan
$$
\phi([x]_{m}) = [kx]_{n}
$$
merupakan homomorfisma. Lebih lanjut, misalkan $f: \mathbb{Z}_{m} \to \mathbb{Z}_{n}$ adalah homomorfisma maka
$$
f([x]_{m}) = [\alpha x]_{n}
$$
untuk suatu $[\alpha] \in \mathbb{Z}_{n}$ sehingga $n \mid \alpha m$.

---
## Bukti 1
### Terdefinisi Dengan Baik
Ambil $[x]_{m} = [y]_{m} \in \mathbb{Z}_{m}$. Artinya $m \mid (x - y)$ atau $x-y = ml_1$ untuk suatu $l_{1}\in \mathbb{Z}$. Perhatikan bahwa
$$
\phi([x]_{m}) - \phi([y]_{m}) = [kx]_{n} - [ky]_{n} = [k(x-y)]_{n}
$$
Perhatikan bahwa
$k(x-y) = kml_{1}$. Karena $n \mid km$ maka $n \mid  k(x - y)$. Artinya
$$
\phi([x]_{m}) = \phi([y]_{n})
$$
Maka $\phi$ terdefinisi dengan baik.

### Homomorfisma
Ambil $[x]_{m} , [y]_{m} \in \mathbb{Z}_{m}$. Perhatikan bahwa
$$
\phi([x]_{m} + [y]_{m}) = \phi([x+y]_{m}) = [k(x+y)]_{n} = [kx+ky]_{n} = [kx]_{n} + [ky]_{n} = \phi([x]_{m}) + \phi([y]_{m})
$$
Maka terbukti $\phi$ adalah homomorfisma grup.

## Bukti 2
Misalkan $f : \mathbb{Z}_{m} \to \mathbb{Z}_{n}$ adalah homomorfisma. Perhatikan bahwa
$$
f([x]_{m}) = f([1]_{m}+[1]_{m}+\dots+[1]_{m}) = f([1]_{m}) + f([1]_{m})+\dots+f([1]_{m}) = [f([1]_{m}) \cdot x]_{n}
$$
Pilih $\alpha = f([1]_{m})$. Berdasarkan [[Sifat Homomorfisma Grup]] maka
$$
f([m]_{m}) = f([0]_{m}) = [\alpha m]_{n} = [0]_{n}
$$
Artinya $n \mid \alpha m$. Terbukti.

***
## Definition Used 
 * [[Grup Penjumlahan Zn]]
 * [[Homomorfisma (Grup)]]
 * [[Keterbagian]]