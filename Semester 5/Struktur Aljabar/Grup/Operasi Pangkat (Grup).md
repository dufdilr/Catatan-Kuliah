#Teorema 

Misalkan $(G, *)$ suatu grup dengan unsur identitas $e$ dan $a \in G$. Maka berlaku
* $a^m * a^n = a^{m+n}$
* $(a^m)^{-1} = a^{-m}$

---
## Bukti
### Poin Pertama
Jika $m = 0$ atau $n = 0$. Tanpa mengurangi keumuman misalkan $n = 0$ maka jelas
$$a^m * a^n = a^m * e = a^{m+0} = a^{m+n}$$
Jika $m, n$ keduanya bilangan positif maka
$$
a^m*a^n = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m$ kali}} *\underbrace{a*a*\cdots*a}_{\text{sebanyak $n$ kali}} = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m + n$ kali}} = a^{m+n}
$$
Jika $m, n$ keduanya bilangan negatif maka
$$a^m*a^n = \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-m$ kali}} * \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-n$ kali}} = \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-(m+n)$ kali}} = a^{m+n}$$
Jika salah satu positif dan yang lain negatif. Tanpa mengurangi keumuman misalkan $m> 0$ dan $n < 0$.  
* Jika $m > -n$
 $$
 a^m * a^n = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m$ kali}} * \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-n$ kali}} = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m + n$ kali}} = a^{m+n}
 $$
* Jika $m < -n$
$$
 a^m * a^n = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m$ kali}} * \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-n$ kali}} = \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $-(m+n)$ kali}} = a^{m+n}
 $$
* Jika $m = -n$
$$
a^m * a^n = \underbrace{a*a*\cdots*a}_{\text{sebanyak $m$ kali}} * \underbrace{(a^{-1})*(a^{-1})*\cdots*(a^{-1})}_{\text{sebanyak $m$ kali}} = e = a^0 = a^{m+n}
$$

Terbukti bahwa $a^m*a^n = a^{m+n}$

### Poin Kedua
Jelas bahwa
$$
a^m * a^{-m} = a^0 = e
$$
Berdasarkan [[Sifat Grup|Sifat Ketunggalan Identitas]] maka terbukti $(a^m)^{-1} = a^{-m}$.

***
## Definition Used
* [[Grup]]
* [[Pangkat (Grup)]]