#Teorema 

Misalkan suatu bilangan asli $p>1$. Bilangan $p$ adalah bilangan *prima* jika dan hanya jika $p$ memiliki tepat dua faktor positif yakni $1$ dan .

## Bukti

### $\Rightarrow$
Karena $p > 1$ serta $1 | p$ dan $p | p$ berarti $p$ pasti memiliki setidaknya dua faktor positif. Andaikan terdapat bilangan prima dengan lebih dari dua faktor positif. Misalkan terdapat $d \in \mathbb{N}$ dengan $1 < d < p$ dan $d | p$. 

Perhatikan bahwa jelas karena $p > d$ maka $p \ |\not \ d$. Namun, jelas karena $d|d$ dan $d | p$ maka $d | FPB(d, p)$ sehingga $FPB(d, p) \neq 1$. Berarti terdapat $d \in \mathbb{N}$ sehingga $p \ |\not\ d$ dan $FPB(d, p) \neq 1$, kontradiksi dengan fakta bahwa $p$ adalah bilangan [[Bilangan Prima|prima]].

Berarti pengandaian salah. Terbukti setiap bilangan prima $p$ memiliki tepat dua faktor positif yakni $1$ dan $p$.

### $\Leftarrow$
Misalkan $p$ bilangan asli yang memiliki tepat dua faktor positif yakni $1$ dan $p$. Ambil sembarang bilangan asli $n$ dengan $p \ |\not\ n$. 

Andaikan $FPB(p, n) = d \neq 1$. Misalkan $d^*$ adalah [[Dekomposisi Prima|faktor prima terkecil]]
dari $d$. Perhatikan bahwa $p \ |\not\  \ n$ maka $p \ | \not  \ d$. Dengan kata lain $1 < d^* < p$. Berarti $d^*$ adalah faktor lain dari $p$, kontradiksi dengan fakta bahwa $p$ memiliki tepat dua faktor positif.

***
## Definition Used 
 * [[Bilangan Prima]]
 * [[Keterbagian]]
