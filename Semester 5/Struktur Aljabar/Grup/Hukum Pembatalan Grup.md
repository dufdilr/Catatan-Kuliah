#Teorema 

Misalkan $(G, *)$ membentuk suatu grup. Misalkan $a, b, c \in G$. Berlaku
1. **Pembatalan Kiri**: Jika $ab = ac$ maka $b = c$
2. **Pembatalan Kanan**: Jika $ba = ca$ maka $b = c$

---
## Bukti
Misalkan $e$ adalah unsur identitas di $G$
### 1.
Misalkan $ab = ac$ maka
$$
\begin{align*}
a^{-1}ab &= a^{-1}ac && \text{kalikan kiri dengan } a^{-1} \\
eb &= ec &&\text{Invers } a \\
b &= c && \text{Identitas } e
\end{align*}
$$
Terbukti $b = c$
### 2.
Misalkan $ba = ca$ maka
$$
\begin{align*}
baa^{-1} &= caa^{-1} && \text{kalikan kanan dengan } a^{-1} \\
be &= ce &&\text{Invers } a \\
b &= c && \text{Identitas } e
\end{align*}
$$
Terbukti $b = c$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]