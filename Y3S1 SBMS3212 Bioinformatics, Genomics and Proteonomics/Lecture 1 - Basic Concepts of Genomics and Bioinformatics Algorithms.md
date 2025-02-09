Lecture Notes

**Lecture Coverage:**
- Human Genome and Function
- Genome Sequence Data
- Human Reference Genome
- Bioinformatic Analyses
- Algorithms

---
#### **Human Genome and Function**
- Store, Propagate & Express Genetic Information for Cell Machinery

**Non-Protein Coding DNA (98.5%)**

|          Type          | Function                                                                                  |
| :--------------------: | ----------------------------------------------------------------------------------------- |
|    Heterochromatin     | Regulate Transcription<br>Contains Simple Sequence Repeats (2-1k b.p.) as Genetic Markers |
| Segmental Duplications | In multiple locations (>1k b.p.)                                                          |
| Transposable Elements  | Source of mutations<br>e.g. LINE, SINE, Retrotransposons                                  |


#### **Genome Sequence Data**
**Types of Genomic Assays**

| Coding Region |                   <                   |
| :-----------: | :-----------------------------------: |
|    <br>DNA    |             Whole Genome              |
|       ^       |       Specific-Enriched Regions       |
|    <br>RNA    |                 mRNA                  |
|       ^       | <abbr Title="Non-coding">nc</abbr>RNA |


**Sequencing Methods**

|          Method           |                         Description                          |
| :-----------------------: | :----------------------------------------------------------: |
|     Sanger Sequencing     |          Flanking primers to sequence short regions          |
|    Shotgun Sequencing     |          Sequence entire genome in small fragments           |
|            NGS            | PCR amplify genomic fragments annealed with common adapters  |
| TGS<br>(PacBio, Nanopore) | Longer Read but Lower Accuracy & Cost-Effectiveness than NGS |

- Quality of NGS
	- Optimized by:
		- Verifying Biases: Fragmentation / PCR Amplification
		- Detecting & Filtering Errors: Polymerase mistakes / Imaging issues
	- Base Calling Accuracy is represented by Phred Quality Score
		- Q = -10 log<sub>10</sub> (<abbr Title="Probability of Incorrectness out of 1">P</abbr>)



**Sequencing Data Formats**
- FASTA: Store reference genome
- FASTQ: Store genome fragments before mapping
	- Line 1: Header
	- Line 2: DNA Sequence
	- Line 3: + (Comments)
	- Line 4: Phred Quality Score (ASCII 33-126)
- SAM/BAM: Store genome fragments after mapping
	- PacBio: zmw.bam & subread.bam


#### **Human Reference Genome**
- Reference for mapping the location of gene sequences

**The Human Genome Project**
- Newest version: GRCH38
	- Corrected mis-assemblies
		- Including medically important regions
	- Added new sequences, improved representation & closed gaps
		- From newer technologies (TGS), donors & bioinformatics methods
	- Improved alternative allele representation
		- From 9 to 216
- Limitations:
	- Not truly representative of human diversity
	- 603 Gaps
		- Especially in repeat-rich regions
	- Mosaic of different individuals
- Advancements:
	- Combining NGS & TGS
	- Resolving Gaps Manually
	- Improving Accuracy through Iterative Process
	- Optical Maps

**Sequencing of Haploid Human Genome**
- Molar Pregnancy

| Step | Description                              |
| :--: | :--------------------------------------- |
|  1   | Sperm combining with Egg without DNA     |
|  2   | Sperm becomes 2n diploid through Mitosis |
|  3   | Abnormal tissue called mole grows        |
|  4   | The homozygous cell line is sequenced    |


#### **Bioinformatic Analyses**
- Alignment or Assembly

**Duties of Bioinformaticians**
- Analytical method development
	- Applies Statistics, Math models & Computer simulations
- Construction & Curation of Computational Tools & Databases
- Data Mining, Interpretation & Analyses

**Alignment to Reference**
- Research, Discovery and Clinical Applications
	- Compare DNA variations & expression frequency between groups
	- Find preferred binding regions of proteins
- Workflow of Variant Calling

|      Step       | Description                       |
| :-------------: | :-------------------------------- |
|  Base Calling   | Sequence nucleotides from signals |
|    Alignment    | Align reads to reference genome   |
| Variant Calling | Identify variations in sample     |
|    Filtering    | Lookup & Filter variants          |
| Casual Variant  | Identify most promising variant   |
- Workflow of Counting Gene Expression

|      Step       | Description                             |
| :-------------: | :-------------------------------------- |
|  Base Calling   | Sequence nucleotides from signals       |
|    Alignment    | Align reads to reference genome         |
| Quality Control |                                         |
|    Counting     | Count reads associated with gene        |
| Identification  | Identify differentially expressed genes |

**De Novo Assembly**
- Characterize and classify novel genomes / variations
	- Classifying & Clustering novel strains
	- Identifying genome distinctions behind phenotype / branched evolution / drug responses

|         Step          | Description                                                   |
| :-------------------: | :------------------------------------------------------------ |
|     Base Calling      | Single / paired end                                           |
|    Genome Assembly    | Use RNA-Seq data & Reference information from related species |
| Draft Genome Assembly |                                                               |

#### **Algorithms**
- Self-contained instructions describing information flow to address specific problems
	- Input to output