#Teorema 

Misalkan $f: X \to Y$ maka ketiga pernyataan berikut ekivalen
1.  $f$ fungsi kontinu
2.  untuk setiap $E\subseteq X$ berlaku $f(\overline{E}) \subseteq \overline{f(E)}$
3.  untuk setiap $F \subseteq Y$ berlaku $f^{-1}(\overline{F}) \supseteq \overline{f^{-1}(F)}$

---

## Bukti

### $1 \Rightarrow 2$:
Misalkan $f$ kontinu.
    Perhatikan bahwa
    $$E \subseteq f^{-1}(f(E)) \subseteq f^{-1}\left(\overline{f(E)}\right)$$
    Karena $\overline{f(E)}$ [[Penutup Himpunan|himpunan tutup]] dan $f$ fungsi kontinu maka berdasarkan [[Fungsi Kontinu dan Himpunan Tutup|teorema]], $f^{-1}\left(\overline{f(E)}\right)$ juga himpunan tutup. Berdasarkan [[Sifat Penutup Himpunan]] didapatkan
    $$\overline{E} \subseteq \overline{f^{-1}\left(\overline{f(E)}\right)} = f^{-1}\left(\overline{f(E)}\right)$$
    Terbukti bahwa
    $$f\left(\overline{E}\right) \subseteq \overline{f(E)}$$

2.  **2 $\Rightarrow$ 3:**
    Misalkan untuk setiap $E\subseteq X$ berlaku $f(\overline{E}) \subseteq \overline{f(E)}$.
    Perhatikan bahwa $f^{-1}(F) \subseteq X$ sehingga
    $$f\left(\overline{f^{-1}(F)}\right) \subseteq \overline{f(f^{-1}(F))}$$
    
    Ambil $y \in f(f^{-1}(F))$. Berarti terdapat $x \in f^{-1}(F)$ dengan $f(x) = y$. Perhatikan bahwa $x \in f^{-1}(F)$, maka $f(x) = y \in F$. Berarti $f(f^{-1}(F)) \subseteq F$. Artinya
    $$f\left(\overline{f^{-1}(F)}\right) \subseteq \overline{f(f^{-1}(F))} \subseteq \overline{F}$$
    Ambil $x \in \overline{f^{-1}(F)}$. Maka $f(x) \in f\left(\overline{f^{-1}(F)}\right) \subseteq \overline{F}$ sehingga $x \in f^{-1}(\overline{F})$.
    
    Terbukti bahwa
    $$\overline{f^{-1}(F)} \subseteq f^{-1}(\overline{F})$$

3.  **3 $\Rightarrow$ 1:**
    Misalkan untuk setiap $F \subseteq Y$ berlaku $\overline{f^{-1}(F)} \subseteq f^{-1}(\overline{F})$. Misalkan $E$ himpunan tutup di $Y$. Artinya $\overline{E} = E$. Perhatikan bahwa
    $$\overline{f^{-1}(E)} \subseteq f^{-1}(\overline{E}) = f^{-1}(E)$$
    Jelas $f^{-1}(E) \subseteq \overline{f^{-1}(E)}$, artinya $f^{-1}(E) = \overline{f^{-1}(E)}$. Berdasarkan
    corrolary no. 1
    maka $f^{-1}(E)$ adalah himpunan tutup.
    
    Berdasarkan corrolary terbukti bahwa $f$ fungsi kontinu.