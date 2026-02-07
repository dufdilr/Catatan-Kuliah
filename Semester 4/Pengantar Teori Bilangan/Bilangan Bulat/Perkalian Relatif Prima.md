#Teorema
Jika $a, b, c$ bilangan asli berlaku
    $$(a, c) = 1 \text{ dan } (b, c) = 1 \quad 
    \iff \quad (ab, c) = 1$$
---
## Bukti

* **($\Rightarrow$):**
    Jelas $1 \mid ab$ dan $1 \mid c$. Misalkan $d \mid ab$ dan $d \mid c$.
    Berdasarkan [[Teorema Bezout|teorema]], karena $(a,c)=1$, maka $\exists \ s_1, t_1 \in \mathbb{Z}$ sehingga
    $$as_1 + ct_1 = 1$$
    Kalikan kedua ruas dengan $b$:
    $$abs_1 + bct_1 = b$$
    Karena $d \mid ab$ dan $d \mid c$, maka $d$ harus membagi [[Sifat Keterbagian#^ab6a93|kombinasi linear]] di atas, sehingga $d \mid (abs_1 + bct_1)$. Ini berarti $d \mid b$.
    
    Sekarang kita punya $d \mid b$ dan $d \mid c$. Karena diketahui $(b, c) = 1$, maka setiap pembagi bersama dari $b$ dan $c$ haruslah membagi 1. Jadi, $d \mid 1$.
    
    Karena setiap pembagi bersama $d$ dari $ab$ dan $c$ juga membagi 1, maka terbukti $(ab, c) = 1$.

* **($\Leftarrow$):**
    Diketahui $(ab,c)=1$. Berdasarkan [[Teorema Bezout|teorema]], maka $\exists \ s_1, t_1 \in \mathbb{Z}$ sehingga
    $$abs_1 + ct_1 = 1$$
    Persamaan ini dapat ditulis sebagai:
    $$a(bs_1) + c(t_1) = 1$$
    Karena ada kombinasi linear dari $a$ dan $c$ yang sama dengan 1, [[Karakterisasi Relatif Prima|maka]] $(a, c) = 1$.
    
    Persamaan yang sama juga dapat ditulis sebagai:
    $$b(as_1) + c(t_1) = 1$$
    Karena ada kombinasi linear dari $b$ dan $c$ yang sama dengan 1, [[Karakterisasi Relatif Prima|maka]] $(b, c) = 1$.
***
## Definition Used:
* [[Faktor Persekutuan Terbesar]]