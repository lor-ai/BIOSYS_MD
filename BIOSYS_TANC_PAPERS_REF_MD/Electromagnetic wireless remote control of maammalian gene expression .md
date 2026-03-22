Electromagnetic wireless remote control of
mammalian transgene expression

https://doi.org/10.1038/s41565-025-01929-w

Received: 25 July 2024

Accepted: 2 April 2025

Published online: 5 May 2025

 Check for updates

Zhihua Lin
Martin Fussenegger

  1, Preetam Guha Ray
  1,2

  1, Jinbo Huang

  1, Peter Buchmann

  1 &

Communication between wireless field receivers and biological sensors
remains a key constraint in the development of wireless electronic devices
for minimally invasive medical monitoring and biomedical applications
involving gene and cell therapies. Here we describe a nanoparticle–cell
interface that enables electromagnetic programming of wireless expression
regulation (EMPOWER) of transgenes via the generation of cellular reactive
oxygen species (ROS) at a biosafe level. Multiferroic nanoparticles coated
with chitosan to improve biocompatibility generate ROS in the cytoplasm of
cells in response to a low-frequency (1-kHz) magnetic field. Overexpressed
ROS-responsive KEAP1/NRF2 biosensors detect the generated ROS which
is rewired to synthetic ROS-responsive promoters to drive transgene
expression. In a proof-of-concept study, subcutaneously implanted
alginate-microencapsulated cells stably expressing an EMPOWER-controlled
insulin expression system normalized blood-glucose levels in a mouse model
of type 1 diabetes in response to a weak magnetic field.

Synthetic biology has revolutionized cell engineering for alleviating
numerous diseases1,2, including chronic pain3, obesity4, diabetes5,
cancer6 and muscle atrophy7, and for investigating neural circuits8
and bioelectronics interfaces9,10. In particular, physical stimuli of gene
circuits, such as light11, sound12, electrical signals13,14 and magnetic
fields15,16, have been intensively explored for spatiotemporal control
of therapeutic outputs. To circumvent the challenge of wireless sig-
nal propagation, electromagnetic fields (EMFs) of varying strength,
frequency, duration and location have been exploited in conjunction
with the mechanical17–19 or thermal properties8,20,21 of magnetic nano-
particles to enable coupling with ion channels on cell membranes.
EMFs with an amplitude of <50 mT and a frequency of <1 MHz mini-
mize energy dissipation in living tissues22, and therefore are suitable
for remotely programmable switches to stimulate cellular functions
with minimal influence on native systems. However, legacy technology
pioneering the electromagnetic programming of cellular behaviour
was based on cell-specific in vivo coordination of inorganic nano-
particles to channels or receptors of native or engineered cells using
antibodies23,24 or tags16,18,25, which may elicit off-target effects of conju-
gated nanoparticles26,27, promote liver toxicity20,28 or limit robustness

due to intracellular trafficking of channels and receptors29, resulting
in limited tunability22 and biosafety30. We have therefore designed and
tested a versatile and robust genetic interface enabling tunable remote
control of therapeutic transgene expression by microencapsulated
designer cells using low-power EMF.

Multiferroic materials that harmonize magnetostrictive and piezo-
electric effects can exploit magnetic fields to generate electricity for
biological applications, such as remote brain activity detection, deep
neural stimulation31, bone defect repair32 and degradation of Alzhei-
mer’s β-amyloid aggregates33. These effects occur as aqueous solvents
and solutes transfer charge carriers from multiferroic material surfaces
to produce electrophiles, mostly reactive oxygen species (ROS)34,35.
Thus, a.c. millitesla EMFs in the low-frequency range (0.1–1 kHz) hold
promise as a biological portal via ROS.

ROS act as native cytoplasmic signals in living systems, and
human cells contain components that can sense and respond to
them36,37. When exposed to elevated ROS, Kelch-like ECH-associated
protein 1 (KEAP1), which contains ROS-sensitive cysteine residues,
releases nuclear factor erythroid 2 p45-related factor 2 (NRF2), allow-
ing NRF2 to translocate and bind to intranuclear antioxidant-response

1Department of Biosystems Science and Engineering, ETH Zurich, Basel, Switzerland. 2University of Basel, Faculty of Life Science, Basel, Switzerland.

 e-mail: fussenegger@bsse.ethz.ch

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1071

nature nanotechnologyArticle
a

b

c

)
.
u
.
a
(

y
t
i
s
n
e
t
n

I

Hydrothermal

Sol–gel and
calcination

Ionic
adsorption

CoFe2O4
(CFO)

CoFe2O4@BiFeO3
(BCFO)

CoFe2O4@BiFeO3@chitosan
(CBCFO)

CoFe2O4@BiFeO3@chitosan

CoFe2O4

BiFeO3

Chitosan

BF

Co

Co/Bi

Co/Bi/N

Co K

Bi M

N

)
.
u
.
a
(

y
t
i
s
n
e
t
n

I

0

25

50

Distance (nm)

BCFO

CBCFO

>0.9999 0.3937 0.3937 0.2151 0.0590 0.2151

B

BCFO

B

B

C

B

C

BB

C

C

C

B

BiFeO3

CoFe2O4

d

)

%

(
e
c
n
a
t
t
i

m
s
n
a
r
T

BCFO

Chitosan

CBCFO

e

60

)

V
m

(

l
a
i
t
n
e
t
o
p
a
t
e
Z

40

20

0

–20

–40

f

150

)

%

(

y
t
i
l
i

i

b
a
v
l
l
e
C

100

50

0

20

30

40

50

60

70

4,000

3,000

2,000

1,000

BCFO

CBCFO

2θ (deg)

Wavelength (cm–1)

5

0
Concentration (µg per 106 cells)

100

500 1,000

50

Fig. 1 | Construction and characterization of CBCFO nanoparticles.
a, Illustration of the synthesis of CBCFO nanoparticles. b, STEM bright-field (BF)
images and corresponding EDX results with colocalized elemental mapping of
cobalt, bismuth and nitrogen are consistent with a core–shell structure of CBCFO
nanoparticles. Scale bar, 50 nm. c, XRD pattern displaying the crystallinity of
BCFO. Black, BCFO; B, peaks from BiFeO3; C, peaks from CoFe2O4. d, Attenuated

total reflectance infrared spectra of BCFO, chitosan and CBCFO. e, Zeta potential
of BCFO and CBCFO, before and after coating with the chitosan layer. f, Cell
viability upon exposure to CBCFO nanoparticles is dependent on nanoparticle
mass per million cells. Data are presented as mean ± s.d., n = 3 (e) or n = 4 (f)
independent experiments. P values in f were calculated versus the corresponding
non-induced control by a two-sided unpaired t-test.

elements (AREs), resulting in transcriptional antioxidant responses38.
Here we utilized magnetoresponsive ROS-generating multiferroic
(CoFe2O4@BiFeO3@chitosan, CBCFO) nanoparticles to communi-
cate with cells sensitized to ROS by overexpressing KEAP1/NRF2 and
rewired NRF2 to synthetic ARE-containing promoters, thereby con-
structing a system that we term electromagnetic programming
of wireless expression regulation (EMPOWER). In this system, the
embedded CBCFO nanoparticles serve as nanoreceivers of an exter-
nal electromagnetic field, providing electromagnetic tunability of
ROS generation to drive transgene expression of the target protein
by the host cells. For proof of concept and as an example, we chose
to validate the EMPOWER system for blood-glucose management
in experimental type 1 diabetes (T1D) because diabetes is a dynami-
cally highly challenging medical condition with dramatically increas-
ing prevalence39–41. Therefore, we implanted transgenic human cells
with the EMPOWER system enclosed in coherent, clinically licensed
alginate microcapsules into T1D mice and exposed them to an EMF
to control insulin release. Low-frequency EMF (1 kHz) stimulation
of 21 mT for 3 min per day effectively induced insulin secretion from
the subcutaneously implanted EMPOWER-controlled designer cells
and restored normoglycaemia in T1D mice over the entire 4-week
experimental period.

Results
Characterization of chitosan-multiferroic nanoparticles
To sense the magnetic field for ROS-mediated transgene expression
control, we synthesized core–shell CoFe2O4@BiFeO3 (BCFO) multi-
ferroic nanoparticles consisting of magnetostrictive CoFe2O4 (CFO)
nanoparticle cores and piezoelectric BiFeO3 (BFO) shells, with the
chitosan outer layer to form the CBCFO nanoparticles, as illustrated
in Fig. 1a. Scanning transmission electron microscopy (STEM) imaging
and corresponding energy-dispersive X-ray spectroscopy (EDX) map-
ping (Fig. 1b) confirmed the structure of the CBCFO nanoparticles, as
demonstrated by the distributions of cobalt, bismuth and nitrogen in
the CFO, BFO and chitosan. The line profile of the CBCFO nanoparticle
shows the representative spatial distributions of cobalt, bismuth and
nitrogen, quantitatively confirming the structure. The EDX spectrum
indicated similar atom contents of cobalt and bismuth in the CBCFO
nanoparticles (Supplementary Fig. 1), in contrast with CFO (Supple-
mentary Fig. 2a) and BCFO (Supplementary Fig. 2b) nanoparticles.
The CBCFO nanoparticles were 35.5 ± 10.3 nm in diameter, while the
diameters of CFO and BCFO nanoparticles were 25.4 ± 6.1 nm and
32.9 ± 8.5 nm, respectively, according to the transmission electron
microscopy (TEM) results (n = 50 particles). At the physiological pH of
7.4, the hydrodynamic diameter of CBCFO nanoparticles is 36.3 ± 4.8 nm

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1072

Articlehttps://doi.org/10.1038/s41565-025-01929-w

CFO
BCFO
CBCFO

b

)

1
–
g
u
m
e
(

t
n
e
m
o
M

150

100

50

0

–50

–100

–150

O2

−·

O2

c

0.2

)

V

(

l
a
i
t
n
e
t
o
P

0

–0.2

+

+
+
+
+
+
+

+

–

–
–

–

–

–

–
–

ROS generation

On

On

On

On

On

300

P = 0.0001

P = 0.3578

200

P = 0.9971

100

d

)
l
o
r
t
n
o
c
f
o
%

(

l
e
v
e
l

S
O
R

–30 –20

–10  0

10

20  30

0

20

40

60

80

100

Magnetic field (kOe)

Time (s)

a

H2O

OH·

e

CBCFO

ROS/electrophiles

KEAP1 KEAP1

NRF2

NRF2

Ub

Ub

Ub

Ub

Degraded
NRF2

Engineered cell

sMaf

NRF2

PARE

PhCMV

PhCMV

POI

KEAP1

NRF2

f

)

1
–

l

U

(
P
A
E
S

h

Insulin

)

1
–

l

U

(
P
A
E
S

120

100

80

60

40

20

0

250

200

150

100

50

0

EMFS (–)

EMFS (+)

13.8×
P < 0.0001

7.2×
P < 0.0001

1.2×
P > 0.9999

CFO

BCFO

CBCFO

CBCFO (–)

CBCFO (+)

11.7×, P < 0.0001

U

(
P
A
E
S

i

)

1
–

l

U

(
P
A
E
S

200

150

100

50

0

250

200

150

100

50

0

0

CBCFO

EMFS

g

)

1
–

l

–

–

–

+

+

–

+

+

EMFS (–)

EMFS (+)

8.1×, P < 0.0001

5.8×, P < 0.0001

0

0.5

5

10

50

100

CBCFO-cell ratio (µg per 106 cells)

CBCFO (–)

CBCFO (+)

9.5×, P < 0.0001

0

9

12

15

18

21

0

1

2

3

5

10

Magnetic field (mT)

EMFS time (min)

Fig. 2 | Electromagnetically stimulated ROS production and transgene
expression in transiently transfected cells. a, Schematic illustration of the
magnetoelectric effect of CBCFO nanoparticles and ROS production. b, Magnetic
hysteresis curves of CFO, BCFO and CBCFO at r.t. with magnetic field strengths
ranging from −30 kOe to +30 kOe. c, The on/off behaviour of the OCV induced
by CBCFO nanoparticles depends on the applied a.c. magnetic field (21 mT,
1 kHz). d, Fluorescence-based quantification of cellular ROS levels after EMF
stimulation (21 mT, 1 kHz, 3 min). e, Scheme of the proposed mechanism of
electromagnetically induced gene expression in engineered responsive cells
transfected with pJH1003, pJH1004 and pJH1005. The ROS generated by EMF-
stimulated CBCFO disrupts the interaction between KEAP1 and NRF2, thereby
inhibiting ubiquitination by the KEAP1-associated ubiquitin (Ub) ligase complex.
Consequently, NRF2 translocates to the nucleus, where it binds to small Maf
proteins (sMaf) and to the antioxidant-response elements (ARE) in the regulatory

regions of its target genes. f, SEAP production by transiently transfected
ROS-responsive cells containing CFO, BCFO and CBCFO nanoparticles. g, SEAP
expression is dependent on the CBCFO–cell ratio (magnetic field, 21 mT; 3 min).
h, Electromagnetic-field-dependent gene expression (stimulation time, 3 min).
SEAP expression was maximum at 21 mT, reaching peak levels that compare
to SEAP levels of isogenic cells in which SEAP is driven by a strong constitutive
promoter (149.3 ± 8.7 U l−1). i, Stimulation-time-dependent gene expression
(magnetic field, 21 mT). Data are presented as mean ± s.d., n = 6 (d,g), n = 4 (f) or
n = 3 (h,i) independent experiments. P values in d–i were calculated versus the
corresponding non-stimulated control. Statistical significance was analysed
by one-way ANOVA with Dunnett’s multiple-comparisons test (d), two-way
ANOVA with Bonferroni’s multiple comparisons test (f) and two-way ANOVA with
Dunnett’s multiple comparisons test (g,h,i). Mechanism schematics created with
BioRender.com.

and their polydispersity index reaches 0.190 (Supplementary Fig. 3).
The X-ray diffraction (XRD) patterns revealed the cubic spinel structure
of CFO with an Fd3m space group, and the rhombohedral perovskite
structure of BFO with an R3c space group (Fig. 1c)33,42.

In attenuated total reflectance infrared analysis, the region
between 800 and 1,200 cm−1 shows characteristic absorption of
chitosan saccharide structure (Fig. 1d)43. The chitosan protonation
and hydration processes during coating of CBCFO nanoparticles are
reflected in changes in the asymmetric –NH band between 1,300 and
1,700 cm−1 compared with chitosan powder. The resulting ammonium
groups within the chitosan layer of CBCFO nanoparticles contribute
to the positive surface charge of 31.6 ± 4.6 mV compared with the
negative charge (−22.5 ± 5.5 mV) of BCFO nanoparticles (Fig. 1e and
Supplementary Fig. 4). Cells containing up to 50 μg BCFO or 100 μg
CBCFO per 106 human embryonic kidney cells (HEK-293) retained more
than 95% viability after 48 h (Fig. 1f). These results guided our choice of

concentration range for the following in vitro evaluation. The decrease
in cell viability at higher CBCFO concentrations was directly correlated
with cytosolic accumulation, and presumably resulted from exces-
sive changes in mitochondrial membrane potential which triggered
apoptosis-associated release of cytochrome C (Extended Data Fig. 1).

Electromagnetically induced ROS production in vitro
Under a.c. electromagnetic field stimulation (EMFS), multiferroic
BCFO generates electric polarization due to the interfacial lattice strain
between BFO and CFO44,45. Charge separation of BCFO affords excited
charge carriers on the surface of CBCFO nanoparticles, leading to local
−·) and hydroxyl radi-
production of ROS such as superoxide radical (O2
cal (OH·) in an aqueous environment33 (Fig. 2a). CBCFO nanoparticles
exhibit magnetic hysteresis loops (EMF range, −30 to 30 kOe) under
ambient conditions (Fig. 2b), with a saturation magnetization (Ms)
and remnant magnetization (Mr) of 77.8 and 45.2 emu g−1, respectively,

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1073

Articlehttps://doi.org/10.1038/s41565-025-01929-wOff Off OffOffOff

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

6.2×, P < 0.0001

4

3

2

1

0

0

9

12

15

18

21

EMF (mT)

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

4

3

2

1

0

9.3×, P < 0.0001

0

1

3

5

7

EMFS time (min)

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

EMFS (–)

EMFS (+)

7.9×
<0.0001

8.1×
<0.0001

6.0×
<0.0001

5.5×
0.0199

3.2×
0.8903

1.2×
>0.9999

5

4

3

2

1

0

)

1
–

l

g
u
(
n

i
l

u
s
n

I

5

4

3

2

1

0

EMFS (–)

EMFS (+)

<0.0001

<0.0001

<0.0001

200

150

)

%

EMFS (–)

EMFS (+)

>0.9999

>0.9999

>0.9999

>0.9999

0.0147

0.0022

0.0010

(
y
t
i
l
i

i

b
a
v
l
l
e
C

100

50

0

0

3

6

12

24

36

12 h

24 h

12 h

24 h

12 h

24 h

Time (h)

Day 1

Day 3

Day 5

1

2

3

4

Time (weeks)

Fig. 3 | Electromagnetically stimulated gene expression in microencapsulated
HEKEMPOWER cells. a, Magnetic-field-dependent insulin expression (stimulation
time, 3 min). b, Stimulation-time-dependent insulin expression (magnetic field,
21 mT, 1 kHz). c, Time-dependent insulin production during 36 h after an EMFS
stimulation of 21 mT, 1 kHz, 3 min. Profiling was started immediately after EMF
stimulation. d, Reversibility of insulin production. The cells were alternatively
stimulated with an EMFS of 21 mT for 3 min (on) or unstimulated (off) at 24-h
intervals. The cell culture medium was renewed each time the EMF stimulation

was switched from on-to-off or from off-to-on. e, Viability of HEKEMPOWER following
daily 3-min EMF stimulation for 4 weeks (21 mT, 1 kHz, 3 min per day), compared
with unstimulated HEKEMPOWER cells. All data are presented as mean ± s.d.; n = 6
(a,b) and n = 3 (c,d) independent experiments. P values in a–c were calculated
versus the corresponding non-stimulated control. The induction factors were
calculated between non-stimulated (EMFS (−)) and stimulated (EMFS (+)) groups.
Statistical significance was analysed by two-way ANOVA with Tukey’s test (a,b)
and one-way ANOVA with Dunnett’s multiple comparisons test (c,d).

signifying room-temperature ferromagnetism. The decreased ferromag-
netism of CBCFO derived from BCFO nanoparticles (Ms = 96.8 emu g−1,
Mr = 57.2 emu g−1) is attributable to the content of chitosan. For the fol-
lowing experiments, we employed EMFs of 1 kHz frequency and up to
21 mT field strength to avoid any adverse thermal effect22 in living sys-
tems and to maintain effective coupling of the BFO–CFO interface44.
A Helmholtz-coil-based device was assembled to generate a uniform
a.c. EMF of 9–21 mT in multiwell plates (Supplementary Fig. 5). The
induced electrical potential of CBCFO powder in an open-circuit-voltage
(OCV) set-up (Supplementary Fig. 6a) was measured with an EMF of
1 kHz and 21 mT and reached 0.11 V (Fig. 2c), in contrast with the device
bias control of 0.016 V (Supplementary Fig. 6b). The relative charge
separation was detected by a terephthalic acid (TA) assay depending on
the EMFS strength (Extended Data Fig. 2a,b). The capability of the
charge carriers to induce ROS was evaluated by measuring the non-
specific ROS-mediated decolorization of methylene blue (MB assay,
Extended Data Fig. 2c,d). The degradation rate of 39% with CBCFO
nanoparticles (5 mg ml−1) after 1-h EMFS (1 kHz, 21 mT) indicates a
significant ROS production from CBCFO with EMFS, compared with
bare CBCFO and EMFS-alone control groups.

In vitro quantification showed that intracellular ROS production
was accelerated with CBCFO in contrast to control groups immediately
after 3 min EMFS (1 kHz, 21 mT) (Fig. 2d). The acceleration occurred
mostly within the first 30 min (Extended Data Fig. 3a) and declined in
the following 3–6 h (Extended Data Fig. 3b). We confirmed no signifi-
cant difference in cell viability among stimulated and non-stimulated
groups due to this accelerated ROS production (Extended Data Fig. 3c),
and cell viability started to decrease with only EMFS of 5 min or longer
(Extended Data Fig. 3d).

Electromagnetically controlled transient gene expression
To utilize EMF for gene expression, we cotransfected HEK-293 cells
with constitutive KEAP1 (pJH1004, PhCMV-KEAP1-pA) and NRF2 (pJH1003,
PhCMV-NRF2-pA) expression plasmids to construct a ROS-biosensing sys-
tem, together with the reporter pJH1005 (PDART-SEAP-pA; PDART, OARE-PhCMVmin)
encoding the model human glycoprotein SEAP (human placental secreted
alkaline phosphatase) for quantification of the expression level (Sup-
plementary Table 1). In these cells, electromagnetically induced cellular
ROS production via CBCFO nanoparticles interferes with the NRF2–
KEAP1 interaction, leading to release and translocation of NRF2 to the
nucleus, which results in expression of the protein of interest (POI) from
the NRF2-specific ARE-containing PDART promoter (Fig. 2e). In comparison
with CFO-embedded engineered cells, electromagnetically stimulated
SEAP expression was significantly elevated (13.8-fold) compared with
the non-stimulated control (Fig. 2f). The CBCFO group afforded lower
leakiness and a higher expression level than the BCFO group, in accord-
ance with the higher cellular uptake and improved endosome-escape
capability as judged from time-lapse microscopy images (Extended Data
Fig. 4a,b), fluorescence colocalization (Extended Data Fig. 4c–e) and flow
cytometry (Extended Data Fig. 4f,g). These results can be attributed to
the proton sponge effect of chitosan modification46. Cellular uptake of
CBCFO nanoparticles occurs via classical clathrin-mediated endocytosis
(Extended Data Fig. 5a) and no cellular nanoparticle extrusion occurred
beyond 3 days after cellular uptake (Extended Data Fig. 5b). Leakage
was not observed from implant preparations in 4 weeks, confirming
the integrity of the alginate-based microcapsules (Extended Data Fig. 5c).
The transgene expression level increased with increasing concentra-
tion of CBCFO, peaking at a CBCFO concentration of 50 μg per 106 cells
under an EMF of 21 mT and 1 kHz for 3 min (Fig. 2g), corresponding to

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1074

Articlehttps://doi.org/10.1038/s41565-025-01929-wabcde

b

mm

44.5

Insulin

a

12.829.3

.

0
4
1

.

0
0
1

35.0

c

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

f

1.5

1.0

0.5

0

4

3

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

Isoflurane

Off

On

Off–on–off

On–off–on

0.3207

0.6554

0.9309

<0.0001

<0.0001

<0.0001

50

40

30

20

10

0

e

)

M
m

l

(
e
s
o
c
u
g
d
o
o
B

l

<0.0001

<0.0001

<0.0001

0.2464

d

1.5

Off

On

Off–on–off

On–off–on

<0.0001

<0.0001

<0.0001

0.9732

0.9993

0.9972

)

1
–

l

g
µ
(
n

i
l

u
s
n

I

1.0

0.5

0

40

0

0.5

1

2

3

EMFS time (min)

EMFS (–), WT
Untreated, WT

g

EMFS (+), T1D
EMFS (–), T1D

Untreated, T1D
0.9658

0.8106

0.7178

0.9748

0.4570

0.9359

2

     <0.0001

<0.0001

<0.0001

<0.0001

    0.3928

    0.8330

    0.9266

    0.9998

1

0

1

2

3

4

Time (weeks)

0

3

6

9

0

3

6

9

0

3

6

9

0

3

6

9

Time (days)

Time (days)

EMFS (+), T1D

EMFS (–), WT

h

EMFS (+), T1D

EMFS (–), WT

EMFS (–), T1D
Untreated, T1D

<0.0001

Untreated, WT

<0.0001

<0.0001

<0.0001 <0.0001

)

M
m

l

(
e
s
o
c
u
g
d
o
o
B

l

30

<0.0001

20

10

0

0

0.9894 0.9916

0.5334

0.9424

0.8371

0.5794

7

14

21

28

Time (days)

)

M
m

l

(
e
s
o
c
u
g
d
o
o
B

l

40

30

20

10

0

0

EMFS (–), T1D
Untreated, T1D

Untreated, WT

<0.0001

<0.0001

<0.0001

<0.0001

<0.0001 <0.0001

0.8279

0.4227

0.5740

0.6987

0.8279 0.6214

30

60

90

120

Time (min)

Fig. 4 | In vivo evaluation of HEKEMPOWER cells for wireless-controlled treatment
of T1D. a, Scheme illustrating the magnetic field stimulation of encapsulated
HEKEMPOWER cells implanted in the dorsoventral side of mice, using a centimetre-
sized single-coil device. b, Scheme showing the simultaneous stimulation of
an experimental group of mice with a parallel assembly of single-coil devices.
c, Stimulation-time-dependent tunability of insulin secretion (21 mT, 1 kHz,
0–3 min). d,e, Reversibility of EMF-controlled insulin (d) and blood-glucose (e)
levels. Microencapsulated subcutaneous HEKEMPOWER implants were exposed
to alternating on-to-off and off-to-on EMF stimulation every 3 days (on: 21 mT,
1 kHz, 3 min; off: unstimulated). f,g, Fasting blood-insulin (f) and blood-glucose
(g) levels were recorded before implantation (week 0) and for up to 4 consecutive
weeks after implantation of HEKEMPOWER cells in T1D mice stimulated for 3 min

(21 mT, 1 kHz): EMFS (+) group. T1D and WT mice groups with non-stimulated
HEKEMPOWER cell implants (EMFS (−)), and without implants (untreated) were
used as controls. Over the entire treatment period of 4 weeks fed WT mice
maintained average blood-insulin levels of 2.1 ± 0.8 μg l−1. h, Intraperitoneal GTT
was performed on mice 3 days after implantation of microencapsulated cells and
after fasting for 8 h. Data are presented as mean ± s.d., n = 5 (c–g) and n = 10 (h)
biological replicates. P values in d,e were calculated between the indicated data
and the initial (day 0) unstimulated T1D control. P values in g,h were calculated
versus the corresponding non-stimulated control (black, bottom) and WT
control (green, top). Statistical significance in d–h was analysed with two-way
ANOVA Dunnett’s multiple comparison tests. Mouse schematic illustrations
created with BioRender.com.

1.5 × 104 J s m−3 in volume-averaged energy density. At the CBCFO con-
centration of 50 μg per 106 cells, the SEAP level increased along with
EMF strength (0–21 mT; Fig. 2h). The expression level of SEAP could
be precisely adjusted by varying the EMFS time at 21 mT (Fig. 2i). The
EMPOWER is characterized in HEK-293 cells, known for their convenience
in engineering and their use in biopharmaceutical manufacturing7,41,47,
but it also works in a variety of mammalian cells (Extended Data Fig. 6).

Stimulated insulin release in encapsulated HEKEMPOWER cells
To  construct  the  EMPOWER  system  for  EMF-controlled  insulin
production and release in human cells, we first established stable

HEK-293 cell lines engineered for constitutive expression of KEAP1
(ITR-PhCMV-KEAP1-P2A-BlastR-pA-ITR, pJH1054), NRF2 (ITR-PhCMV-NRF2-
pA:PRPBSA-ECFP-P2A-PuroR-pA-ITR, pJH1101) and NRF2-dependent
expression of insulin (ITR-PDART4-NLuc-P2A-mINS-pA:PmPGK-ZeoR-pA-ITR,
pJH1196; PDART4, OARE4-PhCMVmin). Nanoluciferase (NLuc) was used as a
bioluminescent reporter for screening. The best-in-class monoclonal
cell line, HEKEMPOWER, exhibited ectopic KEAP1 and NRF2 expression
and showed the highest NLuc fold induction (Extended Data Fig. 7).
To customize HEKEMPOWER cells for implantation, they were mixed with
CBCFO nanoparticles and enclosed in clinically licensed alginate micro-
capsules48 to shield the engineered cells from the host immune system

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1075

Articlehttps://doi.org/10.1038/s41565-025-01929-w

while enabling diffusion of nutrients and the release of biopharmaceu-
ticals. The performance of the HEKEMPOWER-containing implants was vali-
dated under a Helmholtz-coil-based uniform EMF. The magnetic field
strength (Fig. 3a) and stimulation time dependence (Fig. 3b) of insulin
production were evaluated. The highest insulin level of 2.76 ± 0.45 μg l−1
was obtained under an EMFS of 21 mT and 3 min, which is consistent
with the results for NLuc expression (Extended Data Fig. 8). A kinetic
study revealed that stimulated insulin production from the HEKEMPOWER
cells reached a significant level in the culture supernatant within 3 h and
was maintained for over 24 h (Fig. 3c). We also confirmed the excellent
reversibility in on/off stimulation patterns at 24-h intervals over 5 days
(Fig. 3d and Extended Data Fig. 8d). Under standard stimulation condi-
tions (1 kHz, 21 mT, 3 min), transgene expression compared favourably
with reported levels of ROS-triggered gene expression49, and daily EMF
exposure (21 mT, 1 kHz, 3 min per day) had no impact on cell viability
during the experimental period of 4 weeks (Fig. 3e), suggesting that
the EMPOWER system was operating at near-optimal performance
(Figs. 2 and 3).

Electromagnetically powered glucose homeostasis in T1D
For in vivo validation, we designed a single-coil EMF generator with
an E-shaped iron core (Fig. 4a). The EMF from this single-coil device
reached 20–22 mT at a plane 3–5 mm from the coil surface, which
matches the depth of subcutaneous implantation in mice. This device
generates a magnetic field gradient rather than the uniform field from
the Helmholtz-coil device. The device was able to stimulate transgene
expression from the encapsulated cells in vitro, and no significant
difference was observed compared with the Helmholtz-coil device
(Supplementary Fig. 7). For in vivo single-coil EMFS, five devices were
fitted into a 3D-printed holder to facilitate parallel stimulation of mice
(Fig. 4b and Supplementary Fig. 8).

The encapsulated HEKEMPOWER cells implanted in T1D mice were
subjected to a 3-min magnetic field stimulation (EMFS (+) T1D group)
using the single-coil devices. Insulin secretion kinetics matched those
found for other transcription-control modalities and the insulin levels
were consistent with those in previous studies using experimental
T1D as a proof-of-concept model (Extended Data Fig. 9)7,12,41,47,50,51.
The insulin secretion levels of HEKEMPOWER could be adjusted by vary-
ing the EMF stimulation time (Fig. 4c) and the glycaemic control was
fully reversible; switching the EMFS from off-to-on or from on-to-off
every 3 days resulted in corresponding changes in insulin (Fig. 4d)
and blood-glucose levels (Fig. 4e). The EMFS-driven secretion of
insulin (Fig. 4f) from the HEKEMPOWER cells attenuated blood-glucose
levels and subsequently maintained normoglycaemia in the T1D
mice (Fig. 4g). Furthermore, EMFS-triggered insulin production
by the HEKEMPOWER cells ameliorated postprandial glycaemic excur-
sions in glucose tolerance tests (GTTs) and restored normoglyca-
emic levels (Fig. 4h). Real-time glycaemic measurements confirmed
that daily stimulation of the HEKEMPOWER cells for 3 min could restore
normoglycaemic levels in T1D mice and maintain glucose homeo-
stasis for at least 4 weeks without any hypoglycaemic excursion. No
significant difference in blood glucose or insulin levels was observed
in non-stimulated wild-type (WT) mice implanted with HEKEMPOWER
cells (EMFS (−) WT group) compared with non-treated WT mice. This
confirms non-leakiness of the EMPOWER system and is consistent
with the absence of hypoglycaemic episodes. At the end of the treat-
ment period, the animals showed no sign of macroscopic (Extended
Data Fig. 10a) or systemic inflammation (Extended Data Fig. 10b–d),
and histological analyses of the implantation site indicated that the
EMPOWER capsules remained in place, intact and unaffected by
EMF stimulation (Extended Data Fig. 10e,f). The body weight gain
(1.5 ± 0.6 g per mouse), daily food intake (6.5 ± 0.8 g per mouse) and
water consumption (7.7 ± 1.6 ml per mouse) of EMF-stimulated T1D
mice were identical to those of WT mice in the terminal phase of the
4-week treatment period.

Conclusions
EMFs represent promising, minimally invasive control modalities for
next-generation gene- and cell-based therapies. First-in-class mag-
netic stimulation methodologies reported so far mostly use mem-
brane channels or receptors conjugated to inorganic nanoparticles
activated by thermal or mechanical coupling8,15,31. However, challenges
still remain associated with receptor and channel functionalization
and intracellular trafficking as well as off-target effects and toxici-
ties, limited robustness, tunability and clinical translation of these
methods22,27,29,30. Instead, our work utilizes modified multiferroic nano-
particles to communicate with cytoplasmic ROS sensors KEAP1/NRF2,
affording a nanoparticle–cell interface to drive transgene expression
via synthetic promoters for wireless electromagnetic cell therapy. To
test this approach, we focused on T1D, one of the dynamically most
challenging chronic diseases, requiring meticulous blood-glucose
control and daily insulin administration. In a T1D mouse model, daily
EMFS (21 mT, 1 kHz, 3 min.) of subcutaneously implanted, microencap-
sulated HEKEMPOWER cells was sufficient to drive transgene expression
of insulin at a level sufficient to produce sustained normoglycaemia.
Our proof-of-concept study successfully restored normoglycaemia
in a mouse model of experimental T1D throughout the 4-week experi-
mental period, demonstrating dynamically robust, reversible and tun-
able in vivo control. The EMPOWER system compared favourably in
performance with established cell-based therapeutic modalities using
chemical7,41,49,52 and physical stimuli12,13 with identical cell-encapsulation
technology, which has been validated for longevity53 and in human
clinical trials48.

The CBCFO nanoparticles used here exhibit efficient coupling
between magnetostrictive and piezoelectric composites45, while
the bio-originated, positively charged polymer chitosan improves
biocompatibility and cell adhesion54. In addition to shielding the bare
ferric oxides from the cellular environment, chitosan also enables the
short-lived ROS generated by the CBCFO nanoparticles to escape from
the endosomes into the cytoplasm via the proton sponge effect46.
Indeed, such multiferroic nanoparticles have been directly injected
into the brain or blood circulation for deep neuron stimulation26,
guided central nervous delivery55 and dissociation of Alzheimer’s
β-amyloid aggregates33. A key advantage of our system is that cellular
stimulation can be triggered at a much lower dose of nanoparticles
(50 μg per 106 cells, over 20 times lower than in the aforementioned
applications)56. The alginate-microencapsulated implants also mini-
mize the risk of liver damage53 associated with the direct adminis-
tration of nanoparticles27. In addition, cellular ROS levels increased
immediately after stimulation and then declined within 3–6 h, and
the KEAP1/NRF2 system recognizes this ROS peak, not a gradual accu-
mulation of ROS14, as typically observed in ROS-signalling systems57.
Such kinetics limit the adverse effect of ROS on HEKEMPOWER cells, as
evidenced by the reversibility of the stimulation of therapeutic
protein expression.

A low-frequency EMF of 1 kHz imposes a negligible magneto-
thermal effect or mechanical force on the cells22. More importantly,
because  even  chemical  ROS  inducers  producing  systemic  ROS
surges have no apparent impact on cell physiology or metabolism14,
EMF-triggered ROS induction confined to the vicinity of intracellular
CBCFO nanoparticles should bear little risk of potential side effects.
Additionally, our work highlights the use of weak EMFs (up to 21 mT),
much weaker than those used in MRI scanners (in the tesla range),
promising safety in clinical use. This level of EMFS can be achieved
by a single induction coil with a fixed coil structure and input param-
eters (akin to wireless phone chargers), and tuned by adjusting a
single parameter, stimulation time, avoiding the need for complex
software or electronic implants. We believe that this kind of interface
between programmable electronic devices and genetic therapies has
the potential to dramatically streamline the treatment regimen for
patients with chronic diseases.

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1076

Articlehttps://doi.org/10.1038/s41565-025-01929-wOnline content
Any methods, additional references, Nature Portfolio reporting sum-
maries, source data, extended data, supplementary information,
acknowledgements, peer review information; details of author contri-
butions and competing interests; and statements of data and code avail-
ability are available at https://doi.org/10.1038/s41565-025-01929-w.

References
1.  Cubillos-Ruiz, A. et al. Engineering living therapeutics with
synthetic biology. Nat. Rev. Drug Discov. 20, 941–960 (2021).
2.  Xie, M. & Fussenegger, M. Designing cell function: assembly of

synthetic gene circuits for cell biology applications. Nat. Rev. Mol.
Cell Biol. 19, 507–525 (2018).

3.  Wang, H., Xie, M., Charpin-El Hamri, G., Ye, H. & Fussenegger, M.

Treatment of chronic pain by designer cells controlled by
spearmint aromatherapy. Nat. Biomed. Eng. 2, 114–123 (2018).

4.  Wang, C.-H. et al. CRISPR-engineered human brown-like
adipocytes prevent diet-induced obesity and ameliorate
metabolic syndrome in mice. Sci. Transl. Med. 12, eaaz8664
(2020).

5.  Zhao, H., Xue, S., Hussherr, M.-D., Teixeira, A. P. & Fussenegger, M.
Autonomous push button controlled rapid insulin release from a
piezoelectrically activated subcutaneous cell implant. Sci. Adv. 8,
eabm4389 (2022).

6.  Yu, Y. et al. Optogenetic-controlled immunotherapeutic designer
cells for post-surgical cancer immunotherapy. Nat. Commun. 13,
6357 (2022).

7.  Bai, P. et al. A fully human transgene switch to regulate

therapeutic protein production by cooling sensation. Nat. Med.
25, 1266–1273 (2019).

8.  Sebesta, C. et al. Subsecond multichannel magnetic control of

select neural circuits in freely moving flies. Nat. Mater. 21, 951–958
(2022).

9.  Maity, D., Guha Ray, P., Buchmann, P., Mansouri, M. & Fussenegger, M.
Blood-glucose-powered metabolic fuel cell for self-sufficient
bioelectronics. Adv. Mater. 35, 2300890 (2023).

10.  Holt, B. A. & Kwong, G. A. Protease circuits for processing
biological information. Nat. Commun. 11, 5021 (2020).

11.  Kuwasaki, Y. et al. A red light-responsive photoswitch for deep
tissue optogenetics. Nat. Biotechnol. 40, 1672–1679 (2022).
12.  Zhao, H. et al. Tuning of cellular insulin release by music for

real-time diabetes control. Lancet Diabetes Endocrinol. 11,
637–640 (2023).

21.  Huang, H., Delikanli, S., Zeng, H., Ferkey, D. M. & Pralle, A. Remote
control of ion channels and neurons through magnetic-field
heating of nanoparticles. Nat. Nanotech. 5, 602–606 (2010).

22.  Romero, G., Park, J., Koehler, F., Pralle, A. & Anikeeva, P.

Modulating cell signalling in vivo with magnetic nanotransducers.
Nat. Rev. Methods Primers 2, 92 (2022).

23.  Perica, K. et al. Magnetic field-induced T cell receptor clustering
by nanoparticles enhances T cell activation and stimulates
antitumor activity. ACS Nano 8, 2252–2260 (2014).

24.  Cheng, K. et al. Magnetic antibody-linked nanomatchmakers for

therapeutic cell targeting. Nat. Commun. 5, 4880 (2014).
25.  Wu, S. et al. Genetically magnetic control of neural system via
TRPV4 activation with magnetic nanoparticles. Nano Today 39,
101187 (2021).

26.  Kozielski, K. L. et al. Nonresonant powering of injectable

nanoelectrodes enables wireless deep brain stimulation in freely
moving mice. Sci. Adv. 7, eabc4189 (2021).

27.  Boey, A. & Ho, H. K. All roads lead to the liver: metal nanoparticles

and their implications for liver health. Small 16, 2000153 (2020).
28.  Gao, C. et al. Biomedical micro-/nanomotors: from overcoming

biological barriers to in vivo imaging. Adv. Mater. 33, 2000512
(2021).

29.  Rennick, J. J., Johnston, A. P. R. & Parton, R. G. Key principles
and methods for studying the endocytosis of biological and
nanoparticle therapeutics. Nat. Nanotech. 16, 266–276 (2021).

30.  Stueber, D. D., Villanova, J., Aponte, I., Xiao, Z. & Colvin, V. L.

Magnetic nanoparticles in biology and medicine: past, present,
and future trends. Pharmaceutics 13, 943 (2021).

31.  Chen, J. C. et al. Self-rectifying magnetoelectric metamaterials

for remote neural stimulation and motor function restoration.
Nat. Mater. 23, 139–146 (2024).

32.  Liu, W. et al. In situ activation of flexible magnetoelectric

membrane enhances bone defect repair. Nat. Commun. 14, 4091
(2023).

33.  Jang, J. & Park, C. B. Magnetoelectric dissociation of Alzheimer’s

β-amyloid aggregates. Sci. Adv. 8, eabn1675 (2022).

34.  Vensaus, P., Liang, Y., Ansermet, J.-P., Soler-Illia, G. J. A. A. &
Lingenfelder, M. Enhancement of electrocatalysis through
magnetic field effects on mass transport. Nat. Commun. 15, 2867
(2024).

35.  Kim, D. et al. Magnetoelectric effect in hydrogen harvesting:

magnetic field as a trigger of catalytic reactions. Adv. Mater. 34,
2110612 (2022).

13.  Krawczyk, K. et al. Electrogenetic cellular insulin release for

36.  Balaban, R. S., Nemoto, S. & Finkel, T. Mitochondria, oxidants, and

real-time glycemic control in type 1 diabetic mice. Science 368,
993–1001 (2020).

14.  Huang, J., Xue, S., Buchmann, P., Teixeira, A. P. & Fussenegger, M.

An electrogenetic interface to program mammalian gene
expression by direct current. Nat. Metab. 5, 1395–1407 (2023).
15.  Abdel Fattah, A. R. et al. Targeted mechanical stimulation via

magnetic nanoparticles guides in vitro tissue development. Nat.
Commun. 14, 5281 (2023).

16.  Lee, J.-U. et al. Non-contact long-range magnetic stimulation of

mechanosensitive ion channels in freely moving animals. Nat.
Mater. 20, 1029–1036 (2021).

aging. Cell 120, 483–495 (2005).

37.  Lennicke, C. & Cochemé, H. M. Redox metabolism: ROS as

specific molecular regulators of cell signaling and function.
Mol. Cell 81, 3691–3707 (2021).

38.  Baird, L. & Yamamoto, M. The molecular mechanisms regulating
the KEAP1-NRF2 pathway. Mol. Cell. Biol. 40, e00099–20 (2020).
39.  Zhang, J. et al. Week-long normoglycaemia in diabetic mice and

minipigs via a subcutaneous dose of a glucose-responsive insulin
complex. Nat. Biomed. Eng. 8, 1214–1225 (2024).

40.  Chen, Z. et al. Synthetic beta cells for fusion-mediated dynamic

insulin secretion. Nat. Chem. Biol. 14, 86–93 (2018).

17.  Choi, S.-H. et al. In vivo magnetogenetics for cell-type-specific

41.  Xie, M. et al. Β-Cell–mimetic designer cells provide closed-loop

targeting and modulation of brain circuits. Nat. Nanotech. 19,
1333–1343 (2024).

18.  Kim, J.-W. et al. Single-cell mechanogenetics using monovalent

magnetoplasmonic nanoparticles. Nat. Protoc. 12, 1871–1889 (2017).

19.  Lee, J.-H. et al. Magnetic nanoparticles for ultrafast mechanical

control of inner ear hair cells. ACS Nano 8, 6590–6598 (2014).
20.  Tay, Z. W. et al. Magnetic particle imaging-guided heating in vivo
using gradient fields for arbitrary localization of magnetic
hyperthermia therapy. ACS Nano 12, 3699–3713 (2018).

glycemic control. Science 354, 1296–1301 (2016).

42.  Bae, I.-T. et al. Elucidation of crystal and electronic structures

within highly strained BiFeO3 by transmission electron microscopy
and first-principles simulation. Sci. Rep. 7, 46498 (2017).
43.  Branca, C. et al. Role of the OH and NH vibrational groups in

polysaccharide–nanocomposite interactions: a FTIR-ATR study on
chitosan and chitosan/clay films. Polymer 99, 614–622 (2016).
44.  Huang, Z. et al. Interface engineering and emergent phenomena

in oxide heterostructures. Adv. Mater. 30, 1802439 (2018).

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1077

Articlehttps://doi.org/10.1038/s41565-025-01929-w45.  Li, Y. et al. Magnetoelectric quasi-(0–3) nanocomposite

heterostructures. Nat. Commun. 6, 6680 (2015).

46.  Richard, I., Thibault, M., De Crescenzo, G., Buschmann, M. D. &
Lavertu, M. Ionization behavior of chitosan and chitosan–DNA
polyplexes indicate that chitosan has a similar capability to
induce a proton-sponge effect as PEI. Biomacromolecules 14,
1732–1740 (2013).

47.  Mansouri, M. et al. Smart-watch-programmed green-light-
operated percutaneous control of therapeutic transgenes.
Nat. Commun. 12, 3388 (2021).

48.  Jacobs-Tulleneers-Thevissen, D. et al. Sustained function of

alginate-encapsulated human islet cell implants in the peritoneal
cavity of mice leading to a pilot study in a type 1 diabetic patient.
Diabetologia 56, 1605–1614 (2013).

49.  Huang, J., Xue, S., Teixeira, A. P. & Fussenegger, M. A gene-switch
platform interfacing with reactive oxygen species enables
transcription fine-tuning by soluble and volatile pharmacologics
and food additives. Adv. Sci. 11, 2306333 (2024).

50.  Bertschi, A. et al. Controlling therapeutic protein expression

via inhalation of a butter flavor molecule. Nucleic Acids Res. 51,
e28–e28 (2023).

51.  Ye, H., Baba, M. D.-E., Peng, R.-W. & Fussenegger, M. A synthetic
optogenetic transcription device enhances blood-glucose
homeostasis in mice. Science 332, 1565–1568 (2011).

52.  Shao, J. et al. Engineered poly(A)-surrogates for translational

regulation and therapeutic biocomputation in mammalian cells.
Cell Res. 34, 31–46 (2024).

53.  Lai, J. et al. Alginate-based encapsulation fabrication technique

for drug delivery: an updated review of particle type, formulation
technique, pharmaceutical ingredient, and targeted delivery
system. Pharmaceutics 16, 370 (2024).

54.  Kou, S., Peters, L. M. & Mucalo, M. R. Chitosan: a review of sources
and preparation methods. Int. J. Biol. Macromol. 169, 85–94
(2021).

55.  Kaushik, A. et al. Magnetically guided central nervous system

delivery and toxicity evaluation of magneto-electric nanocarriers.
Sci. Rep. 6, 25309 (2016).

56.  Feliu, N. et al. Nanoparticle dosage—a nontrivial task of

utmost importance for quantitative nanosafety research. Wiley
Interdiscip. Rev. Nanomed. Nanobiotechnol. 8, 479–492 (2016).
57.  Murphy, M. P. et al. Guidelines for measuring reactive oxygen

species and oxidative damage in cells and in vivo. Nat. Metab. 4,
651–662 (2022).

Publisher’s note Springer Nature remains neutral with regard to
jurisdictional claims in published maps and institutional affiliations.

Open Access This article is licensed under a Creative Commons
Attribution 4.0 International License, which permits use, sharing,
adaptation, distribution and reproduction in any medium or format,
as long as you give appropriate credit to the original author(s) and the
source, provide a link to the Creative Commons licence, and indicate
if changes were made. The images or other third party material in this
article are included in the article’s Creative Commons licence, unless
indicated otherwise in a credit line to the material. If material is not
included in the article’s Creative Commons licence and your intended
use is not permitted by statutory regulation or exceeds the permitted
use, you will need to obtain permission directly from the copyright
holder. To view a copy of this licence, visit http://creativecommons.
org/licenses/by/4.0/.

© The Author(s) 2025

Nature Nanotechnology | Volume 20 | August 2025 | 1071–1078

1078

Articlehttps://doi.org/10.1038/s41565-025-01929-wMethods
Fabrication of CBCFO
CFO nanoparticles were synthesized according to the literature with
modifications33. To prepare CFO nanoparticles, iron(III) chloride hexa-
hydrate (0.995 g) and cobalt(II) chloride (0.239 g) were mixed in deion-
ized water (35 ml) containing hexadecyltrimethylammonium bromide
(2.041 g). Sodium hydroxide solution (6 M) was then added dropwise to
the mixture under continuous stirring to achieve a final pH of 11.0. After
ultrasound stimulation for 30 min, additional hydrothermal treatment
was applied to the mixture at 180 °C for 24 h in a 50-ml Teflon-lined
stainless-steel autoclave. The resulting black precipitates were washed
with deionized water and ethanol several times after cooling to room
temperature.

To synthesize BCFO magnetoelectric nanoparticles, a sol–gel
treatment was applied to the as-prepared CFO nanoparticles33. Briefly,
CFO nanoparticles (50 mg) were dispersed into 30 ml ethylene glycol
(catalogue number 324588, Sigma-Aldrich) containing bismuth(III)
nitrate pentahydrate (0.160 g) and iron(III) nitrate nonahydrate
(0.121 g). After 2 h of sonication, the sol mixture was moved to a vac-
uum oven and dried for 24 h. Next, the resulting gel-state mixture was
preheated at 400 °C for 30 min to eliminate organic compounds and
successively calcined at 500 °C for 90 min. The resulting BCFO nano-
particles were washed several times with deionized water and ethanol
on a nylon membrane and collected with a neodymium permanent
magnet after ultrasound treatment.

Chitosan (catalogue number 448877-50 G, Sigma-Aldrich) was first
dissolved in 0.1-M NaCl to form a 0.1% solution after acidification with
1% acetic acid. Rhodamine B isothiocyanate (RITC)-labelled chitosan
was prepared by dissolving RITC (40 μM, catalogue number CAY20653-
100 mg, Cayman) in methanol and mixing it 1:1 with a 10 mg ml−1
chitosan solution under nitrogen protection, followed by dialysis
against 0.1-M NaCl. The prepared BCFO nanoparticles were then
dispersed and mixed in the chitosan solution (5 mg ml−1) by sonication
for 1 h. The CBCFO nanoparticles were collected by centrifugation
and washed with water three times. RITC-CBCFO nanoparticles were
fabricated by mixing BCFO nanoparticles with RITC-labelled chitosan.
For cellular uptake, all nanoparticles were sonicated at 35 kHz for
30 min (Bandelin Electronic, RK100H) and filtered through a 0.22-μm
filter (catalogue number P668.1, Carl Roth).

Characterization of CBCFO
The morphology of the obtained CFO, BCFO and CBCFO nanoparticles
was examined by TEM (FEI F30) and STEM ( JEM-F200). The distribution
of elements along the nanoparticles was studied by STEM EDX mapping
( JEM-F200). The crystallographic structure of the nanostructures was
analysed by XRD on a Bruker AXS D8 Advance 1 X-ray diffractometer,
equipped with a copper target at a wavelength of 1.542 Å. The magnetic
properties were evaluated by scanning probe microscopy (Bruker
Dimension ICON) according to the magnetic force model. The zeta
potential and the hydrodynamic size of samples were measured by
a dynamic light scattering Zetasizer (Malvern, ZEN3600) in DPBS
(0.01 M, pH 7.4). Relative charge separation and ROS induction from
nanoparticles were evaluated by TA assay (3 mM, λex/λem = 310/430 nm)
and MB assay (5 mM, λabs = 664 nm), respectively, using a plate reader
(Tecan, Spark Reader). For TA and MB assays, an aqueous solution
(400 μl) containing different nanoparticles was exposed to a magnetic
field under constant agitation, and 100-μl aliquots of the supernatant
were transferred to 96-well plates for colorimetric or fluorometric
measurement.

Magnetic field stimulation
Electromagnet-containing 3D-printed holders (Supplementary Figs. 5a
and 8c) were designed to minimize the thermal effect on biological
systems. Samples were exposed to a uniform EMF by placing them in
the central area (5.8 cm × 5.8 cm) of a Helmholtz-coil-based device.

Nature Nanotechnology

The circuits (Supplementary Fig. 5c) for magnetic field stimulation
were powered by custom-designed electrical drivers. The field strength
generated by the Helmholtz-coil device was 9–21 mT and that generated
by the single-coil device was 20–22 mT at a plane of 0.3–0.5 cm from the
coil, with the frequency fixed at 1 kHz (sinusoidal). The amplitude of
the applied alternating magnetic field was confirmed by a gaussmeter.

Cell culture and engineering
Cell culture. Human embryonic kidney cells (HEK-293, ATCC, CRL-
11268), human telomerase-immortalized mesenchymal stem cells
(hMSC-TERT, RRID: CVCL_Z015), human liver cancer cell line (HepG2,
ATCC, CRL-11997), Chinese hamster ovary cells (CHO-K1, ATCC, CCL-61),
baby hamster kidney cells (BHK-21, ATCC, CCL-10) and mouse pituitary
tumour cells (AtT-20, ATCC, CCL-89), were cultivated in Dulbecco’s
modified Eagle’s medium (DMEM, catalogue number 52100-39, Thermo
Fisher Scientific) supplemented with 100 mM proline (CHO-K1 only),
10% fetal bovine serum (FBS, catalogue number F7524, Sigma-Aldrich)
and 1% (v/v) streptomycin/penicillin (catalogue number L0022, Bio-
west) at 37 °C in a humidified atmosphere containing 5% CO2.

Cell transfection. For transfection, 104 cells (CellDrop BF Brightfield
Cell Counter, DeNovix) were seeded per well in a 96-well plate (cata-
logue number 3599, Corning Life Sciences) 24 h before transfection
by addition of 20 μl of a mixture containing 0.3 μg polyethyleneimine
(PEI MAX, mol. wt 40,000, 1 μg μl−1 in double-distilled H2O, catalogue
number 24765-2, Polysciences) and 0.1 μg plasmid DNA (equimolar
concentrations for plasmid mixtures) per well. After 8 h, the mixture
was replaced with a standard cultivation medium or nanoparticle
medium suspension (100 μl) for further characterization.

Monoclonal cell line construction. HEK-293 cells (1.5 × 105) were
cotransfected with pJH1101 (ITR-PhCMV-NRF2-pA: PRPBSA-ECFP-P2A-
PuroR-pA-ITR) (200 ng), pJH1054 (ITR-PhCMV-KEAP1-P2A-BlastR-pA-ITR)
(550 ng),  pJH1096  (ITR-P ARE-NLuc-P2A-mINS:PmPGK-ZeoR-pA-ITR)
(400 ng) and pJH42 (PhCMV-SB100X-pA) encoding constitutive expres-
sion of a hyperactive Sleeping Beauty (SB) transposase (200 ng)58.
After selection for two passages in culture medium supplemented
with 2.5 μg ml−1 puromycin, 300 μg ml−1 blasticidin and 300 μg ml−1
zeocin, the resistant polyclonal population was divided by ECFP-
based FACS-mediated single-cell sorting into 48 monoclonal cell
lines. Twelve monoclonal cell lines with the highest ECFP-based
fluorescence  intensity  were  loaded  with  CBCFO  nanoparticles
(50 μg per 106 cells) and stimulated by EMF (1 kHz, 21 mT, 3 min).
HEKEMPOWER (clone number 3), showing best-in-class EMF-stimulated
transgene-fold induction, was chosen for further studies (Extended
Data Fig. 7a).

Microencapsulation and implantation of HEKEMPOWER cells
To protect HEKEMPOWER cells from the mouse immune system while per-
mitting the exchange of nutrients and release of therapeutic proteins,
we used a clinical trial-validated alginate-based encapsulation techno-
logy48. HEKEMPOWER cells were encapsulated in alginate/poly(l-lysine)/
alginate microcapsules with a diameter of 400 μm by treating a mixture
of 9.0 × 107 cells with 18 ml alginate (w/v, 1.6%; Na-alginate, catalogue
number 71238, Sigma-Aldrich) in an encapsulator (Inotech Encapsu-
lator IE-50R, EncapBiosystems) equipped with a 200-μm nozzle. A
20-ml syringe was operated at a flow rate of 20 ml min−1 with a vibration
frequency of 1.2 kHz and 1.2 kV voltage for bead dispersion. A 100-ml
poly(l-lysine) 2000 (w/v, 0.05%; catalogue number 25988-63-0, Ala-
manda Polymers) solution and a 100-ml 0.03% alginate solution were
sequentially used to form the microcapsules. For delivery, 2.5 × 106
encapsulated cells in 0.5 ml serum-free DMEM were subcutaneously
implanted through a 3-ml syringe (catalogue number 9400038, Bec-
ton Dickinson) with a 0.7-mm × 30-mm needle (catalogue number
30382903009009, Becton Dickinson).

Articlehttps://doi.org/10.1038/s41565-025-01929-wAnimal experiments
Preparation of experimental mouse models. C57BL/6JRJ mice were
kept and monitored in groups (n = 5) in an environment controlled at
21 ± 2 °C and 55 ± 10% humidity and maintained under a 12-h reverse
light–dark cycle, with free access to standard diet and water. All
procedures were performed in compliance with Swiss animal wel-
fare regulations, approved by the Veterinary Office of the Canton
Basel-Stadt, Switzerland (license number 2996_34477), the French
Republic (project number DR2018-40v5 and APAFIS number 16753)
and the People’s Republic of China (Institutional Animal Care and Use
Committee of Westlake University, protocol ID20-009-XMQ). The
experiments were conducted by P.G.R. (license number LTK 5507),
G. Charpin-El Hamri (number 69266309; University of Lyon, Institut
Universitaire de Technologie) or by S. Xue (Westlake University). Two
groups of mice were utilized: WT and experimentally induced T1D mice.
To induce the T1D condition, male WT mice (8–9 weeks old, 18–23 g)
were intraperitoneally injected with streptozotocin (STZ; 75 mg kg−1,
0.2 M citrate buffer, pH 4.2; Sigma-Aldrich, catalogue number S0130)
for 4 consecutive days following a 6-h fasting period59. Control WT
mice from Janvier Labs (18–23 g) received identical injections without
STZ. At 10 days after the final injection of STZ, fasting blood-glucose
levels were measured using ContourNext test strips and a ContourNext
ONE reader (Ascensia Diabetes Care; catalogue numbers 84191451 and
85659367) to confirm persistent hyperglycaemia and T1D status in the
STZ-treated group.

Experimental procedure. Microencapsulated HEKEMPOWER cells with
CBCFO  nanoparticles  (50 μg  per  106  cells)  were  subcutaneously
implanted in the experimental and control groups. The hair on the
dorsoventral side of the mice was completely shaved, and the animals
were anaesthetized with 4% isoflurane and maintained under 2%
isoflurane during surgery. Microencapsulated HEKEMPOWER cells were
injected subcutaneously (0.5 ml DMEM, 5 × 106 cells) on the dorsoven-
tral side using a 5-ml syringe with a 21-gauge needle to reduce the risk of
aseptic loosening. After a 24-h stabilization period, the HEKEMPOWER cells
were wirelessly stimulated using a portable (single-coil-based) device
(Fig. 4b) for 3 min once every 24 h in the EMFS (+) group. For the rest of
each day, treated animals were not restrained. The single-coil devices
(n = 5) were fitted into a 3D-printed holder (Supplementary Fig. 8d) and
a rectangular tunnel (with five parallel holes, Supplementary Fig. 8b)
was used to maximize efficiency and facilitate parallel experiments. The
animals were fasted for 6 h before measuring blood-glucose and insulin
levels. For the GTT experiment, treated animals were intraperitoneally
injected with 1.5 g kg−1 glucose and glycaemia was recorded at regular
intervals over 2 h. Real-time blood-glucose monitoring was performed at
regular time points over a period of 4 weeks after a fasting period of 6 h.
Alongside glycaemic levels, the corresponding blood insulin levels were
also measured and compared with those of untreated WT and T1D groups.

Blood collection. The level of blood glucose was monitored peri-
odically using ContourNext test strips and a ContourNext ONE reader
(catalogue numbers 84191451 and 85659367, Ascensia Diabetes Care)60.
Blood insulin levels were assessed in serum samples collected in Micro-
tainer serum separator tubes (centrifuged at 6,000g for 10 min at 4 °C;
catalogue number 365967, Becton Dickinson) with an ultrasensitive
ELISA assay (catalogue number 10-1247-01, Mercordia).

Histology. Microencapsulated HEKEMPOWER and surrounding tissue
were explanted from EMF-stimulated and unstimulated mice and
fixed overnight in 10% buffered formalin (100 ml 40% formalin, 900 ml
double-distilled H2O, 4 g l−1 NaH2PO4, 6.5 g l−1 Na2HPO4, pH 7). The tissue
samples were trimmed, dehydrated in increasing concentrations of
ethanol, cleared with xylene, embedded in paraffin wax, processed into
5-μm slices using an EXAKT 300 CP system (EXAKT Technologies) and
stained with haematoxylin and eosin. The tissue sections were analysed

Nature Nanotechnology

by light microscopy (Olympus CKX53) and images were acquired with
an Olympus DP75 camera.

Statistics and reproducibility
The data presentation, sample size of biological replicates (n), statis-
tical analysis and significance of differences are shown in the figure
legends. All in vitro experiments were repeated at least twice unless
otherwise stated. For the mouse experiments, biological replicates
(n = 5 mice per group) were randomly assigned to different experi-
mental groups. The details are described in each figure legend. To
determine the statistical significance of differences in the case of
multiple comparisons we used GraphPad Prism 10 (v.10.1.0, GraphPad
Software) and a two-tailed, unpaired, Student’s t-test and one-way or
two-way analysis of variance (ANOVA). No statistical methods were
used to prespecify sample sizes, but our sample sizes are the same as
previously reported12,14. Data distribution was assumed to be normal,
but was not formally tested. All investigators involved in this study were
blinded to group allocation during data collection and analysis. No
animals or data points were excluded from the analyses for any reason.

Reporting summary
Further information on research design is available in the Nature
Portfolio Reporting Summary linked to this article.

Data availability
All data supporting the findings of this study are presented in the
paper and the Supplementary Information. Source data are provided
with this paper.

References
58.  Mátés, L. et al. Molecular evolution of a novel hyperactive

Sleeping Beauty transposase enables robust stable gene transfer
in vertebrates. Nat. Genet. 41, 753–761 (2009).

59.  Furman, B. L. Streptozotocin-Induced diabetic models in mice

and rats. Curr. Protoc. 1, e78 (2021).

60.  Christiansen, M. et al. A new, wireless-enabled blood glucose

monitoring system that links to a smart mobile device: accuracy
and user performance evaluation. J. Diabetes Sci. Technol. 11,
567–573 (2017).

Acknowledgements
This work was financially supported through a European Research
Council advanced grant (ElectroGene, number 785800) and in
part by the Swiss National Centre of Competence in Research
(NCCR) for Molecular Systems Engineering. We are grateful to
G. Charpin-El-Hamri, M. Xie and S. Xue for generous advice and
support in animal experimentation.

Author contributions
Z.L. and M.F. designed the project. Z.L. and P.B. conducted
device fabrication and electrical characterization and the in vitro
experiments. Z.L., P.G.R., J.H. and M.F. designed the experiments
and analysed the results. P.G.R. performed the animal experiments.
Z.L., P.G.R., J.H. and M.F. wrote the paper.

Funding
Open access funding provided by Swiss Federal Institute of
Technology Zurich.

Competing interests
The authors declare no competing interests.

Additional information
Extended data is available for this paper at
https://doi.org/10.1038/s41565-025-01929-w.

Articlehttps://doi.org/10.1038/s41565-025-01929-wSupplementary information The online version
contains supplementary material available at
https://doi.org/10.1038/s41565-025-01929-w.

Peer review information Nature Nanotechnology thanks Victoria
Cogger and the other, anonymous, reviewer(s) for their contribution to
the peer review of this work.

Correspondence and requests for materials should be addressed to
Martin Fussenegger.

Reprints and permissions information is available at
www.nature.com/reprints.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 1 | Impact of CBCFO nanoparticle concentration and EMFS
on mitochondrial membrane potential (MMP) and cytochrome C release.
(a) Relationship between MMP and CBCFO nanoparticle concentration 24 h after
addition. (b) CBCFO nanoparticle concentration-dependent MMP 24 h after
EMF stimulation (21 mT, 1 kHz, 3 min). (c) EMFS time-dependent MMP by CBCFO
nanoparticles (50 μg/106 cells) 24 h after EMFS (21 mT, 1 kHz, 0–5 min).

(d) Western blot-based analysis of cytochrome C release from mitochondria
24 h after addition of different concentrations of CBCFO nanoparticles
(0–500 μg/106 cells). Vinculin was used as a loading control. All data are presented
as means ± s.d.; n = 6 independent experiments. Statistical significance
was analysed by one-way ANOVA with Tukey’s multiple comparisons test in (a)
and two-way ANOVA with Dunnett’s multiple comparisons test in (b, c).

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 2 | Quantification of charge carriers and ROS. (a) The
mechanism of TA assay to detect charge carriers. (b) The mean fluorescence
intensities (MFI) show the magnetic-field-dependent generation of
2-hydroxyterephthalic acid. (c) The mechanism of MB assay to detect ROS

production in the aqua-based environment. (d) Decrease of MB induced by CBCFO
and EMFS, measured in terms of the absorbance at 664 nm. All data are presented
as means ± s.d.; (b, d) n = 3 independent experiments. Statistical significance was
analysed by one-way ANOVA with Tukey’s multiple comparisons test in (b, d).

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 3 | In vitro ROS production stimulated by the magnetic
field. (a) Significantly increased production of ROS over 30 min in HEK-293
cells with CBCFO after EMFS (1 kHz, 21 mT, 3 min). (b) Accumulated ROS in the
cells reached a maximum at about 6 h after stimulation in (a). All groups show
similar increases in ROS production at 12 h after stimulation. Percent mean
fluorescence intensity (MFI %) represents the mean fluorescence intensity

normalized to blank assay fluorescence. (c) Cell viability 72 h after EMF
stimulation. (d) EMF stimulation-time-dependent cell viability (21 mT, 1 kHz,
0–10 min). All data are presented as means ± s.d.; n = 4 independent experiments.
Statistical significance was analysed by one-way ANOVA with Dunnett’s multiple
comparisons test in (c, d).

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 4 | Endosome escape behaviour. Representative
fluorescence microscopy images of HEK-293 cells incubated with RITC
(Ex/Em: 531/593, red)-labelled (a) CBCFO and (b) BCFO nanoparticles for 12, 24
and 48 h. For co-localization analysis, lysosomes (Lyso tracker green, Ex/Em:
466/495, green) and nuclei (Hochst-33342, Ex/Em: 387/409, blue) were labelled.
The region of interest (ROI, white) was derived from the bright-field images.
Pearson’s correlation coefficient (PCC) was calculated from the co-localization

results between lysosomes and (c) CBCFO, (d) BCFO nanoparticles. Statistical
quantification (e) shows enhanced endosome escape of CBCFO nanoparticles
from the lysosomes. Flow-cytometric analysis of cells incubated with (f) CBCFO
and (g) BCFO nanoparticles confirmed the endosome escape behaviour. In all
these experiments, CBCFO nanoparticles are applied as 50 μg/106 cells. All data
are presented as means ± s.d.; n = 5 independent experiments.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 5 | Endocytosis and cellular extrusion of CBCFO
nanoparticles. (a) Impact of CBCFO nanoparticle endocytosis inhibition on
EMF-stimulated SEAP expression. Inhibition of classical clathrin-mediated
endocytosis by chlorpromazine decreases endocytosis-mediated uptake of
CBCFO nanoparticles, reduces EMF-triggered ROS-production and attenuates
ROS-induced SEAP expression. (b, c) Fluorescence-based extrusion of rhodamine

B isothiocyanate-labelled CBCFO nanoparticles (50 mg/106 cell) from native (b)
and microencapsulated (c) HEKEMPOWER cells. Fluorescence intensity (I) (b, c) was
normalized to DMEM fluorescence (I0). Data are presented as means ± s.d.; n = 5
(a); n = 3 (b, c) independent experiments. Statistical significance was analysed by
two-way ANOVA with Dunnett’s test.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 6 | EMF-controlled SEAP expression in various mammalian
cell types. 104 hMSC-TERT (human), HepG2 (human), CHO-K1(hamster), BHK-
21 (hamster), and AtT-20 (mouse) cells were co-transfected with EMPOWER
vectors pJH1003, pJH1004 and pJH1005, loaded with CBCFO nanoparticles

(50 μg/106 cells) and optionally stimulated by EMF (21 mT, 1 kHz, 3 min). All
data are presented as means ± s.d.; n = 6 independent experiments. Statistical
significance was calculated by two-way ANOVA with Dunnett’s multiple
comparisons test.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 7 | Screening of monoclonal HEK-293 cell lines based on
NLuc expression in response to electromagnetic stimulation. (a) The EMPOWER
system is based on the constitutive expression of KEAP1 (ITR-PhCMV-KEAP1-P2A-
BlastR-pA-ITR, pJH1054) and NRF2 (ITR-PhCMV-NRF2-pA: PRPBSA-ECFP-P2A-
PuroR-pA-ITR, pJH1101), and four-tandem ARE (DART4)-controlled NLuc
reporter followed by mouse insulin (mINS) (ITR-PDART4-NLuc-P2A-mINS:

PmPGK-ZeoR-pA-ITR, pJH1196). All the constructs are flanked by inverted
terminal repeats (ITR) for SB100X-based Sleep Beauty transposase recognition.
CBCFO concentration was fixed at 50 μg/106 cells. Electromagnetic stimulation:
1 kHz, 21 mT, 3 min. All data are presented as means ± s.d.; n = 2 independent
experiments. Western blot analysis of KEAP1 (b) and NRF2 (c) levels in parental
(HEK-293) and HEKEMPOWER cells. Vinculin was used as a loading control.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 8 | NLuc expression of encapsulated HEKEMPOWER cells. (a)
Field-strength-dependent NLuc expression (1 kHz, 3 min). (b) Stimulation-time-
dependent NLuc expression (1 kHz, 21 mT). (c) Time-dependent expression over
36 h (1 kHz, 21 mT, 3 min). (d) Reversible expression (1 kHz, 21 mT, 3 min). The
CBCFO concentration was fixed at 50 μg/106 cells. P values and fold changes in

(a, b, c) were calculated versus the corresponding non-stimulated control. All
data are presented as means ± s.d.; (a and b) n = 6; (c) n = 3; (d) n = 4 independent
experiments. Statistical significances were calculated via two-way ANOVA
Dunnett’s multiple comparison tests.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 9 | EMF-stimulated blood-insulin levels in type-1 diabetic
mice. Type-1-diabetic mice implanted with microencapsulated HEKEMPOWER cells
were stimulated with EMF (21 mT, 1 kHz, 3 min). Blood insulin reached wild-type
levels within 12 h. Data are presented as mean ± s.d., n = 5 biological replicates.

Statistical significance of differences between EMF-stimulated and unstimulated
control groups was analysed by two-way ANOVA with Dunnett’s multiple
comparisons test.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-wExtended Data Fig. 10 | Impact of subcutaneous EMPOWER implants in
mice. (a) Pictures of the implantation site of a representative T1D mouse
subcutaneously implanted with the EMPOWER system and treated for four weeks
with daily EMF stimulation (21 mT, 1 kHz, 3 min). The implant site is encircled
and does not show any macroscopic signs of inflammation. (b, c) Histological
analyses of tissue sections around the implant site of EMF-stimulated (b) and
unstimulated (c) T1D mice. Microcapsules containing HEKEMPOWER cells are

indicated with arrows. Scale bar, 100 μm. (d-f) Profiling of key inflammatory
cytokines, IL-6 (d), TNF-α (e) and IFN-γ (f), in the bloodstream of T1D mice four
weeks after implantation of the EMPOWER system and daily EMF stimulation
(21 mT, 1 kHz, 3 min). All data are presented as means ± s.d.; n = 5 biological
replicates. Statistical significance was analysed by two-way ANOVA with
Dunnett’s multiple comparisons test.

Nature Nanotechnology

Articlehttps://doi.org/10.1038/s41565-025-01929-w