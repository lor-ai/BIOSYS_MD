ABSTRACT

IN VIVO BIOSYNTHESIS OF N,N-DIMETHYLTRYPTAMINE, 5-MeO-N,N-
DIMETHYLTRYPTAMINE, AND BUFOTENINE IN E. COLI

by Lucas Michael Friedberg

N,N-dimethyltryptamine (DMT), 5-methoxy-N,N-dimethyltryptamine (5-MeO-DMT) and
5-hydroxy-N,N-dimethyltryptamine (bufotenine) are psychedelic tryptamines found
naturally in both plants and animals and demonstrate clinical potential to help treat
mental disorders such as anxiety and depression. Advances in both metabolic and genetic
engineering make it possible to engineer microbes as microbial cell factories to produce
DMT and its aforementioned derivatives to meet demand for ongoing clinical study.
Here, we present the development of a biosynthetic production pathway for DMT, 5-
MeO-DMT, and bufotenine in the model microbe Escherichia coli. Through the
application of genetic optimization techniques and process optimization via benchtop
fermenters, the in vivo production of DMT in E. coli was observed. DMT production
from tryptophan reached maximum titers of 80.1 mg/L, a 48-fold increase from first
proof-of-principle experiments. Additionally, we show the first reported case of de novo
production of DMT in E. coli at a maximum titer of 14 mg/L. Finally, we provide the first
reported case of microbial 5-MeO-DMT and bufotenine production in vivo. This work
provides a starting point for further genetic and fermentation optimization studies with
the goal to increase methylated tryptamine production metrics to industrially competitive
levels.

IN VIVO BIOSYNTHESIS OF N,N-DIMETHYLTRYPTAMINE, 5-MeO-N,N-
DIMETHYLTRYPTAMINE, AND BUFOTENINE IN E. COLI

A Thesis

Submitted to the

Faculty of Miami University

in partial fulfillment of

the requirements for the degree of

Master of Science

by

Lucas Michael Friedberg

Miami University

Oxford, Ohio

2022

Advisor:  J. Andrew Jones

Reader:  Jason Boock

Reader:  Andrea Kravats

©2022  Lucas Michael Friedberg

This Thesis titled

IN VIVO BIOSYNTHESIS OF N,N-DIMETHYLTRYPTAMINE, 5-MeO-N,N-
DIMETHYLTRYPTAMINE, AND BUFOTENINE IN E. COLI

by

Lucas Michael Friedberg

has been approved for publication by

The College of Engineering and Computing

and

Department of Chemical, Paper and Biomedical Engineering

____________________________________________________
J. Andrew Jones

 ______________________________________________________
Jason Boock

_______________________________________________________
Andrea Kravats

Table of Contents

1.0 Introduction: ............................................................................................................................ 1

2.0 Completed Work: ................................................................................................................... 5

2.1 Materials and Methods: ................................................................................................... 5

2.1.1 Bacterial Strains, Vectors and Media: ................................................................... 5

2.1.2 Plasmid Construction: .............................................................................................. 6

2.1.3 Standard Screening Conditions: ............................................................................. 6

2.1.4 Initial pH Screening Method: .................................................................................. 7

2.1.5 pH-Controlled, Medium Throughput Screening Method: .................................. 7

2.1.6 Promoter Library Validation: .................................................................................. 8

2.1.7 Overlay Screening Method and Sample Collection: ............................................ 8

2.1.8 pH Stat Bioreactor Screening: ................................................................................ 9

2.1.9 Standard Curve Development for DMT, 5-MeO-DMT, Bufotenine: .............. 10

2.1.10 Analytical Methods: ............................................................................................. 11

2.2 Results: ............................................................................................................................. 12

2.2.1 Temperature and pH Dependent Production of N,N-dimethyltryptamine: ..... 12

2.2.2 Promoter Library Screening Under Monitored pH Helps Identify Most
Suitable Promoter: ............................................................................................................ 14

2.2.3 Strict pH Monitoring and Control Increases NMT and DMT Production: ..... 15

2.2.4 Extended Metabolic Pathways and Further Promoter Library Screening Lead
to de novo Production of Methylated Tryptamine: ...................................................... 16

2.2.5 Bioreactor Fermentation with Glucose Feed Increases DMT Titers ............... 19

2.2.6 Implementation of Hydrophobic Overlays Fail to Resolve INMT Inhibition:20

2.2.7 Production of 5-MeO-DMT and Bufotenine ...................................................... 20

2.3 Discussion ........................................................................................................................ 22

3.0 Conclusions and Future Work: ........................................................................................... 25

References .................................................................................................................................... 28

Supplementary Materials ........................................................................................................... 33

iii

List of Tables

Supplementary Table 1. Strain and plasmid list……………………………………....35
Supplementary Table 2. Primer list…………………………………………………...36

iv

 List of Figures

Figure 1. Chemical structures and names………………………………………………….3
Figure 2. Metabolic pathway for the production of N-methylated tryptamines……………5
Figure 3. Visual representation of different pH control schemes………………………...13
Figure  4.  NMT  and  DMT  concentrations  from  BL21  StarTM  (DE3)  pETM6-SDM2x-
INMT and pETM6-SDM2x-PaNMT plasmid expressing bacteria from 48 well plates…..13
Figure  5.  NMT  and  DMT  concentration  based  on  promoter  strength  of  key
methyltransferase………………………………………………………………………....14
Figure 6. NMT, DMT and TMT concentrations from pH stat bioreactor runs from BL21
StarTM (DE3) pETM6-SDM2x-INMT……………………………………………………15
Figure 7. NMT, DMT and TMT concentration based on gene configuration and promoter
strength of INMT and PsiD……………………………………………………………….17
Figure 8. NMT and DMT production of top performing strains selected from each distinct
library construct ………………………………………………………………………….18
Figure 9. de novo production of NMT, DMT, and TMT with select strains…………….19
Figure  10.  Fed-batch  bioreactor  scale-up  with  the  use  of  a  glucose  feed  with  select
strains………….………………………………………………………………………….20
Figure 11. 5-MeO-NMT and 5-MeO-DMT production.…………………………………21
Figure 12. 5-HO-NMT, 5-HO-DMT, and 5-HO-TMT production……………………...21
SF 1. A280 chromatograph of a DMT standard and a bioreactor sample………..………..33
SF 2. Extracted Ion Channel Mass-spectroscopy peaks…………………………………..34

v

Dedication

To family and friends who have supported me throughout my studies, in the both the
good and the bad. I couldn’t have done it without you.

vi

Acknowledgements

First and foremost, I would like to acknowledge Dr. Andrew Jones for his continued
support and mentorship throughout my thesis.  He has been an incredible source of
knowledge, encouragement, patience and wisdom that has made this thesis possible. He
pushed me in the best way possible to realize the full potential of this thesis.  I would also
like to acknowledge Jones Lab members, Bill Gibbons, Abhishek Sen, and Quynh
Nguyen for their necessary roles within the lab, as well as Jones Lab graduate students
Phill O’Dell and Nick Kaplan for their project advice and brainstorming. I would also
like to thank undergraduate students in the Jones Lab for their support in keeping the lab
in working order.  Finally, I would like to thank my thesis committee members Dr.
Andrew Jones, Dr. Jason Boock, and Dr. Andrea Kravats for their feedback and support.
Finally, I would like to thank PsyBio for believing in the Jones Lab vision and providing
the funding that helped make this thesis possible.

vii

1.0 Introduction:

N,N-dimethyltryptamine (DMT) is a tryptophan-derived alkaloid that is naturally present

in many plants and animals. As a structural analog of serotonin, DMT acts as an agonist to 2A

serotonin receptors in the brain inducing mind altering changes. DMT has a history of being

consumed by several indigenous groups from the Northwestern Amazon for therapeutic purposes

(Schultes et al., 1992). The most recent estimate of the first known use of DMT by humans dates

to pre-Colombian times, or about 1,000 years ago, based on carbon dating of a leather bag

containing a “ritual bundle,” which contained paraphernalia for consuming psychotropic plants

(Miller et al., 2019). Indigenous groups orally ingested a DMT containing mixture called

ayahuasca, which is made from the leaves of the shrub Psychotria viridis, providing the source

of DMT, and the vine Banisteriopsis caapi, providing the monoamine oxidase inhibitors

(MAOIs) required for DMT to be orally activity (Schultes et al., 1992). In the west, DMT was

first seen in 1931 when Canadian scientist Richard Manske developed a chemical synthesis route

starting from a trimethylated indole derivative (Manske, 1931). It wasn’t until 1946 that Oswaldo

Gonclaves de Lima discovered its natural occurrence in plants (Lima, 1946). The hallucinogenic

properties of DMT were not discovered until 1956 when the Hungarian chemist and psychiatrist

Stephen Szara extracted DMT from Mimosa hostilis and self-dosed intramuscularly (Szára,

1956). The discoveries made by the aforementioned scientists led to a link between modern

science and the historical use of DMT in religious and spiritual practices rooted in the mind-

altering effects of the chemical.

Similarly, DMT derivatives 5-MeO-DMT and its active metabolite 5-HO-DMT

(bufotenine), have been traced back thousands of years for its use in ceremonies in Venezuela,

Columbia, and Brazil in the form of crushed seeds known as ‘Yopo’ (Artal and Carbera 2007).

Additionally, 5-MeO-DMT also makes up the active ingredient of the venom and parotid gland

secretions of Colorado River Toad, Incilius alvarius (Shen et al. 2011). Also, like DMT, 5-MeO-

DMT exhibits hallucinogenic properties upon parenteral administration and conversion to its

active metabolite bufotenine.

Clinical depression is a highly prevalent and debilitating disorder estimated to effect

4.4% of the global population (“WHO | Depression and Other Common Mental Disorders,”

2017). Presently available treatments for depression have proven to have low response rates,

1

slow onset of efficacy, as well as adverse effects such as increased suicidality, especially in

adolescents (Pacher & Kecskemeti, 2005). Altogether, current treatments fail to provide

adequate treatment for roughly 60% of patients struggling with this disease (de Osório et al.,

2015; Fava, 2003; Knoth et al., 2010; Penn & Tracy, 2012). Recently, psychoactives, such as

DMT, 5-MeO-DMT, MDMA, ketamine, and psilocybin, have gained interest as potential

alternatives to traditional Selective Serotonin Reuptake Inhibitor (SSRI)-based antidepressants

such as fluoxetine (Prozac®). Longitudinal studies of effects of ayahuasca consumption on the

psyche of ritual users suggest that DMT is not detrimental to psychological well-being and is

conversely associated with reduced incidence of mental illness (Davis et al., 2019; Anderson et

al., 2012; Barbosa et al., 2016; Bouso et al., 2012; Guimarães dos Santos, 2013). In an open-label

clinical trial held at Universidade de Sao Paulo, Ribeirao Preto, Brazil, 6 patients were

administered ayahuasca and showed significant reductions in their depressive scores of up to

82% based on the Hamilton Rating Scale for Depression (HAM-D) and the Montgomery-Asberg

Depression Rating Scale (MADRS) (de Osório et al., 2015). With growing evidence to support

DMT’s use as an effective anti-depressant, there is a growing need to develop sustainable,

reproducible, and scalable synthesis methods to provide a safe source for pharmaceutical-grade

product. Research on psilocybin, another psychedelic tryptamine, has gained attention for its

antidepressant properties as well. Recently, psilocybin has successfully been produced in vivo in

the mold Aspergillus nidulans, yeast Saccharomyces cerevisiae, and bacteria Escherichia coli

(Hoefgen et al., 2018; Adams et al., 2019; Milne et al., 2020). The in vivo production of

psilocybin has shown potential as a competitor to traditional chemical synthesis on the basis of

scalability, cost, and speed of production (Fricke et al., 2019). Leveraging these advantages, we

investigate the in vivo production of DMT, as well as explore novel metabolic pathways for the

production of other psychoactive indoleamine alkaloids.

In 1961, the discovery of the methylation of tryptamine and structurally related

compounds by a cytosolic S-adenosyl-L-methionine (SAM)-dependent methyltransferase was

described in the rabbit lung (Axelrod, 1961). Further studies observed the production of N-

methyltryptamine (NMT) and DMT in human and rat brain incubated with tryptamine, revealing

the presence of indolethylamine-N-methyltransferase (INMT) activity (Mandell & Morgan,

1971; Saavedra et al., 1973). In 1999, human INMT (hINMT) was successfully cloned, further

2

elucidating the broad presence of methylated tryptamines in human physiology and metabolism

(Thompson et al., 1999).

Recently, phenylalkylamine N-methyltransferase (PaNMT) from Ephedra sinica, has

demonstrated a broad range of substrate promiscuity in vitro ranging from its native substrate,

norephedrine, to indoleamines (Morris et al., 2018) . Figure 1 displays the core tryptamine

structure common to the neurotransmitter serotonin and to some psychedelics such as DMT and

psilocybin.

Figure 1. Chemical structures and names of common, bioactive tryptamines.

Here we demonstrate in vivo activity of Homo sapiens INMT and Ephedra sinica PaNMT in

an E. coli host, resulting in the production of NMT, DMT, and N,N,N-trimethyltryptamine

(TMT) from tryptamine, leveraging in vivo production of the required activated methyl donor,

SAM (Figure 3). Identification and quantification of target metabolites was performed by high

performance liquid chromatography (HPLC) and liquid chromatography mass spectrometry

(LCMS) analysis. Libraries of transcriptionally-varied genetic mutants of both PaNMT and

3

INMT were constructed using the ePathOptimize approach and screened using a medium

throughput, pH-controlled, well plate platform coupled with HPLC/LCMS analysis (Adams et

al., 2019; Jones et al., 2015). Through this process, we identified our top production strain

containing the T7 consensus promoter controlling methyltransferase expression (T7-INMT),

which demonstrated the highest production titers of NMT, DMT, and TMT reported to date from

a bacterial host platform. Further analysis of fermentation conditions identified pH and

temperature as key process parameters, which was consistent with previous results reported in

the literature for in vitro approaches (Morris et al., 2018).

Bioreactors were implemented to explore the viability of scale-up production of DMT

through this newly created bacterial host platform. The previously isolated strain, T7-INMT, was

used as the model for bioreactor fermentation experiments. Once optimal conditions were

established, we began to run fed batch bioreactor fermentations which proved effective in

increasing the production of DMT and provides a path forward for further study and

optimization.

In addition to demonstrating in vivo activity for INMT and PaNMT, we also demonstrate the

incorporation of INMT into a functional metabolic pathway to realize methylated tryptamine

biosynthesis from a variety of substrates including: tryptophan, and indole derivatives. The

previously reported psilocybin biosynthesis pathway in Psilocybe cubensis contains PsiD, a

tryptophan decarboxylase with activity towards both tryptophan and 4-hydroxytryptophan

(Fricke et al., 2017). Figure 2 illustrates the novel pathway we have designed for methylated

tryptamine biosynthesis through the simultaneous enzymatic expression of both PsiD and INMT

coupled with the native E. coli metabolism.

Furthermore, we have demonstrated that enzymes INMT and PsiD exhibit substrate

promiscuity. Using the novel pathway outlined in Figure 2, and described above, indole

derivatives, such as 5-methoxyindole (5-MeO-indole), and 5-hydroxyindole (5-HO-indole) are

converted to psychoactive chemical derivatives of DMT, specifically 5-methoxy-

dimethyltryptamine (5-MeO-DMT) and Bufotenine (5-HO-DMT) respectively.

Through the implementation of genetic and metabolic engineering techniques, and

benchtop fermentation, we have demonstrated the ability to produce DMT and its

aforementioned derivatives in vivo in the prokaryotic host platform E. coli. Furthermore, we have

4

shown that genetic optimization led to an increase in DMT titers from initial proof of concept

experiments and the possibility for a de novo production of DMT in E. coli.

Figure 2. Metabolic pathway for the production of N-methylated tryptamines from various

starting substrates. TrpB = tryptophan synthase, subunit B; psiD = psilocybin decarboxylase;

INMT = indolethylamine-N-methyltransferase (INMT); PaNMT = phenylalkylamine-N-

methyltransferase (PaNMT); SAM = S-Adenosyl methionine (cosubstrate); SAH = S-Adenosyl

homocysteine; Met = methionine; NMT = N-methyltryptamine; DMT = N,N-

dimethyltryptamine; TMT = N,N,N-trimethyltryptamine

2.0 Completed Work:

2.1 Materials and Methods:

2.1.1 Bacterial Strains, Vectors and Media:

5

E. coli DH5α was used to propagate all plasmids, while BL21 StarTM (DE3) was used as

the host for all chemical production experiments. Plasmid transformations were completed using

standard chemical competency protocols as specified. Unless otherwise noted, Andrew’s Magic

Media (AMM) (He et al., 2015), (without MOPS and tricine), was supplemented with 1 g/L

methionine and 150 mg/L of tryptamine or tryptophan and 100 mg/L of alternative precursor

molecules such as 5-hydroxyindole, or 5-methoxyindole depending on the desired end product

(Figure 2). Non-supplemented AMM was used for preculture growth while supplemented AMM

was used for production media (He et al., 2015). Luria Broth (LB) was used for plasmid

propagation during cloning. The antibiotic ampicillin (80 ug/mL) was added to the culture media

where appropriate for plasmid selection. The exogenous pathway gene encoding PsiD was taken

from a plasmid construct reported by the Jones Lab for psilocybin biosynthesis (Adams et al.,

2019).

2.1.2 Plasmid Construction:

Human INMT and PaNMT gene sequences were ordered as linear, double stranded DNA

fragments from Genewiz Inc. INMT and PaNMT were codon optimized for expression in E. coli,

PCR amplified, restriction digested with NdeI and XhoI, and ligated into a modified ePathBrick

expression vector also digested with NdeI and XhoI. The resulting plasmids containing the genes

responsible for INMT and PaNMT expression, #4 and #5 respectively, were sequence verified

and used to create all pathway variants and transcriptionally varied libraries described below. All

multigene expression plasmids were constructed using a modified version of the previously

published ePathBrick methods as described above, while all transcriptional libraries were

constructed using standard ePathOptimize methods and mutant T7 promoters G6, H9, H10, and

C4 to create an operon and pseudooperon configuration for plasmids #6 and #7 and an additional

monocistronic configuration for plasmid #5 (Jones et al., 2015; Xu et al., 2012). Additional

information on plasmids constructed for this study can be found in Supplemental Table 1 (ST1).

2.1.3 Standard Screening Conditions:

Standard screening was performed in 2 mL working volume cultures in 48-well plates at

either 30 ˚C, 37 ˚C or 42 ˚C, depending on gene construct, and non-supplemented AMM was

used for overnight cultures and AMM supplemented with the relevant precursor molecules

6

mentioned in 2.1.2 was used for production cultures. Overnight cultures were grown either from

agar plates or a glycerol freezer stock in AMM (pH = 7.0) with appropriate antibiotics for 12-16

h in a shaking (250 rpm) incubator at 30 ˚C, 37 ˚C or 42 ˚C. Production cultures were grown in

media identical to media used for overnight cultures with the addition of product specific

substrate and were inoculated at 2% of working volume (40 µL) with the overnight cultures

grown under similar process conditions. Cultures were grown with a minimum number of

replicates of N = 2, unless otherwise noted. Induction with 1 mM isopropyl β-D-1-

thiogalactopyranoside (IPTG) occurred 4h after inoculation unless otherwise noted. Cultures

were then sampled for HPLC and LCMS analysis 24 h post inoculation.

2.1.4 Initial pH Screening Method:

The standard screening method outlined above was used with the addition of varying the

initial pH condition. The overnight cultures were grown using the conditions outlined above to

result in a standardized inoculum. Before inoculation of the production cultures, the AMM

media, supplemented with 150 mg/L tryptamine, 1 g/L methionine, and ampicillin was pH

adjusted to either 8.0 using 1 M KOH, or to 6.0 using 1 M HCl. Fermentation pH was not

monitored throughout the fermentation and conditions correspond to those outlined in the

standard screening method above.

2.1.5 pH-Controlled, Medium Throughput Screening Method:

Using the standard screening conditions described above, we developed a modified

protocol to test chemical production under controlled pH conditions in a medium throughput

well plate screening approach. Replicate 48-well plates were set-up in a way to allow for many

replicate cultures which could be sacrificed for pH monitoring and empirical pH adjustment

purposes. Beginning at time of induction (4 hours post inoculation), 4 mL (2 mL from 2

sacrificial wells) of the pH control plate were transferred into a falcon tube and the pH was

measured using Fisher Scientific AccumetTM AE150 pH benchtop meter. pH of the sacrificial

culture is then adjusted by the addition of 10M KOH in 2 µL increments until the desired

setpoint was achieved. pH at the time of sampling averaged about 6.7 and required, on average,

15 uL of 10 M KOH.  The total volume of 10 M KOH required was recorded and used to inform

the adjustment of the pH, using a 2.5 M KOH solution, for the remaining sacrificial controls and

7

experimental cultures in the 48-well plate format using a multichannel pipette. The pH

measuring and adjustment procedure described above was performed every two hours over the

course of 8 hours beginning at induction unless otherwise noted.

2.1.6 Promoter Library Validation:

Upon constructing and testing promoter library strains, stock cultures were made by

combining cultures grown overnight with 30% sterile glycerol to produce a 15% glycerol stock

culture in 96 well plates. Once promoter library constructs were screened using the previously

mentioned screening methods, a few top performing strains, based on DMT titer, from each

library were selected for further screening. Selected strains (BL21 StarTM (DE3)) were streaked

from previously described freezer stocks onto an agar plate containing ampicillin. The following

day, streaked plates were used to inoculate a 48 well plate for screening outlined in 2.1.5.

Following well inoculation, an agar plate containing ampicillin was streaked to preserve well

plate cultures. Once strain performance was validated, select colonies from the 48 well agar plate

streak were grown overnight in AMM. Plasmid DNA of overnight cultures was isolated and

purified using Omega Bio-tek E.Z.N.A® Plasmid DNA mini Kit I followed by digestion and gel

electrophoresis to confirm expected plasmid construct. Purified plasmid DNA was then

transformed into DH5α and plated on agar plates containing ampicillin. Colonies of

transformants were used to grow overnight cultures in LB. DH5α overnight cultures were subject

to plasmid DNA purification, followed by digestion and gel electrophoresis to confirm expected

plasmid construct. Plasmid DNA was transformed back into (BL21 StarTM (DE3)) and plated on

agar plates containing ampicillin. Transformants were grown overnight in AMM media.

Overnight cultures were used to create freezer stocks, which served as the final production strain

moving forward with additional screening.

2.1.7 Overlay Screening Method and Sample Collection:

A modified version of the pH controlled; medium throughput screening method outlined

above was used to test efficacy of hydrocarbon overlays on DMT production. 250mL

Erlenmeyer flasks were used to test the DMT production of 50mL cultures with the addition of

10mL of a chemical overlay (Jang et al. 2011). Two chemical overlays, dodecane and diisononyl

phthalate (DINP), were tested individually. As mentioned above, additional cultures were grown

8

to be used for sacrificial pH measurements to inform pH adjustment of experimental cultures. To

reduce error in pH adjusting cultures, the entire 50 mL sacrificial culture was pH adjusted with

10 M KOH. The pH probe was rinsed with 70% EtOH between measurements to reduce chance

of contamination. Cultures were sampled 24 h post inoculation. Final OD measurements were

taken at time of sample collection and compared to determine potential effects of the overlay on

cell viability. Cultures were collected in 50mL Falcon tubes and subject to centrifugation at 4696

rcf for 10 minutes to separate media and overlay from cells. Following initial separation, media

and overlay solutions were separated into multiple 1mL tubes and centrifuged at 21000 rcf for 10

minutes to separate media and overlay. Media and overlay where analyzed for tryptamine

content as described in Analytical Methods.

2.1.8 pH Stat Bioreactor Screening:

Once optimal conditions were determined using our standard and pH-controlled

screening conditions at both 37 ˚C and 42 ˚C, we selected the Eppendorf BioFlo120 bioreactor

with a 1.5 L working volume to scale up DMT production. The cylindrical vessel was mixed by

a direct drive shaft containing two Rushton-type impellers positioned equidistant under the liquid

surface. The overnight culture of BL21 StarTM (DE3) containing pETM6-SDM2x-INMT was

grown for 12 h at 37 ˚C in 50 mL of AMM supplemented with methionine (1 g/L), tryptamine

(150 mg/L), and ampicillin (80 ug/mL) in a 250mL non-baffled Erlenmeyer flask. The bioreactor

contained the same media composition which was used for the overnight culture and was

inoculated at a 2% v/v (30 mL into 1.5 L). Temperature was held at a constant 42 ˚C with a heat

jacket and recirculating cooling water, pH was automatically and continuously controlled at

either 6.5, 7.0, 7.5, or 8.0, with the addition of 10 M KOH. Agitation and air flow rate were

maintained at 500 rpm and 2 v/v (3 SLPM) for the entirety of the 24-hour fermentation. Samples

were collected periodically for measurement of OD600 and metabolite analysis. The fermentation

cultures were induced with 1 mM IPTG 4 hours post inoculation. Apart from periodic sample

collection, the reactor screening process required minimal observation with integrated control

systems sensing and maintaining process parameters as described above. The concentration of

DMT and all metabolic intermediates and side products were analyzed via HPLC and LC-MS.

Final bioreactor fermentations were carried out with the addition of a glucose feed. Glucose

analysis was performed using an Aminex HPX-87H column maintained at 30 °C followed by a

9

refractive index detector (RID) held at 35 °C. The mobile phase was 5 mM H2SO4 in water at a

flow rate of 0.6 mL/min. Glucose was quantified using a standard curve with a retention time of

8.8 min (Adams et al., 2019). A 50% w/v glucose stock was used to feed fermenters.

2.1.9 Standard Curve Development for DMT, 5-MeO-DMT, Bufotenine:

Quantification using absorbance in the ultraviolet region (e.g., 280 nm) was not utilized

in this study due to difficulty achieving separation of key metabolites using liquid

chromatography. Supplemental Figure 1 provides a visual representation of NMT and DMT

detection as compared with a DMT standard; however, TMT was unable to be detected as a

distinct single peak due to overlapping retention times with DMT. This led to the use of the mass

spectroscopy extracted ion chromatographs (EIC) for metabolic quantification.

DMT analytical standard was purchased from Cerilliant Corporation. The authentic

standard was used to create a standard curve through serial dilutions in spent and filtered cell

broth and these samples were analyzed using the methods described below. The standard curve

was created to determine both the low and high limits of detection and quantification of about

0.05 mg/L NMT and 0.06 mg/L DMT to 3.09 mg/L NMT and 3.34 mg/L DMT respectively for

the MS detector. Several DMT standard curves were run to validate quantification by LCMS

using extracted ion chromatograms (Supplemental Figure 2): 1) An undiluted bioreactor broth

sample containing DMT was initially spiked with 40 mg/L of pure DMT to determine if DMT

saturation affected the accuracy of the EIC peak area of the co-eluting metabolite, TMT, 2) An

undiluted bioreactor broth sample containing DMT was serially diluted in a broth that was free

of DMT and each diluted sample was spiked with 40 mg/L of pure DMT to ensure that saturation

of DMT would not affect the peak areas of NMT or TMT extracted ion channels of the diluted

samples, 3) a traditional standard curve was made by diluting pure DMT in negative control cell

broth to ensure that “matrix” effects did not affect peak quantification. Each standard curve

displayed a range of linearity (0.05 mg/L NMT and 0.06 mg/L DMT to 3.09 mg/L NMT and

3.34 mg/L DMT) before demonstrating detector saturation. We utilized the slope from the linear

portion of the DMT standard curves to quantify NMT, DMT, and TMT products on a molar basis

due to no commercially available standards for NMT and TMT.

5-MeO-DMT and Bufotenine standard curves were created via serial dilutions of 1.0

mg/mL pure reagent stock solutions purchased from Cerilliant and Lipomed respectively. The

10

slope of the linear portion of the Mass Spectroscopy Extracted Ion Chromatograph (MS-EIC)

peak area was used to quantify respective product concentrations.

2.1.10 Analytical Methods:

Samples were prepared for HPLC and LC-MS analysis by centrifugation at 21,000 rcf for

5 minutes; 2 µL of the resulting supernatant was then injected for analysis. Analysis was

performed on a Thermo Scientific Ultimate 3000 High-Performance Liquid Chromatography

(HPLC) system equipped with Diode Array Detector (DAD) and Thermo Scientific ISQTM EC

single quadrupole mass spectrometer (MS).

Mass spectroscopy extracted ion channels (EIC) were used to quantify the aromatic

compounds of interest in this study. Metabolite separation was performed using an Agilent

Zorbax Eclipse XDB-C18 analytical column (3.0 mm x 250 mm, 5 µm) with mobile phases of

water (A) and acetonitrile (B) both containing 0.1% formic acid at a rate of 1 mL/min: 0 min, 5%

B; 0.43 min, 5% B; 5.15 min, 19% B; 6.44 min, 100% B; 7.73 min, 100% B; 7.73 min, 5% B;

9.87 min, 5% B (Adams et al., 2022). The ISQTM EC mass spectrometer, equipped with a heated

electrospray ionization (HESI) source, was operated in positive mode. The mass spectrometer

was supplied ≥ 99% purity nitrogen using a Peak Scientific Genius XE 35 laboratory nitrogen

generator. The source and detector conditions were as follows: sheath gas pressure of 80.0 psig,

auxiliary gas pressure of 9.7 psig, sweep gas pressure of 0.5 psig, foreline vacuum pump

pressure of 1.55 Torr, vaporizer temperature of 500 °C, ion transfer tube temperature of 300 °C,

source voltage of 3049 V, source current of 15.90 µA.

LC-MS data was collected, where the full MS scan was used to provide an extracted ion

chromatogram (EIC) of our compounds of interest for the DMT production platform (M+1):

tryptamine (m/z 161), NMT (m/z 175), DMT (m/z 189), and TMT (m/z 203). This method

resulted in the following observed retention times as verified by analytical standards (when

commercially available): tryptamine (5.63 min), NMT (5.79 min), DMT (6.01 min) and TMT

(6.05 min).

EICs for compounds of interest for the 5-MeO-DMT production platform (M+1): 5-

MeO-NMT (m/z 205), 5-MeO-DMT (m/z 219). This method resulted in the following observed

retention times as verified by analytical standards (when commercially available): 5-MeO-NMT

(6.34 min) and 5-MeO-DMT (6.59 min).

11

EICs for compounds of interest for the Bufotenine production platform (M+1): 5-HO-

NMT (m/z 205), Bufotenine (m/z 219), 5-HO-TMT (m/z 233). This method resulted in the

following observed retention times as verified by analytical standards (when commercially

available): 5-HO-NMT (3.27 min), Bufotenine (3.51 min), and 5-HO-TMT (3.49 min).

Samples quantified by LC-MS were appropriately diluted such that their detector

response falls in the linear response regime, as reported above. All data was managed and

processed using Thermo Scientific Chromeleon 7.3 Chromatography Data System.

2.2 Results:

2.2.1 Temperature and pH Dependent Production of N,N-dimethyltryptamine:

Both methyltransferases investigated in this study, INMT and PaNMT, were expressed in

E. coli using the strong consensus T7-lac promoter system. The production of NMT and DMT

by these recombinant E. coli hosts were monitored as a function of both temperature and pH. In

this assessment, the pathway intermediate, tryptamine, was provided in the culture media to

allow for the direct assessment of effective methyltransferase activity. Induction with IPTG led

to the observation of the presence of NMT and DMT in both INMT and PaNMT expressing E.

coli under well-plate conditions. DMT was never observed in the absence of NMT. Figure 3a

provides a qualitative visual for the time variant pH levels throughout this assay. The highest

titers observed for both NMT and DMT in 48 well plate experiments (7.58 +/- 0.51 mg/L and

0.22 +/- 0.01 mg/L, respectively) were observed in INMT expressing E. coli at 42 ˚C with an

initial media pH of 8.0. NMT and DMT concentrations were significantly higher in cultures

incubated with a starting pH of 8 compared to other pHs tested (p < 0.05) (Figure 4). In PaNMT

expressing E. coli, NMT titer reached a high of 1.16 +/- 0.003 mg/L when grown at 30 ˚C and

having the media pH initially adjusted to 8. DMT production was not observed in PaNMT

expressing E. coli under these conditions. The 150 mg/L tryptamine supplementation was not

exhausted during these studies. NMT and DMT titers from the expression of INMT were highest

at temperatures of 42 ˚C and whereas PaNMT had the highest NMT titers at 30 ˚C.

12

Figure 3. Visual representation of the different pH control schemes used. A) Starting pH was

adjusted at the start of the experiment. b) pH was adjusted to 7.5 at the beginning of the

experiment and readjusted to 7.5 every 2 h. c) pH was maintained at 7.5 for the entirety of the

experiment. The green portion highlights the observed optimal pH range for methylated

tryptamine production.

Figure 4. NMT and DMT concentrations from BL21 StarTM (DE3) pETM6-SDM2x-INMT and

pETM6-SDM2x-PaNMT plasmid expressing bacteria from 48 well plates at t = 24 h post

inoculation under standard screening conditions a) NMT produced by INMT strain as a function

of temperature and pH b) DMT produced by INMT strain as a function of temperature and pH.

c) NMT produced by PaNMT strain as a function of temperature and pH. *No DMT observed in

PaNMT screening.

13

2.2.2 Promoter Library Screening Under Monitored pH Helps Identify Most Suitable
Promoter:

Following the trends observed from the temperature and pH dependent production of

NMT and DMT, we screened a panel of transcriptionally varied mutants to select genetically

superior strains for the production of the methylated tryptamines. A promoter library of both

INMT and PaNMT plasmids were made following the ePathOptimize method (Jones et al.,

2015). IPTG inducible promoters from the weakest to strongest: G6, H9, H10, C4, and T7 and

constitutive promoters XylA and GAP were all independently tested. Methylated tryptamine

production was tested by culturing cells in a media at pH 7.5 and 42 °C with supplemental

tryptamine. In order to combat the decrease in pH over time (Figure 3a), we readjusted the pH to

7.5 every 2 h over the course of 10 hours following the pH-controlled methods described above

and as shown in Figure 3b. Figure 5a and b show the NMT and DMT concentrations observed in

the INMT and PaNMT promoter library, respectively. For both INMT and PaNMT mediated

methylations, use of the T7 promoter yielded the highest concentrations of both NMT and DMT.

NMT and DMT production from INMT under the control of the T7 consensus promoter reached

titers of 3.60 +/- 0.11 mg/L and 2.54 +/- 0.13 mg/L, respectively (Figure 5a). PaNMT production

of NMT and DMT were also highest under T7 consensus facilitated expression with titers

reaching 0.37 +/- 0.03 mg/L (Figure 5b). These results led to the use of the T7 promoter for all

further experimentation with both INMT and PaNMT.

Figure 5. NMT and DMT concentration based on promoter strength of key methyltransferase-

encoding gene a) pETM6-SDM2x-INMT b) pETM6-SDM2x-PaNMT. (-) indicates pH control

was not performed.

14

2.2.3 Strict pH Monitoring and Control Increases NMT and DMT Production:

With the results from the temperature, pH, and genetic optimization assays for

methylated tryptamine production completed, we next scaled up production through the use of a

bioreactor, which allowed us to work with greater volumes as well as maintain a constant pH

throughout the fermentation (Figure 3c). We used BL21 StarTM (DE3) w/ pETM6-SDM2x-

INMT (T7 promoter) as our model bioreactor strain due to its consistently higher concentrations

of both NMT and DMT as compared to PaNMT in previous well plate studies. Informed by

previously pH-controlled production of NMT and DMT, we scaled up production through the

use of pH stat controlled bioreactor fermentations. NMT, DMT, and TMT production titers were

observed, at pH 6.5, 7.0, 7.5, and 8.0 (Figure 6). All concentrations represented in Figure 6 are

from bioreactor samples taken 24 h after inoculation. For all three methylated tryptamine

compounds of interest (NMT, DMT and TMT), fermentations conducted under pH-stat

conditions of pH = 7.5 yielded the highest titers. NMT titers from pH 7.5 fermentations reached

11.44 +/- 2.01 mg/L, a 1.5-fold increase over highest NMT titers observed from 48 well plate

assays. DMT titers from pH 7.5 fermentations reached 12.73 +/- 3.28 mg/L, which mark a 7.8-

fold increase compared to DMT produced from the top performing 48 well plate assays. TMT

titers were also observed in the largest quantities from the pH 7.5 fermentations at a value of

6.76 +/- 2.52 mg/L representing the first TMT production observed from a bacterial culture.

Figure 6. NMT, DMT and TMT concentrations from pH stat bioreactor runs of BL21 StarTM

(DE3) containing pETM6-SDM2x-INMT. Highest concentrations of NMT, DMT, and TMT

were achieved at pH = 7.5.

15

2.2.4 Extended Metabolic Pathways and Further Promoter Library Screening Lead to de
novo Production of Methylated Tryptamine:

We further explored the synthesis of DMT from tryptophan by extending our metabolic

pathway to include PsiD, a tryptophan decarboxylase native to the psilocybin biosynthesis

pathway of Psilocybe cubensis. This extended pathway enables a theoretical de novo pathway to

NMT and DMT from glucose in E. coli (Figure 2).

Initial studies, including promoter library optimization, were conducted in tryptophan

supplemented media to reduce metabolic burden and show proof of concept of the newly

constructed metabolic pathway. All promoter library screens were performed using the pH

controlled, medium throughput screening assay described previously. Lead strains from the

promoter library screens were selected for their ability to produce the highest titers of DMT from

tryptophan. The selected strains were then used to test the viability of de novo DMT

biosynthesis. Figure 7 illustrates the success of the promoter library screening in identifying a

pathway construct capable of producing more DMT from tryptophan as compared to the T7-

INMT-PsiD expressing strain. The T7-INMT-PsiD was created as an initial proof of concept for

de novo production of DMT and has been labeled to easily compare its performance within the

promoter library screening results. Figure 7a shows the combined results of two separate

promoter library screens with varied operon gene orientation, specifically, xx5-PsiD-INMT and

xx5-INMT-PsiD. The number of strains screened is ranged between 5-10 times the library size.

A total of 96 strains were selected and are represented in Figure 7a, with 48 strains selected per

operon gene orientation. The ‘xx5’ notation indicates the pseudorandom incorporation of 5

mutant T7 promoters of varied strength and determines the library size and the number of strains

that need to be screened to account for representation of all possible promoter-gene

combinations. Given the large number of strains that need to be screened for promoter library

representation, strains were tested in singlicate (n =1), and lead mutants were later isolated and

rescreened in replicate. Figure 7b represents the monocistronic library screen of 144 strains for

the gene orientation INMT-psiD, and it should be noted that a monocistronic promoter library

with the gene construct psiD-INMT could not be created due to limitations in plasmid

construction methods. Within the operon, monocistronic, and pseudooperon (xx5-psiD-xx5-

INMT) promoter libraries, the best performing strains resulted in just under 25 mg/L DMT and

NMT (Figure 7a, band c) with the highest TMT titer just under 12mg/L observed within the

16

monocistronic promoter library (Figure 7b). The pseudooperon library screening results

represented in Figure 7d (144 strains screened) reveal that the INMT-psiD gene expression order

was less successful compared to the pseudooperon library screening represented in Figure 7c

(144 strains screened) with a psiD-INMT gene expression order and was the least successful

overall in providing high DMT producing strains compared to the others.

Figure 7. NMT, DMT and TMT concentration based on gene configuration and promoter

strength of INMT and PsiD. a) Operon configuration: pETM6-SDM2X-INMT-PsiD and

pETM6-PsiD-INMT. b) Monocistronic configuration: pETM6-SDM2X-INMT-PsiD. c) Pseudo-

operon configuration: pETM6-SDM2x-PsiD-INMT. d) Pseudo-operon configuration: pETM6-

SDM2x-INMT-PsiD.

 Figure 8 shows the comparison in DMT production between top to middle performing

strains selected from each promoter library screening presented in Figure 7. Strains represented

in Figure 8 were labeled and identified according to the promoter library they were selected

from, and the number that was assigned during initial screening: M = monocistronic, P =

pseudooperon, O = operon. T7-INMT-psiD (T7-I-D) was again used as a baseline comparison

for the success of the promoter library in increasing DMT titers. All strains, with the exception of

17

M29, O20, and M132 produced significantly more DMT than T7-INMT-psiD (p < 0.05). Strains

M111, M21, P117, P29 and O1 were selected for all future methylation screenings to present a

relatively broad range of methylation activity. Selected strains were also sent for sequencing

yielding the following promoter identities: M111 = H9-INMT-G6-psiD, M21 = H10-INMT-G6-

psiD, P117 = G6-psiD-C4-INMT, P29 = H10-psiD-C4-INMT, and O1 = C4-psiD-INMT.

Figure 8. NMT and DMT production of top performing strains selected from each distinct

library construct. Strain: M = monocistronic, P = pseudo-operon, O = operon.

These top strains were also tested for their ability to catalyze de novo biosynthesis

(Figure 9). Screening conditions were conserved from previous studies; however, tryptophan was

not supplemented into the media, such that glucose represents the sole carbon source for growth

and product formation. All selected promoter library strains produced significantly more DMT (p

< 0.05) than the T7-INMT-psiD strain (T7-I-D), with the best strain producing 14 +/- 0.37 mg/L

DMT and 31.3 +/- 0.84 mg/L of total methylated tryptamines (Figure 9).

18

Figure 9. De novo production of NMT, DMT, and TMT by select lead strains. (-) symbolizes the

negative control empty vector, pETM6-SDM2X. T7-I-D = T7-INMT-psiD.

2.2.5 Bioreactor Fermentation with Glucose Feed Increases DMT Titers

Benchtop bioreactor fermentation was carried out similarly to previously described

bioreactor methods but with the addition of a glucose feed, which previously went unused as

initial studies utilized a pH-controlled batch operation paradigm. Glucose concentrations within

the fermentation media was monitored using methods outlined in Section 2.1.8. With the

addition of glucose fed batch strategy, we aimed to revisit the viability of DMT production scale-

up; as a result, we chose to ferment our T7-INMT strain with tryptamine supplementation at both

37 °C and 42 °C to compare directly to previous bioreactor data (Figure 6). Additionally, we

wished to compare the DMT production outputs of the T7-INMT strain with tryptamine

supplementation to a strain that expressed both INMT and PsiD with tryptophan

supplementation, in this case strain M111. Figure 10 shows the end point NMT, DMT and TMT

titers observed under a glucose fed batch condition. Strain M111 was grown in AMM

supplemented with 1 g/L of tryptophan. Strain T7-INMT was grown in AMM supplemented with

150 mg/L tryptamine. Although T7-INMT produced more DMT when fermented at 42°C

compared to 37°C it was not significant (p > 0.05), Figure 10. On the other hand, the addition of

the glucose feed made a significant difference in DMT titers compared to previous bioreactor

batch fermentations (Figure 6), showing a 6-fold increase from 12.7 mg/L to 80.1 mg/L. (p <

0.05). Furthermore, M111, was able to produce more NMT and DMT from tryptophan than the

T7-INMT strain from tryptamine under fed-batch conditions, suggesting the methyltransferase

step to be rate limiting.

19

Figure 10. 2L Fed-batch bioreactor studies with select strains. M111 was supplemented with 1

g/L tryptophan, while T7-INMT was supplemented with 150 mg/L tryptamine.

2.2.6 Implementation of Hydrophobic Overlays Fail to Resolve INMT Inhibition:

Before testing overlays on cell cultures, we tested the efficacy of both dodecane and

DINP for their ability to extract DMT from media. MS chromatographs show that less than 1%

of the DMT partitioned into dodecane after a 72 h incubation period with media containing DMT

at relevant levels for the biosynthetic system presented herein. Only 15% of the DMT partitioned

into DINP when incubated for 24 h. Despite the lack of observed efficacy, DINP was used as an

overlay during a 50mL flask fermentation. We did not observe an increase in DMT production

between cultures with an overlay compared to those without. We determined the affect the

overlay had on cell viability by comparing OD600 values between cultures with and without

overlays. OD600 readings of cultures with an overlay were not significantly different (p > 0.05)

than those without and overlay.

2.2.7 Production of 5-MeO-DMT and Bufotenine

By leveraging the substrate promiscuity of both PsiD and INMT in tandem with E. coli’s

native tryptophan synthase subunit TrpB, we demonstrated that our production platform could

process indole derivatives 5-methoxyindole (5-MeO-indole) and 5-hydroxyindole (5-HO-indole)

20

into DMT derivatives 5-MeO-DMT and Bufotenine, respectively, following the metabolic

pathway from Figure 2. Strains used during this screening were the same used for the de novo

production of DMT. The pH-controlled, medium throughput screening method was used to

realize the production of both of these DMT derivatives. Figure 11 shows the production of 5-

MeO-NMT and 5-MeO-DMT by select strains with a maximum observed titers of 0.67 +/- 0.02

mg/L and 0.23 +/- 0.02 mg/L, respectively, by strain P117. Figure 12 shows the production of 5-

HO-methylatedtryptamines by select strains with a maximum observed titer of 2.64 +/- 0.003

mg/L, 3.58 +/- 0.02 mg/L, and 0.39 +/- 0.05 mg/L of 5-HO-NMT, Bufotenine, and 5-HO-TMT,

respectively, also by strain P117.

Figure 11. 5-MeO-NMT and 5-MeO-DMT production by select strains. (-) = pETM6-SDM2X.

T7-I-D = T7-INMT-psiD. No 5-MeO-TMT was observed.

Figure 12. 5-HO-NMT, 5-HO-DMT, and 5-HO-TMT production. (-) = pETM6-SDM2X. T7-I-D

= T7-INMT-psiD.

21

2.3 Discussion

This study shows the first reported case of in vivo NMT, DMT, and TMT production, as

well as their 5-methoxy and 5-hydroxy derivatives, using a prokaryotic host. Additionally, this

study demonstrates the effectiveness of genetic, and fermentation conditions optimization for the

purpose of enhancing desired product titers.

Through the use of a 48 well plate assays to test a large number of fermentation

parameters, it was possible to identify key components to successful methylated tryptamine

biosynthesis. HPLC-MS analysis aided in the identification of desired products within the culture

media confirming the presence of NMT, DMT, and TMT and thus confirming the hypothesis that

INMT and PaNMT could be used to enable in vivo methylation of tryptamine in E. coli.

Identifying the optimal pH and temperature for INMT and PaNMT methylation activity

led to a large increase in product titers over traditional E. coli batch fermentation conditions of

37 ˚C at a neutral initial pH that is not strictly controlled. Furthermore, by employing stricter

limits on pH fluctuation over time, final titers of NMT and DMT were seen to increase compared

to cultures without pH control. We observed consistent trends among INMT methylation activity

with respect to temperature and pH; however, PaNMT activity remained unpredictable due to

low activity, with NMT and DMT concentrations frequently near the limit of quantification. The

PaNMT containing E. coli strain was less successful in producing both NMT and DMT

compared to the strain containing INMT, under their respective optimal conditions. Furthermore,

our in vivo results show PaNMT activity decreasing at increased fermentation temperature,

which was not expected as PaNMT activity was previously reported to increase with temperature

in an in vitro system up to approximately 52 ˚C (Morris et al., 2018).

Genetic optimization through the testing of a wide range of different strength promoters,

including both inducible and constitutive expression, demonstrated the efficacy of the strongly

inducible T7 promoter in the production of NMT, DMT, and TMT. Library construction and

screening of transcriptional variants ensured the most productive pathway configuration for the

production of the products of interest had been identified. It is important to note that although the

initial screening demonstrated a clear preference for the T7 promoter, it will be imperative that

extended pathways be rescreened via the pH-controlled medium throughput well plate assay

described above. As the biosynthesis pathway is extended, the metabolic burden and associated

co-factor and precursor needs from the native E. coli metabolism will change, directly affecting

22

the interplay between expression level for the exogenous pathway and resource availability for

endogenous metabolism (Wu et al., 2016) .

Scaled-up production to bench top fermenters proved successful as INMT methylation of

tryptamine was seen to increase as observed through enhanced titers of NMT, DMT, and the first

observation of TMT biosynthesis. It is important to note that the only variables monitored and

controlled through the initial use of benchtop fermenters were the pH, maintained at 7.5, and the

temperature, controlled at 42 ˚C. Dissolved oxygen (DO), an integral parameter for maximizing

cell growth and maintaining ideal fermentation conditions was not monitored, leaving room for

future bioreactor-based optimization studies. Additionally, the fed-batch functionality for both

carbon and substrate feed were not utilized. Had either the DO been monitored, or substrate

continuously fed to the fermenter, it is expected that product titers would increase beyond levels

observed in this study. It should also be addressed that the TMT identified in the bioreactor

studies presented above has not been well described in terms of its potential psychoactive effects

and to our knowledge has only previously been described twice in the peer reviewed literature

(Servillo et al., 2012; Servillo et al. 2013) . Due to the structural similarity to the natural product,

aeruginascin, it is expected that TMT may have significant bioactivity motivating further study

to enhance its production and exploration of its pharmacological potential in animal studies.

Furthermore, since the biosynthesis of NMT, DMT, and most notably, TMT, was observed to be

catalyzed by the human INMT, this indicates that these mono- and tri-methylated derivatives

may play a currently unstudied role in human health. The development of an E. coli-based

process to facilitate the efficient biosynthesis of these compounds can lead to more focused

studies to determine the roles and mechanism of actions for tryptamines in human neurobiology.

The de novo biosynthesis of DMT was attempted in this study to eliminate the need for

relatively more expensive substrates such as tryptophan, tryptamine, serine, or indole, compared

with D-glucose, a cheaper and more readily available substrate. Through the expression of

transcriptionally-varied genetic mutants of PsiD and INMT onto a single plasmid construct using

the same ePathOptimize approach (Jones et al., 2015) we used for the single INMT/PaNMT gene

constructs, we were able to achieve de novo production of NMT and DMT in vivo (Figure 9). A

total of six gene constructs were selected from an iterative screening process of each library to be

further tested for their ability to produce DMT from either tryptophan or glucose. Final data

analysis led to the identification of the top de novo performing strain M111, which contains a

23

monocistronic gene construct with the low strength T7 mutant promoters H9 and G6 controlling

the expression of INMT and PsiD, respectively (H9-INMT-G6-PsiD). Through screening of

genetically-varied libraries, we were able to demonstrate the first example of a microbe capable

of de novo (from glucose) synthesis of NMT, DMT, and TMT in a bacterial host platform.

Native E. coli TrpB, and heterologously expressed PsiD and INMT were shown to

exhibit substrate promiscuity through the production of the 5-MeO-DMT, and bufotenine via the

metabolic pathway described in Figure 2. 5-MeO-DMT and bufotenine are both psychoactive

DMT derivatives that reside in some species of plants and the Colorado River Toad, found in

Sonoran Desert. These compounds have recently seen increased use recreationally and spiritually

and have anecdotally been known to help treat mental health conditions (Davis et al. 2019). The

same elite performing strains isolated for the de novo production of DMT were used for this

screening process. Results led to the identification of strain P117, which contains a pseudo-

operon gene construct with the weak G6 promoter controlling the expression of PsiD and the

strong C4 promoter controlling INMT expression (G6-psiD-C4-INMT), as the most effective

strain in producing both 5-MeO-DMT and bufotenine from their respective indole precursors

(Figure 2). After producing DMT derivatives we believed that we could further utilize the

observed substrate promiscuity in attempt to produce psilocin (4-HO-DMT), the active form of

the native mushroom psychedelic psilocybin, by feeding the substrate 4-HO-indole using the

same pathway previously described. Unfortunately, after comparing screening results to a

standard, we were unable to detect any presence of psilocin in our fermentation media. The

substrate promiscuity demonstrated by the production of these DMT analogs suggests that

additional DMT derivatives, both existing and novel, could be produced through this metabolic

pathway. The limited evidence presented here suggests there will likely be some chemical

position sensitivity, however, screening of different promoter variants and/or enzyme homologs

from varied species may be able to overcome this limitation.

Through the studies outlined in this thesis it has been shown that DMT and DMT

derivatives can be synthesized in vivo; however, the bioreactor fermentation studies indicate that

limitations in this biosynthetic production platform of DMT exist. The presence of unmethylated

tryptamine in the LCMS analysis corroborates the idea that INMT methylation of tryptamine is

the rate limiting step for the in vivo biosynthesis of DMT and DMT derivatives described in this

work. UB et al., 2014, suggest that the activity of INMT is attenuated by both non-competitive

24

and competitive inhibition of DMT on the methyltransferase. We believe that if DMT could be

removed from the media as it was produced, this potential inhibition of INMT could be reduced

or eliminated. To test this hypothesis, we screened two potential hydrophobic overlays as a

potential sink for DMT during fermentation. Unfortunately, we observed minimal partition of

methylated tryptamines into either hydrophobic overlay, limiting our ability to attenuate any

INMT inhibition that may be present. More thorough study using a more diverse range of

hydrophobic overlays may provide valuable insight into an appropriate path forward towards

enhanced fermentation-based production of methylated tryptamines.

In conclusion, the biosynthesis of DMT through application of metabolic and pathway

engineering principles in E. coli presented in this work is the first instance of in vivo and de novo

DMT synthesis in a prokaryotic host. The highest reproducible titers of DMT achieved in this

study is reported as 80.1 mg/L, a total of a 48-fold increase from our first proof of concept well

plate assays, which was synthesized by co-expression of the human INMT enzyme and the

Psilocybe cubensis psiD gene and produced from tryptophan supplemented media at a maximum

molar yield of 0.050 mol/mol. Further efforts to genetically optimize the de novo DMT synthesis

pathway, and to tailor the fermentation process to enhance DMT production could lead to an

alternative production method competitive with the chemical synthesis of DMT (Cozzi & Daley,

2020; Speeter & Anthony, 1954).  As regulations around the studies of DMT and its derivatives

for medical use continue to relax moving forward, it is important that avenues for the supply and

discovery of these medical compounds are continuously explored.

3.0 Conclusions and Future Work:

We have demonstrated a proof of principle for the in vivo and de novo production of

NMT, DMT and TMT using genetically engineered E. coli. Excitingly, we have also leveraged

the same engineered E. coli for the in vivo production of 5-MeO-DMT and Bufotenine; however,

the fermentation-based process still requires further improvements before an industrially

competitive bioprocess will become a reality.

Through the creation and screening of a large number of transcriptionally varied operon

configurations we have explored the potential for genetic optimization strategies to enhance

DMT titers and enable the production of DMT derivatives.

25

Here we have taken a specific genetic optimization approach that focuses on altering

transcription unit structure and promoter strength. Additional genetic optimization techniques

that focus on varying the enzyme structure through protein engineering efforts or sourcing

diverse enzymes from various natural sources could lead to further enhanced DMT production or

substrate promiscuity, possibly enabling biosynthesis of novel DMT derivatives. Specifically,

methods involving bioinformatics and the comparison of alternative indolethylamine-N-

methyltransferases between species may lead to higher methyltransferase activity compared to

the human INMT system presented above. Other genetic optimization techniques could also

include chromosomal integration of the necessary enzymes. By integrating the genes responsible

for enzyme expression directly onto the chromosome, the need for antibiotic selection is

eliminated, which might provide the cells with a metabolic advantage, resulting in higher product

yields. It is also important to note that fine-tuned genetic balancing at the scale performed in this

thesis is currently difficult to achieve on the chromosome. The chromosomal integration process

has been used before for other high-value products and has proven effective, further motivating

this future direction (Englaender et al., 2017).

This opportunity to maximize INMT activity and end product titers proves important as

DMT derivatives, such as 5MeO-DMT and Bufotenine have been shown to treat diseases that

have not conventionally been treated with serotonin analogs, such as ocular hypertension and

glaucoma (May et al., 2003). Furthermore, as one of the main natural sources of 5-MeO-DMT is

the Colorado River Toad, it is important that new synthesis methods be made viable to prevent

ecological collapse of the species from human interaction. One such example of an alternative

method for the production of 5-MeO-DMT is a chemical synthesis performed by Sherwood et al.

2020 (Sherwood et al., 2020). Although the current biosynthetic approach is unable to produce

comparable titers and yields to the chemical synthesis, the pursuit of a biosynthetic synthesis can

shed light into some of the enzymatic mechanisms (Sherwood et al., 2020).

 Literature has reported a Km value twice as large compared to Km of uninhibited rabbit

INMT (rabINMT) at a DMT concentration of 18.8 mg/L (UB et al., 2014). With our titers

reaching as high 80 mg/L it is possible that INMT is being inhibited by its product DMT. Two

options that can be explored to overcome this obstacle is either to circumnavigate the inhibitory

effects of DMT on INMT, or to eliminate them. In this study we attempted to circumnavigate the

issue by using a hydrophobic overlay to extract DMT out of the aqueous media so as to alleviate

26

enzymatic inhibition. As shown, this approach did not prove successful, however alternative

overlay solvents are available and could be evaluated. In vitro enzyme kinetics studies could

provide the data necessary to better inform if and when INMT inhibition by methylated

tryptamines is playing a role in reducing the potential production of DMT in our system. One

such method for running enzyme kinetic studies would involve enzyme purification and

analyzing Michaelis-Menten kinetics. With a known concentration of enzyme, varying

concentrations of substrate, in this case tryptamine, can be added to a solution containing the

enzyme. As the enzyme converts tryptamine to DMT the rate of reaction can be measured by

taking periodic samples of the solution. Based on the concentration of tryptamine at each time

point, a reaction rate could be calculated. Doing this with a few different known concentrations

of substrate and a constant enzyme concentration, a Michaelis-Menten kinetic curve could be

generated. This experiment could then be repeated with the addition of the proposed inhibitor

DMT. A decrease in maximum reaction rate (Vmax) and increase in Km as reported previously,

would suggest non-competitive mixed inhibition and corroborate cited literature (UB et

al.,2014). A more thorough characterization of the INMT’s enzymatic structure could also

provide insights into mechanisms that dictate its methylation activity. Through the identification

of enzyme active and inhibition sites, specific amino acid residues can be targeted through site

directed mutagenesis (SDM) which could lead to increased enzyme activity, and reduced

inhibitory response. Previously conducted in silico analysis of DMT binding to both rabINMT

and hINMT could prove useful as a starting point for exploring the effect of SDM on DMT

production.

As outlined in the conclusion above, we believe that the main hurdle to the viability of

scaled-up production of DMT is the inhibitory effect it has on INMT, the enzyme responsible for

the sequential methylation of tryptamine to DMT.

Although many roadblocks exist, the potential for an industrially competitive

fermentation-based approach for the production of DMT and derivative compounds is possible.

Previous reports of gram-scale production of tryptamines norbaeocystin and psilocybin using

similar optimization methods in E. coli leaves promise that further enhancements in titer, rate,

and yield for DMT producing strains is feasible (Adams et al. 2022; Adams et al., 2019). By

exploring the potential research directions outlined above, it could lead to the realization of the

potential of microbial-based biosynthesis of methylated tryptamines.

27

References

“WHO | Depression and Other Common Mental Disorders.” 2017. WHO.

http://www.who.int/mental_health/management/depression/prevalence_global_health_estim
ates/en/ (May 24, 2021).

“Rabbit Lung Indolethylamine N-Methyltransferase | Elsevier Enhanced Reader.”

https://reader.elsevier.com/reader/sd/pii/S002192581988479X?token=B7300F56A249E7B1
22B08AC03CA97A7EB425CDDF144B82C9D7BDCA2045745DF2DE91263D7F9522D7
A40A8B5C6AF68FAE&originRegion=us-east-1&originCreation=20210716162611 (July
20, 2021).

“World Drug Report 2019: 35 Million People Worldwide Suffer from Drug Use Disorders While

Only 1 in 7 People Receive Treatment.”
https://www.unodc.org/unodc/en/frontpage/2019/June/world-drug-report-2019_-35-million-
people-worldwide-suffer-from-drug-use-disorders-while-only-1-in-7-people-receive-
treatment.html (September 28, 2021).

“UK Company Secures Approval for World’s First DMT Clinical Trial.”

https://www.pharmexec.com/view/uk-company-secures-approval-for-world-s-first-dmt-
clinical-trial (September 30, 2021).

“Fusion Protein Linkers: Property, Design and Functionality | Elsevier Enhanced Reader.”

https://reader.elsevier.com/reader/sd/pii/S0169409X12003006?token=C171820728222EEF
6BBC1A9B2427D4452E1AFC70F86B4A87FD08FCDF4083F377F79557D85CE37F21A4
EB60CAC91CE020&originRegion=us-east-1&originCreation=20211027180703 (October
27, 2021).

“Strategy for Linker Selection to Enhance Refolding and Bioactivity of VAS-TRAIL Fusion

Protein Based on Inclusion Body Conformation and Activity | Elsevier Enhanced Reader.”
https://reader.elsevier.com/reader/sd/pii/S0168165615300092?token=C95AE473E0FF451E
1A7AFD3EF14C6FC12D75A8DE7B73694CF3DCF0081AF89EE37D5F3519573E9F4790
F68C2649958BCB&originRegion=us-east-1&originCreation=20211027180701 (October
27, 2021).

“Ritual Use of Anadenanthera Seeds among South America Natives | Request PDF.”

https://www.researchgate.net/publication/6227936_Ritual_use_of_Anadenanthera_seeds_a
mong_South_America_natives (June 21, 2022).

Adams, Alexandra M. et al. 2022. “Development of an E. Coli-Based Norbaeocystin Production

Platform and Evaluation of Behavioral Effects in Rats.” Metabolic Engineering
Communications 14: e00196.

28

Adams, Alexandra M. et al. 2019. “In Vivo Production of Psilocybin in E. Coli.” Metabolic

Engineering 56: 111–19.

Anderson, Brian T. et al. 2012. “Statement on Ayahuasca.” International Journal of Drug Policy

23(3): 173–75.

Axelrod, Julius. 1961. “Enzymatic Formation of Psychotomimetic Metabolites from Normally

Occurring Compounds.” Science 134(3475): 343.
https://pubmed.ncbi.nlm.nih.gov/13685339/ (May 16, 2021).

Barbosa, Paulo Cesar Ribeiro et al. 2016. “Psychological and Neuropsychological Assessment of

Regular Hoasca Users.” Comprehensive Psychiatry 71: 95–105.

Bouso, José Carlos et al. 2012. “Personality, Psychopathology, Life Attitudes and

Neuropsychological Performance among Ritual Users of Ayahuasca: A Longitudinal
Study.” PLoS ONE 7(8): 42421. www.ploso

Cozzi, Nicholas V., and Paul F. Daley. 2020. “Synthesis and Characterization of High-Purity
N,N-Dimethyltryptamine Hemifumarate for Human Clinical Trials.” Drug Testing and
Analysis 12(10): 1483–93. h

Davis, Alan K. et al. 2019. “5-Methoxy-N,N-Dimethyltryptamine (5-MeO-DMT) Used in a

Naturalistic Group Setting Is Associated with Unintended Improvements in Depression and
Anxiety.” The American journal of drug and alcohol abuse 45(2): 161.
/pmc/articles/PMC6430661/ (June 26, 2022).

de Osório, Flávia L. et al. 2015. “Antidepressant Effects of a Single Dose of Ayahuasca in
Patients with Recurrent Depression: A Preliminary Report.” Revista Brasileira de
Psiquiatria 37(1): 13–20. ht

Englaender, Jacob A. et al. 2017. “Effect of Genomic Integration Location on Heterologous
Protein Expression and Metabolic Engineering in E. Coli.” ACS Synthetic Biology 6(4):
710–20. https://pubs.acs.org/doi/full/10.1021/acssynbio.6b00350 (June 26, 2022).

Fava, Maurizio. 2003. “Diagnosis and Definition of Treatment-Resistant Depression.” Biological
Psychiatry 53(8): 649–59. https://pubmed.ncbi.nlm.nih.gov/12706951/ (May 16, 2021).

Forsström, T., J. Tuominen, and J. Kärkkäinen. 2001. “Determination of Potentially

Hallucinogenic N-Dimethylated Indoleamines in Human Urine by HPLC/ESI-MS-MS.”
Scandinavian Journal of Clinical and Labora

Fricke, Janis, Felix Blei, and Dirk Hoffmeister. 2017. “Enzymatic Synthesis of Psilocybin.”

Angewandte Chemie - International Edition 56(40): 12352–55.
https://pubmed.ncbi.nlm.nih.gov/28763571/ (May 1

29

Fricke, Janis et al. 2019. “Production Options for Psilocybin: Making of the Magic.” Chemistry -

A European Journal 25(4): 897–903. https://chemistry-
europe.onlinelibrary.wiley.com/doi/full/10.1002/ch

Guimarães dos Santos, Rafael. 2013. “Safety and Side Effects of Ayahuasca in Humans-An

Overview Focusing on Developmental Toxicology.” Journal of Psychoactive Drugs 45(1):
68–78. https://www.tandfonli

He, Wenqin et al. 2015. “Production of Chondroitin in Metabolically Engineered E. Coli.”

Metabolic Engineering 27: 92–100.

Hoefgen, Sandra et al. 2018. “Facile Assembly and Fluorescence-Based Screening Method for
Heterologous Expression of Biosynthetic Pathways in Fungi.” Metabolic Engineering 48:
44–51.

Jang, Hui Jeong et al. 2011. “Retinoid Production Using Metabolically Engineered Escherichia

Coli with a Two-Phase Culture System.” Microbial Cell Factories 10.

Jones, J. Andrew et al. 2015. “EPathOptimize: A Combinatorial Approach for Transcriptional

Balancing of Metabolic Pathways.” Scientific Reports 5. /pmc/articles/PMC4650668/ (May
16, 2021).

Knoth, Russell L, Susan C Bolge, Edward Kim, and Quynh-Van Tran. 2010. “Effect of

Inadequate Response to Treatment in Patients with Depression.” The American Journal of
Managed Care 16(8): e188-196. h

Lima, Osvaldo Gonçalves. 1946. “Observações Sobre o ‘Vinho Da Jurema’ Utilizado Pelos
Índios Pancarú de Tacaratu (Pernambuco ).” Arquivos do Instituto de Pesquisas
Agronômicas 4: 45–86.

Mandell, Arnold J., and Merrily Morgan. 1971. “Indole(Ethyl)Amine N-Methyltransferase in

Human Brain.” Nature New Biology 230(11): 85–87.
https://www.nature.com/articles/newbio230085a0 (May 16, 2021).

Manske, Richard H. F. 1931. “A SYNTHESIS OF THE METHYLTRYPTAMINES AND

SOME DERIVATIVES.” Canadian Journal of Research 5(5): 592–600.

May, Jesse A. et al. 2003. “Evaluation of the Ocular Hypotensive Response of Serotonin 5-
HT1A and 5-HT2 Receptor Ligands in Conscious Ocular Hypertensive Cynomolgus
Monkeys.” The Journal of pharmacology and experimental therapeutics 306(1): 301–9.
https://pubmed.ncbi.nlm.nih.gov/12676887/ (June 12, 2022).

Miller, Melanie J., Juan Albarracin-Jordan, Christine Moore, and José M. Capriles. 2019.

“Chemical Evidence for the Use of Multiple Psychotropic Plants in a 1,000-Year-Old Ritual
Bundle from South America.”

30

Milne, N. et al. 2020. “Metabolic Engineering of Saccharomyces Cerevisiae for the de Novo

Production of Psilocybin and Related Tryptamine Derivatives.” Metabolic Engineering 60:
25–36.

Morris, Jeremy S., Ryan A. Groves, Jillian M. Hagel, and Peter J. Facchini. 2018. “An N-
Methyltransferase from Ephedra Sinica Catalyzing the Formation of Ephedrine and
Pseudoephedrine Enables Microbial Pheny

Pacher, Pal, and Valeria Kecskemeti. 2005. “Trends in the Development of New

Antidepressants. Is There a Light at the End of the Tunnel?” Current Medicinal Chemistry
11(7): 925–43. https://pubmed.ncbi

Penn, Elizabeth, and Derek K Tracy. 2012. “The Drugs Don’t Work? Antidepressants and the

Current and Future Pharmacological Management of Depression.” Therapeutic advances in
psychopharmacology 2(5):

Saavedra, J. M., J. T. Coyle, and J. Axelrod. 1973. “THE DISTRIBUTION AND PROPERTIES

OF THE NONSPECIFIC N‐METHYLTRANSFERASE IN BRAIN.” Journal of
Neurochemistry 20(3): 743–52. https://pubmed.ncbi.nlm.

Schultes, R., A. Hofmann, and Christian Rätsch. 1992. “Plants of the Gods: Their Sacred,

Healing, and Hallucinogenic Powers.” undefined.

Schultes, R., A. Hofmann, and Christian Rätsch. 1992. “Plants of the Gods: Their Sacred,

Healing, and Hallucinogenic Powers.” undefined.

Servillo, Luigi et al. 2012. “N-Methylated Tryptamine Derivatives in Citrus Genus Plants:

Identification of N, N, N -Trimethyltryptamine in Bergamot.” Journal of Agricultural and
Food Chemistry 60(37)

Shen, Hong-Wu, Xi-Ling Jiang, Jerrold C. Winter, and Ai-Ming Yu. 2010. “Psychedelic 5-

Methoxy-N,N-Dimethyltryptamine: Metabolism, Pharmacokinetics, Drug Interactions, and
Pharmacological Actions.” Current drug metabolism 11(8): 659.
/pmc/articles/PMC3028383/ (June 21, 2022).

Souza, Rita C.Z. et al. 2019. “Validation of an Analytical Method for the Determination of the

Main Ayahuasca Active Compounds and Application to Real Ayahuasca Samples from
Brazil.” Journal of Chromatogr

Speeter, Merrill E., and William C. Anthony. 1954. “Furochromones and Coumarins. XI. the
Molluscicidal Activity of Bergapten, Isopimpinillin and Xanthotoxin.” Journal of the
American Chemical Society

Szára, St. 1956. “Dimethyltryptamin: Its Metabolism in Man; the Relation of Its Psychotic Effect

to the Serotonin Metabolism.” Experientia 12(11): 441–42.
https://link.springer.com/article/10.1007/BF0

31

Thompson, Michael A. et al. 1999. “Human Indolethylamine N-Methyltransferase: CDNA

Cloning and Expression, Gene Cloning, and Chromosomal Localization.” Genomics 61(3):
285–97. https://pubmed.ncbi.nlm.

UB, Chu et al. 2014. “Noncompetitive Inhibition of Indolethylamine-N-Methyltransferase by

N,N-Dimethyltryptamine and N,N-Dimethylaminopropyltryptamine.” Biochemistry 53(18):
2956–65. https://pubmed.nc

Wu, Gang et al. 2016. “Metabolic Burden: Cornerstones in Synthetic Biology and Metabolic

Engineering Applications.” Trends in Biotechnology 34(8): 652–64.
https://pubmed.ncbi.nlm.nih.gov/26996613/ (Ma

Xu, Peng, Amerin Vansiri, Namita Bhan, and Mattheos A.G. Koffas. 2012. “EPathBrick: A

Synthetic Biology Platform for Engineering Metabolic Pathways in E. Coli.” ACS Synthetic
Biology 1(7): 256–66. htt

Young, Kevin P. et al. 2021. “Health Care Workers’ Mental Health and Quality of Life during
COVID-19: Results from a Mid-Pandemic, National Survey.” Psychiatric Services 72(2):
122–28.

32

Supplementary Materials

SF1. A280 chromatograph comparing the absorbances of a DMT standard (purchased from
Cerilliant) and a bioreactor sample. Blue = DMT standard; Black = bioreactor sample.

33

SF2. Extracted Ion Channel Mass-spectroscopy peaks. Time is given on the x axis, and total
counts are given on the y axis. The first three chromatographs (top down) are taken from
bioreactor samples and the final chromatograph is that of a DMT standard (purchased from
Cerilliant): NMT (top), DMT (top-middle), TMT (bottom-middle), DMT standard (bottom).
Retention times provided in parentheses.

34

ST1. Strain and Plasmid List.
Number

Strain or vector

Relevant properties

Reference

Strain 1

Escherichia coli DH5a

F−, φ80d lacZΔM15, Δ(lacZYA-argF)U169, recA1,
endA1, hsdR17(rk−, mk+), phoA, supE44λ−, thi−1, gyrA96,
relA1

Strain 2  E. coli BL21 Star™ (DE3)

F−ompT gal dcm rne131 lon hsdSB (rB

_mB

_) λ(DE3)

Novagen

Invitrogen

Plasmid 1

pETM6

ColE1(pBR322), AmpR

(Xu et al., 2012)

Plasmid 2

pETM6-SDM2x

#6 with XbaI and XmaJI sites swtiched

Plasmid 3

pETM6-SDM2x-PsiD

#1 containing psiD

#1 containing INMT

#1 containing PaNMT

#3 containing PsiD

(Adams et al.,
2017)

(Adams et al.,
2017)

This Study

This Study

This Study

Plasmid 4  pETM6-SDM2x-INMT

Plasmid 6

Plasmid 5  pETM6-SDM2x-PaNMT
pETM6-SDM2x-INMT-
PsiD
pETM6-SDM2x-PsiD-
INMT

Plasmid 7

Plasmid 8

pETM6-G6-mCherry

Plasmid 9

pETM6-H9-mCherry

Plasmid 10  pETM6-H10-mCherry

Plasmid 11

pETM6-mCherry

Plasmid 12

pETM6-C4-mCherry

Plasmid 13

M111

Plasmid 14

M21

Plasmid 15

P117

Plasmid 16

Plasmid 17

P29

O1

#3 PsiD and INMT expression order switched

This Study

#4 containing the mCherry reporter under control of the
G6 mutant T7 promoter
#4 containing the mCherry reporter under control of the
H9 mutant T7 promoter
#4 containing the mCherry reporter under control of the
H10 mutant T7 promoter
#4 containing the mCherry reporter under control of the
consensus T7 promoter
#4 containing the mCherry reporter under control of the
C4 mutant T7 promoter
#5 in monocistronic configuration: H9 mutant T7
promoter expressing INMT and G6 mutant T7 promoter
expressing PsiD
#5 in monocistronic configuration: H10 mutant T7
promoter expressing INMT and G6 mutant T7 promoter
expressing PsiD
#6 in pseudo-operon configuration: G6 mutant T7
promoter expressing INMT and C4 mutant T7 promoter
expressing PsiD
#6 in pseudo-operon configuration: H10 mutant T7
promoter expressing INMT and C4 mutant T7 promoter
expressing PsiD
#6 in operon configuration: C4 mutant T7 promoter
expressing PsiD and INMT

(Jones et al.,
2015)
(Jones et al.,
2015)
(Jones et al.,
2015)

(Xu et al., 2012)

(Jones et al.,
2015)

This Study

This Study

This Study

This Study

This Study

35

ST2. Primer List
Sequence (5' - 3')
Name
GATCGATCATATGAAAGGAGGATTTACAGGTG
INMT_FWD_NdeI
CAGTCAGCTCGAGTTACGGTC
INMT_REV_XhoI
GCGCCGCATATGGAAGAGGCTAAAATGGCAAC
PaNMT_FWD_NdeI
GCCGCCTCGAGTTACTTTTTCTTAAACAGAAAATGGG
PaNMT_REV_XhoI
INMT-Seq-Mid-Rev
TCCAGCTCCTCACGATTACG
PaNMT-Seq-Mid-Rev  GCAGTTCGTAATGCTGACCC
TTGGAGAGTCCTGAATGCCC
psiD-Seq-Mid-Rev

36

