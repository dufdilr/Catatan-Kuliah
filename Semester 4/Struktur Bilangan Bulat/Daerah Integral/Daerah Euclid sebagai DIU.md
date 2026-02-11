#Teorema 

Setiap Daerah Euclid adalah Daerah Ideal Utama ^939743

---

## Bukti

Misalkan $R$ dengan pemetaan $\delta$ adalah suatu daerah euclid. Misalkan $I$ ideal dari $R$. Tinjau
$$A = \{\delta (x) \quad | \quad x \in I/\{0\}\}$$
Jelas $\emptyset \neq A \subseteq \mathbb{N}$, sehingga ada unsur terkecil $\delta(d)$. Akan ditunjukkan bahwa $I = \langle d \rangle$. Karena $d \in I$ dan $I$ ideal maka $rd \in I \ \forall r \in R$. Artinya $\langle d \rangle \subseteq I$.

Ambil $x \in I$, karena daerah euclid maka dapat dituliskan
$$x = dq + r$$
dengan $\delta(r) < \delta(d)$ atau $r = 0$. Perhatikan bahwa $r = x - dq$. Karena $x, d \in I$ dan $I$ ideal maka $r = x - dq \in I$.

Jika $r \neq 0$ maka $r \in A$ sehingga $\delta (r) \ge \delta(d)$ (Kontradiksi dengan fakta $\delta(r) < \delta(d)$). Artinya $r = 0$. Berarti $x = qd \in \langle d \rangle$. Maka $I \subseteq \langle d \rangle$.

Berarti, setiap ideal $I$ dari $R$ dapat ditulis sebagai $\langle d \rangle, \quad \exists \ d \in I$. Maka daerah euclid adalah daerah ideal utama.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Euclid]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]]