#Teorema 

Misalkan suatu lapangan $\mathbb{F}$ dan $\mathbf{A} \in M_{m \times n}(\mathbb{F})$. $\mathrm{Im}(\mathbf{A})$ adalah himpunan **Kombinasi Linear** dari vektor kolom $\mathbf{A}$.

---
## Bukti
Misalkan $C$ adalah himpunan kombinasi linear dari vektor kolom $\mathbf{A}$. Misalkan pula
$$
\mathbf{A} = 
\begin{bmatrix}
\mathbf{a}_{1} & \mathbf{a}_{2} & \dots & \mathbf{a}_{n}
\end{bmatrix}
$$
dengan $\mathbf{a}_{1}, \mathbf{a}_{2}, \dots, \mathbf{a}_{n}$ adalah vektor kolom dari $\mathbf{A}$. Akan ditunjukkan $C = \mathrm{Im}(A)$.
### $\subseteq$
Ambil $w \in C$. Artinya
$$
w = c_{1}\mathbf{a}_{1}+c_{2}\mathbf{a}_{2}+ \cdots + c_n \mathbf{a}_{n}
$$
untuk suatu $c_1, c_2, \cdots, c_n \in \mathbb{F}$. Misalkan vektor $\mathbf{c} \in \mathbb{F}^n$ dengan $\mathbf{c} = \begin{pmatrix}c_{1} \\ c_{2} \\ \vdots \\ c_n\end{pmatrix}$. Perhatikan bahwa
$$
\mathbf{A}\mathbf{c} = 
\begin{bmatrix}
\mathbf{a}_{1} & \mathbf{a}_{2} & \dots & \mathbf{a}_{n}
\end{bmatrix}
\begin{pmatrix}c_{1} \\ c_{2} \\ \vdots \\ c_n\end{pmatrix} = c_{1}\mathbf{a}_{1}+c_{2}\mathbf{a}_{2}+ \cdots + c_n \mathbf{a}_{n}
= w
$$
maka, $w \in \mathrm{Im}(A)$. Terbukti $C \subseteq \mathrm{Im}(A)$.

### $\supseteq$
Ambil $w \in \mathrm{Im}(\mathbf{A})$. Artinya terdapat $\mathbf{v} \in \mathbb{F}^n$ sehingga $\mathbf{A}\mathbf{v} = w$. Tulis $\mathbf{v} = \begin{pmatrix}v_{1} \\ v_{2} \\ \vdots \\ v_n\end{pmatrix}$. Perhatikan bahwa
$$
w = \mathbf{A}\mathbf{v} = 
\begin{bmatrix}
\mathbf{a}_{1} & \mathbf{a}_{2} & \dots & \mathbf{a}_{n}
\end{bmatrix}
\begin{pmatrix}v_{1} \\ v_{2} \\ \vdots \\ v_n\end{pmatrix}  = v_{1}\mathbf{a}_{1}+v_{2}\mathbf{a}_{2}+\dots+v_n\mathbf{a}_{n}
$$
maka, $w \in C$. Terbukti $C \supseteq \mathrm{Im}(A)$.


Karena $C \subseteq \mathrm{Im}(A)$ dan $C \supseteq \mathrm{Im}(A)$ maka $C = \mathrm{Im}(A)$


***
## Definition Used 
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Ruang Vektor Matriks]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Kombinasi Linear dan Span]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Matriks dan Pemetaan Linear/Range dan Kernel Pemetaan Linear]]
