#Teorema 

Misalkan $R$ adalah gelanggang komutatif dan $I$ adalah ideal dari $R$. Maka berlaku
$$
R/I \text{ daerah integral} \quad \iff \quad I \text{ ideal prima}
$$
---
## Bukti

### $\Leftarrow$
Misalkan $I$ adalah ideal prima. Akan ditunjukkan $R/I$ membentuk daerah integral. 

Ambil $r_{1}I, r_{2}I \in R/I$ dengan $r_{1}I \neq I$ namun $r_{1}I \cdot r_{2}I=(r_{1}r_{2})I = I$. Berdasarkan [[Kesamaan Koset]] maka $r_{1}r_{2} \in I$. Karena $r_{1}I \neq I$ [[Kesamaan Koset|maka]] $r_{1} \notin I$. Karena $I$ adalah ideal prima dengan $r_{1}r_{2}\in I$ namun $r_{1}\notin I$ maka $r_{2}\in I$. Akibatnya $r_{2}I = I$. Berarti $r_{1}I$ bukan [[Unsur Pembagi Nol (Ring)|pembagi nol]]. Maka $R/I$ adalah daerah integral.
### $\Rightarrow$
Misalkan $R/I$ adalah daerah integral. Akan ditunjukkan $I$ adalah ideal prima.

Ambil $r_{1}, r_{2} \in I$ dengan $r_{1}r_{2} \in I$ namun $r_{1} \notin I$. Perhatikan bahwa
$$
(r_{1}r_{2})I = r_{1}I \cdot r_{2}I = I
$$
Karena $r_{1}\not\in I$ maka $r_{1}I \neq I$. Karena $R/I$ adalah daerah integral maka $r_{2}I = I$. Berdasarkan [[Kesamaan Koset]] maka $r_{2} \in I$. Per definisi, maka $I$ adalah ideal prima.

***
## Definition Used 
 * [[Gelanggang Komutatif]]
 * [[Ideal (Ring)]]
 * [[Daerah Integral]]
 * [[Ideal Prima]]
 * [[Gelanggang Hasil Bagi]]