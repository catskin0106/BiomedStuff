Lecture Notes

**Lecture Coverage:**
- Current Flow across Cell Membrane
- Ion Flow through Ion Channels
- Cell Membrane as Capacitor
- Ion Channels in Electrical Conduction

---
#### **Current Flow Across Cell Membrane**
- <abbr Title="Net flow rate of charge">Current</abbr> caused by:
	- Flow of Ions between the <abbr Title="Na+, Cl- & (Minor) K+">Extracellular Matrix</abbr> & <abbr Title="A.A.- , K+ & (Minor) Na+, Cl-">Neuron Cytoplasm</abbr>
		- Across Cell Membrane through Ion Channels
	- Cell membrane storing / releasing charges as Capacitor
- Quantified by the Hodgkin-Huxley model
	- <abbr Title="Total Current Flow across Membrane">I<sub>m</sub></abbr> = I<sub>capacitive</sub> + I<sub>ionic</sub> (V<sub>m</sub> , t)

**Calculation of Electrical Potential (Nernst Equation)**
- E = Cytoplasm Voltage relative to ECM ( V<sub>in</sub> - V<sub>out</sub> )
	- Nernst Equation (<abbr Title="Universal Gas Constant">R</abbr>, <abbr Title="Absolute Temperature (Kelvin)">T</abbr>, <abbr Title="Ion charge no. (e.g. Ca2+ = 2)">z</abbr>, <abbr Title="Faraday's Constant">F</abbr>, <abbr Title="Ionic Concentration in / out of cell">C</abbr>):
$$\huge - \frac{RT}{zF}\text{ln} \frac{C_{in}}{C_{out}}$$

#### **Ion Flow through Ion Channels**
**Factors affecting Ion Flow through Ion Channels**
- Sum of 2 Factors:
	- Ion Concentration Gradient
	- Electrical Field of ECM / Cytoplasm
- State of Ion Channels
	- Affected by the 2 factors

**Calculation of Ionic Current Flow**
- Can be calculated by Ohm's Law ( <abbr Title="Ionic Current">I</abbr> = <abbr Title="Conductance / Reciprocal of Resistance">g</abbr><abbr Title="Voltage">V</abbr> or <abbr Title="Ionic Current">I</abbr> = <abbr Title="Voltage">V</abbr> / <abbr Title="Resistance">R</abbr> )
	-  I<sub>ion</sub> = g<sub>ion</sub> ( <abbr Title="Membrane Potential">V<sub>m</sub></abbr> - <abbr Title="Equilibrium Potential of given Ion">E<sub>ion</sub></abbr> )
		- ( V<sub>m</sub> - E<sub>ion</sub> ) : Ion Driving Force, determines I<sub>ion</sub> is <abbr Title="i.e. Flowing out of cell">Positive</abbr> or <abbr Title="Flowing into cell">Negative</abbr>
	- V<sub>m</sub> & t affects I<sub>ion</sub> & g<sub>ion</sub> as well, Besides Ohm's Law
		- Can be viewed as a function I<sub>ion</sub>(V<sub>m</sub> , t) or g<sub>ion</sub>(V<sub>m</sub> , t)
	- I<sub>ionic</sub> (V<sub>m</sub> , t) = I<sub>Na</sub> + I<sub>Cl</sub> + I<sub>K</sub> 


#### **Cell Membrane as Capacitor**
**Capacitive Current**
- Changes in V<sub>m</sub> due to Cell Membrane Charging & Discharging as a Capacitor

**Calculation of Capacitive Current**
- Can be calculated by the derivative of Standard Capacitor Equation ( <abbr Title="Charges stored in Capacitor">Q</abbr> = <abbr Title="Capacitance (Ability of Cell Membrane to Store Charge)">C</abbr><abbr Title="Voltage Difference">V</abbr> )
	- <abbr Title="dQ">I<sub>capacitive</sub></abbr> = <abbr Title="Membrane Capacitance">C<sub>m</sub></abbr> <abbr Title="Change in Membrane Potential Vm over Time t">( dV<sub>m</sub> / dt )</abbr>

**Calculation of Total Current Flow across Cell Membrane**
- I<sub>m</sub> = I<sub>capacitive</sub> +  I<sub>ionic</sub> (V<sub>m</sub> , t)

$$\huge C_{m}\frac{dV_{m}}{dt}+\sum_{idk\;what\;is\;this}^{just\;repeat\;for\;every\;ion}g_{ion} (V_{m },t)\cdot(V_{m}-E_{ion})$$


#### **Ion Channels in Electrical Conduction**
**Categorization of Ion Channels**
- Ion Selectivity
	- Non-selective Cation
	-  Na<sup>+</sup> / Cl<sup>-</sup> / K<sup>+</sup> / H<sup>+</sup> / Ca<sup>2+</sup>
- Gating Mechanisms
	- Physical (Voltage, Force, Temperature & Light)
	- Chemical (Ligand / 2nd Messenger & pH)

**Examples of Ion Channels**

|   Ion Channel    |           Ion Selectivity           | Gating Mechanism |
| :--------------: | :---------------------------------: | :--------------: |
|       KcsA       | K<sup>+</sup> (Pore loop as Filter) |   pH-sensitive   |
| Na<sub>v</sub>Ab |           Na<sup>+</sup>            |  Voltage-gated   |

**Process of Action Potential**
- Mainly relies on actions of the Na<sup>+</sup> & K<sup>+</sup> Channels in Na<sup>+</sup>-K<sup>+</sup> ATPase

|               Stage                | Event                                                                                                                                                                                            |
| :--------------------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <br>Depolarization<br>(Initiation) | Na<sup>+</sup> Channels open (Na<sup>+</sup> enter cell) →<br>Few K<sup>+</sup> Channels open (Some K<sup>+</sup> exit cell) →<br>Na<sup>+</sup> Channels close (Na<sup>+</sup> stop enter cell) |
|           Repolarization           | K<sup>+</sup> Channels open (K<sup>+</sup> exit cell)                                                                                                                                            |
|         Hyperpolarization          | Both Channels close                                                                                                                                                                              |

**Advantages of Electrical Signal Transmission**
- Need for speed in quick response to environment
	- AP Propagation speed can exceed 100m/s