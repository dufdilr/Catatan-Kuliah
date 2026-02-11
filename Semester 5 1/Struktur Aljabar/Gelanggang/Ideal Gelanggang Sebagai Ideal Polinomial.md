#Teorema 

Jika $R$ adalah gelanggang komutatif dan $I$ adalah ideal dari $R$ maka 
$$
I[x] := \{ i_0+i_{1}x+i_{2}x^2+\dots+i_nx^n \in R[x] \ | \ n \in \mathbb{N_0}, \text{ dan }\ i_0, i_1, \dots,i_n \in I \}
$$
membentuk ideal dari $R[x]$.

---
## Bukti
Berdasarkan [[Ideal Sebagai Subgelanggang|teorema]] maka $I$ adalah subgelanggang dari $R$. Berdasarkan [[Subgelanggang Sebagai Subgelanggang Polinomial]], maka $I[x]$ adalah subgelanggang dari $R[x]$. Maka $(I[x], +)$ adalah subgrup dari $(R[x], +)$.

Ambil $f(x) \in I[x]$ dan $g(x) \in R[x]$. Tulis
$$
f(x) = a_{0}+a_{1}x+a_{2}x^2+\dots \quad \text{dan} \quad g(x) = b_{0}+b_{1}x+b_{2}x^2 + \dots
$$
dengan $a_i \in I$ dan $b_j \in R$. Misalkan $h(x) = f(x)g(x) = c_{0} + c_{1}x + c_{2}x^2 + \dots$. Perhatikan bahwa
$$
c_k = \sum_{p = 0}^k a_p b_{k-p} = a_0b_k + a_1b_{k-1} + \dots + a_kb_0
$$
Perhatikan bahwa $I$ adalah ideal dari $R$. Karena $a_p \in I$ dan $b_{k-p} \in R$, maka $a_p b_{k-p} \in I$. Akibatnya
$$
c_k = \sum_{p = 0}^k \underbrace{a_p b_{k-p}}_{\in I} \in I
$$
Karena $c_k \in I$ untuk setiap $k \in \mathbb{N_0}$, maka $h(x) = f(x)g(x) \in I[x]$.

Berdasarkan [[Karakterisasi Ideal]] terbukti bahwa $I[x]$ membentuk ideal dari $R[x]$.

***
## Definition Used 
 * [[Ideal (Ring)]]
 * [[Gelanggang Polinomial]]
 * [[Subgelanggang]]