
## Magnetic field strength $H$
A magnetic field $H$ is generated in response to an electrical current density $J$ or current $I$ as described by [[Maxwell's Equations#Ampere's law|Ampere's law]]. The units of $H$ are \[A/m].
## Magnetic induction $B$
When a [[#Magnetic field strength $H$|magnetic field]] $H$ appears in a medium, the medium will respond with a certain induction $B$, also called magnetic flux density. The relation between $H$ and $B$ depends on the material (see [[Types of Magnetism]]), and is typically described by [[#Permeability $ mu$|permeability]] $\mu$.
The units of $B$ are \[Wb/m<sup>2</sup>] or \[T]. It may be interpreted as the force generated on a 1 A current using Ampere's force equation:
$$\mathbf{F} = i\mathbf{l} \times \mathbf{B}$$
## Magnetic flux $\phi$
The magnetic flux $\phi$ is defined as the [[#Magnetic induction $B$|magnetic induction]] through a surface. Its units are, therefore, \[Wb = Vs].
$$\phi = \iint_S \mathbf{B} \cdot d\mathbf{s}$$
## Magnetic moment $m$
A magnetic dipole with moment $m$ consists of two magnetic "poles" with strength $p$ separated by a distance $l$, pointing from the positive to the negative pole. The moment has units \[Am<sup>2</sup>].
$$m = pl = \frac{\phi l}{\mu_0}$$
A current loop carrying a current $i$ with an area $A$ has a moment $m = i A$. It is oriented perpendicular to the loop.
## Magnetisation $M$
The magnetisation $M$ expresses the permanent and induced magnetic dipole [[#Magnetic moment $m$|moments]] in a material. In all cases, the magnetisation arises from the dipole moments corresponding to electron spin and orbit around atoms, as described in [[Types of Magnetism]]. It is defined as the magnetic moment per unit volume and therefore has the same units as $H$, the \[A/m].
$$\mathbf{M} = \frac{\mathbf{m}}{V}$$
In the absence of external currents, the magnetisation is related to the flux density by
$$\mathbf{M} = \frac{\phi l}{\mu_0 V} = \frac{\phi}{\mu_0 A} = \frac{\mathbf{B}}{\mu_0}$$
## Permeability $\mu$
The magnetic induction $B$ is the sum of two components: (i) the magnetic field, and (ii) the magnetisation of the medium. Assuming a linear relation between the field and the magnetisation ($M = \chi_m H$, where $\chi_m$ is the magnetic susceptibility), the relative permeability $\mu_r$ can be expressed.
$$B = \mu_0 (H + M) = \mu_0 (1 + \chi_m) H = \mu_0 \mu_r H$$
The behaviour of $\mu = \mu_0 \mu_r$ versus the [[#Magnetisation $M$|magnetisation]] depends on the properties of the medium and is usually not linear (see [[Types of Magnetism]]).
## Flux linkage $\lambda$
If a magnetic flux "links" with an electrical circuit of $N$ turns, we interpret this as a flux linkage $\lambda$, which is defined as
$$\lambda = N \phi = N \iint_S \mathbf{B} \cdot d\mathbf{s},$$
where $\phi$ is the flux through a single turn enclosing the surface $S$. A changing flux linkage results in a voltage induced in the circuit according to [[Maxwell's Equations#Faraday's law|Faraday's law]]. Considering the [[#Inductance $L$|inductance]] $L$ of the circuit, the flux linkage may be written as
$$\lambda = L i = N \phi = N B A.$$
## Inductance $L$
Inductance is the property of an electrical circuit which allows for the exchange and storage of magnetic energy. It is directly a consequence of [[Maxwell's Equations#Faraday's law|Faraday's law]]. By defining $\lambda = L i$, we obtain the relation between voltage and current:
$$ u(t) = \frac{\partial \lambda(t)}{\partial t} = L \frac{d i(t)}{d t} $$
The inductance $L$ then has units of \[Wb/A] or \[Vs/A].
## Analogy to electric fields

| Magnetic field                       |                         | Electric field                      |                    |
| ------------------------------------ | ----------------------- | ----------------------------------- | ------------------ |
| Field strength $H$                   | \[A/m]                  | Field strength $E$                  | \[V/m]             |
| Flux $\phi$                          | \[Wb = Vs]              | Current $I$                         | \[A = C/s]         |
| Flux density $B$                     | \[T = Wb/m<sup>2</sup>] | Current density $J$                 | \[A/m<sup>2</sup>] |
| Inductance $L$                       | \[H = Wb/A]             | Capacitance $C$                     | \[F = C/V]         |
| Permeability $\mu$                   | \[H/m]                  | Permittivity $\varepsilon$          | \[F/m]             |
| Energy $E_{mag} = \frac{1}{2} L I^2$ |                         | Energy $E_{el} = \frac{1}{2} C V^2$ |                    |






