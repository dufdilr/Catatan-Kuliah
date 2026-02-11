#Teorema 

Misalkan $A$ dan $B$ adalah grup dengan identitas $e_A$ dan $e_B$ berturut turut. Misalkan pula $f:A \to B$ adalah **homomorfisma grup** serta $S \le A$ dan $H \le B$. Maka berlaku
1. $f(e_A) = e_B$ ^5884b9
2. Untuk setiap $a \in A$ berlaku $f(a^{-1}) = \left( f(a) \right)^{-1}$
3. $f(S)$ merupakan subgrup dari $B$ ^bf256b
4. Untuk setiap $a \in A$ dan $n \in \mathbb{N}$ berlaku $f(a^n) = (f(a))^n$
5. Jika $S$ adalah grup komutatif maka $f(S)$ juga grup komutatif.
6. Jika $S$ adalah grup siklik maka $f(S)$ juga grup siklik.

---
## Bukti
### 1.
Perhatikan bahwa
$$
\begin{align*}
f(e_A) &= f(e_A) \cdot e_B = f(e_A) \cdot f(e_A)\cdot (f(e_A))^{-1} \\
&= f(e_A \cdot e_A) \cdot \left( f(e_A) \right) ^{-1} \\
&= f(e_A) \cdot (f(e_A))^{-1} \\
&= e_B
\end{align*}
$$

### 2.
Perhatikan bahwa
$$
\begin{align*}
f(a) \cdot f(a^{-1}) &= f(a \cdot a^{-1}) = f(e_A) = e_B \\
f(a^{-1}) \cdot f(a) &= f(a^{-1} \cdot a) = f(e_A) = e_B 
\end{align*}
$$
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Sifat Grup#^cfe6f6|Ketunggalan Inverse]] maka $(f(a))^{-1} = f(a^{-1})$.

### 3.
Jelas $e_A \in S$ maka $f(e_A) \in f(S)$ sehingga $f(S) \neq \emptyset$. Ambil $y_{1}, y_{2} \in f(S)$ maka $y_{1}=f(a_{1})$ dan $y_{2} = f(a_{2})$ untuk suatu $a_{1}, a_{2} \in S$. Perhatikan bahwa $y_{2}^{-1} = (f(a_{2}))^{-1} = f(a_{2}^{-1})$ maka
$$
y_{1}y_{2}^{-1} = f(a_{1})f(a_{2}^{-1}) = f(a_{1}a_{2}^{-1})
$$
Karena $a_{1}, a_{2} \in S$ maka $a_{1}a_{2}^{-1} \in S$. Akibatnya $y_{1}y_{2}^{-1} \in f(S)$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Subgrup]] maka $f(S)$ adalah subgrup dari $B$.

### 4. 
Akan dibuktikan dengan induksi. Ambil $a \in A$
1. **Kasus Basis**
	Jelas 
	$$
f(a^1) = f(a) = (f(a))^1
$$
2. **Langkah Induksi**
Misalkan untuk suatu $n \in \mathbb{N}$ berlaku $f(a^n) = (f(a))^n$. Perhatikan bahwa
$$
f(a^{n+1}) = f(a^n \cdot a) = f(a^n) \cdot f(a) = (f(a))^n \cdot f(a) = (f(a))^{n+1}
$$

Berdasarkan [[Buat Backup/Prerquested/Prinsip Induksi Matematika]] terbukti bahwa untuk setiap $n \in \mathbb{N}$ berlaku
$$
f(a^n) = (f(a))^n
$$

### 5.
Misalkan $S$ grup komutatif. Telah ditunjukkan $f(S)$ membentuk subgrup dari $B$. Ambil $y_{1}, y_{2} \in f(S)$ maka $y_{1}=f(a_{1})$ dan $y_{2} = f(a_{2})$ untuk suatu $a_{1}, a_{2} \in S$. Perhatikan bahwa
$$
\begin{align*}
y_{1}y_{2} &= f(a_{1})f(a_{2}) = f(a_{1}a_{2}) = f(a_{2}a_{1}) = f(a_{2})f(a_{1}) = y_{2}y_{1}
\end{align*}
$$
Terbukti $f(S)$ adalah grup komutatif.

### 6.
Misalkan $S = \left< s \right>$ grup siklik. Telah ditunjukkan $f(S)$ membentuk subgrup dari $B$. Ambil $y_{1} \in f(S)$ maka $y_{1}=f(a_{1})$  untuk suatu $a_{1} \in S$. Karena $S = \left< s \right>$ maka $a_{1} = s^n$ untuk suatu $n \in \mathbb{N}$. Perhatikan bahwa
$$
y_{1} = f(a_{1}) = f(s^n) = (f(s))^n
$$
Maka, $f(S) = \left< f(s) \right>$. Terbukti $f(S)$ adalah grup siklik.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Homomorfisma (Grup)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Komutatif]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]