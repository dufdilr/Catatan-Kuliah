#Teorema
Jika $a, b \in \mathbb{Z}$, tidak keduanya nol, maka ada bilangan asli **tunggal** $c$ sehingga $c = (a, b)$ dan
$$
c = sa + tb, \quad \text{untuk suatu } s, t \in \mathbb{Z}.
$$

---

## Bukti

Misalkan $a, b \in \mathbb{Z}$ dengan $a \neq 0$ atau $b \neq 0$. Tinjau himpunan semua kombinasi linear dari $a$ dan $b$:
$$W = \{sa + tb \mid s, t \in \mathbb{Z}\}$$
dan himpunan bagian dari $W$ yang berisi semua bilangan asli:
$$V = W \cap \mathbb{N}$$

Himpunan $V$ tidak kosong, karena $a^2 + b^2 = a(a) + b(b) \in W$, dan karena $a, b$ tidak keduanya nol, $a^2+b^2$ adalah bilangan asli, sehingga $a^2+b^2 \in V$.

Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]], himpunan $V$ memiliki elemen terkecil $c$. Karena $c \in V$, maka $c$ dapat ditulis sebagai:
$$c = s_1a + t_1b, \quad \text{untuk suatu } s_1, t_1 \in \mathbb{Z}.$$
Sekarang, akan kita tunjukkan bahwa $c = (a, b)$.

### 1. Menunjukkan $c$ adalah Pembagi Bersama
Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Algoritma Pembagian]], ada $q_1, r_1 \in \mathbb{Z}$ dengan $0 \le r_1 < c$ sehingga $a = q_1c + r_1$. Perhatikan bahwa
$$r_1 = a - q_1c = a - q_1(s_1a + t_1b) = (1-q_1s_1)a + (-q_1t_1)b$$
Maka $r_1 \in W$. Karena $r_1 < c$ sedangkan $c$ adalah elemen *terkecil* yang positif di $W$, maka $r_1\notin V$. 
Karena $r_1 \in W$ dan $r_1 \notin V$, maka haruslah $r_1 \le 0$. Karena $r_1 \ge 0$ dan $r_1 \le 0$ maka dapat disimpulkan $r_1 = 0$.
Perhatikan bahwa 
$$a = q_1c + 0 = q_{1}c$$Berarti $c \mid a$. Dengan argumen yang sama, dapat ditunjukkan bahwa $c \mid b$.
Jadi, $c$ adalah pembagi bersama dari $a$ dan $b$.

### 2. Menunjukkan $c$ adalah Pembagi Terbesar
Misalkan $d$ adalah sembarang pembagi bersama dari $a$ dan $b$ ($d \mid a$ dan $d \mid b$). Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|sifat kelinieran keterbagian]], $d$ harus membagi setiap kombinasi linear dari $a$ dan $b$. Maka:
$$d \mid (s_1a+t_1b)$$
Ini berarti $d \mid c$.
Karena $c$ adalah pembagi bersama dan setiap pembagi bersama lainnya ($d$) juga membagi $c$, maka $c$ terbukti merupakan FPB dari $a$ dan $b$. Jadi, $c = (a, b)$.

### 3. Menunjukkan Ketunggalan
Akan ditunjukkan bahwa FPB tunggal. Misalkan $c' = (a, b)$ adalah FPB lainnya.
* Karena $c$ adalah pembagi bersama ($c \mid a$ dan $c \mid b$) dan $c'$ adalah FPB, maka menurut definisi, $c \mid c'$.
* Sebaliknya, karena $c'$ adalah pembagi bersama ($c' \mid a$ dan $c' \mid b$) dan $c$ adalah FPB, maka $c' \mid c$.

Karena $c \mid c'$ dan $c' \mid c$, serta $c$ dan $c'$ keduanya adalah bilangan asli (positif), [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^d21346|maka]] satu-satunya kemungkinan adalah $c=c'$.
Maka, terbukti bahwa $(a, b)$ adalah tunggal. ■

***
## Definition Used:
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor Persekutuan Terbesar]]
