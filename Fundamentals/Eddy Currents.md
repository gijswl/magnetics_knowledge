When an electrically conducting material is exposed to a time-varying magnetic field or flux, an opposing voltage is induced (see [[Maxwell's Equations#Faraday's law|Faraday's law]]). This voltage gives rise to induced currents, known as _eddy currents_.
The penetration of the magnetic field in the material is opposed and results in an attenuated field, depending on the conductivity, frequency, and permeability. The _skin depth_ is the depth at which the field decays to $e^{-1}$ of its value at the surface.
$$\delta = \sqrt{\frac{2}{\mu \sigma \omega}} = \frac{1}{\sqrt{\pi \mu \sigma f}}$$
## Derivation for a plane wave

## Eddy current loss
The (classical) eddy current loss can be calculated in a homogeneous magnetic material with permeability $\mu$. [[Maxwell's Equations#Faraday's law|Faraday's law]] states that
$$\nabla \times \mathbf{E} = \frac{1}{A} \oint \mathbf{E} \cdot d\mathbf{l} = -\frac{d\mathbf{B}}{dt}$$
Assuming that the field is impinging normally (on $wd$ face) on a lamination of width $w$, length $l$, and thickness $d$,
$$\frac{2(w+d)}{wd} \mathbf{E} \approx \frac{2}{d} \mathbf{E} = -\frac{d\mathbf{B}}{dt} \implies \mathbf{J} = -\frac{d}{2 \rho} \frac{d\mathbf{B}}{dt}$$
The volumetric power loss is calculated from the dot product of current and electric field:
$$w_{ec} = \frac{1}{V} \iiint \mathbf{J}\cdot\mathbf{E} dv = \frac{d^2}{12 \rho} \left( \frac{d\mathbf{B}}{dt} \right)^2 \qquad \mathrm{[W/m^3]}$$
### Shape factor
In general, a shape factor $\beta$ (value $\beta = 6$ for laminations, $\beta = 16$ for cylinders, and $\beta = 20$ for spheres) is defined and the eddy current loss becomes
$$w_{ec} = \frac{d^2}{2 \beta \rho} \left( \frac{d\mathbf{B}}{dt} \right)^2$$