#Teorema 

Misalkan $\emptyset \neq I \subseteq \mathbb{Z}$. $I$ adalah **Ideal Prima** dari $\mathbb{Z}$ jika dan hanya jika
$$
I = p \mathbb{Z} \quad\text{ atau } \quad I = \{ 0 \}
$$

---
## Bukti
### $\Rightarrow$
Misalkan $I$ adalah ideal prima dari $\mathbb{Z}$. Artinya $I$ adalah [[Subgelanggang Z]], maka $I = n \mathbb{Z}$ untuk suatu $n \in \mathbb{Z}$. 
* Jika $n = 0$ maka $I = 0 \mathbb{Z} = \{ 0 \}$
* Jika $n \neq 0$, ambil $x, y \in \mathbb{Z}$ sehingga $xy \in I$. Artinya $n \mid xy$. Karena $I$ prima maka $x \in I$ atau $y \in I$. Berdasarkan [[Karakterisasi Bilangan Prima]] maka $n$ adalah bilangan prima. Dengan kata lain 

### $\Leftarrow$
* Jika $I = \{ 0 \}$ maka jelas $I$ adalah [[Ideal Trivial]] dari $\mathbb{Z}$.
* Jika $I = p \mathbb{Z}$ dengan $p$ bilangan prima. Ambil $x, y \in \mathbb{Z}$ sehingga $p \mid xy$. Berdasarkan [[Karakterisasi Bilangan Prima]] maka $p \mid x$ atau $p \mid y$. Artinya $x \in p \mathbb{Z}$ atau $y \in p \mathbb{Z}$. Terbukti $I$ membentuk ideal.

***
## Definition Used 
 * [[Gelanggang Z]]
 * [[Ideal Prima]]
 * [[Ideal Trivial]]
 * [[Bilangan Prima]]
 * [[Keterbagian]]