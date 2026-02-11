#Teorema 

Misalkan $(\mathbb{V}, \|\cdot\|)$ adalah ruang bernorm. Definisikan 
$$d_{\|\cdot\|} (x, y) = \|x - y\|$$
untuk setiap $x, y \in \mathbb{V}$. Maka, $(\mathbb{V}, d_{\|\cdot\|})$ adalah ruang metrik.

---
## Bukti
Akan ditunjukkan bahwa $d_{\|\cdot\|}$ memenuhi keempat aksioma metrik dengan menggunakan sifat-sifat norm.

1.  **Aksioma Simetri:** $d(x, y) = d(y, x)$
    $$
    \begin{align*} 
    d_{\|\cdot\|} (x, y) &= \|x - y\| \\
    &= \|(-1) \cdot (y - x)\| \\
    &= |(-1)| \cdot \|y-x\| \quad (\text{Sifat Homogenitas Absolut}) \\
    &= 1 \cdot \|y-x\| \\
    &= d_{\|\cdot\|} (y, x)
    \end{align*}
    $$

2.  **Aksioma Non-negativitas:** $d(x, y) \ge 0$
    Berdasarkan sifat definit positif dari norm, $\|v\| \ge 0$ untuk setiap vektor $v$. Maka:
    $$d_{\|\cdot\|} (x, y) = \|x - y\| \ge 0$$

3.  **Aksioma Identitas:** $d(x, y) = 0 \iff x = y$
    Berdasarkan sifat definit positif dari norm, $\|v\| = 0 \iff v = \mathbf{0}$. Maka:
    $$
    \begin{align*} 
    d_{\|\cdot\|} (x, y) = 0 &\iff \|x - y\| = 0 \\
    &\iff x - y = \mathbf{0} \\
    &\iff x = y
    \end{align*}
    $$

4.  **Aksioma Ketaksamaan Segitiga:** $d(x, y) \le d(x, z) + d(z, y)$
    Berdasarkan ketaksamaan segitiga pada norm, $\|u+v\| \le \|u\| + \|v\|$. Maka:
    $$
    \begin{align*} 
    d_{\|\cdot\|} (x, y) &= \|x - y\| \\
    &= \|(x - z) + (z - y) \| \\
    &\le \|x - z\| + \|z - y \| \quad (\text{Ketaksamaan Segitiga Norm}) \\
    &= d_{\|\cdot\|}(x, z) + d_{\|\cdot\|}(z, y)
    \end{align*}
    $$
Karena keempat aksioma terpenuhi, maka $(\mathbb{V}, d_{\|\cdot\|})$ adalah ruang metrik. ■

***
## Definition Used:
* [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
* [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Bernorm]]