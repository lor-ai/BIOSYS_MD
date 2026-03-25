SYNTHESIS OF PSILOCYBIN ANALOGUES
AND OTHER 5-HT RECEPTOR AGONISTS
FOR STIMULATION OF
NEUROTRANSMISSION

Anne-Julie Longueville
Student number: 01909938

Promotor: Prof. dr. ir. Christian Stevens

Tutor: ir. Andreas Simoens

Master’s Dissertation submitted to Ghent University in partial fulfilment of the requirements
for the degree of Master of Science in Bioscience Engineering: Chemistry and Bioprocess
Technology
Academic year: 2023-2024

ii

Copyright

The author and the promotor give permission to use this thesis for consultation and to copy
parts of it for personal use. Every other use is subject to the copyright laws, more specifically
the source must be extensively specified when using results from this thesis.

The author declares the use of generative artificial intelligence, specifically the [OpenAI GPT-
4.0 model]. This technology acted solely as a tool to correct writing style and grammar, thus
improving the overall quality of the written work. However, the author emphasizes that the
content of this work is original and also takes full responsibility for this.

Ghent, June 2024

The promotor,

The author,

Prof. dr. ir. Christian Stevens

Anne-Julie Longueville

iii

iv

Acknowledgements

The journey at the Faculty of Bioscience Engineering at campus Coupure is coming to its end.
It has been a remarkable experience, where I was able to uncover my through interests and
passions, providing clear insights in what direction I wish to pursue. In this final year, I was able
to apply a large part of the knowledge acquired in the previous years. This extended beyond
the scientific knowledge, namely the assumed responsibility and the experience of working in
a lab environment was very meaningful.

First  and  foremost,  I  would like to  thank  Professor  Christian  Stevens.  Both  myself  and  your
other  thesis  students  were  very  well  mentored  and  guided  through  this  year.  During  the
monthly meetings, we got the opportunity to discuss problems and questions that had arose.
Moreover, outside of these meetings, you were always reachable when we needed additional
support.

Secondly, I would like to thank my tutor Andreas Simoens. You guided me  through the year
while  providing  plentiful  of  personal  freedom.  I  was  able  to  develop  independence  and
formulate my own ideas. Whenever I needed assistance, I received the necessary guidance
and advice.

I would also like to extend my gratitude to Marthe VandeVelde. She was always approachable
whenever I had questions or was in need of advice or refreshing ideas, or I simply wished a
pleasant conversation.

Finally, I would like to thank my fellow thesis students. We shared many memorable moments
together and formed a close group. A special thanks to Fien and Lise, with whom I enjoyed the
pleasure of sharing many lunch and coffee breaks together.

Anne-Julie Longueville
June, 2024

v

Table of contents

1.  Literature review ........................................................................................................ 1

1.1 Introduction ...................................................................................................................... 1

1.2 Major depressive disorder (MDD) .................................................................................... 1

1.3 Psilocybin .......................................................................................................................... 2

1.3.1 Traditional use and history of psilocybin ................................................................... 3

1.3.2 Psilocybin in the human body .................................................................................... 5

1.3.3 Clinical trials results ................................................................................................... 5

1.4 Psychedelics in general ..................................................................................................... 7

1.4.1 Pharmacodynamics .................................................................................................... 9

1.5 Methods for antidepressant discovery and design ........................................................ 14

1.6 Synthesis of psilocybin (analogues) ................................................................................ 17

1.7 Concluding remarks ........................................................................................................ 20

2. Results and discussion ................................................................................................. 22

2.1 First pathway ................................................................................................................... 22

2.1.1 Starting from 5-Bromo-7-indazole ........................................................................... 24

2.1.2 Starting from 5-Bromo-1H-indazole......................................................................... 29

2.2 Introducing the borrowing hydrogen strategy ............................................................... 33

2.2.1 Synthesis 5-bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-b]pyridine by applying
the borrowing hydrogen strategy ..................................................................................... 34

2.2.2 Phosphonylation of 5-bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-b]pyridine  36

2.2.3 Reversing the reaction sequence ............................................................................. 37

2.3 Synthesis of 5-bromo-N,N-dimethyltryptamine followed by a Suzuki coupling ............ 38

2.3.1 Fisher Indole reaction for synthesis of 5-bromo-DMT ............................................. 38

2.3.2 Suzuki coupling with 5-bromo-DMT ........................................................................ 40

2.4 β-carbolines, another group of tryptamine-like compounds ......................................... 44

2.4.1 Synthesis of tetrahydro-β-carbolines ....................................................................... 47

2.4.2 Dehydrogenation of tetrahydro-β-carbolines to the β-carbolines .......................... 49

3. Conclusion and future perspectives ............................................................................. 51

3.1    Summary and conclusion ............................................................................................. 51

3. 2   Future  perspectives ..................................................................................................... 51

4. Material and methods ................................................................................................. 53

1.  Automatic Flash Column chromatography .................................................................... 53

2.  Dry Solvents ................................................................................................................... 53

vi

3.

Liquid chromatography coupled with Mass Spectrometry ........................................... 53

4.  Mass Spectrometry ....................................................................................................... 54

5.  Nuclear Magnetic Resonance Spectrometry (NMR) ..................................................... 54

6.

Infrared Spectroscopy (IR) ............................................................................................. 54

7.  Thin layer Chromatography (TLC) .................................................................................. 54

8.  Hydrogen generator ...................................................................................................... 54

5. Safety ......................................................................................................................... 55

6. Experimental section ................................................................................................... 58

7. Bibliography ................................................................................................................ 62

vii

Abstract

Psilocybin, which is one the compounds present in Psilocybe mushrooms, gained interest for
the treatment of various psychiatric disorders, especially for the treatment of major depressive
disorder.  Psilocybin  in  its  natural  form,  as  found  in  Psilocybe  mushrooms  is  limited  in  its
therapeutic  use,  since  it  still  faces  different  challenges,  especially  its  hallucinogenic effects.
This limitation can be mitigated by synthesizing non-hallucinogenic analogues, making them
promising antidepressants with a rapid onset and a sustained remission.

In this dissertation, various analogues of psilocybin have been aimed to synthesize, with the
purpose  of  retaining  the  antidepressant  effect  but  omitting  the  psychotropic  effects.
Therefore, different synthetic routes have been explored to develop these kind of analogues,
in  order  to  alter  their  interaction  with  human  enzymes  and  receptors  (mainly  the  5-HT
receptors) by modifying the indole core. Additionally, the synthesis of β-carbolines was also
initiated.  These  are  structures  that  also  show  potential  as  therapeutics  for  psychoactive
disorders such as Alzheimer, again through interaction with 5-HT receptors.

Over the course of this year, psilocybin analogues were synthesized, although primarily as in-
termediates due to several challenges encountered in the synthetic routes. Synthesizing Psilo-
cybin  analogues  represents  a  significant  step  towards  the  development  of  antidepressants
with a rapid onset and sustained remission, eliminating the hallucinogenic effects associated
with  the  natural  psilocybin.  Furthermore,  three  different  tetrahydro-β-carbolines  were  also
synthesized. While psilocybin analogues are promising for treating major depressive disorder,
β-carbolines could benefit disorders such as Alzheimer. The synthesized intermediates should
be subjected to further research in order to develop the aimed analogues and be subjected to
biological testing to evaluate their true potential.

viii

List of Figures

Figure 1.1………………………………………………………………………………………………………………………….….1

Figure 1.2  Representation of the classical psychedelics…………………………………………………..…..8

Figure 1.3 Representation of the different targets of psychedelics…………………………………..….11

Figure 1.4 Location of the claustrum (A), whole-brain anatomical connectivity of the
claustrum (B), and a summary of the functions related to claustrum connections (C)…….…..13

Figure 1.5 Overview of some 5-HT2A receptor agonists evaluated by Cao et al. (2022)………..15

Figure 1.6: 5-HT2A receptor with hydrophobic binding pocket and side extended cavity………16

Figure 1.7 Agonist behaviour of biased ligands ………………………………………………………………..…16

Figure 1.8 Hofmann reaction scheme………………………………………………………………………………….17

Figure 1.9 Synthesis of psilocybin according to Shirota et al. (2003).………..………..………….……18

Figure 1.10 Synthesis of psilocin by Sherwood et al. (2022)………………….……………………………..18

Figure 1.11 Synthesis of psilocin using transition metals…………..………..……………………………….19

Figure 1.12 Psilocin synthesis by Bartolucci et al. (2016)……..…………..………………………………...19

Figure 1.13 Chemoenzymatic approach………………………………………………………………………………20

Figure 2.1 Reaction scheme starting from 5-Bromo-7-azaindole…………………………………….……23

Figure 2.2 Reaction scheme starting from 5-Bromo-1H-indazole…………………………………………23

Figure 2.3 Mannich type of reaction…………………………………………………………………………….……..24

Figure 2.4 Acid catalysed formation of iminium ion…………………………………………………………….24

Figure 2.5 reaction mechanism for the synthesis of 3-(N,N-dimethylaminomethyl)-5-bromo-
7-azaindole…………………………………………………………………………………………………………………...…….24

Figure 2.6 Mannich reaction on 5-Bromo-7-indazole…………………………………………………………..25

Figure 2.7 Mannich reaction on N-1 position with formation of 1-(N,N-
dimethylaminomethyl)-5-bromo-1H-pyrrolo[2,3-b]pyridine ……………………………………………….25

Figure 2.8 Chemical structure of N,N-dimethyltryptamine and N,N-dimethylisotryptamine..27

Figure 2.9 N-alkylation of various indoles…………………………………………………………………..……….27

Figure 2.10 Initial reaction for the synthesis of 5-bromo-3-(2-nitroethyl)-1H-pyrrolo[2,3-
b]pyridine………………………………………………………………………………………………………………………..….27

Figure 2.11 Reaction mechanism for the synthesis of 5-bromo-3-(2-nitroethyl)-1H-
pyrrolo[2,3-b]pyridine…………..……………………………………………………………………………………….……28

Figure 2.12 Actual course of reaction with the formation  of 18 as intermediate…………..……29

Figure 2.13 Mannich reaction on 5-Bromo-1H-indazole………………………………………….…………..29

ix

Figure 2.14 Mannich reaction with nucleophilic attack of N at position 1..……………………..…..30

Figure 2.15 Alkylation using Vilsmeier reagent…………………………………………………………………….30

Figure 2.16 Reaction mechanism using Vilsmeier reagent with nucleophilic attack of C-3
position…………………………………………………………………………….………………..……………………………….31

Figure 2.17 Actual course of reaction with the Vilsmeier reagent……………………..……..…………32

Figure 2.18 Reductive amination of 5-bromo-1-formylindazole…………………………………………..33

Figure 2.19 Reducing the first pathway to 2 reaction steps…….……………………………………………33

Figure 2.20 Mechanism of the borrowing hydrogen strategy using an alcohol and transition
metal catalyst………………………………………………………………………………………………………………………34

Figure 2.21 Synthesis of 5-Bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-b]pyridine……..…35

Figure 2.22 Formation of dimer side product …………………………….…….…………………………………35

Figure 2.23 Synthesis of diethyl (3-(2-(dimethylamino)ethyl)-1H-pyrrolo[2,3-b]pyridin-5-
yl)phosphonate by a Hirao coupling…………………………………………………..………………………………..36

Figure 2.24 Hirao coupling reaction mechanism………………………………..………………………………..37

Figure 2.25 Reversed reaction sequence……………………………………………………………………………..37

Figure 2.26 Phosphonylation of 5-bromo-7-azaindole following a Hirao coupling
mechanism…..……………………………………………………………………………………………………………………..38

Figure 2.27 Alkylation of diethyl (1H-pyrrolo[2,3-b]pyridin-5-yl)phosphonate…………..………..38

Figure 2.28: Synthesis of 5-bromo-DMT………………….…………………………………………………………..38

Figure 2.29 Synthesis of 5-bromo-DMT following a Fischer Indole reaction mechanism….….39

Figure 2.30 Catalytic cycle of the Suzuki coupling with boronic acids………………………….……….40

Figure 2.31 Overview of the different boronic acids………….…………………………………………………41

Figure 2.32 Synthesis of N,N-dimethyl-2-(5-phenyl-1H-indol-3-yl)ethan-1-amine via Suzuki
coupling reaction…………………………………………………………………………………………………………………41

Figure 2.33 Overview of the different Suzuki coupling with different reaction conditions,
tested on different boronic acids………………………………………………………………………………………...42

Figure 2.34 Oxidized compounds……………………………………………………….……………………………….43

Figure 2.35 Reduction of oxidized compounds using activated zinc dust……………………..………44

Figure 2.36 Carboline alkaloid skeleton……………………………………………………………………………….44

Figure 2.37 Pictet-Spengler reaction……………………………………………………………………….…………..45

Figure 2.38 Representation of the 5 clusters of β-carbolines…………………………………………..…..46

Figure 2.39 Synthesis of β-carbolines with Pictet Spengler reduction using nitriles, followed
by an aromatization step……………………………………………………………………………………………………..46

x

Figure 2.40 Synthesis of β-carbolines with Pictet Spengler reduction using aldehydes,
followed by an aromatization step……………………………………………………………….………………….….47

Figure 2.41 Synthesis of the THBC of Eudistomin U……………………………………………………………..47

Figure 2.42 Synthesis of 7-fluoro-1-(1H-indol-3-yl)-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole
(cluster 1)……………………………………………………………………………………..…………………………………….48

Figure 2.43 Synthesis of 1-(6-bromopyrazolo[1,5-a]pyrimidin-3-yl)-2,3,4,9-tetrahydro-1H-
pyrido[3,4-b]indole (cluster 3)…………………………………………………………………………………………….48

Figure 2.44 Synthesis of methyl 3-(2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indol-1-yl)-1H-indole-
6-carboxylate (cluster 4)…………………………………………………………………..…………………………………48

Figure 2.45 Synthesis of 1-(1H-indol-3-yl)-6-methoxy-2,3,4,9-tetrahydro-1H-pyrido[3,4-
b]indole (cluster 5)………………………………………………………………………………………………………………49

Figure 2.46 Aromatization of 1-(1H-indol-3-yl)-6-methoxy-2,3,4,9-tetrahydro-1H-pyrido[3,4-
b]indole …………………………………………………………………………………………………….……………………….50

xi

1. Literature review

is

also

widely

psilocybin

1.1 Introduction
Psilocybin (O-phosphoryl-4-hydroxy-N,N-dimethyltryptamine)  is a tryptamine alkaloid which
can  be  found  in  certain  mushrooms,  mainly  in  the  genus  Psilocybe.  However,  synthetically
produced
days.
It is naturally produced by certain mushrooms such as Psilocybe, Panaeolus and others (Strauss
et al., 2022), in which they represent a content of 0.2% to 1% of the dry weight (Tylš et al.,
2014). These substances can be called psychedelics or hallucinogens, however in this master
dissertation, the objective is to synthesize psilocybin analogues with no hallucinogenic activity.
Market values from $1.9 to $253 billion are estimated for psilocybin, because of its treatment
potential as a non-addictive antidepressant. Currently, the chemical synthesis is performed on
a smaller scale than the harvesting from mushrooms and sclerotia on the nutraceutical public
market. This is mainly because of the ease of the production of these mushrooms and due to
the  possible  synergism  with  other  hallucinogenic  compounds  produced  in  these  organisms
(Strauss et al., 2022).

available

these

Figure 1.1

The Swiss scientist Adolphe Hofmann was the first to isolate the psychedelics psilocybin and
psilocin, and gave them their current names. After the isolation, but also synthesis of these
molecules  by  Hofmann,  the  first  ‘golden  era’  in  the  research  of  psilocybin  occurred.  This
slowed down after 1971, partially due to Nixon’s declaration of the war on drugs. In the period
of  1972  to  2010,  the  researched  declined,  and  the  publications  per  year  decreased
significantly. After 2011, interest in these compounds increased once again, due to different
psychedelic  advocates  such  as  the  Multidisciplinary  Association  for  Psychedelic  Studies
(MAPS). In 2020, 140 publications on psilocybin appeared, and in 2021, this even reached 204.
This is shaping up to be the second wave on psychedelic research, far exceeding the efforts
made in the first research wave during the 1960s (Agrawal et al., 2023).

Modern  studies  for  psilocybin  mainly  focus  on  the  possibility  of  psilocybin  to  treat  major
depressive  disorder.  However,  other  studies  on  disorders  such  as  obsessive-compulsive
disorder, cocaine use disorder, anorexia nervosa, and more have also been conducted using a
psilocybin treatment (Strauss et al., 2022).

1.2 Major depressive disorder (MDD)
Major  depressive  disorder  is  a  widely  occurring  cause  of  disability.  Currently  available
treatments take weeks or months before they show any symptom reduction. Additionally to

1

this, the treatment adherence seems to be problematic for several patients, resistance against
the treatments of this depressive illness occurs frequently. 40 To 60% of the patients that were
diagnosed once, relapse and its rate also accelerates after every episode. It is thus clear that
the discovery of novel treatments, which work more rapidly and produce a sustained remission
is an urgent need (Gukasyan et al., 2022).

Several  studies  already  suggested  the  use  of  a  psilocybin  treatment,  where  antidepressant
effects were visible within the short time of a week after administration. Even for treatment
resistant patients, the response rate seems to be positive (Gukasyan et al., 2022).

The disease affects 1 in 6 adults, where the amount of women affected is twice the amount of
men.  It  is  the  second  leading  contributor  to  chronic  diseases,  and  it  is  associated  with
increasing risks in developing other conditions such as diabetes, heart diseases and strokes.
Patients with MDD have almost a 20-fold more likelihood to die by suicide compared to the
population.
general
The  disease  has  a  genetic  contribution  which  is  estimated  to  be  35%,  and  environmental
factors during childhood are strongly associated with the chance of developing MDD during
adulthood.
All aspects of the disease in terms of neurobiology are not completely understood yet. What
is known, is the fact that MDD is associated with small hippocampal volumes and a change in
the activation or the connectivity of the neural networks. The hypothalamic-pituitary-adrenal
(HPA) axis, a neurobiological system that mediates the stress response, is altered next to the
automatic nervous system and the immune system. This HPA axis forms the most researched
biological  system  in  MDD.  Cortisol  levels  are  raised  in  patients  with  MDD  and  impaired
cognitive function frequently occurs, more common and more pronounced in patients with
severe depression and elder patients (Otte et al., 2016).

MDD treatments consist of both psychotherapy and psychopharmacology. 30% Of the patients
does  not  remit  from  the  disease,  even  after  several  treatments  (Otte  et  al.,  2016).  New
pharmacological approaches using ketamine and psychedelics find themself under scientific
research with promising results, forming the main objective of this master dissertation.

1.3 Psilocybin
Psilocybin  is  a  secondary  metabolite  occurring  in  different  mushrooms  and  fungal  species.
These mushrooms are frequently referred to as magic mushrooms. They have been used for a
long time by humanity for spiritual purposes, given its hallucinogenic properties. They mediate
interactions between the producing fungi and other organisms. A possible explanation for its
evolution is the defence mechanism against fungivores and resource competitors. It can also
increase  the  dispersal  of  spores  by  the  animals  coming  near  these  mushrooms.  Another
proposed explanation states that psilocybin is synthesized as a store/disposal product for the
excess nitrogen, which could otherwise exert a toxic effect on the mushroom itself. Studying
the natural mechanisms of psilocybin should not be neglected, since it might help in exploring
the  different  applications  for  humans.  Psilocybin  producers  are  typical  fungi  that  find
themselves in dung, late-wood decay niches. They can be found in all sorts of climates, with
the
2023).
Typically, the concentration of metabolites such as psilocybin is highest in the fruiting bodies.
It is a logical assumption to suspect that animals are targeted by psiloids (the collective name
for psilocybin, its precursors and derivates), given their structural similarity to serotonin and

concentrations

neotropics

highest

(Meyer

Slot,

and

in

2

its  ability  to  bind  to  all  kind  of  receptors  as  will  be  described  below.  These  effects  can  be
beneficial for the fungi in different ways. Since they affect physiological processes in animals,
there is no doubt that this interferes with the interaction of the mushrooms and the animals
(Meyer and Slot, 2023).

Psilocybin  and  its  derivative  psilocin  are  tryptamine  molecules,  consisting  of  an  indole  ring
with attached amine side chains. In their pure forms, these compounds can be found as white
powders. Bulky phosphate groups of psilocybin render this molecule more water soluble than
psilocin,  representing
(Strauss  et  al.,  2022).
In  general,  the  psychoactive  effect  of  tryptamines  is  mainly  due  to  the  indole  alkylamine
moiety of the molecules. Alkylations of the side chain nitrogen, substitutions of the indole ring
and  the  side  chain  carbon  are  all  factors  impacting  the  psychoactive  effect  of  tryptamine
2022).
derivatives

lipid  soluble  compound

the  more

(Ashgar

al.,

et

Many  behavioural  assays  exist  to  evaluate  the  therapeutic  potential  of  possible
antidepressants. A commonly used test next to the head twitch response that will mentioned
further below, is the forced swim test, where the animal’s despair is assessed. A decrease in
immobility shows a potential antidepressive effect. Previous tests with psilocybin have shown
this decrease in immobility time.

The brain derived neurotrophic factor (BDNF), which are proteins where increased expression
modifies gene expression and causes signalling cascades, and decreased BDNF levels increase
depressive  like  behaviour,  is  upregulated  in  the medial  prefrontal  cortex  and  hippocampus,
promote the synaptic plasticity and reduce the immobility, which could mean that these BDNF
form biological markers for antidepressive therapeutic potential (Sandoval, 2023). However,
this  test  mainly  evaluates  the  stress  coping  response  of  rodents  and  not  necessarily  their
depression  like  behaviour  (Yin  et  al.,  2023).  Which  makes  using  them  as  markers  of
antidepressive behaviour possibly not the best option.

are

they

1.3.1 Traditional use and history of psilocybin
The first evidence of the use of psilocybin returns to a codex in the years 1500, belonging to
the Mixtec culture in Mesoamerica. Even to this day, the use of Psilocybe species is continued
by  different  Mexican  ethnic  groups  such  as  the  Chatins,  Maztecs  etc.  Most  of  these
hallucinogenic species were reported to be used by groups in central and southern Mexico,
where
tradition.
Current  rituals  and  ceremonies  in  both  Catholic  and  Mesoamerican  context,  use  Psilocybe
species  for  the  treatment  of  spiritual  and  physical  illnesses.  Because  of  the  hallucinations
associated with the consumption of these species, people have a trance like experience where
the soul is able to dissociate from the body. These treatments are  conducted by doctors or
shamans, typically at night at quiet places, where no food, drinks or other medicines and drugs
are  allowed  to  be  taken  in  advance,  and  travelling  is  discouraged  up  to  a  week  after  the
treatment. Indigenous groups also use the Psilocybe mushrooms for the treatment of anxiety,
rheuma and sometimes it is used as an analgesic to relieve pain (van Court et al., 2022).

ancient

sacred

part

an

of

Aztec Indians from South America used to refer to them as ‘teonanacatl’, which means ‘God’s
flesh’.  Secondary  metabolites  such  as  psilocybin  have  proven  their  potency  as  novel
therapeutics through the years, where they have served as prototypes or lead compounds that
can be synthesized chemically with or without certain modifications to increase their potency,

3

stability, or superiorize drug-like properties. Most of the secondary metabolites from plants,
fungi and/or bacteria have known their use in anti-infective and anti-cancer treatments, but
recently  these  are  more  and  more  being  used  in  the  treatment  of  disorders  of  the  central
nervous system (CNS) such as depression (Nichols et al., 2020).

For psilocybin, it all starts with Benardino de Sahagun, a Spanish Franciscan that engaged in
ethnographic research in Mexico. He wrote the General History of the Things of New Spain,
where  in  his  most  famous  manuscript  (the  Florentine  Codex)  he  refers  multiple  times  to
‘teonanacatl’ or ‘Gods Flesh’, namely the sacred mushrooms in Mesoamerica. For a very long
time, the existence of these mushrooms was very controversial and even denied, such that
debate  existed until 1936.  After  this,  a botanist named  Richard  Evans  at  Harvard  university
identified specimens of three species of these sacred mushrooms where they were identified
as  Psilocybe  caerulescens,  Panacolus  campanula,  and  Stropharua  cubensis.  World  war  II
interrupted further research. Until in 1952, amateur mycologist R. Gordon Wasson travelled
to Mexico on the search for these mushrooms. These trips resulted in the publication of an
article in Life Magazine, where psychoactive mushrooms were introduced to the wide public
(Nichols et al., 2020). The French mycologist Roger Heim was able to cultivate the mushrooms
himself  and  sent  samples  to  Albert  Hofmann  for  further  analysis.  He  subjected  extracts  of
these mushrooms to paper chromatography to separate the different compounds, where he
identified  the active  compound  and  named  it  psilocybin.  Additionally to  psilocybin,  he  also
identified  a  compound,  which  was  the  dephosphorylated  psilocybin  and  named  it  psilocin
(Nichols et al., 2020). The identification of the active compounds in these magic mushrooms
were encouraged by the recurring crises in the coffee prices since the 50’s (de Teresa, 2022).

In 1970, under the orders of US president Richard Nixon, psilocybin and other hallucinogens
have  been  placed  in Schedule  I  category of  the  United  States  Controlled  Substances  Act  of
1970. These substances are implicated with involvement and influence on anti-war protests
and cultural movements in the 60’s, forming an explanation for this decision. To the current
day,  these  substances  remain  in  this  Schedule  I  status,  meaning  that  the  substance  has  no
accepted medical or therapeutic use (Heilman, 2023).

Since 1971, psilocybin mushrooms have been included in the list of illicit substances in Mexico.
But their use is tolerated when their consumption is related to medico-religious ceremonies.
People  travel  to  the  city  of  Huautla  de  Jimenez  for  experiencing  the  psychoactive  effect  of
these mushrooms. This city played a very important role in the history of psychedelica and in
their use across other cultures by the ‘counterculture’ movement (de Teresa, 2022).

In  1986,  there  was  the  establishment  of  the  Multidisciplinary  association  for  Psychedelic
Studies (MAPS), a non-profit psychedelic pharmaceutical company, by the founder Rick Doblin.
It  was  established  with  the  goal  to  facilitate  the  research  of  the  use  3,4-methylenedioxy
methamphetamine  (MDMA)  as  a  therapeutic,  being  an  apparent  move  against  the  Drug
Enforcement Administration (DEA) wanting to criminalize MDMA. A study of the use of MDMA
in treating pain, anxiety and depression in cancer patients was conducted by Charles Grob, a
member  of  this  organization.  Thanks  to  the  completion  of  this  study,  the  Food  and  Drug
Administration of the US (FDA) accepted the use of psychedelics in human clinical research
with the same standards as other potential prescription drugs. Even though Grob’s initial focus
was  on  MDMA,  he  focused  on  psilocybin  in  the  treatment  of  cancer  patients  because  he
thought  that  this  research  would  be  less  controversial  than  his  MDMA  research.  For  the
research of lysergic acid diethylamide (LSD) assisted psychotherapy, the MAPS extended its

4

research to Switzerland, since it there received the permission to conduct research that it did
not receive from the FDA. Eventually in 2008, the Swiss study was accepted by the FDA and
finally, the last one of the classic psychedelics was accepted for research (before research with
MDMA, psilocybin, N,N-Dimethyltryptamine (DMT), tryptamine, ketamine and mescaline had
already been approved) (Heilman, 2023).

 1.3.2 Psilocybin in the human body
Psilocybin is usually administered in doses of 15, 25 or 30 mg (Holze et al., 2023). 90 To 97% of
the psilocybin is dephosphorylated to psilocin in our metabolism, which appears in the blood
plasma  after  oral  administration.  They both  affect  the  serotonergic  pathway,  a  system  that
regulates functions such as pain, cognitive function, vascular tone, motor activity etc. (Dodd
et al., 2022). This dephosphorylation takes place in the acidic environment of the stomach or
by alkaline phosphatase and a non-specific esterase present in the intestine and kidney. This
compound  is  now  lipid  soluble  and  able  to  cross  the  blood  brain  barrier.  Psilocin  is
subsequently  distributed  to  other  tissues,  with  an  estimate  of  the  apparent  volume  of
distribution  of  298  L,  exceeding  the  volume  of  the  human  body,  when  applying  a  one
compartment  model.  During  its  first  pass  through  the  liver,  a  demethylation  and  oxidation
phase 1 metabolism by mono-amine oxidase and aldehyde dehydrogenase on psilocin to form
4-hydroxindole-3-acetic
4-
hydroxytryptophol takes place (Dodd et al., 2022). About 4% of psilocin is metabolised in this
way. Another possibility, is the oxidation of psilocin to products with an O-quinone or imino-
quinone structure by hydroxyindole oxidases (Tylš et al., 2014).

4-hydroxy-indole-acetaldehyde

(4-HIAA),

acid

and

Subsequently, a phase 2 metabolism takes place, mainly catalysed by endoplasmatic enzymes
(UDP-glucuronosyltransferases, or UGT). Psilocin is glucuronidated to psilocin-O-glucuronide.
There  is  an  extensive  glucuronidation  in  the  small  intestine  by  UGT1A10.  When  the
compounds  are  absorbed
into  the  circulation,  UGT1A9  contributes  most  to  the
glucuronidation (Dodd et al., 2022). It is in this form, the psilocin-O-glucuronide, that 80% of
2014).
the

administered

psilocybin

excreted

(Tylš

al.,

et

is

Psilocybin and its metabolic derivatives are found in our blood plasma 20 to 40 minutes after
an  oral  administration  and  maximum  levels  are  observed  after  80  to  105  minutes.  Oral
ingestion half-life is around 2.5 hours, intravenous administration half-life is approximately to
be  1.23 hours. The conjugated form of psilocin represents the biggest part in the blood plasma
(80%).  Both  psilocin  and  psilocybin  can  be  detected  in  human  urine,  they  are  detected
unmodified but mostly conjugated with glucuronic acid. The biggest part is excreted 3 hours
after the oral administration and there is a complete elimination from the human body after
24h (Tylš et al., 2014).

 1.3.3 Clinical trials results
A phase 1 randomized, double-blind and placebo-controlled study was conducted by Rucker
et al. (2022), to assess the safety of psilocybin administration to healthy people. Short and
longer term changes in cognitive functions were assessed by a Cambridge Neuropsychological
Test automated Battery (CANTAB) panel and an emotional processing scale. Additionally, the
safety of psilocybin administration was evaluated using the CANTAB global composite score
and by monitoring treatment-emergent adverse events (TEAE) (Rucker et al., 2022).  During
the study, 89 healthy adults with a mean age of 36.1 years were randomized and dosed with

5

10 mg of psilocybin, 25 mg of psilocybin or placebo. The participants were being followed up
for  12  weeks  after  the  drug  administration.  In  the  results  of  the  study,  511  TEAEs  were
observed with a mean duration of a day. These TEAEs all started and resolved again on the
same day. Hence, it could be concluded that the doses of 10 and 25 mg of psilocybin were well
tolerated and no detrimental short- or long-term effects on the cognitive functioning and the
emotional processing were caused. These findings support the further research and studies
on psilocybin related treatments for different psychiatric disorders (Rucker et al., 2022).

In the follow up of phase 1 studies, phase 2 studies are now also being conducted. Another
randomized  placebo-controlled,  6-week  trial  in  104  people  that  received  a  25  mg  dose  of
psilocybin  was  conducted  by  Raison  et  al.  (2023).  This  phase  2  study  was  randomized  and
multiblinded,  comparing  a  single  dose  psilocybin  with  niacin  (a  placebo  controller).  The
outcome assessments were exerted by blinded centralized raters to gain information on the
timing  of  the  onset  of  action,  the  lastingness  of  the  beneficial  effects  and  the  safety  of
psilocybin  during  a  period  of  6  weeks.  The  efficacy  was  examined  using  the  MADRS  score,
which is 10-item scale that has a scoring range from 0 to 60, where the higher the score, the
more depressive the patient. These scores were compared from baseline to day 43. Next to
this,  changes  in  the  Sheehan  Disability  Scale  (SDS)  and  the  percentage  of  patients  with  a
sustained  depressive  system  response,  were  assessed.    Next  to  its  efficacy,  the  safety  of
psilocybin administration was evaluated in this study. Adverse effects such as elevated blood
pressure, headache, nausea and others were examined.  The statistical analysis was conducted
using  a  covariance  matrix  for  the  continuous  outcomes  of  the  mixed  effects,  sensitivity
analysis,  logistic  regression,  odds  ratios  with  95%  confidence  intervals,  and  sequential
significance testing to ensure an overall α level of 0.05. Two-sided tests were used to compare
the MADRS score from the baseline to day 43 and day 8. The incidence of the adverse effects
was  examined  using  counts  and  percentages,  and  a  Clopper-Pearson  interval  with  95%
confidence intervals. The participants that received psilocybin showed a greater difference in
MADRS score from baseline to day 8 as to day 43, compared to the group that received niacin
(P  <  0.001).    The  treatment  with  psilocybin  had  associations  with  improvements  in  the
reduction  of  global  disease  severity,  depressive  and  anxiety  symptoms,  and  quality  of  life.
Looking at the results regarding the safety, the most commonly occurring adverse effect was
headache, followed by nausea and visual perceptual effects. Both statistically and clinically,
this study showed a significant decrease in depressive symptoms. These improvements were
visible within 8 days of the dosing and knew a fast onset of action. Mean differences in the
SDS score showed improvements in psychosocial functioning. The adverse effects that were
experienced during the dosing were most of a mild nature and only occurred during the acute
period of dosing (Raison et al., 2023).

Another double-blind, randomised clinical trial with 52 patients suffering from MDD received
a  single  moderate  dose  of  psilocybin  (0.215  mg/kg  body  weight)  or  a  placebo.  By  the
assessment of MADRS and Beck depression inventory (BDI) score, the severity of the patient's
depression was estimated. This BDI is multiple-choice self-report inventory that consists of 21
questions. It is another widely used instrument to assess the severity of depression. Again, the
higher the total score, the more the severity of the depression (Beck et al., 1961). The patients
receiving  psilocybin  showed  a  decrease  in  the  severity  of  depression  symptoms,  namely  a
decrease of 13 points of the MADRS score compared to baseline (p = 0.0011) after 14 days.
The  findings  suggest  that  this  dose  of  psilocybin  has  significantly  reduced  the  patient's
depression symptoms for a minimum period of 2 weeks (von Rotz et al., 2022).

6

A systematic review and meta-analysis of clinical trials was conducted by Vargas et al. (2020).
This review with meta-analysis was performed on the following databases: PubMed, Web of
Science, Scopus, and SciELO. The Boolean operator with a specific search strategy was used.
Additionally, the reference’s list of the relevant articles were also examined to check for more
work.  In  total,  670  articles  were  evaluated.  For  the  statistical  analysis,  weighted  mean
differences  (WMD)  of  the  intervention  group  (receiving  psilocybin)  and  control  group
(receiving placebo), between the change in pre-and post-treatment mean values, were used.
The psychometric scales of the study were the BDI and the State-Trait Anxiety Inventory (STAI).
Where BDI is used to assess depression, STAI is used to assess anxiety. STAI is just like BDI, a
self-report questionnaire, being able to detect the presence and severity of anxiety symptoms
and the general propensity to feel anxious. Furthermore, it is divided into 2 subscales: the STAI-
Trait and the STAI-State (Vargas et al., 2020). Through the meta-analysis it could be concluded
that for BDI, the intervention group was favoured over the control group (p = 0.002).  In order
to do this, 11 effect sizes were considered. As for BDI, 11 effect sizes were considered for STAI-
Trait. The same conclusion as for the BDI could be conducted, namely the favouritism of the
intervention group over the control group (p < 0.001). For the STAI-State, 9 effect sizes were
chosen.  The  outcome  was  the  same  as  for  the  previous  two  (p  <  0.001).  Hence,  this  study
demonstrates the effectiveness of psilocybin to reduce symptoms of depression and anxiety
(Vargas et al., 2020). These promising results emphasize the importance of psilocybin (clinical)
research.

Clinical trials both assessing the safety and adverse effects of psilocybin administration and
studies  regarding  its  therapeutic  potential  show  that  the  compound  possibly  forms  an
interesting  anti-depressant.  Even  taking  into  account  the  publication  bias  which  was
performed by Vargas et al. (2020), the compound is still regarded as effective. Now that these
clinical  studies  have been  performed,  it’s  important  to  further  conduct  mechanistic  studies
that  try  to  fully  clarify  the  action  mechanism  of  the  drug,  which  is  still  under  quiet  some
discussion as will be further described below.

1.4 Psychedelics in general
The molecular structure of psychedelics resembles a serotonin molecule, and they are defined
by  their  serotonergic  action  mechanisms.  Apart  from  the  rise  of  their  use  in  meditative
settings,  they  are  also  more  and  more  studied  in  clinical  studies  testing  their  potential  for
treatment  of  psychiatric  disorders.  However,  both  early  and  more  recent  research
demonstrated  that  repeated  administration  of  psychedelics  can  induce  cross-toleration,
lowering  their  effectiveness.  Classical  psychedelics  share  a  common  mechanism  of  action,
comprising their partial agonism for the 5-hydroxy-tryptamine 2A (5-HT2A) receptors and their
binding to receptors that activate a whole lot of intraneuronal signalling pathways. Different
psychedelic  drugs  can  be  compared,  having  the  same  occupancy  of  a  certain  receptor  (5-
HT2AR),  for  their  difference  in  efficacy,  selectivity  or  their  polypharmacology  (Grieco  et  al.,
2022). The administration of a compound named ketanserin prevents the effects associated
with  psychedelics,  since  it  acts  as  a  5-HT2A  antagonist  (van  Elk  et  al.,  2022).  In  this  way,
ketanserin  blocks  dose  dependently  the perceptual  disturbance and  hallucinations  that  are
induced by psychedelics such as psilocybin (Dodd et al., 2022).

7

Figure 1.2:  Representation of the classical psychedelics

Different animal studies, of which the most reliable seems to be  the head twitch response,
indicated the important role of the 5-HT2A receptor. The head twitch response in rodents forms
a  reliable  way to make a  distinction between  hallucinogenic  and non-hallucinogenic  5-HT2A
agonists. This type of response is a side-to-side head movement, that occurs in rodents when
the 5-HT2A receptor is activated and therefore indicates hallucinogenic effects (Nakagawasai et
2004).
al.,

Because of their agonism to this receptor, an increased frequency of cortical layer 5 pyramidal
neurons is observed, next to evoking excitatory post-synaptic currents and an increase of their
firing  rate  upon  its  activation.  Activation  of  these  receptors  is  necessary  for  tryptamine
psychedelic analogues to fulfil their antidepressant effect. Both the hallucinogenic as well as
the  therapeutic  effects  are  a  result  of  the  activation  of  the  same  receptor.  Psychedelics
stimulate  the  growth  of  neurons  in  the  medial  prefrontal  cortex  (mPFC),  however  their
produced experiences are very subjective. Changes in neuroplasticity are also associated with
psilocin, these neuro-plastogenic effects were proposed to be a part of the non-hallucinogenic
part of the therapeutic effect. This together with a 5-HT2A activation of phosphatidylinositol
hydrolysis, this receptor agonism activates the tropomyosin receptor kinase B pathway (TrkB)
and  possibly  also  other  pathways  (Dodd  et  al.,  2022).  Serotonergic  psychedelics  promote
neuroplasticity  by  activating  rapamycin.  It  is  known  that  the  hallucinogenic  effect  from
psychedelics is due to their agonism of the 5-HT2A receptors, but unclarity remains among the
role of this receptor in the mechanisms of long-lasting changes in the neuronal structure and
behaviour. Both evidences as conflicting results have been established, which makes drawing
conclusions  a  hard  task  (Cameron  et  al.,  2023).    5-HT2A  receptors  are  involved  in  a  lot  of
functions,  they  play  a  role  in  the  memory,  pain,  perception  etc.  They  are  present  in  the
pyramidal neurons in layer 5 of the neo-cortex, in the thalamus, and the reticular nucleus. Next

8

to these, high concentrations are present in higher-order association areas of the brain: the
temporo-parietal junction and the medial prefrontal cortex. Possibly explaining the influence
of psychedelics on e.g., emotional functions. Looking at the density of these receptors, the
highest concentration was found in the visual cortex, forming a possible explanation for the
visual hallucinations associated with psychedelics. However, even given the proof of the role
of the 5-HT2A receptor, limitations are found in recent research. Even after administration of
ketanserin, hedonic behaviour after psilocybin administration was not affected. This blocking
of  the  receptor  did  induce  the  abolishment  of  the  head  twitch  response,  but  the  induced
changes in structural plasticity were not changed. These findings all point in the direction of
possible additional pharmacological action mechanisms of psychedelics.

1.4.1 Pharmacodynamics
The usual anti-depressants onset time is about 3 to 4 weeks, which is much longer than would
be desired in cases where an urgent therapeutic effect is needed for the benefit of the patient.
Additionally, to that, there is only an ameliorating effect in one-third of the patients, showing
the importance of improved antidepressants with fast-working action. Psychedelic drugs are
promising  for  healing  depressions,  but  their  hallucinogenic  effects  limit  their  current
application. The target molecules therefore would keep their anti-depressive effect but omit
the  hallucinations.  The 5-hydroxy-tryptamine  receptor,  a  G  protein  coupled  receptor,  forms
the  receptor  where  hallucinogens  such  as  psilocybin  bind  to.  Recent  studies  from  China
explained mechanisms through which the hallucinogens exert their anti-depressive effect by
structural biology. High resolution density maps of ligand-receptor complexes were obtained,
and by comparing the different conformations of different compounds bound to this receptor,
2 binding pockets were found. The orthosteric binding pocket (OBP) and the extended binding
pocket  (EBP).  For  hallucinogens,  their  binding  to  the  two  pockets  differs,  but  for  the  non-
hallucinogenic compounds, they bind less strongly to the EBP. Binding to OBP activates a G
protein  signalling  pathway  where  binding  to  the  EBP  activates  the  β-arrestin  pathway.  So,
hallucinogenic effects could be a consequence of a simultaneous activation of these pathways.
Molecules that bypass the OBP and only bind to EBP and therefore target the activation of the
β-arrestin pathway may not have these unwanted hallucinogenic effects. Analysis of the head
twitch  response  (which  indicates  hallucination)  in  mice,  even  by  high  doses  of  designed
compounds that mainly bind to EBP and not to OBP resulted in no head twitch response. Based
on the structural features of the target sites of the receptors,  analogous molecules may be
designed, circumventing the problems related to hallucinations (Yin et al., 2023). The concept
of ligand bias of the 5-HT2A receptors has been identified as way of creating biased agonists
with potentially greater therapeutic power over the known agonists with a balanced agonism
between the G-protein dependent pathways and the β-arrestin pathways. In this way many
side  effects,  such  as  hallucinations  could  be  further  avoided  (Cameron  et  al.,  2023).  This  is
further described below.

Psychedelics and in particular psilocybin can react with various receptor subtypes, respectively
following this order ranked according to affinity: 5-HT2B > 5-HT1A > 5-HT2A in a rat or bovine
cortex.  It was shown that psilocin is also bound to other receptors than 5-HT2A, namely: 5-
HT2B, 5-HT2D, dopamine D1, 5-HT1E, 5-HT1A, 5-HT5A, 5-HT7, 5-HT6, D3, 5-HT2C and 5-HT1B, ranked
from lower to higher affinity (Dodd et al., 2022).

It is also possible that the psychedelics target an intracellular pool of these 5-HT2A receptors
instead  of  the  receptors  on  the  membrane  surfaces.  Since  serotonergic  psychedelics  are

9

lipophilic compounds, they can pass the cell membrane and some of them such as psilocin
even  target  these  intracellular  receptors  and  induce  neuronal  growth.  However,  it  remains
unknown if this targeted volume of receptors is sufficient to obtain neuronal growth or if there
are  other  properties  and  signalling  pathways  that  lead  to  the  effects  induced  by  these
substances (Cameron et al., 2021).

Other interesting compounds, such as the modified 2-bromo-LSD, are partial agonists to the
5-HT2A receptor. They form mild agonists for different 5-HT receptors, but also show agonism
to the dopamine D2 and D4 receptors. Since it only partially activates the 5-HT receptors and
partially antagonizes in the presence of serotonin, it may explain the lack of hallucinogenic
effects. Hence, their might be a threshold below which side effects are not activated. This is
another  example  that  may  suggest  that  the  hallucinogenic  part  of  psychedelics  is  not  a
necessity for their therapeutic potential (Cameron et al., 2023).

Psychedelics  induce  a  cascade  of  pharmacological  processes,  of  which  several  had  been
described in literature. One of these mechanisms is the psychoplastogen model. At the neural
level, it was found that psychedelics increase the number of connections between neurons,
increasing the synaptic growth and increasing the complexity of the dendrites and the amount
of  synapses.  This  increased  neuroplasticity  is  due  to  post-synaptic  effects  in  layer  5  of  the
medial prefrontal cortex. This induces a glutamate release and the activation of the α-amino-
3-hydroxy-5-methyl-4-isoxazolepropionic acid receptor (AMPAR). Brain derived neurotrophic
factor-tropomyosin receptor kinase B (BDNF-TrkB) is released as a result and the mammalian
version of rapamycin signalling is triggered, upregulating the expression of genes related to
neuroplasticity  and  the  synthesis  of  protein  from  synaptic  components  by  the  eukaryotic
elongation factor 2 (eEF2). Al these effects together amplify the neuroplasticity which can have
a therapeutic effect. This forms indirect evidence for the neuroplastic effects since depressive
patients  show  lower  levels  of brain  derived  neurotrophic  factor  (BDNF).  Additionally,  direct
evidence  was  found  in  animal  studies  where  it  was  indicated  that  prosocial  behaviour  was
increased  and  stress-induced  behaviour  was  reversed,  but  it  must  be  mentioned  that  it  is
questionable how these neuroplastic effect could be beneficial for humans. In recent studies,
it was shown that only high levels of e.g., LSD resulted in increased BDNF levels, whereas this
was  not  the  case  for  lower doses. Following  this  view  of  psychedelics,  they can be  seen  as
‘psychoplastogens’, molecules promoting the rapid neural plasticity. It is therefore likely that
neural  plasticity  plays  a  role  in  the  therapeutic  effects  of  psychedelics,  but  the  evidence  is
limited
2022).
Psychedelics  increase  levels  of  the  psychoactive  substance  oxytocin,  a  hormone  leading  to
feelings such as empathy and sociability. Acute effects that are experienced can therefore be
the result of these increased oxytocin levels.

specificity

because

(van

lack

al.,

Elk

of

et

of

In  addition  to  binding  to  receptors,  molecules  such  as  serotonin  are  chemically  reactive
molecules that can bind in a covalent way to glutamine residues of several proteins, which is
called transamidation and is catalysed by transglutaminase 2 (TGM 2). When molecules such
influence  cytoskeletal  rearrangement,
as  serotonin  bind  to  key  proteins,  they  can
transcriptional regulation, mitogenesis and different processes regarding synapse formation
and  maturation.  Since  psychedelics  resemble  serotonin,  they  serve  as  substrates  for  these
amidation reactions in place of endogenous enzymes. There is a hypothesis that both the 5-
HT2A agonism and the TGM2-amidation reactions work in a conjunction to establish the effects
inside cells. Primary amines can directly undergo this amidation by TGM-2, other psychedelics

10

such as secondary or tertiary amines would have to be demethylated first, which occurs in vivo
quite rapidly. Now the question arises whether this TGM-2 activity mediates the therapeutic
affects  in  some  way.  In  a  landmark  study  it  was  shown  there  was  a  decreased  histone
serotonylation  in  patients  with  MDD  who  were  not  taking  any  antidepressants.  Further
research has  to be  performed  to  check  whether  these histone  marks  influence depression,
anxiety and others (Cameron et al., 2023).

On the genetic level, psychedelics also exert an effect since they affect the transcription by
activating a small amount of 5-HT2A receptors. These are called ‘trigger neurons’, who activate
anti-inflammatory mechanisms, giving psychedelics the potential to be used in treatments for
other  disorders  such  as  Alzheimer  and  Parkinson.  These  are  diseases  where  the  immune
system  is  chronically  over  activated,  thereby  turning  psychedelics  into  potential  remedies
because of their anti-inflammatory character. This anti-inflammatory behaviour could also be
beneficial for the treatment of depression and addiction. Cytokines trigger the inflammatory
response in our body. Disturbances of these cytokines are linked to depression and anxiety-
related disorders (van Elk et al., 2022).

It is thus clear that psychedelics exert many different effects on the pharmacological level, and
it is likely that the combination of all these effects forms the basis for why psychedelics are of
interest for all kinds of disorders where depression only represents one of them.

Figure 1.3:  Representation of the different targets of psychedelics. Mainly in the pyramidal neurons of cortical
areas such as the prefrontal cortex (Cameron et al., 2023)

Looking  at  neuroscientific  explanations,  different  hypotheses have  been proposed,  namely:
the thalamo-cortical filter theory, the relaxed beliefs under psychedelics model (REBUS) and
the claustro-cortical circuit model (CCC). Overall, it appears that there is a detrimental effect
of  psychedelics  on  cognitive  and  attentional  processing,  where  the  different  theories
mentioned above can give possible explanations for this detrimental effect. The first theory,

11

the  thalamo-cortical  filter  theory  mentions  the  functioning  of  our  brain  through  feedback
loops between cortical regions and the thalamic nuclei. These loops prevent the overload of
sensory and interoceptive information. The thalamus has a filtering function since it controls
the  amount  of  signals  that  go  to  higher-level  cortical  regions.  This  filter  function  is  then
controlled by the prefrontal cortex, where psychedelics would release the inhibitory control
mechanism, meaning that there is a reduction in the inhibitory control of the prefrontal cortex
on the thalamus, which then results in an overload of information to higher-level brain regions.
These events are associated with different neural mechanisms such as an excessive stimulation
of the 5-HT2A receptors. Both PET-studies and recent fMRI studies showed that psychedelics
alter the activity and the connection between the prefrontal cortex and the thalamus. In this
model,  similarities  are  seen  with  the  psychotic  state,  which  leads  to  the  name  of
psychotomimetic model for psychedelics, since they provide some sort of psychotic state. It is
the intensification of sensory processing that bears similarities to this psychotic state (van Elk
et al., 2022).

The  second  mentioned  model,  the  REBUS  model  represents  an  integrative  account  since  it
integrates the entropic brain hypothesis with the free energy principle. Since psychedelics act
on the 5-HT2A receptors, they promote excessive excitement of deep-layer pyramidal neurons,
which encode our precision of belief. In our everyday consciousness there is this hierarchal
model  that  gives  predictions  on  sensory  input  that  enters  our  senses.  When  there  is  a
mismatch between this prediction and the input, a prediction error is generated, that in turn
will update the generative model. So, psychedelics will fail to suppress these prediction errors,
loosen  prior  predictions,  and  increase  the  sensitivity  towards  these  prediction  errors.  As
mentioned before, perceptual effects of psychedelics might appear since there is high density
of 5-HT2A receptors in the visual system. The effect of loosening prior predictions can be shown
by the ‘breathing walls’ phenomenon, here our perception of a wall is no longer constrained
by  the  prior  perception,  being  a  solid  object.  This  absence  of  the  correct  prediction  error
results in an event named visual trails, referring to the fact that moving objects leave a visual
trace (van Elk et al., 2022). When looking at higher doses of psychedelics, higher level regions
according  to  cortical hierarchy are  affected.  The Default  Mode Network plays  an  important
role here, being implicated in task-free processing such as self-referential processing. In fMRI
studies it has been shown that there is a decreased activity in this DMN during a psychedelic
experience. However, this is contradictory with other studies showing an increased activity in
prefrontal  areas.  Both  differences  relating  to  methodologies  as  the  dynamic  nature  of  a
psychedelic experience may explain these discrepancies (van Elk et al., 2022). Additionally, this
model also integrates the entropic brain hypothesis, where there is an increased connection
between brain regions that are normally not very interconnected. So, the phenomenon of the
‘entropic brain’ refers to the fact that our brain is in a state of increased disorder compared to
our normal functioning. This hypothesis helps to explain the synthetic experiences that might
be experienced under psychedelics, such as sounds inducing certain colours. Psychedelics may
have disruptive effects on attention, thereby keeping in mind that attention can be conceived
of the precision of prior expectations that shape our perception. Hence, impaired attentional
processing  is  a  result  from  less  precise  predictions  because  of  loosened  prior  predictions.
This REBUS model can partly explain the therapeutic effects of psychedelics. A disorder such
as depression is characterized by a maladaptive hyperprior, which are beliefs that are resistant
to change e.g., overly negative self-images. Other beliefs, actions and emotions are influenced
by  these  hyperpriors.  Psychedelics  temporarily  loosen  these  maladaptive  hyperpriors  by

12

directly acting on how these prior beliefs are coded in our brain. Hence, people can become
more open to new beliefs, also outside the psychedelic experience, in the following weeks and
months. Again, this model is subjected to criticism on both methodological and conceptual
level (van Elk et al., 2022).

Another  model,  the  claustro-cortical  circuit  (CCC)  is  mainly  based  on  neuroimaging
observations.  The  claustrum  is  located  between  the  insula  and  the  putamen,  and  is  highly
saturated with 5-HT2A receptors and connected to different cortical and sub-cortical regions.
This grey matter is involved in different tasks relating to cognitive control and sensory conflict.
Activation of this claustrum results in cortical activation, and the activation of the claustrum
itself is mainly driven by the prefrontal cortex, resulting in this so called claustro-cortical circuit.
Psychedelics can destabilize canonical brain network states and decouple prefrontal areas from
the claustrum. It has been suggested that  this coupling and thus coordination between the
claustrum and these prefrontal areas is important in cognitive control, whereby psychedelics
seem to disrupt this cognitive control. The effects that psychedelics have on the claustrum may
form the reason for a decrease in the executive functioning.

Summarizing what is written above, 3 frameworks are proposed for a psychedelic experience:
a  filtering  mechanism,  the  relaxing  of  beliefs  and  the  claustrum  cortical  circuit.
Next to neurological effects, psychedelics also exert different psychological mechanism where
several effects such as altered states, belief change, social effects and others can be observed
(van Elk et al., 2022).

Figure 1.4:  Location of the claustrum (A), whole-brain anatomical connectivity of the claustrum (B), and a
summary of the functions related to claustrum connections (C) (Smith et al., 2020)

13

1.5 Methods for antidepressant discovery and design
The process of drug discovery can be roughly divided into experimental, knowledge based and
computational  methods.  In  the  experimental  methods,  combinatorial  methods,  and  high
throughput  screening  (HTS)  are  popular.  In  this  combinatorial  chemistry  a  large  library  of
structurally differing molecules is synthesized, leading to a rapid lead generation, diversity, and
a cost-effective synthesis method. Thanks to HTS, this large chemical library of compounds can
be  rapidly  pharmacologically  screened  in  vivo.  Lead  identification  is  dominated  by  this
2013).
technique

(Immadisetty

al.,

et

In  the  knowledge-based  methods,  structure-activity  relationships  (SAR)  and  the  molecular
hybridization  technique  stand  central.  Biostructural  data  and  different  available  chemical
entities provide the necessary information. These SAR studies are especially relevant in the
optimization  of  a  lead  component  towards  their  specific  target  by  generating  different
structural  analogues.  A  chimeric  bioactive  compound  with  superior  characteristics  is
generated by the combination of features from different bioactive compounds, in a technique
called  molecular  hybridization.  In  this  way,  receptor  selectivity may be  improved.  However,
this method is mainly interesting for creating analogues of already existing molecules, rather
2013).
scaffolds
than

(Immadisetty

generating

novel

drug

al.,

et

The third category of methods, the computational methods are expected to take the lead in
drug discovery. High-throughput virtual screening (HTVS) forms the in-silico alternative to HTS.
Databases containing up to millions of chemical structures can be ranked according to their
predicted affinity to a certain receptor or other targets. These HTVS methods can be further
subdivided into ligand-based, structure-based and a hybrid method, combining the 2. In the
ligand-based methods, the interactions between ligands and proteins are predicted based on
structures  of  already  established  ligands  in  a  pharmacophore  approach,  without  further
information  on  the  structure  of  the  targeted  protein.  In  a  pharmacophore  approach,  the
spatial orientation of the ligand required for the biological activity is taken into account. This
is interesting when there is no information available on the binding sites because of a lack of
an X-ray crystallographic structure of the target. Compared to structure-based HTVS, this is
computationally less intensive but on the other hand, there is a reduction in the likelihood of
finding  novel  scaffolds  and  there  is  a  requirement  for  the  conformation  of  at  least  one
bioactive ligand. When there is information available on the target proteins, structural based
methods are preferred. The technique used in these methods, is ligand docking on the target.
In the absence of crystal structures, homology models are used, where the 3D structure of
evolutionary  related  structures  are  used  as  a  basis  for  alignment.  The  different  chemical
compounds present in a certain library, are docked in the site of interest of targeted proteins
and are subsequently being ranked. A force-field measuring the interaction between a ligand
and  a  protein  is  the  most  frequently  used.  Visual  inspection  is  however  required  since  the
accuracy  is  still  quite  limited.  Enrichment  of  these  studies  can  be  improved  by  the  use  of
ensemble docking, where multiple conformations of the targeted protein is used (Immadisetty
et al., 2013).

An  example  of  such  a  structure-oriented  method  for  the  synthesis  of  non-hallucinogenic
antidepressants  was  performed  by  Cao  et  al.  (2022).  Their  design  strategy  was  the
identification of structures that target the EBP and mimic the second binding pose of psilocin,
without  engaging  to  the  deep  hydrophobic  binding  pocket,  which  is  responsible  for  the

14

antagonist working action of the 5-HT2A receptor. Risperidone and ritanserin are two 5-HT2A
receptor antagonists, that both have a deep binding pose, characterized by a fluorobenzioxazol
ring and a 4-fluorophenyl group. Their moiety resembles the second binding pose of psilocin.

Other 5-HT2A receptor antagonists such as atypical antipsychotics have a similar 4-fluorophenyl
group, of whom is suspected by Cao et al. (2022) to have the same deep binding pose. Three
rigid moieties were identified for a possible binding to the EBP: the moiety from lumateperone
(IHCH-7113),  the  moiety  from  spiperone  (IHCH-7117)  and  the  moiety  from  pimozide  and
benperidol  (IHCH-7125).  The  tetracyclic  core  of  lumateperone  orients  towards  the  EBP
(revealed by analysis of crystalizing lumateperone in the receptor) and has a similar pose as
the  second  binding  pose  of  psilocin.  Just  as  risperidone  and  ritanserin,  the  4-fluorophenyl
group  from  lumateperone  is  placed  in  the  deep  hydrophobic  binding  pocket.  The  contact
between this group and residues in the proline-isoleucine-phenylalanine motif (PIP) and the
‘toggle switch’ seems to prevent a rearrangement which would be necessary to activate the
receptor and hence forms a possible explanation for the antagonist activity of lumateperone
(Cao et al., 2022).

Figure 1.5: Overview of some 5-HT2A receptor agonists evaluated by Cao et al. (2022)

IHCH-7112 (lumateperone analogue: shortening of one carbon of linker group and the removal
of the fluorine atom) was further modified by the introduction of a 2-methoxy or 2-hydroxy
substitution  on  the  terminal  phenyl  group.  In  this  way,  the  major  interaction  with  the  EBP,
determining  the  β-arrestin-bias,  was  retained  (bias  of  3.7  for  IHCH-7112),  but  an  increased
flexibility limited their binding to a conserved serine in the side extended pocket (SEP). The
most potent analogue to IHCH-7112 was e.g.. IHCH-7086 (Cao et al., 2022).

15

Figure 1.6: 5-HT2A receptor with hydrophobic binding pocket and side extended cavity (SEP) (Albujuq et al.,
2023)

In the case of LSD, it appears that there is no requirement for a hallucinogenic effect to have
an  anti-depressant  like  effect.  Components  such  as  IHCH-7086  are  supposed  not  to  cause
hallucinations  and  therefore  they  were  assessed  for  their  in  vivo  antidepressant  potential.
Acute administration of these compounds clearly decreased depression like behaviour in the
forced  swimming  test  and  the  tail  suspension  test.  Even  the  low  efficacy  of  these  5-HT2A
receptor agonists is sufficient to exert an antidepressant effect (Cao et al., 2022).

By the identification of a second binding mode of psilocybin, it was possible to do a structure-
based design of β-arrestin-biased ligands such as IHCH-7086. β-arrestin activity is a key factor
in  anti-depressant  like  behaviour,  but  it  is  insufficient  for  the  introduction  of  psychoactive
actions.

Figure 1.7: Agonist behaviour of biased ligands (Yin et al., 2023)

16

To have a hallucinogenic effect, it seems to be necessary to have a high transduction efficiency
of the 5-HT2A agonists for both G-protein-mediated signalling as the β-arrestin activity. The low
transduction  efficiency  of  these  β-arrestin-biased  ligands  is  sufficient  to  eliminate  the
hallucinogenic effect. This is illustrated in Figure 1.7, where a binding to pocket 2 mediates the
β-arrestin signalling and binding to pocket 1 mediates G-protein signalling (Cao et al., 2022).

A last method, the hybrid approach, conjugates the ligand- and structure-based approaches.
These HTVS are superior to HTS in certain aspects, since they can provide a larger screening
library and time and money is saved. But the overall reliability is still lower than HTS given its
virtual nature, and the hits found by HTVS still need to be tested in vitro (Immadisetty et al.,
2013).

1.6 Synthesis of psilocybin (analogues)
The different synthetic routes used for the synthesis of psilocybin analogues are the same as
those for tryptamine synthesis. A substitution of the indole at position 3, the creation of the
5-membered  ring  starting  from  a  functionalized  aromatic  and  a  methodology  involving
coupling reactions catalysed by different transition metals such as iridium and palladium, form
possible synthesis methods.

Hofmann  was  one  of  the  first  to  synthesize  psilocybin  in  1958.  In  this  reaction  scheme,  an
amino-ethyl  group  was  inserted  in  the  3  position  of  the  indole  core.  After  a  few  steps,  a
phosphorylation  using  O,O-dibenzylphosphorylchloride  was  performed,  followed  by  a
hydrogenation of palladium on carbon (Figure 1.8) (Hofmann et al., 1958).

Figure 1.8: Hofmann reaction scheme

The years following this synthesis, different improvements in yield and purity were obtained.
Different  phosphorylation  protocols,  for  example,  were  used.  Nichols  et  al.  (1986)  used
another  phosphorylating  agent,  tetra-O-benzyl-pyrophosphate,  which  increased  the  yield
from  20%  to  46.9%.  However,  there  appeared  to  be  a  hydrolytic  cleavage  of  one  O-benzyl

17

group  at  room  temperature,  and  in  addition  the  purification  of  psilocybin  appeared  to  be
difficult.

An adaptation of the Speeter-Anthony tryptamine synthetic pathway using Shirota’s conditions
(Figure 1.9) performed by Sherwood et al. (2022),  was able to obtain psilocybin in a high purity
(99.9%).  Therefore,  4-acetoxyindole  was  acylated  with  oxalyl  chloride,  leading  to  3.  This
intermediate 3 was then reduced with LiALH4, leading to a mixture of compounds, including a
β-hydroxy derivative. Allowing this mixture to reflux, resulted in psilocin 2 (Figure 1.10). This
was then phosphorylated using the rearrangement protocol.

Alternative  solutions  for  the  use  of  expensive  reagents  such  as  tetra-benzyl-pyrophosphate
were developed in a second-generation synthesis, where phosphorus oxychloride was used as
a replacement. This resulted in a more atom efficient process (Serreau et al., 2022).

Figure 1.9: Synthesis of psilocybin according to Shirota et al. (2003)

Figure 1.10: Synthesis of psilocin by Sherwood et al. (2022)

Psilocin can also be synthesized by metal-catalysed reactions, giving the opportunity to start
the  synthesis  from  a  wider  range  of  functional  groups.  The  indole  core  structure  can  be
obtained  via  a  palladium-catalysed  cyclization  reaction  starting  from  4-hydroxy-ortho-
iodoaniline 4 and a silylated alkyne that bears the dimethyl aminoethyl chain. The silyl group
is then removed using trifluoroacetic acid, and in a third step, the methyl group is removed

18

using boron tribromide. According to this protocol, a yield of 24% was obtained (Figure 1.11)
(Serreau et al., 2022).

Figure 1.11: Synthesis of psilocin using transition metals

A more recent approach, using the borrowing hydrogen strategy, starts from an indole 5 and
introduces the alkyl chain at the 3-position. A selective iridium-catalysed alkylation on the C3
position  of  the  indole  using  an  N-protected  ethanolamine  has  been  reported.  This
transformation was performed at 150 °C for 48 hours and caesium carbonate was used as a
base (Figure 1.12) (Bartolucci et al., 2016). However, it must be noted that these reactions with
transition metals are interesting for small scale applications but become more difficult at larger
scale seen the high cost of these catalysts (Serreau et al., 2022).

Figure 1.12: Psilocin synthesis by Bartolucci et al. (2016)

Given  the  known  difficulties  in  the  synthetic  routes  and  the  increasing  use  and  demand  of
these molecules given their therapeutic potential, solutions comprising enzymatic routes were
sought. Biocatalytic synthesis in vitro and in vivo in microbial hosts were performed by using
the  kinase  gene  for  psiK  (4-hydroxytryptamine  kinase)  that has  been  identified  in Psilocybe
mushrooms.  Hence,  the  compounds  need  to  be  extracted  from  the  matrices  to  eliminate
cellular  dishes.  To  avoid  these  issues,  a  combined  synthesis  was  developed  using  both  a
chemical  pathway  and  biosynthesis  route.  PsiK  was  first  produced  by  E.  coli.  After  psiK
conducted  the  phosphorylation  step,  another  enzyme,  an  S-adenosyl-L-methionine  (SAM)-
dependent N-methyltransferase acts twice and forms psilocybin. In this research performed

19

by Fricke et al. (2020), the dual characteristic of the enzyme psiK was discovered, namely both
its  biosynthetic  as  its  protective  role,  accepting  both  4-hydroxytryptamine  as  psilocin  as
substrates.

Fricke  et  al.  (2021)  developed  a  chemo-enzymatic  synthesis  approach,  using  the  Speeter-
Anthony tryptamine synthesis with a subsequent enzymatic phosphorylation by psiK. This is
convenient since the formation of 4-hydroxylated tryptamines is relatively straightforward, but
the subsequent phosphorylation step forms the difficult part from a chemical synthesis point
of view. With the help of ATP, the enzyme psiK originating from Psilocybe cubensis replaces the
chemical  phosphorylating  step.  The  commercially  available  5-methyl-1H-indol-4-ol  6  is
protected with an acetyl group using acetic anhydride and NaHCO3, resulting in 1H-indol-4-ol-
acetate  7.  Afterwards,  a  modified  version  of  the  Speeter-Anthony  tryptamine  synthesis
resulted  in  the  amine  substituted  derivate.  The  1H-indol-4-ol  acetate  7  reacted  with  oxalyl
chloride  and  dimethylamine  to  result  in  the  ketoamide  8.  This  was  further  reduced  using
aluminium hydride. The resulting amine 9 was incubated with the enzyme and ATP. This hybrid
chemoenzymatic synthesis of C4-C5 substituted compounds was performed, and after the in
vivo bioassay, its psychedelic like activity was shown to be retained. This encourages further
research to check for other substrates that could also be appropriate for this phosphorylation
by the enzyme, and to check whether the structure activity relationships of the disubstituted
tryptamines are retained (Fricke et al., 2021).

In this way heavy metals and expensive reagents can be avoided, yielding a synthesis route in
a greener way with reduced costs (Serreau et al., 2022).

Figure 1.13: Chemoenzymatic approach (Fricke et al., 2021)

 1.7 Concluding remarks
As  indicated  by  the  clinical  trials  regarding  psilocybin  use,  and  its  use  during  history  by
mankind, the therapeutic potentials of this compound are demonstrated. However, the fact
that it comes along with hallucinogenic effects, still forms an unwanted side effect hampering
its current use. Current research, trying the understand the mechanism of action of the drug

20

in combination with docking studies can give lead to compounds resembling psilocybin and its
derivatives. In this way, anti-depressants can be discovered without the hallucinogenic effects,
and maybe even showing enhanced therapeutic effects.

Different  synthesis  methods  can  be  used,  purely  chemical,  purely  enzymatical  or  a
combination of the 2, where difficulties concerning certain reaction steps can be overcome
using enzymes. Additionally, this can add to a greener way of producing drugs, avoiding toxic
solvents,  catalysts  and  high  energy  demands  for  the  harsh  reaction  conditions  sometimes
required.

21

2. Results and discussion

2.1 First pathway
As  has  been  extensively  discussed  in  the  literature  review,  the  search  for  new  (fast  lane)
antidepressants  is  prominent.  In  this  master  dissertation,  an  attempt  at  finding  and
synthesizing  such  molecules  was  made.  Several  molecules  analogous  to  psilocybin  were
targeted for synthesis, using different kind of pathways. It is the intention to subsequently test
these molecules for their antidepressant character and their (non)-hallucinogenic properties.
Throughout  this  master  dissertation,  different  pathways  and  methods  were  considered  in
order to obtain these analogues. Initially psilocybin analogues were aimed at synthesizing with
the intention of creating compounds, where the labile phosphate bond is replaced with a more
stable  P-C  bond,  making  the  molecule
less  susceptible  to  the  human  enzymes.
During the year, methods were frequently switched around because of several difficulties that
arose.

In the first series of attempts, psilocybin analogues with substitutions at different places of the
indole core of the molecules, formed the objective of the synthesis routes, namely 16 and 16b.
In this first series of attempts, two different starting products were used: 5-Bromo-7-azaindole
10 and 5-Bromo-1H-indazole 10b. Therefore, a substitution with a phosphoric acid group on
this  azaindole  and  indazole  ring  will  be  attempted  at  position  5.  The  motivation  behind
targeting the C-5 position was based on prior testing and evaluation of similar molecules by
Vandevelde 2023.

of

on

first

series

performed

experiments  were

The
5-bromo-7-azaindole.
In a first step, a Mannich reaction was  performed in order to substitute the azaindole-core
with a diamine group at position 3, leading to 11. The second step consists out of an oxidation
of the diamine group to a nitrogen oxide group (12). After this, the nitro ethyl group will be
reduced  to  the  amine  analogue  (13)  using  zinc.  Subsequently,  the  amine  group  should  be
transformed  into  the  dimethyl  amine  analogue  (14).  After  this,  the  bromo  atom  will  be
substituted  by  a  diethyl  phosphite  group  (15),  through  a  Hiroa  coupling.  In  a  last  step,  the
diethyl group will be hydrolysed to form the phosphoric acid analogue (16). This first pathway
is represented in Figure 2.1.

22

Figure 2.1: Reaction scheme starting from 5-Bromo-7-azaindole

This same type of strategy will be used starting from 5-Bromo-1H-indazole (Figure 2.2)

Figure 2.2: Reaction scheme starting from 5-Bromo-1H-indazole

23

2.1.1 Starting from 5-Bromo-7-indazole
2.1.1.1 Mannich reaction for the synthesis 3-(N,N-dimethylaminomethyl)-5-bromo-7-
azaindole
In a first step, 5-bromo-7-indazole is subjected to a Mannich reaction. This method is used to
synthesize β-amino carbonyl compounds by formation of carbon-carbon bonds. It involves the
use of a carbonyl donor, an amine and an acceptor aldehyde (Figure 2.3)( Córdova, 2004). The
reaction mechanism for this type of reaction is presented in Figure 2.3 and Figure 2.4. In this
case,  the  reaction  is  acid  catalysed.  First,  the  formaldehyde  is  activated  and  the  amine
performs a nucleophilic addition. Water is eliminated and the iminium ion is formed. Next, the
double bond of 10 in the five membered ring will attack the iminium ion, yielding an enamine
intermediate. This will, via an imine-enamine tautomerisation, give rise to the imine 11. Glacial
acetic acid will act as the acid catalyst and formaldehyde as the carbonyl donor.

Figure 2.3: Mannich type of reaction (Córdova, 2004)

Figure 2.4: Acid catalysed formation of iminium ion

Figure 2.5: reaction mechanism for the synthesis of 3-(N,N-dimethylaminomethyl)-5-bromo-7-azaindole

24

Figure 2.6: Mannich reaction on 5-Bromo-7-azaindole

The reaction conditions for this reaction were followed as described by Alzweiri et al. (2021).
Therefore, 10 was dissolved in acetonitrile and glacial acetic acid was added at a temperature
of  0  °C  in  a  ratio  of  3:1,  respectively.  Subsequently  formaldehyde  and  dimethylamine  were
added. The solution was stirred at room temperature for 2 hours. The resulting mixture was
basified with sodium hydroxide and extracted twice with ethyl acetate. The organic phase was
dried with magnesium sulfate and the solvents evaporated. For the purification, both normal-
and  reversed-phase  liquid  chromatography  with  different  solvent  mixtures  were  tested.
Regarding  the  normal-phase  chromatography,  solvent  mixtures  were  tested  on  silica  plates
using TLC. The solvent mixtures tested consisted out of, hexane-ethyl acetate and chloroform-
acetone in different ratio’s. The best separation of the compounds was achieved with a mixture
of chloroform-acetone in a ratio of 90:10.

In  first  instance,  the  reaction  depicted  in  Figure  2.6  was  thought  to  be  successful,  the
associated mass was indicated on LC-MS and the spectrum of the 1H-NMR analysis revealed a
peak  for  the  two  methyl  groups  and  a  CH2   peak.  However,  there  appeared  to  be  a  fourth
aromatic  peak,  which  was  first  overlooked and  thought  to belong  to  some  leftover  starting
product. But even after purification, this peak remained. Additionally, the peak belonging to
the NH of the pyrrole ring also seemed to have disappeared. From this, it was concluded that
the Mannich reaction had occurred at the N-1 position rather than the C-3 position of the 7-
azaindole
2.7).
The  mixture  was  thus  purified  using  normal-phase  chromatography  with  chloroform  and
acetone as eluents, leading to 17 instead of 11 as a white powder with an isolated yield of
63%.

(Figure

core

This observation revealed that this brominated 7-azaindole exhibits a different kind of activity
compared to the brominated indole derivatives  examined in the dissertation of Vandevelde
(2023).  In  this  way,  the N-1  alkylated 7-azaindole  instead  of  the  7-azagramine  was  formed,
which does not form the target molecule since an alkylation occurred at the incorrect position
of the 7-azaindole ring. Literature was reviewed to look for an explanation for this reaction
behaviour.

Figure 2.7: Mannich reaction on  N-1 position with formation of 1-(N,N-dimethylaminomethyl)-5-bromo-1H-
pyrrolo[2,3-b]pyridine

25

When comparing the reactivity of 7-azindole to indole at the C-3 position, there appears to be
a relative inertness of this C-3 position in 7-azaindole. Most probably this is the result of the
electron-deficient  nature  of  this  pyridine  moiety,  which  causes  a  reduction  in  the  overall
nucleophilicity  of  the  heterocyclic  system.  Other  strategies  for  a  direct  acylation  at  the  C-3
position  are  reported  in  literature,  e.g.  by  enhancing  the  nucleophilicity  of  the  7-azindole
moiety. This can be achieved by reacting an 7-azaindolyl Grignard reagent with diethyl oxalate
to form the α-keto ester (Popowycz et al., 2007).

The  replacement  of  the carbon  atom  at  position  7  of  the  indole  ring  with  a  nitrogen  atom
decreases the reactivity at the 3-position. This reactivity is even more reduced in the presence
of a Lewis or Bronsted acid. The basic strength of this 7-azaindole, with a pKa  of 4.59, is higher
than the one of indoles, with a pKa  < 1. Protonation of this nitrogen causes a lowering in the
electron availability at the 3-position compared to indoles (Kannaboina et al., 2020).

A characteristic feature of these azaindoles is that because of their fused bicyclic system, there
is a directly opposite displacement of the π-electrons in each ring. This creates a π-electron
deficient pyridine ring and a π-electron excessive pyrrole ring. An electrophilic reaction such
as a Mannich and Vilsmeier reaction is more difficult to perform on this C-3 position compared
to indoles. Additionally, substitutions on the N-1 position can have considerable effects on the
reactivity  of  this  C-3  position.  They  change  the  electron  density  and  the  ability  of  the
protonation of the nitrogen in the pyridine moiety (Yakhontov et al., 1968).

However,  the  same  type  of  Mannich  reaction  on  5-bromo-7-azaindole  was  performed  by
Brnardic (1998), and proved to be successful at the C-3 position when performed at elevated
temperatures (60 °C). This increase in temperature seems to enhance the reactivity of the C-3
position.

Even  though  the  targeted  7-azagramine  was  not  formed,  an  N1-alkylazaindole  was  formed
instead. These compounds also seem to have interesting antidepressant activities and show
promising interactions with 5-HT receptors (Dunlap et al., 2020). They are receiving increased
attention  in  medicinal  chemistry,  given  both  their  hydrogen-bond  donor  and  acceptor
in  a  broad  spectrum  of  activities  (Kannaboina  et  al.,  2020).
properties,  resulting

in

these

research

literature

reports  on

the  effects  of

Other
compounds.
Psychedelic compounds such as the N,N-dimethyltryptamines (DMT) have showed a clinical
efficacy for the treatment of depression; this molecule therefore forms an important starting
point for medicinal chemistry. Analogues of DMT have also been evaluated in this dissertation,
as will be described in section 2.3. Next to several difficulties in synthesizing DMT derivatives
in a rapid way, these DMT’s are also known to be potential hallucinogens. This is where the
it  shows  a  reduced
N,N-dimethylaminoisotryptamine  (isoDMT)  come
hallucinogenic potential and allows an easier and faster N-alkylation. They also appear to have
a comparable affinity for the serotonin receptors (Dunlap et al., 2020). Research conducted by
Glennon et al. (1984) compared the 5-HT receptor affinity for a series of isoDMT and DMT. This
study  revealed  that  the  isoDMT  appeared  to  possess  a  greater  affinity  than  the  DMT.  The
neuronal growth seems to be promoted, even in the absence of the N-H bonds. Additionally,

into  play,  as

26

because of the loss of a hydrogen bond donor (lack of NH), the polar surface area is decreased
which appears to improve the central nervous system multiparameter optimization (CNS MPO)
score (Dunlap et al., 2020). This CNS MPO, which is based on 6 physicochemical properties,
forms one of several approaches that medicinal chemists use in their decision making for the
design of novel drug candidates (Wager et al., 2016).

Figure 2.8: Chemical structure of N,N-dimethyltryptamine and N,N-dimethylisotryptamine

Thus, even though these molecules first appeared to be unwanted  side products, they may
form  even  more  interesting  compounds,  creating  new  opportunities  for  further  research.
Methods leading to the synthesis of these isoDMT’s often result in higher yields. Therefore,
the  use  of  crystallization  as  purification  instead  of  column  chromatography  could  lead  to
higher isolated yields. It also appeared that substitutions on the indole ring  did not impact
reaction  performance,  nor  did  substitutions  for  related  heterocycles  (Dunlap  et  al.,  2020).
As depicted in Figure 2.9, using 2-chloro-N,N-dimethylethan-1-amine as the alkylating agent
resulted in yields in the range of 41% to 95%, depending on the substitutions, as reported by
Dunlap et al. (2020). They suggest that the reaction proceeds through a SN2-mechanism with
negligible participation of neighbouring groups.

Figure 2.9: N-alkylation of various indoles

2.1.1.2 Synthesis of 5-bromo-3-(2-nitroethyl)-1H-pyrrolo[2,3-b]pyridine

Figure 2.10: Initial reaction for the synthesis of 5-bromo-3-(2-nitroethyl)-1H-pyrrolo[2,3-b]pyridine

27

In a subsequent step,  11 would be reacted with sodium methoxide and dimethyl sulfate to
form  the  nitro  analogue  12  (Figure  2.10).  This  reaction  would  be  performed  in  a
nitromethane/methanol  mixture  and  stirred  at  room  temperature  for  24  hours.  However,
because the formation of 11 failed, the reaction procedures were performed on 17.

Since during the course of these reactions, it was still assumed that 11 was formed instead of
17, the associated mass of 12 was sought during the follow up of the reaction using LC-MS.
Due to the match in mass associated with 12 and 18, the reaction was initially thought to be
successful. Consequently, an appropriate extraction and purification method was sought for
the  assumed  product,  12.  The  compound  was  attempted  to  be  extracted,  using
dichloromethane, followed by washing it with ammonium hydroxide (5%), hydrogen chloride
(1M), and brine. However, the compound remained in the aqueous phase. A solution of 3M
instead of 1M hydrogen chloride was used and the reaction mixture was acidified until a pH of
3  was  obtained.  Instead  of  acidifying  the  mixture,  it  was  opted  to  basify  the  mixture  with
potassium  hydroxide.  This  still  resulted  in  an  unsuccessful  extraction.  Because  of  the
difficulties during this extraction, another method was evaluated. The reaction was repeated,
and  the  mixture  was  filtered  off.  Toluene  was  then  added,  and  this  was  evaporated.  The
product was dissolved in saturated potassium hydrogen carbonate, and extracted with ethyl
acetate. This was once more washed with brine. The organic phase was dried with magnesium
sulfate,  and  the  solvents  evaporated.  Because  of  the  presence  of  several  impurities,  the
reaction mixture was subjected to a TLC analysis. Different solvent mixtures were tested, but
hexane/ethyl  acetate  (50:50),  chloroform/acetone  (80:20)  and  (90:10)  did  not  result  in  a
proper separation. Therefore, the decision was made to attempt purification with reversed-
phase chromatography using acetonitrile and water as eluents, employing a rising gradient of
acetonitrile. However, during a final analysis with  1H-NMR,  13C-NMR and 2D spectra, it was
discovered that not 19 was formed, but rather an intermediate with the same associated mass
on the LC-MS spectrum. It is assumed that the reaction stopped at the formation of 18 (Figure
2.12), resulting in an isolated yield of 35% of 18.

Figure 2.11: Reaction mechanism for the synthesis of 5-bromo-3-(2-nitroethyl)-1H-pyrrolo[2,3-b]pyridine

28

Figure 2.12: Actual course of reaction with the formation 18 as intermediate

2.1.2 Starting from 5-bromo-1H-indazole
2.1.2.1 Synthesis of 5-bromo-3-(N,N-dimethylaminomethyl)indazole with a Mannich
reaction

Simultaneously,  the  same  pathway  was  initiated,  but  starting  from  5-bromo-1H-indazole,
starting  with  a  Mannich  reaction.  Therefore,  10b    was  dissolved  in  acetonitrile  and  glacial
acetic  acid  at  0  °C  in  a  ratio  of  3:1.  Subsequently,  formaldehyde  and  dimethylamine  were
added,  and  the  solution  was  stirred  at  room  temperature  for  multiple  hours.  The  reaction
progress was followed up on LC-MS. However, analysis with 1H-NMR indicated the absence of
11b.

Figure 2.13: Mannich reaction on 5-Bromo-1H-indazole

Similar to the brominated 7-azaindole, the C-3 position of the indole did  not conduct the
nucleophilic attack on the iminium ion. The nitrogen at position 1 did, resulting in the
formation of 20 (Figure 2.14).

29

Figure 2.14: Mannich reaction with nucleophilic attack of N at position 1

2.1.2.1 Synthesis of 5-bromo-3-(N,N-dimethylaminomethyl)indazole via 5-bromo-3-
formylindazole and a reductive amination

Another type of reaction, using a Vilsmeier reagent, was also evaluated to determine if this
could lead to the synthesis of the target molecule 11b. To achieve this, the aldehyde derivative
first needed to be synthesized using a Vilsmeier reagent to yield 21 (Figure 2.15), which could
then further undergo a reductive amination leading to 11b.

Figure 2.15: Alkylation using Vilsmeier reagent

A reaction with a Vilsmeier reagent, often includes N,N-dimethylformamide (DMF) and POCl3,
where  a  Vilsmeier  reagent  is  first  formed.  This  should  then  react  with  10b  through  an
electrophilic substitution and addition reaction. The reaction mechanism is depicted below in
Figure 2.16.

30

Figure 2.16: Reaction mechanism using  Vilsmeier reagent with nucleophilic attack of C-3 position  (Valiulin,
(2020))

The Vilsmeier reagent was made by adding dropwise the POCl3 in DMF, whilst stirring for 15
minutes  between  0  °C  and  5  °C.  Compound  10b  was  dissolved  in  DMF  and  added  to  the
Vilsmeier reagent. This mixture was allowed to stir overnight. Analysis with LC-MS indicated
the  mass  associated  with  21,  but  an  1H-NMR  analysis  revealed  that  it  was  the  nitrogen  at
position 1 that reacted with the Vilsmeier reagent (Figure 2.17).

31

Figure 2.17: Actual course of reaction with the Vilsmeier reagent

The mixture was poured over crushed ice, and sodium hydroxide was added. A white/yellowish
precipitate  arose.  This  precipitate  was  filtered  off  and  recrystalized  with  hot  ethanol.  An
isolated yield of 31% was obtained for 21b.

In the subsequent step, 21b should undergo a reductive amination using a Lewis acid catalyst,
where DMF acts as the dimethylamino source, reductant and solvent.  This leads towards a
greener character of the reaction, as DMF serves multiple purposes. Currently, the majority of
reductive aminations is performed by the use of heterogenous boron hydrides or homogenous
catalytic  hydrogenation.  The  use  of  boron  hydrides  often  generates  a  lot  of  waste  and  has
multiple other shortcomings, such as its toxic nature. In organometallic hydrogenation, noble
metal  catalysts  and  complex  ligands  are often required,  which  also  tends  to result  in a  low
chemoselectivity (Yang et al., 2018).

The reaction where carbonyl compounds are reduced with ammonium formate is called the
Leuckart-Wallach reaction. However, in this reaction a temperature of 240 °C  and an autoclave
are  required.  A  reductive  amination  with  only  DMF  and  H2O  would  still  require  harsh
conditions (250 °C and an autoclave). The use of the Lewis acid is critical, since it accelerates
the hydrolysis of DMF to produce the dimethylamine and the formic acid, thereby making the
reaction conditions milder. It also promotes the imine formation by increasing the electrophilic
reactivity  of  the  carbonyl  compounds,  which  then  undergo  a  condensation  with  the
dimethylamine (Yang et al., 2018).

32

The reaction conditions for the reductive amination were followed as described by Yang et al.
(2018). The obtained crystals 21b from the previous reaction were dissolved in DMF. The most
promising catalyst according to Yang et al. (2018), the Lewis acid zinc acetate dihydrate-catalyst
(Zn(OAc)2·2H2O),  was  added  in  a  concentration of  10  mole%,  along  with  5.5  equivalents  of
water.  The  reaction  mixture  was  stirred  at  150  °C  for  24  hours  (Figure  2.18).  The  reaction
progress was followed up on LC-MS. After 24 hours, a conversion of 100% was obtained, but
according to LC-MS there was no formation of 20. The reaction mixture was however diluted
with brine and subsequently extracted with ethyl acetate. The organic phase was dried, and
the solvents were evaporated. This resulted in a red coloured oil that was dissolved in an ethyl
acetate-methanol (9:1) mixture and filtered over a silica plug.  Analysis by  1H-NMR revealed
the absence of 20.

Figure 2.18: Reductive amination of 5-bromo-1-formylindazole

Both  the  Mannich  reaction  as  the  reaction  with  a  Vilsmeier  reagent  did  not  result  in  the
formation of 11b, but led to the formation of 20 and 21b, respectively. Although they were
not the targeted molecules, as described in the previous section, these compounds may even
have better therapeutic potential and certainly form an interesting basis for future research.

Because of other ongoing research at the SynBioc Research group, attention was shifted to
another method. This method aimed at replacing the four first reaction steps of the initial
pathway (Figure 2.1) to a single step (Figure 2.19), potentially leading to the substitution of
the ring at the initial targeted C-3 position.

2.2 Introducing the borrowing hydrogen strategy
The first pathway presented in section 2.1 is here replaced by a two-step pathway in which an
amine alkylating step is followed by a phosphonylation step (Figure 2.19). In this pathway, the
first step is able to replace the first four reaction steps of the first pathway.

Figure 2.19: Reducing the first pathway to 2 reaction steps

33

2.2.1 Synthesis 5-bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-b]pyridine
by applying the borrowing hydrogen strategy
A new reaction, using the borrowing hydrogen strategy could reduce the  four first reaction
steps of the first pathway to a single step. The reaction mechanism of this protocol is depicted
in Figure 2.20. It can be used for the replacement of the Friedl-Crafts alkylation of indoles. A
poorly  reactive  alcohol  is  dehydrogenated,  and  the  created  hydrogen  equivalents  will
afterwards be consumed again for the hydrogenation of the imine.  In these types of reactions,
a  set  of  hydrogenations  is  linked  to  an  intermediate  reaction  involving  a  generated
intermediate.  In  this  strategy,  an  alcohol  (or  amine)  is  converted  to  a  carbonyl  (or  imine)
through a transition-metal catalysed dehydrogenation. This can be further condensed with an
amine,  which  can  then  be  reduced  by  the  [MH2]  species  that  was  generated  in  the  initial
dehydrogenation step (Figure 2.20). In this way the catalyst is regenerated to its active form,
and  it  forms  a  catalytic  cycle.  This  approach  enables  commodity  alcohols  to  be  used  as
alkylating agents, thereby avoiding multistep approaches and  the formation of stochiometric
2021).
side

products

(Reed

al.,

et

Figure 2.20: Mechanism of the borrowing hydrogen strategy using an alcohol and transition metal catalyst
(Reed et al., 2021)

Different  transition  metal  catalysts  were  examined  by  Bartolucci  et  al.  (2015),  but  for  the
alkylation of indoles an Iridium-catalyst, namely the pentamethylcyclopentadienyliridium(III)
chloride, dimer [Cp*IrCl2]2, proved to be the most effective.

N-acetyl  ethanolamine  functions here both as  an  amino  ethylene  alkylating  agent  and as  a
source of hydrogen, which eliminates the need for the use of an external reductant.

34

Figure 2.21: Synthesis of 5-Bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-b]pyridine

A GC-MS vial was flame dried with a Bunsen  burner to remove as much water as possible.
Afterwards,  10  was  added  to  the  vial,  along  with  caesium  carbonate,  the  catalyst
(pentamethylcyclopenta-dienyliridium(II) chloride dimer), and dimethylethanolamine, which
also serves as the solvent in this reaction. The vial was sealed and flushed with nitrogen. The
mixture was stirred at 120 °C for 48 hours, and on regular time intervals, samples were taken
and analysed on LC-MS to follow up on the reaction progress (Figure 2.21). The temperature
was chosen at 120 °C (lower than described by Bartolucci et al.), trying to reduce the formation
of the dimer side product 22 (Figure 2.22). Formation of this dimer was already visible within
30 minutes. This dimer was formed through the addition of 10 to a transient azafulvene (Figure
2.22) (Bartolucci et al., 2015)

Figure 2.22: Formation of dimer side product

After 48 hours, the reaction mixture was allowed to cool to room temperature and the mixture
was dissolved in an ethyl acetate-methanol mixture in a ratio 9:1, respectively. This residue
was filtered through a silica plug. Afterwards, this silica plug was rinsed with methanol to re-

35

move the residual product on the plug. The main fraction of the reaction product 14 was col-
lected in the first fraction that came off the silica plug along with the dimer. Several solvent
mixtures were tested with TLC to search appropriate eluents for a normal-phase liquid chro-
matography. Cyclohexane/ethyl acetate in a ratio of (10/90), cyclohexane/ethyl acetate in a
ratio  of  (30/70),  ethyl  acetate/methanol  (95/5),  and  ethyl  acetate/methanol  (90/10)  were
tested but did not result in a successful separation. A reversed-phase chromatography using
water and methanol as eluents resulted in a successful separation. An isolated yield of 85%
was obtained, where 14 was visible as a brown, beige precipitate.

The borrowing hydrogen strategy forms therefore a successful method for substituting the
molecule at the C-3 position of the 7-azaindole derivative.

2.2.2 Phosphonylation of 5-bromo-3-(N,N-dimethylaminoethyl)pyrrolo[2,3-
b]pyridine
In a subsequent step, 14 was attempted to be phosphonylated (Figure 2.23). This mechanism
involves a palladium catalysed coupling mechanism, known as the Hirao coupling (Figure
2.24).

Figure 2.23: Synthesis of diethyl (3-(2-(dimethylamino)ethyl)-1H-pyrrolo[2,3-b]pyridin-5-yl)phosphonate by a
Hirao coupling

During  a  Hirao  coupling  reaction,  dialkyl  phosphites  and  aryl  halides  are  coupled  in  the
presence  of  a  palladium  catalyst  and  a  base,  providing  the  aryl  phosphonates,  and  several
mono-  and  bidentate  P-ligands.  Instead  of  the  sensitive  and  rather  expensive  Pd(PPh3)4,
palladium precursors such as Pd(OAc)2 can be used. In this case, the active catalyst is formed
in  situ,  and a reduction of  Pd(II)  to  Pd(0)  takes  place.  This  reaction  follows  a  catalytic  cycle
where  three  classic  steps  are  followed.  First,  an oxidative  addition  of  the  aryl halide to  the
Pd(0) occurs, resulting in the formation of an intermediate complex. Then, a ligand exchange
takes place where the X-anion is replaced in the Pd-complex. Finally, a reductive elimination
generates the desired product and regenerates the active catalyst. It must be noted that both
electron donating as electron withdrawing groups substituted on the aromatic ring decrease
the  reactivity  of  the  substrate,  which  will result in  the  requirement of  more  harsh reaction
conditions (Henyecz and Keglevich, 2019). In this specific coupling, aryl bromides were used,
where X represents a bromide atom.

36

Figure 2.24: Hirao coupling reaction mechanism (Henyecz and Keglevich, 2019)

Compound 14, along with the palladium catalyst, the ligand (DPPF) and the base (potassium
carbonate), were added to a flask. The flask was sealed and flushed with nitrogen. The bottle
containing the diethyl phosphite was first flushed with nitrogen, and afterwards the diethyl
phosphite was added (Figure 2.23). The flask was once more flushed with nitrogen, reducing
the oxygen content to a minimum. The reaction was followed up on LC-MS. However, even
after 24 hours, there was still 0% conversion, as observed on LC-MS and 1H-NMR.

2.2.3 Reversing the reaction sequence
Due to the failure of this reaction sequence (Figure 2.19), it was decided to reverse the order
of the reaction. First a phosphonylation step was attempted, followed by an alkylation using
the borrowing hydrogen strategy (Figure 2.25).

Figure 2.25: Reversed reaction sequence

2.2.3.1 Phosphonylation of 5-bromo-7-azainole
For the phosphonylation, similar reaction conditions were used as described in section 2.2.2
(Figure 2.26). After 16 hours, the reaction was stopped, and the solvents were evaporated.
The residue was dissolved in ethyl acetate and filtered through a silica plug. This fraction was
collected, and methanol was subsequently used to rinse the plug. This fraction was collected
separately. Compound 23 appeared to be present in both fractions, along with a lot of diethyl
phosphite, as shown by LC-MS and  1H-NMR. However, the first fraction appeared to be the
purest. This first fraction was subjected to reversed-phase liquid chromatography, using ace-
tonitrile and water as eluents. The pure product was isolated as brown/yellow oil, with a yield
of 63%. The purity of this residue was confirmed by LC-MS and 1H-NMR.

37

Figure 2.26: Phosphonylation of 5-bromo-7-azaindole following a Hirao coupling mechanism

 2.2.3.2 Alkylation of diethyl (1H-pyrrolo[2,3-b]pyridin-5-yl)phosphonate using the
borrowing hydrogen strategy
In a subsequent step, 23 was subjected to the alkylation conditions, using the same reaction
mechanism and conditions as described in section 2.2.1 (Figure 2.27). At a temperature of
120 °C, there was still no sign of compound 15 on either LC-MS or 1H-NMR. The temperature
was raised to 150 °C, but still without success.

Figure 2.27: Alkylation of diethyl (1H-pyrrolo[2,3-b]pyridin-5-yl)phosphonate

Because of the several difficulties that were encountered during the previous experiments, it
was decided to change strategy and switch the targeted synthesis molecules.

2.3 Synthesis of 5-bromo-N,N-dimethyltryptamine followed by a
Suzuki coupling
In a new strategy, different alkylations were attempted on 5-bromo-N,N-dimethyltryptamine
(5-bromo-DMT), shifting from a 7-azaindole ring to an indole ring. In a first step, the 5-bromo-
DMT is synthesized, which will then be subjected to a Suzuki coupling using different boronic
acids.

2.3.1
reaction
The synthesis of 24 is conducted by a Fischer Indole reaction (Figure 2.28).

synthesis

Indole

Fisher

for

of

Figure 2.28: Synthesis of 5-bromo-DMT

5-bromo-DMT

38

In  this  Fischer  indolization,  the  following  steps  are  involved:  first,  a  hydrolysis  of  the
dimethylamino acetal to the hydrazone occurs. Then, an isomerization takes place, yielding
the ene-hydrazine. This undergoes a sigmatropic rearrangement, followed by a ring closure
resulting in the indole (Chen et al., 1994). These reaction mechanisms are depicted in Figure
2.29.

Figure 2.29:  Synthesis of 5-bromo-DMT following a Fischer Indole reaction mechanism (Valiulin, 2020)

The reaction conditions for this reaction were followed  as described by  Chen et al. (1994).
4-Bromophenylhydrazine hydrochloride was added together with the diethyl acetal to a 4%
sulphuric  acid  solution.  This  was  allowed  to  reflux  for  2  hours  while  being  flushed  with
nitrogen.  During  the  reaction,  a  pinkish  colour  shifted  to  a  yellowish  colour.  The  resulting
mixture was basified with 30% ammonium hydroxide. This was extracted with DCM, and the
organic layer was dried with magnesium sulfate and the solvents evaporated. Next, the residue
was dissolved in 9:1 acetone/methanol mixture, and sent over a silica plug. In this way, the
starting products were removed. The remaining fraction contained both 24 as its oxidized form
24b. This resulted in brown oil, with a conversion to 24 and 24b of 92%.

39

2.3.2 Suzuki coupling with 5-bromo-DMT
In the subsequent step, a Suzuki coupling using different boronic acids was attempted. For this,
a  palladium-catalysed  coupling  reaction  using  different  palladium  catalysts  and  bases  was
performed, following the Suzuki coupling mechanism.

In a Suzuki coupling or Suzuki Miyaura reaction, organohalides are treated with organoborane
compounds  and  a  palladium  catalyst.  In  these  reactions,  new  C-C  bonds  are  formed.
Additionally, a base is added to increase the reaction rate. This reaction is both stereo and
regiospecific, maintaining the stereochemistry of the reactants in the products. The reactivity
of organohalides decreases in the following order: alkenyl halides > aryl halides > alkyl halides.
For  the  halogens,  in  decreasing  order  this  becomes:  iodides  >  bromides  >  chlorides.  The
hybridization  of  the  carbon  adjacent  to  the  boron  atom  in  the  organoboron  species  will
influence  through  the  steric  factor.  Sterically  hindered  compounds  react  slower  than  the
unhindered alternatives. In general, a B-C(sp3) carbon will be more sterically hindered than a
B-C(sp) carbon. In decreasing order regarding the reactivity, this yields: B-C(sp) > B-C(sp2) > B-
C(sp3) (Verma et al., 2023).

Similar to the Hirao coupling, a Pd(0) catalyst is required. This catalyst can already exist in the
active state or be a Pd(II) catalyst that will be activated in situ with the help of a ligand.

As depicted in Figure 2.30, a sequence of an oxidative addition and trans metallisation allows
for  a  cross-coupling  of  the  components.  This  type  of  reaction  allows  for  mild  reaction
conditions,  using  relatively  environmentally  friendly  boron  reagents  and  palladium(II)
complexes (Lennox et al., 2014).

Figure 2.30: Catalytic cycle of the Suzuki coupling with boronic acids (Lennox et al., 2014)

40

Figure 2.31: Overview of the different boronic acids

The different boronic acids used in the coupling reactions were the following: phenylboronic
acid  25a,  4-methylphenylboronic  25b  acid,  2,6-dimethylphenylboronic  acid  25c,  4-tert-bu-
tylphenyl boronic acid 25d, 4-biphenylboronic acid 25e (Figure 2.31).

A first attempt of this Suzuki coupling was performed with palladium acetate as the catalyst,
and potassium hydroxide as the base. This was initially conducted on the simplest boronic acid
present in the lab, phenylboronic acid 25a.

Figure 2.32: Synthesis of N,N-dimethyl-2-(5-phenyl-1H-indol-3-yl)ethan-1-amine via Suzuki coupling reaction

An example of a Suzuki coupling using 5-bromo-indole and 25a was described by Shao et al.
(2015).  They  used  Pd(PPh3)4  as  the  catalyst,  potassium  phosphate  as  the  base,  and  a
combination of DME and water as solvents, ensuring all the reagent were dissolved. Because
of the absence of DME in the lab, these conditions with solely water as a solvent were tested.
However, this resulted in an improper dissolution of the reagents. Therefore, a combination of
water and tetrahydrofuran (THF) was used instead. In the first attempt, Pd(PPh3)4 was replaced
by the cheaper Pd(OAc)2 without the addition of additional ligands.

The reaction conditions were as follows: 24 was diluted in THF, while potassium hydroxide, the
palladium  catalyst,  and  the  boronic  acid  were  first  dissolved  separately  in  water.  The  two
mixtures were added together and flushed with nitrogen. The reaction was stirred for 16 hours
at 60 °C under nitrogen atmosphere (Figure 2.32). The reaction was stopped, and the residue
was  diluted  with  water  and  extracted  with  ethyl  acetate.  Purifications  using  normal-phase
liquid  chromatography  were  attempted  but  proved  unsuccessful.  Afterwards,  a  purification
using reversed-phase liquid chromatography using water and methanol as eluents resulted in
a successful separation. Compound 26 was isolated as a brown oil with a yield of 64%.

Using similar reaction conditions, the other boronic acids were  evaluated as well. However,
this proved unsuccessful for the coupling of 25c and 25d. In order to tackle this, literature was
reviewed  for  different  reaction  conditions.  Zhou  et  al.  (2016)  performed  a  Suzuki-Miraya
coupling using aryl chlorides and boronic acids, evaluating different reaction conditions. Since
the reactivity of aryl chlorides is generally lower than those of aryl bromides, these conditions

41

could be evaluated. The most efficient conditions according to Zhou et al. (2016) appeared to
be the use of [Pd2(dba)3] as a catalyst, sodium phosphate as the base, and DME as solvent
medium.  Other  conditions,  described  by  Suzuki  (2004),  reported  the  use  of  potassium
carbonate, and Pd(PPh3)4 as a base in reactions with aryl iodides.

Figure 2.33: Overview of the different Suzuki coupling with different reaction conditions, tested on different
boronic acids

Reaction conditions using Pd(PPh3)4 and Na2CO3  were tested and proved more successful with
the other boronic acids (Figure 2.33). For the solvent mixture, a combination of toluene, water,
and ethanol was chosen to dissolve all the compounds. At a temperature of 60 °C, the progress
of the reaction was followed up using LC-MS. After 24 hours, the conversions and yields are
depicted in table 3-1. However, instead of the desired reaction product, another oxidated form
was  created.  The  reagent  24  as  well  as  the  desired  reaction  products  (25a,b  and  d)  were
oxidized (Figure 2.34).

42

Table 3.1: Overview of reaction progress of the different Suzuki coupling reactions

Product

Reaction conditions  Yield

26a

26a

26b

26c

26c

26d

26d

Pd(OAc)2, KOH,
THF:H2O
Pd(PPh3)4, Na2CO3,
EtOH:H2O:toluene
Pd(PPh3)4, Na2CO3,
EtOH:H2O:toluene
Pd(OAc)2,
THF:H2O
Pd(PPh3)4, Na2CO3,
EtOH:H2O:toluene
Pd(OAc)2,
THF:H2O
Pd(PPh3)4, Na2CO3,
EtOH:H2O:toluene

KOH,

KOH,

0%

0%

54%

0%

0%

0%

0%

to

Conversion
oxidized
product
35%

39%

3%

0%

0%

0%

11%

To tackle this side product formation, the oxidized compounds were attempted to be reduced
(Figure 2.35). Therefore, the residues of the Suzuki reactions were dissolved in a mixture of
acetic acid and methanol. Activated zinc dust was used, therefore the zinc dust first needed to
be  activated.  This  was  performed  by  stirring  the  zinc  dust  in  hydrogen  chloride  with  a
concentration of 1M. The zinc dust was filtered off and washed with distilled water, ethanol,
and  anhydrous  diethyl  ether  before  it  was  rigorously  dried.  In  this  way,  the  oxides  on  the
surface of zinc are removed which can be formed upon standing in air. The zinc dust was added
in 1.2 equivalents, and allowed to stir for 2 hours at room temperature. The reduction proved
successful for the oxidized unreacted form of the reagent 24b, but remained unsuccessful for
the oxidized products (27,28,29).

Figure 2.34: Oxidized compounds

43

Figure 2.35: Reduction of oxidized compounds using activated zinc dust

Because  of  progress  of  other  ongoing  research  at  the  SynBioc  research  group,  and  the
difficulties  encountered  during  the  synthesis  and  purification  of    these  compounds,  it  was
opted  to  combine  this  strategy  with  the  parallel  synthesis  of  other  5-HT2A  agonists,  β-
carbolines.

2.4 β-carbolines, another group of tryptamine-like compounds
The  type  of  compounds  described  in  this  chapter  belong  to  the  category  of  β-carbolines,
whereof  their  base  skeleton  is  depicted  in  Figure  2.36.  These  are  compounds  with  a  high
potential  for  the  treatment  of  several  types  of  neurological  diseases,  such  as  Alzheimer,  a
chronic  neurodegenerative  disorder  in  need  of  new  treatment  possibilities.  Similar  to  the
Psilocybin analogues, these compounds also bind to the 5-HT receptors. These compounds are
heterocyclic amines, derived from tryptophan, which can be found in several plants and animal
tissues. They are again resembling human tryptamine-based neurotransmitters like serotonin.
Because of this resemblance but also because of the increased rigidity due to the additional
ring, they can be synthesized and used as bioactive compounds for targeting several central
nervous systems. They interact with a variety of enzymes and are able to inhibit certain brain
enzymes.
In current research, their main focus is on the treatment of Alzheimer's disease (Beato et al.,
2021).

Figure 2.36: Carboline alkaloid skeleton (Szabó et al., 2021)

Many methodologies have already been described in literature to synthesize  these sorts of
compounds. One of the most important procedures that has been described is the Bischler-
Napieralski  reaction,
in  which  3,4-dihydro-β-carbolines  are  synthesized  starting  from
tryptamine. This is a cyclization type of reaction, requiring harsh conditions and reagents such
as POCl3 or P2O5 in solvents with high boiling points. Over the last decades, milder reaction
conditions  have  been  established  for  this  type  of  reaction  (Abranyi-Balogh  et  al.,  2016).
To current date, the Pictet Spengler reaction forms one of the most important synthesis routes.
This  type  of  reaction  is  a  condensation  reaction,  giving  rise  to  tetrahydro-β-carbolines
(THBC’s),  which  can  be  further  dehydrogenated  to  the  associated  β-carboline  alkaloids.

44

However,  due to different  issues  with  polyfunctional  aldehydes  such  as  their  low  yield,  the
scope of this kind of reaction for more complex derivatives is limited (Pakhare et al., 2015).

This Pictet-Spengler reaction is a condensation type of reaction that was discovered by Pictet
and Spengler and forms one of the most important synthesis routes for alkaloid scaffolds. The
power  of  this  reaction  lies  in  the  ability  to  construct  stereochemical  and  complex  alkaloid
molecules. It was in 1911 that Pictet and Spengler discovered that when β-phenylethylamine
and  formaldehyde  were  heated  with  hydrochloric  acid,  they  underwent  a  cycloaddition
reaction. It took 20 years before tryptamine was used as the amine compound. Tatsui was the
first in 1928, resulting in the formation of the tetrahydro-β-carboline skeleton. This forms a
key  structure  element  for  complex  synthetic  products  and  natural  compounds  such  as
isoquinolines  and  indole  alkaloids.  To  develop  different  kinds  of  these  molecules,  both  the
amine compound and the aldehyde (as in the original reaction) can be varied. Over the last
few decades, there has been a large progress in the development of highly enantioselective
methods for these THBC’s by the use of enzymes, which are called the Pictet-Spenglerases. In
the biosynthesis of morphine, an enzyme catalysed Pictet-Spengler condensation step is the
key in the synthesis route (Stöckigt et al., 2011).

When  the  Pictet-Spengler  reaction  is  conducted  with  an  amine  and  an  aldehyde,  an
intermediate 30 is formed. This will then transform into the iminium ion 31, which will undergo
an  electrophilic  attack,  resulting  in  a  tetrahydropyridine  moiety  32  (Figure  2.37).  This
represents the classic Pictet-Spengler reaction (Calcaterra et al., 2020).

Figure 2.37: Pictet-Spengler reaction (Calcaterra et al., 2020)

A modification using a nitril and a tryptamine under hydrogenating conditions already solved
a few of the issues. This is the type of reaction that was also evaluated in this dissertation. It
should  be  mentioned,  however,  that  using  aldehydes  or  carboxylic  acids  represents  other
al.,  2015).
forms  of

(Pakhare  et

the  Pictet

type  of

Spengler

reaction

As  described  by  Pakhare  et  al.  (2015),  the  following  reaction  conditions  were  used:  a
tryptamine derivative was reacted with a nitril, palladium on activated carbon (10%)  was used
as a catalyst under a hydrogen atmosphere in acetic acid. Subsequently, the formed THBC’s
were dehydrogenated using potassium permanganate. In the aromatization step, they opted
not  to  use  the  Pd/C  catalyst  because  of  the  risk  of  breakage  of  the  ring  during  this
step.
dehydrogenation

45

The molecules aimed at synthesizing in this master dissertation, were obtained by research at
the  SynBioc  research  group.  These  β-carbolines  were  clustered  in  5  clusters  by  comparing
different characteristics. These 5 clusters are presented below (Figure 2.38).

Figure 2.38: Representation of the 5 clusters of β-carbolines

For each one of these clusters, one molecule will be attempted to be synthesized. A first step
using a Pictet-Spengler reaction, followed by an aromatization step.

Figure 2.39: Synthesis of β-carbolines with Pictet Spengler reduction using nitriles, followed by an aromatization
step

46

Figure 2.40: Synthesis of β-carbolines with Pictet Spengler reduction using aldehydes, followed by an
aromatization step

Because of the time limitation, it was opted to evaluate Pictet-Spengler reactions with amines
and nitriles (Figure 2.39). The reaction procedure for this reaction was followed as described
by Pakhare et al. (2015). The amine compound, specifically tryptamine, was dissolved in acetic
acid,  to  which  the  nitril  and  palladium  on  activated  carbon  (Pd/C  10%)  were  added.  This
mixture  was  hydrogenated  and  stirred  at  room  temperature  under  a  hydrogen  balloon
atmosphere for 24 to 40 hours. The course of the reaction was followed on LC-MS. After the
reaction had  run to  completion,  the  catalyst  was  removed  by  filtration  over  celite,  and  the
product purified by chromatography.

2.4.1 Synthesis of tetrahydro-β-carbolines
This first step was performed for the 5 clusters. The reaction conditions were first evaluated
for  the  synthesis  of  Eudistomin  U,  the  most  simple  possible  β-carboline,  starting  from
tryptamine 33 and 1H-indole-3-carbonitril 34, resulting in the formation of 35 with a yield of
37% (Figure 2.41).

Figure 2.41: Synthesis of the THBC of Eudistomin U

The same reaction was performed with the use of a hydrogen generator, where the applied
pressure of the hydrogen gas could be adopted. A pressure of 2 bars was tested to determine
if this could result in a higher yield. This was however, not the case.

47

A  similar  reaction  was  conducted to  yield  the  THBC’s  of  the  five  clusters.  For  cluster  1,  the
fluorinated tryptamine 36 was reacted with 34, using similar reaction conditions as described
above (Figure 2.42). This was performed both in a flask with a hydrogen balloon creating a
hydrogen atmosphere, as with a hydrogen generator, with a pressure of 5 bar. Respectively
resulting in a yield for 37 of 11% and 5%.

Figure 2.42: Synthesis of 7-fluoro-1-(1H-indol-3-yl)-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole (cluster 1)

For cluster 3, this comes down to reacting tryptamine 33 with 38 (Figure 2.43). Again both a
hydrogen atmosphere created with a balloon and the use of hydrogen generator at 5 bars were
evaluated. However, both setups proved unsuccessful and resulted in a conversion of 0%.

Figure 2.43:  Synthesis of 1-(6-bromopyrazolo[1,5-a]pyrimidin-3-yl)-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole
(cluster 3)

Similarly, for cluster 4, tryptamine 33 was reacted with the carboxylate 40,  resulting in 41 with
a yield of 16% and 5%, using the hydrogenator at 2 bar and the hydrogen balloon, respectively
(Figure 2.44).

Figure 2.44: Synthesis of methyl 3-(2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indol-1-yl)-1H-indole-6-carboxylate
(cluster 4)

Finally, the same was performed for cluster 5, where the methoxy substituted tryptamine 42
was reacted with 34, resulting in 43 with a yield of 75% using a balloon to create a hydrogen
atmosphere (Figure 2.45). This reaction resulted in the highest yield. In order to purify 43, it
was  opted  to  perform  a  normal-phase  liquid  chromatography  using  DCM  and  methanol  as

48

eluents in a ratio of 95:5, yielding the pure tetrahydro-β-carboline 43 with an isolated yield of
35%. This according to Santhanam et al. (2020).

Figure 2.45: Synthesis of 1-(1H-indol-3-yl)-6-methoxy-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole (cluster 5)

Similar purification conditions were also tested to purify 37 and 41, but the attempts remained
unsuccessful, neither did a reversed phase-chromatography.

Due to the failure of chromatographic purification of 37 and 41, efforts were made to achieve
a higher conversion by increasing the reaction temperature. This was done in the hope that
potentially a crystallization step could be performed, leading to a successful separation. At an
elevated temperature of 50 °C using similar reaction conditions as depicted in Figure 2.43 and
Figure  2.45,  a  conversion  and  yield  for  37  and  41  were  18%  and  4%  and  40%  and  11%,
respectively.

2.4.2 Dehydrogenation of tetrahydro-β-carbolines to the β-carbolines
The next step for the synthesis of these β-carbolines, consists out of an aromatization of the
THBC’s. Initially, the reaction conditions described by Pakhare et al. (2015) were  evaluated,
using  palladium  on  activated  carbon  at  elevated  temperatures.  This  was  tested  on  the
tetrahydro-β-carboline derivative 44 (cluster 5). Therefore, 44 was added to toluene, and the
mixture  was  allowed  to reflux  for  24  to  30  hours  (Figure 2.46).  However,  44 dissolved  very
poorly in the toluene and only a partly dehydrogenation of 6% took place.

Another  approach  for  this  step,  also  described  by  Pakhare  et  al.  (2015),  involved  using
potassium  permanganate.  Therefore,  44  was  dissolved  in  acetone  and  4  equivalents  of
potassium permanganate were added. This was stirred at room temperature (Figure 2.46). The
reaction was monitored on LC-MS. After 4 hours, a partly dehydrogenation of 17% took place.

49

Figure 2.46: Aromatization of 1-(1H-indol-3-yl)-6-methoxy-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole

Again, another setup for this aromatization was evaluated. Stöckigt et al. (2011) performed an
aromatization of  THBC’s using of N-methylpyrrolidon (NMP) at elevated temperatures. These
conditions were also evaluated (figure 2.47). The reaction was monitored on LC-MS, but this
did not result in an increase of (partial) dehydrogenation.

50

3. Conclusion and future perspectives

3.1 Summary and conclusion
During the course of this dissertation, the target molecules were shifted several times. Initially,
the primary aim was to synthesize psilocybin analogues with an additional nitrogen atom in
the indole ring and a phosphonate group at the 5-position. In this way, the labile P-O link in
psilocybin is replaced by a more stable P-C bound, making the molecule less susceptible to the
degradation of human enzymes. This choice of the 5-position was made because of the results
of previous master’s dissertations at the Synbioc Research group, demonstrating an enhanced
activity at the receptors responsible for the depressive/antidepressive behaviour. Two types
of analogues were targeted: one with a nitrogen at position 7 in the indole ring (7-azaindole
core) and one indazole analogue. The alkylations occurred at the N-1 position instead of the
C-3 position, giving rise to difficulties from the beginning. However, in further literature review
it appeared that substitutions at this N-1 position, even though these were initially undesired,
could provide a basis for other compounds with potentially even superior therapeutic effects.
In this way, developing analogues with alkylations at the N-1 position, such as the iso-DMT
analogues, might form an interesting topic for further research.

The initial pathway was eventually replaced by another one, representing a shortcut of the
first. The first step in this pathway employs the borrowing hydrogen strategy, that was able to
successfully facilitate the alkylation at the initially targeted C-3 position.  Depending on the
reaction type and conditions applied, 7-azaindole and indazole will behave in a different way
compared  to  indoles.  In  this  second  pathway,  the  substituted  azaindole  rings  encountered
difficulties  with  phosphonylation.  Even  when  the  reaction  sequence  was  reversed,  the
synthesis of the targeted compounds remained unsuccessful.

Due  to  these  challenges  with  the  7-azaindole  derivatives,  the  strategy  was  altered  to
synthesizing  psilocybin  analogues  without  the  additional  nitrogen  in  the  indole  ring.  By  a
Fischer  indole  synthesis,  5-bromo-DMT  was  synthesized.  This  was  followed  by  a  Suzuki
coupling with boronic acids, which encountered issues with oxidation of the desired products.
Attempts  at  reductions  remained  to  a  large  extent  unsuccessful.  At  the  same  time,
developments  in  other  research  at  the  Synbioc  Research  group  led  to  a  refocus  on  newly
acquired  knowledge.  Using  computational  methods,  five  clusters  of  β-carbolines  were
identified.  Synthesizing  the  molecules  from  the  five  clusters  varied  significantly  from  the
methods  that  had  been  used  earlier  in  this  dissertation.  A  Pictet-Spengler  reaction  was
successful for compounds from three clusters, with one of the compounds being successfully
purified. However, the aromatization of the THBCs has not yet been successful.

To conclude, reactions with azaindoles or indazoles will lead to different outcomes compared
to  those  with  indoles  due  to  their  different  reactivities.  Concerning  the  synthesis  of  β-
carbolines,  the  initial  steps  regarding  the  synthesis  of  THBC’s  are  promising,  but  further
research  is  necessary  to  come  to  a  successful  aromatization  of  these  compounds  to  their
corresponding β-carbolines.

3. 2   Future  perspectives
Because of the rising prevalence of depression and the increase of age-related neurological
diseases,  major  depressive  disorder  and  other  neurological  disorders  are  becoming

51

increasingly  problematic.  Different  kinds  of  natural  molecules  such  as  psilocybin  and  β-
carbolines have promising therapeutic potential for these type of disorders.

For a precise targeting of the receptors and their specific interactions, it’s important to use
computational methods, such as docking studies. Potentially powerful therapeutic compounds
can be developed by synergies of different scientific disciplines. This has been demonstrated
by the  development  of  the five  β-carboline  clusters.  It  is  up  to further  research  to  develop
appropriate  aromatization  methods  for  the  conversion  of  the  tetrahydro-β-carbolines  into
their corresponding β-carbolines. Once these compounds have been synthesized, they can be
subjected to further biological testing.

52

4. Material and methods
During the synthesis procedures, there has been made use of commercially available solvents
and reagents, purchased from Sigma-Aldrich®, Acros Organics®, Apollo scientific® and TCI®.
The demineralized water was obtained by using an Aquadem ion exchanger 22DF type on tap
water.

1. Automatic Flash Column chromatography
In  automatic  flash  chromatography,  different  compounds  can  be  separated  and  purified
because of their differing affinities towards the mobile and stationary phase. There are 2 types
of  chromatography  used  here,  the  normal-phase  chromatography  and  reversed-phase
chromatography.  In  the  normal-  and  reversed-phase  chromatography,  the  stationary  phase
consists out of silica or C-18 contained in a cartridge. For different weights of the samples,
different cartridge sizes are used. The compounds are detected based on their UV absorption,
which can be determined by the LC-MS.

A  Büchi  Pure  C-815  flash  chromatography  system  was  used  to  perform  normal-phase
automatic flash chromatography. This NP Flash system includes a UV detector (200 – 400 nm)
that can monitor four wavelengths simultaneously as well as an evaporative light scattering
detector (ELSD). The ELSD can monitor compounds that are non-volatile that do not absorb
UV,  enabling  the  detector  to  detect  the  non  UV-absorbing  compounds  and  offering  the
addition of using a mobile phase that absorbs light at the same wavelength as the compound
of interest.

A  Reveleris  flash  chromatography  system  is  used  to  perform  the  reversed-phase  automatic
flash chromatography. In this Reveleris system, there is also a UV-detector built in (200 – 400
nm) that can monitor two wavelengths simultaneously. Additionally, for compounds being non
UV  active,  evaporative  light  scattering  (ELSD)  can  also  be  detected,  also  by  a  built  in  ELSD
detector.

2. Dry Solvents
An  MBraun  SPS-800  solvent  purification  system  was  used  generating  dry  solvents.  In  this
dissertation,  the  system was  used  for  dry toluene  and  THF.  The  solvents were  contained  in
Pure-Pac containers of 17 L, pressurized with nitrogen gas and eventually passed through 2
filtration and drying columns. These columns have an internal volume of 4.8 L and consist out
of stainless steel (1.4301/ US 304) with molecular sieves, tuned to the solvent passing the tube.
After  the  purification  and  drying,  the  solvents  are  collected  in  glass  recipients  under  inert
atmosphere, created by membrane pumps of the type MPC 301 Zp.

3. Liquid chromatography coupled with Mass Spectrometry
In a Liquid Chromatography–Mass Spectrometry system (LC-MS), mixtures can be separated
and products can be identified on both UV and MS. It allows for the follow-up of reactions,
measurement  of  m/z,  determination  of  the  purity  of  a  sample,  measurement  of
concentrations of compounds, preparation of samples for direct inlet MS and HRMS, or as an
alternative to a TLC-analysis. In this system, there is a reversed set up, meaning a polar mobile
phase and an apolar stationary phase. The apparatus is equipped with 4 polar solvents: water,
acetonitrile, methanol and isopropanol.  An Agilent 1200 Series HPLC with a Supelco Ascentic

53

Express C18 column (3 cm x 4.6 mm, 2.7 µm fused-core particles, 90 Å), a Phenomemnex guard
column (SecurityGuard Standard) and a UV-DAD detector was used. This system is coupled to
an  Agilent  1100  Series  MS  with  electrospray  ionization  (70  eV)  with  a  single  quadrupole
detector. A combination of water and acetonitrile (30% to 100% in water) was the mainly used
mobile phase, but other gradient and mixtures are also possible.

4. Mass Spectrometry
As described above.

5. Nuclear Magnetic Resonance Spectrometry (NMR)
A Bruker Avance III HD Nanobay spectrometer, equipped with z 1H/BB z-gradient probe (BBO,
5 mm), was used to obtain the 1H-NMR and  13C-NMR spectra. The spectra were obtained at
400  MHz  for  the  1H-NMR  and  100.6  MHz  for  the  13C-NMR.  For  dissolving  the  samples,
deuterated solvents were used (CDCL3, MeOD) with tetramethylsilane (TMS) as the internal
standard.  For  assigning  the  signals,  2  dimensional  spectra  were  also  generated,  at  night  or
during the weekend because of time management. All spectra were processed using TOPSPIN
3.2. The spectra were acquired through the standard sequences available in the Bruker pulse
program library. Other types of spectra could be achieved by custom settings.

6. Infrared Spectroscopy (IR)
A  Shimadzu  IRAFFINITY-1S  Fourier  Transform  Infrared  Spectrophotometer  with  a  signal-to-
noise ratio (S/N) of 30 000:1 was used to obtain the infrared spectra from neat samples. A
(FTIR)Quest ATR (Attenuated Total Reflectance) accessory with diamond crystal pucks was also
contained in the spectrophotometer.

7. Thin layer Chromatography (TLC)
Suitable solvent mixtures in combination with silica plates with a glass back (Merck Silicagel
60  F254,  precoats,  25  mm  thickness)  were  used  for  this  type  of  chromatography.  The
compounds in this dissertation could be visualized at an UV irradiation of 254 or 365 nm. This
type of chromatography was used to follow up on reactions and to find appropriate solvent
mixtures for column chromatography.

8. Hydrogen generator
In the hydrogen generator, hydrogen gas is provided up to 5 bar. The pressure is indicated in
barg (pressure in excess of atmospheric pressure). To ensure suitable hydrogen conditions, the
machine is first flushed three times with hydrogen.

54

5. Safety
Before starting this dissertation, students have been informed about several risks and hazards
linked to working in a lab environment. Before getting into practice, a safety test had to be
passed before access to the lab was granted. Three documents concerning the safety had to
be signed, this included the internal guidelines of the research group, a document describing
safe  handling  of  different  classes  of  compounds,  and  the  wellbeing  and  environmental
university.
guidelines
All practices in the lab were performed wearing the appropriate protective clothing, such as a
lab coat and glasses. Hair was tight up, and long trousers with closed shoes were mandatory.
When work was performed with hazardous substances, protective gloves were worn. Because
of the toxic nature of certain reagents and products, reactions took place in hoods to provide
as much protection as possible. In what follows, the risks and hazards of the most hazardous
reagents that were used in this dissertation will be described.

Ghent

of

1,1'-Bis(diphenylphosphino)ferrocene  (Dppf)  -  yellow-orange  powder  that  causes  skin  and
serious eye irritation.

2,6-Dimethylphenylboronic acid - white crystalline powder that is harmful when swallowed,
causes skin and serious eye irritation, and may cause respiratory irritation.

4-bromophenylhydrazine hydrochloride - beige/white powder that causes severe skin burns
and eye damage.

4-Biphenylboronic acid - white powder that is harmful if swallowed, causes skin irritation and
serious eye irritation, and may cause respiratory irritation.

4-tert-Butylphenylboronic acid - white/off-white crystalline powder, causing serious eye and
skin irritation and may cause respiratory irritation.

5-bromo-1H-indazole - white crystalline powder that may cause respiratory irritation, is toxic
if swallowed, causes serious eye irritation and skin irritation.

5-bromo-1H-pyrrolo[2,3-b]pyridine-3-carbaldehyde - white/yellow solid that causes skin and
serious eye irritation.

5-Bromo-N,N-dimethyltryptamine - crystalline solid causing skin and serious eye irritation and
may cause respiratory irritation.

5-bromo-7-azaindole  -  white/yellow  crystalline  powder  that  can  cause  serious  eye
damage/irritation, is corrosive to the skin and causes acute oral toxicity.

Acetonitrile - colourless liquid that is highly flammable, harmful if swallowed or inhaled and
causes serious eye irritation.

Ammonium  hydroxide  (NH4OH)  -  colourless  aqueous  solution,  that  may  be  corrosive  to
metals, causes skin burns and eye damage, may cause respiratory irritation and is very toxic to
aquatic life.

Caesium  carbonate  (Cs2CO3)  -  white  crystalline  solid  causing  serious  eye  damage  and  may
cause damage to organs at prolonged or repeated exposure.

55

Celite  -  grey/white  powder  with  a  small  particle  size,  with  specific  organ  toxicity  (lungs)
through prolonged or repeated exposure when inhaled.

Diethyl ether - clear, colourless extremely flammable liquid that is harmful when swallowed
and may cause dizziness.

Diethyl  phosphite  -  colourless  liquid  that  may  cause  an  allergic  skin  reaction  and  causes
serious eye damage.

Dimethylethanolamine - colourless flammable liquid that is harmful when swallowed, causes
severe skin burns and eye damage, is toxic if inhaled and is harmful to aquatic life.

Dimethyl sulphide - colourless flammable liquid that causes serious eye damage/irritation.

Dimethylamine  -  colourless  gas  that  causes  severe  skin  burns  and  eye  damage,  may  cause
respiratory irritation and is harmful when swallowed or inhaled.

Formaldehyde  -  gas  contained  in  a  colourless  liquid  that  is  acutely  toxic  when  inhaled,
swallowed or when it comes into contact with the skin, and causes damage to the eye. It's a
flammable liquid.

Glacial acetic acid - colourless liquid that causes severe skin burns and eye damage.

Hydrochloric acid (HCl) - colourless liquid that is highly corrosive, causes severe skin burns,
and eye damage.

Indole-3-carbonitrile - off-white powder that is harmful when swallowed, causes skin and eye
irritation, and may cause respiratory irritation.

Methanol - colourless liquid that is highly flammable, causing acute toxicity if swallowed or
inhaled.

NaOMe - white powder that causes severe skin burns and eye damage, is toxic if swallowed or
when it comes into contact with skin or when inhaled.

Nitromethane - colourless oily flammable liquid that is suspected of causing cancer and the
fertility or the unborn child.

N,N-Dimethylformamide (DMF) - flammable colourless liquid that causes serious eye irritation
and is harmful when in contact with the skin or when inhaled.

Pentamethylcyclopentadienyliridium(III) chloride, dimer ([Cp*IrCl2]2) - orange/red coloured
powder that causes skin and serious eye irritation.

Phenylboronic acid - white powder that is harmful when swallowed.

Pd(OAc)2 - red-brown solid crystals, causes serious eye damage and may cause an allergic skin
reaction, and is very toxic to the aquatic environment.

POCl3 - colourless liquid that may be corrosive to metals, is harmful if swallowed, causes severe
skin burns and eye damage, is fatal if inhaled, and causes damage to organs at prolonged or
repeated exposure.

Potassium carbonate (K2CO3) - white solid that causes skin and eye irritation.

56

Potassium hydroxide (KOH) - white solid that may be corrosive to metals, is harmful when
swallowed, causes severe skin burns and eye damage, and can cause respiratory irritation.

Silica  -  white  powder  that  may  cause  damage  to  the  lungs  through  prolonged  or  repeated
exposure when inhaled because of its small particle size.

Sodium Carbonate (Na2CO3) - white hygroscopic solid causing serious eye irritation.

Sulphuric  acid  -  used  in  solution  as  a  colourless  liquid,  may  be  corrosive  to  metals,  causes
severe skin burns and eye damage, may cause cancer when inhaled and it is harmful to aquatic
life.

Tetrahydrofuran (THF) - clear colourless highly flammable liquid, causes acute oral toxicity and
serious eye irritation, is carcinogen and has a specific target organ toxicity.

Tetrakis(trifenylfosfine)palladium(0) (Pd(pph3)4) - yellow/brown powder that is harmful when
swallowed.

Tripotassium  phosphate  (K3PO4)  -  white  powder  that  causes  serious  eye  damage  and  may
cause respiratory irritation.

Toluene - clear, colourless highly flammable liquid that may be fatal if swallowed, causes skin
irritation and may cause dizziness, may cause damage to the organs, and is harmful to aquatic
life.

Tryptamine - pale white to yellow needles, that are harmful when swallowed, cause serious
eye damage and may cause an allergic skin reaction.

Zinc acetate dihydrate (Zn(OAc)2.2H2O) - white crystals that are harmful when swallowed and
cause serious eye damage.

Zinc dust - grey dust that is hazardous to the aquatic environment.

57

6. Experimental section
1-(5-bromo-1H-pyrrolo[2,3-b]pyridin-1-yl)-N,N-dimethylmethanamine

1H-NMR (400 MHz, MeOD): δ = 8.33 (1H, d, JH-H = 2.2 Hz,
C10H), 8.02 (1H, d, JH-H = 2.1 Hz, C12H), 7.30 (1H, d, , JH-H =
3.6 Hz, C6H), 6.43 (1H, d, , JH-H = 3.5 Hz, C5H), 5.02  (2H, s,
C1H2), 2.33 (6H, s, C4,3H3); 13C-NMR (100.6 MHz, MeOD):
δ  =  146.77  (1C,  C8),  143.50  (1C,    C10),  130.70  (1C,  C6),
130.21 (1C, C12), 121.84 (1C, C13), 111.84 (1C, C11), 199.55
(1C, C5), 65.98 (1C, C1), 42.35 (2C, C3,4); MS (70 eV): m/z
% 254.1 ([M+H]+, 100), 256.0 ([M+H]+, 97), 257.0 ([M+H]+,
16)

5-bromo-7-azaindole  (300  mg,  1.52  mmol,  1  eq.)  was  dissolved  in  a  10  mL  flask  with
acetonitrile and glacial acetic acid in a ratio of 3:1. Subsequently formaldehyde (53 mg, 1.78
mmol, 1.17 eq.) and dimethylamine (91 mg, 2.03 mmol, 1.33 eq.) were added to the flask. This
was allowed to stir for 2 hours at room temperature. The acetonitrile was evaporated and the
residue was basified using potassium hydroxide. This mixture was extracted twice using ethyl
acetate.  The  organic  fraction  was  dried  with  magnesium  sulphate  and  the  solvents  were
evaporated.  The  mixture  was  purified  using  normal  phase  liquid  chromatography,  with
chloroform and acetone as eluents with a gradient  going from 100:0 to 0:100. The product
remained as a white powder with an isolated yield of 12%.

1-(5-bromo-1H-pyrrolo[2,3-b]pyridin-1-yl)-N,N,N-trimethylmethanaminium

1H-NMR (400 MHz, CDCl3): δ = 8.44 (1H, d, , JH-H = 2.1 Hz,
C7H), 8.27 (1H, d, JH-H = 2.1 Hz, C5H), 7.72 (1H, d, JH-H = 3.8
Hz,  C2H),  6.77  (1H,  d,  JH-H  =  3.8  Hz,  C3H),  5.82  (2H,  s,
C11H2),  3.24  (9H,  s,  C13,14,15H3);  13C-NMR  (100.6  MHz,
CDCl3): δ = 147.07 (1C, C9), 144.26 (1C,  C7), 131.77 (1C,
C5),  131.23  (1C,  C2),  122.79  (1C,  C4),  113.51  (1C,  C6),
103.45 (1C, C3), 70.32 (1C, C11), 50.72 (3C, C13,14,15); MS
(70 eV): m/z % 270.1 ([M+H]+, 100), 268.1 ([M+H]+, 100),
271.1 ([M+H]+, 16)

In a flask 1-(5-bromo-1H-pyrrolo[2,3-b]pyridin-1-yl)-N,N-dimethylmethanamine (399 mg, 1.57
mmol, 1eq.) was dissolved in 3.4 mL methanol. Next natrium methoxide (116 mg, 2.15 mmol,
1.37 eq.) and dimethyl sulphate were added (396 mg, 3.14 mmol, 2 eq.) along with 6.8 mL
nitromethane.  The  mixture  was  stirred  at  room  temperature  for  one  and  a  half  hour.  The
solvents  were  evaporated  and  the  residue  was  extracted  with  sodium  bicarbonate  and
dichloromethane. The residue was subjected to reversed-phase liquid chromatography with
acetonitrile and water as eluents. This resulted in an isolated yield of 35% as a white/yellow
powder.

58

5-bromo-1H-indazole-1-carbaldehyde

1H-NMR (400 MHz, CDCl3): δ = 9.42 (1H, s, C13H),
8.28  (1H,  d,  JH-H =  8.7  Hz,  C3H),  8.21  (1H,  s,  C8H),
7.93 (1H, d, JH-H = 1.5 Hz, C6H), 7.70 (1H, d x d, JH-H
=  8.8    Hz,  JH-H =  1.8  Hz,  C5H);  MS  (70  eV):  m/z  %
224.8 ([M+H]+, 100), 226.9 ([M+H]+,100)

5-Bromo-1H-indazole (300 mg, 1.53 mmol, 1 eq.) was dissolved in 0.25 mL DMF. The Vilsmeier
reagent was made with made 1 mL DMF, where POCL3  (256 mg, 1.67 mmol, 1.1 eq.) was added
dropwise over 15 minutes at a temperature of 0 °C. The reaction mixture with 5-Bromo-1H-
indazole  was  subsequently  added  dropwise  to  the  prepared  Vilsmeier  reagent.  This  was
allowed to stir for 16 hours at room temperature. The colour of the reaction mixture changed
from  white  to  yellow.  After  16  hours,  the  mixture  was  poured  over  crushed  ice.  Potassium
hydroxide was added and  a white/yellow precipitate arose. This precipitate  was filtered off
and recrystalized in hot ethanol. The product remained as yellow crystals with an isolated yield
of 31%.

2-(5-bromo-1H-pyrrolo[2,3-b]pyridin-3-yl)-N,N-dimethylethan-1-amine

1H-NMR (400 MHz, CDCl3): δ = 9.50 (1H, s, NH), 8.31 (1H,
d, JH-H = 1.9 Hz, C12H), 8.03 (1H, d, JH-H = 1.9 Hz, C10H), 7.16
(1H, s, C7H), 2.88 (2H, t, JH-H = 8.0 Hz, C2H2), 2.60 (2H, t, JH-
H = 8.2 Hz, C1H2), 2.33 (6H, s, C4,5H3); 13C-NMR (100.6 MHz,
CDCl3): δ =  147.12 (1C, C14), 143.41 (1C, C12), 129.39 (1C,
C10),  123.48  (1C,  C7),  121.76  (1C,  C9),  112.97  (1C,  C11),
111.22 (1C, C8), 60.00 (1C, C1), 23.76 (1C, C2), 45.49 (2C,
C4,5); IR (cm-1): 3144, 2931, 989, 1465, 1406, 754; MS (70
eV): m/z % 270.0 ([M+H]+, 97), 268.1 ([M+H]+, 97), 269.0
([M+H]+, 15), 271.0 ([M+H]+, 17)

5-Bromo-7-azaindole  (100  mg,  0.51  mmol,  1  eq.),  Cs2CO3  (182  mg,  0.56  mmol,  1.1  eq.),
pentamethylcyclopenta-dienyliridium(II) chloride, dimer (10 mg, 0.013 mmol, 0.025 eq.), and
2-dimethylamino-ethanol (136 mg, 1.53 mmol, 3 eq.) were added to a flame dried GC-MS vial.
The mixture was flushed with nitrogen and stirred at 120 °C for 48 hours. This residue was
dissolved  in  an  ethyl  acetate/methanol  mixture  with  a ratio  of  9 to 1  and this was filtered
through a silica plug. The product was purified with a reversed-phase liquid chromatography
using water and methanol as eluents. The product was isolated as a brown/beige solid with a
yield of 85%.

59

diethyl (1H-pyrrolo[2,3-b]pyridin-5-yl)phosphonate

1H-NMR (400 MHz, MeOD): δ = 12.02 (1H, s, NH), 8.78 (1H, d,
JH-H= 6.2 Hz, C7H), 8.45 (1H, d x d, JH-H=13.8 Hz and JH-H= 1.5 Hz,
C5H), 7.51 (1H, s, C3H), 6.62 (1H, d, JH-H = 2.4 Hz, C2H), 4.09-4.27
(4H,  m,  C14,16H2),  1.36  (6H,  t,  JH-H=  7.1  Hz,  C15,17H3);
13C-NMR (100.6 MHz, MeOD): δ =  150.27 (1C, C9), 145.35 (1C,
C7), 133.38 (1C, C5), 127.02 (1C, C2), 120.01 (1C, C4), 116.25 (1C,
C6),  101.62  (1C,  C3),  62.23  (2C,  C14,16),  16.35  (2C,  C15,17);
IR (cm-1): 1620, 1340, 989, 827, 692; MS (70 eV): m/z % 255.1
([M+H]+, 100), 256.1 ([M+H]+, 20)

5-Bromo-7-azaindole (100 mg, 0.51 mmol, 1 eq.), Pd(OAc)2 (11 mg, 0.051 mmol, 0.1 eq.), DPPF
(28 mg, 0.051 mmol, 0.1 eq.) and K2CO3  (140 mg, 1.02 mmol, 2 eq.) were added to a 10 mL
flask. This flask was flushed with nitrogen, while 3.8 mL dry toluene was added. The bottle of
diethyl  phosphite  was  first  flushed  with nitrogen  and  then  diethyl phosphite  (140  mg,  1.02
mmol, 2 eq.) was added to the flask. This was flushed with nitrogen for another 5 minutes. The
reaction was stirred at 90 °C for 16 hours. The solvents were evaporated and the residue was
dissolved in ethyl acetate and sent over a silica plug. This residue was subjected to reversed-
phase liquid chromatography using acetonitrile and water as eluents. The product was isolated
as a transparent oil with a yield of 63%.

N,N-dimethyl-2-(5-phenyl-1H-indol-3-yl)ethan-1-amine

Hz,

(6H,

C1H2),

1H-NMR (400 MHz, CDCl3): δ = 8.16 (1H, NH), 7.80 (1H, s,
C8H), 7.66 (2H, d, JH-H = 7.9 Hz, C14,18H), 7.38-7.48 (4H, m,
C6,9,15,17H),  7.31  (1H,  t,  JH-H =  7.4  Hz,  C16H),  7.04  (1H,  s,
C12H), 2.99 (2H, t, JH-H = 7.71 Hz, C2H2), 2.67 (2H, t, JH-H =
C19,20H3);
8.87
2.35
13C-NMR (100.6 MHz, CDCl3): δ =  142.67 (1C, C7), 135.83
(1C, C13), 132.91  (1C, C4), 128.65 (2C, C15,17), 127.43 (2C,
C14,18), 126.30 (1C, C16), 124.75 (1C, C5), 122.17 (1C, C12),
121.87 (1C, C6), 117.37 (1C, C8), 112.53 (1C, C11), 111.33
(1C, C9), 60.33 (1C, C1), 45.48 (2C, C19,20), 23.63 (1C, C2);
IR (cm-1) 2941, 2857, 2778, 1599, 1460, 1036, 795, 754,
698;  MS  (70  eV):  m/z  %  265.2  ([M+H]+,  100),  266.2
([M+H]+, 22)

s,

The observed [M+H]+ values are in accordance with literature (Wu et al., 2002).

5-bromo-dimethyltryptamine (176 mg, 0.66 mmol, 1eq.) was dissolved in 2 mL THF. In 2 mL
water,  phenylboronic  acid  (96  mg,  0.79  mmol,  1.2  eq.),  palladium  acetate  (7.4  mg,  0.033
mmol, 0.05 eq.), and potassium hydroxide (74 mg, 1.32 mmol, 2 eq.) were dissolved. The two
mixtures were added together and the reaction mixture was flushed with nitrogen. The flask
was sealed off, and a nitrogen balloon was placed on the flask. The reaction was stirred at 60
°C for 16 hours. The reaction mixture was allowed to cool to room temperature, afterwards
diluted with water and extracted with ethyl acetate. The organic phase was dried with mag-
nesium  sulfate  and  the  solvents  evaporated.  The  residue  was  subjected  to  reversed-phase
chromatography using water and methanol as eluents. This resulted in an isolated yield of 64%
as a brown oil.

60

1-(1H-indol-3-yl)-6-methoxy-2,3,4,9-tetrahydro-1H-pyrido[3,4-b]indole

1H-NMR  (400  MHz,  CDCl3):  δ  =  8.17  (1H,  s,  N16H),  7.51
(1H, s, N1H), 7.40 (2H, T, JH-H = 8.0 Hz, C20,23H), 7.16-7.22
(2H, m, C17,22H), 7.00-7.09 (3H, m, C5,8,21H), 6.77 (1H, d x
d, JH-H = 8.8 Hz, JH-H = 2.5 Hz,  C7H), 5.53 (1H, s, C10H), 3.88
(3H, s, C15H3), 3.21 (2H, m, C12H2), 2.88 (2H, m, C11H2);
13C-NMR (100.6 MHz, CDCl3): δ = 154.15 (1C, C6), 148.96
(1C, C24),  132.57 (1C, C2), 128.05 (1C, C9), 126.43 (1C, C4),
122.51  (2C,  C17,22),  120.16  (1C,  C21),  119.26  (1C,  C20),
111.32 (1C, C18), 111.82 (1C, C7), 111.21 (2C, C23,8), 109.25
(1C, C3), 100.62 (1C, C5),  55.96, (1C, C10), 50.48 (1C, C15),
43.35 (1C, C12), 22.69 (1C, C11); MS (70 eV): m/z % 318.2
([M+H]+, 100), 319.2 ([M+H]+, 30), 320.2 ([M+H]+, 10)

This is in accordance with literature (Sas et al., 2016)

2-(5-methoxy-1H-indol-3-yl)ethan-1-amine (190 mg, 1mmol, 1eq.) was dissolved in 10 mL gla-
cial acetic acid along with 1H-indole-3-carbonitril (213 mg, 1.5 mmol, 1.5 eq.) and 10% palla-
dium on activated carbon (22 mg, 0.2 mmol, 0.2 eq.). This was hydrogenated under balloon
pressure for 48 hours at room temperature. The catalyst was removed by filtering the mixture
over celite and washing it with dichloromethane. The resulting reaction mixture was basified
with  aqueous  ammonia and extracted with dichloromethane.  The organic  phase  was dried
with magnesium sulfate and the solvents evaporated. The residue was purified using normal-
phase chromatography using dichloromethane and methanol (95:5) as eluents. After purifica-
tion, the product remained as a yellow liquid with an isolated yield of 35%.

61

7. Bibliography
Abranyi-Balogh, P., Földesi, T., Grün, A., Volk, B., Keglevich, G., & Milen, M. (2016). Synthetic
study on the T3P®-promoted one-pot preparation of 1-substituted-3, 4-dihydro-β-carbolines
by the reaction of tryptamine with carboxylic acids. Tetrahedron Letters, 57(18), 1953-1957.

Agrawal, D. C., & Dhanasekaran, M. (Eds.). (2023). Mushrooms with Therapeutic Potentials:
Recent Advances in Research and Development.

Albujuq,  N.  R.,  Meana,  J.  J.,  Diez-Alarcia,  R.,  Muneta-Arrate,  I.,  Naqvi,  A.,  Althumayri,  K.,  &
Alsehli, M. (2023). Design, Synthesis, Molecular Docking, and Biological Evaluation of Novel
Pimavanserin-Based  Analogues  as  Potential  Serotonin  5-HT2A  Receptor  Inverse  Agonists.
Journal of Medicinal Chemistry, 66(13), 9057-9075.

Alzweiri, M., Alsegiani, A. S., Karaj, E., Almarghalani, D. A., Tabaza, Y., Shah, Z. A., & Tillekeratne,
L. V. (2021). The structural simplification of lysergic acid as a natural lead for synthesizing novel
anti-Alzheimer agents. Bioorganic & medicinal chemistry letters, 47, 128205.

Asghar,  S.,  Mushtaq,  N.,  Khan,  A.,  Akhtar,  S.,  Munawar,  R.,  Ansari,  S.,  &  Saify,  Z.  S.  (2022).
Tryptamine Analogs as Antidepressant and Anxiolytic Agents: Synthesis and In Vivo Evaluation.
Pharmaceutical Chemistry Journal, 56(7), 918-924.

Bartolucci, S., Mari, M., Bedini, A., Piersanti, G., & Spadoni, G. (2015). Iridium-catalyzed direct
synthesis of tryptamine derivatives from indoles: exploiting N-protected β-amino alcohols as
alkylating agents. The Journal of Organic Chemistry, 80(6), 3217-3222.

Bartolucci, S., Mari, M., Di Gregorio, G., & Piersanti, G. (2016). Observations concerning the
synthesis of tryptamine homologues and branched tryptamine derivatives via the borrowing
hydrogen process: synthesis of psilocin, bufotenin, and serotonin. Tetrahedron, 72(18), 2233-
2238.

Beato, A., Gori, A., Boucherle, B., Peuchmaur, M., & Haudecoeur, R. (2021). β-Carboline as a
privileged  scaffold  for  multitarget  strategies  in  Alzheimer’s  disease  therapy.  Journal  of
Medicinal Chemistry, 64(3), 1392-1422.

Beck,  A.  T.,  Ward,  C.  H.,  Mendelson,  M.,  Mock,  J.,  &  ERBAUGH,  J.  (1961).  An  inventory  for
measuring depression. Archives of general psychiatry, 4(6), 561-571.

Brnardic, E. J. (1998). Synthesis of aza-tryptophan derivatives.

Calcaterra, A., Mangiardi, L., Delle Monache, G., Quaglio, D., Balducci, S., Berardozzi, S., ... &
Ghirga, F. (2020). The pictet-spengler reaction updates its habits. Molecules, 25(2), 414.

Cameron, L. P., Benetatos, J., Lewis, V., Bonniwell, E. M., Jaster, A. M., Moliner, R., ... & Aguilar-
Valles, A. (2023). Beyond the 5-HT2A Receptor: Classic and Nonclassic Targets in Psychedelic
Drug Action. Journal of Neuroscience, 43(45), 7472-7482.

Cameron, L. P., Patel, S. D., Vargas, M. V., Barragan, E. V., Saeger, H. N., Warren, H. T., ... & Olson,
D. E. (2023). 5-HT2ARs mediate therapeutic behavioral effects of psychedelic tryptamines. ACS
Chemical Neuroscience, 14(3), 351-358.

Cao, D., Yu, J., Wang, H., Luo, Z., Liu, X., He, L., ... & Wang, S. (2022). Structure-based discovery
of nonhallucinogenic psychedelic analogs. Science, 375(6579), 403-411.

62

Chen, C. Y., Senanayake, C. H., Bill, T. J., Larsen, R. D., Verhoeven, T. R., & Reider, P. J. (1994).
Improved Fischer indole reaction for the preparation of N, N-dimethyltryptamines: Synthesis
of  L-695,894,  a  potent  5-HT1D  receptor  agonist.  The  Journal  of  Organic  Chemistry,  59(13),
3738-3741.

Córdova, A. (2004). The direct catalytic asymmetric Mannich reaction. Accounts of chemical
research, 37(2), 102-112.

de Teresa, M. G. (2022). Selling the Priceless Mushroom: A History of Psilocybin Mushroom
Trade in the Sierra Mazateca (Oaxaca). Journal of Illicit Economies and Development, 4(2).

Dodd, S., Norman, T. R., Eyre, H., Stahl, S. M., Phillips, A., Carvalho, A. F., & Berk, M. (2022).
Psilocybin  in  Neuropsychiatry:  a  review  of  its  pharmacology,  safety  and  efficacy.  CNS
spectrums, 1-36.

Dunlap, L. E., Azinfar, A., Ly, C., Cameron, L. P., Viswanathan, J., Tombari, R. J., ... & Olson, D. E.
(2020).  Identification  of  psychoplastogenic  N,  N-dimethylaminoisotryptamine  (isoDMT)
analogues
studies. Journal  of  medicinal
chemistry, 63(3), 1142-1155..

structure–activity

relationship

through

Fricke, J., Kargbo, R., Regestein, L., Lenz, C., Peschel, G., Rosenbaum, M. A., ... & Hoffmeister,
D.  (2020).  Scalable  hybrid  synthetic/biocatalytic  route  to  psilocybin.  Chemistry–A  European
Journal, 26(37), 8281-8285.

Fricke,  J.,  Sherwood,  A.  M.,  Halberstadt,  A.  L.,  Kargbo,  R.  B.,  &  Hoffmeister,  D.  (2021).
Chemoenzymatic  synthesis  of  5-methylpsilocybin:  A  tryptamine  with  potential  psychedelic
activity. Journal of natural products, 84(4), 1403-1408.

Glatfelter, G. C., Pottie, E., Partilla, J. S., Sherwood, A. M., Kaylo, K., Pham, D. N., ... & Baumann,
M.  H.  (2022).  Structure–Activity  Relationships  for  Psilocybin,  Baeocystin,  Aeruginascin,  and
Related  Analogues  to  Produce  Pharmacological  Effects  in  Mice.  ACS  Pharmacology  &
Translational Science, 5(11), 1181-1196.

Grieco, S. F., Castrén, E., Knudsen, G. M., Kwan, A. C., Olson, D. E., Zuo, Y., ... & Xu, X. (2022).
Psychedelics and neural plasticity: therapeutic implications. Journal of Neuroscience, 42(45),
8439-8449.

Gukasyan, N., Davis, A. K., Barrett, F. S., Cosimano, M. P., Sepeda, N. D., Johnson, M. W., &
Griffiths, R. R. (2022). Efficacy and safety of psilocybin-assisted treatment for major depressive
disorder: Prospective 12-month follow-up. Journal of Psychopharmacology, 36(2), 151-158.

Heilman,  J.  (2023).  The  History,  Legalization  and  Potentials  of  Psilocybin-Assisted
Psychotherapy. Journal of Scientific Exploration, 36(4), 623-640.

Henyecz, R., & Keglevich, G. (2019). New developments on the Hirao reactions, especially from
“green” point of view. Current Organic Synthesis, 16(4), 523-545.

Hofmann, A., Frey, A., Ott, H., Zilka, P., & Troxler, F. (1958). Elucidation of the structure and the
synthesis of psilocybin. Experientia, 14(11), 397-399.

Holze,  F.,  Becker,  A.  M.,  Kolaczynska,  K.  E.,  Duthaler,  U.,  &  Liechti,  M.  E.  (2023).
Pharmacokinetics  and  pharmacodynamics  of  oral  psilocybin  administration  in  healthy
participants. Clinical Pharmacology & Therapeutics, 113(4), 822-831.

63

Immadisetty, K., Geffert, L. M., Surratt, C. K., & Madura, J. D. (2013). New design strategies for
antidepressant drugs. Expert opinion on drug discovery, 8(11), 1399-1414.

Kannaboina, P., Mondal, K., Laha, J. K., & Das, P. (2020).  Recent advances in the global ring
functionalization of 7-azaindoles. Chemical Communications, 56(79), 11749-11762.

Lennox,  A.  J.,  &  Lloyd-Jones,  G.  C.  (2014).  Selection  of  boron  reagents  for  Suzuki–Miyaura
coupling. Chemical Society Reviews, 43(1), 412-443.

Meyer, M., & Slot, J. (2023). The Evolution and Ecology of Psilocybin in Nature. Fungal Genetics
and Biology, 103812.

Nakagawasai, O., Arai, Y., Satoh, S. E., Satoh, N., Neda, M., Hozumi, M., ... & Tadano, T. (2004).
Monoamine  Oxidase  and  Head-Twitch  Response  in  Mice:  Mechanisms  of  α-Methylated
Substrate Derivatives. Neurotoxicology, 25(1-2), 223-232.

Nichols,  D.  E.  (2020).  Psilocybin:  From  ancient  magic  to  modern  medicine.  The  Journal  of
antibiotics, 73(10), 679-686.

Nichols, D. E., & Frescas, S. (1999). Improvements to the synthesis of psilocybin and a facile
method for preparing the O-acetyl prodrug of psilocin. Synthesis, 1999(06), 935-938.

Otte, C., Gold, S. M., Penninx, B. W., Pariante, C. M., Etkin, A., Fava, M., ... & Schatzberg, A. F.
(2016). Major depressive disorder. Nature reviews Disease primers, 2(1), 1-20.

Pakhare, D. S., & Kusurkar, R. S. (2015). Synthesis of tetrahydro-β-carbolines, β-carbolines, and
natural  products,(±)-harmicine,  eudistomin  U  and  canthine  by  reductive  Pictet  Spengler
cyclization. Tetrahedron Letters, 56(44), 6012-6015.

Popowycz,  F.,  Routier,  S.,  Joseph,  B.,  &  Mérour,  J.  Y.  (2007).  Synthesis  and  reactivity  of  7-
azaindole (1H-pyrrolo [2, 3-b] pyridine). Tetrahedron, 63(5), 1031-1064.

Raison, C. L., Sanacora, G., Woolley, J., Heinzerling, K., Dunlop, B. W., Brown, R. T., ... & Griffiths,
R.  R.  (2023).  Single-dose  psilocybin  treatment  for  major depressive disorder:  A randomized
clinical trial. JAMA, 330(9), 843-853.

Reed-Berendt,  B.  G.,  Latham,  D.  E.,  Dambatta,  M.  B.,  &  Morrill,  L.  C.  (2021).  Borrowing
hydrogen for organic synthesis. ACS Central Science, 7(4), 570-585.

Rucker, J. J., Marwood, L., Ajantaival, R. L. J., Bird, C., Eriksson, H., Harrison, J., ... & Young, A.
H.  (2022).  The  effects  of  psilocybin  on  cognitive  and  emotional  functions  in  healthy
participants:  Results  from  a  phase  1,  randomised,  placebo-controlled  trial
involving
simultaneous  psilocybin  administration  and  preparation.  Journal  of  Psychopharmacology,
36(1), 114-125.

Sandoval, O. (2023). Potential Antidepressant Efficacy of Psilocybin and Related Tryptamines
(Doctoral dissertation, Miami University).

Santhanam, S., Ramu, A., Baburaj, B., & Kalpatu Kuppusamy, B. (2020). Application of metal
free aromatization to total synthesis of perlolyrin, flazin, eudistomin U and harmane. Journal
of Heterocyclic Chemistry, 57(5), 2121-2127.

Sas,  J.,  Szatmári,  I.,  &  Fulop,  F.  (2016).  One-pot  α-arylation  of  β-carboline  with  indole  and
naphthol derivatives. Current Organic Synthesis, 13(4), 611-616.

64

Schwan,  A.  L.  (2004).  Palladium  catalyzed  cross-coupling  reactions  for  phosphorus–carbon
bond formation. Chemical Society Reviews, 33(4), 218-224.

Serreau, R., Amirouche, A., Benyamina, A., & Berteina-Raboin, S. (2022). A Review of Synthetic
Access to Therapeutic Compounds Extracted from Psilocybe. Pharmaceuticals, 16(1), 40.

Shao,  C.,  Shi,  G.,  Zhang,  Y.,  Pan,  S.,  &  Guan,  X.  (2015).  Palladium-Catalyzed  C–H
Ethoxycarbonyldifluoromethylation  of  Electron-Rich  Heteroarenes.  Organic  letters,  17(11),
2652-2655.

Sherwood, A. M., Halberstadt, A. L., Klein, A. K., McCorvy, J. D., Kaylo, K. W., Kargbo, R. B., &
Meisenheimer,  P.  (2020).  Synthesis  and  biological  evaluation  of  tryptamines  found  in
hallucinogenic mushrooms: norbaeocystin, baeocystin, norpsilocin, and aeruginascin. Journal
of natural products, 83(2), 461-467.

Shirota,  O.,  Hakamata,  W.,  &  Goda,  Y.  (2003).  Concise  large-scale  synthesis  of  psilocin  and
psilocybin,  principal  hallucinogenic  constituents  of  “magic  mushroom”.  Journal  of  natural
products, 66(6), 885-887.

Smith, J. B., Lee, A. K., & Jackson, J. (2020). The claustrum. Current Biology, 30(23), R1401-
R1406.

Stöckigt, J., Antonchick, A. P., Wu, F., & Waldmann, H. (2011). The Pictet–Spengler reaction in
nature  and  in  organic  chemistry.  Angewandte  Chemie  International  Edition,  50(37),  8538-
8564.

Strauss, D., Ghosh, S., Murray, Z., & Gryzenhout, M. (2022). Psilocybin containing mushrooms:
a  rapidly developing biotechnology  industry  in  the  psychiatry,  biomedical  and nutraceutical
fields. 3 Biotech, 12(12), 339.

Suzuki,  A.  (2004).  Organoborane  coupling  reactions  (Suzuki  coupling).  Proceedings  of  the
Japan Academy, Series B, 80(8), 359-371.

Szabó,  T.,  Volk,  B.,  &  Milen,  M.  (2021).  Recent  advances  in  the  synthesis  of  β-carboline
alkaloids. Molecules, 26(3), 663.

Tatsui, G. J. (1928). Preparation of 1-methyl-1, 2, 3, 4-tetrahydro-β-carboline. J. Pharm. Soc.
Jpn, 48, 92.

Tylš,  F.,  Páleníček,  T.,  &  Horáček,  J.  (2014).  Psilocybin–summary  of  knowledge  and  new
perspectives. European Neuropsychopharmacology, 24(3), 342-356.

Valiulin,  R.  (2020).  Organic  Chemistry:  100  Must-Know  Mechanisms.  Berlin,  Boston:  De
Gruyter.

Van Court, R. C., Wiseman, M. S., Meyer, K. W., Ballhorn, D. J., Amses, K. R., Slot, J. C., ... &
Uehling, J. K. (2022). Diversity, biology, and history of psilocybin-containing fungi: suggestions
for research and technological development. Fungal Biology, 126(4), 308-319.

van  Elk,  M.,  &  Yaden,  D.  B.  (2022).  Pharmacological,  neural,  and  psychological  mechanisms
underlying psychedelics: A critical review. Neuroscience & Biobehavioral Reviews, 104793.

65

Vargas,  A.  S.,  Luís,  Â.,  Barroso,  M.,  Gallardo,  E.,  &  Pereira,  L.  (2020).  Psilocybin  as  a  new
approach  to  treat  depression  and  anxiety  in  the  context  of  life-threatening  diseases—a
systematic review and meta-analysis of clinical trials. Biomedicines, 8(9), 331.

Verma,  D.  K.,  Dewangan,  Y.,  &  Verma,  C.  (2023).  Handbook  of  Organic  Name  Reactions:
Reagents, Mechanism and Applications. Elsevier.

von Rotz, R., Schindowski, E. M., Jungwirth, J., Schuldt, A., Rieser, N. M., Zahoranszky, K., ... &
Vollenweider,  F.  X.  (2023).  Single-dose  psilocybin-assisted  therapy  in  major  depressive
disorder: A placebo-controlled, double-blind, randomised clinical trial. EClinicalMedicine, 56.

Wager,  T.  T.,  Hou,  X.,  Verhoest,  P.  R.,  &  Villalobos,  A.  (2016).  Central  nervous  system
multiparameter  optimization  desirability:  application  in  drug  discovery.  ACS  chemical
neuroscience, 7(6), 767-775.

Wu, T. Y., & Schultz, P. G. (2002). A versatile linkage strategy for solid-phase synthesis of N, N-
dimethyltryptamines and β-carbolines. Organic Letters, 4(23), 4033-4036.

Yakhontov,  L.  N.  (1968).  The  chemistry  of  azaindoles  [pyrrolo  [2,  3]  pyridines].  Russian
Chemical Reviews, 37(7), 551.

Yang,  L.,  Lin,  J.,  Kang,  L.,  Zhou,  W.,  &  Ma,  D.  Y.  (2018).  Lewis  Acid-Catalyzed  Reductive
Amination of Aldehydes and Ketones with N, N-Dimethylformamide as Dimethylamino Source,
Reductant and Solvent. Advanced Synthesis & Catalysis, 360(3), 485-490.

Yin,  Y.  N.,  &  Gao,  T.  M.  (2023).  Non-hallucinogenic  Psychedelic  Analog  Design:  A  Promising
Direction for Depression Treatment. Neuroscience Bulletin, 39(1), 170-172.

66

