Lecture Notes

**Lecture Coverage:**
- Gastric Ulcer
- Antacids
- Mucosa Protecting Drugs
- Triple Therapy

---
#### **Gastric Ulcer**
**Causes of Gastric Ulcer**
- Direct: 
	- Inability of mucus to protect gastric mucosa
- Indirect:
	- H. Pylori Infection
	- NSAIDs (COX-1 inhibitors)

**H. Pylori Infection**

| Step | Stage                     | Description                        |
| ---- | ------------------------- | ---------------------------------- |
| 1    | Local Inflammation        | H. Pylori attaches to Mucous Cells |
| 2    | Neutrophil Infiltration   | ↑ Gastrin & ↓ Somatostatin         |
| 3    | ↑ H<sup>+</sup> Secretion |                                    |

**Stimulation of Acid Secretion**

```mermaid
flowchart LR
	subgraph 1["<b>Neural Input"]
	a["Efferent<br>Vagal<br>Pathway"] -- ACh --> c["<font size="2">(N & M<sub>1</sub> Receptors)</font><br>Submucosal<br>Plexus"]
	b["Local<br>Sensory<br>Receptors"] -- ACh --> c
	end
	c -- ACh --> d
	c -- ACh --> e
	subgraph 2["<b>Secretory Cell Stimulation"]
	d["<font size="2">(M<sub>3</sub> Receptors)</font><br>Antral<br>Cells"] -- Plasma Gastrin --> e["<font size="2">(M Receptors)</font><br>EC-Like<br>Cells"]
	end
	c -- ACh --> f
	d -- Plasma Gastrin --> f
	e -- Histamine --> f
	subgraph 3["<b>Parietal Cell Stimulation"]
	f["<font size="2">(M<sub>3</sub> & H<sub>2</sub> Receptors)</font><br>Parietal<br>Cells"]
	f -- cAMP --> g["H<sup>+</sup> Secretion"]
	end
```
**Inhibition of Acid Secretion**
- PG Synthesis by COX-1
	- ↓ Parietal Cell H<sup>+</sup> Pump
	- ↑ Mucous Cell Secretion of Mucus & Bicarbonate
- Somatostatin Secretion
	- ↓ Parietal Cell H<sup>+</sup> Pump


#### **Antacids**
- Aim: ↓ Acid Secretion

**Muscarinic M₁ Antagonists**
- [[Lecture 5.1 - (Synaptic Pharmacology) Cholinergic Receptors#**Muscarinic Cholinergic Receptor Drugs**|Atropine-Like Drugs]] (e.g. Pirenzepine)
- Selective Inhibition of ACh Release from Submucosal Plexus
	- Anti-Spasmodic → Analgesic
	- Low CNS Penetration

**Histamine H₂ Antagonists**
- Suffix: -tidine (e.g. Cimetidine, Ranitidine, Famotidine)
- Competitive Inhibition of Histamine Release from EC-Like Cells
	- Heals Ulcers due to Food / Gastrin
	- Treats <abbr Title="Gastro-Esophageal Reflux Disorder">GERD</abbr>

**Proton Pump Inhibitors (PPI)**
- Suffix: -zole (e.g. Omeprazole)
- Irreversible Inhibition on H<sup>+</sup>/K<sup>+</sup>-ATPase as Sulphenamide
	- Absorbed in Duodenum
	- Accumulates in Parietal Cell Canaliculi


#### **Mucosa Protecting Drugs**
- Aim: ↑ Mucus & Bicarbonate Secretion

|         Drug         | Function                             |
| :------------------: | ------------------------------------ |
|      Sucralfate      | ↑ PG → ↑ Mucous Cell Secretion       |
|     Misoprostol      | PG Agonist → ↑ Mucous Cell Secretion |
| Carbenoxolone Sodium | ↑ Mucus Secretion & Viscosity        |


#### **Triple Therapy**
- Regimen to treat H. Pylori Infection

|      Drug       | Function                             |
| :-------------: | ------------------------------------ |
|  Metronidazole  | PPI                                  |
| Bismuth Chelate | Sucralfate-Like Drug & Antibacterial |
| Clarithromycin  | Antibiotic                           |
