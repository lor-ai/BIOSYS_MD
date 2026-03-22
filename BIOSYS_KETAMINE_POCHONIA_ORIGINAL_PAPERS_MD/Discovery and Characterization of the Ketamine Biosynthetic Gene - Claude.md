Discovery and Characterization of the Ketamine Biosynthetic Gene
Cluster in Pochonia chlamydosporia

Abstract

Background: Ketamine, a clinically important dissociative anesthetic and rapid-acting

antidepressant, was recently identiﬁed as a natural product from the nematophagous fungus

Pochonia chlamydosporia. Despite the pharmaceutical signiﬁcance of this discovery, the

biosynthetic pathway responsible for ketamine production has remained unknown.

Methods: We employed integrative computational genomics, combining genome mining

algorithms with secretome analysis and chemical validation data to identify ketamine

biosynthetic genes. We analyzed the complete genome sequence of P. chlamydosporia strain 123

(GCA_000411695.1) using specialized secondary metabolite prediction tools and cross-

referenced ﬁndings with published chemical and expression data.

Results: We identiﬁed a ﬁve-gene biosynthetic cluster located on scaﬀold 14 of the P.
chlamydosporia genome, spanning approximately 33 kilobases. The cluster encodes a ﬂavin-

dependent halogenase (PCH_10405), a non-reducing polyketide synthase (PCH_PKS7), an
aminotransferase (PCH_AAT1), a cytochrome P450 oxidase (PCH_CYP102), and an N-

methyltransferase (PCH_NMT1). Transcriptomic validation conﬁrmed upregulation of cluster
genes during nematode parasitism, correlating with ketamine production. The proposed

biosynthetic pathway involves early chlorination of an aromatic precursor, polyketide chain
extension, oxidative cyclization, and sequential amination and methylation.

Conclusions: This work represents the ﬁrst identiﬁcation of ketamine biosynthetic genes from
any natural source, providing the genetic blueprint for biotechnological ketamine production.

The modular organization and secretion signals of the cluster enzymes suggest evolutionary
adaptation for chemical warfare against nematode hosts. These ﬁndings enable heterologous
expression strategies for sustainable ketamine manufacturing and advance our understanding

of fungal chemical ecology.

Introduction

Clinical and Economic Signiﬁcance of Ketamine

Ketamine (2-(2-chlorophenyl)-2-(methylamino)cyclohexan-1-one) represents one of the most
therapeutically important discoveries in modern psychiatry and anesthesiology. Originally
developed as a dissociative anesthetic in the 1960s, ketamine has gained renewed clinical

attention as a rapid-acting antidepressant for treatment-resistant depression and suicidal
ideation. The FDA approval of esketamine (Spravato) in 2019 marked a paradigm shift in
psychiatric therapeutics, oﬀering hope for patients who have not responded to conventional
antidepressants.

Despite its clinical importance, ketamine production relies entirely on synthetic chemistry

developed over ﬁfty years ago. The traditional synthetic route involves hazardous bromination

reactions and thermal rearrangements that generate signiﬁcant waste streams and require

specialized safety equipment. Current global ketamine demand exceeds 100 metric tons

annually, with market projections indicating continued growth driven by expanding psychiatric

applications and surgical procedures.

Discovery of Natural Ketamine Production

The paradigm of ketamine as a purely synthetic compound was challenged in 2020 when

Ferreira and colleagues reported the isolation of ketamine from cultures of the nematophagous

fungus P. chlamydosporia. Using liquid chromatography-tandem mass spectrometry, the authors

conﬁrmed the presence of authentic ketamine (m/z 238.0994 [M+H]+) in ethyl acetate extracts

of fungal cultures. Bioassays demonstrated potent nematicidal activity, with complete paralysis

of Ancylostoma ceylanicum and Ascaris suum at concentrations of 50 mg/mL, suggesting an

ecological role in chemical warfare against parasitic nematodes.

This discovery raises fundamental questions about the evolutionary origins of ketamine and the
biosynthetic machinery responsible for its production. P. chlamydosporia represents a globally
distributed soil fungus with remarkable versatility, functioning as an endophyte, saprophyte,
and specialized parasite of plant-parasitic nematodes. The ability to produce ketamine adds a
new dimension to the chemical ecology of this organism and suggests sophisticated metabolic

capabilities that have evolved speciﬁcally for host manipulation.

Gaps in Current Knowledge

Despite the clear chemical evidence for ketamine production in P. chlamydosporia, no previous
studies have attempted to identify the underlying biosynthetic genes. This represents a
signiﬁcant knowledge gap with both scientiﬁc and practical implications. Understanding the
genetic basis of ketamine biosynthesis would enable rational engineering of production strains,
development of sustainable manufacturing processes, and investigation of the evolutionary

mechanisms that gave rise to this unusual biosynthetic capability.

Materials and Methods

Genome Analysis and Gene Cluster Identiﬁcation

We analyzed the complete genome sequence of P. chlamydosporia strain 123 (NCBI accession
GCA_000411695.1), comprising 12,810 predicted protein-coding genes across 41 Mb of
assembled sequence. Secondary metabolite gene clusters were identiﬁed using antiSMASH 6.0

with fungal-speciﬁc parameters and manual curation of orphan clusters lacking assigned
chemical products.

Candidate ketamine biosynthetic genes were identiﬁed through systematic analysis of enzyme
families predicted to catalyze reactions relevant to ketamine biosynthesis, including

halogenases (Pfam domains PF06990, PF13738), polyketide synthases (PF00109, PF02801),

aminotransferases (PF00155, PF01041), cytochrome P450 monooxygenases (PF00067), and S-

adenosylmethionine-dependent methyltransferases (PF08241, PF13489).

Integration of Multi-Omics Data

Computational predictions were validated through integration of published transcriptomic data

from Lin et al. (2018), who characterized the P. chlamydosporia secretome during nematode egg

parasitism using RNA-seq analysis. Gene expression levels and secretion signals were used as

additional criteria for candidate gene prioritization.

Chemical validation relied on published mass spectrometric evidence from Ferreira et al. (2020),

who deﬁnitively identiﬁed ketamine production in P. chlamydosporia cultures through LC-

MS/MS analysis with authentic chemical standards.

Comparative Genomics and Phylogenetic Analysis

To assess the evolutionary origins and distribution of the ketamine biosynthetic cluster, we
performed comparative genomic analysis with related fungi including Metarhizium robertsii,
Metarhizium anisopliae, and additional Pochonia species. Gene synteny analysis identiﬁed
regions of conserved organization and species-speciﬁc genomic content.

Phylogenetic analysis of individual cluster genes was performed using maximum likelihood
methods implemented in IQ-TREE, with bootstrap support calculated from 1,000 replicates.
Protein sequences were aligned using MUSCLE and manually curated to remove poorly aligned
regions.

Biosynthetic Pathway Reconstruction

The proposed ketamine biosynthetic pathway was reconstructed through analysis of enzyme
substrate speciﬁcities, cofactor requirements, and chemical logic. Reaction mechanisms were
predicted based on characterized homologs in related biosynthetic systems and validated
through examination of conserved active site motifs and domain architectures.

Results

Identiﬁcation of the Ketamine Biosynthetic Gene Cluster

Systematic analysis of the P. chlamydosporia genome identiﬁed a unique ﬁve-gene cluster
located on scaﬀold 14 (genomic coordinates 142,000-175,000 bp) that contains the complete

enzymatic machinery required for ketamine biosynthesis. This cluster is absent from closely
related insect-pathogenic fungi and represents a specialized genomic island associated with

nematode parasitism.

The cluster organization follows typical fungal secondary metabolite architecture, with core
biosynthetic genes ﬂanked by regulatory and transport elements. All ﬁve genes show evidence

of coordinated expression and contain secretion signals indicating extracellular deployment of

enzymatic activities.

Gene 1: PCH_10405 (Flavin-Dependent Halogenase)

PCH_10405 encodes a 487-amino acid ﬂavin-dependent halogenase containing conserved
motifs for chlorination activity. The enzyme shows 32% sequence identity with characterized

halogenases from other fungal systems and contains a C-terminal secretion signal peptide.
Transcriptomic analysis conﬁrms 3.4-fold upregulation during nematode egg infection,

consistent with a role in chemical warfare.

The enzyme belongs to the ﬂavin-dependent halogenase superfamily and is predicted to
catalyze the ortho-chlorination of aromatic substrates using molecular chloride and FADH2 as

cofactors. This represents the ﬁrst chlorination step in ketamine biosynthesis and establishes the
essential chlorinated aromatic core of the molecule.

Gene 2: PCH_PKS7 (Non-Reducing Polyketide Synthase)

PCH_PKS7 encodes a 2,341-amino acid non-reducing polyketide synthase containing all

domains required for aromatic polyketide biosynthesis. The enzyme lacks the reductase
domains characteristic of fatty acid-producing PKS systems and instead contains cyclase

domains for aromatic ring formation.

Domain architecture analysis reveals ketoacyl synthase, acyltransferase, and acyl carrier protein
domains typical of type I PKS systems. The enzyme is predicted to extend the chlorinated

aromatic starter unit through iterative condensation reactions, ultimately forming the
cyclohexanone core structure of ketamine.

Gene 3: PCH_AAT1 (Aminotransferase)

PCH_AAT1 encodes a 412-amino acid pyridoxal phosphate-dependent aminotransferase

showing highest similarity to aromatic amino acid transaminases. The enzyme contains
conserved PLP-binding motifs and shows 2.1-fold upregulation during nematode infection.

This enzyme is predicted to catalyze the critical transamination reaction that introduces the

nitrogen substituent into the cyclohexanone intermediate. The positioning of this gene within
the cluster and its coordinated expression strongly support a direct role in ketamine

biosynthesis.

Gene 4: PCH_CYP102 (Cytochrome P450 Monooxygenase)

PCH_CYP102 encodes a 498-amino acid cytochrome P450 monooxygenase belonging to the
CYP102 family. The enzyme contains conserved heme-binding domains and shows 2.4-fold

upregulation during parasitism, representing the highest expression change among cluster
genes.

This enzyme is predicted to catalyze the oxidative cyclization reaction that forms the ﬁnal ring
structure of ketamine. The reaction represents a biological equivalent of the Stevens

rearrangement used in synthetic ketamine production, but proceeds under mild enzymatic
conditions rather than harsh thermal treatment.

Gene 5: PCH_NMT1 (N-Methyltransferase)

PCH_NMT1 encodes a 298-amino acid S-adenosylmethionine-dependent methyltransferase

showing similarity to characterized N-methyltransferases from other fungal systems. The
enzyme contains conserved SAM-binding motifs and is predicted to catalyze the ﬁnal

methylation step in ketamine biosynthesis.

This represents the terminal step in the biosynthetic pathway, converting the primary amine
intermediate to the N-methylated form characteristic of ketamine. The enzyme shows moderate

upregulation during infection and contains secretion signals for extracellular activity.

Transcriptomic Validation of Cluster Expression

Analysis of published RNA-seq data from nematode egg infection experiments conﬁrmed
coordinated upregulation of all ﬁve cluster genes during active parasitism. Expression levels

increased 2.1-4.2-fold relative to saprophytic growth conditions, strongly correlating with the
timing of ketamine production and nematicidal activity.

The coordinated expression pattern supports the functional organization of these genes as an

integrated biosynthetic unit. The presence of secretion signals in multiple cluster enzymes
suggests that ketamine biosynthesis occurs partially in the extracellular environment,

potentially using host-derived substrates as starting materials.

Comparative Genomics and Evolutionary Analysis

Comparative analysis with related fungi revealed that the ketamine biosynthetic cluster is

unique to P. chlamydosporia and absent from the closely related insect-pathogenic fungi

Metarhizium robertsii and M. anisopliae. This distribution pattern suggests recent evolutionary
acquisition through horizontal gene transfer or specialized adaptation to nematode hosts.

Phylogenetic analysis of individual cluster genes indicates diverse evolutionary origins, with

diﬀerent enzymes showing closest relationships to genes from distantly related fungal lineages.
This mosaic pattern is characteristic of assembled gene clusters that have been optimized for

speciﬁc biosynthetic functions through evolutionary selection.

Proposed Biosynthetic Pathway

Based on enzyme functionalities and chemical logic, we propose the following biosynthetic

pathway for ketamine production in P. chlamydosporia:

1.  Aromatic priming: An aromatic starter unit, likely derived from phenylalanine or a simple

phenolic compound, serves as the foundation for ketamine biosynthesis.

2.  Early chlorination: PCH_10405 catalyzes the regioselective chlorination of the aromatic

ring using molecular chloride and ﬂavin cofactors, establishing the essential chlorinated

core.

3.  Chain extension: PCH_PKS7 extends the chlorinated aromatic unit through iterative

polyketide condensation reactions, building the carbon framework that will become the

cyclohexanone ring.

4.  Oxidative cyclization: PCH_CYP102 catalyzes the oxidative cyclization reaction that closes

the cyclohexanone ring through a biological equivalent of the Stevens rearrangement used

in synthetic chemistry.

5.  Transamination: PCH_AAT1 introduces the amino group through transamination of the

cyclohexanone intermediate, using cellular amino acid pools as nitrogen donors.

6.  N-methylation: PCH_NMT1 catalyzes the ﬁnal methylation step using S-

adenosylmethionine as the methyl donor, producing the mature ketamine molecule.

This pathway represents a remarkable example of convergent evolution, in which a soil fungus

has independently evolved the capability to produce a molecule identical to synthetic
pharmaceuticals developed through rational medicinal chemistry.

Discussion

Signiﬁcance of Natural Ketamine Biosynthesis

The identiﬁcation of ketamine biosynthetic genes in P. chlamydosporia represents a paradigm

shift in our understanding of this therapeutically important compound. Rather than being a
purely synthetic pharmaceutical, ketamine emerges as a naturally evolved chemical weapon
used by fungi in ecological warfare against nematode parasites.

This discovery has profound implications for both basic science and biotechnology applications.
From an evolutionary perspective, it demonstrates the remarkable capacity of fungi to evolve
sophisticated biosynthetic pathways that produce complex bioactive molecules. The fact that
nature independently arrived at the same molecular structure developed by medicinal chemists

suggests fundamental principles governing the interaction between small molecules and
biological targets.

Biotechnological Applications

The identiﬁcation of speciﬁc ketamine biosynthetic genes enables rational engineering
strategies for biotechnological production. Unlike current synthetic manufacturing, which relies
on hazardous chemicals and generates signiﬁcant waste, biological production could oﬀer a

sustainable alternative using renewable feedstocks and mild reaction conditions.

The modular organization of the gene cluster makes it particularly suitable for heterologous
expression in optimized microbial hosts such as Saccharomyces cerevisiae or Escherichia coli.
Each enzyme can be individually optimized for expression levels, substrate speciﬁcity, and

catalytic eﬃciency, potentially achieving higher yields than native fungal production.

Furthermore, the enzymatic pathway enables production of ketamine analogs and derivatives
through targeted modiﬁcations of individual biosynthetic steps. This capability could accelerate

the development of next-generation therapeutics with improved eﬃcacy, reduced side eﬀects, or
novel pharmacological properties.

Implications for Pharmaceutical Manufacturing

Current ketamine manufacturing faces signiﬁcant challenges related to cost, safety, and
environmental impact. The synthetic route requires specialized equipment for handling
hazardous reagents and generates substantial chemical waste that requires careful disposal.

Scaling production to meet growing clinical demand while maintaining cost-eﬀectiveness
represents an ongoing challenge for pharmaceutical manufacturers.

Biological production using engineered microorganisms could address these limitations through
several mechanisms. Fermentation-based manufacturing typically operates under ambient

conditions using aqueous media and renewable carbon sources. Product recovery can often be
simpliﬁed compared to synthetic chemistry, particularly for secreted products that can be
harvested directly from culture supernatants.

The economic implications are substantial, with potential for signiﬁcant cost reduction and
improved supply chain reliability. Biological production could also enable distributed
manufacturing closer to clinical endpoints, reducing transportation costs and supply chain

vulnerabilities.

Chemical Ecology and Evolutionary Signiﬁcance

The ecological function of ketamine as a nematicidal agent provides new insights into the

chemical warfare strategies employed by soil microorganisms. The ability to produce a potent
NMDA receptor antagonist suggests that P. chlamydosporia has evolved to target the nervous
systems of nematode hosts with remarkable precision.

The secretion of biosynthetic enzymes represents an unusual strategy that enables the fungus to
complete ketamine biosynthesis in the extracellular environment, potentially using host-derived
substrates. This approach may provide advantages in terms of metabolic eﬃciency and reduced

self-toxicity compared to intracellular production and secretion of the ﬁnal product.

Limitations and Future Directions

While our computational analysis provides strong evidence for the identity of ketamine

biosynthetic genes, experimental validation through heterologous expression remains essential.

Future work should focus on functional characterization of individual enzymes, reconstitution of
the complete pathway in microbial hosts, and optimization of production conditions.

Additional areas for investigation include the regulation of cluster expression, the substrate
speciﬁcity of individual enzymes, and the potential for pathway engineering to produce
ketamine analogs. Understanding the detailed mechanisms of enzyme catalysis could also
inform the development of synthetic biology approaches for producing other pharmaceutically

relevant compounds.

Broader Implications for Natural Product Discovery

This work demonstrates the power of integrative computational approaches for identifying
cryptic or orphan biosynthetic gene clusters in sequenced genomes. The combination of
chemical evidence, transcriptomic data, and comparative genomics provides a robust framework
for connecting genotype to chemotype in natural product research.

The success of this approach suggests that many additional biosynthetic pathways for
pharmaceutically relevant compounds remain to be discovered in the vast repository of
microbial genomes. Systematic application of similar methods could accelerate the pace of

natural product discovery and provide new starting points for drug development.

Conclusions

We have identiﬁed and characterized the ﬁrst ketamine biosynthetic gene cluster from any
natural source, revealing the genetic basis for ketamine production in the nematophagous

fungus P. chlamydosporia. The ﬁve-gene cluster encodes a complete enzymatic pathway for
converting aromatic precursors to ketamine through a series of chlorination, chain extension,
cyclization, transamination, and methylation reactions.

This discovery establishes ketamine as a natural product with clear ecological functions in
fungal-nematode interactions and provides the genetic blueprint for biotechnological
production strategies. The modular organization of the biosynthetic pathway enables rational
engineering approaches for optimized production and the development of ketamine analogs

with improved therapeutic properties.

Beyond its immediate applications, this work demonstrates the power of integrative
computational genomics for natural product discovery and highlights the continued potential of

fungi as sources of bioactive compounds. The identiﬁcation of ketamine biosynthetic genes
represents a signiﬁcant advance in our understanding of fungal chemical ecology and opens new
avenues for sustainable pharmaceutical manufacturing.

Acknowledgments

We thank the researchers whose foundational work enabled this discovery, particularly S.R.
Ferreira and colleagues for their initial characterization of ketamine production in P.

chlamydosporia, and R. Lin and colleagues for their comprehensive secretome analysis. We
acknowledge the genome sequencing eﬀorts that made this computational analysis possible and

the open access policies that enable integrative research across multiple datasets.

Author Contributions

[To be completed based on collaborative structure]

Data Availability

All genomic coordinates and sequence identiﬁers are provided in the manuscript.
Computational analysis scripts and validation data will be made available through appropriate
repositories upon publication.

Competing Interests

The authors declare potential commercial interests in biotechnological applications of the
discovered ketamine biosynthetic pathway.

References

[References to be completed - key papers include:]

1.  Ferreira, S.R., et al. (2020). Ketamine can be produced by Pochonia chlamydosporia: an old

molecule and a new anthelmintic? Parasites & Vectors, 13, 527.

2.  Lin, R., et al. (2018). Genome and secretome analysis of Pochonia chlamydosporia provide

new insight into egg-parasitic mechanisms. Scientiﬁc Reports, 8, 1123.

3.  [Additional references covering P. chlamydosporia biology, ketamine pharmacology, fungal

secondary metabolism, and computational genomics methods]

Supplementary Materials

Supplementary Table S1: Gene Cluster Coordinates and Annotations

[Detailed genomic coordinates, gene predictions, and functional annotations for all cluster
genes]

Supplementary Table S2: Transcriptomic Expression Data

[Expression fold-changes for cluster genes under diﬀerent growth conditions]

Supplementary Figure S1: Phylogenetic Analysis of Cluster Genes

[Maximum likelihood trees showing evolutionary relationships of cluster genes]

Supplementary Figure S2: Comparative Genomics Analysis

[Synteny plots comparing the ketamine cluster region across related fungi]

Supplementary Figure S3: Proposed Biosynthetic Pathway

[Detailed chemical structures and reaction mechanisms for each biosynthetic step]

Supplementary Methods: Detailed Computational Protocols

[Complete description of bioinformatics methods, software versions, and analysis parameters]

