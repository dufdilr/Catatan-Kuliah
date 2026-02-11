#Definisi #Teorema 

Definisikan relasi pada bilangan bulat
$$
a < b \iff b-a \in \mathbb{N}
$$
Lebih lanjut, didefinisikan pula $\mathbb{N}_{0} = \mathbb{N}\cup \{ 0 \}$. Didefinisikan relasi
$$
\begin{align*}
a>b & \iff a - b \in \mathbb{N} \\
a\le b & \iff b - a \in \mathbb{N}_{0}  \\
a\ge b & \iff a - b \in \mathbb{N}_{0} 
\end{align*}
$$
Lebih lanjut, $(\mathbb{N}, \le)$ membentuk *urutan parsial*.

---
## Bukti
Serupa dengan bukti [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Urutan Bilangan Real]]
### Refleksif
Ambil $a \in \mathbb{R}$. Jelas $a-a = 0 \in \mathbb{N}_{0}$. Maka $a \le a$. Terbukti $\le$ refleksif.

### Anti-simetri
Misalkan $a,b \in \mathbb{R}$ dengan $a \le b$ dan $b \le a$. Artinya $(a - b) \in \mathbb{N}_{0}$ dan $(b - a) \in \mathbb{N}_{0}$. Misalkan $c = (a - b)$. Perhatikan bahwa $c \in \mathbb{N} \cup \{  0 \}$ dan $-c \in \mathbb{N} \cup \{  0 \}$. Berdasarkan aksioma haruslah $a - b = c = 0$. Terbukti $a = b$. Berarti $\le$ bersifat antisimetri.

### Transitif
Misalkan $a,b, c \in \mathbb{R}$ dengan $a \le b$ dan $b \le c$. Artinya $(b-a), (c - a) \in \mathbb{N}_{0}$. Berdasarkan aksioma maka
$$
(c-a) = (c-b) + (b-a) \in \mathbb{N}_{0}
$$
Berarti $a \le c$. Terbukti $\le$ bersifat transitif.
***
## Definition Used 
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Urutan Parsial]]