Complete biosynthesis of noscapine and halogenated
alkaloids in yeast

Yanran Lia,1, Sijin Lib,1, Kate Thodeyc, Isis Trenchardc, Aaron Cravensb, and Christina D. Smolkeb,d,2

aDepartment of Chemical and Environmental Engineering, University of California, Riverside, CA 92521; bDepartment of Bioengineering, Stanford
University, Stanford, CA 94305; cAntheia Inc., Menlo Park, CA 94025; and dChan Zuckerberg Biohub, San Francisco, CA 94158

Edited by James C. Liao, Institute of Biological Chemistry, Academia Sinica, Taipei, Taiwan, and approved March 7, 2018 (received for review December
9, 2017)

Microbial biosynthesis of plant natural products from simple
building blocks is a promising approach toward scalable production
and modification of high-value compounds. The pathway for bio-
synthesis of noscapine, a potential anticancer compound, from
canadine was recently elucidated as a 10-gene cluster from opium
poppy. Here we demonstrate the de novo production of noscapine in
Saccharomyces cerevisiae, through the reconstruction of a biosyn-
thetic pathway comprising over 30 enzymes from plants, bacteria,
mammals, and yeast itself, including 7 plant endoplasmic reticulum
(ER)-localized enzymes. Optimization directed to tuning expression of
pathway enzymes, host endogenous metabolic pathways, and fer-
mentation conditions led to an over 18,000-fold improvement from
initial noscapine titers to ∼2.2 mg/L. By feeding modified tyrosine
derivatives to the optimized noscapine-producing strain we further
demonstrated microbial production of halogenated benzylisoquino-
line alkaloids. This work highlights the potential for microbial bio-
synthetic platforms to support the synthesis of valuable and novel
alkaloid compounds, which can advance alkaloid-based drug discov-
ery and development.

benzylisoquinoline alkaloids | metabolic engineering | plant alkaloids |
Saccharomyces cerevisiae

Noscapine is a natural phthalideisoquinoline alkaloid drug

that is extracted from opium poppy (Papaver somniferum).
Although present in opium, noscapine is a nonnarcotic drug that
has been used worldwide for over 50 years as a safe, nonnarcotic
antitussive. Noscapine has also been demonstrated to exhibit an-
ticancer activity (1, 2); however, the dose required for treating
cancer is much higher than when it is used as a cough suppressant
(1,000–2,250 mg/d for cancer treatment vs. 45–200 mg/d for cough
treatment). Due to its long-established safety record, noscapine is
a compelling candidate anticancer drug and has been used off-
label to treat cancers in some countries (3). In addition, a number
of noscapine derivatives have been shown to exhibit higher ther-
apeutic potential toward certain cancer cell lines resulting from
enhanced in vitro and in vivo activities or water solubility (4, 5).
Noscapine and its analogs (collectively referred to as noscapi-
noids) serve as an emerging class of microtubule-modulating an-
ticancer agents that exhibit fewer side effects than traditional
chemotherapy drugs (6).

All noscapinoids are currently derived from noscapine isolated
from the opium poppy. Tens of tons of noscapine are extracted
from thousands of tons of raw narcotic poppy straw annually to
meet medical and scientific demand (7). Industrial poppy farming
is susceptible to environmental factors such as pests, disease, and
climate, resulting in instability and variability in this geographically
concentrated supply chain (8). Relying on a narcotic supply chain
(i.e., opium poppy) to produce a nonnarcotic drug introduces
additional unnecessary hurdles and costs to procurement, which
are amplified due to the small size of the noscapinoid market
relative to the opioid market. Despite these challenges, poppy
farming remains the sole source of noscapinoids, in part because
chemical synthesis of these complex molecules is not commercially
competitive. A number of chemical syntheses of noscapine and

derivatives have been reported, but none are currently feasible for
large-scale production (5, 9).

A microbial-based manufacturing process for noscapinoids,
which are part of a larger class of benzylisoquinoline alkaloids
(BIAs), has the potential to address many of the challenges as-
sociated with the current poppy-based supply chain. Industrial
cultivation of microorganisms, such as the baker’s yeast Saccharomyces
cerevisiae, occurs over days, whereas poppies are annuals. Also,
because microbes are grown in closed fermentation vessels, the
production process is not susceptible to external environmental
factors and could provide greater consistency in product com-
position and impurity profiles across batches. Finally, by engineering
a microorganism that does not make the broader profile of nar-
cotic alkaloids present naturally in the opium poppy, one can remove
the unnecessary hurdles associated with a tightly controlled supply
chain.

In recent years, a number of pioneering studies have demon-
strated the reconstruction of complex plant-based pathways in
yeast, including the complete biosynthesis of strictosidine (10)
and opioids (11). A 10-gene cluster encoding enzymes respon-
sible for the biosynthesis of noscapine from (S)-scoulerine in
opium poppy was recently identified (12, 13). We reconstructed
the noscapine gene cluster in yeast to achieve microbial biosynthesis

Significance

We demonstrate yeast’s capacity for biosynthesis of complex
plant natural products by reconstructing a de novo noscapine
biosynthetic pathway and optimizing noscapine production to-
ward scalable manufacturing. Engineered strain contains 25 het-
erologous plant, bacteria, and mammalian genes and 6 mutant or
overexpressed yeast genes. The noscapine biosynthetic path-
way incorporates seven endomembrane-localized plant en-
zymes, highlighting yeast’s ability to functionally express and
properly localize large numbers of heterologous enzymes into
the endoplasm reticulum. Noscapine titers were improved by
18,000-fold (to low mg/L levels) via a combination of enzyme
engineering, pathway and strain engineering, and fermentation
optimization. We demonstrated that microbial fermentation can
be used to produce halogenated alkaloid derivatives, which can
ultimately serve as potential drug leads, through feeding amino
acid derivatives to strains.

Author contributions: Y.L., S.L., K.T., I.T., and C.D.S. designed research; Y.L., S.L., K.T., I.T.,
and A.C. performed research; Y.L., S.L., K.T., I.T., and C.D.S. analyzed data; and Y.L., S.L.,
and C.D.S. wrote the paper.

Conflict of interest statement: C.D.S. and Y.L. report a patent application published on
May 26, 2016, “Noscapinoid-Producing Microbes and Methods of Making and Using the
Same,” application WO 2016/081371.

This article is a PNAS Direct Submission.

Published under the PNAS license.

1Y.L. and S.L. contributed equally to this work.

2To whom correspondence should be addressed. Email: csmolke@stanford.edu.

This article contains supporting information online at www.pnas.org/lookup/suppl/doi:10.
1073/pnas.1721469115/-/DCSupplemental.

Published online April 2, 2018.

E3922–E3931 | PNAS | vol. 115 | no. 17

www.pnas.org/cgi/doi/10.1073/pnas.1721469115

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.of noscapine from (S)-canadine and norlaudanosoline (14). Sepa-
rately, we engineered the first part of the biosynthetic pathway from
glucose to (S)-reticuline (15) and (S)-reticuline to (S)-canadine (16)
into yeast (Fig. 1A). These earlier studies suggested that yeast might
be capable of synthesizing noscapinoids via fermentation of simple
carbon and nitrogen sources. However, functionally expressing the

more than 25 heterologous enzymes required for complete bio-
synthesis of these complex molecules is nontrivial because of the
decreases in titer observed with each additional enzymatic step. In
addition, microbial expression of multiple endomembrane-localized
plant enzymes, such as cytochrome P450s, has remained challeng-
ing (17), and full reconstruction of the noscapine biosynthetic

S
U
L
P

S
A
N
P

A

Sugar

E4P
+
PEP

MeO

HO

HO

MeO

(S)-Reticuline

BBE

H

MeO

HO

Tkl1p

Increased pentose phosphate
pathway flux to E4P

CPR

Redox partner for
cytochrome P450 enzymes

*

5 BH4 Biosynthetic,
recycling and salvage enzymes

B

+ESI MRM 414(cid:2)220

Aro4pQ166K

DAHP

Aro1p

Aro2p

Aro7pT226I

Tyr1p

4-HPP

NMe

6OMT

CNMT

NMCH

4’OMT

HO

HO

NCS

NH

HO

(S)-Norcoclaurine

Aro8p
Aro9p

HO

CO2H

NH2

L-Tyrosine

OH

TyrHWR*

NH2

DODC

HO

HO

CO2H

NH2

2

3

4

5

Time (minute)

Aro10p

4-HPAA
+

O

HO

HO

Dopamine

L-DOPA

MeO

N

S9OMT

HO

OH

OMe

N

H

CAS

OMe

N

H

(S)-Canadine

TNMT

OMe

OMe

O

O

H

N

CYP82Y1

O

O

N

H

OH

OMe

OMe

OMe

(S)-Scoulerine

(S)-Tetrahydrocolumbamine

OMe

(S)-N-methylcanadine

OMe
(S)-1-Hydoxy-N-methylcanadine

NMe

CHO

CYP82X1

OMe

H

HO

AcO

O

O

NMe

AT1

OMe

H

HO

AcO

CYP82X2

O

O

NMe

HO

H

HO

4'-O-Desmethyl-
3-O-acetylpapaveroxine

OMe

1-Hydroxy-13-O-acetyl-
N-methylcanadine

OMe

1,13-Dihydroxy-
N-methylcanadine

OMe

OMe

O

O

O

O

O

O

O

O

NMe
O

O

H

OH

SDR1

O

O

NMe
O

OH

CXE1

H

HO

OMe

OMe

OMe

OMe

Narcotoline

Narcotolinehemiacetal

N4’OMT

N4’OMT

NMe

O

O

H
OMe

SDR1

OMe

Noscapine

OMe

O

O

NMe

O

OH

H
OMe

OMe

OMe

Narcotinehemiacetal

Fig. 1. De novo noscapine biosynthesis in S. cerevisiae. (A) The proposed biosynthetic pathway of noscapine in yeast. Block arrows indicate enzyme-catalyzed
steps. Light gray arrows, unmodified yeast enzymes; dark gray arrows, overexpressed and modified yeast enzymes; purple arrows, mammalian (Rattus
norvegicus) enzymes; orange arrows, bacterial (Pseudomonas putida) enzymes; green arrows, plant (Papaver somniferum, Coptis japonica) enzymes. Aro10p,
phenylpyruvate decarboxylase; Aro1p, pentafunctional arom enzyme; Aro2p, bifunctional chorismate synthase and flavin reductase; Aro4pQ166K, DAHP
synthase; Aro7pT226I, chorismate mutase; Aro8p, aromatic aminotransferase I; Aro9p, aromatic aminotransferase II; AT1, 1,13-dihydroxy-N-methylcandine 13-
O-acetyltransferase; BBE, berberine bridge enzyme; BH4, 5,6,7,8-tetrahydrobiopterin; CAS, canadine synthase; CNMT, coclaurine N-methyltransferase; CPR,
cytochrome P450 reductase; CXE1, 3-O-acetylpapaveroxine carboxylesterase; CYP82X1, 1-hydroxy-13-O-acetyl-N-methylcanadine 8-hydroxylase; CYP82X2, 1-
hydroxy-N-methylcanadine 13-hydroxylase; CYP82Y1, 1-hydroxy-N-methylcanadine synthase; DAHP, 3-deoxy-D-arabino-2-heptulosonic acid 7-phosphate;
DODC, L-dopa decarboxylase; E4P, erythrose 4-phosphate; MT2/MT3, narcotoline-4′-O-methyltransferase. NCS, (S)-norcoclaurine synthase; NMCH, N-meth-
ylcoclaurine hydroxylase; PEP, phosphoenolpyruvate; S9OMT, scoulerine 9-O-methyltransferase; SDR1, short-chain dehydrogenase/reductase; Tkl1p, trans-
ketolase; TNMT, tetrahydroprotoberberine cis-N-methyltransferase; Tyr1p, prephenate dehydrogenase; TyrHWR, feedback inhibition-resistant tyrosine
hydroxylase (R37E, R38E, W166Y); 4-HPAA, 4-hydroxyphenylacetaldehyde; 4-HPP, 4-hydroxyphenylpyruvate; 4′OMT, 3′-hydroxy-N-methylcoclaurine 4′-O-
methyltransferase; and 6OMT, norcoclaurine 6-O-methyltransferase. (B) EIC MRM using noscapine’s highest characteristic precursor ion/product ion
transition (414 → 220) of (i) 0.5 μg/L noscapine standard, (ii) CSY1149 media, and (iii ) CSY1150 media. CSY1150 was cultured in SD with 2% dextrose in the
presence of 10 mM ascorbic acid at 25 °C for 72 h. Growth medium was analyzed by LC–MS/MS MRM. Traces are representative of three biological
replicates.

L
A
C
I
G
O
L
O
I
B
D
E
I
L
P
P
A

S
E
C
N
E
I
C
S

Li et al.

PNAS | vol. 115 | no. 17 | E3923

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.pathway requires expression of seven membrane-localized enzymes,
including five plant cytochrome P450s.

We demonstrate the de novo production of the anticancer
alkaloid noscapine via a single engineered yeast strain. The initial
yeast strain was engineered to express 29 enzymes from plant, bac-
teria, mammals, and yeast and produced ∼120–230 ng/L noscapine.
Through engineering rate-limiting pathway enzymes, optimizing
enzyme expression levels, introducing modifications to the endog-
enous yeast metabolism to enhance NADPH supply, and opti-
mizing fermentation conditions, we improved noscapine titers by
over 18,000-fold to ∼2.2 mg/L. We also demonstrated the bio-
synthesis of halogenated benzylisoquinoline alkaloid molecules by
feeding tyrosine derivatives to the optimized noscapine-producing
strain. Further optimization of the pathway and process will enable
scale up to a commercially relevant, cost-effective fermentation
process, offering a supply chain for noscapine and related mole-
cules that does not rely on opium poppy farming. In addition, the
yeast-based platform also supports the synthesis of novel benzy-
lisoquinoline alkaloids and can be used to advance drug discovery,
particularly for new chemotherapeutics.

Results
Construction of a de Novo Noscapine Biosynthetic Pathway in Yeast.
We started the construction of a de novo biosynthetic pathway to
noscapine with two previously described platform strains that
produce (S)-reticuline (11, 15), a key biosynthetic intermediate to
many benzylisoquinoline alkaloids including the noscapinoids. The
reticuline-producing strains encode the expression of 17 enzymes
responsible for the biosynthesis of reticuline across five genetic
modules (Fig. 1B and Fig. S1). The five modules were integrated
into select chromosomal loci in a wild-type haploid strain CEN.
PK2-1D. Module I is designed to increase accumulation of L-tyrosine
and 4-hydroxyphenylacetaldehyde (4-HPAA) and encodes the
overexpression of four yeast proteins—mutants of 3-deoxy-D-
arabino-2-heptulosonic acid 7-phosphate (DAHP) synthase and
chorismate mutase (Aro4pQ166K and Aro7pT226I) that are less
susceptible to feedback inhibition by L-tyrosine, and transketolase
(TKL1p) and phenylpyruvate decarboxylase (Aro10p). Module II
is designed to synthesize and recycle tetrahydrobiopterin (BH4),
the cofactor for tyrosine hydroxylase (TyrH), and encodes expres-
sion of four proteins from Rattus norvegicus—sepiapterin reductase
(SepR), 6-pyruvoyl tetrahydrobiopterin synthase (PTPS), quinonoid
dihydropteridine reductase (QDHPR), and pterin carbinolamine
dehydratase (PCD). Module III is designed to synthesize norco-
claurine and encodes expression of four proteins—a mutant (R37E,
R38E, and W166Y) of tyrosine hydroxylase (TyrHWR) that is more
resistant to inhibition by L-tyrosine and catecholamines and the
BH4 salvage enzyme dihydrofolate reductase (DHFR) from R.
norvegicus, DOPA decarboxylase (DoDC) from Pseudomonas
putida, and norcoclaurine synthase (NCS) from Coptis japonica.
Module IV is designed to synthesize reticuline and encodes expression
of five plant proteins—norcoclaurine 6-O-methyltransferase (6OMT),
coclaurine-N-methyltransferase (CNMT), 4′-O-methyltransferase
(4′OMT), cytochrome P450 reductase (CPR) from P. somniferum,
and N-methylcoclaurine hydroxylase (NMCH) from Eschscholzia
californica. Finally, module V encodes the overexpression of three
identified bottleneck proteins—TyrHWR, 4′OMT, and NCS—and
was integrated either to knockout the native ZWF1 gene (zwf1Δ;
CSY1061) or into a separate locus (CSY1060).

Initial noscapine-producing strains were constructed by intro-
ducing 12 additional plant enzymes into the reticuline-producing
platform strains (CSY1060 and CSY1061) encoded across three
additional genetic modules. Module VI encodes the expression of
canadine synthase (CAS) from Coptis japonica and berberine bridge
enzyme (BBE), scoulerine 9-O-methyltransferase (S9OMT), and
an N-terminal engineered variant of 1-hydroxy-N-methylcanadine
synthase (CYP82Y1A) from P. somniferum. Module VII encodes
the expression of tetrahydroprotoberberine cis-N-methyltransferase

(TNMT), 1-hydroxy-13-O-acetyl-N-methylcanadine 8-hydroxylase
(CYP82X1), 3-O-acetylpapaveroxine carboxylesterase (CXE1), and
narcotoline-4′-O-methyltransferase (I) (MT2) from P. somnife-
rum. Finally, module VIII encodes the expression of 1-hydroxy-
N-methylcanadine 13-hydroxylase (CYP82X2), 1,13-dihydroxy-N-
methylcandine 13-O-acetyltransferase (AT1), short-chain dehydrogenase/
reductase (SDR1), and narcotoline-4′-O-methyltransferase (II)
(MT3) from P. somniferum. The introduction of these three genetic
modules into chromosomal loci in CSY1060 and CSY1061 resulted
in two base noscapine-producing strains (CSY1149: zwf1Δ and
CSY1150: ZWF1).

We assayed noscapine production by growing yeast strains
in synthetic defined medium (SD) supplemented with 10 mM
ascorbic acid for 72 h at 25 °C. Because the intracellular con-
centrations of most metabolites along the noscapine biosynthetic
pathway are relatively low (14), we used the extracellular titer to
indicate the production of noscapine and pathway intermediates
from the engineered yeast strains. The growth media was analyzed
for BIA molecules by liquid chromatography coupled with tandem
mass spectrometry (LC–MS/MS). The synthesis of noscapine was
confirmed through comparison with the chemical reference stan-
dard (Fig. 1B). The base noscapine-producing strains, incorpo-
rating modules I–VIII, produced 120.0 ng/L (CSY1149; zwf1Δ)
and 227.1 ng/L (CSY1150; ZWF1) of noscapine. Although earlier
work indicated that the ZWF1 knockout leads to enhanced pro-
duction of reticuline (11), our studies indicate that this deletion is
not advantageous for production of noscapine. ZWF1 encodes a
glucose-6-phosphate dehydrogenase, which catalyzes the oxidation
of glucose-6-phosphate and synthesizes NADPH (18). Plant cyto-
chrome P450s require NADPH for electron transfer, and the bio-
synthesis of noscapine includes five such enzymes, whereas the
biosynthesis of reticuline employs only one. Thus, the NADPH
requirement for a noscapine-producing strain is expected to be
substantially greater than that for a reticuline-producing strain. We
hypothesize that in our two constructed noscapine strains (CSY1149
and CSY1150), any positive effect on reticuline production resulting
from deletion of ZWF1 in CSY1149 was small compared with the
negative effect on the downstream pathway to noscapine caused by
removal of this NADPH-generating enzyme. Therefore, CSY1150
was selected as the base noscapine-producing strain to further engi-
neer for enhanced noscapine biosynthesis.

Increased Noscapine Production Through Genetic Modifications That
Push Flux into the Pathway. We first focused on increasing noscapine
production by improving the activities of key bottleneck enzymes in
the early part of the pathway to convert more precursor molecules
into the 1-benzylisoquinoline backbone. NCS catalyzes the conden-
sation reaction between dopamine and 4-HPAA to produce norco-
claurine. Earlier studies indicate substantial accumulation of dopamine
in the reticuline-producing platform strain (11), suggesting that
NCS activity is a key bottleneck in pushing more flux into the
BIA pathway. Recent investigations on NCS indicate that the N-
terminal signal peptide on some NCS variants may have a deleterious
effect on enzyme function (19). Thus, we designed an NCS variant
with the first 24 amino acids deleted and used a CRISPR/CAS9 ge-
nomic editing strategy to directly replace the original NCS variants in
CSY1150 with this modified NCS variant (CSY1151; Table S1) (20).
Production of noscapine from the strain harboring the modified NCS
variant increased approximately eightfold to 1.9 μg/L (Fig. 2A).

In addition, the tyrosine hydroxylase (TyrH) used in the recon-
structed pathway is a variant from R. norvegicus and harbors mutations
R37E, R38E, and W166Y (TyrHWR) to reduce substrate inhibition
(11, 15). Tyrosine hydroxylase (TyrH) catalyzes the conversion of
tyrosine to L-DOPA, which is one of the first steps in the early BIA
biosynthetic pathway. Earlier studies observed nearly complete con-
version of L-DOPA in the reticuline-producing platform strain,
suggesting that TyrH activity also limits flux into the BIA pathway
(11). We designed a codon-optimized version of this TyrH variant

E3924 | www.pnas.org/cgi/doi/10.1073/pnas.1721469115

Li et al.

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.and used a CRISPR/CAS9 cloning strategy to directly replace the
original TyrHWR variant in CSY1151 with this codon-optimized
variant (CSY1152; Table S1). Production of noscapine from the
strain harboring the codon-optimized TyrHWR variant increased a
further ∼2.5-fold to 4.7 μg/L (Fig. 2A).

Increased Noscapine Production Through Genetic Modifications That
Regenerate a Key Cofactor to Improve the Efficiency of Limiting
Pathway Enzymes. Noscapine biosynthesis requires five plant cy-
tochrome P450s that each utilize NADPH for electron transfer.
The decrease observed in noscapine production upon deletion of
ZWF1 indicates that the supply of NADPH may be critical to the
enzymatic efficiency of the plant cytochrome P450s. In addition
to enhanced supply of NADPH, previous investigations also
ratio can improve
demonstrate that a higher NADPH/NADP
the activity of cytochrome P450s (21). We thus attempted to
increase the pool of available NADPH by introducing an extra
copy of selected yeast enzymes that can regenerate NADPH (Fig.
S2), specifically, NADH kinase (Pos5p), three isocitrate reduc-
tases (Idp1-3p), pyruvate decarboxylase (Pdc6p), two aldehyde

+

A

/

)
L
g
μ
(

r
e
t
i
T

i

e
n
p
a
c
s
o
N

20.0

15.0

10.0

5.0

0.0

CSY
1149

CSY
1150

CSY
1151

CSY
1152

CSY
1153

Δzwf1

NCS N-terminus
Fixation

TyrH Codon
Optimization

NADPH Supply/
CYP82X2/PsS9OMT

+

_

-

-

-

_

-

-

-

+

-

-

-

+

+

-

-

+

+

+

B

/

)
L
g
μ
(

r
e
t
i
T

i

e
n
p
a
c
s
o
N

6.0

4.0

2.0

0.0

CSY1152 +

y
t
p
m
E

i

d
m
s
a
l
p

p
5
s
o
P

p
1
p
d

I

p
2
p
d

I

p
3
p
d

I

p
6
c
d
P

p
4
d
A

l

p
6
d
A

l

p
1
r
y
T

Fig. 2. Strain optimization for enhanced noscapine production in yeast.
(A) Noscapine titers from yeast strains engineered with pathway and en-
zyme improvements. (B) Optimization of noscapine production through
NADPH regeneration. S. cerevisiae endogenous genes were expressed from
a low-copy plasmid in CSY1152. All strains were cultured in SD with 2%
dextrose in the presence of 10 mM ascorbic acid at 25 °C for 72 h. Error bars
represent SD of three biological replicates.

dehydrogenases (Ald4p and Ald6p), and prephenate dehydrogenase
(Tyr1p). The genes encoding each enzyme were cloned into a
low-copy plasmid regulated by a strong GPD promoter. The
noscapine-producing strain CSY1152 was transformed individu-
ally with each plasmid and noscapine production was measured.
Noscapine production levels were assayed and compared with
CSY1152 harboring an empty plasmid. All of the candidate NADPH-
generating enzymes other than Idp1p and Ald4p resulted in more
efficient synthesis of noscapine, whereas overexpression of Ald6p
and Tyr1p led to the largest and statistically significant improvements
in noscapine production, ∼1.4 fold (Fig. 2B). Tyr1p is also involved
in the production of tyrosine and 4-hydroxyphenylacetaldehyde
(4-HPAA) (Fig. S2), which are key precursors of the noscapine
pathway (Fig. 1A). The noscapine titer of CSY1152 overexpressing
both Ald6p and Tyr1p exhibits a higher noscapine titer than over-
expression of Ald6p or Tyr1p alone in this strain (Fig. S2).

Earlier work indicated that the activities of CYP82X2 and
S9OMT limit pathway flux to noscapine (14). Thus, we designed a
ninth genetic module (IX) to enhance noscapine production. Module
IX is designed to regenerate NADPH to improve the activity of
cytochrome P450s along the pathway and pull more flux through
the pathway and encodes four proteins—Ald6p and Tyr1p from
yeast and CYP82X2 and S9OMT from P. somniferum. The in-
troduction of this module into chromosomal loci in CSY1152
resulted in an enhanced noscapine-producing strain (CSY1153),
from which noscapine production levels increased approximately
threefold to 15.4 μg/L (Fig. 2A). Quantification of the pathway
intermediates synthesized by CSY1152 and CSY1153 indicated
that more scoulerine is converted to tetrahydrocolumbamine
and 1-hydroxy-N-methylcanadine accumulates to a lower level in
CSY1153 compared with CSY1152, consistent with the incor-
poration of additional copies of PsS9OMT and CYP82X2 in
CSY1153 (Fig. S3).

Media Optimization Leads to Substantial Improvements in Noscapine
Production. We next explored the effect of various base media
and carbon sources on noscapine production from the highest-
producing noscapine strain CSY1153. Specifically, synthetic de-
fined medium (SD) and complex medium (Yeast extract and
peptone, YP) were investigated with a number of carbon sources
(2% wt/vol), including dextrose, galactose, sucrose, trehalose,
and glycerol. Across all of the carbon sources examined, YP led
to a pronounced increase in noscapine titers (SD with 2% dex-
trose, 15.4 μg/L; YP with 2% dextrose, 293.9 μg/L; SD with 2%
galactose, 11.9 μg/L; YP with 2% galactose, 188.0 μg/L; SD with
2% sucrose, 10.5 μg/L; YP with 2% sucrose, 118.2 μg/L; SD with
2% trehalose, 32.7 μg/L; YP with 2% trehalose, 805.8 μg/L; SD
with 2% glycerol, 43.2; YP with 2% glycerol, 496.3 μg/L) (Fig. 3).
Under the best media condition (YP supplemented with 2%
trehalose) production of noscapine was increased over 50-fold
from 15.4 to 805.8 μg/L.

The positive effect of YP on noscapine production relative to
SD is likely to be a result of the higher concentrations of the
noscapine precursor tyrosine and other nutrients. However, the
effects of carbon sources varied; trehalose, a disaccharide com-
posed of 2 α-glucose, afforded highest noscapine production levels
in SD and YP. Galactose and sucrose, also disaccharide sugars,
resulted in lower production of noscapine in SD and YP. Dextrose
led to the intermediate noscapine production level in SD and in
YP. Glycerol, the only nonsugar carbon source examined, affor-
ded substantially higher noscapine titer in SD and YP compared
with dextrose, sucrose, and galactose. Quantification of the
pathway intermediates also implies more efficient conversion
from reticuline, scoulerine, and tetrahydrocolumbamine to
canadine and downstream pathway metabolites when utilizing
glycerol as the carbon source (Fig. S4).

The effect of higher carbon concentration (10% wt/vol) was
investigated with SD and YP as the base medium. The cells grew

S
U
L
P

S
A
N
P

L
A
C
I
G
O
L
O
I
B
D
E
I
L
P
P
A

S
E
C
N
E
I
C
S

Li et al.

PNAS | vol. 115 | no. 17 | E3925

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.

SD

YP

/

)
L
g
m

(

r
e
t
i
T

i

e
n
p
a
c
s
o
N

1

0.8

0.6

0.4

0.2

0

Sugar

Dextrose

Galactose

Sucrose

Trehalose

Glycerol

% (w/v)

2

10

2

10

2

10

2

10

2

10

of aggregated proteins both in vitro and in cells (31, 32). Apart
from being able to stabilize the membrane and facilitate the correct
folding of proteins, glycerol utilization in S. cerevisiae is also asso-
ciated with the regeneration of NADPH (Fig. 4A): an NADP-
dependent glycerol dehydrogenase (Gcy1p and Ypr1p) catalyzes
the conversion of glycerol to dihydroxyacetone (DHA), which is
subsequently phosphorylated to DHAP via a DHA kinase (Dak1p
and Dak2p) (33). We compared noscapine production at different
glycerol concentrations (0, 2, 5, 8, and 10%). The media in these
experiments was maintained at 12% total carbon by including 2%
dextrose (to support efficient cell growth in the early stages of
fermentation), and the remaining carbon up to 12% was made up
with trehalose. The cells grew to the same density under all media
conditions (OD600 in the range of 22.83 ± 0.72–24.79 ± 0.86), and
noscapine titer positively correlated with glycerol concentration in
the media (Fig. 4B). The highest noscapine titer (1.71 ± 0.03 mg/L)
was observed from YP media supplemented with 2% dextrose and
10% glycerol, likely resulting from availability of an efficiently utilized
carbon source supporting early cell growth, protein stabilization,

Fig. 3. Media optimization for enhanced noscapine production in yeast.
Noscapine titers were measured from CSY1153 in different medium and
carbon sources. Base medium includes SD (synthetic complete) and YP (yeast
extract and peptone). Carbon sources include 2% or 10% of dextrose, ga-
lactose, sucrose, trehalose, and glycerol. The strain was cultured at 25 °C for
72 h in the indicated media composition with 10 mM ascorbic acid. Error bars
represent SD of at least three biological replicates.

A

to a similar density across the various carbon sources in SD
(OD600 ∼ 4.5–7) and YP (OD600 ∼ 23–32). In SD, higher concen-
tration (10% wt/vol) of dextrose leads to a decrease in noscapine
titer, whereas enhanced concentrations of other sugars generally
lead to a slight increase in noscapine titer (dextrose, 1.7 μg/L;
galactose, 14.3 μg/L; sucrose, 25.7 μg/L; trehalose, 43.2 μg/L)
(Fig. 3). The data indicate that high concentration of dextrose in
the defined SD media may inhibit the activities of certain enzymes
associated with noscapine production, such as enzymes involved in
aromatic amino acid biosynthesis (22), whereas high concentra-
tion of other sugars does not affect the production of noscapine as
significantly. In YP, higher concentration of sugars (10% dextrose,
galactose, sucrose, and trehalose) leads to reduced noscapine
production (32.0, 103.8, 9.2, and 732.8 μg/L, respectively) (Fig. 3).
The data also show that high concentration of trehalose and ga-
lactose in the complex YP media does not exhibit as deleterious
an effect to noscapine production compared with the other sugars.
The reduction in noscapine production under high concentrations
of sugars (especially glucose and sucrose) is likely a result of (i) faster
growth rates that may lead to misfolding of heterologous en-
zymes (or the relatively slower growth rate in high concentrations
of nonfermentive carbon sources, compared with glucose and sucrose,
may result in comparatively better enzyme folding) (23) and (ii)
repressive effects on yeast metabolism leading to a redirection of
metabolic production away from noscapine bioproduction related
metabolism, such as aromatic amino acid biosynthesis (22, 24).
In contrast, the higher concentrations of the nonsugar carbon
source, glycerol, enhanced noscapine production by 243% from
168.9 to 409.8 μg/L in SD and 127% from 496.3 to 633.6 μg/L in
YP (Fig. 3).

We continued to investigate the role glycerol plays in noscapine
synthesis and further optimize medium composition. Glycerol may
increase noscapine production through a number of mechanisms.
For example, natural osmolytes (e.g., trehalose, sucrose, and glyc-
erol) have been reported to promote stabilization of recombinant
proteins (25) and cellular membranes (26–28). Additionally, glyc-
erol and trehalose have also been reported to facilitate the correct
folding of nascent polypeptides (29, 30) and thus have been utilized
as chemical chaperones to reverse the misfolding or mislocalization

Gcy1p

Gpd1p, Gpd2p

Gut2p

D
a
k
1
p

G
u
t
1
p

2.0

1.5

1.0

0.5

0.0

B

/

)
L
g
m

(

r
e
t
i
T

i

e
n
p
a
c
s
o
N

Glycerol
(% w/v)

Trehalose
(% w/v)

0

0

0

10

2

8

5

5

8

2

10

0

Fig. 4. Effect of glycerol on noscapine production. (A) Schematic illustrating
the glycerol utilization mechanism. The pathway facilitating NADPH re-
generation is highlighted in blue, and the pathway converting glycerol to
dihydroxyacetone phosphate is highlighted in gray. (B) Noscapine titers from
CSY1153 under different glycerol concentrations. Ten percent glycerol and
trehalose at the indicated ratios were supplemented into YP with 2% dex-
trose. The strain was cultured at 25 °C for 72 h in the indicated media
composition with 10 mM ascorbic acid. Error bars represent SD of three bi-
ological replicates.

E3926 | www.pnas.org/cgi/doi/10.1073/pnas.1721469115

Li et al.

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.and NADPH regeneration. However, CSY1153 exhibits a lower
noscapine titer in YP media supplemented with 2% dextrose and
10% trehalose (0.44 mg/L), compared with when cultured in YP
media supplemented with only 10% trehalose (0.73 mg/L), which
is likely due to glucose repression caused by the 2% dextrose
(22). In contrast, CSY1153 exhibits a higher noscapine titer in
YP media supplemented with 2% dextrose and 10% glycerol
(1.71 mg/L), compared with when cultured in YP media sup-
plemented with only 10% glycerol (0.63 mg/L). These data indicate
that slower growth rate may not be the main reason for improved
noscapine titers when using glycerol as the carbon source. The
effect of higher concentration of glycerol (15, 20, and 25% glycerol
supplemented to YP with 2% dextrose) was subsequently exam-
ined and revealed that concentrations of glycerol higher than 10%
are not beneficial to noscapine production (Fig. S5).

The optimized noscapine production media was utilized to
grow the highest noscapine producing strain (CSY1153) in a 250-mL
shake flask to model enhanced oxygen transfer in a larger culture
vessel. The maximum noscapine titer was further increased to 2.21 ±
0.35 mg/L after 72 h of fermentation and remained stable after an
additional 24 h of growth. The increase in noscapine titer observed
in the shake flask experiment may be due to enhanced oxygen
transfer in this culture vessel flask compared with the 96-deep
well plate. The results from the shake flask experiments reveal
that noscapine production is not coupled with biomass production,
because the maximum cell density was reached on day 2, whereas
over 50% of the accumulated noscapine was produced on day 3.
Our work highlights the central role of optimizing media and
fermentation conditions to improve bioprocesses for complex
plant natural products. Our media optimization efforts resulted in
an ∼300-fold increase in noscapine titers. Our work also demon-
strates that glycerol substantially enhances noscapine production,
possibly by regenerating the essential cofactor NADPH for cyto-
chrome-P450–catalyzed reactions and by stabilizing heterologous
proteins localized to subcellular membranes.

Biosynthesis of Halogenated BIA Derivatives Through Feeding Tyrosine
Derivatives. Chemical transformation, such as functional group in-
terconversion and addition (e.g., acylation, alkylation, and halo-
genation), plays a critical role in drug candidate preparation in
pharmaceutical synthesis (34). Noscapine derivatives have shown
higher therapeutic potential toward certain cancer cell lines (5,
35), indicating a promising approach to enhance the bioactivity of
noscapine-derived anticancer agents. However, the number and
chemical diversity of noscapine derivatives are limited, due to the
lack of commercially available noscapine synthetic intermediates
and the structural complexity and chemical reactivity of noscapine
(5). The reconstruction of the complete biosynthetic pathway to
noscapine in yeast offers a versatile platform to provision previously
inaccessible noscapine intermediates and to enable the de novo
biosynthesis of unique noscapine derivatives (Fig. 5A).

We probed the flexibility of the noscapine biosynthetic path-
way to convert tyrosine analogs fed to the engineered yeast
during fermentation. Sixteen tyrosine derivatives were supplemented
into a tyrosine-free SD growth media (Table S4). No significant dif-
ference was observed in the growth rates of the highest-producing
noscapine strain (CSY1153) in SD when supplemented with tyrosine
or tyrosine analogs at the same concentration. The growth media
was analyzed for derivatized BIA molecules by high-resolution
liquid chromatography quadrupole time-of-flight mass spectrom-
etry (LC-QTOF). The exact masses of the expected products with
the incorporation of tyrosine derivatives were utilized to filter and
analyze the LC-QTOF chromatographs.

We observed peaks that match the exact masses of 8-fluoro-
reticuline (Fig. 5B) and 8-chloro-reticuline (Fig. 5C), when feeding
3-fluoro-tyrosine and 3-chloro-tyrosine, respectively. The detection
of peaks matching the exact mass of 8-fluoro- and 8-choloro-
reticuline implies that these molecules were synthesized from fed

3-fluoro- and 3-chloro-tyrosine, respectively, via oxidation by TyrH
and subsequent incorporation into the biosynthetic pathway by
DODC, NCS, 6OMT, CNMT, NMCH, and 4′OMT toward reticuline
(Fig. 5A). To confirm that the eight-substituted reticuline molecules
were formed via uptake and transformation of tyrosine derivatives
by our noscapine strains, we searched for additional pathway inter-
mediates and observed 8-halogen substituted (S)-N-methylcoclaurine
(Fig. 5 D and E). In addition, when fed with a third tyrosine
derivative, 3-iodo-tyrosine, a peak that matches the exact mass of
8-iodo substituted (S)-N-methylcoclaurine (Fig. 5F) was observed.
Notably, peaks that match the exact mass of 8-iodo substituted
reticuline were not detected, suggesting that flux of this derivatized
tyrosine molecule into the reticuline pathway is incomplete. Fur-
thermore, conversion of the derivatized 1-benzylisoquinoline
intermediates to the downstream berberine, secoberberine, and
phthalideisoquinoline alkaloids was not detected. The results
highlight that the reconstructed noscapine pathway is capable of
incorporating tyrosine derivatives to generate reticuline deriva-
tives, demonstrating the possibility of the substrate-feeding approach
in synthesizing novel BIA derivatives. The lack of conversion to
the downstream BIAs in the noscapine pathway may be due to
the limited promiscuity of the native enzymes, low reaction effi-
ciency, and low abundance of the substrate. Thus, the biosynthesis
of halogenated noscapinoids could be achieved through two
routes: (i) engineering of tailoring enzymes, such as halogenases,
to accept noscapinoids as substrates and (ii) engineering limiting
enzymes in the noscapine pathway, such as BBE, to exhibit increased
activity on halogenated substrates. In addition, further optimization
of the yeast biosynthetic platform will allow for increased synthesis
efficiency of the halogenated intermediates, which could ultimately
allow more flux to be directed to the downstream part of the noscapine
pathway. Therefore, future efforts directed to enzyme engineering
and further pathway improvements may address these limitations
and enable the production of a broad array of novel noscapinoid
derivatives.

Discussion
We have demonstrated yeast-based fermentation of noscapine
and related pathway intermediates from simple carbon and nitrogen
sources. Our pathway engineering and optimization efforts resulted
in a yeast strain engineered to express 31 enzymes, including 25
heterologous pathway enzymes taken from plants, mammals, and
bacteria and 6 mutant or overexpressed yeast enzymes, that pro-
duced noscapine titers up to 15.4 μg/L. Further highlighting yeast’s
ability to serve as a platform host for complex plant natural product
pathways, 7 of the 25 heterologous enzymes require proper an-
choring and folding within the endoplasm reticulum membrane for
function, including five plant cytochrome P450s, a plant cytochrome
P450 reductase, and berberine bridge enzyme (BBE). Media and
growth optimization efforts further enhanced noscapine titers by
∼140-fold to ∼2.2 mg/L. Although titers will need to be further
increased by ∼100–1,000 fold to realize a commercially viable
manufacturing process at scale, our initial work highlights the
feasibility of using yeast fermentation for supplying complex plant
alkaloids for global demand with further improvement of the pro-
cess. We anticipate that such improvements will be realized through
a combination of enzyme and strain engineering and fermentation
process optimization. We also show the value of such fermentation
processes for realizing alkaloid derivatives through feeding modified
substrates to the engineered cells.

Our results indicate that NADPH balance is likely an impor-
tant factor in optimizing noscapine production in yeast, likely
due to the relatively large number of pathway enzymes requiring
this cofactor (e.g., cytochrome P450s). Although prior work had
shown that a ZWF1 knockout strain results in higher reticuline
production (15), we observed higher noscapine titers in strains
harboring the intact ZWF1 gene. This observation is consistent
with prior work describing production of strictosidine in yeast,

Li et al.

PNAS | vol. 115 | no. 17 | E3927

S
U
L
P

S
A
N
P

L
A
C
I
G
O
L
O
I
B
D
E
I
L
P
P
A

S
E
C
N
E
I
C
S

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.A

X=H Native Pathway
X=F, Cl, I

3-X-tyrosine

DODC

3-X-L-DOPA

TyrH

8-X-(S)-Reticuline

8-X-(S)-N-
Methylcoclaurine

B
+ESI EIC (348.1611)

D
+ESI EIC (318.1505)

348.1606

328.1543

432.2806

300

350

400
m/z+

450

500

318.1497

349.1830

478.7628

300 350 400 450 500
m/z+

F
=
X

+

ii

i

2.0

2.2

2.4

2.6

1.6

2.0

2.4

2.8

ii

i

3-X-Dopamine

4-HPAA

Time (minute)

Time (minute)

NCS

C
+ESI EIC (364.1316)

E
+ESI EIC (334.1210)

8-X-(S)-Norcoclaurine

6OMT
CNMT

ii

i

342.1706

364.1313

323.1761

328.1532

334.1198

300 350 400 450 500
m/z+

300 350 400 450 500
m/z+

l

C
=
X

ii

i

2.0

2.2
Time (minute)

2.4

2.6

1.6

2.0

2.4

2.8

Time (minute)

8-X-(S)-N-
Methylcoclaurine

NMCH
4’OMT

8-X-(S)-Reticuline

F
+ESI EIC (426.0566)

342.1702

314.1753

426.0561

300 350 400 450 500
m/z+

I

=
X

ii

i

1.6

2.4

2.0
Time (minute)

2.8

Fig. 5. Proposed tyrosine derivative incorporation mechanism and LC–MS analyses of noscapine producing strain fed tyrosine derivatives. (A) Proposed
biosynthetic pathway of 8-halo-(S)-reticuline from 3-halo-tyrosine when X = F, Cl, or I and native biosynthetic pathway of reticuline from typrosine when X = H.
The high-resolution EIC of CSY1153 fed with (i) tyrosine and (ii) the corresponding 3-halo-tyrosine. Mass spectra of eight-substituted-(S)-N-Methylcoclaurine
synthesized from (B) 3-fluro-tyrosine, (C) 3-chloro-tyrosine, and (D) 3-iodo-tyrosine and eight-substituted-(S)-reticuline synthesized from (E) 3-fluro-tyrosine and (F)
3-chloro-tyrosine. The EIC was extracted using the calculated m/z+ of target intermediate and derivatives, with a mass accuracy below 100 ppm. The EIC and mass
spectra were obtained from CSY1153 cultured at 25 °C for 72 h in YP supplemented with 2% dextrose and 10% glycerol with 10 mM ascorbic acid, fed with
tyrosine or the indicated derivative. Error bars represent SD of three biological replicates.

+

which involves five NADPH-dependent enzymes, where product
titer was enhanced by the overexpression of ZWF1 to increase
NADPH availability (10). We achieved enhanced noscapine titers
by overexpressing two native genes, TYR1 and ALD6, which generate
NADPH through their native activities. The overexpression of
ZWF1, TYR1, and ALD6 is likely to result in a higher NADPH/
NADP
ratio, which is kinetically preferred by the cytochrome
P450s. Future engineering efforts directed to improving noscapine
production should focus on further optimizing NADPH levels or
+
NADPH/NADP
ratios and enhancing the activities of the cytochrome
P450s. For example, protein engineering can be performed on
the rate limiting P450s (e.g., CYP82X2 and CAS) to enhance their
kinetic properties, and strain engineering can be directed to achieving

higher ER capacity to support the overexpression of the multiple
membrane-bound pathway enzymes.

The pattern of pathway intermediate accumulation indicates
bottlenecks in the pathway; however, these patterns vary with
media composition. When the strains are cultured in SD, (S)-
reticuline, scoulerine,
tetrahydrocolumbamine, and canadine
accumulated to the highest relative levels and the intermediates
downstream of N-methylcanadine (except for noscapine) are
relatively low (Fig. S3). These results are consistent with a prior
study indicating that S9OMT and CAS are rate-limiting steps
and CYP82X2 exhibits low activity in yeast (16). In contrast,
when strains are cultured in YP media, relative accumulation of
the early stage intermediates is reduced, and N-methylcanadine,

E3928 | www.pnas.org/cgi/doi/10.1073/pnas.1721469115

Li et al.

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.3.0

2.0

1.0

/

)
L
g
m

(

r
e
t
i
T

i

e
n
p
a
c
s
o
N

0.0

0

Noscapine Titer

OD600

24

48

72

96

Time (hours)

30.0

20.0

10.0

0.0

0
0
6
D
O

Fig. 6. Noscapine production in shake flasks. Noscapine titers from
CSY1153 at different time points in a shake flask experiment. The strain was
cultured in a 250-mL shake flask at 25 °C for 96 h. Medium contains YP with
2% dextrose and 10% glycerol with 10 mM ascorbic acid. Noscapine con-
centration, blue; cell density at OD600, red. Error bars represent SD of three
biological replicates.

1-hydroxy-N-methylcanadine, 1-hydroxy-13-O-acetyl-N-methylcanadine,
and narcotinehemiacetal accumulate to relatively higher levels.
This trend is more prominent when the strain is cultured in the
presence of trehalose and glycerol (Fig. S4). The data imply that
complex medium may help to enhance the activity of the enzymes
responsible for conversion of the early stage intermediates (e.g.,
reticuline, scoulerine, and tetrahydrocolumbamine) to downstream
intermediates (e.g., canadine, N-methylcanadine, and 1-hydroxy-N-
methylcanadine), such as BBE, Ps9OMT, and CAS. Because YP
is a complex medium, the specific components responsible for driving
the metabolic flux farther downstream the pathway are unclear
from these results alone. However, future experiments may focus
on elucidating the mechanism underlying the effects of media
components, including nitrogen, on pathway flux.

Results of carbon source optimization revealed that high sugar
concentration and fermentative carbon sources that can be benefi-
cial in the optimization of central metabolism (36) are not optimal
for noscapine production, which may be due to the higher growth
rate leading to protein misfolding and the redirection of metab-
olite production away from noscapine bioproduction-related
metabolism. We observed that trehalose and glycerol enhanced
plant natural product biosynthesis encoded by a cytochrome P450-
rich, complex biosynthetic pathway. Trehalose and glycerol may
simultaneously serve as carbon source and protein stabilizer,
whereas glycerol also functions as a NADPH regeneration agent
(Fig. 4A). In addition, we observed that adding low concentrations
of dextrose (2%) to the YP medium supplemented with 10%
glycerol further enhanced noscapine production. Because nosca-
pine production is not fully correlated with cell growth (Fig. 6), the
beneficial effect may be due to the accelerated cell growth before
stationary phase. The effect of media and fermentation conditions
observed in these preliminary studies indicates that the precise
control afforded by transferring the process to a bioreactor may
lead to even higher noscapine production.

The de novo biosynthesis of noscapine in yeast provides a
unique opportunity to generate novel natural product derivatives
synthesized from precursor derivatives. As proof of concept, we
demonstrate the capability of de novo noscapine-producing strain
to generate various reticuline derivatives via the incorporation of
tyrosine derivatives in the pathway, which illustrates the potential
of a biological approach to produce novel drug leads. Although we

did not observe the accumulation of BIAs downstream of re-
ticuline, such as noscapine, this may be addressed by a combina-
tion of further improvement of pathway efficiency; engineering
downstream enzymes, such as BBE, for higher activity on nonnatural
substrates; and engineering tailoring enzymes for broader substrate
specificity toward noscapinoids. The successful reconstruction of
this complex plant natural product pathway and synthesis of
benzylisoquinoline alkaloid derivatives via precursor feeding demon-
strates the capacity of yeast to serve as a scalable production platform
for complex plant natural products and highlights the trans-
formative effect synthetic biology may have in drug development
and production.

Methods
Materials and Culture Conditions. Reticuline was purchased from Santa Cruz
Biotechnology and Specs, and noscapine (97% purity) was purchased from
Sigma–Aldrich. For DNA manipulation and amplification, we used chemically
competent or electrocompetent Escherichia coli TOP10 strains purchased
from Life Technologies. E. coli strains were grown at 37 °C in lysogeny broth
medium obtained from Fisher Scientific supplemented with 100 mg/mL
ampicillin (EMD Chemicals) or 50 mg/mL kanamycin (Fisher Scientific) for
plasmid maintenance. All engineered yeast strains described in this work, as
listed in Table S1, were constructed with the reticuline-producing yeast strain
CSY1060 and CSY1061 as a starting point (11). Unless specified, yeast strains
were cultured at 25 °C in complex yeast extract peptone dextrose (YPD; all
components from BD Diagnostics) medium, SD [containing yeast nitrogen base
(YNB) without amino acids (BD Diagnostics), ammonium sulfate (Fisher Scien-
tific), 2% dextrose, and synthetic complete or the appropriate dropout solution
for plasmid maintenance]. Selection in YPD medium used 200 mg/L G418 sulfate
(Calbiochem) or 200 mg/L hygromycin B (Life Technologies).

Plasmid and Yeast Strain Construction. Custom oligonucleotides were syn-
thesized by Integrated DNA Technologies (IDT) and the Stanford Protein and
Nucleic Acid Facility. Heterologous gene sequences were codon-optimized for
expression in S. cerevisiae using the GeneArt GeneOptimizer program (Life
Technologies) and synthesized by GeneArt (Life Technologies) or IDT. Expand
High Fidelity PCR system (Roche Diagnostics) was used for PCR amplifications
according to manufacturer’s instructions. PCR products were purified by aga-
rose gel extraction with Zymoclean gel DNA recovery kit (Zymo Research)
according to manufacturer’s instructions. Restriction enzymes, T4 DNA ligase,
and deoxynucleotides were purchased from New England Biolabs. Plasmids
were prepared from E. coli using QIAprep columns (Qiagen) and Econospin
columns (Epoch Life Science) according to manufacturer’s instructions. Sequencing
was performed by Elim Biopharmaceuticals, Inc.

pos5, idp1, idp2, idp3, pdc6, ald4, ald6, and tyr1 were PCR amplified from
S. cerevisiae genomic DNA and introduced into Gateway pDONR221 using BP
Clonase II Enzyme Mix to yield pCS3636, pCS3642, pCS3643, pCS3637, pCS3663,
pCS3640, pCS3639, and pCS3644, respectively (Table S2). The genes were sub-
sequently recombined into selected pAG416GPD-ccdB expression vectors from
the S. cerevisiae Advanced Gateway Destination Vector Kit (37) using LR
Clonase II to generate the corresponding yeast expression constructs pCS3645,
pCS3649, pCS3652, pCS3646, pCS3657, pCS3647, pCS3653, and pCS3655, re-
spectively (Table S1).

S. cerevisiae CSY1060 and CSY1061 strains were used as the base strain for
construction of the de novo noscapine biosynthetic strains (11). tyr1 and ald6
were each inserted into pCS3125 and pCS3131, respectively, using Gibson
assembly to yield pCS3659 and 3661 (14), respectively. For chromosome-
based DNA assembly, 500–1,000 bp flanking the target loci (from genomic
DNA), certain expression cassettes (from pCS3146, pCS3064, pCS3060,
pCS3075, pCS3145, pCS3143, pCS3134, pCS3141, pCS3147, pCS3140, pCS3142,
pCS3244, pCS3659, pCS3136, pCS3064, and pCS3661; Table S2), and selection
markers [hygR and trp1 from pCS2922 and pCS2923 (38)] were PCR amplified
and incorporated into selected loci to generate CSY1049, CSY1050, and
CSY1053 (Table S1). The chromosome-based DNA assemblies were conducted
through transformation of yeast with a mixture of 100 ng of each DNA frag-
ment using electroporation, and the correctly assembled constructs were verified
through PCR analysis of the junctions between each adjacent DNA fragment
(39). The integration selection marker was then rescued by heterologous
expression of Cre recombinase (40), except for CSY1053.

CSY1051 was constructed by transforming CSY1050 with pCS3638 and the
linear double strand DNA fragment (5′-gatcatcaaggaagtaattatctactttttacaa-
caaatatatacaatgaacggtagaccttt gttgcacagagtcaccaaagaagaaactgttatgttg-3′).
pCS3638 is composed of a Cas9 expression cassette and two transcription

Li et al.

PNAS | vol. 115 | no. 17 | E3929

S
U
L
P

S
A
N
P

L
A
C
I
G
O
L
O
I
B
D
E
I
L
P
P
A

S
E
C
N
E
I
C
S

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.cassettes for the two guide RNAs (5′-acaaatatatacaatgagaa-3′ and 5′-tgcga
aagattgatctttaa-3′). Similarly, CSY1052 was constructed by transforming
CSY1051 with pCS3658 and the linear double strand DNA fragment of codon-
optimized tyrHWR (Table S3) flanked by 5′-cttagtttcgacggattctagaactagtgg-
atcctataca-3′ on the N terminus and 5′-gggcccttcgaatgacgcgccacttctaaataagc-
gaatt-3′ on the C terminus. pCS3658 is composed of a Cas9 expression cassette
and two transcription cassettes for the two guide RNAs (5′-ggcgagggg gcgc-
tgggggt-3′ and 5′-gcgcggccgctcgagtctta-3′).

Culture and Fermentation Conditions. To assay for noscapine production and
for media optimization, yeast strains were initially inoculated in 96-well
plates (BD Falcon) with 0.5 mL YP (1% yeast extract, 2% peptone) with 2%
dextrose per well and incubated in a Kuhner LT-X plate shaker (Kuhner AG) at
25 °C, 480 rpm agitation, 1.24 cm orbital diameter, with 80% humidity in
triplicates overnight. Cultures were then back-diluted 50× into 0.5 mL SD
(0.17% yeast nitrogen base, 0.5% ammonium sulfate, and 1× amino acid
drop-out mixture if necessary) or YP growth medium supplemented with
corresponding carbon sources and 10 mM ascorbic acid per well, and in-
cubated in a Kuhner LT-X plate shaker at 25 °C, 480 rpm agitation, 1.24 cm
orbital diameter, with 80% humidity in triplicates for 72 h. To determine cell
density, the final OD600 (after 10× or 50× dilution) was measured in a cuvette
on a Nanodrop 2000c spectrophotometer (Thermo Scientific).

For enhanced batch culture in shake flasks, strains were initially inoculated
into YP medium with 2% dextrose and grown at 30 °C overnight. Cultures
were then back-diluted 100× into YP medium supplemented with 2% dex-
trose and 10% glycerol, with 10 mM ascorbic acid, and incubated in a
250-mL shake flask with 25 mL starting volume at 30 °C for 96 h in triplicates.
At appropriate time points, 0.5 mL samples were taken for metabolite
analysis, and cell density was recorded from diluted samples measured in a
cuvette on a Nanodrop 2000c spectrophotometer.

Analysis of Noscapine and Intermediate Production. Noscapine and other BIA
intermediates secreted into the culture medium by the engineered yeast
strains were identified and quantified by HPLCy mass spectrometry (HPLC–
MS). Yeast culture medium was analyzed by reverse phase LC–MS/MS on an
Agilent 6420 triple quad LC–MS (Agilent EclipsePlus C18, 2.1 × 50 mm,
1.8 μm) using positive ionization. Metabolites in the medium were separated
on a linear gradient of 10% CH3CN (vol/vol in water, 0.1% formic acid) to
40% CH3CN (vol/vol in water, 0.1% formic acid) over 5 min with a flow rate
of 0.4 mL/min using multiple reaction monitoring (MRM) mode. The identifi-
cation of each compound was verified by MRM using the highest characteristic
precursor ion/product ion transition (Table S5), and the quantification of noscapine

1. Ye K, et al. (1998) Opium alkaloid noscapine is an antitumor agent that arrests
metaphase and induces apoptosis in dividing cells. Proc Natl Acad Sci USA 95:
1601–1606.

2. Barken I, Geller J, Rogosnitzky M (2008) Noscapine inhibits human prostate cancer

progression and metastasis in a mouse model. Anticancer Res 28:3701–3704.

3. Joshi HC, Salil A, Bughani U, Naik P (2010) Noscapinoids: A new class of anticancer
drugs demand biotechnological intervention. Medicinal Plant Biotechnology (Centre
for Agriculture and Bioscience International South Asia Edition, Wallingford, UK), pp
303–320.

4. Mahmoudian M, Rahimi-Moghaddam P (2009) The anti-cancer activity of noscapine:

A review. Recent Patents Anticancer Drug Discov 4:92–97.

5. DeBono A, Capuano B, Scammells PJ (2015) Progress toward the development of

noscapine and derivatives as anticancer agents. J Med Chem 58:5699–5727.

6. Ke Y, et al. (2000) Noscapine inhibits tumor growth with little toxicity to normal
tissues or inhibition of immune responses. Cancer Immunol Immunother 49:217–225.
7. Pushpangadan P, George V, Singh SP (2012) Poppy. Handbook of Herbs and Spices, ed

Peter KV (Woodhead Publishing, Cambridge, England), A2, pp 437–448.

8. Bradsher K (July 20, 2014) Shake-up on opium island. New York Times. Available at
https://www.nytimes.com/2014/07/20/business/international/tasmania-big-supplier-to-
drug-companies-faces-changes.html. Accessed on March 19, 2018.

9. Chen X, Dang TT, Facchini PJ (2015) Noscapine comes of age. Phytochemistry 111:

7–13.

10. Brown S, Clastre M, Courdavault V, O’Connor SE (2015) De novo production of the
plant-derived alkaloid strictosidine in yeast. Proc Natl Acad Sci USA 112:3205–3210.
11. Galanie S, Thodey K, Trenchard IJ, Filsinger Interrante M, Smolke CD (2015) Complete

biosynthesis of opioids in yeast. Science 349:1095–1100.

12. Winzer T, et al. (2012) A Papaver somniferum 10-gene cluster for synthesis of the

anticancer alkaloid noscapine. Science 336:1704–1708.

13. Dang T-TT, Chen X, Facchini PJ (2015) Acetylation serves as a protective group in

noscapine biosynthesis in opium poppy. Nat Chem Biol 11:104–106.

14. Li Y, Smolke CD (2016) Engineering biosynthesis of the anticancer alkaloid noscapine

in yeast. Nat Commun 7:12137.

15. Trenchard IJ, Siddiqui MS, Thodey K, Smolke CD (2015) De novo production of the key
branch point benzylisoquinoline alkaloid reticuline in yeast. Metab Eng 31:74–83.

was measured by comparing the integrated peak area to a standard curve of
standard of noscapine using precursor ion/product ion transition 414 → 220.

Tyrosine Derivative Feeding Assay and Analysis. Sixteen tyrosine derivatives
were fed to CSY1153 (Table S4): 3-fluoro-L-tyrosine, 3-chloro-L-tyrosine, 3-iodo-L-
tyrosine, 3-amino-L-tyrosine, 3-nitro-L-tyrosine, and α-methyl-L-tyrosine
(all >95% purity) were purchased from Sigma–Aldrich; 3-O-methyl-DOPA
(PubChem CID 13206354), 3-hydroxymethyl-L-tyrosine (PubChem CID 10081872),
2-amino-3-hydroxy-3-(4-hydroxyphenyl)propanoic acid (PubChem CID 13309269),
2-amino-3-(3-tert-butyl-4-hydroxyphenyl)propanoic acid (PubChem CID 18352476),
(2S)-2-amino-3-[4-hydroxy-3-(phosphonomethyl)phenyl]propanoic acid (PubChem
CID 15045708), 2-amino-3-(3-ethyl-4-hydroxyphenyl)-2-methylpropanoic acid
(PubChem CID 18544337), D-α-methyl DOPA (PubChem CID 721860), 3-(2-
Amino-2-carboxyethyl)benzoic acid (PubChem CID 265274), L-m-tyrosine (PubChem
CID 6950578), 4-aminophenylalanine (PubChem CID 95174), 2-amino-3-(3,4,5-
trihydroxyphenyl)propanoic acid (PubChem CID 22283619), 3-carboxytyrosine
(PubChem CID 583884), and 4-amino-3-hydroxyphenylalanine (PubChem CID
23253805) were kindly gifted by Novartis Institutes for Biomedical Research.
CSY1153 was initially inoculated into SD with 2% dextrose and grown at 30 °C
overnight. Cultures were then back-diluted 50× into 0.5 mL tyrosine-free SD
(0.17% yeast nitrogen base, 0.5% ammonium sulfate, and 1× tyrosine drop-
out amino acid mixture) medium supplemented with 2% dextrose and 10 mM
ascorbic acid per well. Tyrosine derivatives were supplemented into the
medium at a concentration of 100 mg/L. Yeasts were cultured at 25 °C for 72 h
in triplicates, and 2 μL of the yeast culture medium was analyzed by reverse
phase LC–MS on an Agilent 6545 QTOF LC–MS using dual AJS positive ioni-
zation on a Zorbax SB-Aq column (3.0 mm × 50 mm, 1.8 μM particle size).
Metabolites in the medium were separated on a linear gradient of 5% CH3CN
(vol/vol in water, 0.1% formic acid) to 95% CH3CN (vol/vol in water, 0.1%
formic acid) over 8 min with a flow rate at 0.6 mL/min. Exact mass was
obtained at the Stanford ChEM-H (Chemistry, Engineering & Medicine for
Human Health) Metabolic Chemistry Analysis Center and was extracted using
the calculated m/z+ of target reticuline derivatives, with a mass accuracy
below 10 ppm.

ACKNOWLEDGMENTS. We thank the Stanford ChEM-H Metabolic Chemistry
Analysis Center and Dr. Curt Fischer for instrument access and training and
C. Schmidt for valuable feedback in the preparation of the manuscript. This
work was supported by National Institutes of Health Grant AT007886 (to
C.D.S.) and Novartis Institutes for Biomedical Research Grant IC2013-1373 (to
C.D.S.).

16. Galanie S, Smolke CD (2015) Optimization of yeast-based production of medicinal

protoberberine alkaloids. Microb Cell Fact 14:144.

17. Urlacher VB, Girhard M (2012) Cytochrome P450 monooxygenases: An update on

perspectives for synthetic application. Trends Biotechnol 30:26–36.

18. Nogae I, Johnston M (1990) Isolation and characterization of the ZWF1 gene of
Saccharomyces cerevisiae, encoding glucose-6-phosphate dehydrogenase. Gene 96:
161–169.

19. Li J, Lee EJ, Chang L, Facchini PJ (2016) Genes encoding norcoclaurine synthase occur

as tandem fusions in the Papaveraceae. Sci Rep 6:39256.

20. Ryan OW, Poddar S, Cate JH (2016) CRISPR-Cas9 genome engineering in Saccharomyces

cerevisiae cells. Cold Spring Harb Protoc 2016:pdb.prot086827.

21. Wu Y, et al.

(2015)

Improvement of NADPH-dependent P450-mediated bio-
transformation of 7α,15α-diOH-DHEA from DHEA by a dual cosubstrate-coupled
system. Steroids 101:15–20.

22. Kayikci Ö, Nielsen J (2015) Glucose repression in Saccharomyces cerevisiae. FEMS Yeast

Res 15:fov068.

23. Baneyx F, Mujacic M (2004) Recombinant protein folding and misfolding in Escherichia

coli. Nat Biotechnol 22:1399–1408.

24. Marques WL, Raghavendran V, Stambuk BU, Gombert AK (2016) Sucrose and Sac-

charomyces cerevisiae: A relationship most sweet. FEMS Yeast Res 16:fov107.

25. Bolen DW (2001) Protein stabilization by naturally occurring osmolytes. Protein Structure,

Stability, and Folding, ed Murphy KP (Humana Press, Totowa, NJ), pp 17–36.

26. Gekko K, Timasheff SN (1981) Mechanism of protein stabilization by glycerol: Pref-

erential hydration in glycerol-water mixtures. Biochemistry 20:4667–4676.

27. Crowe JH, et al. (1988) Interactions of sugars with membranes. Biochim Biophys Acta

947:367–384.

28. Crowe LM, Mouradian R, Crowe JH, Jackson SA, Womersley C (1984) Effects of car-
bohydrates on membrane stability at low water activities. Biochim Biophys Acta 769:
141–150.

29. Sato S, Ward CL, Krouse ME, Wine JJ, Kopito RR (1996) Glycerol reverses the mis-
folding phenotype of the misfolding phenotype of the most common cystic fibrosis
mutation. Mol Biol Cell 7:1534.

30. Meng F, Park Y, Zhou H (2001) Role of proline, glycerol, and heparin as protein
folding aids during refolding of rabbit muscle creatine kinase. Int J Biochem Cell Biol
33:701–709.

E3930 | www.pnas.org/cgi/doi/10.1073/pnas.1721469115

Li et al.

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.31. Perlmutter DH (2002) Chemical chaperones: A pharmacological strategy for disorders

36. Borodina I, Nielsen J (2014) Advances in metabolic engineering of yeast Saccharo-

of protein folding and trafficking. Pediatr Res 52:832–836.

32. Diamant S, Eliahu N, Rosenthal D, Goloubinoff P (2001) Chemical chaperones regulate
molecular chaperones in vitro and in cells under combined salt and heat stresses.
J Biol Chem 276:39586–39591.

33. Costenoble R, Valadi H, Gustafsson L, Niklasson C, Franzén CJ (2000) Microaerobic

glycerol formation in Saccharomyces cerevisiae. Yeast 16:1483–1495.

34. Carey JS, Laffan D, Thomson C, Williams MT (2006) Analysis of the reactions used
the preparation of drug candidate molecules. Org Biomol Chem 4:

for
2337–2347.

35. Tomar V, Kukreti S, Prakash S, Madan J, Chandra R (2017) Noscapine and its an-
alogs as chemotherapeutic agent: Current updates. Curr Top Med Chem 17:
174–188.

myces cerevisiae for production of chemicals. Biotechnol J 9:609–620.

37. Alberti S, Gitler AD, Lindquist S (2007) A suite of gateway cloning vectors for high-

throughput genetic analysis in Saccharomyces cerevisiae. Yeast 24:913–919.

38. Siddiqui MS, Choksi A, Smolke CD (2014) A system for multilocus chromosomal in-
tegration and transformation-free selection marker rescue. FEMS Yeast Res 14:
1171–1185.

39. Shao Z, Zhao H, Zhao H (2009) DNA assembler, an in vivo genetic method for rapid

construction of biochemical pathways. Nucleic Acids Res 37:e16.

40. Güldener U, Heck S, Fielder T, Beinhauer J, Hegemann JH (1996) A new efficient
gene disruption cassette for repeated use in budding yeast. Nucleic Acids Res 24:
2519–2524.

Li et al.

PNAS | vol. 115 | no. 17 | E3931

S
U
L
P

S
A
N
P

L
A
C
I
G
O
L
O
I
B
D
E
I
L
P
P
A

S
E
C
N
E
I
C
S

Downloaded from https://www.pnas.org by 75.218.75.123 on March 17, 2026 from IP address 75.218.75.123.