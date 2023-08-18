Core losses occur in magnetic materials when subjected magnetization cycles. A changing magnetic field $H$ elicits a response from the material in the form of a changing magnetization. There are two sources of core loss: [[#Eddy currents|eddy current]] loss and [[#Hysteresis|hysteresis]] loss.
## Eddy currents
[[Eddy Currents|Eddy currents]] are induced in any conductive material when exposed to a changing magnetic field. The eddy currents oppose the changing magnetic field following [[Maxwell's Equations#Faraday's law|Faraday's law]]. 
The flow of eddy currents results in power dissipation due to the finite conductivity of the material.

To limit the magnitude of the induced currents, two approaches may be taken:
1) Lamination of the core. By constructing the core of many thin electrically-insulated laminations, the loop area in which eddy currents can be induced is reduced (provided that the laminations are in the correct plane!).
2) High resistivity. If the core is constructed of highly resistive material (e.g., ferrites and powdered iron cores), the magnitude of the induced eddy currents (and hence the dissipation) will be low.
## Hysteresis

## Residual losses
Losses due to magnetic relaxation effects

## Steinmetz equation
The Steinmetz equation is an empirical equation that describes the volumetric loss density $P_v$ \[W/m<sup>3</sup>] of a magnetic material when subjected to a _sinusoidally_ varying induction.
$$P_v = k f^\alpha \Delta B^\beta,$$where $k$, $\alpha$, and $\beta$ are the Steinmetz parameters, $f$ is the frequency of the excitation, and $\Delta B$ is the peak-to-peak flux swing. Typically $\alpha = 1-2$ and $\beta = 2-3$.
It is important to note that this is merely an approximation based on the core loss curves usually given in material datasheets. The Steinmetz parameters are only valid for a limited range of frequency, flux swing, and temperature. It does not take into account DC bias.

In power electronic applications, the flux is usually not sinusoidal, but is instead triangular or trapezoidal (for 2-level or 3-level rectangular voltages). In resonant converters, the flux may be quasi-sinusoidal. 
Several modifications to the Steinmetz equation have been proposed to improve the core loss estimates for non-sinusoidal flux waveforms. Nevertheless, since the core loss data is based on sinusoidal excitation, it cannot be very accurate.
### Modified Steinmetz equation (MSE)

$$\begin{align}
	P_v    & = (k f_{eq}^{\alpha-1} \Delta B^\beta) f \\
	f_{eq} & = \frac{f}{2\pi (D - D^2)}
\end{align}$$
### Generalized Steinmetz equation (GSE)

$$\begin{align}
	P_v    & = k f_{eq}^{\alpha-1} B_{eq}^\beta \\
	B_{eq} & = \frac{1}{4} \int_0^T \left| \frac{dB}{dt} \right| dt
\end{align}$$
### Improved generalized Steinmetz equation (iGSE)

$$\begin{align}
	P_v & = \frac{1}{T} \int_0^T k_i \left| \frac{dB}{dt} \right|^\alpha (\Delta B)^{\beta - \alpha} dt \\
	k_i & = \frac{k}{(2\pi)^{\alpha-1} \int_0^{2\pi} |\cos\theta|^\alpha 2^{\beta-\alpha} d\theta}
\end{align}$$
### Improved-improved GSE (i<sup>2</sup>GSE)
Magnetic relaxation effects
