#Teorema 

Misalkan $D$ Daerah Ideal Utama dan $p \in D$ unsur taknol bukan unit.
$$p \text{ prima} \quad \iff \quad \text{Jika }\ p = ab \ \text{ maka } \ a\ \text{ unit atau } \ b\ \text{ unit}$$

---

## Bukti

### ($\Rightarrow:$)

Karena setiap Daerah Ideal Utama adalah Daerah Integral maka berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Unsur Prima Daerah Integral|teorema]] jelas berlaku jika $p = ab$ maka $a$ unit atau $b$ unit.
### ($\Leftarrow:$)

Misalkan $D$ Daerah Ideal Utama dan $p \in D$ sehingga "Untuk setiap $a, b \in D$ jika $p = ab$ maka $a$ unit atau $b$ unit". Akan ditunjukkan $p$ prima.
Misalkan $p \mid gh$ namun $p \nmid g$ untuk suatu $g, h \in D$. Akan ditunjukkan $p \mid h$.
Berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Teorema Bezout (Daerah Ideal Utama)|Identitas Bezout]], ada $d \in D$ sehingga $$d = (p, g) = sp+gt, \quad \exists s, t \in D$$
Karena $d \mid g$ dan $d\mid p$ maka $g = du_1$ dan $p = du_2$ untuk suatu $u_1, u_2 \in D$.

Jika $u_2$ unit maka terdapat invers $u_2^{-1}$ sehingga $p = du_2 \Rightarrow d = pu_2^{-1}$. Artinya
$$g = du_1 = pu_2^{-1}u_1 \quad \Rightarrow \quad p \mid g \quad\text{(Kontradiksi)}$$
Berdasarkan premis, karena $p = du_2$ dan $u_2$ bukan unit maka $d$ unit. Artinya ada invers sehingga
$$
\begin{align*}
1 &= d^{-1} \cdot d = d^{-1}\cdot(sp + gt) \\
&= d^{-1}sp + d^{-1}gt \\
h &= d^{-1}sph + d^{-1}tgh
\end{align*}
$$
Perhatikan bahwa $p\mid gh$ maka $p \mid \left(d^{-1}sph + d^{-1}tgh\right) = h$.

Terbukti $p$ prima.


***

## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Unit (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Prima (Ring)]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Unsur Tak Tereduksi (Ring)]]