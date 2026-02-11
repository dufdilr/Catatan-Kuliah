#Teorema 

Misalkan $S \in \mathcal{L} (\mathbb{F}^n, \mathbb{F}^m)$ dan $T \in \mathcal{L}(\mathbb{F}^m, \mathbb{F}^k)$ maka
$$
\mathbf{A_TS} = \mathbf{A_T} \cdot \mathbf{A_S}
$$

---
## Bukti
Perhatikan bahwa berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Dekomposisi Perkalian Matriks]] dan [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn]] maka
$$
\begin{align*}
\mathbf{A_TS} &= 
\begin{bmatrix}
TS(\mathbf{e}_{1}) & TS(\mathbf{e}_{2}) & \dots & TS(\mathbf{e}_{n})
\end{bmatrix} \\
\\ &= 
\begin{bmatrix}
T(S(\mathbf{e}_{1})) & T(S(\mathbf{e}_{2})) & \dots & T(S(\mathbf{e}_{n})) 
\end{bmatrix} \\
\\&= 
\begin{bmatrix}
\mathbf{A_T}\cdot S(\mathbf{e}_{1}) & \mathbf{A_T}\cdot S(\mathbf{e}_{2}) & \dots & \mathbf{A_T}\cdot S(\mathbf{e}_{n})
\end{bmatrix} \\
\\&= \mathbf{A_T} \cdot
\begin{bmatrix}
S(\mathbf{e}_{1}) & S(\mathbf{e}_{2}) & \dots & S(\mathbf{e}_{n})
\end{bmatrix} \\
\\ &= \mathbf{A_T} \cdot \mathbf{A_S}
\end{align*}
$$
Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Komposisi Pemetaan Linear]]
