#Teorema

Misalkan $z_1 = a+bi, z_2 = c+di, z_3 = p+qi \in \mathbb{Z}[i]$ dan $\alpha, \beta \in \mathbb{Z}$. Maka berlaku:

1. **Asosiatif Penjumlahan**
   $$
   (z_1 + z_2) + z_3 = z_1 + (z_2 + z_3)
   $$
2. **Komutatif Penjumlahan**
   $$
   z_1 + z_2 = z_2 + z_1
   $$
3. **Asosiatif Perkalian**
   $$
   (z_1 \cdot z_2) \cdot z_3 = z_1 \cdot (z_2 \cdot z_3)
   $$
4. **Komutatif Perkalian**
   $$
   z_1 \cdot z_2 = z_2 \cdot z_1
   $$
5. **Distributif Perkalian terhadap Penjumlahan**
   $$
   z_1 \cdot (z_2 + z_3) = (z_1 \cdot z_2) + (z_1 \cdot z_3)
   $$
6. **Asosiatif Perkalian Skalar**
   $$
   \alpha \cdot (\beta \cdot z_1) = (\alpha \beta) \cdot z_1
   $$
7. **Asosiatif Perkalian Skalar dan Unsur Ring**
   $$
   (\alpha \cdot z_1) \cdot z_2 = \alpha \cdot (z_1 \cdot z_2) = z_1 \cdot (\alpha \cdot z_2)
   $$
8. **Distributif Skalar terhadap Penjumlahan Ring**
   $$
   \alpha \cdot (z_1 + z_2) = (\alpha \cdot z_1) + (\alpha \cdot z_2)
   $$
9. **Distributif Penjumlahan Skalar terhadap Unsur Ring**
   $$
   (\alpha + \beta) \cdot z_1 = (\alpha \cdot z_1) + (\beta \cdot z_1)
   $$
10. **Identitas Penjumlahan**
    $$
    z_1 + 0 = z_1
    $$
11. **Invers Penjumlahan**
    $$
    z_1 + (-z_1) = 0
    $$
12. **Identitas Perkalian**
    $$
    z_1 \cdot 1 = z_1
    $$

---
## Bukti

Karena $a, b, c, d, p, q, \alpha, \beta \in \mathbb{Z}$, maka sifat-sifat operasi bilangan bulat (asosiatif, komutatif, distributif) berlaku pada komponen-komponennya.

### 1. Asosiatif Penjumlahan
$$
\begin{align*}
(z_1 + z_2) + z_3 &= [(a+c) + (b+d)i] + (p+qi) \\
&= [(a+c)+p] + [(b+d)+q]i \\
&= [a+(c+p)] + [b+(d+q)]i \quad (\text{sifat asosiatif } \mathbb{Z}) \\
&= (a+bi) + [(c+p) + (d+q)i] \\
&= z_1 + (z_2 + z_3)
\end{align*}
$$

### 2. Komutatif Penjumlahan
$$
\begin{align*}
z_1 + z_2 &= (a+c) + (b+d)i \\
&= (c+a) + (d+b)i \quad (\text{sifat komutatif } \mathbb{Z}) \\
&= (c+di) + (a+bi) \\
&= z_2 + z_1
\end{align*}
$$

### 3. Asosiatif Perkalian
Perhatikan hasil kali $(z_1 z_2) z_3$:
$$
\begin{align*}
(z_1 z_2) z_3 &= [(ac-bd) + (ad+bc)i] \cdot (p+qi) \\
&= [(ac-bd)p - (ad+bc)q] + [(ac-bd)q + (ad+bc)p]i \\
&= [acp - bdp - adq - bcq] + [acq - bdq + adp + bcp]i
\end{align*}
$$
Sekarang perhatikan hasil kali $z_1 (z_2 z_3)$:
$$
\begin{align*}
z_1 (z_2 z_3) &= (a+bi) \cdot [(cp-dq) + (cq+dp)i] \\
&= [a(cp-dq) - b(cq+dp)] + [a(cq+dp) + b(cp-dq)]i \\
&= [acp - adq - bcq - bdp] + [acq + adp + bcp - bdq]i
\end{align*}
$$
Karena penjumlahan bilangan bulat komutatif, kedua hasil di atas identik. Maka terbukti asosiatif.

### 4. Komutatif Perkalian
$$
\begin{align*}
z_1 \cdot z_2 &= (ac - bd) + (ad + bc)i \\
&= (ca - db) + (da + cb)i \quad (\text{sifat komutatif } \mathbb{Z}) \\
&= (c+di) \cdot (a+bi) \\
&= z_2 \cdot z_1
\end{align*}
$$

### 5. Distributif Perkalian terhadap Penjumlahan
$$
\begin{align*}
z_1 \cdot (z_2 + z_3) &= (a+bi) \cdot [(c+p) + (d+q)i] \\
&= [a(c+p) - b(d+q)] + [a(d+q) + b(c+p)]i \\
&= [(ac+ap) - (bd+bq)] + [(ad+aq) + (bc+bp)]i \\
&= [(ac-bd) + (ap-bq)] + [(ad+bc) + (aq+bp)]i \\
&= [(ac-bd) + (ad+bc)i] + [(ap-bq) + (aq+bp)i] \\
&= (z_1 \cdot z_2) + (z_1 \cdot z_3)
\end{align*}
$$

### 6. Asosiatif Perkalian Skalar
Perkalian skalar dengan $\alpha \in \mathbb{Z}$ didefinisikan sebagai $\alpha(a+bi) = \alpha a + (\alpha b)i$.
$$
\begin{align*}
\alpha \cdot (\beta \cdot z_1) &= \alpha \cdot (\beta a + \beta bi) \\
&= \alpha(\beta a) + \alpha(\beta b)i \\
&= (\alpha \beta)a + (\alpha \beta)b i \quad (\text{sifat asosiatif } \mathbb{Z}) \\
&= (\alpha \beta) \cdot z_1
\end{align*}
$$

### 7. Asosiatif Perkalian Skalar dan Unsur Ring
$$
\begin{align*}
(\alpha \cdot z_1) \cdot z_2 &= (\alpha a + \alpha bi) \cdot (c+di) \\
&= [(\alpha a)c - (\alpha b)d] + [(\alpha a)d + (\alpha b)c]i \\
&= \alpha(ac - bd) + \alpha(ad + bc)i \quad (\text{distributif } \mathbb{Z}) \\
&= \alpha \cdot [(ac-bd) + (ad+bc)i] \\
&= \alpha \cdot (z_1 \cdot z_2)
\end{align*}
$$

### 8. Distributif Skalar terhadap Penjumlahan Ring
$$
\begin{align*}
\alpha \cdot (z_1 + z_2) &= \alpha \cdot [(a+c) + (b+d)i] \\
&= \alpha(a+c) + \alpha(b+d)i \\
&= (\alpha a + \alpha c) + (\alpha b + \alpha d)i \\
&= (\alpha a + \alpha bi) + (\alpha c + \alpha di) \\
&= (\alpha \cdot z_1) + (\alpha \cdot z_2)
\end{align*}
$$

### 9. Distributif Penjumlahan Skalar terhadap Unsur Ring
$$
\begin{align*}
(\alpha + \beta) \cdot z_1 &= (\alpha + \beta)a + (\alpha + \beta)bi \\
&= (\alpha a + \beta a) + (\alpha b + \beta b)i \\
&= (\alpha a + \alpha bi) + (\beta a + \beta bi) \\
&= (\alpha \cdot z_1) + (\beta \cdot z_1)
\end{align*}
$$

### 10. Identitas Penjumlahan
Elemen nol di $\mathbb{Z}[i]$ adalah $0 = 0 + 0i$.
$$
z_1 + 0 = (a+bi) + (0+0i) = (a+0) + (b+0)i = a+bi = z_1
$$

### 11. Invers Penjumlahan
Invers dari $z_1 = a+bi$ adalah $-z_1 = -a + (-b)i$.
$$
z_1 + (-z_1) = (a-a) + (b-b)i = 0 + 0i = 0
$$

### 12. Identitas Perkalian
Elemen satuan di $\mathbb{Z}[i]$ adalah $1 = 1 + 0i$.
$$
\begin{align*}
z_1 \cdot 1 &= (a+bi)(1+0i) \\
&= (a\cdot 1 - b\cdot 0) + (a\cdot 0 + b\cdot 1)i \\
&= (a - 0) + (0 + b)i \\
&= a + bi = z_1
\end{align*}
$$

***
## Definition Used
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Bilangan Bulat Gauss]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Gelanggang Komutatif]]
 