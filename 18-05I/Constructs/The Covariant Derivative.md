> We seek 

The covariant derivative $\nabla$ is an *operator* on $n\choose m$-tensors yielding $n\choose{m+1}$-tensors, satisfying the following properties:
- **Linearity.** For $A, B$ $\in \mathfrak T{n\choose m}$, and scalars $f, g$, $$\nabla_\mu(fA^{(n)}_{(m)} + gB^{(n)}_{(m)}) = f\nabla_\mu A^{(n)}_{(m)} + g\nabla_\mu B^{(n)}_{(m)}.$$
- **Leibnitzarity.** For $A, B \in \mathfrak T{n\choose m}$, $$\nabla_\mu(A^{(n)}_{(m)} \otimes B^{(n)}_{(m)}) = A^{(n)}_{(m)}\otimes \nabla _\mu B^{(n)}_{(m)} + B^{(n)}_{(m)}\otimes \nabla_\mu A^{(n)}_{(m)}.$$
- **Commutativity with Contraction.** For $A \in \mathfrak T{n\choose m}$, $$\nabla _\mu A^{\nu_{1\cdot}c_{\cdot n}}_{\rho_{1\cdot}c_{\cdot m}} = \nabla_\mu[A^{\nu_{1\cdot}c_{\cdot n}}_{\rho_{1\cdot}c_{\cdot m}}].$$
- **Natural Reduction over Scalars.** If $f \in \mathfrak T{0\choose 0}$, $$\nabla_\mu f = \partial_\mu f;$$alternatively, for $T \in T_p$, $$T^\mu\nabla_\mu f = T(f).$$
Additionally, there exists one *natural axiom* of $\nabla$ which is satisfies in nearly all physical contexts:
- **Vanishing of Torsion:** For any $f \in \mathfrak T{0\choose 0}$, $$\nabla_\mu\nabla_\nu f = \nabla_\nu\nabla_\mu f.$$
---
- **0.** *EXISTENCE, UNIQUENESS.*
	- i. There exists at least one covariant derivative on any manifold $M$, called the *ordinary covariant derivative $\partial_\mu$*, defined as $$\partial_\mu A^{(n)}_{(m)} = \frac{\partial A^{(n)}_{(m)}}{\partial x^\mu}.$$
		- *Proof.* Let $\partial_\mu$ be defined as above. Then it follows from the regular properties of the partial derivative that $\partial_\mu$ is *linear*, follows the *product rule*, and is *torsion-free* for any tensors $A$ and $B$ (and so for any scalar). If $A$ is a tensor with a contraction, then interpreting $A$ as a metric tensor over the natural coordinate bases $\partial/\partial x^\mu$ and $dx^\mu$ the commutativity of $\text{tr}$ with $\partial_\mu$ follows. Finally, it is apparent that $\partial_\mu$ reduces to the partial derivative for scalars. 
	- ii. Any two covariant derivatives satisfy the *gauge condition* $$\nabla_\mu \omega_\nu = \nabla_\mu' \omega_\nu - \text C^{\rho}_{\mu\nu}\omega_\rho.$$
		- 