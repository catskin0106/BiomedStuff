Lecture Notes

**Lecture Coverage:**
- Gastric Ulcer
- Drugs for Gastric Ulcer

---
#### **Gastric Ulcer**
**Causes of Gastric Ulcer**
- Direct: 
	- Inability of mucus to protect gastric mucosa
- Indirect:
	- H. Pylori Infection
	- NSAIDs (COX-1 inhibitors)

**Stimulation of Acid Secretion**

```mermaid
flowchart LR
	subgraph 1["Neural Input"]
	a["Efferent<br>Vagal<br>Pathway"] -- ACh --> c["<font size="2">(N & M<sub>1</sub> Receptors)</font><br>Submucosal<br>Plexus"]
	b["Local<br>Sensory<br>Receptors"] -- ACh --> c
	end
	c -- ACh --> d
	c -- ACh --> e
	subgraph 2["Secretory Cell Stimulation"]
	d["<font size="2">(M<sub>3</sub> Receptors)</font><br>Antral<br>Cells"] -- Plasma Gastrin --> e["<font size="2">(M Receptors)</font><br>EC-Like<br>Cells"]
	end
	c -- ACh --> f
	d -- Plasma Gastrin --> f
	e -- Histamine --> f
	subgraph 3["Parietal Cell Stimulation"]
	f["<font size="2">(M<sub>3</sub> & H<sub>2</sub> Receptors)</font><br>Parietal<br>Cells"]
	f -- cAMP --> g["H<sup>+</sup> Secretion"]
	end
```
**Inhibition of Acid Secretion**
- PG Synthesis by COX-1
	- ↓ Parietal Cell H<sup>+</sup> Pump
	- ↑ Mucous Cell Secretion of Mucus + Bicarbonate


#### **Drugs for Gastric Ulcer**
**Muscarinic M1 Antagonists**