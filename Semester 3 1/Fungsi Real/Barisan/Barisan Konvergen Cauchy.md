#Teorema

Jika $(x_n) \subseteq \mathbb{X}$ adalah barisan konvergen ke $x \in \mathbb{X}$ maka $(x_n)$ merupakan barisan cauchy.

---
## Bukti
Misalkan $(x_n) \subseteq \mathbb{X}$ adalah barisan konvergen ke $x \in \mathbb{X}$. Ambil $\varepsilon > 0$. 
Berdasarkan definisi konvergensi,
$$
\exists \ N\in \mathbb{N}, \ \forall \ n>N: \ d(x_n, x) < \frac{\varepsilon}{2}
$$
Perhatikan bahwa untuk setiap $n, m > N$:
$$
\begin{align*}
d(x_n, x_m) &\le d(x_n, x) + d(x, x_m) \\
&= d(x_n, x) + d(x_m, x) \\
&< \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon
\end{align*}
$$
Maka $(x_n) \subseteq \mathbb{X}$ adalah barisan cauchy. ■

***
## Definition Used
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan (Metrik)]]
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
* [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Cauchy (Metrik)]]