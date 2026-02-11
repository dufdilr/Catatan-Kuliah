#Teorema 
Misalkan $(G, *)$ suatu grup dan $A \subseteq G$ maka $\langle A \rangle$ adalah **subgrup** dari $G$

#Akibat
Misalkan $(G, *)$ suatu grup dan $a \subseteq G$ maka $\langle a \rangle$ adalah **subgrup** dari $G$

---
## Bukti Teorema

Ambil $g, h \in \langle A \rangle$. Artinya terdapat $n_1, n_2, \cdots, n_k, m_1, m_2, \cdots, m_l \in \mathbb{Z}$ dan $a_1, a_2, \cdots, a_k, b_1, b_2, \cdots , b_l \in A$ sehingga

$$g = a_1^{n_1}*a_2^{n_2}*\cdots*a_k^{n_k} \text{ dan }h = b_1^{m_1}*b_2^{m_2}*\cdots*b_l^{m_l}$$
Perhatikan bahwa
$$
g*h^{-1} = \left(a_1^{n_1}*a_2^{n_2}*\cdots*a_k^{n_k}\right) * \left(b_1^{m_1}*b_2^{m_2}*\cdots*b_l^{m_l}\right)^{-1} = a_1^{n_1}*a_2^{n_2}*\cdots*a_k^{n_k} * b_l^{-m_l} * b_{l-1}^{-m_{l-1}} * \cdots * b_2^{-m_2} * b_1^{-m_1}
$$
Sehingga jelas $g*h^{-1} \in \langle A \rangle$. Berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Karakterisasi Subgrup|Teorema]] terbukti $\langle A \rangle$ subgrup dari $G$.
### Bukti Akibat
Perhatikan bahwa

$$
\langle a \rangle = \langle \{ a \}\rangle
$$
yang mana adalah subgrup berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup Terbangun|Teorema]]  

***
## Definition Used
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subhimpunan Terbangun]]
* [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Pangkat (Grup)]]