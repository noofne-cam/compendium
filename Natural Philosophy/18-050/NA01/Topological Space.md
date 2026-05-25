*or,* **Space**

> A **topological space** is a *set* $X$ augmented with a *structure* $\tau$ called a **topology**, satisfying the following three properties:
> i. $X \in \tau$ and $\varnothing \in \tau$
> ii. If $(A_i) \subset \tau$, then $\bigcup A_i \in \tau$.
> iii. If $(A_i)^n \subset \tau$, then $\bigcap A_i \in \tau$.
---
- **A.** *Auxiliary Notions*
	- The sets in $\tau$ are called **open**.
	- A set $C$ whose complement under $X$ is open is called **closed**.
---
- **B.** *Basis*
	- Let $B$ be a *collection* of open sets which covers $X$ and satisfies the condition: if $b_1, b_2 \in B$ and $x \in b_1 \cap b_2$, there exists a set $b_3 \in B$ such that $x \in b_3 \subset b_1 \cap b_2$. Then $B$ is called a **basis** on $X$, and defined a topology in one of two equivalent ways:
	- i. *Basis Condition.* A set $U$ is open under $B$ if, for each $x \in U$, there exists a set $b \in B$ such that $x \in b \subset U$.
	- ii. *Union Condition.* The open sets under $B$ are the unions of the elements of $B$. 
---
- **C.** *Derivation from a Metric*
	- Let $X$ be a metric space with metric $g$. We may define a canonical topology on $X$ as follows: 