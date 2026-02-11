#Teorema 

Misalkan $S \subseteq \mathbb{Z}$. $S$ subgelanggang jika dan hanya jika $S = n\mathbb{Z}$ untuk suatu $n \in \mathbb{Z}$.

---

## Bukti

### ($\Leftarrow:$)

Akan ditunjukkan $n\mathbb{Z}$ subgelanggan dari $\mathbb{Z}$. Ambil $a, b \in n\mathbb{Z}$. Maka, $a = np, \ b = nq$. Jelas $\emptyset \neq n\mathbb{Z} \subseteq \mathbb{Z}$.
1.  $a + b = np + nq = n(p+q) \in n\mathbb{Z}$
2.  $a + (-b) = np + (-nq) = n(p-q) \in n\mathbb{Z}$
3.  $a \cdot b = np \cdot nq = n(npq) \in n\mathbb{Z}$

Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Karakterisasi Subgelanggang|teorema]], maka $n\mathbb{Z}$ subruang dari $\mathbb{Z}$.

### ($\Leftarrow$:)

Misalkan $S$ subgelanggang takkosong dari $\mathbb{Z}$. Tinjau $S^* = S \cap \mathbb{N}$. Karena $S^* \subseteq \mathbb{N}$ maka berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]] maka ada unsur terkecil $S^*$, sebut saja $n$.

Kemudian akan ditunjukkan bahwa $S = n\mathbb{Z}$.

#### ($\subseteq:$)
Ambil $x \in S$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Algoritma Pembagian]] $\exists q, r \in \mathbb{Z}$ sehingga
$$x = pn + r\quad\text{ dan }\quad0 \le r < n$$
Perhatikan bahwa $pn$ adalah penjumlahan $n$ (atau $-n$) sebanyak $p$ kali. Artinya, $pn \in S$.

Karena $r = x - pn$ dan $S$ subgelanggang maka $r \in S$. Karena $r < n$ maka $r\notin S^*$.
Artinya $r \le 0$. Karena $r \ge 0$ dan $r \le 0$ maka $r = 0$. Akibatnya $x = pn \in n\mathbb{Z}$.

Berarti $S \subseteq n\mathbb{Z}$.

#### ($\supseteq:$) 
Ambil $x \in n\mathbb{Z}$. Maka $x = nk, \quad \exists k \in \mathbb{Z}$. Perhatikan bahwa $nk$ adalah penjumlahan $n$ (atau $-n$) sebanyak $k$ kali. Artinya, $nk \in S$. Berarti $n\mathbb{Z} \subseteq S$.

Maka terbukti $S = n\mathbb{Z}$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Z]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Subgelanggang]]