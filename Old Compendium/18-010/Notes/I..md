> Exposition on the real numbers, their properties, the complex field, euclidean spaces, and the hyperreal set.

- **0.** The main result [A] of this section may require some exposition. [A] consists of three distinctions of the reals, each of which has a precise definition:
	- *Order*
	- *Fields*
	- *Least-Upper-Bound Property* (l.u.b) 
	- *The Rational Set* $\mathbb Q$
---
- **A.** *THE REAL SET*
	- The **real set** $\mathbb R$ is *the* ordered field with the least-upper-bound property.
	  *The existence and uniqueness proof is a construction. There exist several variations, providing different interpretations for the elements of $\mathbb R.$ Each extends the role of $\mathbb Q$ to being subset to $\mathbb R$.* 
	- **I.** Dedekind Construction, Association with $\supset \mathbb Q$.
		- A. The key construct is as follows: the member $\alpha \in \mathbb R$ is defined as a subset of $\mathbb Q$, called a *cut* of $\mathbb Q$, such that (a) $\alpha$ is nonempty and $\alpha \neq \mathbb Q$, (b) $p \in \alpha$ and $q \in \mathbb Q$ with $q < p$ means that $q \in \alpha$, (c) $p \in \alpha$ means that $r \in \alpha$ exists with $p < r$.
		  *The remainder of this part of the proof consists of showing that the set $\mathbb R$ defined above is an ordered field satisfying l.u.b.* 
		- B. *ORDER*. With $s, r \in \mathbb R$, let us define $s < r$ by $s \subset r$. It follows that if $s \neq r$, that $s \subset r$ or $r \subset s$, by the definition of the subset. Moreover, if $s < r$ and $r < t$ then $s < t$, as $s\subset r$ and $r\subset t$ means that $s \subset t$. With this the set $\mathbb R$ is ordered.
		- C. *L.U.B.* Let $E \subset \mathbb R$ be nonempty and bounded above. Let $B_E$ be the set of upper bounds of $E$. Consider the element $E^\circ = \bigcup E$, defined by the set of all elements in at least one of the elements in $E$. 
			- 1. First, we show that $E^\circ$ is indeed a member of $\mathbb R$. Clearly $E^\circ$ is nonempty and not equal to $\mathbb Q$ as $\mathbb Q - E^\circ$ is nonempty. Now if $p \in E^\circ$ and $q \in \mathbb Q$, with $q < p$, then there exists some $e \in E$ for which $p \in e$, whence $q < p \implies q \in e$ and $q \in E^\circ$ by property (ii). Finally, if $p \in E^\circ$, then $p \in e$ for $e \in E$, whence there exists $r \in e$ such that $r > p$. Thus there exists some $r \in E^\circ$ for which $r > p$. As $E^\circ$ satisfies the three defining characteristics of a cut it follows that $E^\circ \in \mathbb R$.
			- 2. Next it is shown that $E^\circ$ is the least-upper-bound of $E$. Let $\beta$ be an upper bound of $E$. It follows that $\beta > e \in E$, meaning that $\beta \supset e$. Clearly $E^\circ$ is an upper bound of $E$. Now if $\gamma < E^\circ$, then $\gamma \subset E^\circ$ with $\gamma \neq E^\circ$. Let $r \in E^\circ$ but not $r \in \gamma$. Then if $r \in e \in E$, it follows that $e \not\subset \gamma$, meaning that $e \not\lt \gamma$. Thus, $\gamma$ cannot be an upper bound of $E$. Thus, it is shown that the least-upper-bound of the nonempty set $E$ that is bounded above exists in $\mathbb R$, such that $\mathbb R$ satisfies the least-upper-bound-property.
		- D. *FIELD ADDITION.* We define the notion of addition on the cuts of $\mathbb R$ as follows: if $\alpha, \beta \in\mathbb R$, then $\alpha + \beta$ is the set of all $r+s$ with $r \in \alpha$ and $s \in \beta$. Now it is clear that $+$ is commutative and associative as defined on $\mathbb R$, as $+$ on $\mathbb Q$ is commutative and associative. Next, we define the element $0 \in \mathbb R$ as the set of all $q \in \mathbb Q$ such that $q < 0$, and for each element $x \in \mathbb R$ the set $-x$ defined as all $-q$ for $q \in x$. The proof of the validity of these definitions is postponed until the proof that $+$ is closed:   
	- **II.** Cantorean Construction
	- **III.** Uniqueness
---
- **B.** *Properties of the Reals*
	- §1, [Archimedean Property]. If $x, y \in \mathbb R$ and $x > 0$, there exists $n \in \mathbb Z^+$ such that $nx > y$.
		- Let $S$ be the set consisting of all $nx - y$ as $n$ iterates over $\mathbb Z^+$. As $S$ is nonempty, it must have a supremum in $\mathbb R$ if it is bounded above. But if $S$ has some supremum $\gamma$ in $\mathbb R$, then any $\gamma - nx < \gamma$ cannot be an upper bound of $S$. But then $\gamma - nx + nx + x = \gamma + x > \gamma$ cannot be an upper bound either,      
	- §2, [Density]. $\mathbb Q$ is dense in $\mathbb R$; i.o.w. if $x, y \in \mathbb R$ and $x < y$, there exists $q \in \mathbb Q$ such that $x < q < y$.
		- Consider the inequality $0 < q < y-x$. With the representation $q = m/n$, the validity of this is equivalent to the statement [B1]. Now it follows that $0 < m < ny - nx$, whence $nx < m + nx < ny$, or $x < m$  
	- §3, [Root Completeness]. If $x \in \mathbb R$ and $n \in \mathbb Z$ with $x, n > 0$, then there exists a unique $y \in \mathbb R$ such that $y^n = x$. 