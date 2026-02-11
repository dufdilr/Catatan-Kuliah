#Teorema

Misalkan $G$ suatu graf. $G$ adalah pohon jika dan hanya jika untuk setiap $u, v \in V(G)$ terdapat $(u, v)-$path secara tunggal.

---
## Bukti
### $\Rightarrow$
Misalkan $G$ suatu pohon dan $u, v \in V(G)$. Karena $G$ pohon [[Pohon Graf Sederhana|maka]] $G$ adalah graf sederhana dan terhubung. Karena $G$ [[Graf Terhubung|terhubung]] maka terdapat $(u, v)-$path. Akan ditunjukkan ketunggalan.

Andaikan terdapat $(u, v)-$path yakni $P_1 = u \ v_{1}\ v_{2} \cdots\ v_{k-1}\ v$ dan $P_2 =  u \ w_{1}\ w_{2} \cdots\ w_{l-1}\ v$ dengan $P_1 \neq P_2$. Karena $P_{1} \neq P_{2}$ maka terdapat $w \in P_1 \backslash P_2$ atau $w \in P_2 \backslash P_1$. Tanpa mengurangi keumuman misalkan terdapat $w \in P_1 \backslash P_2$. Tinjau himpunan
$$N = \{n\in \mathbb{N}:v_{n} \in P_{1} \backslash P_{2}\}$$
Perhatikan bahwa $N \neq \emptyset$ dan $N\subseteq \mathbb{N}$, maka berdasarkan [[Aksioma Urutan Sempurna]] terdapat unsur terkecil $i$. Lebih lanjut, karena $i - 1 < i$ maka $i - 1 \notin N$. Berarti, $v_{i-1} \in P_2$. Misalkan $v_{i-1} = w_j$. Tinjau himpunan
$$N_{2} = \{ n \in \mathbb{N} : n > i, v_{n} \in P_{2} \}$$
dengan $v_k = v$ maka jelas $k \in N_2$. Berarti $N_2 \neq \emptyset$ dan $N_2 \subseteq \mathbb{N}$. Berdasarkan [[Aksioma Urutan Sempurna]], terdapat unsur terkecil $p$. Perhatikan bahwa $v_p \in P_2$. Misalkan $v_p = w_q$. Konstruksi
$$
C = v_{i-1}\ v_{i} \ v_{i+1} \ \cdots \ v_{p-1} \ v_{p} \ w_{q-1} \ w_{q-2} \ \cdots \ w_{j + 1}\ w_{j}
$$
Perhatikan bahwa $C$ membentuk siklus di $G$ maka $G$ bukan pohon, kontradiksi dengan premis awal. Artinya pengandaian salah. Terbukti untuk setiap $u, v \in V(G)$ terdapat $(u, v)-$path secara tunggal.

### $\Leftarrow$
Misalkan $G$ suatu graf sehingga untuk setiap $u, v \in V(G)$ terdapat $(u, v)-$path secara tunggal. Dapat disimpulkan $G$ terhubung. Lebih lanjut, akan ditunjukkan $G$ [[Graf Asiklik|asiklik]].

Andaikan $G$ mengandung siklik
$$
C = u\ v_{1}\ v_{2} \ \cdots \ v_{k} \ u
$$
Perhatikan bahwa $P_{1} = u \ v_{1}$ dan $P_2 = u \ v_{k} \ v_{k-1} \ \cdots \ v_{2} \ v_{1}$ keduanya adalah $(u, v_1)-$path. Namun jelas $P_1 \neq P_2$. Hal ini kontradiksi dengan premis awal. Artinya pengandaian salah. Terbukti $G$ asiklik.

Karena $G$ terhubung dan asiklik maka $G$ adalah pohon.

***
## Definition Used
* [[Pohon (Graf)]]
* [[Path (Graf)]]
* [[Graf Terhubung]]
* [[Graf Asiklik]]
