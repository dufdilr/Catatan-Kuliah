#Definisi 

Misalkan $\mathbf{A}, \mathbf{B} \in M_{m \times n}(R)$ dengan $R$ dilengkapi operasi $+$. Definisikan operasi **penjumlahan matriks**
$$
\begin{align*}
\mathbf{A} + \mathbf{B} &= 
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & \cdots  & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & \cdots  & a_{2, n} \\
& &\cdots \\
a_{m, 1} & a_{m, 2} & \cdots  & a_{m, n}
\end{bmatrix}
+
\begin{bmatrix}
b_{1, 1} & b_{1, 2} & \cdots  & b_{1, n} \\ 
b_{2, 1} & b_{2, 2} & \cdots  & b_{2, n} \\
& &\cdots \\
b_{m, 1} & b_{m, 2} & \cdots  & b_{m, n}
\end{bmatrix} \\
\\
&= 
\begin{bmatrix}
a_{1, 1} + b_{1, 1} & a_{1, 2} + b_{1, 2} & \cdots  & a_{1, n} + b_{1, n} \\ 
a_{2, 1} + b_{2, 1} & a_{2, 2} + b_{2, 2} & \cdots  & a_{2, n} + b_{2, n} \\
& &\cdots \\
a_{m, 1} + b_{m, 1} & a_{m, 2} + b_{m, 2} & \cdots  & a_{m, n} + b_{m, n}
\end{bmatrix}
\end{align*}
$$
misalkan $\mathbf{A} \in M_{m \times n}(R),\ \mathbf{B} \in M_{n \times k}(R)$ dan $\lambda \in R$ dengan $R$ dilengkapi operasi $+$ dan $\cdot$. Definisikan operasi **perkalian matriks** $\mathbf{A} \cdot \mathbf{B} = \mathbf{C} = [c]_{i,j}$ dengan $\mathbf{C} \in M_{m \times k}(R)$ dan
$$
c_{i, j} = a_{i,1}\cdot b_{1,j} + a_{i,2}\cdot b_{2, j} + \cdots + a_{i, n} \cdot b_{n, j} = \sum_{l = 1}^n a_{i, n} \cdot b_{n, j}
$$
Didefinisikan pula operasi **perkalian skalar** 
$$
\begin{align*}
\lambda \cdot\mathbf{A} &= \lambda \cdot
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & \cdots  & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & \cdots  & a_{2, n} \\
& &\cdots \\
a_{m, 1} & a_{m, 2} & \cdots  & a_{m, n}
\end{bmatrix}
=
\begin{bmatrix}
\lambda \cdot a_{1, 1} & \lambda \cdot a_{1, 2} & \cdots  & \lambda \cdot a_{1, n} \\ 
\lambda \cdot a_{2, 1} & \lambda \cdot a_{2, 2} & \cdots  & \lambda \cdot a_{2, n} \\
& &\cdots \\
\lambda \cdot a_{m, 1} & \lambda \cdot a_{m, 2} & \cdots  & \lambda \cdot a_{m, n}
\end{bmatrix}

\end{align*}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Operasi]]
 