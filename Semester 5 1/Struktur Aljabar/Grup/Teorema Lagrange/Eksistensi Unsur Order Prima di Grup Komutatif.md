#Teorema
Misalkan $A$ grup komutatif. Jika $p$ bilangan prima sehingga $p \mid \text{ord}(A)$ maka terdapat $a \in A$ sehingga
$$
\text{ord}(a) = p
$$
---
## Bukti
Akan ditunjukkan dengan induksi bahwa untuk setiap $n \in \mathbb{N}$ berlaku: Untuk setiap grup $A$ dengan $\text{ord}(A) = np$ terdapat $a \in A$ sehingga $\text{ord}(a) = p$.
### Kasus Basis
Misalkan $A$ grup komutatif dengan $\text{ord}(A) = p$. Berdasarkan [[Grup Siklik Orde Prima|Teorema]], $A$ adalah grup siklik sehingga $A = \left< a \right>$ dan [[Order Unsur Pembangun|berlaku]] $\text{ord}(a) = \text{ord}(A) = p$.

### Kasus Induksi
Misalkan $n \in \mathbb{N}$ sehingga berlaku: Untuk setiap grup $G$ dengan $\text{ord}(G) = kp$ dimana $k < n$ terdapat $g \in G$ sehingga $\text{ord}(g) = p$.
Misalkan $A$ grup komutatif dengan $\text{ord}(A) = np$. Ambil $a \in A$ dengan $a \neq e$. Tinjau $B = \left< a \right>$. Karena $A$ grup komutatif maka $B \unlhd A$ dan $A/B$ adalah [[Grup Hasil Bagi]]. Berdasarkan [[Teorema Lagrange]], berlaku
$$
\text{ord}(B) \cdot \text{ord}(A/B) = \text{ord}(A) = np
$$
Tinjau kasus berikut
* Jika $p \mid \text{ord}(B)$.
[[Order Unsur Pembangun|Maka]], $\text{ord}(B) = \text{ord}(a) = mp$ untuk suatu $m \in \mathbb{N}$. Perhatikan [[Order Pangkat|bahwa]]
$$
\text{ord}(a^m) = \frac{\text{ord}(a)}{(\text{ord}(a), m)} = \frac{mp}{(mp, m)} = \frac{mp}{m} = p
$$
Pilih $x = a^m$. Didapatkan unsur dengan $\text{ord}(x) = p$.
* Jika $p \nmid \text{ord}(B)$. 
Berdasarkan [[Karakterisasi Bilangan Prima]], maka $p \mid \text{ord}(A/B)$. 
Misalkan $\text{ord}(A/B) = mp$ untuk suatu $m \in \mathbb{N}$. Perhatikan bahwa $\text{ord}(B) = \text{ord}(a) > 1$. Artinya $mp < np$ sehingga $m < n$. 
Berdasarkan hipotesa induksi, terdapat $xB \in A/B$ sehingga $\text{ord}(xB) = p$. 
$$
(xB)^p = x^pB = eB
$$
Maka $x^p \in x^pB = B$. Misalkan $\text{ord}(x^p) = k$. Berdasarkan [[Order Pangkat]]
$$
\text{ord}(x^p) = \frac{\text{ord}(x)}{(\text{ord}(x), p)} \quad\implies\quad \text{ord}(x) = \text{ord}(x^p) \cdot (\text{ord}(x), p) > k
$$
Lebih lanjut, tinjau $g = x^k$. Perhatikan bahwa
$$
(x^p)^k = (x^k)^p = e
$$
Artinya $\text{ord}(g) \mid p$. Karena $\text{ord}(x) > k$ maka $g = x^k \neq e$, artinya $\text{ord}(g) \neq 1$. Dapat disimpulkan $\text{ord}(g) = p$. Terbukti $A$ mengandung unsur dengan orde $p$.

Berdasarkan [[Prinsip Induksi Matematika]], terbukti untuk setiap grup $A$ dengan $\text{ord}(A) = np$ untuk suatu $n \in \mathbb{N}$ maka terdapat $g \in A$ sehingga $\text{ord}(g) = p$.

***
## Definition Used 
 * [[Grup Komutatif]]
 * [[Bilangan Prima]]
 * [[Order Unsur Grup]]
 * [[Orde Grup]]
 * [[Indeks Subgrup]]
 * [[Subgrup Terbangun]]