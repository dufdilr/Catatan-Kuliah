#Teorema 

Misalkan $\mathbf{A}, \mathbf{B} \in M_n(R)$ invertibel maka
1. **Ketunggalan Inverse Matriks** ^24898b
2. **Invers Perkalian Matriks** 
$$
(\mathbf{A}\mathbf{B})^{-1} = \mathbf{B}^{-1} \mathbf{A}^{-1}
$$
3. **Invers dari Invers**
$$
\left(\mathbf{A}^{-1}\right)^{-1} = \mathbf{A}
$$

---
## Bukti
### 1.
Misalkan $\mathbf{C}$ dan $\mathbf{D}$ adalah inverse dari matriks $\mathbf{A}$. Maka berdasarkan [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Sifat Operasi Matriks]]
$$
\mathbf{C} = \mathbf{C} \mathbf{I_n} = \mathbf{C} \mathbf{A} \mathbf{D} = \mathbf{I_n} \mathbf{D} = \mathbf{D}
$$
Terbukti ketunggalan inverse matriks.
### 2.
Perhatikan bahwa
$$
(\mathbf{A}\mathbf{B})(\mathbf{B}^{-1}\mathbf{A}^{-1}) = \mathbf{A} (\mathbf{B}\mathbf{B}^{-1}) \mathbf{A}^{-1} = \mathbf{A}\mathbf{I_n}\mathbf{A}^{-1} = \mathbf{A}\mathbf{A}^{-1} = \mathbf{I_n}
$$
Berdasarkan ketunggalan inverse, terbukti $(\mathbf{A}\mathbf{B})^{-1} = \mathbf{B}^{-1} \mathbf{A}^{-1}$.
### 3.
Perhatikan bahwa
$$
\mathbf{A}^{-1} \mathbf{A} = \mathbf{I_n}
$$
Berdasarkan ketunggalan inverse, terbukti $\left(\mathbf{A}^{-1}\right)^{-1} = \mathbf{A}$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Matriks]]
 * [[Buat Backup/Semester 3/Aljabar Linier Elementer/SPL dan Matriks/Operasi Matriks]]
 * [[Buat Backup/Semester 4 1/Aljabar Linear/Matriks dan Pemetaan Linear/Inverse Matriks]]