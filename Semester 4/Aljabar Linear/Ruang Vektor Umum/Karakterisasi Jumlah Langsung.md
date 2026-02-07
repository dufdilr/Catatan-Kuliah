#Teorema 

Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $V_1, V_2, ... , V_n$ adalah subruang dari $V$.  Berlaku $V_1 + V_2 + \cdots + V_n$ adalah **Jumlah Langsung** jika dan hanya jika berlaku 
"Jika $\mathbf{0} = v_{1} + v_{2} + \cdots + v_n$ dengan $v_i \in V_i$ maka $v_i = \mathbf{0}$ untuk setiap $i$"

---
## Bukti

### $\Rightarrow$
Misalkan $V_1 + V_2 + \cdots + V_n$ adalah jumlah langsung. Perhatikan bahwa $\mathbf{0} = \mathbf{0} + \mathbf{0} + \cdots + \mathbf{0}$. Lebih lanjut, misalkan $\mathbf{0} = v_{1} + v_{2} + \cdots + v_n$. Karena $V_1 + V_2 + \cdots + V_n$ adalah jumlah langsung maka haruslah $v_i = \mathbf{0}$ untuk setiap indeks $i$. Terbukti.
### $\Leftarrow$
Misalkan berlaku "Jika $\mathbf{0} = v_{1} + v_{2} + \cdots + v_n$ dengan $v_i \in V_i$ maka $v_i = \mathbf{0}$ untuk setiap $i$". Ambil $w \in V_1 + V_2 + \cdots + V_n$ dengan
$$
w = v_{1} + v_{2} + \cdots + v_n = v_{1}' + v_{2}' + \cdots + v_n'
$$adalah representasi dari $w$. Perhatikan bahwa
$$
\mathbf{0} = w - w =  v_{1} + v_{2} + \cdots + v_n - v_{1}' + v_{2}' + \cdots + v_n' = (v_{1} - v_{1}') + (v_{2} - v_{2}') + \cdots + (v_n - v_n')
$$
Berdasarkan hipotesa maka untuk setiap indeks $i$ berlaku $v_i - v_i' = \mathbf{0}$. Artinya berlaku $v_i = v_i'$. Artinya, representasi dari $w$ tunggal. Maka terbukti bahwa $V_1 + V_2 + \cdots + V_n$ adalah jumlah langsung.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Jumlah Subruang]]
 * [[Jumlah Langsung Subruang]]
