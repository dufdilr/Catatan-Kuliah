#Teorema 

Misalkan $A, B$ subhimpunan tak-kosong dari $\mathbb{R}$. Jika untuk setiap $a\in A$ dan $b\in B$ berlaku
$$
a \le b
$$
Maka $A$ memiliki supremum dan $B$ memiliki infimum dengan $\sup A \le \inf B$.

---
## Bukti

Ambil $a \in A$. Karena untuk setiap $b \in B$ berlaku $a \le b$ maka $a$ adalah batas bawah dari $B$. Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Eksistensi Supremum dan Infimum]] maka $B$ memiliki infimum, sebut $\inf B = v$. Karena $a$ batas bawah $B$ dan $v$ adalah infimum dari $B$ maka berlaku
$$
a \le v
$$
Perhatikan bahwa untuk setiap $a \in A$ berlaku $a \le v$ maka $A$ terbatas di atas. Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Eksistensi Supremum dan Infimum]] maka $A$ memiliki supremum, sebut $\sup A = u$. Perhatikan bahwa $v$ adalah batas atas dari $A$ dan $u$ adalah supremum dari $A$ maka berlaku
$$
u \le v \quad\implies\quad \sup A \le \inf B
$$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]]
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Himpunan Terbatas di Atas]]
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Himpunan Terbatas di Bawah]]
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Supremum]]
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Infimum]]