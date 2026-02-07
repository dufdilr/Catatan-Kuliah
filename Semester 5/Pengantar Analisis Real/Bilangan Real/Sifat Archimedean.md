#Teorema 

Untuk setiap bilangan real $x, y \in \mathbb{R}$ dengan $x > 0$ terdapat $M \in \mathbb{N}$ sehingga $Mx > y$.

## Bukti

Andaikan terdapat $x, y\in \mathbb{R}$ dengan $x > 0$ sehingga untuk setiap $M \in \mathbb{N}$ berlaku $Mx \le y$. Tinjau
$$
A := \{ nx : x\in \mathbb{N} \}
$$
Berdasarkan pengandaian maka $y$ batas atas dari $A$. Berdasarkan [[Aksioma Bilangan Real#^ad636f|aksioma kelengkapan]] maka terdapat supremum dari $A$. Misalkan $a = \sup(A)$. Karena $x > 0$, berdasarkan definisi supremum maka $a - x$ bukan batas atas dari $A$. Berarti terdapat $mx \in A$ dengan
$$
mx > a-x \quad\Rightarrow \quad (m + 1)x > a
$$
Perhatikan bahwa $(m + 1) x \in A$, kontradiksi dengan $a$ supremum dari $A$. Maka pengandaian salah.

Terbukti.

***
## Definition Used 
 * [[Aksioma Bilangan Real]]
 * [[Bilangan Asli]]
 * [[Urutan Bilangan Real]]
 * [[Supremum]]
 