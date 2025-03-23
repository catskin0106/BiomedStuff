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

**Process of Acid Secretion**

| Step  |           Stage            | Description                                | Receptors Involved |
| :---: | :------------------------: | ------------------------------------------ | ------------------ |
| <br>1 |      <br>Neural Input      | Parasympathetic Nerve<br>- Local Receptors |                    |
|   2   | Secretory Cell Stimulation |                                            |                    |
```mermaid
flowchart LR
	subgraph 1["Neural Input"]
	direction LR
	a["Efferent Vagal Pathway"] -- ACh --> c["<font size="2">(N & M<sub>1</sub> Receptors)</font><br>Submucosal Plexus"]
	b["Local Sensory Receptors"] -- ACh --> c
	end
	c -- ACh --> d
	c -- ACh --> e
	subgraph 2["Secretory Cell Stimulation"]
	d["Antral Cells"] -- Plasma Gastrin --> e["EC-Like Cells"]
	end
	c -- ACh --> f
	d -- Plasma Gastrin --> f
	e -- Histamine --> f
	subgraph 3["Parietal Cell Stimulation"]
	f["Parietal Cells"]
	end
```