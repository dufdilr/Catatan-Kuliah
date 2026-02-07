#Teorema 

Misalkan $P$ suatu peluang pada $\mathcal{A}$. Maka berlaku:
* Untuk setiap $A \in \mathcal{A}$ berlaku $P(A^C) = 1 - P(A)$
* Jika $A \subseteq B$ maka $P(A) \le P(B)$
* $P(A \cup B) = P(A) + P(B) - P(A \cap B)$

## Bukti
### Sifat Pertama
Misalkan $A \in \mathcal{A}$. Perhatikan bahwa $A \cup A^C = S$ dan $A \cap A^C = \emptyset$. Berdasarkan [[Aksioma Peluang#^1c71b4|aksioma]] berlaku
$$P(A \cup A^C) = P(A) + P(A^C)$$
Berdasarkan [[Aksioma Peluang#^cdcec8|aksioma]] maka $P(A\cup A^C) = P(S) = 1$. Akibatnya
$$P(A^C) = 1 - P(A) \quad \blacksquare$$
### Sifat Kedua
Misalkan $A \subseteq B$. Artinya $B = A \cup (B/A)$. Perhatikan bahwa $A \cup (B/A) = \emptyset$. Berdasarkan [[Aksioma Peluang#^1c71b4|aksioma]] berlaku
$$P(B) = P(A \cup (B/A)) = P(A) + P(B/A)$$
Berdasarkan [[Aksioma Peluang#^44e1c0|aksioma]] maka $P(B/A) \ge 0$. Akibatnya
$$P(B) \ge P(A) \quad \blacksquare$$
### Sifat Ketiga
Misalkan $A, B \in \mathcal{A}$. Perhatikan bahwa
$$
\begin{align*}
P(A \cup B) &= P((A\backslash B) \cup (B\backslash A) \cup (A \cap B)) \\
&= P(A\backslash B) + P(B\backslash A) + P(A \cap B) \\
&=(P(A\backslash B)+P(A \cap B)) + (P(B\backslash A) + P(A \cap B)) - P(A \cap B) \\
&=P((A\backslash B)\cup(A \cap B)) + P((B\backslash A) \cup (A \cap B)) - P(A \cap B) \\
&= P(A) + P(B) - P(A \cap B) \quad \blacksquare
\end{align*}
$$

***
## Definition Used:
* [[Aksioma Peluang]]
* [[Aljabar Sigma]]
* [[Himpunan]]