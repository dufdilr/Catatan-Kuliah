#Teorema

**Teorema**

Untuk setiap bilangan asli $n > 1$ maka $n$ bilangan prima atau perkalian bilangan prima.

---
## Bukti

Misalkan ada bilangan asli $m >1$ tak prima dan bukan perkalian bilangan prima. Definisikan
$$A = \{ a \in \mathbb{N} \mid a>1, a \text{ bukan prima dan bukan perkalian bilangan prima}\}$$
Jelas $m \in A$. Maka $\emptyset \neq A \subseteq \mathbb{N}$. Berdasarkan [[Aksioma Urutan Sempurna]] terdapat unsur terkecil dari $A$, sebut saja $b$. Karena $b$ bukan prima maka ada $b' \in \mathbb{N}$ sehingga $(b, b') = d > 1$. 

Jelas $d \mid b$ sehingga dapat dituliskan $b = c \cdot d$ dengan $1 < c, d < b$. Artinya $c, d \notin A$. Berarti, $c, d$ adalah bilangan prima atau perkalian bilangan bilangan prima. Berarti $b = cd$ juga perkalian bilangan prima. 

Hal ini kontradiksi dengan pengandaian. Artinya, pengandaian salah. Terbukti bahwa setiap bilangan asli $n > 1$ maka $n$ bilangan prima atau perkalian bilangan prima.

***
## Definition Used:
* [[Bilangan Prima]]