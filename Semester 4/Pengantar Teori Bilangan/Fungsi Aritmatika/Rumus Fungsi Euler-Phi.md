#Teorema 

Jika $n = p_{1}^{a_{1}}p_{2}^{a_{2}}\cdots p_k^{a_k}$ adalah [[Teorema Fundamental Aritmatika|Faktorisasi Prima]] dari $n$ maka
$$
\varphi(n) = \left(p_{1}^{a_{1}}-p_{1}^{a_{1}-1}\right)\left( p_{2}^{a_{2}}-p_{2}^{a_{2}-1} \right)  \cdots \left( p_k^{a_k}-p_k^{a_k-1} \right) 
$$

---
## Bukti

Karena $p_{1}, p_{2}, \dots, p_k$ adalah bilangan prima berbeda maka $(p_i^{a_i},p_j^{a_j}) = 1$ jika $i \neq j$. Berdasarkan [[Fungsi Euler-Phi Prima]] maka
$$
\varphi(p_i^{a_i}) = p_i^{a_i} - p_i^{a_i-1}
$$
Karena [[Multiplikatif Fungsi Euler-Phi]] maka
$$
\varphi(n) =\varphi(p_1^{a_1})\cdot \varphi p_{2}^{a_{2}} \cdots \varphi(p_k^{a_k}) = \left(p_{1}^{a_{1}}-p_{1}^{a_{1}-1}\right)\left( p_{2}^{a_{2}}-p_{2}^{a_{2}-1} \right)  \cdots \left( p_k^{a_k}-p_k^{a_k-1} \right) 
$$

***
## Definition Used 
 * [[Fungsi Euler-Phi]]
 * [[Fungsi Multiplikatif]]
 * [[Faktor Persekutuan Terbesar]]