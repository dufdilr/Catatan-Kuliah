#Teorema 
Misalkan $n \in \mathbb{N}$ berlaku
$$
\text{Aut}\left({\mathbb{Z}_{n}}\right) \cong U_n
$$
---
## Bukti

Definisikan pemetaan $\phi:U_n \to \text{Aut}\left({\mathbb{Z}_{n}}\right)$ dengan $\phi(k) = \phi_k : \mathbb{Z}_{n} \to \mathbb{Z}_{n}$  memenuhi
$$
\phi_k([x]_{n}) = [kx]_{n}
$$
Akan ditunjukkan $\phi$ adalah isomorfisma.

Ambil $k_{1},k_{2} \in U_n$. Perhatikan bahwa untuk setiap $[x]_{n} \in \mathbb{Z}_{n}$ berlaku
$$
\phi_{k_{1}k_{2}}([x]_{n}) = [k_{1}k_{2}x]_{n} = \phi_{k_{1}}([k_{2}x]_{n}) = \phi_{k_{1}} (\phi_{k_{2}}([x]_{n})) = \phi_{k_{1}} \circ \phi_{k_{2}}([x]_{n})
$$
maka $\phi(k_{1}k_{2}) = \phi(k_{1})\circ \phi(k_{2})$. Terbukti $\phi$ adalah homomorfisma.

Ambil $k_{1}, k_{2} \in U_n$ dengan $\phi(k_{1}) = \phi_{k_{1}} = \phi_{k_{2}} = \phi(k_{2})$. Perhatikan bahwa
$$
[k_{1}]_{n} = \phi_{k_{1}}([1]_{n}) = \phi_{k_{2}}([1]_{n}) = [k_{2}]_{n}
$$
Terbukti $[k_{1}]_{n} = [k_{2}]_{n}$. Maka $\phi$ bersifat injektif.

Ambil $f \in \text{Aut}\left({\mathbb{Z}_{n}}\right)$. Berdasarkan [[Automorfisma Zn|Teorema]] maka terdapat $k \in \mathbb{Z}$ dengan $(k, n) = 1$ sedemikian sehingga
$$
f([x]_{n}) = [kx]_{n} = \phi_k([x]_{n})
$$
Karena $(k, n)=1$ maka $[k]_{n} \in U_n$. Artinya, $f = \phi(k)$. Maka $\phi$ bersifat surjektif.

Karena $\phi$ homomorfisma injektif dan surjektif maka $\phi$ adalah isomorfisma. Terbukti bahwa
$$
\text{Aut}\left({\mathbb{Z}_{n}}\right) \cong U_n
$$

***
## Definition Used 
 * [[Automorfisma Zn]]
 * [[Grup Perkalian Un]]