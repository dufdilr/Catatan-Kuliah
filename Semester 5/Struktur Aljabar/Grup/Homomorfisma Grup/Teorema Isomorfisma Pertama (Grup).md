#Teorema 

Misalkan $f:A \to B$ adalah homomorfisma grup maka
$$
A/\mathrm{Inti}(f) \cong f(A)
$$

```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}[row sep=huge, column sep=huge]
    % Top left node (G) to Top right node (H)
    A \arrow[r, "f"] \arrow[d, "\pi"'] 
    & f(A) \\
    % Bottom left node (Quotient Group)
    A/\ker(f) \arrow[ur, dashed, "\phi"']
\end{tikzcd}
\end{document}
```

---
## Bukti

Tulis $\mathrm{Inti}(f) = C$. Berdasarkan [[Inti Homomorfisma Sebagai Subgrup Normal|teorema]], maka $C$ membentuk subgrup normal dari $A$. Artinya, $A/C$ terdefinisi dengan baik sebagai grup. Tinjau pemetaan
$$
\phi:A/C \to f(A)
$$
dengan $\phi(aC) = f(a)$. Akan ditunjukkan $\phi$ adalah isomorfisma.

Ambil $a_{1}C, a_{2}C \in A/C$. Perhatikan bahwa
$$
\phi(a_{1}C \cdot a_{2}C) = \phi((a_{1}a_{2})C) = f(a_{1}a_{2}) = f(a_{1})\cdot f(a_{2}) = \phi(a_{1}C) \cdot \phi(a_{2}C)
$$
Maka $\phi$ adalah homomorfisma.

Lebih lanjut, ambil $a_{1}C, a_{2}C \in A/C$ sedemikian sehingga $\phi(a_{1}C) = \phi(a_{2}C)$. Artinya
$$
f(a_{1}) = f(a_{2}) \quad\implies\quad f(a_{1})(f(a_{2}))^{-1}=f(a_{1}a_{2}^{-1}) = e \quad\implies\quad a_{1}a_{2}^{-1} \in \mathrm{Inti}(f) = C
$$
Karena $a_{1}a_{2}^{-1}\in C$, berdasarkan [[Himpunan Hasil Bagi dan Koset Grup|teorema]] maka $a_{1}C = a_{2}C$. Terbukti $\phi$ bersifat injektif.

Lebih lanjut, ambil $b \in f(A)$. Per definisi maka terdapat $a \in A$ sehingga $f(a) = b$. Perhatikan bahwa
$$
\phi(aC) = f(a) = b
$$
Maka $\phi$ bersifat surjektif.

Karena $\phi$ adalah homomorfisma yang injektif dan surjektif maka $\phi$ adalah isomorfisma grup. Terbukti bahwa
$$
A/\mathrm{Inti}(f) \cong f(A)
$$

***
## Definition Used 
 * [[Homomorfisma (Grup)]]
 * [[Inti Homomorfisma Grup]]
 * [[Isomorfisma (Grup)]]
 * [[Grup Hasil Bagi]]
 * [[Koset Grup]]
