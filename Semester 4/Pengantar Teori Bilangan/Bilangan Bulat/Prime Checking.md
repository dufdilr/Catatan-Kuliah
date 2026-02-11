#Teorema 

Misalkan $n \in \mathbb{N}$. Bilangan $n$ merupakan bilangan *komposit* jika dan hanya jika $n$ memiliki faktor prima $p$ dengan $p \le \sqrt{ n }$.

## Bukti
### $\Rightarrow$
Misalkan $n$ bilangan komposit, berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor dari Bilangan Prima|teorema]] maka terdapat bilangan asli $d$ dengan $1 < d < n$ dan $d | n$. Misalkan $n = df$ untuk suatu $f \in \mathbb{N}$. Perhatikan pula bahwa $1<f<n$. Tanpa mengurangi keumuman, misalkan $1 < d \le f < n$. Akan ditunjukkan $d \le \sqrt{n}$

Andaikan $d > \sqrt{ n }$, maka $n = ab \ge a^2 > n$, kontradiksi. Maka terbukti $d \le \sqrt{ n }$.

Lebih lanjut, $d$ [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Dekomposisi Prima|memiliki faktor prima]] $p$. Perhatikan bahwa $p \le d \le \sqrt{ n }$. Terbukti, $n$ memiliki faktor prima $p$ dengan $p \le \sqrt{ n }$

### $\Leftarrow$
Perhatikan bahwa $n$ memiliki setidaknya tiga faktor yakni $1, n$ dan $p$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Faktor dari Bilangan Prima|teorema]] maka $n$ bukan bilangan prima, sehingga terbukti $n$ adalah bilangan komposit.

***
## Definition Used 
 * [[Buat Backup/Prerquested/Bilangan Asli]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Prima]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Bilangan Komposit]]
