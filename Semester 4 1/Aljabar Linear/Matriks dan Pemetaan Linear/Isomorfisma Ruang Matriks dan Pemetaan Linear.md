#Teorema 
Misalkan $C : \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m) \to M_{m \times n}(\mathbb{F})$ yang memetakan pemetaan linear ke [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn|Matriks Representasi]]. Fungsi $C$ adalah fungsi **Isomorfisma** Ruang Vektor.

---
## Bukti

### Pemetaan Linear

Misalkan $S, T \in \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m)$, maka [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks dari Pemetaan Linear Fn|Matriks Representasi]] dari $T$ dapat dituliskan sebagai
$$
\begin{align*}
\mathbf{A_S} &= 
\begin{bmatrix}
S(\mathbf{e}_{1}) & S(\mathbf{e}_2)  & \dots & S(\mathbf{e}_{n})
\end{bmatrix}\\
\\
\mathbf{A_T} &= 
\begin{bmatrix}
T(\mathbf{e}_{1}) & T(\mathbf{e}_2)  & \dots & T(\mathbf{e}_{n})
\end{bmatrix}
\end{align*}
$$
dengan $\mathbf{e}_{i}$ adalah vektor di $\mathbb{F}^n$ dengan elemen di baris ke-$i$ bernilai 1 dan elemen di baris lain bernilai 0. Perhatikan pula bahwa
$$
\begin{align*}
C(S+T) = \mathbf{A_{S+T}} &= 
\begin{bmatrix}
(S+T)(\mathbf{e}_{1}) & (S+T)(\mathbf{e}_2)  & \dots & (S+T)(\mathbf{e}_{n})
\end{bmatrix} \\
\\
&= \begin{bmatrix}
S(\mathbf{e}_{1}) + T(\mathbf{e}_{2}) & S(\mathbf{e}_2) + T(\mathbf{e}_2)  & \dots & S(\mathbf{e}_{n}) + T(\mathbf{e}_n) 
\end{bmatrix}\\
\\
&= \begin{bmatrix}
S(\mathbf{e}_{1}) & S(\mathbf{e}_2)  & \dots & S(\mathbf{e}_{n})
\end{bmatrix}
+
\begin{bmatrix}
T(\mathbf{e}_{1}) & T(\mathbf{e}_2)  & \dots & T(\mathbf{e}_{n})
\end{bmatrix} \\
\\
&= C(S) + C(T) \\
\\
\\
C(\alpha T) = \mathbf{A_{\alpha T}} &= 
\begin{bmatrix}
(\alpha T)(\mathbf{e}_{1}) & (\alpha T)(\mathbf{e}_2)  & \dots & (\alpha T)(\mathbf{e}_{n})
\end{bmatrix} \\
\\
&= \begin{bmatrix}
\alpha T(\mathbf{e}_{1}) & \alpha T(\mathbf{e}_2)  & \dots & \alpha T(\mathbf{e}_{n})
\end{bmatrix} \\
\\ &= \alpha
\begin{bmatrix}
T(\mathbf{e}_{1}) & T(\mathbf{e}_2)  & \dots & T(\mathbf{e}_{n})
\end{bmatrix} \\
\\ &= \alpha C(T)
\end{align*}
$$
Maka $C$ adalah pemetaan linear.

### Invertibel
Ambil $\mathbf{A} \in M_{m \times n}(\mathbb{F})$. Jelas berdasarkan [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Matriks Sebagai Pemetaan Linear]], dapat dibentuk pemetaan linear $A \in \mathcal{L}(\mathbb{F}^n , \mathbb{F}^m)$ sehingga
$$
\mathbf{A}v = A(v)
$$
untuk setiap $v \in A$. Artinya didapatkan invers dari $C$ yakni memetakan dari Matriks ke Pemetaan Linear yang dibangun dari Matriks tersebut. 

Karena $C$ invertibel maka $C$ bijektif. Karena $C$ Pemetaan Linear yang Bijektif maka $C$ adalah **Isomorfisma Ruang Vektor**. Akibatnya
$$
\mathcal{L}(\mathbb{F}^n, \mathbb{F}^m) \cong M_{m \times n}(\mathbb{F})
$$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Ruang Vektor Matriks]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Ruang Vektor Pemetaan Linear]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Isomorfisma (Ruang Vektor)]]