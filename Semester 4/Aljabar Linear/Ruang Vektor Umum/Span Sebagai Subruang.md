#Teorema 

Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$. Misalkan pula $v_{1}, v_{2}, \cdots, v_n \in V$. Maka himpunan **Span** 
$$
\left< v_{1}, v_{2}, \cdots, v_n \right>
$$
membentuk **Subruang** dari $V$

---
## Bukti
Jelas $v_{1},v_{2}, \cdots, v_n \in \left< v_{1}, v_{2}, \cdots, v_n \right>$ maka $\left< v_{1}, v_{2}, \cdots, v_n \right> \neq \emptyset$. Lebih lanjut, jelas $\left< v_{1}, v_{2}, \cdots, v_n \right> \subseteq V$. Maka $\left< v_{1}, v_{2}, \cdots, v_n \right>$ adalah subhimpunan tak-kosong dari $V$. 
Ambil $u, w \in \left< v_{1}, v_{2}, \cdots, v_n \right>$ dan $\alpha \in \mathbb{F}$. Tulis $u = a_{1}v_{1} + a_{2}v_{2} + \cdots + a_nv_n$ dan $w = b_{1}v_{1} + b_{2}v_{2} + \cdots + b_nv_n$ dengan $a_{1}, a_{2}, \cdots, a_n, b_{1}, b_{2}, \cdots, b_n \in \mathbb{F}$. Perhatikan bahwa
$$
\begin{align*}
u + w &=  a_{1}v_{1} + a_{2}v_{2} + \cdots + a_nv_n + b_{1}v_{1} + b_{2}v_{2} + \cdots + b_nv_n \\
&= (a_{1}+b_{1})v_{1} + (a_{2}+b_{2})v_{2} + \cdots + (a_n+b_n)v_n \\
\\
\alpha \cdot u &= \alpha \cdot \left( a_{1}v_{1} + a_{2}v_{2} + \cdots + a_nv_n \right) \\
&= \alpha a_{1}v_{1} + \alpha a_{2}v_{2} + \cdots +  \alpha a_nv_n
\end{align*}
$$
Jelas $u + w, \alpha \cdot u \in \left< v_{1}, v_{2}, \cdots, v_n \right>$ maka berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Subruang]] terbukti bahwa $\left< v_{1}, v_{2}, \cdots, v_n \right>$ membentuk subruang dari $V$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Subruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Kombinasi Linear dan Span]]