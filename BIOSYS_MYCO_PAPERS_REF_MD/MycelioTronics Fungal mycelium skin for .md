M A T E R I A L S   S C I E N C E

MycelioTronics: Fungal mycelium skin for
sustainable electronics
Doris Danninger1,2†, Roland Pruckner1,2†, Laura Holzinger3,
Robert Koeppe1,4, Martin Kaltenbrunner1,2*

Electronic devices are irrevocably integrated into our lives. Yet, their limited lifetime and often improvident dis-
posal demands sustainable concepts to realize a green electronic future. Research must shift its focus on substi-
tuting nondegradable and difficult-to-recycle materials to allow either biodegradation or facile recycling of
electronic devices. Here, we demonstrate a concept for growth and processing of fungal mycelium skins as biode-
gradable substrate material for sustainable electronics. The skins allow common electronic processing techniques
including physical vapor deposition and laser patterning for electronic traces with conductivities as high as 9.75 ±
. The conformal and flexible electronic mycelium skins withstand more than 2000 bending cycles
1.44 × 10
and can be folded several times with only moderate resistance increase. We demonstrate mycelium batteries with
 used to power autonomous sensing devices including a Bluetooth module
capacities as high as ~3.8 mAh cm
and humidity and proximity sensor.

4
 S cm

−2

−1

Copyright © 2022
The Authors, some
rights reserved;
exclusive licensee
American Association
for the Advancement
of Science. No claim to
original U.S. Government
Works. Distributed
under a Creative
Commons Attribution
NonCommercial
License 4.0 (CC BY-NC).

INTRODUCTION
Wearable and untethered electronics are increasingly accessible to
various fields, with applications ranging from robotics to medical
applications and consumer electronics (1–3). The vast number of
devices produced every day along with the decrease of their lifetime
inevitably results in the generation of enormous amounts of elec-
tronic waste (4). Circular economy and recycling concepts alone
cannot solve the growing waste crisis. Electronics research, and es-
pecially electronic materials research, thus must shift its focus from
strictly high-functionality concepts to sustainable, cost-effective ap-
proaches (5, 6). Wearable devices are designed to function in close
interaction with their user, combining conventional electronics such
as transistors with sensors allowing the collection of a plethora of
signals (7). Fabricating such smart devices with sustainable materials,
however, is still a challenge. Carbon biomaterials including carbon
nanotubes and graphene are promising due to their excellent elec-
tronic and mechanical characteristics and may lead to a new class of
electronics, yet the majority of reported devices still incorporate un-
sustainable substrates (8–11). Li et al. (12), for instance, not only
demonstrate carbonized cotton sensors with good sensing perfor-
mance but also include the silicone-based elastomer polydimethyl-
siloxane in their composite. However, to realize truly sustainable
electronics, every component of a device must be substituted with
environmentally benign alternatives. Integrated circuits (ICs) make
up the majority of the total mass of printed circuit boards (PCBs),
due to the high density of the metals used, yet biodegradable ver-
sions of such are difficult to realize. Conventional PCBs of mobile
phones, for instance, consist of 63 weight % (wt %) metals, 24 wt %
ceramics, and 13 wt % polymers (13). Reported works on biode-
gradable ICs are based on biomass and plant-based materials, yield-
ing entirely transient electronics including degradable circuit elements

1Division of Soft Matter Physics, Institute for Experimental Physics, Johannes Kepler
University, Altenberger Str. 69, Linz 4040, Austria. 2Soft Materials Lab, Linz Institute
of Technology, Johannes Kepler University, Altenberger Str. 69, Linz 4040, Austria.
3Institute of Polymer Science, Johannes Kepler University, Altenberger Str. 69, Linz
4040, Austria. 4Sendance GmbH, Pulvermühlstr. 3, Linz A-4040, Austria.
*Corresponding author. Email: martin.kaltenbrunner@jku.at
†These authors contributed equally to this work.

(14, 15). These, although promising, exhibit still limited perfor-
mance, durability, and, hence, applicability. With the substrate be-
ing the second major contributor to the total mass of a PCB (37 wt %),
developing  biodegradable  alternatives  of  such  serves  as  a  viable
route for sustainable electronics (13, 16). By combining conven-
tional (eventually reusable) ICs with a biodegradable substrate in-
stead of hard to recycle polymers and plastics, e-waste can already
be reduced markedly. Flexible PCBs on paper substrates demon-
strate the feasibility of combining nondegradable IC components
with a new class of substrates (17–19). Cellulose nanofibril paper
allows processing of sophisticated electronics as, for example, gallium
arsenide microwave devices on its surface (20, 21). However, the pro-
duction process of paper is resource intensive, requiring, on aver-
age, 300 million liters of water and 33.76 GJ energy per ton and
involves the use of large amounts of toxic acids, solvents, and bases
in the process (22). We herein propose a new electronic substrate
material as an alternative, a fungal mycelium “skin” based on a sap-
rophytic fungus Ganoderma lucidum growing naturally on dead
hardwood in mild temperate climates (Fig. 1A) (23, 24). We report
on a method for its efficient and scalable growth and harvest and its
use in a new approach toward flexible and biodegradable electronics
called MycelioTronics. Pure fungus mycelium exhibits promising
properties, closer to high-performance polymer microfoams than to
other as-grown biomaterials, and environmentally benign post-
treatment  procedures  allow  tuning  of  mechanical  properties
(25, 26). Our material, being entirely biodegradable, therefore ren-
ders the replacement of fossil-based and heavily processed com-
ponents of electronics feasible (27). We couple our fungus material
with conventional nondegradable circuit components, achieving
high-functionality electronic devices without sacrificing sustain-
ability (Fig. 1B). To date, combinations of fungus mycelium with
electronics and sensing platforms are scarce. Recent developments
in this field are either unfavorably bulky or exhibit limited sensing
performance (28,  29). We demonstrate the fabrication of light-
weight and shape-adaptive standalone sensor patches based on an
as-grown fungus mycelium substrate and highlight general process-
ing techniques of mycelium skin for electronics. We construct con-
ductor paths by metalizing mycelium surfaces via physical vapor

1 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026A

C

B

D

E

Fig. 1. Formation and properties of mycelium skin. (A) Structure of G. lucidum fungus. Mycelium roots are growing inside the chosen medium, with fruiting bodies
forming on the surface at longer growth times. Mycelium strains consist of hyphen structures on a microscopic level. Scale, bar 10 m. (B) Concept of using mycelium skin
as substrate for electronic devices. (C) Growth of mycelium skin on PE-separator grid and underlying substrate. (D) Three distinct types of mycelium skin are obtained
depending on the growth time. Sides A and B refer to the surface in contact with the surrounding air and the separation grid, respectively. (E) TGA of all mycelium types
with a constant temperature change of 0.166 K/s, revealing thermal stability to more than 250°C.

deposition (PVD) of thin metal layers and subsequent laser ablation.
Our mycelium skin exhibits high thermal stability, allowing soldering
of electronic components and facilitating the fabrication of electronic
sensor boards, not restricted to planar geometry due to its shape
adaptiveness. In addition, we propose a new concept of mycelium
batteries, using our skins both as battery separators and casing. We
achieve untethered operation of a standalone circuit directly incor-
porating our mycelium battery, a capacitive sensor, and all necessary
communication modules. We demonstrate the versatility of the ma-
terial for sustainable electronics on a profound level, bringing us
closer toward a more sustainable architecture of electronic devices.

RESULTS
Mycelium skin growth, harvest, and characterization
We fabricate our mycelium skins by covering moist beech wood–
based inocula with a polyethylene (PE) separation grid and storing
them at 25°C (details given in Materials and Methods). The humid
and CO2-rich atmosphere allows the growth of G. lucidum fungus
and the formation of mycelium skins on the surface. Its development
on the surface exhibits three distinct phases (Fig. 1C and fig. S1).
During the first phase (“young” skin), the surface has a bright white
color while covering the separation grid with an increasingly dense layer
(Fig. 1D). In the second phase (“medium” skin), the skin grows more

thick and dense, and brown patches appear on the surface that
are covered with a rough crust. The third phase (“mature” skin) is
marked by a complete coverage of the surface with the brown crust.
Thereafter, the skin formation is complete, and the growth process
stops. We observe growth times to be approximately 2 weeks until a
closed sheet of young skin is formed and two further weeks until
it can be classified as mature. Further optimizing the starting and
growth conditions could potentially accelerate and stabilize this pro-
cess substantially. Moreover, primordia formation and subsequently
the formation of fruiting bodies must be suppressed to obtain a
smooth skin. Thus, exposure to light must be minimized, and a high
level of CO2 in the surrounding atmosphere must be maintained.
Directly after the harvest, the skins are composed of living mycelium,
saturated with water, thus we impose additional compressing and
drying, yielding the final skins. Hereby, the grammage of the skins
is reduced by up to a factor of 8, and we observe slight shrinking
(<10%) and notable stiffening (fig. S2C). Our growth and harvest
method is readily scalable to yield areas of several square meters,
depending mostly on the growing substrate. Irregular growth, the
malleable material with soft and fuzzy surfaces, and inhomogene-
ities in the pressing and drying process result in variations in skin
thickness over the harvested area (table S1). Thus, sample gram-
mage is more suitable to characterize larger areas of our mycelium
skin. Furthermore, our  substrate  is able  to supply nutrients for

2 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026additional  skin  growth,  enabling  several  mycelium  skin  harvests
all from one source material. We achieved a maximum of five sub-
sequent harvests from one growing medium over a period of 6 weeks
with sufficient yield and quality of the obtained mycelium skins. To
achieve such high growth cycle numbers, we prevent contamination
of the surface and the separation grid with competing organisms by
maintaining a high level of cleanliness, as contamination may lead
to irregular skin formation. Growth of the fungus can be terminally
stopped after harvest by drying and heating the remaining biode-
gradable mycelium-beech wood composite. The remainder exhibits
low density and comparatively high compressive and tensile strength
due to the long growth time. These properties render it suitable to
be further used in various applications such as mycelium composite
construction or packaging (30). Alternatively, the fungus can as well
still produce a certain amount of fruiting bodies for medical pur-
poses from the remaining substrate block. Utilization of abundant
agricultural waste to obtain multiple high-value products, as pro-
posed in our method, is an indispensable aspect of sustainable fab-
rication routes and conforms perfectly with proposed schemes for
biorefineries in a circular economy (31–33). To allow combination
of our substrate with standard electronic processing techniques,
a high temperature stability is indispensable. Thermogravimetric
analysis (TGA) (Fig. 1E) of all three skin types in pure oxygen atmo-
sphere demonstrates the material stability up to more than 250°C,
with the critical temperature increasing slightly with the age of the
skin. This allows processing of electrical components on top of our
substrate using standard techniques like soldering.

Electronic circuits on mycelium skin
The excellent thermal stability and electrically insulating nature
of the hyphen network renders our mycelium skin a highly suitable
biodegradable substrate for electronic circuit boards. We herein
demonstrate several routes for functionalization, forming the foun-
dation for further use in electronic circuits and sensor technology
(Fig. 2A). We achieve cohesive metallic films on top of harvested
skins with a surface roughness Rrms of 7.5 ± 1.8 m by PVD (fig. S3),
which allow for further processing to circuit paths. We obtain films
with reproducible continuity by depositing 400 nm of copper as con-
ductive bulk, with predeposition of 3 nm of chromium for better
adhesion (Fig. 2B) (34). We further improve conductivity by depos-
iting an additional layer of gold with a thickness of 50 nm onto the
initial copper layer. As an alternative route, we demonstrate gold
plating of the already metalized (copper) mycelium, using electro-
plating and a respective electrolyte solution. For this purpose, met-
alized mycelium is dipped into the plating solution along with a
stainless-steel anode, both connected to a power supply, with the plat-
ing process then being controlled by the applied current. Our met-
alized mycelium skin hence enables the fabrication of traces and
pads for electronic circuit boards in an easily scalable manner. The
additional gold coating is especially advantageous at connecting
pads and soldering points, where copper corrosion would otherwise
diminish performance. We then pattern conductive traces into our
mycelium-metal films by laser ablation, without impairing the me-
chanical integrity of the underlying substrate (Fig. 2C and fig. S2).
Trace conductivity decreases with increasing skin age, as the surface
structure changes in the growth process (Fig. 2D). We achieve
a high trace conductivity of 9.75 ± 1.44 × 104 S cm−1 with the bulk-
facing side of young skin, comparable with conductors on common
printing paper (17, 35). In general, the electrical properties of young

mycelium are similar to paper-based substrates (18, 35); they exhibit
a breakdown strength of 13.5 ± 3.7 kV mm−1, a relative permittivity
of r = 3 ± 0.9, a loss tangent of  = 0.06 ± 0.01 at 1 MHz, and a
conductivity of 0.27 ± 0.1 S m−1 at 10 MHz (see fig. S4 for details).
With increasing skin maturity, formation of islands of rough crusts
disrupts the continuity of the surface, hence impairing the forma-
tion of continuous metal films. Consequently, side B exhibits higher
conductivity values across all ages, as little to no crust forms on the
side facing the bulk growing medium opposed to side A, which is in
contact with the surrounding air. For mature mycelium skin with a
fully developed crust, no continuous metal film could be formed.
With this insight, we focus all following demonstrations on the bulk
side of young mycelium. Traces fabricated using this approach can
sustain high current densities up to 333 A mm−2, before electrode
failures due to overheating arise (figs. S5 and S6). In addition to its
high conductivity, the lack of crust and overall low thickness yield
high flexibility of the fabricated traces. Cyclic bending of a single
Cu-Au trace between a bending radius of 22.5 and 5 mm is feasible
for more than 2000 bending cycles with only a small increase in re-
sistance of 18.1% (Fig. 2E). We observe a burn-in effect in the first
cycles, wherein the resistance increases by 6% in the first 10 cycles.
In later iterations, the resistance changes only marginally within
1 cycle indicating only minimal damage of hyphen connections
(Fig. 2F). At around 2000 cycles, the metal film begins to crack over
larger areas with each cycle, resulting in a steep resistance increase
(fig. S7), similarly to the behavior observed in metal depositions on
plain polymer substrates (36). We achieve not only bending of me-
tallic traces but also folding of metalized mycelium several times
is feasible while remaining fully functional (Fig. 2G and fig. S8). The
normalized resistance R/R0 rises to 4.07 ± 0.51 after imposing 12-fold
(Fig. 2H), comparable to reports on glossy printing papers with sub-
stantially lower surface roughness (17). The ability of our metalized
mycelium skin to withstand such extreme deformations with rea-
sonable increases in resistance thus allows the realization of complex
conductor geometries. Surface mounting of electronics to passive
components can be imposed onto MycelioTronic devices without
major performance losses under deformation. Our mycelium skins
can be permanently forced into numerous geometries by exploiting
the soakability of the foam-like hyphen network using a hydroset-
ting method (37). Soaking the mycelium with 2-propanol, subse-
quently reshaping it into its desired form using a mold (fig. S9), and
lastly air drying of the skin in ambient environment in its deformed
state yield a permanently deformed yet fully functional Mycelio-
Tronic device. To illustrate this concept of shape-adaptive electronics,
we reshape a conductor strip including a surface mounted device–
light-emitting diode (SMD-LED) into a helical structure, with the
LED’s luminosity not being visibly diminished (Fig. 2I). Such Mycelio-
Tronic devices can further be encapsulated using a biodegradable
shellac-ethanol varnish to ensure electrical insulation and be used
for wearable applications as well (fig. S10).

Mycelium skin for flexible and biodegradable batteries
Our mycelium skin cannot only be used as a substrate for sustain-
able electronic circuits. With its highly porous structure, mycelium
skin can soak up large amounts of liquid and is thus a promising
candidate for realizing sustainable battery separators (fig. S11).
Electronic devices rely heavily on either external or integrated power
sources, with truly sustainable solutions being scarce. Larcher et al.
(38), for example, discuss the importance of developing greener battery

3 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026A

B

D

G

C

F

I

E

H

Fig. 2. Functionalization methods for mycelium skin. (A) Possible functionalization methods of mycelium skin. (B) Formation of Cu and Cu-Au bilayer films on
mycelium skin. (C) Colorized SEM image of a laser-ablated edge of a Cu-Au layer fabricated by PVD (3 nm of Cr, 400 nm of Cu, and 50 nm of Au) on a young mycelium skin
(side A). Scale bar, 20 m. (D) Conductivity of a PVD-Cu-Au layer on young, medium, and mature mycelium skin, sides A and B. n = 5. N.C., non-conducting. (E) Normalized
resistance of young Cu-Au–covered mycelium during cyclic bending over 2000 times between bending radii of 5 and 25 mm. Variation of resistance in 1 cycle (gray) decreases
with the number of cycles, while the maximum (blue) increases. (F) Normalized resistance of selected cycles of (E) as a function of bending radius. (G) Optical image of
Cu-Au traces on a young mycelium skin after recovery of several hard folds being imposed. Scale bar, 5 mm. (H) Normalized resistance of conductor traces increases with
the number of applied folds. n = 5. (I) Photograph of a young mycelium skin conductor strip with a surface mounted LED reshaped into a helix. Scale bar, 5 mm.

chemistries in detail. Thus, we herein are focusing on demonstrat-
ing sustainable concepts for the passive components and building
blocks of a battery, universal and not restricted to battery chemistry,
namely, the separator and packaging. With this approach, we sub-
stitute the bulk volume of a typical battery with a sustainable mate-
rial. Yet, depending on the battery chemistry, different requirements
must be met by a material to be suitable as a separator. Commercial
Li-ion batteries mostly use polyolefin polymer separators, as they
exhibit excellent mechanical properties, are chemically stable with

respect to lithium chemistries, and can be produced with small enough
pore sizes to incorporate safety mechanisms (39). However, these are
nonrenewable petroleum products, both expensive and unfavorable
in terms of environmental impact. The use of biomaterials as bat-
tery separators is still very limited and must increase for a transition
to more and more sustainable portable energy sources (40). Mycelium
skin separators may serve as an eco-friendly alternative, as they can
be grown naturally and consume little resources even compared to
paper-based materials (41). We herein use the mycelium skin’s

4 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026ability to soak up high amounts of liquid in combination with a
highly ion-conducting electrolyte solution, yielding a flexible mem-
brane that can be readily incorporated in batteries as separator
material. We test their performance using primary zinc-carbon cell
chemistry, using a conventional ammonium chloride and zinc chlo-
ride solution as electrolyte (Fig. 3A). The solution fills the cavities of
the otherwise dry sheets of mycelium skin by soaking for 12 hours.
We determine the quality of ion transport through the bulk materi-
al by impedance spectroscopy of the liquid-filled separators using a
custom-built measurement cell (42). Mycelium skin of type medi-
um exhibits the lowest specific resistance (Fig. 3B), being as low
as 54.3 ± 19.8 ohm cm with our electrolyte solution, rendering it a
viable separator material. However, the ability to transport ions is
inevitably lowered by any separator material when compared to
unrestrained, i.e., freestanding liquid electrolyte solutions. Conduc-
tivity itself highly depends on the used electrolyte solution and is
hence not universal with respect to the used chemistry. To ease compar-
ison with other materials, the quality of a separator is also described
by the MacMullin number, being the ratio between freestanding
electrolyte conductivity and separator conductivity. With medium
mycelium skin, we achieve MacMullin numbers as low as 6.7, mak-
ing them comparable to commercial Li-ion battery separators in this
respect (39). In the construction of full cells, mycelium skin does
not only serve as a well-conducting separator, we also use the same
material in its dry form as packaging. Thus, we are already substitut-
ing many components of a standard zinc-carbon cell with a sustain-
able alternative, making a high percentage of the resulting battery
biocompatible and biodegradable (Fig. 3C). In our demonstration,
electrode materials are constructed as pastes, with the anode being
a zinc paste, and the cathode being a manganese dioxide and carbon
black paste. The outer packaging layers are mycelium skin foils met-
alized on one side, to allow collection of the current generated by
the battery. For the cathode current collector, both vapor-deposited
and electroplated Cu-Au bilayers can be used. The battery is then

assembled layer by layer, bonded together with shellac glue, a natu-
ral and biocompatible alternative to synthetic glues. Chambers for
the electrode pastes are cut out of untreated mycelium skin and
glued onto the outer packaging layers on the metalized sides serv-
ing as current collectors. Pastes are filled into the chambers, and a
separator frame and the liquid-filled mycelium skin separator are
enclosed in between. Polarization curves of the assembled cells ex-
hibit strictly linear behavior, and short-circuit currents up to ~50 mA
are feasible (Fig. 3D). Using a vapor-deposited Cu-Au bilayer as
cathode, current collector yields a discharge capacity of 3.8 mA
hour cm−1 when discharged with a high current of 2 mA. We
achieved high discharge capacities of up to 3.1 mA hour cm−1 using
electroplated gold cathode current collectors at a high discharge
current of 2 mA (Fig. 3E). Furthermore, with this simple assem-
bling approach, multicell arrangements can easily be constructed, if
higher voltages or capacities are needed.

Untethered MycelioTronic sensing circuit
Our mycelium battery concept allows autonomous operation of
various electronics in a sustainable manner. Combining our metal
trace fabrication approach with our mycelium batteries now enables
standalone MycelioTronic circuits. We demonstrate an untethered
mycelium sensor board, with a surface-mounted data communica-
tion module powered by an integrated mycelium battery and an
embedded impedance sensor (Fig. 4A). The latter consists of two
interdigitated electrodes with a length of 12 mm, a gap width of
400 m, a trace width of 600 m, and an overall width of 15 mm.
We directly incorporate this sensor structure and two 15 mm by
15 mm electrodes for the mycelium battery in our circuit by laser
ablation (fig. S12A) from copper-gold metalized mycelium skin. Col-
lection and transmission of sensor data are handled by a commercial
Bluetooth low-energy (BLE) module soldered to the respective con-
nection pads in the circuit. To meet its power requirements (op-
erating voltage of >1.9 V), we use two cells in series and assemble

A

C

B

E

D

Fig. 3. Concept for mycelium batteries. (A) Explosion view of a mycelium zinc-carbon battery, using a mycelium separator soaked with electrolyte solution. (B) Specific
resistance of young, medium, and mature electrolyte-filled mycelium. (C) Optical image of a sample battery. Scale bar, 1 cm. (D) Polarization curve of an assembled battery
using a vapor-deposited gold cathode current collector. (E) Discharge of mycelium batteries with varying discharge current and both electroplated (EP-Au) and vapor-
deposited (PVD-Au) cathode current collectors.

5 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026A

D

I

B

E

G

C

F

H

J

Fig. 4. Mycelium sensor board. (A) Photograph of a sensor board including a dual-cell mycelium battery, a Bluetooth module, and an impedance sensor with an inter-
digitated electrode structure. Scale bar, 1 cm. (B) Impedance response of the sensor highly depends on the relative humidity of the environment. (C) Fitted capacitance
and resistance of the interdigitated sensor structure as function of frequency. (D) Block diagram of the sensor board generating and transferring data to an external PC
during untethered experiments. (E) A finger approaching the sensor results in clear changes in sensor capacity. Scale bar, 2 cm. (F) Capacity response of the sensor to the
repeatedly approaching finger in (E). (G) Aspiration onto the sensor board causes clearly detectable humidity changes. Scale bar, 2 cm. (H) Capacity response to
the humidity changes on (G). (I) Aerobic disintegration of MycelioTronic PCB substrates occurs within 2 weeks in composting soil. Scale bar, 2 cm. (J) Mass percent of the
decomposing PCB substrate depicted in (I) measured over 11 days.

the battery directly on the two integrated electrodes. Thus, the cir-
cuit substrate simultaneously functions as the bottom layer of the
battery (fig. S12B). We first investigate the performance of our my-
celium impedance sensor as humidity sensor within a controlled
environment using a climate chamber (Fig. 4B). The relative humidity
was gradually incremented by 10% relative humidity (r.H.) from 20 to
70% r.H. performing impedance spectra from 1 Hz to 10 MHz during
stable climate conditions. Thereby, the impedance response can
be modeled by a parallel capacitor-resistor circuit (fig. S13). The
corresponding capacity increased around 29%, and the resistance de-
creased over three orders of magnitude to a resistance of 1.17 megohm
at 70% r.H. (Fig. 4C). With this general high resistance and capacitance
in the picofarad (pH) range, the sensor is suitable to be used with the
built-in capacitance measurement system of the BLE module (Fig. 4D).
Thereby, the sensor is periodically charged with a 2.2-nF capacitor

to a reference voltage of 1.2 V (fig. S14) exhibiting only a slight leak-
ing current of 0.5 A at 70% r.H., negligible compared to the overall
charging current of 138 A. Combined with our mycelium battery,
we demonstrate untethered humidity and proximity sensing with
our circuit. The battery supplies a high operating current of approx-
imately 2 mA under standard operation and approximately 13.5 mA
during data transmission to the circuit. When an object like a finger
approaches the sensor (Fig. 4E), its charging is altered as the object
acts as a parasitic capacitance, resulting in distinct changes in sen-
sor capacitance (Fig. 4F). In addition to proximity sensing, we also
demonstrate the sensor’s aspiration sensing capabilities (Fig. 4G). A
short-term rise of humidity causes a clearly detectable change in
capacity (Fig. 4H). After direct aspiration is terminated, the signal
first decreases steeply, until a region of slower decrease caused by
residual moisture adhering to the mycelium surface is observed. Thus,

6 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026we are able to conduct both proximity and humidity sensing entire-
ly untethered and with an integrated sustainable power supply with
our sustainable MycelioTronic design. We demonstrate the potential
of finely structured circuits on mycelium skins powered by myce-
lium batteries. Our MycelioTronic approach therefore serves as a
foundation for sustainable electronics with high functionality and
variability. After the end of life of our circuit, reusable surface-
mounted components are easily dissembled from the board using
simple tools like a heat gun or solder iron, leaving solely the biode-
gradable substrate as waste product (fig. S15). The mycelium PCB
disintegrates readily in composting soil after the removal of the con-
ventional ICs (Fig. 4I). It loses 93.4% of its dry mass within 11 days
(Fig. 4J). After this period, sample remnants are indistinguishable
from the soil. Unprocessed mycelium skins disintegrate likewise
down to 9.3% of their initial mass after 11 days (fig. S16). Further-
more, with our ability to use conventional IC elements, routes for
improvement analogous to standard PCBs holds great promise. Im-
plementation of vias through the skin constitutes only one of many
promising routes for future improvements to the design and imple-
mentation of MycelioTronic circuits. Vias hold a vast potential to-
ward multilayer PCBs with even higher complexity, closing the gap
to conventional electronics in terms of sophistication. Traditionally,
vias are realized by creating holes through the board and filling with a
conductive material, connecting two or more layers. The soakability of
the porous hyphen network of mycelium skins, however, allows for
filling with conductive polymer suspensions, e.g., poly(3,4-ethylene
dioxythiophene) polystyrene sulfonate (PEDOT:PSS) (fig. S17). This
enables the fabrication of vias without the necessity of drilling or
punching holes.

DISCUSSION
We here developed a new approach to fabricate sustainable elec-
tronics including power sources for untethered and standalone de-
vices. We report methods for scalable growth of mycelium skins
and fabrication of electronic traces on top these biodegradable sub-
strates. We demonstrate PVD of gold and copper films combined
with laser-assisted patterning and achieve high trace conductivities
of 9.74 ± 1.44 × 104 S cm−1. Good flexibility of the substrate enables
thin traces to be bent repeatedly 2000 times down to a bending ra-
dius of only 5 mm with only moderate increase in resistance. We
additionally demonstrate the fabrication of mycelium-based bat-
teries, substituting both the packaging and the separator of zinc-
carbon cells with our sustainable mycelium skins that achieve
capacities up to ~3.8 mA hour cm−2. We use these batteries to
power an untethered mycelium sensor board, able to measure, store,
and transmit humidity and proximity sensing data. All the materials
used can either be composted or be recycled. With these advances,
biodegradable mycelium skins may emerge as a sustainable alterna-
tive materials class for a green electronic future.

MATERIALS AND METHODS
Materials
All chemicals were used as received without further purification.
Ammonium chloride (NH4Cl; Sigma-Aldrich) and zinc chloride
(ZnCl2; VWR, USA) were used as electrolyte solution. Zinc powder
(Grillo-Werke AG, Germany), xanthan powder (Sigma-Aldrich),
manganese(IV) oxide (MnO2; Sigma-Aldrich), and acetylene carbon

black (ABCR GmbH & Co KG, Germany) were used for the battery
electrodes. Gold electrolyte solution (Conrad Electronic Interna-
tional GmbH & Co. KG) was used for galvanizing copper-plated
mycelium. Shellac flakes (A.F. Suter & Co. Ltd.) were used to fab-
ricate shellac glue. PEDOT:PSS (Clevios PH 1000, Heraeus) was used
as conductive filler. Silver ink (Leitsilber 200, Ögussa) was used as
conductive coating. Low-temperature solder (IND:282, Indium cor-
poration) was used for soldering.

Mycelium skin growth and harvest procedure
One kilogram of dry beech wood shavings (Räucherspan.de Buche
Typ 7) was thoroughly mixed with about 50 g of organic full-grain
spelt flour (local grocery store) and 25 g of fine plaster (CaSO4) dust
(local construction market). This mixture together with 2 liters of
water was boiled in a pressure cooker for at least 30 min for steril-
ization. The wet substrate was filled in sterilized polypropylene
boxes to a height of 4 to 8 cm. After cooling down to room tempera-
ture with closed lid, about 500 g of beech wood–based inoculum
(Tyroler Glückspilze Sägemehlbrut G. lucidum Sopron strain) was
evenly distributed to all containers, manually ripped apart into small
pieces, and mixed thoroughly under the substrate. As a separation
grid, a strong polyethylene fly screen with square holes of 0.5 mm
in width was cut to fit onto the surface of the substrate in the con-
tainers. After sterilization with boiling water and isopropanol, the
fly screen patches are placed on the substrate, the lid are closed
tightly to minimize gas exchange, and the boxes are stored in a dark
space at approximately 25°C. After appropriate fungus growth,
the separation grid was ripped off the solidified substrate together
with the mycelium skin. The mycelium skin was peeled off carefully
from the separation grid using a blade or a spatula. The wet skin was
repeatedly placed between two paper towels and pressed gently
to remove most of the water content. When the mycelium skin was
dry to the touch, it was placed between two straight wood plates and
left to completely dry while being forced flat.

TGA measurement
A crucible was filled with ~5 mg of mycelium skin, placed in a
Mettler Toledo TGA, and flooded with pure O2. The temperature was
set to 50°C for 30 min and then increased with a rate of 0.166 K/s
until 400°C.

SEM measurement
Scanning electron microscopy (SEM) measurements were per-
formed using the Zeiss 1540 XB CrossBeam SEM (acceleration volt-
age, 5 keV). Before imaging, the samples were covered with ca.
10 nm of gold via thermal evaporation (pressure, ~3 × 10–6 mbar;
deposition rate, 0.1 to 0.3 A s−1) to increase surface conductivity and
thus image quality.

Uniaxial tensile tests
Mycelium skin specimens were punched out with a dog bone–
shaped punching tool based on ISO 527-2:2012(E) type 5A and tested
with a Zwick Roell Z005 (100 N load cell).

Surface metallization (PVD)
Mycelium skin samples were metallized with a PVD system (Oerlikon
Leybold Univex 350), using a vacuum pressure of less than 5 ×
10−6 mbar. The deposition rates were 0.02 nm s−1 for chromium,
0.3 nm s−1 for copper, and 0.15 nm s−1 for gold.

7 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026Electroplating
Premetalized mycelium skin samples were submerged in a gold elec-
trolyte solution (Conrad Electronic International GmbH & Co. KG)
and connected to a power supply (Rohde & Schwarz München Typ
NGM 70/05) with a fixed current supply of 100 mA. Hereby, a steel
ring was used as the counter electrode.

Conductivity of metallized mycelium skins
The conductivity of a metallized trace on a mycelium skin was deter-
mined by measuring the resistance with a multimeter (Keithley 2110)
in four-wire configuration. All mycelium samples are metallized with
a chromium-copper-gold trilayer (3 nm of Cr, 400 nm of Cu, and
50 nm of Au), and the desired traces and pads were created by
removing the negative by laser ablation with a fiber laser cutter
(Trotec Speedy300 flexx). The conductivity  was calculated as

   =

l ─
R · A

(1)

where R is the measured resistance, A is the cross section (1 mm by
450 nm), and l is the length (10 mm) of the Cu-Au metal trace.

Cyclic bending
A mycelium sample with an engraved trace was placed on a 75-m-
thick polyimide foil (Kapton HN). The foil was clamped between two
parallel poly(methyl methacrylate) plates, and the resistance was de-
termined with a multimeter (Keithley 2110) in four-wire configuration.
The distance between the two plates was adjusted periodically, and the
bending  radius  is  approximated  as  the  halved  distance  between
the two plates.

Folding experiment
A metallized mycelium sample (3 nm of Cr, 400 nm of Cu, and
50 nm of Au) was engraved to yield five parallel traces. The edge of
a thin plastic plate was used to fix the sample around the desired
folding edge following a second plate to fold the mycelium over the
edge. After removing the first plate, the mycelium was compressed even
further to ensure a hard edge. This process was repeated 12 times
with alternating folding directions, and for each new fold, the previous
folds are compressed as well. For every two new folds, the resistance
was determined with a multimeter (Keightley 2110) in four-wire
configuration.

Reshaping into helix structure
A metallized mycelium strip (3 nm of Cr, 400 nm of Cu, and 50 nm
of Au) with a mounted LED was soaked with isopropanol and was
helically wrapped around a 5-mm-thick glass tube. A thin gap in the
metallic layer ensures the current flow through the LED, and a
low-temperature solder paste (IND:282, Indium Corporation) was
used to mount the LED. The wrapped mycelium was fixed on the
endings of the strip with tape. As soon as the isopropanol was com-
pletely evaporated, the mycelium can be removed by sliding it over
the glass tube. The mycelium stayed in the given helix structure
without any additional process.

Impedance spectroscopy
Mycelium skin samples were soaked for 24 hours in electrolyte
solution before testing. A custom-made measurement cell was
used to determine the impedance between 1 and 10 MHz using an

impedance analyzer (Novocontrol Alpha A Analyzer) with 1 mV
of AC voltage applied. The bulk resistance was determined from
the high-frequency plateau of the real part of the impedance. The
conductivity and specific resistance were calculated using the bulk
resistance and membrane geometry.

Battery fabrication
The anode paste was prepared by mixing 63.5 wt % zinc powder,
35 wt % electrolyte solution, and 1.5 wt % xanthan powder. The
cathode paste was prepared by mixing 12 wt % manganese (IV)
oxide and 12 wt % acetylene carbon black in 76 wt % electrolyte
solution. For a single cell, the anode current collector is composed
of a mycelium skin with a chromium-copper bilayer applied by va-
por evaporation (3 nm of Cr and 900 nm of Cu). For the cathode
current collector, gold was either deposited onto the same by elec-
troplating with gold electrolyte solution and deposit time of 1 min
or by subsequent PVD of a 50-nm gold layer. The mycelium was
thoroughly rinsed and left to dry for 24 hours after electroplating.
Chambers for the active anode and cathode pastes (1 cm by 1 cm) as
well as a frame for the separator (1.5 cm by 1.5 cm) were cut out of
plain, untreated mycelium skin sheets. The separator was soaked in
electrolyte solution for at least 24 hours before assembly. One gram
of shellac flakes was dissolved in 4 ml of ethanol and stirred for
20 hours to form an adhesive. The battery was constructed layer by
layer, using shellac glue for adhesion of the mycelium skin layers to
each other. For the two-cell configuration as used to power the cir-
cuit board, the anode current collector was, as well, made of gold-
plated copper-mycelium skin.

Battery characterization
The characteristics of the batteries were recorded using a Keithley
2611A Source Measuring Unit connected to the battery current
collectors.

Flexible PCB fabrication
The flexible PCB was based on a metallized mycelium skin with a
chromium-copper-gold trilayer (3 nm of Cr, 400 nm of Cu, and
50 nm of Au). The traces and pads of the PCB were created by
removing the negative by laser ablation with a fiber laser cutter
(Trotec Speedy300 flexx). To avoid overheating and degradation
of the mycelium skin over 250°C, all SMDs were soldered onto the
pads with a low-temperature solder paste (IND:282, Indium Cor-
poration). The core of the electronic system was a Bluetooth mod-
ule (CYBLE-222014, Cypress Semiconductor Corp.). This module
was connected to a Programmer/Debugger (Kitprog, Cypress) and
flushed with a Bootloader program, enabling updating the mod-
ule Over-The-Air via Bluetooth. The application of the module was
programmed in PSoc Creator 4.2 and updated with the program
CySmart 1.3 using the USB-dongle CY5677 CySmart BLE 4.2. To
ensure a better connection to the PCB, short pieces of a copper wire
were previously soldered onto the pads of the module to increase
the size of the pads. An additional switch (CVS-01B, Copal Elec-
tronics) was included to cut off the power supply of the battery.

Humidity measurements
The mycelium sensor was placed in a climate chamber (C-40/350,
CTS Clima Temperatur Systeme GmbH) and was read out with an
impedance analyzer (Novocontrol Alpha A Analyzer) between 1 Hz
and 10 MHz.

8 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026

PEDOT:PSS soaking
Young mycelium skins were soaked with aqueous PEDOT:PSS
solution either by submerging or by placing a droplet of PH1000
on  the  skin.  Silver  ink  was  used  to  contact  the  PEDOT:PSS-
soaked mycelium.

Shellac coating of LED strip
Young metallized mycelium (3 nm of Cr, 400 nm of Cu, and 50 nm
of Au) with three surface-mounted LEDs was brush-coated with a
1:4 shellac/ethanol mixture. The resulting shellac layer is an electri-
cally insulating coating providing also mechanical protection. A
second sample was coated with an airbrush, and the resulting sur-
face structure was further analyzed by SEM.

Surface roughness measurement
Young mycelium skin of three different harvests were placed in a
profilometer (Dektak 3), and the surface roughness Rrms was deter-
mined by calculating the root mean square average over a scanning
length of 2 mm and averaging over all measured traces (n = 9).

Dielectric breakdown measurement
Young mycelium skins were positioned between two brass stamps
connected to a high voltage supply (140-35000, FuG Elektonik
GmbH). The voltage was continuously increased with 50 V s−1 until
a breakdown/sharp voltage drop occurred.

Electrical property measurement
Double-sided metallized mycelium samples (3 nm of Cr and 500 nm
of Cu) were engraved on both sides to form a plate capacitor with an
area of 78.5 mm2. The conducting electrodes are engraved in oppo-
site directions and were connected with an impedance analyzer
(Novocontrol Alpha A Analyzer). The impedance of the capacitor
was determined between 10 and 1 MHz with 1 V of AC voltage ap-
plied. The relative permittivity r, the conductivity , and the loss
tangent  are calculated from the complex impedance, taking into
account the geometry of the electrodes.

Electrical heating measurement
A metallized mycelium sample (3 nm of Cr, 400 nm of Cu, and
50 nm of Au) was engraved to yield three parallel traces with a
width of 2 mm. The traces were consecutively connected to a labo-
ratory power supply (GPD-3303D, GW Instek) with step-wise in-
creased current settings until failure. Simultaneously, a thermal
infrared camera (325sc, FLIR) performs temperature measurements
on the mycelium samples.

Biodecomposition measurement
Mycelium samples were mixed with properly operating aerobic
composting inoculum and  put  into  static  composting vessels,
purged with oxygen, and kept at a constant temperature of 58°C. For
this  purpose,  the  inoculum  was  first  sorted  to  be  free  of  large
inert objects and to yield a homogeneous fine-grain mixture. Inocu-
lum was then saturated with water and filled into the compost-
ing vessels along with mycelium samples. Vessels were sealed
and purged with water-saturated air. Samples were filtered from
the inoculum in intervals of 3 to 4 days, dried at 60°C, and weighed
to  yield  the  dry  mass  of  samples.  Photographs  were  taken,  and
mass  loss  was  calculated  with  reference  to  the  sample’s  original
dry mass.

Statistical analysis
Sample size of trace conductivity and resistance measurements
were n = 5 per type, data points being mean values and error bars
indicating SD. Sample size of separator conductivity measurements
was n = 4 per type, data points being mean values and error bars
indicating SD. Rp and Cp values in Fig. 4C are fitted according to
a  parallel resistor-capacitor circuit model minimizing the least
squared error of the impedance spectrum for each humidity setting
using the Levenberg-Marquardt algorithm (fig. S7). All further mea-
surement data are plotted as recorded.

SUPPLEMENTARY MATERIALS
Supplementary material for this article is available at https://science.org/doi/10.1126/
sciadv.add7118

REFERENCES AND NOTES
  1.  A. Heiden, D. Preninger, L. Lehner, M. Baumgartner, M. Drack, E. Woritzka, D. Schiller,
R. Gerstmayr, F. Hartmann, M. Kaltenbrunner, 3D printing of resilient biogels
for omnidirectional and exteroceptive soft actuators. Sci. Robot. 7, eabk2119 (2022).

  2.  Y. Khan, A. E. Ostfeld, C. M. Lochner, A. Pierre, A. C. Arias, Monitoring of vital signs

with flexible and wearable medical devices. Adv. Mater. 28, 4373–4395 (2016).

  3.  J. S. Heo, J. Eom, Y.-H. Kim, S. K. Park, Recent progress of textile-based wearable

electronics: A comprehensive review of materials, devices, and applications. Small 14,
1703034 (2018).

  4.  D. Hoornweg, P. Bhada-Tata, C. Kennedy, Environment: Waste production must peak this

century. Nature 502, 615–617 (2013).

  5.  M. Baumgartner, F. Hartmann, M. Drack, D. Preninger, D. Wirthl, R. Gerstmayr, L. Lehner,
G. Mao, R. Pruckner, S. Demchyshyn, L. Reiter, M. Strobel, T. Stockinger, D. Schiller,
S. Kimeswenger, F. Greibich, G. Buchberger, E. Bradt, S. Hild, S. Bauer, M. Kaltenbrunner,
Resilient yet entirely degradable gelatin-based biogels for soft robots and electronics.
Nat. Mater. 19, 1102–1109 (2020).

  6.  W. Li, Q. Liu, Y. Zhang, C. Li, Z. He, W. C. H. Choy, P. J. Low, P. Sonar, A. K. K. Kyaw,

Biodegradable materials and green processing for green electronics. Adv. Mater. 32,
2001591 (2020).

  7.  T. Das, S. Tosoni, G. Pacchioni, Structural and electronic properties of bulk and ultrathin

layers of V2O5 and MoO3. Comput. Mater. Sci. 163, 230–240 (2019).

  8.  T. Dinh, H.-P. Phan, T.-K. Nguyen, A. Qamar, A. R. Md Foisal, T. N. Viet, C.-D. Tran, Y. Zhu,
N.-T. Nguyena, D. V. Dao, Environment-friendly carbon nanotube based flexible
electronics for noninvasive and wearable healthcare. J. Mater. Chem. C 4, 10061–10068
(2016).

  9.  C. Sun, X. Li, Z. Cai, F. Ge, Carbonized cotton fabric in situ electrodeposition polypyrrole
as high-performance flexible electrode for wearable supercapacitor. Electrochim. Acta
296, 617–626 (2019).

  10.  L. Xiang, H. Zhang, Y. Hu, L. M. Peng, Carbon nanotube-based flexible electronics.

J. Mater. Chem. C 6, 7714–7727 (2018).

  11.  S. Choi, H. Lee, R. Ghaffari, T. Hyeon, D.-H. Kim, Recent advances in flexible and stretchable

bio-electronic devices integrated with nanomaterials. Adv. Mater. 28, 4203–4218 (2016).

  12.  S. Li, K. Shu, C. Zhao, C. Wang, Z. Guo, G. Wallace, H. K. Liu, One-step synthesis

of graphene/polypyrrole nanofiber composites as cathode material for a biocompatible
zinc/polymer battery. ACS Appl. Mater. Interfaces 6, 16679–16686 (2014).

  13.  L. H. Yamane, V. T. de Moraes, D. C. R. Espinosa, J. A. S. Tenório, Recycling of WEEE:

Characterization of spent printed circuit boards from mobile phones and computers.
Waste Manag. 31, 2553–2558 (2011).

  14.  Y. Gao, Y. Zhang, X. Wang, K. Sim, J. Liu, J. Chen, X. Feng, H. Xu, C. Yu, Moisture-triggered

physically transient electronics. Sci. Adv. 3, e1701222 (2017).

  15.  L. Wang, K. Wang, Z. Lou, K. Jiang, G. Shen, Plant-based modular building blocks for

“green” electronic skins. Adv. Funct. Mater. 28, 1804510 (2018).

  16.  M. J. Tan, C. Owh, P. L. Chee, A. K. K. Kyaw, D. Kai, X. J. Loh, Biodegradable electronics:
Cornerstone for sustainable electronics and transient applications. J. Mater. Chem. C 4,
5531–5558 (2016).

  17.  A. C. Siegel, S. T. Phillips, M. D. Dickey, N. Lu, Z. Suo, G. M. Whitesides, Foldable printed

circuit boards on paper substrates. Adv. Funct. Mater. 20, 28–35 (2010).

  18.  J. Liu, C. Yang, H. Wu, Z. Lin, Z. Zhang, R. Wang, B. Li, F. Kang, L. Shi, C. P. Wong, Future
paper based printed circuit boards for green electronics: Fabrication and life cycle
assessment. Energ. Environ. Sci. 7, 3674–3682 (2014).

  19.  Z. Fang, H. Zhu, W. Bao, C. Preston, Z. Liu, J. Dai, Y. Li, L. Hu, Highly transparent paper
with tunable haze for green electronics. Energ. Environ. Sci. 7, 3313–3319 (2014).
  20.  Y. H. Jung, T.-H. Chang, H. Zhang, C. Yao, Q. Zhen, V. W. Yang, H. Mi, M. Kim, S. J. Cho,
D.-W. Park, H. Jiang, J. Lee, Y. Qiu, W. Zhou, Z. Cai, S. Gong, Z. Ma, High-performance

9 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026green flexible electronics based on biodegradable cellulose nanofibril paper. Nat. Commun.
6, 7170 (2015).

H. A. B. Wösten, Growing a circular economy with fungal biotechnology: A white paper.
Fungal Biol. Biotechnol. 7, 5 (2020).

  21.  Z. Liu, S. Nie, J. Luo, Y. Gao, X. Wang, Q. Wan, Flexible indium-tin-oxide homojunction

  33.  M. Jones, A. Gandia, S. John, A. Bismarck, Leather-like material biofabrication using fungi.

thin-film transistors with two in-plane gates on cellulose-nanofiber-soaked papers.
Adv. Electron. Mater. 5, 1900235 (2019).

  22.  S. Nandy, S. Goswami, A. Marques, D. Gaspar, P. Grey, I. Cunha, D. Nunes, A. Pimentel,

R. Igreja, P. Barquinha, L. Pereira, E. Fortunato, R. Martins, Cellulose: A contribution
for the zero e-waste challenge. Adv. Mater. Technol. 6, 2000994 (2021).

  23.  M. Haneef, L. Ceseracciu, C. Canale, I. S. Bayer, J. A. Heredia-Guerrero, A. Athanassiou,

  24.

Advanced materials from fungal mycelium: Fabrication and tuning of physical properties.
Sci. Rep. 7, 41292 (2017).
I. Kuznetsova, B. Zaitsev, L. Krasnopolskaya, A. Teplykh, A. Semyonov, A. Avtonomova,
M. Ziangirova, A. Smirnov, V. Kolesov, Influence of humidity on the acoustic properties
of mushroom mycelium films used as sensitive layers for acoustic humidity sensors.
Sensors (Switzerland) 20, 2711 (2020).

  25.  M. R. Islam, G. Tudryn, R. Bucinell, L. Schadler, R. C. Picu, Morphology and mechanics

of fungal mycelium. Sci. Rep. 7, 13070 (2017).

  26.  F. V. W. Appels, J. G. van den Brandhof, J. Dijksterhuis, G. W. de Kort, H. A. B. Wösten,

Fungal mycelium classified in different material families based on glycerol treatment.
Commun. Biol. 3, 334 (2020).

  27.  A. Van Wylick, E. Elsacker, L. L. Yap, E. Peeters, L. de Laet, Mycelium composites and their

biodegradability: An exploration on the disintegration of mycelium-based materials in
soil. Bio Based Build. Mater. 1, 652–659 (2022).

  28.  E. S. Lazaro Vasquez, K. Vega, From plastic to biomaterials: Prototyping DIY electronics

with mycelium, in UbiComp/ISWC 2019- - Adjunct Proceedings of the 2019 ACM
International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of
the 2019 ACM International Symposium on Wearable Computers (Association for
Computing Machinery, 2019), pp. 308–311, doi:10.1145/3341162.3343808.
  29.  A. Adamatzky, A. Gandia, A. Chiolerio, Towards fungal sensing skin. Fungal Biol.

Biotechnol. 8, 6 (2021).

  30.  M. Jones, A. Mautner, S. Luenco, A. Bismarck, S. John, Engineered mycelium composite
construction materials from fungal biorefineries: A critical review. Mater. Des. 187,
108397 (2020).

  31.  E. Elsacker, E. Peeters, L. De Laet, Mycelium-based materials at the dawn of the

anthropocene, in Structures and Architecture: Bridging the Gap and Crossing Borders—
Proceedings fo the Fourth International Conference on Structures and Architectrue ICSA 2019
(CRC Press, 2019), pp. 1083–1090, uresdoi:10.1201/9781315229126-129.

Nat. Sustain. 4, 9–16 (2021).

  34.  H. Aouani, J. Wenger, D. Gerard, H. Rigneault, E. Devaux, T. W. Ebbesen, F. Mahdavi, T. Xu,

S. Blair, Crucial role of the adhesion layer on the plasmonic fluorescence enhancement.
ACS Nano 3, 2043–2048 (2009).

  35.  D. Tobjörk, R. Österbacka, Paper electronics. Adv. Mater. 23, 1935–1961 (2011).
  36.  B.-J. Kim, H. Shin, S.-Y. Jung, Y. Cho, O. Kraft, I.-S. Choi, Y.-C. Joo, Crack nucleation during

mechanical fatigue in thin metal films on flexible substrates. Acta Mater. 61, 3473–3481
(2013).

  37.  J. Wang, L. Emmerich, J. Wu, P. Vana, K. Zhang, Hydroplastic polymers as eco-friendly

hydrosetting plastics. Nat. Sustain. 4, 877–883 (2021).

  38.  D. Larcher, J. M. Tarascon, Towards greener and more sustainable batteries for electrical

energy storage. Nat. Chem. 7, 19–29 (2015).

  39.  P. Arora, Z. Zhang, Battery separators. Chem. Rev. 104, 4419–4462 (2004).
  40.  S. Leijonmarck, A. Cornell, G. Lindbergh, L. Wågberg, Single-paper flexible Li-ion battery
cells through a paper-making process based on nano-fibrillated cellulose. J. Mater. Chem. A
1, 4671–4677 (2013).

  41.  D. Grimm, H. A. B. Wösten, Mushroom cultivation in the circular economy. Appl. Microbiol.

Biotechnol. 102, 7795–7803 (2018).

  42.  D. Danninger, F. Hartmann, W. Paschinger, R. Pruckner, R. Schwödiauer, S. Demchyshyn,

A. Bismarck, S. Bauer, M. Kaltenbrunner, Stretchable polymerized high internal phase
emulsion separators for high performance soft batteries. Adv. Energy Mater. 10, 2000467
(2020).

Acknowledgments: We thank S. Demchyshyn for support with SEM measurements. Funding:
This work was supported by an ERC Starting Grant “GEL-SYS” 757931 (to M.K.) and the Austrian
Research Promotion Agency GmbH (FFG) “Myco-Insulation” FO999891082 (to M.K.). Author
contributions: Conceptualization: R.P., D.D., R.K., and M.K. Methodology: R.P., D.D., R.K., and
M.K. Investigation: R.P., D.D., L.H., and R.K. Visualization: R.P. and D.D. Supervision: R.K. and
M.K. Writing—original draft: D.D., R.P., and R.K. Writing—review and editing: D.D., R.P., R.K.,
and M.K. Competing interests: The authors declare that they have no competing interests.
Data and materials availability: All data needed to evaluate the conclusions in the paper are
present in the paper and/or the Supplementary Materials. Supplementary information is
available online.

  32.  V. Meyer, E. Y. Basenko, J. P. Benz, G. H. Braus, M. X. Caddick, M. Csukai, R. P. de Vries,
D. Endy, J. C. Frisvad, N. Gunde-Cimerman, T. Haarmann, Y. Hadar, K. Hansen,
R. I. Johnson, N. P. Keller, N. Kraševec, U. H. Mortensen, R. Perez, A. F. J. Ram, E. Record,
P. Ross, V. Shapaval, C. Steiniger, H. van den Brink, J. van Munster, O. Yarden,

Submitted 29 June 2022
Accepted 26 September 2022
Published 11 November 2022
10.1126/sciadv.add7118

10 of 10

Danninger et al., Sci. Adv. 8, eadd7118 (2022)     11 November 2022SCIENCE ADVANCES | RESEARCH ARTICLEDownloaded from https://www.science.org on March 14, 2026MycelioTronics: Fungal mycelium skin for sustainable electronics
Doris Danninger, Roland Pruckner, Laura Holzinger, Robert Koeppe, and Martin Kaltenbrunner

Sci. Adv. 8 (45), eadd7118.  DOI: 10.1126/sciadv.add7118

View the article online
https://www.science.org/doi/10.1126/sciadv.add7118
Permissions
https://www.science.org/help/reprints-and-permissions

Use of this article is subject to the Terms of service

Science Advances (ISSN 2375-2548) is published by the American Association for the Advancement of Science. 1200 New York Avenue
NW, Washington, DC 20005. The title Science Advances is a registered trademark of AAAS.

Copyright © 2022 The Authors, some rights reserved; exclusive licensee American Association for the Advancement of Science. No claim
to original U.S. Government Works. Distributed under a Creative Commons Attribution NonCommercial License 4.0 (CC BY-NC).

Downloaded from https://www.science.org on March 14, 2026