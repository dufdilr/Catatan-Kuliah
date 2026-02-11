#Teorema 

**Teorema (Teorema Fundamental Aritmetika)**

Untuk setiap bilangan asli $n>1$ dapat dituliskan sebagai
$$n = p_1^{a_1} \cdot p_2^{a_2} \cdot p_3^{a_3} \cdots p_k^{a_k}$$
dengan $p_i$ bilangan prima dan $a_i$ bilangan asli secara **tunggal**.

---
## Bukti

Sebelumnya telah ditunjukkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Dekomposisi Prima|keberadaan dekomposisi prima]]. Akan dibuktikan ketunggalannya. 

Andaikan terdapat bilangan asli $m>1$ sehingga dapat dituliskan sebagai perkalian bilangan prima secara tidak tunggal. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]], misalkan $m_0$ adalah bilangan asli terkecil yang memenuhi, maka dapat dituliskan
$$m_0 = p_1^{a_1} p_2^{a_2} \cdots p_k^{a_k} = q_1^{b_1} q_2^{b_2} \cdots q_l^{b_l}$$
dengan $1< p_1 < p_2 < \cdots$, $1< q_1 < q_2 < \cdots$ dan $a_i, b_j$ adalah bilangan asli. Perhatikan bahwa 
$$p_1 \mid q_1^{b_1} q_2^{b_2} \cdots q_l^{b_l}$$
maka $p_1 \mid q_i$ untuk suatu $i \in [1, l]_{\mathbb{N}}$. Karena $p_1$ dan $q_i$ prima dan $p_1 \mid q_i$ maka $p_1 = q_i$. 

Dengan argumen serupa maka $q_1 = p_j$ untuk suatu $j\in [1, k]_{\mathbb{N}}$. Perhatikan bahwa
$$p_1 \le p_j = q_1 \le q_i = p_1$$
Artinya $p_1 = q_1$. Pandang
$$m_1 = \frac{m_0}{p_1} = p_1^{a_1-1} p_2^{a_2} \cdots p_k^{a_k} = q_1^{b_1-1} q_2^{b_2} \cdots q_l^{b_l}$$
Perhatikan bahwa $m_1 < m_0$. Artinya, $m_1$ dapat dituliskan sebagai perkalian bilangan prima secara tunggal. Berarti $k = l, \ p_i = q_i, \ a_i = b_i$ untuk setiap indeks $i$. Ini berarti faktorisasi $m_0$ juga merupakan perkalian bilangan prima secara tunggal. Maka, terjadi kontradiksi dengan asumsi awal.

***
## Definition Used:
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]