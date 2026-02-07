Misalkan $f(x)$ fungsi real kontinu di interval $[a, b]$ dengan $f(a) \cdot f(b) < 0$. Berdasarkan [[Teorema Nilai Antara]] terdapat $c \in [a, b]$ sehingga $f(c) = 0$.

Berdasarkan teorema tersebut, dapat dibentuk **Metode Bisection** yakni metode untuk mencari akar persamaan $f(x) = 0$ dengan menguji titik tengah $a$ dan $b$ yakni $c = \frac{a + b}{2}$. Iterasi berakhir jika [[Galat#Galat Mutlak|galat mutlak]] kurang dari batas galat.  

Algoritma untuk metode Bisection adalah
```
Input: 
	f    := Fungsi yang dicari akar
	a, b := Tebakan awal
	eps  := Batas galat
Output:
	akar := Hampiran akar dari f
Algoritma:
1. FA := f(a)
2. FB := f(b)
3. if FA*FB >= 0:
	   error
	end
4. c := (a+b)/2
5. FC := f(c)
6. while (b - a) >= eps and FC >= 10^(-6) do
	if FA*FC <0 do
		b:= c
		FB := FC
	else
		a := c
		FA := FC
	end
	c := (a+b)/2
	FC := f(c)
   end
7. akar := c
8. return(c)
```