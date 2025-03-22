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
```mermaid
flowchart LR
classDef Ca fill:yellow
classDef Thrombin fill:
    subgraph box1 [<abbr Title="7+3=10">Extrinsic Pathway</abbr>]
		direction LR
		XII-->XI
		XI-->IX:::Ca
		VIII:::Thrombin
    end
    subgraph box2 [<abbr Title="12 to 8 without 10">Intrinsic Pathway</abbr>]
	    direction RL
	    VII
	    III
    end
    subgraph box3 [<abbr Title="10=5*2*1 plus 13">Common Pathway</abbr>]
	    X["<abbr Title="Needs either 3+7 or 8+9">X</abbr>"]:::Ca-->II
	    V:::Thrombin-->II:::Ca
	    II-->I
	    I
	    XIII:::Thrombin
    end
    I-->final["Stable Fibrin Clot"]
	XIII-->final
    III-->X
    VII-->X
    VIII-->X
    IX-->X
```
