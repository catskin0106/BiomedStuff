Lecture Notes

- Microbiome
- Microbiome and Human Diseases
- Microbiome Analysis

---
#### **Microbiome**
- Genes, Genomes and Products of the Microbiota

|  Component  | Description                                         |
| :---------: | --------------------------------------------------- |
| Prebiotics  | Compounds facilitating beneficial microorganisms    |
| Probiotics  | Live microorganisms providing benefits to gut flora |
| Postbiotics | Soluble factors secreted by live bacteria           |

**Factors Affecting Microbiota**
- Childbirth Method
- Diet (Infant & Adult)
- Personal Habits
- Disease, Medication & Age
- Geography


#### **Microbiome and Human Diseases**
**Microbiota on Educating Immune System**
- Commensal microorganisms train & tune immunoresponses at intestinal epithelium
	- Chemokines / Cytokines: epithelial, myeloid & lymphoid cell communication
	- Postbiotics: Prevent T-Cell attack through reaching DCs in lymph nodes & liver
- Dysbiosis / Altered crosstalk leads to chronic inflammation:
	- Autoinflammatory: IBD, Type 1 Diabetes, RA
	- Neoplastic: Carcinogenesis
	- Metabolic: Obesity, NAFLD, Atherosclerosis
- Examples:
	- SARS-CoV-2
		- Gastrointestinal Symptoms
		- Highest mortality seen in people with co-morbidity of reduced microbiota diversity
	- Upper Respiration Tract Infection
		- Probiotics reported to boost immunoresponses

**Microbiota on Mental Health**
- Affects brain by:
	- Release metabolites to circulatory system
	- Communication with Vagus Nerve → Alter brain signal production
- Examples:
	- Autism
		- 20% Higher in Cesarean Section
	- ADHD
		- Gut microbiota affect Dopamine
	- Stress
		- Dysbiosis increases circulatory toxins → CNS inflammation
	- Depression


#### **Microbiome Analysis**
- Workflow
	- Sample Collection → DNA Extraction & Sequencing → Bioinformatics Analysis → Data Interpretation

**Sequencing Methods**

| Distinctions  |         <          | 16S rRNA Sequencing             | Shotgun Metagenomic Sequencing (WGS) |
| :-----------: | :----------------: | ------------------------------- | ------------------------------------ |
|  Description  |         <          | Target specific 16S rRNA Region | Sequence all DNA in Sample           |
| <br>16S > WGS |        Cost        | Cheaper (50k Reads / Sample)    | Expensive (>1m Reads / Sample)       |
|       ^       | Host Contamination | Yes                             | No                                   |
|       ^       |  Well-Established  | Yes                             | No                                   |
| <br>WGS > 16S |    Primer Bias     | Yes (Choice of Region)          | No                                   |
|       ^       |     Resolution     | Genus level                     | Species / Strain level               |
|       ^       |   Identification   | No virus & eukaryotes           | All microbes (Except rare ones)      |

**Microbiome Diversity Analysis**
- Measures Richness & Evenness of Microbes in a Sample
- Alpha Diversity (Shannon Index): Measures Diversity within a Sample
	- <abbr Title="Relative abundance of taxon i">p<sub>i</sub></abbr> , <abbr Title="Taxa amount in the sample">S</abbr>
$$
H' = - \sum_{i=1}^{S}(p_{i}ln(p_{i}))
$$
- Beta Diversity (Bray-Curtis Dissimilarity Index): Compares Diversity between 2 samples
	- <abbr Title="Sum of lesser count of each species on both sites">C<sub>ij</sub></abbr> , <abbr Title="Total specimen counted in site">S</abbr>
$$
BC_{ij} = 1-\frac{2C_{ij}}{S_{i}+S_{j}}
$$