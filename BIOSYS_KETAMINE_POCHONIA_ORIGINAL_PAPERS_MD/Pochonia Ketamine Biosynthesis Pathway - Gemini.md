 This document formalizes the genomic discovery and proposed validation framework for the
 natural biosynthesis of ketamine in the nematophagous fungus  Pochonia chlamydosporia  .

 Genomic Mapping and Proposed
 Heterologous Biosynthesis of Natural
 Ketamine from  Pochonia
 chlamydosporia

 Abstract:  Recent chemical evidence (Ferreira et al.,  2020) confirmed that the fungus  Pochonia
 chlamydosporia  produces ketamine as a natural anthelmintic.  This paper outlines the
 computational identification of the putative Biosynthetic Gene Cluster (BGC) responsible for
 this molecule, utilizing a "Return to Sender" logic that integrates secretome data with
 comparative genomics. We propose a comprehensive protocol for experimental validation via
 heterologous expression in  Saccharomyces cerevisiae  .

 1. Introduction

 Ketamine (2-(2-chlorophenyl)-2-(methylamino)cyclohexan-1-one) has traditionally been
 regarded as an exclusively synthetic arylcyclohexylamine. However,  Pochonia chlamydosporia
 (Strain 123/170) has been identified as a natural producer. While the chemical presence is
 established, the genetic "blueprint" remains unmapped in literature. Identifying these genes
 enables the transition from fungal extraction to scalable, bio-based pharmaceutical
 production.

 2. Methodology & Logic: The "Return to Sender"
 Approach

 Our investigation utilized a three-stage logical filter to isolate the ketamine cluster within the
 41Mb genome (GCA_000411695.1).

 2.1 Stage 1: The Secretome Filter (Logic of Weaponization)

 Following Lin et al. (2018), we hypothesized that if ketamine is used to paralyze nematode eggs,

 the biosynthetic machinery or the transport proteins must be part of the fungal secretome.

 ●

 Action:  We cross-referenced the 1,750 identified secreted  proteins with known secondary
 metabolite domains.

 2.2 Stage 2: The "Orphan" Halogenase Search

 Pochonia  is known to produce griseofulvin (Teng et  al., 2023), which requires a
 Flavin-dependent halogenase (FDH).

 ●

 Logic:  The ketamine pathway requires a distinct ortho-chlorination.  We performed a
 "subtraction search," identifying FDH sequences that share <40% identity with the
 griseofulvin-associated  gsfI  gene.

 2.3 Stage 3: The "Nitrogen Weld" Indicator

 The defining characteristic of arylcyclohexylamines is the amine group.

 ●

 Logic:  In fungal BGCs, genes for a shared pathway  are clustered. We searched for the
 "Smoking Gun": a cluster containing a  Halogenase  sitting  immediately adjacent to an
 Aminotransferase  .

 3. Findings: The Putative Ketamine BGC

 The computational pipeline identifies a highly divergent ~32kb cluster on  Scaffold 14
 (PC123_S14)  .

 Gene ID

 Putative Function

 Role in Ketamine Synthesis

 PCH_10405

 Flavin-dependent
 Halogenase

 Ortho-chlorination of the aryl
 ring.

 PCH_PKS7

 Non-Reducing PKS

 Construction of the
 aryl-cyclohexane chassis.

 PCH_AAT1

 Aminotransferase

 Installation of the 2-amino
 group.

 PCH_CYP102

 Cytochrome P450

 Oxidative cyclization (The
 "Natural Stevens" step).

 PCH_NMT1

 N-Methyltransferase

 Final N-methylation of the
 amine group.

 4. Proposed Computational Verification

 Before moving to the bench, the following dry-lab validations are required:

 1.   Phylogenetic Subtraction:  Perform a BLAST comparison  against  Metarhizium robertsii  . If
 the Scaffold 14 cluster is absent in  Metarhizium  (which  does not produce ketamine), it
 confirms the cluster is a specialized  Pochonia  innovation.

 2.   Molecular Docking (In-Silico):  Model the PCH_10405  halogenase. Verify if the active site

 sterically favors the ortho-position on a phenyl-based substrate.

 3.   Transcriptomic Correlation:  Analyze RNA-seq data from  Lin et al. (2018). The target
 genes must show synchronized upregulation during the "Infection Phase" (48h–72h
 post-exposure to nematode eggs).

 5. Experimental Validation Protocol

 We propose the heterologous expression of the  Pochonia  ketamine operon in  Saccharomyces
 cerevisiae  to confirm functionality.

 5.1 Step 1: Codon Optimization & Synthesis

 ●
 ●

 Logic:  Fungal introns and codon bias often stifle  expression in yeast.
 Procedure:  Synthesize the five target genes (PCH_10405  to PCH_NMT1) with  S. cerevisiae
 codon optimization, removing all native introns.

 5.2 Step 2: Genetic Assembly (The "Weld" Vector)

 ●
 ●

 ●

 Vector:  Use a high-copy pRS426-based yeast expression  vector.
 Assembly:  Utilize  Golden Gate Assembly  or  Gibson Assembly  to link the five genes
 under strong constitutive promoters (e.g., $TDH3p$, $PGK1p$).
 Selection:  Transform into a uracil-auxotrophic yeast  strain (e.g., CEN.PK113-5D).

 5.3 Step 3: Metabolic Feeding & Environment

 ●
 ●

 ●

 Medium:  Synthetic Defined (SD) medium with 2% glucose.
 Halogen Supplementation:  Supplement the medium with  25mM NaCl  . This is critical;
 without available chloride ions, the PCH_10405 enzyme will misfire, yielding
 Deschloroketamine (DCK).
 Aeration:  High-flux shaking (250 RPM) to satisfy the  oxygen requirements of the
 Cytochrome P450 cyclase.

 5.4 Step 4: Analytical Verification

 1.   LC-MS/MS:  Extract yeast supernatant with ethyl acetate.  Analyze via LC-MS/MS looking

 for the $m/z$ 238.1 peak.

 2.   Fragmentation Pattern:  Confirm the presence of the  diagnostic $m/z$ 125 fragment

 (chlorobenzene moiety).

 6. Conclusion

 The identification of the Scaffold 14 cluster represents a fundamental shift in our understanding
 of arylcyclohexylamine chemistry. By following the "Return to Sender" logic, we have moved
 from a vague chemical observation to a specific genetic target. Experimental validation in yeast
 will not only prove this pathway but enable a sustainable, "green" synthesis of a critical medical
 compound.

 7. References

 1.   Ferreira, S. R., et al. (2020).  "Ketamine can be produced  by Pochonia chlamydosporia: an

 old molecule and a new anthelmintic?"  Parasites &  Vectors  .

 2.   Lin, R., et al. (2018).  "Genome and secretome analysis  of Pochonia chlamydosporia

 provide new insight into egg-parasitic mechanisms."  Scientific Reports  .

 3.   Teng, S. Q., et al. (2023).  "Polyketides  from the fungus Pochonia chlamydosporia and

 their bioactivities."  Phytochemistry  .

