#Teorema

Misalkan $\langle\cdot,\cdot\rangle$ adalah **hasil kali dalam** pada $\mathbb{V}$. Maka
$$\|u\| = \sqrt{\langle u,u\rangle}$$
adalah suatu **norm** pada $\mathbb{V}$.

---
## Bukti
Akan ditunjukkan bahwa $\|u\| = \sqrt{\langle u,u\rangle}$ memenuhi ketiga aksioma norm dengan menggunakan sifat-sifat hasil kali dalam.

### 1. Sifat Definit Positif
Berdasarkan sifat definit positif dari hasil kali dalam, kita tahu $\langle u, u \rangle \ge 0$. Akibatnya, $\|u\| = \sqrt{\langle u, u \rangle}$ juga selalu $\ge 0$.

Selanjutnya,
$$ \|u\| = 0 \iff \sqrt{\langle u, u \rangle} = 0 \iff \langle u, u \rangle = 0 $$
Dan dari aksioma hasil kali dalam, $\langle u, u \rangle = 0$ jika dan hanya jika $u = \mathbf{0}$. Maka, aksioma pertama terpenuhi.

### 2. Sifat Homogenitas Absolut
Untuk setiap skalar $\alpha \in \mathbb{R}$:
$$ \|\alpha u\| = \sqrt{\langle \alpha u, \alpha u \rangle} $$
Menggunakan sifat homogenitas dan simetri dari hasil kali dalam:
$$ \langle \alpha u, \alpha u \rangle = \alpha \langle u, \alpha u \rangle = \alpha \langle \alpha u, u \rangle = \alpha^2 \langle u, u \rangle $$
Maka,
$$ \|\alpha u\| = \sqrt{\alpha^2 \langle u, u \rangle} = \sqrt{\alpha^2} \sqrt{\langle u, u \rangle} = |\alpha| \|u\| $$
Aksioma kedua terpenuhi.

### 3. Ketaksamaan Segitiga
Perhatikan bahwa
$$
\begin{align*}
\|u+v\|^2 &= \langle u+v, u+v \rangle \\
&= \langle u, u \rangle + \langle u, v \rangle + \langle v, u \rangle + \langle v, v \rangle \quad (\text{Aditivitas}) \\
&= \|u\|^2 + 2\langle u, v \rangle + \|v\|^2 \quad (\text{Simetri})
\end{align*}
$$
Karena $\langle u, v \rangle \le |\langle u, v \rangle|$ dan berdasarkan [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ketaksamaan Cauchy-Schwarz]], $\langle u, v \rangle \le \|u\|\|v\|$, maka:
$$ \|u+v\|^2 \le \|u\|^2 + 2\|u\|\|v\| + \|v\|^2 = (\|u\| + \|v\|)^2 $$
Dengan mengakarkan kedua sisi, kita dapatkan:
$$ \|u+v\| \le \|u\| + \|v\| $$
Aksioma ketiga terpenuhi. Karena semua aksioma terpenuhi, maka $\|u\| = \sqrt{\langle u,u\rangle}$ adalah sebuah norm. ■

***
## Definition Used:
* [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Hasil Kali Dalam]]
* [[Buat Backup/Semester 3 1/Fungsi Real/Ruang Metrik/Ruang Bernorm]]