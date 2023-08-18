
## Paramagnetism
Paramagnetism occurs in atoms and molecules with an odd number of electrons (unpaired electron spin) resulting in a permanent magnetic moment $\mathbf{m}$. The magnetic moment is oriented randomly throughout the medium and hence no permanent magnetisation is present. Unlike [[#Ferromagnetism|ferromagnetism]], paramagnetism is not a cooperative phenomenon and can be studied on single atoms.

When an external [[Definitions#Magnetic field strength $H$|magnetic field]] $\mathbf{H}$ is applied, a torque is applied to the moments, which start to align with the field lines. The net alignment is small because it is disturbed by the thermal agitation of the electrons. The resulting [[Definitions#Magnetisation $M$|magnetisation]] $\mathbf{M}(\mathbf{H})$ is described classically by the Langevin function:
$$\mathbf{M} = N \mathbf{m} \left[ \coth\left( \frac{\mu_0 \mathbf{m} \cdot \mathbf{H}}{k_B T} \right) - \frac{k_B T}{\mu_0 \mathbf{m} \cdot \mathbf{H}} \right],$$
where $N$ is the number of atoms per unit volume, $\mathbf{m}$ is the magnetic moment per atom, $k_B$ is the Boltzmann constant, and $T$ is the temperature in \[K]. The [[Definitions#Permeability $ mu$|susceptibility]] $\chi$ (below saturation) is described approximately by the Curie law, since the alignment of the magnetic moments decreases at high temperatures.
$$\chi \approx \frac{\mu_0 n \mathbf{m}^2}{3k_B T} \implies \chi \propto T^{-1}$$
## Diamagnetism
Diamagnetism occurs in materials where there is no net magnetic moment because the atomic shells are completely occupied. These materials have a negative [[Definitions#Permeability $ mu$|susceptibility]] ($\chi < 0$) because the induced [[Definitions#Magnetisation $M$|magnetisation]] $\mathbf{M}$ opposes the external [[Definitions#Magnetic field strength $H$|field]] $\mathbf{H}$.
### In dielectrics
In dielectric materials (containing atoms with closed shells), the electrons start to precess under an applied magnetic field resulting in a current loop with a magnetic moment opposing the external field. The phenomenon is described by the Langevin susceptibility, which is independent of temperature:
$$\chi = -\mu_0 \frac{q^2 Z N}{6 m_e} \langle r^2 \rangle,$$
where $q$ is the electron charge, $Z$ is the number of electrons per atom, $N$ is the number of atoms per unit volume, $m_e$ is the electron mass, and $\langle r^2 \rangle$ is the mean square distance of electrons from the nucleus.
### In metals
In metals, non-localised electrons (free electron gas) cause a weak counteracting field that forms from the curvature of electron trajectories due to the Lorentz force. This phenomenon is called Landau diamagnetism.
$$\chi = -\mu_0 \frac{\mu_B^2 N}{2 k_B T_F},$$
where $\mu_B = \frac{q \hbar}{2 m_e}$ is the Bohr magneton and $T_F = \frac{E_F}{k_B}$ is the Fermi temperature.
## Ferromagnetism
Ferromagnetism arises from the interaction between magnetic moments, which form [[#Weiss Domains|domains]] with aligned $\mathbf{m}$, potentially resulting in a strong magnetisation $\mathbf{M}$. This is only possible if the atoms/molecules have a net magnetic moment (spin and/or orbital) like [[#Paramagnetism]].
Ferromagnetism occurs only in a few substances. Most commonly [[Electron Configuration#Transition metals|iron, nickel, cobalt]], and their alloys (transition metals).

## Anti-ferromagnetism
## Ferrimagnetism
