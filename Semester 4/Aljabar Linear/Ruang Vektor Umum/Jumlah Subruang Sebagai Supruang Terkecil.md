#Teorema

Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$. Himpunan $V_1 + V_2 + \cdots + V_n$ merupakan **Subruang Terkecil** dari $V$ yang memuat $V_1, V_2, ... , V_n$

---
## Bukti
### Bukti Subruang $V$
Jelas ${0} \in V_1, V_2, \cdots, V_n$. Artinya
$$
{0} = {0} + {0} + \cdots + {0} \in V_1 + V_2 + \cdots + V_n
$$
Artinya $V_1 + V_2 + \cdots + V_n$ takkosong. Berdasarkan sifat [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]] maka setiap unsur di $V_1 + V_2 + \cdots + V_n$ juga unsur $V$. Berarti $V_1 + V_2 + \cdots + V_n$ adalah subhimpunan tak-kosong dari $V$

Lebih lanjut, ambil $\lambda \in \mathbf{F}$  dan  ${v}, {w} \in V_1 + V_2 + \cdots + V_n$  dengan ${v} = {v_1} + {v_2} + \cdots + {v_n}$ dan ${w} = {w_1} + {w_2} + \cdots + {w_n}$ dimana ${v_i},\ {w_i} \in V_i$ untuk setiap indeks $i$. Perhatikan bahwa
$$
\begin{align*}
{v} + {w} &= \left({v_1} + {v_2} + \cdots + {v_n}\right) + \left({w_1} + {w_2} + \cdots + {w_n}\right) \\
&= \left({v_1}+{w_1}\right) + \left({v_2}+{w_2}\right) + \cdots + \left({v_n}+{w_n}\right) \\
\\
\lambda {v} &= \lambda \left({v_1} + {v_2} + \cdots + {v_n}\right) \\
&= \left(\lambda {v_1}\right) + \left(\lambda {v_2}\right) + \cdots + \left(\lambda {v_n}\right)
\end{align*}
$$
Perhatikan bahwa ${v_i},\ {w_i} \in V_i$ sehingga $\left({v_i}+{w_i}\right), \lambda {v_i} \in V_i$. Artinya $\left({v}+{w}\right), \lambda {v} \in V_1 + V_2 + \cdots V_n$. Berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Subruang]] maka $V_1 + V_2 + \cdots + V_n$ adalah subruang dari $V$.

### Bukti Subruang Terkecil
Misalkan $W$ adalah subruang yang memuat $V_1, V_2, \cdots, V_n$. Ambil ${v} \in V_1 + V_2 + \cdots + V_n$ dengan ${v} = {v_1} + {v_2} + \cdots + {v_n}$. Perhatikan bahwa ${v_i} \in V_i \subseteq W$. Artinya ${v_i} \in W$. Karena $W$ subruang maka 
$$
{v} = {v_1} + {v_2} + \cdots + {v_n} \in W
$$
Akibatnya $V_1 + V_2 + \cdots V_n \subseteq W$. Terbukti.

***
## Definition Used:
* [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
* [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]