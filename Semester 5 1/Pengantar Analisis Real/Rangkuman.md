
# Chapter 4: Limits

## I. Definitions

**Definition 4.1.1 (Cluster Point)**
A point $c \in \mathbb{R}$ is a cluster point of a subset $A$ of $\mathbb{R}$ if every $\delta$-neighborhood $V_\delta(c) = (c - \delta, c + \delta)$ of $c$ contains at least one point of $A$ distinct from $c$.

**Definition 4.1.4 (Limit of a Function)**
Let $A \subseteq \mathbb{R}$, and let $c$ be a cluster point of $A$. For a function $f: A \to \mathbb{R}$, a real number $L$ is said to be a limit of $f$ at $c$ if, given any $\epsilon > 0$, there exists a $\delta > 0$ such that if $x \in A$ and $0 < |x - c| < \delta$, then $|f(x) - L| < \epsilon$.

**Definition 4.3.1 (One-Sided Limits)**
(i) Let $c \in \mathbb{R}$ be a cluster point of $A \cap (c, \infty)$. We say $L$ is a **right-hand limit** of $f$ at $c$ ($\lim_{x \to c+} f = L$) if for every $\epsilon > 0$ there exists a $\delta > 0$ such that for all $x \in A$ with $0 < x - c < \delta$, then $|f(x) - L| < \epsilon$.
(ii) Let $c \in \mathbb{R}$ be a cluster point of $A \cap (-\infty, c)$. We say $L$ is a **left-hand limit** of $f$ at $c$ ($\lim_{x \to c-} f = L$) if for every $\epsilon > 0$ there exists a $\delta > 0$ such that for all $x \in A$ with $0 < c - x < \delta$, then $|f(x) - L| < \epsilon$.

**Definition 4.3.5 (Infinite Limits)**
(i) We say that $f$ tends to $\infty$ as $x \to c$ ($\lim_{x \to c} f = \infty$) if for every $\alpha \in \mathbb{R}$ there exists $\delta > 0$ such that for all $x \in A$ with $0 < |x - c| < \delta$, then $f(x) > \alpha$.
(ii) We say that $f$ tends to $-\infty$ as $x \to c$ ($\lim_{x \to c} f = -\infty$) if for every $\beta \in \mathbb{R}$ there exists $\delta > 0$ such that for all $x \in A$ with $0 < |x - c| < \delta$, then $f(x) < \beta$.

**Definition 4.3.10 (Limits at Infinity)**
Let $A \subseteq \mathbb{R}$ and let $f: A \to \mathbb{R}$. Suppose that $(a, \infty) \subseteq A$ for some $a \in \mathbb{R}$. We say that $L \in \mathbb{R}$ is a limit of $f$ as $x \to \infty$ if given any $\epsilon > 0$ there exists $K > a$ such that for any $x > K$, then $|f(x) - L| < \epsilon$.

## II. Theorems

**Theorem 4.1.2 (Sequential Characterization of Cluster Points)**
A number $c \in \mathbb{R}$ is a cluster point of $A \subseteq \mathbb{R}$ if and only if there exists a sequence $(a_n)$ in $A$ such that $\lim(a_n) = c$ and $a_n \neq c$ for all $n \in \mathbb{N}$.

**Theorem 4.1.5 (Uniqueness of Limits)**
If $f: A \to \mathbb{R}$ and if $c$ is a cluster point of $A$, then $f$ can have only one limit at $c$.

**Theorem 4.1.8 (Sequential Criterion for Limits)**
Let $f: A \to \mathbb{R}$ and let $c$ be a cluster point of $A$. Then the following are equivalent:
(i) $\lim_{x \to c} f = L$.
(ii) For every sequence $(x_n)$ in $A$ that converges to $c$ such that $x_n \neq c$ for all $n \in \mathbb{N}$, the sequence $(f(x_n))$ converges to $L$.

**Theorem 4.2.4 (Algebraic Limit Theorem)**
Let $A \subseteq \mathbb{R}$, let $f, g: A \to \mathbb{R}$, and let $c$ be a cluster point of $A$. If $\lim_{x \to c} f = L$ and $\lim_{x \to c} g = M$, then:
(a) $\lim_{x \to c} (f + g) = L + M$, $\lim_{x \to c} (f - g) = L - M$, $\lim_{x \to c} (fg) = LM$.
(b) If $h: A \to \mathbb{R}$, if $h(x) \neq 0$ for all $x \in A$, and if $\lim_{x \to c} h = H \neq 0$, then $\lim_{x \to c} (f/h) = L/H$.

**Theorem 4.2.7 (Squeeze Theorem)**
Let $A \subseteq \mathbb{R}$, let $f, g, h: A \to \mathbb{R}$, and let $c$ be a cluster point of $A$. If $f(x) \le g(x) \le h(x)$ for all $x \in A, x \neq c$, and if $\lim_{x \to c} f = L = \lim_{x \to c} h$, then $\lim_{x \to c} g = L$.

---

# Chapter 5: Continuous Functions

## I. Definitions

**Definition 5.1.1 (Continuity at a Point)**
Let $A \subseteq \mathbb{R}$, let $f: A \to \mathbb{R}$, and let $c \in A$. We say that $f$ is continuous at $c$ if, given any number $\epsilon > 0$, there exists $\delta > 0$ such that if $x$ is any point of $A$ satisfying $|x - c| < \delta$, then $|f(x) - f(c)| < \epsilon$.

**Definition 5.1.5 (Continuity on a Set)**
Let $A \subseteq \mathbb{R}$ and let $f: A \to \mathbb{R}$. If $B$ is a subset of $A$, we say that $f$ is continuous on the set $B$ if $f$ is continuous at every point of $B$.

**Definition 5.3.1 (Bounded Function)**
A function $f: A \to \mathbb{R}$ is said to be bounded on $A$ if there exists a constant $M > 0$ such that $|f(x)| \le M$ for all $x \in A$.

**Definition 5.3.3 (Absolute Maximum/Minimum)**
Let $A \subseteq \mathbb{R}$ and let $f: A \to \mathbb{R}$. We say that $f$ has an absolute maximum on $A$ if there is a point $x^* \in A$ such that $f(x^*) \ge f(x)$ for all $x \in A$. We say that $f$ has an absolute minimum on $A$ if there is a point $x_* \in A$ such that $f(x_*) \le f(x)$ for all $x \in A$.

**Definition 5.4.1 (Uniform Continuity)**
Let $A \subseteq \mathbb{R}$ and let $f: A \to \mathbb{R}$. We say that $f$ is uniformly continuous on $A$ if for each $\epsilon > 0$ there is a $\delta(\epsilon) > 0$ such that if $x, u \in A$ are any numbers satisfying $|x - u| < \delta(\epsilon)$, then $|f(x) - f(u)| < \epsilon$.

**Definition 5.4.4 (Lipschitz Function)**
Let $A \subseteq \mathbb{R}$ and let $f: A \to \mathbb{R}$. If there exists a constant $K > 0$ such that $|f(x) - f(u)| \le K|x - u|$ for all $x, u \in A$, then $f$ is said to be a Lipschitz function on $A$.

## II. Theorems

**Theorem 5.1.3 (Sequential Criterion for Continuity)**
A function $f: A \to \mathbb{R}$ is continuous at the point $c \in A$ if and only if for every sequence $(x_n)$ in $A$ that converges to $c$, the sequence $(f(x_n))$ converges to $f(c)$.

**Theorem 5.2.1 (Combinations of Continuous Functions)**
Let $A \subseteq \mathbb{R}$, let $f$ and $g$ be functions on $A$ to $\mathbb{R}$, and let $b \in \mathbb{R}$. Suppose that $c \in A$ and that $f$ and $g$ are continuous at $c$.
(a) Then $f + g$, $f - g$, $fg$, and $bf$ are continuous at $c$.
(b) If $h: A \to \mathbb{R}$ is continuous at $c \in A$ and if $h(x) \neq 0$ for all $x \in A$, then the quotient $f/h$ is continuous at $c$.

**Theorem 5.3.2 (Boundedness Theorem)**
Let $I := [a, b]$ be a closed bounded interval and let $f: I \to \mathbb{R}$ be continuous on $I$. Then $f$ is bounded on $I$.

**Theorem 5.3.4 (Maximum-Minimum Theorem)**
Let $I := [a, b]$ be a closed bounded interval and let $f: I \to \mathbb{R}$ be continuous on $I$. Then $f$ has an absolute maximum and an absolute minimum on $I$.

**Theorem 5.3.5 (Location of Roots Theorem)**
Let $I := [a, b]$ and let $f: I \to \mathbb{R}$ be continuous on $I$. If $f(a) < 0 < f(b)$, or if $f(a) > 0 > f(b)$, then there exists a number $c \in (a, b)$ such that $f(c) = 0$.

**Theorem 5.3.7 (Bolzano's Intermediate Value Theorem)**
Let $I$ be an interval and let $f: I \to \mathbb{R}$ be continuous on $I$. If $a, b \in I$ and if $k \in \mathbb{R}$ satisfies $f(a) < k < f(b)$, then there exists a point $c \in I$ between $a$ and $b$ such that $f(c) = k$.

**Theorem 5.4.3 (Uniform Continuity Theorem)**
Let $I$ be a closed bounded interval and let $f: I \to \mathbb{R}$ be continuous on $I$. Then $f$ is uniformly continuous on $I$.

**Theorem 5.4.8 (Continuous Extension Theorem)**
A function $f$ is uniformly continuous on the interval $(a, b)$ if and only if it can be defined at the endpoints $a$ and $b$ such that the extended function is continuous on $[a, b]$.

**Theorem 5.6.5 (Continuous Inverse Theorem)**
Let $I \subseteq \mathbb{R}$ be an interval and let $f: I \to \mathbb{R}$ be strictly monotone and continuous on $I$. Then the function $g$ inverse to $f$ is strictly monotone and continuous on $J := f(I)$.

---

# Chapter 6: Differentiation

## I. Definitions

**Definition 6.1.1 (The Derivative)**
Let $I \subseteq \mathbb{R}$ be an interval, let $f: I \to \mathbb{R}$, and let $c \in I$. We say that a real number $L$ is the derivative of $f$ at $c$ if given any $\epsilon > 0$ there exists $\delta(\epsilon) > 0$ such that if $x \in I$ satisfies $0 < |x - c| < \delta(\epsilon)$, then
$$\left| \frac{f(x) - f(c)}{x - c} - L \right| < \epsilon$$
In this case we say that $f$ is differentiable at $c$, and we write $f'(c)$ for $L$.

**Definition (Relative Extremum)**
Let $I \subseteq \mathbb{R}$ be an interval and let $f: I \to \mathbb{R}$. We say that $f$ has a **relative maximum** at $c \in I$ if there exists a neighborhood $V_\delta(c)$ of $c$ such that $f(x) \le f(c)$ for all $x \in V_\delta(c) \cap I$. We say $f$ has a **relative minimum** at $c$ if there exists a neighborhood $V_\delta(c)$ such that $f(c) \le f(x)$ for all $x \in V_\delta(c) \cap I$.

**Definition (Increasing/Decreasing)**
Let $I \subseteq \mathbb{R}$ be an interval and let $f: I \to \mathbb{R}$. We say $f$ is **increasing** on $I$ if $x_1, x_2 \in I$ with $x_1 < x_2$ implies $f(x_1) \le f(x_2)$. We say $f$ is **decreasing** on $I$ if $x_1 < x_2$ implies $f(x_1) \ge f(x_2)$.

## II. Theorems

**Theorem 6.1.2 (Differentiability Implies Continuity)**
If $f: I \to \mathbb{R}$ has a derivative at $c \in I$, then $f$ is continuous at $c$.

**Theorem 6.1.3 (Algebra of Derivatives)**
Let $I \subseteq \mathbb{R}$ be an interval, let $c \in I$, and let $f: I \to \mathbb{R}$ and $g: I \to \mathbb{R}$ be functions that are differentiable at $c$. Then:
(a) If $\alpha \in \mathbb{R}$, then $(\alpha f)'(c) = \alpha f'(c)$.
(b) $(f + g)'(c) = f'(c) + g'(c)$.
(c) **Product Rule:** $(fg)'(c) = f'(c)g(c) + f(c)g'(c)$.
(d) **Quotient Rule:** If $g(c) \neq 0$, then $(f/g)'(c) = \frac{f'(c)g(c) - f(c)g'(c)}{(g(c))^2}$.

**Theorem 6.1.5 (Carathéodory's Theorem)**
Let $f$ be defined on an interval $I$ containing the point $c$. Then $f$ is differentiable at $c$ if and only if there exists a function $\varphi$ on $I$ that is continuous at $c$ and satisfies $f(x) - f(c) = \varphi(x)(x - c)$ for $x \in I$. In this case, $\varphi(c) = f'(c)$.

**Theorem 6.1.6 (Chain Rule)**
Let $I, J$ be intervals in $\mathbb{R}$, let $g: I \to \mathbb{R}$ and $f: J \to \mathbb{R}$ be functions such that $f(J) \subseteq I$, and let $c \in J$. If $f$ is differentiable at $c$ and if $g$ is differentiable at $f(c)$, then the composite function $g \circ f$ is differentiable at $c$ and $(g \circ f)'(c) = g'(f(c)) \cdot f'(c)$.

**Theorem 6.2.1 (Interior Extremum Theorem)**
Let $c$ be an interior point of the interval $I$ at which $f: I \to \mathbb{R}$ has a relative extremum. If the derivative of $f$ at $c$ exists, then $f'(c) = 0$.

**Theorem 6.2.3 (Rolle's Theorem)**
Suppose that $f$ is continuous on a closed interval $I := [a, b]$, that the derivative $f'$ exists at every point of the open interval $(a, b)$, and that $f(a) = f(b) = 0$. Then there exists at least one point $c$ in $(a, b)$ such that $f'(c) = 0$.

**Theorem 6.2.4 (Mean Value Theorem)**
Suppose that $f$ is continuous on a closed interval $I := [a, b]$, and that $f$ has a derivative in the open interval $(a, b)$. Then there exists at least one point $c$ in $(a, b)$ such that $f(b) - f(a) = f'(c)(b - a)$.

**Theorem 6.2.12 (Darboux's Theorem)**
If $f$ is differentiable on $I = [a, b]$ and if $k$ is a number between $f'(a)$ and $f'(b)$, then there is at least one point $c$ in $(a, b)$ such that $f'(c) = k$.

**Theorem 6.3.3 (L'Hospital's Rule I)**
Let $-\infty \le a < b \le \infty$ and let $f, g$ be differentiable on $(a, b)$ such that $g'(x) \neq 0$ for all $x \in (a, b)$. Suppose that $\lim_{x \to a+} f(x) = 0 = \lim_{x \to a+} g(x)$.
(a) If $\lim_{x \to a+} \frac{f'(x)}{g'(x)} = L \in \mathbb{R}$, then $\lim_{x \to a+} \frac{f(x)}{g(x)} = L$.
(b) If $\lim_{x \to a+} \frac{f'(x)}{g'(x)} = L \in \{-\infty, \infty\}$, then $\lim_{x \to a+} \frac{f(x)}{g(x)} = L$.

**Theorem 6.4.1 (Taylor's Theorem)**
Let $n \in \mathbb{N}$, let $I := [a, b]$, and let $f: I \to \mathbb{R}$ be such that $f$ and its derivatives $f', f'', \dots, f^{(n)}$ are continuous on $I$ and that $f^{(n+1)}$ exists on $(a, b)$. If $x_0 \in I$, then for any $x$ in $I$ there exists a point $c$ between $x$ and $x_0$ such that
$$f(x) = f(x_0) + \frac{f'(x_0)}{1!}(x - x_0) + \dots + \frac{f^{(n)}(x_0)}{n!}(x - x_0)^n + \frac{f^{(n+1)}(c)}{(n+1)!}(x - x_0)^{n+1}$$