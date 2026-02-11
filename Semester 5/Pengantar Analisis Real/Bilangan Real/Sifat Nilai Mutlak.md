#Teorema 
Untuk setiap $x, y \in \mathbb{R}$ dan $a > 0$ berlaku
1. $|x| \ge 0$
2. $|x|\cdot |y| = |xy|$
3. $|x| \le a \iff -a \le x \le a$ ^b4f8ad
4. $-|x|\le x \le |x|$

---
## Bukti
### 1.
Ambil sebarang $x \in \mathbb{R}$. Berdasarkan [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]] (Sifat Trikotomi), maka berlaku tepat satu kondisi: $x \in \mathbb{P}, -x \in \mathbb{P}$ atau $x = 0$. Berdasarkan [[Definisi Nilai Mutlak]]:
* **Jika $x \in \mathbb{P}$**
  Maka $|x| = x$. Karena $x \in \mathbb{P}$ maka $|x| > 0$.
* **Jika $x = 0$**
  Maka $|x| = 0$.
* **Jika $-x \in \mathbb{P}$ (artinya $x < 0$)**
  Maka $|x| = -x$. Karena $-x \in \mathbb{P}$ maka $|x| > 0$.

Dari ketiga kasus di atas, terbukti bahwa untuk setiap $x \in \mathbb{R}$, $|x| \ge 0$.

### 2.
Ambil sebarang $x, y \in \mathbb{R}$. Tinjau kasus berdasarkan tanda dari $x$ dan $y$:
* **Jika salah satu $x=0$ atau $y=0$**
  Tanpa mengurangi keumuman, misal $x=0$. Maka $|x||y| = 0 \cdot |y| = 0$ dan $|xy| = |0| = 0$. Terbukti sama.
* **Jika $x > 0$ dan $y > 0$**
  Maka $xy > 0$. Sehingga $|x||y| = x \cdot y = xy = |xy|$.
* **Jika $x > 0$ dan $y < 0$**
  Maka $xy < 0$. Sehingga $|x||y| = x \cdot (-y) = -(xy) = |xy|$.
* **Jika $x < 0$ dan $y < 0$**
  Maka $xy > 0$. Sehingga $|x||y| = (-x) \cdot (-y) = xy = |xy|$.

Dalam semua kasus, terbukti $|x|\cdot|y| = |xy|$.

### 3.
Akan dibuktikan dua arah ($\iff$):
**($\Rightarrow$)**
Diketahui $|x| \le a$.
* Jika $x \ge 0$, maka $|x| = x$. Sehingga $x \le a$. Karena $a > 0$ dan $x \ge 0$, jelas bahwa $-a < 0 \le x$. Maka $-a \le x \le a$.
* Jika $x < 0$, maka $|x| = -x$. Sehingga $-x \le a \iff x \ge -a$. Karena $x < 0 < a$, maka $x \le a$. Maka $-a \le x \le a$.

**($\Leftarrow$)**
Diketahui $-a \le x \le a$.
* Jika $x \ge 0$, maka $|x| = x$. Karena diketahui $x \le a$, maka $|x| \le a$.
* Jika $x < 0$, maka $|x| = -x$. Karena diketahui $-a \le x$, kalikan dengan $-1$ (tanda pertidaksamaan berbalik) menjadi $a \ge -x$, atau $|x| \le a$.

Terbukti $|x| \le a \iff -a \le x \le a$.

### 4.
Ambil $a = |x|$.
Berdasarkan pembuktian nomor 1, kita tahu bahwa $|x| \ge 0$. Maka kita dapat mensubstitusi $a$ dengan $|x|$ pada ketaksamaan nomor 3.
$$
|x| \le |x| \iff -|x| \le x \le |x|
$$
Karena pernyataan $|x| \le |x|$ selalu benar (trivial), maka implikasinya $-|x| \le x \le |x|$ juga bernilai benar.

***
## Definition Used 
 * [[Buat Backup/Semester 5/Pengantar Analisis Real/Bilangan Real/Aksioma Bilangan Real]]
 * [[Definisi Nilai Mutlak]]
 * [[Sifat Aljabar Bilangan Real]]