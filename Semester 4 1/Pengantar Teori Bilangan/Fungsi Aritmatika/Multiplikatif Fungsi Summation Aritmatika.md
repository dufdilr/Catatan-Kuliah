#Teorema 

Jika $f$ adalah fungsi multiplikatif maka Summation Aritmatika dari $f$ juga **multiplikatif**.

## Bukti
Misalkan $m, n \in \mathbb{N}$ dengan $(m, n) = 1$. Ambil sembarang $d \in \mathbb{N}$ dengan $d \mid mn$. Perhatikan bahwa terdapat [[Faktor Saling Prima|bijeksi]] dari faktor $mn$ dengan $d_1, d_2$ faktor dari $m$ dan $n$. Maka
$$
\begin{align*}
F(mn) &= \sum_{d \mid mn} f(d) =  \sum_{d_1d_{2}\mid mn} f(d_1d_{2})
\end{align*}
$$
Karena $(m, n) = 1$ maka $(d_1,d_2) = 1$. Karena $f$ fungsi multiplikatif maka
$$
\begin{align*}
F(mn) &= \sum_{d_1d_{2}\mid mn} f(d_1)(d_{2}) = \sum_{d_{1}\mid m ; d_{2} \mid n} f(d_1) f(d_{2}) \\
&= \sum_{d_{1}\mid m} \sum_{d_{2}\mid n} f(d_{1}) f(d_{2}) = \sum_{d_{1}\mid m} f(d_{1}) \sum_{d_{2}\mid n}  f(d_{2}) \\
&= \sum_{d_{1}\mid m} f(d_{1}) F(n) \\
&= F(m) F(n)
\end{align*}
$$
Terbukti, fungsi Summation Aritmatika juga fungsi multiplikatif.

***
## Definition Used 
 * [[Fungsi Summation Aritmatika]]
 * [[Fungsi Multiplikatif]]
