#Definisi 

Berdasarkan aksioma, misalkan $\mathbb{P} \subseteq \mathbb{R}$  adalah himpunan yang memenuhi aksioma urutan. Definisikan relasi 
$$
a < b \iff b-a \in \mathbb{P}
$$
Lebih lanjut, didefinisikan pula $\mathbb{P}_{0} = \mathbb{P}\cup \{ 0 \}$
$$
\begin{align*}
a>b & \iff a - b \in \mathbb{P} \\
a\le b & \iff b - a \in \mathbb{P}_{0}  \\
a\ge b & \iff a - b \in \mathbb{P}_{0} 
\end{align*}
$$
Lebih lanjut, $(\mathbb{R}, \le)$ membentuk *urutan parsial*

## Bukti Urutan Parsial
### Refleksif
Ambil $a \in \mathbb{R}$. Jelas $a-a = 0 \in \mathbb{P}_{0}$. Maka $a \le a$. Terbukti $\le$ refleksif.

### Anti-simetri
Misalkan $a,b \in \mathbb{R}$ dengan $a \le b$ dan $b \le a$. Artinya $(a - b) \in \mathbb{P}_{0}$ dan $(b - a) \in \mathbb{P}_{0}$. Misalkan $c = (a - b)$. Perhatikan bahwa $c \in \mathbb{P} \cup \{  0 \}$ dan $-c \in \mathbb{P} \cup \{  0 \}$. Berdasarkan aksioma haruslah $a - b = c = 0$. Terbukti $a = b$. Berarti $\le$ bersifat antisimetri.

### Transitif
Misalkan $a,b, c \in \mathbb{R}$ dengan $a \le b$ dan $b \le c$. Artinya $(b-a), (c - a) \in \mathbb{P}_{0}$. Berdasarkan aksioma maka
$$
(c-a) = (c-b) + (b-a) \in \mathbb{P}_{0}
$$
Berarti $a \le c$. Terbukti $\le$ bersifat transitif.

***

## Definition Used 
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Urutan Parsial]]