Lecture Notes

- Whole Exome Sequencing
- Whole Genome Sequencing

---
#### **Whole Exome Sequencing**
- Sequencing of all exons and splice junctions of the genome
- Finding functional variants of genes through filters:
	- Filter common variants with high frequency in normal individuals
	- Nature, Location & Damaging effects of affected amino acids
	- Occurrence / Function of affected proteins
	- Synonymous / non-synonymous variants
- Pros:
	- Usually lower cost
	- Easier & Quicker data analysis
		- Less noise
- Cons:
	- Requires exon capture → Complicated operation
	- Information loss in other regions → Lower diagnostic yield


**Bioinformatics Analysis Workflow**

| Stage              | Description                                                                                                          |
| ------------------ | -------------------------------------------------------------------------------------------------------------------- |
| Pre-processing     | BWA & SAMtools: Map reads to human genome<br>GATK: Realign inde                                                      |
| Variant Calling    | GATK: Algorithm used for germline mutat                                                                              |
| Variant Filtration | dbSNP135: Database for filtering<br>Parent variants: Filter for de novo mutat                                        |
| Variant Annotation | SnpEff: Identify non-synonymous / frame-shift mutations<br>PROVEAN & SIFT / Polyphen-2: Predict Deleteriousness n-2: |

**Long-Read Sequencing**
- Can be performed complementarily with PacBio Revio & Nanopore PromethION
- More complete reading of genomic information:
	- Detect structural variants, chromosomal breaking points & copy number variants
	- Assemble complete genomes (viral / bacterial / telomere-telomere)
	- Detect epigenetic features (DNA methylation)



#### **Whole Genome Sequencing**
- Sequencing all exons, introns & intergenic regions
	- WES Exon capture is skipped
	- Promoter & Enhancer can be analyzed