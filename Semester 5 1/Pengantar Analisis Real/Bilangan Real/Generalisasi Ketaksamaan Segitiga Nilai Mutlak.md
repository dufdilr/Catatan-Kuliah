#Teorema 
Misalkan $x_{1}, x_{2}, x_{3}, \dots , x_n \in \mathbb{R}$ maka
$$
|x_{1}+x_{2}+x_{3}+\dots+x_n| \le |x_{1}| + |x_{2}|+\cdots + |x_n|
$$

***
## Bukti
Akan dibuktikan dengan induksi. Definisikan
$$
P(n) := \text{Untuk setiap } x_{1}, x_{2}, x_{3}, \dots , x_n \in \mathbb{R} \text{ berlaku } 
|x_{1}+x_{2}+x_{3}+\dots+x_n| \le |x_{1}| + |x_{2}|+\cdots + |x_n|
$$
* **Kasus Basis**
	Berdasarkan [[Sifat Nilai Mutlak]] maka $x_{1} \le |x_{1}|$. Maka $P(1)$ benar.
* **Langkah Induksi**
	Misalkan $P(n)$ benar. Misalkan $x_{1}, x_{2}, x_{3}, \dots , x_{n+1} \in \mathbb{R}$. Perhatikan bahwa
	$$
|x_{1}+x_{2}+x_{3}+\dots+x_{n+1}| \le |x_{1}+x_{2}+\dots+x_n| + |x_{n+1}| \le |x_{1}| + |x_{2}|+\cdots + |x_n| +x_{n+1}
$$

Berdasarkan [[Prinsip Induksi Matematika]], maka $P(n)$ benar untuk setiap $n \in \mathbb{N}$.


***
## Definition Used 
 * [[Aksioma Bilangan Real]]
 * [[Urutan Bilangan Real]]
 * [[Nilai Mutlak]]