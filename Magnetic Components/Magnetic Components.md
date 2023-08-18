[[Equivalent Circuits]]

## Power components
Magnetic components for power electronic applications can be split into two categories (i) inductors or coils, and (ii) coupled inductors and transformers. Because these power components must operate with high voltage and high current, [[Core Losses]] and [[Winding Losses]] are very important.
### Inductors
Inductors or coils have a single winding (coil) with an optional magnetic core with the main purpose of storing magnetic energy and blocking HF signals. Examples for this family of magnetic components are:
* [[Electromagnetic Compatibility|Differential-mode (DM)]] chokes, used in [[Electromagnetic Compatibility|EMC filtering]] applications. Typically have a large DC bias and small HF ripple. 
* DC-link inductors, operate with a mix of DC bias and HF ripple.
* AC or resonant inductors, used in resonant converters or other applications with quasi-sinusoidal current.
### Coupled inductors
Coupled inductors on the other hand include at least 2 windings that have a mutual coupling that depends on the applications' requirements. The term "coupled inductor" is used for coupled magnetic components that have no galvanic isolation.
* [[Electromagnetic Compatibility|Common-mode (CM)]] chokes, used in [[Electromagnetic Compatibility|EMC filtering]] applications. These are coupled inductors with 2, 3 or 4 windings that feature very high CM (kΩ range) and low DM impedance over the frequency range of interest.
* HF transformers, passive devices that provide current/voltage scaling and galvanic isolation. Used in isolated DC/DC converters.
* Mains transformers, passive 50/60 Hz devices that provide current/voltage scaling and galvanic isolation. Large and expensive due to the low frequencies.
* Instrumentation transformers
	* Voltage/potential transformer (PT): galvanically isolated passive voltage measurement devices for AC voltages.
	* Current transformer (CT): galvanically isolated passive current measurement devices for AC currents.
## EMC Filter Chokes
