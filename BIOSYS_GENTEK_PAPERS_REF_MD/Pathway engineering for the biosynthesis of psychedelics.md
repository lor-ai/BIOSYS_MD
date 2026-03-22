Available online at www.sciencedirect.com

Review

Pathway engineering for the biosynthesis of
psychedelics
Zachary N Abrahms*, Abhishek K Sen* and J Andrew Jones

]]]]

]]]]]]

Naturally occurring psychoactive compounds have been used
for cultural and ethnomedical purposes for centuries. Several
more such molecules continue to be chemically synthesized,
exhibiting a wide range of potency, therapeutic, and
hallucinogenic effects. Promising clinical data and a renewed
interest in understanding the cellular mechanisms of action
have inspired synthetic biology efforts to develop alternative
production routes for psychedelic compounds. Here, we
highlight the latest biosynthetic accomplishments for
indolamines (psilocybin, N,N-dimethyltryptamine, 5-methoxy-
N,N-dimethyltryptamine, and bufotenine), ergolines (lysergic
acid), and phenethylamines (mescaline) in both eukaryotic and
prokaryotic production hosts. We further curate a list of relevant
biosynthetic enzymes that have reports of successful in vivo
heterologous activity.

diethylamide  (LSD;  acid),  and  mescaline  (peyote),  re-
spectively  (Figure  1).  Various  synthesis  methods  have
been  reported  for  these  classes  of  compounds,  ranging
from traditional chemical synthesis to in vitro and in vivo
biosynthesis,  each  with  unique  pros  and  cons  [7–9].  In
vivo  production  in  heterologous  hosts,  such  as  Sacchar-
omyces cerevisiae and Escherichia coli, offers an alternative
and  increasingly  competitive  route  to  longstanding
chemical  synthetic  methods  used  to  produce  these  va-
luable compounds as well as their derivatives (Figure 1)
[10].  Here,  we  review  the  landscape  of  heterologous
biosynthetic  efforts  for  improved  psychedelic  drug  pro-
duction and summarize efforts to understand, engineer,
and characterize the key classes of enzymes involved in
these pathways.

Address
Miami  University,  Department  of  Chemical,  Paper,  and  Biomedical
Engineering, Oxford, OH, USA

Corresponding author: Jones, J Andrew (jones@miamioh.edu)
* These authors contributed equally to this work.

Current Opinion in Biotechnology 2025, 94:103314

This review comes from a themed issue on Food Biotechnology

Edited by Mattheos Koffas and Tom Mansell

For complete overview of the section, please refer to the article
collection, “Food Biotechnology (2025)”

Available online 15 May 2025

https://doi.org/10.1016/j.copbio.2025.103314

0958–1669/© 2025 The Author(s). Published by Elsevier Ltd. This is
an open access article under the CC BY-NC license (http://
creativecommons.org/licenses/by-nc/4.0/).

Introduction
Psychedelic  compounds  are  naturally  produced  by  a
range of organisms, including fungi, plants, and animals,
and have been used for millennia in spiritual rituals [1,2].
These  small  molecules  are  of  revitalized  interest  for
their potential to treat individuals with neuropsychiatric
conditions  [3–5].  Most  of  these  compounds  elicit  a  hal-
lucinogenic experience on the user by acting as 5-HT2A
serotonin  receptor  agonists  [6].  These  drugs  are  classi-
fied  as  tryptamines,  ergolines,  and  phenethylamines,
such  as  psilocybin  (magic  mushrooms),  lysergic  acid

Legislation and regulation
While  we  are  centrally  focused  on  the  production  of
psychedelics,  we  must  acknowledge  the  regulatory  fra-
mework  of  these  compounds  that  will  continue  to  in-
fluence  work  in  this  field.  In  the  United  States,  most
psychedelics are classified as Schedule I drugs, labeling
them as having no currently accepted medical use and a
high  potential  for  abuse  [11].  The  acknowledgment  of
the  potential  therapeutic  benefit  of  psychedelics,  cou-
pled  with  decriminalization  efforts,  has  led  some  states
to change their legislation. U.S. federal policy, however,
has  remained  unchanged.  For  example,  Oregon  and
Colorado legalized many psychedelic substances in 2020
and  2022,  respectively,  albeit  each  with  their  own  in-
dependent legal frameworks and restrictions [12]. Even
with  the  increasing  number  of  bills  seeking  to  support
the reform of regulatory policy for psychedelics, in 2024,
many counties in Oregon voted to ban psilocybin locally
[13,14].  The  strict  policies  and  regulatory  hurdles  con-
trolling the production, use, and storage of psychedelics
discourage  academic  research  as  well  as  mainstream  in-
vestment  in  this  commercial  space.  The  volatile  reg-
ulatory patchwork for psychedelics in the United States
makes  it  difficult  to  predict  the  future  legislation  of
these  compounds.  While  the  aforementioned  informa-
tion is based on U.S. policy, we acknowledge that other
countries  and
legislative  bodies  are  experiencing
changes surrounding the legality of psychedelic drugs as
well.  For  example,  in  2023,  Australia  approved  pre-
scription-based use of psilocybin for treatment-resistant
depression  and  3,4-methylenedioxymethamphetamine
(MDMA; ecstasy) for post-traumatic stress disorder [15].
Furthermore,  the  European  Medicines  Agency  (EMA)

www.sciencedirect.com

Current Opinion in Biotechnology 2025, 94:103314

2 Food Biotechnology

Figure 1

Overview of natural and biosynthetic sources for psychedelics. The left panel depicts known natural sources for psychoactive compounds, grouped
based on the class of psychedelic (or psychedelic precursor) they produce. The right panel shows an overview of the heterologous biosynthetic
production of psychedelics, starting from the nucleic acid sequences from nature that encode the biosynthetic pathways, followed by screening and
scale-up processes. This figure was created with the assistance of BioRender and Google Gemini.

publicly acknowledges the potential for psychedelics to
treat  neuropsychiatric  conditions,  and  in  April  of  2024,
the  EMA  held  a  workshop  to  discuss  how  they  can  fa-
cilitate
testing  of  psyche-
delics [16].

the  development  and

Recombinant production in eukaryotic hosts
Fricke  et  al.  were  the  first  to  identify  the  enzymes  re-
quired  for  biosynthesis  of  the  classical  indolamine,  psi-
locybin  [17].  This  work  led  to  the  psilocybin  pathway
serving  as  a  proof-of-principle  example  and  further  en-
abled  development  of  a  synthetic  biology  tool  to  im-
prove heterologous  multi-gene  expression  in  the  fungal
host  Aspergillus  nidulans,  resulting  in  psilocybin  titers  of
up  to 110 mg/l  [18]. This  work and a summary  of other
production routes were reviewed by Fricke et al. in 2019
[7].  Soon  after,  a  modified  version  of  the  pathway,  in-
cluding  an  alternative  decarboxylase  and  newly  identi-
fied P450 reductase, was expressed in brewer’s yeast (S.
cerevisiae), resulting in psilocybin titers of 627  ±  140 mg/l
in  a  fed-batch  bioreactor  [19].  More  recently,  efforts
have focused on the identification and deletion of genes
encoding  tryptophan  degrading  enzymes  in  S.  cerevisiae

and A. nidulans to increase the intracellular availability of
psilocybin’s  tryptophan  precursor.  In  A.  nidulans,  this
resulted  in  a  10-fold  increase  in  psilocybin  production
over  wild  type  and,  following  process  optimization,  en-
abled  batch  culture  psilocybin  titers  of  up  to  267 mg/l
[20].  Despite  improvements  in  psilocybin  titer  from re-
combinant  fungal  hosts,  product  stability  remains  a
challenge,  with  several  reports  of  significant  accumula-
tion  of  dephosphorylated  products  of  psilocybin  and  its
precursors.  It  remains  unclear  if  this  degradation  is
spontaneous  or  enzyme  catalyzed,  but  blocking  this
process  could  improve  the  competitiveness  of  fungal
production  hosts.  Notably,  psilocybin  production  in
bacterial  hosts,  reviewed  below,  demonstrates  greater
product  stability,  suggesting  a  eukaryotic  host-specific
link to the observed product degradation.

Ergolines,  such  as  lysergic  acid  (LA),  have  also  been
produced using recombinant fungal hosts. LA is of par-
ticular interest because it serves as a precursor to LSD.
In A. nidulans, overexpression of the P450 CloA enabled
production of LA, albeit at low titers [21]. S. cerevisiae has
also been harnessed to produce a specific stereochemical
configuration  of  LA,  D-lysergic  acid  (DLA).  The  first

Current Opinion in Biotechnology 2025, 94:103314

www.sciencedirect.com

Current Opinion in Biotechnologyheterologous expression of the DLA pathway in S. cere-
visiae  resulted  in  1.7 mg/l  of  DLA  in  a  1 l  fed-batch
fermentation  [22].  Hu  et  al.,  however,  speculated  im-
proved production titers could be achieved by returning
to  the  native  fungi,  Claviceps  paspali.  Ergoline  produc-
tion  was  improved  in  C.  paspali  through  media  optimi-
zation  and  inactivation  of  the  lpsB  gene,  blocking  LA
degradation.  These  changes  resulted  in  a  peak  titer  of
total lysergic acids (iso-LA and LA) of 3.7 g/l, which was
4.6 times higher than total LA production from native C.
paspali  in  nonoptimized  media  [23].  Recently,  ergoline
production in S. cerevisiae was improved through a series
of  genetic  manipulations,  including  deletion  of  the
SCH9  gene  to  enhance  peroxisomal  metabolism,  tar-
geting  EasC  to  the  peroxisomes,  and  spatially  reor-
ienting  the  P450  CloA  and  its  reductase  partner  on  the
endoplasmic  reticulum  to  help  electron  transfer.  These
modifications  resulted  in  a  17.4-fold  increase  in  LA
concentrations,  resulting
in  fermentation  titers  of
509.8 mg/l in a 50 l fed-batch bioreactor [24].

remained  unknown

Phenethylamines  include  commonly  known  psyche-
delics  and  stimulants  such  as  mescaline,  MDMA  (ec-
stasy),  amphetamine,  and  methamphetamine  and
numerous  other  synthesized  derivatives  and  neuro-
transmitters,  such  as  dopamine,  adrenaline,  and  nora-
drenaline. Biosynthetic efforts of phenethylamines have
been  limited  compared  to  indolamines.  Mescaline  was
one of the first psychedelics used by humans over 8500
years  ago  [25].  Despite  early  radiolabeling  studies  that
traced  the  catalytic  steps  from  tyrosine,  a  mono-
oxygenase
[26,27].  Recently,
Berman  et  al.  discovered  this  missing  cytochrome  P450
(CYP),  LwCYP76AD131,  in  the  skin  of  buttons  that
contain  the  highest  mescaline  concentrations  in  Lopho-
phora williamsii, a cactus popularly known as peyote [28].
We now understand that there are two natural routes to
the  mescaline  precursor,  dopamine:  hydroxylation  of
tyrosine (by BvCYP76AD1) followed by decarboxylation
(LwTyDC2)  or  vice  versa  [27,28].  Dopamine  is  then
methylated  at  the  3’  hydroxyl  group  by  LwOMT1  or
LwOMT5
3-methoxytyramine.  Next,
LwCYP76AD131  adds  the  final  hydroxyl  group.  There-
after,  the  5’  and  4’  hydroxyl  groups  are  O-methylated
sequentially  by  LwOMT1/LwOMT5  and  LwOMT10/
LwOMT11, respectively, to yield mescaline.

form

to

Biosynthesis of psychedelics Abrahms, Sen and Jones 3

concentrations  of  all  pathway  intermediates,  until  the
penultimate  step  [28].  Therefore,  despite  successful
functional  expression  of  necessary  enzymes,  neither
expression system yielded de novo mescaline.

Recombinant production in bacterial hosts
There  are  no  known  bacteria,  which  naturally  produce
psychedelics.  The  bacterial  host,  E.  coli,  was  first  har-
nessed  for  psilocybin  production  by  expressing  the
fungal  enzymes  PsiD,  PsiK,  and  PsiM,  resulting  in  psi-
locybin titers of 1.16 g/l in a fed-batch bioreactor system
[29].  This  route  circumvented  the  need  for  the  P450
monooxygenase,  PsiH,  through  the  feeding  of  4-hydro-
xyindole,  which  was  promiscuously  converted  to  4-hy-
droxytryptophan  by  the  native  tryptophan  synthase,
TrpB.  PsiH  has  shown  limited  activity  in  prokaryotic
hosts due to its native endoplasmic reticulum membrane
association, which is lacking in prokaryotes. Despite this
observation,  proof-of-principle  level,  de  novo  psilocybin
production  in  E.  coli  was  achieved  through  an  in-
vestigation into the potential of small, regulatory RNAs
(sRNA)  to  improve  metabolic  pathway  regulation  [30].
The  sRNAs  were  utilized  to  lower  the  expression  of
enzymes  involved  in  drug-export,  L-Tryptophan  con-
sumption, and S-adenosyl methionine (SAM) utilization.
Via  these  expression  changes,  a  fourfold  increase  in
psilocybin  production  (from  6.9 mg/l  to  27.7 mg/l)  was
observed [30]. More recently, the promiscuity of the full
psilocybin  pathway,  including  PsiH,  was  harnessed  to
synthesize  13  psilocybin  derivatives  in  E.  coli,  starting
from  single-substituted  indole  derivatives  [31].  This
work  identified  PsiH  as  the  primary  rate-limiting  step,
with  numerous  tryptophan  and  tryptamine  derivatives
produced  at  high  yield.  Beyond  psilocybin,  E.  coli  has
also  been  engineered  to  produce  the  psychedelic  tryp-
tamines  N,N-dimethyltryptamine  (DMT),  5-methoxy-
N,N-dimethyltryptamine
(5-MeO-DMT),  and  5-hy-
droxy-N,N-dimethyltryptamine  (bufotenine)  from  cor-
responding indole derivatives using Homo sapiens INMT
and PsiD [32]. Notably, the discovery of a highly active
N-methyltransferase  from  the  cane  toad  (RmNMT)  has
greatly  expanded  the  biosynthetic  potential  for  nu-
merous DMT  derivatives [33,34]. We recommend a re-
view  by  Jamieson  et  al.  for  additional  information
regarding the biosynthesis of DMT [35].

Berman  et  al.  heterologously  expressed  the  necessary
genes  (LwTyDC2,  LwCYP76AD131,  LwOMT1,  and
LwOMT11)  in  S.  cerevisiae,  but  unfortunately,  they  ob-
served shunting of pathway intermediates by a putative
arylalkyl  amine  N-acetyltransferase,  ScAANAT,  only
observing  accumulation  of  tyramine  and  dopamine.
They  were  able  to  verify  the  in  vivo  activity  of  each
enzyme  by  supplementing  respective  intermediates  as
substrates  [28].  Next,  the  pathway  was  reconstituted  in
Nicotiana  benthamiana,  which  significantly  improved

Enzymes involved in the biosynthesis of
psychedelics
Assembling  functional  heterologous  pathways  faces  a
litany  of  technical  challenges,  such  as  inadequate  en-
zyme  expression,  low  enzyme  activity,  high  metabolic
burden,  and  cofactor  imbalances,  which  often  lead  to
metabolic flux bottlenecks and low system performance.
Some  of  these  issues  can  successfully  be  navigated
through  alternative  enzyme  and  pathway  selections.
Here, we review the classes of enzymes most commonly

www.sciencedirect.com

Current Opinion in Biotechnology 2025, 94:103314

4 Food Biotechnology

Table 1

Summary of key enzymes used for biosynthesis of psychedelics.

Enzyme

Source

Notes

Decarboxylase

PsiD

Psilocybe cubensis

RgnTDC

Ruminococcus gnavus

LcTDC

PsmH

GsTDC

CrTDC
SsDDC
HaDDC
PsTDC
LbTDC
EfTDC
TPH1
TPH2
P4H

PsiH
HpaBC
CloA
PsiM
RmNMT
INMT
PaNMT
COMT

LwOMT1
LwOMT5
LwOMT10
LwOMT11
PsiK

Latilactobacillus
curvatus
Streptomyces
griseofuscus
Gelatoporia
subvermispora
Catharanthus roseus
Sus scrufa
Harminia axyridis
Papaver somniferum
Lactobacillus brevis
Enterococcus faecalis
Homo sapiens
Homo sapiens
Xanthomonas
campestris
Psilocybe cubensis
Escherichia coli
Claviceps paspali
Psilocybe cubensis
Rhinella marina
Homo sapiens
Ephedra sinica
Oryza sativa

Lophophora williamsii

Psilocybe cubensis

Monooxygenase

Methyltransferase

Kinase

Tryptophan synthase Tri-100-2-A

Escherichia coli

Q90*-003-1-A
TmAzul

Shown to decarboxylate tryptophan and substituted tryptophans in
E. coli, S. cerevisiae, and A. nidulans
Highly active and promiscuous enzyme in E. coli on substituted
tryptophans
Tdc2 decarboxylates tryptophan, Tdc1 decarboxylates tyrosine,
and L-DOPA in E. coli
Decarboxylates 5-HTP in Streptomyces albus and E. coli. No
activity on tryptophan.
While GsTDC demonstrates poor activity overall, CrTDC shows
improved activity toward 5-HTP, SsDDC activity was highest
toward 5-HTP in E. coli.

Acts on 5-HTP and L-DOPA in E. coli
Decarboxylates tyrosine in E. coli

Needs N- and C-terminal truncations and BH4 regeneration system
in E. coli to produce 5-HTP
Needs W179F mutation and MH4  regeneration system in E. coli to
produce 5-HTP
Made 4-HTP with co-expression of reductase partner PcCPR
First evidence of activity on primary amine, such as tyramine
Monooxygenase involved in the biosynthesis of LA
Production of psilocybin and derivatives thereof in E. coli
Highly active and promiscuous NMT in E. coli
Demonstrated functional N-methyltransferase activity on
tryptamine in E. coli
Demonstrated activity on N-acetylserotonin enabling melatonin
biosynthesis in E. coli
O-methyltransferases involved in mescaline biosynthesis

Reference

[17,20,29]

[39,43]

[40]

[42,44]

[39,45]

[46,47]
[48]

[49,50]
[51–53]
[53–55]
[44,56,57]

[31]
[49]
[21,24]
[19,29,31]
[33]
[32]

[44,58]

[27,28]

Phosphorylates 4-hydroxy group in the synthesis of psilocybin in E.
coli, A. nidulans, and S. cerevisiae
Incorporated a continuous directed evolution platform called
OrthoRep to increase TrpB promiscuity

[19,20,29]

[59]

used  in  the  biosynthesis  of  psychedelics,  with  focus  on
derivatization  post-amino  acid  synthesis.  A  summary  of
enzymes used in the biosynthesis of psychedelics can be
found in Table 1.

Decarboxylase
Aromatic  L-amino  acid  decarboxylases  (AADCs)  are
generally  pyridoxal-5’-phosphate–dependent  enzymes
that  catalyze  the  primary  step  in  the  synthesis  of  natu-
rally  occurring  psychedelics.  AADCs  remove  the  car-
boxylic  acid  group  from  naturally  occurring  aromatic
amino acids, producing respective primary amines in all
aforementioned pathways, except LA [35].

As  mentioned  previously,  PsiD,  an  L-tryptophan  dec-
arboxylase from psilocybin mushrooms, has been studied
extensively  in  the  context  of  tryptamine  biosynthesis
and  has  shown  significant  biosynthetic  promiscuity
tryptophan  decarboxylases
[36,37].  Other  notable

include  RUMGNA_01526  from  human  gut  firmicute
Ruminococcus  gnavus  [38,39] and  Tdc2  from  Latilactoba-
cillus  curvatus  strain  FAM25164  [40].  Decarboxylases
that  natively  accept  5-hydroxytryptophan  (5-HTP)  as
substrate  have  been  studied  for  their  relevance  to
pathways  for  serotonin  synthesis  and  therefore  psyche-
delics such as bufotenine and 5-MeO-DMT. PsmH from
Streptomyces  griseofuscus  has  been  shown  to  selectively
decarboxylate  5-HTP  [41,42].  A  recent  research  article
compared  catalytic  efficiencies  of  Gelatoporia  sub-ver-
mispora  tryptophan  decarboxylase  (GsTDC),  Cathar-
anthus  roseus  tryptophan  decarboxylase  (CrTDC),  and
Sus  scrofa  dopa  decarboxylase  (SsDDC)  on  5-HTP  and
found SsDDC to be the most active [45]. Additionally, a
DOPA  decarboxylase  from  Harminia  axyridis  originally
discovered  for  decarboxylating  L-DOPA  [47],  forming
dopamine,  was  shown  to  specifically  catalyze  5-HTP
over tryptophan [46]. We refer readers to a recent review
article that summarizes efforts to produce serotonin, with

Current Opinion in Biotechnology 2025, 94:103314

www.sciencedirect.com

discussion of decarboxylases from microbes, plants, and
animals [60].

from  Papaver

Two  decarboxylases  relevant  in  the  production  of  phe-
nethylamines  are  (1)  tyrosine  decarboxylases  such  as
PsTDC
from
Lactobacillus brevis, and EfTDC from Enterococcus faecalis
[48–50];  and  (2)  L-DOPA  decarboxylases,  which  have
been  isolated  from  pig  kidney  cells  and  H.  axyr-
idis [47,61].

somniferum,  LbTDC

Hydroxylase/monooxygenase
The addition of a hydroxyl group is another abundantly
studied biocatalytic step in psychedelic biosynthesis and
is  frequently  catalyzed  by  CYPs,  as  introduced  above.
Hydroxylation  of  indolamines  has  attracted  heavy  re-
search  interest,  given  the  commercial  value  of  5-HTP.
Tryptophan  hydroxylases  (TPH)  belong  to  a  family  of
pterin-dependent  aromatic  amino  acid  hydroxylases
(AAAH), which also includes tyrosine and phenylalanine
hydroxylases  [62].  It  is  critical  to  establish  either  a  tet-
rahydrobiopterin
tetrahydromonapterin
(MH4)  cofactor  regeneration  system  while  expressing
mammalian or bacterial AAAHs, respectively. To date, a
mutated and truncated phenylamine hydroxylase (P4H)
from  Xanthomonas  campestris,  and  mutated  TPH1  from
H.  sapiens  have  produced  gram  per  liter  titers  in  re-
combinant  systems  [51,52,55,56].  Recently,  Shi  et  al.
discovered  a  group  of  bacterial  TPHs  capable  of  site-
specific hydroxylation of free tryptophan at the 4, 5, and
6 positions [42]. This opens an alternative route to the de
novo  production  of  natural  psychedelics  such  as  psilo-
cybin, although this has yet to be reported.

(BH4)  or  a

The P450 monooxygenase, PsiH, is the only tryptamine
4-hydroxylase  identified  to  be  involved  in  the  bio-
synthesis  of  psychedelics,  namely,  psilocybin  [17].  As
highlighted  above,  PsiH  has  been  shown  to  be  highly
active in recombinant fungal systems, but it has limited
activity  in  E.  coli  [19,30].  Despite  this  limitation,  sig-
nificant  substrate  promiscuity  has  been  reported,  en-
couraging  efforts  to  produce  a  range  of  nonnatural
psychedelic-inspired compounds [31].

The  most  versatile  class  of  enzymes  for  the  hydroxyla-
tion  of  tyrosine-derived  compounds,  such  as  phenethy-
lamines, is the 4-Hydroxyphenylacetate 3-Hydroxylases
(HpaBC/HpaH).  Unlike  the  pterin-dependent  AAAHs,
these  two-component  oxygenase/reductase  systems,  na-
tive  to  E.  coli  and  Pseudomonas  aeruginosa,  have  been
studied extensively on a range of substrates [49,63–65].

Methyltransferase
The primary amines and hydroxyl groups resulting from
decarboxylation  and  hydroxylation  activities  described
above  serve  as  targets  for  nucleophilic  substitution  by
SAM-dependent  N-methyltransferases  (NMT)  and  O-

Biosynthesis of psychedelics Abrahms, Sen and Jones 5

methyltransferases  (OMT)  [66].  NMTs,  such  as  PsiM
from psilocybin mushrooms [67], INMT from H. sapiens
[32], and RmNMT from Rhinella marina [33], transfer up
to  three  methyl  groups  sequentially  to  primary  amines.
The  substrate  specificity  of  these  NMTs  varies  widely,
with PsiM being very selective for the presence of the 4-
phosphoryloxy group, and INMT and RmNMT showing
significant  promiscuity  toward  a  range  of  indoleamine
substrates. A unique tryptophan NMT from Psilocybe sp.,
TrpM, has also been reported to have activity on a range
of substrates [37,68] but is independent from psilocybin
biosynthesis.  OMTs,  on  the  other  hand,  have  been
studied  from  a  broad  array  of  organisms  and  on  an  ex-
tensive set of substrates, where no universal mechanism
can be established despite high regioselectivity observed
in these enzymes [69].

Other tryptophan and tryptamine-modifying enzymes
In  addition  to  the  enzyme  classes  noted  above,  several
other  classes  of  enzymes  have  found  utility  in  the  de-
velopment  of  psychedelic  and  psychedelic-inspired
compounds.  Of  specific  note  is  PsiK,  the  kinase  re-
sponsible  for  4-position  phosphorylation  in  the  psilo-
cybin biosynthesis pathway as well as the regeneration of
psilocybin  from  psilocin  [17,70,71].  Additionally,  efforts
to  enzymatically  produce  derivatized  tryptophan  and
tryptamine can be leveraged to expand the biosynthetic
capabilities of many psychedelic derivative biosynthesis
efforts [43,72].

Conclusion and future perspective
The  past  decade  has  supported  tremendous  growth  of
the  psychedelics  biosynthesis  field,  from  pathway  elu-
cidation  and  first  proof-of-principle  studies,  through
multiple examples of high titer psychedelics production
and  the  founding  of  multiple  commercial  ventures
looking to make large-scale biosynthesis of psychedelics
a  reality.  Despite  this  growth,  several  technical  and
legislative  hurdles  remain  that  hinder  full-scale  com-
mercial  viability.  Psilocybin  biosynthesis  has  been  the
largest  success  in  this  space,  but  continued  efforts  to
enhance  pathway  flux,  decrease  product  degradation,
and  develop  economic  and  scalable  purification  pro-
cesses are still needed. Despite this, growing motivation
for  new  psychedelic-inspired  mental  health  treatments
will  continue  to  motivate  innovation  in  this  space  for
years to come.

CRediT authorship contribution statement
Zachary  N.  Abrahms:  Conceptualization,  Writing  –  ori-
ginal draft, Writing – review & editing. Abhishek K. Sen:
Conceptualization,  Writing  –  original  draft,  Writing  –
review  &  editing.  J.  Andrew  John:  Conceptualization,
Funding  acquisition,  Supervision,  Writing  –  review  &
editing.

www.sciencedirect.com

Current Opinion in Biotechnology 2025, 94:103314

6 Food Biotechnology

Data Availability

No data were used for the research described in the ar-
ticle.

Declaration of Competing Interest
JAJ is an inventor on multiple patent applications related
to tryptamine biosynthesis. All other authors declare no
conflicts of interest.

Acknowledgements
The authors would like to acknowledge past research funding from PsyBio
Therapeutics. The authors would like to thank Kathryn Jones for providing
helpful comments and edits on the final draft.

References and recommended reading
Papers of particular interest, published within the period of review, have
been highlighted as:

•• of special interest
•• of outstanding interest

1. Nichols DE: Psilocybin: from ancient magic to modern

medicine. J Antibiot 2020, 73:679-686.

2.

Tupper KW, Wood E, Yensen R, Johnson MW: Psychedelic
medicine: a re-emerging therapeutic paradigm. CMAJ 2015,
187:1054-1059.

3. Carhart-Harris R, Giribaldi B, Watts R, Baker-Jones M, Murphy-

Beiner A, Murphy R, Martell J, Blemings A, Erritzoe D, Nutt DJ: Trial
of psilocybin versus escitalopram for depression. N Engl J Med
2021, 384:1402-1411.

4. Davis AK, Barrett FS, May DG, Cosimano MP, Sepeda ND,

Johnson MW, Finan PH, Griffiths RR: Effects of psilocybin-
assisted therapy on major depressive disorder: a randomized
clinical trial. JAMA Psychiatry 2021, 78:481-489.

5.

Fuentes JJ, Fonseca F, Elices M, Farré M, Torrens M: Therapeutic
use of LSD in psychiatry: a systematic review of randomized-
controlled clinical trials. Front Psychiatry 2020, 10:943.

15. Nutt DJ, Hunt P, Schlag AK, Fitzgerald P: The Australia story:

current status and future challenges for the clinical
applications of psychedelics. Br J Pharm 2024,1-10, https://doi.
org/10.1111/BPH.17398

16. Butlen-Ducuing F, Silva F, Silva I, Balabanov P, Thirstrup S:

Applying the EU regulatory framework for the clinical use of
psychedelics. Lancet Psychiatry 2024, 12:7-9.

17. Fricke J, Blei F, Hoffmeister D: Enzymatic synthesis of psilocybin.

Angew Chem Int Ed 2017, 56:12352-12355.

18. Hoefgen S, Lin J, Fricke J, Stroe MC, Mattern DJ, Kufs JE,

Hortschansky P, Brakhage AA, Hoffmeister D, Valiante V: Facile
assembly and fluorescence-based screening method for
heterologous expression of biosynthetic pathways in fungi.
Metab Eng 2018, 48:44-51.

19. Milne N, Thomsen P, Mølgaard, Knudsen N, Rubaszka P,
Kristensen M, Borodina I: Metabolic engineering of
Saccharomyces cerevisiae for the de novo production of
psilocybin and related tryptamine derivatives. Metab Eng 2020,
60:25-36.

20.
•

Janevska S, Weiser S, Huang Y, Lin J, Hoefgen S, Jojić K, Barber
AE, Schäfer T, Fricke J, Hoffmeister D, et al.: Optimized psilocybin
production in tryptophan catabolism-repressed fungi. Micro
Biotechnol 2024, 17:e70039.

Here,  A.  nidulans  was  rationally  engineered  to  improve  tryptophan
availability,  resulting  in  a  10-fold  improvement  in  psilocybin  titer  over
wildtype, reporting a final de novo psilocybin titer of 267 mg/l.

21. Yao Y, Wang W, Shi W, Yan R, Zhang J, Wei G, Liu L, Che Y, An C,
Gao SS: Overproduction of medicinal ergot alkaloids based on
a fungal platform. Metab Eng 2022, 69:198-208.

22. Wong G, Lim LR, Tan YQ, Go MK, Bell DJ, Freemont PS, Yew WS:
Reconstituting the complete biosynthesis of D-lysergic acid in
yeast. Nat Commun 2022, 13:1-10.

23. Hu M, Zhou Y, Du S, Zhang X, Tang S, Yang Y, Zhang W, Chen S,

Huang X, Lu X: Construction of an efficient Claviceps paspali
cell factory for lysergic acid production. Front Bioeng Biotechnol
2023, 10:1093402.

24.
••

Wu N, Yao M, Xiao W-H, Wang Y, Yuan Y-J: Highly efficient
synthesis of lysergic acid using engineered budding yeast.
Green Chem 2024, 26:10330-10343.

LA biosynthesis was enhanced in S. cerevisiae through a series of en-
gineering  approaches,  ultimately  resulting  in  509.9 mg/l  of  LA  in  a 50 l
fed-batch fermentation.

6. Nichols DE: Structure–activity relationships of serotonin 5-HT2A

agonists. Wiley Inter Rev Membr Transp Signal 2012, 1:559-579.

25. Adovasio JM, Fry GF: Prehistoric Psychotropic Drug Use in

Northeastern Mexico and Trans-Pecos Texas. 1976, 30:94–96.

7.

Fricke J, Lenz C, Wick J, Blei F, Hoffmeister D: Production options
for psilocybin: making of the magic. Chem A Eur J 2019,
25:897-903.

26. Lundström J, Agurell S: A complete biosynthetic sequence from

tyrosine to mescaline in two cactus species. Tetrahedron Lett
1969, 10:3371-3374.

8. Nutt MJ, Woolf N, Stewart SG: Overview of the synthetic

approaches to lysergic acid as a precursor to the psychedelic
LSD. Aust J Chem 2023, 76:279-287, https://doi.org/10.1071/
CH23055

9. Sherwood AM, Claveau R, Lancelotta R, Kaylo KW, Lenoch K:

Synthesis and characterization of 5-MeO-DMT succinate for
clinical use. ACS Omega 2020, 5:32067-32075.

10. Li G, Facchini PJ: New frontiers in the biosynthesis of

psychoactive specialized metabolites. Curr Opin Plant Biol 2024,
82:102626.

11. Behera HK, Joga R, Yerram S, Karnati P, Mergu T, Gandhi K, M S,
Nathiya D, Singh RP, Srivastava S, et al.: Exploring the regulatory
framework of psychedelics in the US & Europe. Asian J Psychiatr
2024, 102:104242.

12. Asebey E, O’Reilly J: FDA law and the psychedelic renaissance.

FDLI Update 2024, 2024:23.

13. Siegel JS, Daily JE, Perry DA, Nicol GE: Psychedelic drug

legislative reform and legalization in the US. JAMA Psychiatry
2023, 80:77-83.

14. Rush C: A Growing Number of Oregon Cities Vote to Ban

Psilocybin | AP News. 2024.

27. Watkins JL, Li Q, Yeaman S, Facchini PJ: Elucidation of the

mescaline biosynthetic pathway in peyote (Lophophora
williamsii). Plant J 2023, 116:635-649.

28.
••

Berman P, de Haro LA, Cavaco AR, Panda S, Dong Y, Kuzmich N,
Lichtenstein G, Peleg Y, Harat H, Jozwiak A, et al.: The
biosynthetic pathway of the hallucinogen mescaline and its
heterologous reconstruction. Mol Plant 2024, 17:1129-1150.
The  authors  elucidated  the  final  biosynthetic  step  in  mescaline  bio-
synthesis  and  reconstituted  the  complete  pathway  in  yeast  and  N.
benthamiana;  however,  they  were  unable  to  realize  full  de  novo  pro-
duction in either host despite positive validation of each enzyme in vivo.

29. Adams AM, Kaplan NA, Wei Z, Brinton JD, Monnier CS, Enacopol
AL, Ramelot TA, Jones JA: In vivo production of psilocybin in E.
coli. Metab Eng 2019, 56:111-119.

30. Bao SH, Jiang H, Zhu LY, Yao G, Han PG, Wan XK, Wang K, Song
TY, Liu CJ, Wang S, et al.: A dynamic and multilocus metabolic
regulation strategy using quorum-sensing-controlled bacterial
small RNA. Cell Rep 2021, 36:1-13.

31.
•

Flower JE, Gibbons WJ, Adams AM, Wang X, Broude CN, Jones
JA: Biosynthesis of psilocybin and its nonnatural derivatives by
a promiscuous psilocybin synthesis pathway in Escherichia
coli. Biotechnol Bioeng 2023, 120:2214-2229.

Current Opinion in Biotechnology 2025, 94:103314

www.sciencedirect.com

Biosynthesis of psychedelics Abrahms, Sen and Jones 7

Here, the authors probed the promiscuity of the native psilocybin bio-
synthetic pathway in E. coli with a library of 49 single-substituted indole
substrates.  In  the  end,  they  were  able  to  show  proof-of-principle  pro-
duction of 39 tryptophan derivatives, 35 tryptamine derivatives, and 13
psilocybin derivatives.

32. Friedberg LM, Sen AK, Nguyen Q, Tonucci GP, Hellwarth EB,

Gibbons WJ, Jones JA: In vivo biosynthesis of N,N-
dimethyltryptamine, 5-MeO-N,N-dimethyltryptamine, and
bufotenine in E. coli. Metab Eng 2023, 78:61-71.

33.
••

Chen X, Li J, Yu L, Maule F, Chang L, Gallant JA, Press DJ,
Raithatha SA, Hagel JM, Facchini PJ: A cane toad (Rhinella
marina) N-methyltransferase converts primary
indolethylamines to tertiary psychedelic amines. J Biol Chem
2023, 299:105231.

This  work  summarizes  the  discovery  and  initial  characterization  of  a
highly active N-methyltransferase from R. marina (cane toad). This en-
zyme  was  used  to  produce  multiple  DMT  derivatives  at  purifiable
quantities, which enabled receptor binding and stability studies.

34. Sen AK, Jones JA: Unlocking the biosynthesis of psychedelic-

inspired indolethylamines. Trends Biochem Sci 2024,
49:189-191.

35. Jamieson CS, Misa J, Tang Y, Billingsley JM: Biosynthesis and

synthetic biology of psychoactive natural products. Chem Soc
Rev 2021, 50:6950-7008.

36. Adams AM, Anas NA, Sen AK, Hinegardner-Hendricks JD, O’Dell

PJ, Gibbons WJ, Flower JE, McMurray MS, Jones JA:
Development of an E. coli-based norbaeocystin production
platform and evaluation of behavioral effects in rats. Metab Eng
Commun 2022, 14:e00196.

37. Kanis FC, Broude CN, Hellwarth EB, Gibbons WJ, Sen AK, Adams
AM, Wang X, Jones JA: Evaluation of TrpM and PsiD substrate
promiscuity reveals new biocatalytic capabilities. Biotechnol
Prog 2024, 40:e3492.

38. Williams BB, Van Benschoten AH, Cimermancic P, Donia MS,

Zimmermann M, Taketani M, Ishihara A, Kashyap PC, Fraser JS,
Fischbach MA: Discovery and characterization of gut
microbiota decarboxylases that can produce the
neurotransmitter tryptamine. Cell Host Microbe 2014,
16:495-503.

39. McDonald AD, Perkins LJ, Buller AR: Facile in vitro biocatalytic
production of diverse tryptamines. ChemBioChem 2019,
20:1939-1944.

40.

Irmler S, Bavan T, Binz E, Portmann R: Ability of Latilactobacillus
curvatus FAM25164 to produce tryptamine: identification of a novel
tryptophan decarboxylase. Food Microbiol 2023, 116:104343.

41. Liu J, Ng T, Rui Z, Ad O, Zhang W: Unusual acetylation-
dependent reaction cascade in the biosynthesis of the
pyrroloindole drug physostigmine. Angew Chem Int Ed 2014,
53:136-139.

42.
•

Shi X, Zhao G, Li H, Zhao Z, Li W, Wu M, Du YL:
Hydroxytryptophan biosynthesis by a family of heme-
dependent enzymes in bacteria. Nat Chem Biol 2023,
19:1415-1422.

The authors report a class of tryptophan hydroxylases of bacterial origin,
demonstrate their functional activity in E. coli, and assemble a proof-of-
concept melatonin production pathway.

43.
•

Reed KB, Brooks SM, Wells J, Blake KJ, Zhao M, Placido K,
d’Oelsnitz S, Trivedi A, Gadhiyar S, Alper HS: A modular and
synthetic biosynthesis platform for de novo production of
diverse halogenated tryptophan-derived molecules. Nat
Commun 2024, 15:1-13.

These authors report a comprehensive screening of various tryptophan
halogenases  in  E.  coli  yielding  between  300  and  700 mg/l  of  haloge-
nated product from glucose.

46. Wang Y, Chen X, Chen Q, Zhou N, Wang X, Zhang A, Chen K,
Ouyang P: Construction of cell factory capable of efficiently
converting l-tryptophan into 5-hydroxytryptamine. Micro Cell
Fact 2022, 21:1-9.

47. Gao S, Guo Y, Ma C, Ma D, Chen K, Ouyang P, Wang X:

Characterization and application of a recombinant dopa
decarboxylase from Harmonia axyridis for the efficient
biosynthesis of dopamine. Chin J Chem Eng 2022, 41:449-456.

48. Shen N, Satoh Y, Koma D, Ohashi H, Ogasawara Y, Dairi T:
Optimization of tyrosol-producing pathway with tyrosine
decarboxylase and tyramine oxidase in high-tyrosine-
producing Escherichia coli. J Biosci Bioeng 2024, 137:115-123.

49. Chen W, Yao J, Meng J, Han W, Tao Y, Chen Y, Guo Y, Shi G, He Y,

Jin JM, et al.: Promiscuous enzymatic activity-aided multiple-
pathway network design for metabolic flux rearrangement in
hydroxytyrosol biosynthesis. Nat Commun 2019, 10:1-12.

50. Connil N, Le Breton Y, Dousset X, Auffray Y, Rincé A, Prévost H:

Identification of the Enterococcus faecalis tyrosine
decarboxylase operon involved in tyramine production. Appl
Environ Microbiol 2002, 68:3537-3544.

51. Xu D, Fang M, Wang H, Huang L, Xu Q, Xu Z: Enhanced

production of 5-hydroxytryptophan through the regulation of L-
tryptophan biosynthetic pathway. Appl Microbiol Biotechnol
2020, 104:2481-2488.

52. Shen B, Zhang L, Zhou Y, Song F, You S, Su R, Qi W: Efficient
synthesis of 5-hydroxytryptophan in Escherichia coli by
bifunctional utilization of whey powder as a substrate for cell
growth and inducer production. J Biotechnol 2024, 393:100-108.

53. Wang H, Liu W, Shi F, Huang L, Lian J, Qu L, Cai J, Xu Z: Metabolic

pathway engineering for high-level production of 5-
hydroxytryptophan in Escherichia coli. Metab Eng 2018,
48:279-287.

54. Luo H, Schneider K, Christensen U, Lei Y, Herrgard M, Palsson BØ:
Microbial synthesis of human-hormone melatonin at Gram
scales. ACS Synth Biol 2020, 9:1240-1245.

55. Zhang Z, Yu Z, Wang J, Yu Y, Li L, Sun P, Fan X, Xu Q: Metabolic
engineering of Escherichia coli for efficient production of L-5-
hydroxytryptophan from glucose. Micro Cell Fact 2022, 21:198.

56. Lin Y, Sun X, Yuan Q, Yan Y: Engineering bacterial phenylalanine

4-hydroxylase for microbial synthesis of human
neurotransmitter precursor 5-hydroxytryptophan. ACS Synth
Biol 2014, 3:497-505.

57. Wang L, Deng Y, Gao J, Wang B, Han H, Li Z, Zhang W, Wang Y, Fu
X, Peng R, et al.: Biosynthesis of melatonin from l-tryptophan by
an engineered microbial cell factory. Biotechnol Biofuels Bioprod
2024, 17:27.

58. Byeon Y, Back K: Melatonin production in Escherichia coli by
dual expression of serotonin N-acetyltransferase and caffeic
acid O-methyltransferase. Appl Microbiol Biotechnol 2016,
100:6683-6691.

59. Rix G, Watkins-Dulaney EJ, Almhjell PJ, Boville CE, Arnold FH, Liu
CC: Scalable continuous evolution for the generation of diverse
enzyme variants encompassing promiscuous activities. Nat
Commun 2020, 11:5644.

60. Li D, Tan F, Lin CSK, Liu Y, Liu J, Gao C: Advances in the

metabolic engineering of Escherichia coli for the production of
serotonin and its precursor, tryptophan. Biochem Eng J 2024,
208:1-9.

61. Das A, Verma A, Mukherjee KJ: Synthesis of dopamine in E. coli
using plasmid-based expression system and its marked effect
on host growth profiles. Prep Biochem Biotechnol 2017,
47:754-760.

44. Zhang Y, He Y, Zhang N, Gan J, Zhang S, Dong Z: Combining

62. Liu XX, Zhang B, Ai LZ: Advances in the microbial synthesis of 5-

protein and metabolic engineering strategies for biosynthesis
of melatonin in Escherichia coli. Micro Cell Fact 2021, 20:170.

hydroxytryptophan. Front Bioeng Biotechnol 2021, 9:1-6.

63. Sun P, Xu S, Tian Y, Chen P, Wu D, Zheng P: 4-

45. Shen P, Gu S, Jin D, Su Y, Wu H, Li Q, Yang J, He W, Huang J, Qi F:

Engineering metabolic pathways for cofactor self-sufficiency
and serotonin production in Escherichia coli. ACS Synth Biol
2022, 11:2889-2900.

Hydroxyphenylacetate 3-hydroxylase (4HPA3H): a vigorous
monooxygenase for versatile O-hydroxylation applications in
the biosynthesis of phenolic derivatives. Int J Mol Sci 2024,
25:1-24.

www.sciencedirect.com

Current Opinion in Biotechnology 2025, 94:103314

8 Food Biotechnology

64. Xu S, Zheng P, Sun P, Chen P, Wu D: Biosynthesis of 3-

68. Blei F, Fricke J, Wick J, Slot JC, Hoffmeister D: Iterative l-

hydroxyphloretin using rational design of 4-
hydroxyphenylacetate 3-monooxygenase. J Agric Food Chem
2023, 71:19457-19464.

65. Jones JA, Collins SM, Lachance DM, Vernacchio VR, Koffas MAG:
Optimization of naringenin and p -coumaric acid hydroxylation
using the native E. coli hydroxylase complex, HpaBC.
Biotechnol Prog 2016, 32:21-25.

66. Bennett MR, Shepherd SA, Cronin VA, Micklefield J: Recent

advances in methyltransferase biocatalysis. Curr Opin Chem
Biol 2017, 37:97-106.

tryptophan methylation in psilocybe evolved by subdomain
duplication. ChemBioChem 2018, 19:2160-2166.

69. Wang J, Liao N, Liu G, Li Y, Xu F, Shi J: Diversity and

regioselectivity of O-methyltransferases catalyzing the
formation of O-methylated flavonoids. Crit Rev Biotechnol 2023,
44:1203-1225, https://doi.org/10.1080/07388551.2023.2280755

70. Rogge K, Wagner TJ, Hoffmeister D, Rupp B, Werten S: Substrate

recognition by the 4-hydroxytryptamine kinase PsiK in
psilocybin biosynthesis. FEBS Lett 2024, 599:447-455, https://
doi.org/10.1002/1873-3468.15042

67.
•

Hudspeth J, Rogge K, Dörner S, Müll M, Hoffmeister D, Rupp B,
Werten S: Methyl transfer in psilocybin biosynthesis. Nat
Commun 2024, 15:1-14.

In this work, the authors present an in-depth study of the terminal me-
thyltransferase in psilocybin biosynthesis. Their analysis sheds light on
the mechanism of action and substrate binding, ultimately leading to a
better  functional  understanding  of  PsiM,  which  can  inform  future  en-
zyme engineering efforts.

71. Fricke J, Kargbo R, Regestein L, Lenz C, Peschel G, Rosenbaum
MA, Sherwood A, Hoffmeister D: Scalable hybrid synthetic/
biocatalytic route to psilocybin. Chemistry 2020, 26:8281.

72. Milne N, Sáez-Sáez J, Nielsen AM, Dyekjær JD, Rago D, Kristensen

M, Wulff T, Borodina I: Engineering Saccharomyces cerevisiae
for the de novo production of halogenated tryptophan and
tryptamine derivatives. ChemistryOpen 2023, 12:1-10.

Current Opinion in Biotechnology 2025, 94:103314

www.sciencedirect.com

