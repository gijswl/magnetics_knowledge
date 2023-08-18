In analogy to electrical circuit analysis, a magnetic circuit may be described by the magnetomotive force (voltage), [[Definitions#Magnetic flux $ phi$|magnetic flux]]
(current), and reluctance (resistance). This can significantly simplify the calculation of [[Definitions#Inductance $L$|inductances]] and the magnetic field in [[Magnetic Components|coils and transformers]] consisting of a magnetic core with multiple flux paths and potentially air gaps.

| Quantity            | Definition                                  | Unit    | Electrical analog |
| ------------------- | ------------------------------------------- | ------- | ----------------- |
| Magnetomotive force | $\mathcal{F} = N i$                         | \[At]   | Voltage           |
| Reluctance          | $\mathcal{R} = \dfrac{l}{\mu A}$          | \[A/Wb] | Resistance        |
| Flux                | $\phi = \dfrac{\mathcal{F}}{\mathcal{R}}$ | \[Wb]   | Current           |
Sometimes the _permeance_ $\mathcal{P} = \mathcal{R}^{-1}$ is used instead. This is analogous to conductance in electrical circuits.
## Derivation
[[Maxwell's Equations#Ampere's law|Ampere's law]] can be written in a form more suitable for circuit analysis by dividing the magnetic circuit into segments over which $H$ is approximately constant.
$$\oint_{\partial S} \mathbf{H} \cdot d\mathbf{l} = \iint_S \mathbf{J} \cdot d\mathbf{s}$$
Consider a magnetic circuit with $k$ segments, each with a magnetic field $H_k$ and length $l_k$. The source term can be simplified into $m$ excitation currents with turns $N_m$ and current $I_m$. The integrals simplify to summation:
$$\sum_k H_k l_k = \sum_m N_m I_m$$
Assuming a constant cross-section $A_k$ and permeability $\mu_k$ for each segment further allows us to express the LHS in terms of the magnetic flux $\phi_k$.
$$\sum_k \phi_k \frac{l_k}{\mu_0\mu_k A_k} = \sum_k \phi_k \mathcal{R}_k = \sum_m \mathcal{F}_m$$
## Induction and Inductance
The reluctance model can relatively accurately describe the flux (and from there the [[Definitions#Magnetic field strength $H$|magnetic field]] and [[Definitions#Magnetic induction $B$|magnetic induction]]) based on the provided excitation current(s). For a complete description of the link between magnetic and electrical circuits, the response (induced) voltage can be derived from [[Maxwell's Equations#Faraday's law|Faraday's law]].
$$\oint_{\partial S} \mathbf{E} \cdot d\mathbf{l} = \frac{\partial}{\partial t} \iint_S \mathbf{B} \cdot d\mathbf{s}$$
The voltage over each winding (corresponding to the sources $m$ in the section above), can then be written as
$$e = R i + \frac{d\lambda}{dt}$$
where $\lambda = N \phi = L i$. The inductance can further be written as
$$L = \frac{N \phi}{i} = \frac{N \mathcal{F}}{\mathcal{R} i} = \frac{N^2}{\mathcal{R}}$$
## Example: Gapped Toroidal Inductor
Consider a toroidal core with cross-section $A$, mean path length $l = 2\pi\cdot \frac{1}{2}(r_i + r_o)$, and $N$ turns distributed equally over the core. The core has a gap of length $l_g$.
The reluctance of this configuration consists of two components: the core and the gap.
$$\begin{align}
	\mathcal{R}_c & = \frac{l}{\mu_0\mu_r A} \\
	\mathcal{R}_g & = \frac{l_g}{\mu_0 A_g}
\end{align}$$
Assume $A_g = A$, which is not true in practice due to fringing.
$$\mathcal{R} = \frac{l/\mu_r + l_g}{\mu_0 A} \implies L = \frac{\mu_0 A N^2}{l_g + l/\mu_r}$$
The addition of a gap to the core provides a high reluctance, reducing the flux for a given excitation current (i.e., increasing the saturation current) but also reducing the inductance.