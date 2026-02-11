#Teorema 

Misalkan $\mathbf{A}, \mathbf{B}, \mathbf{C} \in M_{m \times n}(R); \ \ \mathbf{D}, \mathbf{E} \in M_{n \times k}(R); \ \ \mathbf{F} \in M_{k \times l}$  dan $\alpha, \beta \in R$ dengan $R$ suatu **gelanggang komutatif**. Maka berlaku:

1. **Asosiatif Penjumlahan Matriks**
   $$
   (\mathbf{A} + \mathbf{B}) + \mathbf{C} = \mathbf{A} + (\mathbf{B}+\mathbf{C}) 
   $$
2. **Komutatif Penjumlahan Matriks**
   $$
   \mathbf{A} + \mathbf{B} = \mathbf{B} + \mathbf{A}
   $$
3. **Asosiatif Perkalian Matriks**
   $$
   (\mathbf{A} \cdot \mathbf{D})\cdot \mathbf{F} = \mathbf{A} \cdot (\mathbf{D}\cdot \mathbf{ F})
   $$
4.  **Asosiatif Perkalian Skalar**
   $$
   \alpha \cdot(\beta\cdot \mathbf{A}) = (\alpha \cdot \beta) \cdot \mathbf{A}
   $$
5.  **Asosiatif Perkalian Skalar dan Matriks**
   $$
   (\alpha \cdot \mathbf{A}) \cdot \mathbf{D} = \alpha \cdot (\mathbf{A} \cdot \mathbf{D}) = \mathbf{A} \cdot (\alpha \cdot \mathbf{D})
   $$
6. **Distributif Penjumlahan terhadap Perkalian Matriks Kiri**
   $$
   \mathbf{A} \cdot (\mathbf{D} + \mathbf{E}) = (\mathbf{A} \cdot \mathbf{D}) + (\mathbf{A} \cdot \mathbf{E})
   $$
7. **Distributif Penjumlahan terhadap Perkalian Matriks Kanan**
   $$
   (\mathbf{A}+\mathbf{B})\cdot \mathbf{D} = (\mathbf{A} \cdot \mathbf{D}) + (\mathbf{B}\cdot \mathbf{D})
   $$
8. **Distributif Penjumlahan Skalar terhadap Perkalian Skalar**
   $$
   (\alpha+\beta)\cdot \mathbf{A} = (\alpha \cdot \mathbf{A}) + (\beta \cdot \mathbf{A})
   $$
9. **Identitas Penjumlahan**
   $$
   \mathbf{A} + \mathbf{O}_{m, n} = \mathbf{A}
   $$
10. **Inverse Penjumlahan**
    $$
    \mathbf{A} + (\mathbf{-A}) = \mathbf{O}_{m,n}
    $$
11. **Identitas Perkalian Kiri**
    $$
    \mathbf{A}\mathbf{I_n} = \mathbf{A}
    $$
12. **Identitas Perkalian Kanan**
    $$
    \mathbf{I_m} \mathbf{A} = \mathbf{A}
    $$

## Bukti
Pandang $\mathbf{A} = [a]_{m, n},\ \mathbf{B} = [b]_{m,n},\ \mathbf{C} = [c]_{m,n},\ \mathbf{D} = [d]_{n,k},\ \mathbf{E} = [e]_{n,k}$ dan $\mathbf{F} = [f]_{k, l}$.

### 1. Asosiatif Penjumlahan Matriks
Berdasarkan sifat asosiatif penjumlahan pada elemen gelanggang:
$$
\begin{align*}
(\mathbf{A} + \mathbf{B}) + \mathbf{C} &= [(a_{i, j} + b_{i, j}) + c_{i, j}] \\
&= [a_{i, j} + (b_{i, j} + c_{i, j})] \\
&= \mathbf{A} + (\mathbf{B}+\mathbf{C}) 
\end{align*}
$$

### 2. Komutatif Penjumlahan Matriks
Berdasarkan sifat komutatif pada penjumlahan gelanggang maka:
$$
\begin{align*}
\mathbf{A} + \mathbf{B} &= [a_{i,j} + b_{i,j}] \\
&= [b_{i,j}+a_{i,j}] \quad (\text{sifat komutatif ring}) \\
&= \mathbf{B} + \mathbf{A}
\end{align*}
$$

### 3. Asosiatif Perkalian Matriks
Tinjau elemen ke-$(i, q)$ dari hasil perkalian, dimana $1 \le i \le m$, $1 \le j \le n$, $1 \le p \le k$, dan $1 \le q \le l$.
$$
\begin{align*}
[(\mathbf{A} \cdot \mathbf{D}) \cdot \mathbf{F}]_{i,q} &= \sum_{p=1}^{k} \left( \sum_{j=1}^{n} a_{i,j} d_{j,p} \right) f_{p,q} \\
&= \sum_{p=1}^{k} \sum_{j=1}^{n} (a_{i,j} d_{j,p}) f_{p,q} \\
&= \sum_{j=1}^{n} a_{i,j} \left( \sum_{p=1}^{k} d_{j,p} f_{p,q} \right) \quad (\text{menukar urutan penjumlahan}) \\
&= [\mathbf{A} \cdot (\mathbf{D} \cdot \mathbf{F})]_{i,q}
\end{align*}
$$
Sehingga $(\mathbf{A} \cdot \mathbf{D})\cdot \mathbf{F} = \mathbf{A} \cdot (\mathbf{D}\cdot \mathbf{ F})$.

### 4. Asosiatif Perkalian Skalar
$$
\begin{align*}
\alpha \cdot (\beta \cdot \mathbf{A}) &= \alpha \cdot [\beta a_{i,j}] \\
&= [\alpha (\beta a_{i,j})] \\
&= [(\alpha \beta) a_{i,j}] \quad (\text{sifat asosiatif perkalian skalar}) \\
&= (\alpha \beta) \cdot \mathbf{A}
\end{align*}
$$

### 5. Asosiatif Perkalian Skalar dan Matriks
Tinjau elemen ke-$(i, p)$ dimana $1 \le j \le n$:
$$
\begin{align*}
[(\alpha \cdot \mathbf{A}) \cdot \mathbf{D}]_{i,p} &= \sum_{j=1}^{n} (\alpha a_{i,j}) d_{j,p} \\
&= \alpha \sum_{j=1}^{n} a_{i,j} d_{j,p} = \alpha \cdot [\mathbf{A} \cdot \mathbf{D}]_{i,p} \\
&= \sum_{j=1}^{n} a_{i,j} (\alpha d_{j,p}) \quad (\text{karena } R \text{ komutatif, } \alpha a_{i,j} = a_{i,j} \alpha) \\
&= [\mathbf{A} \cdot (\alpha \cdot \mathbf{D})]_{i,p}
\end{align*}
$$
Sehingga $(\alpha \cdot \mathbf{A}) \cdot \mathbf{D} = \alpha \cdot (\mathbf{A} \cdot \mathbf{D}) = \mathbf{A} \cdot (\alpha \cdot \mathbf{D})$.

### 6. Distributif Penjumlahan terhadap Perkalian Matriks Kiri
Tinjau elemen ke-$(i, p)$ dimana $1 \le j \le n$:
$$
\begin{align*}
[\mathbf{A} \cdot (\mathbf{D} + \mathbf{E})]_{i,p} &= \sum_{j=1}^{n} a_{i,j} (d_{j,p} + e_{j,p}) \\
&= \sum_{j=1}^{n} (a_{i,j} d_{j,p} + a_{i,j} e_{j,p}) \quad (\text{sifat distributif skalar}) \\
&= \sum_{j=1}^{n} a_{i,j} d_{j,p} + \sum_{j=1}^{n} a_{i,j} e_{j,p} \\
&= [\mathbf{A} \cdot \mathbf{D}]_{i,p} + [\mathbf{A} \cdot \mathbf{E}]_{i,p}
\end{align*}
$$
Sehingga $\mathbf{A} \cdot (\mathbf{D} + \mathbf{E}) = (\mathbf{A} \cdot \mathbf{D}) + (\mathbf{A} \cdot \mathbf{E})$.

### 7. Distributif Penjumlahan terhadap Perkalian Matriks Kanan
Tinjau elemen ke-$(i, p)$ dimana $1 \le j \le n$:
$$
\begin{align*}
[(\mathbf{A} + \mathbf{B}) \cdot \mathbf{D}]_{i,p} &= \sum_{j=1}^{n} (a_{i,j} + b_{i,j}) d_{j,p} \\
&= \sum_{j=1}^{n} (a_{i,j} d_{j,p} + b_{i,j} d_{j,p}) \\
&= \sum_{j=1}^{n} a_{i,j} d_{j,p} + \sum_{j=1}^{n} b_{i,j} d_{j,p} \\
&= [\mathbf{A} \cdot \mathbf{D}]_{i,p} + [\mathbf{B} \cdot \mathbf{D}]_{i,p}
\end{align*}
$$
Sehingga $(\mathbf{A}+\mathbf{B})\cdot \mathbf{D} = (\mathbf{A} \cdot \mathbf{D}) + (\mathbf{B}\cdot \mathbf{D})$.

### 8. Distributif Penjumlahan Skalar terhadap Perkalian Skalar
$$
\begin{align*}
(\alpha + \beta) \cdot \mathbf{A} &= [(\alpha + \beta) a_{i,j}] \\
&= [\alpha a_{i,j} + \beta a_{i,j}] \quad (\text{sifat distributif skalar}) \\
&= [\alpha a_{i,j}] + [\beta a_{i,j}] \\
&= (\alpha \cdot \mathbf{A}) + (\beta \cdot \mathbf{A})
\end{align*}
$$

### 9. Identitas Penjumlahan
$$
\begin{align*}
\mathbf{A} + \mathbf{O}_{m, n} &= [a_{i,j} + 0] = [a_{i,j}] \\
&= \mathbf{A}
\end{align*}
$$

### 10. Inverse Penjumlahan
$$
\begin{align*}
\mathbf{A} + (\mathbf{-A}) 
&= [a_{i,j} + (-a_{i,j})] \\
&= [0] \\
&= \mathbf{O}_{m, n}
\end{align*}
$$

### 11. Identitas Perkalian Kiri
Misalkan $\mathbf{I}_n = [\delta_{j,k}]$ dimana $\delta_{j,k}$ . Tinjau elemen ke-$(i, k)$ dari $\mathbf{A}\mathbf{I}_n$:
$$
\begin{align*}
[\mathbf{A}\mathbf{I}_n]_{i,k} &= \sum_{j=1}^{n} a_{i,j} \delta_{j,k} \\
&= a_{i,k} \cdot 1 \quad (\text{karena semua suku lain bernilai } 0) \\
&= [\mathbf{A}]_{i,k}
\end{align*}
$$
Sehingga $\mathbf{A}\mathbf{I}_n = \mathbf{A}$.

### 12. Identitas Perkalian Kanan
Misalkan $\mathbf{I}_m = [\delta_{k,i}]$ dimana $\delta_{k,i}$ . Tinjau elemen ke-$(k, j)$ dari $\mathbf{I}_m\mathbf{A}$:
$$
\begin{align*}
[\mathbf{I}_m \mathbf{A}]_{k,j} &= \sum_{i=1}^{m} \delta_{k,i} a_{i,j} \\
&= 1 \cdot a_{k,j} \quad (\text{karena semua suku lain bernilai } 0) \\
&= [\mathbf{A}]_{k,j}
\end{align*}
$$
Sehingga $\mathbf{I}_m \mathbf{A} = \mathbf{A}$.

***
## Definition Used 
 * [[Buat Backup/Semester 3 1/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
 * [[Buat Backup/Semester 3 1/Aljabar Linier Elementer/SPL dan Matriks/Operasi Matriks]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]