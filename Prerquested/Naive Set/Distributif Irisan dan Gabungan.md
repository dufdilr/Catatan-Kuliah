#Teorema 

Misalkan $A, B, C$ himpunan. Maka berlaku
* 
$$
A \cap (B \cup C) = (A \cap B) \cup (A \cap C)
$$
* 
$$
A \cup (B \cap C) = (A \cup B) \cap (A \cup C)
$$

## Bukti
### Sifat Pertama
#### $\subseteq$
Ambil $x \in A \cap (B \cup C)$. Maka $x \in A$ dan $x \in B \cup C$. Karena $x \in B \cup C$ maka $x \in B$ atau $x \in C$. 

Tanpa mengurangi keumuman, misalkan $x \in B$. Karena $x \in A$ dan $x \in B$ maka $x \in A \cap B$. Sehingga $x \in (A \cap B) \cup (A \cap C)$. Kasus $x \in C$ didapatkan hasil yang sama. Terbukti bahwa
$$
A \cap (B \cup C) \subseteq (A \cap B) \cup (A \cap C)
$$

#### $\supseteq$
Ambil $x \in  (A \cap B) \cup (A \cap C)$. Artinya $(A \cap B)$ atau $(A \cap C)$. 

Tanpa mengurangi keumuman, misalkan $x \in A \cap B$. Artinya $x \in A$ dan $x \in B$. Karena $x \in B$ maka $x \in B \cup C$. Karena $x \in A$ dan $x \in B \cup C$ maka $x \in A \cap (B \cup C)$. Kasus $x \in A \cap C$ didapatkan hasil yang sama. Terbukti bahwa
$$
A \cap (B \cup C) \supseteq (A \cap B) \cup (A \cap C)
$$

Karena $A \cap (B \cup C) \subseteq (A \cap B) \cup (A \cap C)$ dan $A \cap (B \cup C) \supseteq (A \cap B) \cup (A \cap C)$ maka terbukti
$$
A \cap (B \cup C) = (A \cap B) \cup (A \cap C)
$$

### Sifat Kedua
Berdasarkan [[Sifat Disjungsi dan Konjungsi]] didapatkan
$$
\begin{align*}
x \in A \cup (B \cap C) & \iff x \in A \text{ atau } x \in B \cap C \\
& \iff x \in A \text{ atau } (x \in B \text{ dan } x \in C) \\
& \iff (x \in A \text{ atau } x \in B) \ \text{ dan } \ (x \in A \text{ atau } x \in C) \\
& \iff x \in A \cup B \ \text{ dan }  \ x \in A \cup C \\
& \iff x \in (A \cup B) \cap(A \cup C)
\end{align*}
$$
Terbukti 
$$
A \cup (B \cap C) = (A \cup B) \cap (A \cup C)
$$

***
## Definition Used
* [[Himpunan]]
* [[Irisan Gabungan dan Komplemen Himpunan]]
