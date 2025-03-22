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

**Coagulation Cascade**
- 3 Pathways: Extrinsic, Intrinsic & Common
- Involves <abbr Title="Xa">activated</abbr> factors activating <abbr Title="X → Xa">another factor</abbr> until clot formation:
	- Gray (2,9,10 & Blood Clot): Additionally requires Ca<sup>2+</sup> to be activated
	- Red (5,8,13): Requires Factor IIa (Thrombin) to be activated
	- Green: Starting point of Each Pathway
		- 3: Requires 
	- Some Factors require additional molecules to be activated:

|   Color & Factors   | Note | Required Molecule |
| :-----------------: | ---- | ----------------- |
| 2,9,10 & Blood Clot |      |                   |
|         5,          |      |                   |
|                     |      |                   |

```mermaid
flowchart LR
classDef Ca fill:#aaa
classDef Thrombin fill:#fdd
classDef Start fill:#bfb
    subgraph box1 [<abbr Title="7+3=10">Extrinsic Pathway</abbr>]
		direction LR
		XII:::Start-->XI
		XI-->IX:::Ca
		VIII:::Thrombin
    end
    subgraph box2 [<abbr Title="12 to 8 without 10">Intrinsic Pathway</abbr>]
	    direction RL
	    VII
	    III:::Start
    end
    subgraph box3 [<abbr Title="10=5*2*1 plus 13">Common Pathway</abbr>]
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
