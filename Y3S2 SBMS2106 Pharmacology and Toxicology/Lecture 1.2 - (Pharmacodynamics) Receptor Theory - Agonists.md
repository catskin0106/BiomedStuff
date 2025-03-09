Lecture Notes

**Lecture Coverage:**
- Receptor Affinity, Occupancy & Efficacy
- Full & Partial Agonists
- Interaction between Agonists under Different Receptor Reserves

---
#### **Receptor Affinity, Occupancy & Efficacy**
**Affinity (1/Kd)**
- The Tendency of a Ligand to bind with Receptor:
$$\Large \ce{[A][R] <=>[k1][k_{-1}] [AR]}$$
- Equilibrium: <abbr Title="[A][R]k₁">Forward Rate</abbr> = <abbr Title="[AR]k₂">Backward Rate</abbr>

| **Variable** |                   **Affected by**                   | **Value within Same Agonist Series** |
| :----------: | :-------------------------------------------------: | :----------------------------------: |
|      k1      | [A] Diffusion Rate<br>[A] [R] Collision Probability |               Similar                |
|      k2      |                   [AR] Stability                    |                Varies                |

- Factors affecting Collision Probability:
	- 3D Conformation of Ligand & Receptor
	- Molecular Size & Shape
	- Lipid Solubility to Cross Plasma Membrane
	- pH & Ionization


- - Equilibrium dissociation constant (Kd): Concentration at which <abbr Title="50% of the receptors are occupied">Occupancy (y) = 0.5</abbr>:
    -  Or Tendency of AR to dissociate: Kd ∝ 1 / Affinity
$$\Large Kd = \frac{k_{-1}}{k_{1}} \text{ or } \frac{[A][R]}{[AR]}$$

**Occupancy (y)**
- Fraction of the Receptors occupied:
$$\Large y = \frac{[A]}{[A] +Kd}$$
- Dimensions of Occupancy
	- Kd & [A] have dimensions of concentration (i.e. a unit)
	- y is a dimensionless ratio


**Biological Stimulus (S)**
- Total input to the transduction system from ligand-receptor binding:
	- Affected by Efficacy (e) & Occupancy (y)
$$\Large S = ey$$
- Might be lowered in Desensitization by:
	- Receptor Modification / Phosphorylation
	- Receptor Internalization

#### **Full & Partial Agonists**
**Types of Functional Agonists**
- Full Agonists: Can achieve E<sub>max</sub> of 100% in <abbr Title="Concentration-Response Curve">CRC</abbr> 
	- Possibly without occupying all receptors
- Partial Agonists: With E<sub>max</sub> lower than 100%

**Explanation for Partial Agonism**

|    **Explanation**    | **Explanation**                                                                    |
| :-------------------: | :--------------------------------------------------------------------------------- |
|  Two Receptor System  | Partial agonist activate a different receptor with weaker effect than full agonist |
| Functional Antagonism | Same Partial agonist can activate 2 types of receptors with opposing effects       |
|       Efficacy        | <abbr Title="Due to conformation">Agonist has lower efficacy</abbr>                |

**Advantages & Disadvantages for Partial Agonist Drugs**
- Advantages:
	- ↓ Side Effects  
	- <abbr Title="Limit Biological Stimulus after certain dosage">Ceiling Effect</abbr>
		- ↓ Abuse & Overdose Potential
		- Manage Withdrawal Symptoms

**Inverse Agonists**
- Ligands that bind to same receptor but have opposing pharmacological responses to agonist
	- Reduces CRC response below the level observed in the absence of any ligand [(Diagram)](2106_CRC.png)



#### **Interaction between Agonists under Different Receptor Reserves**

| **Receptor Reserve** | **Agonists Present** | **Biological Stimulus / Response**                                                                               |
| :------------------: | -------------------- | ---------------------------------------------------------------------------------------------------------------- |
| <br>Most unoccupied  | Full only            | None / Low                                                                                                       |
|          ^           | Partial only         | Lower than Full Only                                                                                             |
|          ^           | Full + Partial       | <abbr Title="Additive Effect by Full & Partial Agonists">Medium</abbr>                                           |
|  <br>Most occupied   | Full only            | High                                                                                                             |
|          ^           | Partial only         | <abbr Title="↓ efficacy for each activated receptor">Lower than Full Only</abbr>                                 |
|          ^           | Full + Partial       | <abbr Title="Partial Agonists occupy receptors that Full Agonists could've occupied">Lower than Full Only</abbr> |
