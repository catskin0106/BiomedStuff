Lecture Notes

**Lecture Coverage:**
- Plasma Concentration Curve of Drugs
- Models to Quantify Drug Distribution & Elimination

---
#### **Plasma Concentration Curve of Drugs**
**Properties of Plasma Concentration Curve**
![[Pasted image 20250302192418.png]]


**Therapeutic Index**
![[Pasted image 20250302192432.png|300]]
- TI = <abbr Title="Toxic Dose in 50% Population">TD<sub>50</sub></abbr> / <abbr Title="Effective Dose in 50% Population">ED<sub>50</sub></abbr>


**Therapeutic Drug Monitoring (TDM)**
- Collection of Blood samples at fixed time relative to drug administration intervals
- Needed if:
	- Drug has narrow TI → High Toxicity Risk
		- E.g. Digoxin, Phenytoin & Cyclosporine
	- Patient Non-compliance
	- Lack of / Not Easily Quantified Therapeutic Responses
	- Variability in Drug Dose-Concentration relationship


#### **Models to Quantify Drug Distribution & Elimination**
**Pharmacokinetics Variables**

|                    Variable                    | Description                                                                                     | Formula                                                                                                                                        |
| :--------------------------------------------: | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
|                Cp<sup>(t)</sup>                | Drug Concentration at time t                                                                    | /                                                                                                                                              |
|                       V                        | Volume of Distribution                                                                          | [[Lecture 2.2 - (Pharmacokinetics) Distribution#**Drug Distribution**\|There]]                                                                 |
|            <abbr Title="">k</abbr>             | Abstract Rate of Elimination                                                                    | Cp = Cp<sup>0</sup>e<sup>-kt</sup><br><abbr Title="Logarithm Form (Straight Line Equation)">log Cp = (-k / 2.303)t + log Cp<sup>0</sup></abbr> |
| <abbr Title="Half-Life">t<sub>1/2</sub></abbr> | Time for Cp<sup>0</sup> to be halved                                                            | First Order Kinetics: 0.693 / k                                                                                                                |
|   <abbr Title="Clearance">CL</abbr> (mL/min)   | Blood Volume cleared from Drug per unit time                                                    | k<abbr Title="Volume of Distribution">V</abbr>                                                                                                 |
|       <abbr Title="Area Under Curve">AUC       | Measure of <abbr Title="Bioavailability">F</abbr>: Amount of Drug Reaching Systemic Circulation | Dose / CL                                                                                                                                      |

**One Compartment Model**
- Model that considers body as a single compartment in which drug distributes homogeneously
	- Mostly hydrophilic drugs (Antibiotics)
- Different Drugs have different rate of elimination in relation to k:
	- First Order: [Same % of Drugs Eliminated](3206_FirstOrder.png)
	- Zero Order: [Same volume of Drugs Eliminated](3206_ZeroOrder.png)

| Kinetics    | Elimination Rate         | Changes in t<sub>1/2</sub> & CL                                    |
| ----------- | ------------------------ | ------------------------------------------------------------------ |
| First Order | Constant                 | Constant                                                           |
| Zero Order  | Inversely varies with Cp | t<sub>1/2</sub> Inversely Proportional<br>CL Directly Proportional |


**Two Compartment Model**
- Drug distributes differently in various body compartments
	- Central compartment: Rapid & Uniform
	- Tissue compartment: Slow Equilibration