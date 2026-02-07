#Teorema 
Misalkan $V$ suatu ruang vektor atas $\mathbb{F}$ dan $T \in \mathcal{L}(V)$ dan $\lambda \in \mathbb{F}$. Berlaku
$$
\lambda \text{ nilai eigen dari } T \quad \iff \quad \text{Eig}_{\lambda}(T) \neq \{ \mathbf{0_V} \}
$$

---
## Bukti

### $\Rightarrow$
Misalkan $\lambda$ adalah nilai eigen dari $T$. Artinya terdapat $v \in V$ dengan $v \neq \mathbf{0_V}$ sehingga
$$
T(v) = \lambda v
$$
Artinya $v \in \text{Eig}_{\lambda}(T)$. Terbukti $\text{Eig}_{\lambda}(T) \neq \{ \mathbf{0_V} \}$.

### $\Leftarrow$
Misalkan $\text{Eig}_{\lambda}(T) \neq \{ \mathbf{0_V} \}$. [[Ruang Eigen#^de6d31|Jelas]], $\text{Eig}_{\lambda}(T) \supsetneq \{ \mathbf{0_V} \}$, berarti terdapat $v \neq \mathbf{0_V}$ dengan $v \in \text{Eig}_{\lambda}(T)$, artinya $T(v) = \lambda v$. Berarti, $\lambda$ adalah nilai eigen dari $T$.

***
## Definition Used 
 * [[Ruang Vektor]]
 * [[Pemetaan Linear]]
 * [[Ruang Eigen]]
 * [[Vektor dan Nilai Eigen]]