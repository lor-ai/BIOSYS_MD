Computational Identification of Candidate Genes

for Ketamine Biosynthesis in Pochonia

chlamydosporia: Deep Research Synthesis,

Reconciliation, and Revised Manuscript Draft

Executive summary

The   central   scientific   question—whether  Pochonia   chlamydosporia  produces   ketamine   de   novo—remains

unresolved  because (i) there is  no established natural (biosynthetic) pathway  for ketamine in curated

metabolism/secondary-metabolism   resources,   and   (ii)   the   current   manuscript   draft’s   computational

evidence   (candidate   enzymes   and   putative   clusters)   is  not   yet   specific   enough  to   uniquely   support

ketamine biosynthesis over alternative explanations (notably contamination, uptake, or misidentification).

The motivating experimental report (“Ketamine can be produced by Pochonia chlamydosporia…”, Parasites &

Vectors,   2020)   provides   important   impetus   but   does   not,   on   its   own,   establish   a   biosynthetic   gene-to-

metabolite chain of evidence.

1

A   rigorous   manuscript   can   still   be   built—as   a   hypothesis-generating   genome-mining   study—if   it   is

reframed   around:   (a)   stringent   compound   verification   (including   stereochemistry   and   isotope

incorporation), (b) reproducible genome mining against a clearly versioned assembly/annotation, and (c)

orthogonal   evidence   linking   a   specific   genomic   locus   (ideally   a   cluster)   to   ketamine-associated   features

(expression,   knockout   phenotype,   heterologous   reconstitution).   The   Pc123   reference   genome   context   is

well-defined (GenBank assembly accession GCA_000411695.2 is widely cited and indexed in Ensembl Fungi;

a PacBio-improved assembly exists as GCA_000411695.4).

2

Because   ketamine   appears   in  drug/ligand  databases   (e.g.,   KEGG   DRUG   D08098)   rather   than   natural-

product   biosynthesis   resources,   the   manuscript   must   explicitly   treat   ketamine   biosynthesis   as

extraordinary and require correspondingly strong controls.

3

Evidence landscape and biological plausibility

Ketamine is a synthetic arylcyclohexylamine anesthetic (KEGG DRUG: D08098), and major public pathway

resources do not provide a biosynthetic module for its natural production (it is cataloged as a drug/ligand

and receptor antagonist, not as an endogenous metabolite pathway).

4

  A curated biosynthetic-cluster

resource like MIBiG (v4.0) is designed to standardize and disseminate experimentally supported BGC-to-

metabolite links; ketamine is not presently represented as a canonical MIBiG metabolite class with a known

BGC, underscoring the novelty of the hypothesis.

5

In contrast,  P. chlamydosporia  is  well established  as a prolific secondary metabolite producer, including

halogenated   polyketides   and   griseofulvin-related   compounds,   and   its  radicicol/pochonin  chemistry

1

provides a concrete precedent for fungal aromatic chlorination chemistry within this organism.

6

  The

relevant   enzymology   is   also   well   understood:   fungal   aromatic   chlorination   is   often   mediated   by  flavin-

dependent   halogenases  (FDHs),   whose   mechanistic   chemistry   (FADH₂/O₂/Cl⁻   →   HOCl/halogenating
equivalent) and active-site features have been characterized in depth.

7

However,   this   same   point   cuts   both   ways:   the   presence   of   FDHs,   P450s,   aminotransferases,   and

methyltransferases   in   a   genome—especially   in   fungi—does   not   uniquely   imply   a   ketamine   pathway,

because these enzyme families are common across many unrelated BGCs. The draft therefore must go

beyond   “family   plausibility”   to   show  phylogenetic   specificity,

 cluster   coherence,   and   ideally

experimental linkage.

Reproducibility and computational-methods audit

A   reproducible   computational   study   in   this   area   should   explicitly   version   and   parameterize  all  of   the

following: genome assembly/annotation, BGC calling, homology search, domain assignment, alignment/

tree inference, and cluster/comparison annotation. The manuscript should standardize on a single primary

assembly (Pc123) and then optionally provide lift-over/mapping to newer assemblies.

Genome data provenance and assembly versioning

Pc123 public genome resources exist in at least two actively used versions:

•

GCA_000411695.2 (Pc123; referenced widely and indexed in Ensembl Fungi under Pochonia

chlamydosporia 123, assembly “PcB1v2”).

8

•

GCA_000411695.4 (PacBio-improved assembly; reduced scaffolds and updated gene models

reported in a Pc123 reassembly/reannotation study).

9

The manuscript should explicitly state which is used for coordinates and locus IDs, because coordinate

systems and gene IDs can change across versions. For computational reproducibility (and compatibility with

older   locus   tags   used   in   earlier   work),   starting   with  GCA_000411695.2  is   defensible,   while   providing   a

mapping to GCA_000411695.4 is strongly recommended.

Tooling: primary-source supported versions

The following toolchain is standard, with primary references that should be cited:

•

antiSMASH 7.0 for BGC detection and annotation.

10

•

InterProScan 5 for protein family/domain integration at genome scale.

11

•

SignalP 6.0 for secretion/signal peptide prediction where relevant (mainly for secreted proteins;

often less central for intracellular BGC enzymes).

12

•

MAFFT v7 for multiple sequence alignments.

13

•

IQ-TREE 2 for maximum-likelihood phylogenetic inference; optionally include UFBoot2 when

reporting support.

14

•

MIBiG 4.0 as the curated BGC reference benchmark.

5

The revised manuscript should include exact command lines (or, if HPC/containers are used, an equivalent

workflow specification) and provide a minimal reproducible “start-to-finish” pipeline.

2

Minimal reproducible pipeline outline

Below is a reproducible computational template (fill in actual file names, hashes, and tool versions used in

the study):

Data acquisition - Download assembly FASTA + annotation GFF3 for Pc123. - Record SHA256 checksums. -

Record assembly accession.version (e.g., GCA_000411695.2) and annotation release date/source.

BGC   calling   (antiSMASH)  -   Run   antiSMASH   on   the   genome   FASTA,   with   fungal   mode   enabled   and   all

options captured in a log file.

15

- Export: cluster boundaries, gene lists per cluster, predicted product class, and MIBiG similarity hits.

Protein   annotation   (InterProScan)  -   Run   InterProScan   on   predicted   proteins   to   obtain   Pfam/InterPro

domains, active site signatures, and GO terms.

11

Candidate prioritization  - Filter for enzyme families plausibly relevant to: aromatic halogenation (FDH),

oxidative tailoring (P450/oxidases), C–N chemistry (aminotransferases), and N-methylation (SAM-dependent

NMTs). - Apply genomic-context scoring: prefer candidates that co-localize in clusters with coherent tailoring

logic.

Phylogenetics - For each enzyme family (FDH, P450, aminotransferase, NMT), build: - a reference set from

experimentally characterized enzymes (MIBiG-linked where possible), - plus P. chlamydosporia candidates. -

Align   with   MAFFT;   trim   if   needed;   infer   ML   tree   with   IQ-TREE   2;   report   model   selection   and   bootstrap

supports.

16

Cluster/synteny  -   Visualize   cluster   gene   order   and   compare   to   known   clusters   (e.g.,  radicicol/pochonin

cluster). The radicicol cluster in  P. chlamydosporia  is documented in primary literature and provides a key

comparator.

17

Reconciled candidate genes and evidence table

Candidate-list reconciliation across drafts

Your described drafts appear to contain two overlapping “candidate sets”:

•

A minimal-deviation enzyme set (halogenase, P450, oxidoreductase, cyclase/condensase,

aminotransferase, N-methyltransferase) intended to implement a short putative pathway.

•

A scaffold/cluster-based set (a putative cluster containing halogenase + PKS + aminotransferase +

P450 + N-methyltransferase) intended to leverage BGC logic.

Because stable accessions may be missing, the most defensible manuscript approach is:

1) Treat draft locus tags (e.g., “PCH_07892”) as working identifiers.

2) Map them to stable public identifiers from Pc123 (GCA_000411695.2) via Ensembl Fungi (species entry

exists and supports queries by gene-like IDs such as I1G_… per the species page).

8

3) If direct mapping cannot be automated from identifiers alone, request protein FASTA or the authors’

mapping table (draft IDs → public IDs).

3

Candidate evidence table (structured for completion once accessions are supplied)

The   table   below   is   provided   in   the   exact   schema   you   requested;   fields   that   require   stable   accessions/

sequences are left as  TBD  and are paired with explicit instructions for completion. Confidence scores are

defined on a 0–5 scale (0 = unsupported; 5 = experimentally validated in pathway).

Draft candidate ID

Assembly

Genomic

Protein

InterPro/Pfam

accession used

coordinates

length

domains

PCH_07892
(putative

halogenase)

GCA_000411695.2

(Pc123; Ensembl
Fungi PcB1v2)

8

TBD

TBD

Expect FDH/
halogenase

signatures

Phylogenetic

placement

Genomic

neighbors /

synteny

Expression

Predicted

Confidence

evidence

reaction

(0–5)

membership vs

seq/qPCR)

precursor

TBD (RNA-

a phenolic

TBD (critical:

cluster

dispersed FDH)

Aromatic

chlorination of

(plausible

chemistry)

21

Closest

homologs

(accession;

%ID)

Compare to

Radicicol/Rdc2-

like

halogenases;

gsfI~RadH
similarity

reported in

griseofulvin/

radicicol

context

19

Catalytic

motifs to

verify

FDH catalytic

Lys (e.g., RebH

Lys79 analog),

FAD-binding/
FDH motifs;

verify

regiospecificity

determinants

18

Heme-binding

Cys motif

(FGxGPR/CxG),

Should nest

within fungal

FDH clade;

compare with

known fungal

halogenation

enzymes

20

Compare with

known tailoring

P450s from

fungal polyketide

clusters (e.g.,

radicicol)

22

Place within

aminotransferase

class I/II or IV;

compare to

secondary

metabolism

transaminases

2

1

1

1

2

Hydroxylation/

epoxidation or

oxidative

(highly

nonspecific

family)

Redox tailoring

(ketone/alcohol

interconversion)

C–C bond

formation / ring

closure (highest

biochemical

uncertainty)

Install amino

group

(precursor →

amine)

TBD

TBD

P450 domain

PERF motif;

TBD

TBD

TBD

coupling step

substrate

recognition

sites

TGXXXGIG

(Rossmann) if

SDR /

TBD

TBD

dehydrogenase?

SDR; active

TBD

TBD

TBD

TBD

(TBD)

Tyr/Lys motif if

SDR

TBD

TBD

TBD

TBD

TBD

TBD

TBD

TBD

PCH_05123

(putative

aminotransferase)

GCA_000411695.2

8

PLP-dependent

TBD

TBD

aminotransferase

(expected)

Lys for PLP

Schiff base;

NNRYGGHGS-

like motifs

depend on

class

TBD

TBD

TBD

4

PCH_11234

(putative

cytochrome P450)

GCA_000411695.2

8

PCH_03567

(putative

oxidoreductase)

GCA_000411695.2

8

PCH_09871

(putative cyclase/

condensase)

GCA_000411695.2

8

Draft candidate ID

Assembly

Genomic

Protein

InterPro/Pfam

accession used

coordinates

length

domains

PCH_08456

(putative N-

methyltransferase)

GCA_000411695.2

8

TBD

TBD

SAM-dependent

MTase

Catalytic

motifs to

verify

VLDI/

VIGCGTG,

FxGXGXG (SAM

binding region

varies by fold);

verify N-MT vs

O-MT

Closest

homologs

(accession;

%ID)

Compare to

characterized

alkaloid NMTs;

avoid

conflation with

O-MTs from

polyketide

pathways

22

PCH_10405

(cluster
halogenase

candidate)

GCA_000411695.2

8

TBD

TBD

FDH? (TBD)

As above for
FDH

TBD

TBD

NMT, raises

TBD

PCH_PKS7

(putative PKS)

GCA_000411695.2

8

PKS domains (KS,

KS Cys-His-His

(reducing +

Compare to

radicicol PKSs

TBD

TBD

AT, ACP ± KR/DH/

catalytic triad

nonreducing)

membership

TBD

ER)

signatures

in P.

chlamydosporia

cluster

22

PCH_AAT1

(aminotransferase;

cluster)

GCA_000411695.2

8

TBD

TBD

PLP

aminotransferase

PLP Lys motif

TBD

TBD

PCH_CYP102

(P450; cluster)

GCA_000411695.2

8

TBD

TBD

P450

P450 motifs

TBD

TBD

Adjacent to PKS/

FDH/P450?

Adjacent to other

tailoring genes

TBD

TBD

Amine

installation

Oxidative

tailoring

PCH_NMT1 (N-

methyltransferase;

cluster)

GCA_000411695.2

8

TBD

TBD

SAM-dependent

SAM binding

MTase

motifs

TBD

TBD

TBD

N-methylation

Adjacent to

aminotransferase?

Phylogenetic

placement

Genomic

neighbors /

synteny

Expression

Predicted

Confidence

evidence

reaction

(0–5)

TBD

TBD

TBD

If truly in a BGC

with PKS/P450/

priority (cluster

coherence)

PKS family clade

placement

Cluster

critical

N-methylation

of amine to

methylamine

substituent

Chlorination of

aromatic

precursor

Produces

polyketide

scaffold(s); link

to ketamine is

indirect

2

3

1

2

2

2

Key   interpretation:  At   present,   the  highest-scoring   hypothesis  is  not  “these   genes   prove   ketamine

biosynthesis,” but rather: “Pc123 contains plausible enzyme families, and at least one candidate locus may

represent   a   coherent   secondary-metabolism   region;   targeted   phylogeny   +   expression   +   genetics   can

decisively test linkage.”

Immediate data request to complete the table

To fill the “TBD” fields rigorously, please provide at least one of:

5

1) A mapping spreadsheet from the drafts:  draft gene IDs → public IDs  (e.g., I1G_000xxxxx, GenBank
protein accessions, or Ensembl gene IDs), or

2) The protein FASTA for all candidate genes (headers containing locus IDs), or

3) The  antiSMASH output folder  (GBK/JSON) used in the draft, which typically contains coordinates and

gene calls, or

4) A GenBank/RefSeq GFF3 used for annotation.

Without   one   of   these,   any   coordinate/length/domain   claims   would   be   speculative   and   should   not   be

included as “results” in a scientific manuscript.

Phylogeny and pathway figures

Hypothetical pathway logic (explicitly framed as a testable model)

This   diagram   represents   a   hypothesis   consistent   with   known   enzyme   chemistries   (FDH   halogenation;
aminotransferase; methyltransferase), but it is not supported by any established ketamine biosynthetic

pathway in curated resources.

23

flowchart TD

  A["Primary metabolism precursors<br/>(aromatic precursor + carbon skeleton)"]

--> B["Aromatic precursor assembly<br/>(shikimate-derived OR polyketide-derived;

TBD)"]

  B --> C["Flavin-dependent halogenase (FDH)<br/>chlorination of aromatic ring"]

  C --> D["Ketone-containing scaffold formation<br/>(cyclohexanone-like; unknown

enzymology)"]

  D --> E["C–C bond formation / aryl–alkyl coupling<br/>(candidate: P450 or

other oxidative enzyme; TBD)"]

  E --> F["Aminotransferase<br/>install amino group"]

  F --> G["N-methyltransferase<br/>N-methylation to methylamino"]

  G --> H["Ketamine (hypothesized)"]

Mechanistic plausibility anchors: FDH catalysis and halogenating intermediates are well characterized in

flavin-dependent halogenases (e.g., RebH-class enzymes).

24

Computational analysis workflow (reproducible scaffold)

flowchart TD

  A["Select assembly/annotation<br/>Pc123: GCA_000411695.2 (primary)"] -->

B["Run antiSMASH 7.0<br/>BGC calls + MIBiG similarity"]

  B --> C["Annotate proteins with InterProScan 5<br/>domains + families"]

  C --> D["Candidate selection<br/>FDH, P450, aminotransferase, NMT"]

  D --> E["Genomic context scoring<br/>cluster coherence + synteny"]

  E --> F["Phylogenetics per family<br/>MAFFT v7 -> IQ-TREE 2 (+UFBoot2)"]

  F --> G["Expression evidence integration<br/>RNA-seq mapping/qPCR"]

6

  G --> H["Prioritized experimental tests<br/>knockout / heterologous

expression"]

Toolchain references: antiSMASH 7.0, InterProScan 5, MAFFT v7, IQ-TREE 2, UFBoot2.

25

Experimental evidence assessment and prioritized experiments

Why contamination and non-biosynthetic explanations must be foregrounded

Ketamine is widely used and can be environmentally persistent; wastewater studies report persistence and

limited microbial degradation in some contexts, making trace contamination a realistic confounder.

26

Additionally, ketamine exists as enantiomers; a  natural biosynthesis  would often be expected to show

enantioenrichment, whereas contamination from pharmaceutical sources may appear  racemic  (though

handling and transformations could complicate this). (If the 2020 study reported stereochemical analysis, it

should be highlighted; if not, it is a high-priority gap.)

1

Prioritized experiments table

Timelines below assume standard molecular biology and analytical chemistry access; “resources” refer to

instrumentation and expertise, not budget.

Priority

Experiment

Key control(s)

Readout

Expected

timeline

Resources

Why it is decisive

Orthogonal

compound

Highest

confirmation

from fresh

cultures

Chiral analysis of

Highest

ketamine (if

detected)

Media blanks;

extraction

blanks; lab

environmental

blanks;

authentic

ketamine

standard;

carryover

controls

Ketamine

racemate +

enantiopure

standards

LC–MS/MS

(MRM +

HRMS), GC–

MS, and NMR

confirmation;

retention time

match;

fragmentation

match

Chiral LC or

GC to

measure

enantiomeric

excess

2–6

weeks

LC–MS/MS +

NMR access

Confirms the

metabolite identity

beyond a single

modality;

addresses mis-ID

2–6

weeks

Chiral column

method

development

Enantioenrichment

is strong evidence

against generic

contamination

7

Priority

Experiment

Key control(s)

Readout

Expected

timeline

Resources

Why it is decisive

Stable-isotope

Highest

incorporation

(biosynthesis test)

Unlabeled

controls;

isotope

natural

abundance

correction

Multiple

independent

Time-course

culture

High

production and

replicates;

different
media; sterile

controls

localization

Targeted

knockout/

knockdown of

Ectopic

High

top candidate

transformants;

gene(s) (starting

complemented

with putative

strains

FDH/P450 in any

coherent cluster)

Heterologous

expression of a

Empty vector;

minimal gene set

partial-

or cluster in

pathway

yeast/Aspergillus

constructs

High

Medium

host

RNA-seq under

producing vs

non-producing

conditions

In vitro enzyme

assays (FDH

Incorporation

from ^13C/

^15N

precursors

into ketamine

mass shifts/

patterns

1–3

months

Isotope

substrates +

HRMS

Directly tests de

novo biosynthesis

vs uptake/

contamination

Production

kinetics; intra/

1–2

extracellular

months

localization

LC–MS/MS

Distinguishes

secreted

metabolite vs

medium artifact;

strengthens
reproducibility

Loss/

reduction of

ketamine

signal (and/or

cluster

metabolite

changes)

New

metabolite

peaks

consistent

with

intermediates/

ketamine

3–9

Fungal

genetics

months

(CRISPR or

HR), LC–MS

Establishes

gene→metabolite
causality

6–18

months

Synthetic

biology + LC–

MS

Powerful

reconstruction

test; aligns with

known cluster

reconstitution

strategies

22

Supports cluster

2–4

RNA-seq +

coherence and

months

bioinformatics

prioritization; not

definitive alone

Biological

replicates;

spike-ins

Co-expression

of cluster

genes

Medium

halogenation;

NMT methylation;

aminotransferase)

Heat-killed

enzyme;

Substrate

conversion by

6–18

minus-cofactor

purified

months

controls

enzymes

Enzyme

Mechanistic

purification +

validation; helps

assays

map intermediates

Feasibility   note:  The   Pc123   genome   has   been   improved   with   long   reads   and   transcriptome-supported

annotation, and prior work demonstrates availability of RNA-seq contexts for Pc123 analyses.

27

8

Full revised manuscript draft and figure plan

Manuscript title

Computational   Identification   of   Candidate   Genes   for   Ketamine   Biosynthesis   in  Pochonia

chlamydosporia

Executive summary (for the manuscript)

A   2020   report   described   ketamine   as   a   major   compound   in   bioactive   fractions   from  Pochonia

chlamydosporia,   motivating   the   hypothesis   that   this   fungus   might   produce   ketamine   or   a   ketamine-like

compound.

1

  Here,   we   conduct   a   reproducible   genome-mining   analysis   of   Pc123   (P.   chlamydosporia

isolate 123), integrating biosynthetic gene-cluster prediction, protein domain annotation, and comparative

genomics   to   identify   candidate   enzymes   and   loci   consistent   with   chemical   transformations   required   to

produce   a   chlorinated   arylcyclohexylamine.   We   emphasize   stringent   alternative   explanations

(contamination, uptake, misidentification) and propose a prioritized experimental strategy (stable-isotope

incorporation,   chiral   analysis,   genetics,   and   heterologous   expression)   to   link   genomic   candidates   to

metabolite evidence.

Introduction (background and contamination risks)

Pochonia  chlamydosporia  is  a  nematophagous  and  endophytic  fungus  widely  studied  for  biocontrol  and

known to produce diverse secondary metabolites, including halogenated polyketides.

28

  A particularly

relevant   precedent   is   the   documented   radicicol/pochonin   biosynthetic   machinery   in  P.   chlamydosporia,

which includes enzymatic chlorination in a fungal secondary-metabolism context.

17

Ketamine, by contrast, is a widely used anesthetic classified and indexed primarily as a drug/ligand rather

than a known natural product, and curated resources do not provide an established ketamine biosynthetic

pathway.

23

  Consequently,   claims   of   natural   ketamine   production   require   exceptional   rigor.   Plausible

confounders   include   trace   environmental   or   laboratory   contamination,   metabolite   carryover,   or

misassignment   of   analytical   signals.   Ketamine   can   persist   in   aqueous   environments,   underscoring   that

contamination is not merely hypothetical.

26

We therefore frame this work as hypothesis generation and prioritization: identifying the most plausible

genomic candidates and defining decisive experiments to test de novo biosynthesis.

Methods (computational and experimental proposals)

Genome assembly and annotation selection

We used Pc123 assembly GCA_000411695.2 as the primary coordinate system because it is a stable, widely

referenced   Pc123   assembly   and   is   indexed   as   PcB1v2   in   Ensembl   Fungi.

8

  We   note   that   a   PacBio-

improved Pc123 assembly  GCA_000411695.4  exists and should be used in follow-up mapping/validation

analyses.

29

BGC mining

We propose running antiSMASH 7.0 with fungal settings on the selected assembly to detect candidate BGCs

and assess similarity to curated MIBiG clusters.

30

9

Protein domain and enzyme-family assignment

We   propose   InterProScan   5   for   integrated   domain   calls,   with   orthogonal   motif   scanning   for   hallmark

catalytic residues in FDHs and P450s.

31

Phylogenetic inference

For each candidate enzyme family, we propose: MAFFT v7 alignments and IQ-TREE 2 maximum-likelihood

trees, reporting model selection and bootstrap supports (UFBoot2 when used).

32

Experimental plan (proposed, not executed here)

We prioritize isotope incorporation and stereochemical analysis as the fastest decisive tests, followed by

genetics and heterologous expression.

Results (candidate tables, phylogenies, synteny, expression)

Candidate genes

We reconcile candidate genes into (i) a minimal enzyme set consistent with required chemistries and (ii)

clustered   candidates   that   better   satisfy   BGC   logic.   The   current   evidence   supports   “enzyme-family

plausibility”   most   strongly   for   halogenation   (FDH)   because   fungal   halogenation   is   well   documented

mechanistically and in P. chlamydosporia’s known chemistry.

33

Phylogenetic trees and alignments (to be included as Supplementary Data)

Because stable candidate accessions and FASTA sequences are not yet provided in the drafts, the following

are defined as required supplements once sequences are available:

•

FDH protein alignment (FASTA + MSA) and ML tree including:

•

Pc123 FDH candidates,

•

known fungal FDHs (e.g., radicicol/pochonin halogenase context),

•

bacterial RebH-class FDHs as mechanistic anchors.

34

•

P450 alignment + ML tree including radicicol-cluster P450 comparators (where applicable).

22

•

Aminotransferase and N-methyltransferase trees with curated references (MIBiG-linked where

possible).

5

Synteny/cluster analysis

We recommend explicit synteny maps comparing any “ketamine-candidate cluster” to known Pc secondary-

metabolism   loci   (especially   the   radicicol   cluster   reported   in  P.   chlamydosporia),   to   avoid   misattributing

known polyketide clusters as ketamine-specific.

35

Expression evidence

If  RNA-seq  is  available  for  producing  vs  non-producing  conditions,  a  heatmap  should  be  generated  for

candidate   genes   and   neighboring   cluster   genes.   Pc123   has   documented   transcriptome-based   genome

reannotation contexts in the literature.

36

Discussion (alternative explanations, limitations, and interpretation)

At present, the genome-mining evidence most strongly supports that  P. chlamydosporia encodes plausible

machinery   for  aromatic   halogenation  and   diverse   secondary   metabolism,   consistent   with   its   known

production   of   halogenated   polyketides   and   established   radicicol/pochonin   gene   clusters.

37

  However,

10

ketamine is not an established natural product pathway in curated metabolism/BGC resources, and the

candidate gene list—without phylogenetic specificity, cluster coherence, expression linkage, and genetic

validation—cannot uniquely implicate ketamine biosynthesis.

38

We therefore interpret the present computational results as an argument for  where to look, rather than

proof   of   a   pathway.   The   decisive   discriminators   are:   isotope   incorporation,   stereochemistry,   and

gene→metabolite causality.

Recommended experiments (prioritized action plan)

Phase 1 (decisive compound validation; 1–3 months)

Confirm   ketamine   identity   by   orthogonal   analytics;   determine   enantiomeric   composition;   test   isotope

incorporation.

Phase 2 (genetics; 3–9 months)

Target   the   highest-confidence   locus   (preferably   a   coherent   cluster   containing   FDH   +   amination   +

methylation logic). Demonstrate loss-of-signal and rescue by complementation.

Phase 3 (reconstitution; 6–18 months)

Heterologous   expression   of   the   minimal   gene   set   or   full   cluster   to   identify   intermediates   and   confirm

sufficiency.

Conclusions

A rigorous, publishable manuscript can be produced now if reframed as: “Pc123 genome mining identifies

plausible enzyme families and one or more candidate loci consistent with transformations required for a

chlorinated   arylamine;   decisive   experimental   tests   are   proposed.”   Stronger   causal   language   (“ketamine

biosynthesis   genes   identified”)   should   be   avoided   until   compound   validation   and   genetic   linkage   are

demonstrated.

Figures and tables to include

•

Table 1: Candidate-gene evidence table (schema provided above; complete once accessions are

supplied).

•

Table 2: antiSMASH clusters and top MIBiG similarity hits (to prevent conflation with known Pc

polyketide clusters).

39

•

Table 3: Domain architecture summary (InterPro/Pfam) for each candidate.

11

•

Figure 1: Hypothetical pathway diagram (Mermaid flowchart above).

•

Figure 2: FDH phylogenetic tree (IQ-TREE 2) with bootstrap supports (UFBoot2).

14

•

Figure 3: Cluster synteny map highlighting candidate locus vs radicicol/pochonin locus.

17

•

Figure 4 (optional): Expression heatmap under producing vs non-producing conditions (if data

exist).

36

Reproducible computational appendix (commands/pseudocode)

antiSMASH - Provide: software version, database versions, parameters, and the full output archive.

15

11

InterProScan  -   Provide:   version,   member   databases   enabled,   and   output   formats   (TSV   +   GFF3

recommended).

11

Phylogenetics - MAFFT v7 alignment, IQ-TREE 2 inference, UFBoot2 supports.

32

Proposed file organization -  data/genome/  (FASTA, GFF3, checksums)
-  analysis/antismash/  (full output)
-  analysis/interproscan/
-  analysis/phylogeny/<family>/  (FASTA, MSA, treefiles, logs)
-  results/tables/  (CSV/TSV)
-  results/figures/  (PDF/SVG)

Missing information required from the drafts (explicit requests)

To  complete  the  manuscript  to  the  level  you  specified  (coordinates,   domains,  closest   homologs   with  %
identity, phylogenetic trees, alignments), please provide at least one of the following:

•

Candidate-gene protein FASTA (or nucleotide CDS FASTA),

•

•

Draft-to-public ID mapping (PCH_ / custom labels → I1G_ and/or GenBank/UniProt accessions),
antiSMASH output ZIP used in the draft,

•

Any available RNA-seq accession(s) or raw count tables for candidate loci under ketamine-

producing conditions,

•

Raw analytical data supporting ketamine (LC–MS/MS raw files, NMR files, standards,

chromatograms), and (critically) whether chiral measurements were performed.

Without these, the manuscript can be finalized as a hypothesis-driven genome-mining and experimental-

design paper, but not as a definitive “biosynthetic pathway identification” study.

1

Ketamine can be produced by Pochonia chlamydosporia: an old molecule and a new anthelmintic? |

Parasites & Vectors | Full Text

https://parasitesandvectors.biomedcentral.com/articles/10.1186/s13071-020-04402-w?utm_source=chatgpt.com

2

8

https://fungi.ensembl.org/Pochonia_chlamydosporia_123_gca_000411695/Info/Index

https://fungi.ensembl.org/Pochonia_chlamydosporia_123_gca_000411695/Info/Index

3

4

23

KEGG DRUG: Ketamine

https://www.kegg.jp/entry/D08098?utm_source=chatgpt.com

5

38

MIBiG 4.0: advancing biosynthetic gene cluster curation through global collaboration - PubMed

https://pubmed.ncbi.nlm.nih.gov/39657789/?utm_source=chatgpt.com

6

17

22

28

34

35

37

Genes for the biosynthesis of the fungal polyketides hypothemycin from

Hypomyces subiculosus and radicicol from Pochonia chlamydosporia - PubMed

https://pubmed.ncbi.nlm.nih.gov/18567690/?utm_source=chatgpt.com

7

21

24

Flavin redox chemistry precedes substrate chlorination during the reaction of the flavin-

dependent halogenase RebH - PubMed

https://pubmed.ncbi.nlm.nih.gov/16784243/?utm_source=chatgpt.com

12

9

27

29

https://pmc.ncbi.nlm.nih.gov/articles/PMC8817618/

https://pmc.ncbi.nlm.nih.gov/articles/PMC8817618/

10

15

25

30

39

antiSMASH 7.0: new and improved predictions for detection, regulation, chemical

structures and visualisation | Nucleic Acids Research | Oxford Academic

https://academic.oup.com/nar/article-abstract/51/W1/W46/7151336?utm_source=chatgpt.com

11

31

InterProScan 5: genome-scale protein function classification - PubMed

https://pubmed.ncbi.nlm.nih.gov/24451626/?utm_source=chatgpt.com

12

SignalP 6.0 predicts all five types of signal peptides using protein language models | Nature

Biotechnology

https://www.nature.com/articles/s41587-021-01156-3?utm_source=chatgpt.com

13

16

32

MAFFT multiple sequence alignment software version 7: improvements in performance and

usability - PubMed

https://pubmed.ncbi.nlm.nih.gov/23329690/?utm_source=chatgpt.com

14

IQ-TREE 2: New Models and Efficient Methods for Phylogenetic Inference in the Genomic Era | Molecular

Biology and Evolution | Oxford Academic

https://academic.oup.com/mbe/article/37/5/1530/5721363?utm_source=chatgpt.com

18

Chlorination by a long-lived intermediate in the mechanism of flavin-dependent halogenases - PubMed

https://pubmed.ncbi.nlm.nih.gov/17260957/?utm_source=chatgpt.com

19

Identification of the Viridicatumtoxin and Griseofulvin Gene Clusters from Penicillium aethiopicum -

ScienceDirect

https://www.sciencedirect.com/science/article/pii/S1074552110001560?utm_source=chatgpt.com

20

33

Halogenation in Fungi: What Do We Know and What Remains to Be Discovered? | MDPI

https://www.mdpi.com/1420-3049/27/10/3157?utm_source=chatgpt.com

26

Ketamine and the metabolite norketamine: persistence and phototransformation toxicity in hospital

wastewater and surface water - PubMed

https://pubmed.ncbi.nlm.nih.gov/24531031/?utm_source=chatgpt.com

36

https://pubmed.ncbi.nlm.nih.gov/35123406/

https://pubmed.ncbi.nlm.nih.gov/35123406/

13

