#Teorema 

Setiap pohon adalah graf sederhana.

---
## Bukti
Misalkan $G$ adalah suatu pohon. Andaikan dia tidak sederhana. Artinya terdapat *loop* atau *multiple edges*
* Jika terdapat *loop* $e_0$ maka terdapat $e_0$ membentuk siklus dengan panjang 1. Artinya $G$ bukan pohon (Kontradiksi).
* Jika terdapat *multiple edges* $e_1, e_2$ yang menghubungkan $u$ dan $v$. Tinjau $C = u\ e_1 \ v \ e_2 \ u$. Perhatikan bahwa $C$ adalah siklus di $G$. Artinya $G$ bukan pohon (Kontradiksi).

Untuk kedua kasus terjadi kontradiksi. Artinya, pengandaian salah. Terbukti setiap pohon adalah graf sederhana

***
## Definition Used
* [[Buat Backup/Semester 5/Pengantar Teori Graf/2. Tree/Pohon (Graf)]]
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Graf Sederhana]]
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Loop dan Multiple Edges]]
