#Teorema 

Misalkan $T \in \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m)$. Maka terdapat matriks $\mathbf{A_T} \in M_{m \times n}(\mathbb{F})$ sehingga untuk setiap $v \in \mathbb{F}$ berlaku
$$
T(v) = \mathbf{A_T}\cdot v
$$

---
## Bukti
Tinjau $\mathbf{e}_{i} = \begin{pmatrix}0 \\ 0 \\ \cdots  \\ 1 \\ 0 \\ \cdots  \\ 0\end{pmatrix} \in \mathbb{F}^n$ adalah vektor di $\mathbb{F}^n$ dengan elemen $0$ di indeks selain $i$ dan 1 di indeks $i$. Misalkan pula $\mathbf{a}_{i} = T(\mathbf{e}_{i}) = \begin{pmatrix}a_{1, i} \\  a_{2, i} \\ a_{3, i}  \\ \cdots  \\ a_{m, i}\end{pmatrix} \in \mathbb{F}^m$. Bangun matriks $\mathbf{A_T}$ sebagai berikut
$$
\mathbf{A_T} = 
\begin{bmatrix}
\mathbf{a}_{1} & \mathbf{a}_{2} & \cdots & \mathbf{a}_{n} 
\end{bmatrix}
=
\begin{bmatrix}
a_{1, 1} & a_{1, 2} & \cdots & a_{1, n} \\ 
a_{2, 1} & a_{2, 2} & \cdots & a_{2, n}  \\
\dots & \dots & \dots & \dots \\
a_{m, 1} & a_{1, 2} & \cdots & a_{m, n}
\end{bmatrix}
$$
Ambil $v = \begin{pmatrix}v_{1}  \\ v_{2} \\ \cdots  \\ v_n\end{pmatrix} \in \mathbb{F}^n$. Perhatikan bahwa
$$
\begin{align*}
T(v) &= T(v_{1}\mathbf{e}_{1} + v_{2}\mathbf{e}_{2} + \cdots + v_n\mathbf{e}_{n}) = v_{1}T(\mathbf{e}_{1}) + v_{2}T(\mathbf{e}_{2}) + \cdots + v_nT(\mathbf{e}_{n}) \\
&= v_{1}\mathbf{a}_{1} +v_{2}\mathbf{a}_{2} + \cdots + v_n \mathbf{a}_{n} \\
&= 
\begin{bmatrix}
\mathbf{a}_{1} & \mathbf{a}_{2} & \dots & \mathbf{a}_{n}
\end{bmatrix}
\begin{pmatrix}
v_{1} \\
v_{2} \\
v_{3} \\
\cdots \\
v_n
\end{pmatrix} \\
&= \mathbf{A_T} \cdot v
\end{align*}
$$
Terbukti terdapat matriks $\mathbf{A_T} \in M_{m \times n}(\mathbb{F})$ sehingga untuk setiap $v \in \mathbb{F}$ berlaku $T(v) = \mathbf{A_T}\cdot v$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor Fn]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Pemetaan Linear]]
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]