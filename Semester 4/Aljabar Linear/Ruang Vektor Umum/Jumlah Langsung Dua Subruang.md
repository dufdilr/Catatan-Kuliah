#Teorema 

Misalkan $V$ ruang vektor atas $\mathbf{F}$ dan $U, W$ adalah subruang dari $V$. Berlaku
$$
U + W \text{ adalah Jumlah Langsung} \quad \iff \quad U\cap W = \{\overline{0}\}
$$

---
## Bukti
### $\Rightarrow$
Misalkan $U + W$ adalah Jumlah Langsung. Ambil ${v} \in U \cap W$. Perhatikan bahwa ${v} \in U$ dan ${-v} \in W$. Maka ${v} + ({-v}) = \mathbf{0} \in U+W$ namun $\mathbf{0}+\mathbf{0} = \mathbf{0}$. Karena $V + W$ adalah Jumlah Langsung maka haruslah $v = \mathbf0$.

Terbukti $U\cap W = \{\mathbf{0}\}$
### $\Leftarrow$
Misalkan $U \cap W =  \{\mathbf{0}\}$. Tinjau $\mathbf{0} = u+w$ dengan $u \in U$ dan $w \in W$. Perhatikan bahwa $u = -w$, artinya $u \in U \cap W$. Berdasarkan hipotesis maka $u = \mathbf{0}$ akibatnya $w = -u = \mathbf{0}$. Berdasarkan [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Karakterisasi Jumlah Langsung]] terbukti bahwa $U+W$ adalah **Jumlah Langsung**.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Ruang Vektor]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Jumlah Subruang]]
 * [[Buat Backup/Semester 4/Aljabar Linear/Ruang Vektor Umum/Jumlah Subruang]]