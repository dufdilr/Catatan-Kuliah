#Teorema 

Misalkan $A$ adalah suatu gelanggang dan $I$ adalah ideal dari $A$. Maka, terdapat gelanggang $B$ dan homomorfisma gelanggang $f:A \to B$ sehingga $\mathrm{Inti}(f) = I$.

---
## Bukti
Karena $I$ adalah ideal dari $A$ maka $A/I$ membentuk [[Gelanggang Hasil Bagi]]. Tinjau pemetaan
$$
f:A \to A/I
$$
dengan $f(a) = a+I$. 

Ambil $a_{1}, a_{2} \in A$. Perhatikan bahwa
$$
\begin{align*}
f(a_{1}+a_{2}) &= (a_{1}+a_{2})I = (a_{1}+I) + (a_{2}+I) \\
&= f(a_{1})+ f(a_{2}) \\
f(a_{1}a_{2}) &= (a_{1}a_{2})+I = (a_{1}+I) \cdot(a_{2}+I) \\
&= f(a_{1})f(a_{2})
\end{align*}
$$
Maka $f$ adalah homomorfisma gelanggang.

Lebih lanjut, berdasarkan [[Kesamaan Koset]] maka
$$
\begin{align*}
a \in \mathrm{Inti}(f) &\ \iff f(a) = I \\
&\ \iff a+I = I \\
&\ \iff a \in I
\end{align*}
$$
Maka $\mathrm{Inti}(f) = I$, terbukti.

***
## Definition Used 
 * [[Gelanggang]]
 * [[Homomorfisma (Ring)]]
 * [[Kesamaan Koset]]
 * [[Inti Homomorfisma Gelanggang]]
 * [[Gelanggang Hasil Bagi]]