#Definisi 
Misalkan $R$ adalah gelanggang komutatif. Operasi penjumlahan dan perkalian pada $R[x]$ didefinisikan sebagai berikut. Misalkan $f(x) = \sum a_{i}x^{i}$ dan $g(x) = \sum b_{i}x^{i}$:
1. **Penjumlahan Polinomial**
$$
f(x) + g(x) = \sum_{i=0}^{\infty} (a_{i} + b_{i})x^{i}
$$
2. **Perkalian Polinomial**
Definisikan $f(x) \cdot g(x) = h(x) = \sum_{i=0}^{\infty} c_ix^i$ dengan
$$
\begin{align*}
c_i = \sum_{j=0}^{i} a_{j}b_{i-j}
\end{align*}
$$
3. **Perkalian Skalar** 
	Untuk sebarang skalar $c \in R$, perkalian skalar $c \cdot f(x)$ didefinisikan sebagai: $$ c \cdot f(x) = \sum_{i=0}^{n} (c a_{i})x^{i} $$
4. **Komposisi Polinomial** 
	Komposisi $f(x)$ dengan $g(x)$, dinotasikan sebagai $(f \circ g)(x)$ atau $f(g(x))$, didefinisikan dengan mensubstitusi variabel $x$ pada $f(x)$ dengan polinomial $g(x)$: $$ (f \circ g)(x) = \sum_{i=0}^{n} a_{i}(g(x))^{i} = a_{0} + a_{1}g(x) + a_{2}(g(x))^{2} + \dots + a_{n}(g(x))^{n} $$

***
## Definition Used 
 * [[Polinomial]]
 * [[Gelanggang Komutatif]]