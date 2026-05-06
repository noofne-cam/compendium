> Sequences and sequential convergence, Cauchy sequences, Limits

- **N.** *Notation.*
	- Throughout this document the following symbols are reserved:
		- $\epsilon$ denotes an arbitrary positive real, usually taken to be small ($\ll 1$). 
		- $N$ denotes an arbitrary positive integer, usually taken to be large ($\gg 1$).
		- $X$ denotes an arbitrary metric space.
---
- **A.** *CONVERGENCE OF SEQUENCES*
	- If $(p_n)$ is a sequence in $X$, then $(p_n)$ **converges** to $p \in X$ *if*, for all $\epsilon$ there exists $N$ such that $n \ge N$ means that $d(p_n, p) < \epsilon$. 
	  *In other words, $(p_n)$ converges to $p$ if $(p_n)$ is eventually always near $p$.* 
	- That $(p_n)$ converges to $p$ may be expressed in the form $p_n \to p$ (as $n \to \infty$), or in the form $\lim_{n\to \infty} p_n = p$. 
---
- **B.** *Convergence Properties.*
	- 1. A sequence $(p_n) \to p$ *iff* each neighborhood of $p$ contains all but a finite number of $p_n$.
	- 2. If $(p_n) \to p$ and $(p_n) \to p'$, then $p = p'$.
	- 3. If $(p_n)$ converges, $(p_n)$ is bounded.
	- 4. If $E \subset X$ and $p$ is a limit point of $E$, there exists a sequence $(p_n) \subset E$ such that $p_n \to p$.
---
- **C.** *Arithmetic on Convergent Sequences*
	- Let $(s_n)$, $(t_n)$ be sequences in $\mathbb C$, with $s_n \to s$ and $t_n \to t$. Then
	- 1. $(s_n + t_n) \to s+t$,
	- 2. $cs_n \to cs$ and $c + s_n \to c + s$ for any $c \in \mathbb C$,
	- 3. $s_nt_n \to st$,
	- 4. $1/s_n \to 1/s$ given $s_n, s \neq 0$.
---
- **D.** *SUBSEQUENCES*