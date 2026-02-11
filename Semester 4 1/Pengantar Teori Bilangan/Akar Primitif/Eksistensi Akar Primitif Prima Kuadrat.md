#Teorema 

Misalkan $p$ adalah bilangan prima ganjil dan $r$ adalah akar primitif dari $p$. Maka $r$ atau $r+p$ adalah akar primitif dari $p^2$.

---
## Bukti

Perhatikan bahwa $\text{ord}_{p}(r) = \varphi(p)=p-1$. Misalkan $\text{ord}_{p^2}(r) = k$ maka
$$
r^k \equiv 1 \mod p^2 \quad\implies\quad p^2 \mid r^k-1  \quad\implies\quad p \mid r^k-1 \quad\implies\quad r^k \equiv 1 \mod p
$$
Berdasarkan [[Buat Backup/Semester 4 1/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat|teorema]] maka $\text{ord}_{p}(r) = p-1 \mid k$. Karena $r$ akar primitif dari $p$ maka jelas $p \not\mid r$ sehingga $(p, r) = 1$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima]] maka $(p^2, r) = 1$. Berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Teorema Euler (Modulo)]] maka
$$
r^{\varphi(p^2)} = r^{p^2-p} = r^{p(p-1)} \equiv 1 \mod p^2
$$
Berdasarkan  [[Buat Backup/Semester 4 1/Pengantar Teori Bilangan/Akar Primitif/Persamaan Diophantine Modulo Pangkat|teorema]] maka $\text{ord}_{{p^2}}(r) = k \mid p(p-1)$.

Perhatikan bahwa $p-1 \mid k$ dan $k \mid p(p-1)$ maka pastilah $k = p-1$ atau $k = p(p-1)$.
* **Jika $k = p-1$**
	Perhatikan bahwa $r^{p-1} \equiv 1 \mod p^2$. Tinjau $s = r+p$. Perhatikan bahwa $r \equiv s \mod p$. Artinya $s$ juga akar primitif dari $p$. Telah ditunjukkan bahwa $\text{ord}_{p^2}(s) = p(p-1)$ atau $\text{ord}_{p^2}(s) = p-1$. Perhatikan bahwa
	$$
\begin{align*}
s^{p-1} &= (r+p)^{p-1} \\
&= r^{p-1} + (p-1)r^{p-2}p^1 + \frac{p(p-1)}{2}r^{p-3}p^2 + \dots + (p-1)r^1p^{p-2} \\
&\equiv r^{p-1} + (p-1)pr^{p-2} &\mod p^2 \\
& \equiv 1 + (p^2-p)r^{p-2} &\mod p^2 \\
&\equiv 1  - pr^{p-2} & \mod p^2
\end{align*}
$$
	Karena $\text{ord}_{p^2}r = p-1$ maka $r^{p-2} \not \equiv 1 \mod p^2$. Artinya $s^{p-1} \not \equiv 1 \mod p^2$. Artinya
	$$
\text{ord}_{p^2}(s) \neq p-1
$$
	Dapat disimpulkan $\text{ord}_{p^2}(s) = p(p-1) = \varphi(p^2)$. Maka $s = r+p$ adalah akar primitif 