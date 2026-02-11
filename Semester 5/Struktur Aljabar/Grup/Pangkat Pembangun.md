#Teorema 
Misalkan $A$ adalah grup siklik dengan $|A| = n$ dan pembangun $a$. Unsur $a^k$ adalah pembangung dari $A$ jika dan hanya jika $(n, k) = 1$.

---
## Bukti
Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Unsur Pembangun]], maka $\text{ord}(a) = \text{ord}(A) = n$. 

Perhatikan bahwa berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Order Pangkat|Teorema]] maka $\text{ord}\left({a^k}\right) = \frac{n}{(n, k)}$. Maka berlaku
$$
\begin{align*}
a^k \text{ unsur pembangun dari } A &\ \iff \text{ord}(a^k) = n \\
&\ \iff \frac{n}{(n,k)} = n \\
& \ \iff (n, k) = 1
\end{align*}
$$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Orde Grup]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Relatif Prima]]
