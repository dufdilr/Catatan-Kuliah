#Teorema 
Misalkan $n \in \mathbb{N}$ dan $r$ adalah akar primitif dari $n$. Maka
$$
r^u \text{ akar primitif } n \quad\iff\quad (u, \varphi(n)) = 1
$$

---
## Bukti
Misalkan $r^u$ akar primitif dari $n$. Karena $r$ akar primitif dari $n$ maka $\text{ord}_{n}\left({r}\right) = \varphi(n)$. Perhatikan bahwa
$$
\text{ord}_{n}\left({r^u}\right) = \frac{\varphi(n)}{(\varphi(n), u)}
$$
Maka
$$
\begin{align*}
r^u \text{ akar primitif } n & \iff \text{ord}_{n}\left({r^u}\right) = \varphi(n)\\
& \iff\frac{\varphi(n)}{(\varphi(n), u)} = \varphi(n) \\
& \iff (u, \varphi(n)) = 1 \\
\end{align*}
$$
Terbukti.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Akar Primitif/Akar Primitif]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]