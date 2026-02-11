#Teorema 

Misalkan $A$ adalah suatu grup dan $Z(A)$ adalah pusat $A$. Jika $A/Z(A)$ adalah grup siklik maka $A$ adalah grup komutatif.

---
## Bukti
Telah ditunjukkan bahwa [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Pusat Grup Sebagai Subgrup Normal|Pusat Grup adalah Subgrup Normal]]. Artinya $A/Z(A)$ membentuk [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Normal/Grup Hasil Bagi]]. Lebih lanjut, karena $A/Z(A)$ adalah grup siklik maka
$$
A/Z(A) = \left< aZ(A) \right> 
$$
untuk suatu $aZ(A) \in A/Z(A)$. Ambil $x, y \in A$. Perhatikan bahwa
$$
xZ(A) = a^mZ(A) \quad \text{dan} \quad yZ(A) = a^nZ(A)
$$
untuk suatu $m, n \in \mathbb{N}$. Perhatikan bahwa $x \in xZ(A)$ dan $y \in yZ(A)$. Artinya $x = a^mz_{1}$ dan $y = a^nz_{2}$ untuk suatu $z_{1}, z_{2} \in Z(A)$. Perhatikan bahwa
$$
\begin{align*}
xy = (a^mz_{1})(a^nz_{2}) &= a^m(z_{1}a^n)z_{2} & \text{(Asosiatif)} \\
&= a^m(a^nz_{1})z_{2} & z_{1}\in Z(A) \\
&= (a^ma^n)(z_{1}z_{2}) & \text{(Asosiatif)} \\
&= a^{m+n}(z_{1}z_{2}) & \text{(Operasi Pangkat)} \\
&= (a^na^m)(z_{1}z_{2}) & \text{(Operasi Pangkat)} \\
&= (a^na^m)(z_{2}z_{1}) & z_{1} \in Z(A) \\
&= a^n(a^mz_{2})z_{1} & \text{(Asosiatif)} \\
&= a^n(z_{2}a^m)z_{1} & z_{2} \in Z(A) \\
&= (a^nz_{2})(a^mz_{1}) & \text{(Asosiatif)} \\
&= yx
\end{align*}
$$
Terbukti bahwa $xy=yx$ untuk setiap $x,y \in A$
***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pusat Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Siklik]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup Komutatif]]