#Teorema 

Jika $p$ adalah bilangan prima dan $p \mid (a_1a_2\cdots a_n)$, maka $p \mid a_i$ untuk suatu $i \in \{1, 2, \dots, n\}$.

***

## Bukti

Pembuktian akan dilakukan dengan induksi matematika pada $n$.

* **Basis Induksi (n=1):**
    Jika $p \mid a_1$, maka pernyataan ini jelas benar.

* **Langkah Induksi:**
    Asumsikan jika $p | a_{1}a_{2}\cdots a_{n-1}$, maka $p|a_{i}$ untuk suatu $i \in \{ 1, 2, \dots, n-1 \}$. Misalkan diberikan $p \mid (a_1a_2\cdots a_{n-1}a_n)$.
    
    Ada dua kemungkinan untuk $a_n$:
    1.  Jika $p \mid a_n$, maka teorema terbukti.
    2.  Jika $p \nmid a_n$, karena  adalah bilangan prima dan  maka $(p, a_n) = 1$**.

        Berdasarkan[[Hukum Pembatalan Keterbagian| sifat pembatalan]] dapat disimpulkan
        $$p \mid (a_1a_2\cdots a_{n-1})$$
        Berdasarkan hipotesis induksi,  maka haruslah $p \mid a_i$ untuk suatu $i \in \{1, 2, \dots, n-1\}$.

Dalam kedua kasus, kita menemukan bahwa $p$ membagi salah satu $a_i$. Berdasarkan [[Prinsip Induksi Matematika|prinsip induksi matematika]], teorema ini terbukti benar. ■

***
## Definition Used:
* [[Bilangan Prima]]