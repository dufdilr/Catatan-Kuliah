#Teorema 

1.  $\forall n \in \mathbb{Z}: \quad 1 \mid n$
2.  Jika $m \neq 0$, maka $m \mid 0$
3.  Jika $m \mid n$ dan $n \mid q$, maka $m \mid q$ (**Sifat Transitif**) ^39704a
4.  Jika $d \mid m$ dan $d \mid n$, maka $d \mid (tm + sn)$ untuk setiap $t, s \in \mathbb{Z}$ (**Sifat Kelinieran**) ^ab6a93
5.  Jika $m \mid 1$, maka $m = 1$ atau $m = -1$
6.  Jika $m \mid n$ dan $n \mid m$, maka $m = \pm n$ ^d21346

***
## Bukti

### 1. Bukti untuk $1 \mid n$
Perhatikan bahwa $n = 1 \cdot n$, maka terbukti bahwa **$1 \mid n$**.

### 2. Bukti untuk $m \mid 0$
Perhatikan bahwa $0 = 0 \cdot m$ maka $m \mid 0$

### 3. Bukti Sifat Transitif
Misalkan $m \mid n$ dan $n \mid q$. Artinya terdapat $k_1, k_2 \in \mathbb{N}$ sehingga
$$n = m\cdot k_{1} \quad \text{dan} \quad q = n \cdot k_{2}$$
Perhatikan bahwa 
$$
\begin{align*}
q &= n \cdot k_{2} = m \cdot k_{1}\cdot k_{2}
\end{align*}
$$
Karena $k_1k_2 \in \mathbb{N}$ maka $m \mid q$

### 4. Bukti Sifat Kelinieran
Diketahui $d \mid m$ dan $d \mid n$.
* $d \mid m$ berarti $m = d \cdot k_1$ untuk suatu $k_1 \in \mathbb{Z}$.
* $d \mid n$ berarti $n = d \cdot k_2$ untuk suatu $k_2 \in \mathbb{Z}$.

Tinjau ekspresi $(tm + sn)$ untuk sembarang $t, s \in \mathbb{Z}$:
$$tm + sn = t(d \cdot k_1) + s(d \cdot k_2)$$
$$tm + sn = d(tk_1) + d(sk_2)$$
$$tm + sn = d(tk_1 + sk_2)$$
Misalkan $k_3 = tk_1 + sk_2$. Karena $t, s, k_1,$ dan $k_2$ semuanya bilangan bulat, maka $k_3$ juga bilangan bulat. Kita telah menemukan $k_3 \in \mathbb{Z}$ sehingga $tm+sn = d \cdot k_3$.
Jadi, terbukti bahwa **$d \mid (tm + sn)$**.



### 5. Bukti untuk $m \mid 1$
Diketahui $m \mid 1$. Menurut definisi, ini berarti ada $k \in \mathbb{Z}$ sehingga $1 = m \cdot k$.
Satu-satunya pasangan bilangan bulat yang hasil perkaliannya adalah 1 adalah $(1, 1)$ dan $(-1, -1)$.
* Jika $k=1$, maka $m=1$.
* Jika $k=-1$, maka $m=-1$.
Jadi, terbukti bahwa jika $m \mid 1$, maka **$m = 1$ atau $m = -1$**.



### 6. Bukti untuk $m \mid n$ dan $n \mid m$
Diketahui $m \mid n$ dan $n \mid m$.
* $m \mid n$ berarti $n = m \cdot k_1$ untuk suatu $k_1 \in \mathbb{Z}$.
* $n \mid m$ berarti $m = n \cdot k_2$ untuk suatu $k_2 \in \mathbb{Z}$.

Substitusikan persamaan kedua ke persamaan pertama:
$$n = (n \cdot k_2) \cdot k_1$$
$$n = n \cdot (k_1 k_2)$$
Jika $n \neq 0$, kita bisa membagi kedua sisi dengan $n$ dan mendapatkan $1 = k_1 k_2$. Berdasarkan bukti nomor 5, ini berarti $(k_1, k_2)$ bisa jadi $(1, 1)$ atau $(-1, -1)$.
* Jika $k_1 = 1$, maka dari $n = m \cdot k_1$, kita dapatkan $n=m$.
* Jika $k_1 = -1$, maka dari $n = m \cdot k_1$, kita dapatkan $n=-m$.

Jika $n=0$, maka dari $m=n \cdot k_2$ didapat $m=0$. Dalam kasus ini, $m=n=0$ juga memenuhi $m = \pm n$.
Jadi, terbukti bahwa **$m = \pm n$**.

***
## Definition used:
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Keterbagian]]