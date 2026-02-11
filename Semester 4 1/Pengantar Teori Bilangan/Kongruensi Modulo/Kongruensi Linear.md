#Teorema 
Misalkan $a, b \in \mathbb{Z}$; $m \in \mathbb{N}$ dan $(a, m) = d$. Tinjau persamaan
$$
ax \equiv b \mod m
$$
maka berlaku:
1. Jika $d \nmid b$ maka persamaan tersebut **tidak memiliki solusi**.
2. Jika $d \mid b$ maka persamaan tersebut memiliki tepat $d$ solusi.

## Bukti
Perhatikan bahwa persamaan $ax \equiv b \mod m$ ekuivalen dengan persamaan
$$
ax - my = b
$$
untuk suatu $y \in \mathbb{Z}$. Berdasarkan [[Persamaan Diophantine Linear]], persamaan tersebut tidak memiliki solusi jika $d \nmid b$. Lebih lanjut, jika $d \mid b$ maka solusi berbentuk
$$
x = \frac{m}{d}n + x_0
$$
dengan $n \in \mathbb{N}$. Perhatikan bahwa kita bekerja di $\mod m$, artinya, terdapat tepat $d$ solusi yang memenuhi.

***

## Definition Used 
 * [[Kongruensi Modulo]]