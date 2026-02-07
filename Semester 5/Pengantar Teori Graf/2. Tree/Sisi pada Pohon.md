#Teorema 

Misalkan $T$ adalah graf pohon dengan $n$ titik, maka $T$ memiliki $n -1$ sisi.

## Bukti

Akan dibuktikan menggunakan prinsip induksi matematika.
### Kasus Basis
Jelas untuk pohon dengan 1 titik, tidak ada sisinya. Lebih lanjut, untuk pohon dengan 2 titik, karena $T$ terhubung dan sederhana maka hanya ada 1 sisi. Terbukti untuk kasus basis.

### Kasus Induksi
Misalkan untuk suatu $n \in \mathbb{N}$, berlaku: setiap pohon dengan $n$ titik memiliki $n-1$ sisi. Ambil sembarang $T$, pohon dengan $(n+1)$ titik. Akan ditunjukkan $T$ memuat $n$ sisi.

Perhatikan [[Daun pada Pohon|bahwa]], $T$ memiliki daun. Misalkan $v$ adalah daun dari $T$. Tinjau $G = T - {v}$. Jelas bahwa $G$ tetap terhubung dan tidak memuat siklik. Maka $G$ adalah pohon dengan $n$ titik. Artinya $G$ memuat $n -1$ sisi. Lebih lanjut, $T$ berarti menghubungkan satu sisi dari $v$ ke $G$. Berarti terbukti, $T$ memuat $n$ sisi.

### Kesimpulan
Berdasarkan prinsip induksi matematika, terbukti setiap pohon dengan $n$ titik memiliki $n - 1$ sisi.

***
## Definition Used 
 * [[Graf]]
 * [[Pohon (Graf)]]
 * [[Daun (Graf)]]
 