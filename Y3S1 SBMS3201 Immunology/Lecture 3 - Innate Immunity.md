Lecture Notes

**Lecture Coverage:**
- Innate Immunity
- Complement System
- Bridging between Innate and Adaptive Immunity

---
#### **Innate Immunity**
**1st Line of Defense: Physical Barrier**
- Keratin on Skin
- Mucosal & Glandular Surface
	- Expel response in airway & lungs
		- Facilitated by cilia & mucus
	- Mucus in GI Tract

**1st Line of Defense: Chemical Barrier**
- Acidic pH & Digestive Enzymes in GI Tract
- Antimicrobial Peptides

| Antimicrobial Peptides | Location                              | Antimicrobial Activities                                                                              |
| ---------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Lysozyme               | Mucosal/Glandular Secretions          | Bacterial <abbr Title="Through cleavage of glycosidic bonds in peptidoglycans">Cell Wall Lysis</abbr> |
| Defensin α/β           | Skin & Mucosal Epithelia              | Disrupt membranes of pathogens                                                                        |
| Surfactant Proteins    | Respiratory Tract & Mucosal Epithelia | Block bacterial surface components<br>Promotes Phagocytosis                                           |

**Receptors in the 2nd Line of Defense: PRRs**
- Major Type of PRR: <abbr Title="Toll-like Receptor Family">TLR</abbr>
	- Membrane-bound to Plasma membrane, Endosome & Lysosome
	- <abbr Title="Leucine-rich Repeats">LRR</abbr> as recognition regions
		- Plasma membrane: Outside membrane
		- Endosome & Lysosome: <abbr Title="Due to pathogens being ingested">Inside membrane</abbr>
	- TLR Ligands:

| TLR Ligands               | Pathogens Detected   |
| ------------------------- | -------------------- |
| Lipopolysaccharides       | Gram -ve pathogens   |
| Peptidoglycan             | Gram +ve pathogens   |
| Cell wall polysaccharides | Fungi                |
| Flagellins                | Flagellated bacteria |
| DNA & RNA                 | Virus & Bacteria     |
- TLR Signaling Pathway:

| Step  | Process                                                                                                                               |
| :---: | ------------------------------------------------------------------------------------------------------------------------------------- |
|   1   | Ligand-induced TLR Dimerization                                                                                                       |
| <br>2 | Cascade of Common & Unique signaling components<br>- Common: NF-κB<br>- Unique: <abbr Title="Interferon Regulatory Factor">IRF</abbr> |
| <br>3 | Transcription of Proteins<br>- Cytokines, Chemokines & Antimicrobials<br>- Not phagocytic receptors                                   |
- Other types of PRRs:

| PRR                                              | Ligands                             | Note                                    |
| ------------------------------------------------ | ----------------------------------- | --------------------------------------- |
| <abbr Title="C-Type Lectin Receptors">CLR</abbr> | Pathogen Carbohydrates<br>Allergens | Phagocytic receptors on plasma membrane |
| <abbr Title="Nod-like Receptors">NLR</abbr>      | Cytosolic Pathogens                 | Part of NLR inflammasome                |
| <abbr Title="AIM-2 Like Receptors">ALR</abbr>    | Cytosolic DNA (dsDNA)               | <br>/                                   |
| <abbr Title="RIG-like Receptors">RLR</abbr>      | Cytosolic RNA (dsRNA)               | ^                                       |

**2nd Line of Defense: Local Inflammation**
- Caused by infection, tissue damage or harmful substance
- A cascade of innate response events by <abbr Title="Pattern Recognition Receptor">PRR</abbr> Signaling:
```mermaid
graph TD 

A(Production of <abbr Title="IL-1β,TNF-α, IL-6">Cytokines</abbr> & <abbr Title="IL-8">Chemokines</abbr>) --> B(Vascular Endothelium Activation<br>Vascular Permeability ↑) 
B --> C(Influx of blood containing anti-microbials & phagocytes)
C --> F(Symptoms: Redness, Swelling, Heat & Pain)
A --> D(Cytokines in Liver stimulate Acute Phase Protein production <br> e.g. <abbr Title="C-Reactive Protein">CRP</abbr>)
D --> E(CRP Functions as Opsonin & Inflammation marker)
```


**2nd Line of Defense: Phagocytosis**

| Step  | Event                                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | PAMP/DAMP recognized by PRRs on Phagocytes, or<br>Opsonin recognized by Opsonin receptors                                                     |
| 2     | Pseudopodium extends to ingest microbe                                                                                                        |
| 3     | Phagosome forms and fuses with lysosome                                                                                                       |
| <br>4 | Microbe is killed by:<br>- Anti-microbial peptides<br>- Low pH<br>- <abbr Title="Reactive Oxygen/Nitrogen Species (ROS/RNS)">Oxidative Attack |

<br>


#### **Complement System**
- Immunoresponse enhancing host defenses through:

|                                                          Process                                                          |            <             | Molecules involved                                                                                                           | Receptors   |
| :-----------------------------------------------------------------------------------------------------------------------: | :----------------------: | ---------------------------------------------------------------------------------------------------------------------------- | ----------- |
|                                                        Cell Death                                                         |            <             | <abbr Title="Membrane Attack Complex">MAC</abbr>:C5b678 + Poly-C9                                                            | /           |
|                                                       Opsonization                                                        |            <             | Opsonin: C3b & C4b                                                                                                           | CR1         |
|                                                       Inflammation                                                        |            <             | <abbr Title="Chemoattractants to induce proinflammatory cytokine expression in other cells">Anaphylatoxins: C3a & C5a</abbr> | C3aR & C5aR |
|                                             <br>Adaptive Immunity cross-talk                                              |   Antigen uptake by DC   |                                                                                                                              |             |
|                                                             ^                                                             | B-Cell mediated immunity | CD21 Ligand: C3d                                                                                                             | CR2 (CD21)  |
| <abbr Title="Immunoresponse termination & disposal of apoptotic bodies / immune complex">Immunoresponse Contraction Phase |            <             |                                                                                                                              |             |

**Complement System Pathway**
- 3 major pathways → C3 & C5 Convertase generation → <span style="color:lightblue">Complement Receptor Activation</span>

```mermaid
stateDiagram-v2

classDef style1 color:lightblue
class 0113,0116,0211,0212 style1

    001: Classical Pathway
    state 001 {
        0011: Antibody IgM / IgG recognizes antigen
        0012: Immune complex formation
        0011 --> 0012
    }
    002: Lectin Pathway
    003: Alternative Pathway
    002 --> 011
    001 --> 011
    003 --> 011
    011: C3 & C5 Convertase generation
    state 011 {
	    0212: <abbr Title="B-Cell activation for antigen uptake & presentation">C3d binds to CR2(CD12)</abbr>
        0111: C3 Convertase generation
        0112: C3 Convertase cleaves C3 into C3a + C3b
        0113: <abbr Title="Inflammation">C3a binds to C3aR</abbr>
        0119: <abbr Title="Phagocytosis & Degradation in liver">C3b binds to Fc region of immune complex</abbr>
        0114: C3b + C3 convertase = C5 Convertase
        0115: C5 Convertase cleaves C5 into C5a + C5b
        0116: <abbr Title="Inflammation">C5a binds to C5aR</abbr>
        0117: C5b acts as Binding site for MAC
        0118: MAC induces cell death by damaging membrane integrity
        0111 --> 0112
        0112 --> 0113
        0112 --> 0211
        0112 --> 0119
        0112 --> 0114
        0114 --> 0115
        0115 --> 0116
        0115 --> 0117
        0117 --> 0118
        0211: <abbr Title="Oposnization for Phagocytosis & Inflammatory Factor Secretion">C3b & C4b binds to CR1</abbr>
    }

```


<br>

#### **Bridging between Innate and Adaptive Immunity**
- Involves <abbr Title="Dendritic Cells">DCs</abbr> at different states & APCs
	- Professional APCs: DCs, Macrophages & B-Cells
		- Requires Co-stimulatory molecules CD80/86 & MHCII to activate T-Cells

|   DC State   | Immunity System | Actions                                                                                                                                                                                                          |
| :----------: | :-------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   Immature   |     Innate      | Recognize PAMPs through PRRs<br>-Activates phagocytosis & signaling pathway                                                                                                                                      |
|  Transition  |        <        | Carry bound microbes and travel to secondary lymphatic tissues<br>-Internalizes foreign antigen & expresses it on MHCII                                                                                          |
| Mature (APC) |    Adaptive     | <abbr Title="Increased MHCII, CD80 & CD86 level">Matures & Becomes APC by PRR</abbr> signaling<br>- Presents <abbr Title="Major Histocompatibility Complex">MHC</abbr>-Antigen complex to activate naïve T-cells |
- Activation of T-Cells are pathogen specific
	- T<sub>H</sub> cells
		- Different pathogen → different TLR responses → DC release different IL → Different TH types

| Pathogen          | TLR                    | IL by DC              | T-Cell                                          | Effects                                                                                               |
| ----------------- | ---------------------- | --------------------- | ----------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Gram -ve bacteria | 4(5)                   | <br>IL-12             | <br>T<sub>H</sub>1     ㅤ                        | <br>IFNγ ↑ → <abbr Title="Macrophage M1, Viral specific Tc cells & B Cells">Cellular Responses</abbr> |
| Virus             | 3/7/9                  | ^                     | ^                                               | ^                                                                                                     |
| Gram +ve bacteria | 2/1                    | <br>IL-10<br>(IL-12↓) | T<sub>H</sub>2                                  | IL-4/5/13 ↑ → <abbr Title="Antibodies">Humoral Responses</abbr>                                       |
| Parasite          | 2/6                    | ^                     | T<abbr Title="regulatory"><sub>reg</sub></abbr> | TGF-β1/IL10 ↑ → Cytokine/APC Inhibition                                                               |
| Fungi             | CLR/Dectin-1 (Not TLR) | TNF-α & IL-6/23       | T<sub>H</sub>17                                 | IL-17 ↑ → <abbr Title="Phagocytic Neutrophils">Cellular Responses                                     |
- T<sub>C</sub> cells
	- Cross-presentation

**Major Histocompatibility Complex**
- Characteristics of MHCs (Called <abbr Title="Human Leukocyte Antigen">HLA Complex</abbr> in humans):

| Characteristic  | <                                      | Explanation                                                                                                              |
| --------------- | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| <br>Biochemical | Membrane-bound Glycoproteins           | Only in Class I & II (Not Class III)                                                                                     |
| ^               | Promiscuous                            | 1 MHC can bind to several peptides;<br>1 peptide can bind to several MHCs                                                |
| Genetic         | Polymorphism in Antigen-binding Region | Encoded by a cluster of genes with different alleles                                                                     |
| ^               | Co-dominant haplotypes                 | Both maternal & paternal alleles will be expressed<br>- 25% histocompatibility in offspring<br>- Difficult to transplant |

- Classes of MHCs

|                          | MHCI                                                                                     | MHCII                                                          |
| ------------------------ | ---------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| Subtypes                 | HLA-(A/B/C)                                                                              | HLA-D(P/Q/R)                                                   |
| Cell Types with Presence | Nucleated Cells                                                                          | APC                                                            |
| MHC-T Complex            | <abbr Title="Cytotoxic T Lymphocytes">CD8+</abbr> T Cells                                | <abbr Title="Helper T Cells">CD4+</abbr> T Cells               |
| Antigen Presented        | Endogenous<br>- Healthy cells: Self peptides<br>- Viral infected cells: Foreign peptides | <abbr Title="e.g. from phagocytosed bacteria">Exogenous</abbr> |
- Function of MHC: 
	- Binds to self/foreign antigens & presents them to appropriate T-Cell surfaces for recognition

| Molecule Presented          | Location                  | Function                                      |
| --------------------------- | ------------------------- | --------------------------------------------- |
| Self MHCI                   |                           | Show cell is healthy                          |
| Self peptide (by MHCI & II) | Primary Lymphoid Organs   | Check autoreactivity                          |
| ^                           | Secondary Lymphoid Organs | Develop self-tolerance                        |
| Foreign peptide (by MHCI)   | CTL / T<sub>C</sub>       | Show infected cell -> Activates T<sub>C</sub> |
| Foreign peptide (by MHCII)  | T<sub>H</sub>             | Show infected cell -> Activates T<sub>H</sub> |

**Antigen Processing & Presentation of MHC**
- Processing separated into endogenous & exogenous pathways

| Stage              | <                                  | MHCI (Endogenous Pathway)                                                                                                     | MHCII (Exogenous Pathway)                                          |
| ------------------ | ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| <br><br>Processing | Antigen Internalization            | Internal synthesis of viral protein<br>- ∵ When APCs are infected                                                             | Endocytosis of incompetent virus<br>- ∵ When APCs are not infected |
| ^                  | Antigen Digestion                  | Antigen degraded by Proteasome                                                                                                | Antigen degraded by endosomal/lysosomal enzymes                    |
| ^                  | MHC-peptide complex Transportation | From cytoplasm to cell membrane                                                                                               | <                                                                  |
| <br>Recognition    | Self-MHC Restriction               | Both T<sub>H</sub> & T<sub>C</sub> only recognizes antigens presented by self-MHC<br>- APC & T-Cell MHC haplotypes must match | <                                                                  |
| ^                  | Cell Activation                    | <abbr Title="Cytotoxic T Lymphocytes">CD8+</abbr> T Cells                                                                     | <abbr Title="Helper T Cells">CD4+</abbr> T Cells                   |

- Cross-Presentation on DCs
	- Can switch from exogenous pathway to endogenous pathway
		- "Disguise" as infected APCs -> Activate T<sub>C</sub> Cells even APC is not targeted by virus
			- Inhibit further spread of infection
	- Requires licensing of antigen-specific T<sub>H</sub> cells
		- Prevents accidental T<sub>C</sub> Cell activation by safe/self antigens

| Stage                              | <                                | Process                                                                                                                                  |
| ---------------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Original Exogenous Pathway         | <                                | Antigen processed in DCs as usual                                                                                                        |
| <br>APC-T<sub>H</sub> Interactions | Antigen Presentation             |                                                                                                                                          |
| ^                                  | Licensing                        | CD40 Ligand - CD40 interaction                                                                                                           |
| <br>Cross Priming                  | DC Altered Metabolism            | <abbr Title="Activates CTL">CD80 & CD86</abbr> ↑<br><abbr Title="Inhibits CTL Activation">Programmed cell Death Ligand 1 (PDL1)</abbr> ↓ |
| ^                                  | T<sub>H</sub> Altered Metabolism | <abbr Title="Activates CTL">IL-2</abbr> ↑                                                                                                |
