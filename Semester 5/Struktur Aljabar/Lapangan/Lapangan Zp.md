#Teorema 
Gelanggang $\mathbb{Z}_{p}$ adalah **Lapangan** jika dan hanya jika $p$ adalah bilangan prima.

---
## Bukti
### $\Rightarrow$
Misalkan $\mathbb{Z}_{p}$ adalah lapangan. Andaikan $p$ komposit, [[Dekomposisi Prima|maka]] $p = ab$ dengan $1 < a \le b < p$. Maka $[a]_{p}, [b]_{p}$ keduanya taknol. Perhatikan bahwa
$$
[a]_{p}\cdot[b]_{p} = [ab]_{p} = [p]_{p} = [0]_{p}
$$
Maka $\mathbb{Z}_{p}$ memiliki pembagi nol, kontradiksi dengan $\mathbb{Z}_{p}$ sebagai lapangan sehingga $\mathbb{Z}_{p}$ [[Lapangan Sebagai Daerah Integral|Daerah Integral]]. Maka pengandaian salah. Terbukti $p$ adalah bilangan prima.

### $\Leftarrow$
Misalkan $p$ adalah bilangan prima. Ambil $[n]_{p}\in \mathbb{Z}_{p}$ dengan $[n]_{p} \neq [0]_{p}$. Artinya $p \nmid n$. Karena $p$ adalah [[Bilangan Prima]] maka $(n, p) = 1$. Berdasarkan [[Teorema Bezout]] terdapat $k, q \in \mathbb{Z}$ sehingga
$$
kp + nq = 1 \quad\implies\quad nq - 1 = kp \quad\implies\quad p \mid nq - 1
$$
Artinya $[nq]_{p} = [n]_{p}[q]_{p}= [1]_{p}$. Berarti $[n]_{p}$ memiliki inverse. Karena setiap unsur memiliki inverse maka $\mathbb{Z}_{p}$ adalah lapangan.
***
## Definition Used 
 * [[Gelanggang Zn]]
 * [[Lapangan]]
 * [[Unsur Pembagi Nol (Ring)]]
 * [[Bilangan Prima]]
 * [[Bilangan Komposit]]