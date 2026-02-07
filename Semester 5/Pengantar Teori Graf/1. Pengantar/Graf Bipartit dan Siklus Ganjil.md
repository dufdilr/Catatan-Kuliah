#Teorema 

Misalkan $G$ suatu graf. $G$ adalah graf bipartit jika dan hanya jika $G$ tidak mengandung siklus dengan panjang ganjil.

---
## Bukti
### Hanya jika
Misalkan $G$ suatu graf bipartit dengan partisi $(X, Y)$. 

Andaikan $G$ mengandung siklus ganjil $C = v_{0}\ v_{1}\ v_{2} \ v_{3} \cdots v_{n}$ dengan $v_0 = v_n$ dan $n$ suatu bilangan ganjil. Tanpa mengurangi keumuman, misalkan $v_0 \in X$. Karena $v_0 \in X$ dan $v_0$ bertetangga dengan $v_1$ maka $v_1 \in Y$. Karena $v_1 \in Y$ dan $v_1$ bertetangga dengan $v_2$ maka $v_2 \in X$. Lebih lanjut, untuk setiap indeks $i$ berlaku
$$
v_{i} \in X \text{ jika $i$ genap dan } \quad v_{i} \in Y \text{ jika i ganjil}
$$
Perhatikan bahwa $n$ bilangan ganjil. Artinya $v_n \in Y$. Namun, $v_n = v_0 \in X$. Berarti $\{ v_{0} \}\subseteq X\cap Y \neq \emptyset$. Kontradiksi dengan fakta bahwa $X$ dan $Y$ partisi dari $V$.

Terbukti jika $G$ bipartit maka $G$ tidak mengandung siklus dengan panjang ganjil.

### Jika
Misalkan $G$ suatu graf yang tidak mengandung siklus dengan panjang ganjil. Pilih sembarang $u \in V(G)$. Konstruksi himpunan
$$
\begin{align*}
X &:= \{v \in V(G) : d(u, v) \text{ ganjil} \} \\
Y &:= \{v \in V(G) : d(u, v) \text{ genap} \}
\end{align*}
$$
Jelas $X, Y$ adalah partisi dari $G$. Lebih lanjut, akan ditunjukkan $G$ bipartit dengan partisi $(X, Y)$.

Ambil $x_1, x_2 \in X$. Akan ditunjukkan $x_1$ dan $x_2$ tidak bertetangga. Andaikan $x_1, x_2$ bertetangga dengan sisi penghubung $e_0$.
Misalkan $P_1 = x_{1}\ e_{1} \ v_{1}\ e_{2}\ v_{2} \cdots\ v_{k-1}\ e_{k}\ u$ dan $P_2 = x_{2}\ f_{1} \ w_{1}\ f_{2}\ w_{2} \cdots\ w_{l-1}\ f_{l}\ u$ berturut-turut adalah $(x_1, u)-$path dan $(x_2, u)-$path terpendek. Misalkan $v_k = w_l = u$. Tinjau himpunan
$$
N := \{ i : v_{i} \in P_{2} \}
$$
Jelas $v_k = u \in P_2$ maka $k \in N$ sehingga $N \neq \emptyset$. Berdasarkan [[Aksioma Urutan Sempurna]], terdapat indeks terkecil $n \in N$. Misalkan $v_n = w_m$. Konstruksi siklus
$$
C = x_{1}\ e_{1} \ v_{1}\ e_{2}\ v_{2} \cdots\ v_{n-1}\ e_{n}\ v_{n} \ f_{m-1} \ w_{m-1} \ \cdots\ w_{2}\ f_{2}\ w_{1}\ f_{1} \ x_{2} \ e_{0} x_{1}
$$
Perhatikan bahwa panjang $C$ adalah $m + n + 1$.  Karena $x_1$ dan $x_2$ berada di partisi yang sama, maka paritas dari $n$ dan $m$ haruslah sama. Berarti $m + n + 1$ ganjil. Dengan kata lain, $C$ adalah siklus dengan panjang ganjil. Kontradiksi dengan asumsi awal soal. Maka pengandaian salah. 

Terbukti untuk setiap $x_1, x_2 \in X$, $x_1$ dan $x_2$ tidak bertetangga. Bukti serupa dapat ditunjukkan untuk partisi $Y$. Terbukti $G$ adalah graf bipartit dengan partisi $(X, Y)$.
***
## Definition Used
* [[Graf]]
* [[Graf Bipartit]]
* [[Siklus (Graf)]]
* [[Tetangga dan Insiden]]
