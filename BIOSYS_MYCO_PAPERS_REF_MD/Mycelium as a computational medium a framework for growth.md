NaturalComputing
https://doi.org/10.1007/s11047-025-10040-x
(0123456789().,-volV)(0123456789().,-volV)
Mycelium as a computational medium: a framework for growth
modeling towards reservoir computing
Ioannis Tompris1 • Ioannis K. Chatzipaschalis1,2 • Theodoros Panagiotis Chatzinikolaou1 •
Georgios Kleitsiotis1 • Karolos-Alexandros Tsakalos1 • Iosif-Angelos Fyrigos1 • Michail-Antisthenis Tsompanas3 •
Andrew Adamatzky3 • Phil Ayres4 • Georgios Ch. Sirakoulis1
Accepted:2July2025
(cid:2)TheAuthor(s)2025
Abstract
Mycelium,theintricatevegetativenetworkoffungi,hasemergedasapromisingcandidatewithintherealmofengineered
livingmaterials(ELMs).Whileitsintriguingstructuralandelectricalpropertieshighlightitspotential,myceliumgrowthis
highly sensitive to environmental conditions. To bridge this gap, a robust framework was developed to both model
mycelium growth and explore its computational capabilities. This framework uses a cellular automata (CA) approach,
enhanced with reaction-diffusion (RD) processes, to simulate mycelium growth under diverse environmental conditions.
Thisconfiguration,combinedwithtunableparameters,enablestheidentificationandvalidationofoptimalgrowthpatterns,
supported by an algorithm designed to extract key features of hyphae–the fundamental building blocks of the mycelial
network. Subsequently, the small-world properties of the modeled mycelium networks were investigated, revealing high
clusteringcoefficientsandshortpathlengths,characteristicsthatmakethemwell-suitedforreservoircomputing(RC).To
demonstrate their computational capabilities, mycelium-inspired RC architectures were evaluated on the MNIST dataset
classification task, achieving an accuracy of up to 97.09%, highlighting the effectiveness of biologically inspired models.
As a result, this framework establishes a comprehensive test-bench for mycelium modeling, growth, and computational
exploration, paving the way for innovative applications in bio-inspired computing.
Keywords Mycelium (cid:2) Reaction diffusion (cid:2) Cellular automata (cid:2) Electrical activity (cid:2) Small-world (cid:2) Reservoir computing (cid:2)
Neuron
1 Introduction potentialcomputingapproach.Morespecifically,somestud-
ies(RobertsandAdamatzky2023;DehshibiandAdamatzky
Engineered Living Materials (ELMs) are considered as an 2021; Adamatzky et al. 2019) demonstrate the distinctive
emerging field of research, characterized by their unique electricalbehaviorofmyceliuminresponsetovariouselec-
ability to integrate self-healing, regenerative, and adaptive tricalstimuli,revealingacomplex,brain-likespikingpattern
traits of biological systems within contemporary materi- that encapsulates the depolarization, repolarization, and
als (Mora-Boza et al. 2023). Among various ELMs, myce- refractoryphasescharacteristicofbiologicalspikes,together
lium-basedmaterialsareparticularlynotable (Elsackeret al. withlow-voltageandsparsespikingactivity.
2023;Karanaet al.2018;Adamatzky2023)andserveasthe By integrating these electrical properties, combined with
focusofthisstudy.Thisisbecausemycelium,thevegetative mycelium’sstructuralcharacteristics,whichareindicativeof
structure of fungi, is widely recognized for its growth and small-world topologies, we enter the domain of liquid state
sustainability, offering an eco-friendly alternative to con- machines(LSMs),aclassofnetworksthatutilizebio-inspired
ventionalmaterialswhilebeingabundantlyavailableinnat- architectures and intricate dynamics (Tsakalos et al. 2021;
ure (Ayres et al. 2022; Angelova et al. 2021).Furthermore, Beiler et al. 2010; Dale et al. 2021; Maass 2011). LSMs
myceliumexhibitselectricalactivity, recentlyexploredasa belongtothebroaderframeworkofreservoircomputing(RC)
(Tanaka et al. 2019), which is utilized for solving pattern
recognition problems and cognitive tasks. In this approach,
Extendedauthorinformationavailableonthelastpageofthearticle
123

I.Tomprisetal.
| input data | is mapped   |     | onto a    | high-dimensional |           | space    | repre-     |     |     |     |     |     |     |     |
| ---------- | ----------- | --- | --------- | ---------------- | --------- | -------- | ---------- | --- | --- | --- | --- | --- | --- | --- |
| sentation  | through     | the | reservoir | dynamics,        |           | allowing | for the    |     |     |     |     |     |     |     |
| extraction | of temporal |     | and       | spatial          | features. | The      | reservoir, |     |     |     |     |     |     |     |
oftencomposedofspikingneuronsornon-lineardynamical
| units, uses | recurrent |     | connections |     | and temporal |     | memory to |     |     |     |     |     |     |     |
| ----------- | --------- | --- | ----------- | --- | ------------ | --- | --------- | --- | --- | --- | --- | --- | --- | --- |
processsequentialdata,makingitsuitablefortime-dependent
tasks,suchaspatternrecognitionandclassification.LSMscan
recognizecomplexpatternsovertime,makingthemusefulfor
tasksthatrequireadaptability.
| Despite                     | its | promising | topology, |       | electrical | activity, | and      |     |     |     |     |     |     |     |
| --------------------------- | --- | --------- | --------- | ----- | ---------- | --------- | -------- | --- | --- | --- | --- | --- | --- | --- |
| computingpotential,mycelium |     |           |           | faces | challenges |           | asafunc- |     |     |     |     |     |     |     |
tionalmaterial.Oneoftheprimaryobstaclesliesinitssen-
| sitivity | to environmental |     |     | conditions, | which |     | necessitates |     |     |     |     |     |     |     |
| -------- | ---------------- | --- | --- | ----------- | ----- | --- | ------------ | --- | --- | --- | --- | --- | --- | --- |
highlycontrolledcultivationenvironments.Preciseregula-
| tion of                      | temperature, |        | humidity,       |                | and light              | is              | essential to |     |     |     |     |     |     |     |
| ---------------------------- | ------------ | ------ | --------------- | -------------- | ---------------------- | --------------- | ------------ | --- | --- | --- | --- | --- | --- | --- |
| maintain                     | optimal      | growth | and             | functionality, |                        | making          | large-       |     |     |     |     |     |     |     |
| scale production             |              | and    | experimentation |                | both                   | resource-inten- |              |     |     |     |     |     |     |     |
| sive and                     | technically  |        | demanding       | (Omuse         |                        | et al.          | 2022; Arya   |     |     |     |     |     |     |     |
| andSingh2016;Jesse2023;Linet |              |        |                 |                | al.2021).Additionally, |                 |              |     |     |     |     |     |     |     |
thecommercializationofmycelium-basedmaterialsishin-
| dered by            | stringent | regulatory |           | frameworks    |     | (Aiduang | et al. |     |     |     |     |     |     |     |
| ------------------- | --------- | ---------- | --------- | ------------- | --- | -------- | ------ | --- | --- | --- | --- | --- | --- | --- |
| 2024; Molitorisova´ |           | et         | al. 2021; | Molitorisova´ |     | and      | Monaco |     |     |     |     |     |     |     |
2023).Asaresult,whilemyceliumholdsimmensepotential
| as a sustainable |     | and | computationally |     | active | material, | its |     |     |     |     |     |     |     |
| ---------------- | --- | --- | --------------- | --- | ------ | --------- | --- | --- | --- | --- | --- | --- | --- | --- |
practicalimplementationremainsachallengingendeavor.
| In this         | work,       | we exploit  |         | the unique |            | topology     | and elec-  |     |     |     |     |     |     |     |
| --------------- | ----------- | ----------- | ------- | ---------- | ---------- | ------------ | ---------- | --- | --- | --- | --- | --- | --- | --- |
| trical activity |             | of mycelium |         | to         | implement  | biologically |            |     |     |     |     |     |     |     |
| inspired        | reservoir   | networks    |         | for        | RC.        | By utilizing | the        |     |     |     |     |     |     |     |
| mycelium’s      | small-world |             | network |            | properties | and          | brain-like |     |     |     |     |     |     |     |
Fig.1 Statemachineoftheproposedframework
| spiking | behavior, | we  | demonstrate |     | effective |     | RC perfor- |     |     |     |     |     |     |     |
| ------- | --------- | --- | ----------- | --- | --------- | --- | ---------- | --- | --- | --- | --- | --- | --- | --- |
mance, achieving up to 97.09% accuracy on the MNIST Tompris et al. 2024). The model is developed within a CA
framework,whichprovidesadiscrete,lattice-basedstructure
| classification | task. | In  | this | direction, | a   | proof-of-concept |     |     |     |     |     |     |     |     |
| -------------- | ----- | --- | ---- | ---------- | --- | ---------------- | --- | --- | --- | --- | --- | --- | --- | --- |
framework, outlined in Fig. 1, is proposed. Section 2 thatenhancesparallelismandallowsprecisecontroloverthe
|            |                      |     |     |          |     |       |          | diffusion | dynamics | of  | the ELM, | (Tsompanas | et  | al. 2022; |
| ---------- | -------------------- | --- | --- | -------- | --- | ----- | -------- | --------- | -------- | --- | -------- | ---------- | --- | --------- |
| introduces | a reaction-diffusion |     |     | Mycelium |     | Model | within a |           |          |     |          |            |     |           |
Cellular Automata (CA) framework, incorporating Pavlidiset al.2023;Chatzinikolaouet al.2024;Vaxevanellis
et al.2024)ensuringseamlessintegrationwiththedesiredRD
adjustableFittingParameters&EnvironmentalConditions
to simulate mycelium growth under various factors. Sec- processes(Codd2014;Weimar1997).Incontrast,lattice-free
|                |     |            |     |             |     |            |       | approaches | documented |     | in  | the literature | demonstrate |     |
| -------------- | --- | ---------- | --- | ----------- | --- | ---------- | ----- | ---------- | ---------- | --- | --- | -------------- | ----------- | --- |
| tion 3 details |     | the Hyphae |     | Information |     | algorithm, | which |            |            |     |     |                |             |     |
evaluates growth and extracts Small-World Metrics to promising modelingcapabilities(CarverandBoswell2008;
|                |     |           |         |     |              |     |           | Vidal-DiezdeUlzurrunet |     |     | al.2017),althoughtheyoftenincur |     |     |     |
| -------------- | --- | --------- | ------- | --- | ------------ | --- | --------- | ---------------------- | --- | --- | ------------------------------- | --- | --- | --- |
| assess network |     | topology. | Section |     | 4 implements |     | Reservoir |                        |     |     |                                 |     |     |     |
Computing utilizing this topology, with configurable increased computational complexity and lack the inherent
|          |         |     |         |            |     |          |       | parallelism | offered | by  | CA-based | system. | Notably, | the pro- |
| -------- | ------- | --- | ------- | ---------- | --- | -------- | ----- | ----------- | ------- | --- | -------- | ------- | -------- | -------- |
| Training | Options | and | Network | Evaluation |     | methods, | which |             |         |     |          |         |          |          |
include both contemporary and biologically-inspired cost posedmodelemergesasanidealcandidateforimplementa-
|     |     |     |     |     |     |     |     | tion on | efficient | parallel | hardware | (Ntinas | et  | al. 2020; |
| --- | --- | --- | --- | --- | --- | --- | --- | ------- | --------- | -------- | -------- | ------- | --- | --------- |
functions.Finally,Section5concludesthepaperproviding
a thorough outline of its most important aspects. Karamani et al. 2021; Chatzinikolaou et al. 2022; Chatzi-
|            |     |       |     |     |     |     |     | paschaliset                       | al.2023),facilitatingthedevelopmentofareal- |     |           |           |     |     |
| ---------- | --- | ----- | --- | --- | --- | --- | --- | --------------------------------- | ------------------------------------------- | --- | --------- | --------- | --- | --- |
|            |     |       |     |     |     |     |     | timedigitaltwin(Chatzipaschaliset |                                             |     |           | al.2024). |     |     |
| 2 Mycelium |     | model |     |     |     |     |     |                                   |                                             |     |           |           |     |     |
|            |     |       |     |     |     |     |     | 2.1 Reaction-diffusion            |                                             |     | processes |           |     |     |
Reaction-Diffusion(RD)processesareessentialinthismodel
astheyenableaccuratefungalgrowthsimulations,including The mycelium model employed is grounded in RD pro-
|     |     |     |     |     |     |     |     | cesses (Sugimura |     | et al. | 2007; | Tompris | et al. | 2024), as |
| --- | --- | --- | --- | --- | --- | --- | --- | ---------------- | --- | ------ | ----- | ------- | ------ | --------- |
mechanismssuchashyphalextension,anastomosis,andapi-
calandlateralbranching(Frickeret al.2017;Boswell2008; articulated in Eqs. (1) - (4). It describes the growth of
123

Myceliumasacomputationalmedium:aframework...
mycelium, represented by the concentration c, as the out- TF ¼a(cid:5)T (cid:5)ðT (cid:3)T Þ(cid:5)ðT (cid:3)TÞ; T \T\T
min max min max
comeofintricateinteractionsbetweentheactivatorandthe
ð6Þ
inhibitor,componentsuandvrespectively,withtheformer
promoting mycelium growth, while the latter denotes it. HF ¼0:00232(cid:5)H2(cid:3)0:326(cid:5)Hþ11:4; H[H
min
ou ð7Þ
¼r2uþfðjuþu2(cid:3)kuvÞn; u2X ð1Þ
ot c 8 8(cid:5)10(cid:3)11(cid:5)LW4
ov ¼dr2vþfðlu3(cid:3)vÞ; v2X ð2Þ LF ¼
<
10(cid:3)4þ
p
ffi L ffiffi I ffiffi 4 ffiffi
; if LF(cid:6)2
ð8Þ
ot :
2; otherwise
dc
¼fmcðaðuÞ(cid:3)cÞðc(cid:3)1Þ; c2X ð3Þ The environmental effects are mathematically represented
dt
in Eqs. (5) - (8), where TF denotes the influence of tem-
(cid:2) n; if u(cid:4)threshold
perature,HFrepresentstheeffectofrelativehumidity,and
aðuÞ¼ ð4Þ
n(cid:3)hðu(cid:3)thresholdÞ; otherwise LF captures the impact of light. These factors can assume
values within the interval [0, 2]. Values below 1 restrict
A critical aspect to consider is the initial segment of
growth by directly limiting the concentration of the acti-
Eqs. (1) and (2), which relates to the diffusion term. This
vator, while values above 1 promote growth. The param-
segment employs the Laplacian operator r to precisely
etersn andn areadjustedtoalignwiththeproperties
describethe spatialpropagation ofthese components,with min span
of the simulated mycelium, and only one environmental
the parameter d governing the rate at which the inhibitor
conditionisexaminedatatime.Additionally,thesubstrate
expands relative to the activator. The second term in the
factor SF is introduced, to apply a small deviation of
corresponding equations,a polynomial ofu and v is called
approximately (cid:7)5% in the matrix n, ensuring a non-uni-
the reaction term and denotes the interaction between the
form and biologically plausible substrate.
twocomponentsandtheirrespectiveeffectsoneachother.
Furthermore, ithas been observedthat mycelium grows
Herein, the term f linearly scales the values of u and v to
bestinaparticulartemperaturerangerepresentinganormal
desirable ranges, while the adjustable terms d, j, k and l
distribution (Omuse et al. 2022), while outside of this
are treated as fitting parameters and allow for various
range, growth rates are slowed down by thermal stress (at
growth patterns, explained thoroughly in Section 3.1.
high temperatures) or enzymatic inefficiency (at low tem-
The variable spaces of X and X and the differences
c
peratures). The optimal temperature values for optimal
between them should also be noted. While X represents
growth seem to be between 10(cid:8)C (T ) and 35(cid:8)C (T )
growthofacomponentthroughoutthewholegrid,X ,tiedto min max
c withapeakaround25(cid:8)C,asillustratedinFig.2a.Inorder
the activator, defines a growth that is restricted within a
tomodelthisnon-linearcorrelationbetweenfungalgrowth
specified radius relative to c, effectively replicating the
and temperature, the Van Der Heide model has been
plasmamembraneofabiologicalorganismandmaintaining
used (Van der Heide et al. 2006), due to its simplicity and
biologicalfidelity.Finally,movingontoEqs.(3)and(4),itis
biologicalrelevanceinmodelingthenonlinearrelationship
evidentthattheactivatoruindirectlyregulatesthegrowthof
between temperature and fungal growth. This is described
myceliumcthroughthefunctiona(u),indicatingthatgrowth
inEq.(6),whereTFrepresentsthetemperature’sinfluence
occursonlywhentheactivatorreachesorexceedsaspecific
on mycelial growth rate due to a specific temperature (T),
thresholdvalue.Lastly,inEq.(4),thevaluesoftheparam-
while a is a multiplier to limit TF on the specified range
etersnandh,dependonthedefinedthresholdandenablecto
[0, 2].
assumebothpositiveandnegativevalues,througha(u).
Considering the humidity factor, it has been noted that
the mycelium can grow vigorously as humidity rises. The
2.2 Environmental conditions
reason is that the better hydration conditions allow nutri-
ents to be transported and enzymatic reactions that are
Mycelialgrowthcanbeaffectedbyenvironmentalfactorssuch
necessary for mycelial growth to occur. The Time of
astemperature,humidity,andlight.Inthemodel,theinfluence
Wetness (TOW) model, which links mycelium growth
of these environmental conditions on mycelial growth is
rates to the duration of high relative humidity (e.g., above
computedonthefactornofEq.(1),whichaffectsthereaction
80%),explainsthisphenomenon (AryaandSingh2016).It
term of the activator, encapsulating the aggregated environ-
has been observed that an area is not seen as prosperous
mental effects, as shown in Eq. (5), thereby dynamically
and, hence, growth is hindered when the humidity level
modifyinggrowthbehaviorsandenvironmentalinteractions.
falls below 75%. In accordance with the findings from
n¼n min þn span (cid:5)SF(cid:5)ðTF_HF_LFÞ ð5Þ Arya and Singh (2016), which suggest a positive associa-
tion of relative humidity to mycelial growth, the
123

I.Tomprisetal.
Fig.2 Normalizedeffectofenvironmentalfactorsintegratedontheproposedmodel,namely(a)temperature,(b)humidity,and(c)lightintensity
andwavelength
mathematical model relating humidity and growth is pre- 2.3 Cellular automata implementation
sentedinEq.(7).Herein,Hrepresentsrelativehumidityin
the span of [0, 100], while HF represents mycelial growth Herein, the algorithm underlying the mycelium model is
rate due to a specific humidity. The relationship between presentedandthoroughlyillustratedinFig.3anddescribedin
humidity and mycelial growth is depicted in Fig. 2b. Algorithm 1. To begin with, given thatthe concentrations of
Light exerts a complex and wavelength-dependent u andv mustbedeterminedpriortoc,andtheactivatoru is
influence on fungal mycelium growth. According to Lin constrained to values within a specific spatial range from c,
et al. (2021), the growth and reproduction of Aspergillus the first step involves defining the matrix X . This matrix is
c
oryzae were found to be highly sensitive to blue light constructed by conditionally updating its values, specifically
(around 475nm) under specific conditions, whereas green in cases where c exceeds 0.5, with a 5(cid:5)5 inverse-square
light (around 520nm) and red light (around 630nm) had distance-weighted kernel (L ), centered at the source (where
2
minimalimpactonthegrowthofmycelium.Theinhibitory c[0:5) (line 3 of Algorithm 1). This simulates the propa-
effectsoflightdependnotonlyonthewavelengthbutalso gation of the central‘‘fired‘‘ cell’s influence to its neighbors,
onitsintensity,whichismeasuredinlmolphotonsm(cid:3)2s(cid:3)1. withtheeffectdiminishingasafunctionofdistancefromthe
For instance, blue light at intensities of 60 and 80 source. Adjacent cells that are activated through this process
lmolphotonsm(cid:3)2s(cid:3)1 significantly suppressed mycelium are marked with X c ¼1, enabling the activator u in these
growth, reducing colony diameters compared to darkness. regions and facilitating its spread.
In contrast, red and green light consistently showed neg-
ligible inhibition, with growth rates comparable to those Algorithm1 Myceliummodelpseudo-code(iterativeprocess)
observed in complete darkness.
Thiswavelength-intensityinterplayreflectstheselective
activation of fungal photoreceptors, which are sensitive to
specificlightspectra.Bluelightreceptors,forexample,are
known to trigger inhibitory responses that reduce hyphal
elongationandsuppressconidiumproduction.Inthestudy,
thenumberofconidiaproducedunderbluelightirradiation
with and intensity of 80 lmolphotonsm(cid:3)2s(cid:3)1 was 57:4%
lower than that inthe darkness group. This starkreduction
underscores the potential for blue light to regulate fungal
reproduction in controlled environments. On the other
hand,redlightreceptorsappearedinactiveunderthetested
conditions, aligning with the insensitivity observed in
colony diameter and conidium yield. To capture this rela-
tionship, seen in Fig. 2c, the formula presented in Eq. (8)
was employed, with LW to represent the light wavelength
on the visible area [380, 780] and LI to represent the
intensity on the range [0, 100].
123

Myceliumasacomputationalmedium:aframework...
|     |     |     |     |     |     | time unit | dt¼10(cid:3)5 | was | applied | to  | both | the reaction | and |
| --- | --- | --- | --- | --- | --- | --------- | ------------- | --- | ------- | --- | ---- | ------------ | --- |
diffusion terms.
|     |     |     |     |     |     | Following | this, | the function |     | aðuÞ | is defined. | Depending |     |
| --- | --- | --- | --- | --- | --- | --------- | ----- | ------------ | --- | ---- | ----------- | --------- | --- |
onwhethertheactivator’sconcentrationmeetstherequired
|     |     |     |     |     |     | threshold,    | set                | to 1, c is      | subsequently |               | updated           | (lines        | 6-11).   |
| --- | --- | --- | --- | --- | --- | ------------- | ------------------ | --------------- | ------------ | ------------- | ----------------- | ------------- | -------- |
|     |     |     |     |     |     | Finally,      | the concentrations |                 | of           | u, v,         | and c             | are evaluated | to       |
|     |     |     |     |     |     | ensure they   | remain             | within          | their        | limits        | (lines            | 12-16).       | If any   |
|     |     |     |     |     |     | concentration |                    | falls outside   |              | the allowable |                   | range,        | it is    |
|     |     |     |     |     |     | bounded       | properly.          | In cases        | where        |               | the concentration |               | c is     |
|     |     |     |     |     |     | negative,     | a scenario         | that,           | while        | biologically  |                   | implausible,  |          |
|     |     |     |     |     |     | can arise     | due                | to the dynamics |              | of aðuÞ       | in discrete       |               | time and |
space,theconcentrationisnotimmediatelyclampedto0or
|     |     |     |     |     |     | 1. Instead, | a   | small negative |     | or positive |     | noise | term is |
| --- | --- | --- | --- | --- | --- | ----------- | --- | -------------- | --- | ----------- | --- | ----- | ------- |
introduced,respectively,toensurecontinuedgrowthunder
|     |     |     |     |     |     | the constraints |              | of discrete   | time         | and            | space.        | This approach |           |
| --- | --- | --- | --- | --- | --- | --------------- | ------------ | ------------- | ------------ | -------------- | ------------- | ------------- | --------- |
|     |     |     |     |     |     | maintains       | the          | system’s      | stability    | while          | accommodating |               | the       |
|     |     |     |     |     |     | inherent        | limitations  | of            | the modeling |                | framework.    |               |           |
|     |     |     |     |     |     | 2.4 CA          | response     | under         | different    |                | conditions    |               |           |
|     |     |     |     |     |     | The response    |              | of the        | employed     | CA             | model         | to            | different |
|     |     |     |     |     |     | environmental   |              | conditions    | is evaluated |                | in this       | Section.      | The       |
|     |     |     |     |     |     | precise         | calculations | allow         |              | the simulation |               | of            | mycelial  |
|     |     |     |     |     |     | behavior        | under        | varied        | conditions,  |                | making        | the           | model a   |
|     |     |     |     |     |     | robust tool     | for          | predictive    | analysis     | and            | optimization. |               |           |
|     |     |     |     |     |     | In Fig.         | 4a-b,        | the influence |              | of varying     |               | temperatures  | on        |
myceliumgrowthisillustrated.Optimalgrowthisobserved
|     |     |     |     |     |     | at T ¼25(cid:8)C, |     | while minor | deviations |     | from | this tempera- |     |
| --- | --- | --- | --- | --- | --- | ----------------- | --- | ----------- | ---------- | --- | ---- | ------------- | --- |
¼29(cid:8)C,donotsignificantlyimpedegrowth
| Fig. 3 Representation |     | of the | RD algorithm | utilized | in the proposed | ture,suchasT |     |     |     |     |     |     |     |
| --------------------- | --- | ------ | ------------ | -------- | --------------- | ------------ | --- | --- | --- | --- | --- | --- | --- |
CAMyceliumModel.Beginswithinitializationofu,v,c.Following, and can still support favorable development. In contrast,
| X is generated | based      | on    | the concentration | of                  | c. Should it be |             |            |     |         |         |        |        |      |
| -------------- | ---------- | ----- | ----------------- | ------------------- | --------------- | ----------- | ---------- | --- | ------- | ------- | ------ | ------ | ---- |
| c              |            |       |                   |                     |                 | substantial | deviations |     | lead to | reduced | growth | rates, | pri- |
| sufficient,    | apart from | v , u | is also           | generated promoting | growth          |             |            |     |         |         |        |        |      |
new new marily due to enzymatic inefficiency or thermal stress, as
| andaðu newÞiscalculated.Finally,c |     |     | isdefinedbasedonaðu |     | newÞand |     |     |     |              |     |     |     |     |
| --------------------------------- | --- | --- | ------------------- | --- | ------- | --- | --- | --- | ------------ | --- | --- | --- | --- |
|                                   |     |     | new                 |     |         |     |     |     | ¼15(cid:8)C. |     |     |     |     |
eachofthecomponentsfu;v;cg areboundedtotheircorrespond- evidenced in the case of T
new
| ingranges |     |     |     |     |     | Following,Fig. |          | 4c-dpresentthemyceliumgrowthunder |              |     |        |         |          |
| --------- | --- | --- | --- | --- | --- | -------------- | -------- | --------------------------------- | ------------ | --- | ------ | ------- | -------- |
|           |     |     |     |     |     | different      | relative | humidity                          | levels.      |     | A very | high    | relative |
|           |     |     |     |     |     | humidity       | ensures  | mycelium                          | development, |     |        | like in | the case |
AfterthevariablespaceX isdeterminedandmovingon of H ¼97%, where a proper growth can be observed. On
c
to the calculation of the activator and inhibitor, the theotherhand,insufficienthumiditycaninhibitgrowth,as
Laplacian operator, which models diffusion across space observed in the case of H ¼84%.
(O’Reilly and Beck 2006), is applied to u and v, by con- Finally, the influence of light on mycelium growth is
volving the system with a 3(cid:5)3 Laplacian kernel (L Þ depicted in Fig. 4e-f. Light affects mycelial development
1
(lines4and5).Thisapproachallowsfortheparallelupdate primarily through its wavelength (LW) and intensity (LI).
|                       |     |     |          |             |               | Short wavelengths, |     | such | as blue | light, | particularly |     | at high |
| --------------------- | --- | --- | -------- | ----------- | ------------- | ------------------ | --- | ---- | ------- | ------ | ------------ | --- | ------- |
| of the concentrations |     | of  | both the | activator u | and the inhi- |                    |     |      |         |        |              |     |         |
bitor v, along with the calculation of the corresponding intensity,are demonstrated toinhibitgrowth(480nmat an
lmolphotonsm(cid:3)2s(cid:3)1),
reactiontermsofuandv.Also,inthisstateoftheCA,the intensity of 80 whereas red light,
growthmatrixnisintegratedwiththereactiontermsofthe especially at low intensity, exhibits minimal inhibitory
activator u, allowing the model to simulate growth under effects (630nm at an intensity of 0). This is clearly
distinct environmental influences. It is noteworthy that the demonstrated by the limited growth observed under blue
calculation of the concentration of each RD component light compared to the red light scenario.
| involves | the time | derivative, | and | consequently | a relative |     |     |     |     |     |     |     |     |
| -------- | -------- | ----------- | --- | ------------ | ---------- | --- | --- | --- | --- | --- | --- | --- | --- |
123

I.Tomprisetal.
Fig.4 Impactofdiverse
environmentalconditionson
myceliumgrowthevery15,000
timesteps,ina200(cid:5)200lattice
(a)Temperature’simpactforT =15C
(b)Temperature’simpactforT =29C
(c)Humidity’simpactforH=84%
(d)Humidity’simpactforH=97%
(e)Light’simpactforLW =480nmandLI=80µmolphotonsm−2s−1
(f)Light’simpactforLW =630nmandLI=0µmolphotonsm−2s−1
123

Myceliumasacomputationalmedium:aframework...
3 Evaluating model as a reservoir network therobustnessandvitalityoffungalgrowth,akernelbased
|     |     |     |     |     |     |     | on the inverse |     | square | of the | distance | from | the | core is |
| --- | --- | --- | --- | --- | --- | --- | -------------- | --- | ------ | ------ | -------- | ---- | --- | ------- |
Modeling itself can reproduce plausible results. However, convolved with the tip locations of c. This convolution
it is difficult to accurately simulate mycelium growth measurestheintensitydistributionaroundeachtip,serving
because of the complex and dynamic interactions between as a proxy for width. Finally, to determine the length of
hyphae, the fundamental structural units of mycelium each tip that gives information about the magnitude and
(namely the tips), and their surroundings. In most fungi, direction of fungal growth, a breadth-first search (BFS)
hyphae serve as the primary mechanism for vegetative algorithm is utilized. Starting from each identified tip, the
growthandarecollectivelyreferredtoasmycelium.Being BFS investigates the shortest route from the tip to the
able to identify which parameters can be adjusted accord- mycelium core, tracing the hyphae backwards to the core.
ingly to match realistic fungi behavior can lead to an Thesearchterminateswhenacorecellisdetected,andthe
accurate reservoir network with proper computational pathlengthisthenmeasuredtoindicatehowfarthehyphal
properties based on its small-world properties. tip extends from the core. In Fig. 5 the metrics are visu-
alizedona2Dplane,takingintoaccountthedefaultvalues
3.1 Hyphae information extraction forthetuningparameters.InFig. 5bthemyceliumcorehas
|     |     |     |     |     |     |     | been identified, |     | while | in Fig. 5c-d | each | cell | represents | the |
| --- | --- | --- | --- | --- | --- | --- | ---------------- | --- | ----- | ------------ | ---- | ---- | ---------- | --- |
Given the model’s emphasis is on generalization, its tip width and tip length, respectively.
capacity to represent a variety of mycelium structures, ThevisualizedmetricsinFig. 6illustratehowvariations
greaterattentionshouldbedirectedtowardstheparameters in the four key parameters (d, j, k, and l) by (cid:7)5% affect
d, j, k, and l, which critically influence the topological hyphal growth characteristics, including tip count, average
characteristicsofthehyphae,particularlythecount,width, width, and average length. These parameters align with
andlengthofthehyphaltipsandultimatelyserveastuning theirrolesinEqs.(1)-(4),demonstratingtheirinfluenceon
|             |     |          |     |           |                  |     | hyphal morphology. |     |     | The parameter |     | d, representing |     | the |
| ----------- | --- | -------- | --- | --------- | ---------------- | --- | ------------------ | --- | --- | ------------- | --- | --------------- | --- | --- |
| parameters. | To  | quantify | the | specified | characteristics, | an  |                    |     |     |               |     |                 |     |     |
algorithm has been developed to generate the necessary ratiobetweentheinhibitor’sandactivator’sdiffusionrates,
|         |               |     |       |        |               |      | enhances | inhibitor | diffusion, |     | allowing | it to | spread | more |
| ------- | ------------- | --- | ----- | ------ | ------------- | ---- | -------- | --------- | ---------- | --- | -------- | ----- | ------ | ---- |
| metrics | for adjusting | the | model | to the | corresponding | real |          |           |            |     |          |       |        |      |
mycelium as it calculates the discussed hyphal features of extensively across the grid. This forces the activator into
|                 |     |          |        |     |        |            | narrower | pathways, | leading | to  | increased | branching |     | and tip |
| --------------- | --- | -------- | ------ | --- | ------ | ---------- | -------- | --------- | ------- | --- | --------- | --------- | --- | ------- |
| an experimental |     | mycelium | image. | In  | such a | way, it is |          |           |         |     |           |           |     |         |
possibletoinferthefungalnetwork’sefficiency,flexibility, count while reducing hyphal width. The parameter j
|             |        |       |           |                |     |         | amplifies | activator | concentration, |     | promoting |     | both | wider |
| ----------- | ------ | ----- | --------- | -------------- | --- | ------- | --------- | --------- | -------------- | --- | --------- | --- | ---- | ----- |
| and general | health | under | different | circumstances, |     | leading |           |           |                |     |           |     |      |       |
to modeling simulations that closely resemble actual and longer hyphal tips. In contrast, k reduces width and
|              |     |        |         |     |     |     | length by | lowering | activator | concentration |     | while | simulta- |     |
| ------------ | --- | ------ | ------- | --- | --- | --- | --------- | -------- | --------- | ------------- | --- | ----- | -------- | --- |
| observations | of  | fungal | growth. |     |     |     |           |          |           |               |     |       |          |     |
Initially,themyceliumcoremustbedetermined,asitis neouslydecreasingtipcountbydiminishingtheinhibitor’s
|             |          |       |     |        |         |             | influence | in the | reaction | terms. | Lastly, | l   | suppresses | all |
| ----------- | -------- | ----- | --- | ------ | ------- | ----------- | --------- | ------ | -------- | ------ | ------- | --- | ---------- | --- |
| the central | hub from | which | the | hyphal | strands | occur. This |           |        |          |        |         |     |            |     |
process is achieved by applying a convolutional kernel to three characteristics, tip width, length, and count, by
directlyincreasinginhibitorconcentration,therebylimiting
| detect regions | within | the | matrix | c, which | represents | the |     |     |     |     |     |     |     |     |
| -------------- | ------ | --- | ------ | -------- | ---------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
mycelium concentration. This process identifies areas overall growth and structural expansion.
| characterized | by  | eight | high-concentration |     | neighbors | that |     |     |     |     |     |     |     |     |
| ------------- | --- | ----- | ------------------ | --- | --------- | ---- | --- | --- | --- | --- | --- | --- | --- | --- |
signify the core of the structure. Subsequently, a specified 3.2 Small-world properties
| concentration | threshold |     | is applied | to these | regions | to val- |     |     |     |     |     |     |     |     |
| ------------- | --------- | --- | ---------- | -------- | ------- | ------- | --- | --- | --- | --- | --- | --- | --- | --- |
idatethetruecoreandnototherdenselyconnectedregions. With the mycelium model and feature extraction estab-
lished,thisworkexploreshowtheuniquecharacteristicsof
| This threshold |     | is dynamically |     | determined | based | on the |     |     |     |     |     |     |     |     |
| -------------- | --- | -------------- | --- | ---------- | ----- | ------ | --- | --- | --- | --- | --- | --- | --- | --- |
concentration range, the predefined number of growth mycelium’s structure can serve as a basis for unconven-
|            |        |        |     |             |             |       | tional computing |     | that | is resource-, | cost-, | and | power-effi- |     |
| ---------- | ------ | ------ | --- | ----------- | ----------- | ----- | ---------------- | --- | ---- | ------------- | ------ | --- | ----------- | --- |
| iterations | in the | model, | and | the initial | conditions, | which |                  |     |      |               |        |     |             |     |
influence the rate at which the maximum concentration cient.Itsintricatestructure,whichismarkedwithhighand
|            |       |             |      |               |     |             | random | connectivity, |     | showcases | a small-world |     | topology, |     |
| ---------- | ----- | ----------- | ---- | ------------- | --- | ----------- | ------ | ------------- | --- | --------- | ------------- | --- | --------- | --- |
| within the | range | is achieved | over | the specified |     | iterations. |        |               |     |           |               |     |           |     |
In order to detect the first characteristic (the hyphal mainly high connectivity at its core sparsity connections
|         |               |     |      |            |        |         | near its | edges, | which | is a useful | attribute |     | for building |     |
| ------- | ------------- | --- | ---- | ---------- | ------ | ------- | -------- | ------ | ----- | ----------- | --------- | --- | ------------ | --- |
| count), | the algorithm |     | must | locate the | hyphal | tips by |          |        |       |             |           |     |              |     |
employing neighbor count analysis. They are represented reservoir networks, as it has been shown to improve the
|              |       | c       |     |                |     |           | echo-state | property | (Kawai | et  | al. 2019). | Additionally, |     | it  |
| ------------ | ----- | ------- | --- | -------------- | --- | --------- | ---------- | -------- | ------ | --- | ---------- | ------------- | --- | --- |
| as the array | cells | of with | a   | limited number | of  | neighbors |            |          |        |     |            |               |     |     |
(three or fewer) having less than a specific concentration. has been shown that the echo-state property in reservoir
Thisconcentrationisrelativetotheconcentrationofcnear computing is improved by small-world characteristics,
itsedges.Tocomputethe widthofeach tip,which reflects which are characterized by high node clustering and short
123

I.Tomprisetal.
Fig.5 Basicmyceliumcharacteristicsproducedbythehyphaeextractionalgorithm,namely:aconcentration,bcore,ctipwidth,anddtiplength
Fig.6 Changein:ahyphaltipcount,baveragetipwidthandcaveragelength(logscale)byadjustingthemodel’stuningparametersto(cid:7)5%of
theirdefaultvalues,beingd¼29,j¼0:8,k¼0:8andl¼3:5
| path lengths | between |     | nodes | (Tsakalos |     | et al. 2021; | Man- |     |     |     |     |     |
| ------------ | ------- | --- | ----- | --------- | --- | ------------ | ---- | --- | --- | --- | --- | --- |
neschi et al. 2021; Bassett and Bullmore 2017). Table1 Small-Worldcharacteristicsfor30runsofthemodel
Inordertoevaluatethemyceliummodel’sfeasibilityas Averagepathlength Clusteringcoefficient
| a reservoir,     | the            | average | path                         | length        | (APL)   | and            | average   |              |               |              |     |               |
| ---------------- | -------------- | ------- | ---------------------------- | ------------- | ------- | -------------- | --------- | ------------ | ------------- | ------------ | --- | ------------- |
|                  |                |         |                              |               |         |                |           | 1(cid:3)1.65 | 16(cid:3)1.72 | 1(cid:3)0.19 |     | 16(cid:3)0.21 |
| clustering       | coefficient    |         | (C),                         | two important |         | metrics        | repre-    |              |               |              |     |               |
|                  |                |         | i                            |               |         |                |           | 2(cid:3)1.58 | 17(cid:3)1.69 | 2(cid:3)0.18 |     | 17(cid:3)0.20 |
| sentative        | of small-world |         | characteristics,             |               |         | were computed. |           |              |               |              |     |               |
|                  |                |         |                              |               |         |                |           | 3(cid:3)1.71 | 18(cid:3)1.63 | 3(cid:3)0.20 |     | 18(cid:3)0.19 |
| The results      | were           | shown   | for                          | 30 different  |         | runs, as       | presented |              |               |              |     |               |
|                  |                |         |                              |               |         |                |           | 4(cid:3)1.67 | 19(cid:3)1.74 | 4(cid:3)0.21 |     | 19(cid:3)0.18 |
| in Table         | 1, to          | ensure  | fidelity                     | and           | account | for            | the small |              |               |              |     |               |
|                  |                |         |                              |               |         |                |           | 5(cid:3)1.82 | 20(cid:3)1.68 | 5(cid:3)0.19 |     | 20(cid:3)0.22 |
| randomness       | inherent       |         | in the                       | model.        | First,  | an             | adjacency |              |               |              |     |               |
|                  |                |         |                              |               |         |                |           | 6(cid:3)1.73 | 21(cid:3)1.77 | 6(cid:3)0.20 |     | 21(cid:3)0.21 |
| matrix           | A, derived     | from    | the                          | mycelium’s    |         | concentration  |           |              |               |              |     |               |
|                  |                |         |                              |               |         |                |           | 7(cid:3)1.79 | 22(cid:3)1.75 | 7(cid:3)0.18 |     | 22(cid:3)0.19 |
| matrix c,hasbeen |                | created | inordertoobtainthesemetrics. |               |         |                |           |              |               |              |     |               |
Inaddition,themodelwastreatedasanunweightedgraph, 8(cid:3)1.66 23(cid:3)1.71 8(cid:3)0.22 23(cid:3)0.20
|           |      |        |        |          |     |               |      | 9(cid:3)1.74 | 24(cid:3)1.69 | 9(cid:3)0.19 |     | 24(cid:3)0.18 |
| --------- | ---- | ------ | ------ | -------- | --- | ------------- | ---- | ------------ | ------------- | ------------ | --- | ------------- |
| with each | cell | of the | matrix | c having |     | a significant | con- |              |               |              |     |               |
centration (greater than 0.5) being considered as a node. 10(cid:3)1.81 25(cid:3)1.72 10(cid:3)0.21 25(cid:3)0.20
|         |          |     |      |         |      |          |            | 11(cid:3)1.83 | 26(cid:3)1.70 | 11(cid:3)0.20 |     | 26(cid:3)0.19 |
| ------- | -------- | --- | ---- | ------- | ---- | -------- | ---------- | ------------- | ------------- | ------------- | --- | ------------- |
| The APL | (Average |     | Path | Length) | is a | critical | metric for |               |               |               |     |               |
evaluatingtheefficiencyofinformationpropagationwithin 12(cid:3)1.68 27(cid:3)1.76 12(cid:3)0.18 27(cid:3)0.21
|            |       |         |        |      |     |              |       | 13(cid:3)1.85 | 28(cid:3)1.73 | 13(cid:3)0.19 |     | 28(cid:3)0.20 |
| ---------- | ----- | ------- | ------ | ---- | --- | ------------ | ----- | ------------- | ------------- | ------------- | --- | ------------- |
| a network. | It is | defined | as the | mean | of  | the shortest | paths |               |               |               |     |               |
between all pairs of nodes and is computed using Eq. (9), 14(cid:3)1.72 29(cid:3)1.78 14(cid:3)0.21 29(cid:3)0.18
|            |               |     |     |          |      |          |         | 15(cid:3)1.77 | 30(cid:3)1.74 | 15(cid:3)0.20 |     | 30(cid:3)0.19 |
| ---------- | ------------- | --- | --- | -------- | ---- | -------- | ------- | ------------- | ------------- | ------------- | --- | ------------- |
| where d(i, | j) represents |     | the | shortest | path | distance | between |               |               |               |     |               |
nodes i and j, and N denotes the total number of nodes. A Avg-1.729 Avg-0.198
| low APL            | (greater     | than | but      | close | to         | 1) signifies | rapid    |     |     |     |     |     |
| ------------------ | ------------ | ---- | -------- | ----- | ---------- | ------------ | -------- | --- | --- | --- | --- | --- |
| information        | transmission |      | across   | the   | network,   | a fundamen-  |          |     |     |     |     |     |
| tal characteristic |              | for  | enabling | the   | responsive |              | dynamics |     |     |     |     |     |
1 X
required in reservoir computing (Nakajima and Fischer APL¼ dði;jÞ
ð9Þ
NðN(cid:3)1Þ
| 2021). |     |     |     |     |     |     |     |                | i6¼j                   |            |                |              |
| ------ | --- | --- | --- | --- | --- | --- | --- | -------------- | ---------------------- | ---------- | -------------- | ------------ |
|        |     |     |     |     |     |     |     | The clustering | coefficient            | quantifies | the propensity | of           |
|        |     |     |     |     |     |     |     | nodes to form  | densely interconnected |            | groups,        | facilitating |
123

Myceliumasacomputationalmedium:aframework...
|     |     |     | (a)Contemporary |     |     |     |     |     |     |     | (b)Biological |     |     |     |
| --- | --- | --- | --------------- | --- | --- | --- | --- | --- | --- | --- | ------------- | --- | --- | --- |
Fig.7 ThetwoReservoirnetworkarchitecturesemployed,differingintheiroutput
localized and intricate dynamics within the network. For a clustering coefficient and optimal average path length
given node i, C is determined by Eq. (10), where degðiÞ confirm its suitability for dynamic, nonlinear applications.
i
| represents |     | the degree | of  | node | i. A high | clustering | coeffi- |     |     |     |     |     |     |     |
| ---------- | --- | ---------- | --- | ---- | --------- | ---------- | ------- | --- | --- | --- | --- | --- | --- | --- |
cient(lessthanbutcloseto1)isahallmarkofsmall-world
|          |     |              |     |           |          |     |             | 4 Reservoir |     | computing |     | with | mycelium | CA- |
| -------- | --- | ------------ | --- | --------- | -------- | --- | ----------- | ----------- | --- | --------- | --- | ---- | -------- | --- |
| networks |     | and enhances | the | network’s | capacity |     | to generate |             |     |           |     |      |          |     |
diverse,context-dependentresponses,whicharecrucialfor based networks
| applications |     | in reservoir |     | computing |     | (Gallicchio | et al. |     |     |     |     |     |     |     |
| ------------ | --- | ------------ | --- | --------- | --- | ----------- | ------ | --- | --- | --- | --- | --- | --- | --- |
2018). The biological mycelium has been the subject of research
|     | P   |           |      |     |     |     |     | regarding | its electrical |     | activity | (Adamatzky | 2022, | 2018b), |
| --- | --- | --------- | ---- | --- | --- | --- | --- | --------- | -------------- | --- | -------- | ---------- | ----- | ------- |
|     |     | A ij A jk | A ki |     |     |     |     |           |                |     |          |            |       |         |
C ¼ j;k ð10Þ whichhasdemonstrateditsabilitytopropagateinformation
i
degðiÞðdegðiÞ(cid:3)1Þ
|     |     |     |     |     |     |     |     | and electrical | signals |     | across | its network. | In  | particular, |
| --- | --- | --- | --- | --- | --- | --- | --- | -------------- | ------- | --- | ------ | ------------ | --- | ----------- |
studieshaverevealedthatmycelialnetworksarecapableof
TheAPLvaluesdemonstrateanaverageof1:729acrossall
configurations, with a range extending from 1:58 to 1:85, performing basic computational operations, such as
|       |     |            |         |     |         |           |         | implementing |     | Boolean | logic | gates | (Adamatzky | et al. |
| ----- | --- | ---------- | ------- | --- | ------- | --------- | ------- | ------------ | --- | ------- | ----- | ----- | ---------- | ------ |
| while | the | C i values | exhibit | an  | average | of 0:198, | ranging |              |     |         |       |       |            |        |
from 0:18 to 0:22. To assess these metrics and determine 2022). When combined with its inherent small-world
properties,markedbyhighclusteringcoefficientsandshort
| whether | the | resulting | topology |     | exhibits | small-world | char- |     |     |     |     |     |     |     |
| ------- | --- | --------- | -------- | --- | -------- | ----------- | ----- | --- | --- | --- | --- | --- | --- | --- |
acteristics, the small-world coefficient must be computed. path lengths, these properties suggest mycelium could be
If this coefficient, derived from Eq. (11), exceeds one an effective substrate for reservoir computing.
(S[1), results in the topology being classified as small- Toevaluatethispotential,twodifferentmycelium-based
world (Hung and Wang 2010). reservoir networks, illustrated in Fig. 7, have been defined
|     |     |     |     |     |     |     |     | and their | performance |     | was evaluated |     | on the classification |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --------- | ----------- | --- | ------------- | --- | --------------------- | --- |
|     | C   | L   |     |     |     |     |     |           |             |     |               |     |                       |     |
S¼ graph (cid:2) random ð11Þ of the MNIST dataset, thereby constituting a comprehen-
|         | C random | L graph   |       |           |             |     |             |               |          |                   |     |            |           |           |
| ------- | -------- | --------- | ----- | --------- | ----------- | --- | ----------- | ------------- | -------- | ----------------- | --- | ---------- | --------- | --------- |
|         |          |           |       |           |             |     |             | sive testbed. | Both     | networks          |     | start with | a fully   | connected |
|         | L        |           | C     |           |             |     |             | inputlayer,   | followed | byamycelium-based |     |            | reservoir | layer.    |
| Herein, |          | graph and | graph | represent | the average |     | path length |               |          |                   |     |            |           |           |
and average clustering coefficient of the graph, respec- The construction of the reservoir layer utilizes the adja-
|           |         |               |            |               |               |                   |           | cency matrix          | A             | analyzed      | in Section  |          | 2 as its weight | matrix.      |
| --------- | ------- | ------------- | ---------- | ------------- | ------------- | ----------------- | --------- | --------------------- | ------------- | ------------- | ----------- | -------- | --------------- | ------------ |
| tively,   | while   | L random      | and        | C random      | denote        | the corresponding |           |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | The response          | of            | the reservoir |             | layer    | to each         | image, for a |
| metrics   | for     | a random      | graph      | with          | an equivalent |                   | number of |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | time window           | of            | 6ms,          | is captured |          | and, along      | with the     |
| nodes     | and     | edges.        | These      | metrics       | were computed |                   | using the |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | corresponding         | labels,       | is            | used        | to train | the output      | weights      |
| NetworkX  |         | Python        | package    | (Hagberg      |               | et al. 2008),     | which     |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | (W ) of               | the networks. |               |             |          |                 |              |
| supported |         | the efficient | generation |               | of            | a sufficiently    | large     | O                     |               |               |             |          |                 |              |
| sample    | (up     | to 30         | instances) | of            | random        | graph metrics.    | The       |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | 4.1 Reservoir         |               | layer neuron  |             |          |                 |              |
| results   | not     | only yielded  |            | a small-world |               | coefficient       | signifi-  |                       |               |               |             |          |                 |              |
| cantly    | greater | than          | one        | but also      | revealed      | values            | consis-   |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | The electrical        |               | activity      | observed    | in       | mycelium        | exhibits     |
| tently    | ranging | between       |            | 30 and        | 1000,         | highlighting      | the       |                       |               |               |             |          |                 |              |
|           |         |               |            |               |               |                   |           | striking similarities |               | to            | biological  | neuronal | spiking         | behav-       |
| mycelium  |         | network’s     | strong     | potential     |               | as a small-world  |           |                       |               |               |             |          |                 |              |
topology. These resultsindicate the network’s capacity for ior, characterized by distinct phases of depolarization,
repolarization,andarefractoryperiod(Adamatzky2018a).
rapiddatapropagationandstructuraladaptability.Thehigh
Thus,abiologicalneuronmodelisselectedinthereservoir
123

I.Tomprisetal.
layer’s nodes to properly replicate key neuronal phenom- constant d to account for the refractory period following a
ena,suchasactionpotentialsandthresholdbehavior.There spike. As aresult, the neuron outputs I as a response toits
are various such models, including the Leaky Integrate- inputs, and the FHN model captures the interplay between
and-Fire (LIF), the Izhikevich (IZH), and the FitzHugh- membrane potential dynamics, recovery processes, and
Nagumo (FHN); yet, this work is mostly focused on the external stimuli, providing a comprehensive description of
FHN model, as prior studies have demonstrated its effec- neural spiking behavior.
tiveness in mimicking the electrical activity of mycelium To enhance the realism of the spiking behavior of the
(Adamatzky et al. 2022). nodes, the Nelder-Mead method (Nelder and Mead 1965)
The model in question is an efficient representation of wasappliedtoadjusttheparameters(cid:2),a,andbintheFHN
neuronal dynamics, capturing the essential features of equation set. This optimization process aimed to align the
spiking behavior while remaining computationally inex- model’s output with specific spiking characteristics,
pensive. The FHN model is a two-dimensional simplifica- including period, amplitude, duration, depolarization rate,
tion of the Hodgkin-Huxley equations (Phillipson and repolarization rate, and refractory period, as observed in
Schuster 2005), describing the activation and inactivation studies of fungal electrical activity (Adamatzky 2018a).
of ion channels in neuronal membranes. It consists of two The optimization was guided by minimizing the mean
coupled differential equations, showcased in Eqs. (12) - squarederror(MSE)betweenthesimulatedFHNdynamics
(15)(Heet al.2020).Byincorporatingitintothenetwork, and the target spiking features, ensuring a close match to
thisworkaimstobetteremulatetheelectricalpropertiesof the empirical data. By iteratively refining the parameters,
biological neurons, thereby providing a more realistic the algorithm successfully captured the essential electrical
frameworkforevaluatingthecomputationalcapabilitiesof characteristic of fungal spiking, as shown in Fig. 8, and
mycelium-based reservoirs. more specifically the spiking characteristics of the oyster
|       |     |     |     |     |     |     |     | fungi Pleurotus |     | djamor. |     |     |     |     |
| ----- | --- | --- | --- | --- | --- | --- | --- | --------------- | --- | ------- | --- | --- | --- | --- |
| dvðtÞ |     |     | 1   |     |     |     |     |                 |     |         |     |     |     |     |
¼vðtÞ(cid:3) vðtÞ3þwðtÞþI; vðtÞ\v ð12Þ Building upon the network implementation, the input
|     | dt  |     | 3   |     |     | thresh |     |            |         |     |           |       |            |            |
| --- | --- | --- | --- | --- | --- | ------ | --- | ---------- | ------- | --- | --------- | ----- | ---------- | ---------- |
|     |     |     |     |     |     |        |     | traversing | through | the | reservoir | layer | influences | the firing |
dwðtÞ dynamics of the FHN neurons, with a key conceptual note
|     | ¼(cid:2)ða(cid:3)vðtÞ(cid:3)bwðtÞÞ; |     |     | vðtÞ\v |        |     | ð13Þ |            |     |       |           |     |               |          |
| --- | ----------------------------------- | --- | --- | ------ | ------ | --- | ---- | ---------- | --- | ----- | --------- | --- | ------------- | -------- |
|     | dt                                  |     |     |        | thresh |     |      |            |     |       |           |     |               |          |
|     |                                     |     |     |        |        |     |      | being that | the | input | connected | to  | the reservoir | nodes is |
v¼v ; vðtÞ(cid:4)v : ð14Þ incorporated as part of the external current I in the FHN
|           | reset |     | thresh       |     |     |     |      |                  |     |     |           |               |     |                 |
| --------- | ----- | --- | ------------ | --- | --- | --- | ---- | ---------------- | --- | --- | --------- | ------------- | --- | --------------- |
|           |       |     |              |     |     |     |      | model, showcased |     | in  | Eq. (12). | Specifically, |     | the total input |
| w¼wðtÞþd; |       |     | vðtÞ(cid:4)v | :   |     |     | ð15Þ |                  |     |     |           |               |     |                 |
thresh current I for each FHN neuron is calculated as the sum of
I ¼g (cid:5)in þg (cid:5)sumðW Þ ð16Þ twocomponents, asdescribedinEq.16:theexternalinput
|        | ext       | i             | local    | fired        |          |        |            |         |          |        |     |     |     |     |
| ------ | --------- | ------------- | -------- | ------------ | -------- | ------ | ---------- | ------- | -------- | ------ | --- | --- | --- | --- |
|        |           |               |          |              |          |        |            | and the | synaptic | input. |     |     |     |     |
| The    | FHN       | equations     | describe | the          | dynamics | of     | the mem-   |         |          |        |     |     |     |     |
| brane  | potential |               | vðtÞ and | the recovery | variable |        | wðtÞ, cap- |         |          |        |     |     |     |     |
| turing |           | the essential |          | features     | of       | neural | activity.  |         |          |        |     |     |     |     |
Equation(12)governstheevolutionofvðtÞ,wheretheterm
vðtÞ(cid:3)1vðtÞ3
|     |     | models | the | rapid activation |     | and | inactivation |     |     |     |     |     |     |     |
| --- | --- | ------ | --- | ---------------- | --- | --- | ------------ | --- | --- | --- | --- | --- | --- | --- |
3
| of     | sodium   | ion | (Naþ) channels, |          | while wðtÞ   | represents | the      |     |     |     |     |     |     |     |
| ------ | -------- | --- | --------------- | -------- | ------------ | ---------- | -------- | --- | --- | --- | --- | --- | --- | --- |
| slower | recovery |     | process         | mediated | by potassium |            | ion (Kþ) |     |     |     |     |     |     |     |
I
| channels.   |              | The external | current         |             | is a key | input          | to the sys- |     |     |     |     |     |     |     |
| ----------- | ------------ | ------------ | --------------- | ----------- | -------- | -------------- | ----------- | --- | --- | --- | --- | --- | --- | --- |
| tem,        | representing |              | the total       | synaptic    |          | input          | or external |     |     |     |     |     |     |     |
| stimulation |              | received     | by              | the neuron. | This     | current        | directly    |     |     |     |     |     |     |     |
| influences  |              | the          | membrane        | potential,  | driving  |                | the neuron  |     |     |     |     |     |     |     |
| toward      | firing       | or           | resting states. | Equation    |          | (13) describes | the         |     |     |     |     |     |     |     |
recoveryvariablewðtÞ,with(cid:2)beingasmallparameterthat
| ensures |       | the recovery | process        |     | occurs | more        | slowly than |     |     |     |     |     |     |     |
| ------- | ----- | ------------ | -------------- | --- | ------ | ----------- | ----------- | --- | --- | --- | --- | --- | --- | --- |
| changes |       | in vðtÞ.     | The parameters |     | a and  | b determine | the         |     |     |     |     |     |     |     |
| resting | state | of           | the neuron     | and | the    | sensitivity | of the      |     |     |     |     |     |     |     |
recovery process to changes in vðtÞ, respectively. Fig.8 SpikingactivityofFitzHugh-Nagumoneuronswith(cid:2)=0.0335,
WhenvðtÞexceedsthethresholdv ,theneuronemits a=0.1034, b=1.1887, and I =0.0645, v =1:3mV and d=0.01
|       |        |         |           |                  | thresh |         |            |                |                |                | ext        |           | thresh       |                 |
| ----- | ------ | ------- | --------- | ---------------- | ------ | ------- | ---------- | -------------- | -------------- | -------------- | ---------- | --------- | ------------ | --------------- |
|       |        |         |           |                  |        |         |            | featuring:     | Period         | (sec) 82.8172, |            | Amplitude | (mV) 1.9170, | Duration        |
| a     | spike, | and the | system    | resets according |        | to Eqs. | (14) and   |                |                |                |            |           |              |                 |
|       |        |         |           |                  |        |         |            | (sec) 82.8172, | Depolarization |                | Rate       | (mV/sec)  | 0.0295,      | Repolarization  |
| (15). | At     | this    | point, we | can deduce       | that   | a       | neuron has |                |                |                |            |           |              |                 |
|       |        |         |           |                  |        |         |            | Rate (mV/sec)  | 0.0294,        | and            | Refractory | Period    | (sec)        | 83.5223, resem- |
‘‘fired’’, then vðtÞ is set to v , and wðtÞ is increased by a bling fungal spiking activity under thermal stimuli in Adamatzky
reset
(2018a)
123

Myceliumasacomputationalmedium:aframework...
|     | (a)0ms |     |     |     | (b)2ms |     |     | (c)4ms |     |     |     | (d)6ms |     |     |     |
| --- | ------ | --- | --- | --- | ------ | --- | --- | ------ | --- | --- | --- | ------ | --- | --- | --- |
Fig.9 SpikingactivityofthereservoirlayerwithFitzHugh-Nagumonodes,forarandomsampleoftheMNISTdataset(number4),observedina
timewindowof6ms.Reservoir’sresponse:a0spikes,b270spikes,c617spikes,andd882spikes
The external input represents the contribution from the firingwiththoseinthereservoirlayerarereinforced,while
input layer, scaled by a factor g ext , and corresponds to thosefiringasynchronouslyarepenalized.Thismechanism
images orother stimuli, denoted asin, where iindexes the is governed by the ReSuMe (Remote Supervised Method)
current input. This external input is directly injected into learning rule (Kasin´ski and Ponulak 2006), which is
the neurons as part of the driving current. The synaptic mathematically expressed in Eq. (17).
input,ontheotherhand,representstheinputreceivedfrom dwðtÞ Z 1
neighboring neurons within the reservoir layer that have ¼ðS ðtÞ(cid:3)S ðtÞÞ½aþ WðsÞS ðt(cid:3)sÞds(cid:9) ð17Þ
|     |     |     |     |     |     |     | dt  |     | d   | o   |     |     | in  |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
0
| fired, calculated |     | as local | gain(cid:5)sumðW |     | fired | Þ. The param- |     |     |     |     |     |     |     |     |     |
| ----------------- | --- | -------- | ---------------- | --- | ----- | ------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
eter g scales this synaptic input, allowing control over The equation describes the rate of change of synaptic
local
dwðtÞ
its influence on the neuron’s dynamics. weights over time, driven by the difference between
dt
| Together, | these | components |     | define | the | total current I |     |         |       |        |         |         |        |       |        |
| --------- | ----- | ---------- | --- | ------ | --- | --------------- | --- | ------- | ----- | ------ | ------- | ------- | ------ | ----- | ------ |
|           |       |            |     |        |     |                 | the | desired | spike | output | S d ðtÞ | and the | actual | spike | output |
that drives the FHN neurons, integrating both external S ðtÞ. The learning process is further modulated by a
o
| stimuli | and internal | network |     | dynamics. |     | The temporal |          |     |          |      |     |     |             |     |      |
| ------- | ------------ | ------- | --- | --------- | --- | ------------ | -------- | --- | -------- | ---- | --- | --- | ----------- | --- | ---- |
|         |              |         |     |           |     |              | constant |     | learning | rate | a   | and | an integral |     | term |
evolution of this current over a 6ms window is illustrated R1WðsÞS ðt(cid:3)sÞds, which accounts for the influence of
|         |          |          |        |     |          |              | 0    |       | in     |            |     |             |          |     |       |
| ------- | -------- | -------- | ------ | --- | -------- | ------------ | ---- | ----- | ------ | ---------- | --- | ----------- | -------- | --- | ----- |
| in Fig. | 9, using | a random | sample |     | from the | dataset. The |      |       |        |            |     |             |          |     |       |
|         |          |          |        |     |          |              | past | input | spikes | S weighted |     | by a kernel | function |     | WðsÞ. |
in
figure demonstratesthe influence of the externalcurrent in By rewarding synchronized spike timing and penalizing
| the initial | phase | of the | response | (around | 2ms), | where it |            |     |        |          |        |      |     |            |     |
| ----------- | ----- | ------ | -------- | ------- | ----- | -------- | ---------- | --- | ------ | -------- | ------ | ---- | --- | ---------- | --- |
|             |       |        |          |         |       |          | otherwise, |     | ReSuMe | learning | aligns | with | the | principles | of  |
stimulates neurons at random positions, generating a total spike-timing-dependent plasticity (STDP) (Ponulak and
| of 270 | spikes. | As the | response | progresses, |     | the activity |           |     |       |         |               |          |     |             |     |
| ------ | ------- | ------ | -------- | ----------- | --- | ------------ | --------- | --- | ----- | ------- | ------------- | -------- | --- | ----------- | --- |
|        |         |        |          |             |     |              | Kasin´ski |     | 2010; | Passias | et al. 2024), | enabling |     | the network |     |
propagatestoneighboringneurons,particularlyinthelater to adapt its synaptic weights in a biologically plausible
phaseofthetimewindow(between4msand6ms).During
|     |     |     |     |     |     |     | manner. |     | This approach |     | not only | enhances | the | network’s |     |
| --- | --- | --- | --- | --- | --- | --- | ------- | --- | ------------- | --- | -------- | -------- | --- | --------- | --- |
this period, the spiking activity increases significantly, abilitytoprocesstemporalinformationbutalsobridgesthe
| reaching | a peak | of 882 | spikes. | This | pattern | highlights the |     |         |            |     |     |            |        |          |     |
| -------- | ------ | ------ | ------- | ---- | ------- | -------------- | --- | ------- | ---------- | --- | --- | ---------- | ------ | -------- | --- |
|          |        |        |         |      |         |                | gap | between | artificial |     | and | biological | neural | systems, |     |
interplay between external stimulation and emergent net- emphasizing the importance of precise spike timing in
| work dynamics, |     | showcasing | how | localized |     | input can lead |          |     |         |     |     |     |     |     |     |
| -------------- | --- | ---------- | --- | --------- | --- | -------------- | -------- | --- | ------- | --- | --- | --- | --- | --- | --- |
|                |     |            |     |           |     |                | learning | and | memory. |     |     |     |     |     |     |
to widespread neural activation over time. The second approach includes a fully connected ReLU
|            |        |     |     |     |     |     | layer, | followed   |      | by a fully | connected |               | softmax | layer      | at the |
| ---------- | ------ | --- | --- | --- | --- | --- | ------ | ---------- | ---- | ---------- | --------- | ------------- | ------- | ---------- | ------ |
| 4.2 Output | layers |     |     |     |     |     |        |            |      |            |           |               |         |            |        |
|            |        |     |     |     |     |     | output | (Fig.      | 7a), | which      | produces  | probabilities |         | indicating |        |
|            |        |     |     |     |     |     | the    | likelihood | of   | an image   | belonging |               | to each | of the     | ten    |
Regarding the output layers, two options have been classes of the dataset. Regarding the training of this net-
| employed: | a purely | biologically-inspired |     |     |     | approach, fol- |     |     |     |     |     |     |     |     |     |
| --------- | -------- | --------------------- | --- | --- | --- | -------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
work,astandardcross-entropylossfunctionwasemployed
lowed by a contemporary one. The fully biologically-in- to evaluate the performance of the classification task. This
spiredapproachincorporateschangesinbothitsnodesand
|     |     |     |     |     |     |     | loss | function | directly | compares |     | the predicted |     | output | prob- |
| --- | --- | --- | --- | --- | --- | --- | ---- | -------- | -------- | -------- | --- | ------------- | --- | ------ | ----- |
training method. Thisnetwork consists ofareservoirlayer abilities to the desired one-hot encoded labels, quantifying
| and an output | layer,  | both           | composed |            | of FHN    | neurons, with  |            |             |           |              |             |            |                |               |     |
| ------------- | ------- | -------------- | -------- | ---------- | --------- | -------------- | ---------- | ----------- | --------- | ------------ | ----------- | ---------- | -------------- | ------------- | --- |
|               |         |                |          |            |           |                | the        | discrepancy |           | between      | the model’s |            | predictions    | and           | the |
| the output    | layer   | containing     | 10       | neurons    | (Fig.     | 7b). Training  |            |             |           |              |             |            |                |               |     |
|               |         |                |          |            |           |                | ground     | truth.      | To        | optimize     | the         | parameters | of             | this network, |     |
| is based      | on the  | precise        | spike    | timing,    | a key     | aspect of bio- |            |             |           |              |             |            |                |               |     |
|               |         |                |          |            |           |                | the        | Adam        | optimizer |              | (Zhang      | 2018)      | has been       | utilized,     | a   |
| logical       | neural  | communication. |          | During     | training, | the spike      |            |             |           |              |             |            |                |               |     |
|               |         |                |          |            |           |                | widely     | adopted     |           | optimization | algorithm   |            | based          | on momen-     |     |
| timings       | of both | the reservoir  |          | and output | layers    | are recor-     |            |             |           |              |             |            |                |               |     |
|               |         |                |          |            |           |                | tum-based  |             | gradient  | descent      | known       | for        | its efficiency |               | and |
| ded. Neurons  | in      | the output     | layer    | that       | exhibit   | synchronous    |            |             |           |              |             |            |                |               |     |
|               |         |                |          |            |           |                | robustness |             | in the    | training     | of deep     | learning   | (DL)           | models.       |     |
123

I.Tomprisetal.
|     |     | (a)Biological |     |     |     |     |     |     | (b)Contemporary |     |     |     |     |     |
| --- | --- | ------------- | --- | --- | --- | --- | --- | --- | --------------- | --- | --- | --- | --- | --- |
Fig.10
Confusionmatricesforallthesamples oftheMNISTdatasetfordifferentnetworkarchitectures. Resultsarecolumn-normalized and
scaledto[0,1]
|         |                      |           |       |           |     |          | This observation |            | is         | also supported |        | by the  | comparative |     |
| ------- | -------------------- | --------- | ----- | --------- | --- | -------- | ---------------- | ---------- | ---------- | -------------- | ------ | ------- | ----------- | --- |
| Table 2 | Results of different | reservoir | nodes | employed, | in  | both the |                  |            |            |                |        |         |             |     |
|         |                      |           |       |           |     |          | analysis         | with other | biological |                | neuron | models, | presented   | in  |
biologicalandcontemporaryarchitectures
|                     |     |     |           |     |             |     | Table 2,namelyLIFandIzhikevich,employedinreservoir |     |     |     |     |     |     |     |
| ------------------- | --- | --- | --------- | --- | ----------- | --- | -------------------------------------------------- | --- | --- | --- | --- | --- | --- | --- |
| Outputarchitecture& |     |     | Reservoir |     | Accuracy(%) |     |                                                    |     |     |     |     |     |     |     |
andoutputlayers.Herein,wherewecanseesimilarresults
| trainingmethod |     |     | node |     |     |     |          |               |     |              |      |     |              |     |
| -------------- | --- | --- | ---- | --- | --- | --- | -------- | ------------- | --- | ------------ | ---- | --- | ------------ | --- |
|                |     |     |      |     |     |     | for each | configuration |     | respectively | with | the | contemporary |     |
Biological LIF 91.84 architecture reaching up to 97.09% accuracy, utilizing the
|              |            |          |      |         |               |     | IZH neuron    | model,   | closely         |           | followed    | by the             | FHN and      | LIF   |
| ------------ | ---------- | -------- | ---- | ------- | ------------- | --- | ------------- | -------- | --------------- | --------- | ----------- | ------------------ | ------------ | ----- |
|              |            |          | FHN  |         | 90.51         |     |               |          |                 |           |             |                    |              |       |
|              |            |          | IZH  |         | 92.32         |     | models.       |          |                 |           |             |                    |              |       |
| Contemporary |            |          | LIF  |         | 96.9          |     |               |          |                 |           |             |                    |              |       |
|              |            |          | FHN  |         | 96.99         |     |               |          |                 |           |             |                    |              |       |
|              |            |          |      |         |               |     | 5 Conclusions |          |                 |           |             |                    |              |       |
|              |            |          | IZH  |         | 97.09         |     |               |          |                 |           |             |                    |              |       |
|              |            |          |      |         |               |     | In this       | work,    | a comprehensive |           | framework   |                    | for modeling |       |
|              |            |          |      |         |               |     | mycelium      | growth   | and             | exploring | its         | computational      |              | capa- |
| 4.3 Results  | comparison |          |      |         |               |     |               |          |                 |           |             |                    |              |       |
|              |            |          |      |         |               |     | bilities      | has been | presented.      |           | It is based | on                 | the Cellular |       |
|              |            |          |      |         |               |     | Automata      | (CA)     | theory          | enhanced  | with        | reaction-diffusion |              |       |
| Moving       | on to the  | results, | each | network | was evaluated |     |               |          |                 |           |             |                    |              |       |
having a 70/30 training/testing sample ratio, randomly (RD) processes in order to vigorously capture the intricate
|              |        |         |     |         |             |     | growth | dynamics | of  | mycelium | under | various | environ- |     |
| ------------ | ------ | ------- | --- | ------- | ----------- | --- | ------ | -------- | --- | -------- | ----- | ------- | -------- | --- |
| distributed, | for 50 | epochs. | The | results | demonstrate | the |        |          |     |          |       |         |          |     |
effectiveness of mycelium-based reservoir computing for mental factors such as temperature, humidity, and light,
|             |           |          |      |             |          |     | useful for | understanding |     | its | behavior | in real-world |     | condi- |
| ----------- | --------- | -------- | ---- | ----------- | -------- | --- | ---------- | ------------- | --- | --- | -------- | ------------- | --- | ------ |
| classifying | the MNIST | dataset, | with | all network | configu- |     |            |               |     |     |          |               |     |        |
rations achieving high accuracies, as showcased by the tions. On top of that, a hyphae information algorithm has
|     |     |     |     |     |     |     | been included |     | in the | framework | to  | extract | key features |     |
| --- | --- | --- | --- | --- | --- | --- | ------------- | --- | ------ | --------- | --- | ------- | ------------ | --- |
confusionmatricesdepictedinFig.10.Thepurebiological
configuration, which combined the FHN model with the useful for appropriate tuning of the model to real struc-
|        |          |                                 |     |     |     |          | tures. Taking |     | into account |     | the result | that | the mycelium |     |
| ------ | -------- | ------------------------------- | --- | --- | --- | -------- | ------------- | --- | ------------ | --- | ---------- | ---- | ------------ | --- |
| ReSuMe | learning | rule for spike-timing-dependent |     |     |     | plastic- |               |     |              |     |            |      |              |     |
ity, achieved an accuracy of 90:51%, whereas the con- model has generated with all the aforementioned features,
ithasbeenproventhatthestructureiscapableofservingas
| temporary | architecture | achieved |     | 96:99%. | The | results |     |     |     |     |     |     |     |     |
| --------- | ------------ | -------- | --- | ------- | --- | ------- | --- | --- | --- | --- | --- | --- | --- | --- |
demonstrate the potential of leveraging mycelium growth areservoirlayerforunconventionalcomputing,leveraging
|               |        |           |      |          |     |       | its electrical | activity. |     | More | specifically, | a   | test case | of  |
| ------------- | ------ | --------- | ---- | -------- | --- | ----- | -------------- | --------- | --- | ---- | ------------- | --- | --------- | --- |
| for cognitive | tasks, | achieving | high | accuracy | in  | MNIST |                |           |     |      |               |     |           |     |
classification. Furthermore, it is apparent that integrating classification of the MNIST dataset has been conducted
|     |     |     |     |     |     |     | with accuracy |     | up to | 97:09%. | To enhance |     | the biological |     |
| --- | --- | --- | --- | --- | --- | --- | ------------- | --- | ----- | ------- | ---------- | --- | -------------- | --- |
deeplearning(DL)withanadditionalReLUlayer,coupled
with a gradient descent-based training algorithm, outper- fidelity of the designed network and closely mimic the
|         |                   |     |           |      |            |     | electrical | activity | observed |     | in real | mycelium, | the | Fitz- |
| ------- | ----------------- | --- | --------- | ---- | ---------- | --- | ---------- | -------- | -------- | --- | ------- | --------- | --- | ----- |
| forms a | purely biological |     | approach. | This | highlights | the |            |          |          |     |         |           |     |       |
significance of combining biologically inspired architec- Hugh-Nagumo (FHN) neuron model was integrated into
|            |           |           |     |          |                |     | the reservoir |     | layer. | In this | direction, | the | gap between |     |
| ---------- | --------- | --------- | --- | -------- | -------------- | --- | ------------- | --- | ------ | ------- | ---------- | --- | ----------- | --- |
| tures with | advanced, | optimized |     | training | methodologies. |     |               |     |        |         |            |     |             |     |
123

Myceliumasacomputationalmedium:aframework...
biological systems and artificial intelligence is being fur- AdamatzkyA(2022)Languageoffungiderivedfromtheirelectrical
ther bridged, opening new avenues for the development of spikingactivity.RSocOpenSci9(4):211926
AdamatzkyA(2023)Fungalmachines:sensingandcomputingwith
bio-inspired computing systems utilizing sustainable
fungi,vol47.Springer
Engineered Living Materials (ELMs)for future computing Adamatzky A, Ayres P, Belotti G, etal (2019) Fungal architecture.
applications. arXivpreprintarXiv:1912.13262
We aim to improve the model by including data from Adamatzky A, Ayres P, Beasley AE et al (2022) Logics in fungal
myceliumnetworks.LogUnivers16(4):655–669
different fungal species and studying how they respond to
AiduangW,JinanukulP,ThamjareeWetal(2024)Acomprehensive
environmental changes. Additionally, the exploration of reviewonstudyinganddevelopingguidelinestostandardizethe
othermachinelearningtasksanddatasetswillhelptofully inspectionofpropertiesandproductionmethodsformycelium-
investigate the capabilities of mycelium-based computing bound composites in bio-based building material applications.
Biomimetics9(9):549
systems. The next step is implementing the reservoir layer
Angelova GV, Brazkova MS, Krastanov AI (2021) Renewable
in novel hardware for real-time, low-power computation myceliumbasedcomposite-sustainableapproachforlignocellu-
and developing a digital twin of real mycelial structures lose waste recovery and alternative to synthetic materials-a
replicated from the proposed model. review.ZNaturforschungC76(11–12):431–442
Arya G, Singh J (2016) The mathematical isopleth model for fungi
growthinbuildingmaterial.JDrugDelivTher6(4):21–26
AyresP,RigobelloA,You-WenJ,etal(2022)Investigatingadesign
Author contributions All authors contributed equally to the study and construction approach for fungal architectures. In: Design
conception and design, the material preparation, data collection and modellingsymposiumBerlin,Springer,pp571–583
analysis,andthemanuscriptwritingandediting.Allauthorsreadand Bassett DS, Bullmore ET (2017) Small-world brain networks
approvedthefinalmanuscript. revisited.Neuroscientist23(5):499–516
Beiler KJ, Durall DM, Simard SW et al (2010) Architecture of the
Funding OpenaccessfundingprovidedbyHEAL-LinkGreece.This wood-wideweb:Rhizopogonspp.genetslinkmultipledouglas-
work has been supported by the framework of the FUNGATERIA fircohorts.NewPhytol185(2):543–553
project, which has received funding from the European Union’s Boswell GP (2008) Modelling mycelial networks in structured
HORIZON-EIC-2021-PATHFINDER CHALLENGES program environments.MycolRes112(9):1015–1025
undergrantagreementNo.101071145. Carver I, Boswell GP (2008) A lattice-free model of translocation-
induced outgrowth in fungal mycelia. IAENG Int J Appl Math
Availabilityofdataandmaterials Thedatasetsgeneratedduringand/ 38(4):173–179
or analyzed during the current study are available from the corre- ChatzinikolaouTP,FyrigosIA,NtinasV,etal(2022)Wavecellular
spondingauthoronreasonablerequest. automata for computing applications. In: 2022 IEEE interna-
tional symposium on circuits and systems (ISCAS),
pp 3463–3467, https://doi.org/10.1109/ISCAS48785.2022.
Declarations 9937915
ChatzinikolaouTP,KaramaniRE,FyrigosIAetal(2024)Handling
Conflictofinterest TheauthorshavenoConflictofinteresttodeclare sudoku puzzles with irregular learning cellular automata. Nat
thatarerelevanttothecontentofthisarticle. Comput 23(1):41–60. https://doi.org/10.1007/s11047-024-
09975-4
Ethicsapproval Notapplicable. Chatzipaschalis IK, Chatzinikolaou TP, Fyrigos IA et al (2023)
Memristor-based cellular automata for natural language pro-
Open Access This article is licensed under a Creative Commons cessing. In: 2023 30th IEEE international conference on
Attribution 4.0 International License, which permits use, sharing, electronics.IEEE,CircuitsandSystems(ICECS),pp1–4
adaptation,distributionandreproductioninanymediumorformat,as ChatzipaschalisIK,TomprisI,RallisK,etal(2024)Mycelium-based
long as you give appropriate credit to the original author(s) and the elm digital twin implemented in fpga. In: International confer-
source,providealinktotheCreativeCommonslicence,andindicate ence on cellular automata for research and industry, Springer,
ifchangesweremade.Theimagesorotherthirdpartymaterialinthis pp265–276
articleareincludedinthearticle’sCreativeCommonslicence,unless CoddEF(2014)Cellularautomata.Academicpress
indicatedotherwiseinacreditlinetothematerial.Ifmaterialisnot Dale M, O’Keefe S, Sebald A et al (2021) Reservoir computing
includedinthearticle’sCreativeCommonslicenceandyourintended quality:connectivityandtopology.NatComput20:205–216
useisnotpermittedbystatutoryregulationorexceedsthepermitted Dehshibi MM, Adamatzky A (2021) Electrical activity of fungi:
use, you will need to obtain permission directly from the copyright spikes detection and complexity analysis. Biosystems
holder.Toviewacopyofthislicence,visithttp://creativecommons. 203:104373
org/licenses/by/4.0/. Elsacker E,ZhangM,Dade-RobertsonM(2023)Fungalengineered
living materials: the viability of pure mycelium materials with
self-healingfunctionalities.AdvFuncMater33(29):2301875
Fricker MD, Heaton LL, Jones NS, etal (2017)The mycelium as a
References
network.Thefungalkingdompp335–367
GallicchioC,MicheliA,PedrelliL(2018)Designofdeepechostate
AdamatzkyA(2018a)Onspikingbehaviourofoysterfungipleurotus networks.NeuralNetw108:33–47
djamor.SciRep8(1):7873 HagbergA,SwartPJ,SchultDA(2008)Exploringnetworkstructure,
Adamatzky A (2018b) Towards fungal computer. Interface Focus dynamics,andfunctionusingnetworkx.Tech.rep.,LosAlamos
8(6):20180029 NationalLaboratory(LANL),LosAlamos,NM(UnitedStates)
123

I.Tomprisetal.
HeZ,LiC,ChenLetal(2020)Dynamicbehaviorsofthefitzhugh- O’Reilly RC, Beck JM (2006) A family of large-stencil discrete
nagumo neuron model with state-dependent impulsive effects. laplacian approximations in three-dimensions. Int J Numer
NeuralNetw121:497–511 MethodsEngpp1–16
VanderHeideT,RoijackersRM,VanNesEHetal(2006)Asimple Passias A, Tsakalos KA, Kansizoglou I et al (2024) A biologically
equation for describing the temperature dependent growth of inspired movement recognition system with spiking neural
free-floatingmacrophytes.AquatBot84(2):171–175 networks for ambient assisted living applications. Biomimetics
HungSW,WangAP(2010)Examiningthesmallworldphenomenon 9(5):296
inthepatentcitationnetwork:acasestudyoftheradiofrequency Pavlidis N, Perifanis V, Chatzinikolaou TP, etal (2023) Intelligent
identification(rfid)network.Scientometrics82(1):121–134 client selection for federated learning using cellular automata.
Jesse H (2023) Understanding the best humidity for mycelium In: 2023 18th international workshop on cellular nanoscale
growth. https://amhuru.com/understanding-the-best-humidity- networksandtheirapplications(CNNA),pp1–4,https://doi.org/
for-mycelium-growth/ 10.1109/CNNA60945.2023.10652769
Karamani RE, Fyrigos IA, Tsakalos KA et al (2021) Memristive PhillipsonPE,SchusterP(2005)Acomparativestudyofthehodgkin-
learning cellular automata for edge detection. Chaos, Solitons huxley and fitzhugh-nagumo models of neuron pulse propaga-
Fractals145:110700 tion.IntJBifurcChaos15(12):3851–3866
KaranaE,BlauwhoffD,HultinkEJ,etal(2018)Whenthematerial Ponulak F,Kasin´skiA(2010)Supervised learninginspikingneural
grows: a case study on designing (with) mycelium-based networks with resume: sequence learning, classification, and
materials.IntJDes12(2) spikeshifting.NeuralComput22(2):467–510
Kasin´ski A, Ponulak F (2006) Comparison of supervised learning RobertsN,AdamatzkyA(2023)Mininglogicalcircuitsinfungi.In:
methodsforspiketimecodinginspikingneuralnetworks.IntJ Fungal machines: sensing and computing with fungi. Springer,
ApplMathComputSci16(1):101–113 p311–321
KawaiY,ParkJ,AsadaM(2019)Asmall-worldtopologyenhances Sugimura K, Shimono K, Uemura T et al (2007) Self-organizing
the echo state property and signal propagation in reservoir mechanismfordevelopmentofspace-fillingneuronaldendrites.
computing.NeuralNetw112:15–23 PLoSComputBiol3(11):e212
LinS, QinH, ZhangXet al(2021)Inhibition ofaspergillus oryzae Tanaka G, Yamane T, He´roux JB et al (2019) Recent advances in
mycelium growth and conidium production by irradiation with physical reservoir computing: a review. Neural Netw
light at different wavelengths and intensities. Microbiol Spectr 115:100–123
9(1):10–1128 Tompris I, Chatzipaschalis IK, Chatzinikolaou TP, etal (2024) A
Maass W (2011) Liquid state machines: motivation, theory, and reaction-diffusion cellular automata model for mycelium-based
applications.Computabilityincontext:computationandlogicin engineered living materials evolution. In: International confer-
therealworldpp275–296 ence on cellular automata for research and industry, Springer,
ManneschiL,LinAC,VasilakiE(2021)Sparce:improvedlearning pp253–264
of reservoir computing systems through sparse representations. Tsakalos KA, Sirakoulis GC, Adamatzky A et al (2021) Protein
IEEETransNeuralNetwLearnSyst34(2):824–838 structured reservoir computing for spike-based pattern recogni-
Molitorisova´ A, Monaco A (2023) Innovating food law with tion.IEEETransParallelDistribSyst33(2):322–331
mycelium:Euregulations.SSRN Tsompanas MA, Chatzinikolaou TP, Sirakoulis GC (2022) Cellular
Molitorisova´A,MonacoA,PurnhagenKP(2021)Ananalysisofthe automata application on chemical computing logic circuits. In:
regulatory framework applicable to products obtained from Chopard B, Bandini S, Dennunzio A et al (eds) Cellular
mushroomandmycelium.AvailableatSSRN3955899 Automata.Springer,Cham,pp3–14
Mora-Boza A, Acosta S, Puertas-Bartolome´ M (2023) Biopolymers Vaxevanellis E, Liolis O, Chatzinikolaou TP, etal (2024) Cellular
forthedevelopmentoflivingmaterialsforbiomedical applica- automata-based system for traffic and parking management in
tions.In:Biopolymers.Elsevier,p263–294 urbancenters.JCellAutomata18
NakajimaK,FischerI(2021)Reservoircomputing.Springer Vidal-DiezdeUlzurrunG,BaetensJ,VandenBulckeJetal(2017)
Nelder JA, Mead R (1965) A simplex method for function Modelling three-dimensional fungal growth in response to
minimization.ComputJ7(4):308–313 environmentalstimuli.JTheorBiol414:35–49
Ntinas V, Karamani RE, Fyrigos IA, etal (2020) Cellular automata WeimarJR (1997)Cellularautomata forreaction-diffusion systems.
coupledwithmemristordevices:afineunconventionalcomput- ParallelComput23(11):1699–1715
ing paradigm. In: 2020 international conference on electronics, ZhangZ(2018)Improvedadamoptimizerfordeepneuralnetworks.
information,andcommunication(ICEIC),IEEE,pp1–4 In:2018IEEE/ACM26thinternationalsymposiumonqualityof
Omuse ER, Niassy S, Wagacha JM et al (2022) Suitable models to service(IWQoS),IEEE,pp1–2
describe the effect of temperature on conidial germination and
mycelial growth of metarhizium anisopliae and beauveria
Publisher’s Note Springer Nature remains neutral with regard to
bassiana.BiocontrolSciTech32(3):281–298
jurisdictionalclaimsinpublishedmapsandinstitutionalaffiliations.
123

Myceliumasacomputationalmedium:aframework...
Authors and Affiliations
Ioannis Tompris1 • Ioannis K. Chatzipaschalis1,2 • Theodoros Panagiotis Chatzinikolaou1 • Georgios Kleitsiotis1 •
Karolos-Alexandros Tsakalos1 • Iosif-Angelos Fyrigos1 • Michail-Antisthenis Tsompanas3 • Andrew Adamatzky3 •
Phil Ayres4 • Georgios Ch. Sirakoulis1
& IoannisTompris AndrewAdamatzky
itompris@ee.duth.gr adamatzky@gmail.com
IoannisK.Chatzipaschalis PhilAyres
ichatzip@ee.duth.gr Phil.Ayres@kglakademi.dk
TheodorosPanagiotisChatzinikolaou GeorgiosCh.Sirakoulis
tchatzin@ee.duth.gr gsirak@ee.duth.gr
GeorgiosKleitsiotis
gkleitsi@ee.duth.gr 1 DepartmentofElectricalandComputerEngineering,
Karolos-AlexandrosTsakalos DemocritusUniversityofThrace,Xanthi,Greece
ktsakalo@ee.duth.gr 2 DepartmentofElectronicEngineering,Universitat
Iosif-AngelosFyrigos Polite´cnicadeCatalunya,Barcelona,Spain
ifyrigos@ee.duth.gr 3 DepartmentofComputerScienceandCreativeTechnologies,
Michail-AntisthenisTsompanas UniversityoftheWestofEngland,Bristol,UK
antisthenis.tsompanas@uwe.ac.uk 4 InstituteofArchitectureandTechnology,RoyalDanish
Academy,Copenhagen,Denmark
123