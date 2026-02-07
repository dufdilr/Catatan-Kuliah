#Teorema

Misalkan $(x_n)$ dan $(y_n)$ adalah barisan konvergen di $\mathbb{X}$ dengan $x_n \to x$ dan $y_n \to y$. Maka, $x = y$ jika dan hanya jika 
$$\lim_{n\to\infty} d(x_n, y_n) = 0$$

---
## Bukti

* **($\Rightarrow$): Misalkan $x = y$.**
    Akan dibuktikan $\lim_{n\to\infty} d(x_n, y_n) = 0$.

    Ambil $\varepsilon > 0$. Karena kedua barisan konvergen, maka:
    $$
    \begin{align*}
        \exists N_1 \in \mathbb{N}, \ \forall n>N_1: \ d(x_n, x ) < \frac\varepsilon2 \\
        \exists N_2 \in \mathbb{N}, \ \forall n>N_2: \ d(y_n, y ) < \frac\varepsilon2
    \end{align*}
    $$
    Pilih $N = \max(N_1, N_2)$. Untuk setiap $n > N$, berlaku:
    $$
    \begin{align*}
        d(x_n, y_n) &\le d(x_n, x) + d(x, y_n) \\
        &\le d(x_n, x) + d(x, y) + d(y, y_n)
    \end{align*}
    $$
    Karena  $x=y$, maka $d(x,y)=0$. Sehingga:
    $$
    \begin{align*}
        d(x_n, y_n) &< \frac\varepsilon2 + 0 + \frac\varepsilon2 
        = \varepsilon
    \end{align*}
    $$
    Terbukti bahwa $\lim_{n\to\infty} d(x_n, y_n) = 0$.

* **($\Leftarrow$): Misalkan $\lim_{n\to\infty} d(x_n, y_n) = 0$.**
    Akan dibuktikan $x=y$.

    Ambil $\varepsilon > 0$. Karena konvergensi, kita memiliki:
    $$
    \begin{align*}
        \exists N_1 \in \mathbb{N}, \ \forall n>N_1:&\ d(x_n, x ) < \frac\varepsilon3 \\
        \exists N_2 \in \mathbb{N}, \ \forall n>N_2:&\ d(y_n, y ) < \frac\varepsilon3 \\
        \exists N_3 \in \mathbb{N}, \ \forall n>N_3:&\ d(x_n, y_n) < \frac\varepsilon3
    \end{align*}
    $$
    Pilih $N = \max(N_1, N_2, N_3)$. Untuk setiap $n > N$, ketiga kondisi di atas terpenuhi. Perhatikan jarak $d(x,y)$:
    $$
    \begin{align*}
    d(x, y) &\le d(x, x_n) + d(x_n, y_n) + d(y_n, y) \\
    &< \frac\varepsilon3 + \frac\varepsilon3 + \frac\varepsilon3 \\
    &= \varepsilon
    \end{align*}
    $$
    Karena untuk setiap $\varepsilon > 0$ berlaku $d(x, y)<\varepsilon$ [[Teorema Karakterisasi Nol|maka]] $d(x, y) = 0$.

    Terbukti bahwa $x = y$. ■

***
## Definition Used:
* [[Semester 5/Pengantar Analisis Real/Barisan Bilangan Real/Barisan Konvergen|Barisan Konvergen]]