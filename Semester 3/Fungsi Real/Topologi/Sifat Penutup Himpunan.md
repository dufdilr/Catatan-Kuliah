#Teorema 

Misalkan $(X, d)$ ruang metrik. Misalkan pula $E, F$ subhimpunan $X$ serta $\overline{E}, \overline{F}$ adalah himpunan penutup dari $E, F$ berturut-turut. Maka berlaku
1. $E$ himpunan tutup jika dan hanya jika $E = \overline{E}$ ^e1ad0a
2.  Jika $E \subseteq F$ maka $\overline{E} \subseteq \overline{F}$ ^738419
3.  $\overline{E \cup F} = \overline{E} \cup \overline{F}$
4.  $\overline{E \cap F} \subseteq \overline{E} \cap \overline{F}$

---

## Bukti

### Sifat 1
#### $\Rightarrow$
Misalkan $E$ himpunan tutup. Jelas $E \subseteq E'$. Karena $E$ tutup [[Himpunan Tutup dan Himpunan Titik Limit|maka]] $E' \subseteq E$ . Terbukti $E' = E$.
#### $\Leftarrow$
Misalkan  $E' = E$ maka $E' \subseteq E$  [[Himpunan Tutup dan Himpunan Titik Limit|sehingga]] $E$ himpunan tutup. 

### Sifat 2
Berdasarkan [[Sifat Himpunan Titik Limit#^c3b08e|teorema]] jika $E \subseteq F$
    $$\overline{E} = E \cup E' \subseteq F \cup F' = \overline{F}$$

### Sifat 3
Berdasarkan [[Sifat Himpunan Titik Limit#^a3c017|teorema]]
    $$
    \begin{align*}
    \overline{E \cup F} = (E\cup F) \cup (E\cup F)' = (E \cup F) \cup (E' \cup F') = (E \cup E') \cup (F \cup F') = \overline{E} \cup \overline{F}
    \end{align*}
    $$
### Sifat 4
Berdasarkan [[Sifat Himpunan Titik Limit#^69421e|teorema]]
    $$
    \begin{align*}
    \overline{E \cap F} &= (E\cap F) \cup (E\cap F)' \subseteq (E \cap F) \cup (E' \cap F') \\
    &\subseteq (E \cup E') \cap (F \cup F') \\
    &= \overline{E} \cap \overline{F}
    \end{align*}
    $$

***
## Definition Used 
 * [[Ruang Metrik]]
 * [[Penutup Himpunan]]
 * [[Himpunan Tutup]]
 
