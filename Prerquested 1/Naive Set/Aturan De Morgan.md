#Teorema 

Misalkan $A, B, C$ adalah himpunan. Maka berlaku
* 
$$
A \backslash(B \cup C) = (A \backslash B) \cap (A \backslash C)
$$
* $$
A \backslash(B \cap C) = (A \backslash B) \cup (A \backslash C)
$$
## Bukti
### Bagian Pertama
Berdasarkan [[Sifat Disjungsi dan Konjungsi]] didapatkan
$$
\begin{align*}
x \in A \backslash(B \cup C) &\iff x \in A \ \text{ dan } x \notin B \cup C \\
&\iff x \in A \ \text{ dan } \ (x \notin B \text{ dan } x \notin C) \\
& \iff (x \in A \text{ dan } x \notin B)\ \text{ dan }\ (x \in A \text{ dan } x \notin C) \\
& \iff x \in A \backslash B\ \text{ dan }\ x \in A \backslash C \\
& \iff x \in (A \backslash B) \cap (A \backslash C)
\end{align*}
$$
Terbukti 
$$
A \backslash(B \cup C) = (A \backslash B) \cap (A \backslash C)
$$

### Bagian Kedua
Berdasarkan [[Sifat Disjungsi dan Konjungsi]] didapatkan
$$
\begin{align*}
x \in A \backslash(B \cap C) &\iff x \in A \ \text{ dan } x \notin B \cap C \\
&\iff x \in A \ \text{ dan } \ (x \notin B \text{ atau } x \notin C) \\
& \iff (x \in A \text{ dan } x \notin B)\ \text{ atau }\ (x \in A \text{ dan } x \notin C) \\
& \iff x \in A \backslash B\ \text{ atau }\ x \in A \backslash C \\
& \iff x \in (A \backslash B) \cup (A \backslash C)
\end{align*}
$$
Terbukti 
$$
A \backslash(B \cap C) = (A \backslash B) \cup (A \backslash C)
$$

***
## Definition Used
* [[Buat Backup/Prerquested 1/Naive Set/Himpunan]]
* [[Buat Backup/Prerquested 1/Naive Set/Irisan Gabungan dan Komplemen Himpunan]]

