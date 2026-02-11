#Teorema 
Misalkan $R$ adalah Daerah Ideal Utama dan $q \in R$. Maka berlaku
$$
q \text{ unsur tak-tereduksi } \iff \left< q \right>  \text{ ideal maksimal}
$$
---
## Bukti
### $\Rightarrow$
Misalkan $q$ adalah unsur tak-tereduksi. Pandang ideal $\left< q \right>$. Andaikan $\left< q \right>$ bukan ideal maksimal. Maka terdapat $J$ ideal sejati dari $R$ sehingga $\left< q \right> \subsetneq J$. Karena $R$ adalah daerah ideal utama, maka $J = \left< a \right>$ untuk suatu $a \in R$. 

Perhatikan bahwa $q \in \left< q \right> \subseteq \left< a \right>$. Artinya $q = ua$. Karena $q$ adalah unsur tak-tereduksi maka $u$ adalah unit atau $a$ adalah unit.
* **Jika $u$ adalah unit.**
	Maka $q = au$ dengan $u$ unit. Artinya $a, q$ sekawan. Berdasarkan [[Kesamaan Ideal Utama]] maka $\left< q \right> = \left< a \right> = J$, kontradiksi dengan pemilihan $J$ berbeda dengan $\left< q \right>$.
* **Jika $a$ adalah unit**
	Berdasarkan [[Ideal dengan Unit|teorema]] $J = \left< a \right> = R$. Kontradiksi dengan pemilihan $J$ ideal sejati.

Pada kedua kasus, terjadi kontradiksi. Maka pengandaian salah. Terbukti, $\left< q \right>$ adalah ideal maksimal.
### $\Leftarrow$
Misalkan $\left< q \right>$ adalah ideal maksimal. Ambil $u, v \in R$ sehingga $uv = q$.
Perhatikan bahwa $q \in \left< u \right>$. Artinya, $\left< q \right> \subseteq \left< u \right>$. Karena $\left< q \right>$ adalah ideal maksimal maka $\left< u \right> = \left< q \right>$ atau $\left< u \right> = R$.
* **Jika $\left< u \right> = \left< q \right>$**
	Berdasarkan [[Kesamaan Ideal Utama]] maka $u, q$ sekawan. Maka $q = uw$ untuk suatu $w$ unit. Perhatikan bahwa
	$$
q = uw = uv \quad\implies\quad uw - uv = 0 \quad\implies\quad u(v - w) = 0
$$
	Jelas karena $q$ tak-nol maka $u$ tak-nol. Karena Daerah Ideal Utama adalah Daerah Integral maka $v - w = 0$. Dengan kata lain $v = w$ adalah unit.
* **Jika $\left< u \right> = R$**
	Perhatikan bahwa $1 \in R = \left< u \right>$, maka $1 = uw$ untuk suatu $w \in R$. maka $u$ adalah unit.

Terlihat untuk kedua kasus, $u$ adalah unit atau $v$ adalah unit. Per defisini, terbukti $q$ adalah unsur tak-tereduksi.

***
## Definition Used 
 * [[Daerah Ideal Utama]]
 * [[Daerah Integral]]
 * [[Unsur Tak Tereduksi (Ring)]]
 * [[Ideal Maksimal]]
 * [[Ideal Utama]]