Contents lists available at ScienceDirect

Metabolic Engineering

journal homepage: www.elsevier.com/locate/meteng

Repurposing plant hormone receptors as chemically-inducible genetic
switches for dynamic regulation in yeast

Shuang Wei a, Mengwan Li b, Xuye Lang b, 1, Nicholas R. Robertson b, Sang-Youl Park c, Sean
R. Cutler c, d, Ian Wheeldon b,d, e, *
a Biochemistry and Molecular Biology, University of California, Riverside, Riverside, CA, USA
b Chemical and Environmental Engineering, University of California, Riverside, Riverside, CA, USA
c Botany and Plant Sciences, University of California, Riverside, Riverside, CA, USA
d Institute for Integrative Genome Biology, University of California, Riverside, Riverside, CA, USA
e Center for Industrial Biotechnology, University of California, Riverside, Riverside, CA, USA

A B S T R A C T

Precise control of gene expression is critical for optimizing cellular metabolism and improving the production of valuable biochemicals. However, hard-wired ap-
proaches  to  pathway  engineering,  such  as  optimizing  promoters,  can  take  time  and  effort.  Moreover,  limited  tools  exist  for  controlling  gene  regulation  in  non-
conventional hosts. Here, we develop a two-channel chemically-regulated gene expression system for the multi-stress tolerant yeast Kluyveromyces marxianus and
use it to tune ethyl acetate production, a native metabolite produced at high titers in this yeast. To achieve this, we repurposed the plant hormone sensing modules
(PYR1ABA/HAB1  and  PYR1*MANDI/HAB1*)  for  high  dynamic-range  gene  activation  and  repression  controlled  by  either  abscisic  acid  (ABA)  or  mandipropamid
(mandi). To redirect metabolic flux towards ethyl acetate biosynthesis, we simultaneously repress pyruvate dehydrogenase (PDA1) and activate pyruvate decar-
boxylase (PDC1) to enhance ethyl acetate titers. Thus, we have developed new tools for chemically tuning gene expression in K. marxianus and S. cerevisiae that
should be deployable across many non-conventional eukaryotic hosts.

1. Introduction

Metabolic  engineering  seeks  to  harness  native  and  heterologous
pathways  for  the  high  titer,  rate,  and  yield  production  of  chemicals.
Central  to  this  is  the  ability  to  manipulate  gene  expression.  Pathway
refactoring  using  promoters  and  terminators  of  known  strength,
knockout of competing pathways, and overexpression of bottleneck re-
action steps are common approaches to enhance the biosynthesis of a
desired  metabolite.  While  these approaches  are  very  often  successful,
they impose static changes on the host cell, which leads to the need for a
large set of strains to test multiple conditions. Permanent changes to the
genetics of the production host can also be detrimental to cell fitness and
prevent the ability to separate growth and product production phases.
Dynamic regulation, where gene expression patterns can be altered on
cue  and  at  a  desired  level,  can  help  overcome  these  challenges,  ulti-
mately  reducing  the  number  of  strains  needed  for  optimization  and
enabling  process  strategies  that  maximize  metabolic  production,  for
example, by separating biomass and production phases or by enabling
the  accumulation  of  substrate  pools  before  redirecting  them  to  the

product pathway.
Starting  with

the

lactose-sensing

lac  repressor,  metabolite-
responsive  circuits  (e.g.,  transcriptional  regulators,  two-component
systems,  riboswitches,  nuclear  hormone  receptors,  and  others
(Cameron et al., 2014; Kis et  al., 2015; McIsaac et  al., 2013; Sanford
et al., 2022; Wittmann and Suess, 2012)) have been modified to create
complex chemically controlled genetic responses in yeast, bacteria, and
mammalian cell lines (Arita et al., 2021; Li et al., 2022; Meyer et al.,
2019). These systems are robust but provide a limited palette of con-
trolling  ligands,  many  of  which  are  too  costly  for  use  in  commercial
applications  or  have  undesirable  pharmacological  activity.  In  yeast,
inducible  systems  that  rely  on  changes  in  carbon  source  or  media
composition (e.g., galactose- and copper-inducible expression (Mascor-
ro-Gallardo et al., 1996; Yocum et al., 1984)) are also widely used, but
these systems can introduce physiological changes and are not suitable
for use at scale. New regulatory systems controlled by process-friendly
ligands would facilitate dynamic regulation in commercial settings.

The plant stress hormone abscisic acid (ABA) is a non-toxic molecule
that has been harnessed to engineer ABA-regulated circuits (Jones et al.,

* Corresponding author. Chemical and Environmental Engineering, University of California, Riverside, Riverside, CA, USA.

E-mail address: wheeldon@ucr.edu (I. Wheeldon).

1  Current institution: ZJU-Hangzhou Global Scientific and Technological Innovation Center, No.733 Jianshe San Road, Xiaoshan District, Hangzhou, Zhejiang,

China, 311,200.

https://doi.org/10.1016/j.ymben.2024.03.006
Received 20 December 2023; Received in revised form 28 February 2024; Accepted 25 March 2024

MetabolicEngineering83(2024)102–109Availableonline29March20241096-7176/©2024TheAuthors.PublishedbyElsevierInc.onbehalfofInternationalMetabolicEngineeringSociety.ThisisanopenaccessarticleundertheCCBY-NC-NDlicense(http://creativecommons.org/licenses/by-nc-nd/4.0/).S. Wei et al.

2019; Liang et al., 2011). ABA is perceived by the soluble receptor PYR1
(Pyrabactin  resistance  1),  which  forms  a  stable  heterodimer  with  its
coreceptor HAB1 (Homolog of ABA insensitive 1) in response to ABA (Park
et  al.,  2009).  The  PYR1ABA-HAB1  system  has  several  advantages  for
engineering dynamic regulation. It has a malleable binding pocket that
can be mutationally reprogrammed to bind a wide range of chemicals
with high affinity, including the low-cost agrochemical mandipropamid,
various  herbicides,  organophosphate  pesticides,  and  natural  and  syn-
thetic cannabinoids (Beltr´an et al., 2022; Park et al., 2015; Zimran et al.,
2022). Thus, the PYR1ABA system enables designing processes controlled
by user-specified, industry-friendly molecules. A second benefit of this
system is a recently developed orthogonal PYR1*MANDI-HAB1* that can
operate  independently  from  the  wild-type  module.  The  PYR1*MANDI--
HAB1*  module  can  also  be  reprogrammed  to  bind  new  ligands  and
enable multi-input, multi-output genetic circuits (Park et al., 2023).

The  PYR1ABA/HAB1  system  provides  general-purpose  modules  for
constructing  dynamic  regulatory  systems  across  biological  kingdoms;
this  portability  opens  new  possibilities  for  metabolic  engineering,
particularly  in  non-conventional  hosts  that  lack  extensive  dynamic
regulation systems. Realizing this utility requires developing repressible
and inducible systems to control metabolite flux and direct carbon to-
ward desired precursors and products. In this work, we address the need
for  chemically-regulated gene  regulation  systems  in non-conventional
microbial  hosts  by  adapting  the  PYR1ABA-HAB1  and  PYR1*MANDI-
HAB1* systems for use in the multi-stress tolerant yeast Kluyveromyces
marxianus.  We  demonstrate  the  utility  of  these  dynamic  regulation
systems by using them to optimize carbon flux to ethyl acetate (EA), a
native K. marxianus metabolite with commercial value as a solvent and
flavoring agent.

2. Results and discussion

Strains of K. marxianus are known to natively produce high levels of
EA, an industrial solvent and flavoring agent (L¨obs et al., 2016; L¨oser
et  al.,  2015).  In  K.  marxianus,  EA  synthesis  is  accomplished  by  the
alcohol acetyltransferase EAT1 (Kruis et al., 2017; L¨obs et  al., 2018),
which condenses ethanol and an acetyl group from acetyl-CoA to pro-
duce EA (Fig. 1a). Precursors to this reaction are derived from pyruvate;
Pdc1  converts  pyruvate  to  acetaldehyde,  which  is  subsequently  con-
verted to ethanol via alcohol dehydrogenase activity, while acetyl-CoA
is  produced  via  the  pyruvate  dehydrogenase  complex  (Pdh;  Pda1  in
particular) or via the Acs1/2 conversion of acetate to acetyl-CoA. In a
previous  study,  we  demonstrated  that  repressing  the  TCA  cycle  and

down-regulating  the  electron  transport  chain  redirects  carbon  flux  to
ethanol and acetyl-CoA and subsequently to EA by Eat1 activity (L¨obs
et  al.,  2018).  The  CRISPRi  repression  approach  that  we  took  to
demonstrate this required a relatively large number of strain engineer-
ing steps, the repression conditions were fixed at a single level, and the
strategy could only be activated from the outset of the cultures. PYR1-
ABA-HAB1 genetic circuits enable a dynamic approach to fine-tune gene
expression  around the  pyruvate  node  (Fig.  1b). Genetic  circuits regu-
lated by low-cost molecules (i.e., ABA and mandipropamid) also enable
the separation of biomass production and product formation stages.

PYR1-based  chemically  regulated  activation  circuits  in  Saccharo-
myces cerevisiae exploit a yeast-two-hybrid approach with multiple split
DNA binding and activation domains (DBDs and ADs) fused to PYR1 and
HAB1  respectively  (Beltr´an  et  al.,  2022;  Park  et  al.,  2023).  Before
deploying  this  system  in  K.  marxianus,  we  investigated  the  effects  of
different  circuit  architectures  and  DBDs  on  circuit  function  in
S.  cerevisiae  (Fig.  S1).  We  first  tested  the  activation  of  a  report  gene
(EGFP) with alternative AD-PYR1*MANDI  and DBD-HAB1* fusions that
swap the architecture and found that all construct designs were func-
tional  but  that  the  lowest  background  and  highest  fold-change  were
achieved  using  the  DBD-PYR1*MANDI/AD-HAB1*  configuration  (here,
the AD was VP64 (Jonker et al., 2005) and the DBD was Z4 (McIsaac
et al., 2013)). We next explored different DBDs and found that Z4, EP
(Weber et al., 2002), LexA (Wade et al., 2005), and ATAF1 (Naseri et al.,
2017) fusions to PYR1* were all functional, indicating multiple DBDs
can be used (Fig. S2).

Given the success in S. cerevisiae, we ported the PYR1*MANDI/HAB1*
circuit to K. marxianus (Fig. 2a). We first tested to see if ABA or mandi
was  toxic  to  K.  marxianus.  No  negative  growth  effects  were  observed
with up to 100 μM of each ligand and 200 μM combined of ABA and
mandi (Fig. S3). Reporter gene expression (EGFP) was first tested using
the synthetic promoter Z44-ScCYC1core, but we sought to optimize cir-
cuit function by testing a series of K. marxianus core promoters (150 bp
upstream of the start codon) previously tested in our lab. We found that
a  synthetic  Z44-HTB1core  promoter  (histone  B1)  achieved  the  highest
fold-change with nM responsiveness to mandipropamid (Fig. 2b and c).
The series of tested core promoters ranged in expression level; HTB1 was
the  strongest  of  the  set  (Lang  et  al.,  2020).  Of  the  weaker  promoters
(SSA3, INU1, PIR1, and PST1) only SSA3 produced a functional circuit,
while all medium strength promoters produced at least a 2-fold response
in the presence of activating ligand.

To develop a chemically regulated repression system, we tested if a
repression domain could substitute for the activation domain in VP64-

Fig.  1. Dynamic  regulation  of  carbon  flux  around  the  pyruvate  metabolic  node  for  increased  ethyl  acetate  production  in  K.  marxianus.  (a)  Metabolic
pathway for ethyl acetate (EA) biosynthesis in K. marxianus. Increased pyruvate flux to acetaldehyde via PDC1 activation increases ethyl acetate precursor con-
centrations, while repression of PDA1, which is part of the pyruvate dehydrogenase complex, reduces pyruvate flux to the TCA cycle. (b) PYR1-based genetic switches
for gene activation and repression. The PYR1ABA-HAB1 chemical-induced dimerization module responsive to the plant hormone ABA activates PDC1 expression. The
PYR1*MANDI-HAB1* module responds to the agrochemical mandipropamid (mandi) and operates orthogonally to PYR1ABA-HAB1 to repress PDA1 expression.

MetabolicEngineering83(2024)102–109103S. Wei et al.

Fig. 2. PYR1-based gene activation in K. marxianus. (a) Genetic circuit design of the PYR1*MANDI/HAB1* activation system and reporter gene in K. marxianus.
The genetic circuit and reporter gene were separately expressed from low copy plasmids, pKmCEN/ARS (L¨obs et al., 2017) with URA3 or HIS3 auxotrophic markers
(here indicated as pKm). Four Z4 DNA binding sequence repeats (Z44) act as an upstream activating sequence (UAS) for the reporter gene core promoter. (b) Fold
change in EGFP fluorescence from various core promoters (Pcore) when activated with 100 μM mandi. Fluorescence from each condition was measured by flow
cytometry. Bars represent the mean, and data points for each replicate are shown. Core promoters are K. marxianus sequences except for ScCYC1, which is native to
S. cerevisiae. (c) Response function with the HTB1 core promoter with mandi concentration ranging from 0.1 nM to 100 μM. Data from two biological replicates is
C, 990 rpm plate shaking. Activating ligand was
shown. Fluorescence measurements were taken 12 h after induction with the relevant mandi concentration, 30
added at the outset of the culture.

◦

HAB1*.  Six  well-characterized  S.  cerevisiae  repressors  were  tested  for
activity  in  K.  marxianus  (TUP1,  HDT1,  RPD,  MBD2B,  ACR1,  and  HST
(Boeke et al., 2000; Lee and Ziff, 1999; Rusch´e and Rine, 2001; Varanasi
et al., 1996; Vincent and Struhl, 1992)) in combination with Z4 binding
sites placed at variable positions upstream of a TEF3 K. marxianus pro-
moter  driving  expression  of  a  plasmid-localized  EGFP  reporter  gene.
These experiments determined that positioning four repeats of the Z4
binding  sequence  at  -150  bp  from  the  start  codon  combined  with
TUP1-HAB1*  yielded  maximal  ligand-mediated  reductions  in  EGFP
expression  (Fig.  3a  and  b).  Placing  the  binding  sequence  further

upstream decreased the repression effect; expression was increased in
the  presence  and  absence  of  mandi  and  fold  change  in  expression
decreased from a high at -150 bp to less than 2-fold at -400 bp (Fig. S4).
This  distance-dependent  trend  has  been  observed  in  other  transcrip-
tional repression approaches, including CRISPR interference strategies
in yeast, which is enhanced with dCas9 binding close to the transcrip-
tional start sites (L¨obs et al., 2018; Schwartz et al., 2017a).

Given  the  success  of  the  HTB1  promoter  for  activation,  we  next
sought  to  test  the  optimal repression  architecture  (-150 Z44  + TUP1-
HAB1*  + Z4-PYR1*MANDI)  with  this  promoter  and  found  that  the

Fig. 3. PYR1-based gene repression in K. marxianus. (a) A Z4-PYR1*MANDI/TUP1-HAB1* system was used to repress the expression of EGFP. Four repeats of the Z4
DNA binding sequence (Z44) were inserted at various locations into the TEF3 promoter; fluorescence was measured in the presence and absence of mandi (0 μM, solid
blue bars; 100 μM open blue bars). The optimal insertion location (-150 bp from the start codon) was tested in TEF3 and HTB1 promoters. (b) A series of repression
domains  were  tested  using  the  PYR1*MANDI/HAB1*  repression  system  with  a  TEF3  promoter  modified  with  the  Z44  binding  sequence  at  -150  bp  driving  the
expression of EGFP. (c) EGFP expression with the optimal repression circuit configuration (Z4-PYR1*MANDI/TUP1-HAB1* + HTB1550(Z44)HTBcore). Data in (a), (b),
and (c) were generated with all components expressed from plasmids with a pKmCEN/ARS backbone (see Table S2). PYR1*MANDI/HAB1* were expressed from one
plasmid, while the reporter gene was expressed from a separate plasmid, each with a unique auxotrophic marker. (d) Simultaneous activation and repression in
K. marxianus. The genetic circuit design of the PYR1ABA/HAB1 activation circuit and PYR1*MANDI/HAB1* repression circuit with fluorescent protein reporter genes.
The PYR1ABA/HAB1 and PYR1*MANDI/HAB1* components were expressed from plasmids, each with a different auxotrophic marker as indicated. The reporter genes
were expressed from expression cassettes integrated into the genome of K. marxianus CBS6556. The addition of ABA activated EGFP expression and the addition of
mandi repressed mCHERRY expression; both circuits respond with nM sensitivity. Fluorescence measurements were taken 12 h after induction with the relevant
ligand  concentration.  Both  ligands  were  added  to  cultures  grown  at  30
C,  990  rpm  plate  shaking.  Fluorescence  from  each  condition  was  measured  by  flow
cytometry. Bars represent the mean, and data points for each replicate are shown (n = 3).

◦

MetabolicEngineering83(2024)102–109104S. Wei et al.

repression fold change was enhanced; maximal repression with HTB1
yielded  a  22-fold  reduction  in  EGFP  expression  at  saturating  ligand
concentrations with a low nanomolar EC50 (Fig. 3c).

With an optimized repression system in hand, we next set out to test
whether gene activation and repression could function simultaneously.
To  do  so,  we  integrated  EGFP  and  mCHERRY  reporter  genes  into
genomic landing sites (Li et al., 2021) and expressed an ABA-responsive
PYR1-activation circuit and a mandi-responsive PYR1*-repression cir-
cuit  from  separate  plasmids  (Fig.  3d).  The  circuits  functioned  as  ex-
pected, activating EGFP expression and repressing mCHERRY expression
by 19- and 32-fold, respectively.

The tandem PYR1-based activation and repression systems provide
an  opportunity  for  the  dynamic  control  of  chemical  biosynthesis  in
K.  marxianus.  Known  for  its  high  native  capacity  to  produce  EA,  we
sought  to  test  this  ability  to  redirect  carbon  flux  to  EA  precursors  in
K. marxianus. To do this, we replaced the native promoter of PDC1 with
(EP4)HTB1core, which is activated by EP-PYR1ABA/VP64-HAB1 upon the
addition  of  ABA.  We  also  replaced  the  native  PDA1  promoter  with
HTB1550(Z44)HTB1core  for repression with mandi (Fig. 4a) to create a
K.  marxianus  strain  (called  dynKm)  for  dynamic  control  of  gene
expression. A chemical refactoring experiment using three levels of in-
duction and repression revealed that the expression level of both genes
could be effectively modulated with up to 21-fold activation of PDC1
and 17-fold repression of PDA1 (Fig. S5). This experiment tested ABA
and mandi inducer levels corresponding to low, intermediate, and high
expression or repression by adding 0, 1, and 10 μM of ABA and mandi.
Given  the  essential  role  that  Pda1  plays  in  aerobic  metabolism,  we
anticipated  that  substantial  repression  of  this  gene  would  limit  cell
growth. This proved true, as PDA1 repression with 1 and 10 μM mandi
resulted in cultures with cell densities, almost half that achieved with no
or low repression (Fig. S6). Given this, we limited the repression of PDA1
in EA optimization experiments to 1 μM or less while using the full range
of ABA-induced activation of PDC1.

The  3-level  refactoring  experiment  with  the  reduced  repression
range  for  PDA1  revealed  that  EA  biosynthesis  was  significantly
enhanced  with  partial  PDA1  repression  and  full  activation  of  PDC1
(Fig.  4b).  This  condition,  however,  also  resulted  in  increased  ethanol
over  the  unregulated  condition,  indicating  an  imbalance  in  EA  pre-
cursors. Given this, we sought to explore a finer range of transcriptional
conditions. Using the activation and repression circuit response curves
as a guide, we estimated the ligand concentrations necessary to create a
series of conditions that increase by ~10% activation or repression at
each step. With the addition of 5.36 μM ABA and the addition of 0.35 μM
(cid:0) 1
mandi, EA biosynthesis was increased to more than 132 mg L
(Fig. 4c), a 4.4-fold increase over the baseline strain in the absence of
ABA and mandi-induced gene regulation.

(cid:0) 1  OD

Our dynamic regulation strategy seeks to redirect pyruvate flux away
from  the  TCA  cycle  and  toward  acetaldehyde  via  Pdc1  activity.  We
hypothesize  that  this  strategy  will  increase  ethanol  biosynthesis  and
balance EA precursors to maximum production; however, there is the
possibility that this strategy will instead lead to an increase in the acetyl-
CoA pool as acetaldehyde can be converted to acetate and subsequently
to acetyl-CoA via acetyl-CoA synthetase activity encoded by ACS1 and
ACS2 (Sakihama et al., 2019). To test this, we created single knockouts
of ACS1 and ACS2 in the dynKm strain and subjected the mutant strains
to the 3-level chemical refactoring experiment (Fig. 5a). These optimi-
zation  experiments  yielded  results  similar  to  those  conducted  with
functional  ACS1  and  ACS2;  EA  production  was  maximized  with  full
PDC1 activation and partial repression of PDA1. This suggests that our
initial  hypothesis  was  correct  –  redirecting  pyruvate  flux  to  acetalde-
hyde leads to increased ethanol production and, consequently, increased
EA. Disrupting ACS1 and ACS2 likely reduced the available acetyl-CoA
pool as total EA production from these strains was reduced compared
to dynKm with functional acetyl-CoA synthase activity (Fig. 5b).

With  optimized  induction  and  repression  levels  in  hand,  we  next
sought to test the timing of the dynamic regulation strategy. EA exhibits

Fig. 4. Chemical control of pyruvate flux to ethyl acetate precursors and increases ethyl acetate biosynthesis. (a) Genetic circuit design for the activation of
PDC1 and repression of PDA1 in the K. marxianus CBS6556 strain dynKm. PYR1ABA and PYR1*MANDI-based genetic switches were expressed from CEN/ARS low-copy
plasmids (pKm). The native promoters for PDC1 and PDA1 were replaced with synthetic HTB1 promoters with EP upstream activation (PDC1) and Z4 upstream
(cid:0) 1  with com-
repression sequences (PDA1) based on designs optimized in Figs. 2 and 3. (b) Specific titer of ethyl acetate (EA; left) and ethanol (right) in g L1  OD
binations of ABA-induced activation of PDC1 and mandi induced repression of PDA1. ABA induction concentrations are shown on the x-axis, while the concentration
of mandi for each set of ABA inductions is indicated for each pair of EA and ethanol measurements. (c) Optimization of ABA and mandi induction conditions to
maximize EA biosynthesis. The heat map shows EA-specific titer with ABA ranging from 1 to 10 μM and mandi from 0.1 to 1 μM. Metabolite measurements (b and c)
◦
were acquired after 20 h of cultivation at 30
C in a 25 mL SD-U-H medium, 300 rpm shaking. All experiments were performed in biological triplicate. Bars represent
the mean, while error bars represent the standard deviation. The heat map color scale indicates specific EA titers in mg L

(cid:0) 1  OD

(cid:0) 1.

MetabolicEngineering83(2024)102–109105S. Wei et al.

Fig. 5. Pyruvate flux optimization is not affected by acetyl-CoA activity.
(a)  Optimization  of  ABA  and  mandi  induction  conditions  to  maximize  EA
biosynthesis without acetyl-CoA synthetase activity. The heat maps show EA-
specific titer with ABA ranging from 1 to 10 μM and mandi from 0.1 to 1 μM
with K. marxianus CBS 6556 PDC1Δ::EP4-HTB1-PDC1 PDA1Δ::HTB1-Z44-PDA1
ura3Δ his3Δ (indicated here as dynKm). The left-hand heat map was generated
with ACS1 disrupted; the right-hand map with ACS2 disrupted. (b) Comparison
of EA-specific titers achieved with and without functional ACS1 and ACS2 and
induction  conditions  from  the  coarse  and  fine  grain  chemical  refactoring  ex-
periments. Metabolite measurements were acquired after 20 h of cultivation at
◦
30
C in a 25 mL SD-U-H medium with 300 rpm shaking. All experiments were
performed  in  biological  triplicate.  Bars  represent  the  mean,  while  error  bars
represent the standard deviation. The heat map color scale indicates specific EA
titers in mg L

(cid:0) 1  OD

(cid:0) 1.

(cid:0) 1 OD

a growth-dependent production profile (L¨obs et al., 2017); we manip-
ulated  PDC1/PDA1  expression  during  early  exponential  growth  so
cellular  resources  would  be  directed  toward  EA  biosynthesis  when
growth rates are maximal. Activation and repression of PDC1 and PDA1
in  the  early  exponential  phase  (12  h  post-inoculation)  increased  EA
(cid:0) 1. EA titers were 33% higher than when
biosynthesis to 151 mg L
ABA and mandi were added at the outset of the culture and 55% higher
than the uninduced condition (Fig. 6). While EA production was higher
with  dynamic  pyruvate  metabolism  initiated  during  the  exponential
phase, glucose consumption and EA production profile were generally
consistent; glucose consumption approached completion at 24 h, and EA
titers  reached  a  maximum  between  20  and  22  h  post-inoculation.  In
addition, ethanol production was low in all cases. We note that ethyl
acetate production from the wild type strain of K. marxianus CBS6556 is
on  par  with  our  optimized  dynamic  regulation  strategy  (L¨obs  et  al.,
2017), suggesting that further strain engineering (e.g., integration of the
sensor  system)  is  still  needed  prior  to  deploying  this  strategy  in
bioprocesses.

Regulated  transcription  systems  are  core  technological  tools  for
dynamically tuning regulatory network nodes. Our work demonstrates
chemically-mediated  activation  and  repression  of  target  genes  using
simple,  low-cost  inducers  with  the  PYR1ABA/HAB1  and  PYR1*MANDI/
HAB1*  dimerization  systems.  Although  several  systems  for  regulated
transcription have been developed in S. cerevisiae, including the PYR1/
HAB1 system, relatively few have been developed for and validated in
non-conventional yeasts, such as K. marxianus. We see several advan-
tages that our system offers for metabolic engineering. First, the PYR1/

Fig.  6. Time-dependent  dynamic  regulation  of  EA  biosynthesis  in
K.  marxianus.  (a)  Time-course  of  specific  EA  and  ethanol  titers  and  con-
sumption of glucose for various dynamic regulation strategies, including acti-
vation of PDC1 and repression of PDA1 upon inoculation (t = 0 h), at the outset
of  exponential  phase  (t  = 12  h),  and  no  induction  (top,  middle,  bottom,
respectively).  Data  points  represent  the  mean,  while  error  bars  represent  the
standard deviation. In some cases, error bars are within the data points and are
therefore  not  shown.  Growth  data  provided  in  Supporting  Figure  S7.  (b)
Comparison of maximum specific EA titer. Maximum specific titers were ach-
ieved  between  20  and  22  h.  All  experiments  were  performed  in  biological
triplicate: 30
C in 25 mL SD-U-H medium, 300 rpm shaking. Data points are
shown for each replicate; bars represent the mean.

◦

HAB1 scaffolds provide new expression systems controlled by low-cost
chemicals  (ABA,  mandi,  and  others  (Beltr´an  et  al.,  2022;  Park  et  al.,
2023)) that are suitable for use at scale. Both ABA and mandipropamid
are used in industrial agriculture: ABA is used as a fruit ripening agent
and  as  a  means  to  induce  drought  tolerance;  mandipropamid  is  a
fungicide often used on vegetable crops to defend against downy mildew
and Phytophthora blight. These at scale uses provide evidence for their
potential for use in industrial microbial bioprocesses. Second, our work
provides tools for facile chemical tuning  of metabolic nodes, empow-
ering  efforts  to  harness  and  manipulate  the  immense  biochemical  di-
versity  afforded  by  non-conventional  yeasts.  The  tools  created  here
leverage our experience in optimizing PYR1 and PYR1* sensor systems
for  use  in  S.  cerevisiae  and  in  the  plant  species  Arabidopsis  thaliana
(Beltr´an et al., 2022; Park et al., 2023). Adopting these platforms for use
in K. marxianus required the design of new expression constructs that use
species  specific  promoters,  thus  providing  an  example  of  how  these
systems  can  be  adopted  for  use  in  other  non-conventional  yeast  and
industrially relevant eukaryotic metabolic engineering hosts. Third, our
systems  enable  chemical  refactoring  experiments,  which  reduce  the
number of strains needed for optimization and accelerate the explora-
tion of biochemical solution space. Creating new strains, particularly in

MetabolicEngineering83(2024)102–109106S. Wei et al.

non-conventional species, is a bottleneck in our engineering pipelines
that can take weeks. Taken together, the advantages, beneficial char-
acteristics,  and  portability  with  respect  to  host  species,  of  the  PYR1
system makes for a promising platform for engineering dynamic regu-
lation in a broad range of metabolic engineering hosts.

3. Conclusion

We  have  tackled  the  challenge  of  dynamic  gene  regulation  in  the
yeast K. marxianus, aiming to enhance the production of ethyl acetate, a
naturally  occurring  metabolite  of  significant  commercial  interest.  We
developed a two-channel, chemically-regulated gene expression system
that  leverages  plant-derived  PYR1ABA/HAB1  and  PYR1*MANDI/HAB1*
hormone-sensing modules to engineer induction and repression circuits.
We optimized the architectures of these modules and then used them to
control the activity of key EA nodes (PDC1 and PDA1). This approach
allowed us to redirect metabolite flux and improve ethyl acetate titers.
Our ABA and mandipropamid-controlled dual-channel systems function
in both K. marxianus and S. cerevisiae and should function widely across
eukaryotic  hosts,  given  our  use  of  standard  biological  parts.  Our
approach illustrates how dynamic control of gene expression facilitates
metabolic engineering using non-toxic and low-cost molecules deploy-
able at scale.

4. Materials and methods

4.1. Strains, plasmids, and cell culture

All yeast strains and plasmids used in this work are listed in Tables S1
and S2. Notably, S. cerevisiae strain BY4742 ura3Δ his3Δ LeuΔ TrpΔ was
utilized as the base S. cerevisiae strain, while K. marxianus strain CBS
6556  ura3Δ  his3Δ  was  used  as  the  base  K.  marxianus  strain.  Strains
(cid:0) 1 yeast extract, 5 g
without plasmids were grown in YPD media (10 g L
(cid:0) 1 glucose). All yeast
(cid:0) 1 peptone; DB Difco®, Becton-Dickinson, 20 g L
L
strains harboring plasmids with auxotrophic markers were cultured with
synthetic  defined  (SD)  media  minus  the  selective  amino  acid.  For
example, strains containing plasmids with a uracil auxotrophic marker
(cid:0) 1 BD Difco™ Yeast Nitrogen Base
were cultured in SD-U media: 6.7 g L
(cid:0) 1 Yeast Synthetic Drop-
without amino acids (Sigma-Aldrich), 1.92 g L
out Medium Supplements without uracil (Sunrise Science Products), and
(cid:0) 1 D-glucose. K. marxianus and S. cerevisiae strains were grown at
20 g L
◦
30
C. Liquid cell cultures in shake flasks were grown at 300 rpm in a
shaker incubator. Liquid cell cultures in 96 deep-well plate format were
grown at 990 rpm in a shaker incubator.

suspended in 100 μg carrier DNA and 0.2–1 μg of plasmid or linear DNA.
500 mL of transformation mix, which contains 40% polyethylene glycol
3350,  0.1  M  lithium  acetate,  10  mM  Tris-HCl  (pH  7.5),  1  mM  EDTA
disodium salt dihydrate, and 10 mM dithiothreitol, was added and the
solution  was  incubated  at  room  temperature  for  45  min  and  subse-
quently heat shocked at 42
C for 45 min. The transformed cells were
plated on solid SD-U agar plates or the appropriate selective media.

◦

4.3. Molecular cloning and reagents

All primers used in this work are listed in Table S2. All generated
gene construct sequences and plasmid maps are provided as Multimedia
Compenents 1-38. Cloning reagents and restriction enzymes were pur-
chased from New England Biolabs (NEB). All primers for DNA amplifi-
cations were purchased from Integrated DNA Technologies (IDT). The
Q5® High-Fidelity DNA polymerase system was used for DNA amplifi-
cation. NEBuilder® HiFi DNA Assembly Master Mix was used for Gibson
assembly. All PCR products and linearized vectors were fractionated by
agarose  gel  electrophoresis  and  purified  using  a  Zymo  Research  gel
extraction  kit.  All  plasmids  were  propagated  in  E.  coli  TOP10  cells
(Thermo  Fisher  Scientific),  and  plasmid  extractions  were  performed
with  the  Zymo  Research  plasmid  miniprep  kit.  All  g-block  DNA  frag-
ments used in this work are provided in Table S5.

4.4. Dual K. marxianus reporter strain

A single K. marxianus strain with two fluorescent reporter genes was
constructed to investigate simultaneous activation and repression. EGFP
was used as a reporter for repression, while mCHERRY was used as a
reporter  for  activation.  The  activation  report  expression  cassette
(HBT1550-Z44-HTB1core-EGFP-CYC1t) was inserted into the K. marxianus
genome at the ABZ1 locus using CRISPR-mediated integration (Li et al.,
2021;  Schwartz  et  al.,  2017b).  The  repression  reporter  cassette
(EP4-HTB1core-mCHERRY-CYC1t) was subsequently integrated into this
strain using the same procedure. Briefly, a two-plasmid system was used
to integrate each gene. One plasmid encodes 700 bp of up- and down-
stream homology to the integration site ABZ1 locus and the gene to be
integrated;  a  second  plasmid  expresses  CAS9  and  cognate  sgRNA.
Co-transformed cells are outgrown and plated on selective media, with
PCR screening to confirm reporter gene integration. K. marxianus strain
CBS  6556  abz1::EGFP  ura3Δ  his3Δ  was  created  using  pIW1134  and
pIW1135.  CBS  6556  abz1::EGFP  ura3::mCHERRY  his3Δ  was  created
using pIW1123 and pIW1124.

4.2. Yeast transformation

4.5. PDA1 and PDC1 dynamic regulation strain

◦

For K. marxianus, a single colony was picked and grown in 2 mL YPD
for  16  h  at  30
C.  One  milliliter  of  cell  culture  was  harvested  by
centrifugation at 5000g for 2 min. The supernatant was removed, and
the pellet was washed with an equal volume of sterile ddH2O. Pelleting
and  washing  were  repeated  twice  before  moving  forward  with  the
transformation protocol. Washed cell pellets were suspended in 100 μg
salmon sperm carrier DNA (R&D Systems™  Salmon Sperm DNA) and
0.2–1 μg of DNA. Five hundred milliliters of transformation mix con-
taining 40% polyethylene glycol 3350 (Fisher Scientific), 0.1 M lithium
acetate, 10 mM Tris-HCl (pH 7.5), 1 mM EDTA disodium salt dihydrate
(Sigma-Aldrich)  and  10  mM  Dithiothreitol  (Fisher  Scientific),  was
added. The solution was incubated at room temperature for 15 min and
subsequently heat shocked at 48
C for 15 min. The transformed cells
were  plated  on  solid  selective  media  (e.g.,  SD-U  for  URA3  markered
plasmids).

◦

For S. cerevisiae, a single colony was picked and grown to stationary
phase in YPD and then diluted to a 1:50 ratio in YPD and grown for 4–6
h. Cells were harvested by centrifugation at 4000g for 10 min. An equal
volume of sterile ddH2O was used to wash cells twice. The cell pellet was

The approach to creating a strain with inducible activation of PDC1
and repression of PDA1 was based on the CRISPR-mediated gene inte-
gration strategy described in section 4.4. Briefly, sgRNAs targeting the
first 700 bp of each gene’s promoter region were designed using CCTop
and CRISPRater (https://crispr.cos.uni-heidelberg.de/)  (Labuhn et  al.,
2018;  Stemmer  et  al.,  2015).  The  top  predicted  sgRNAs  were  each
inserted  into  a  PspXI  linearized  K.  marxianus  CRISPR-Cas9  vector,
pIW601  by  Gibson  cloning  (see  Table  S3  for  all  sgRNAs  used  in  this
work).  The  repair  plasmids,  one  for  PDA1  and  a  second  for  PDC1,
encoded an integration cassette with 700 bp homology to the upstream
promoter region (-1400 to -700 bp), and 700 bp homology to the coding
sequence  beginning  at  the  transcriptional  start  site  (pSW267  and
pSW300). The homology donor regions were assembled into SacII and
XhoI  digested  pIW1135.  Using  sgRNAs  targeting  PDA1  and  a  PDA1
repair  plasmid,  TEF1550-EP4-HTB1core,  replaced  the  native  PDA1  pro-
moter. Using sgRNAs targeting PDC1 and a PDC1 repair template, the
synthetic  promoter  Z44-HTB1core  replaced  the  native  PDC1  promoter.
The  genotype  of  K.  marxianus  CBS  6556  PDA1::Z44-PDA1  PDC1::
EP4-PDC1 ura3Δ his3Δ was confirmed by Sanger sequencing.

MetabolicEngineering83(2024)102–109107S. Wei et al.

4.6. Chemical refactoring of PDA1 and PDC1 expression

◦

Single colonies were inoculated into 2 mL SD-U-H in a 14-mL culture
tube (USA Scientific, Orlando, FL, USA) and grown at 30
C, 300 rpm
overnight in a Multitron Pro shaker incubator (INFORS HT, Bottmingen,
Switzerland). The overnight cultures were diluted 1:500 into 25 mL SD-
U-H and grown at 30
C, 300 rpm. Ethyl acetate production was first
measured after culturing in all combinations of mandipropamid (0, 0.1,
and 1 μM) and ABA (0, 1, and 10 μM). The next search was performed by
dividing the concentration range with higher ethyl acetate production
into  6  groups.  All  combinations  of  0.1,  0.23,  0.35,  0.39,  0.47,  1  μM
mandipropamid, 1, 1.43, 2.46, 3.74, 5.36,10 μM ABA were tested.

◦

4.7. Construction of PYR1-based activation and repression circuits

All PYR1-based genetic circuits were built using previously described
parts validated in S. cerevisiae (Beltr´an et al., 2022; Park et al., 2023).
Briefly,  PYR1ABA/HAB1  and  PYR1*MANDI/HAB1*  expression  cassettes
were  amplified  from  previously  described  constructs  and  assembled
using a combination of Gibson assembly and conventional cloning into
K.  marxianus  expression  vectors  (pRS426  backbone).  The  tested
repression domains that enabled a repression circuit (TUP1, HDT1, RPD,
MBD2B,  ACR1,  HST,  and  MXI1)  were  amplified  from  S.  cerevisiae
genomic material and cloned into the HAB1* expression cassette after
digestion with Eag 1/Ale 1. Upstream repressing positions (-150, -200,
-400, and -700 bp from the translational start site) were selected based
on core promoter design (150 bp) and increasing distances upstream,
exploring up to 700 bp from the start site. All plasmid sequences are
provided in Multimedia Components 2-38.

4.8. Flow cytometry analysis of cellular fluorescence

Three single transformants were used to inoculate 2 mL SD-U media
cultures  containing  2%  glucose  and  pre-cultured;  cells  were  then
passaged into wells of a 96-deep-well plate (USA Scientific, Orlando, FL,
USA) in 1 mL media (OD600 = 0.1). Up to 5 μL of ligand stocks (solvated
in DMSO) were added immediately after inoculation, plates sealed with
an AeraSeal film (Excel Scientific, Victorville, CA, USA), and grown at
990  rpm,  and  90  %  humidity  for  12  h.  The  cells  were  harvested  by
centrifuge at 5000 g for 10 min. After discarding the supernatant, the
cells were suspended in 1 mL phosphate-buffered saline (PBS) (Sigma
Aldrich) and centrifuged at 5000 g for 10 min. The cells were washed
twice with 1 mL PBS and suspended in 1 mL DI water for flow cytomety
analysis. BD accuri™ C6 flow cytometer (BD Bioscience) was used for
data collection and analysis. A control cell population without fluores-
cent  protein  expression  was  first  run  to  identify  basal  cell  auto-
fluorescence  before  collecting  data  for  the  experimental  samples.  For
each  sample,  10,000  events  were  collected.  The  forward  scatter,  side
scatter, EGFP fluorescence, and mCHERRY fluorescence were recorded
for each event. All experiments were performed in biological triplicate.

4.9. Metabolite quantification

Ethyl  acetate  (EA)  was  extracted  from  culture  media  with  cyclo-
hexane  (ReagentPlus.,  ≥99%;  Sigma  Aldrich)  and  quantified  by  gas
chromatography. Extraction began with collecting 700 μL media from
24-h cell cultures centrifuged at 5000 g for 10 min 500 μL of the media
was transferred to another tube to which an equal volume of solvent was
added. The two-phase solution was vortexed for 30 min, and 100 μL of
the cyclohexane layer was collected after centrifugation at 10,000 g for
1  min.  Quantification  was  performed  with  a  Shimadzu  GC-2010  Plus
equipped  with  a  Shimadzu  AOC-20s  autosampler,  AOC-20i  auto-
injector, and FID detector. An Agilent J&W DB-WAX Ultra Inert column
(length:  30 m;  inner diameter: 0.32 mm;  film  thickness:  0.5 μm)  was
used  for  separations.  One  microliter  samples  were  injected  and  sub-
◦
jected to a temperature ramp starting at 100
C at

◦
C, increasing to 140

◦

◦
C at 10

◦
C/min, holding at 160

◦
C/min, then increasing to 150

◦
C/min, and finally, increasing to 220

C/min increase, holding again from 2 min at 170
◦
C at 25

◦
C for
20
◦
2 min after at 5
C
◦
C/
after increasing at 1
min. Helium was used as a carrier gas at a flow rate of 1.9 mL/min. Using
these methods, the retention time of EA was determined to be 3.9 min.
EA  quantification  was  aided  by  standard  curves  linking  the  FID  peak
area of EA extracted from SD-H-U media containing 1, 2, 4, 20, and 100
(cid:0) 1 EA subjected to the extraction protocol described above.
mg L
Extracellular glucose and ethanol were quantified by HPLC analysis.
Briefly,  1  mL  of  spent  media  was  collected  from  cell  culture  samples
centrifuged at 5000 g for 10 min. The supernatant was filtered through a
0.2 μm filter (VWD) and analyzed using an Aminex HPX-87H column
(Bio-rad) in an Ultimate 2200 HPLC system (ThermoFisher Scientific).
Eluting  with  0.8  L  min
C,  glucose  had  a
retention time of 3.7 min while ethanol eluted at 7.1 min. Calibration
curves for both compounds were created using a series of SD-H-U so-
(cid:0) 1  of glucose and ethanol
lutions with 10, 50, 100, 200, and 500 mg L
and analyzed as described above.

(cid:0) 1  of  5  mM  H2SO4  at  60

◦

4.10. Reverse transcription quantitative PCR (RT-qPCR)

Total RNA from each strain was extracted using the YeaStar™ RNA
Kit  (Zymo  Research).  RNA  was  treated  with  DNAse  (DNAse  I,  New-
England Biolabs) for 10 min and subsequently extracted using the RNA
Clean  &  Concentrator™-5  Kit  (Zymo  Research).  cDNA  was  obtained
using  theiScript™  Reverse  Transcription  Supermix  for  RT-qPCR  (Bio-
Rad).  SYBR  Green  qPCR  (SsoAdvanced™  Universal  SYBR;  Green
Supermix,  Bio-Rad)  was  used  for  quantification  using  a  Bio-Rad  CFX
Connect™ Real-Time PCR Detection System. All primers are provided in
Table  S4.  Chemically  induced  expression  levels  were  compared using
transcript levels normalized to GAPDH.

CRediT authorship contribution statement

Shuang Wei: Writing –  review &  editing, Writing –  original draft,
Visualization, Validation, Methodology, Investigation, Formal analysis.
Mengwan Li: Writing – review & editing, Methodology, Investigation.
Xuye  Lang:  Writing  –  review  &  editing,  Methodology,  Investigation.
Nicholas R. Robertson: Writing – review & editing, Writing – original
draft,  Visualization,  Validation.  Sang-Youl  Park:  Resources,  Method-
ology. Sean R. Cutler: Writing –  review &  editing, Writing –  original
draft, Supervision, Conceptualization. Ian Wheeldon: Writing – review
&  editing, Writing –  original draft, Visualization, Supervision, Project
administration,  Methodology,  Funding  acquisition,  Formal  analysis,
Conceptualization.

Data availability

Data will be made available on request.

Acknowledgments

This  work  was  supported  by  Defense  Advanced  Research  Projects
Agency Advanced Plant Technologies (DARPA-APT, HR001118C0137),
DOE DE-SC0019093, NSF-1803630, NSF-2128016, and NSF-1922642.
The views, opinions, and/or findings expressed are those of the authors
and should not be interpreted as representing the official views or pol-
icies of the Department of Defense or the U.S. Government. Approved for
Public Release, Distribution Unlimited.

Appendix A. Supplementary data

Supplementary data to this article can be found online at https://doi.

org/10.1016/j.ymben.2024.03.006.

MetabolicEngineering83(2024)102–109108S. Wei et al.

References

Arita, Y., Kim, G., Li, Z., Friesen, H., Turco, G., Wang, R.Y., Climie, D., Usaj, M., Hotz, M.,
Stoops, E.H., Baryshnikova, A., Boone, C., Botstein, D., Andrews, B.J., McIsaac, R.S.,
2021. A genome-scale yeast library with inducible expression of individual genes.
Mol. Syst. Biol. 17, e10207.

Beltr´an, J., Steiner, P.J., Bedewitz, M., Wei, S., Peterson, F.C., Li, Z., Hughes, B.E.,

Hartley, Z., Robertson, N.R., Medina-Cucurella, A.V., Baumer, Z.T., Leonard, A.C.,
Park, S.-Y., Volkman, B.F., Nusinow, D.A., Zhong, W., Wheeldon, I., Cutler, S.R.,
Whitehead, T.A., 2022. Rapid biosensor development using plant hormone receptors
as reprogrammable scaffolds. Nat. Biotechnol. 40, 1855–1861.

Boeke, J., Ammerpohl, O., Kegel, S., Moehren, U., Renkawitz, R., 2000. The minimal
repression domain of MBD2b overlaps with the methyl-CpG-binding domain and
binds directly to Sin3A. J. Biol. Chem. 275, 34963–34967.

Cameron, D.E., Bashor, C.J., Collins, J.J., 2014. A brief history of synthetic biology. Nat.

Rev. Microbiol. 12, 381–390.

Jones, K.A., Kentala, K., Beck, M.W., An, W., Lippert, A.R., Lewis, J.C., Dickinson, B.C.,
2019. Development of a split esterase for protein-protein interaction-dependent
small-molecule activation. ACS Cent. Sci. 5, 1768–1776.

Jonker, H.R.A., Wechselberger, R.W., Boelens, R., Folkers, G.E., Kaptein, R., 2005.

Structural properties of the promiscuous VP16 activation domain. Biochemistry 44,
827–839.

Kis, Z., Pereira, H.S., Homma, T., Pedrigi, R.M., Krams, R., 2015. Mammalian synthetic
biology: emerging medical applications. J. R. Soc. Interface 12. https://doi.org/
10.1098/rsif.2014.1000.

Kruis, A.J., Levisson, M., Mars, A.E., van der Ploeg, M., Garc´es Daza, F., Ellena, V.,

Kengen, S.W.M., van der Oost, J., Weusthuis, R.A., 2017. Ethyl acetate production by
the elusive alcohol acetyltransferase from yeast. Metab. Eng. 41, 92–101.
Labuhn, M., Adams, F.F., Ng, M., Knoess, S., Schambach, A., Charpentier, E.M.,

Schwarzer, A., Mateo, J.L., Klusmann, J.-H., Heckl, D., 2018. Refined sgRNA efficacy
prediction improves large- and small-scale CRISPR-Cas9 applications. Nucleic Acids
Res. 46, 1375–1385.

Lang, X., Besada-Lombana, P.B., Li, M., Da Silva, N.A., Wheeldon, I., 2020. Developing a
broad-range promoter set for metabolic engineering in the thermotolerant yeast.
Metab Eng Commun 11, e00145.

Lee, T.C., Ziff, E.B., 1999. Mxi1 is a repressor of the c-Myc promoter and reverses

activation by USF. J. Biol. Chem. 274, 595–606.

Liang, F.-S., Ho, W.Q., Crabtree, G.R., 2011. Engineering the ABA plant stress pathway

for regulation of induced proximity. Sci. Signal. 4, rs2.

Li, H.-S., Israni, D.V., Gagnon, K.A., Gan, K.A., Raymond, M.H., Sander, J.D., Roybal, K.

T., Joung, J.K., Wong, W.W., Khalil, A.S., 2022. Multidimensional control of
therapeutic human cell function with synthetic gene circuits. Science 378,
1227–1234.

Li, M., Lang, X., Moran Cabrera, M., De Keyser, S., Sun, X., Da Silva, N., Wheeldon, I.,

2021. CRISPR-mediated multigene integration enables Shikimate pathway
refactoring for enhanced 2-phenylethanol biosynthesis in Kluyveromyces marxianus.
Biotechnol. Biofuels 14, 3.

L¨obs, A.-K., Engel, R., Schwartz, C., Flores, A., Wheeldon, I., 2017. CRISPR-Cas9-enabled
genetic disruptions for understanding ethanol and ethyl acetate biosynthesis in.
Biotechnol. Biofuels 10, 164.

L¨obs, A.-K., Lin, J.-L., Cook, M., Wheeldon, I., 2016. High throughput, colorimetric

screening of microbial ester biosynthesis reveals high ethyl acetate production from
Kluyveromyces marxianus on C5, C6, and C12 carbon sources. Biotechnol. J. 11,
1274–1281.

L¨obs, A.-K., Schwartz, C., Thorwall, S., Wheeldon, I., 2018. Highly multiplexed CRISPRi
repression of respiratory functions enhances mitochondrial localized ethyl acetate
biosynthesis in Kluyveromyces marxianus. ACS Synth. Biol. 7, 2647–2655.

L¨oser, C., Urit, T., Keil, P., Bley, T., 2015. Studies on the mechanism of synthesis of ethyl
acetate in Kluyveromyces marxianus DSM 5422. Appl. Microbiol. Biotechnol. 99,
1131–1144.

Mascorro-Gallardo, J.O., Covarrubias, A.A., Gaxiola, R., 1996. Construction of a CUP1
promoter-based vector to modulate gene expression in Saccharomyces cerevisiae.
Gene 172, 169–170.

McIsaac, R.S., Oakes, B.L., Wang, X., Dummit, K.A., Botstein, D., Noyes, M.B., 2013.
Synthetic gene expression perturbation systems with rapid, tunable, single-gene
specificity in yeast. Nucleic Acids Res. 41, e57.

Meyer, A.J., Segall-Shapiro, T.H., Glassey, E., Zhang, J., Voigt, C.A., 2019. Escherichia
coli “Marionette” strains with 12 highly optimized small-molecule sensors. Nat.
Chem. Biol. 15, 196–204.

Naseri, G., Balazadeh, S., Machens, F., Kamranfar, I., Messerschmidt, K., Mueller-

Roeber, B., 2017. Plant-derived transcription factors for orthologous regulation of
gene expression in the yeast Saccharomyces cerevisiae. ACS Synth. Biol. 6,
1742–1756.

Park, S.-Y., Fung, P., Nishimura, N., Jensen, D.R., Fujii, H., Zhao, Y., Lumba, S.,

Santiago, J., Rodrigues, A., Chow, T.-F.F., Alfred, S.E., Bonetta, D., Finkelstein, R.,
Provart, N.J., Desveaux, D., Rodriguez, P.L., McCourt, P., Zhu, J.-K., Schroeder, J.I.,
Volkman, B.F., Cutler, S.R., 2009. Abscisic acid inhibits type 2C protein
phosphatases via the PYR/PYL family of START proteins. Science 324, 1068–1071.

Park, S.-Y., Peterson, F.C., Mosquna, A., Yao, J., Volkman, B.F., Cutler, S.R., 2015.

Agrochemical control of plant water use using engineered abscisic acid receptors.
Nature 520, 545–548.

Park, S.-Y., Qiu, J., Wei, S., Peterson, F.C., Beltr´an, J., Medina-Cucurella, A.V., Vaidya, A.
S., Xing, Z., Volkman, B.F., Nusinow, D.A., Whitehead, T.A., Wheeldon, I., Cutler, S.
R., 2023. An orthogonalized PYR1-based CID module with reprogrammable ligand-
binding specificity. Nat. Chem. Biol. https://doi.org/10.1038/s41589-023-01447-7.

Rusch´e, L.N., Rine, J., 2001. Conversion of a gene-specific repressor to a regional

silencer. Genes Dev. 15, 955–967.

Sakihama, Y., Hidese, R., Hasunuma, T., Kondo, A., 2019. Increased flux in acetyl-CoA

synthetic pathway and TCA cycle of Kluyveromyces marxianus under respiratory
conditions. Sci. Rep. 9, 5319.

Sanford, A., Kiriakov, S., Khalil, A.S., 2022. A toolkit for precise, multigene control in.

ACS Synth. Biol. 11, 3912–3920.

Schwartz, C., Frogue, K., Ramesh, A., Misa, J., Wheeldon, I., 2017a. CRISPRi repression

of nonhomologous end-joining for enhanced genome engineering via homologous
recombination in Yarrowia lipolytica. Biotechnol. Bioeng. 114, 2896–2906.
Schwartz, C., Shabbir-Hussain, M., Frogue, K., Blenner, M., Wheeldon, I., 2017b.

Standardized markerless gene integration for pathway engineering in yarrowia
lipolytica. ACS Synth. Biol. 6, 402–409.

Stemmer, M., Thumberger, T., Del Sol Keyer, M., Wittbrodt, J., Mateo, J.L., 2015. CCTop:
an intuitive, flexible and reliable CRISPR/Cas9 target prediction tool. PLoS One 10,
e0124633.

Varanasi, U.S., Klis, M., Mikesell, P.B., Trumbly, R.J., 1996. The Cyc8 (Ssn6)-Tup1

corepressor complex is composed of one Cyc8 and four Tup1 subunits. Mol. Cell Biol.
16, 6707–6714.

Vincent, A.C., Struhl, K., 1992. ACR1, a yeast ATF/CREB repressor. Mol. Cell Biol. 12,

5394–5405.

Wade, J.T., Reppas, N.B., Church, G.M., Struhl, K., 2005. Genomic analysis of LexA

binding reveals the permissive nature of the Escherichia coli genome and identifies
unconventional target sites. Genes Dev. 19, 2619–2630.

Weber, W., Fux, C., Daoud-el Baba, M., Keller, B., Weber, C.C., Kramer, B.P., Heinzen, C.,
Aubel, D., Bailey, J.E., Fussenegger, M., 2002. Macrolide-based transgene control in
mammalian cells and mice. Nat. Biotechnol. 20, 901–907.

Wittmann, A., Suess, B., 2012. Engineered riboswitches: expanding researchers’ toolbox

with synthetic RNA regulators. FEBS Lett. 586, 2076–2083.

Yocum, R.R., Hanley, S., West Jr., R., Ptashne, M., 1984. Use of lacZ fusions to delimit

regulatory elements of the inducible divergent GAL1-GAL10 promoter in
Saccharomyces cerevisiae. Mol. Cell Biol. 4, 1985–1998.

Zimran, G., Feuer, E., Pri-Tal, O., Shpilman, M., Mosquna, A., 2022. Directed evolution of
herbicide biosensors in a fluorescence-activated cell-sorting-compatible yeast two-
hybrid platform. ACS Synth. Biol. 11, 2880–2888.

MetabolicEngineering83(2024)102–109109