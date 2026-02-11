#Teorema 

Misalkan $R$ suatu [[Buat Backup/Prerquested 1/Relasi dan Fungsi/Relasi Ekuivalen|relasi ekuivalen]] pada himpunan $A$. Himpunan kelas ekuivalen dari $R$ membentuk *partisi* dari $A$.

## Bukti

Tinjau $\mathcal{P} = \{ [a]_{R} : a \in A \}$. Akan ditunjukkan $\mathcal{P}$ adalah partisi dari $A$.
### Tak Kosong
Ambil $P = [a]_{R} \in \mathcal{P}$. Karena $R$ refleksif maka $aRa$. Berarti $a \in [a]_R$. Terbukti $P \neq \emptyset$.

### Saling Lepas
Ambil $P, Q \in \mathcal{P}$ dengan $P = [a]_R$ dan $Q = [b]_R$ untuk suatu $a, b \in A$ serta $P\neq Q$. Akan ditunjukkan $P \cap Q = \emptyset$.

Andaikan $P \cap Q \neq \emptyset$. Artinya terdapat $x \in A$ sehingga $x \in P$ dan $x \in Q$. Berarti $xRa$ dan $xRb$. 
Ambil $z \in P$. Artinya $zRa$. Karena $R$ simetris dan $xRa$ maka $aRx$. Karena $R$ transitif serta $zRa$ dan $aRx$ maka $zRx$. Karena $zRx$ dan $xRb$ maka $zRb$. Artinya $z \in Q$. Berarti $P \subseteq Q$. Dengan argumen serupa didapatkan $Q \subseteq P$. Berarti $P = Q$. Hal ini kontradiksi dengan hipotesis awal bahwa $P \neq Q$. Berarti pengandaian salah. 

Terbukti jika $P \neq Q$ maka $P \cap Q= \emptyset$.

### Membangun A
Jelas $A \supseteq \bigcup_{P \in \mathcal{P}} P$. Lebih lanjut, ambil $a \in A$. Karena $R$ refleksif maka $aRa$. Berarti $a \in [a]_R \in \mathcal{P}$. Berarti 
$$
A \subseteq \bigcup_{P \in \mathcal{P}} P
$$
Terbukti
$$
A = \bigcup_{P \in \mathcal{P}} P
$$

Berdasarkan definisi, maka terbukti $\mathcal{P}$ adalah partisi dari $A$.

***
## Definition Used
* [[Buat Backup/Prerquested 1/Relasi dan Fungsi/Kelas Ekuivalen]]
* [[Buat Backup/Prerquested/Naive Set/Partisi Himpunan]]
* [[Buat Backup/Prerquested 1/Relasi dan Fungsi/Gabungan dan Irisan Kumpulan Himpunan]]
