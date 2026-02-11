#Teorema

Fungsi Euler-Phi $\varphi$ adalah fungsi multiplikatif. Dengan kata lain, jika $(m, n) = 1$ maka
$$\varphi(mn)= \varphi(m)\varphi(n)$$

---
## Bukti

Tinjau fungsi $f: U_{mn} \to U_m \times U_n$ dengan $f([x]_{mn}) = ([x]_m, [x]_n)$.
Akan ditunjukkan bahwa fungsi $f$ ini terdefinisi dengan baik (*well-defined*) dan bijektif.

1.  **Well-defined**
    Ambil $[x]_{mn} \in U_{mn}$. Ini berarti $(x, mn) = 1$. Akibatnya, $(x, m) = 1$ dan $(x, n) = 1$, sehingga $[x]_m \in U_m$ dan $[x]_n \in U_n$. Dengan kata lain, $f: U_{mn} \to U_m \times U_n$.
    
    Sekarang, misalkan $[x]_{mn} = [y]_{mn}$. Akan ditunjukkan $f([x]_{mn}) = f([y]_{mn})$.
    
	 Karena $[x]_{mn} = [y]_{mn}$ maka $mn \mid (x - y)$. Berdasarkan [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Sifat Keterbagian#^39704a|sifat keterbagian]] dapat simpulkan bahwa $m \mid (x - y)$ dan $n \mid (x - y)$. Dengan kata lain, $[x]_m = [y]_m$ dan $[x]_n = [y]_n$. Sehingga
    $$f([x]_{mn}) = ([x]_m, [x]_n) = ([y]_m, [y]_n) = f([y]_{mn})$$
    Terbukti bahwa fungsi $f$ adalah *well-defined*.

2.  **Injektif**
    Misalkan $f([x]_{mn}) = f([y]_{mn})$. Berdasarkan definisi $f$, ini berarti:
        $$([x]_m, [x]_n) = ([y]_m, [y]_n)$$
    Akibatnya $[x]_m = [y]_m$ dan $[x]_n = [y]_n$. Dengan kata lain, $m \mid (x - y)$ dan $n \mid (x - y)$. Karena $(m, n) = 1$, [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Bilangan Bulat/Perkalian Relatif Prima]] $mn \mid (x - y)$. Dengan kata lain
    $$[x]_{mn} = [y]_{mn}$$
    Terbukti $f$ adalah injektif.

3.  **Surjektif**
    Ambil $([a]_m, [b]_n) \in U_m \times U_n$. Berdasarkan [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Chinese Remainder Theorem]], karena $(m,n)=1$, maka ada solusi tunggal $x$ (modulo $mn$) untuk sistem kongruensi:
        $$x \equiv a \pmod{m} \quad \text{dan} \quad x \equiv b \pmod{n}$$
    Untuk $x$ ini, berlaku $f([x]_{mn}) = ([x]_m, [x]_n) = ([a]_m, [b]_n)$.  Karena setiap elemen di kodomain memiliki pra-peta, maka terbukti $f$ adalah surjektif.

Karena $f$ adalah fungsi yang bijektif (injektif dan surjektif) dari $U_{mn}$ ke $U_m \times U_n$, maka kedua himpunan tersebut harus memiliki jumlah elemen yang sama (kardinalitas yang sama).
$$|U_{mn}| = |U_m \times U_n| = |U_m| \cdot |U_n|$$
Dengan definisi fungsi $\varphi$, kita dapatkan:
$$\varphi(mn) = \varphi(m) \varphi(n)$$

***
## Definition Used 
 * [[Buat Backup/Semester 4/Struktur Bilangan Bulat/Struktur Modulo Bilangan/Fungsi Euler-Phi]]
 * [[Buat Backup/Semester 4/Pengantar Teori Bilangan/Fungsi Aritmatika/Fungsi Multiplikatif]]