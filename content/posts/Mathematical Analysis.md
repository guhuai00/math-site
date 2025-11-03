---
title: "Mathematical Analysis"
date: 2025-11-03T10:00:00+08:00
description: "Notes for Mathematical Analysis, based on baby rudin"
featured_image: "/images/notebook.jpg"
categories: "Notes"
---



# Number System

1. Concepts:
	1. ordered sets
	2. $sup/inf$
	3. least-upper-bound property：
		If $E\subset S$ , $E$ is not empty, and $E$ is bounded above, then $sup E$exists in $S$.
	4. field:
		1. A/M/D
	5. Real field:
		1. **Definition** There exists an ordered field $R$ which has the least-upper-bound property
		2. Archimedean property
		3. $Q$ is dense in $R$
		4. ? *proof and construction*
	6. complex field:
		1. Schwarz inequality: $$\left|\sum_{j=1}^na_j\bar{b}_j\right|^2\leq\sum_{j=1}^n|a_j|^2\sum_{j=1}^n|b_j|^2.$$
		2. $\lvert x \cdot y\rvert\leq\lvert x\rvert \cdot \lvert y \rvert$


# Basic Topology

1. Concepts:
	1. Set
		1. into, onto, 1-1 mapping, equivalent(~), cardinal number
		2. finite, countable, at most countable, uncountable
		3. **Theorem** Every infinite subset of a countable set A is countable.
		4. **Theorem** Corollary Suppose $A$ is at most countable, and for every $\alpha \in A$, $B_\alpha$ is at most countable. Put $T = \bigcup_{\alpha \in A} B_\alpha.$ Then $T$ is at most countable.
			1. **Corollary** Let $A$ be a countable set, and let $B_{n}$ be the set of all $n$-tuples $(a_{1}, \ldots, a_{n})$, where $a_{k} \in A$ $(k = 1, \ldots, n)$, and the elements $a_{1}, \ldots, a_{n}$ need not be distinct. Then $B_{n}$ is countable.
			2. **Corollary** The set of all rational numbers is countable.
	2. Metric Spaces
		1. convex
		2. limit point, interior point, bounded, open, closed, perfect, dense
		3. compact:
			1. **Theorem** Suppose  $K\subset Y \subset X$. Then $K$ is compact relative to X if and only if K is compact relative to $Y$.
			2. **Theorem** Compact subsets of metric spaces are closed.
			3. **Theorem** Closed subsets of compact sets are compact.
			4. **Theorem** If ${K_\alpha}$ is a collection of compact subsets of metric space X such that the intersection of every finite subcollection of ${K_\alpha}$ is nonempty, the $\bigcap K_\alpha$ is nonempty.
				1. **Corollary** If ${K_\alpha}$ is a sequence of nonempty compact sets such that $K_n\subset K_n+1(n=1,2,3...)$, then $\bigcap^\infty_1 K_n$ is not empty
			5. **Theorem** If $E$ is an infinite subset of a compact set $K$, then $E$ has a limit point in $K$.
			6.  **Heine-Borel theorem** ![image.png](https://image-1301391052.cos.ap-beijing.myqcloud.com/20251005205423379.png)
		4. perfect sets:
			1. **Theorem** Let $P$ be a nonempty perfect set in $R^k$.Then P is uncountable.
			2. **The Cantor set**: An example of an uncountable set of measure zero
		5. connected sets
		6. 
# Numerical Sequences and Series

1. Concepts：
	1. Sequences：
		1. convergent and subsequences
			1. **Theorem** If $E \subset X$ and if $p$ is a limit point of $E$, then there is a sequence $\{p_n\}$ in $E$ such that $p=\lim_{n\to\infty} p_n$
			2. **Theorem** If {$p_n$} is a sequence in a compact metric space $X$, then some subsequence of {$p_n$} converges to a point of X.
				1. **Corollary** Every bounded sequence in $R^k$ contains a convergent subsequence.
		2. Cauchy sequences：
			1.  **Theorem** ![image.png](https://image-1301391052.cos.ap-beijing.myqcloud.com/20251006103210460.png)
			2. **Corollary** (**Cauchy criterion**)：A sequence converges in $R^k$ if and only if it is a Cauchy sequence
			3. **Definition** A metric space in which every Cauchy sequence converges is said to be complete.
		3. monotonic sequences
			1. **Theorem** Suppose ${s_n}$ is monotonic. Then ${s_n}$ converges if and only if it is bounded.
		4. upper and lower limits
		5. some special sequences
	2. Series:
		1. Cauchy criterion
			1.  $|\sum_{k=m}^{n}a_k|\leq \varepsilon$
			2. **Theorem** If $\sum{a_n}$ converges, then $\lim_{n\rightarrow+\infty}a_n = 0$
		2. **Theorem** A series of nonnegative terms converges if and only if its partial sums form a bounded sequence
		3. comparison test
		4. series of nonnegative terms
			1. geometric series：If $0 \leq x < 1$, then$$\sum_{n=0}^{\infty} x^{n} = \frac{1}{1 - x}.$$If $x \geq 1$, the series diverges.
			2. **Theorem** Suppose $a_1 \geq a_2 \geq a_3 \geq \cdots \geq 0$. Then the series $\sum_{n=1}^{\infty} a_n$ converges if and only if the series$$\sum_{k=0}^{\infty} 2^k a_{2k} = a_1 + 2a_2 + 4a_4 + 8a_8 + \cdots$$converges.
				1. **Theorem** $\sum\frac{1}{n^p}\text{ converges if }p>1\text{ and diverges if }p\leq1.$ 
		5. $e$
			1. **Definition** $$e=\sum_{n=0}^{\infty}\frac{1}{n!}=\lim_{n\rightarrow \infty} {(1+\frac{1}{n})}^n$$
		6. root and ratio test
			1. **Theorem(Root Test)** Given $\Sigma a_{n}$, put $\alpha=\lim_{n \to \infty} sup \sqrt[n]{|a_{n}|}$. Then
				1. if $\alpha < 1$, $\Sigma a_{n}$ converges;
				2. if $\alpha > 1$, $\Sigma a_{n}$ diverges;
				3. if $\alpha = 1$, the test gives no information.
			2. **Theorem(Ratio Test)** The series $\sum a_n$ 
				1. converges if $lim_{n\to \infty} sup |\frac{a_{n+1}}{a_n}| < 1$,
				2. diverges if $|\frac{a_{n+1}}{a_n}| \geq 1$ for all $n \geq n_0$, where $n_0$ is some fixed integer.
			3. **Remarks** 
				1. the root test has wider scope
				2. all for absolute convergence
		7. power series
		8. summation by parts
			1. **Theorem** Suppose:
				(a) the partial sums $A_n$ of $\sum a_n$ form a bounded sequence;
				(b) $b_0 \geq b_1 \geq b_2 \geq \cdots$;
				(c) $\lim_{n \to \infty} b_n = 0$.
				Then $\sum a_n b_n$ converges.
		9. absolute convergence
		10. addition and multiplication of series
			1. Cauchy product:
				1. **Theorem** the Cauchy product of two convergent series converges, if at least one of the two series converges absolutely
				2.  **Theorem** If the series $\sum a_n$, $\sum b_n$, $\sum c_n$ converge to $A$, $B$, $C$, then $C = AB$
			2. Rearrangement
				1. **Theorem** Let $\sum a_n$ be a series of real numbers which converges, but not absolutely. Suppose $-\infty \leq \alpha \leq \beta \leq + \infty$ . Then there exists a rearrangement $\sum a'_n$ with partial sums $\sum s'_n$ such that   $lim_{n \to \infty} inf \;s'_n = \alpha$,    $lim_{n \to \infty} sup \;s'_n = \beta$
				2. **Theorem** If $\sum a _n$ is a series of complex numbers which converges absolutely, then every rearrangement of $\sum a _n$ converges, and they all converge to the same sum.
2. Key Points:
	1. Series Convergence:
		1. Cauchy criterion
		2. If $\sum a_n$ converges, then $\lim _{n\to\infty}a_n = 0$.
		3. Nonnegative terms - monotonic
		4. comparison test
		5. the terms of the series decrease monotonically: $\sum_{k=0}^{\infty} 2^k a_{2k}$ （$a_1 \geq a_2 \geq a_3 \geq \cdots \geq 0$）
		6. root test
		7. ratio test
		8. summation by parts:$\sum a_nb_n$
		9. Cauchy product
	2. special series
		1. $\sum x^n$
		2. $\sum \frac{1}{n^p}$
		3. $\sum \frac{1}{log n}$
	3. **Remark** 
		1. The comparison, root and ratio tests, is really a test for absolute convergence.
		2. Summation by parts can sometimes be used to handle the non-absolutely convergent series.
		3. Power series converge absolutely in the interior of the circle of convergence.


# Continuity

1. Concepts:
	1. Limits of Function
	2. Continuous Function
		1. **Theorem** f is continuous at p if and only if $\lim _{x\to\infty} f(x)=f(p)$.
		2. **Theorem** A mapping $f$ of a metric space X into a metric space Y is continuous on X if and only if $f^{-1}(V)$ is open in X for every open set V in Y.
	3. Continuous and Compactness
		1. **Theorem** Suppose $f$ is a continuous mapping of a compact metric space X into a metric space Y. Then $f(X)$ is compact.
		2. uniformly continuous
			1. **Definition**
			2. **Theorem** Let f be a continuous mapping of a compact metric space X into a metric space Y. Then f is uniformly continuous on X.(i.e. continuous on compact metric space = uniformly continuous)
	4. Continuity and Connectedness
	5. DisContinuities
		1. first kind(simple discontinuity), second kind
		2. **Theorem** Let $f$ be monotonically increasing on $(a, b)$. Then $f(x+)$ and $f(x-)$ exist at every point $x$ of $(a, b)$.
			1. **Corollary** Monotonic functions have no discontinuities of the second kind.
			2. Let $f$ be monotonic on $(a, b)$. Then the set of points of $(a, b)$ at which $f$ is discontinuous is at most countable.
	6. Infinite limits and limits at infinity

# Differentiation

1. Concepts:
	1. Derivative
	2. Mean Value Theorems
		1. **Theorem** generalized mean value theorem:If $f$ and $g$ are continuous real functions on $[a, b]$ which are differentiable in $(a, b)$, then there is a point $x\in (a,b)$ at which$$[f(b)-f(a)]g'(x)=[g(b)-g(a)]f'(x)$$
			1. **Corollary** mean value theorem($g(x)=x$):If $f$ is a real continuous function on $[a, b]$ which is differentiable in $(a, b)$, then there is a point $x\in(a, b)$ at which$$f(b)-f(a)=(b-a)f'(x)$$
	3. The Continuity of Derivatives
		1. **Theorem** Suppose $f$ is a real differentiable function on $[a, b]$ and suppose $f'(a) < \lambda <f'(b)$. Then there is a point $x \in (a, b)$ such that $f'(x) = \lambda$.
			1. **Corollary** If $f$ is differentiable on $[a, b ]$, then $f'$ cannot have any simple discontinuities on $[a, b ]$.
	4. L'Hospital's Rule
		1. Proof：by generalized mean value theorem
	5. Derivative of Higher Order
	6. Taylor's Theorem
		1. **Theorem** $$f(\beta)=\sum_{k=0}^{n-1}\frac{f^k(\alpha)}{k!}(\beta-\alpha)^k+\frac{f^n(x)}{n!}(\beta-\alpha)^n$$
	7. Differentiation of vector-valued function
		1. **Remark** the mean value theorem and its corollary(i.e. L'Hospital's rule) does *not* apply
		2. **Theorem** Suppose $\mathbf{f}$ is a continuous mapping of $[a, b]$ into $R^k$and $\mathbf{f}$ is differentiable in $(a, b)$. Then there exists $x \in (a, b)$ such that$$|\mathbf{f}(b)-\mathbf{f}(a)|\leq(b-a)|\mathbf{f}'(x)|$$

# The Riemann-Stieltjes Integral

1. Concepts:
	1. Existence of the Integral
		1. **Theorem** $f\in \mathscr R(\alpha)$ on $[a, b]$ if and only if for every $\varepsilon > 0$ there exists a partition P such that$$U(P,f,\alpha)-L(P,f,\alpha)<\varepsilon$$
		2. **Theorem** If $f$ is continuous on $[a, b]$ then $f\in \mathscr{R}(\alpha)$ on $[a, b]$.
		3. **Theorem** If $f$ is monotonic on $[a, b ]$, and if $\alpha$ is continuous on $[a, b ]$, then $f\in \mathscr{R}(\alpha)$. (We still assume that $\alpha$ is monotonic.)
		4. **Theorem** Suppose $f$ is bounded on $[a, b]$, f has only finitely many points of discontinuity on $[a, b ]$, and $\alpha$ is continuous at every point at which $f$ is discontinuous. Then $f\in \mathscr{R}(\alpha)$.
		5. **Theorem** Suppose $f \in \mathscr{R}(\alpha)$ on $[a, b]$, $m\leq f \leq M$, $\phi$ is continuous on $[m, M]$, and $h(x) = \phi (f(x))$ on $[a, b]$. Then $h\in \mathscr{R}(\alpha)$ on $[a, b]$.
	2. Properties of the Integral
		1. **Theorem** Assume $\alpha$ increases monotonically and $\alpha' \in \mathscr{R}$ on $[a, b]$. Let $f$ be a bounded real function on $[a, b ]$. Then $f\in \mathscr{R}(\alpha)$ if and only if $f\alpha' \in \mathscr{R}$. In that case$$\int_a^bfd\alpha = \int_a^bf\alpha'dx$$
		2. **Theorem**(change of variable): Suppose $\varphi$ is a strictly increasing continuous function that maps an interval $[A, B]$ onto $[a, b]$. Suppose $\alpha$ is monotonically increasing on $[a, b]$ and $f\in \mathscr{R}(\alpha)$on $[a, b]$. Define $\beta$ and $g$ on $[A, B]$ by $\beta(y)=\alpha(\varphi(y))$, $g(y)=f(\varphi(y))$. Then $g\in \mathscr{R}(\beta)$ and $$\int_A^B gd\beta=\int_a^bfd\alpha$$
	3. Integration and Differentiation
		1. **The fundamental theorem of calculus:**  If $f\in \mathscr{R}$ on $[a, b]$ and if the there is a differentiable function $F$ on $[a, b]$ such that $F' = f$, then$$\int_a^bf(x)dx=F(b)-F(a)$$
		2. **Theorem**(integration by parts): Suppose $F$ and $G$ are differentiable functions on $[a, b]$, $F' = f \in \mathscr{R}$, and $G' = g \in \mathscr{R}$. Then$$\int_a^bF(x)g(x)dx=F(b)G(b)-F(a)G(a)-\int_a^bf(x)G(x)dx$$
	4. Integration of vector-valued Functions
	5. Rectifiable curves
		1. $Theorem$ If $\gamma'$ is continuous on $[a, b]$, then $\gamma$ is rectifiable, and$$\Lambda(\gamma)=\int_a^b|\gamma'(t)|dt$$
2. Extension:
3. Key points:

# Sequences and Series of Functions

1. Concepts:
	1. Pointwise convergence
	2. Uniform convergence
		1. **Theorem**（Cauchy criterion） The sequence of functions {$f_n$}, defined on $E$, converges uniformly on $E$ if and only if for every $\varepsilon>0$ there exists an integer $N$ such that $m\geq N, n\geq N, x \in E$implies$$|f_n(x)-f_m(x)|\leq \varepsilon$$
		2. **Theorem** Suppose $\lim_{n\to\infty}f_n(x)=f(x)$, put $M_n = sup_{x\in E}|f_n(x)-f(x)|$, Then $f_n \to f$ uniformly on $E$ if and only if $M_n \to 0$ as $n\to \infty$.
		3. **Theorem** Suppose ${f_n}$ is a sequence of functions defined on $E$, and suppose $|f_n(x)|\leq M_n$, Then $\sum f_n$ converges uniformly on $E$ if $\sum M_n$ converges.
	3. Uniform convergence and Continuity
		1. **Theorem** If ${f_n}$ is a sequence of continuous functions on $E$, and if $f_n \to f$ uniformly on $E$, then $f$ is continuous on $E$.
		2. **Theorem**![image.png](https://image-1301391052.cos.ap-beijing.myqcloud.com/20251015115301654.png)
		3. **Definition** If $X$ is a metric space, $\mathscr{C}(X)$ will denote the set of all complex valued, continuous, bounded functions with domain $X$. We associate with each $f\in \mathscr{C}(X)$ its supremum norm： $\lVert f\rVert =sup_{x\in E}|f(x)|$， then made $\mathscr{C}(X)$ into a **complete** metric space.
	4. Uniform convergence and Integration
		1. **Theorem** if$f_n \subset R(\alpha)$, suppose $f_n \to f$ uniformly, then $f\subset R(\alpha)$, and $$\int_a^b fd\alpha = \lim_{n\to\infty}\int_a^b f_nd\alpha$$ $$\int_a^b fd\alpha = \sum_{n=1}^{\infty}\int_a^bf_nd\alpha$$
	5. Uniform convergence and Differentiation
		1. **Theorem** Suppose ${f_n}$ is a sequence of functions, differentiable on $[a, b]$ and such that ${f_n(x_0)}$ converges for some point $x_0$ on $[a, b]$. If ${f_n'}$ converges uniformly on $[a, b ]$, then ${f_n}$ converges uniformly on $[a, b ]$, to a function $f$, and $f'(x)=\lim_{n\to\infty}f_n'(x)$
	6. Equicontinuous family of functions
		1. *pointwise bounded* and *uniformly bounded*
		2. bounded and convergence
			1. **Theorem** If ${f_n}$ is a pointwise bounded sequence of complex functions on a **countable** set E, then ${f_n}$ has a subsequence ${f_{n_k}}$ such that ${f_{n_k}}$ converges for every $x\in E$.
		3. Equicontinuous
			1. **Definition** A family $\mathscr{F}$ of complex functions $f$ defined on a set $E$in a metric space $X$ is said to be **equicontinuous** on $E$ if for every $\varepsilon > 0$ there exists a $\delta > 0$ such that $|f(x)-f(y)|<\varepsilon$, whenever $d(x,y)<\delta, x\in E, y\in E,f\in \mathscr{F}$.(i.e. every member of an equicontinuous family is uniformly continuous).
		4. Equicontinuous and uniform convergence
			1. **Theorem** If $K$ is a compact metric space, if $f_n \in \mathscr{C}(K)$for n = 1, 2, 3, ... , and if ${f_n}$ converges uniformly on $K$, then ${f_n}$ is equicontinuous on K.(i.e. uniform continuous and uniform convergence = equicontinuous)
			2. **Theorem** If $K$ is compact, if $f_n\in \mathscr{C}(K)$ for n = 1, 2, 3, ... , and if {${f_n}$} is pointwise bounded and equicontinuous on $K$, then 
				(a){$f_n$} is uniformly bounded on K.
				(b){$f_n$} contains a uniformly convergent subsequence.
	7. ! ~={9}The Stone-Weierstrass Theorem=~


# Some Special Functions

1. Concepts:
	1. 