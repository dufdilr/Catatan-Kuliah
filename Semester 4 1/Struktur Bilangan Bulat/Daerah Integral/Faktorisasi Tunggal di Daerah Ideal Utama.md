#Teorema 

Setiap Daerah Ideal Utama adalah Daerah Faktorisasi Tunggal

---

## Bukti

Misalkan $D$ Daerah Ideal Utama dan $a \in D$ tak nol dan bukan unit. Terdapat beberapa kasus
* Jika $a$ prima maka $a = 1 \cdot a$
* Jika $a$ takprima, maka ada $b_1, c_1$ takunit sehingga
    $$a = b_1 \cdot c_1$$
    Jika $b_1, c_1$ prima maka $a = b_1 \cdot c_1$. Jika $b_1$ tak prima maka ada $b_2, c_2$ tak unti sehingga
    $$b_1 = b_2 \cdot c_1$$
    Akan ditunjukkan bahwa dengan melakukan hal tersebut terus menerus akan tercapai $b_k = b_{k+1} c_{k+1}$ dimana keduanya prima.
    
    Andaikan ada barisan $b_1, b_2, b_3, \cdots$ yang tak prima. Misalkan $I_k = \langle b_k \rangle$. Perhatikan bahwa $b_{k+1} \mid b_k$ dan $b_{k+1} \nsim b_l$, artinya
    $$I_1 \subsetneq I_2 \subsetneq I_3 \subsetneq \cdots$$
    Berdasarkan [[Rantai Ideal Sejati|teorema]] $I_k$ pasti berhingga. Kontradiksi.
    
    Artinya $\{b_k\}$ pasti berhingga. Sehingga dapat dituliskan
    $$a = 1\cdot b_k \cdot c_k \cdot c_{k-1} \cdots c_1$$
    dengan $b_k, c_k, c_{k-1}, c_1$ semuanya prima.
Kemudian akan ditunjukkan ketunggalan. Misalkan
$$a = u \cdot p_1 \cdot p_2 \cdots p_n = v \cdot q_1 \cdot q_2 \cdots q_m$$
dengan $v$ unit dan $q_i$ prima. Tanpa mengurangi keumuman, misalkan $n \le m$.
Perhatikan bahwa
$$p_1 \mid v \cdot q_1 \cdot q_2 \cdots q_m$$
Karena $p_1$ prima maka $p_1 \mid q_{i_1}$. Artinya $q_{i_1} = u_1 \cdot p_1$. Berdasarkan [[Unsur Prima Daerah Ideal Utama|teorema]], $u_1$ unit. Artinya dapat dituliskan
$$
\begin{align*}
u \cdot p_1 \cdot p_2 \cdots p_n &= v \cdot u_1 \cdot p_1 \cdot q_1 \cdot q_2 \cdots \hat{q_{i_1}} \cdots q_m \\
u \cdot p_2 \cdots p_n &= v \cdot u_1 \cdot q_1 \cdot q_2 \cdots \hat{q_{i_1}} \cdots q_m
\end{align*}
$$
Kemudian, perhatikan bahwa
$$p_2 \mid q_1 \cdot q_2 \cdots \hat{q_{i_1}} \cdots q_m$$
Karena $p_2$ prima maka $p_2 \mid q_{i_2}$ dengan $i_2 \neq i_1$. Artinya $q_{i_2} = u_2 \cdot p_2$ dengan $u_2$ unit.
Hal tersebut dilakukan hingga $n$-kali sehingga didapatkan
$$u = v \cdot u_1 \cdot u_2 \cdots u_n \cdot q_{i_{n+1}} \cdot q_{i_{n+2}} \cdots q_{i_m}$$
dimana $q_{i_{n+1}},\ q_{i_{n+2}}, \ q_{i_m}$ adalah bilangan prima yang tersisa. Perhatikan bahwa ruas kiri unit. Agar ruas kanan unit, maka tidak mungkin ada bilangan prima yang tersisa. Artinya $\boxed {m = n}$ dan berlaku
$$u = v \cdot u_1 \cdot u_2 \cdots u_n$$
Lebih lanjut, perhatikan bahwa $q_{i_k} = u_k \cdot p_k, \quad \forall k \in [1, n]_{\mathbb{N}}$. Artinya $q_{i_k} \sim p_k$ dengan $\{i_1,i_2, \cdots i_n\}$ adalah permutasi-n.

***
## Definition Used 
 * [[Daerah Ideal Utama]]
 * [[Daerah Faktorisasi Tunggal]]
 * [[Ideal Sejati]]
 * [[Unsur Prima (Ring)]]
 * [[Unsur Unit (Ring)]]