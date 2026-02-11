#Teorema 

Misalkan $G$ suatu graf. Definisikan relasi $u \sim v$ jika $u$ dan $v$ *terhubung*. Relasi ini membentuk [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]].

## Bukti
### Refleksif
Jelas $u$ terhubung dengan $u$. Artinya $u \sim u$ untuk setiap $u \in V$.

### Simetris
Misalkan $u \sim v$. Artinya terdapat $(u, v)-$path $P = u \ v_1\ v_2\ \cdots \ v_{k-1} \ v$. Perhatikan bahwa $P = v \ v_{k-1}\ \cdots \ v_{2} \ v_{1} \ u$ adalah $(v, u)-$path. Terbukti $v \sim u$.

### Transitif
Misalkan $u \sim v$ dan $v \sim w$. Artinya terdapat $(u, v)-$path $P_{1} = u \ v_1\ v_2\ \cdots\ v_{k-1}\ v$ dan $(v, w)-$path $P_{2} = v \ w_1\ w_2\ \cdots \ w_{l-1}\ w$. Definisikan $v_0 = u, \ v_k = v, \ w_0 = v,$ dan $w_l = w$. Tinjau
$$
N = \{ i : w_{i} \in P_{1} \}
$$
Jelas $w_0 \in P_1$. Artinya $N \neq \emptyset$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Aksioma Urutan Sempurna]] terdapat unsur terkecil $n$. Misalkan $w_{n} = v_{m}$. Konstruksi
$$
P = u \ v_{1} \ v_{2} \ \cdots \ v_{m-1} \ w_{n} \ w_{n+1} \ \cdots \ w_{l-1} \ w
$$
Perhatikan bahwa $P$ adalah $(u, w)-$path. Terbukti $u \sim w$.

Terbukti relasi tersebut adalah relasi ekuivalen.
***
## Definition Used
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Graf]]
* [[Buat Backup/Semester 5/Pengantar Teori Graf/1. Pengantar/Keterhubungan Titik]]
* [[Buat Backup/Prerquested/Relasi dan Fungsi/Relasi Ekuivalen]]