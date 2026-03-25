Metabolic Engineering 91 (2025) 119–129

Contents lists available at ScienceDirect

Metabolic Engineering

journal homepage: www.elsevier.com/locate/meteng

Psilocybin biosynthesis enhancement through gene source optimization

Madeleine R. Keller a,1, Madeline G. McKinney a,1, Abhishek K. Sen a, Felicia G. Guagliardo a,
Elle B. Hellwarth a, Khondokar Nowshin Islam b,c, Nicholas A. Kaplan a, William J. Gibbons Jr. a,
Grace E. Kemmerly a, Chance Meers d,e, Xin Wang b,c, J. Andrew Jones a,*
a Miami University, Department of Chemical, Paper, and Biomedical Engineering, Oxford, OH, USA
b Miami University, Department of Microbiology, Oxford, OH, USA
c University of Florida, Department of Microbiology and Cell Science, Institute of Food and Agricultural Sciences, Gainesville, FL, USA
d Department of Biochemistry and Molecular Biophysics, Columbia University, New York, NY, USA
e Howard Hughes Medical Institute, Columbia University, New York, NY, USA

A R T I C L E  I N F O

A B S T R A C T

Keywords:
Gene source optimization
Psilocybin
Promoter library
Baeocystin
Psilocybe cubensis
Gymnopilus dilepis
Norbaeocystin methyltransferase
PsiM

Psilocybin,  the  prodrug  to  the  psychoactive  compound  in  ‘magic’  mushrooms,  is  currently  being  studied  in
clinical trials as a treatment for severe mental health conditions, such as depression and anxiety. Previous reports
of psilocybin biosynthesis as reconstituted in E. coli reported maximum titers of 1.16 g/L, exclusively using genes
from the most common recreationally used mushroom, Psilocybe cubensis. This study explores the effect of gene
species  variation  on  psilocybin  and  baeocystin  production  using  various  exogenous  genes  sourced  from
psilocybin-producing mushrooms Psilocybe cubensis, Psilocybe cyanescens, Panaeolus cyanescens, and Gymnopilus
dilepis. The psiD and psiK genes sourced from P. cubensis demonstrated unequivocally superior performance, while
psiM showed varied production levels of psilocybin and the pathway intermediate baeocystin with changes in
gene source. Strains containing a psiM gene sourced from Psilocybe cyanescens demonstrated a higher degree of
baeocystin selectivity as compared to other psiM genes, demonstrating a key difference between species. Most
notably, the strain Gymdi30, containing psiM sourced from G. dilepis, achieved a psilocybin titer of 1.46 ± 0.13 g/
L,  the  highest  reported  to  date.  Comparative  proteomic  analysis  of  Gymdi30  during  periods  of  high  and  low
productivity was also performed to investigate bottlenecks in cellular metabolism, which could be limiting strain
performance. This work represents a significant improvement in psilocybin biosynthesis, a key step towards the
development of a biosynthetic manufacturing route for psilocybin.

1. Introduction

Approximately 1 out of 5 U.S. adults are currently living with some
type of mental illness (NIH: Key substance use and, 2023), and current
standards of care come with a plethora of side effects, including weight
gain, headaches, and anxiety (Hirsch and Birnbaum, 2018). Psilocybin,
the active ingredient in ‘magic’ mushrooms, is under clinical evaluation
for the treatment of severe depression (Ross et al., 2016), post-traumatic
stress  disorder  (PTSD)  (Gluff  et  al.,  2017),  and  anxiety  (Grob  et  al.,
2011), among other indications (Matsushima et al., 2009; Garcia-Romeu
et al., 2015). Currently, the United States Food and Drug Administration
has granted three psilocybin-based clinical trials Breakthrough Therapy

status, suggesting that early evidence for psilocybin-based therapy may
demonstrate substantial improvement over existing therapies.

Until recently, psilocybin production methods only included tradi-
tional chemical synthesis and whole organism farming, which although
successful, do have specific limitations related to cost, scalability, and/
or  reproducibility  (Kooijman  et  al.,  2023;  Hofmann  et  al.,  1958).  To
date, the chemical synthetic drug substance dominates clinical use ap-
plications,  while  whole  mushroom-based  products  are  the  most
commonly used recreational form (Vunduk et al., 2002). In 2017, the
biosynthetic pathway for psilocybin, as present in Psilocybe mushrooms,
was reported by the Hoffmeister group (Fricke et al., 2017). A year later,
this pathway was expressed in Aspergillus nidulans, enabling production

* Corresponding author. Miami University 64 Engineering Building 650 E. High St. Oxford, OH, 45056, USA.

E-mail  addresses:  keller65@miamioh.edu (M.R.  Keller),  mckinnm5@miamioh.edu (M.G.  McKinney),  sena2@miamioh.edu (A.K.  Sen),  guaglifg@miamioh.edu
(F.G.  Guagliardo),  ebhellwarth@crimson.ua.edu (E.B.  Hellwarth),  islamk@ufl.edu (K.N.  Islam),  kaplanna@uw.edu (N.A.  Kaplan),  gibbonwj@miamioh.edu
(W.J. Gibbons), kemmerge@miamioh.edu (G.E. Kemmerly), chancemeers@gmail.com (C. Meers), wangx3@ufl.edu (X. Wang), jones@miamioh.edu (J.A. Jones).

1 These authors contributed equally to this work.

https://doi.org/10.1016/j.ymben.2025.04.003
Received 14 January 2025; Received in revised form 13 April 2025; Accepted 14 April 2025
Available online 16 April 2025
1096-7176/© 2025 The Authors.  Published by Elsevier Inc.  on behalf of International Metabolic Engineering Society.  This is an open access article under the CC
BY-NC-ND license ( http://creativecommons.org/licenses/by-nc-nd/4.0/ ).

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

of  approximately  100  mg/L  of  psilocybin  through  a  pathway  that
included  the  P450  monooxygenase  (PsiH)  (Hoefgen  et  al.,  2018).  In
2020, this pathway was transferred to Saccharomyces cerevisiae to show
high-titer production of both psilocybin (627 mg/L) and its less stable
degradation product, psilocin (580 mg/L); however, the mechanism of
degradation was not fully explored (Milne et al., 2020). Due to the low
activity  of  P450  monooxygenases  in  prokaryotes,  the  PsiH-catalyzed
biosynthetic step was circumvented when the pathway was expressed
in Escherichia coli by feeding a hydroxylated substrate, 4-hydroxyindole
(Fig.  1)  (Adams  et  al.,  2019).  Biosynthetic  production  of  psilocybin
achieved  in  E.  coli  using  this  approach  resulted  in  the  first  report  of
gram-scale titers at 1.16 g/L, which represents the highest titer reported
to date from any recombinant organism.

The  production  pathway  as  reconstituted  in  E.  coli  (Fig.  1)  begins
with  a  substrate  feed  of  4-hydroxyindole,  which  is  condensed  with
serine into L-4-hydroxytryptophan through the promiscuous action of
the native E. coli tryptophan synthase beta subunit, TrpB. A decarbox-
ylase (psiD) catalyzes the formation of 4-hydroxytryptamine releasing
carbon dioxide, then a kinase (psiK) catalyzes the phosphorylation of the
4-hydroxyl group to produce norbaeocystin, and finally the N-methyl-
transferase  (psiM)  iteratively  methylates  the  terminal  amine  to  first
produce  baeocystin,  followed  by  psilocybin,  and  ultimately  aerugi-
nascin,  the  latter  of  which  is  questioned  in  the  recent  literature
(Hudspeth  et  al.,  2024).  Each  species  of  psilocybin-containing  mush-
rooms accumulates these latter N-methylated molecules in distinct ratios
(Gotvaldov´a et al., 2022), suggesting that slight genomic variations in
the structure, function, or expression of psiD, psiK, and particularly psiM
may  play  a  crucial  role  in  differentiating  metabolite  accumulation  in
nature. Evolutionary differences between these distantly linked mush-
rooms  may  be  essential  to  the  selective  over-production  of  the
lesser-studied metabolites (e.g., norbaeocystin, baeocystin, and aerugi-
nascin) (Reynolds et al., 2018).

The work presented below uses exogenous pathway genes encoding
psiD, psiK, and psiM from Psilocybe cubensis (Psicu), Psilocybe cyanescens
(Psicy), Panaeolus cyanescens (Pancy), and Gymnopilus dilepis (Gymdi) to
explore  their  impact  on  the  function  of  the  psilocybin  biosynthesis
pathway in E. coli. Recently, Psilocybe cyanescens has been proposed to
be synonymous with Psilocybe subaeruginosa (McTaggart et al., 2023);
however, we will use Psilocybe cyanescens herein for consistency. Here,

we describe the development of multiple pathway variants capable of
high-titer  psilocybin  production  and  those  capable  of  norbaeocystin-
and baeocystin-specific production. The most commonly used psiD and
psiK variants from P. cubensis were determined to be the best respective
psiD  and  psiK  variants,  while  psiM  variants  showed  more  diversity,
warranting  further  study.  The  best  psilocybin  production  strain,
Gymdi30, harboring the psiM from G. dilepis, demonstrated production
of 1.46 ± 0.13 g/L psilocybin in a glucose-fed batch bioreactor, repre-
senting  the  highest  psilocybin  titer  reported  to  date.  Furthermore,
strains containing psiM from Psilocybe cyanescens were shown to accu-
mulate higher titers of the intermediate baeocystin, indicating a lower
functional activity towards baeocystin as substrate in comparison to the
other enzyme variants in our E. coli model system. This work will form a
basis for continuing studies to enhance the production of these natural
tryptamines, enabling subsequent development as clinical therapeutics.

2. Materials & methods

2.1. Bacterial strains, vectors, media, and substrates

Escherichia coli DH5α was used to propagate all plasmids, while the
host for chemical production experiments was E. coli BL21star™ (DE3)
(Table  S1).  Plasmid  transformations  were  completed  using  standard
chemical competency protocols. For studies with a small fermentation
volume (2 mL scale), Andrew’s Magic Media (AMM) (He et al., 2015),
without MOPS (Adams et al., 2022), was supplemented with 1 g/L serine
and  1  g/L  methionine.  Larger  scale  experiments  were  supplemented
with  5 g/L  serine  and  5 g/L  methionine,  when appropriate.  The sup-
plemented AMM was used for both preculture growth and production
media.  Luria  Broth  (LB)  was  used  for  plasmid  propagation  during
cloning. The antibiotic ampicillin (80 μg/mL) was added to the culture
media for plasmid selection. The substrate, 4-hydroxyindole, was pur-
chased from A2B Chem, LLC (San Diego, CA) and stored as a 40 mg/mL
stock in absolute ethanol at (cid:0) 20
C until use. Where appropriate, psi-
locin was generated in situ using commercial alkaline phosphatase and
psilocybin  purified  in  house,  as  previously  reported  (Rakoczy  et  al.,
2024).

◦

Fig.  1. Psilocybin  biosynthesis  pathway  via  fed  substrate,  4-hydroxyindole.  TrpB,  E.  coli  tryptophan  synthase;  PsiD,  decarboxylase;  PsiK,  kinase;  PsiM,  SAM-
dependent  norbaeocystin  N-methyltransferase;  AP,  alkaline  phosphatase;  MetK,  methionine  adenosyltransferase;  MET,  methionine.  Endogenous  E.  coli  enzymes
are listed in orange, while recombinant enzymes are listed in blue. (For interpretation of the references to colour in this figure legend, the reader is referred to the
Web version of this article.)

120

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

2.2. Gene sourcing and initial cloning

Nucleotide sequences of decarboxylases, kinases, and norbaeocystin
methyltransferases  from  Psilocybe  cubensis,  Psilocybe  cyanescens,  Pan-
aeolus cyanescens, and Gymnopilus dilepis were sourced from UniprotKB
and are provided in the supplementary materials (Table S4). To generate
phylogenetic  trees,  amino  acid  sequences  were  aligned  using  MAFFT
(version v7.525, released on March 13, 2024) with the L-INS-i algorithm
and  parameters  –localpair  –maxiterate  1000.  Phylogenetic  trees  were
constructed from these alignments using IQ-TREE (version 2.3.6), with
optimal  evolutionary  models  selected  using  the  built-in  ModelFinder
(MFP) and branch support assessed by ultrafast bootstrap approximation
with 1000 replicates (Katoh and Standley, 2013; Minh et al., 2020).

Plasmids  containing  the  gene  sequences  encoding  psiD,  psiK,  and
psiM from Psilocybe cubensis with the T7 epitope tag were used from a
previous  study  (Table  S1:  13,  17,  21),  and  the  gene  sequences  from
Psilocybe  cyanescens,  Panaeolus  cyanescens,  and  Gymnopilus  dilepis
without the T7 epitope tag were ordered as linear double-stranded DNA
from  Genewiz  (now  Azenta).  The  template  sequences  were  PCR-
amplified  using  complementary  primers  (Table  S3:  1–17),  digested
with NdeI and XhoI, gel-extracted, and ligated into the pETM6-SDM2x
plasmid  backbone,  also  digested  with  NdeI  and  XhoI.  These  products
were  transformed  into  DH5α  and  plated  on  ampicillin-containing  LB
agar plates. Single colonies were confirmed by restriction ligation and
verified  via  Sanger  sequencing  using  primers  (Table  S3:  33–40),
resulting in plasmids 10–12, 14–16, and 18–20, (Table S1).

2.3. N-term epitope tag

To evaluate if the presence of a T7 N-term epitope tag (Table S4: 13)
had an effect on functional activity, PCR primers were designed to add
the 42-base pair T7 tag to the Psilocybe cyanescens, Panaeolus cyanescens,
and Gymnopilus dilepis genes, and remove the T7 tag from the Psilocybe
cubensis  genes.  The  gene  sequences  were  PCR-amplified  using  these
primers  (Table  S3:  9–32),  digested  with  NdeI  and  XhoI,  and  gel-
extracted. The genes were then ligated into a pETM6-SDM2x plasmid
backbone, similarly digested with NdeI and XhoI, resulting in plasmids
(Table S1: 34–45). These plasmids were transformed into DH5α, then
plated  on  LB  agar  plates  containing  ampicillin.  Constructs  were
confirmed by Sanger sequencing using primers (Table S3: 34–45).

2.4. Library construction

Plasmids  were  constructed  to  verify  the  ability  of  each  gene  to
convert substrate to product. A pETM6-H10-mCherry plasmid (Table S1:
5)  was  digested  with  NdeI  and  XhoI,  and  individually  ligated  with
similarly  digested  pETM6-SDM2x-T7  Tag  Gymdi,  Pancy,  Psicy,  and
Psicu psiDs (Table S1: 13, 34–36), to produce pETM6-H10-PsiD of each
gene species (Table S1: 22–25). To verify the activity of PsiK variants,
the plasmid pETM6-H10-PsicuPsiD (Table S1: 25) containing the pre-
viously verified Psilocybe cubensis psiD was digested with BcuI and ApaI
and individually ligated with pETM6-SDM2x Gymdi, Pancy, Psicy, and
Psicu psiKs (Table S1: 17, 38–40) digested with XbaI and ApaI, to pro-
duce  pETM6-H10-PsicuPsiD-PsiK  for  each  gene  variant  of  PsiK
(Table S1: 26–29). Similarly, to verify the activity of PsiM variants, the
plasmid  pETM6-H10-PsicuPsiD-PsicuPsiK  (Table  S1:  29)  containing
Psilocybe  cubensis  psiD and  psiK was  digested  with BcuI  and  PacI  and
individually ligated with pETM6-SDM2x Gymdi, Pancy, Psicy, and Psicu
psiMs  (Table  S1:  21,  42–44) digested  with  XbaI  and  PacI,  to  produce
pETM6-H10-PsicuPsiD-PsicuPsiK-PsiM  for  each  gene  variant  of  PsiM
(Table S1: 30–33).

For simultaneous psiD, psiK, and psiM analysis, plasmids were built
on pETM6-C4-mCherry and pETM6-H10-mCherry backbones (Table S1:
3, 5), as these T7 mutant promoters had been previously shown to be
optimal  for  norbaeocystin  and  psilocybin  production,  respectively
(Adams et al., 2019, 2022). Libraries were constructed in basic operon

121

to  produce

format  similarly  to  the  individual  plasmid  constructs  above,  using  a
modified ePathOptimize-based approach (Jones et al., 2015). Four gene
variants were used for each of the three pathway genes, resulting in a
combinatorial library of 64 (43) possible combinations for each of the
two  promoters  (H10  and  C4)  evaluated.  Briefly,  the  Gymdi,  Pancy,
Psicy,  and  Psicu  psiD  plasmids  (Table  S1:  10–12,  37)  were  pooled  in
equimolar quantities, digested with NdeI and XhoI, gel-extracted, and
ligated with similarly digested and gel-extracted pETM6-C4-mCherry or
the  pETM6-C4-xx4PsiD  and
pETM6-H10-mCherry
pETM6-H10-xx4PsiD libraries (Table S2: 1–2, Fig. 2A-Left). These two
libraries  were  then  independently  digested  with  BcuI  and  ApaI,
gel-extracted,  and  ligated  with  Gymdi,  Pancy,  Psicy,  and  Psicu  psiKs
(Table S1: 14–16, 41) pooled in equimolar quantities, digested with XbaI
and ApaI, and gel-extracted to produce pETM6-C4-xx4PsiD-xx4PsiK and
pETM6-H10-xx4PsiD-xx4PsiK libraries (Table S2: 3–4, Fig. 2A-Center).
These  PsiD-PsiK  libraries  were  then  digested  with  BcuI  and  PacI
gel-extracted,  and  ligated  with  Gymdi,  Pancy,  Psicy,  and  Psicu  psiMs
(Table S1: 18–20, 45) pooled in equimolar quantities, digested with XbaI
and  PacI,  and  gel-extracted  to  produce  pETM6-C4-xx4PsiD-xx4-
PsiK-xx4PsiM  and  pETM6-H10-xx4PsiD-xx4PsiK-xx4PsiM
libraries
(Table S2: 5–6, Fig. 2A-Right). This process was repeated using genes
containing the T7 Tag (Table S1: 13, 17, 21, 34–36, 38–40, 42–44), to
create  two  additional  final  libraries:  pETM6-C4-T7Tag-xx4PsiD-xx4-
PsiK-xx4PsiM
pETM6-H10-T7Tag-xx4PsiD-xx4PsiK-xx4PsiM
(Table S2: 7–8).

and

For  individual  psiM  analysis,  mCherry-expressing  plasmids,  each
containing a different promoter sequence (T7, H9, H10, C4, G6, pXylA,
pGAP; Table S1: 3–9) (Jones et al., 2015; Xu et al., 2014; Englaender
et al., 2017), were pooled in equimolar quantities, digested with XbaI
and  ApaI,  gel-extracted,  and  ligated  with  the  similarly  digested  pNor
plasmid  (Table  S1:  46)  to  create  a  pETM6-xx7-PsiDK  plasmid  library
(Table S2: 9). The xx7-PsiDK plasmid library was then digested with BcuI
and  ApaI  and  ligated  with  the  respective  psiM  plasmids  (Table  S1:
18–20, 45) cut with XmaJI and ApaI. This library construction process
was performed individually for the Gymdi, Pancy, Psicy, and Psicu psiM
genes, creating four separate basic operon configuration libraries con-
taining the full biosynthetic pathway with PsiD and PsiK from P. cubensis
and  PsiM  from  one  of  the  four  variants  under  investigation  (Fig.  2,
Table S2: 10–13).

In each case above, the ligated plasmids or plasmid libraries (both
gene  and  promoter  type)  were  transformed  into  DH5α,  plated  on
◦
ampicillin-containing LB agar plates, and grown overnight at 37
C. The
resulting colonies were scraped from the agar plate with a clean razor
blade to pool all variants, and DNA was extracted from the resulting cell
pellet in alignment with previously published methods (Xu et al., 2012).
The purified plasmid library was validated by restriction digestion and
transformed into BL21star™ (DE3) for preliminary screening.

2.5. Fermentation conditions

Library screening was performed in 2 mL cultures in 48-well plates at
◦
37
C. AMM (no MOPS) supplemented with methionine (1 g/L), serine
(1  g/L),  4-hydroxyindole  (350  mg/L),  and  ampicillin  (80  μg/mL).
Overnight cultures were grown from either an agar plate or freezer stock
culture  in  AMM  with  appropriate  supplements  (all  described  above,
◦
except 4-hydroxyindole) for 12 h in a shaking 37
C incubator. Although
some promoters under investigation are constitutive, induction occurred
for all variants 4 h after inoculation with 1 mM isopropyl-β-D-1-thio-
galactopyranoside (IPTG). Cultures were then sampled 48 h post inoc-
ulation and subjected to HPLC-MS analysis for quantification of target
metabolites,  as  previously  described  (Adams  et  al.,  2019).  Statistical
significance,  where  appropriate,  was  determined  using  a  two-tailed,
unpaired t-test.

Bioreactor  conditions  were  maintained  at  37

C  with  a  1.5  L
fermentation volume and AMM (no MOPS) initially supplemented with
methionine  and  serine  at  5  g/L  each  and  ampicillin  (80  μg/mL).  4-

◦

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

Fig. 2. Library Construction and Gene Phylogeny. (A) Pathway library assembly for initial gene evaluations. ’xx4’ denotes 1 of 4 possible sequences encoding the
respective genes. (B) Phylogenetic tree illustrating the relationships among PsiD, PsiK, and PsiM from four distinct organisms. Bootstrap values, shown in bold,
indicate the statistical support for each branch, while branch lengths in parentheses represent evolutionary distances measured as the number of amino acid sub-
stitutions per site between species.

hydroxyindole was initially supplemented at 150 mg/L in addition to a
variable-rate  feed  of  a  40  mg/mL  solution  throughout  fermentation.
Glucose was similarly fed to the fermentation vessel at a variable rate
from a solution of 50 % glucose. Substrate and glucose feed rates were
varied in response to HPLC concentration data as previously reported
(Adams et al., 2019, 2022). KOH (10 M) was used to maintain pH at 6.5.
Analysis of strain performance uses substrate molar yield, defined here
as  the  ratio  of  total  moles  of  psilocybin  or  baeocystin  produced  (or
psilocybin and baeocystin for total molar yield) over the total moles of
4-hydroxyindole  fed.  Where  appropriate,  baeocystin  selectivity  was
calculated  as  baeocystin  titer  divided  by  the  sum  of  baeocystin  and
psilocybin titers.

2.6. Validating recombinant psilocybin-producing strains

Following  preliminary  screening  of  libraries  in  48-well  plates,
selected transformants were isolated and evaluated for target metabolite
production in triplicate. Each strain was streaked on an LB-agar plate
from the 96-well plate freezer stock and incubated for 16 h. A range of
four to six individual colonies were picked from the agar plate and used
to inoculate a 48-well plate and were retained on a LB-agar patch plate.
After secondary screening, a representative strain most closely resem-
bling  the  original  screening  performance  was  selected  for  each  trans-
formant. Plasmid DNA was purified from each strain, digested to verify
proper assembly, and transformed into DH5α.

A single colony from the DH5α transformation was grown overnight
and  used  to  create  a  permanent  freezer  stock,  sent  for  sequencing  to
verify the gene variant and/or promoter in the selected transformant, as
well  as  transformed  back  into  BL21star™  (DE3)  to  create  the  final
production  strains.  This  production  strain  was  verified  via  a  48-well
plate fermentation experiment under standard screening conditions to
confirm expected production capabilities were retained.

2.7. Analytical methods

Metabolite analysis was performed on a Thermo Scientific Ultimate
3000 High-Performance Liquid Chromatography (HPLC) system equip-
ped with Diode Array Detector (DAD), Refractive Index Detector (RID),
and Thermo Scientific ISQ™  EC single quadrupole mass spectrometer
(MS). Samples were prepared for HPLC and LC-MS analysis by centri-
fugation at 15,000×g for 5 min. A volume of 2 μL of the resulting su-
pernatant  was  then  directly  injected  for  HPLC  and  LC-MS  analysis.

122

Norbaeocystin,  baeocystin,  psilocybin,  and  aeruginascin  were  quanti-
fied using respective standard curves generated from standards created
in house (Adams et al., 2022; Rakoczy et al., 2024).

Quantification of aromatic metabolites was performed using absor-
bance at 280 nm from the DAD and the metabolites were separated using
an Agilent Zorbax Eclipse XDB-C18 analytical column (3.0 mm × 250
mm, 5 μm) with mobile phases of water (A) and acetonitrile (B) both
containing 0.1 % formic acid at a total flow rate of 1 mL/min: 0 min, 5 %
B; 0.43 min, 5 % B; 5.15 min, 19 % B; 6.44 min, 100 % B; 7.73 min, 100
% B; 7.73 min, 5 % B; 9.87 min, 5 % B. This method resulted in the
following observed retention times (from DAD) as verified by analytical
standards when available (indicated as commercially available (ca) or
in-house  synthesized  (ihs))  and  MS  analysis  (as  described  below):  4-
hydroxyindole  (ca,  BioSynth  International  (FH24367);  6.7  min),  4-
hydroxytryptophan  (3.7  min),  4-hydroxytryptamine  (3.6  min),  nor-
baeocystin  (ihs;  1.6  min),  baeocystin  (ihs;  2.0  min),  psilocybin  (ca,
Cerilliant  Corporation  (P-097-1ML);  2.3  min),  and  aeruginascin  (ihs;
1.9 min). All methods for production and verification of in-house syn-
thesized standards have been previously reported (Adams et al., 2022;
Rakoczy et al., 2024). As previously reported, 4-hydroxytryptophan and
4-hydroxytryptamine were quantified based on the standard curves for
5-hydroxytryptophan  and  5-hydroxytryptamine  (serotonin)  due  to
limited commercial availability (Adams et al., 2019).

Quantification of sugars and organic acids in fermentation broth was
performed using a Bio-Rad Aminex HPX-87H column coupled with a RI
detector. The mobile phase was 5 mM H2SO4 in water at a flow rate of
0.600 mL/min. Retention times were verified by authentic standards.

Liquid  Chromatography  Mass  Spectrometry  (LC-MS)  data  was
collected where the full MS scan was used to provide an extracted ion
chromatogram  (EIC)  of  our  compounds  of  interest.  Analytes  were
measured in positive ion mode at the flow rate, solvent gradient, and
column conditions described above. The instrument was equipped with
a  heated  electrospray  ionization  (HESI)  source  and  supplied  ≥99  %
purity nitrogen from a Peak Scientific Genius XE 35 laboratory nitrogen
generator. The source and detector conditions were as follows: sheath
gas pressure of 80.0 psig, auxiliary gas pressure of 9.7 psig, sweep gas
pressure  of  0.5  psig,  foreline  vacuum  pump  pressure  of  1.51  Torr,
vaporizer  temperature  of  550
C,  ion  transfer  tube  temperature  of
◦
C, source voltage of 3050 V, and source current of 20.98 μA. Error
300
bars represent ± 1 standard deviation from the mean of biological du-
plicates, unless otherwise noted.

◦

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

2.8. Shotgun proteomics

Comparative  proteomics was  conducted  to compare  the  metabolic
changes  between  the  high  and  low  psilocybin-productivity  phases.
Approximately 10 OD600⋅mL of cells (i.e., 1 mL of OD600 = 10, 0.33 mL of
OD600  = 30, etc.) were collected at 36 h (high productivity) and 61 h
(low productivity) by centrifugation at 15,000×g for 5 min. The prote-
omics  sample  preparation  and  mass  spectrometry  analysis  were  con-
ducted following the same protocol used in our previous study (Shinde
et  al., 2020). A total of 10 μg of trypsin-digested peptides from eight
fractions per sample were loaded onto a capillary C18 column using a
Thermo  nanoLC-1000  liquid  chromatography  system,  coupled  to  a
Thermo LTQ Orbitrap XL mass spectrometer for MS/MS data acquisi-
tion. Three protein sequences in the psilocybin production pathway, i.e.,
N-methyltransferase  (PsiM),  L-tryptophan  decarboxylase  (PsiD),  and
4-hydroxyltryptamine kinase (PsiK), were added to the E. coli BL21-DE3
proteome (UP000002032) to serve as the protein search database. The
MS/MS  raw  data  was  searched  using  PatternLab  V  (Carvalho  et  al.,
2016).  Differentially  expressed  proteins  were  compared  based  on  the
normalized  spectral  abundance  factor (NSAF)  (Zybailov  et  al.,  2006).
The mass spectrometry proteomics data have been deposited to both the
MassIVE  repository  (dataset  identifier:  MSV000096751)  and  the  Pro-
teomeXchange  Consortium  (dataset  identifier:  PXD059355)  (Vizcaíno
et al., 2016).

3. Results and discussion

3.1. Confirmation of PsiD, PsiK, and PsiM activity

Initial  testing  was  performed  to  confirm  activity  of  Psilocybe  cya-
nescens, Panaeolus cyanescens, and Gymnopilus dilepis PsiDs, PsiKs, and
PsiMs using a 48-well plate assay (Fig. 3). Psilocybe cubensis PsiD, PsiK,
and PsiM were included as positive controls, as their activities in E. coli
have  been  confirmed  in  previous  publications  (Adams  et  al.,  2019;
Adams et al., 2022; Flower JE; Gibbons et al., 2021). Additionally, due
to  limited  commercial  availability  of  select  intermediates  and/or
membrane transport limitations surrounding direct supplementation of
phosphorylated immediate precursors to the culture media (Fig. S1B),
PsiK  and  PsiM  variants  were  tested  in  combination  with  previously
verified  genes  from  P.  cubensis.  For  example,  to  test  the  Gymdi  PsiM
variant, it was co-expressed with Psicu PsiD and Psicu PsiK to ensure the

in vivo production of the necessary precursor compounds. The purpose of
this screen was to confirm individual enzyme activity prior to combi-
natorial  transcriptional  pathway  balancing  and  screening  described
below. These constructs were expressed in basic operon form under the
control  of  the  H10  mutant  T7  promoter  without  further  genetic  opti-
mization. Consequently, these initial  activity validations are intended
solely  as  a  basic  confirmation  of  function  and  should  not  be  used  to
compare functional activity between different gene sources.

In each of the nine cases under study, the product of interest was
detected indicating all gene variants showed some degree of functional
activity. However, it is important to note that PsiD sourced from Psilo-
cybe  cyanescens  exhibited  exceptionally  low  activity  (Fig.  3A  inset),
which  could  not  be  markedly  improved  through  modest  genetic  or
fermentation optimization (data not shown).

3.2. Evaluation of combinatorial Gene variant libraries

Using psiDs, psiKs, and psiMs from Psilocybe cubensis, Psilocybe cya-
nescens, Panaeolus cyanescens, and Gymnopilus dilepis, four total libraries
were cloned, each having a theoretical library size of 64 members. Each
library  contained  1  of  4  possible  gene  variants  for  each  of  the  three
pathway genes (43 = 64), denoted by the ‘xx4’ preceding genes in library
names.  The  libraries  varied  from  each  other  by  the  choice  of  either
promoter strength (H10 mutant T7 – medium strength or C4 mutant T7 –
high strength) and whether or not the N-term T7 epitope tag was present
on the construct (Table S2: 5–8). Seeing as the pSilo16 positive control is
a previously optimized construct containing the T7 tag, it is reasonable
to expect it to perform well against other similar T7 tagged constructs.
Initial screening in medium-throughput 48-well plate assays identified
multiple high-producing strains that outperformed the pSilo16 positive
control shown in black (Fig. 4). Initial screening of random combina-
torial libraries presented in Fig. 4 was performed in singlicate at roughly
150 % of theoretical library size (92 colonies screened per library).

Top producing strains, denoted by an asterisk next to colony ID in
Fig. 4, were later rescreened in duplicate (Fig. 5A) and six select strains
were  sent  for  Sanger  sequencing  (Fig.  5B).  Five  out  of  six  sequenced
strains contained Psilocybe cubensis psiD and Psilocybe cubensis psiK, the
same gene variant as the control production strain pSilo16. This result
suggests the use of Psicu PsiD and Psicu PsiK as the best gene source
options for the production of the valuable pathway intermediate, nor-
baeocystin.  Previously  published  works  have  extensively  investigated

Fig. 3. Activity validation of PsiD, PsiK, and PsiM enzyme variants by HPLC-MS. (A) Mass Spectroscopy Extracted Ion Chromatogram (MS-EIC) for PsiD product, 4-
hydroxytryptamine (177 m/z). Inset shows low activity of Psilocybe cyanescens PsiD (green) as compared to the empty vector negative control (yellow). (B) MS-EIC for
PsiK product, norbaeocystin (257 m/z). (C) MS-EIC for PsiM product, psilocybin (285 m/z). Expected retention times for respective products are shaded in gray.
Empty vector negative control indicated by ‘((cid:0) ) Ctrl’. Vector schematics show the pathway configuration tested with Psicu indicating the gene from Psilocybe cubensis
and ‘Xx’ indicating 1 of 4 gene sources under evaluation. (For interpretation of the references to colour in this figure legend, the reader is referred to the Web version
of this article.)

123

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

Fig. 4. Preliminary screening of combinatorial gene libraries. Psilocybin production from (A) H10 (green) and C4 (pink) libraries with T7 tag present, and (B) H10
(green) and C4 (pink) libraries without T7 tag, each normalized to the control production strain pSilo16 (black, H10 promoter, Psilocybe cubensis genes, T7 tagged). In
total, 92 variants were screened per library. 74 % (275/368) of clones were found to have no measurable psilocybin production and are not shown, N = 1. Colony IDs
appended with an asterisk were selected for further evaluation. (For interpretation of the references to colour in this figure legend, the reader is referred to the Web
version of this article.)

Fig. 5. Rescreen of selected transformants and sequencing. (A) Psilocybin production compared to control production strain pSilo16 (black, H10 promoter, Psilocybe
cubensis genes, T7 tagged), N = 2. (B) Gene species information of select transformants. Note: pSilo16 construct is identical to that of transformant 360.

this solution space, resulting in the development of strain pNor (Adams
et al., 2022), which produced 1.58 ± 0.08 g/L norbaeocystin under fed
batch bioreactor conditions, and as such, further norbaeocystin strain
development was not considered in this study. However, the variability
of the PsiM gene source among these top strains suggests that exploring
the optimization of the PsiM step has the potential to improve overall
psilocybin  pathway  performance.  Thus,  specific  optimization  of  PsiM
was further investigated.

3.3. Methyltransferase variant screening and characterization

Focusing efforts on PsiM evaluation, a co-culture screening structure
was developed to independently screen PsiM without needing to opti-
mize the full biosynthetic pathway, minimizing experimental effort. The
goal  was  to  provide  norbaeocystin,  produced  by  the  previously  opti-
mized pNor strain in co-culture, which would then be taken up by the
methyltransferase-containing strain, permitting production of baeocys-
tin  and  psilocybin. This  experimental design  allowed for  the  simplest
library creation possible with the lowest metabolic burden due to only a
single gene overexpression in the strains being evaluated, the PsiM gene
from  Psilocybe  cubensis,  Psilocybe  cyanescens,  Panaeolus  cyanescens,  or
Gymnopilus dilepis. In the co-culture screen, the inoculation ratios of the
two strains were skewed towards an excess of the psiM-expressing strain

to  account  for  the  fact  that  pNor  had  previously  been  optimized  and
would  likely  outperform  the  newly  constructed,  unoptimized  psiM
variants.  This  population  bias  resulted  in  the  expected  increase  in
extracellular norbaeocystin availability with a higher pNor strain frac-
tion (Fig. S1A). However, the absence of psilocybin or baeocystin pro-
duction  (data  not  shown)  suggests  a  mass  transport  limitation  in
norbaeocystin reuptake into the cytoplasm of the recipient psiM strain,
preventing  the  methylation  step  of  the  pathway,  as  illustrated  in
Fig. S1B. This result was unexpected as norbaeocystin, baeocystin, and
psilocybin  products  are  predominantly  found  extracellularly  (Adams
et al., 2019, 2022), suggesting transport out of the cell is not impeded.
These  preliminary  results  suggested  that  a  more  intensive  screening
method would be required where a single strain would contain all three
genes in the exogenous pathway to circumvent the observed interme-
diate transport issues between co-culture members.

To accomplish this screening, 4 independent transcriptionally varied
libraries  were  cloned  in  operon  configuration,  each  with  7  possible
promoters: H9, H10, C4, G6, XylA, GAP, and the T7 consensus, using
psiD and psiK from Psilocybe cubensis and psiM from Psilocybe cubensis,
Psilocybe  cyanescens,  Panaeolus  cyanescens,  or  Gymnopilus  dilepis.  Both
XylA and GAP are constitutive promoters, while the other 5 promoters
under study are IPTG inducible. This configuration allows for a theo-
retical library size of 7 constructs for each of the 4 pathway libraries,

124

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

differentiated  by  having  a  different  PsiM  variant.  Initial  screening  of
over  5x  theoretical  library  size  in  high  throughput,  48-well  assays
yielded  select  strains  of  interest.  Data  shown  in  Fig.  6A–D  were  per-
formed in singlicate to maximize screening throughput, and top trans-
formants  were  rescreened  in  quadruplicate  later  in  the  strain
development pipeline (Fig. 6E).

After transitioning to a monoculture screening structure, pathways
containing  Psilocybe  cubensis  PsiM  (Psicu)  acted  as  a  baseline  for  this
experiment, as these libraries have been similarly constructed in a pre-
vious study (Adams et al., 2019). We selected one high psilocybin pro-
ducing  strain  (Psicu1,  338.0  ± 46.7  mg/L  psilocybin)  to  verify  the
previously discovered H10 promoter, which was  identified as the top
promoter choice in the optimized psilocybin production strain pSilo16
(Fig. 6E). We also selected a low producing strain (Psicu35) as a sec-
ondary control, which produced 116.8 ± 21.5 mg/L psilocybin as seen
in  Fig.  6E.  This  strain,  Psicu35,  was  sequenced  to  reveal  the  G6  pro-
moter, aligning with previous low producer results (Adams et al., 2022).
Pathways  containing  Gymnopilus  dilepis  psiM  (Gymdi)  presented
many  strains  of  interest,  with  the  top  3  randomly  selected  colonies
producing an average of 507 ± 8.8 mg/L of psilocybin (Fig. 6B). These
strains outperformed the previously established psilocybin production
strain, pSilo16 (Psicu1, here), under identical conditions by almost 12 %
(454  vs.  507  mg/L,  Fig.  6AB).  Although  capable  of  producing  large
amounts of psilocybin, none of the top-performing Gymdi configurations
resulted  in  specific  compositional  enhancements  in  any  of  the  other
methylated products of interest (e.g., baeocystin).

preliminary  screening,  while  strain  #10  was  the  highest  psilocybin
producer within this gene species library screen (Fig. 6C). These trans-
formants are noteworthy because they produced more baeocystin than
Gymdi  pathways  (top  strains:  114  vs.  62  g/L,  respectively)  while
simultaneously producing less psilocybin than Gymdi (370 vs. 517 mg/
L, respectively), suggesting an inefficiency in the methylation of baeo-
cystin  to  psilocybin.  Regarding  baeocystin  selectivity,  the  top-
performing  Gymdi  constructs  reached  almost  11  %  baeocystin  out  of
total methylated tryptamines, whereas Psicy10 and Psicy30 reached 20
and 26 %, respectively. This result points to the idea that the psiM gene
from Psicy may naturally exhibit greater selectivity towards baeocystin
accumulation.

Pathways  containing  Panaeolus  cyanescens  psiM  (Pancy)  produced
far lower psilocybin titers than Psicy, Gymdi, and Psicu, with the highest
concentration achieved being 195 mg/L, less than half of the other li-
braries (Fig. 6D). The Pancy library also contained some transformants
with higher baeocystin production than psilocybin (#35, #4, #20, etc.);
however, the absolute titers in this case were low in comparison to lead
baeocystin-production transformants from other libraries.

The select lead strains highlighted above from each library screen
were isolated for  further characterization in shake  flasks as shown in
Fig. 6E. Transformants Gymdi30, Gymdi3, and Pancy10 yielded 490.0
± 25.7, 449.7 ± 15.7, and 462.1 ± 16.9 mg/L psilocybin, respectively.
These transformants significantly outperformed the positive control and
highest psilocybin production strain published to date, pSilo16, which
produced 397.3 ± 25.2 mg/L psilocybin (all p ≤ 0.01).

Pathways  containing  Psilocybe  cyanescens  psiM  (Psicy)  displayed  a
strain (#30) that produced the highest baeocystin titer observed during

To  reduce  the  solution  space,  transformants  that  did  not  produce
competitive titers of psilocybin or baeocystin were not taken further in

Fig. 6. PsiM methyltransferase promoter library screening. Each library contains PsiD and PsiK from P. cubensis with the PsiM variant as listed. All genes are under
the control of one of seven promoters in basic operon configuration. Psilocybin and baeocystin production from (A) Psilocybe cubensis PsiM library, (B) Gymnopilus
dilepis PsiM library, (C) Psilocybe cyanescens PsiM library, and (D) Panaeolus cyanescens PsiM library. Strains without psilocybin or baeocystin production are not
shown. In total, 36 variants were screened per library, N = 1. (E) Rescreening of lead transformants (blue and gray) and comparison to pSilo16 positive control (black
and gray) in shake flasks. Error bars show ±1 standard deviation from the mean, N = 4. “*” indicates statistically significant improvement in psilocybin production
(p < 0.05) vs. pSilo16. (For interpretation of the references to colour in this figure legend, the reader is referred to the Web version of this article.)

125

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

the study. This included Pancy11 and Pancy4, which did not produce
notable  quantities  of  either  target  compound.  The  remaining  trans-
formants  were  analyzed  using  Sanger  sequencing  to  determine  the
identity  of  the  promoter  sequence  incorporated  into  the  pathway
construct (Fig. 6E). This screening allowed for duplicate constructs to be
eliminated as lead transformants. Psicu1 contained the same promoter
and  gene  species  as  previous  control  strain  pSilo16,  while  Gymdi3,
Gymdi30,  Psicy10,  and  Psicy30  all  contained  the  constitutive  XylA
promoter;  of  these,  Gymdi30  and  Psicy30  were  selected  for  further
study, as well as Gymdi22 and Pancy 10.

3.4. Evaluation of leading psilocybin-producing strains in bioreactors

Following confirmation of reproducibility for psilocybin production
titers  and  sequencing  validation  to  eliminate  identical  strains,  the
remaining  lead  strains  were  then  evaluated  in  1.5-L  working  volume
benchtop  bioreactors  to  determine  the  full  potential  of  these  strains.
Lead  strains  were  selected  based  on  potential  for  either  psilocybin
(Gymdi30  and  Pancy10)  or  baeocystin  (Psicy30  and  Gymdi22)  pro-
duction,  according  to  their  performance  in  small  scale  screening.
Bioreactor operation generally followed previously optimized fermen-
tation parameters and control processes for the production of psilocybin
as outlined in Adams et al. (2019) with slight variation for the strains
selected for baeocystin production. Psilocybin production strains were
grown in AMM supplemented with 5 g/L of methionine and serine, while
baeocystin  production  strains  were  grown  without  supplemental
methionine. Through bioreactor studies using pSilo16, this supplement
composition  showed  that  restricting  methionine  supplementation  in-
creases the overall titers of norbaeocystin (~0 mg/L vs 178 ± 17 mg/L)
and baeocystin (162 ± 1 mg/L vs. 348 ± 13 mg/L), and correspondingly
decreases  titers  of  psilocybin  (920  ± 28  mg/L  vs.  402  ± 35  mg/L),
without  impacting  biomass  formation  (Fig.  S2).  These  results  are  hy-
pothesized  to  be  due  to  a  shortage  of  the  methyltransferase  co-factor
SAM, limiting PsiM activity in the nonsupplemented condition.

3.5. Psicy30 bioreactor evaluation

Selected  for  baeocystin  production  after  demonstrating  25.7  %
baeocystin  selectivity  in  small  scale,  Psicy30  was  scaled  up  to  a  1.5L
bioreactor  and  evaluated  without  methionine  supplementation  to
maximize baeocystin titer. We observed a longer lag phase (Figs. S3E
and S3F) before growth and production begin to increase as compared
with other lead candidates. This lag in growth is likely due to the initial
addition of the 4-hydroxyindole substrate, which has been reported to
be toxic to the cells in high concentrations (Adams et al., 2019) and puts
the culture under stress during key growth periods. It is  unclear why
some  strains  developed  in  this  work  present  higher  sensitivity  to
4-hydroxyindole than others, and this observation is a subject of future
investigations. Once the cells have emerged from the lag phase, cellular
growth  rate  increases  rapidly,  as  seen  in  the  OD600  of  the  culture
increasing from 0.5 to 12.5 in 11 h (Fig. S3F). The spike in cell density
correlates  with  the  majority  of  the  product  formation,  reaching
maximum productivity of baeocystin (9.6 ± 0.47 mg/L/hr) and psilo-
cybin (10.7 ± 0.11 mg/L/hr), both at 25h.

Psicy30  is  unique  in  that  it  shows  virtually  equal  production  of
baeocystin  and psilocybin,  reaching  113.5 ± 14.3 mg/L and  111.9 ±
5.6 mg/L, respectively. This combined with earlier results support the
suggestion that the PsiM sourced from the Psilocybe cyanescens mush-
room may have diminished affinity for the single-methylated substrate,
resulting  in  moderate baeocystin selectivity  leading  to the  baeocystin
accumulation.  It  is  important  to  note  that  although  the  baeocystin
accumulation  phenotype  was  retained  and  enhanced  in  bioreactor
evaluation, overall strain performance upon scale-up was poor and does
not support further study.

3.6. Gymdi22 bioreactor evaluation

This selected strain was the only transformant found to empirically
produce  more  baeocystin  than  psilocybin,  although  baeocystin  titers
were significantly below  the observed ~100  mg/L production  bench-
mark  found  in  some  Psicy  transformants  (#10,  #14,  #30)  in  initial
screening.  While  supplementing  to  enhance  baeocystin  production
further, this strain was able to produce 51.9 ± 7.9 mg/L baeocystin and
16.1 ± 5.6 mg/L psilocybin (Fig. S4A). Molar substrate yields were less
than  1.5  %  for  psilocybin  and  slightly  above  5  %  for  baeocystin
(Fig. S4D). Low demonstrated titers and poor molar yield does not make
Gymdi22  realistic  for  large-scale  baeocystin  production.  While  other
strains  investigated  in  this  work  have  demonstrated  much  higher
baeocystin titers, Gymdi22 represents the highest baeocystin selectivity
achieved at more than 76 % baeocystin. The increased lag phase seen in
Psicy30 appears with this strain as well, taking over 12 h to begin to see
significant growth or production. Maximum production coincides with
swift cell growth (Fig. S4B) and was achieved around hour 35, with 3.84
± 1.1 mg/L/hr baeocystin and 0.94 ± 0.02 mg/L/hr psilocybin.

This poor performance upon scale-up suggests that selecting strains
for baeocystin production on the basis of baeocystin selectivity without
considering overall titers and productivity results in poorly genetically
optimized  transformants  rather  than  constructs  capable  of  enhanced
baeocystin  production.  Suboptimal  pathway  performance  can  artifi-
cially  inflate  the  baeocystin  titer,  especially  when  screening  trans-
formants without methionine supplementation as was done for Psicy30
and Gymdi22. This increase may lead to false positive ‘baeocystin pro-
ducers’  that  upon  scaleup  to  more  conducive  growth  conditions  may
lose  their  identity  as  a  baeocystin  selective,  resulting  in  mediocre,
nonoptimal  psilocybin  production.  In  light  of  this  observation,  future
screening may benefit from selection metrics that incorporate total mass
flux in conjunction with baeocystin selectivity.

3.7. Pancy10 bioreactor evaluation

Selected  for  high  psilocybin  titer,  Pancy10  has  previously  demon-
strated psilocybin production of just under 200 mg/L in 48-well plates
(Fig. 6D) and up to 462 ± 16.9 mg/L in shake flasks (Fig. 6E). Upon
scaleup to 1.5-L bioreactor, product titers reached a maximum of 459 ±
32.7 mg/L psilocybin and 95.8 ± 11.6 mg/L baeocystin (Fig. S3A), an
insignificant difference in production (p > 0.05) as compared to shake
flasks.  Psilocybin  productivity  hit  a  maximum  around  30h,  achieving
26.3 ± 1.6 mg/L/hr psilocybin. Overall productivity was 9.19 ± 0.65
mg/L/hr  psilocybin  and  molar  yield  reached  a  maximum  at  49.7  %
(Fig. S3D). Overall productivity is notably impacted by the slowing of
both psilocybin and baeocystin production that begins around hour 36.
Overall, Pancy10’s performance upon scaleup did not warrant further
investigation,  as  it  did  not  outperform  the  previously  published
benchmarks.

3.8. Gymdi30 bioreactor evaluation

Gymdi30 was selected for enhanced psilocybin titer and achieved a
final titer upon scale-up of 1.46 ± 0.13 g/L psilocybin (Fig. 7A), sur-
passing the previously published production record of 1.16 g/L set by
the pSilo16 strain (Adams et al., 2019). Molar substrate yield of psilo-
cybin reached 43.2 ± 3.9 % and a combined psilocybin and baeocystin
total  molar  substrate  yield  of  54.5  ± 4.7  %  (Fig.  S5D).  Productivity
peaked  at  70.6  mg/L/hr  around  36  h,  which  also  correlates  with  the
maximum  oxygen  demand  as  denoted  by  the  agitation  maximum
observed in Fig. 7B. Overall productivity was calculated at 24 mg/L/hr.
Baeocystin titer reached a record high as well, steadily increasing to 274
± 8.1 mg/L at 85 h. This value more than doubles the baeocystin titer of
any  previous  report.  In  alignment  with  previous  bioreactor  runs
described  above,  a  productivity  plateau  is  present  although  delayed
compared  to  previous  runs,  occurring  after  approximately  60  h

126

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

Bioreactor runs of both Gymdi30 and pSilo16 took around 72 h to reach
reported titers. Therefore, overall productivity between the two strains
was similar and was not a considered economic factor. Using Gymdi30
allows for a $0.84/g reduction in cost due to both the elimination of
IPTG and increased psilocybin titer, leaving the cost per gram of psilo-
cybin for Gymdi30 at $8.42. Hence, Gymdi30 realized an approximate 9
% reduction in material cost as compared with pSilo16.

Table S5 demonstrates that while Gymdi30 ended up as the cheaper
option on a per gram of product basis, the increase in glucose and 4-
hydroxyindole fed made the cost per liter of fermentation capacity for
Gymdi30 higher than pSilo16. It is important to note that 4-hydroxyin-
dole represents roughly a third of total materials cost and that further
bioreactor  process  optimization  could  be  performed  with  the  goal  of
increasing yield on this component, further improving the economics of
this bioproduction process.

3.9. PsiM catalyzes the formation of aeruginascin

During  the  Gymdi30  bioreactor  evaluation,  we  observed  minor
accumulation of a compound with a retention time and mass-to-charge
ratio consistent with aeruginascin. Recent in silico and in vitro analysis of
Psicu PsiM came to the conclusion that the formation of aeruginascin
was unfavorable and unobserved (Hudspeth et al., 2024), which leads us
to further  evaluate the aforementioned  observation. To  test if  aerugi-
nascin formation was  due to  the presence  of PsiM,  as opposed  to the
promiscuous action of another N-methyltransferase naturally present in
our E. coli host, we supplemented psilocin to a series of controlled strains
expressing PsiK only, PsiK and PsiM, and PsiD, PsiK, and PsiM (Gymdi30
configuration). Psilocin was supplemented to circumvent the transport
limitations  related  to  phosphorylated  tryptamines  discussed  above.  It
also provides a route to psilocybin, which avoids the accumulation of
other tryptamines that could complicate the analysis (Fig. 1). PsiK first
converts  psilocin  to  psilocybin  in  vivo,  which  could  then  further  be
methylated by PsiM. The Gymdi30 strain was also used in this context as
a genetically optimized control, as the other PsiK and PsiM containing
vectors were not transcriptionally optimized for this study.

When no supplement was added, no psilocybin (m/z 285) or aeru-
ginascin  (m/z  299)  were  observed,  as  expected  (Fig.  S6A,  top  half).
However,  when psilocin was supplemented to the  growth media, psi-
locybin formation was observed in all strains expressing PsiK, and low
formation of aeruginascin was observed in strains expressing PsiM and
was  lacking  in  its  absence  (Fig.  S6A,  bottom  half).  Furthermore,  this
observation of aeruginascin was much more pronounced under the more
optimal bioreactor conditions for both Gymdi30 and Psilo16 production
strains, suggesting that this observation is not unique to Gymdi PsiM, but
is also observed from Psicu PsiM (pSilo16 (black trace), Fig. S6B). It is
important  to  note  that  the  observed  aeruginascin  accumulation,  even
under optimal conditions, remains quite low, representing less than 1 %
of the psilocybin accumulation. Given this evidence, we conclude that
PsiM  is  capable  of  aeruginascin  formation;  however,  this  activity  is
markedly lower than its activity towards either norbaeocystin or baeo-
cystin  substrates,  and  therefore  is  only  detectable  under  optimal
conditions.

3.10. Proteomic analysis reveals energy limitations for continued High
psilocybin production in the Gymdi30 strain

Bioreactor strains discussed above all show a plateauing of produc-
tion during the second half of the fermentation. Strains like Pancy10 and
Psicy30  hit  this  production  plateau  around  hour  36  (Fig.  S3),  while
Gymdi30 remains productive until hour 60 (Fig. 7). To investigate this
phenomenon,  comparative  proteomic  analysis  of  our  best  performing
psilocybin production strain, Gymdi30, was performed. Gymdi30 cells
grown in bioreactors were collected in triplicate in both the log (t = 36
h) and early stationary phase (t = 61 h) of cell growth, which corre-
sponds  to  high  and  low  psilocybin  productivity  periods,  respectively

Fig. 7. Gymdi30 bioreactor vessel data. (a) Metabolite concentrations, OD600,
and  glucose  concentration,  N  = 3.  (b)  Representative  process  data  showing
reactor temperature, pH, dissolved oxygen (DO), and agitation rate.

(Fig. 7A).

Fig.  7 shows  the  metabolite  and  process  curves  for  the  Gymdi30
bioreactor runs. Fig. 7A shows transient glucose and 4-hydroxyindole
concentrations,  showing  an  initial  decrease  to  near  zero  and  feeding
strategies  that  maintained  concentrations  low  enough  not  to  hinder
psilocybin  production,  but  are  also  non-zero,  maintaining  substrate
availability  throughout  the  fermentation.  Fig.  7B  shows  a  steadily
increasing oxygen demand characterized first by a decrease in dissolved
oxygen (green) to the 30 % setpoint, then an increase agitation speed
(blue) to maintain the DO at the 30 % setpoint. Oxygen demand reaches
a plateau around 36 h, beginning to slow around the 44-h mark, char-
acterized by a decrease in agitation rate. Psilocybin titer and cell growth
continue  to  increase  for  roughly  12  more  hours  before  reaching  a
◦
plateau after 60 h. No large fluctuations in vessel temperature (37
C) or
pH (6.5) were observed.

While  improved  production  of  both  psilocybin  and  baeocystin  is
notable in itself, this strain is also unique in its pathway construction.
Sequencing of Gymdi30 revealed the presence of the constitutive XylA
promoter. This promoter permits the bioproduction of large quantities of
psilocybin and its intermediates without the addition of IPTG, which is
required  by  the  inducible  H10  promoter  in  pSilo16.  These  qualities
result in an economic value as well as a process simplification due to no
need to purchase the inducer or schedule the induction.

Lab  scale  economic  analyses  of  both  pSilo16  and  Gymdi30  were
performed as shown in Table S5. This analysis was performed using lab-
scale quantities of media components and pricing from recent orders (ca.
2021–2023).  Economic  analysis  of  psilocybin  production  using  previ-
ously  published  pSilo16  bioreactor  data  considering  media  and  sup-
plement costs as well as glucose and 4-hydroxyindole consumption lead
to  the  estimated  cost  of  $9.26  per  gram  of  psilocybin  (Table  S5).

127

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

(Fig. 7 and S5).

Approximately 1100 proteins were identified under each condition,
with  108  proteins  showing  differential  expression  between  the  two
growth  phases  (Fig.  8).  Notably,  the  enzyme  PsiD  was  significantly
lower in the early stationary phase (61 h) compared to the log phase (36
h),  indicating  reduced  carbon  flux  toward  the  psilocybin  pathway,
which corresponds to lower psilocybin production during the stationary
phase.  Analysis  of  the  soluble  protein  relative  abundance  data  shows
that  the  exogenous  pathway  enzymes  (PsiD,  PsiK,  and  PsiM)  and  the
endogenous TrpB rank among the top quartile of most abundant proteins
at both time points. At 36 h, TrpB, PsiD, PsiK, and PsiM were in the 93rd,
84th, 97th, and 99th percentiles, respectively. By 61 h, TrpB, PsiK, and
PsiM  remained  at  the  92nd,  96th,  and  99th  percentiles,  while  PsiD
dropped  to  the  77th  percentile.  These  data  suggest  that  the  key
biosynthetic enzymes are expressed at levels comparable to core meta-
bolic  enzymes,  enabling  a  balance  between  the  metabolic  burden  of
pathway  overexpression  and  robust  biosynthetic  activity—ultimately
yielding the observed strong biosynthetic phenotype.

Compared  to  the  low-production  phase  at  61  h,  several  enzymes
involved in the TCA cycle, including fumarate hydratase (FH), aconitase
(ACO1/2), and phosphoenolpyruvate carboxylase (PEPC), were signifi-
cantly more abundant during the high-production log phase. PEPC likely
supplies  oxaloacetate  by  converting  phosphoenolpyruvate  (PEP)  from
the glycolysis pathway, thereby accelerating reductant generation via
the TCA cycle. This is consistent with the observation of higher protein
fragment  levels  from  the  electron  transport  chain  (ETC)  in  the  low-
production  phase  samples  (degraded  ETC  complex  fragments  in  the
soluble  proteomics  fraction),  including  NADH  dehydrogenase  (NDH)
and  ATP  synthase  alpha  and  beta  subunits.  These  results  suggest
increased  energy  demands  to  support  the  heterologous  psilocybin
pathway, aligning with the higher oxygen consumption observed at 36 h
(Fig. 7). During the low-production phase at 61 h, cell energy needs are
likely  fulfilled  by  a  shift  in  their  metabolism  toward  fermentative
pathways.  This  is  supported  by  higher  levels  of  enzymes  involved  in
glycolysis,
such  as  glyceraldehyde-3-phosphate  dehydrogenase
(GAPDH),  and  the  pentose  phosphate  pathway,  such  as  transaldolase
(TA).

Interestingly,  proteomic  analysis  revealed  changes  in  carbon
resource allocation driven by the supplementation of amino acids such
as serine to support the heterologous pathway. The most striking impact
was observed in cysteine synthesis. Proteins related to sulfur uptake and
conversion for cysteine synthesis were significantly more abundant in
log phase cells. Specifically, ATP sulfurylase (ATPS) was over 12-fold
higher  in  the  log  phase  compared  to  the  stationary  phase.  Addition-
ally, the sulfate ABC transporter (SulT) and phosphoadenosine 5′-phos-
phosulfate reductase (PAPSR) were over 2-fold higher in the log phase.
This  is  supported  by  previous  findings  that  serine  can  induce  sulfur
metabolism to support cysteine synthesis, as serine serves as a precursor
for  cysteine  (Gu´edon  and  Martin-Verstraete,  2006).  Furthermore,
S-adenosylmethionine synthase (MetK) was expressed at higher levels in
low-production cells, suggesting inefficiency in SAM supply during the
stationary phase. These findings point to future optimization targets in
energy  production  pathways
to  sustain  continuous  psilocybin
production.

Fig.  8. Proteomic  data  demonstrating  differentially  regulated  proteins  of  a
Gymdi30  culture  at  36  h  and  61  h,  N  = 3.  Red  dots  represent  proteins  with
significantly higher abundances in high-producing cells (36 h), while blue dots
represent proteins with significantly higher abundances in low-producing cells
(61  h).  Gray  dots  denote  proteins  with  no  significant  change  in  abundance.
Enzymes discussed in the text are labeled for reference. (For interpretation of
the references to colour in this figure legend, the reader is referred to the Web
version of this article.)

psilocybin.  Additionally,  the  constitutive  promoter  used  in  the  con-
struction of Gymdi30 eliminates the need for IPTG induction, reducing
both process cost and complexity. Proteomic analysis of Gymdi30 was
performed  to  gain  insight  into  possible  explanations  for  the  abrupt
reduction in psilocybin productivity and to provide solutions capable of
further extending the production window of our top performing strain.
While  multiple  sulfur  supplementation  conditions  were  considered,
these  failed  to  increase  titer  significantly  or  extend  the  length  of  fer-
mentations.  Further  investigation  is  required  to  achieve  a  process-
orientated solution to extend productivity and enhanced product titer.

CRediT authorship contribution statement

Madeleine R. Keller: Writing – review & editing, Writing – original
draft, Investigation, Formal analysis, Data curation, Conceptualization.
Madeline G. McKinney: Writing – review & editing, Writing – original
draft, Investigation, Formal analysis, Data curation, Conceptualization.
Abhishek K. Sen: Writing – review & editing, Investigation. Felicia G.
Guagliardo:  Writing  –  review  &  editing,  Investigation.  Elle  B.  Hell-
warth: Writing – review & editing, Investigation. Khondokar Nowshin
Islam:  Writing  –  review  &  editing,  Investigation,  Formal  analysis.
Nicholas A. Kaplan: Writing – review & editing, Investigation, Formal
analysis. William J. Gibbons: Jr, Writing – review & editing, Investi-
gation. Grace E. Kemmerly: Writing – review & editing, Investigation.
Chance Meers: Writing – review & editing, Formal analysis. Xin Wang:
Writing – review & editing, Writing – original draft, Supervision, Formal
analysis, Data curation, Conceptualization. J. Andrew Jones: Writing –
review & editing, Writing – original draft, Supervision, Project admin-
istration,  Methodology,  Investigation,  Funding  acquisition,  Formal
analysis, Data curation, Conceptualization.

4. Conclusions

Competing interests

This work demonstrates a successful alternative optimization tech-
nique  for  biosynthetic  production  platforms  utilizing  enzymes  from
natural  sources.  Psilocybin  pathway  enzymes,  originating  from  4
different  species  of  hallucinogenic  mushrooms,  were  investigated  for
enhanced  production  of  methylated  tryptamines  of  interest  in  a  re-
combinant  E.  coli  platform.  Select  transformants  were  isolated,  vali-
dated,  and  evaluated  at  benchtop  bioreactor  scale.  This  work
successfully  developed  a  psilocybin  production  strain,  Gymdi30,
capable  of  the  highest  published  titer  to  date  of  1.46  ± 0.13  g/L

128

This work was supported by a sponsored research grant from PsyBio
Therapeutics (JAJ). PsyBio Therapeutics did not contribute to the data
collection, analysis, writing, or decision to publish. JAJ is a significant
shareholder  at  PsyBio  Therapeutics.  MRK,  MGM,  and  JAJ  are  co-
inventors  on  patent  applications  related  to  this  work.  MRK,  MGM,
AKS, FGG, NAK, WJGJ, and JAJ are co-inventors on patent applications
related to tryptamine biosynthesis. All other authors declare no conflicts
of interest.

M.R. Keller et al.

Metabolic Engineering 91 (2025) 119–129

Acknowledgments

Requests  for  strains  and  plasmids  capable  of  producing  controlled
substances (e.g., psilocybin) will require proof of appropriate approvals
and  licenses  from  all  necessary  state  and  federal  agencies  prior  to
completion of a materials transfer agreement. The authors would like to
thank  Alexandra  M.  Adams  for  construction  of  several  plasmid  con-
structs  used  in  this  work  and  David  K.  Tiller  for  providing  helpful
comments and edits on the final draft.

Appendix A. Supplementary data

Supplementary data to this article can be found online at https://doi.

org/10.1016/j.ymben.2025.04.003.

Data availability

Data will be made available on request.

References

Adams, A.M., Kaplan, N.A., Wei, Z., Brinton, J.D., Monnier, C.S., Enacopol, A.L.,

Ramelot, T.A., Jones, J.A., 2019. In vivo production of psilocybin in E. coli. Metab.
Eng. 56, 111–119.

Adams, A.M., Anas, N.A., Sen, A.K., Hinegardner-Hendricks, J.D., O’Dell, P.J.,

Gibbons, W.J., Flower, J.E., McMurray, M.S., Jones, J.A., 2022. Development of an
E. coli-based norbaeocystin production platform and evaluation of behavioral effects
in rats. Metab Eng Commun 14.

Carvalho, P.C., Lima, D.B., Leprevost, F.V., Santos, M.D.M., Fischer, J.S.G., Aquino, P.F.,
Moresco, J.J., Yates, J.R., Barbosa, V.C., 2016. Integrated analysis of shotgun
proteomic data with PatternLab for proteomics 4.0. Nat. Protoc. 11.

Englaender, J.A., Jones, J.A., Cress, B.F., Kuhlman, T.E., Linhardt, R.J., Koffas, M.A.G.,
2017. Effect of genomic integration location on heterologous protein expression and
metabolic engineering in E. coli. ACS Synth. Biol. 6.

Flower JE, Gibbons WJ, Adams AM, Wang X, Broude CN, Jones JA: “Biosynthesis of
psilocybin and its nonnatural derivatives by a promiscuous psilocybin synthesis
pathway in Escherichia coli .” Biotechnol. Bioeng. 2023, doi:10.1002/bit.28480.
Fricke, J., Blei, F., Hoffmeister, D., 2017. Enzymatic synthesis of psilocybin. Angew.

Chem. Int. Ed. 56.

Garcia-Romeu, A., Griffiths, R., Johnson, M., 2015. Psilocybin-occasioned mystical
experiences in the treatment of tobacco addiction. Curr. Drug Abuse Rev. 7,
157–164.

Gibbons, W.J., McKinney, M.G., O’Dell, P.J., Bollinger, B.A., Jones, J.A., 2021.

Homebrewed psilocybin: can new routes for pharmaceutical psilocybin production
enable recreational use? Bioengineered 12, 8863–8871.

Gluff, J.A., Teolis, M.G., Moore, A.A., Kelly, D.R., 2017. Post-traumatic Stress Disorder

(PTSD): A Webliography 21, 389–401.

Gotvaldov´a, K., Boroviˇcka, J., H´ajkov´a, K., Cihl´aˇrov´a, P., Rockefeller, A., Kuchaˇr, M.,

2022. Extensive collection of psychotropic mushrooms with determination of their
tryptamine alkaloids. Int. J. Mol. Sci. 23.

Grob, C.S., Danforth, A.L., Chopra, G.S., Hagerty, M., McKay, C.R., Halberstad, A.L.,

Greer, G.R., 2011. Pilot study of psilocybin treatment for anxiety in patients with
advanced-stage cancer. Arch. Gen. Psychiatry 68, 71–78.

Gu´edon, E., Martin-Verstraete, I., 2006. Cysteine metabolism and its regulation in
bacteria. In: Amino Acid Biosynthesis ~ Pathways, Regulation and Metabolic
Engineering. Springer, Berlin Heidelberg, pp. 195–218.

He, W., Fu, L., Li, G., Andrew Jones, J., Linhardt, R.J., Koffas, M., 2015. Production of

chondroitin in metabolically engineered E. coli. Metab. Eng. 27.

Hirsch, M., Birnbaum, R.J., 2018. Selective serotonin reuptake inhibitors: pharmacology.

administration, and side effects. https://www.uptodate.com/contents/selecti
ve-serotonin-reuptake-inhibitors-pharmacology-administration-and-side-effects.
Hoefgen, S., Lin, J., Fricke, J., Stroe, M.C., Mattern, D.J., Kufs, J.E., Hortschansky, P.,

Brakhage, A.A., Hoffmeister, D., Valiante, V., 2018. Facile assembly and
fluorescence-based screening method for heterologous expression of biosynthetic
pathways in fungi. Metab. Eng. 48, 44–51.

Hofmann, A., Frey, A., Ott, H., Petrzilka, Th, Troxler, F., 1958. Konstitutionsaufkl¨arung

und Synthese von Psilocybin. Experientia 14, 397–399.

Hudspeth, J., Rogge, K., D¨orner, S., Müll, M., Hoffmeister, D., Rupp, B., Werten, S., 2024.

Methyl transfer in psilocybin biosynthesis. Nat. Commun. 15.

Jones, J.A., Vernacchio, V.R., Lachance, D.M., Lebovich, M., Fu, L., Shirke, A.N.,

Schultz, V.L., Cress, B., Linhardt, R.J., Koffas, M.A.G., 2015. ePathOptimize: a
combinatorial approach for transcriptional balancing of metabolic pathways. Sci.
Rep. 5, 11301.

Katoh, K., Standley, D.M., 2013. MAFFT multiple sequence alignment software version 7:

improvements in performance and usability. Mol. Biol. Evol. 30, 772–780.

Kooijman, N.I., Willegers, T., Reuser, A., Mulleners, W.M., Kramers, C., Vissers, K.C.P.,
van der Wal, S.E.I., 2023. Are psychedelics the answer to chronic pain: a review of
current literature. Pain Pract. https://doi.org/10.1111/papr.13203.

Matsushima, Y., Shirota, O., Kikura-Hanajiri, R., Goda, Y., Eguchi, F., 2009. Effects of
psilocybe argentipes on marble-burying behavior in mice. Biosci. Biotechnol.
Biochem. 73, 1866–1868.

McTaggart, A.R., James, T.Y., Slot, J.C., Barlow, C., Fechner, N., Shuey, L.S., Drenth, A.,
2023. Genome sequencing progenies of magic mushrooms (Psilocybe subaeruginosa)
identifies tetrapolar mating and gene duplications in the psilocybin pathway. Fungal
Genet. Biol. 165.

Milne, N., Thomsen, P., Mølgaard Knudsen, N., Rubaszka, P., Kristensen, M., Borodina, I.,
2020. Metabolic engineering of Saccharomyces cerevisiae for the de novo production
of psilocybin and related tryptamine derivatives. Metab. Eng. 60, 25–36.
Minh, B.Q., Schmidt, H.A., Chernomor, O., Schrempf, D., Woodhams, M.D., von

Haeseler, A., Lanfear, R., 2020. IQ-TREE 2: new models and efficient methods for
phylogenetic inference in the genomic era. Mol. Biol. Evol. 37, 1530–1534.

NIH: Key Substance Use and Mental Health Indicators in the United States: Results from

the 2022 National Survey on Drug Use and Health, 2023.

Rakoczy, R.J., Runge, G.N., Sen, A.K., Sandoval, O., Wells, H.G., Nguyen, Q., Roberts, B.
R., Sciortino, J.H., Gibbons, W.J., Friedberg, L.M., et al., 2024. Pharmacological and
behavioural effects of tryptamines present in psilocybin-containing mushrooms. Br.
J. Pharmacol. 181, 3627–3641.

Reynolds, H.T., Vijayakumar, V., Gluck-Thaler, E., Korotkin, H.B., Matheny, P.B., Slot, J.
C., 2018. Horizontal gene cluster transfer increased hallucinogenic mushroom
diversity. Evol Lett 2.

Ross, S., Bossis, A., Guss, J., Agin-Liebes, G., Malone, T., Cohen, B., Mennenga, S.E.,
Belser, A., Kalliontzi, K., Babb, J., et al., 2016. Rapid and sustained symptom
reduction following psilocybin treatment for anxiety and depression in patients with
life-threatening cancer: a randomized controlled trial. J. Psychopharmacol. 30,
1165–1180.

Shinde, S., Zhang, X., Singapuri, S.P., Kalra, I., Liu, X., Morgan-Kiss, R.M., Wang, X.,
2020. Glycogen metabolism supports photosynthesis start through the oxidative
pentose phosphate pathway in cyanobacteria. Plant Physiol 182, 507–517.

Vizcaíno, J.A., Csordas, A., Del-Toro, N., Dianes, J.A., Griss, J., Lavidas, I., Mayer, G.,

Perez-Riverol, Y., Reisinger, F., Ternent, T., et al., 2016. 2016 update of the PRIDE
database and its related tools. Nucleic Acids Res. 44, D447–D456.

Vunduk, J., Tura, D., Biketova, A.Y., 2002. Medicinal Mushroom Nutraceutical

Commercialization: Two Sides of a Coin. CRC Press.

Xu, P., Vansiri, A., Bhan, N., Koffas, M.A.G., 2012. EPathBrick: a synthetic biology

platform for engineering metabolic pathways in E. coli. ACS Synth. Biol. 1, 256–266.

Xu, P., Li, L., Zhang, F., Stephanopoulos, G., Koffas, M., 2014. Improving fatty acids

production by engineering dynamic pathway regulation and metabolic control. Proc.
Natl. Acad. Sci. U. S. A. 111, 11299–11304.

Zybailov, B., Mosley, A.L., Sardiu, M.E., Coleman, M.K., Florens, L., Washburn, M.P.,

2006. Statistical analysis of membrane proteome expression changes in
Saccharomyces cerevisiae. J. Proteome Res. 5, 2339–2347.

129

