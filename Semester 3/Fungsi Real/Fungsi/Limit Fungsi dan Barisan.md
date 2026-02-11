#Teorema

Misalkan $(X, d_X)$ dan $(Y, d_Y)$ ruang metrik dan $A \subseteq X$. Misalkan pula fungsi $f: A \to Y$ serta titik limit $c \in A'$. Berlaku $\displaystyle \lim_{x \to c} f(x) = l$ **jika dan hanya jika**
$$\forall \{x_n\} \subseteq A, x_n \neq c:\ x_n \to c \ \Rightarrow \ f\{x_n\} \to l$$

---

## Bukti

### **$\Rightarrow:$**
Misalkan $\displaystyle \lim_{x \to c} f(x) = l$. Ambil $\{x_n\} \subseteq A$ dengan $x_n \to c$. Ambil $\varepsilon > 0$.
    $$
    \begin{align*}
    \exists \ \delta > 0, \ \forall x \in A :&\quad 0 < d_X(x, c) < \delta \Rightarrow d_Y(f(x), l) < \varepsilon \\
    \exists N \in \mathbb{N}, \ \forall n>N: & \quad d_X(x_n, c) < \delta
    \end{align*}
    $$
    Perhatikan bahwa untuk setiap $n > N$ berlaku
    $$d_X(x_n, c) < \delta \quad \Rightarrow \quad d_Y(f\{x_n\}, l) < \varepsilon$$
    Terbukti bahwa jika $x_n \to c$ maka $f\{x_n\} \to l$

### **$\Leftarrow:$**
Misalkan jika $x_n \to c$ maka $f\{x_n\} \to l$. Andaikan $\displaystyle \lim_{x \to c} f(x) \neq l$. Artinya, terdapat $\varepsilon > 0$ sehingga untuk setiap $r > 0$ terdapat $x \in A$ dengan
    $$0 < d_X(x, c) < r \quad \text{ namun }\quad d_Y(f(x), l) \ge \varepsilon$$
    Pilih $x_n$ sehingga $0 < d_X(x_n, c) < 1/n$ namun $d_Y(f\{x_n\}, l) \ge \varepsilon$. Perhatikan bahwa $x_n \to c$ namun $f\{x_n\} \not\to l$, kontradiksi dengan hipotesa jika $x_n \to c$ maka $f\{x_n\} \to l$. Artinya pengandaian salah.
    
Terbukti bahwa $\displaystyle \lim_{x \to c} f(x) = l$

***
## Definition Used 
 * [[Buat Backup/Semester 3/Fungsi Real/Ruang Metrik/Ruang Metrik]]
 * [[Buat Backup/Prerquested/Relasi dan Fungsi/Fungsi]]
 * [[Buat Backup/Semester 3/Fungsi Real/Fungsi/Limit Fungsi]]
 * [[Buat Backup/Semester 3/Fungsi Real/Barisan/Barisan Konvergen (Metrik)|Barisan Konvergen (Metrik)]]
