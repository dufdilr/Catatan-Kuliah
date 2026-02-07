#Teorema 
Misalkan $a, b, c \in \mathbb{P}$ maka berlaku
1. **Transitif:** Jika $a > b$ dan $b > c$ maka $a > c$.
2. **Penjumlahan:** Jika $a > b$ maka $a + c > b + c$
3. **Perkalian Positif:** Jika $a > b$ dan $c > 0$ maka $ac > bc$
4. **Perkalian Negatif:** Jika $a > b$ dan $c < 0$ maka $ac < bc$

---
## Bukti
### 1.
Karena $a > b$ dan $b > c$ maka $a - b \in \mathbb{P}$ dan $b - c \in \mathbb{P}$. Berdasarkan [[Aksioma Bilangan Real#^d869f3|Aksioma Bilangan Real]] maka 
$$
(a-b) + (b - c) = a - c \in \mathbb{P}
$$
Terbukti $a > c$
### 2.
Karena $a > b$ maka $a - b \in \mathbb{P}$. Perhatikan bahwa
$$
a - b = a-b + c - c = (a + c) - (b + c) \in \mathbb{P}
$$
Maka $a+c > b+c$
### 3.
Karena $a > b$ dan $c > 0$ maka $a - b, c\in \mathbb{P}$. Berdasarkan [[Aksioma Bilangan Real#^b8b0f5|Ketertutupan Perkalian]] maka
$$
c(a - b) = ac - bc \in \mathbb{P}
$$
Maka $ac > bc$
### 4.
Karena $a>b$ dan $c > 0$ maka $a-b, -c \in \mathbb{P}$. Perhatikan bahwa
$$
(-c)(a - b) = bc - ac \in \mathbb{P}
$$
Maka $bc > ac$.

***
## Definition Used 
 * [[Aksioma Bilangan Real]]
 * [[Urutan Bilangan Real]]