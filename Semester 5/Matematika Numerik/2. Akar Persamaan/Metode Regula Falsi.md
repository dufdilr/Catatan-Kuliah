Misalkan $f(x)$ fungsi real kontinu di interval $[a, b]$ dengan $f(a) \cdot f(b) < 0$. Berdasarkan [[Teorema Nilai Antara]] terdapat $c \in [a, b]$ sehingga $f(c) = 0$.

Serupa dengan [[Buat Backup/Semester 5/Matematika Numerik/2. Akar Persamaan/Metode Bisection]], metode ini menggunakan konsep memperkecil selang tebakan. Pada metode ini, nilai $c$ bukan nilai tengah melainkan perpotongan garis lurus yang menghubungkan $f(a)$ dan $f(b)$ dengan sumbu-$x$. Dengan kata lain,
$$c = a - f(a) \cdot \frac{b-a}{f(b)-f(a)}$$
Iterasi berhenti ketika $|c_{k+1} - c_k|$ kurang dari batas galat. Algoritma untuk metode ini juga serupa yakni
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
4. clama := 2*b - a
5. c := a - FA*(b-a)/(FB-FA)
6. FC := f(c)
7. while abs(clama - c) >= eps and FC >= 10^(-6) do
	if FA*FC <0 do
		b:= c
		FB := FC
	else
		a := c
		FA := FC
	end
	clama := c
	c := a - FA*(b-a)/(FB-FA)
	FC := f(c)
   end
8. akar := c
9. return(c)
```