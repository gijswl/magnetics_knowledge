## Gauss' laws
[[Gauss' integral theorem]]
## Ampere's law
Ampere's law describes the formation of a magnetic field $\mathbf{H}$ by a current flowing in space.
$$\oint_{\partial S} \mathbf{H} \cdot d\mathbf{l} = N I,$$
where $N$ is the number of turns and $I$ is the current through a surface $S$ with boundary $\partial S$. The differential form is derived using [[Stokes' theorem]]:
$$\oint_{\partial S} \mathbf{H} \cdot d\mathbf{l} = \iint_S (\nabla \times \mathbf{H}) \cdot d\mathbf{s} = \iint_S \mathbf{J} \cdot d\mathbf{s} = NI$$
Maxwell added an additional term to the total current density $J$: the displacement current. This results in the final form of the Maxwell-Ampere law (see [[#Differential form]]).
$$\mathbf{J} = \mathbf{J}_0 + \mathbf{J}_{dis} = \mathbf{J}_0 + \frac{\partial \mathbf{D}}{\partial t}$$
## Faraday's law
Faraday's law of induction states that a time-varying magnetic flux through a circuit will result in an induced voltage. This induced voltage is such that it would create a current which _opposes_ the change in flux through the circuit (also called the [[Definitions#Flux linkage $ lambda$|flux linkage]]). We model this circuit property as [[Definitions#Inductance $L$|inductance]].
$$u(t) = -\frac{\partial \lambda}{\partial t} = -N \frac{\partial \mathbf{\phi}}{\partial t} = -N \frac{\partial}{\partial t} \iint_S \mathbf{B} \cdot d\mathbf{s}$$
Again using [[Stokes' theorem]], we can derive the differential form of Faraday's law.
$$u(t) = \oint_{\partial S} \mathbf{E} \cdot d \mathbf{l} = \iint_S (\nabla \times \mathbf{E}) \cdot d\mathbf{s} = \iint_S \left( \frac{\partial \mathbf{B}}{\partial t} \right) \cdot d\mathbf{s}$$
## Differential form

$$\begin{alignat}{3}
	\nabla \cdot \mathbf{D} & = \rho \qquad && \nabla \cdot \mathbf{B} && = 0 \\
	\nabla \times \mathbf{E} & = -\frac{\partial \mathbf{B}}{\partial t} \qquad && \nabla \times \mathbf{H} && = \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t} 
\end{alignat}$$
## Integral form

$$\begin{align}
	\oint_{\partial V} \mathbf{D} \cdot d\mathbf{s} & = \iiint_V \rho dv \\
	\oint_{\partial V} \mathbf{B} \cdot d\mathbf{s} & = 0 \\
	\oint_{\partial S} \mathbf{E} \cdot d\mathbf{l} & = -\frac{\partial}{\partial t} \iint_S \mathbf{B} \cdot d\mathbf{s} \\
	\oint_{\partial S} \mathbf{H} \cdot d\mathbf{l} & = \iint_S \left( \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t} \right) \cdot d\mathbf{s} \\
\end{align}$$
## Constitutive relations
