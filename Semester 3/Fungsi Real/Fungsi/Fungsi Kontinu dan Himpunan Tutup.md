#Teorema 

Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$.  Fungsi $f$ kontinu pada himpunan $A$ **jika dan hanya jika** berlaku
$$\forall \ \mathcal{F} \subseteq Y \text{ himpunan tutup di } Y \text{ maka } f^{-1}(\mathcal{F}) \text{ adalah himpunan tutup relatif di } A$$

---

## Bukti

### **$\Rightarrow:$**
Misalkan $f$ kontinu di $A$. Ambil himpunan tutup $F \subseteq Y$. Perhatikan bahwa $F^c$ adalah himpunan buka. Berdasarkan [[Fungsi Kontinu dan Himpunan Buka|teorema]] $f^{-1}(F^c)$ juga himpunan buka di $A$.
    
Perhatikan bahwa
    $$x \in f^{-1}(F^c) \iff f(x) \in F^c \iff f(x) \not\in F \iff x \not\in f^{-1}(F) \iff x \in \left(f^{-1}(F)\right)^c$$
    Berarti $\left(f^{-1}(F)\right)^c = f^{-1}(F^c)$ juga himpunan buka di $A$.
    
Terbukti bahwa $f^{-1}(F)$ juga himpunan tutup relatif di $A$.

###  **$\Leftarrow:$**
Misalkan untuk setiap himpunan tutup $F \subseteq Y: \ f^{-1}(F)$ juga himpunan tutup relatif di $A$. Akan ditunjukkan $f$ kontinu.
    
Ambil $O \subseteq Y$ himpunan buka. Perhatikan bahwa $O^c$ himpunan tutup sehingga berdasarkan premis $\left(f^{-1}(O)\right)^c = f^{-1}(O^c)$ himpunan tutup di $A$. Berarti $f^{-1}(O)$ himpunan buka di $A$.
    
Berdasarkan [[Fungsi Kontinu dan Himpunan Buka|teorema]] terbukti bahwa $f$ kontinu.

***
## Definition Used 
 * [[Ruang Metrik]]
 * [[Fungsi]]
 * [[Fungsi Kontinu]]
 * [[Himpunan Buka]]
 * [[Himpunan Tutup]]