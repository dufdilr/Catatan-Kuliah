#Definisi #Teorema 

Misalkan $A$ adalah gelanggang dan $I_{1}, I_{2}$ keduanya adalah ideal dari $A$. Maka
$$
I = I_{1} I_{2} := \left\{  \sum_{k=1}^n x_k y_k \ | \ n \in \mathbb{N}, \  x_k \in I_{1}, y_{k} \in I_{2}  \right\}
$$
juga merupakan ideal bagi $A$.

---
## Bukti
Jelas $0 \in I_{1}, 0 \in I_{2}$. Karena $0 = 0 \cdot 0$, maka $0 \in I \neq \emptyset$.

Lebih lanjut, ambil $u, v \in I$ dan $r \in A$ dengan
$$
u = \sum_{j=1}^{n} x_{j}y_{j} \quad \text{dan} \quad v = \sum_{k=1}^{m} p_{k}q_{k}
$$
dimana $x_{j}, p_{k} \in I_{1}$ dan $y_{j}, q_{k} \in I_{2}$. Perhatikan bahwa
$$
u - v = \sum_{j=1}^{n} x_{j}y_{j} - \sum_{k=1}^{m} p_{k}q_{k} = \sum_{j=1}^{n} x_{j}y_{j} + \sum_{k=1}^{m} (-p_{k})q_{k}
$$
Karena $I_{1}$ adalah ideal, maka $-p_{k} \in I_{1}$. Akibatnya $u-v \in I$.
Lebih lanjut, perhatikan bahwa
$$
\begin{align*}
ru &= r \left( \sum_{j=1}^{n} x_{j}y_{j} \right) = \sum_{j=1}^{n} r(x_{j}y_{j}) = \sum_{j=1}^{n} (rx_{j})y_{j} \\
ur &= \left( \sum_{j=1}^{n} x_{j}y_{j} \right) r = \sum_{j=1}^{n} (x_{j}y_{j})r = \sum_{j=1}^{n} x_{j}(y_{j}r)
\end{align*}
$$
Karena $I_{1}$ ideal, maka untuk setiap $j$, $rx_{j} \in I_{1}$. Demikian pula karena $I_{2}$ ideal, maka untuk setiap $j$, $y_{j}r \in I_{2}$. Maka, $ur, ru \in I$

Berdasarkan [[Karakterisasi Ideal]] maka $I = I_{1}I_{2}$ membentuk ideal dari $A$.

***
## Definition Used 
 * [[Gelanggang]]
 * [[Ideal (Ring)]]