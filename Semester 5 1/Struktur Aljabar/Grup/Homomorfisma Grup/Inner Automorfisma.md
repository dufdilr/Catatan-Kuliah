#Definisi #Teorema 
Misalkan $A$ suatu grup dan $a \in A$. Definisikan **Automorfisma Dalam** pada $A$ adalah
$$
f_a (x) = axa^{-1}
$$
untuk setiap $x \in A$. Pemetaan ini membentuk automorfisma pada $A$. Lebih lanjut, himpunan
$$
\mathrm{Inn}(A) := \{ f_a(x) \mapsto axa^{-1} \ | \ a \in A \} \subseteq \text{Aut}\left({A}\right)
$$

---
## Bukti Automorfisma
### Homomorfisma
Ambil $x, y \in A$. Perhatikan bahwa
$$
f_a(xy) = axya^{-1} = axeya^{-1} = axa^{-1}aya^{-1} = f_a(x)f_a(y)
$$
maka $f_a$ adalah homomorfisma

### Injektif
Ambil $x, y \in A$ sehingga $f_a(x) = f_a(y)$. Berdasarkan [[Hukum Pembatalan Grup]] maka
$$
\begin{align*}
axa^{-1} = aya^{-1} \quad\implies\quad x = y
\end{align*}
$$
Terbukti, $f_a$ bersifat injektif.

### Surjektif
Ambil $y \in A$. Pilih $x = a^{-1}ya$. Perhatikan bahwa
$$
f_a(x) = axa^{-1}=aa^{-1}yaa^{-1} = y
$$
Terbukti, $f_a$ bersifat surjektif.

Terbukti, $f_a$ automorfisma sehingga
$$
\mathrm{Inn}(A) \subseteq \text{Aut}\left({A}\right)
$$
***
## Definition Used 
 * [[Grup]]
 * [[Automorfisma Grup]]