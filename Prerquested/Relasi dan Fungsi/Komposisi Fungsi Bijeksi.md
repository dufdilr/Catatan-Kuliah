#Teorema 
Misalkan $A, B, C$ himpunan serta $f:A \to B$ dan $g:B \to C$ keduanya adalah fungsi bijektif. Maka
$$
g\circ f : A \to C
$$
juga merupakan fungsi bijeksi.

---
## Bukti
### Surjektif
Ambil $c \in C$. Karena $f, g$ bijektif maka terdapat $b \in B$ sehingga $g(b) = c$ dan terdapat $a \in A$ sehingga $f(a) = b$. Artinya
$$
g\circ f(a) = g(b) =  c
$$
Artinya $g\circ f$ bersifat surjektif.

### Injektif
Ambil $a_{1}, a_{2} \in A$ sehingga $g\circ f(a_{1}) = g\circ f(a_{2})$. Artinya $g(f(a_{1})) = g(f(a_{2}))$. Karena $g$ bijektif maka $f(a_{1}) = f(a_{2})$. Karena $f$ bijektif maka $a_{1}=a_{2}$. Terbukti $g \circ f$ bersifat injektif

Karena $g \circ f$ bersifat injektif dan surjektif maka $g \circ f$ juga bersifat bijektif.

***
## Definition Used 
 * [[Buat Backup/Prerquested/Naive Set/Himpunan]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi Bijektif]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Komposisi Fungsi]]