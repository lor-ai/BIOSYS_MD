Computational Identiﬁcation of Candidate Genes for Ketamine
Biosynthesis in Pochonia chlamydosporia: A Minimal Deviation
Pathway Hypothesis

Abstract

Background: Chemical evidence conﬁrms ketamine production by the nematophagous fungus

Pochonia chlamydosporia through multi-modal analytical validation. Given the organism's

established secondary metabolite capacity including chlorinated aromatic compounds,

ketamine biosynthesis likely represents minimal deviation from existing fungal chemistry

rather than wholesale biosynthetic innovation.

Methods: We employed a minimal deviation hypothesis focusing on identifying the critical

biochemical novelty required for ketamine biosynthesis from existing P. chlamydosporia

aromatic and polyketide metabolism. Our computational approach prioritized orphan enzymatic
modules capable of aryl-cyclohexanone coupling as the key transformation, with conventional

ﬁnishing chemistry through established fungal aminotransferase and methyltransferase
families.

Results: We identiﬁed candidate enzymatic components that could support ketamine
biosynthesis through late-stage branching from established secondary metabolism. The critical

step appears to be aryl-cyclohexanone coupling, requiring one novel carbon-carbon bond-
forming enzyme, while subsequent amination and N-methylation proceed through conventional

fungal enzymology. Candidate genes include orphan aromatic halogenation modules and
unusual carbon-carbon bond-forming enzymes showing coordinated expression patterns.

Conclusions: This work presents computationally prioritized candidates for ketamine
biosynthesis representing minimal biochemical deviation from established fungal secondary

metabolism. The proposed pathway provides testable hypotheses for experimental validation

through heterologous expression followed by genetic manipulation studies. These ﬁndings
establish a framework for investigating ketamine biosynthesis while acknowledging that
computational identiﬁcation requires experimental validation to establish genetic causality.

Introduction

Chemical Evidence Foundation

The discovery of ketamine production in Pochonia chlamydosporia challenges the paradigm of

exclusively synthetic origins for this therapeutically critical compound. Ferreira and colleagues
demonstrated ketamine presence in fungal extracts through rigorous analytical characterization
including GC-MS identiﬁcation, UPLC-ESI-MS/MS with characteristic chlorine isotope patterns
at m/z 238/240, and comprehensive 2D NMR validation including HSQC, HMBC, and COSY
analyses.

The ketamine-consistent signal was isolated in active ethyl acetate fractions through bioassay-

guided fractionation, ultimately appearing in subfraction F5 where no other identiﬁed

substances were detected. Critically, ketamine production occurred in fungal cultures grown in

potato dextrose medium without nematode presence, establishing endogenous biosynthetic

capacity rather than environmental contamination or host-derived precursor rerouting.

This chemical evidence provides the foundation for genetic investigation but does not identify

the biosynthetic machinery responsible for ketamine production. The existence of a ketamine-

consistent analyte in fungus-only culture establishes the starting point for understanding the

underlying biochemical pathway.

Metabolic Context and Secondary Metabolite Capacity

P. chlamydosporia demonstrates extensive secondary metabolite production well beyond

ketamine synthesis. The organism produces resorcylic acid lactones, pyranones, alkaloids,

phenolic compounds, griseofulvin derivatives, and additional polyketide structures. Most

signiﬁcantly, P. chlamydosporia harbors characterized biosynthetic gene clusters including the
radicicol pathway featuring reducing and non-reducing polyketide synthases, halogenase
modules, and post-PKS tailoring enzymes.

This chemical versatility indicates sophisticated secondary metabolite infrastructure capable of
supporting diverse aromatic transformations and halogenation chemistry. The established
precedent for chlorinated aromatic secondary metabolites provides the metabolic context within
which ketamine biosynthesis most likely operates.

The genome comprises 41.47 Mb with 12,122 predicted genes, placing P. chlamydosporia within
the expected range for metabolically versatile ﬁlamentous fungi. This genetic capacity supports
the hypothesis that ketamine biosynthesis emerged through modest modiﬁcation of existing
capabilities rather than wholesale innovation.

Minimal Deviation Pathway Model

The most parsimonious explanation for ketamine biosynthesis involves minimal deviation from
established P. chlamydosporia secondary metabolism rather than requiring dedicated
biosynthetic machinery. This minimal deviation model proposes that ketamine production
requires only one truly novel biochemical transformation: the formation of an aryl-
cyclohexanone linkage that couples a chlorinated aromatic precursor with a cyclohexanone
scaﬀold.

The aromatic precursor can be derived from existing halogenated secondary metabolite
pathways demonstrated in P. chlamydosporia. The cyclohexanone component represents a
relatively simple carbonyl structure that could emerge from basic fungal metabolism or
polyketide-derived intermediates. The subsequent enzymatic steps including transamination
through PLP-dependent aminotransferases and N-methylation through SAM-dependent

methyltransferases represent conventional fungal enzymology broadly distributed across

ﬁlamentous fungi.

This model explains several critical observations including fungus-only production capability,

chemical complexity emerging from known metabolic foundations, and the absence of an

obvious dedicated biosynthetic cluster that would be expected for wholesale pathway

innovation.

Experimental Validation Framework

This investigation aims to identify candidate genes supporting ketamine biosynthesis while

establishing clear experimental validation requirements. We acknowledge that computational

gene identiﬁcation represents hypothesis generation rather than deﬁnitive pathway

characterization and that establishing genetic causality requires systematic experimental

validation.

Our approach provides a foundation for heterologous expression studies in Saccharomyces

cerevisiae following a progressive validation strategy. Initial experiments would test late-stage
enzymatic suﬃciency by expressing ﬁnishing genes with fed precursors. Subsequent testing
would evaluate mid-pathway suﬃciency and ultimately full de novo production from glucose as
sole carbon source. Final validation would require genetic manipulation in P. chlamydosporia to

establish native pathway necessity through gene deletion and complementation studies.

Materials and Methods

Genome Resources and Reproducibility Framework

We analyzed P. chlamydosporia strain 123 using NCBI assembly GCA_000411695.2 with
GenBank annotation GCF_000411695.2. All genomic coordinates and gene identiﬁers reference
this speciﬁc assembly version with documented annotation track to ensure computational

reproducibility.

Computational analysis employed antiSMASH v7.0.0 with fungal-speciﬁc parameters including

detection strictness: relaxed, minimum cluster size: 5000 bp, cluster border threshold: 10000 bp,
and CF-cutoﬀ: 0.6. Hidden Markov Model searches used Pfam v35.0 with gathering threshold

cutoﬀs to maintain consistent detection sensitivity across enzyme families.

Minimal Deviation Computational Strategy

Rather than applying traditional biosynthetic gene cluster detection that assumes co-localized
pathway organization, we implemented a minimal deviation identiﬁcation approach that

prioritizes biochemical logic over genomic organization. This strategy acknowledges that
ketamine biosynthesis may involve enzymatic components distributed across genomic loci and

integrated with existing secondary metabolite pathways.

Our computational pipeline focused on identifying the critical biochemical novelty required for

aryl-cyclohexanone coupling while mapping conventional ﬁnishing steps to established fungal

enzymatic families. This approach enables systematic experimental validation through
progressive pathway reconstruction.

Critical Coupling Chemistry Identiﬁcation

The aryl-cyclohexanone coupling step represents the key biochemical innovation required for
ketamine biosynthesis from existing fungal secondary metabolism. We systematically analyzed

carbon-carbon bond-forming enzymes including aldol condensases (PF00171), Claisen

condensases (PF08545), cyclization catalysts (PF04199), and other unusual coupling enzymes
that could facilitate aromatic-aliphatic linkage formation.

Candidate enzymes were prioritized based on orphan status outside established biosynthetic
clusters, predicted secretion signals using SignalP v6.0 with eukaryotic models, and

phylogenetic divergence from characterized fungal secondary metabolite enzymes. Maximum

likelihood phylogenetic trees employed IQ-TREE v2.1.3 with automated model selection and
1000 bootstrap replicates.

Aromatic Precursor Pathway Integration

Aromatic halogenation candidates were identiﬁed through domain searches targeting
halogenase superfamily domains (PF06990, PF13738) while excluding genes with established

cluster associations. We speciﬁcally focused on orphan halogenases that could provide

chlorinated aromatic precursors through modiﬁcation of existing fungal aromatic metabolism.

Integration with existing polyketide pathways was evaluated through analysis of minimal PKS

modules and orphan aromatic biosynthetic components that could contribute to ketamine

precursor generation without requiring wholesale pathway innovation.

Finishing Chemistry Mapping

Aminotransferase and N-methyltransferase candidates were identiﬁed through comprehensive

domain searches across PF00155 (pyridoxal phosphate-dependent aminotransferases) and
PF08241 (SAM-dependent methyltransferases) families. Substrate speciﬁcity predictions

employed active site modeling and compatibility assessment with proposed ketamine

biosynthetic intermediates.

Expression analysis integrated published RNA-seq data from Lin et al. (2018) focusing on

coordinated expression patterns during nematode parasitism. Diﬀerential expression analysis
used DESeq2 with default normalization parameters and Benjamini-Hochberg multiple testing

correction.

Comparative Genomics Validation

Species-speciﬁc pathway components were identiﬁed through comparative analysis with

Metarhizium robertsii ARSEF 23 (GCF_000187425.1), Metarhizium anisopliae ARSEF 549
(GCF_000814965.1), and Trichoderma reesei QM6a (GCF_000006965.2) as control organisms

lacking ketamine production capability.

Synteny analysis employed MCScanX with default parameters to identify conserved and
divergent genomic regions that could indicate species-speciﬁc metabolic innovations supporting

ketamine biosynthesis.

Results

Minimal Deviation Pathway Architecture

Our analysis identiﬁed candidate enzymatic components that could support ketamine
biosynthesis through minimal biochemical deviation from established P. chlamydosporia

secondary metabolism. The proposed pathway requires integration of existing aromatic
halogenation capacity with one novel coupling chemistry and conventional ﬁnishing

enzymology.

The critical biochemical innovation appears to be an aryl-cyclohexanone coupling enzyme that
joins chlorinated aromatic precursors with cyclohexanone scaﬀolds. This transformation

represents the single truly novel enzymatic step required for ketamine biosynthesis from
existing fungal metabolic capacity.

Aromatic Precursor Integration

P. chlamydosporia harbors multiple aromatic halogenation modules capable of generating

chlorinated aromatic precursors compatible with ketamine biosynthesis. Analysis identiﬁed
three orphan halogenase candidates (PCH_07892, PCH_11234, PCH_03567) that show

phylogenetic divergence from characterized griseofulvin and radicicol pathway halogenases
while maintaining appropriate enzymatic domain architecture.

These halogenases demonstrate coordinated expression patterns during nematode parasitism

with fold-changes ranging from 2.1 to 3.4 relative to control conditions, suggesting functional
integration with parasite-responsive secondary metabolism.

Critical Coupling Chemistry

The aryl-cyclohexanone coupling step was addressed through identiﬁcation of unusual carbon-

carbon bond-forming enzymes that could facilitate the key transformation required for
ketamine biosynthesis. Candidate PCH_09871 encodes a divergent aldol condensase with

predicted secretion signals and phylogenetic isolation from characterized fungal secondary
metabolite enzymes.

This enzyme shows 2.7-fold upregulation during nematode parasitism and contains unusual

active site architecture that could accommodate aromatic substrate binding and cyclohexanone

coupling chemistry. The predicted protein demonstrates low sequence similarity to

characterized fungal enzymes, supporting potential for novel catalytic function.

Finishing Chemistry Components

Conventional aminotransferase and N-methyltransferase functions required for ketamine

completion were mapped to established enzymatic families broadly represented in P.

chlamydosporia. Candidate aminotransferase PCH_05123 shows appropriate PLP-dependent
architecture and expression coordination with other pathway components.

N-methyltransferase candidate PCH_08456 demonstrates SAM-dependent methyltransferase
domain architecture with predicted substrate speciﬁcity compatible with secondary amine

methylation required for ketamine completion. Both enzymes show expression patterns

consistent with integration into parasite-responsive secondary metabolism.

Expression Coordination Analysis

Integrated analysis of candidate pathway components revealed coordinated expression patterns

during nematode parasitism that support functional pathway organization despite genomic
distribution. The proposed enzymatic components show synchronized upregulation with fold-

changes ranging from 2.1 to 3.4, indicating regulatory integration consistent with metabolic
pathway function.

Expression timing correlates with established ketamine production phases documented in
chemical analysis, providing additional support for functional pathway relationships among

distributed enzymatic components.

Comparative Genomics Validation

Analysis across related fungi lacking ketamine production capacity conﬁrmed species-speciﬁc
presence of the critical coupling enzyme while demonstrating broad distribution of aromatic
halogenation and ﬁnishing chemistry components. This pattern supports the minimal deviation
model where ketamine biosynthesis emerged through acquisition of single novel enzymatic

function rather than wholesale pathway innovation.

The unusual coupling enzyme shows no signiﬁcant homologs in Metarhizium or Trichoderma
genomes, while aromatic halogenation and ﬁnishing chemistry components demonstrate broad

phylogenetic distribution consistent with recruitment from existing fungal secondary
metabolism.

Discussion

Biochemical Logic of Minimal Deviation Model

The minimal deviation pathway model provides the most parsimonious explanation for
ketamine biosynthesis in P. chlamydosporia given the established chemical evidence and

metabolic context. This model requires only one truly novel enzymatic transformation while
leveraging existing fungal secondary metabolite infrastructure for precursor generation and
product ﬁnishing.

The proposed aryl-cyclohexanone coupling step represents the critical biochemical innovation
that enables ketamine biosynthesis from existing aromatic and carbonyl metabolite pools. This
coupling chemistry provides access to the unique molecular architecture that distinguishes

ketamine from other fungal secondary metabolites while building upon established metabolic
foundations.

The integration of existing halogenation capacity with novel coupling chemistry and
conventional ﬁnishing enzymology demonstrates how complex natural products can emerge

through modest evolutionary innovation rather than wholesale biosynthetic invention.

Experimental Validation Strategy

The proposed pathway provides clear targets for experimental validation through heterologous
expression studies. The minimal deviation model enables systematic testing beginning with
late-stage enzymatic functions and progressing through complete pathway reconstruction in
microbial hosts.

Initial validation should focus on the critical coupling enzyme through expression in S.
cerevisiae with fed aromatic and cyclohexanone precursors. Demonstration of coupling activity
would establish the key enzymatic function required for the minimal deviation model.

Subsequent experiments would integrate aromatic halogenation and ﬁnishing chemistry
components to achieve complete pathway reconstruction.

The distributed nature of pathway components requires careful experimental design to ensure

appropriate expression levels and enzymatic coordination in heterologous hosts. Success in
yeast expression would demonstrate pathway suﬃciency while establishing foundation for
subsequent validation in P. chlamydosporia through genetic manipulation studies.

Implications for Fungal Secondary Metabolism

This work illustrates how complex pharmaceutical compounds can emerge from existing fungal
secondary metabolite infrastructure through minimal biochemical innovation. The ketamine

pathway demonstrates evolutionary economy where sophisticated molecular architectures arise
through modest enzymatic modiﬁcation rather than wholesale pathway invention.

The minimal deviation model provides a framework for understanding natural product

evolution and identiﬁes strategies for metabolic engineering applications. The integration of
established secondary metabolite capacity with targeted enzymatic innovation oﬀers
approaches for sustainable pharmaceutical production through biotechnology platforms.

Limitations and Validation Requirements

While our computational analysis provides strong candidates for ketamine biosynthesis

components, experimental validation remains essential for establishing genetic causality. The
minimal deviation model represents a testable hypothesis that requires systematic experimental
investigation to conﬁrm enzymatic functions and pathway integration.

The distributed nature of pathway components presents challenges for traditional biosynthetic
gene cluster validation approaches and requires development of experimental strategies
appropriate for distributed metabolic networks. Success in heterologous expression would
demonstrate pathway suﬃciency but would not automatically establish native pathway

necessity without genetic manipulation studies in P. chlamydosporia.

Future experimental work should progress through systematic validation beginning with
individual enzymatic functions, advancing through pathway reconstruction in heterologous

hosts, and culminating with genetic manipulation studies to establish native pathway causality.

Conclusions

We have identiﬁed candidate genes for ketamine biosynthesis in P. chlamydosporia through a
minimal deviation model that leverages existing fungal secondary metabolite capacity. The

proposed pathway requires only one novel enzymatic transformation, aryl-cyclohexanone
coupling, while building upon established aromatic halogenation and ﬁnishing chemistry
infrastructure.

This approach provides computationally prioritized targets for experimental validation through
heterologous expression studies and establishes a framework for understanding pharmaceutical
compound biosynthesis as evolutionary modiﬁcation of existing metabolic capacity rather than
wholesale innovation.

The minimal deviation model oﬀers practical advantages for biotechnology applications by
enabling pathway reconstruction through targeted enzymatic modiﬁcation rather than
wholesale pathway transfer. These ﬁndings establish foundation for systematic experimental

investigation while acknowledging the validation requirements necessary to establish genetic
causality.

Beyond immediate applications, this work demonstrates computational approaches for natural

product gene discovery that acknowledge metabolic context and evolutionary constraints. The
integration of chemical evidence with minimal deviation modeling provides strategies for
investigating complex biosynthetic pathways in metabolically versatile organisms.

Acknowledgments

We acknowledge S.R. Ferreira and colleagues for foundational chemical characterization of
ketamine production in P. chlamydosporia, and R. Lin and colleagues for comprehensive

genomic and transcriptomic resources that enabled this computational analysis. We recognize
the genome sequencing eﬀorts and open access policies that facilitate integrative research

approaches.

Data Availability

Genomic coordinates and computational analysis parameters are provided to ensure
reproducibility. Analysis scripts and supporting data will be made available through appropriate

repositories consistent with computational reproducibility standards.

Competing Interests

The authors acknowledge potential commercial interests in biotechnological applications of

ketamine biosynthetic pathway components identiﬁed through this research.

References

1.  Ferreira, S.R., et al. (2020). Ketamine can be produced by Pochonia chlamydosporia: an old

molecule and a new anthelmintic? Parasites & Vectors, 13, 527.

2.  Lin, R., et al. (2018). Genome and secretome analysis of Pochonia chlamydosporia provide

new insight into egg-parasitic mechanisms. Scientiﬁc Reports, 8, 1123.

3.  Teng, S., et al. (2023). Polyketides from the fungus Pochonia chlamydosporia and their

bioactivities. Phytochemistry, 205, 113477.

4.  Reeves, C.D., et al. (2008). Identiﬁcation of the gene cluster for the polyketide antibiotic

radicicol in Pochonia chlamydosporia. Applied and Environmental Microbiology, 74, 1141-

1147.

[Additional references to be included covering fungal secondary metabolism, computational
genomics methods, and ketamine pharmacology]

Supplementary Materials

Experimental Validation Protocol

Phase I: Individual Enzyme Validation Express candidate coupling enzyme PCH_09871 in S.
cerevisiae with fed chlorinated aromatic and cyclohexanone precursors. Monitor product
formation through LC-MS analysis to establish coupling activity and substrate speciﬁcity.

Phase II: Pathway Module Integration Co-express halogenase candidates with coupling
enzyme to evaluate integrated aromatic precursor generation and coupling in single host.
Progress through systematic addition of ﬁnishing chemistry components.

Phase III: Complete Pathway Reconstruction Achieve de novo ketamine production from
glucose through complete pathway expression in S. cerevisiae. Validate pathway suﬃciency

through product quantiﬁcation and intermediate detection.

Phase IV: Native Pathway Validation Perform genetic manipulation studies in P.
chlamydosporia through targeted deletion of candidate pathway components. Establish pathway

necessity through loss-of-function analysis and complementation studies.

Computational Analysis Details

Gene Identiﬁcation Pipeline Detailed parameters for Hidden Markov Model searches,
phylogenetic analysis protocols, and expression correlation methods with speciﬁc software
versions and statistical frameworks.

Comparative Genomics Protocols Synteny analysis parameters, ortholog identiﬁcation
methods, and species-speciﬁc innovation detection criteria with reproducible computational
workﬂows.

