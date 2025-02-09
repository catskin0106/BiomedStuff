Lecture Notes

- Transcriptome Profiling Methods
- Data Analysis

---
#### **Transcriptome Profiling Methods**
**Microarray**
- Traditional
- Examination of multiple gene differential expression using hybridization & fluorescent probes
	- Presence of unmixed colors in well → differentially expressed genes

**RNA Sequencing**
- Reverse transcription of RNA into cDNA before high throughput sequencing to reference genome
	- Analysis with a known reference transcriptome: Mapping-based analysis

**Comparison between Microarray and RNA Sequencing**

| Differences          | Microarray        | RNA-Seq      |
| -------------------- | ----------------- | ------------ |
| Expression Level     | Semi-Quantitative | Quantitative |
| Sensitivity          | Low               | High         |
| False Positive Rate  | High              | Low          |
| Alternative Splicing | No                | Yes          |
| Mutation Detection   | No                | Yes          |
| Novel Transcript     | No                | Yes          |
| Non-coding RNA       | No                | Yes          |
| Data Analysis        | Simple            | Complex      |


#### **Data Analysis**
**Obtain raw data from sequencer**
- To be backed up

**Align & Assemble Reads for Quantification**
- Quality control with QV scores
	- Trimming primer & poor quality bases
	- Even distribution of reads after mapping

**Differential Analysis**
- Identify differentially expressed genes / transcripts (DEG / DET)
	- Statistics include p-value to indicate false positives

**Summary & Visualization**
- Heatmaps

**Gene Enrichment / Pathway Analysis**
- Creating gene lists
- Prioritize validation candidates
