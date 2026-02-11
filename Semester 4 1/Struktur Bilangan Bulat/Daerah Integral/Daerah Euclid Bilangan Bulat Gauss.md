#Teorema 
Gelanggang Bilangan Bulat Gauss $(\mathbb{Z}[i], +, \cdot)$ adalah daerah euclid.

---
## Bukti
Akan ditunjukkan beberapa hal.
1.  Akan ditunjukkan $\mathbb{Z}[i]$ merupakan daerah integral. Misalkan $a = a_1 + a_2 i,\ \ b = b_1 + b_2i \ \in \mathbb{Z}[i]$ dengan $a \neq 0$ dan $ab = 0$. Perhatikan bahwa
    $$ab = (a_1 + a_2i)(b_1+b_2i)
    = (a_1b_1 - a_2b_2) + (a_1b_2 + a_2b_1) i = 0 + 0i$$
    $$a_1b_1 = a_2b_2$$
    $$a_1b_2 + a_2b_1 = 0 $$
    Sehingga $a_1b_1 = a_2b_2$ dan $a_1b_2 + a_2b_1 = 0$. Perhatikan bahwa
    $$
    \begin{align*}
    b_1(a_1b_2 + a_2b_1) &= a_1b_1b_2 + a_2b_1^2 = (a_2b_2)b_2 + a_2b_1^2 \\
    &= a_2 (b_1^2 + b_2^2) = 0 &&(i) \\
    \\
    b_2(a_1b_2 + a_2b_1) &= a_1b_2^2 + a_2b_1b_2 = a_1b_2^2 + (a_1b_1)b_1 \\
    &= a_1 (b_1^2 + b_2^2) = 0 &&(ii)
    \end{align*}
    $$
    Karena $a_1 + a_2i \neq 0$ maka $b_1^2 + b_2^2 = 0$. Maka $b_1 = b_2 = 0$, sehingga $b = 0$.
    Berarti $\mathbb{Z}[i]$ adalah daerah integral.
2.  Tinjau $\delta(a + bi) = a^2 + b^2$. Perhatikan bahwa $\delta(a + bi) = a^2 + b^2 \in \mathbb{Z}^+$. Lebih lanjut
    $$
    \begin{align*}
    \delta(ab) &= \delta\left((a_1b_1 - a_2b_2) + (a_1b_2 + a_2b_1)i\right) \\
    &= (a_1b_1 - a_2b_2)^2 + (a_1b_2 + a_2b_1)^2 \\
    &= (a_1^2 + a_2^2)(b_1^2 + b_2^2) = \delta(a)\delta(b)
    \end{align*}
    $$
    Sehingga jelas $\delta(a) \le \delta(a) \delta(b) = \delta(ab)$
3.  Ambil $a, b \in \mathbb{Z}[i]$ dengan $a \neq 0$. Perhatikan bahwa
    $$
    \begin{align*}
    \frac{b_1 + b_2i}{a_1+a_2i} &= \frac{b_1 + b_2i}{a_1+a_2i} \cdot \frac{a_1 - a_2i}{a_1-a_2i} = \frac{(a_1b_1 + a_2b_2) + (a_1b_2 - a_2b_1)i}{a_1^2 + a_2^2} = \frac{M + Ni}{A}
    \end{align*}
    $$
    dengan $a_1b_1 + a_2b_2 = M, \quad a_1b_2 - a_2b_1 = N, \quad a_1^2 + a_2^2 = A$. Berdasarkan Algoritma Pembagian dapat dituliskan
    $$
    \begin{align*}
    M &= q'_1 A + r'_1 & 0 \le r'_1 < A \\
    N &= q'_2 A + r'_2 & 0 \le r'_2 < A
    \end{align*}
    $$
    Jika $r'_1 < \frac{A}{2}$, pilih $r_1 = r'_1$ dan $q_1 = q'_1$. Jika $r'_1 \ge \frac{A}{2}$, pilih $r_1 = r'_1 - A$ dan $q_1 = q'_1 + 1$. $r_2$ dan $q_2$ didefinisikan serupa sehingga dapat dituliskan
$$
\begin{align*}
M &= q_1 A + r_1 \\
 -\frac{A}{2} &\le r_1 < \frac{A}{2} \\
N &= q_2 A + r_2 \\
-\frac{A}{2} &\le r_2 < \frac{A}{2}
\end{align*}
$$
Artinya, dapat kita tuliskan
$$
\begin{align*}
\frac{b_1 + b_2i}{a_1+a_2i} &= \frac{q_1 A + r_1 + \left(q_2 A + r_2\right)i}{A} \\
&= q_1 + q_2 i + \frac{r_1 + r_2i}{(a_1 + a_2i)(a_1 - a_2i)} \\
b_1+b_2i &= (q_1+q_2i)(a_1+a_2i) + \frac{r_1 + r_2i}{a_1 - a_2i}
\end{align*}
$$
Pilih $q = q_1 + q_2 i$ dan $\displaystyle r = \frac{r_1 + r_2i}{a_1 - a_2i}$. Dapat dituliskan
$$b = qa + r$$
Perhatikan bahwa $r =b - qa$. Karena $a, b, q \in \mathbb{Z}[i]$, dan $\mathbb{Z}[i]$ gelanggang maka $r \in \mathbb{Z}[i]$. Lebih lanjut $r \cdot (a_1-a_2i) = (r_1 + r_2i) \quad \Rightarrow \quad \delta(r) \cdot \delta(a) =r_1^2+r_2^2$ sehingga
$$
\begin{align*}
\delta(r) &= \frac{r_1^2 + r_2^2}{A} \le \frac{1}{A} \left(\frac{A^2}{4} + \frac{A^2}{4}\right) = \frac{A}{2} < A = \delta(a)
\end{align*}
$$


Terbukti $\mathbb{Z}[i]$ membentuk daerah euclid.

***

## Definition Used 
 * [[Daerah Euclid]]
 * [[Gelanggang Bilangan Bulat Gauss]]