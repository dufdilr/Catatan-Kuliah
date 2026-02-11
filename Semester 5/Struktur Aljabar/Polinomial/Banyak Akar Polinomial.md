#Teorema 

Misalkan $R$ daerah integral dan $f(x) \in R[x]$ dan $f(x) \neq 0$. Banyak akar dari $f(x)$ (jumlah multisiplitasnya) tidak lebih dari $\deg f(x)$.

---
## Bukti

Definisikan untuk $n \in \mathbb{N}_{0}$
$$
P(n) := \text{Polinomial berderajat } n \text{ memiliki paling banyak } n  \text{ jumlah multisiplitas akar}
$$
Akan ditunjukkan $P(n)$ benar untuk setiap $n \in \mathbb{N}_{0}$.
* **Kasus Basis**
	Misalkan $f(x)$ berderajat nol. Artinya $f(x) = d$  untuk suatu $d \in R$. Perhatikan bahwa untuk setiap $c \in R$ berlaku
	$$
f(c) = d \neq 0
$$
	Maka $f(x)$ tidak memiliki akar. Sehingga jumlah multiplisitas akar sebanyak $0 \le \deg f$. Terbukti $P(0)$ benar.
	
* **Langkah Induksi**
	Misalkan untuk suatu $n\in \mathbb{N}$ berlaku $P(k)$ benar untuk setiap $k < n$. Akan ditunjukkan $P(n)$ benar.

	Misalkan $f(x)$ polinomial berderajat $n$. Tinjau $f(x)$ memiliki akar atau tidak.
	* Jika $f(x)$ tidak memiliki akar, maka jumlah multiplisitas akar dari $f$ adalah $0 \le \deg f$.
	* Jika $f(x)$ memiliki akar $c \in R$ dengan multiplisitas $m \in \mathbb{N}$. Artinya, terdapat $q(x) \in R[x]$ sehingga
	 $$
f(x) = q(x) (x-c)^m
$$
		dengan $q(c) \neq 0$. Karena $q(c) \neq 0$. Lebih lanjut, karena $R$ adalah daerah integral, berdasarkan [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Derajat Hasil Operasi Polinomial|teorema]] maka $\deg f = \deg q(x) + \deg (x-c)^m = \deg q(x) + m$. Artinya $\deg q(x) = \deg f - \deg (x - c)^m = n - m < n$. 
	
		Berdasarkan hipotesa induksi, maka $q(x)$ memiliki paling banyak $n - m$ jumlah multiplisitas akar. Akibatnya $f(x)$ memiliki paling banyak $(n-m)+m = n = \deg f$ jumlah multiplisitas akarnya.

	Untuk kedua kasus, terbukti $P(n)$ benar

Berdasarkan [[Buat Backup/Prerquested/Prinsip Induksi Matematika]] maka $P(n)$ benar untuk setiap $n \in \mathbb{N}$.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Polinomial Daerah Integral]]
 * [[Buat Backup/Semester 5/Struktur Aljabar/Polinomial/Akar Polinomial]]