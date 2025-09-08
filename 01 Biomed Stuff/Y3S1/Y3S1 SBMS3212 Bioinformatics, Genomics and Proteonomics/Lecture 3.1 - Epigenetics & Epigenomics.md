Lecture Notes

- Epigenetics and Epigenomics
- Histone Modifications
- DNA Methylation
- Clinical Applications

---
#### **Epigenetics and Epigenomics**
**Epigenetics**
- Heritable stable traits not explained by DNA sequences
- Histone Modification & DNA methylation affecting gene expression 
	- When and how genes are turned on / off
	- Can determine cell types
	- Affected by environment & diseases

**Epigenomics**
- Analysis of epigenetic changes across many genes in cell / organism


#### **Histone Modification**
- Methylation (Activation) / Acetylation (Activation & Repression) / Phosphorylation (Activation)
- Involves different enzymes / proteins
	- Writers: Enzymes that add a mark (modification)
	- Erasers: Enzymes that remove a mark (un-modification)
	- Readers: Proteins that bind to the mark to influence gene expression (interpretation)
- Format: <abbr Title="Histone">H2</abbr><abbr Title="A.A. Residue">A</abbr><abbr Title="Residue location from N terminal">10</abbr><abbr Title="Modification Type">me1</abbr>

**Measurement of Histone Modifications**
- Chromatin Immunoprecipitation (ChIP) for localizing histone marks
	- Limitations: 
		- Antibody specificity
		- Inherent biases of localization method
		- ChIP-qPCR: Only for known target genes
	- ChIP-chip, ChIP-seq: Less Biased
- Mass spectrometry
	- Limitations: Histone digestion is required
Workflow:
	- Sample preparation → Sequencing → Computational analysis 


**Histone Modifications in Cancers**
- Changes in associated proteins leading to the generation of super-enhancers / megadomains
	- Change in NUT gene → Midline carcinoma
		- Feed-forward model: NUT recruits p300 for BRD4 acetylation loop → Megadomain formation
	- MYC oncogene → Multiple Myeloma
		- Treated with BET Bromodomain inhibitor JQ1


#### **DNA Methylation**
- Happens primarily at CpG dinucleotides (~1% of genome)
	- Not evenly spaced & symmetrical
	- Spatially correlated methylation

**Measurement of DNA Methylation**
- Bisulphite Conversion (BS-seq)
	- Chemical process to create SNPs: C → T while met-C are protected
		- C/T Ratio = Proportion of Methylation
	- Whole genome & Targeted BS-seq

| Differences | Whole genome BS-seq         | Targeted BS-seq                             |
| ----------- | --------------------------- | ------------------------------------------- |
| Coverage    | Genome-wide (Gold Standard) | Regions of interest (by restriction enzyme) |
| Cost        | High                        | Low                                         |
- <abbr Title="Algorithm for the Reconstruction of Accurate Cellular Networks">ARACNE</abbr>
	- Distinguish cascade gene interactions with information theoretical approach
		- Supplementary to genome-wide clustering of gene expression profiles
- Single Nucleotide / Regional Resolution
	- Array Sequencing
- Methylated DNA enrichment
- Limitations:
	- Correct alignment of reference sequence needed
		- Aligned sequence might not match reference
	- Reduced complexity of libraries (Many C → T)
	- Methylation is not symmetrical



**DNA Methylation in Cancer**
- Overexpression of miR-200 Family leads to less aggressive cancer cells


#### **Clinical Applications**
**Biomarkers**
- DNA hypermethylation: Transcriptional suppression
- DNA hypomethylation: Improved aneuploidy

**Diagnosis**
- Prediction / Test
	- Commercial Kits for DNA methylation (SEPT9 gene methylation assay for colorectal cancer)
	- Selected non-invasive DNA methylation tests
- Advantages:
	- Early diagnosis in tumorigenesis
	- Highly tissue specific & consistent among individuals

**Prognosis**
- Colorectal cancer survival
	- <abbr Title="Cell-free">cfDNA</abbr> methylation profiling

**Early Cancer Detection**
- Circulating Cell-free Genome Atlas Study (CCGA)
	- Targeted methylation-based multi-cancer early detection(MCED) test 

**Chemotherapy Resistance Test**
- Related to both hypermethylation (DCR1 in Colorectal Cancer) & hypomethylation (CDO1 in Colorectal Cancer)

**Epigenetic Therapeutics**
- Decitabine reduce methylation → miR-200 Family re-expression
	- Overexpression of miR-200 Family leads to less aggressive cancer cells