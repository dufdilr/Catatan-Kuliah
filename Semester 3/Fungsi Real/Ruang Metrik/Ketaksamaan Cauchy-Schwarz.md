#Teorema 

Misalkan $V$ adalah ruang hasil kali dalam atas $\mathbb{R}$. Untuk setiap $x, y \in V$ berlaku
$$|\langle x, y\rangle | \ \le \ \|x\| \cdot \|y\|$$

---
## Bukti 1 (Ketaksamaan Trivial):
Ambil $x, y \in V$. Definisikan $f(t) = \|x + ty\|^2$ untuk setiap $t \in \mathbb{R}$. Perhatikan bahwa:
$$
\begin{align*}
f(t) &= \langle x+ty, x+ty\rangle \\
&= \langle x, x \rangle + 2t \cdot \langle x, y \rangle + t^2 \cdot\langle y,y \rangle \\
&= \|y\|^2 \cdot t^2 + 2\cdot \langle x, y \rangle \cdot t +\|x\|^2
\end{align*}
$$
Karena $x$ dan $y$ tetap, maka $f(t)$ adalah fungsi kuadrat dalam $t$. Berdasarkan definisi, $f(t) = \|x + ty\|^2 \ge 0$ untuk setiap $t \in \mathbb{R}$. Agar sebuah fungsi kuadrat tidak pernah bernilai negatif, grafiknya tidak boleh memotong sumbu-x lebih dari satu kali, yang berarti diskriminannya harus non-positif ($D \le 0$).
$$
\begin{align*}
D = (2\cdot \langle x, y \rangle)^2 - 4 (\|y\|^2)(\|x\|^2) &\le 0 \\ 
4\langle x, y \rangle^2 - 4\|x\|^2 \|y\|^2 &\le 0 \\ 
\langle x, y \rangle^2 &\le \|x\|^2 \|y\|^2 \\ \\
|\langle x, y \rangle| &\le \|x\|\cdot \|y\| 
\end{align*}
$$

## Bukti 2:

***
## Definition Used:
* [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Hasil Kali Dalam]]