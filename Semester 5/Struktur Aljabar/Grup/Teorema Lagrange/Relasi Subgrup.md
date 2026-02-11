#Definisi #Teorema 

Misalkan $G$ suatu grup dan $S \le G$. Definisikan relasi $\sim_S$ di $G$ sebagai
$$
a \sim_S b \quad\iff\quad a^{-1}b \in S
$$
Relasi ini membentuk relasi ekuivalen di $G$.

---

## Bukti
1. **Refleksif**
Jelas
$$
a^{-1}a = e \in S
$$
maka $a \sim_S a$.
2. **Simteris**
Misalkan $a \sim_S b$. Artinya $a^{-1}b \in S$, maka $b^{-1}a = (a^{-1}b)^{-1} \in S$. Maka $b \sim_S a$.
3. **Transitif**
Misalkan $a \sim_S b$ dan $b \sim_S c$. Artinya $a^{-1}b, b^{-1}c \in S$. Perhatikan bahwa
$$
a^{-1}c = a^{-1}b \cdot b^{-1}c \in S
$$
Maka $a \sim_S c$.

Karena $\sim_S$ bersifat refleksif, simetris dan transitif maka $\sim_S$ merupakan relasi ekuivalen.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Subgrup]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]]
