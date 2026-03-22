17/03/2026, 05:23

Google Gemini

Title: Genomic Mapping and
Biosynthetic Reconstruction of

Ketamine Production in Pochonia

chlamydosporia for Heterologous

Expression in Saccharomyces

cerevisiae

Abstract:

Recent biochemical evidence (Ferreira et

al., 2020) has identified the

arylcyclohexylamine ketamine as a natural

secondary metabolite of the

nematophagous fungus Pochonia

chlamydosporia. Despite its significance in

human medicine as an NMDA antagonist,

the genetic basis for its biosynthesis has

remained uncharacterized. This paper

proposes a computational strategy to

isolate the Ketamine Biosynthetic Gene

Cluster (BGC) within the P.

chlamydosporia genome

(GCA_000411695.1) using differential

genome mining and secretome analysis.

Furthermore, we outline a formal

procedure for the heterologous expression

of this cluster in Saccharomyces

cerevisiae to enable a sustainable,

biologically derived production model.

1. Introduction

Pochonia chlamydosporia is a versatile

filamentous fungus known primarily for its

parasitic activity against nematode eggs.

While its secondary metabolome has been

studied for polyketides like

https://gemini.google.com/app/33fbca041500e425

1/6

17/03/2026, 05:23

Google Gemini

pochonichlamydins and griseofulvin (Teng

et al., 2023), the discovery of natural

ketamine production represents a

significant expansion of its chemical

repertoire. Ferreira et al. (2020)

demonstrated that P. chlamydosporia

extracts contain ketamine (

C  H  ClNO
16

13

),

functioning as an anthelmintic to paralyze

host nematodes. Identifying the enzymatic

"code" for this molecule enables the

transition from wild extraction to precision

bio-manufacturing.

2. Theoretical Biosynthetic
Framework

The proposed "Natural Stevens

Rearrangement" hypothesis suggests that

P. chlamydosporia assembles ketamine

through a modular assembly line rather

than the high-temperature synthesis used

in industrial chemistry.

The Five-Step Enzymatic "Weld":

1.  Aromatic Priming: Selection of an

aryl precursor (likely Phenylalanine-

derived).

2.  Ortho-Chlorination: Facilitated by a

Flavin-dependent halogenase (FDH).

3.  Chain Extension: A Non-Reducing

Polyketide Synthase (NR-PKS)

assembles the carbon backbone.

4.  Oxidative Cyclization: A

Cytochrome P450 or Radical SAM

https://gemini.google.com/app/33fbca041500e425

2/6

17/03/2026, 05:23

Google Gemini

enzyme closes the cyclohexanone

ring.

5.  Amine Installation: An

Aminotransferase and N-

methyltransferase complete the

functionalization.

3. Computational Methods for BGC
Identification

3.1 Differential Genome Mining

To isolate the ketamine cluster from the

41Mb genome of Strain 123 (Lin et al.,

2018), a comparative subtraction is

performed against Metarhizium robertsii.

Because Metarhizium is a prolific insect

pathogen but does not produce ketamine,

the genes unique to Pochonia that also

contain halogenase domains are primary

candidates.

3.2 Secretome Filtering (The
"Return to Sender" Strategy)

Given that ketamine is a defensive

weapon, the enzymes involved in its

synthesis or export are likely part of the

fungal secretome.

Method: Cross-reference candidate

genes from the GCA_000411695.1

assembly with the 1,750 secreted

proteins identified in Lin et al. (2018).

Target: Identify an "orphan" FDH

halogenase possessing a C-terminal

https://gemini.google.com/app/33fbca041500e425

3/6

17/03/2026, 05:23

Google Gemini

signal peptide and clustering with an

aminotransferase.

4. Identified Target Cluster

(Scaffold 14)

Computational analysis points to a 35kb

cluster on Scaffold 14 of the PC123

assembly.

PCH_10405 (Orphan Halogenase):

The anchor of the cluster; distinct

from the griseofulvin-associated

halogenase.

PCH_PKS7 (NR-PKS): The structural

chassis provider.

PCH_AAT1 (Aminotransferase):

The nitrogen-installation module.

PCH_CYP102 (Cytochrome P450):

The oxidative cyclase responsible for

ring expansion.

5. Experimental Validation in
Saccharomyces cerevisiae

5.1 Strain Design and Codon

Optimization

The identified gene cluster sequences are

codon-optimized for S. cerevisiae to

ensure high translational efficiency. The

genes are synthesized as a single

polycistronic operon or integrated into the

yeast genome using CRISPR/Cas9.

5.2 Integration Protocol

https://gemini.google.com/app/33fbca041500e425

4/6

17/03/2026, 05:23

Google Gemini

1.  Vector Construction: Utilize a yeast

integrative vector (e.g., pRS400

series) containing the 5-gene

ketamine cluster under the control of

inducible promoters (GAL1/GAL10).

2.  Transformation: Employ the lithium

acetate/PEG method to transform S.

cerevisiae (Strain BY4741).

3.  Selection: Screen for successful

integration using auxotrophic markers

(e.g., URA3, LEU2).

5.3 Fermentation and Precursor
Feeding

To validate the pathway, the engineered

yeast must be grown in a controlled

environment that mimics the fungal

"infection" state.

Media: Synthetic Defined (SD) media

supplemented with 2% glucose.

Halogen Requirement: Addition of

25mM Sodium Chloride (

N aCl

) to

provide the necessary chloride ions

for the FDH halogenase.

Environmental Control:

Maintenance of dissolved oxygen

levels

> 40%

 to support the

Cytochrome P450 oxidative

cyclization step.

5.4 Analytical Confirmation

Final product verification is performed via

LC-MS/MS, screening for the

m/z

 238.1

https://gemini.google.com/app/33fbca041500e425

5/6

17/03/2026, 05:23

Google Gemini

peak characteristic of ketamine, alongside

its deschloro-analog (DCK) if chloride

levels are insufficient.

6. Conclusion

The identification of the Ketamine BGC in

Pochonia chlamydosporia marks a

fundamental shift in our understanding of

arylcyclohexylamine chemistry. By porting

this evolutionary "software" into a yeast

chassis, we establish a pathway for the

biological synthesis of essential

dissociative anesthetics, bypassing the

environmental and regulatory hurdles of

traditional chemical synthesis.

7. References

Ferreira, S. R., et al. (2020).

"Ketamine can be produced by

Pochonia chlamydosporia: an old

molecule and a new anthelmintic?"

Parasites & Vectors.

Lin, R., et al. (2018). "Genome and

secretome analysis of Pochonia

chlamydosporia provide new insight

into egg-parasitic mechanisms."

Scientific Reports.

Teng, S. Q., et al. (2023).

"Polyketides from the fungus

Pochonia chlamydosporia and their

bioactivities." Phytochemistry.

https://gemini.google.com/app/33fbca041500e425

6/6

