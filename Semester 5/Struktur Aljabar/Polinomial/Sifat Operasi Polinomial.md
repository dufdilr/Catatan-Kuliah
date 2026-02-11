#Teorema 

Misalkan $R$ adalah gelanggang komutatif. Misalkan $f(x), g(x), h(x) \in R[x]$ dan $\alpha, \beta \in R$. Maka berlaku sifat-sifat aljabar berikut:

1. **Asosiatif Penjumlahan Polinomial**
   $$
   (f(x) + g(x)) + h(x) = f(x) + (g(x) + h(x))
   $$
2. **Komutatif Penjumlahan Polinomial**
   $$
   f(x) + g(x) = g(x) + f(x)
   $$
3. **Asosiatif Perkalian Polinomial**
   $$
   (f(x) \cdot g(x))\cdot h(x) = f(x) \cdot (g(x) \cdot h(x))
   $$
4. **Komutatif Perkalian Polinomial**
   $$
   f(x) \cdot g(x) = g(x) \cdot f(x)
   $$
5. **Distributif Perkalian Polinomial terhadap Penjumlahan**
   $$
   f(x) \cdot (g(x) + h(x)) = (f(x) \cdot g(x)) + (f(x) \cdot h(x))
   $$
6. **Asosiatif Perkalian Skalar**
   $$
   \alpha \cdot (\beta \cdot f(x)) = (\alpha \beta) \cdot f(x)
   $$
7. **Asosiatif Perkalian Skalar dan Polinomial**
   $$
   (\alpha \cdot f(x)) \cdot g(x) = \alpha \cdot (f(x) \cdot g(x)) = f(x) \cdot (\alpha \cdot g(x))
   $$
8. **Distributif Skalar terhadap Penjumlahan Polinomial**
   $$
   \alpha \cdot (f(x) + g(x)) = (\alpha \cdot f(x)) + (\alpha \cdot g(x))
   $$
9. **Distributif Penjumlahan Skalar terhadap Polinomial**
   $$
   (\alpha + \beta) \cdot f(x) = (\alpha \cdot f(x)) + (\beta \cdot f(x))
   $$
10. **Identitas Penjumlahan**
    $$
    f(x) + 0(x) = f(x)
    $$
11. **Invers Penjumlahan**
    $$
    f(x) + (-f(x)) = 0(x)
    $$
12. **Identitas Perkalian**
    $$
    f(x) \cdot 1(x) = f(x)
    $$

---
## Bukti

Misalkan polinomial didefinisikan sebagai deret pangkat formal (di mana $a_i, b_i, c_i = 0$ untuk $i$ yang cukup besar):
$$
f(x) = \sum_{i=0}^{\infty} a_{i}x^{i}, \quad g(x) = \sum_{i=0}^{\infty} b_{i}x^{i}, \quad h(x) = \sum_{i=0}^{\infty} c_{i}x^{i}
$$

### 1. Asosiatif Penjumlahan Polinomial
Tinjau koefisien ke-$k$ dari hasil penjumlahan:
$$
\begin{align*}
(f(x) + g(x)) + h(x) &= \sum_{k=0}^{\infty} [(a_{k} + b_{k}) + c_{k}] x^k \\
&= \sum_{k=0}^{\infty} [a_{k} + (b_{k} + c_{k})] x^k \quad (\text{sifat asosiatif ring } R) \\
&= f(x) + (g(x) + h(x))
\end{align*}
$$

### 2. Komutatif Penjumlahan Polinomial
$$
\begin{align*}
f(x) + g(x) &= \sum_{k=0}^{\infty} (a_{k} + b_{k}) x^k \\
&= \sum_{k=0}^{\infty} (b_{k} + a_{k}) x^k \quad (\text{sifat komutatif ring } R) \\
&= g(x) + f(x)
\end{align*}
$$

### 3. Asosiatif Perkalian Polinomial
Tinjau koefisien $x^n$ pada hasil perkalian.
Koefisien $x^n$ dari $(f(x)g(x))h(x)$ adalah:
$$
\begin{align*}
\sum_{k=0}^{n} \left( \sum_{j=0}^{k} a_j b_{k-j} \right) c_{n-k} &= \sum_{k=0}^{n} \sum_{j=0}^{k} a_j b_{k-j} c_{n-k} \\
&= \sum_{i+j+k=n} a_i b_j c_k
\end{align*}
$$
Bentuk $\sum_{i+j+k=n} a_i b_j c_k$ adalah simetris dan sama dengan koefisien $x^n$ dari $f(x)(g(x)h(x))$.
Maka $(f(x) \cdot g(x))\cdot h(x) = f(x) \cdot (g(x) \cdot h(x))$.

### 4. Komutatif Perkalian Polinomial
Tinjau koefisien $x^k$ dari $f(x)g(x)$:
$$
\begin{align*}
c_k &= \sum_{i=0}^{k} a_{i}b_{k-i} \\
\text{Misalkan } j = k-i &\Rightarrow i = k-j. \text{ Saat } i=0, j=k; \text{ saat } i=k, j=0. \\
c_k &= \sum_{j=0}^{k} a_{k-j}b_{j} \\
&= \sum_{j=0}^{k} b_{j}a_{k-j} \quad (\text{sifat komutatif ring } R) \\
&= \text{Koefisien } x^k \text{ dari } g(x)f(x)
\end{align*}
$$
Maka $f(x) \cdot g(x) = g(x) \cdot f(x)$.

### 5. Distributif Perkalian terhadap Penjumlahan
Tinjau koefisien $x^k$ dari $f(x) \cdot (g(x) + h(x))$:
$$
\begin{align*}
d_k &= \sum_{i=0}^{k} a_{i} (b_{k-i} + c_{k-i}) \\
&= \sum_{i=0}^{k} (a_{i}b_{k-i} + a_{i}c_{k-i}) \quad (\text{sifat distributif ring } R) \\
&= \sum_{i=0}^{k} a_{i}b_{k-i} + \sum_{i=0}^{k} a_{i}c_{k-i} \\
&= \text{Koef. } (f(x)g(x)) + \text{Koef. } (f(x)h(x))
\end{align*}
$$
Maka $f(x)(g(x)+h(x)) = f(x)g(x) + f(x)h(x)$.

### 6. Asosiatif Perkalian Skalar
$$
\begin{align*}
\alpha \cdot (\beta \cdot f(x)) &= \alpha \cdot \sum_{i=0}^{\infty} (\beta a_{i}) x^i \\
&= \sum_{i=0}^{\infty} \alpha (\beta a_{i}) x^i \\
&= \sum_{i=0}^{\infty} (\alpha \beta) a_{i} x^i \quad (\text{sifat asosiatif perkalian ring}) \\
&= (\alpha \beta) \cdot f(x)
\end{align*}
$$

### 7. Asosiatif Perkalian Skalar dan Polinomial
Tinjau koefisien $x^k$ dari $(\alpha \cdot f(x)) \cdot g(x)$:
$$
\begin{align*}
\sum_{i=0}^{k} (\alpha a_{i}) b_{k-i} &= \alpha \sum_{i=0}^{k} a_{i} b_{k-i} \quad (\text{distributif skalar}) \\
&= \text{Koefisien } x^k \text{ dari } \alpha \cdot (f(x)g(x))
\end{align*}
$$
Karena $R$ komutatif, $(\alpha a_i)b_{k-i} = a_i (\alpha b_{k-i})$, maka ini juga sama dengan koefisien $f(x) \cdot (\alpha \cdot g(x))$.

### 8. Distributif Skalar terhadap Penjumlahan Polinomial
$$
\begin{align*}
\alpha \cdot (f(x) + g(x)) &= \alpha \cdot \sum_{i=0}^{\infty} (a_{i} + b_{i}) x^i \\
&= \sum_{i=0}^{\infty} (\alpha a_{i} + \alpha b_{i}) x^i \quad (\text{distributif ring}) \\
&= \sum_{i=0}^{\infty} \alpha a_{i} x^i + \sum_{i=0}^{\infty} \alpha b_{i} x^i \\
&= (\alpha \cdot f(x)) + (\alpha \cdot g(x))
\end{align*}
$$

### 9. Distributif Penjumlahan Skalar terhadap Polinomial
$$
\begin{align*}
(\alpha + \beta) \cdot f(x) &= \sum_{i=0}^{\infty} (\alpha + \beta) a_{i} x^i \\
&= \sum_{i=0}^{\infty} (\alpha a_{i} + \beta a_{i}) x^i \\
&= (\alpha \cdot f(x)) + (\beta \cdot f(x))
\end{align*}
$$

### 10. Identitas Penjumlahan
Misalkan $0(x)$ adalah polinomial nol di mana semua koefisiennya adalah $0 \in R$.
$$
f(x) + 0(x) = \sum_{i=0}^{\infty} (a_{i} + 0) x^i = \sum_{i=0}^{\infty} a_{i} x^i = f(x)
$$

### 11. Invers Penjumlahan
Misalkan $-f(x) = \sum_{i=0}^{\infty} (-a_{i}) x^i$.
$$
f(x) + (-f(x)) = \sum_{i=0}^{\infty} (a_{i} + (-a_{i})) x^i = \sum_{i=0}^{\infty} 0 x^i = 0(x)
$$

### 12. Identitas Perkalian
Misalkan $1(x)$ adalah polinomial konstan dengan $c_0 = 1$ dan $c_i = 0$ untuk $i \ge 1$.
Koefisien $x^k$ dari $f(x) \cdot 1(x)$ adalah $\sum_{j=0}^{k} a_j c_{k-j}$.
Suku dalam penjumlahan ini bernilai $0$ kecuali saat $k-j=0$ (atau $j=k$), di mana $c_0=1$.
$$
\text{Koef } x^k = a_k c_0 = a_k \cdot 1 = a_k
$$
Maka $f(x) \cdot 1(x) = f(x)$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Operasi Polinomial]]