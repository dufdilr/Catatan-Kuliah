#Teorema 
Misalkan $A, B$ grup dan $f:A \to B$ adalah **isomorfisma grup**. Maka
1. Jika $A$ siklik maka $B$ juga siklik.
2. Jika $A$ komutatif maka $B$ juga komutatif.
3. $f(Z(A)) = Z(B)$
4. Untuk setiap $a \in A$ berlaku $\text{ord}(a) = \text{ord}(f(a))$

---
## Bukti

### 1.
Misalkan $A = \left< a \right>$ grup siklik. Ambil $b \in B$, karena $f$ adalah isomorfisma grup, maka ada $x \in A$ sehingga $f(x) = b$. Karena $A$ grup siklik maka $x = a^n$ untuk suatu $n \in \mathbb{Z}$. Perhatikan bahwa
$$
b = f(x) = f(a^n) = (f(a))^n
$$
Maka $B = \left< f(a) \right>$. Terbukti, $B$ juga grup siklik.

### 2.
Misalkan $A$ grup komutatif. Ambil $b_{1}, b_{2} \in B$. Karena $f$ adalah isomorfisma grup, maka terdapat $a_{1}, a_{2} \in A$ sehingga $f(a_{1}) = b_{1}$ dan $f(a_{2}) = b_{2}$. Perhatikan bahwa
$$
b_{1}b_{2} = f(a_{1})f(a_{2}) = f(a_{1}a_{2}) = f(a_{2}a_{1}) = f(a_{2})f(a_{1}) = b_{2}b_{1}
$$
Terbukti $B$ juga grup komutatif.

### 3.
Ambil $h \in f(Z(A))$, maka terdapat $g \in Z(A)$ sehingga $f(g) = h$. Ambil $b \in B$. Karena $f$ isomorfisma grup maka terdapat $a \in A$ sehingga $f(a) = b$. Lebih lanjut
$$
bh = f(a)f(g) = f(ag) = f(ga) = f(g)f(a) = hb
$$
Terbukti untuk setiap $b \in B$, $bh = hb$. Maka $h \in Z(B)$. Artinya $f(Z(A))\subseteq Z(B)$.

Lebih lanjut, ambil $h \in Z(B)$. Karena $f$ adalah isomorfisma maka terdapat $g \in A$ sehingga $f(g) = h$. Ambil $a \in A$. Perhatikan bahwa
$$
f(ag) = f(a)f(g) = f(a)h = hf(a) = f(g)f(a) = f(ga)
$$
Karena $f(ag) = f(ga)$ dan $f$ adalah isomorfisma maka $ga = ag$. Maka $g \in Z(A)$. Akibatnya $h \in f(Z(A))$. Artinya $f(Z(A))\supseteq Z(B)$.

Terbukti $f(Z(A)) = Z(B)$.

### 4.
Misalkan $\text{ord}(a) = k$ dan $\text{ord}(f(a)) = l$. Perhatikan bahwa
$$
a^k = e_A \quad\implies\quad f(a^k)= (f(a))^k = e_B
$$
Artinya $\text{ord}(f(a)) = l \mid k$. Perhatikan bahwa
$$
f(a)^l = e_B \quad\implies\quad f(a^l) = f(e_A) = e_B \quad\implies\quad a^l = e_A
$$
Artinya $\text{ord}(a) = k \mid l$. Karena $l \mid k$ dan $k \mid l$ [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^d21346|maka]] $k = l$ .



***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Homomorfisma Grup/Isomorfisma (Grup)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Komutatif]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pusat Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Unsur Grup]]