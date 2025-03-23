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
	- Anti-inflammatory Drugs (COX-1 inhibitors)

**Stimulation of Acid Secretion**

```mermaid
flowchart LR
	subgraph 1["Neural Input"]
	direction LR
	a["Efferent<br>Vagal Pathway"] -- ACh --> c["<font size="2">(N & M<sub>1</sub> Receptors)</font><br>Submucosal Plexus"]
	b["Local<br>Sensory Receptors"] -- ACh --> c
	end
	c -- ACh --> d
	c -- ACh --> e
	subgraph 2["Secretory Cell Stimulation"]
	d["<font size="2">(M<sub>3</sub> Receptors)</font><br>Antral Cells"] -- Plasma Gastrin --> e["<font size="2">(M Receptors)</font><br>EC-Like Cells"]
	end
	c -- ACh --> f
	d -- Plasma Gastrin --> f
	e -- Paracrine Histamine --> f
	subgraph 3["Parietal Cell Stimulation"]
	f["<font size="2">(M<sub>3</sub> & H<sub>2</sub> Receptors)</font><br>Parietal Cells"]
	end
```
