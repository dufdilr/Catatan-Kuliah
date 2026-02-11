#Definisi #Teorema 

Misalkan $A$ adalah gelanggang dan $I_{1}, I_{2}$ keduanya adalah ideal dari $A$. Maka
$$
I = I_{1} + I_{2} := \{ i_{1}+i_{2} \ | \ i_{1} \in I_{1}, i_{2} \in I_{2} \}
$$
juga merupakan ideal bagi $A$.

---
## Bukti
Jelas $0 \in I_{1}, 0\in I_{2}$. Karena $0 = 0 + 0$ maka $0 \in I_{1}+I_{2} \neq \emptyset$.

Lebih lanjut, ambil $x, y \in I_{1}+I_{2}$ dan $r \in A$. Perhatikan bahwa $x = x_{1} + x_{2}$ dan $y = y_{1}+y_{2}$ dengan $x_{1}, y_{1} \in I_{1}$ dan $x_{2}, y_{2} \in I_{2}$. Perhatikan bahwa
$$
\begin{align*}
x - y &= (x_{1} + y_{1}) - (x_{2} +y_{2}) = (x_{1}-y_{1}) + (x_{2} - y_{2}) \\
xr &= (x_{1}+x_{2})r = x_{1}r + x_{2}r \\
rx &= r(x_{1}+x_{2}) = rx_{1} + rx_{2}
\end{align*}
$$
Perhatikan bahwa $I_{1}$ dan $I_{2}$ ideal. Karena $x_{1}, y_{1} \in I_{1}$ dan $x_{2}, y_{2} \in I_{2}$ serta $r \in A$ maka $x_{1}-y_{1}, rx_{1}, x_{1}r \in I_{1}$ dan $x_{2}-y_{2}, rx_{2},x_{2}r \in I_{2}$. Artinya
$$
x-y, xr, rx \in I_{1}+I_{2}
$$
Berdasarkan [[Karakterisasi Ideal]] maka $I_{1}+I_{2}$ membentuk ideal dari $A$.

***
## Definition Used 
 * [[Gelanggang]]
 * [[Ideal (Ring)]]