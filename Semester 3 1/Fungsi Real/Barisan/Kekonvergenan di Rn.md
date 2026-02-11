Tinjau $(\mathbb{R}^n, \| \cdot \|_p)$ dan $\{x_n\}\subseteq \mathbb{R}^k$ dengan $x_i = (x_i(1),\ x_i(2),\ \cdots ,\ x_i(k))$ untuk setiap $i \in \mathbb{N}$.
$$x_n \to x \quad \iff \quad x_n(j) \to x(j) \ \ \forall j \in [1, k]_\mathbb{N}$$

---
## Bukti
###  $\Rightarrow:$
Misalkan $x_n \to x$. Ambil $j \in [1, k]_\mathbb{N}$. Ambil $\varepsilon > 0$. Terdapat $N \in \mathbb{N}$ sehingga untuk setiap $n > N$
    $$d(x_n, x) = \left(\sum_{i = 1}^k|x_n(i) - x(i)|^p\right)^{1/p} < \varepsilon$$
   Perhatikan bahwa untuk setiap $n > N$
    $$
    \begin{align*}
     |x_n(j) - x(j)|^p & \le \sum_{i = 1}^k|x_n(i) - x(i)|^p \\
     \\
     |x_n(j) - x(j)| &\le \left(\sum_{i = 1}^k|x_n(i) - x(i)|^p \right)^{1/p} \\
     \\
     & = d(x_n, x) 
     < \varepsilon
    \end{align*}
    $$
   Terbukti untuk setiap $j \in [1, k]_\mathbb{N}$ berlaku $x_n(j) \to x(j)$.

### $\Leftarrow:$

Misalkan untuk setiap $j \in [1, k]_\mathbb{N}$ berlaku $x_n(j) \to x(j)$. Ambil $\varepsilon > 0$. Untuk setiap $j \in [1, k]_\mathbb{N}:$
    $$\exists \ N_j \in \mathbb{N}, \ \forall n > N_j: \ |x_n(j) - x(j)| < k^{-1/p} \cdot \varepsilon$$
    Pilih $\displaystyle N = \max_{j \in [1, k]_\mathbb{N}} N_j$. Perhatikan bahwa untuk setiap $n > N:$
    $$
    \begin{align*}
     d(x_n, x) &= \left(\sum_{i = 1}^k|x_n(i) - x(i)|^p \right)^{1/p}
     < \left(\sum_{i = 1}^k\left(k^{-1/p} \cdot \varepsilon\right)^p \right)^{1/p} \\
     &= \left(\sum_{i = 1}^kk^{-1}\cdot \varepsilon^p \right)^{1/p} 
     = \left(k\cdot k^{-1}\cdot \varepsilon^p \right)^{1/p} = \varepsilon
    \end{align*}
    $$
    Terbukti bahwa $x_n \to x$.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik Rn Norm p]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]