Article
Psychedelic Drugs Rediscovered—In Silico Study of
Potential Fetal Exposure to Analogues of Psychedelic Drugs
During Pregnancy

Anna W. Soba ´nska 1,*

, Andrzej M. Soba ´nski 2

and El˙zbieta Brzezi ´nska 1

1 Department of Analytical Chemistry, Medical University of Lodz, 90-151 Łód´z, Poland;

elzbieta.brzezinska@umed.lodz.pl
Faculty of Chemistry, University of Lodz, 91-403 Łód´z, Poland; andrzej.sobanski@edu.uni.lodz.pl

2

* Correspondence: anna.sobanska@umed.lodz.pl

Abstract

A total of 250 known and novel compounds—ketamine and serotonergic psychedelics
or their analogues—designed to target depression, addictions and/or other mental or
neurological disorders and developed as “recreational” (illegal) drugs from three chemical
families, ergolines, tryptamines and phenylethylamines, were investigated in the context
of their ability to cross the human placenta. Using a novel multivariate model involving
compounds’ drug-likeness (according to Lipinski’s Ro5), caco-2 membrane permeability,
fraction unbound to plasma proteins, steady-state volume of distribution and the total
count of heteroatoms (non-carbon atoms with hydrogens included), it was established that
the majority of studied compounds are likely to cross the placenta easily, most probably by
the passive diffusion mechanism. Atomic contributions of structural elements of studied
compounds were investigated using the Morgan fingerprinting algorithm and it was
postulated that the fragments promoting transport of compounds across the placenta are
carbonyl, hydroxyl, nitro- and phosphoryloxy groups—rigid polycyclic structures, bulky
alkyl/aryl groups and halogen atoms restrict the trans-placental passage. All studied
compounds are expected to be relatively easily obtained by synthetic routes, which makes
them an interesting target for manufacturers of illegal drugs and warrants the need to
pursue pharmacological studies of these compounds in silico.

Keywords: psychedelic drugs; placenta permeability; drug-likeness; QSAR; atomic
contributions; synthetic availability

1. Introduction

Academic Editor: Marina DellaGreca

Received: 15 November 2025

Revised: 23 December 2025

Accepted: 5 January 2026

Published: 8 January 2026

Copyright: © 2026 by the authors.

Licensee MDPI, Basel, Switzerland.

This article is an open access article

distributed under the terms and

conditions of the Creative Commons

Attribution (CC BY) license.

Psychedelics are a subclass of hallucinogenic drugs whose primary activity is to trigger
non-ordinary mental states. Serotonin is a neurotransmitter that affects many human
behavioural processes [1] and it was established that the major chemotypes of psychedelics—
tryptamines, ergolines and phenylalkylamines—are serotonergic psychedelics that share
pharmacology as 5-HT2A, 5-HT2B and 5-HT2C receptor agonists [2,3]. According to
archeological studies from today’s Iraq, Europe, Mexico and South America, psychedelic
mushrooms and plants (including psilocybin, peyote and strands of morning glory) have
been used by humans for ritual purposes for at least 10,000 years [4]; religious rituals
involving the consumption of psychedelics are still performed in some populations [5]. In
the 1960s and 1970s, the recreational use of psychedelic drugs (including LSD synthetized
by A. Hoffmann in 1938 and established to have psychoactive properties in 1943) became

Molecules 2026, 31, 212

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

2 of 16

a part of counter-cultural trends [6]. Interestingly, low doses of psychedelics and other
psychoactive compounds are found in some popular, legal dietary ingredients [7].

Serious scientific interest in serotonergic psychedelics began soon after the psychoac-
tive activity of LSD had been discovered [8]. Clinical studies of LSD proved that small doses
of this compound cause several types of short-term symptoms in healthy individuals and
psychiatric patients, such as the following: (i) visual disturbances; (ii) auditory phenomena;
(iii) cutaneous sensations; (iv) taste changes; (v) space perception disturbances; (vi) thought
disorders; (vii) mood changes; (viii) sexual excitement; (ix) paranoid features; (x) distur-
bances of ego-experience; (xi) time disorders; (xii) changes in body image; (xiii) autonomic
disturbances and (xiv) drowsiness. At the same time, some positive, long-term effects of low
doses of LSD were reported, such as the following: symptoms in patients with schizophre-
nia or depression improved for periods of up to a few weeks even after a single LSD
administration [8]; potential applications of LSD also include the treatment of alcoholism
and tobacco addiction [5,9]. Similarly, other classic psychedelic drugs like psylocibin appear
to improve emotional empathy and specific memory types such as semantic associations
and associative learning [10]. Psylocibin and its analogues seem to be useful in treatments
of eating disorders, chronic pain, depression, fear and PTSD [11–13], and an interest in “re-
discovered” and “repurposed” psychedelic drugs continues to surge [12,14]. Unfortunately,
despite the results suggesting that psychedelic drugs may have a positive influence on
some psychiatric patients, natural and synthetic compounds associated with psychedelic
experience are illegal in many countries [15]. Such restrictions limit the research using
these compounds—human studies are replaced by animal (mainly rodent) models, e.g.,
head-twitch response assay [16] and in silico investigations [17]. Using rat models, it was
established that N,N-dimethyltryptamine (DMT) improves mood and reduces anxiety [18]
and psychedelics such as LSD or psylocibin have antidepressant effects [19]—with the
likely hypothesis that psychedelic tryptamines can induce hallucinogenic and therapeutic
effects through activation of the same receptor [20]. Some psychedelics were also found to
exert anti-inflammatory effects which can be further investigated in the context of asthma
treatment [21]. It is also postulated that some psychedelics are used in studies of neurode-
generative diseases—it was discovered that psylocibin may induce psychotic-like states in
lab animals similar to human Parkinson’s psychosis [22].

Several studies focused on explaining the molecular mechanisms responsible for dif-
ferent changes in human perception associated with already known psychedelics [23]. In-
teractions between psychedelics and 5-HT1A and 5-HT2A receptors were investigated [24]
and the effects of structural modifications (both in the indole ring system and in the amine
side chain) of 5-methoxytryptamines upon their affinity for 5-HT1A and 5-HT2A recep-
tors were determined. It was discovered that the biological activity of psilocin isomers
with the OH group occupying positions C4 to C7 in the indole ring differ due to different
ligand-5-HT2AR receptor interactions [25]. Psychedelics’ affinity for plasma proteins was
studied with the conclusion that albumin, as the most abundant protein of blood serum,
could serve as the biodistributor of psychedelic drugs [26]. Based on mechanistic insights,
some promising analogues of natural psychedelics were designed, which are expected to
target depression and other psychiatric disorders without the hallucinogenic activity of
parent molecules [1,3,24,27–35]. In some instances, on the other hand, novel psychoactive
substances (e.g., from the chemical families of tryptamines or phenylalkylamines) were
developed as new drugs of abuse [36]. The search for novel, psychedelics-related drugs
active in the central nervous system prompted the development of some new (bio)synthetic
routes [37,38].

Considering an increasing interest in psychedelic drugs and their possible applications
in pharmacotherapy of pain, inflammation and mental and neurodegenerative disorders,

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

3 of 16

it is difficult to understand why so little attention has been paid so far to the safety of
emerging compounds from this class in the context of pregnancy. A report on pregnancies of
a group of 140 women admitting to the use of LSD prior to or during pregnancy suggested
that LSD consumption may increase the prevalence of defects in embryos or infants, but
the results were inconclusive since some patients from the studied group suffered from
infectious diseases or gave a story of ingestion of other illicit drugs during pregnancy [39].
Some other case studies showed that the LSD exposure during pregnancy may lead to
ocular anomalies [40] or intrauterine amputations [41]; on the other hand, according
to some researchers, no increased offspring fatality or defects among children could be
associated with the maternal LSD ingestion [42,43]. The reported results lack systematic
approach—properly designed in vivo studies on pregnant females and human embryos
exposed to psychedelics are difficult to conduct due to ethical reasons. Some valuable
results were obtained from animal (rat, hamster or zebrafish) tests; it was established
that there are possible teratogenic effects or incidents of delayed development in infants
whose mothers used LSD, hallucinogenic plant-based beverage ayahuasca, mescaline or
ecstasy during pregnancy [44,45]. Other risks associated with the exposure of offspring
to psychedelic substances during pregnancy and breastfeeding may be a consequence of
altered mental states of mothers, leading to disrupted maternal care [46].

Serotonergic psychedelics are promising drugs in the treatment of postpartum de-
pression but there is insufficient evidence regarding the transfer of such compounds to
mother’s milk [47].

So far, the pharmacology of psychedelics and their analogues have been studied
mainly in the context of their ability to interact with biological targets in the central nervous
system [30]. Data on the ability of both legal and illicit analogues of psychedelics from
the chemical families of tryptamines, ergolines and phenylethylamines to undergo trans-
placental passage are scarce, and in this study, we intended to fill this gap with systematic
investigations based on a novel, simple model of the placenta permeability.

2. Results and Discussion
2.1. Properties of Studied Compounds

Psychoactive compounds investigated in this study belong, with the exception of
ketamine, to one of the following three main chemical families: tryptamines (DMT, psy-
locibin, psilocin), ergolines (e.g., LSD) and phenylethylamines (mescaline and related
compounds). The compounds from these families do not differ significantly in the context
of the mean values of many pharmacologically relevant physico-chemical properties or
biomembrane permeability descriptors (log P, log D, caco2, MDCK, PAMPA, nHA and
nHD) (Supplementary Materials); all of them are drug-like, according to the Lipinski’s Ro5
(Lipinski = 1) [48,49]. There are, however, parameters which differ between the groups,
such as the following: (i) nRig—higher in ergolines; (ii) PPB—lower in tryptamines;
(iii) Fu—higher in tryptamines; (iv) Flex—higher in phenylethylamines; (v) MW—lower
in tryptamines; (vi) nRot—higher in phenylethylamines; (vii) nRing—higher in ergolines;
(viii) MaxRing—higher in ergolines; (ix) logVDss—lower in ergolines; (x) TPSA—higher in
phenylethylamines and (xi) nHet—higher in phenylethylamines (compared to the other
two chemical families). Some of these properties, as demonstrated below, are linked to
the ability of molecules to cross the placenta, expressed as log FM. The properties that
play a pivotal role in the placenta permeability are Lipinski (which encodes compounds’
lipophilicity, molecular size and the ability to form H-bonds), nHet, logVDss, Fu and caco2.
Despite the similarities between the three chemical families, the key descriptors (with the
exception of Lipinski) differ within the families and those differences are sufficient to result
in the log FM values between ca. −0.05 and −0.70.

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

4 of 16

2.2. Psychedelics’ Placenta Permeability

The placenta permeability of compounds is often expressed as log FM—fetus-to-
mother blood concentration ratio in the state of equilibrium. The main transport mechanism
for small, moderately lipophilic molecules is passive diffusion and the cut-off value between
the crossing and non-crossing compounds is usually assumed to be log FM = −0.52 (to be
more precise, Di Fillipo originally suggested that compounds with log FM > −0.52 cross
the placenta easily; compounds with log FM < −0.82 do not cross the placenta; molecules
with log FM between −0.52 and −0.82 are dubious [50]).

In our study, the placenta permeability (log FM) of 249 psychedelic compounds and
their analogues from three chemical families (tryptamines, ergolines and phenylethy-
lamines; 57 to 305) and ketamine (56) was predicted using a novel Equation (1) based on
independent variables selected using the best model method (Figure 1).

log FM = 0.193 (±0.447) + 0.492 (±0.085) Lipinski + 0.0410 (±0.0141) nHet + 0.268
(±0.103) caco2 − 0.172 (±0.080) logVDss + 0.00526 (±0.00132) Fu

(1)

(Training set: n = 40, R2 = 0.734, R2
test set: n = 15, R2 = 0.580, R2

adj. = 0.695, RMSE = 0.184, PRESS = 1.618 and Q2 = 0.626;

adj. = 0.518, RMSE = 0.370 and F = 18.7; p < 0.001).

Figure 1. Equation (1)—predicted vs. experimental (observed) log FM.

The log FM values calculated according to Equation (1) (Supplementary Materials)
imply a high ability of almost all studied compounds to cross the placenta. Some com-
pounds (listed in the Supplementary Materials) have the predicted log FM values between
−0.7 and −0.5—formally around or just below the threshold postulated by Di Filippo
(−0.52), but above the value indicating poor placenta permeability (−0.82). However, the
lower values of log FM do not make these particular compounds absolutely safe for a fetus,
since the ability of chemicals to reach the fetal circulation is in fact a continuum and even
compounds with fetus-to-mother concentration ratio below the threshold are also capable
of crossing the placenta to some degree.

Predicted log FM values for three families of psychedelics (tryptamines, ergolines and
phenylethylamines) do not differ significantly (Figure 2); they are, on average, slightly

https://doi.org/10.3390/molecules31020212

MLRlog FMexplog FMpred#1#2#3#4#6#8#9#10#11#12#13#15#16#17#19#20#21#22#23#24#25#26#27#28#29#30#31#34#35#36#37#40#43#44#47#48#49#51#52#55#5#7#14#18#32#33#38#39#41#42#45#46#50#53#54-1.2-1.0-0.8-0.6-0.4-0.20.00.20.4-1.2-1.0-0.8-0.6-0.4-0.20.00.2Training setTest set Molecules 2026, 31, 212

5 of 16

higher for tryptamines than for ergolines and phenylethylamines. However, as mentioned
above, larger differences in the psychedelics’ ability to cross the placenta were observed
within the chemical families.

Figure 2. Comparison of predicted mean log FM values for 3 chemical families.

In this study, we analyzed the contributions of particular atoms to the ability of
selected compounds from the studied group to cross the placenta (expressed as log FM).
As demonstrated for the reference group of compounds 1–55, the structural elements
promoting transport of compounds across the placenta are carbonyl, hydroxyl, nitro- and
phosphoryloxy groups; rigid polycyclic structures and halogen atoms restrict the trans-
placental passage (for examples, see Figure 3).

Figure 3. Cont.

https://doi.org/10.3390/molecules31020212

 ErgolinesPhenylethylaminesTryptamines-0.8-0.7-0.6-0.5-0.4-0.3-0.2-0.100.1log FMBox plots—log FM  Molecules 2026, 31, 212

6 of 16

Figure 3. Atomic contributions to low (1) and high (20, 21, 31, 33, 36) placenta permeability.

2.3. Placenta Permeability of Tryptamines

Psilocybin mushrooms were used ritualistically in pre-Columbian Mexico and their
main active constituents, psilocin (135) and psilocybin (131), were isolated, identified and
synthetized in the 1950s [51]. Both compounds became available as “recreational” drugs
in the 1960s; however, there is still a gap in knowledge regarding health risks related
to the consumption of these substances during pregnancy or breastfeeding. According
to our study, their predicted ability to cross the placenta is high, with the log FM val-
ues −0.24 and −0.08 for psilocin and psilocybin, respectively. Other naturally occurring
4-phosphoryloxytryptamines (baeocistin, 132; aeruginascin, 133; norbaeocistin, 134) are
also likely to undergo easy trans-placental transport, with log FM between −0.18 and
−0.21—as expected for compounds without bulky elements, halogen atoms or rigid, poly-
cyclic structures and containing phosphoryloxy groups.

Synthetic 4-substituted tryptamines are a serious public health issue, since they became
popular (mostly as substances of abuse) relatively recently—mainly in the early 2000s—and
there is little information on their pharmacological properties other than the potential
to cause psylocibin-like psychedelic effects [32]. As predicted using Equation (1), the
4-HO- and 4-AcO-tryptamines (Figure S1, Supplementary Materials) are likely to cross the
placenta easily (4-AcO compounds cross the placenta easier than 4-HO compounds, with
log FM between −0.26 and −0.50 for 4-HO and −0.11 and −0.33 for 4-AcO compounds,
respectively). The values of log FM for the N,N-dialkyltryptamines from the 4-AcO and
4-OH series bearing the same substituents at side-chain N atom are highly correlated
(R2 = 0.77). The ability of the 4-AcO- and 4-OH-tryptamines to cross the placenta appears to
be related to the steric properties of the alkyl groups at the amine nitrogen and it changes in
the following order: (i) 4-hydroxytryptamines and 4-acetoxytryptamines with symmetrical
alkyl chains DET > DPT > DIPT; (ii) 4-hydroxytryptamines and 4-acetoxytryptamines with
asymmetrical alkyl chains MET > EPT > MPT. Similar influence of N,N-alkyl substituents
upon activity was reported by Klein et al., who concluded that the crucial factor governing
the median effective dose (ED50) of N,N-dialkyl tryptamines in mice is the sum of the
values of υ (Charton’s parameter υ, based on van der Waals radii) for the two amine
substituents [32].

Other possible alteration to the molecular structures of tryptamines is in the pyrrole
ring. When this ring is substituted with short alkyl chains or a phenyl group at C2, the
ability of compounds to cross the placenta decreases (137 vs. 65, 66 and 67, Figure S2,
Supplementary Materials), although the differences in log FM are relatively small (ca.
0.2–0.3 logarithmic unit).

The tryptamines can also be modified at a pyrrole N1 atom. The atomic contribu-
tions of substituents at N1 are rather small, resulting in slightly lower log FM values for
compounds 63, 64 and 65 compared to psylocine, 135 (ca. −0. 4 vs. −0.24), and a slightly

https://doi.org/10.3390/molecules31020212

 Molecules 2026, 31, 212

7 of 16

higher log FM value for compound 62 with a 2,2-difluoroethyl group at N1 (Figure S3,
Supplementary Materials).

An interesting modification of tryptamines was proposed by Jayakodiarachchi
et al. [35], who replaced an indole ring with an indazole ring, thus producing a series of com-
punds 145 to 149 and 151 to 158, two of which (both with a bulky 1,2,3,6-tetrahydropyridin-
5-yl substituent at C3 and Br (154) or a phenyl group (158) at C5) expected log FM values
below −0.6 (Figure 4).

Figure 4. Indazole analogues of tryptamine.

2.4. Placenta Permeability of Ergolines

The values of log FM for ergolines (−0.27 to −0.56) are sufficiently high to suspect
that most of them are able to cross the placenta easily. Small difference in log FM between
LSD (168) and 169 (predicted log FM values −0.39 and −0.27, respectively) points to a role
of a nitrogen N1 atom and the possible impact of a substituent at this atom; however, there
is currently no sufficient evidence to confirm this observation (Figure S4, Supplementary
Materials). Other reported changes in substituents at N6 (compounds 168 and 171) and
even introducing a Br atom at C2 (compound 170) or a strongly electronegative F atom
at C13 (compound 175) have a limited influence on the predicted ability of ergolines to
cross the placenta. One compound (176) with a markedly lower log FM value (−0.54) has
a modification at C8 (no carbonyl or hydroxyl oxygen atom in close proximity); even a
bulky and rigid (2S,4S)-2,4-dimethylazetidinyl group in 172 does not restrict the ability
of this compound to cross the placenta sufficiently to warrant safe use during pregnancy.
Interestingly, lisuride (173), a non-hallucinogenic analogue of LSD approved for the treat-
ment of Parkinson’s disease and high prolactin levels [30], is also expected to cross the
placenta easily.

2.5. Placenta Permeability of Phenylethylamines

Mescaline (177), known for ca. 5700 years, identified in the late 1890s and synthesized
in 1919 [52], is thought to be relatively safe, with no evidence of cytotoxicity; however, due
to its rapid absorption from the gastro-intestinal tract, it may be available in the maternal
circulation when administered orally, even despite its relatively fast distribution to kidneys
and liver, metabolism and excretion with urine. According to our study, mescaline is a
compound with the highest potential to cross the placenta in the whole group of 250 studied
compounds (predicted log FM = −0.09). However, due to even small structural modifica-
tions to the phenyl ring or an aminoethyl side chain, other phenylethylamines investigated
in this study have significantly lower log FM values. For some phenylethylamines, the log
FM values between −0.51 and −0.73 are around or even below the threshold quoted by
Di Fillipo [50] (−0.52). For example, changing the position of one methoxy group from
C3 to C2 and replacing another one (at C4) with halogen atoms or sterically demanding,

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

8 of 16

lipophilic substituents (e.g., a cyclopentyl group) gave compounds 181 to 183 and 288 with
much lower log FM values (−0.54 to −0.63), as opposed to an insignificant reduction in log
FM (to −0.13) for 187 with a NO2 group occupying C4 position (Figure 5). Compounds
233–238, whose expected log FM values are especially low (−0.6 to −0.7), are formally
phenylethylamines bearing Br atoms at C4 (Figure 6); however, their aminoethyl side chains
are engaged in rigid, cyclic structures condensed with the benzene ring.

Significant reduction in the log FM value could also be observed for mescaline ana-
logues 226–230 (Figure 7) with an aminoethyl side chain incorporated into a cyclopropyl
ring and halide atoms or a methyl group occupying position 4 (log FM = −0.46 for 226 and
−0.53 to −0.58 for compounds 227 to 230, in contrast to log FM = −0.15 for 180). However,
considering the low log FM values for compounds 181–183 (−0.54 to −0.60), which contain
halogen atoms at C4 but no cyclopropyl ring, we concluded that the steric effect of this ring
in the side chain is not significant in the context of the placenta permeability compared to
the presence of halogen atoms at C4.

Figure 5. Mescaline (177) vs. 2,5-dimethoxy-phenylethylamines with different substituents at C4.

https://doi.org/10.3390/molecules31020212

 Molecules 2026, 31, 212

9 of 16

Figure 6. Bi- or tricyclic analogues of mescalines.

Figure 7. Cont.

https://doi.org/10.3390/molecules31020212

     Molecules 2026, 31, 212

10 of 16

Figure 7. 2-(2,5-Dimethoxyphenyl)cyclopropylamines substituted at C4 in the benzene ring.

In our study, we also investigated other series of compounds, e.g., phenylethylamines
with an α-methyl group introduced to the aminoalkyl chain (compounds 189 to 206).
The log FM values for these compounds are between −0.22 and −0.65, depending on
the substituent at C4 in the benzene ring, with bulky and lipophilic hexyl or benzyl
groups at C4 causing the most significant reduction in the log FM values (to −0.65 and
−0.60 for compounds 196 and 197, respectively) and halogen atoms at C4 giving a smaller
but marked effect (compounds 191 to 193 with log FM = −0.49, −0.54 and −0.41, re-
spectively), as compared to 194 with a methyl group at C4 (log FM = −0.33) (Figure S5,
Supplementary Materials).

2.6. Synthetic Availability of Psychedelics’ Analogues in the Context of Future Studies

According to our study, compounds 56 to 305 are likely to be easily absorbed from the
gastro-intestinal tract to the maternal circulation (see the Supplementary Materials—GI
absorption classified as “High” for all the compounds). We also suspect that compounds
56 to 305 are able to reach the fetal circulation easily (their transport across the placenta,
most probably by the passive diffusion mechanism, may be a little bit more difficult but
still possible for some compounds, as discussed above). Unfortunately, many compounds
from tryptamine, phenylamine or ergoline families are synthesized as illicit (“recreational”)
drugs [36] and this seriously compromises the possibility of studying their pharmacological
properties by experimental methods, e.g., due to a limited sample availability. It may also
be suspected that there is little interest in such research among the suppliers before the
substances hit the illegal drug market and in marking them with proper warnings once
they are being sold.

In this study, apart from investigations of psychedelics’ drug-likeness and their ability
to cross the placenta, we also considered the synthetic availability of studied compounds
(predicted based on a combination of fragment contributions and a complexity penalty [53]).
It was observed that all the studied compounds should be easy to synthesize (synthesis may

https://doi.org/10.3390/molecules31020212

   Molecules 2026, 31, 212

11 of 16

be relatively more difficult for ergolines)—there are no compounds in the studied group
whose Synth score would exceed the cut-off = 6 (Supplementary Materials, Table S4 and
Figure 8). The possibility of obtaining novel psychedelics’ analogues by synthetic routes
(without the need to cultivate and process plants) and the activity of many compounds from
this group in the central nervous system make them an attractive target among individuals
trying to evade legal controls; also, it should, in our opinion, prompt research on the
biological activity of such compounds in the contexts other than their activity in the brain.

Figure 8. Mean synthetic accessibilities of compounds 57–305.

2.7. Applicability of Equation (1) and Comparison with Other Published Models

The model developed in this study (Equation (1)) is based on compounds with known
experimental log FM values collected by Takaku [54] and later used in other placenta perme-
ability studies [55,56]. The key molecular/membrane permeability descriptors for the refer-
ence compounds were compared with those calculated for the psychedelics, with particular
focus on the quantitative parameters used in the log FM model developed herein—nHet,
caco2, logVDss and Fu. These values obtained for the studied psychedelic compounds
largely overlap with those for the reference compounds (Supplementary Materials).

The values of log FM predicted using Equation (1) were compared with those pre-
dicted according to Equations (2) [54] and (3) [55] (calculation results are presented in the
Supplementary Materials).

log FM = −0.00238 MW +0.00238 TopoPSA + 0.380 Hmax + 0.0283

log FM = 0.100 − 20.84 AATSC1c − 0.0132 ZMIC1

(2)

(3)

It was established that the Takaku model (Equation (2)) gives results closer to those
predicted using Equation (1) than the Wang model and indicates several drugs with
relatively low log FM, similarly to (1); the Wang model (Equation (3)) gives relatively
high results, with less variability for the studied psychedelics; Wang and Takaku models
are not very close to each other. According to Equations (1) to (3), all of the studied
compounds are likely to cross the placenta easily (log FM > −0.52) or belong to the group
which Di Filippo defined as “dubious” (log FM between −0.52 and −0.82).

https://doi.org/10.3390/molecules31020212

 ErgolinesPhenylethylaminesTryptamines1234567SynthBox plots (Synth)Molecules 2026, 31, 212

12 of 16

3. Materials and Methods
3.1. Compounds

Experimental log FMexp values for compounds 1 to 55, used to generate quantitative
models of placenta permeability described in Section 3, were compiled by Takaku et al. [54]
and corroborated by Wang et al. [55]; they are listed in the Supplementary Materials.

Psychedelic compounds and their analogues (57–305) were taken from

Refs. [3,20,24,25,28,30,34].

3.2. Calculated Descriptors

Physico-chemical and ADMET properties were calculated using ADMETLab3.0 soft-
ware based on SMILES strings collected from PubChem. The following physico-chemical
descriptors were used in this study: molecular weight (MW); van der Waals volume (Vol);
Dense = MW/Vol; count of hydrogen bond acceptors (nHA); count of hydrogen bond
donors (nHD); number of rotatable bonds (nRot); number of rings (nRing); number of
atoms in the largest ring (MaxRing); number of non-carbon atoms including hydrogens
(nHet); number of rigid bonds (nRig); Flex = nRot/nRig; the logarithm of aqueous solubility
value (log S); the logarithm of the n-octanol/water partition coefficient (log P); the loga-
rithm of the n-octanol/water distribution coefficients at pH = 7.4 (log D); Fsp3 = number
of sp3 carbons/total carbon count. Calculated ADMET properties included in the study are
the following: (i) membrane permeabilities Caco2, MDCK and PAMPA; (ii) the volume of
distribution at steady state (logVDss); (iii) plasma protein binding, % (PPB); (iv) the fraction
unbound in plasma, % (Fu). Mordred Lipinski descriptor was calculated using the OCHEM
platform [57]. Binary evaluation of the ability of compounds to be absorbed from the gastro-
intestinal tract was assessed using SwissADME platform [58]. Two-dimensional PaDEL
descriptors [59] used in predictions according to Takaku [54] and Wang [55] models were
calculated using the OCHEM platform [57]. Equation (3) has been modified compared to
the original model proposed by Wang to account for non-normalized independent variables.
Calculated molecular descriptors for reference compounds 1 to 55 and psychedelic

compounds/analogues 56–305 are given in the Supplementary Materials.

3.3. Statistical Analysis

Equation (1) was generated in the “best model” mode using XLSTAT 2025.1 from Lu-
mivero, Denver, CO, USA, with 40 compounds randomly assigned to a training set and the
remaining 15 compounds used as a test set, with the minimum number of variables = 2 and
the maximum number of variables = 5. The best model was selected using the Amemiya’s
prediction criterion which penalizes adding predictors more heavily than adjusted R2 and
thus prevents overfitting [60].

Statistical analysis of physico-chemical and pharmacokinetic properties of compounds

was performed using XLSTAT and Statistica v. 13.3 from StatSoft, Kraków, Poland.

3.4. Atomic Contribution Analysis

Contribution of molecular fragments to log FM values was analyzed using Chem-
Master Pro v. 1.2 from CrescentSilico. An HQSAR model of log FM was generated for
55 reference compounds (1 to 55) and 250 psychedelics (56 to 305), with molecular finger-
prints (circular, 2048 bits, radius = 2, chirality included) as independent variables, with
PLS variables pre-selection and 5-fold leave-many-out cross-validation. A total of 75% of
compounds were selected at random and used as a training set and the remaining 25% of
compounds became a test set. Selected subsets of compounds were then analyzed and the
contributions of particular atoms/fragments to log FM were reviewed manually.

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

13 of 16

3.5. Predicted Synthetic Availability

Synthetic availability of compounds 56 to 305 was assessed using Synth score com-
puted with ADMETLab3.0 according to Ertl methodology [53], which returns values
between 1 (easy to make) and 10 (very difficult to make). It is assumed that compounds
with Synth ≥ 6 are difficult to synthesize.

4. Conclusions

The 250 studied psychoactive compounds are likely to cross the placenta, most proba-
bly by passive diffusion—although some phenylethylamines, ergolines and tryptamines
have log FM values around or slightly below the formal cut-off value usually assumed be-
tween compounds which cross the placenta easily and those whose trans-placental passage
is dubious (log FM = −0.52). Atomic contributions of structural elements of studied com-
pounds were investigated using the Morgan fingerprinting algorithm and it was observed
that the elements promoting the transport of chemicals across the placenta are carbonyl,
hydroxyl, nitro- and phosphoryloxy groups; rigid polycyclic structures, bulky alkyl/aryl
groups and halogen atoms restrict the trans-placental passage. Based on Equations (1)–(3),
there is a high probability of compounds 56 to 305 being absorbed from the maternal to fetal
circulation—no studied psychedelics have log FM values below the threshold proposed by
Di Filippo to identify poor placenta penetrators (log FM < −0.82).

Our study has some limitations—the predictions of the placenta permeability are
made based on a relatively small set of experimental log FM values compiled from several
sources. Additionally, to properly evaluate the risks for offspring, further studies on
psychedelics’ possible maternal metabolism and/or routes of excretion from the mother’s
body are needed.

Supplementary Materials: The following supporting information can be downloaded at https:
//www.mdpi.com/article/10.3390/molecules31020212/s1. Figure S1: Atomic contributions of
compounds 122 and 124 to 130; Figure S2: Atomic contributions to log FM—5-MeO-DMT derivatives
with modifications to the pyrrole ring, at 2 position; Figure S3: Psilocin (135) derivatives with
modifications to the pyrrole ring, at N atom; Figure S4: Atomic contributions to log FM—ergolines
168 to 176; Figure S5: Phenylethylamines with an α-methyl group in the aminoalkyl chain, substituted
at C4. Table S1: Properties of compounds 1 to 55; Table S2: Properties of compounds 56 to 305; Table
S3: Relevant properties of reference compounds vs. drugs; Table S4: Predicted synthetic availability
of compounds 56 to 305.

Author Contributions: Conceptualization, A.W.S. and A.M.S.; methodology, A.W.S. and E.B.; valida-
tion, A.W.S. and E.B.; investigation, A.W.S. and A.M.S.; writing—original draft preparation, A.W.S.
and A.M.S.; funding acquisition, A.W.S. and E.B. All authors have read and agreed to the published
version of the manuscript.

Funding: This research study was supported by an internal grant of the Medical University of Lodz,
no. 503/3-016-03/503-31-001.

Institutional Review Board Statement: Not applicable.

Informed Consent Statement: Not applicable.

Data Availability Statement: Data are reported in the manuscript.

Conflicts of Interest: The authors declare no conflicts of interest.

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

References

14 of 16

1.

2.
3.

4.
5.

6.
7.

8.

9.

Cao, D.; Yu, J.; Wang, H.; Luo, Z.; Liu, X.; He, L.; Qi, J.; Fan, L.; Tang, L.; Chen, Z.; et al. Structure-Based Discovery of
Nonhallucinogenic Psychedelic Analogs. Science 2022, 375, 403–411. [CrossRef]
Aghajanian, G.K.; Marek, G.J. Serotonin and Hallucinogens. Neuropsychopharmacology 1999, 21, 16S–23S. [CrossRef] [PubMed]
Varty, G.B.; Canal, C.E.; Mueller, T.A.; Hartsel, J.A.; Tyagi, R.; Avery, K.; Morgan, M.E.; Reichelt, A.C.; Pathare, P.; Stang, E.;
et al. Synthesis and Structure-Activity Relationships of 2,5-Dimethoxy-4-Substituted Phenethylamines and the Discovery of
CYB210010: A Potent, Orally Bioavailable and Long-Acting Serotonin 5-HT2 Receptor Agonist. J. Med. Chem. 2024, 67, 6144–6188.
[CrossRef] [PubMed]
Renshaw, W.B. The Medical History & Use of Psychedelic Drugs. Legacy 2020, 20, 5.
Johnson, M.W.; Hendricks, P.S.; Barrett, F.S.; Griffiths, R.R. Classic Psychedelics: An Integrative Review of Epidemiology,
Therapeutics, Mystical Experience, and Brain Network Function. Pharmacol. Ther. 2019, 197, 83–102. [CrossRef]
Kline, W. Psychedelic Birth: Bodies, Boundaries and the Perception of Pain in the 1970s. Gend. Hist. 2020, 32, 70–85. [CrossRef]
Smalheiser, N.R. A Neglected Link Between the Psychoactive Effects of Dietary Ingredients and Consciousness-Altering Drugs.
Front. Psychiatry 2019, 10, 10–13. [CrossRef]
Anderson, E.W.; Rawnsley, K. Clinical Studies of Lysergic Acid Diethylamide. Monatsschr Psychiatr. Neurol. 1954, 128, 38–55.
[CrossRef]
Omidian, H.; Omidian, A. Clinical Research on Lysergic Acid Diethylamide (LSD) in Psychiatry and Neuroscience. Pharmaceuticals
2025, 18, 499. [CrossRef]

10. Meshkat, S.; Tello-Gerez, T.J.; Gholaminezhad, F.; Dunkley, B.T.; Reichelt, A.C.; Erritzoe, D.; Veremetten, E.; Zhang, Y.; Greenshaw,
A.; Burback, L.; et al. Impact of Psilocybin on Cognitive Function: A Systematic Review. Psychiatry Clin. Neurosci. 2024, 78,
744–764. [CrossRef]

11. Kelly, T.J.; Bonniwell, E.M.; Mu, L.; Liu, X.; Hu, Y.; Friedman, V.; Yu, H.; Su, W.; McCorvy, J.D.; Liu, Q.S. Psilocybin Analog
4-OH-DiPT Enhances Fear Extinction and GABAergic Inhibition of Principal Neurons in the Basolateral Amygdala. Neuropsy-
chopharmacology 2024, 49, 854–863. [CrossRef]

12. Rush, B.; Marcus, O.; Shore, R.; Cunningham, L.; Thomson, N.; Rideout, K. Psychedelic Medicine: A Rapid Review of Therapeutic

Applications and Implications for Future Research; Homewood Research Institute: Guelph, ON, Canada, 2022.

13. Czopek, A.; Jo ´nczyk, J.J.; Fryc, M.; Kluzik, D.; Zagórska, A. Classic Psychedelics in Pain Modulation: Mechanisms, Clinical

Evidence, and Future Perspectives. ACS Chem. Neurosci. 2025, 16, 2163–2177. [CrossRef]

14. Mastinu, A.; Anyanwu, M.; Carone, M.; Abate, G.; Bonini, S.A.; Peron, G.; Tirelli, E.; Pucci, M.; Ribaudo, G.; Oselladore, E.;
et al. The Bright Side of Psychedelics: Latest Advances and Challenges in Neuropharmacology. Int. J. Mol. Sci. 2023, 24, 1329.
[CrossRef]

15. Gonçalves, J.; Luís, Â.; Gallardo, E.; Duarte, A.P. Psychoactive Substances of Natural Origin: Toxicological Aspects, Therapeutic

Properties and Analysis in Biological Samples. Molecules 2021, 26, 1397. [CrossRef]

16. Collette, K.M. Rediscovering Psilocybin and Its Therapeutic Potential. Available online: https://www.caymanchem.com/news/r-

ediscovering-psilocybin-and-its-therapeutic-potential%0A (accessed on 15 September 2025).

17. Karabulut, S.; Kaur, H.; Gauld, J.W. Applications and Potential of In Silico Approaches for Psychedelic Chemistry. Molecules 2023,

28, 5966. [CrossRef]

18. Cameron, L.P.; Benson, C.J.; Defelice, B.C.; Fiehn, O.; Olson, D.E. Chronic, Intermittent Microdoses of the Psychedelic N, N-
Dimethyltryptamine (DMT) Produce Positive Effects on Mood and Anxiety in Rodents. ACS Chem. Neurosci. 2019, 10, 3261–3270.
[CrossRef]

19. Hibicke, M.; Landry, A.N.; Kramer, H.M.; Talman, Z.K.; Nichols, C.D. Psychedelics, but Not Ketamine, Produce Persistent
Antidepressant-like Effects in a Rodent Experimental System for the Study of Depression. ACS Chem. Neurosci. 2020, 11, 864–871.
[CrossRef] [PubMed]

20. Cameron, L.P.; Patel, S.D.; Vargas, M.V.; Barragan, E.V.; Saeger, H.N.; Warren, H.T.; Chow, W.L.; Gray, J.A.; Olson, D.E. 5-HT2ARs

21.

Mediate Therapeutic Behavioral Effects of Psychedelic Tryptamines. ACS Chem. Neurosci. 2023, 14, 351–358. [CrossRef]
Flanagan, T.W.; Billac, G.B.; Landry, A.N.; Sebastian, M.N.; Cormier, S.A.; Nichols, C.D. Structure-Activity Relationship Analysis
of Psychedelics in a Rat Model of Asthma Reveals the Anti-Inflammatory Pharmacophore. ACS Pharmacol. Transl. Sci. 2021, 4,
488–502. [CrossRef]

22. Campara, A.; Kovacic, D. Exploring Psilocybin as a Tool for Studying Parkinsonism-Related Psychosis: A Narrative Review
Supplemented with a Computational Approach. In Proceedings of the Mediterranean Conference on Medical and Biological Engineering
and Computing (MEDICON) and International Conference on Medical and Biological Engineering (CMBEBIH), Sarajevo, Bosnia, 14–16
September 2023; Conference Paper in IFMBE Proceedings; Springer: Cham, Switzerland, 2024.

23. Canal, C.E. Serotonergic Psychedelics: Experimental Approaches for Assessing Mechanisms of Action. Handb. Exp. Pharmacol.

2018, 252, 227–260. [CrossRef]

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

15 of 16

24. Warren, A.L.; Lankri, D.; Cunningham, M.J.; Serrano, I.C.; Parise, L.F.; Kruegel, A.C.; Duggan, P.; Zilberg, G.; Capper, M.J.; Havel,
V.; et al. Structural Pharmacology and Therapeutic Potential of 5-Methoxytryptamines. Nature 2024, 630, 237–246. [CrossRef]
[PubMed]

25. Zhang, M.; Yang, Y.; Yang, Z.; Wen, X.; Zhang, C.; Xiao, P.; Wang, Y.; Sun, J.; Wang, H.; Wang, X. Structural Insights into
Tryptamine Psychedelics: The Role of Hydroxyl Indole Ring Site in 5-HT2A Receptor Activation and Psychedelic-like Activity.
Eur. J. Med. Chem. 2025, 281, 117049. [CrossRef]

26. Khastar, H.; Foroughi, K.; Aghayan, S.S.; Yarmohammadi, M.; Jafarisani, M. Molecular Docking and Binding Interaction between

27.

28.

Psychedelic Drugs and Human Serum Albumin. Biotechnologia 2020, 101, 109–116. [CrossRef]
Fricke, J.; Sherwood, A.M.; Halberstadt, A.L.; Kargbo, R.B.; Hoffmeister, D. Chemoenzymatic Synthesis of 5-Methylpsilocybin: A
Tryptamine with Potential Psychedelic Activity. J. Nat. Prod. 2021, 84, 1403–1408. [CrossRef]
Sherwood, A.M.; Burkhartzmeyer, E.K.; Williamson, S.E.; Baumann, M.H.; Glatfelter, G.C. Psychedelic-like Activity of Norpsilocin
Analogues. ACS Chem. Neurosci. 2024, 15, 315–327. [CrossRef]

29. Longueville, A.-J. Synthesis of Psilocybin Analogues and Other 5-HT Receptor Agonists for Stimulation of Neurotransmission; Universiteit

Gent: Gent, Belgium, 2024.

30. Duan, W.; Cao, D.; Wang, S.; Cheng, J. Serotonin 2A Receptor (5-HT2AR) Agonists: Psychedelics and Non-Hallucinogenic

Analogues as Emerging Antidepressants. Chem. Rev. 2024, 124, 124–163. [CrossRef]

31. Vandevelde, M.; Simoens, A.; Vandekerckhove, B.; Stevens, C. Synthesis and Bioactivity of Psilocybin Analogues Containing a

Stable Carbon-Phosphorus Bond. RSC Med. Chem. 2024, 15, 998–1002. [CrossRef]

32. Klein, A.K.; Chatha, M.; Laskowski, L.J.; Anderson, E.I.; Brandt, S.D.; Chapman, S.J.; Mccorvy, J.D.; Halberstadt, A.L. Investigation
of the Structure-Activity Relationships of Psilocybin Analogues. ACS Pharmacol. Transl. Sci. 2021, 4, 533–542. [CrossRef]
33. Glatfelter, G.C.; Pham, D.N.K.; Walther, D.; Golen, J.A.; Chadeayne, A.R.; Baumann, M.H.; Manke, D.R. Synthesis, Structural
Characterization, and Pharmacological Activity of Novel Quaternary Salts of 4-Substituted Tryptamines. ACS Omega 2022, 7,
24888–24894. [CrossRef]

34. Glatfelter, G.C.; Pottie, E.; Partilla, J.S.; Sherwood, A.M.; Kaylo, K.; Pham, D.N.K.; Naeem, M.; Sammeta, V.R.; DeBoer, S.;
Golen, J.A.; et al. Structure−Activity Relationships for Psilocybin, Baeocystin, Aeruginascin, and Related Analogues to Produce
Pharmacological Effects in Mice. ACS Pharmacol. Transl. Sci. 2022, 5, 1181–1196. [CrossRef]
Jayakodiarachchi, N.; Maurer, M.A.; Schultz, D.C.; Dodd, C.J.; Thompson Gray, A.; Cho, H.P.; Boutaud, O.; Jones, C.K.; Lindsley,
C.W.; Bender, A.M. Evaluation of the Indazole Analogs of 5-MeO-DMT and Related Tryptamines as Serotonin Receptor 2 Agonists.
ACS Med. Chem. Lett. 2024, 15, 302–309. [CrossRef]

35.

36. Krabseth, H.M.; Silja, S.T.; Strand, M.C.; Karinen, R.A.; Wiik, E.; Vevelstad, M.S.; Westin, A.A.; Øiestad, E.L.; Vindenes, V. Novel

Psychoactive Substances. Tidsskr. Nor. Legeforen 2016, 136, 714–717. [CrossRef]

37. Li, G.; Facchini, P.J. New Frontiers in the Biosynthesis of Psychoactive Specialized Metabolites. Curr. Opin. Plant Biol. 2024, 82,

38.

39.

102626. [CrossRef]
Serreau, R.; Amirouche, A.; Benyamina, A.; Berteina-Raboin, S. A Review of Synthetic Access to Therapeutic Compounds
Extracted from Psilocybe. Pharmaceuticals 2023, 16, 40. [CrossRef]
Jacobson, C.B.; Berlin, C.M. Possible Reproductive Detriment in LSD Users. JAMA J. Am. Med. Assoc. 1972, 222, 1367–1373.
[CrossRef]

40. Chan, C.C.; Fishman, M.; Egbert, P.R. Multiple Ocular Anomalities Associated With Maternal LSD Ingestion. Arch. Ophthalmol.

1978, 96, 282–284.

41. Blanc, W.A.; Mattison, D.R.; Kane, R.; Chauhan, P. L.S.D., Intrauterine Amputations, and Amniotic-Band Syndrome. Lancet 1971,

298, 158–159. [CrossRef]
Scott, K.; Lust, K. Illicit Substance Use in Pregnancy—A Review. Obstet. Med. 2010, 3, 94–100. [CrossRef]

42.
43. Aase, J.M.; Laestadius, N.; Smith, D.W. Children of Mothers Who Took L.S.D. in Pregnancy. Lancet 1970, 296, 100–101. [CrossRef]
Singer, L.T.; Moore, D.G.; Min, M.O.; Goodwin, J.; Turner, J.J.D.; Fulton, S.; Parrott, A.C. Motor Delays in MDMA (Ecstasy)
44.
Exposed Infants Persist to 2 Years. Neurotoxicol. Teratol. 2016, 54, 22–28. [CrossRef]
Syed, O.A.; Tsang, B.; Petranker, R.; Gerlai, R. A Perspective on Psychedelic Teratogenicity: The Utility of Zebrafish Models.
Trends Pharmacol. Sci. 2023, 44, 664–673. [CrossRef] [PubMed]

45.

46. Melo, L.M.; de Barros, W.A.; de Fátima, Â.; Giusti, F.C.V.; Giusti-Paiva, A. Exposure to the Psychedelic Substance 25 H-NBOMe
Disrupts Maternal Care in Lactating Rats and Subsequently Impairs the Social Play Behavior of the Offspring. Behav. Brain Res.
2024, 465, 114924. [CrossRef]
Jairaj, C.; Rucker, J.J. Postpartum Depression: A Role for Psychedelics? J. Psychopharmacol. 2022, 36, 920–931. [CrossRef]

47.
48. Lipinski, C.A. Lead- and Drug-like Compounds: The Rule-of-Five Revolution. Drug Discov. Today Technol. 2004, 1, 337–341.

[CrossRef]

49. Lipinski, C.A. Rule of Five in 2015 and beyond: Target and Ligand Structural Limitations, Ligand Chemistry Structure and Drug

Discovery Project Decisions. Adv. Drug Deliv. Rev. 2016, 101, 34–41. [CrossRef]

https://doi.org/10.3390/molecules31020212

Molecules 2026, 31, 212

16 of 16

50. Di Filippo, J.I.; Bollini, M.; Cavasotto, C.N. A Machine Learning Model to Predict Drug Transfer Across the Human Placenta

Barrier. Front. Chem. 2021, 9, 714678. [CrossRef]

51. Geiger, H.A.; Wurst, M.G.; Daniels, R.N. DARK Classics in Chemical Neuroscience: Psilocybin. ACS Chem. Neurosci. 2018, 9,

2438–2447. [CrossRef] [PubMed]

52. Vamvakopoulou, I.A.; Narine, K.A.D.; Campbell, I.; Dyck, J.R.B.; Nutt, D.J. Mescaline: The Forgotten Psychedelic. Neuropharma-

cology 2023, 222, 109294. [CrossRef]

53. Ertl, P.; Schuffenhauer, A. Estimation of Synthetic Accessibility Score of Drug-like Molecules Based on Molecular Complexity and

Fragment Contributions. J. Cheminform. 2009, 1, 8. [CrossRef]

54. Takaku, T.; Nagahori, H.; Sogame, Y.; Takagi, T. Quantitative Structure-Activity Relationship Model for the Fetal-Maternal Blood

Concentration Ratio of Chemicals in Humans. Biol. Pharm. Bull. 2015, 38, 930–934. [CrossRef]

55. Wang, C.-C.; Lin, P.; Chou, C.-Y.; Wang, S.-S.; Tung, C.-W. Prediction of Human Fetal–Maternal Blood Concentration Ratio of

56.

57.

Chemicals. PeerJ 2020, 8, e9562. [CrossRef]
Soba ´nska, A.W. In Silico Assessment of Risks Associated with Pesticides Exposure during Pregnancy. Chemosphere 2023, 329,
138649. [CrossRef] [PubMed]
Sushko, I.; Novotarskyi, S.; Körner, R.; Pandey, A.K.; Rupp, M.; Teetz, W.; Brandmaier, S.; Abdelaziz, A.; Prokopenko, V.V.;
Tanchuk, V.Y.; et al. Online Chemical Modeling Environment (OCHEM): Web Platform for Data Storage, Model Development
and Publishing of Chemical Information. J. Comput. Aided Mol. Des. 2011, 25, 533–554. [CrossRef]

58. Daina, A.; Michielin, O.; Zoete, V. SwissADME: A Free Web Tool to Evaluate Pharmacokinetics, Drug-Likeness and Medicinal

Chemistry Friendliness of Small Molecules. Sci. Rep. 2017, 7, 42717. [CrossRef]

59. Yap, C.W. PaDEL-Descriptor: An Open Source Software to Calculate Molecular Descriptors and Fingerprints. J. Comput. Chem.

2011, 32, 1466–1474. [CrossRef]

60. Amemiya, T. Selection of Regressors. Int. Econ. Rev. 1980, 21, 331–354. [CrossRef]

Disclaimer/Publisher’s Note: The statements, opinions and data contained in all publications are solely those of the individual
author(s) and contributor(s) and not of MDPI and/or the editor(s). MDPI and/or the editor(s) disclaim responsibility for any injury to
people or property resulting from any ideas, methods, instructions or products referred to in the content.

https://doi.org/10.3390/molecules31020212

