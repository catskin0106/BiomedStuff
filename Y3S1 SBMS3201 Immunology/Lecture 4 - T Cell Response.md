Lecture Notes

**Lecture Coverage:**
- T Cell Development
- T Cell Activation, Differentiation & Memory
- Experimental Methods

---
#### **T Cell Development**
- Double-Negative (DN) Thymocyte -> Double-Positive (DP) Thymocyte -> Thymic Selection -> Lineage Commitment

**DN Thymocyte Phases**
- Takes place at the Thymus Lobe
- 4 Stages differentiated by <abbr Title="Adhesion molecule">CD44</abbr>, <abbr Title="IL-2Receptor α chain">CD25</abbr> & <abbr Title="CD117, Stem cell growth factor receptor">c-Kit</abbr> expression

|   Stage    |             <             | Description                                                                                                                                                              |
| :--------: | :-----------------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|   DN1-2    |                           | Migration to Thymus                                                                                                                                                      |
| <br>DN2-3  | <br>TCR Linage Commitment | Rearrangement of TCR βγδ chains<br>- Commit to:<br>    - αβ (More likely; Higher diversity)<br>    - γδ (Less likely; Lower diversity)                                   |
|   DN3-4    |        β-Selection        | 1. pre-TCR selection<br>2. Only DN3 with a <abbr Title="Can form pre-TCR with fixed pre-T α chain & CD3 complex">Productively Arranged β Chain</abbr> can proceed to DN4 |
| <br>DN4-DP |                           | 1. Proliferation<br>2. α-chain locus rearrangement<br>3. β-chain locus allelic exclusion                                                                                 |

**Thymic Selection**
- To select for T Cells with correct properties:
	- MHC Restriction: Can only interact with antigen presented by self-MHC
	- Self-tolerance: Can't trigger immunoresponse against self-MHC / self-peptides

|         Stage          | Description                                                                                                                                                                |
| :--------------------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <br>Positive Selection | Select for cells that can only interact with antigen presented by self-MHC<br>- Mediated by Cortical Thymic Epithelial Cells<br>- Unqualified cells (98%) die by apoptosis |
| <br>Negative Selection | Select for cells that are not autoreactive<br>- Mediated by Medullary Thymic Epithelial cells<br>- Autoreactive cells die by apoptosis                                     |

**T-Cell Lineage Commitment**
- DP Thymocyte decides whether to join CD8+ or CD4+ cell lineage
	- The lineage gene will be expressed while the other will be silenced


#### **T Cell Activation, Differentiation & Memory**

**T Cell Activation**
- 3-Signal Model Activation: Co-activated by 3 signals
	- Signal 1 - MHC(&Epitope Complex)-TCR Signal
		- <abbr Title="Human Leukocyte Antigen">HLA</abbr>-Epitope Complex-TCR interaction in humans
		- Results in T cells specificity towards this epitope
	- Signal 2 - Co-stimulatory Signal
		- CD80/86 of APC Binds to CD28 of T-Cell
		- Also required for IL-2 & IL-2R upregulation
	- Signal 3 - Cytokine Signal
		- IL-2: Enhances T-Cell proliferation
		- Polarizing Cytokines: Determines T-Cell Lineage Commitment

**T Cell Anergy**
- Temporary functionally inactivated T-Cells
	- Maintain self-tolerance
	- Minimize tissue damages in immunoresponses
- Induced by inhibitory signals
	- Non-APC MHC-TCR Formation: Blocks HLA-Epitope Complex-TCR
	- CD80/86 of APC binds to <abbr Title="Cytotoxic Lymphocyte Ag 4">CTLA-4</abbr> on T-Cell: Blocks CD28
		- CTLA-4 Expressed on T-reg cells
	- PD-L1/2 of APC binds to PD-1 on T-Cell

**T Cell Differentiation (Linage Commitment)**
- T Cells of each Sub-population Characterized by:
	- Foreign Polarizing Cytokines: Initiates differentiation
	- Master Transcriptional Factor: Regulates helper-cell-specific gene production
	- Effector cytokines: Secreted to regulate immunoresponse

- CD4+ Cell Subpopulations

| Subtype                                    | Characteristics                                                  | Function                                                                                                                                                                     |
| ------------------------------------------ | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tfh                                        |                                                                  | Helps B-Cell activation & maturation<br>Strengthen & Lengthen antibody effect                                                                                                |
| Th1                                        |                                                                  | CD8+ T cell activation & <abbr Title="Cytolytic Function & Memory Formation">functionalization</abbr><br>- Through CD40L-CD40 + IL-2 interactions                            |
| <abbr Title="Regulator T cell">Treg</abbr> | CD4 & CD25 Co-expression<br>Master transcriptional Factor: FoxP3 | <abbr Title="Peripheral tolernace & Prevent autoimmunity">Immunosuppression</abbr><br>- Inhibitory cytokines / DC targeting<br>- Direct cytolysis<br>- Metabolism disruption |

- CD8+ Cells Mechanism

| Stage                                                                    | Event                                                                                       | <                                                                                                                                                                   |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <abbr Title="Cancer/Virus-infected cells">Target</abbr>-CD8+ Conjugation | CD8+ Cytoplasmic rearrangement -><br>Immunological Synapse between Target & CD8+            | <                                                                                                                                                                   |
| CD8+ Granule Exocytosis                                                  | Cytotoxic Granules degranulate in synapse -><br>Absorbed by Target                          | <                                                                                                                                                                   |
| Target Cell Apoptosis<br>                                                | Fas Pathway:<br>1. FasL on CD8+ binds to Fas on Target<br>2. Activates FADD & Caspase 8<br> | Perforin-Granzyme Pathway:<br>1. CD8+ Releases Granzyme B & Perforin<br>2. Perforin forms pore on Target<br>3. Granzyme B endocytosis -><br>Activates Caspase 3 & 9 |
| CD8+ Recycling                                                           | CD8+ Dissociates from Target & Recycled                                                     | <                                                                                                                                                                   |
- Shares Apoptosis mechanism with NK(-T) Cells
	- But recognition pathways are unique



**T Cell Memory**
- Recognition of same antigen in high speed & specificity
	- Provides long-term protection in high speed & strength
- Longer lifespan
- Exhaustion upon chronic antigen exposure
	- Characterized by high <abbr Title="CTLA-4, PD-1">co-inhibitory receptors</abbr> expression
		- aka Immune Checkpoints in cancer immunotherapy
		- <abbr Title="Monoclonal Antibodies">MAbs</abbr> against those checkpoints are blocked -> inhibit activation in cancer therapies


#### **Experimental Methods**
**Flow Cytometry**

**ELISPOT assays**
- Measures number of cytokine-secreting cells in a population
- Positive result: colored precipitate at location occupied by cell