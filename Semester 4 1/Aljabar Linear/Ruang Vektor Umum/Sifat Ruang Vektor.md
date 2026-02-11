#Teorema

Misalkan $V$ adalah ruang vektor atas lapangan $\mathbb{F}$. Maka berlaku
1. **Ketunggalan Identitas Penjumlahan** 
2. **Ketunggalan Inverse Penjumlahan** ^c6107a
3. **Perkalian dengan Nol** $\forall a \in \mathbb{F}, \ {v} \in V: \ a{v} = \mathbf{0} \quad \iff \quad a = 0 \text{ atau } {v} = \mathbf{0}$ ^fb9b94
4. **Perkalian Inverse Penjumlahan** $\forall {v} \in V: \ (-1){v} =  {-v}$
5. **Inverse dari Inverse** $\forall {v} \in V: \ -\left(-{v}\right) = {v}$

## Bukti
### 1.
Misalkan $\mathbf{0},\ \mathbf{0'}$ adalah identitas penjumlahan pada $V$ maka berlaku
$$
\mathbf{0} = \mathbf{0} + \mathbf{0'} = \mathbf{0'}
$$

### 2. 
Misalkan ${v} \in V$ dan ${u}, {u'}$ adalah inverse penjumlahan dari ${v}$ maka
$$
{u} = {u} + \mathbf{0} = {u}+ {v} + {u'} = \mathbf{0} + {u'}= {u'}
$$

### 3.
#### $\Leftarrow$
Jika $a = 0$ maka
$$
0 {v} = 0 {v} + \mathbf{0} = 0{v} + 0{v} - 0{v} = (0+0){v}- 0{v} = 0{v} - 0{v} = \mathbf{0}
$$
Jika ${v} = \mathbf0$ maka
$$
a \mathbf{0} = a \mathbf{0} + \mathbf{0} = a\mathbf{0} + a\mathbf{0} - a\mathbf{0} = a(\mathbf{0} + \mathbf{0}) - a\mathbf{0} = a\mathbf{0} - a\mathbf{0} = \mathbf{0}
$$
#### $\Rightarrow$
Misalkan $a{v} = \mathbf{0}$. Andaikan $a \neq 0$ dan ${v}\neq\mathbf{0}$. Karena $a \neq 0$ maka $a^{-1}$ terdefinisi. Artinya
$$
{v} = a^{-1} \ a{v} = a^{-1} \mathbf{0} = \mathbf{0}
$$
Kontradiksi dengan pengandaian ${v}\neq\mathbf{0}$

### 4.
Perhatikan bahwa
$$
{v} + (-1) {v} = (1 - 1){v} = 0{v} = \mathbf{0}
$$
Berdasarkan [[ |Ketunggalan Inverse Penjumlahan]] maka $(-1){v} = {-v}$

### 5.
Perhatikan bahwa
$$
(-{v}) + {v} = \mathbf{0}
$$
Berdasarkan [[ |Ketunggalan Inverse Penjumlahan]] maka $-({-v}) = {v}$

***
## Definition Used 
 * [[Buat Backup/Sem