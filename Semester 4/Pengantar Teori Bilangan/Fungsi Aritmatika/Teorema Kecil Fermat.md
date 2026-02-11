#Teorema 

Jika $a \in \mathbb{N}$ dan $p$ bilangan prima maka
$$
a^p \equiv a \mod p
$$

---
## Bukti
* **Jika $p \mid a$** 
	Perhatikan bahwa $a \equiv 0 \mod p$ maka $a^p \equiv 0 \mod p$. Terbukti $a^p \equiv a \mod p$
* **Jika $p \mid a$** 
	Perhatikan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Rumus Fungsi Euler-Phi|bahwa]] $\varphi(p) = p-1$. Berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Teorema Euler (Modulo)]] maka
	$$
a^{\varphi(p)} \equiv a^{p-1} \equiv 1 \mod p \quad\implies\quad a^p \equiv a \mod p
$$

Terbukti bahwa $a^p \equiv a \mod p$.

***
## Definition Used 
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Kongruensi Modulo]]
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]