#Teorema 

Misalkan $G$ adalah pohon dengan $n$ titik maka $G$ memiliki $n-1$ sisi.

---
## Bukti
Definisikan untuk setiap bilangan asli $n$, 
$$
P(n):= \text{Pohon dengan $n$ titik memiliki $n-1$ sisi}
$$
Akan ditunjukkan untuk setiap bilangan asli $n$, $P(n)$ benar dengan induksi
### Kasus Basis
Untuk pohon dengan 1 titik jelas memiliki 0 sisi. Terbukti $P(1)$ benar.

### Langkah Induksi

Asumsikan untuk suatu bilangan asli $k$, $P(k)$ bernilai benar. Artinya, setiap pohon dengan $k$ titik memiliki $k-1$ sisi.

  

Misalkan $T$ suatu pohon dengan $k+1$ titik. Pilih sembarang $u$ [[Daun pada Pohon]] $T$. Tinjau

$$

T^* = T - \{u\}

$$

Perhatikan bahwa $T^*$ terhubung dan tidak memuat siklus. Artinya $T^*$ adalah pohon dengan $k$ titik. Berdasarkan hipotesis induksi, maka $T^*$ memiliki $k-1$ sisi.

  

Perhatikan bahwa $u$ hanya berinsidensi dengan 1 sisi. Artinya

$$

E(T) = E(T^*) + 1 = (k-1) + 1 = k

$$

Artinya $T$ memiliki $k$ sisi. Terbukti $P(k+1)$ benar.

  

### Kesimpulan

  

Berdasarkan [[Prinsip Induksi Matematika]] terbukti $P(n)$ benar untuk setiap bilangan asli $n$.

  
  

***

## Definition Used

* [[Pohon (Graf)]]

* [[Daun (Graf)]]
