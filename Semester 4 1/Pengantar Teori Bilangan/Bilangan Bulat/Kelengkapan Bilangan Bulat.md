#Teorema 

Misalkan $A \subseteq \mathbb{Z}$ subhimpunan tak-kosong dari bilangan bulat. Berlaku
1. Jika $A$ terbatas di atas maka terdapat unsur maksimum.
2. Jika $A$ terbatas di bawah maka terdapat unsur minimum.

---
## Bukti

### Maksimum
Misalkan $A \subseteq \mathbb{Z}$ terbatas di atas. Berarti terdapat $M \in \mathbb{Z}$ sedemikian sehingga untuk setiap $a \in A$ berlaku $a \le M$.
Tinjau himpunan
$$
S := \{ M - a + 1 \ | \ a \in A \}
$$
Ambil sebarang $s \in S$. Maka $s = M - a + 1$ untuk suatu $a \in A$. Karena $a \le M$, maka $M - a \ge 0$. Artinya, $M - a + 1 \in \mathbb{N}$. Akibatnya, $S \subseteq \mathbb{N}$. Karena $A \neq \emptyset$, maka $S \neq \emptyset$.

Berdasarkan [[Aksioma Urutan Sempurna]], maka $A$ memiliki unsur terkecil. Misalkan $s_0 = \min(S)$.
Karena $s_0 \in S$, terdapat $a_0 \in A$ sehingga $s_0 = M - a_0 + 1$.

Akan ditunjukkan bahwa $a_0 = \max(A)$.
Ambil sebarang $x \in A$. Maka $s_x = M - x + 1 \in S$. Karena $s_0$ elemen terkecil di $S$, maka $s_0 \le s_x$. Perhatikan bahwa
$$
\begin{align*}
M - a_0 + 1 &\le M - x + 1 \\
-a_0 &\le -x \\
a_0 &\ge x
\end{align*}
$$
Karena $a_0 \in A$ dan untuk setiap $x \in A$ berlaku $x \le a_0$, maka $a_0$ adalah maksimum dari $A$.

### Minimum

Andaikan $A \subseteq \mathbb{Z}$ terbatas di bawah. Berarti terdapat $m \in \mathbb{Z}$ sedemikian sehingga untuk setiap $a \in A$ berlaku $a \ge m$.
Tinjau himpunan
$$
T := \{ a - m + 1 \ | \ a \in A \}
$$
Ambil sebarang $t \in T$. Maka $t = a - m + 1$ untuk suatu $a \in A$. Karena $a \ge m$, maka $a - m \ge 0$. Sehingga $t \in \mathbb{N}$. Akibatnya, $T \subseteq \mathbb{N}$. Karena $A \neq \emptyset$, maka $T \neq \emptyset$.

Berdasarkan [[Aksioma Urutan Sempurna]], $T$ memiliki unsur terkecil. Misalkan $t_0 = \min(T)$.
Karena $t_0 \in T$, terdapat $a_0 \in A$ sehingga $t_0 = a_0 - m + 1$.

Akan ditunjukkan bahwa $a_0 = \min(A)$.
Ambil sebarang $x \in A$. Maka $t_x = x - m + 1 \in T$.
Karena $t_0$ elemen terkecil di $T$, maka $t_0 \le t_x$.
$$
\begin{align*}
a_0 - m + 1 &\le x - m + 1 \\
a_0 &\le x
\end{align*}
$$
Karena $a_0 \in A$ dan untuk setiap $x \in A$ berlaku $x \ge a_0$, maka $a_0$ adalah minimum dari $A$.

Terbukti.

***
## Definition Used
* [[Aksioma Bilangan Bulat]]
* [[Aksioma Urutan Sempurna]]
* [[Urutan Bilangan Bulat]]
* [[Himpunan]]