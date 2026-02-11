#Teorema 

Misalkan suatu grup $(G, *)$, berlaku:
1.  **Ketunggalan Identitas**. Jika $e, e'$ adalah identitas dari $G$ maka $e = e'$
2.  **Ketunggalan Invers**. Jika $b_1$ dan $b_2$ adalah invers dari $a$ maka $b_1 = b_2$ ^cfe6f6
3.  **Invers dari Invers**. $(a^{-1})^{-1} = a$ ^6fb1e8
4.  **Invers**. $(a*b)^{-1} = b^{-1} * a^{-1}$

## Bukti
Misalkan suatu grup $(G, *)$
### Sifat 1
Misalkan $e, e'$ identitas di $G$ maka 
    $$e = e *e' = e' \quad $$
### Sifat 2
 Misalkan $b_1,b_2$ invers dari $a$ maka
    $$
    \begin{align*}
     b_1 &= e * b_1 && \text{identitas } e \\
     &= (b_2*a) * b_1 && b_2 \text{ invers } a \\
     &= b_2*(a*b_1) && \text{asosiatif grup} \\
     &= b_2*e && b_1 \text{ invers } a \\
     &= b_2 \quad  && \text{identitas } e
    \end{align*}
    $$
### Sifat 3
Misalkan  $a\in G$ maka
    $$
    \begin{align*}
     (a^{-1})^{-1} &= e * (a^{-1})^{-1} && \text{identitas } e \\
     &= (a*a^{-1}) * (a^{-1})^{-1} && \text{invers } a \\
     &= a*(a^{-1}*(a^{-1})^{-1}) && \text{asosiatif grup} \\
     &= a*e && b_1 \text{ invers } a^{-1} \\
     &= a \quad  && \text{identitas } e
    \end{align*}
    $$
### Sifat 4
Misalkan $a, b \in G$
    $$
    \begin{align*}
     (a*b)^{-1} &= e * (a*b)^{-1} && \text{identitas } e \\
     &= (b^{-1}*b) * (a*b)^{-1} && \text{invers } b \\
     &= (b^{-1}*(e*b)) * (a*b)^{-1}&& \text{identitas } e \\
     & = (b^{-1}*((a^{-1}*a)*b)) * (a*b)^{-1} && \text{invers } a \\
     &= (b^{-1}*a^{-1})*(a*b)*(a*b)^{-1} && \text{asosiatif grup} \\
     &= (b^{-1}*a^{-1})*e && b_1 \text{ invers } a*b \\
     &= b^{-1}*a^{-1} \quad  && \text{identitas } e
    \end{align*}
    $$

***
## Definition Used 
 * [[Buat Backup/Semester 5/Struktur Aljabar/Grup/Grup]]