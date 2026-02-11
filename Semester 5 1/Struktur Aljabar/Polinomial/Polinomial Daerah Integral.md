#Teorema 

Misalkan $R$ adalah daerah integral maka $R[x]$ juga membentuk daerah integral.

---
## Bukti
Misalkan $f(x) \in R[x]$ dengan $f(x) \neq 0$ dan $g(x) \in R[x]$ sehingga $f(x)g(x) = 0$. Andaikan $g(x) \neq 0$ maka tuliskan
$$
f(x) = a_{0}+a_{1}x+a_{2}x^2+\dots+a_nx^n \quad \text{dan} \quad g(x) = b_{0}+b_{1}x+b_{2}x^2 + b_mx^m
$$
dengan $b_m, a_n \neq 0$. Misalkan $f(x)g(x) = h(x) = c_0+c_{1}x + c_{2}x^2 + \dots$ Perhatikan bahwa
$$
c_k = \sum_{i+j = k}a_ib_j
$$
Artinya, koefisien utama dari $h$ yakni $c_{n+m} = a_nb_m$. Karena $h(x) = 0$ maka pastilah $a_nb_m = 0$. Karena $R$ adalah daerah integral maka $b_m = 0$, kontradiksi dengan koefisien utama tak-nol.

Terbukti $R[x]$ juga merupakan daerah integral.

***
## Definition Used 
 * [[Gelanggang Polinomial]]
 * [[Daerah Integral]]