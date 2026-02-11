#Teorema 

Misalkan $\emptyset \subseteq A \subseteq \mathbb{R}$. Jika $A$ terbatas di bawah maka $A$ memiliki infimum. Lebih lanjut, jika $A$ terbatas di atas maka $A$ memiliki supremum.

---
## Bukti

Pernyataan pertama benar berdasarkan [[Aksioma Bilangan Real#^ad636f|Aksioma Kelengkapan Bilangan Real]]. 

Lebih lanjut, misalkan $A$ terbatas di atas. Maka terdapat $u \in \mathbb{R}$ sehingga untuk setiap $a \in A$ berlaku $u \ge a$. Tinjau $B := \{-a \ | \ a \in A\}$. Perhatikan bahwa untuk setiap $b \in B: \ b = -a$ dengan $a \in A$.
$$
a \le u \quad\implies\quad b = -a \ge -u
$$
Maka $-u$ adalah batas bawah dari $B$. Berdasarkan [[Aksioma Bilangan Real#^ad636f|Aksioma Kelengkapan]], maka $B$ memiliki infimum, sebut $v$. Akan ditunjukkan $-v$ adalah supremum dari $A$.

Ambil $a \in A$. Perhatikan bahwa $-a \in B$ maka
$$
-a \ge v \quad\implies\quad a \le -v
$$
Dapat disimpulkan $-v$ adalah batas atas dari $A$. Lebih lanjut, misalkan $w$ adalah batas atas dari $A$. Serupa dengan yang telah ditunjukkan, maka $-w$ juga batas bawah dari $B$. Karena $v$ adalah infimum dari $B$ maka
$$
-w \le v \quad\implies\quad w \ge -v
$$
Terbukti $-v$ adalah batas atas terkecil. Maka $A$ memiliki supremum.

***
## Definition Used 
 * [[Aksioma Bilangan Real]]
 * [[Himpunan Terbatas di Atas]]
 * [[Himpunan Terbatas di Bawah]]
 * [[Infimum]]
 * [[Supremum]]
