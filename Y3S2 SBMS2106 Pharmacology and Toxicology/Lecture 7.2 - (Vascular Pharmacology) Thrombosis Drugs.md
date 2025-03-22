Lecture Notes

**Lecture Coverage:**
- Thrombosis
- Antiplatelets
- Anticoagulants
- Thrombolytic

---
#### **Thrombosis**
- Abnormal Activation of Coagulation Cascade → Blood Clot Formation
	- ∵ Oxidized LDL Accumulation on vessel wall → Endothelial Injury
- Clots mainly consist of Fibrin & Platelets
	- Platelet Coagulation happens through Platelet Adhesion
		- Regulated by Prostanoids
	- Fibrin Coagulation happens through Coagulation Cascade

**Platelet Coagulation**


**Fibrin Coagulation through Coagulation Cascade**
- 3 Pathways: Extrinsic, Intrinsic & Common
- Involves <abbr Title="Xa">activated</abbr> factors activating <abbr Title="X → Xa">another factor</abbr> until clot formation:
	- Some Factors require additional molecules / condition to be activated:

|                                      Color & Factors                                       | Additional Condition                                                  |
| :----------------------------------------------------------------------------------------: | --------------------------------------------------------------------- |
|                                   II, IX, X & Blood Clot                                   | Ca<sup>2+</sup>                                                       |
|                           <font color="red">V, VIII, XIII</font>                           | IIa (Thrombin)                                                        |
| <font color="lime">III</abbr></font><br><font size="2">(Start of Intrinsic Pathway)</font> | Endothelium Damage                                                    |
| <font color="lime">XII</abbr></font><br><font size="2">(Start of Extrinsic Pathway)</font> | Collagen / <abbr Title="Heavy Molecular Weight Kininogen">HMWK</abbr> |

```mermaid
flowchart LR
classDef Ca fill:#aaa
classDef Thrombin fill:#fdd
classDef Start fill:#bfb
    subgraph box1 [<b><abbr Title="7+3=10">Extrinsic Pathway</abbr>]
		direction LR
		XII:::Start-->XI
		XI-->IX:::Ca
		VIII:::Thrombin
    end
    subgraph box2 [<b><abbr Title="12 to 8 without 10">Intrinsic Pathway</abbr>]
	    direction RL
	    VII
	    III:::Start
    end
    subgraph box3 [<b><abbr Title="10=5*2*1 plus 13">Common Pathway</abbr>]
	    X["<abbr Title="Needs either 3+7 or 8+9">X</abbr>"]:::Ca-->II
	    V:::Thrombin-->II:::Ca
	    II-->I
	    I
	    XIII:::Thrombin
    end
    I-->final["Stable Fibrin Clot"]:::Ca
	XIII-->final
    III-->X
    VII-->X
    VIII-->X
    IX-->X
```

#### **Antiplatelets**
