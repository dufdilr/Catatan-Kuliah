#Teorema 
Misalkan $V_1, V_2, \cdots , V_n$ adalah ruang vektor atas lapangan $\mathbb{F}$. Misalkan
$$
W = V_{1} \times V_{2} \times \cdots \times V_n = \{ (v_1, v_{2}, \cdots, v_n) \ : \ v_i \in V_i \}
$$
Definisikan operasi di $W$ untuk setiap $\lambda \in \mathbb{F}$ dan $(v_1,v_{2}, \cdots , v_n), (w_1,w_{2}, \cdots , w_n) \in W$ berlaku
$$
(v_1,v_{2}, \cdots , v_n) + (w_1,w_{2}, \cdots , w_n) = (v_1 + w_{1},v_{2} + w_{2}, \cdots , v_n + w_n) 
$$
$$
\lambda \cdot (v_1,v_{2}, \cdots , v_n) = (\lambda v_1, \lambda v_{2}, \cdots , \lambda v_n)
$$Himpunan $W$ dengan operasi tersebut membentuk **ruang vektor**.

---
## Bukti
Misalkan $\mathbf{0_i}$ adalah vektor nol di ruang vektor $V_i$. Misalkan $\mathbf{0_W} = (\mathbf{0_1}, \mathbf{0_2}, \cdots, \mathbf{0_n})$.
### 1. Asosiatif Penjumlahan
Ambil $u, v, w \in W$ dan $\alpha, \beta \in \mathbb{F}$ dengan $u = (u_1,u_{2}, \cdots , u_n), v = (v_1,v_{2}, \cdots , v_n), w = (w_1,w_{2}, \cdots , w_n)$. Perhatikan bahwa
$$
\begin{align*}
u + (v + w) &= (u_1,u_{2}, \cdots , u_n) + \left( (v_1,v_{2}, \cdots , v_n) + (w_1,w_{2}, \cdots , w_n) \right) \\
&= (u_1,u_{2}, \cdots , u_n) + (v_1 + w_1,v_{2} + w_{2}, \cdots , v_n + w_n) \\
&= (u_{1}+(v_1 + w_1), u_2+(v_{2} + w_{2}), \cdots , u_n+(v_n + w_n)) \\
&= ((u_{1}+v_1) + w_1, (u_2+v_{2}) + w_{2}, \cdots , (u_n+v_n) + w_n) \\
&= (u_1 + v_{1},u_{2} + v_{2}, \cdots , u_n + v_n) + (w_1,w_{2}, \cdots , w_n) \\
&= \left((u_1,u_{2}, \cdots , u_n) + (v_1,v_{2}, \cdots , v_n) \right) + (w_1,w_{2}, \cdots , w_n) \\
&= (u + v) + w
\end{align*}
$$

### 2.  Komutatif Penjumlahan
Ambil $u, v \in W$ dengan $u = (u_1,u_{2}, \cdots , u_n), v = (v_1,v_{2}, \cdots , v_n)$. Perhatikan bahwa
$$
\begin{align*}
u + v &= (u_1,u_{2}, \cdots , u_n) + (v_1,v_{2}, \cdots , v_n) \\
&= (u_1 + v_{1},u_{2} + v_{2}, \cdots , u_n + v_n) \\
&= (v_1 + u_{1},v_{2} + u_{2}, \cdots , v_n + u_n) \\
&= (v_1,v_{2}, \cdots , v_n) + (u_1,u_{2}, \cdots , u_n) \\
&= v + u
\end{align*}
$$

### 3.  Elemen Identitas Penjumlahan
Misalkan $\mathbf{0_i}$ adalah vektor nol di ruang vektor $V_i$. Misalkan $\mathbf{0_W} = (\mathbf{0_1}, \mathbf{0_2}, \cdots, \mathbf{0_n})$. Ambil $u \in W$ dengan $u = (u_1,u_{2}, \cdots , u_n)$. Perhatikan bahwa
$$
\begin{align*}
u + \mathbf{0_W} &= (u_1,u_{2}, \cdots , u_n) + (\mathbf{0_1}, \mathbf{0_2}, \cdots, \mathbf{0_n}) \\
&= (u_1 + \mathbf{0_1}, u_2 + \mathbf{0_2}, \cdots, u_n + \mathbf{0_n}) \\
&= (u_1, u_2, \cdots, u_n) \\
&= u
\end{align*}
$$

### 4. Inverse Penjumlahan
Ambil $u \in W$ dengan $u = (u_1,u_{2}, \cdots , u_n)$. Pilih $-u = (-u_1,-u_{2}, \cdots , -u_n)$. Perhatikan bahwa
$$
\begin{align*}
u + (-u) &= (u_1,u_{2}, \cdots , u_n) + (-u_1,-u_{2}, \cdots , -u_n) \\
&= (u_1 + (-u_1), u_2 + (-u_2), \cdots, u_n + (-u_n)) \\
&= (\mathbf{0_1}, \mathbf{0_2}, \cdots, \mathbf{0_n}) \\
&= \mathbf{0_W}
\end{align*}
$$
### 5. Distributif Penjumlahan Vektor
Ambil $u, v \in W$ dan $\alpha \in \mathbb{F}$ dengan $u = (u_1,u_{2}, \cdots , u_n), v = (v_1,v_{2}, \cdots , v_n)$. Perhatikan bahwa
$$
\begin{align*}
\alpha (u + v) &= \alpha \left( (u_1,u_{2}, \cdots , u_n) + (v_1,v_{2}, \cdots , v_n) \right) \\
&= \alpha (u_1 + v_{1}, u_{2} + v_{2}, \cdots , u_n + v_n) \\
&= (\alpha(u_1 + v_{1}), \alpha(u_{2} + v_{2}), \cdots , \alpha(u_n + v_n)) \\
&= (\alpha u_1 + \alpha v_{1}, \alpha u_{2} + \alpha v_{2}, \cdots , \alpha u_n + \alpha v_n) \\
&= (\alpha u_1, \alpha u_{2}, \cdots , \alpha u_n) + (\alpha v_1, \alpha v_{2}, \cdots , \alpha v_n) \\
&= \alpha (u_1, u_{2}, \cdots , u_n) + \alpha (v_1, v_{2}, \cdots , v_n) \\
&= \alpha u + \alpha v
\end{align*}
$$

### 6. Distributif Penjumlahan Skalar
Ambil $u \in W$ dan $\alpha, \beta \in \mathbb{F}$ dengan $u = (u_1,u_{2}, \cdots , u_n)$. Perhatikan bahwa
$$
\begin{align*}
(\alpha + \beta) u &= (\alpha + \beta) (u_1,u_{2}, \cdots , u_n) \\
&= ((\alpha + \beta)u_1, (\alpha + \beta)u_{2}, \cdots , (\alpha + \beta)u_n) \\
&= (\alpha u_1 + \beta u_1, \alpha u_{2} + \beta u_{2}, \cdots , \alpha u_n + \beta u_n) \\
&= (\alpha u_1, \alpha u_{2}, \cdots , \alpha u_n) + (\beta u_1, \beta u_{2}, \cdots , \beta u_n) \\
&= \alpha (u_1, u_{2}, \cdots , u_n) + \beta (u_1, u_{2}, \cdots , u_n) \\
&= \alpha u + \beta u
\end{align*}
$$

### 7. Asosiatif Perkalian Skalar
Ambil $u \in W$ dan $\alpha, \beta \in \mathbb{F}$ dengan $u = (u_1,u_{2}, \cdots , u_n)$. Perhatikan bahwa
$$
\begin{align*}
(\alpha \beta) u &= (\alpha \beta) (u_1,u_{2}, \cdots , u_n) \\
&= ((\alpha \beta)u_1, (\alpha \beta)u_{2}, \cdots , (\alpha \beta)u_n) \\
&= (\alpha (\beta u_1), \alpha (\beta u_{2}), \cdots , \alpha (\beta u_n)) \\
&= \alpha (\beta u_1, \beta u_{2}, \cdots , \beta u_n) \\
&= \alpha \left( \beta (u_1, u_{2}, \cdots , u_n) \right) \\
&= \alpha (\beta u)
\end{align*}
$$

### 8. Identitas Perkalian Skalar
Ambil $u \in W$ dengan $u = (u_1,u_{2}, \cdots , u_n)$. Perhatikan bahwa
$$
\begin{align*}
1 \cdot u &= 1 \cdot (u_1,u_{2}, \cdots , u_n) \\
&= (1 \cdot u_1, 1 \cdot u_{2}, \cdots , 1 \cdot u_n) \\
&= (u_1, u_{2}, \cdots , u_n) \\
&= u
\end{align*}
$$

Karena memenuhi [[Ruang Vektor|Aksioma Ruang Vektor]] maka terbukti $W$ adalah ruang vektor atas lapangan $\mathbb{F}$.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Perkalian Kartesian]]