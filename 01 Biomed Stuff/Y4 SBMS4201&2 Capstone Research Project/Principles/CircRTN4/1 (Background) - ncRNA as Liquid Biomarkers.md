**Subtopics:**
- Types of ncRNAs in Cancer
- circRTN4

---
#### **Types of ncRNAs in Cancer**
- ncRNA accounts for 97% of genome transcribed into RNA
	- Can be oncogenes / tumor suppressors

| ncRNA   | Structural Characteristics                                          | Mechanism                                                                                                                                                                                                                                                                                                                  | Example                                                                                                                                          |
| ------- | ------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| miRNA   | < 22 bases                                                          | Bind to complementary mRNA as part of <abbr Title="RNA-Induced Silencing Complex">RISC</abbr><br>→ mRNA degradation by RISC → Gene Downregulation<br>**Analogy**: <abbr Title="RISC">Assassin</abbr> obtains <abbr Title="miRNA">address label</abbr> → Kill <abbr Title="complementary mRNA">people</abbr> at the address | <font color="red">miR-126</font>: p53 Downregulation<br>→ ↓ Tumor Suppression                                                                    |
| piRNA   | 24-30 bases                                                         | Guides PIWI proteins to target <abbr Title="DNA Segments that can move within the genome">Transposons</abbr><br>→ Form <abbr Title="piRNA-Induced Silencing Complex">piRISCs</abbr> to silence Transposons                                                                                                                 | <font color="red">piRNA-823</font>: Deactivates <abbr Title="Apoptosis-Associated Transcription Factor">HSF1</abbr><br>→ ↓ Cancer Cell Apoptosis |
| lncRNA  | > 200 bases; linear                                                 | Many (e.g. mRNA interaction & Histone modification)<br>→ Gene Downregulation                                                                                                                                                                                                                                               | <abbr Title="HOXA Transcript At Te Distal Tip"><font color="red">HOTTIP</font></abbr>                                                            |
| circRNA | > 200 bases; <abbr Title="3' end joins with 5' end">circular</abbr> | **miRNA Sponge**: Bind to complementary miRNA<br>→ Prevent mRNA degradation by miRNA                                                                                                                                                                                                                                       | <font color="red">circRTN4</font>                                                                                                                |

**HOTTIP lncRNA in Pancreatic Carcinogenesis**

```mermaid
flowchart LR
	A["↑ HOTTIP"]--<font size="2">↑ WDR5/MLL Complex <br> Binding</font>-->C["↑ H3K4me3 at <br>HOXA13 Promoter"]
	C--<font size="2">Pol II Binding to <br>HOXA13 Promoter</font>-->D["↑ HOXA13"]
	D-->E["↑ IGBFP-3<br><font size="2">(<abbr Title="Epithelial-Mesenchymal Transition">EMT</abbr>)</font>"]
	D-->F["↑ BMP73<br><font size="2">(Proliferation & Invasion)</font>"]
```

#### **circRTN4**
- Upregulated in <abbr Title="Pancreatic Ductal Adenocarcinoma">PDAC</abbr> and other cancers

**Formation of circRTN4**
- Back-splicing (Non-canonical Splicing) of Chr2 RTN4 Exon 4 & 5
	- Canonical Splicing: 3' end of Upstream Exon joins 5' end of Downstream Exon
	- Non-canonical Splicing: 3' end of Downstream Exon joins 5' end of Upstream Exon

**Mechanisms of circRTN4**

```mermaid
flowchart LR
A["↑ circRTN4"]-->B["miR-497-5p Sponging"]
A-->D
subgraph box1 [<b>circRNA-miRNA-lncRNA Pathway]
		direction LR
		B:::Start--<font size="2">↓ HOTTIP degradation by miRNA</font>-->C["↑ HOTTIP"]
    end
subgraph box2 [<b>RAB11FIP1 Stabilization]
		direction LR
		D["Blockage of RAB11FIP1 Ubiquitination Site"]:::Start-->E["↑ <abbr Title="Slug, Snai1, Twist & Zeb1">EMT Markers</abbr>"]
		D-->F["↑ <abbr Title="Promotes Mobility & Invasion in EMT">N-Cadherin</abbr>"]
    end
```
- Ubiquitin: Protein that facilitates protein degradation