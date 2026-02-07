#Teorema 

Misalkan $U, V, W, X$ ruang vektor atas lapangan $\mathbb{F}$. Misalkan pula $P, Q, R \in \mathcal{L}(U, V)$; $\ S, T \in \mathcal{L}(V, W)$; $N \in \mathcal{L}(W, X)$ dan $\alpha, \beta \in \mathbb{F}$. Lebih lanjut, [[Pemetaan Nol, Identitas dan Negatif Pemetaan Linear|didefinisikan]] pula pemetaan nol dan negatif dari pemetaan. Maka berlaku:

1. **Asosiatif Penjumlahan**
$$
(P+Q)+R = P + (Q+R)
$$
2. **Komutatif Penjumlahan**
$$
P+Q = Q+P
$$
3. **Asosiatif Komposisi**
   *(Note: Urutan $P \to S \to N$ ditulis sebagai $NSP$)*
$$
(NS)P = N(SP)
$$
4. **Asosiatif Perkalian Skalar**
$$
\alpha(\beta P) = (\alpha \beta)P
$$
5. **Asosiatif Perkalian Skalar dan Komposisi**
$$
(\alpha S)P = S (\alpha P) = \alpha (SP)
$$
6. **Distributif Penjumlahan dan Komposisi Kiri**

$$
S(P+Q) = SP + SQ
$$
7. **Distributif Penjumlahan dan Komposisi Kanan**

$$
(S+T)P = SP + TP
$$
8. **Distribusi Penjumlahan Skalar**
$$
(\alpha+\beta)P = \alpha P + \beta P
$$
9. **Identitas Penjumlahan**
$$
P + \mathbf{0_{UV}} = P
$$
10. **Inverse Penjumlahan**
$$
P + (-P) = \mathbf{0_{UV}}
$$
11. **Identitas Komposisi Kanan**
$$
P I_U = P
$$
12. **Identitas Komposisi Kiri**
$$
I_VP = P
$$

---
## Bukti
Kita akan menggunakan [[Sifat Ruang Vektor]] dan [[Pemetaan Nol, Identitas dan Negatif Pemetaan Linear]].
*Catatan: Notasi komposisi $ST$ didefinisikan sebagai $(ST)(x) = S(T(x))$.*

### 1. Asosiatif Penjumlahan
Ambil $u \in U$. Perhatikan bahwa:
$$
\begin{align*}
\left( (P+Q)+R \right) (u) &= (P+Q)(u) + R(u) \\
&= \left( P(u) +  Q(u)\right)  + R(u) \\
&= P(u) + \left(  Q(u) + R(u)\right)  \quad (\text{sifat asosiatif vektor di } V) \\
&= P(u) + (Q+R)(u) \\
&= \left( P + (Q+R) \right) (u)
\end{align*}
$$
Maka $(P+Q)+R = P+(Q+R)$.

### 2. Komutatif Penjumlahan
Ambil $u \in U$. Perhatikan bahwa:
$$
\begin{align*}
(P+Q)(u) &= P(u) + Q(u) \\
&= Q(u) + P(u) \quad (\text{sifat komutatif vektor di } V) \\
&= (Q+P)(u)
\end{align*}
$$
Maka $P+Q = Q+P$.

### 3. Asosiatif Komposisi
Ambil $u \in U$. Kita tinjau jalur pemetaan $U \xrightarrow{P} V \xrightarrow{S} W \xrightarrow{N} X$.
$$
\begin{align*}
\left((NS)P\right)(u) &= (NS)(P(u)) \\
&= N\left( S(P(u)) \right) \\
&= N\left( (SP)(u) \right) \\
&= \left( N(SP) \right)(u)
\end{align*}
$$
Maka $(NS)P = N(SP)$.

### 4. Asosiatif Perkalian Skalar
Ambil $u \in U$. Perhatikan bahwa:
$$
\begin{align*}
\left( \alpha(\beta P) \right)(u) &= \alpha \left( (\beta P)(u) \right) \\
&= \alpha \left( \beta P(u) \right) \\
&= (\alpha \beta) P(u) \quad (\text{sifat asosiatif skalar pada vektor}) \\
&= \left( (\alpha \beta)P \right)(u)
\end{align*}
$$
Maka $\alpha(\beta P) = (\alpha \beta)P$.

### 5. Asosiatif Perkalian Skalar dan Komposisi
Ambil $u \in U$. Kita akan membuktikan kesamaan ketiga bentuk tersebut dengan mengingat $S$ adalah linear ($S(\alpha v) = \alpha S(v)$).
$$
\begin{align*}
\left( (\alpha S)P \right)(u) &= (\alpha S)(P(u)) = \alpha \left( S(P(u)) \right) \\
\left( S(\alpha P) \right)(u) &= S \left( (\alpha P)(u) \right) = S \left( \alpha P(u) \right) = \alpha S(P(u)) \quad (\text{linearitas } S) \\
\left( \alpha (SP) \right)(u) &= \alpha \left( (SP)(u) \right) = \alpha \left( S(P(u)) \right)
\end{align*}
$$
Karena ketiga bentuk menghasilkan nilai yang sama untuk setiap $u$, maka $(\alpha S)P = S (\alpha P) = \alpha (SP)$.

### 6. Distributif Penjumlahan dan Komposisi Kiri
Ambil $u \in U$. Perhatikan bahwa $S$ adalah pemetaan linear, sehingga $S(v_1 + v_2) = S(v_1) + S(v_2)$.
$$
\begin{align*}
\left( S(P+Q) \right)(u) &= S\left( (P+Q)(u) \right) \\
&= S\left( P(u) + Q(u) \right) \\
&= S(P(u)) + S(Q(u)) \quad (\text{linearitas } S) \\
&= (SP)(u) + (SQ)(u) \\
&= (SP + SQ)(u)
\end{align*}
$$
Maka $S(P+Q) = SP + SQ$.

### 7. Distributif Penjumlahan dan Komposisi Kanan
Ambil $u \in U$. Perhatikan definisi penjumlahan fungsi.
$$
\begin{align*}
\left( (S+T)P \right)(u) &= (S+T)\left( P(u) \right) \\
&= S(P(u)) + T(P(u)) \quad (\text{definisi penjumlahan fungsi}) \\
&= (SP)(u) + (TP)(u) \\
&= (SP + TP)(u)
\end{align*}
$$
Maka $(S+T)P = SP + TP$.

### 8. Distribusi Penjumlahan Skalar
Ambil $u \in U$. Perhatikan bahwa:
$$
\begin{align*}
\left( (\alpha+\beta)P \right)(u) &= (\alpha+\beta) P(u) \\
&= \alpha P(u) + \beta P(u) \quad (\text{sifat distributif skalar pada vektor}) \\
&= (\alpha P)(u) + (\beta P)(u) \\
&= (\alpha P + \beta P)(u)
\end{align*}
$$
Maka $(\alpha+\beta)P = \alpha P + \beta P$.

### 9. Identitas Penjumlahan
Ambil $u \in U$.
$$
\begin{align*}
(P + \mathbf{0_{UV}})(u) &= P(u) + \mathbf{0_{UV}}(u) \\
&= P(u) + \mathbf{0}_V \quad (\text{pemetaan nol memetakan ke vektor nol}) \\
&= P(u)
\end{align*}
$$
Maka $P + \mathbf{0_{UV}} = P$.

### 10. Inverse Penjumlahan
Ambil $u \in U$.
$$
\begin{align*}
(P + (-P)) (u) &= P(u) + (-P)(u) \\
&= P(u) - P(u) \quad (\text{definisi negatif pemetaan}) \\
&= \mathbf{0}_V \\
&= \mathbf{0_{UV}}(u)
\end{align*}
$$
Maka $P + (-P) = \mathbf{0_{UV}}$.

### 11. Identitas Komposisi Kanan
Ambil $u \in U$.
$$
PI_U(u) = P(I_U(u)) = P(u)
$$
Maka $PI_U = P$

### 12. Identitas Komposisi Kiri
Ambil $u \in U$
$$
I_VP(u) = I_V(P(u)) = P(u)
$$
Maka $I_VP = P$.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Pemetaan Linear]]
 * [[Operasi pada Pemetaan Linear]]
 * [[Pemetaan Nol, Identitas dan Negatif Pemetaan Linear]]