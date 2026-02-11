#Teorema 
Misalkan $R$ adalah suatu gelanggang. $R$ adalah gelanggang komutatif jika dan hanya jika untuk setiap $a, b \in R$ berlaku
$$
a^2 - b^2 = (a+b)(a-b)
$$

---
## Bukti
### $\Rightarrow$
Misalkan $R$ adalah gelanggang komutatif. Ambil $a, b \in R$. Perhatikan bahwa $ab = ba$. Akibatnya
$$
\begin{align*}
a^2-b^2 &= a^2-b^2 + 0 = a^2-b^2+ab-ab \\
&= a^2-b^2+ba-ab = a^2 + ba - ab - b^2 \\
&=(a+b)a - (a+b)b \\
&= (a+b)(a-b)
\end{align*}
$$
Terbukti.

### $\Rightarrow$
Misalkan $R$ gelanggang yang memenuhi sifat, untuk setiap $a, b \in R$ berlaku $a^2-b^2 = (a+b)(a-b)$. Ambil $a, b \in R$. Perhatikan bahwa
$$
\begin{align*}
a^2-b^2&= (a+b)(a-b) = a^2 + ba - ab - b^2 \\
0 &= ba - ab \\
ab = ba
\end{align*}
$$
Terbukti $R$ adalah gelanggang komutatif.

***
## Definition Used 
 * [[Gelanggang Komutatif]]