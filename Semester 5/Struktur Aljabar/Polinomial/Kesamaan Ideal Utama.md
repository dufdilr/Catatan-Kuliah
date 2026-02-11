#Teorema 
Misalkan $D$ adalah daerah integral dan $p, q \in D$ taknol. Maka berlaku
$$
\left< p \right>  = \left< q \right>  \iff p, q \text{ sekawan}
$$

---
## Bukti
### $\Rightarrow$
Misalkan $\left< p \right> = \left< q \right>$. Perhatikan bahwa $p \in \left< q \right>$ dan $q \in \left< p \right>$. Maka $p = qr_{1}$  dan $q = pr_{2}$. Akibatnya
$$
p = qr_{1} = pr_{2}r_{1} \quad\implies\quad p- pr_{2}r_{1} = p(1 - r_{2}r_{1}) = 0
$$
Karena $p$ adalah tak-nol dan $D$ daerah integral, berdarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Hukum Pembatalan (Daerah Integral)|Hukum Pembatalan]] maka 
$$
1-r_{2}r_{1} = 0 \quad\implies\quad r_{2}r_{1} = 1
$$
Artinya $r_{1}$ dan $r_{2}$ adalah unit. Terbukti $r_{1}, r_{2}$ sekawan.

### $\Leftarrow$
Misalkan $p, q$ sekawan. Artinya $p = rq$ untuk suatu $r$ unit di $D$. Perhatikan bahwa
$$
\begin{align*}
x \in \left< p \right> &\ \iff x = pk, \ \exists k \in D \\
&\ \iff x = rqk, \ \exists k \in D \\
&\ \iff x = ql, \exists l \in D \\
&\ \iff x \in \left< q \right> 
\end{align*}
$$
Terbukti $\left< p \right> = \left< q \right>$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Integral]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Sekawan (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Utama]]