#Teorema 

Misalkan $D$ Daerah Ideal Utama dan $\{I_n\}$ adalah ideal-ideal **sejati** dari $D$ dengan
$$I_1 \subseteq I_2 \subseteq I_3 \subseteq \cdots $$
maka terdapat $n \in \mathbb{N}$ sehingga $I_k = I_n \quad \forall k \ge n$.

---

## Bukti

Misalkan $\displaystyle I = \bigcup_{n \in \mathbb{N}} I_n$. Akan ditunjukkan $I$ adalah ideal.

Ambil $x, y \in I$ dan $r \in D$. Maka ada $n_1, n_2 \in \mathbb{N}$ sehingga $x \in I_{n_1}$ dan $y \in I_{n_2}$. Tanpa mengurangi keumuman, misalkan $n_1 \le n_2$. Maka $I_{n_1} \subseteq I_{n_2}$. Artinya $x, y \in I_{n_2}$. Karena $I_{n_2}$ ideal maka
$$x + y \in I_{n_2} \subseteq I \quad \text{dan} \quad rx \in I_{n_2} \subseteq I$$
Maka $I$ adalah ideal. Karena $D$ daerah ideal utama maka $I = \langle d \rangle, \quad \exists \ d \in I$. Karena $d \in I$ maka $d \in I_n \quad \exists \ n \in \mathbb{N}$. Karena $I_n$ ideal maka $rd \in I_n \quad \forall r \in D$. Artinya $I = \langle d \rangle \subseteq I_n$.

Ambil $k \ge n$. Jelas $I_n \subseteq I_k$. Kemudian $I_k \subseteq I \subseteq I_n$. Maka dapat disimpulkan
$$\forall\ k \ge n: \quad I_k = I_n \quad $$


***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Daerah Integral/Daerah Ideal Utama]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Gelanggang/Ideal Sejati]]