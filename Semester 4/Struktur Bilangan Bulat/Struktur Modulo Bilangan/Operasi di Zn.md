#Definisi #Teorema

Misalkan $n$ bilangan asli. Definisikan operasi penjumlahan dan perkalian di $\mathbb{Z}_{n}$ sebagai
$$
\begin{align*}
[a]_{n} + [b]_{n} &= [a+b]_{n} \\
[a]_{n}\cdot [b]_{n} &= [ab]_{n}
\end{align*}
$$
Operasi tersebut terdefinisi dengan baik.

---
## Bukti
### Well-Defined Penjumlahan
Misalkan $[a_1]_n = [a_2]_n$ dan $[b_{1}]_{n} = [b_{2}]_{n}$. Artinya $n \mid (a_1 - a_2)$ dan $n \mid (b_1 - b_2)$. Akan ditunjukkan 
$$[a_{1}]_{n} + [b_{1}]_{n} = [a_{2}]_{n} + [b_{2}]_{n}$$
Perhatikan karena  $[a_1]_n = [a_2]_n$ dan $[b_{1}]_{n} = [b_{2}]_{n}$ maka $n \mid (a _1 - a_2)$ dan $n \mid (b_{1} - b_{2})$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|sifat keterbagian]] maka $n \mid (a_{1}-a_{2}) + (b_{1}-b_{2}) = (a_1 + b_1) - (a_2 + b_2)$. Terbukti
$$
\begin{align*}
[a_{1}]_{n} + [b_{1}]_{n} &= [a_{1} + b_{1}]_{n} = [a_{2} + b_{2}]_{n} = [a_{2}]_{n} + [b_{2}]_{n} \\
\end{align*}
$$
Maka penjumlahan tersebut terdefinisi dengan baik.

### Well-Defined Perkalian
Misalkan $[a_1]_n = [a_2]_n$ dan $[b_{1}]_{n} = [b_{2}]_{n}$. Artinya $n \mid (a_1 - a_2)$ dan $n \mid (b_1 - b_2)$. Akan ditunjukkan 
$$[a_{1}]_{n} \cdot [b_{1}]_{n} = [a_{2}]_{n}\cdot  [b_{2}]_{n}$$
Perhatikan karena  $[a_1]_n = [a_2]_n$ dan $[b_{1}]_{n} = [b_{2}]_{n}$ maka $n \mid (a _1 - a_2)$ dan $n \mid (b_{1} - b_{2})$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|sifat keterbagian]] maka $n|b_{1}(a_{1}-a_{2})+a_{2}(b_{1}-b_{2}) = a_{1}b_{1} - a_{2}b_{2}$. Artinya $[a_{1}b_{1}]_{n} = [a_{2}b_{2}]_{n}$ Terbukti
$$
\begin{align*}
[a_{1}]_{n} \cdot [b_{1}]_{n} &= [a_{1}  b_{1}]_{n} = [a_{2}  b_{2}]_{n} = [a_{2}]_{n} \cdot [b_{2}]_{n} \\
\end{align*}
$$
Maka perkalian tersebut terdefinisi dengan baik.

***
## Definition Used:
* [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Himpunan Zn]]
* [[Buat Backup/Prerquested/Relasi dan Fungsi/Operasi]]


