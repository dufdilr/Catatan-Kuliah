#Teorema

Misalkan $(x_{n}) \subseteq \mathbb{X}$ adalah barisan yang [[Barisan Konvergen (Metrik)|konvergen]]. Jika $x_n \to x$ dan $x_n \to x'$, maka haruslah $x = x'$.

---
## Bukti
Misalkan $(x_{n}) \subseteq \mathbb{X}$ dengan $x_n \to x$ dan $x_n \to x'$. Ambil sembarang $\varepsilon > 0$.  Karena definisi kekonvergenan, maka 
$$
\begin{align*}
        \exists N_1 \in \mathbb{N}, \ \forall n>N_1:\ d(x_n, x) < \frac{\varepsilon}{2}\\
        \exists N_{2} \in \mathbb{N}, \ \forall n>N_2:\ d(x_n, x') < \frac{\varepsilon}{2}
    \end{align*}
$$
Pilih $N = \max(N_1, N_2)$. Berdasarkan ketaksamaan segitiga maka 
$$d(x, x') \le d(x, x_N) + d(x_N, x') < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon$$
Karena $\forall \varepsilon >0$ berlaku $d(x, x') < \varepsilon$ [[Teorema Karakterisasi Nol|maka]] dapat disimpulkan:
$$d(x, x') = 0 \quad \Rightarrow \quad x = x'$$
Ini membuktikan bahwa limit dari sebuah barisan adalah tunggal. ■

***
## Definition Used:
* [[Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]