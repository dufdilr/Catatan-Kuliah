Fungsi yang landai akan memperlambat kekonvergenan [[Buat Backup/Semester 5/Matematika Numerik/2. Akar Persamaan/Metode Regula Falsi Modifikasi]]. Untuk mempercepat kekonvergenan dilakukan modifikasi yakni apabila selama dua iterasi berturut-turut nilai fungsi dikali setengahnya. 

Maka, pada algoritma diberi *counter* berapa banyak perubahan ujung kiri dan ujung kanan.
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
4. kiri = 0
5. kanan = 0
6. clama := 2*b - a
7. c := a - FA*(b-a)/(FB-FA)
8. FC := f(c)
9. while abs(clama - c) >= eps and FC >= 10^(-6) do
	if FA*FC <0 then
		b:= c
		FB := FC
		kanan := 0
		kiri := kiri + 1
		if kiri > 2 then
			FA := FA/2
		end
	else
		a := c
		FA := FC
		kiri := 0
		kanan := kanan +1
		if kanan > 2 then
			FB := FB/2
		end
	end
	clama := c
	c := a - FA*(b-a)/(FB-FA)
	FC := f(c)
   end
10. akar := c
11. return(c)
```