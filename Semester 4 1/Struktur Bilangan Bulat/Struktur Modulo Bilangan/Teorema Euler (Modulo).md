#Teorema 
Jika $(a, n) = 1$ maka 
$$a^{\varphi(n)} \equiv 1 \pmod{n}$$

---
## Bukti
Perhatikan [[Teorema Relatif Prima dengan Un|bahwa]] $U_n = a \cdot U_n$. Artinya, hasil perkalian semua elemen di $U_n$ sama dengan hasil perkalian semua elemen di $a \cdot U_n$, dengan kata lain
$$
\begin{align*}
\prod_{u \in U_n} u &= \prod_{u \in a \cdot U_n} u 
= \prod_{x \in U_n} (a \cdot x) \\
\\
&= \left( \prod_{x \in U_n} a \right) \left( \prod_{x \in U_n} x \right) \\
\\
&= a^{|U_n|} \prod_{x \in U_n} x \\
\\
&= a^{\varphi(n)} \prod_{u \in U_n} u
\end{align*}
$$
Karena setiap elemen di $U_n$ memiliki invers, kita dapat membatalkan $\prod_{u \in U_n} u$ dari kedua sisi. Sehingga, kita peroleh :
$$1 \equiv a^{\varphi(n)} \pmod{n}$$

***
## Definition Used:
* [[Himpunan Un]]