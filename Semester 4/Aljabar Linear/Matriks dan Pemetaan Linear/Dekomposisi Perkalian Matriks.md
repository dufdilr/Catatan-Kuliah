#Teorema

Misalkan $\mathbf{A} \in M_{m \times n}(R)$ dan $\mathbf{B} \in M_{n \times k}(R)$ dengan
$$
\mathbf{B} = 
\begin{bmatrix}
\mathbf{b}_{1} & \mathbf{b}_{2} & \dots & \mathbf{b}_{k}
\end{bmatrix}
$$
dimana $\mathbf{b}_{j}$ adalah vektor kolom ke-$j$ dari matriks $\mathbf{B}$. Berlaku:
$$
\mathbf{AB} =
\begin{bmatrix}
\mathbf{Ab}_{1} & \mathbf{Ab}_{2} & \dots & \mathbf{Ab}_{k}
\end{bmatrix}
$$

---
## Bukti
Tinjau kolom ke-$j$ dari matriks $\mathbf{AB}$ (dinotasikan sebagai $(\mathbf{AB})_{\cdot, j}$). Berdasarkan definisi perkalian matriks:
$$
\begin{align*}
(\mathbf{AB})_{\cdot, j} = \begin{bmatrix} \sum_{p=1}^n a_{1,p} b_{p,j} \\ \vdots \\ \sum_{p=1}^n a_{m,p} b_{p,j} \end{bmatrix} = \mathbf{A} \begin{bmatrix} b_{1,j} \\ \vdots \\ b_{n,j} \end{bmatrix} = \mathbf{A}\mathbf{b}_j
\end{align*}
$$
Karena hal ini berlaku untuk setiap $j = 1, \dots, k$, maka terbukti $\mathbf{AB} = [\mathbf{Ab}_{1} \dots \mathbf{Ab}_{k}]$.

***
## Definition Used 
 * [[Matriks]]
 * [[Operasi Matriks]]