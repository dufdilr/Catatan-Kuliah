#Teorema 

Misalkan $S \subseteq \mathbb{N}$ dengan:
1. $1 \in S$ ^0416ed
2. Jika $n \in S$ maka $n + 1 \in S$ ^6b16ff

Maka $S = \mathbb{N}$.

---

## Bukti

Akan dibuktikan dengan kontradiksi. Andaikan $S \neq \mathbb{N}$. Artinya terdapat $m \in \mathbb{N}$ sehingga $m \notin S$. 

Misalkan $M = \mathbb{N}\backslash S$. Perhatikan bahwa $M \subseteq \mathbb{N}$ dan $m \in M$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]] maka terdapat unsur terkecil $m_0 \in M$. Berdasarkan sifat [[Buat Backup/Prerquested/Prinsip Induksi Matematika#^0416ed|(1)]] maka $m_0 \neq 1$. Artinya $m_0 - 1 \in \mathbb{N}$. Berdasarkan kontrapositif sifat [[Buat Backup/Prerquested/Prinsip Induksi Matematika#^6b16ff|(2)]] maka $m_0 - 1 \notin  S$. Artinya $m_0-1 \in M$. Jelas $m_0 - 1 < m_0$. Kontradiksi dengan $m_0$ adalah unsur terkecil $m_0$. Artinya pengandaian salah.

Terbukti bahwa $S = \mathbb{N}$.

***

## Definition Used
* [[Buat Backup/Prerquested/Bilangan Asli]]

