#Definisi 

Misalkan $n$ suatu bilangan asli. Didefinisikan suatu [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi|relasi]] $a \sim_n b$ jika dan hanya jika $n \mid (a - b)$. Biasanya dinotasikan
$$a \equiv b \mod n$$

Lebih lanjut, relasi ini merupakan [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]].
## Bukti
Akan ditunjukkan relasi di atas adalah relasi ekuivalen:
* **Refleksif** 
	Misalkan $a \sim_n b$. Artinya $n \mid (a - b)$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^ab6a93|sifat keterbagian]] maka $n \mid -1(a - b) = b - a$. Dengan kata lain $b \sim_n a$. Berarti $\sim_n$ refleksif.
* **Simetris**
    Misalkan $a \equiv b \pmod{n}$. Artinya, $n \mid (a-b)$. Sehingga $n \mid (b - a) \quad \Rightarrow \quad b \equiv a \pmod{n}$.

* **Transitif**
    Misalkan $a \equiv b \pmod{n}$ dan $b \equiv c \pmod{n}$. Artinya $n \mid (a - b)$ dan $n \mid (c - b)$. Sehingga $n \mid (a - b) + (b-c) \quad \Rightarrow \quad n \mid (a-c) \quad \Rightarrow a \equiv c \pmod{n}$.

***
## Definition Used:
* [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Keterbagian]]
* [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi]]
* [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]]
