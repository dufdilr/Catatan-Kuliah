#Teorema 

Misalkan $\mathbf{A} \in M_{m \times n}(R)$ dan $\mathbf{B} \in M_{n \times k}(R)$ dimana $R$ adalah gelanggang komutatif. Berlaku:
1. $\left(\mathbf{A}^T\right)^T = \mathbf{A}$
2. $\left( \mathbf{AB} \right)^T = \mathbf{B}^T \mathbf{A}^T$

---
## Bukti
### 1.
Misalkan $\mathbf{C} = \mathbf{A}^T$. Maka $c_{i,j} = a_{j, i}$. Lebih lanjut
$$
\left[\left(\mathbf{A}^T\right)^T\right]_{{i, j}} = [c_{j, i}] = [a_{i, j}] = \mathbf{A}
$$

### 2.
Misalkan matriks hasil $\mathbf{C} = (\mathbf{AB})^T$. Matriks ini akan berukuran $k \times m$.
Tinjau elemen ke-$(i, j)$ dari matriks $\mathbf{C}$, dimana $1 \le i \le k$ dan $1 \le j \le m$.

$$
\begin{align*}
\left[ (\mathbf{AB})^T \right]_{i,j} &= [\mathbf{AB}]_{j,i} && (\text{definisi transpose}) \\
&= \sum_{p=1}^{n} a_{j,p} b_{p,i} && (\text{definisi perkalian matriks}) \\
&= \sum_{p=1}^{n} b_{p,i} a_{j,p} && (\text{sifat komutatif perkalian elemen } R) \\
&= \sum_{p=1}^{n} [\mathbf{B}^T]_{i,p} [\mathbf{A}^T]_{p,j} && (\text{definisi elemen transpose}) \\
&= [\mathbf{B}^T \mathbf{A}^T]_{i,j} && (\text{definisi perkalian matriks})
\end{align*}
$$
Karena berlaku untuk setiap entri $(i, j)$, maka terbukti $(\mathbf{AB})^T = \mathbf{B}^T \mathbf{A}^T$.

***
## Definition Used
 * [[Matriks]]
 * [[Matriks Transpose]]
 * [[Gelanggang Komutatif]]
 * [[Operasi Matriks]]
