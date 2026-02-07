#Teorema 
Misalkan $(R, +, \cdot)$ suatu gelanggang. Maka berlaku
1. **Perkalian Nol:** Untuk setiap $a \in R$ berlaku $a\cdot 0 = 0 \cdot a = 0$ ^1e044a
2. **Perkalian Inverse Penjumlahan:** Untuk setiap $a, b \in R$ berlaku $a(-b) = (-a)b = -(ab)$
3. **Perkalian Dua Inverse:** Untuk setiap $a, b, c \in R$ berlaku $(-a)(-b) = ab$

---
## Bukti
### 1.
Ambil $a \in R$. Perhatikan bahwa
$$
a\cdot 0 = a\cdot 0 + 0 = a\cdot 0 + a\cdot 0 - a\cdot0 = a\cdot(0 + 0) - a\cdot 0 = a\cdot 0 - a\cdot 0 = 0
$$
Serupa,
$$
0\cdot a = 0\cdot a + 0 = 0\cdot a + 0\cdot a-0\cdot a = (0+0)\cdot a - 0\cdot a = 0\cdot a - 0\cdot a = 0
$$
Terbukti $a\cdot0 = 0\cdot a = 0$.

### 2.
Ambil $a, b \in R$. Perhatikan bahwa berdasarkan sifat 1
$$
a(-b) + ab = a(-b+b) = a \cdot 0 = 0
$$
Serupa,
$$
(-a)b + ab = (-a+a)b = 0 \cdot b = 0
$$
Berdasarkan [[Sifat Grup|Ketunggalan Inverse]] pada grup $(R, +)$ maka terbukti $a(-b) = (-a)b = -(ab)$.

### 3.
Ambil $a, b \in R$. Berdasarkan sifat $2$ dan [[Sifat Grup#^6fb1e8|Sifat Inverse dari Inverse]] pada grup $(R, +)$ maka
$$
(-a)(-b) = -(a(-b)) = -(-(ab)) = ab
$$
Terbukti $(-a)(-b)=ab$

***
## Definition Used 
 * [[Gelanggang]]
 * [[Grup]]