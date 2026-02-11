#Teorema

Misalkan $a, n \in \mathbb{N}$. Berlaku $a \cdot U_n = U_n$ jika dan hanya jika $(a, n) = 1$.

---
## Bukti

### $\Rightarrow$
Misalkan $a \cdot U_n = U_n$. Andaikan $(a, n) = d > 1$. Ambil $[x]_{n} \in a \cdot U_n$, maka $[x]_{n} = [ak]_{n}$ dengan $(a, k) = 1$. Per definisi, $d \mid a$ dan $a \mid x$ maka $d \mid x$, namun jelas $d \mid n$. Artinya, $d \mid (n, x)$ sehingga $(n, x) > 1$. Berarti $[x]_{n} \not\in U_n$, kontradiksi dengan $a \cdot U_n = U_n$.

Maka, pengandaian salah. Terbukti, $(a, n) = 1$.
### $\Leftarrow$
Misalkan $(a, n) = 1$.

* **($\subseteq$):**
    Ambil $[x]_n \in U_n$. Karena $(x,n)=1$ dan $(a,n)=1$, maka $(ax, n) = 1$. Artinya $a \cdot [x]_n = [ax]_n \in U_n$. Berarti $a \cdot U_n \subseteq U_n$.

* **($\supseteq$):**
    Ambil $[x]_n \in U_n$. Karena $(a, n) = 1$ maka $[a]_n \in U_n$. Berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Invers Perkalian Zn|teorema]], maka ada $[b]_n$ sehingga $[a]_n \cdot [b]_n = [1]_n$.
    
    Perhatikan bahwa $[x]_n = [1]_n \cdot [x]_n = ([a]_n \cdot [b]_n) \cdot [x]_n = [a]_n \cdot ([b]_n \cdot [x]_n) = [a]_n \cdot [bx]_n$.
    Karena $[x]_n \in U_n$ dan $[b]_n \in U_n$, maka $[bx]_n \in U_n$.
    
    Jadi, kita bisa menulis $[x]_n$ sebagai $a \cdot [bx]_n$, yang merupakan elemen dari $a \cdot U_n$. Ini berarti $U_n \subseteq a \cdot U_n$.

Karena kedua himpunan saling termuat satu sama lain, dapat disimpulkan $a \cdot U_n = U_n$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Grup Perkalian Un]]