UC Berkeley
UC Berkeley Previously Published Works

Title

Biosynthesis of natural and halogenated plant monoterpene indole alkaloids in yeast

Permalink

https://escholarship.org/uc/item/47w2x3tx

Journal

Nature Chemical Biology, 19(12)

ISSN

1552-4450

Authors

Bradley, Samuel A

Lehka, Beata J

Hansson, Frederik G

et al.

Publication Date

2023-12-01

DOI

10.1038/s41589-023-01430-2

Copyright Information

This work is made available under the terms of a Creative Commons Attribution

License, available at https://creativecommons.org/licenses/by/4.0/

Peer reviewed

eScholarship.org

Powered by the California Digital Library
University of California

Biosynthesis of natural and halogenated
plant monoterpene indole alkaloids in yeast

https://doi.org/10.1038/s41589-023-01430-2

Received: 5 May 2022

Accepted: 25 August 2023

Published online: 6 November 2023

 Check for updates

  1, Olga Gudich1, Konstantina Giannakou1, Bettina Lengger

Samuel A. Bradley1,12, Beata J. Lehka1,12, Frederik G. Hansson1, Khem B. Adhikari1,
Daniela Rago1, Paulina Rubaszka1, Ahmad K. Haidar1, Ling Chen1,
Lea G. Hansen
Ryan T. Gill1, Yoko Nakamura2, Thomas Dugé de Bernonville
Konstantinos Koudounas
  4, Thomas M. Frimurer
Yijun Qiao
Sandeep Kumar3, Nicolas Gautron
Remi Jeanneau6, Sarah E. O’Connor
  1
Jay D. Keasling1,7,8,9,10,11, Jie Zhang

  5, Anja A. Petersen5, Sébastien Besseau
  3, Celine Melin3, Jillian Marc3,
  2, Vincent Courdavault
  1
 & Michael K. Jensen

  3, David Romero-Suarez

  1, Ling Ding4,

  3,

  3,

  1,

  3,

Monoterpenoid indole alkaloids (MIAs) represent a large class of plant
natural products with marketed pharmaceutical activities against a
wide range of indications, including cancer, malaria and hypertension.
Halogenated MIAs have shown improved pharmaceutical properties;
however, synthesis of new-to-nature halogenated MIAs remains a challenge.
Here we demonstrate a platform for de novo biosynthesis of two MIAs,
serpentine and alstonine, in baker’s yeast Saccharomyces cerevisiae and
deploy it to systematically explore the biocatalytic potential of refactored
MIA pathways for the production of halogenated MIAs. From this, we
demonstrate conversion of individual haloindole derivatives to a total
of 19 different new-to-nature haloserpentine and haloalstonine analogs.
Furthermore, by process optimization and heterologous expression of a
modified halogenase in the microbial MIA platform, we document de novo
halogenation and biosynthesis of chloroalstonine. Together, this study
highlights a microbial platform for enzymatic exploration and production
of complex natural and new-to-nature MIAs with therapeutic potential.

Monoterpenoid indole alkaloids (MIAs) are an important group of
plant secondary metabolites that possess various medicinal proper-
ties, including marketed chemotherapeutic agents such as vinblastine
and vincristine and the antiarrhythmic drug ajmaline1. Likewise,
numerous bioactive MIAs are used to treat human illnesses outside the

clinic, including ibogaine for the treatment of opioid use disorder
and withdrawal symptoms2 and the stereoisomers alstonine (1a) and
serpentine (2a) with reported therapeutic effects against a broad
number of indications, such as psychotic disorders, cancer and
malaria3.  Beyond  the  range  of  naturally  occurring  bioactive

1Novo Nordisk Foundation Center for Biosustainability, Technical University of Denmark, Lyngby, Denmark. 2Department of Natural Product Biosynthesis,
Max Planck Institute for Chemical Ecology, Jena, Germany. 3EA2106 Biomolécules et Biotechnologies Végétales, Université de Tours, Tours, France.
4Department of Bioengineering, Technical University of Denmark, Lyngby, Denmark. 5Novo Nordisk Foundation Center for Basic Metabolic Research,
University of Copenhagen, Copenhagen, Denmark. 6Axyntis, Pithiviers, France. 7Joint BioEnergy Institute, Emeryville, CA, USA. 8Biological Systems and
Engineering Division, Lawrence Berkeley National Laboratory, Berkeley, CA, USA. 9Department of Chemical and Biomolecular Engineering, University
of California, Berkeley, Berkeley, CA, USA. 10Department of Bioengineering, University of California, Berkeley, Berkeley, CA, USA. 11Center for Synthetic
Biochemistry, Institute for Synthetic Biology, Shenzhen Institutes of Advanced Technologies, Shenzhen, China. 12These authors contributed equally:
Samuel A. Bradley, Beata J. Lehka.

 e-mail: jzha@biosustain.dtu.dk; mije@biosustain.dtu.dk

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1551

nature chemical biologyArticleMIAs, unnatural analogs with improved potency have also been
reported4.

Producing MIAs at scale for medicinal use is challenging. Source
extraction from plants can suffer from supply chain shortages and
generally poor yields5, whereas total chemical synthesis is plagued by
difficulties separating stereoisomers6.

A biotechnological solution for the production of both natural
and modified MIAs is microbial cell factories, which are engineered
to produce bioactive phytochemicals using fermentation. Indeed,
heterologous expression of plant genes in baker’s yeast Saccharomy-
ces cerevisiae has facilitated the production of various plant-derived
pharmaceuticals,  including  MIAs7–9.  Furthermore,  valorization
of commercially available precursors to downstream MIA-based
active pharmaceutical ingredients has been demonstrated10, while
Liu et al. recently documented the de novo production of a complex
class of heteroyohimbines, including tetrahydroalstonine (3a) and
ajmalicine (4a)11, which are the direct precursors for the MIA enantiom-
ers alstonine (1a) and serpentine (2a)12. With continued advancements
in synthetic biology, metabolic engineering and plant biosynthetic
pathway discoveries13, refactoring de novo production of bioactive
MIAs in microbial cells is now facilitated.

In addition to the interest in fermentation-based de novo produc-
tion of MIAs from simple feedstocks (for example, glucose and amino
acids), several pioneering studies have investigated enzymatic produc-
tion of unnatural MIAs from unnatural substrate analogs in vitro14 and
in planta15 by feeding unnatural precursor analogs. Early investigations
into the promiscuity of individual enzymes were followed by heterolo-
gous enzyme expression for directly introducing unnatural elements
into MIA precursors16. In a landmark study, two tryptophan haloge-
nases from Lechevalieria aerocolonigenes (LaeRebH) and Streptomyces
rugosporus (SruPyrH) were expressed in the MIA-producing plant
Catharanthus roseus, resulting in de novo production of chlorinated
and brominated MIAs. Yet, as these new-to-nature chemical spaces
include both regioselective considerations and choice of halogen, it
remains a challenge to mitigate barriers within new-to-nature chemis-
tries in slow-growing plants with limited genetic tractability. Likewise,
regioselective chemical halogenation of pharmacophores and total
chemical synthesis are complicated due to the numerous stereocenters
often found in natural products, not to mention the difficulties of scal-
ing up production once a lead has been identified17. Here, the advanced
genetic toolbox, short generation times and amenable metabolism of
S. cerevisiae for de novo production of strictosidine (5a) and heteroyo-
himbine MIAs9,11 makes this chassis ripe for systematically exploring and
prototyping whole-cell biocatalysis of new-to-nature MIA chemistries.
In this work, we report the engineering of yeasts for de novo pro-
duction of bioactive alstonine (1a) and serpentine (2a) and demon-
strate their utility for exploring enzyme promiscuity and metabolic
limitations in refactored biosynthetic pathways while producing MIA
derivatives. Ultimately, this approach enabled the biosynthesis of 19
halogenated heteroyohimbines (1a–i and 2a–l) and de novo biosyn-
thesis of chloroalstonine (1f).

Results
De novo alstonine and serpentine biosynthesis in yeast
In plants, conversion of strictosidine (5a) to alstonine (1a) or serpentine
(2a) is catalyzed by strictosidine-β-d-glucosidase (SGD)18, the dehydro-
genases tetrahydroalstonine synthase (THAS)19 or heteroyohimbine
synthase (HYS)20 and the recently discovered cytochrome P450 enzymes
alstonine synthase (AS)21 and serpentine synthase (SS12; Fig. 1a). For the
establishment of a microbial platform for producing alstonine (1a) and
serpentine (2a), we initially characterized the promiscuity of the two
heteroyohimbine dehydrogenases C. roseus THAS1 (CroTHAS1) and C.
roseus HYS (CroHYS) in yeast. These enzymes were expressed in a de novo
strictosidine-producing strain (MIA-CM-3 (ref. 9); Supplementary
Table 1) together with SGD from Rauvolfia serpentina (RseSGD; Fig. 1a).

Here, yeast expressing RseSGD and CroTHAS1 produced tetrahydroal-
stonine (THA), whereas yeast expressing RseSGD and CroHYS pro-
duced ajmalicine (4a) and a small amount of THA (3a), as also recently
reported (Extended Data Fig. 1a)11. Next, for the characterization of
P450 enzymes catalyzing the conversion of THA (3a) to alstonine (1a),
we selected candidates reported in the literature, R. serpentina sarpa-
gan bridge enzyme (RseSBE), Gelsemium sempervirens SBE (GseSBE),
C. roseus AS (CroAS)21 and the recently identified C. roseus SS (CroSS)12
due to its close homology with CroAS (Fig. 1b). We also mined the
C. roseus genome for alternative AS candidates22. This led to the identi-
fication of a sequence displaying 87% identity with CroAS, tentatively
named CroAS2 (ref. 21). Additionally, we generated a de novo assembled
transcriptome of R. tetraphylla to search for additional AS candidates.
Mining this new resource allowed the identification of two hypothetical
P450 enzymes (R1n_CGCTCATT-TATAGCCT_DN432_c0_g1_i4.p1 and BP5_
GAGATTCC-GGCTCTGA_DN4992_c0_g1_i3.p1), which displayed more
than 75% identity with already characterized AS21. Based on this signifi-
cant identity, these two sequences were tentatively named RteAS1 and
RteAS2. Three additional sequences of lower identity were also retained
and hereafter named RteAS3 (R1n_CGCTCATT-TATAGCCT_DN14548_c0_
g1_i1.p1), RteAS4 (DL4_GAGATTCC-TATAGCCT_DN2810_c0_g2_i3.p1)
and RteAS5 (BL2_CGCTCATT-CCTATCCT_DN6055_c0_g1_i1.p1; Fig. 1b).
Next,  to  characterize  the  catalytic  activity  of  the  identified
P450 candidates, we used a feeding strategy of secologanin (6) and
tryptamine (7a) to the engineered background strain expressing
C. roseus cytochrome P450 reductase (CroCPR), C. roseus strictosidine
synthase (CroSTR) and RseSGD and CroTHAS1 (Sc86; Fig. 1a). Strains
expressing individual P450 candidates were cultivated in synthetic
complete (SC) or rich cultivation (yeast extract peptone dextrose
(YPD)) medium supplemented with secologanin (6) and tryptamine
(7a; Fig. 1b, Extended Data Fig. 2 and Supplementary Table 1). In this
screen, we identified five enzymes producing alstonine (1a), namely
two synthases from R. tetraphylla (RteAS1 and RteAS2 in strains Sc87
and Sc88), SBE from G. sempervirens (GseSBE_nat in strain Sc98 or
GseSBE in strain Sc104), CroAS2 (strain Sc101) and CroSS (strain Sc157).
In YPD medium, we observed up to 20-fold improvements compared
to SC medium (Extended Data Fig. 2 and Supplementary Table 1), with
RteAS2 (strain Sc88) enabling the production of 71.7 ± 41 µg liter–1 and
CroSS enabling the production of 6,641 ± 1,757 µg liter–1 in YPD (Fig. 1b).
Based on the screen for ASs (Fig. 1b), individual genes encoding
RteAS2, GseSBE_nat and CroSS_nat were genomically integrated into the
strictosidine-producing strain MIA-CM-3 (ref. 9) together with RseSGD
and CroTHAS1 to test de novo alstonine (1a) production (resulting in
strains Sc77, Sc78 and Sc112, respectively) or together with RseSGD
and CroHYS to test de novo serpentine (2a) production (resulting
in strain Sc85). All strains were cultivated in a previously optimized
medium for small-scale MIA production (3× SC)9, in which Sc77 out-
performed Sc78 with an alstonine (1a) titer of 29.7 ± 4 µg liter–1, Sc112
expressing CroSS_nat yielded a further >40-fold increase in alstonine
(1a) titer of 1,034 ± 94 µg liter–1, and Sc85 was observed to produce
1,270 ± 130 µg liter–1 serpentine (2a). Importantly, although stricto-
sidine (5a) was consumed in all strains, THA (3a) and ajmalicine (4a)
accumulated up to 990 ± 192 µg liter–1 and 914 ± 3 µg liter–1, respec-
tively, in strains Sc77 and Sc78, whereas conversion of THA to alstonine
by CroSS_nat in strain Sc112 lowered THA levels to 166 ± 35 µg liter–1
(Extended Data Fig. 1b and Supplementary Fig. 1).

To further investigate the physiology and productivities of
de novo alstonine (1a) and serpentine (2a) strains, fed-batch cultiva-
tion of strains Sc85 and Sc112 were cultivated in 3× SC medium using
controlled microbioreactors (Methods). To prevent accumulation of
by-products (for example, ethanol) and improve biomass and product
yield, cells were grown in batch culture for 20 h, followed by exponen-
tial feeding for 124 h. The highest final titers reached 8.85 mg liter–1
serpentine (2a) from strain Sc85 and 4.48 mg liter–1 alstonine (1a)
from strain Sc112 (Fig. 1c,d, Table 1 and Supplementary Fig. 2). For

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1552

Articlehttps://doi.org/10.1038/s41589-023-01430-2a

b

Tree scale:0.01

RteAS5
RteAS3

RteAS4

RseSBE

RteAS2
RteAS1

CroSS

CroAS2

CroAS

GseSBE

)

1
–

r
e
t
i
l

g
m

i

(
e
n
n
o
t
s
l
A

8

6

4

2

0

1
S
A
e
t
R

2
S
A
e
t
R

3
S
A
e
t
R

4
S
A
e
t
R

5
S
A
e
t
R

S
A
o
r
C

2
S
A
o
r
C

E
B
S
e
s
R

E
B
S
e
s
G

t
a
n
_
S
A
o
r
C

t
a
n
_
2
S
A
o
r
C

t
a
n
_
E
B
S
e
s
R

t
a
n
_
E
B
S
e
s
G

t
a
n
_
S
S
o
r
C

AS candidates

)
l

o
r
t
n
o
c
(
S
A
o
N

c

)

1
–

0.5

,

i

e
n
d
i
s
o
t
c
i
r
t
s

,

A
H
T

d

,

r
e
t
i
l

g
m

i

(
n
n
a
g
o
o
c
e
s

l

)

1
–

i

e
n
d
i
s
o
t
c
i
r
t
s

,

i

e
n
c
i
l
a
m
A

j

r
e
t
i
l

g
m

i

(
n
n
a
g
o
o
c
e
s

l

0.4

0.3

0.2

0.1

0

40

0.5

0.4

0.3

0.2

0.1

0

40

35

30

25

20

15

10

5

0

35

30

25

20

15

10

5

0

90

140

Time (h)

90

140

Time (h)

(

m
g

l
i
t
e
r

–
1

)

A
l
s
t
o
n
n
e
,

i

l

o
g
a
n
n

i

(

m
g

l
i
t
e
r

–
1

)

S
e
r
p
e
n
t
i
n
e

,

l

o
g
a
n
n

i

Alstonine
Loganin
THA
Secologanin
Strictosidine

Serpentine
Loganin
Ajmalicine
Secologanin
Strictosidine

Fig. 1 | De novo alstonine and serpentine production in yeast. a, Integration
of plant biosynthetic pathways with native yeast metabolic pathways to
produce alstonine and serpentine. IPP, isopentenyl pyrophosphate; DMAPP,
dimethylallyl pyrophosphate; GPPS, GPP synthase; FPSN144W, FPP synthase N144W
variant; CPR, NADPH-cytochrome P450 reductase; CYB5, cytochrome b5; GES,
geraniol synthase; G8H, geraniol 8-hydroxylase; 8HGO, 8-hydroxygeraniol
oxidoreductase; ISY, iridoid synthase; IO, iridoid oxidase; CYPADH, alcohol
dehydrogenase 2; 7DLGT, 7-deoxyloganetic acid glucosyl transferase; 7DLH,
7-deoxyloganic acid hydroxylase; LAMT, loganic acid O-methyltransferase;
TDC, tryptophan decarboxylase; SLS, secologanin synthase; STR, strictosidine

synthase. b, Screen of AS candidates in YPD cultivation medium. Gene candidates
are linked to strain identifiers as follows: RteAS1 (Sc87), RteAS2 (Sc88), RteAS3
(Sc90), RteAS4 (Sc92), RteAS5 (Sc94), CroAS_nat (Sc96), RseSBE_nat (Sc97),
GseSBE_nat (Sc98), CroAS2_nat (Sc100), CroAS2 (Sc101), CroAS (Sc102), RseSBE
(Sc103), GseSBE (Sc104) and CroSS_nat (Sc157) and a negative-control strain
(Sc86). c,d, Representative production profiles for alstonine (c), serpentine (d)
and pathway intermediates using a small-scale fed-batch process for strains Sc112
and Sc85, respectively, cultivated in 1 ml of 3× SC medium supplemented with
3 mM tryptophan. For b, n = 3, and error bars represent 1 s.d. from the mean, with
data points overlaid as black dots.

this process, we furthermore observed lowered accumulation of
pathway intermediates compared to batch cultivation, except for
tryptamine (7a) and loganin (8; Fig. 1c,d and Supplementary Figs.
2–4). Here, tryptamine (7a) accumulated to 139 mg liter–1 for Sc85 and

162 mg liter–1 for Sc112, and loganin (8) accumulated to 8.5 mg liter–1
for Sc85 and 6.9 mg liter–1 for Sc112, indicating the P450 C. roseus
secologanin synthase (CroSLS) as a bottleneck for MIA production in
yeast (Supplementary Fig. 3).

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1553

Articlehttps://doi.org/10.1038/s41589-023-01430-2NativemevalonatepathwayNativeshikimatepathwayOPOOPO-OO-O-OPOOPO-OO-O-OPOOPO-OO-O-OHOHOHOOHOHHOHOHHOHOHOHHOHOHOHHOOHOGlcOHHOOHOHOGlcOHHOOOHOGlcOOOOOGlcNHNHOOOOGlcHHNHNHOHOOOHH1aAlstonineNNOOOHH2aSerpentineNNOOOHH3aTetrahydroalstonineNHNOOOHHH4aAjmalicineNHNOOOHHHNHNH27aTryptamineNHNH2OH11aL-Tryptophan8Loganin9Geraniol6Secologanin177-Deoxyloganeticacid167-Deoxyloganeticalcohol15Nepetalactol138-Hydroxygeraniol12GPP148-Oxogeranial187-Deoxyloganic acid19Loganic  acid5aStrictosidine20aStrictosidine  aglycone21IPP22DMAPPIDI1ERG20F96W;F127WFPSN144WGPPS2GESG8H8HGOISYIOCYPADH7DLGT7DLHLAMTSLSSTRTDCSGDTHASHYSAS or SSHYSSSCPRCYB5CPRCYB5CPRCYB5CPRCYB5CPRCYB5CPRCYB5

Table 1 | Fed-batch bioprocess for strains producing
serpentine and alstonine

Strain, colony

Biomass
(g liter–1)a

Yield biomass (g
per g glucose)

Yield product (mg
per g glucose)

Sc85, F1

Sc85, F2

Sc85, D5

Sc112, D2

Sc112, C1

Sc112, D1

8.20

6.60

5.20

8.80

11.00

10.60

0.13

0.11

0.08

0.14

0.18

0.17

0.14

0.12

0.09

0.07

0.06

0.05

Final biomass, yield of biomass and product yields for serpentine produced by Sc85 and
alstonine produced by Sc112 during 144 h of cultivation. Data for three different colonies
are shown for each of the two production strains. aBiomass was measured using grams (dry
weight).

Last, the fed-batch bioprocess for Sc112 was scaled up to 2-liter bio-
reactors. Here, alstonine (1a) production was critically affected by this
change of scale, with titers below 0.1 mg liter–1 (Extended Data Fig. 3).
Acknowledging the reported positive contribution to P450-mediated
biocatalysis23, we decided to delete ROX1, a gene encoding a repressor
of the heme biosynthetic gene HEM13, in Sc112 yielding strain ScH144.
In microbioreactor fermentations, ScH144 produced almost 60% more
alstonine (1a) than Sc112 (16.7 ± 1.33 versus 9.9 ± 0.13 mg liter–1) when
medium was supplemented with bovine peptone (Supplementary Fig.
5)11. Strain ScH144 was fed under a pulsed strategy instead of an expo-
nential strategy given the better production yield observed on glucose
during the batch phase in the 2-liter bioreactor with the parental strain
Sc112 (1.7 versus 0.8 µg g–1). Interestingly, this restored alstonine (1a)
biosynthesis, reaching 3.6 mg liter–1 after 185 h (Supplementary Fig. 6).
In agreement with the positive effect of ethanol substrate on terpene
synthesis previously reported for geraniol (9) and sesquiterpenes, we
finally replaced glucose by ethanol as a yeast carbon source24. Pulsing
ethanol to ScH144 during fed-batch phase in the 2-liter bioreactor
further increased alstonine titer (up 4.9 mg liter–1), thus reaching the
concentration obtained in the microbioreactor with Sc112 (Fig. 1c,d
and Extended Data Fig. 1c). Using the spent medium, we performed a
four-step purification process (Methods) and purified 2 mg of alsto-
nine (1a) at 95% purity (Extended Data Fig. 4). Last, purified alstonine
(1a; 0.3 mg) was analyzed by 1H NMR to validate the structure of the
isolated product compared to an authentic alstonine (1a) standard,
corroborating mass spectrometry (MS) data from broth (Extended
Data Figs. 5 and 6).

Taken together, combinatorial engineering of heteroyohimbine
biosynthetic pathways in yeast combined with scalable bioprocess opti-
mization enabled de novo production of MIAs at the milligram scale.

Bioactivity of alstonine
Heteroyohimbines,  such  as  yohimbine  and  rauwolscine,  have
been  reported  as  ligands  of  monoaminergic  and  serotonergic
G-protein-coupled receptor (GPCR) drug targets17. Furthermore, the
anxiolytic properties of alstonine (1a) have been shown to be reverted
in mice pretreated with a 5-HT2A/5-HT2C antagonist25.

To assess the potential bioactivity of alstonine (1a), we first
adopted  a  previously  developed  antagonist  assay  against  the
epinephrine-activated ADRA2A GPCR expressed in yeast cells26. To
do so, we first estimated the half-maximum effective concentration
of epinephrine against the ADRA2A receptor expressed in yeast cells
as 14 ± 2 µM, with a 95% confidence interval (CI95) of 11.5–16.6 µM
(Fig.  2a).  Next,  we  co-incubated  ADRA2A-expressing  yeast  cells
(Sc272) with 50 µM epinephrine and different dosages of the known
ADRA2A antagonist yohimbine17 or alstonine (1a). We found that alsto-
nine is a weak antagonist of ADRA2A with a half-maximal inhibitory

concentration (IC50) of 59 ± 20 µM (CI95 of 39.0–79.3 µM), whereas
yohimbine exerted an IC50 of 0.13 ± 0.04 µM (CI95 of 0.089–0.181 µM)
against ADRA2A (Fig. 2a). Next, based on the possible link between the
anxiolytic effects of alstonine and the 5-HT2A/5-HT2C GPCRs in rodents25,
we were interested to further explore possible direct drug targets of
alstonine. As the 5-HT2 GPCRs have not been functionalized in yeast27,
we expressed 5-HT2C in mammalian COS7 cells and tested alstonine
activity in the presence and absence of the cognate 5-HT2C agonist
serotonin. Here, we observed alstonine as a weak antagonist of the
5-HT2C receptor, albeit no IC50 could be reported for the concentration
range available (Fig. 2b).

In summary, bioactivity testing of purified alstonine (1a) from
fermentation-based manufacturing identifies alstonine as a possible
antagonist of ADRA2A and 5-HT2C GPCRs.

De novo biosynthesis of new-to-nature heteroyohimbine in
yeast
Motivated by in vitro14 and in planta15 studies documenting halogena-
tion of MIA precursors and the approved drugs founded on halogenated
MIA scaffolds28, we aimed to harness the successful refactoring of MIA
biosynthetic pathways to systematically investigate the potential for
production of new-to-nature MIA analogs in yeast with an initial focus
on alstonine (1a).

Anticipating a derivative bottleneck at the C. roseus tryptophan
decarboxylase (CroTDC)-catalyzed step16, we initially replaced this
enzyme from the de novo strictosidine-producing strain MIA-CM-3
(ref. 9) with a more promiscuous homolog from Ruminococcus gna-
vus (RgnTDC29; MIA-CM-10). Comparing the ability of MIA-CM-3 and
MIA-CM-10 to convert a panel of 18 fluorinated, chlorinated and bro-
minated indoles (10b–10s) into halogenated strictosidine (5b–5n)
revealed that the native tryptophan synthase (encoded by TRP5) can
combine all indole tested derivatives with serine (Extended Data
Fig. 7a,b). Although the bromotryptophan (11j–11m) spectra did not
correlate with that of the tryptophan standard (11a), the presence of
4-, 5-, 6- and 7-bromotryptamine (7j–7m) analogs in MIA-CM-10 infers
the production of the corresponding bromotryptophans (11j–11m;
Extended Data Fig. 7b). The demonstration of haloindoles as a viable
feedstock for microbial production of halogenated tryptagenic com-
pounds is noteworthy as indole derivatives are substantially cheaper
and more accessible than tryptophan or tryptamine derivatives used in
previous feeding studies30. Furthermore, although CroTDC in MIA-CM-3
was observed to accept all the smaller fluoro and difluoro substitutions,
the enzyme showed a strong preference for substitutions at C4 for the
larger chloro substitution, and no bromotryptamine (7j–7m) could
be positively identified (Extended Data Fig. 7c). More promisingly,
RgnTDC retained the broad promiscuity reported in vitro, allowing us to
report additional promiscuity for 5-, 6- and 7-fluorotryptophan (7b–7d)
as well as the six different difluorotryptophans (7n–7s;29 Extended
Data Fig. 7d and Supplementary Table 8). Despite this, the extra larger
halotryptamines produced by MIA-CM-10 were not generally accepted
by CroSTR, meaning MIA-CM-3 and MIA-CM-10 each produced seven
strictosidine derivatives (5b–5j; Extended Data Fig. 7). Based on the
broader production of halotryptamines, RgnTDC was selected for
further use as the higher general promiscuity was regarded as beneficial
for exploring the range of halogenated alstonines possible to produce
in a microbial chassis.

Because of the negative growth effects on yeast when supplement-
ing halogenated indoles to the cultivation medium (Supplementary
Fig. 7), supplementation was performed following biomass accumu-
lation. Likewise, RgnTDC expression was placed under the control of
the galactose-inducible promoter GAL1 (Sc154) to minimize incorpo-
ration of endogenous tryptophan (11a) into the MIA pathway before
indole feeding. As a further pull on halogenated intermediates toward
alstonine analogs, we also introduced CroSS and an additional copy of
CroTHAS under the control of a galactose-inducible promoter (Sc156).

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1554

Articlehttps://doi.org/10.1038/s41589-023-01430-2a

x
a
m

f
o
e
g
a
t
n
e
c
r
e
P

)

U
L
R
(
e
s
n
o
p
s
e
r

100

50

0

b

0.92

P
M
A
c

0.88

0.84

0.80

Epinephrine

x
a
m

f
o
e
g
a
t
n
e
c
r
e
P

)

U
L
R
(
e
s
n
o
p
s
e
r

100

50

0

0

–8

–7

–6

–5

–4

–3

–2

0

–10

–9

–8

–7

–6

–5

–4

–3

–2

log ([epinephrine]) (M)

log ([antagonist]) (M)

Serotonin

0.92

P
M
A
c

0.88

0.84

0.80

Yohimbine

Alstonine

Alstonine

Alstonine +
0.5 µM
serotonin

0

–10

–8

–6

–4

0

–8

–6

–4

–2

log ([serotonin]) (M)

log ([alstonine]) (M)

Fig. 2 | Bioactivity testing of alstonine in yeast and mammalian cells.
a, Dose–response curves of ADRA2A with the agonist epinephrine (left;
R2 = 0.988) and antagonist activities of yohimbine and alstonine (right; R2 = 0.965
and 0.980, respectively). Data are reported in relative luminescence units (RLU)
based on nano-luciferase (NanoLuc) readouts normalized to the maximum
observed luminescence. Data report triplicate biological replicates (n = 3)
measured on yeast cells heterologously expressing the ADRA2A receptor;
[epinephrine], concentration of epinephrine; [antagonist], concentration of
antagonist; [serotonin], concentration of serotonin; [alstonine], concentration

of alstonine. b, Dose–response curves of 5-HT2C with the agonist serotonin (left;
R2 = 0.892) and alstonine with and without 0.5 µM competing serotonin (right;
R2 = 0.792 and 0.913). cAMP levels were monitored using BRET in COS7 cells, and
data are reported for biological duplicates (n = 2). For all data presented, each
replicate is shown, and a non-linear regression model was applied using the least
squares method. The dashed lines in a and b (left) indicate 50 µM and 0.5 µM,
respectively, which were the agonist concentrations used in the respective
competitor assays (right).

Last, in strain Sc156, we engineered inducible expression of CroSLS
(GAL1 promoter) and overexpression of INO2 (TEF1 promoter; Sc159)
to mitigate the CroSLS bottleneck and deleted ROX1 (Sc161) to support
P450 enzymes in the pathway23. Of these strains, Sc161 produced the
most fluoroalstonine (1b) in a pilot experiment (Supplementary Fig. 8a)
and had the highest signal achieved after 144 h of cultivation (Supple-
mentary Fig. 8b). After feeding the larger 18-membered panel of indole
derivatives (10b–10s) to Sc161, eight peaks with masses correspond-
ing to 4-, 5-, 6- and 7-fluorinated analogs (1b–1e), the 7-chlorinated
(1f) and 7-brominated analogs (1g) and 5,6-difluoroalstonine (1i) and
6,7-difluoroalstonine (1h) were identified (Fig. 3a). Importantly, all
eight alstonine analogs shared the same tandem MS (MS/MS) spectra
fragmentation pattern as the alstonine standard and the stereoiso-
mer serpentine31(Fig. 3b,c), and the expected isotopic patterns were
observed (Extended Data Fig. 8). The detection of all MIA derivatives
is summarized in Fig. 3d and Extended Data Fig. 9.

Following these findings, cultivations of an Sc154-equivalent
serpentine-producing strain expressing CroHYS instead of CroTHAS
(ScH125; Fig. 1a) resulted in the detection of 11 halogenated serpentine
analogs (2b–2l; Extended Data Figs. 8 and 10a–d), of which 9 have not
been previously reported. The higher number of detected serpentine
analogs could be due to CroHYS having either higher overall activity
or promiscuity or CroSS having higher promiscuity for ajmalicine
derivatives than for THA derivatives. Surprisingly, we observed two
distinct peaks in all the halogenated serpentine spectra (Extended
Data Fig. 10a). We attribute this to the mixed product profile of
CroHYS  (Extended  Data  Fig.  1a),  which  possibly  produces  both
ajmalicine (4a) and THA (3a), resulting in both haloalstonine and
haloserpentine formation in strain ScH125.

analysis of MIA pathway intermediates can enable elucidation of
biocatalytic bottlenecks. First, a severe bottleneck can be inferred at
the Pictet–Spengler reaction catalyzed by CroSTR, as, although all 18
tryptamine derivatives (7b–7s) are detected, only 12 of these result in
a heteroyohimbine analog with a signal strength sufficient for obtain-
ing an MS/MS spectrum (Fig. 3b,d and Extended Data Fig. 9). Of these,
the tryptamine derivatives turned over by CroSTR are either small
(all fluorotryptamines (7b–7e) and difluorotryptamines (7n–7s)) or
positioned on C7 (7-chlorotryptamine (7f) and 7-bromotryptamine
(7j)). The higher promiscuity of CroSTR at C7 is in line with previously
reported in vitro results14, as clashes occur between larger Cl and Br
atoms on indole positions C4, C5 and C6 with the CroSTR binding site
in which the reactive amine moiety is positioned within 2.5 Å of the
catalytic glutamate residue32.

In addition to the steric constraints imposed by CroSTR promiscu-
ity, secologanin (6) availability also globally restricts flux through this
enzymatic step9, and competition with natural tryptamine (7a) further
reduces derivative production (Fig. 4a). Here, unless supplemented
at 0.25 mM or heterologously produced by all the strains character-
ized, secologanin (6) was not detectable after 144 h of cultivation
(Fig. 4b), and supplementation significantly increased fluoroalstonine
(1b–1e) signals (Fig. 4c). With respect to the production of alstonine
(1a) derivatives, when the cultivation medium was supplemented with
0.25 mM secologanin, fluoroalstonine signals also increased signifi-
cantly (P < 10−4; Fig. 3b). In summary, secologanin (6) availability has
a global limiting effect on both natural MIA and derivative production.
However, the effect on production of derivatized MIAs is compounded
by low CroSTR promiscuity, meaning that they are outcompeted by
underivatized tryptamine for reaction with secologanin (Fig. 3c).

Beyond the detection of novel halogenated MIAs produced in
yeast fed with secologanin (6) and haloindoles (10b–10s), quantitative

In summary, this study enabled the microbial production of 8
alstonines (1b–1i) and 11 serpentines (2b–2l), 9 of which have not been

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1555

Articlehttps://doi.org/10.1038/s41589-023-01430-2

Fig. 3 | Biosynthesis of halogenated alstonine derivatives in engineered
yeast. a, Representative liquid chromatography–MS/MS (LC–MS/MS) traces of
the chemical standard alstonine and the peaks corresponding to halogenated
alstonines after feeding 0.25 mM secologanin and 100 mg liter–1 corresponding
haloindole derivatives with a single halogen atom at C4 (green), C5 (red), C6
(gold) or C7 (blue). b, Representative MS/MS spectra of alstonine standard and

fluoroalstonine, chloroalstonine and bromoalstonine. c, Peak assignments
for alstonine MS/MS spectra shown in b. d, Progress of the given substitution
through the MIA pathway is indicated by the corresponding colored lines.
The presence of the colored box indicates direct detection of the halogenated
compound after haloindole derivative feeding to cells. Abbreviated enzyme
names are stated above the catalyzed reaction.

reported before. Additionally, systematic analysis of pathway interme-
diates demonstrated production of THA (3b–3i), ajmalicine (4b–4l)
and strictosidine aglycone (20b–20n) derivatives, while at the same
time elucidating limiting metabolic reactions restricting the halogena-
tion of bioactive MIAs.

De novo biosynthesis of new-to-nature heteroyohimbines
To explore the potential of producing new-to-nature MIAs without
the need for supplementation of halogenated indoles or secologanin,
we next sought to engineer yeast for de novo production of halogen-
ated MIAs. To do so, we integrated a galactose-inducible halogenase
expression cassette consisting of the FAD-dependent tryptophan halo-
genase LaeRebH33 and the FAD reductase EcoSsuE34 from L. aerocoloni-
genes and Escherichia coli, respectively, into Sc161 (ScH132; Fig. 5a).
LaeRebH has been shown to catalyze regiospecific bromination and
chlorination at C7 of tryptophan and has been previously expressed in
C. roseus16, resulting in the production of halogenated MIAs in planta
and the production of halotryptamine in yeast35. However, when ScH132
is cultivated at 30 °C with 100 mg liter–1 tryptophan (11a) and 300 mM

NaCl, only chlorotryptophan (11f) and chlorotryptamine (7f) were
observable, yet no downstream chlorinated intermediates were seen
(Fig. 5b). As chloroalstonine (1f) was previously identified (Fig. 3b,c,d)
and natural alstonine (1a) was also present in the broth, we reasoned
that the limiting factor in chloroalstonine (1f) production was chlorot-
ryptamine (7f) competition with natural tryptamine (7a; Fig. 5b). This
hypothesis was addressed by increasing halogenase activity. Functional
expression of tryptophan halogenases, such as LaeRebH, is notoriously
hard to achieve heterologously36,37. Indeed, testing a recently devel-
oped biosensor for misfolded protein expression in yeast38 suggested
that a proportion of this enzyme population aggregates in the yeast
cytoplasm and is most likely not functional (Fig. 5c and Supplementary
Fig. 9). To mitigate this, we repeated the cultivation at a lower tem-
perature (25 °C compared to 30 °C), where secologanin (6) produc-
tion was significantly increased and a peak with an exact mass and
retention time consistent with chloroalstonine (1f) was detected in
the broth from ScH132, albeit with a signal strength too low to obtain
a fragmentation pattern required for positive identification (Fig. 5b).
However, the chlorotryptamine (7f) signal was only mildly improved,

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1556

Articlehttps://doi.org/10.1038/s41589-023-01430-2StrictosidineAlstonineadAlstonine standard, m/z [M + H]+ 349.15Sc161, 7-fluoroalstonine, m/z [M + H]+ 367.14Sc161, 6-fluoroalstonine, m/z [M + H]+ 367.14Sc161, 5-fluoroalstonine, m/z [M + H]+ 367.14Sc161, 4-fluoroalstonine, m/z [M + H]+ 367.14Sc161, 7-chloroalstonine, m/z [M + H]+ 383.11Sc161, 7-bromoalstonine, m/z [M + H]+ 427.06Sc161, 5,6-difluoroalstonine, m/z [M + H]+ 385.14Sc161, 6,7-fluoroalstonine, m/z [M + H]+ 385.14345Time (min)6789102349.1549263.0814235.0865207.0916317.1286383.1157297.0424269.0473241.0525351.08950501005010005010050100349.1549263.0814235.0865207.0916317.1286385.1362299.0626271.0677243.0728353.109905010050100Alstonine standardChloroalstonineRelative abundanceadbcadbcAlstonine standardFluoroalstonine349.1549263.0814235.0865207.0916317.1286367.1456281.0723253.0773335.1196225.0822Relative abundance427.0654340.9925312.9969Alstonine standardBromoralstonineRelative abundance349.1549263.0814235.0865207.0916317.128605010050100bcRelative abundanceDifluoroalstonineAlstonine standardadbcb4-Fluoroalstonine, R1 = F, R2 = R3 = R4 = H5-Fluoroalstonine, R2 = F, R1 = R3 = R4 = H6-Fluoroalstonine, R3 = F, R1 = R2 = R4 = H7-Fluoroalstonine, R4 = F, R1 = R2 = R3 = H7-Chloroalstonine, R4 = Cl, R1 = R2 = R3 = H7-Bromoalstonine, R4 = Br, R1 = R2 = R3 = H5,6-Fluoroalstonine, R2 = R3 = F, R1 = R4 = H6,7-Fluoroalstonine, R1 = R2 = F, R3 = R4 = HcRgnTDCCroSTRRseSGDCroTHASCroSSScTRP5Halo-indoleTryptophanTryptamineStrictosidineaglyconeTetrahydro-alstonine765476546547776547654654757467654654775,64,75,76,74,64,55,64,75,76,74,64,55,64,75,76,74,64,55,66,7Sc161 +100 mg liter–1difluoroindoleSc161 +100 mg liter–1bromoindoleSc161 +100 mg liter–1chloroindoleSc161 +100 mg liter–1fluoroindoleNOOONHHR4R3R2R1abcdi

a
e
r
a
k
a
e
p
n
n
a
g
o
o
c
e
s
n
a
e
M

l

108

107

106

105

104

0.25 mM secologanin

Not fed secologanin

***

***

***

***

***

0.25 mM secologanin

Not fed secologanin

***

***

***

***

108

107

106

105

NS

i

a
e
r
a
k
a
e
p
e
n
n
o
t
s
l
a
o
r
o
u
l
f
n
a
e
M

None

4F

5F

6F

7F

Fluoroindole feed

104

None

4F

5F

6F

7F

Fluoroindole feed

Fig. 4 | Secologanin is the global limiting substrate and TDC is the limiting
enzyme for new-to-nature MIA production in engineered yeast. a, Schematic
of the natural and derivative MIA pathways competing for the secologanin
pool. Bottleneck reactions catalyzed by CroSLS and CroSTR are highlighted
in red. b, Secologanin levels in broth following 144 h of cultivation of Sc154
supplemented with 100 mg liter–1 fluoroindole with and without 0.25 mM

secologanin. c, Fluoroalstonine levels in broth following 144 h of cultivation of
Sc154 supplemented with 100 mg liter–1 fluoroindole with and without 0.25 mM
secologanin. For b and c, data represent mean values plotted with standard
deviation, data points are overlaid as black dots, and statistical significance was
calculated using two-tailed Student’s t-tests; ***P < 0.001; NS, not significant.
Data are shown as means (n = 3).

even with an extra two copies of the halogenase cassette integrated
(Fig. 5b). In a third mitigation approach, we fused a thioredoxin solu-
bility tag to the N terminus of RebH (ScH135)39. After cultivating this
strain at 25 °C, we observed a greater than tenfold improvement in
peak area sufficient to obtain an MS/MS spectrum consistent with
that of chloroalstonine (1f), resulting in de novo microbial synthesis
of a halogenated MIA (Fig. 5b,d,e). To determine if the MIA indole
moieties were being directly chlorinated by LaeRebH, as opposed
to being derived from chlorotryptophan (11f), we next fed four dif-
ferent heteroyohimbines (ajmalicine (4a), tetrahydroalstonine (3a),
serpentine (2a) or alstonine (1a)) to a wild-type strain expressing just
the halogenase cassette. In all cases, only chlorotryptophan (11f) was
observed (Supplementary Fig. 10), meaning that the chlorine entry
point in this refactored pathway is indeed tryptophan (Fig. 5a). Last, an
attempt to replicate this result with bromoalstonine (1g) by cultivating
ScH135 with 300 mM KBr resulted in the production of bromotryp-
tophan (11j) and bromotryptamine (7j), as reported recently35, and
did not yield any further brominated metabolites (data not shown).
The larger size of the bromine atom is likely more inhibitory to flux
through the pathway, meaning higher bromotryptamine levels (Fig.
3d) or protein engineering will be required to achieve de novo bro-
moalstonine biosynthesis.

Discussion
This work demonstrates a scalable de novo manufacturing platform
for bioactive heteroyohimbines in yeast and provides a foundation for
further pathway refactoring toward microbial biosynthesis of both
native and new-to-nature MIAs40. As a proof of principle, we estab-
lish biosynthetic pathways for two heteroyohimbines, from which we
systematically assess enzyme promiscuity, sterical parameters and
metabolic limitations, ultimately enumerating the production of 19
new-to-nature halogenated alstonines and serpentines (Fig. 3d and
Extended Data Fig. 10d). Although not all directly detected, this also
implies production of at least 12 halogenated strictosidine aglycones
(20b–f, 20h–n), 8 halogenated tetrahydroalstonines (3b–i) and 11
halogenated ajmalicines (4b–l). With >3,000 different MIAs naturally
produced in plants and with several plant-sourced MIAs used in the
clinic and as traditional medicines in both their natural and derivatized
forms28,41, the presented platform offers fermentation-based manu-
facturing and potentially future drug discovery within MIAs, a natural
product treasure trove otherwise not easy to source by plant-based
extraction or total synthesis.

However, to realize this potential, several challenges need further
investigation. First, the inherent promiscuity of enzymes, such as Cro-
HYS and CroSS (Fig. 1 and Extended Data Fig. 10a), can create off-target

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1557

Articlehttps://doi.org/10.1038/s41589-023-01430-2TryptophanTryptamineSecologaninStrictosidineMevalonatepathwayHalotryptophanHalotryptamineHalostrictosidineMIAsMIAderivativesHaloindoleFeedingLoganinTDCTRP5STRSLSTDCSTRaShikimatepathwayHNXHNHOOCH2NXHNH2NXGlcOOOOHNHNXHHGlcOOOOOGlcOOOOOHHHHNHOOCH2NHNH2NGlcOOOOHNHNHHbc

a
e
r
a
k
a
e
p
n
a
e
M

108

107

106

105

104

*

*

*

Secologanin
Chlorotryptophan
Chlorotryptamine
Chlorostrictosidine
Chlorotetrahydroalstonine
Chlroalstonine

Sc161
30 °C

Sc161
25 °C

ScH132
30 °C

ScH132
25 °C

ScH143
25 °C

ScH135
25 °C

100

Alstonine standard

349.1549

e
c
n
a
d
n
u
b
a
e
v
i
t
a
l
e
R

80

60

40

20

0

20

40

60

80

100

263.0816

235.0868

317.1288

m/z

269.0475

351.0896

297.0424

ScH135, chloroalstonine

383.1156

Fig. 5 | De novo synthesis of chloroalstonine in yeast. a, Schematic outline
of the de novo chloroalstonine biosynthetic pathway in yeast. b, Peak areas
for chlorinated MIA masses for halogenase-expressing strains and strain
Sc161 (control). Data are shown as mean ± s.d., and data points are overlaid as
black dots; n = 3. Significance was calculated by using a two-tailed Student’s
t-test; *P < 0.05. c, Detection of LaeRebH aggregation with the 4×UAS-SSA1p–
365:mKate2 aggregation biosensor. Green fluorescent protein (GFP; left) and
yellow fluorescent protein m4 (YFPm4; middle) strains were used as controls

for the expression of soluble and aggregation-prone proteins, respectively.
Histograms show reporter signals from uninduced (2% glucose) and induced
(2% galactose) expression of the candidate proteins. Histograms show all data
from n = 4 × 4,000 events. Geometric means are reported in the top left. d, MS
chromatogram traces for alstonine standard and chloroalstonine from ScH125
broth cultured at 25 °C. e, Comparison of the MS/MS spectra of an alstonine
standard and the chloroalstonine peak in d shows a similar fragmentation pattern
and a mass shift consistent with a hydrogen-to-chlorine substitution.

reactions. This is a particular problem when investigating the ability of
natural product pathways to turnover substrate analogs as competing
branches can be differentially affected, changing dominant MIA pro-
duction and complicating efforts to produce specific MIA derivatives in
planta16. Characterizing the specific product profiles of these enzymes
in a yeast cell factory context (for example, using the method described
by Yamamoto et al.12) and understanding their implications for yields
and purification strategies will be important future work. Second, the
integration of larger halogens is challenging, as evidenced by the par-
ticularly poor passage of the bulky bromine-substituted compounds
through the MIA pathway (Fig. 3d and Extended Data Figs. 9 and 10d).
Likewise, challenges remain regarding secologanin (6) precursor avail-
ability and STR promiscuity. Here, further bioprospecting or protein
engineering would be warranted42.

With this said, enzyme promiscuity can also be an advantage when
deploying microbial cell factories as an explorative tool for probing
novel regions of chemical space for drug discovery43. Although several
studies have previously investigated the promiscuity of MIA pathway
enzymes for halogenated derivatives in planta16, in vitro14 and recently
in yeast30,35,44, this study expands on prior work in the biosynthesis of

halogenated MIA scaffolds by (1) systematically assessing the turnover
of a wider range of halogenated derivatives by the seven MIA enzymes
separating indole from alstonine (1a) and serpentine (2a; Supplemen-
tary Table 8); (2) demonstrating the semisynthesis of 8 derivatives of
the bioactive alstonine, including diflourinated MIAs (Fig. 3d), which
is notable as successive fluorination has been shown to have additive
effects on ligand binding capacity45, and 11 serpentine derivatives (9 of
which have not been reported before; Extended Data Fig. 10d) and (3)
facilitating further study by demonstrating the utility of cheaper indole
substrates as a viable derivative entry point into the MIA pathway. In
addition to this, the successful biosynthesis of chloroalstonine using
LaeRebH represents the first de novo production of an MIA derivative
in yeast (Fig. 5d,e).

Last, although the fluorinated alstonine (1b–e) and serpentine
(2b–e) analogs are interesting due to overrepresentation in medicinal
compounds46 and the reported effects on MIA potency4, the integra-
tion of chlorine and bromine atoms onto the indole moiety may be of
greater long-term impact because, as effective leaving groups, they
allow specific targeting of the carbon for further derivatization via
chemical cross-coupling to organic groups47. This would allow the

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1558

Articlehttps://doi.org/10.1038/s41589-023-01430-2ChlorotryptophanChlorotryptamineChlorostrictosidineChlorotrictosidine aglyconeChlorotetrahydroalstonineChloroalstonineTryptophanSecologaninFADH2FADEcoSsuELaeRebHRgnTDCCroSTRaRseSGDCroTHASCroSSGlucoseHNH2NOHOHNH2NOHOClHNH2NClHNHNOOOOGlcClNOOOHNHHHClHNHNOOOOHClNOOONHHClcb456789Time (min)Alstonine standardSc161, chloroalstonine 25 °CScH135, chloroalstonine 25 °CdeStrain names and conditionsGFPRebHYFPm4FL5-A :: mKate_APC-A2% Glucose2% Galactose10–11001011021030100200300400Count18.618.219.620.8183145

joining of natural and synthetic spheres of chemical space and unlock
a near infinite number of MIA derivatives, which could form the future
basis of natural product libraries and address the relative lack of drug
screening libraries surrounding the privileged indole moiety.

Online content
Any methods, additional references, Nature Portfolio reporting sum-
maries, source data, extended data, supplementary information,
acknowledgements, peer review information; details of author contri-
butions and competing interests; and statements of data and code avail-
ability are available at https://doi.org/10.1038/s41589-023-01430-2.

References
1.  O’Connor, S. E. & Maresh, J. J. Chemistry and biology of

monoterpene indole alkaloid biosynthesis. Nat. Prod. Rep. 23,
532–547 (2006).

2.  Brown, T. K. & Alper, K. Treatment of opioid use disorder with
ibogaine: detoxification and drug use outcomes. Am. J. Drug
Alcohol Abuse 44, 24–36 (2018).

3.  Elisabetsky, E. & Costa-Campos, L. The alkaloid alstonine:
a review of its pharmacological properties. Evid. Based
Complement. Alternat. Med. 3, 39–48 (2006).

4.  Gotoh, H., Duncan, K. K., Robertson, W. M. & Boger, D. L.

10′-Fluorovinblastine and 10′-fluorovincristine: synthesis of a key series
of modified vinca alkaloids. ACS Med. Chem. Lett. 2, 948–952 (2011).

19.  Stavrinides, A. et al. Unlocking the diversity of alkaloids in

Catharanthus roseus: nuclear localization suggests metabolic
channeling in secondary metabolism. Chem. Biol. 22,
336–341 (2015).

20.  Stavrinides, A. et al. Structural investigation of heteroyohimbine
alkaloid synthesis reveals active site elements that control
stereoselectivity. Nat. Commun. 7, 12116 (2016).
21.  Dang, T.-T. T. et al. Sarpagan bridge enzyme has

substrate-controlled cyclization and aromatization modes.
Nat. Chem. Biol. 14, 760–763 (2018).

22.  Kellner, F. et al. Genome-guided investigation of plant natural

product biosynthesis. Plant J. 82, 680–692 (2015).

23.  Liu, Q. et al. De novo biosynthesis of bioactive isoflavonoids

by engineered yeast cell factories. Nat. Commun. 12, 6085
(2021).

24.  Westfall, P. J. et al. Production of amorphadiene in yeast, and its

conversion to dihydroartemisinic acid, precursor to the antimalarial
agent artemisinin. Proc. Natl Acad. Sci. USA 109, E111–E118 (2012).

25.  Costa-Campos, L., Dassoler, S. C., Rigo, A. P., Iwu, M. &

Elisabetsky, E. Anxiolytic properties of the antipsychotic alkaloid
alstonine. Pharmacol. Biochem. Behav. 77, 481–489 (2004).

26.  Kapolka, N. J. et al. DCyFIR: a high-throughput CRISPR

platform for multiplexed G protein-coupled receptor profiling
and ligand discovery. Proc. Natl Acad. Sci. USA 117, 13117–13126
(2020).

5.  Shuman, A. & Unguru, Y. Drug shortages: the view across an

27.  Lengger, B. et al. Serotonin G protein-coupled receptor-

6.

ocean. Oncologist 25, 274–276 (2020).
Ishikawa, H. et al. Total synthesis of vinblastine, vincristine,
related natural products, and key structural analogues. J. Am.
Chem. Soc. 131, 4904–4916 (2009).

based biosensing modalities in yeast. ACS Sens. 7, 1323–1335
(2022).

28.  Modi, S. et al. Trastuzumab deruxtecan in previously treated

HER2-positive breast cancer. N. Engl. J. Med. 382, 610–621 (2020).

7.  Galanie, S., Thodey, K., Trenchard, I. J., Filsinger Interrante, M. &

29.  McDonald, A. D., Perkins, L. J. & Buller, A. R. Facile in vitro

Smolke, C. D. Complete biosynthesis of opioids in yeast. Science
349, 1095–1100 (2015).

biocatalytic production of diverse tryptamines. ChemBioChem
20, 1939–1944 (2019).

8.  Luo, X. et al. Complete biosynthesis of cannabinoids and their
unnatural analogues in yeast. Nature 567, 123–126 (2019).
9.  Zhang, J. et al. A microbial supply chain for production of the
anti-cancer drug vinblastine. Nature 609, 341–347 (2022).

10.  Qu, Y. et al. Completion of the seven-step pathway from

tabersonine to the anticancer drug precursor vindoline and its
assembly in yeast. Proc. Natl Acad. Sci. USA 112, 6224–6229 (2015).
11.  Liu, T. et al. Construction of ajmalicine and sanguinarine de novo
biosynthetic pathways using stable integration sites in yeast.
Biotechnol. Bioeng. 119, 1314–1326 (2022).

12.  Yamamoto, K. et al. Improved virus-induced gene silencing allows

discovery of a serpentine synthase gene in Catharanthus roseus.
Plant Physiol. 187, 846–857 (2021).

13.  Kwan, B. D., Seligmann, B., Nguyen, T.-D., Franke, J. & Dang, T.-T.

30.  Misa, J., Billingsley, J. M., Niwa, K., Yu, R. K. & Tang, Y. Engineered

production of strictosidine and analogues in yeast. ACS Synth.
Biol. 11, 1639–1649 (2022).

31.  Kumar, S. et al. Structural characterization of monoterpene

indole alkaloids in ethanolic extracts of Rauwolfia species by
liquid chromatography with quadrupole time-of-flight mass
spectrometry. J. Pharm. Anal. 6, 363–373 (2016).

32.  Maresh, J. J. et al. Strictosidine synthase: mechanism of a

Pictet–Spengler catalyzing enzyme. J. Am. Chem. Soc. 130,
710–723 (2008).

33.  Yeh, E., Garneau, S. & Walsh, C. T. Robust in vitro activity of RebF
and RebH, a two-component reductase/halogenase, generating
7-chlorotryptophan during rebeccamycin biosynthesis. Proc. Natl
Acad. Sci. USA 102, 3960–3965 (2005).

T. Leveraging synthetic biology and metabolic engineering to
overcome obstacles in plant pathway elucidation. Curr. Opin.
Plant Biol. 71, 102330 (2023).

14.  McCoy, E., Galan, M. C. & O’Connor, S. E. Substrate specificity of

34.  Heemstra, J. R. Jr & Walsh, C. T. Tandem action of the O2- and
FADH2-dependent halogenases KtzQ and KtzR produce
6,7-dichlorotryptophan for kutzneride assembly. J. Am. Chem.
Soc. 130, 14024–14025 (2008).

strictosidine synthase. Bioorg. Med. Chem. Lett. 16, 2475–2478 (2006).

35.  Milne, N. et al. Metabolic engineering of Saccharomyces

15.  McCoy, E. & O’Connor, S. E. Directed biosynthesis of alkaloid

analogs in the medicinal plant Catharanthus roseus. J. Am. Chem.
Soc. 128, 14276–14277 (2006).

16.  Runguphan, W., Qu, X. & O’Connor, S. E. Integrating carbon–

halogen bond formation into medicinal plant metabolism. Nature
468, 461–464 (2010).

17.  Orr, M. J. et al. Discovery of highly potent serotonin 5-HT2 receptor
agonists inspired by heteroyohimbine natural products. ACS Med.
Chem. Lett. 13, 648–657 (2022).

18.  Gerasimenko, I., Sheludko, Y., Ma, X. & Stöckigt, J. Heterologous

expression of a Rauvolfia cDNA encoding strictosidine
glucosidase, a biosynthetic key to over 2000 monoterpenoid
indole alkaloids. Eur. J. Biochem. 269, 2204–2213 (2002).

cerevisiae for the de novo production of psilocybin and related
tryptamine derivatives. Metab. Eng. 60, 25–36 (2020).

36.  Payne, J. T., Andorfer, M. C. & Lewis, J. C. Regioselective arene
halogenation using the FAD-dependent halogenase RebH.
Angew. Chem. Int. Ed. Engl. 52, 5271–5274 (2013).

37.  Poor, C. B., Andorfer, M. C. & Lewis, J. C. Improving the stability
and catalyst lifetime of the halogenase RebH by directed
evolution. ChemBioChem 15, 1286–1289 (2014).

38.  Romero-Suarez, D. et al. A reporter system for cytosolic protein

aggregates in yeast. ACS Synth. Biol. 10, 466–477 (2021).
39.  LaVallie, E. R. et al. A thioredoxin gene fusion expression

system that circumvents inclusion body formation in the E. coli
cytoplasm. Biotechnology 11, 187–193 (1993).

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1559

Articlehttps://doi.org/10.1038/s41589-023-01430-240.  Pothakos, V. et al. Fermentation titer optimization and impact on
energy and water consumption during downstream processing.
Chem. Eng. Technol. 41, 2358–2365 (2018).

47.  Frese, M. et al. Modular combination of enzymatic halogenation
of tryptophan with Suzuki–Miyaura cross-coupling reactions.
ChemCatChem 8, 1799–1803 (2016).

41.  Geiser, C. F. & Mitus, J. W. Acute monocytic leukemia in children
and its response to vinblastine (NSC-49842). Cancer Chemother.
Rep. 59, 385–388 (1975).

42.  Chen, S., Galan, M. C., Coltharp, C. & O’Connor, S. E. Redesign
of a central enzyme in alkaloid biosynthesis. Chem. Biol. 13,
1137–1141 (2006).

43.  Glasner, M. E., Truong, D. P. & Morse, B. C. How enzyme

promiscuity and horizontal gene transfer contribute to metabolic
innovation. FEBS J. 287, 1323–1342 (2020).

44.  Shahsavarani, M. et al. Improved protein glycosylation enabled

heterologous biosynthesis of monoterpenoid indole alkaloids
and their unnatural derivatives in yeast. Metab. Eng. Commun. 16,
e00215 (2023).

45.  Biffinger, J. C., Kim, H. W. & DiMagno, S. G. The polar

hydrophobicity of fluorinated compounds. ChemBioChem 5,
622–627 (2004).

46.  Fejzagić, A. V., Gebauer, J., Huwa, N. & Classen, T. Halogenating

Publisher’s note Springer Nature remains neutral with regard to
jurisdictional claims in published maps and institutional affiliations.

Open Access This article is licensed under a Creative Commons
Attribution 4.0 International License, which permits use, sharing,
adaptation, distribution and reproduction in any medium or format,
as long as you give appropriate credit to the original author(s) and the
source, provide a link to the Creative Commons license, and indicate
if changes were made. The images or other third party material in this
article are included in the article’s Creative Commons license, unless
indicated otherwise in a credit line to the material. If material is not
included in the article’s Creative Commons license and your intended
use is not permitted by statutory regulation or exceeds the permitted
use, you will need to obtain permission directly from the copyright
holder. To view a copy of this license, visit http://creativecommons.
org/licenses/by/4.0/.

enzymes for active agent synthesis: first steps are done and many
have to follow. Molecules 24, 4008 (2019).

© The Author(s) 2023

Nature Chemical Biology | Volume 19 | December 2023 | 1551–1560

1560

Articlehttps://doi.org/10.1038/s41589-023-01430-2Methods
Chemical standards
All chemical standards (Supplementary Table 2) had a purity of 95%
or higher.

Genes
All biosynthetic genes used in the current study are listed in Supple-
mentary Table 3. Genes were synthesized by either Integrated DNA
Technologies or Twist Bioscience and optimized for expression in S.
cerevisiae unless stated otherwise (_nat). The new candidates of AS
(RteAS1–RteAS5) were predicted by using the RNA-sequencing reads
from project PRJEB39488, downloaded from NCBI. This project con-
tains libraries prepared from young developing leaves and mature
and immature leaves and roots. Reads were trimmed with fastp v0.22
(ref. 48) and first merged into super reads following the procedure
described in the StringTie v2.0 manual using the super-read module
from MaSuRCA49. Paired reads were then de novo assembled with
Trinity v2.8 (ref. 50) using the merged super reads as long-read data.
Cd-hit was further used to cluster identical and redundant protein
sequences51. The blast+ suite v2.9 was used to identify putative ASs in
the resulting compacted assembly52. Alignment and phylogeny were
performed in SeaView v4.0 (ref. 53).

Cloning and yeast transformation
All plasmids were constructed by USER cloning54 and propagated in E.
coli DH5α competent cells. Genes for integrative Easy Clone marker-free
vectors were prepared according to Jessop-Fabre et al.55, and the gRNA
expression cassettes were prepared as previously described56. All
plasmids (Supplementary Table 4) were verified by Sanger sequencing
before yeast transformation. The integrative plasmids were linearized
by treatment with NotI (New England Biolabs). Yeast transformations
were performed using standard lithium acetate methods according to
Gietz and Schiestl57. The integration of heterologous genes was verified
as described in CasEMBLR55,56.

Yeast cultivation and sample preparation
All yeast strains used and constructed in this study (Supplementary
Table 5) are based on CEN.PK2-1C, except for the sensing strain used for
ADRA2A bioactivity, which was based on BY4741. The de novo stricto-
sidine platform, MIA-CM-3, was recently described by Zhang et al.9. To
test the yeast strains for production, three colonies were inoculated in
150 µl of SC and incubated overnight at 30 °C and 300 r.p.m. in a 96-well
microtiter plate. After 16 h, 10 µl of each culture was transferred into
0.5 ml of fresh medium in a deep-well plate and incubated for 144 h
at 30 °C and 400 r.p.m. Yeast strains were cultivated either in YPD
or SC. The strains for AS (Sc86–Sc88, Sc90, Sc92, Sc94, Sc96–Sc98,
Sc100–Sc104 and Sc157) did not express the strictosidine pathway
but only CroSTR and downstream genes (Fig. 1a). These strains were
fed with 0.25 mM secologanin and 1 mM tryptamine at the start of cul-
tivation. Following 144 h, 100 µl of sample was combined with 100 µl
of caffeine (900 µg liter–1) and filtered through a filter plate (PALL,
AcroPrep Advance, 0.2-µm Supor membrane for medium/water) by
centrifugation at 2,200g for 1 min. Samples (2 µl) samples were injected
for analytical measurements.

For the production of halogenated MIAs using haloindole feeding,
triplicate overnight cultures in 18 ml of 3× SC and 2% glucose supple-
mented with 20 g liter–1 bovine peptone (Sigma-Aldrich) were incu-
bated for 72 h at 30 °C or 25 °C and 300 r.p.m. in a baffled shake flask.
Each culture was centrifuged at 3,000 r.p.m. for 5 min, the superna-
tant was discarded, and the pellet was washed three times in 10 ml of
PBS with 5% ethanol and resuspended in 6 ml of 3× synthetic defined
(SD) medium without tryptophan supplemented with 2% galactose
and 0.25 mM secologanin. The optical density at 600 nm (OD600) was
then corrected to 80. The cell suspension (270 µl) was transferred to
a 96-well deep-well plate, and 30 µl of 1 g liter–1 indole, 4-fluoroindole,

Nature Chemical Biology

5-fluoroindole,  6-fluoroindole,  7-fluoroindole,  4-chloroindole,
5-chloroindole, 6-chloroindole, 7-chloroindole, 4-bromoindole,
5-bromoindole, 6-bromoindole, 7-bromoindole, 4,5-difluoroindole,
4,6-difluoroindole,  4,7-difluoroindole,  5,6-difluoroindole,
5,7-difluoroindole or 6,7-difluoroindole dissolved in 3× SC plus 5%
acetone was added to the well. The plate was incubated for 144 h at
30 °C or 25 °C and 400 r.p.m. After 72 h, 15 µl of 2% galactose was spiked
into each well. After 144 h, 100 µl of sample was filtered through a
filter plate (PALL, AcroPrep Advance, 0.2-µm Supor membrane for
medium/water) by centrifugation at 2,200g for 1 min. Samples (1 µl)
were injected for analytical measurements. An identical protocol was
followed for de novo integration of halogens, except 30 µl of 3× SD sup-
plemented with 1 g liter–1 tryptophan and 3 M NaCl or KBr was added
instead of 30 µl of indole.

Analytical methods
For  routine  sample  analysis,  an  advance  UHPLC  system  (Bruker
Daltonics) coupled to an EVOQ Elite triple quadrupole mass spectrom-
eter (Bruker Daltonics) was used. The applied column was a 100-mm
C18 Acquity UPLC HSS T3 column (100 Å) with a 1.8-µm particle size
and 2.1-mm inner diameter (Waters); with [KBA1], the column oven
temperature was 35 °C. The mobile phase consisted of Milli-Q water
(solvent A) and acetonitrile (solvent B) both with 0.1% formic acid.
The flow rate was 0.5 ml min–1 with the following gradient profile:
isocratic 0–0.8 min at 5% B, gradient 0.8–4 min from 5 to 55% B, gradi-
ent 4–4.2 min from 55 to 95% B and isocratic 4.2–5.5 min at 95% B. The
column was reequilibrated for ~2 min before the next injection, and
the instrument was navigated by MS Workstation software version
8.210.0.253 (Bruker Daltonics). Multiple reaction monitoring data
(Supplementary Table 6) were collected by electrospray ionization
that operated in positive ion mode with the following parameters:
spray voltage of 4.5 kV, cone temperature of 350 °C, cone gas flow
of 20, probe gas flow of 50, nebulizer gas flow of 50, heated probe
temperature of 300 °C, exhaust gas on and a collision-induced dis-
sociation of 1.5 mTorr. Analyte stock solutions were prepared in etha-
nol for tryptamine, tetrahydroalstonine, ajmalicine, serpentine and
alstonine and in Milli-Q water for loganic acid, loganin, secologanin
and strictosidine. Ten levels of calibration were prepared, diluting the
standard mixture with SC or YPD (Supplementary Table 6). The calibra-
tion curves for alstonine and ajmalicine were prepared separately to
avoid their interferences on coeluting isomers serpentine and THA,
respectively. Caffeine (0.9 mg liter–1) was used as an internal standard
in standards and samples. The calibration levels were weighted as 1/x,
and the curve was fitted by linear regression. When the concentration
of MIAs in the samples exceeded the highest concentration used in the
calibration curve, the samples were diluted.

To confirm the reported activity of CroTHAS1 and CroHYS, when
heterologously expressed in yeast, method 2 described by Stavrinides
et al.20 was applied. To confirm the identity of alstonine and serpen-
tine, which has the same retention time in the routine LC–MS method
applied in this study, we compared LC–MS transition profiles to the
ones obtained by high-resolution MS (LC–HRMS). Both standards
along with the alstonine de novo producers were included. When the
two stereoisomers were compared by both methods, the ratio of the
fragment ion 316.9 was comparatively higher for serpentine than alsto-
nine (Extended Data Fig. 6). The analysis of halogenated MIAs was
performed on a Vanquish Duo UHPLC binary system (Thermo Fisher
Scientific) coupled to an Orbitrap ID-X mass spectrometer (Thermo
Fisher Scientific). The data were acquired in positive mode with a
voltage of 3,500 V, and the rest of the parameters were as described
previously by Kildegaard et al.58.

For detection of halogenated compounds, LC–MS/MS analysis
was performed using a Vanquish Duo UHPLC binary system (Thermo
Fisher Scientific) coupled to an Orbitrap ID-X Tribrid mass spectrom-
eter (Thermo Fisher Scientific). Chromatographic separation was

Articlehttps://doi.org/10.1038/s41589-023-01430-2achieved under reverse-phase conditions as previously described58.
The MS measurements were performed in positive-heated electrospray
ionization mode with a voltage of 3,500 V acquiring the full MS/MS
spectra (data-dependent acquisition-driven MS/MS) in the mass range
of 70–100 Da. The following data-dependent acquisition settings were
used: automatic gain control target value of 4 × 105 for full-scan MS
and 5 × 104 for the MS/MS spectral acquisition and a mass resolution
of 120,000 for full-scan MS and 30,000 for MS/MS events. Precursor
ions were fragmented by stepped high-energy collision dissociation
using collision energies of 20, 40 and 60. As a general note, as standards
for halogenated MIA analogs are not commercially available, halogen-
ated MIAs were identified based on exact mass and retention times and
MS/MS spectra shifts relative to the unhalogenated standard, as previ-
ously described30,45,59 (Supplementary Table 9).

Glucose, ethanol and organic acids
Glucose, ethanol and organic acids were analyzed using a Rezex
ROA-Organic  Acid  H+  (8%;  150 × 7.8 mm)  column  on  a  Vanquish
dual-system HPLC coupled with a refractive index (IDEX RefractoMax
521) and diode array detector. The HPLC was run with a flow rate of
0.7 ml min–1 (isocratic) using 9 mM sulfuric acid at a column tempera-
ture of 60 °C. The injection loop volume was kept to 5 µl for all samples
and standards. For diode array detection, a 210-nm wavelength was
used for detection and confirmation of organic acids. Peak identifica-
tion was based on the relative retention times determined by injection
of standard solutions. Quantification of compounds was performed
using calibration curves on Chromeleon software, version 7.2.8.

Microbioreactor
For fed-batch cultivations, the microbioreactor screening platform Bio-
Lector Pro coupled to RoboLector (mp2-labs) was used. The microbial
cultures were cultivated in microfluidic flower plates (MTP-MF32C-BOH2,
mp2-labs) in triplicate with a starting OD600 of 0.5 and 1-ml volume, essen-
tially as described previously9. The process started with 20 h of batch
phase (3× SC, 2% glucose and 3 mM tryptophan) followed by exponential
feeding with 36% glucose at a 0.48*exp(0.0125t) feeding rate until 144 h.
To test the effect of supplementation of the medium on alstonine pro-
duction, 10 g liter–1 soy peptone (Sigma-Aldrich) or 10 g liter–1 bovine
peptone (Sigma-Aldrich) was added to the medium, the culture was
maintained at 30 °C and 1,000 r.p.m., and the pH was maintained at
5.5 with the automatic addition of 10% NH4OH solution. The relative
humidity in the growth chamber was maintained at 85% to minimize
evaporation of the medium. The biomass, pH and dissolved oxygen were
recorded during the run using built-in optical sensors. The cultures were
sampled at 48, 96 and 144 h, processed as described in Yeast cultivation
and sample preparation and analyzed for glucose, ethanol, organic acids
and MIAs (routine LC–MS method). Biomass was determined using 0.5 ml
of each sample dried at 60 °C overnight.

Microtiter plate reader
Triplicate overnight cultures of 1 ml of SC plus 2% glucose were inocu-
lated in 15-ml cultivation tubes and incubated overnight at 30 °C. One
hundred and fifty microliters of each overnight culture was diluted
100-fold in SC plus 2% glucose. Then, 135 µl of the 100-fold-diluted
cell suspension was added to a clear-bottomed 96-well plate. Fifteen
microliters of 1 g liter–1 haloindole in 3× SD and 20% DMSO was added
to each well. The plate was then covered with a Breathe-Easy sealing
membrane (Diversified Biotech BEM-1) and incubated in a SynergyMX
microtiter plate reader (BioTek) at 30 °C and 250 r.p.m., and the OD600
was measured every 20 min for 48 h. Growth curves were processed
and analyzed using a Python regression analysis script60.

of batch phase (3× SC, 2% glucose and 3 mM tryptophan), followed by a
fed-batch phase. Sc112 was fed as described for the microbioreactor experi-
ments with a 6% glucose feed. ScH144 was fed with pulses of the batch
medium concentrated ten times without tryptophan with 200 g liter–1 glu-
cose or 153.5 g liter–1 ethanol (equivalence of carbon molarity). For pulsed
fed-batch, yeast nitrogen base concentration in the feed was decreased by
three after 95 h of feeding to avoid over osmotic pressure.

Purification of alstonine
Purification of alstonine for NMR and bioactivity tests included a
four-step procedure based on liquid–liquid extraction, silica pretreat-
ment and two repeated steps of purification by LC. First, for liquid–liquid
extraction, cultivation broth from controlled bioreactors was collected
based on centrifugation and collection of 1.5 liters of supernatant. Next,
two rounds of liquid–liquid extraction with 1:1 dichloromethane:broth
were performed, and the aqueous phase was concentrated by vacuum.
For silica pretreatment, the dried extract was solubilized with water and
methanol and then a normal phase of silica (Fuji Silysia, Chromatorex
GS60 20/45 µm). Following subsequent homogenization, this solution
was concentrated under vacuum to give a dry extract, and the dried
extract was purified using silica gel (Fuji Silysia, Chromatorex GS60
20/45 µm) column chromatography with a different ratio of methylene
chloride:methanol (100:0–0:100), yielding the first crude alstonine
extract. Fractions containing alstonine were then pooled and concen-
trated to dryness, from which the amount of product was approximately
4 g with a purity of alstonine at 250 nm of <1%. Following this, the first LC
step of purification was performed with a Dynamic Axial Column with a
50-mm diameter. The silica gel used was Kromasil C18 5 µm (300 g), with
a mobile phase consisting of water with 0.1% formic acid:acetonitrile
(80:20 (vol/vol)) and washing solvent consisting of 70:30 (vol/vol) formic
acid:acetonitrile and a flow rate of 70 ml min–1. For diode array-based
detection, a 250-nm wavelength was used for detection. All fractions
containing alstonine were pooled, dry distilled and concentrated under
vacuum. From this, 100 mg of alstonine was recovered with 10% relative
purity by HPLC. Last, a second step of purification was performed on a
semipreparative system. Here, the silica gel used was Aquasil C18 5 µm
(250 × 20 mm), with a mobile phase consisting of water with 0.1% formic
acid:methanol (65:35 (vol:vol)) and washing solvent consisting of 20:80
(vol:vol) formic acid:acetonitrile. The flow rate was fixed at 8 ml min–1.
For diode array-based detection, a 250-nm wavelength was used. For the
second purification step, the quantity injected was fixed at 50 mg per run,
and all fractions containing alstonine were again pooled, dry distilled and
concentrated under vacuum. From this, we obtained 2 mg of alstonine,
which was recovered with 95% relative purity by HPLC.

SPE purification
Before NMR, the alstonine sample was purified by short-path chroma-
tography using an SPE cartridge (Discovery DPA-6S, 250 mg, volume
3 ml (Supelco)). The SPE cartridge was conditioned with 3 column
volumes of deionized water and equilibrated with 5 column volumes
of methanol. The product was loaded with a small amount of methanol
and eluted by methanol. The eluted solution was collected as fractions,
and each fraction was checked by LC–MS. The purest fraction was dried
under N2 stream and subjected to NMR measurement.

NMR methods
NMR measurements were performed on a 700 MHz Bruker Avance III
HD spectrometer (Bruker Biospin) equipped with a TCI cryoprobe using
standard pulse sequences, as implemented in Bruker Topspin version
3.6.1 (Bruker Biospin). Chemical shifts were referenced to the residual
solvent signals of methanol-d3 (δH 3.31).

Two-liter bioreactor procedures for Sc112 and FH144
Fed-batch cultivations at 2-liter scales were performed and monitored as
previously described61 with the pH set to 5.5. The process started with 20 h

NMR data of alstonine from fermentation as formic acid salt
1H NMR (700 MHz, methanol-d3): δ ppm: 1.48 (d, J = 6.2 Hz, 3H), 2.56 (dddd,
J = 9.7, 5.8, 5.6, 5.1 Hz, 1H), 3.21 (dddd, J = 9.3, 6.3, 6.2, 5.6 Hz, 1H), 3.37 (dd,

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2J = 17.5, 9.3 Hz, 1H), 3.79 (s, 3H), 4.02 (dq, J = 9.7, 6.2 Hz, 1H), 4.17 (dd, J = 17.5,
6.3 Hz, 1H), 4.69 (dd, J = 14.3, 5.1 Hz, 1H), 5.03 (dd, J = 14.3, 5.8 Hz, 1H), 7.46
(dd, J = 8.0, 7.5 Hz, 1H), 7.73 (s, 1H), 7.75 (d, J = 8.2, 1H), 7.79 (dd, J = 8.2,
7.5 Hz, 1H), 8.38 (d, J = 8.0, 1H), 8.46 (d, J = 6.4, 1H) and 8.52 (d, J = 6.4, 1H).
The chemical shifts were in agreement with published data62.

in a SynergyMX microtiter plate reader (BioTek). Luminescence was
measured at 12, 13.5 and 15 min after mixing. The settings were filter
luminescence, with a gain of 110 and 0.5-s integration per well; the
average of each of the time points is reported as single replicates
per well.

Assessment of RebH aggregation
Protein aggregation was assessed in strains expressing three copies of
target proteins expressed from Gal1p integrated in LP3 landing pads63
and the aggregation reporter 4×UAS-SSA1p–365:mKate2 (ref. 38).
A strain expressing GFP was used as a non-aggregation control, and a
strain expressing the non-fluorescent and aggregation-prone target
YFPm4 (ref. 64) was used as a positive control for aggregation. Strains
expressing YFPm4 and RebH also expressed the Hsp104–GFP fusion
protein to visualize aggregates. Assessment of aggregates was done
in cultures of single colonies in 96-well plates with four replicates per
condition, totaling three strains (GFP, YFPm4 and RebH strains) and
two conditions (2% glucose and 2% galactose media). Precultures were
grown overnight in 150 µl of SC medium with 2% glucose at 30 °C and
300 r.p.m. Cultures were diluted 75-fold in SC with 2% glucose or 2%
galactose and incubated for 16 h at 30 °C at 300 r.p.m. Samples were
taken for flow cytometry (reporter 4×UAS-SSA1p–365:mKate2) and
microscopy. For assessment of aggregation using the 4×UAS-SSA1p–
365:mKate2 aggregation reporter, samples of strains expressing target
proteins were assessed in a MACSQuant Analyzer VYB flow cytometer
(Miltenyi Biotec), totaling four distinct samples per condition. Cell
populations were gated for singlets using an FSC-A versus FSC-H plot,
and 4,000 singlet events were recorded per sample. A 561-nm laser
and 661/20-nm filter were used for the mKate2 measurements. For
observation of protein aggregates by microscopy, strains were grown
overnight in 96-well plates in 150 µl of SC medium with 2% glucose at
30 °C and 300 r.p.m. Cultures were diluted 1:75 in SC with 2% galactose
for 16 h at 30 °C and 250 r.p.m. Aggregates were observed with a Leica
DM4000 B microscope equipped with a DFC 300 FX R2 camera and an
EL600 light source (Leica Microsystems). Excitation/emission filters
used for GFP were 470/40 nm and 525/50 nm, respectively.

Alstonine bioactivity assays
Yeast  strain  Sc272  expresses  NanoLuc  after  stimulation  of  the
ADRA2A  receptor.  Sc272  was  generated  by  changing  the  super-
folder GFP reporter to NanoLuc and integrating ADRA2A in the base
strain yWS2267 (ref. 65). This design was inspired by the similar
ADRA2A-sensing yeast described in ref. 26, and the luciferase assay was
performed essentially as previously reported66. Before the bioactivity
assay, Sc272 was inoculated from cryostock into 5 ml of SC-tryptophan
and incubated overnight at 30 °C and 250 r.p.m. Next, 2 ml of culture
was centrifuged at 5,000g for 5 min, and the supernatant was discarded.
The pellet was then resuspended in pH-buffered SC-tryptophan at pH
7.2. The OD600 was measured and adjusted to 1.25 before 40 µl was dis-
tributed to sterile 96-well plates (Greiner, 655101) and covered with a
Breathe-Easy sealing membrane (Diversified Biotech BEM-1). The plates
were incubated for 2 h at 30 °C and 250 r.p.m. before the membrane
was removed. Then, 5 µl of 12 different 10× stock concentrations of
epinephrine, yohimbine or alstonine containing 10% (vol/vol) DMSO
was added in triplicate series. Milli-Q water (5 µl) was then added to the
wells with epinephrine, whereas 5 µl of 500 µM epinephrine in Milli-Q
water was added to wells with alstonine or yohimbine. The plates were
covered again and incubated for 4 h at 30 °C and 250 r.p.m. Twenty
minutes before incubation was completed, a lysis mix of 1.33% (vol/vol)
furimazine (NanoLuc substrate) from Promega in CelLytic Y cell lysis
reagent (Sigma-Aldrich) was mixed, and 15 µl was distributed to wells
of a white, small-volume 96-well plate (Greiner, 675083). Following
incubation, the plate was vortexed for 5 s before the membrane was
removed, 5 µl of each well containing sensing cells was transferred to
the plate containing the lysis mix, and the plate was immediately placed

Nature Chemical Biology

For the bioactivity assay of alstonine on the 5-HT2C receptor con-
ducted in COS7 cells, the level of cAMP was monitored using biolumi-
nescence resonance energy transfer (BRET). This method is based on
a construct consisting of a cAMP-binding protein (exchange protein
activated by cAMP (Epac)), which is flanked by a BRET pair (Renilla
luciferase (Rluc) and YFP). Together, this complex is called cAMP sen-
sor using YFP–Epac–Rluc (CAMYEL)67. cAMP production is sensed as
Epac changes conformation in response to the increasing levels of
cAMP, leading to a loss of BRET intensity. COS7 cells were plated in
poly-d-lysine-coated, white 96-well plates (20,000 cells per well). The
following day, cells were transfected in 100 µl of transfection medium
per well consisting of 20 µg of plasmid pFH78 and 100 µg of CAMYEL
per 10 ml of medium for a total of 5 h and thereafter incubated in 100 µl
of growth medium overnight. The next day, cells were washed twice
with 100 µl of HBSS per well (Gibco, Life Technologies) and preincu-
bated for 30 min at 37 °C with 60 µl of HBSS. The luciferase substrate
coelenterazine (Thermo Fisher Scientific) was added, and, after a 5-min
incubation, a baseline was measured. Ligands were added, and meas-
urements were recorded every minute for 30 min using a CLARIOstar
Plus plate reader. The BRET signal was calculated as the ratio of the
emission intensity at 535 nm (citrine) to the emission intensity at 475 nm
(luciferase). Determinations were made in triplicate. Dose–response
curves were generated using the non-linear regression function in
GraphPad Prism version 9.5.0 for Windows from GraphPad Software.
For the ADRA2A receptor, the model used the variable slope setting,
whereas the model for 5-HT2C assumed Hill coefficients of 1 and −1 for
stimulation and inhibition curves, respectively.

Reporting summary
Further information on research design is available in the Nature
Portfolio Reporting Summary linked to this article.

Data availability
Data supporting the findings of this work are available within the
article, Extended Data figures and Supplementary Information. The
datasets generated and analyzed during the current study are also
available from the corresponding authors upon request. Source data
are provided with this paper.

Code availability
Not applicable.

References
48.  Chen, S., Zhou, Y., Chen, Y. & Gu, J. fastp: an ultra-fast all-in-one
FASTQ preprocessor. Bioinformatics 34, i884–i890 (2018).
49.  Pertea, M. et al. StringTie enables improved reconstruction
of a transcriptome from RNA-seq reads. Nat. Biotechnol. 33,
290–295 (2015).

50.  Haas, B. J. et al. De novo transcript sequence reconstruction from

RNA-seq using the Trinity platform for reference generation and
analysis. Nat. Protoc. 8, 1494–1512 (2013).

51.  Li, W. & Godzik, A. Cd-hit: a fast program for clustering and
comparing large sets of protein or nucleotide sequences.
Bioinformatics 22, 1658–1659 (2006).

52.  Camacho, C. et al. BLAST+: architecture and applications. BMC

Bioinformatics 10, 421 (2009).

53.  Gouy, M., Guindon, S. & Gascuel, O. SeaView version 4: a

multiplatform graphical user interface for sequence alignment
and phylogenetic tree building. Mol. Biol. Evol. 27, 221–224
(2010).

Articlehttps://doi.org/10.1038/s41589-023-01430-254.  Nour-Eldin, H. H., Hansen, B. G., Nørholm, M. H. H., Jensen, J. K. &
Halkier, B. A. Advancing uracil-excision based cloning towards an
ideal technique for cloning PCR fragments. Nucleic Acids Res. 34,
e122 (2006).

55.  Jessop-Fabre, M. M. et al. EasyClone-MarkerFree: a vector

toolkit for marker-less integration of genes into Saccharomyces
cerevisiae via CRISPR–Cas9. Biotechnol. J. 11, 1110–1117 (2016).
56.  Jakočiūnas, T. et al. Multiplex metabolic pathway engineering

using CRISPR/Cas9 in Saccharomyces cerevisiae. Metab. Eng. 28,
213–222 (2015).

57.  Gietz, R. D. & Schiestl, R. H. Large-scale high-efficiency yeast

transformation using the LiAc/SS carrier DNA/PEG method. Nat.
Protoc. 2, 38–41 (2007).

58.  Kildegaard, K. R. et al. Tailored biosynthesis of gibberellin plant

hormones in yeast. Metab. Eng. 66, 1–11 (2021).

59.  Dalvi, V. H. & Rossky, P. J. Molecular origins of fluorocarbon
hydrophobicity. Proc. Natl Acad. Sci. USA 107, 13603–13607
(2010).

60.  Hoeflinger, J. L., Hoeflinger, D. E. & Miller, M. J. A dynamic

regression analysis tool for quantitative assessment of bacterial
growth written in Python. J. Microbiol. Methods 132, 83–85 (2017).

61.  Kulagina, N. et al. Enhanced bioproduction of anticancer

precursor vindoline by yeast cell factories. Microb. Biotechnol. 14,
2693–2699 (2021).

62.  Younai, A., Zeng, B.-S., Meltzer, H. Y. & Scheidt, K. A.

Enantioselective syntheses of heteroyohimbine natural products:
a unified approach through cooperative catalysis. Angew. Chem.
Int. Ed. Engl. 54, 6900–6904 (2015).

63.  Bourgeois, L., Pyne, M. E. & Martin, V. J. J. A highly characterized
synthetic landing pad system for precise multicopy gene
integration in yeast. ACS Synth. Biol. 7, 2675–2685 (2018).
64.  Geiler-Samerotte, K. A. et al. Misfolded proteins impose a

Department of Energy (grant number DE-SC0018368 to R.T.G.), the
Agence Nationale de la Recherche (grant number ANR-20-CE43-0010
(MIACYC) to V.C.) and the Novo Nordisk Foundation Center for
Biosustainability (grant number NNF20CC0035580) and European
Union Horizon 2020 research and innovation program (grant number
814645 (MIAMi) to M.K.J.). We would like to thank T. Wulff and L.
Guillonneau for analytical support.

Author contributions
S.A.B., B.J.L., J.Z., J.D.K. and M.K.J. conceived the study. S.A.B., B.J.L.,
F.G.H., L.G.H., L.C., B.L., D.R.-S., O.G., K.K., T.D.d.B, R.T.G. and K.G.
designed and constructed plasmid and yeast strains. S.A.B., B.J.L.,
F.G.H., P.R., S.K., N.G., J.M. and K.G. ran yeast cultivations. K.B.A.,
D.R., A.K.H., Y.Q., J.M., C.M., S.B., R.J. and L.D. performed analytical
chemistry on yeast cultivation broths and assisted S.A.B., B.J.L. and
F.G.H. with MS data analysis. D.R., K.B.A., Y.N., S.E.O., A.K.H., S.A.B.,
C.M., Y.Q., L.D., S.B. and V.C. performed all analytical chemistry
experiments and assisted with MS data analysis and interpretation.
T.M.F. and A.A.P. performed bioactivity assays in mammalian cells.
D.R.-S. performed flow cytometry and assisted F.G.H. with data
analysis. S.A.B., B.J.L., F.G.H. and M.K.J. wrote the manuscript. All
authors approved the manuscript.

Competing interests
J.D.K., J.Z., L.G.H., S.A.B. and M.K.J. are inventors on pending
patent applications (patent applicant: Technical University of
Denmark; application number: PCT/EP2023/063481). L.G.H., J.Z.,
J.D.K. and M.K.J. have financial interests in Biomia. J.D.K. also has
financial interests in Amyris, Lygos, Demetrix, Napigen, Apertor
Pharmaceuticals, Maple Bio, Ansa Biotechnologies, Berkeley Yeast and
Zero Acre Farms. All other authors have no competing interests.

dosage-dependent fitness cost and trigger a cytosolic unfolded
protein response in yeast. Proc. Natl Acad. Sci. USA 108,
680–685 (2011).

Additional information
Extended data is available for this paper at
https://doi.org/10.1038/s41589-023-01430-2.

65.  Shaw, W. M. et al. Engineering a model cell for rational tuning of

GPCR signaling. Cell 177, 782–796.e27 (2019).

66.  Miettinen, K. et al. A GPCR-based yeast biosensor for biomedical,

biotechnological, and point-of-use cannabinoid determination.
Nat. Commun. 13, 3664 (2022).

67.  Jiang, L. I. et al. Use of a cAMP BRET sensor to characterize a novel
regulation of cAMP by the sphingosine 1-phosphate/G13 pathway.
J. Biol. Chem. 282, 10576–10584 (2007).

Acknowledgements
This work was supported by the Novo Nordisk Foundation
Copenhagen Bioscience PhD Programme (grant number
NNF19SA0035438 to S.A.B.), the Danish National Research
Foundation (grant number DNRF137 (CeMIST) to L.D. and Y.Q.), the US

Supplementary information The online version
contains supplementary material available at
https://doi.org/10.1038/s41589-023-01430-2.

Correspondence and requests for materials should be addressed to
Jie Zhang or Michael K. Jensen.

Peer review information Nature Chemical Biology thanks the
anonymous reviewers for their contribution to the peer review of this
work.

Reprints and permissions information is available at
www.nature.com/reprints.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 1 | De novo alstonine and serpentine production in yeast.
a. Representative chromatogram from LC-MS analysis of spent medium from
yeast (MIA-CM-3) expressing CroTHAS1+RseSGD and CroHYS+RseSGD when
cultivated in synthetic complete (SC) medium supplemented with secologanin
and tryptamine. Controls include tetrahydroalstonine and ajmalicine standards,
as well as a negative control (MIA-CM-3). b. De novo production of alstonine
produced by CroTHAS1+RteAS2 (Sc77), CroTHAS1+GseSBE_nat (Sc78), and

CroTHAS1+CroSS_nat (Sc112), and de novo production of serpentine by yeast
strain expressing CroHYS+CroSS_nat (Sc85), when cultivated in 3 x SC medium
supplemented with 3 mM tryptophan. The strains are based on MIA-CM-3, with
a genome integrated copy of RseSGD. c, d. Carbon feedstock (c) and alstonine
(d) levels during the 20 h glucose batch followed by a pulsed-ethanol fed-batch
process of de novo alstonine-producing strain ScH144 in 2 ltr bioreactor. For b,
n = 3 and error bars represent one standard deviation from the mean.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 2 | Alstonine titers in yeast strains expressing individual
alstonine synthase variants when cultivated in deep-well plates. Titers of
alstonine (µg/L) after 144 h cultivations of 6 biological replicates of strains
Sc138-153 with 1 mM tryptamine and 0.2 mM secologanin in SC media, + 1 mM
Trp. Gene candidates are linked to strain identifiers as follows: RteAS1 (Sc87),
RteAS2 (Sc88), RteAS3 (Sc90), RteAS4 (Sc92), RteAS5 (Sc94), CroAS_nat

(Sc96), RseSBE_nat (Sc97), GseSBE_nat (Sc98), CroAS2_nat (Sc100), CroAS2
(Sc101), CroAS (Sc102), RseSBE (Sc103), GseSBE (Sc104), CroSS_nat (Sc157) as
well as negative control strain (Sc86). The background strain for this screen
was MIA-B0, with an integrated pathway from tryptamine and secologanin to
THA, allowing for feeding of these close precursors. Mean, n = 6, with error bars
indicating SD.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 3 | Alstonine production of strain Sc112 in 2 ltr bioreactor. Titers of alstonine (mg/L) during 144 h cultivation in 2 ltr bioreactor with 60 g/ltr
glucose feeding. Single measurements.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 4 | Chromatograms from alstonine purification.
a. Chromatogram of alstonine purification on DAC LC50 system. Alstonine
compound is eluted with a retention time of about 40 min after using washing
solvent. b. Chromatogram of alstonine purification on a semi-preparative

system. Alstonine compound is eluted with a retention time of 332 min after
using washing solvent. c. Chromatogram of purified alstonine at 250 nm.
d. Maxplot chromatogram of purified alstonine.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 5 | NMR spectra for alstonine produced in yeast. a. 1H NMR
with water suppression full range in MeOH-d3 alstonine standard (red), and
SPE purified alstonine from alstonine-producing yeast (blue). b. 1H NMR with
water suppression aromatic range in MeOH-d3 alstonine standard (red), and SPE

purified alstonine from enzymatic experiment. c. 1H NMR with water suppression
aliphatic range in MeOH-d3 alstonine standard (red), and SPE purified alstonine
from enzymatic experiment. Gray bars indicate impurities.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 6 | Comparison of alstonine and serpentine standards
and producers. a–c, LCMS analysis of Profile of MS/MS transitions for alstonine
standard (a), broth of alstonine producer Sc77 (b) and serpentine standard
(c). Transitions characteristic for alstonine and serpentine: 262.9 (gray), 316.9

(blue), and 234.9 (green). d–g, HRMS analysis of alstonine standard (d), broth
of alstonine producer Sc112 (e), serpentine standard (f), and broth of serpentine
producer Sc85 (g).

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2A

y
t
i
s
n
e
t
n
I

Tryptophan Standard
Fluorotryptophan, CM10
Chlorotryptophan, CM10
Bromotryptophan, CM10
Difluorotryptophan, CM10

0

1

2

3

4
Time (min)

5

6

7

y
t
i
s
n
e
t
n
I

Tryptamine Standard
Fluorotryptamine, CM10
Chlorotryptamine, CM10
Bromotryptamine, CM10
Difluorotryptamine, CM10

0

1

2

3
Time (min)

4

5

6

7

y
t
i
s
n
e
t
n
I

Strictosidine Standard
Fluorostrictosidine, CM10
Chlorostrictosidine, CM10
Bromostrictosidine, CM10
Difluorostrictosidine, CM10

0

1

2

4

3
Time (min)

5

6

7

B

Tyrptophan Standard

Tryptamine Standard

118.0651

146.0600

91.0542

188.0707

Fluorotryptophan

136.0556

164.0505

206.0612

109.0447

Chlorotryptophan
180.0210

117.0574

152.0260

222.0316

144.0804

Fluorotryptamine

162.0714

115.0541

Stricotisinde Standard

144.0806

514.2065

531.2332

352.1541

Chlorotryptamine

Fluorostrictosidine

532.1971

549.2237

143.0729

178.0419

162.0712

370.1451

Bromotryptophan

117.0571

223.9706

265.9812

Bromotryptamine
143.0728

Chlorostrictosidine

221.9914

178.0417

386.1154

548.1685

565.1938

Difluorotryptophan

Difluorotryptamine

154.0462

127.0354

182.0412

224.0520

180.0620

133.0448

Difluorostrictosidine
388.1353

550.1887

567.2155

180.0617

60 100 140 180 220 260
m/z

60 100 140 180 220
m/z

100 200 300 400 500
m/z

C

D

SceTRP5

CroTDC

CroSTR

SceTRP5

RgnTDC

CroSTR

CM3, 100 mg/L fluoroindole

CM10, 100 mg/L fluoroindole

CM3, 100 mg/L chloroindole

CM10, 100 mg/L chloroindole

CM3, 100 mg/L bromoindole

CM10, 100 mg/L bromoindole

CM3, 100 mg/L difluoroindole

CM3, 100 mg/L difluoroindole

Indole Tryptophan

Tryptamine

Strictosidine

Indole Tryptophan

Tryptamine

Strictosidine

Extended Data Fig. 7 | See next page for caption.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 7 | Biosynthesis of halo-strictosidine by MIA-CM3 and
MIA-CM10. MIA-CM3 and MIA-CM10 were cultivated (see Methods) with
100 mg/L haloindole and 0.25 mM secologanin and the broth at 144 hours
analyzed using HRMS. a. Representative chromatograms for MIA standards
and fluorinated, chlorinated, brominated and difluorinated derivatives after
feeding the corresponding haloindole. b. Representative MS-MS spectra

extracted from the corresponding peaks in panel a. c,d, Indole to strictosidine
pathways expressed in MIA-CM3 (c) and MIA-CM10 (d) with the detection of
halogenated derivatives overlaid. The presence of a colored or gray box indicates
identification of the derivative with a halo-substitution(s) at the indicated carbon
(indole numbering). Enzyme abbreviation: TRP5 - tryptophan synthase 5,
TDC - tryptophan synthase, STR - strictosidine synthase.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 8 | Isotopic profiles of chlorinated and brominated alstonine and serpentine. (Top and Middle panels) Measured isotopic profiles of
chlorinated (left) and brominated (right) serpentine and alstonine. (Bottom panels) Predicted isotopic profiles of chlorinated (left) and brominated (right) serpentine
and alstonine.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 9 | Mean peak areas of halogenated MIA intermediates
in Sc161 broth. Sc161 was cultivated in triplicate for 144 h with 100 mg/L
halo-indole and 0.25 mM secologanin and the broth analyzed with HRMS. Mean

peak areas are plotted with standard deviation and data points overlaid as black
dots. Legends indicate the position of halo-substitution(s) according to indole
carbon numbering.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2Extended Data Fig. 10 | See next page for caption.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2349.1554263.0819235.0869317.1292207.0919335.1194225.0823367.1454281.0722253.0773367.1456281.0723253.0773335.1195225.0823367.1456281.0723253.0773335.1195225.0823367.1459281.0726253.0776335.1198225.0826383.1158297.0427269.0476351.0896241.0526427.0653340.9920312.9970395.0390285.0013385.1353299.0623271.0673353.1093243.0723385.1364299.0630271.0679353.1102243.0729385.1362299.0628271.0677353.1099242.0648243.0724385.1357299.0622271.0678353.1098385.1360299.0627271.0676353.1099243.07277-chloroserpentine, m/z 383.117-bromoserpentine, m/z 427.064,5-difluoroserpentine, m/z 385.134,6-difluoroserpentine, m/z 385.134,7-difluoroserpentine, m/z 385.135,7-difluoroserpentine, m/z 385.136,7-difluoroserpentine, m/z 385.13Serpentine Standard, m/z 3494-fluoroserpentine, m/z 368.145-fluoroserpentine, m/z 368.146-fluoroserpentine, m/z 368.147-fluoroserpentine, m/z 368.14Serpentine Standard, m/z 3494-fluoroserpentine, m/z 368.145-fluoroserpentine, m/z 368.146-fluoroserpentine, m/z 368.147-fluoroserpentine, m/z 368.147-chloroserpentine, m/z 383.117-bromoserpentine, m/z 427.064,5-difluoroserpentine, m/z 385.134,6-difluoroserpentine, m/z 385.134,7-difluoroserpentine, m/z 385.135,6-difluoroserpentine, m/z 385.135,7-difluoroserpentine, m/z 385.136,7-difluoroserpentine, m/z 385.135678Time (min)IntensityABCDabcdNOOONHHR4R3R2R14-Fluoroserpentine, R1=F,  R2=R3=R4=H5-Fluoroserpentine, R2=F,  R1=R3=R4=H6-Fluoroserpentine, R3=F,  R1=R2=R4=H7-Fluoroserpentine, R4=F,  R1=R2=R3=H7-Chloroserpentine, R4=Cl,  R1=R2=R3=H7-Bromoserpentine, R4=br,  R1=R2=R3=H4,5-Fluoroserpentine, R1=R2=F,  R3=R4=H4,6-Fluoroserpentine, R1=R3=F,  R2=R4=H4,7-Fluoroserpentine, R1=R4=F,  R2=R3=H5,7-Fluoroserpentine, R2=R4=F,  R1=R3=H6,7-Fluoroserpentine, R3=R4=F,  R1=R2=HIndoleTryptophanTryptamineStrictosidineStrictosidineAglyconeAjmalicineSerpentineSceTRP5RgnTDCCroSTRRseSGDCroHYSCroSSExtended Data Fig. 10 | Biosynthesis of halo-serpentines by ScH125. ScH125
was cultivated with 100 mg/L halo-indole and 0.25 mM secologanin. Broth
samples were taken at 144 hours and analyzed using HRMS. a. Representative
chromatograms for serpentine standard and halo-serpentines after feeding the
equivalent halo-indole. b. Representative MS-MS spectra extracted from the
peaks in panel a. c. Serpentine and halo-serpentine peak assignment for MS/MS
spectra in panel b. d. Indole to serpentine pathway expressed in ScH125 with the

detection of halogenated derivatives overlaid. The presence of a colored or gray
box indicates identification of the derivative with a halo-substitution(s) at the
indicated carbon (indole numbering). Enzyme abbreviation: TRP5 - tryptophan
synthase 5, TDC - tryptophan synthase, STR - strictosidine synthase,
SGD - strictosidine deglycosylase, HYS - heteroyohimbine synthase,
SS - serpentine synthase.

Nature Chemical Biology

Articlehttps://doi.org/10.1038/s41589-023-01430-2