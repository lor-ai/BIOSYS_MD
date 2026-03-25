Article

https://doi.org/10.1038/s41467-025-58239-x

Structural basis for psilocybin biosynthesis

Received: 17 July 2024

Accepted: 17 March 2025

Check for updates

;
,
:
)
(

0
9
8
7
6
5
4
3
2
1

;
,
:
)
(

0
9
8
7
6
5
4
3
2
1

Chunyan Meng1,2,9, Wenting Guo1,9, Chuan Xiao1,9, Yan Wen1,3,9, Xudong Zhu1,
Qingrong Zhang4, Yuxuan Liang4, Hongwei Li1, Sha Xu 5, Yuntan Qiu 1,10
,
Haitao Chen 4,10

, Wei-Jye Lin 1,6,7,8,10 & Baixing Wu 1,2,10

Psilocybin shows signiﬁcant therapeutic potential for psilocybin-assisted psy-
chotherapy in addressing various psychiatric conditions. The biosynthetic
approach promises rapid and efﬁcient production of psilocybin. Understanding
the enzymes that contribute to the biosynthesis of psilocybin can enhance its
production process. In this study, we elucidate the crystal structures of L-
tryptophan-speciﬁc decarboxylase PsiD in both its apo and tryptamine-bound
states, the 4-hydroxytryptamine kinase PsiK bound to its substrate, and several
forms of the methyltransferase PsiM in either apo or substrate-bound forms
derived from the psychedelic mushroom. Structure-based evaluations reveal
the mechanisms of self-cleavage and self-inhibition in PsiD, along with the
sequential catalytic steps from 4-hydroxytryptamine to the ﬁnal compound,
psilocybin. Additionally, we showcase the antidepressant properties of bio-
synthetic intermediates of psilocybin on female mice experiencing depression-
like behaviors induced by sub-chronic variable stress. Our studies establish a
structural basis for the future biosynthetic production of psilocybin using these
enzymes and emphasize the clinical potential of norbaeocystin.

More than one billion people globally are believed to suffer from
mental disorders, such as depression, bipolar disorder, schizophrenia,
and others1. Over the past decade, the therapeutic potential of psy-
chedelics for treating these disorders has drawn considerable atten-
tion, with more than ten completed clinical trials, particularly in the
ﬁeld of psychiatry2. One of the serotonergic hallucinogens, psilocybin
(4-phosphoryloxy-N,N-dimethyltryptamine), has been proposed to
possess medical potential for drug-assisted psychotherapy in treating
psychiatric disorders3–10. Psilocybin is an indoleamine hallucinogen
and a secondary metabolite produced by hundreds of mushroom
species in the Psilocybe genus, which are distributed globally4,11–14. For
centuries, mushrooms have been used in religious ceremonies by

indigenous societies in South and Central America9,15. Psilocybin was
ﬁrst chemically characterized and crystallized from the dried Psilocybe
mexicana mushroom by Albert Hofmann, who subsequently eluci-
dated the structure and method of chemical
synthesis of
psilocybin4,11,12. When digested by humans, psilocybin is rapidly
dephosphorylated to the main pharmacologically active substance,
psilocin (4-hydroxy-N, N-dimethyltryptamine), by alkaline phospha-
tase in the liver3,16 and nonspeciﬁc esterase in the intestinal
mucosa17. Psilocin serves as a ligand and partial agonist of the
5-hydroxytryptamine (5-HT) receptors in humans, thereby profoundly
impacting human perception and consciousness4,18,19. Psilocin’s ago-
nist activity at the 5-HT2A receptor is generally considered necessary

1Guangdong Provincial Key Laboratory of Malignant Tumor Epigenetics and Gene Regulation, Guangdong-Hong Kong Joint Laboratory for RNA Medicine,
Medical Research Center, Sun Yat-Sen Memorial Hospital, Sun Yat-Sen University, Guangzhou, China. 2Institute of Drug Discovery, Guangzhou Institutes of
Biomedicine and Health (GIBH), Chinese Academy of Sciences (CAS), Guangzhou, China. 3Breast Tumor Center, Sun Yat-Sen Memorial Hospital, Sun Yat-Sen
University, Guangzhou, China. 4School of Public Health (Shenzhen), Sun Yat-Sen University, Shenzhen, China. 5State Key Laboratory of Oncology in South
China, Guangdong Provincial Clinical Research Center for Cancer, Sun Yat-Sen University Cancer Center, Guangzhou, China. 6Brain Research Center, Sun
Yat-Sen Memorial Hospital, Sun Yat-Sen University, Guangzhou, China. 7Nanhai Translational Innovation Center of Precision Immunology, Sun Yat-Sen
Memorial Hospital, Foshan, China. 8Guangdong Provincial Key Laboratory of Brain Function and Disease, Zhongshan School of Medicine, Sun Yat-Sen
University, Guangzhou, China. 9These authors contributed equally: Chunyan Meng, Wenting Guo, Chuan Xiao, Yan Wen. 10These authors jointly supervised
e-mail: qiuyt8@mail2.sysu.edu.cn; chenht56@mail.sysu.edu.cn; linwj26@mail.sysu.edu.cn;
this work: Yuntan Qiu, Haitao Chen, Wei-Jye Lin, Baixing Wu.
wu_baixing@gibh.ac.cn

Nature Communications |

 (2025) 16:2827

1

Article

https://doi.org/10.1038/s41467-025-58239-x

for psychedelic activity to produce a “mystical-like” hallucinatory
effect due to induced frontal hyper-frontality20, which in turn mediates
its antidepressant and anti-anxiety effects21.

1a). Characterization of

The increasing rate of global mood and anxiety disorders and
the therapeutic potential will spur the demand for psilocybin. How-
ever, the extraction of psilocybin from naturally growing or culti-
vated mushrooms is not economically viable for drug research and
development17. Therefore, chemical methods for synthesizing psilo-
cybin have been developed to improve the yield of psilocybin to
kilogram-scale with single (or few) dose regimes22,23. Alternatively,
psilocybin could also be produced through synthetic biological
methods based on the inspiring work that identiﬁed the genes
encoding the enzymes for psilocybin biosynthesis in Psilocybe and
other genera24,25. The metabolic pathway was shown to involve the
activity of four enzymes, including PsiD, PsiH, PsiK, and PsiM22,24,26
these enzymes conﬁrmed that
(Fig.
L-tryptophan acts as the raw material in the biosynthetic pathway.
PsiD functions as the decarboxylase that catalyzes L-tryptophan into
tryptamine, which can subsequently be catalyzed by the indole-4-
monooxygenase PsiH to produce 4-hydroxytryptamine. Meanwhile,
it has also been validated that PsiD could directly convert 4-hydroxy-
L-tryptophan to 4-hydroxytryptamine24. Following these processes,
another critical enzyme, PsiK, further catalyzes 4-hydroxytryptamine
to norbaeocystin by adding a phosphate group to the 4-hydroxyl
position of 4-hydroxytryptamine using the co-substrate ATP24. The
terminal amino group of norbaeocystin will be methylated by the
PsiM protein to form baeocystin and psilocybin, step by step, using
the cofactor S-adenosylmethionine (SAM)24. Per the elucidation of
the biosynthesis pathway24, bioengineering has led to the production
of psilocybin in the ﬁlamentous fungi Aspergillus nidulans27, Escher-
ichia coli28, and Saccharomyces cerevisiae29. Studies have also repor-
ted a scalable hybrid synthetic/biocatalytic route to produce
psilocybin by replacing the phosphorylation step with the PsiK
kinase22 and a biocatalytic route to synthesize 6-methyl-norbaeocy-
sin, 6-methyl-baeocysin, and 6-methyl-psilocybin from 4-hydroxy-6-
methyl-L-tryptophan. In that study, the recombinantly expressed
PsiD, PsiK, and PsiM enzymes were used to achieve the processing
steps26. However, although these enzymes have been biochemically
characterized according to the in-silico models22,26,30, the experi-
mental structures of these enzymes are still valuable in promoting
the development of engineering more productive pathways for psi-
locybin biosynthesis.

Here, we ﬁrst determine the structures of PsiD in its apo and
substrate-bound forms. Based on the structural analysis, we propose
potential mechanisms for the self-cleavage and decarboxylation reac-
tions of PsiD. Additionally, we uncover the self-inhibition mechanism
of the PsiD proenzyme and demonstrate that deleting the N-terminal
region signiﬁcantly increases its decarboxylase activity. Next, we solve
the structure of PsiK in complex with the cofactors and tryptamine
substrate. We uncover the cofactors and substrate-binding properties
of PsiK and identify the key residues for the phosphorylation reaction.
We then determine the structures of PsiM in its apo- and different
substrate-bound forms, revealing its stepwise methylation mechanism.
Finally, we evaluate the biological effects of the intermediate products
of psilocybin in sub-chronic variable stress-induced depression-like
behaviors in mice. Our structural and biochemical characterization of
the enzymes involved in psilocybin biosynthesis, combined with the
behavioral experiments, will shed light on optimizing the synthetic
biological methods for psilocybin production and the combined
administration of psilocybin with the other intermediate products.

Results
The PsiD proenzyme undergoes self-cleavage
To uncover the catalytic mechanism of PsiD, we expressed the full-
length PsiD (1–439) protein from Psilocybe cubensis and determined

its crystal structure using the molecular replacement method with
the model predicted by AlphaFold2 (Fig. 1b, Supplementary Table 1,
Supplementary Fig. 1a)24,31. There are six PsiD molecules in the
asymmetric unit that have similar conformations, with an RMSD of
about 0.2–0.3 Å over equivalent backbone atoms (Supplementary
Fig. 1b). However, the density of the N-terminal ~53–57 residues could
not be modeled in all these molecules (Supplementary Fig. 1a–h);
therefore, we selected one of the PsiD molecules containing residues
53–438 (hereafter named apo-PsiD) for further analysis (Supple-
mentary Fig. 1c).

Consistent with previous observations in studies of the E. coli
phosphatidylserine decarboxylases (PSDs)32–34, which indicate that the
proenzyme undergoes a self-cleavage reaction and can be divided at a
conserved “LGST” motif by a canonical serine protease mechanism35,36,
the PsiD enzyme exhibited self-cleavage between a “GGSS” (G401-
G402-S403-S404) motif, leaving a pyruvoyl prosthetic group within
the N-terminal of the α-chain, which was then named Pvl403, and a β-
chain containing a Gly402 terminus (Fig. 1c, d). The production of the
active Pvl403 group was conﬁrmed by our mass spectra results (Sup-
plementary Fig. 2a). The self-cleavage reaction mechanism of the PsiD
protein can be deduced from previous studies of the PSDs, the bio-
chemical characterization and the in-silico modeling structure of
P. cubensis PsiD30,34. Firstly, the peptide bond between Gly402 and
Ser403 undergoes serinolysis attacked by the side chain hydroxyl
group of Ser403, forming an ester bond between the two amino acids.
Then, an α, β-elimination reaction will break the linkage between the
two residues, and the β-subunit will be released, leaving a dehy-
droalanine at the N-terminus of the α-subunit; a water molecule will
further attack the double bond of the dehydroalanine intermediate to
yield the α-hydroxyl alanyl residue, which will subsequently form the
mature pyruvoyl moiety by releasing ammonia34,37,38 (Fig. 1e).

The overall structure of PsiD
The α and β chains of each PsiD protomer in the asymmetric unit
form a globular fold that consists of 16 α-helices and 13 β-strands
(Fig. 1d, Supplementary Fig. 2b). The Gly402 at the C-terminus of the
β chain is positioned ~11 Å away from the pyruvoyl group, as pre-
dicted by the published AlphaFold2 model (Fig. 1f)30. This con-
formational change results in the exposure of the pyruvoyl group for
further catalytic reactions. The putative active site is surrounded by
four structural elements mainly composed of hydrophobic residues,
including the Loop 1 region (aa. 108–120), the Loop 2 region (aa.
290–297), the Loop 3 region (aa. 324–341), and the Loop 4 region (aa.
371–377) (Fig. 1g, h).

Further analysis revealed that the PsiD molecules might form a
homodimer that adopts central symmetry with an extensive dimer
interface (Supplementary Fig. 3a). Half of the dimer interface was then
selected to show these contacts (Supplementary Fig. 3b). The Asp251,
Glu281, Gln253, Ser254, Lys261, and Asp256 from one molecule formed
various hydrogen bonds with Asp71, Arg137, Arg135, Gln136, Asn139,
and Thr134 from another molecule, either directly or mediated by
water molecules. Meanwhile, Thr257, Val259, and Phe260 from one
molecule had hydrophobic contacts with Thr134, Ile348, Phe130,
Pro321, and Tyr344 from another molecule. The residues involved in
dimer formation are all located within the β-chain (Supplementary
Fig. 3c). Following our observations, Arg135 and Gln136 were mutated
(R135A/Q136A) to assess the in-solution status of PsiD through gel ﬁl-
tration, with wildtype PsiD and S403A serving as controls (Supple-
mentary Fig. 3d). However, our evaluation indicated that both wildtype
PsiD and the PsiD mutants predominantly exist as monomers, with
only a minor fraction displaying the homodimer form. Additionally,
the R135A/Q136A mutation did not signiﬁcantly alter the in-solution
status of PsiD. These results suggested that the PsiD protein mainly
exists as a monomer in the solution state, while some also form a
homodimer state.

Nature Communications |

 (2025) 16:2827

2

Article

https://doi.org/10.1038/s41467-025-58239-x

OH

O

HO

P

O

norbaeocystin

NH2

N
H
SAM

SAH

PsiM

OH

O

HO

P

O

N
H

baeocystin

CH3

N
H

a

O

OH

L-tryptophan

tryptamine

NH2

PsiD

-CO
2

O

OH

NH2

PsiD

-CO
2

N
H

N
H

OH

NH2

N
H

PsiH

[O]

OH

NH2

PsiK

N
H

ATP

ADP

4-hydroxy-L-tryptophan

4-hydroxytryptamine

OH

O

HO

P

O

OH

CH3

N

H3C

?

b

N
H

psilocin

O

OH

L-tryptophan

tryptamine

CH3

PsiM

N

H3C

SAH

SAM

N
H

psilocybin
c

Proenzyme

NH2

PsiD

-CO2

N
H

β-chain

α7

α8

α10

α11

α9

β4

N
H

NH2

1

e

β-chain

H2O

NH3

C

O

O

C

H
N

R
Ser403

R

N
H

Gly402
R

O

C

HO

N
H

CH2

CH

C
H2

O

C

R

C
H2

H2
C

H

C

O

α6

α4

β10

β12

Pvl403
β8

S404

β7

β1
β13

β9

α16

C

β6

β5

α15

α2

α5

α14

α12

β2

β11
β3

α13

α-chain

N

α3

α1

d

f

1

Gly401-Gly402-S403-S404

439

Self-cleavage site

O-

O

+

Gly402

O

O

Pvl403

Mature β-chain

439

α-chain

Gly402

O

R

C

C
H2

H2C

C

O-

O

C

R

N
H

R

N
H

+

NH3

Mature α-chain

Pvl403

O

C

CH3

O

C

N
H

H2O

R

+

NH4

H3C

+
NH3

O

C

OH

C

+
NH3

g

h

β10

Loop2(290-297)

Loop3(324-341)

Gly402

β8

Pvl403

~11 Å

β7

Ser404

Pvl403

Loop4 (371-377)

Loop1 (108-120)

Substrate
Substrate
pocket
pocket

Pvl403

Fig. 1 | Structure of L-tryptophan decarboxylase PsiD. a Enzymatic synthesis
pathway of psilocybin in P. cubensis. The reaction scheme was redrawn from a
previous study24. b Schematic representation of the catabolic substrate and pro-
duct of the PsiD protein. c The schematic depicts the self-cleavage mechanism of
PsiD from the proenzyme to the mature enzyme. d The overall structure of the PsiD
protein. The α-chain is colored cyan, and the β-chain is colored green. The pyruvoyl
group is shown as sticks. e The potential reaction scheme for the self-cleavage of

the PsiD proenzyme. f The distance between the C-terminal of the β-chain Gly402
and the N-terminal Pvl403 of the α-chain after self-cleavage. The residues G402 and
Pvl403 are shown as sticks. The |Fo|-|Fc| map is contoured at 3.0 σ (colored blue).
g The four loop regions responsible for pocket formation are colored yellow, blue,
cyan, and purple, respectively. h The electrostatic surface representation of the
substrate-binding pocket. The pocket region containing Pvl403 is indicated by a
blue circle.

Nature Communications |

 (2025) 16:2827

3

Article

https://doi.org/10.1038/s41467-025-58239-x

Structure of the Schiff-base intermediate of PsiD with
L-tryptophan
To further investigate substrate recognition and the catalytic
mechanism, we determined the structure of PsiD complexed with the
substrate L-tryptophan through co-crystallization (Supplementary
Table 1). Hereafter, we refer to this structure as PsiD-Trp. There are also
six PsiD molecules in the crystallographic asymmetric unit, showing
minor differences (Supplementary Fig. 4a–g). Thus, we selected one of
them to compare with the apo-PsiD structure (Fig. 2a, Supplementary
Fig. 4b). Structural comparisons between the PsiD-Trp complex and
the apo-PsiD revealed no signiﬁcant conformational changes in the
PsiD structure upon substrate binding, as demonstrated by the RMSD
of about 0.24 Å between these two structures over equivalent back-
bone atoms (Fig. 2a).

In accordance with previous observations that the pyruvoyl
prosthetic group forms a Schiff-base intermediate with the primary
amine of the substrate during catalysis32–34, the Schiff-base inter-
mediate between Pvl403 and the amino group of L-tryptophan was
captured in our PsiD-Trp structure (Fig. 2b). Meanwhile, the carboxyl
group of L-tryptophan could not be modeled, indicating that the
structure of PsiD in complex with L-tryptophan presents a covalently
bound intermediate state with tryptamine. In this structure of the PsiD-
Trp complex, the methyl group of Pvl403 was hydrophobically
anchored by the side chains of Phe398, His296, and Leu290. The
covalent amide was hydrogen-bonded to the main chain of Leu290.
The only hydrophilic group in the indole ring of tryptamine forms
hydrogen bonds with the side chain of Thr374 and the main chain of
Met373. The indole ring was enclosed by Phe289, Val292, Leu339,
Leu112, Tyr338, Tyr117, Pro114, Met373, Thr374, and Ile376, thereby
stabilizing the intermediate product (Fig. 2b, c). These residues were
almost all within the pocket-composing loops (Fig. 2d). Structure
superposition suggested minor deviations in the catalytic pocket
between the apo-PsiD and the PsiD-Trp complex. Only two residues
had slight conformational differences between these structures:
His296 and Val292, which are closer to the indole ring when PsiD binds
to the intermediate product (Fig. 2e).

Decarboxylase activity assay
To examine the functional roles of the residues involved in substrate
binding, we made several PsiD mutants and measured their dec-
arboxylase activities using the thin-layer chromatography (TLC)
method. Before doing that, we ﬁrst tested the catalytic activity of the
wildtype PsiD using a TLC experiment and validated the catalytic
product through mass spectrometry analysis (Fig. 2f, g, Supple-
mentary Fig. 5a). Based on these results, we then performed the TLC
assays to test the activity of the PsiD mutants (Fig. 2h, i, Supple-
mentary Fig. 5b). In vitro decarboxylation activity assays revealed
that the L112A and F289A mutations did not decrease the dec-
arboxylase activity of PsiD but enhanced its catalytic activity. These
observations may be attributed to weak hydrophobic interactions
with the substrate; in contrast, Y117A reduced the activity. On the
other hand, L290A almost completely lost its decarboxylase activity
for L-tryptophan, indicating the key role of Leu290 in producing and
stabilizing the pyruvoyl group. The Tyr338, necessary for hydro-
phobic contact with the substrate, also shows slightly increased
activity when mutated to alanine. The Thr374, which forms a
hydrogen bond with the L-tryptophan molecule, did not dramatically
impact the catalytic ability of PsiD; as a negative control, the mutants
of His296 and Ser403, which are indicated to be essential for the self-
and
cleavage
L-tryptophan decarboxylase activity when replaced with alanine
(H296A and S403A) (Fig. 2g–j, Supplementary Fig. 5b), while the
Gly402 mutant (G402A), located at the terminus of the β-chain and
not involved in covalent bond formation, showed similar activity to
the wildtype did (Fig. 2g–j,
the L-tryptophan substrate as

reactions30,39,

self-cleavage

abolished

both

Supplementary Fig. 5b). The results mentioned above validated the
roles of the residues we identiﬁed in the catalytic pocket for dec-
arboxylase activity. Unfortunately, although we tried to purify the
other mutations involved in substrate binding and pyruvoyl group
formation, such as F398A, M373A, and P114G, these mutants were not
stable enough to be puriﬁed.

The N-terminal of PsiD revealed a self-inhibition mechanism
Based on the above enzymatic assays, a confusing observation was
that the wildtype PsiD protein exhibited insufﬁcient catalytic activity
toward the substrate, leaving a certain amount of L-tryptophan not
fully reacted (Fig. 2f, Supplementary Fig. 5a, c). To ﬁgure out why the
recombinant full-length PsiD did not have strong enough activity, we
performed the decarboxylase assay using TLC methods with gradient
pH values (Tris pH 7.4-9.0) according to our protein puriﬁcation and
crystallization conditions. However, the different pH values showed a
minor impact on the catalytic activity of the PsiD protein under our
experimental conditions (Supplementary Fig. 5d). In contrast, pre-
vious studies suggested that the optimal condition for PsiD activity
occurred in sodium phosphate buffer (pH 6.6) and between 33 and
36 °C30. These distinctions may explain the capture of the covalent-
bound tryptamine product state in our structure of the PsiD-Trp
complex.

To explore whether other factors exist that cause the insufﬁcient
catalytic activity of PsiD, we reanalyzed its N-terminal region (aa. 1–55),
which remained invisible in both the structures of apo-PsiD and the
PsiD-Trp complex. A structure superposition between the AlphaFold2-
predicted full-length PsiD and our PsiD-Trp structures showed that the
N-terminal region might not impact the dimerization of the PsiD pro-
tein (Supplementary Fig. 6a, b). However, the N-terminal region con-
tains three alpha-helices that lie on the surface of the solved part of the
PsiD structure. Moreover, the ﬁrst helix covers the substrate-binding
pocket of PsiD, with a tryptophan (Trp27) residue inserted into the
substrate-binding pocket, sharing the same set of residues for sub-
strate recognition (Fig. 3a, b). These analyses strongly suggest a cryptic
self-inhibition mechanism in the PsiD protein that inhibits the
enzyme’s activity. Therefore, we chose to construct two additional
truncations, PsiD (aa. 50–439) and PsiD (aa. 30–439), as well as a W27A
mutant of the full-length PsiD to test their catalytic activity. The S403A
was selected as a negative control (Fig. 3c–f, Supplementary Fig. 7a–e).
The TLC results revealed that the PsiD (1–439) W27A mutant, as well as
the PsiD (30–439), showed signiﬁcantly higher catalytic activities for
the L-tryptophan substrate than the wildtype PsiD enzyme (Fig. 3c–e,
Supplementary Fig. 7a–c). Furthermore, deleting the N-terminal 50
residues dramatically increased the catalytic activity of the PsiD pro-
tein for the L-tryptophan substrate (Fig. 3c, f, Supplementary Fig. 7d).
Incubating these different constructs with L-tryptophan also validated
these results; all the L-tryptophan substrate was converted to trypta-
mine in PsiD (1–439) W27A, PsiD (30–439), and PsiD (50–439), but not
in the wildtype PsiD under the same conditions (Fig. 3g, Supplemen-
tary Fig. 7f, g). Accordingly, none of these truncations or the W27A
impact the self-cleavage activity of PsiD (Fig. 3h).

We then co-crystallized PsiD (50–439) with L-tryptophan and
successfully obtained the structure at a high resolution of 1.6 Å
(Supplementary Table 1, Supplementary Fig. 8a). Structural com-
parison of the PsiD (50–439)-Trp complex revealed no signiﬁcant
differences from the PsiD-Trp complex (Supplementary Fig. 8b).
However, in contrast to the tryptamine in the latter complex, which is
presented in a covalently bound state, the former complex shows a
pre-release state when superimposing the catalytic centers of these
two structures (Fig. 3i, j). These results demonstrate that the PsiD
enzyme has a self-inhibition mechanism through its N-terminal
region, particularly the Trp27 residue, thereby regulating its activity.
Deleting the N-terminal region will dramatically improve decarbox-
ylation efﬁciency.

Nature Communications |

 (2025) 16:2827

4

Article

https://doi.org/10.1038/s41467-025-58239-x

a

N

f

h

PsiD-Trp
apo-PsiD

b

c

L290

H296

V292

F289

Trapped
tryptamine

Ser404

Val292

Ile376

Trapped
tryptamine

RMSD=0.243 Å

d

Loop2

L290L290

Loop3

H296H296

F398F398

I376
I376

F289F289

V292V292

L339L339

P114P114

L112L112

Y338Y338

M373M373

T374T374

Y117Y117

Loop4

Loop1

L-tryptophan

WT-PsiD(μM)

20 30 40 50 60 70 80 90 100

4

9
5
678

P114
Y338

L339

L112

Y117

Leu290

Tyr338

Phe398

F398

C

I376

M373

2

1

3

T374

e

H296H296

Loop2

L290L290

F289F289

Thr374

V292V292

L339L339

F398F398

I376
I376

M373M373

Loop4

T374T374

Loop1

L112L112

P114P114
Y338Y338

Loop3

Y117Y117

L-tryptophan

**

tryptamine

*

g

Control

WT-PsiD

50-439

G402A

S403A

3.1

Phe289

His296

Trapped
tryptamine

Leu339

Leu112

Tyr117

2.9

3.1

Pro114

Met373

i

j

)

%
(
y
t
i
v
i
t
c
a
e
v
i
t
a
e
R

l

200

150

100

50

0

Wildtype

L112A

Y117A

F289A

L290A

H296A

Y338A

T374A

G402A

S403A

PsiD mutants

PsiD mutants

WT-PsiD
L112A

Y117A

F289A

L290A

M(kDa)

WT-PsiD
H296A

Y338A

T374A

G402A

S403A

M(kDa)

tryptamine

2

3

PsiD mutants

L-tryptophan
WT-PsiD
L112A

Y117A

F289A

L290A

H296A

Y338A

T374A

G402A

S403A

Control

205.10
**

4
t/min

5

6

*

161.11

WT-PsiD

150 170 190 210

150 170 190 210

m/z

m/z

G402A

161.11

*

S403A

205.10
**

tryptamine

150 170 190 210

150 170 190 210

m/z

m/z

α-chain

40
25

15

8
4.2
2.7

Fig. 2 | The substrate-binding properties of PsiD. a Structural superposition of
the apo-PsiD protein and the PsiD-Trp complex. The trapped tryptamine is shown
as sticks. b The substrate-binding status of the covalently bonded tryptamine by the
pyruvoyl group of the PsiD α-chain. The |Fo|-|Fc| map is contoured at 3.0 σ (colored
blue). c A LIGPLOT diagram listing critical contacts between tryptamine and the
PsiD protein. d Surface representation of the pocket composed of the four loop
regions enclosing the substrate. e The conformational changes of the two residues,
His296 and Val292, between the apo-PsiD and substrate-binding statuses are indi-
cated by red circles. f TLC experiment for testing the product of the decarbox-
ylation reaction of PsiD to L-tryptophan. g Chromatographic analysis of activity

assays to detect tryptamine formation by wildtype PsiD, G402A, and S403A. Con-
trol: chromatograms of the L-tryptophan reference with heat-inactivated PsiD
protein. *: tryptamine; **: L-tryptophan. h The TLC results for testing the product of
the decarboxylation reaction of PsiD mutants to L-tryptophan. All the TLC experi-
ments are independently repeated three times. i Quantitative analysis of the TLC
results for testing the product of the decarboxylation reaction of PsiD mutants to
L-tryptophan. All data are presented as mean ± SEM. j SDS-PAGE results for deter-
mining the self-cleavage status of wildtype or mutated PsiD proteins. The experi-
ments are independently repeated at least three times.

The working model and reaction scheme of PsiD
Searching for the structural homolog of PsiD using the Dali online
server identiﬁed only one homologous protein, PSD, from E. coli40.
Therefore, we compared the structures of EcPSD and PsiD to elucidate
their distinctions and similarities in substrate recognition. The detailed
descriptions of the comparison results are provided in Supplementary

Note 1 (Supplementary Figs. 9 and 10). Drawing from our structural
studies, functional assays, and biochemical characterization from
earlier research30, along with the reaction scheme of EcPSD38, we
proposed a working model and catalytic mechanism for the bio-
synthesis of tryptamine catalyzed by PsiD (Fig. 3k): (a) In the catalyti-
cally inactive state, the N-terminus of PsiD covers the surface region

Nature Communications |

 (2025) 16:2827

5

Article

https://doi.org/10.1038/s41467-025-58239-x

a
PsiD-Trp(Chain AB)
AlphaFold model

b

Y117

L112

c

α2

α1

α3

N-ter (aa. 1-55)
N-ter (aa. 1-55)

T374

Y338

M373

I376

P114

L339

W27W27

V292

F398

Pvl403

F289

L290

d

L-tryptophan

0.5

min

1.0

2.0

4.0

WT-PsiD (1-439)
6.0
8.0

10 12 14

e

L-tryptophan

0.5

1.0

min

WT-PsiD (1-439) W27A
4.0
8.0

6.0

10 12 14

2.0

)

%

(
d
l
e
i
Y

t
c
u
d
o
r
P

100

50

0

0

WT-PsiD

PsiD(1-439)W27A

PsiD(30-439)

PsiD(50-439)

5

Time(min)

10

15

f

L-tryptophan

0.5

1.0

min

WT-PsiD (50-439)
8.0
4.0

6.0

10 12 14

2.0

tryptamine

g

h

i

L-tryptophan

PsiD(1-439)

PsiD(50-439)

PsiD(1-439)W27A
PsiD(30-439)

PsiD(1-439)W27A
PsiD(30-439)

M(kDa)

PsiD(50-439)

PsiD(1-439)

40

25

15

8

4.2
2.7

tryptamine

α-chain

k

a)
Self-inhibited state

PsiD

H
N

CHCH

CHCH2

Self-cleavage

b)
Self-inhibited state

Proenzyme

c)
Substrate-triggered
conformational change

O

O-

CHCH

L-tryptophan

α-chain

H2N

Pvl403

H
N

O

C

CHCH3

CHCH

CHCH2

CHCH2

N
H

Subtrate enter

Gly402

β-chain

Enzyme
Regeneration

α-chain

O

O-

Pvl403

O

H2N

CHCH

CHCH2

C

CHCH3

N
H

Gly402

β-chain

Decarboxylation

H2
C

CHCH2

+H3N

tryptamine

N
H

Product release

α-chain

Pvl403
O-

C

C

H3C

N
H
+

H
C

CHCH2

d)

α-chain

Pvl403

O

C

CHCH3

Gly402

β-chain

Product release

NH

2

CHCH
CHCH

Gly402

N
H

β-chain

Trapped tryptamine
state

tryptamine

tryptamine

L290

F289

V292

Pvl403

H296

L112

2.7

tryptamine

j

PsiD(50-439)-Trp
PsiD(50-439)-
PsiD-Trp
PsiD-Trp

Trapped
tryptamine

2.7

I376

P114

Pvl403

Release

F398

M373

3.3

2.9

Y117

tryptamine

Y338

T374

O

O-

CH

H2N

CH2

N
H

i)

O

C

R

N
H

O

C

CH3

R

HN

C

H2O

H3C

R

HN

C

H3C

H2
C

CH2

+H3N

R

H2O

HN

C

iv)

H3C

O

C

O-

C

O

C

O

N
H
+

N
H
+

N
H
+

O-

CH

CH2

N
H

ii)

CO2

H
C

CH2

N
H

H2
C

CH2

H+

iii)

N
H

N
H

NH

2

CHCH
CHCH

NH

2

CHCH
CHCH

above the catalytic pocket with Trp27 inserted, leading to the self-
inhibition of the PsiD enzyme; (b) Then, the PsiD proenzyme under-
goes self-cleavage between Gly402 and Ser403, producing the mature
enzyme with a catalytically active pyruvoyl prosthetic group (Pvl403)
at the N-terminal of the α-chain; (c) During the catalytic process, the
L-tryptophan substrate triggers conformational changes in the N-
terminal, at least competing with the Trp27 residue to enter the

catalytic center. The detailed catalytic reaction scheme can be
deduced from the PSDs34,38: (i) First, the hydrophobic indole ring of
L-tryptophan is attracted into the pocket and binds to the active site
via a Schiff-base formed between the primary amine of L-tryptophan
and the α-carbonyl carbon of Pvl403; (ii) The electron rearrangement
favors decarboxylation, and the formation of an azomethine inter-
mediate; (iii) Subsequent protonation generates another intermediate

Nature Communications |

 (2025) 16:2827

6

Article

https://doi.org/10.1038/s41467-025-58239-x

Fig. 3 | The self-inhibition mechanism of PsiD. a Electrostatic surface repre-
sentation of the PsiD-Trp structure overlaid with the AlphaFold2-predicted PsiD
model. b Comparison of the substrate-binding states of the PsiD-Trp and the
N-terminal inhibited state of the predicted PsiD model. c Quantitative results of the
TLC experiment testing the catalytic activity of wildtype PsiD, PsiD (1–439) W27A,
PsiD (30–439), and PsiD (50–439). All data are presented as mean ± SEM. All the TLC
experiments are independently repeated three times. d–g The TLC experiment
results for testing the catalytic activity of wildtype PsiD, PsiD (1–439) W27A, PsiD
(30–439), and PsiD (50–439). h The SDS-PAGE results for determining the self-

cleavage status of wildtype PsiD, PsiD (50–439), PsiD (30–439), and PsiD (1–439)
W27A proteins. The results are independently repeated at least three times. i The
tryptamine-bound state of the PsiD (50–439)-Trp complex. Tryptamine is colored
purple, and the Pvl403 group is colored cyan. The |Fo|-|Fc| map is contoured at 3.0 σ
(colored blue and purple). j The comparison of the covalently bound and pre-
release states of the tryptamine substrate in the structures of PsiD-Trp and PsiD
(50–439)-Trp complexes. The trapped tryptamine is colored yellow, and the pre-
released tryptamine is colored purple. k The proposed reaction scheme of the PsiD
enzyme.

product in Schiff-base linkage with the enzyme; (iv) The addition of a
water molecule across the Schiff-base regenerates the pyruvoyl pros-
thetic group and liberates tryptamine from the active site; (d) Finally,
the enzyme may regenerate to catalyze a new round of reactions.

The overall structure of PsiK
Next, to uncover the phosphorylation mechanism of PsiK, we solved
the structure of the PsiK complex with the cofactor ADP and trypta-
mine, which were used to capture the substrate-bound state of PsiK
(Fig. 1a, Supplementary Table 1)24. In addition, two Mg2+ ions derived
from the crystallization conditions were observed alongside the
phosphate groups of the ADP molecule (Fig. 4a). The PsiK molecule
contains a β-strand-rich smaller N-lobe (aa. 1–118) and a larger helix-
rich C-lobe (aa. 126–362), with a total of nine β-strands and twelve α-
helices (Fig. 4a). The cofactor ADP and the substrate were located in a
long cleft beneath the N-lobe, with two metal ions situated between
the cofactor and substrate (Fig. 4b).

Searching the structure of homologous proteins of PsiK revealed
that the PsiK enzyme structurally resembles protein kinase-like
phosphotransferases40, especially the 5-Methylthioribose (MTR)
kinases from A. thaliana and B. subtilis, with Z-scores of 32.4 and 31.3,
, respectively41,42 (Supplemen-
and Cα RMSD values of 2.8 A
and 3.1 A
tary Fig. 11a, b). Nevertheless, PsiK shares only ~16% sequence identity
with these two MTR kinases. Previous studies have uncovered four
loop regions in these MTR kinases that play critical roles in ADP
binding, divalent cation chelation, and substrate recognition,
including a glycine-rich loop (G-loop) between β1 and β2, an HGD
catalytic loop, an Mg2+ binding DXE motif, and a semi-conserved W-
loop41,42 (Supplementary Fig. 12). In our PsiK structure, there are four
loop regions and a linker that correspond to these regions in the MTR
kinases, playing a role in substrate and cofactor binding (Fig. 4c).
Based on these analyses, we further inspected the cofactor binding,
divalent cation chelation, and substrate recognition properties of the
PsiK protein.

Cofactor binding and substrate recognition properties of PsiK
During the phosphorylation process, the co-substrate ATP donates the
γ-phosphate group to the substrate and produces the ADP molecule.
The ADP molecule in our structural complex is clamped in a cleft
between two β-sheet regions composed of β1-β5 and β7-β8 from the
two lobes of PsiK (Fig. 4d). The adenine ring of the ADP points to the
linker region and resides in a relatively hydrophobic area. The N1 and
N6 nitrogen atoms of the ADP are hydrogen-bonded to the amide
nitrogen of Val120 and the main-chain carbonyl of Gln118, respectively
(Fig. 4d). The N3 position of adenine forms hydrogen bonds with Arg41
via a water molecule. In addition to these hydrogen interactions, the
ADP base is enclosed by several hydrophobic residues, including
Val120, Leu231, Pro103, Leu248, Met117, Leu31, and Ile55. The con-
served Lys57 residue interacts with the α- and β-phosphoryl groups of
ADP, and the main chain of Gly228 contacts both the α-phosphoryl
group and the O3’ position of the ribose group of ADP (Fig. 4e, Sup-
plementary Fig. 12). Asn37 and Thr39 form hydrogen bonds to the β-
phosphoryl group to anchor and coordinate the ADP, either directly or
via a water molecule (Fig. 4e).

The two Mg2+ ions (M1 and M2), which assist in the binding of ADP
and are essential for kinase activity, were observed forming hexa-
coordination structures with water molecules, PsiK residues, and ADP
phosphoryl groups (Fig. 4e). The M1 ion hexa-coordinates with the
oxygen atoms of the α- and β-phosphoryl groups of ADP, the side
chains of Asp249 and Asn229, and two water molecules named w1 and
w2; M2 has a hexa-coordinate status with the side chains of Glu251 and
Asp249, the oxygen atom from the β-phosphoryl group of ADP, and
two water molecules named w3 and w4. Asp249 and Asp251 are part of
the strictly conserved “DXE” motif on the loop between strands β8 and
β9, while Asn229 is located in the Loop 3 region (Supplemen-
tary Fig. 12).

The tryptamine we used to capture the substrate-binding state is
stabilized by a channel full of hydrophobic residues, including Phe35,
Met63, Val36, Phe69, Ile71, Thr180, Leu252, Leu184, Trp316, and
Phe319 (Fig. 4f). Among them, two phenylalanine residues, Phe35 and
Phe319, adopt a bolt-like conformation to lock in the tryptamine
(Fig. 4f, g). The indole ring of tryptamine is inserted into the pocket
toward the Mg2+ ions, leaving the terminal amino group pointing
toward the pocket entry (Fig. 4f–h). The C4 position of the indole ring
of distance separated by two water
points to Asp224, with about 5 A
molecules, w5 and w6 (Fig. 4h). Modeling 4-hydroxytryptamine in the
pocket revealed that it is somewhat far from the catalytic active resi-
due Asp224 (Fig. 4i). Therefore, the captured tryptamine represents an
inactive state of the enzyme. We speculate that when the phosphor-
ylation reaction of PsiK occurs, the 4-hydroxytryptamine substrate
moves closer to Asp224 and occupies the position of w5.

We then compared the differences and similarities between the
PsiK protein and the plant MTK enzyme in cofactor binding, Mg2+
chelation, and substrate recognition to deduce the catalytic scheme of
PsiK (Supplementary Fig. 13a, b). The detailed description can be found
in Supplementary Note 2. The PsiK employs a general acid-base
mechanism to achieve the phosphorylation process (Fig. 4j): when the
substrate binds, Asp224 functions as a base, accepting a proton from
the substrate’s 4-hydroxyl group. This action initiates the in-line
nucleophilic attack of the negatively charged oxygen on the γ-phos-
phate, resulting in a transient complex. Subsequently, the substrate’s
4-hydroxyl group cleaves the γ-phosphate, which is stabilized by M2,
causing the intermediate to split into the phosphorylated products
and ADP. The product is then released from the catalytic center, while
ADP exhibits a lower afﬁnity for the binding pocket43.

Conformational changes of PsiM during the stepwise methyla-
tion reaction
To illustrate the methylation steps from norbaeocystin to psilocybin,
we have also solved six structures of PsiM alone and in various com-
plexes with SAH, SAM, SAH-norbaeocystin, SAH-baeocystin, and SAH-
psilocybin (Fig. 5a–f, Supplementary Figs. 14–19). However, our
structures align with the recently published ﬁndings44. Therefore,
detailed descriptions of our results are provided in Supplementary
Notes 3. Even so, our results provide a clearer picture of the sequential
conformational changes of PsiM during the methylation steps
(Fig. 5g, h): (i) In the apo state, the region between Pro185 and Gly222
was dynamic and unstable in the absence of the cofactor and substrate;

Nature Communications |

 (2025) 16:2827

7

̊
̊
̊

Article

https://doi.org/10.1038/s41467-025-58239-x

a

d

b

N

α1α1

β4β4

β5β5

β1β1

β2β2

β3β3

ADPADP

β7β7

β8β8

α3α3

η1η1

α4α4

α8α8

α9α9

C

α12α12

M1M1 M2M2

α2α2

tryptamine
tryptamine

η2η2

β6β6

α5α5

α6α6

β9β9

α10α10

α11α11

α7α7

e

UNK

β3β3

R41R41

I55I55

Q118Q118

V120V120

3.2

3.3

P103P103

3.0

2.8

L231L231
β8β8

β7β7

L248L248

G228G228

2.8

2.7

3.0

M1M1

M2M2

M117M117

L31L31

2.9

2.9

K57K57

β2β2

β5β5

β4β4

ADP binding site

F35F35

B
B
olt
olt

g

j

tryptamine
tryptamine

F319F319

ADPADP

M1M1 M2M2

tryptamine
tryptamine

c

f

α1α1

β1β1

β2β2

Loop1
Loop1
(aa. 31-36)
(aa. 31-36)

β4β4

β5β5

Loop2
Loop2
(aa. 60-72)
(aa. 60-72)

ADPADP

α2α2

M1M1 M2M2

tryptamine
tryptamine

α5α5

Linker
Linker
(aa. 119-125)
(aa. 119-125)

β3β3

Loop4
Loop4
(aa. 248-253)
(aa. 248-253)

β7β7

β8β8

α3α3

α4α4

Loop3
Loop3
(aa. 221-231)
(aa. 221-231)
α8α8

α9α9

β6β6

β9β9

α10α10

α6α6

α11α11

α7α7

α12α12

UNK

W316W316

T39T39

N37N37

β2β2

K57K57

F319F319

ADPADP

E251E251

F35F35

tryptamine
tryptamine

L184L184

M2M2

M1M1

D249D249

w4

w3

w2

D224D224

w1

N229N229

N37N37

β8β8

β7β7

h

ADPADP

E251E251

tryptamine
tryptamine

D249D249

M2M2

w4

w3

M1M1

w1

w2

N229N229

D224D224

w5

4

w6

M63M63

V36V36

L252L252

F69F69

T180T180

I71I71

N37N37

w1w1

E251E251

M1M1

M2M2

gamma
-P

w4w4
w2w2

w3w3

tryptamine
tryptamine

D224D224

w5w5

w6w6

Glu251

4-Hydroxy
4-Hydroxy
tryptamine
tryptamine

i

ADPADP

D249D249

N229N229

Glu251

Asn37

O-

-O

NH2

β

O

O

P

O-

α

O

O

P

O-

O-

O

O

γ

P

O-

O

w3

4-hydroxy
tryptamine

H
N

OH

HO

OH

w1

M1

w2

M2

O-

O-

-O

O-

Asp224

-O

NH2

Asp249

O

ATP

PsiK

-O

norbaeocystin

ATP

ADP

NH2

ATP

O

Asn37

O-

O-

O

NH2

β

O

O

P

O-

w4

α

O

O

P

O-

HO

OH

w1

M1

w2
-O

-O

NH2

H
N

OH

HO

O

P

O

w3

w5

w6

NH2

M2

O-

O-

O-

Asp224

Asp249

Asn229

Asn229

(ii) When SAM entered the cofactor binding site, Arg75 and Leu68
changed their conformations to stabilize SAM along with other resi-
dues. The region between Ala199 and Ser211 remained ﬂexible without
the substrate, while the regions of Pro185-Ala198 and Gly212-Gly222
were observed in the presence of the cofactor; (iii) When norbaeo-
cystin entered, Arg281 rotated to a new conformation to anchor the
phosphate group of norbaeocystin; the terminal amine group of

norbaeocystin pointed toward the methyl group of SAM, and the
methylation reaction occurred; (iv) With the ﬁrst catalytic step ﬁn-
ished, baeocystin would slightly shift along the indole ring and away
from the cofactor. Then, the methyl group of baeocystin rotates in the
other direction, leaving the amine group toward the cofactor; (v) The
new cofactor SAM transfers the methyl group to the baeocystin, pro-
ducing psilocybin, which will further shift along the indole ring to

Nature Communications |

 (2025) 16:2827

8

Article

https://doi.org/10.1038/s41467-025-58239-x

Fig. 4 | Structure of 4-hydroxytryptamine kinase PsiK. a The overall structure of
PsiK in complex with ADP and tryptamine. The ADP and tryptamine molecules are
colored yellow and pink, respectively, and shown as sticks. The two Mg2+ ions are
depicted as green spheres. b Surface representation of the PsiK enzyme. c The four
loop regions and the linker responsible for cofactor and substrate binding are
colored as follows: red (Loop 1: aa. 31–36), yellow (Loop 2: aa. 60–72), blue (Loop 3:
aa. 221–231), pink (Loop 4: aa. 248–253), and gray (linker: aa. 119–125), respectively.
d The ADP binding site. The ADP molecule is shown as a stick and colored yellow;
the residues involved in ADP binding are colored green and shown as sticks. The
water molecules and Mg2+ ions are depicted as red and green spheres. The |Fo|-|Fc|

map is contoured at 3.0 σ (colored blue). e The Mg2+ chelating site. The |Fo|-|Fc| map
is contoured at 3.0 σ (colored blue). f The substrate recognition site of PsiK. The
contours of tryptamine and the residues involved in substrate binding are colored
purple and green. The |Fo|-|Fc| map is contoured at 3.0 σ (colored blue and purple).
g The substrate-binding pocket is indicated by a yellow dashed circle. h The reac-
tion center of the PsiK enzyme. The catalytic active residue Asp22 is indicated by a
brown circle. i Modeling 4-hydroxytryptamine into the substrate-binding pocket.
The potential movement of the substrate is indicated by a red arrow. j The pro-
posed reaction scheme of the PsiK enzyme.

accommodate the two methyl groups; (vi) Finally, the psilocybin
substrate will be released from the catalytic pocket with the rotation of
Arg281 to the free state without substrate binding.

In vivo activity of the biosynthetic intermediates of psilocybin
Previous studies have reported that psilocybin produces anti-
depressant effects in mice45,46. However, the methylation step pro-
duces two unﬁnished catalytic intermediates structurally quite similar
to psilocybin; it is still unclear whether these intermediates have
similar biological effects. Therefore, we adopted a 6-day sub-chronic
variable stress (SCVS) paradigm in female mice to induce depressive-
like behaviors, followed by a single intraperitoneal injection of saline,
psilocybin, norbaeocystin, and baeocystin (1 mg/kg) one day after the
completion of SCVS, to evaluate the biological effects of these inter-
mediates. The behavioral tests, including the sucrose splash test (ST),
social interaction test (SIT), novelty-suppressed feeding (NSF), forced
swim test (FST), sucrose preference test (SPT), and the open-ﬁeld test
(OFT), were performed to examine the motivated behaviors and
anxiety levels of the mice (Fig. 6a). The behavioral results showed that
the SCVS successfully induced weight loss and depression-like beha-
viors in the female mice (Supplementary Fig. 20a–i).

Compared to the vehicle-injected SCVS mice, the psilocybin- and
norbaeocystin-injected SCVS mice showed a signiﬁcant decrease in
their immobility time in the forced swim test and an increased in social
interaction time (Fig. 6b, c), indicating that both psilocybin and nor-
baeocystin alleviated stress-induced depression-like phenotypes and
increased motivated behaviors. Notably, the SCVS mice treated with
norbaeocystin also showed a reduced latency to eat in the novelty-
suppressed feeding test and increased intake of sucrose water in the
sucrose preference test, suggesting the anti-anhedonic effects of
norbaeocystin (Fig. 6d, e). Meanwhile, no differences were observed
among all groups of SCVS mice regarding grooming time in the splash
test (Fig. 6f). In the open-ﬁeld test that measured the anxiety level of
the animals, the time spent and distance traveled in the central area of
the open ﬁeld remained unaltered in the SCVS mice treated with psi-
locybin and its two biosynthesis intermediates (Fig. 6g).

Changes in neuronal activity of the medial prefrontal cortex
(mPFC) have been reported in stress-induced depression-like beha-
viors in mice47,48. Our results showed that, compared with the vehicle-
injected SCVS mice, norbaeocystin-injected SCVS mice exhibited a
signiﬁcant elevation in c-FOS expression, an indicator of neuronal
activity, in the infralimbic PFC (IL-PFC) of SCVS mice (Fig. 6h–l). These
ﬁndings in SCVS female mice suggest the therapeutic potential of the
biosynthetic intermediates of psilocybin, speciﬁcally norbaeocystin, in
alleviating clinical symptoms of depression.

Discussion
Psilocybin is one of the most attractive psychedelic drugs for coping
with mental disorders because it has been shown to require a low dose,
be non-addictive, and have high safety1,2. Following the elucidation of
the biosynthetic pathway for the production of psilocybin in
P. cubensis24, bioengineering has led to the production of psilocybin in
fungi and bacteria27–29. Solving the structures of the enzymes involved

in producing psilocybin is essential for selecting highly efﬁcient
enzymes to enhance psilocybin production. Here, we have determined
the multiple crystal structures of PsiD, PsiK, and PsiM in their apo and
substrate-bound forms.

Our structural studies revealed that L-tryptophan decarboxylase
PsiD is similar to the PSD superfamily enzyme, featuring self-cleavage
activity that produces a β-chain and an α-chain30,34. This self-cleavage
mechanism is typically found in the pyruvoyl-containing enzymes,
which can be mainly divided into two classes: the ﬁrst is represented by
decarboxylases involved in metabolizing amino acids, such as histi-
dine, S-adenosylmethionine, aspartate, and phosphatidylserine, and
the second class is represented by reductases37. The decarboxylases
use a serine residue to induce the serinolysis reaction to achieve the
self-cleavage of the proprotein37. In contrast, the reductases possess a
cysteine instead of the serine residue for the catalytic reaction49.
However, some decarboxylases and reductases are shown to require
an additional factor to facilitate the maturation process of the pro-
protein, such as the histidine decarboxylase and the L-aspartate-α-
decarboxylase50,51, as well as one of the components of the proline
reductase (Prd) complex49. Consistent with the typical self-cleavage
mechanism, our structure of PsiD unveiled a putative non-classical
catalytic triad Glu242-His296-Ser403, as indicated by previous studies
that differ from those of EcPSD30,52,53. The mutations of the critical
residues His296 and Ser403 have resulted in a loss of their decarbox-
ylation abilities. Unfortunately, the mutation of Glu242 to alanine or
glutamine is insoluble in our studies, so we could not directly test its
impact on the self-cleavage of the PsiD protein. Further studies are
needed to evaluate its role in PsiD for self-cleavage and catalytic
reactions. Additionally, some PsiD mutants present increased catalytic
activity for the L-tryptophan substrate. These observations might be
attributed to the enzyme’s capacity to accommodate the substrate,
thereby promoting the turnover of the reaction.

Only a minor portion of the PsiD protein presented the homo-
dimer conformation in solution, while the main form of the PsiD pro-
tein exists as a monomer (Supplementary Fig. 3d). However, the crystal
structure of the PsiD (50–439)-Trp complex, which has different cell
parameters and contains only two PsiD molecules in the asymmetric
unit, presents itself as a homodimer. Additionally, the PISA analysis
indicated that the structures of apo-PsiD and PsiD-Trp consist of three
identical metastable dimers in their asymmetric unit, while the struc-
ture of PsiD (50–439)-Trp contains one homodimer54. However, we
cannot rule out the possibility that protein concentration in crystal-
lization experiments inﬂuences the PsiD enzyme to favor the homo-
dimer conformation; the monomeric state in solution may reﬂect the
true state of PsiD. Further studies are needed to determine the exact
status of PsiD and whether the monomeric or dimeric conformation
impacts its catalytic activity. The PsiD protein was also indicated to
process other substrates directly, such as 4-hydroxy-L-tryptophan and
4-hydroxy-6-methyl-L-tryptophan26,30. Our structural studies sug-
gested enough space in the catalytic pocket to accommodate the two
substrates without signiﬁcant clashes (Supplementary Fig. 21a, b). It is
also worth noting that although the gene cluster responsible for psi-
locybin biosynthesis has been identiﬁed, research has proposed an

Nature Communications |

 (2025) 16:2827

9

Article

a

apo-PsiM

η2

β1

α1

β2

b

apo-PsiM
PsiM-SAH

https://doi.org/10.1038/s41467-025-58239-x

η2

β1

α1

β2

α2

P185-G222

α4

SAHSAH

η1

α7

α3

β7

β9

β8

η3

N

η4

c

PsiM-SAM
PsiM-SAH

S211

A199

α8

α7

SAMSAM

SAHSAH

α5

β5

β4

α8

β3

β6

α6

α9

RMSD=0.3 Å

α10

C

e
PsiM-SAH-norbaeocystin
PsiM-SAH-baeocystin

RMSD=0.12 Å

f
PsiM-SAH-baeocystin
PsiM-SAH-psilocybin

α2

α4

α5

β5

β4

α6

P185-G222

β3

β6

α3

β7

β9

η1

N

β8

η3

η4

α9

α10

C

d
PsiM-SAH
PsiM-SAH-norbaeocystin

norbaeocystin
norbaeocystin

SAHSAH

baeocystin
baeocystin

norbaeocystin
norbaeocystin

baeocystin
baeocystin

psilocybin
psilocybin

SAH

SAHSAH

g

i)-ii)

iii)

iv)

v)

vi)

RMSD=0.167 Å

RMSD=0.179 Å

RMSD=0.138 Å

L68

norbaeocystin
norbaeocystin

SAMSAM

R75

R281

L68

SAHSAH

R75

R281

L68

SAHSAH

2.1 Å

baeocystin
baeocystin
norbaeocystin
norbaeocystin

R75

R281

psilocybin
psilocybin
baeocystin
baeocystin
norbaeocystin
norbaeocystin

R75

R281

L68

SAHSAH

L68

SAHSAH

psilocybin
psilocybin

R75

R281

apo-PsiM
PsiM-SAM

PsiM-SAM
PsiM-SAH-norbaeocystin

PsiM-SAM
PsiM-SAH-norbaeocystin
PsiM-SAH-baeocystin

PsiM-SAH-norbaeocystin
PsiM-SAH-baeocystin
PsiM-SAH-psilocybin

PsiM-SAH
PsiM-SAH-psilocybin

SAMSAM

SAMSAM

h

O

AdoMet

NH3

O

SAM

O

OH

OH

O

PsiM

S

Me

H2N

AdoMet

NH3

O

SAM

O

S

Me

CH3

HN

OH

OH

SAM

HN

SAM

SAH

HN

O

P

O

OH

OH

O

P

O

OH

OH

AdoHcy

NH3

O

O

SAH

PsiM

H3C

HN

SAH

O

OH

OH

S

CH3

N

O

P

O

OH

OH

norbaeocystin

baeocystin

psilocybin

alternative pathway for the decarboxylation step involving a non-
canonical aromatic L-amino acid decarboxylase (PcncAAAD) sourced
from P. cubensis55. The biochemical characterization and crystal
structure studies of this enzyme reveal its activity toward L-phenyla-
lanine, L-tyrosine, L-tryptophan, and chloro-tryptophan derivatives.
Therefore, this enzyme represents a valuable alternative tool for the
metabolic engineering of psilocybin production.

Our structure of the PsiK-ADP-Mg2+-tryptamine complex unveiled
the cofactor binding site, the divalent chelation status, and the inactive
substrate-binding
of
4-hydroxytryptamine as the substrate. The PsiK showed high structural
conservation to the MTR kinases in Arabidopsis thaliana and Bacillus
subtilis. Based on their similarities, we proposed a potential catalytic
mechanism for the PsiK enzyme in converting 4-hydroxytryptamine to

tryptamine

instead

using

state

by

Nature Communications |

 (2025) 16:2827

10

Article

https://doi.org/10.1038/s41467-025-58239-x

Fig. 5 | The methylation processes of psilocybin production. a The overall
structure of the apo-PsiM protein is colored in rainbow hues. The missing region in
apo-PsiM is indicated by red dashed lines. b Structural superposition of apo-PsiM
and the PsiM-SAH complex. The structures of apo-PsiM and the PsiM-SAH complex
are colored gray and green, respectively. The missing region in the structure of apo-
PsiM is colored purple-blue in the PsiM-SAH complex. c Structural superposition of
PsiM-SAM with PsiM-SAH. The red dashed box indicates the conformationally
changed region attributed to the binding of different cofactors. d Structural
superposition of the PsiM-SAH complex with the PsiM-SAH-norbaeocystin

complex. The norbaeocystin and SAH are colored pink and yellow. e Structural
superposition of the PsiM-SAH-baeocystin complex with the PsiM-SAH-
norbaeocystin complex. The baeocystin substrate and SAH cofactor in the PsiM-
SAH-baeocystin complex are colored purple and yellow. f Structural comparison
between the PsiM-SAH-baeocystin complex and the PsiM-SAH-psilocybin complex:
the former is colored cyan, while the latter is colored orange. g The conformational
changes of the residues involved in cofactor and substrate binding. h The con-
tinuous catalytic scheme of methylation reactions by the PsiM protein.

norbaeocystin. However, due to the control of 4-hydroxytryptamine in
China, we could not obtain the natural substrate for the PsiK complex.
Future studies are needed to uncover the catalytic mechanism of PsiK
in converting 4-hydroxytryptamine into norbaeocystin. Our results
also illustrate the stepwise catalytic mechanism of PsiM in adding two
methyl groups to the norbaeocystin substrate and validate that the
phosphate group is indispensable for the methylation reaction. When
we prepared the manuscript, a similar structural study of PsiM was
published44. In line with that study, our studies also suggest that the
PsiM protein is a homolog of human METTL1644. Additionally, our
studies conﬁrmed that human METTL16 could not catalyze norbaeo-
cystin or baeocystin to psilocybin, as validated by our TLC experi-
ments, suggesting that human METTL16 plays no role in the metabolic
turnover of psilocybin or its derivate psilocin. These analyses could
increase the safety proﬁle of the future use of psilocybin-related drugs.
Other detailed analyses between the PsiM and METTL16 protein can be
found in Supplementary Note 3 and the recently published work44.

In mushrooms, other tryptamine derivatives such as psilocin,
baeocystin, norbaeocystin, aeruginascin, and norpsilocin may also
inﬂuence the efﬁcacy of psilocybin treatment10,56. Hence, we evaluated
the therapeutic effects of the precursors of psilocybin through the
SCVS model of depression in female mice. It is worth noting that
therapeutic doses of psilocybin have been reported to produce
adverse effects, such as anxiety, paranoia, and prolonged visual per-
ceptual effects57,58. In our SCVS model of depression, we showed the
therapeutic effect of the biosynthetic intermediate norbaeocystin to
be comparable to psilocybin in alleviating depression-like behaviors
and anhedonia in SCVS female mice without the anxiogenic effect. Our
animal studies align closely with a recent investigation into the phar-
macological and behavioral impacts of tryptamine derivatives, in
which the researchers showed that, unlike psilocybin, neither baeo-
cystin nor norbaeocystin elicited signiﬁcant head twitch responses
(HTR)59. While they observed immediate antidepressant-like effects of
psilocybin and norbaeocystin in non-stressed rats59, our study
demonstrated sustained effects (spanning 4 days) in female mice
subjected to the SCVS paradigm. Notably, prior studies have reported
persistent antidepressant-like effects of psilocybin injected at low
doses (1 mg/kg) administered to rodent models of depression46,60.
These earlier ﬁndings are not only in line with our behavioral studies on
psilocybin but also underscore the reliability of the antidepressant-like
effects of norbaeocystin.

However, although these results support our ﬁndings, there are
inconsistent studies regarding the antidepressant-like effects of psi-
locybin. These effects may be attributed to various factors, such as
differences in administration doses and frequency45,46,61,62, stress
paradigms45,46, timing of assessment45,63, and genetic background of
animals64,65. For example, earlier studies have highlighted inconsistent
behavioral outcomes of psilocybin in the FST experiments, which can
be attributed to variations in assessment timing and the genetic
backgrounds of the animals45,60,64,65. Nevertheless, most studies on
psilocybin or psilocin showed a signiﬁcant inﬂuence on the FST
experiments at similar doses (1–1.5 mg/kg)46,59–61, supporting our ﬁnd-
ings that female mice receiving SCVS exhibited reduced immobility
time. Similar to the FST experiments, different outcomes can be
observed in the SPT experiments. The increased sucrose intake in our

psilocybin-treated SCVS female mice showed no signiﬁcant differ-
ences, possibly due to varying stress levels45 or the doses of psilocybin
administered62. In the NSF experiments, stress levels and administra-
tion doses also inﬂuenced the efﬁcacy of psilocybin46,66. In our study, a
single dose of psilocybin (1 mg/kg) has no effect on reducing food
intake latency in SCVS female mice, whereas a higher dose of psilocybin
(5 mg/kg) was indicated to reduce the latency to feed signiﬁcantly66. In
the SIT experiments, a single dose of psilocin (1.5 mg/kg) administered
to unstressed adult male mice did not produce any further increase in
social interaction time during a three-chamber social test 24 h post-
injection61. However, our study showed that a single dose of psilocybin
(1 mg/kg) increased social interaction among SCVS females 24 h after
injection. The varying genetic backgrounds may inﬂuence the efﬁcacy
of psilocybin in social interaction performance64. In the OFT experi-
ments, consistent with prior observations in adult male mice58, our
studies revealed that a 1 mg/kg psilocybin treatment did not affect
anxiety levels. However, higher doses of psilocybin (3 mg/kg, 5 mg/kg)
were shown to produce varying effects on anxiety-like behaviors58.
Finally, despite administering the same dose of psilocybin as in the
previous studies45,63, no acute HTR was observed in our experiment.
This may be because the HTR typically peaked within 15 min after
psilocybin administration and then gradually declined and ceased
within 2 h, whereas the behavioral outcomes were assessed one day
following the drug injection in our study. More detailed illustrations of
the variations in the behavioral experiments can be found in Supple-
mentary Note 4. Overall, before referring to the results of anti-
depressants in animals, one should carefully examine the differences in
experimental conditions.

In conclusion, our studies provide a practical view and structural
basis for further bioengineering production of psilocybin and its
derivatives through synthetic biology methods.

Methods
Animals
Three- to four-month-old female wildtype C57BL/6J mice, with a body
weight of (20 ± 5) g, were obtained from the Zhuhai Bai Shi Tong Ani-
mal Center (Zhuhai, China). The animals were kept in a speciﬁc
pathogen-free environment, with 4–5 animals per cage. The tempera-
ture (23 ± 2 °C) and humidity (50–60%) were kept stable. The animals
had free access to food and water. Animals were subjected to a 12 h/
12 h dark/light cycle daily. All animal studies were reviewed and
approved by the Institutional Animal Care and Use Committee of Sun
Yat-Sen University (approval number: SYSU-IACUC-2023-000057).

Protein expression and puriﬁcation
Plasmid encoding full-length Psilocybe cubensis (Psychedelic mushroom)
PsiD (Uniprot ID: P0DPA6) was ordered from Tsingke Biotechnology
Co., Ltd. In brief, the full-length or truncated psiD gene was ligated into a
modiﬁed pET-28a plasmid between BamHI and XhoI, and the pET-28a
plasmid carries N-terminal His6-SUMO fusions and an Ulp1 cleavage site
upstream of BamHI. Mutations were generated based on overlap PCR.
All the constructs were conﬁrmed by DNA sequencing. The wildtype
PsiD and its mutants were transformed into Escherichia coli BL21 (DE3)
strain to produce target proteins. E. coli cells were cultured in LB med-
ium at 37 °C with 50 mg/mL kanamycin until the OD600 reached 0.6–0.8.

Nature Communications |

 (2025) 16:2827

11

Article

a

Female SCVS

Open Field
Test
(OFT)
Splash Test
(ST)

Novelty-suppressed
feeding (NSF)

Forced Swim Test
(FST)

X2

i.p. Psi/Nor/Bae

Social
Interaction
(SIT)

Sucrose
Preference
(SPT)

Sacrifice

C57BL6/J Female
3-4 Months

Treatment

6 Days

Start
Day 7

Day 8

Day 9 Day 10 Day 11

End
Day 14

b

FST

P=0.008

P=0.007

c

200

150

100

50

0

)

%

(
I

D

80

60

40

20

0

-20

)
c
e
s
(
e
m

i
t
e

l
i

b
o
m
m

I

https://doi.org/10.1038/s41467-025-58239-x

Social Interaction Test (SIT)

P=0.018

P=0.007

SIT-DI

SIT-Total

)
s
(
e
m

i
t
n
o
i
t
a
r
o
p
x
e

l

l

a
t
o
T

250

200

150

100

50

0

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

NSF

P=0.009

d

)
c
e
s
(

t
a
e
o
t
y
c
n
e
t
a
L

500

400

300

200

100

0

SPT
P=0.19

P=0.06

P=0.16

e

100

80

60

40

20

0

f

)
c
e
s
(
n
o
i
t
a
r
u
D
g
n
m
o
o
r
G

i

200

150

100

50

0

)

%

(
I

D

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

g

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

Open Field Test (OFT)

ST

Total distance

Center distance

Center time

)

m
m

(
e
c
n
a
t
s
i
d

l
a
t
o
T

30000

20000

10000

0

20

15

10

5

0

)
l
a
t
o
t

%
(
e
c
n
a
t
s
i
d
r
e
t
n
e
C

10

8

6

4

2

0

)
l
a
t
o
t

%
(
e
m

i
t

r
e
t
n
e
C

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS

SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

IL-PFC

p=0.067

p=0.0336

PL-PFC

h

l
l
e
C

+
S
O
F
-
c
f
o
r
e
b
m
u
N

)
e
g
n
a
h
C
d
o
F
(

l

5

4

3

2

1

0

i

l
l
e
C

+
S
O
F
-
c
f
o
r
e
b
m
u
N

)
e
g
n
a
h
C
d
o
F
(

l

5

4

3

2

1

0

j

l
l
e
C

+
S
O
F
-
c
f
o
r
e
b
m
u
N

)
e
g
n
a
h
C
d
o
F
(

l

4

3

2

1

0

NAC

k

VTA

l
l
e
C

+
S
O
F
-
c
f
o
r
e
b
m
u
N

)
e
g
n
a
h
C
d
o
F
(

l

4

3

2

1

0

SCVS+Vehicle
SCVS+psilocybin
SCVS+norbaeocystin
SCVS+baeocystin

SCVS+Vehicle
SCVS+psilocybin
SCVS+norbaeocystin
SCVS+baeocystin

SCVS+Vehicle
SCVS+psilocybin
SCVS+norbaeocystin
SCVS+baeocystin

SCVS+Vehicle
SCVS+psilocybin
SCVS+baeocystin
SCVS+norbaeocystin

SCVS+Vehicle

SCVS+Vehicle

SCVS+psilocybin

SCVS+norbaeocystin

SCVS+norbaeocystin

SCVS+baeocystin

l

IL

IL

PL

IL

100 μm

SCVS+psilocybin

PL

IL

PL

IL

IL

IL

100 μm

SCVS+baeocystin

PL

IL

200 μm

100 μm

200 μm

200 μm

100 μm

The bacteria were induced with 0.2 mM isopropyl-β-d-thiogalactoside
(IPTG) at 18 °C for 14–20 h. Bacteria were collected by centrifugation,
resuspended in buffer containing 20 mM Tris-HCl pH 8.0, 500 mM NaCl,
25 mM imidazole pH 8.0, and then lysed by high pressure. Cell extracts
were centrifuged at 37,157 g for 1 h at 4 °C. Supernatants were puriﬁed
with Ni-NTA (GE), the target protein was washed with lysis buffer and
then eluted with elution buffer containing 20 mM Tris-HCl pH 8.0,

500 mM NaCl and 500 mM imidazole. Ulp1 protease was added to
remove the N-terminal His6-SUMO fusions of the recombinant protein
and dialyzed with lysis buffer for 3 h. Then, the mixture was applied to
another Ni-NTA resin to remove the protease and uncleaved proteins.
Eluted proteins were concentrated by centrifugal ultraﬁltration, loaded
onto a pre-equilibrated HiLoad 16/600 Superdex 200-pg column, and
eluted at a 1 mL/min ﬂow rate with the same buffer containing 10 mM

Nature Communications |

 (2025) 16:2827

12

Article

https://doi.org/10.1038/s41467-025-58239-x

Fig. 6 | Antidepressant effects of psilocybin and its biosynthetic intermediates.
a The experimental timeline of the sub-chronic variable stress (SCVS) paradigm,
behavioral tests, and tissue collection (sacriﬁce) for the four groups of female mice.
b Immobility time of mice in the forced swim test (FST). c Differential index (DI) and
total exploration time in the social interaction test (SIT). d Time of the latency to eat
in the novelty-suppressed feeding test (NSF). e Quantiﬁcation of sucrose water
intake in the sucrose preference test (SPT). f Grooming duration in the splash test
(ST). g Quantiﬁcation of the total distance traveled, the distance traveled in the
center zone as a percentage of the total distance traveled, and the time spent in the
center zone as a percentage of the total time in the open-ﬁeld test (OFT). Quanti-
tative analyses of the density of c-FOS-positive cells in (h) PL-PFC, (i) IL-PFC, (j) NAc,

and (k) VTA brain regions among the four groups of female mice. PL-PFC, prelimbic
prefrontal cortex; IL-PFC, infralimbic prefrontal cortex; NAc, nucleus accumbens;
VTA, ventral tegmental area. l Representative images of c-FOS staining in the IL-PFC
brain region (scale bar: PL+IL: 200 μm, IL only: 100 μm). SCVS + Vehicle: SCVS mice
that received saline injection; SCVS + psilocybin: SCVS mice that received psilocy-
bin injection; SCVS + norbaeocystin: SCVS mice that received norbaeocystin
injection; SCVS + baeocystin: SCVS mice that received baeocystin injection.
b–g N = 7, 9, 8, 7 mice per group, h, i N = 3, 4, 3, 4 mice per group, j, k N = 3, 5, 3, 4
mice per group. All data are presented as mean ± SEM and analyzed using one-way
ANOVA followed by Tukey’s post hoc test.

Tris-HCl pH 8.0, and 100 mM NaCl. Puriﬁed fractions were pooled
together and concentrated by centrifugal ultraﬁltration. The con-
centration was determined by A280 for further crystallization trials and
biochemical characterization of the enzyme activities. A plasmid
encoding Psilocybe cubensis (Psychedelic mushroom) PsiM (Uniprot ID:
P0DPA9) was ordered from Tsingke Biotechnology Co., Ltd. All the
puriﬁcation procedures were the same as those for PsiD. The con-
centration was determined by A280 for
further crystallization
trials and biochemical characterization of the enzyme activities. For the
PsiK production,
cubensis
(Psychedelic mushroom) PsiK (Uniprot ID: P0DPA8) was also ordered
from Tsingke Biotechnology Co., Ltd. All the puriﬁcation procedures
were the same as those for PsiD; however, the ﬁnal gel ﬁltration buffer
was changed to 10 mM Tris pH 8.0, 100 mM NaCl for further crystal-
lization trials and biochemical experiments. The human METTL16 gene
was PCR ampliﬁed from the human cDNA and subcloned into
the modiﬁed pET-28a-Sumo plasmid to express the truncated METTL16
(1–310) protein. All the puriﬁcation procedures were the same as
those for PsiD, but the ﬁnal gel ﬁltration buffer was changed to 10 mM
Tris pH 8.0, 100 mM NaCl, and 1 mM DTT for further biochemical
experiments.

encoding

Psilocybe

plasmid

the

Crystallization and data collection
All the crystals were crystallized using the sitting drop vapor diffusion
method by mixing 0.2 μL of protein and 0.2 μL of reservoir solution at
18 °C. The crystals picked for data collection were all soaked in cryo-
protectants containing the crystallization conditions, supplemented
with 20% glycerol, and were fast-frozen in liquid nitrogen. Diffraction
data were collected from the National Facility for Protein Science in
Shanghai (NFPS) at the Shanghai Synchrotron Radiation Facility
(SSRF). The crystallization conditions are listed below:
1) The crystal of apo-PsiD suitable for X-ray diffraction was grown in
a reservoir solution consisting of 0.2 M Ammonium acetate, 0.1 M
Sodium citrate pH 5.6, 30% w/v Polyethylene glycol 4000.
2) The crystals of the PsiD-Trp complex suitable for X-ray diffraction
were grown in a reservoir solution consisting of 0.2 M Sodium
chloride, 0.1 M Tris pH 8.5, 25% w/v Polyethylene glycol 3350.
3) The crystals of the PsiD (50–439)-Trp complex suitable for X-ray
diffraction were grown in a reservoir solution consisting of 0.1 M
Magnesium formate dihydrate, 15% w/v Polyethylene glycol 3350.
4) The crystals of PsiK-ADP-Mg2+-Tryptamine complex suitable for
X-ray diffraction were grown in a reservoir solution consisting of
20% (w/v) PEG 8000, 0.1 M Tris base/Hydrochloric acid pH 8.5,
0.1 M Magnesium chloride, and 20% (v/v) PEG 400.

5) The crystals of apo-PsiM suitable for X-ray diffraction were grown
in a reservoir solution consisting of 0.2 M Magnesium chloride,
0.1 M Tris pH 8.5, 30% w/v PEG 4000.

6) The crystals of PsiM-SAM suitable for X-ray diffraction were grown
in a reservoir solution consisting of 0.2 M Ammonium acetate,
0.1 M Sodium acetate trihydrate pH 4.6, 30% w/v Polyethylene
glycol 4000.
7) The crystals of

the PsiM-SAH complex suitable for X-ray
diffraction were grown in a reservoir solution consisting of 1.2 M

Potassium phosphate (dibasic)/0.8 M Sodium phosphate (mono-
basic), 0.1 M Sodium acetate/Acetic acid pH 4.5.

8) The crystals of PsiM-SAH-norbaeocystin suitable for X-ray
diffraction were grown in a reservoir solution consisting of 40%
(v/v) Isopropanol, 0.1 M Imidazole/Hydrochloric acid pH 6.5, 15%
(w/v) PEG 8000.

9) The crystals of PsiM-SAH-baeocystin suitable for X-ray diffraction
were grown in a reservoir solution consisting of 0.1 M HEPES pH
7.5, 20% w/v Polyethylene glycol 10,000.

10) The crystals of PsiM-SAH-psilocybin suitable for X-ray diffraction
were grown in a reservoir solution consisting of 0.2 M Sodium
acetate, 0.1 M Sodium cacodylate pH 6.5, 30% w/v PEG 8000.

Structure determination and reﬁnement
For the apo-PsiD structure, the diffraction dataset was processed and
scaled using XDS67. The phase was determined by molecular replace-
ment using the program Phaser with the predicted structure (Uniprot
ID: P0DPA6) by AlphaFold2 as the search model31. Cycles of reﬁnement
and model building were carried out using PHENIX and COOT,
respectively68,69. For the PsiD-Trp and PsiD (50–439)-Trp structures,
the diffraction datasets were also processed and scaled using XDS67.
The phase was determined by molecular replacement using the pro-
gram Phaser with the structure of apo-PsiD as the search model70.
Cycles of reﬁnement and model building were carried out using PHE-
NIX and COOT68,69. For the PsiK-ADP-Mg2+-Tryptamine structure, the
phase was determined by molecular replacement using the program
Phaser with the predicted structure (Uniprot ID: P0DPA8) by Alpha-
Fold2 as the search model. Cycles of reﬁnement and model building
were carried out using PHENIX and COOT, respectively68,71. For the
apo-PsiM structure, the diffraction dataset was processed and scaled
using XDS67. The phase was determined by molecular replacement
using the program Phaser with the predicted structure (Uniprot ID:
P0DPA9) by AlphaFold2 as the search model. Cycles of reﬁnement and
model building were carried out using PHENIX and COOT,
respectively68,71. For the other structures, including PsiM-SAM, PsiM-
SAH, PsiM-SAH-norbaeocystin, PsiM-SAH-baeocystin, and PsiM-SAH-
psilocybin, the diffraction datasets were also processed and scaled
using XDS67. The phase was determined by molecular replacement
using the program Phaser with the structure of apo-PsiM as the search
model70. Cycles of reﬁnement and model building were carried out
using PHENIX and COOT, respectively68,71. The details of data collec-
tion and processing are presented in Supplementary Table 1. All
structure ﬁgures were prepared with PyMOL.

Decarboxylation assay
The enzymatic assays were performed in a buffer containing 10 mM
Tris-HCl pH 8.0 and 100 mM NaCl. For the decarboxylation reactions
of the wildtype PsiD, 20 mM substrate L-tryptophan and gradient-
increased PsiD concentrations ranging from 20 to 100 μM were indi-
vidually included in the total volume of 20 µL reaction systems. The
reaction systems were incubated at 37 °C for 1 h. To test the PsiD
mutants’ activities, 100 µM puriﬁed wildtype PsiD protein or its mutant
proteins and 20 mM substrate L-tryptophan were individually included

Nature Communications |

 (2025) 16:2827

13

Article

https://doi.org/10.1038/s41467-025-58239-x

in the total volume of 20 µL reaction systems. All the reactions were
incubated for 1 h at 37 °C. For testing the impact of the pH value on the
activity of wildtype PsiD, 100 µM puriﬁed wildtype PsiD protein and
20 mM substrate L-tryptophan were individually included in a total
volume of 20 µL reaction systems. The assays were performed in a
buffer containing 100 mM NaCl and 10 mM Tris-HCl, with the pH
ranging from 7.4 to 9.0. The reaction systems were incubated at 37 °C
for 1 h. To determine the enzyme activities of the wildtype PsiD, PsiD
(30–439), PsiD (50–439), PsiD (1–439) S403A, and PsiD (1–439) W27A,
100 µM puriﬁed proteins of these constructs and 20 mM substrate
L-tryptophan were each included in a 20 µL reaction system. The
enzymatic assays were performed in the buffer containing 10 mM Tris-
HCl pH 8.0 and 100 mM NaCl. The reaction systems were incubated at
37 °C for 30 s to 14 min or 1 h.

All the samples were spotted as follows: 1 μL aliquots were taken
and spotted on a pre-saturated (1 h) aluminum plate coated with silica
gel 60 F254 and developed for 3 h. The spots were 2 cm from the
bottom of the plate, and the plates were developed with N-butyl
alcohol: H2O: Ethanoic acid (12:5:3) as solvents. The spots were
exposed to UV light at 254 nm for visualization. All data points were
obtained in three replicate experiments. Data are expressed as the
mean ± SEM unless otherwise noted.

In vitro methylation assay
The enzymatic assays were performed in a buffer containing phos-
phate buffer (50 mM NaH2PO4 pH 7.4). For testing the activities of the
wildtype or mutant PsiM proteins or the METTL16 (1–310), 200 µM of
puriﬁed wildtype PsiM protein or its mutant proteins and 2.5 mM
substrate norbaeocystin or baeocystin, and 2.5 mM cofactor SAM were
included in a total volume of 20 µL reaction system. All the reactions
were incubated for 1 h at 25 °C. Aliquots of 1 μL were taken and spotted
on a pre-saturated (1 h) aluminum plate coated with silica gel 60 F254
and developed for 3 h. The spots were 2 cm from the bottom of the
plate and 1.4 cm apart, and the plates were developed with N-butyl
alcohol: H2O: Ethanoic acid (12:5:3) as the solvents. The spots were
exposed to UV light at 254 nm for visualization. All data points were
obtained from three replicate experiments. Data are expressed as the
mean ± SEM unless otherwise noted.

Analytical gel ﬁltration
PsiD mutant proteins were puriﬁed using the same procedure as
wildtype PsiD. Analytical gel ﬁltration chromatography was performed
at 4 °C using a Superdex 200 10/300 global column (Cytiva) pre-
equilibrated in 10 mM Tris pH 8.0 and 100 mM NaCl. All samples,
including the wildtype PsiD, S403A, and R135A/Q136A, were injected at
a ﬂow rate of 0.3 mL/min, respectively.

Liquid chromatography and mass spectrometry
The enzymatic reaction products were detected by the Ultimate 3000
(HPLC)-Q Exactive plus mass spectrometer (MS) in positive mode. The
linear separation process was performed at 25 °C with a gradient of
acetonitrile (ACN) from 5% to 100% within 7 min at a ﬂow rate of
0.3 mL/min. Solvent A was 0.1 % aqueous formic acid (FA), and solvent
B was ACN + 0.1% FA. High-resolution mass spectra were recorded on
the Thermo Q-Exactive Orbitrap MS, ﬁtted with an ACQUITY UPLC BEH
C18 column (130 A, 1.7 μm, 100 × 2.1 mm). All MS spectra were
obtained in data-dependent mode with one MS full-scan ranging from
70 to 1050 Dalton. The parent ions for reactants and products were
205.10 and 161.11, respectively.

To validate the pyruvoyl prosthetic group instead of the serine
residue that exists in the N-terminal of the α-chain within the mature
PsiD enzyme, the peptides of the α-chain were extracted from the SDS-
PAGE using an 80% ACN aqueous solution. The obtained peptide
solution was freeze-dried. 1 μg of trypsin (dissolved in 100 μL of 10 mM
NH4CO3) was added, followed by digestion at 37 °C overnight. The

tryptic digests were analyzed by a Fusion MS in positive mode. The
gradient is from 6% to 35% ACN in 30 min. All MS and MS/MS spectra
were obtained in data-dependent mode with one MS full-scan ranging
from 300 to 1800, followed by 10 MS/MS scans. The raw ﬁles obtained
were uploaded to Proteome Discoverer (PD, version 2.1) and searched
against
the self-written database (sequence: SFALGLRKDCRAEI-
VEKFTEPGTVIRINEVVAALKA) to show the modiﬁcations of identiﬁed
peptides. The parameters for searching were set as follows: enzyme,
trypsin; missed cleavages, two; variable modiﬁcations, C3H2O2 (S,
70 Da). The peptide tolerance and MS/MS tolerance were 10 ppm and
0.02 Da, respectively. The ascertained false discovery rate (FDR) for all
the identiﬁed peptides was less than 1%.

Sub-chronic variable stress (SCVS)
Animals were adapted to the environment for 3–4 days before the
experiments. The mice were then handled for 3 days before being
subjected to different stressors every day for 6 days. On the ﬁrst and
fourth days, the mice (5–10 grouped in the shock chamber, Med
Associates, Vermont, USA)
received one hundred foot-shocks
(0.45 mA, 1 s delivered at random intervals for 1 h); on the second
and ﬁfth days, they were subjected to tail suspension stress; on the
third and sixth days, the mice were restrained in the conical
tube for 1 h.

Drug injection
Psilocybin, norbaeocystin, and baeocystin powders were dissolved in a
0.9% sterile saline solution, and the mice were intraperitoneally
injected (1 mg/kg) on the morning of the next day after the completion
of SCVS. For the vehicle control group, the mice were injected with
0.9% sterile saline solution. Behavioral testing was conducted on the
days following the injection.

Behavioral tests
Depressive-like and anxiety-like behaviors were assessed within one
week after the completion of SCVS. On the test day, mice were placed
in the testing room for habituation for 1–2 h. The behavioral testing
apparatus was cleaned with 75% ethanol between animals. The order of
the behavioral tests was speciﬁed in the experimental timeline of the
ﬁgures.

Splash test (ST)
The test was conducted in a standard mouse cage under red light
(60–80 Lux) in a sound-insulated chamber. The mice were allowed to
move freely for 1 min to habituate to the arena. Then, the dorsal coat of
the mice was sprayed 3 times with a 10% sucrose solution and video-
taped for 5 min. The time spent grooming was recorded using a
stopwatch by a researcher blinded to the experimental groups.

Social interaction test (SIT)
An unfamiliar female mouse (social mouse) was used for the social
interaction test and acclimated in a round plastic cage for 10 min each
day for 3 days prior to the beginning of the test to reduce the anxiety
level. Social interaction was measured in a 60 × 40 × 20 cm box, divi-
ded into three chambers by two transparent dividing walls, under red
light (60–80 Lux) in a sound-insulated chamber. On the test day, the
test mouse was ﬁrst allowed to explore the box with two empty
enclosures for 10 min. Then, the social mouse was placed in one of the
enclosures, while a toy mouse was placed in the other enclosure. The
test mouse was placed back in the box for 10 min and allowed for free
exploration. Both phases of the test were videotaped and analyzed by a
researcher blinded to the experimental groups. The interaction time
between the test mouse and the social mouse was recorded as A, and
the interaction time between the test mouse and the toy mouse was
recorded as B. The index of social interaction was calculated as
(A−B)/(A + B) × 100%.

Nature Communications |

 (2025) 16:2827

14

Article

https://doi.org/10.1038/s41467-025-58239-x

Novelty-suppressed feeding (NSF) test
Mice were weighed, and all food was removed from their cages 24 h
prior to the test. During the test, the mouse was placed in an empty
white plastic box (30 × 30 × 30 cm) without bedding. A small piece of a
mouse pellet was placed in the center of the arena, and the mouse was
placed in the corner. The box was enclosed in a sound-insulated
chamber, illuminated under red light (60–80 Lux). The latency to
begin food consumption in a 10-min test was measured by a researcher
blinded to the experimental groups.

Open-ﬁeld test (OFT)
The open-ﬁeld arena was a white box (40 × 40 × 40 cm) illuminated
with red light (60–80 Lux), placed inside a sound-insulated chamber.
After wiping the box with 75% alcohol, the mouse was placed into the
corner of the box and allowed to move freely. The total distance tra-
veled, as well as the distance traveled and time spent in the center zone
(20 × 20 cm), were tracked and analyzed by the DigBehv software
(version 4.1.7.171129, Ji-Liang, Shanghai, China).

Forced swim test (FST)
Mice were placed into a 5 L glass beaker containing 3.5 L of water at
24–25 °C under white light (210–280 Lux). The mice were subjected to
the FST for 6 min, and their activity was video-recorded. Each video
was analyzed by a researcher blinded to the experimental groups and
scored for immobility time over the last 4 min duration, which was
deﬁned as the absence of any body movement except that necessary
for the mice to keep their heads above the water.

Sucrose preference test (SPT)
Each mouse was individually housed in a cage with two drinking bot-
tles. All mice had access to chow diet ad libitum. On day 1, two bottles
of 1% sucrose solution were placed at the same time. The mice adapted
to the environment and were allowed to drink freely for 24 h. On day 2,
the weight of a bottle of drinking water (M1 water) and the weight of a
bottle of 1% sucrose solution (M1 sugar) were recorded and placed in
the mouse cage. The mice were allowed to drink freely for 24 h, and the
remaining weight of drinking water (M2 water) and sucrose solution
(M2 sugar) was recorded. On day 3, the positions of the two drinking
bottles were swapped to eliminate the bias caused by position pre-
ference. The weight of a new bottle of drinking water (M3 water) and a
new bottle of 1% sucrose solution (M3 sugar) were recorded. 24 h later,
the weight of the remaining drinking water (M4 water) and sucrose
solution (M4 sugar) was recorded. Sucrose preference was calculated
as follows: [(M1 sugar−M2 sugar) + (M3 sugar−M4 sugar)]/[(M1 water
−M2 water) + (M1 sugar−M2 sugar) + (M3 water−M4 water) + (M3 sugar
−M4 sugar)] × 100%

Immunoﬂuorescence staining and image analysis
Mice were anesthetized with intraperitoneal (i.p.) injection of sodium
pentobarbital (100 mg/kg body weight), transcardially perfused with
PBS for 2 min, followed by 4% paraformaldehyde in PBS for 5 min at a
rate of 10 mL/min. The brains were then harvested and postﬁxed in 4%
paraformaldehyde in PBS overnight at 4 °C, followed by cryoprotec-
tion in 30% sucrose in PBS for 2–3 days at 4 °C. 30–40 μm coronal brain
sections were collected using a cryostat. One coronal section con-
taining the mPFC (at ~1.77 and 1.97 mm anterior to the Bregma), one
section containing the NAc (at ~0.73 and 1.21 mm anterior to the
Bregma), and one section containing the VTA (at ~2.91 and 3.15 mm
posterior to the Bregma) were sampled for free-ﬂoating immuno-
ﬂuorescence staining. The brain regions of interest were determined
based on the 4th edition of “The Mouse Brain in Stereotaxic Coordi-
nates” by Paxinos and Franklin. The sections were blocked with a
solution containing 5% goat serum, 1% bovine serum albumin, and 0.4%
Triton X-100 in PBS for 2 h at room temperature. Subsequently, they
were incubated with the primary antibody of c-FOS (Cell Signaling

Technology, cat#: 2250, 1:750) in the blocking buffer for ~24 h at 4 °C,
followed by 10 min rinse of PBS with 0.4% Triton X-100 for three times,
and incubated with the secondary antibody (Goat anti-rabbit IgG(H+L)
Alexa Fluor 488, Thermo Fisher, A11034,1:800) in the blocking buffer
for 2 h at room temperature. The sections were then washed three
times and mounted onto glass slides. Images were acquired using an
epi-ﬂuorescent microscope (Eclipse Ni-U, Nikon, Japan) and analyzed
with ImageJ (version 1.52n, NIH, USA).

Statistical analysis
Statistical analysis was performed with Prism v10.0 (GraphPad Soft-
ware, Boston, MA). All data are presented as the mean ± SEM. For
multiple-group comparison, one-way ANOVA with Tukey’s post hoc
test was used. p < 0.05 was considered statistically signiﬁcant.

Reporting summary
Further information on research design is available in the Nature
Portfolio Reporting Summary linked to this article.

Data availability
The coordinates generated in this study have been deposited in the
Protein Data Bank under accession codes 8X4Q (apo-PsiD), 8X4S (PsiD-
Trp), 8ZIA (PsiD (50–439)-Trp), 8ZIC (PsiK-ADP-Mg2+-Trp), 8ZIE (apo-
PsiM), 8ZIG (PsiM-SAM), 8ZIH (PsiM-SAH), 8ZII (PsiM-SAH-norbaeo-
cystin), 8ZIM (PsiM-SAH-baeocystin), and 8ZIO (PsiM-SAH-psilocybin).
PDB codes of previously published structures used in this study are
7CNY (EcPSD), 2PYW (AtMTK), 2PUN (BsMTNK), and 6DU4
(HsMETTL16). The mass spectrometry data have been deposited to
the ProteomeXchange Consortium via the PRIDE partner repository
with the dataset identiﬁer PXD06135872. The LC/MS raw data for
detecting enzymatic reaction products have been deposited in the
BMRbig database (https://bmrbig.org/) under the accession number
bmrbig113 [https://bmrbig.org/released/bmrbig113]. Additional infor-
mation and/or materials related to this study will be made available
through a material transfer agreement (MTA) upon request to the
corresponding authors. Source data are provided as a Source Data
ﬁle. Source data are provided with this paper.

References
1.

Rehm, J. & Shield, K. D. Global burden of disease and the impact of
mental and addictive disorders. Curr. Psychiatry Rep. 21, 10 (2019).

2. Nutt, D., Erritzoe, D. & Carhart-Harris, R. Psychedelic psychiatry’s

brave new world. Cell 181, 24–28 (2020).

3. Nichols, D. E. Psilocybin: from ancient magic to modern medicine. J.

4.

Antibiot. 73, 679–686 (2020).
Passie, T., Seifert, J., Schneider, U. & Emrich, H. M. The pharma-
cology of psilocybin. Addict. Biol. 7, 357–364 (2002).

5. Grifﬁths, R. R. et al. Psilocybin produces substantial and sustained

decreases in depression and anxiety in patients with life-
threatening cancer: a randomized double-blind trial. J. Psycho-
pharmacol. 30, 1181–1197 (2016).

7.

6. Carhart-Harris, R. L. et al. Psilocybin with psychological support for
treatment-resistant depression: six-month follow-up. Psycho-
pharmacology 235, 399–408 (2018).
Bogenschutz, M. P. et al. Psilocybin-assisted treatment for alcohol
dependence: a proof-of-concept study. J. Psychopharmacol. 29,
289–299 (2015).
Johnson, M. W., Garcia-Romeu, A., Cosimano, M. P. & Grifﬁths, R. R.
Pilot study of the 5-HT2AR agonist psilocybin in the treatment of
tobacco addiction. J. Psychopharmacol. 28, 983–992 (2014).
Fricke, J., Lenz, C., Wick, J., Blei, F. & Hoffmeister, D. Production
options for psilocybin: making of the magic. Chemistry 25,
897–903 (2019).

9.

8.

10. Lowe, H. et al. The therapeutic potential of psilocybin. Molecules

26, https://doi.org/10.3390/molecules26102948 (2021).

Nature Communications |

 (2025) 16:2827

15

Article

https://doi.org/10.1038/s41467-025-58239-x

11. Hofmann, A. et al. Psilocybin and psilocin, two psychotropic sub-
stances in Mexican magic mushrooms. Helv. Chim. Acta 42,
1557–1572 (1959).

12. Hofmann, A., Heim, R., Brack, A. & Kobel, H. [Psilocybin, a psycho-
tropic substance from the Mexican mushroom Psilicybe mexicana
Heim]. Experientia 14, 107–109 (1958).
Johnson, M. W. & Grifﬁths, R. R. Potential therapeutic effects of
psilocybin. Neurotherapeutics 14, 734–740 (2017).

13.

14. Wieczorek, P. P. et al. Chapter 5 - Bioactive Alkaloids of Hallucino-
genic Mushrooms. In: Studies in Natural Products Chemistry. Vol. 46
(ed. Rahman Atta ur) (Elsevier, 2015). https://doi.org/10.1016/B978-
0-444-63462-7.00005-1.

15. Schultes, R. E. Hallucinogens of plant origin. Science 163,

245–254 (1969).

of phosphatidylserine decarboxylase. J. Biol. Chem. 290,
10972–10980 (2015).

36. Ogunbona, O. B., Onguka, O., Calzada, E. & Claypool, S. M. Multi-

tiered and cooperative surveillance of mitochondrial phosphati-
dylserine decarboxylase 1. Mol. Cell. Biol. 37, https://doi.org/10.
1128/MCB.00049-17 (2017).

37. van Poelje, P. D. & Snell, E. E. Pyruvoyl-dependent enzymes. Annu.

Rev. Biochem. 59, 29–59 (1990).

38. Voelker, D. R. Phosphatidylserine decarboxylase. Biochim. Biophys.

Acta 1348, 236–244 (1997).

39. Li, Q. X. & Dowhan, W. Studies on the mechanism of formation of
the pyruvate prosthetic group of phosphatidylserine decarboxylase
from Escherichia coli. J. Biol. Chem. 265, 4111–4115 (1990).

40. Holm, L. Using Dali for protein structure comparison. Methods Mol.

16. Hasler, F., Bourquin, D., Brenneisen, R., Bar, T. & Vollenweider,

Biol. 2112, 29–42 (2020).

F. X. Determination of psilocin and 4-hydroxyindole-3-acetic
acid in plasma by HPLC-ECD and pharmacokinetic proﬁles of
oral and intravenous psilocybin in man. Pharm. Acta Helv. 72,
175–184 (1997).

17. Tyls, F., Palenicek, T. & Horacek, J. Psilocybin-summary of knowl-
edge and new perspectives. Eur. Neuropsychopharmacol. 24,
342–356 (2014).

18. Geiger, H. A., Wurst, M. G. & Daniels, R. N. DARK classics in chemical
neuroscience: psilocybin. ACS Chem. Neurosci. 9, 2438–2447
(2018).

19. Nichols, D. E. Psychedelics. Pharmacol. Rev. 68, 264–355 (2016).
20. Kargbo, R. B. Psilocybin therapeutic research: the present and
future paradigm. ACS Med. Chem. Lett. 11, 399–402 (2020).

21. Mithoefer, M. C., Grob, C. S. & Brewerton, T. D. Novel psycho-

pharmacological therapies for psychiatric disorders: psilocybin and
MDMA. Lancet Psychiatry 3, 481–488 (2016).

22. Fricke, J. et al. Scalable hybrid synthetic/biocatalytic route to psi-

locybin. Chemistry 26, 8281–8285 (2020).

23. Kargbo, R. B. et al. Direct phosphorylation of psilocin enables

optimized cGMP kilogram-scale manufacture of psilocybin. ACS
Omega 5, 16959–16966 (2020).

24. Fricke, J., Blei, F. & Hoffmeister, D. Enzymatic synthesis of psilocy-

bin. Angew. Chem. Int. Ed. Engl. 56, 12352–12355 (2017).
25. Reynolds, H. T. et al. Horizontal gene cluster transfer increased
hallucinogenic mushroom diversity. Evol. Lett. 2, 88–101 (2018).
26. Fricke, J. et al. Enzymatic route toward 6-methylated baeocystin

and psilocybin. ChemBioChem 20, 2824–2829 (2019).
27. Hoefgen, S. et al. Facile assembly and ﬂuorescence-based

screening method for heterologous expression of biosynthetic
pathways in fungi. Metab. Eng. 48, 44–51 (2018).

28. Adams, A. M. et al. In vivo production of psilocybin in E. coli. Metab.

Eng. 56, 111–119 (2019).

41. Ku, S. Y., Cornell, K. A. & Howell, P. L. Structure of Arabidopsis

thaliana 5-methylthioribose kinase reveals a more occluded active
site than its bacterial homolog. BMC Struct. Biol. 7, 70 (2007).
42. Ku, S. Y. et al. Structures of 5-methylthioribose kinase reveal sub-
strate speciﬁcity and unusual mode of nucleotide binding. J. Biol.
Chem. 282, 22195–22206 (2007).

43. Matte, A., Tari, L. W. & Delbaere, L. T. How do kinases transfer

phosphoryl groups? Structure 6, 413–419 (1998).

44. Hudspeth, J. et al. Methyl transfer in psilocybin biosynthesis. Nat.

Commun. 15, 2709 (2024).

45. Hesselgrave, N., Troppoli, T. A., Wulff, A. B., Cole, A. B. & Thompson,
S. M. Harnessing psilocybin: antidepressant-like behavioral and
synaptic actions of psilocybin are independent of 5-HT2R activation
in mice. Proc. Natl. Acad. Sci. USA 118, https://doi.org/10.1073/
pnas.2022489118 (2021).

46. Sekssaoui, M., Bockaert, J., Marin, P. & Bécamel, C. Antidepressant-
like effects of psychedelics in a chronic despair mouse model: is the
5-HT2A receptor the unique player? Neuropsychopharmacology
49, 747–756 (2024).

47. Arnsten, A. F. Stress signalling pathways that impair prefrontal
cortex structure and function. Nat. Rev. Neurosci. 10, 410–422
(2009).

48. Li, F. et al. Mediodorsal thalamus projection to medial prefrontal
cortical mediates social defeat stress-induced depression-like
behaviors. Neuropsychopharmacology https://doi.org/10.1038/
s41386-024-01829-y (2024).

49. Behlendorf, C. et al. Formation of the pyruvoyl-dependent proline
reductase Prd from Clostridioides difﬁcile requires the maturation
enzyme PrdH. PNAS Nexus 3, pgae249 (2024).

50. Trip, H., Mulder, N. L., Rattray, F. P. & Lolkema, J. S. HdcB, a novel
enzyme catalysing maturation of pyruvoyl-dependent histidine
decarboxylase. Mol. Microbiol. 79, 861–871 (2011).

29. Milne, N. et al. Metabolic engineering of Saccharomyces cerevisiae

51. Nozaki, S., Webb, M. E. & Niki, H. An activator for pyruvoyl-

for the de novo production of psilocybin and related tryptamine
derivatives. Metab. Eng. 60, 25–36 (2020).

30. Schafer, T., Kramer, K., Werten, S., Rupp, B. & Hoffmeister, D.

Characterization of the gateway decarboxylase for psilocybin bio-
synthesis. ChemBioChem 23, e202200551 (2022).
Jumper, J. et al. Highly accurate protein structure prediction with
AlphaFold. Nature 596, 583–589 (2021).

31.

32. Watanabe, Y., Watanabe, Y. & Watanabe, S. Structural basis for
phosphatidylethanolamine biosynthesis by bacterial phosphati-
dylserine decarboxylase. Structure 28, 799–809.e5 (2020).
33. Cho, G., Lee, E. & Kim, J. Structural insights into phosphatidy-

lethanolamine formation in bacterial membrane biogenesis. Sci.
Rep. 11, 5785 (2021).

34. Schuiki, I. & Daum, G. Phosphatidylserine decarboxylases, key

enzymes of lipid metabolism. IUBMB Life 61, 151–162 (2009).
35. Choi, J. Y., Duraisingh, M. T., Marti, M., Ben Mamoun, C. & Voelker, D.
R. From protease to decarboxylase: the molecular metamorphosis

dependent l-aspartate alpha-decarboxylase is conserved in a small
group of the gamma-proteobacteria including Escherichia coli.
MicrobiologyOpen 1, 298–310 (2012).

52. Hedstrom, L. Serine protease mechanism and speciﬁcity. Chem.

Rev. 102, 4501–4524 (2002).

53. Ekici, O. D., Paetzel, M. & Dalbey, R. E. Unconventional serine pro-
teases: variations on the catalytic Ser/His/Asp triad conﬁguration.
Protein Sci. 17, 2023–2037 (2008).

54. Krissinel, E. Stock-based detection of protein oligomeric states in

jsPISA. Nucleic acids Res. 43, W314–W319 (2015).

55. Torrens-Spence, M. P., Liu, C. T., Pluskal, T., Chung, Y. K. & Weng, J.
K. Monoamine biosynthesis via a noncanonical calcium-activatable
aromatic amino acid decarboxylase in psilocybin mushroom. ACS
Chem. Biol. 13, 3343–3353 (2018).

56. Blei, F. et al. Simultaneous production of psilocybin and a cocktail
of beta-carboline monoamine oxidase inhibitors in “magic” mush-
rooms. Chemistry 26, 729–734 (2020).

Nature Communications |

 (2025) 16:2827

16

Article

https://doi.org/10.1038/s41467-025-58239-x

57. Yerubandi, A. et al. Acute adverse effects of therapeutic doses of

psilocybin: a systematic review and meta-analysis. JAMA Netw.
Open 7, e245960 (2024).

58. Harari, R., Chatterjee, I., Getselter, D. & Elliott, E. Psilocybin
induces acute anxiety and changes in amygdalar phospho-
peptides independently from the 5-HT2A receptor. iScience 27,
109686 (2024).

59. Rakoczy, R. J. et al. Pharmacological and behavioural effects of
tryptamines present in psilocybin-containing mushrooms. Br. J.
Pharmacol. 181, 3627–3641 (2024).

60. Hibicke, M., Landry, A. N., Kramer, H. M., Talman, Z. K. & Nichols, C. D.
Psychedelics, but not ketamine, produce persistent antidepressant-
like effects in a rodent experimental system for the study of depres-
sion. ACS Chem. Neurosci. 11, 864–871 (2020).

61. Takaba, R. et al. Ethopharmacological evaluation of antidepressant-
like effect of serotonergic psychedelics in C57BL/6J male mice.
Naunyn Schmiedebergs Arch. Pharmacol. 397, 3019–3035 (2024).

62. Cameron, L. P. et al. 5-HT2ARs mediate therapeutic behavioral

effects of psychedelic tryptamines. ACS Chem. Neurosci. 14,
351–358 (2023).

63. Shao, L. X. et al. Psilocybin induces rapid and persistent growth of

dendritic spines in frontal cortex in vivo. Neuron 109, 2535–2544
e2534 (2021).

64. Kolasa, M. et al. Unraveling psilocybin’s therapeutic potential:

behavioral and neuroplasticity insights in Wistar-Kyoto and Wistar
male rat models of treatment-resistant depression. Psychopharma-
cology https://doi.org/10.1007/s00213-024-06644-3 (2024).
65. Jefsen, O. et al. Psilocybin lacks antidepressant-like effect in the

Flinders Sensitive Line rat. Acta Neuropsychiatr. 31, 213–219 (2019).
66. Farinha-Ferreira, M., Miranda-Lourenco, C., Galipeau, C., Lenkei, Z.
& Sebastiao, A. M. Concurrent stress modulates the acute and post-
acute effects of psilocybin in a sex-dependent manner. Neuro-
pharmacology 110280. https://doi.org/10.1016/j.neuropharm.2024.
110280 (2024).

67. Kabsch, W. Xds. Acta Crystallogr. Sect. D Biol. Crystallogr. 66,

125–132 (2010).

68. Emsley, P. & Cowtan, K. Coot: model-building tools for molecular
graphics. Acta Crystallogr. Sect. D Biol. Crystallogr. 60, 2126–2132
(2004).

69. Liebschner, D. et al. Macromolecular structure determination using
X-rays, neutrons and electrons: recent developments in Phenix.
Acta Crystallogr. D Struct. Biol. 75, 861–877 (2019).

70. McCoy, A. J. et al. Phaser crystallographic software. J. Appl. Crys-

tallogr. 40, 658–674 (2007).

71. Murshudov, G. N. et al. REFMAC5 for the reﬁnement of macro-

molecular crystal structures. Acta Crystallogr. Sect. D Biol. Crys-
tallogr. 67, 355–367 (2011).

72. Perez-Riverol, Y. et al. The PRIDE database at 20 years: 2025 update.

Nucleic acids Res. 53, D543–D553 (2025).

Acknowledgements
We thank the staff from BL17B/BL18U1/BL19U1 beamline of the National
Facility for Protein Science in Shanghai (NFPS) at Shanghai Synchrotron
Radiation Facility for assistance during data collection. We thank the
animal facility and the core facility of the Zhongshan School of Medicine,
Sun Yat-Sen University. We thank Yubai Zhao for the technical support of
immunoﬂuorescence staining. This work was supported by grants from
the National Natural Science Foundation of China (31900435 to B.W.,

81972967 to W.-J.L., 82272312 to H.C.) and the Guangdong Science and
Technology Department (2023B1212060013 and 2020B1212030004 to
B.W. and W.-J.L). Fundamental Research Funds for the Central Uni-
versities, Sun Yat-Sen University (2023KYPT11 to B.W.). The 100 Top
Talent Programs of Sun Yat-Sen University (58000-12230029 to H.C.),
and the Shenzhen-Hong Kong-Macao Science and Technology Project
(Category C project) (SGDX20220530111403024, H.C.). Mass spectro-
metry analysis was performed by the Bioinformatics and Omics Center,
Sun Yat-Sen Memorial Hospital, Sun Yat-Sen University.

Author contributions
B.W., H.C., Y.Q., and W.-J.L. conceived the project. C.M., W.G., and Y.W.
expressed, puriﬁed, and grew the crystals. W.G., X.Z., Y.L., H.L., Q.Z.,
S.X., Y.Q., and C.M. performed the biochemical assays. W.G. and Y.W.
collected X-ray diffraction data. C.X. performed the behavior experi-
ments. B.W., H.C., S.X., and W.-J.L. solved and interpreted the structures
and experimental data. B.W., H.C., Y.Q., and W.-J.L. wrote and revised
the manuscript. B.W. supervised the structural and biochemical studies.
W.-J.L. supervised the in vivo experiments.

Competing interests
The authors declare no competing interests.

Additional information
Supplementary information The online version contains
supplementary material available at
https://doi.org/10.1038/s41467-025-58239-x.

Correspondence and requests for materials should be addressed to
Yuntan Qiu, Haitao Chen, Wei-Jye Lin or Baixing Wu.

Peer review information Nature Communications thanks Wulf Blanken-
feldt, Roberto Steiner, and the other, anonymous, reviewers for their
contribution to the peer review of this work. A peer review ﬁle is available.

Reprints and permissions information is available at
http://www.nature.com/reprints

Publisher’s note Springer Nature remains neutral with regard to jurisdic-
tional claims in published maps and institutional afﬁliations.

Open Access This article is licensed under a Creative Commons
Attribution-NonCommercial-NoDerivatives 4.0 International License,
which permits any non-commercial use, sharing, distribution and
reproduction in any medium or format, as long as you give appropriate
credit to the original author(s) and the source, provide a link to the
Creative Commons licence, and indicate if you modiﬁed the licensed
material. You do not have permission under this licence to share adapted
material derived from this article or parts of it. The images or other third
party material in this article are included in the article’s Creative
Commons licence, unless indicated otherwise in a credit line to the
material. If material is not included in the article’s Creative Commons
licence and your intended use is not permitted by statutory regulation or
exceeds the permitted use, you will need to obtain permission directly
from the copyright holder. To view a copy of this licence, visit http://
creativecommons.org/licenses/by-nc-nd/4.0/.

© The Author(s) 2025

Nature Communications |

 (2025) 16:2827

17

