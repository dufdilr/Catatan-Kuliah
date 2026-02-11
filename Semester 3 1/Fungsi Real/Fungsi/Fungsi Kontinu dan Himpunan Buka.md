#Teorema 

Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$.  Fungsi $f$ kontinu pada himpunan $A$ **jika dan hanya jika** berlaku
$$\forall \ \mathcal{O} \subseteq Y \text{ himpunan buka di } Y \text{ maka } f^{-1}(\mathcal{O}) \text{ adalah himpunan buka relatif di } A$$

---

## Bukti

### **$\Rightarrow:$**
Misalkan $f$ kontinu di $A$. Ambil $\mathcal{O} \subseteq Y$ himpunan buka. Tinjau $f^{-1}(\mathcal{O})$.

Ambil $x \in f^{-1}(\mathcal{O})$. Artinya terdapat $y \in \mathcal{O}$ sehingga $f(x) = y$. Karena $\mathcal{O}$ himpunan buka maka terdapat $r>0$ sehingga $B_Y(y, r) \subseteq \mathcal{O}$.
    
Karena $f$ kontinu di $A$ maka terdapat $\delta > 0$ sehingga untuk setiap $a \in A$
    $$d_X(x, a)<\delta \quad \Rightarrow \quad d_Y(f(x), f(a)) < r$$
    Ambil $x'\in B_X(x, \delta)$. Artinya
    $$d_X(x, x ') < \delta \quad \Rightarrow \quad d_Y(f(x), f(x')) < r \quad \Rightarrow \quad f(x') \in B_Y(y, r) \subseteq\mathcal{O}$$
    Karena $f(x') \in \mathcal{O}$ maka $x' \in f^{-1}(\mathcal{O})$. Berarti, $B_X(x, \delta) \subseteq f^{-1}(\mathcal{O})$
    Terbukti bahwa $f^{-1}(\mathcal{O})$ adalah himpunan buka relatif di $A$

###  **$\Leftarrow:$**
Misalkan untuk setiap himpunan buka $\mathcal{O} \subseteq Y, \ f^{-1}(O)$ juga himpunan buka pada $A$. Ambil $a \in A$. Ambil $\varepsilon > 0$. Tinjau $B(f(a), \varepsilon)$. Perhatikan bahwa $B_Y(f(a), \varepsilon)$ adalah himpunan buka. Berdasarkan hipotesis maka $f^{-1}\left(B_Y(f(a), \varepsilon)\right)$ juga himpunan buka.
    
Jelas $f(a) \in B_Y(f(a), \varepsilon)$. Artinya $a \in f^{-1}\left(B_Y(f(a), \varepsilon)\right)$. Karena himpunan buka maka terdapat $\delta > 0$ sehingga $$B_X(c, \delta) \subseteq f^{-1}\left(B_Y(f(a), \varepsilon)\right)$$
    Artinya $\forall x \in B_X(c, \delta): \ f(x) \in B_Y(f(a), \varepsilon)$, atau dengan kata lain jika $d_X(x, c) < \delta \ \Rightarrow \ d_Y(f(x), f(c)) < \varepsilon$. Terbukti bahwa $f$ fungsi kontinu di $A$.

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi]]
 * [[Buat Backup/Semester 3/Fungsi Real/Topologi/Himpunan Buka]]
 * [[Buat Backup/Semester 3 1/Fungsi Real/Fungsi/Fungsi Kontinu]]