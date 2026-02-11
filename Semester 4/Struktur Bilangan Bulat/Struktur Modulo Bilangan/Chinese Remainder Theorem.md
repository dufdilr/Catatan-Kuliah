#Teorema

Jika $(m, n) = 1$ maka $\forall a, b \in \mathbb{N}$, sistem persamaan
$$x \equiv a \pmod{m} \quad \text{dan} \quad x \equiv b \pmod{n}$$
memiliki **solusi tunggal** dalam modulo $mn$.

---
## Bukti

### Eksistensi Solusi
Dari kongruensi pertama, kita tahu bahwa $x$ harus berbentuk $x = a+mk$ untuk suatu $k \in \mathbb{Z}$. Substitusi nilai $x$ ini ke persamaan kedua:
$$
\begin{align*}
a + mk &\equiv b \pmod{n} \\
mk &\equiv b-a \pmod{n}
\end{align*}
$$
Karena $(m, n) = 1$, maka $[m]_n$ [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Invers Perkalian Zn|memiliki invers perkalian]] di $\mathbb{Z}_n$. Artinya, ada bilangan bulat $p$ sehingga $mp \equiv 1 \pmod{n}$. Kalikan kedua sisi kongruensi di atas dengan $p$:
$$
\begin{align*}
(pm)k &\equiv p(b-a) \pmod{n} \\
1 \cdot k &\equiv p(b-a) \pmod{n} \\
k &\equiv p(b-a) \pmod{n}
\end{align*}
$$
Ini berarti $k$ dapat ditulis sebagai $k = nq + p(b - a)$ untuk suatu $q \in \mathbb{Z}$. Substitusikan kembali nilai $k$ ini untuk menemukan $x$:
$$
\begin{align*}
x &= a + m(nq + p(b - a)) \\
x &= a + mnq + mp(b - a)
\end{align*}
$$
Dalam modulo $mn$, ini berarti $x \equiv a + mp(b - a) \pmod{mn}$. Jadi, solusi ada.

### Ketunggalan Solusi
Misalkan $x'$ adalah solusi lain dari sistem tersebut. Maka:
* $x \equiv a \pmod{m}$ dan $x' \equiv a \pmod{m} \quad \Rightarrow \quad x \equiv x' \pmod{m}$
* $x \equiv b \pmod{n}$ dan $x' \equiv b \pmod{n} \quad \Rightarrow \quad x \equiv x' \pmod{n}$

Ini berarti $m \mid (x - x')$ dan $n \mid (x - x')$. Karena $(m, n) = 1$, maka $mn \mid (x - x')$ yang berarti $x \equiv x' \pmod{mn}$.