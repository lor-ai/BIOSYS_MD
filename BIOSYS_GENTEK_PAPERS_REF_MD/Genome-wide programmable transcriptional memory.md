Genome-wide programmable transcriptional
memory by CRISPR-based epigenome editing

Resource

Graphical abstract

g
n
i
r
e
e
n
g
n
E

i

y
r
o
m
e
m
c
i
t
e
n
e
g
p
E

i

g
n
i
t
e
g
r
a
t

i

e
d
w
-
e
m
o
n
e
G

Me

Me

Me

Me

CRISPRon

CRISPRoff

Active transcription

Heritable gene silencing

Gene reactivation

f
f

o
e
n
e
g
h
t
i

w
s

l
l

e
c
%

100

80

60

40

20

0

0

memory of gene silencing

WGBS

0
4

Targeting sgRNA

highly specific gain in
DNA methylation

transient CRISPRoff
expression

20

10
40
Days post-delivery

30

l

)
e
u
a
v
-
p
(
0
1
g
o
l
-

0
2

0

0
2
-

0
4
-

50

NT sgRNA

1
r
h
c

2
r
h
c

3
r
h
c

4
r
h
c

5
r
h
c

6
r
h
c

7
r
h
c

8
r
h
c

9
r
h
c

0
1
r
h
c

1
1
r
h
c

2
1
r
h
c

3
1
r
h
c

4
1
r
h
c

5
1
r
h
c

6
1
r
h
c

7
1
r
h
c

8
1
r
h
c

9
1
r
h
c

0
2
r
h
c

1
2
r
h
c

2
2
r
h
c

Genome-wide CRISPRoff screens
Target >20,000 genes

Genome-scale sgRNA tiling screens
116,000 sgRNAs, >500 genes

sgRNA-1

sgRNA-2

all genes
negative control
olfactory genes

Y chromosome

f
f
o
R
P
S
R
C

I

c
i
f
i
c
e
p
s
-
n
o
i
t
a
y
h
t
e
m
A
N
D

l

n
w
o
d
k
c
o
n
k

CRISPRoff DNAme mutant

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

TSS

CRISPRi

CRISPRoff

wide targeting window

–1000

–500

500
0
Position relative to TSS (bp)

1000

Authors
James K. Nun˜ ez, Jin Chen,
Greg C. Pommier, ..., Volker Hovestadt,
Luke A. Gilbert, Jonathan S. Weissman

Correspondence
luke.gilbert@ucsf.edu (L.A.G.),
weissman@wi.mit.edu (J.S.W.)

X
r
h
c

In brief
CRISPRoff programs heritable epigenetic
memory and is able to heritably silence
most genes, including genes without CpG
islands. This heritable silencing is highly
speciﬁc and persists through
differentiation of iPSCs into neurons.

Highlights
d CRISPRoff is a single fusion protein that programs heritable

epigenetic memory

d CRISPRoff can heritably silence most genes, including

genes without CpG islands

d CRISPRoff is highly speciﬁc and has a broad targeting

window across gene promoters

d CRISPRoff epigenetic memory persists through

differentiation of iPSCs into neurons

Nun˜ ez et al., 2021, Cell 184, 2503–2519
April 29, 2021 ª 2021 Elsevier Inc.
https://doi.org/10.1016/j.cell.2021.03.025

ll

ll

Resource
Genome-wide programmable transcriptional memory
by CRISPR-based epigenome editing

James K. Nun˜ ez,1,2 Jin Chen,1,2,18 Greg C. Pommier,3,4 J. Zachery Cogan,1,2,5 Joseph M. Replogle,1,5,6,7
Carmen Adriaens,8,9,10 Gokul N. Ramadoss,11 Quanming Shi,12 King L. Hung,12 Avi J. Samelson,11 Angela N. Pogson,1,7
James Y.S. Kim,13 Amanda Chung,3,5 Manuel D. Leonetti,13 Howard Y. Chang,12,14 Martin Kampmann,11,13,15
Bradley E. Bernstein,8,9,10 Volker Hovestadt,9,16,17 Luke A. Gilbert,1,3,4,* and Jonathan S. Weissman1,2,7,19,*
1Department of Cellular and Molecular Pharmacology, University of California, San Francisco, CA 94158, USA
2Howard Hughes Medical Institute, University of California, San Francisco, CA 94158, USA
3Department of Urology, University of California, San Francisco, CA 94158, USA
4Helen Diller Family Comprehensive Cancer Center, University of California, San Francisco, CA 94158, USA
5Tetrad Graduate Program, University of California, San Francisco, CA 94158, USA
6Medical Scientist Training Program, University of California, San Francisco, CA 94158, USA
7Whitehead Institute for Biomedical Research, Massachusetts Institute of Technology, Cambridge 02142, USA
8Department of Pathology, Massachusetts General Hospital and Harvard Medical School, Boston, MA 02114, USA
9Broad Institute of MIT and Harvard, Cambridge, MA 02139, USA
10Center for Cancer Research, Massachusetts General Hospital, Boston, MA 02129, USA
11Institute for Neurodegenerative Diseases, University of California, San Francisco, CA 94158
12Center for Personal Dynamic Regulomes, Stanford University, Stanford, CA 94305, USA
13Chan Zuckerberg Biohub, San Francisco, CA 94158, USA
14Howard Hughes Medical Institute, Stanford University, Stanford, CA 94305, USA
15Department of Biochemistry and Biophysics, University of California, San Francisco, CA 94158, USA
16Department of Pediatric Oncology, Dana-Farber Cancer Institute, Boston, MA 02215, USA
17Division of Hematology/Oncology, Boston Children’s Hospital, Boston, MA 02215, USA
18Present Address: Department of Pharmacology and Cecil H. and Ida Green Center for Reproductive Biology Sciences, UT Southwestern
Medical Center, Dallas, TX 75390, USA
19Lead Contact
*Correspondence: luke.gilbert@ucsf.edu (L.A.G.), weissman@wi.mit.edu (J.S.W.)
https://doi.org/10.1016/j.cell.2021.03.025

SUMMARY

A general approach for heritably altering gene expression has the potential to enable many discovery and
therapeutic efforts. Here, we present CRISPRoff—a programmable epigenetic memory writer consisting of
a single dead Cas9 fusion protein that establishes DNA methylation and repressive histone modiﬁcations.
Transient CRISPRoff expression initiates highly speciﬁc DNA methylation and gene repression that is
maintained through cell division and differentiation of stem cells to neurons. Pairing CRISPRoff with
genome-wide screens and analysis of chromatin marks establishes rules for heritable gene silencing.
We identify single guide RNAs (sgRNAs) capable of silencing the large majority of genes including those
lacking canonical CpG islands (CGIs) and reveal a wide targeting window extending beyond annotated
CGIs. The broad ability of CRISPRoff to initiate heritable gene silencing even outside of CGIs expands
the canonical model of methylation-based silencing and enables diverse applications including
genome-wide screens, multiplexed cell engineering, enhancer silencing, and mechanistic exploration of
epigenetic inheritance.

INTRODUCTION

Advances in gene editing have transformed our ability to modify
the human genome. In particular, clustered regularly interspaced
short palindromic repeats (CRISPR)-CRISPR-associated protein
9 (Cas9) and other CRISPR systems can be programmed with a
single guide RNA (sgRNA) to introduce DNA breaks at a speci-
ﬁed site to inactivate gene function or to stimulate precise DNA

editing by homology-directed repair (Knott and Doudna, 2018).
Additionally, base and prime editing strategies allow for precise
DNA sequence modiﬁcations but generally rely on one or more
DNA single strand nicks (Anzalone et al., 2020). These technolo-
gies have been optimized for targeted changes in the underlying
DNA sequence and are therefore ideally suited for repairing
or introducing pathogenic mutations. However, the reliance
on endogenous DNA repair machinery presents challenges,

Cell 184, 2503–2519, April 29, 2021 ª 2021 Elsevier Inc. 2503

ll

because the complexity of these pathways can make it difﬁcult
to limit the outcome to a single desired change (Yeh et al., 2019).
An alternative modality for modulating gene function is to
rewrite the epigenetic landscape to control gene expression
without changing the underlying DNA sequence. We and others
have shown that fusing protein scaffold or enzyme domains to
catalytically inactive dCas9 can enhance (CRISPRa) or repress
(CRISPRi) transcription in mammalian cells (Holtzman and Gers-
bach, 2018; Xu and Qi, 2019). Programmable epigenome editing
is tunable, reversible, and does not require DNA breaks, effec-
tively bypassing the cellular toxicity associated with gene editing
(Jost et al., 2020). However, current programmable epigenome
editing technologies typically rely on constitutive expression of
dCas9-fusion proteins to maintain transcriptional control. As
such, these modalities remain less suitable for therapeutic cell
and organismal engineering.

Recent work has demonstrated that it is possible for epige-
nome editing to write a stable transcriptional program that is
remembered and propagated by human cells without constitu-
tive expression of the programmable epigenetic modulators
(Amabile et al., 2016; Bintu et al., 2016; Park et al., 2019; Van
et al., 2021). In particular, Amabile et al. (2016) showed that it
was possible to heritably silence human genes by recruitment
of a cocktail of DNA methyltransferase and KRAB domains.
However, to date only a small number of endogenous human
loci have been tested for silencing by epigenetic memory writers
(Amabile et al., 2016; O’Geen et al., 2019; Tarjan et al., 2019).
Moreover, previous designs of programmable epigenetic si-
lencers utilize either two or three fusion proteins for each target
gene, which is experimentally cumbersome—especially for mul-
tiplexed gene targeting—and complicates an optimal gene tar-
geting strategy. Furthermore, a TALE-based fusion of KRAB
and the DNMT3A and DNMT3L domains resulted in low efﬁcacy
long-term gene silencing (Mlambo et al., 2018). Thus, it is unclear
how generalizable these approaches are for establishing herita-
ble gene silencing and whether there are genomic features that
are required for writing and maintaining heritable epigenetic
silencing. We hypothesized that an epigenetic editor composed
of a single dead Cas9 fusion would enable us to broadly explore
the biology and utility of heritable epigenetic gene silencing.

Here, we present the design, development, and character-
ization of CRISPRoff, a programmable epigenetic memory
writer protein that can durably silence gene expression. Tran-
sient expression of CRISPRoff writes an epigenetic program
that human cells maintain for more than 450 cell divisions,
highlighting that this form of gene silencing is stable and her-
itable. CRISPRoff epigenetic memories can be reversed
robustly using a multi-partite epigenetic editor we call CRISP-
Ron, which removes DNA methylation and recruits transcrip-
tional machinery. Using genome-wide CRISPRoff screens,
we show that
this approach can durably and speciﬁcally
silence the large majority of protein-coding genes and has a
wide targeting window across gene promoters. Surprisingly,
canonical CpG island annotations are not necessary for stable
gene silencing by CRISPRoff. Last, we demonstrate that
CRISPRoff can be used for silencing enhancers and engineer-
ing gene silencing programs in human stem cells that persist
through differentiation to neurons. More generally, this system

2504 Cell 184, 2503–2519, April 29, 2021

Resource

allows us to broadly explore the biological rules underlying
epigenetic silencing and provides a robust tool for controlling
gene expression, targeting enhancers, and exploring the prin-
ciples of epigenetic inheritance.

RESULTS

Rational design of a single fusion epigenome memory
editor
We designed a CRISPR-based programmable epigenome editor
protein, termed CRISPRoff-V1, composed of ZNF10 KRAB,
Dnmt3A (D3A), and Dnmt3L (D3L) protein domains fused to cata-
lytically inactive S. pyogenes dCas9 (Figure 1A). To test whether
a transient pulse of CRISPRoff epigenetic editing could silence
gene expression durably, we transiently co-transfected
HEK293T cells stably expressing a DNA methylation-sensitive
GAPDH-Snrpn GFP reporter with either CRISPRoff-V1, dCas9-
KRAB (CRISPRi), or dCas9-D3A-3L, along with sgRNAs target-
ing the GAPDH-Snrpn synthetic promoter (Liu et al., 2016;
Stelzer et al., 2015) (Figure 1B). All three epigenetic editor pro-
teins transiently silenced the GFP reporter (Figure 1C). As ex-
pected for a transient transfection, expression of each epige-
netic editor protein was lost over time, which, for dCas9-KRAB
and dCas9-D3A-3L, resulted in restored expression of GFP. By
contrast, for CRISPRoff-V1, gene silencing memory and CpG is-
land (CGI) methylation was maintained long after CRISPRoff
expression was lost (Figure 1C).

Silencing by CRISPRoff-V1 appeared to be meta-stable as
gene expression of the reporter gradually increased with time
(Figure 1C). To stabilize gene silencing memory, we encoded
CRISPRoff with proteolysis-resistant linkers to minimize proteol-
ysis that could result in untethered D3A-D3L and off-target DNA
methylation as previously reported (Galonska et al., 2018;
Hofacker et al., 2020). CRISPRoff variants programmed variably
durable gene silencing (Figures S1A and S1B). Second, we hy-
pothesized that positioning D3A-3L at the N terminus of dCas9
would allow Dnmt3A optimal access to CpG sites for DNA
methylation (Zhang et al., 2018) (Figure S1C). The CRISPRoff-
V2 epigenetic editors we engineered each had similar gene
silencing stability so we used CRISPRoff-V2.1 in all subsequent
experiments (Figures S1D-S1F).

Transient expression of CRISPRoff-V2 programmed a dura-
ble memory of gene silencing for at
least 50 days post-
transfection, with over 80% of transfected cells silencing the
Snrpn-GFP reporter and over 90% silencing the endogenously
(Figures 1E, 1F, and
GFP-tagged gene HIST2H2BE (H2B)
S1G). H2B silencing was accompanied by CGI methylation
(Figure 1G). Notably, starting at 10 days post-transfection,
no CRISPRoff protein was detected (Figure 1E). Transfection
of CRISPRoff-V2 mRNA also silenced expression of
the
endogenously GFP-tagged gene CLTA, supporting that tran-
sient expression of CRISPRoff
leads to effective gene
(Leonetti et al., 2016). These results
silencing (Figure S1H)
demonstrate that CRISPRoff epigenetic memory does not
depend on sustained transgene expression.

To further compare CRISPRoff-V1 and V2, we silenced three
cell surface-localized proteins (ITGB1, CD81, and CD151) that
are not required for cell proliferation or survival. Transfection of

ll

C

80

60

40

20

f
f

o
-

P
F
G
h

t
i

w
s

l
l

e
c
%

0

0

G

CRISPRoff-V1

dCas9-D3A-3L

dCas9-KRAB

5 10 15 20 25 30 35 40
Days post-transfection

1.7 kb
H2B CpG island

targeting sgRNA

NT sgRNA

Resource

A

B

dCas9-KRAB

dCas9

KRAB

dCas9-D3A-3L

dCas9

Dnmt3A 3L

CRISPRoff-V1

KRAB

dCas9

Dnmt3A 3L

CRISPRoff-V2

Dnmt3A 3L

dCas9

KRAB

CRISPRoff

HEK293T
GFP reporter

sgRNA

Sort
transfected
cells

Monitor
gene
silencing

Co-transfect CRISPRoff
and sgRNA vectors

Gapdh

Snrpn GFP

E

100

f
f

o
-
B
2
H
h
t
i

w
s

l
l

e
c
%

218 bp

3 weeks p.t.

V1

V2

ITGB1

CD81

CD151

80

60

40

20

0

0

I

d
e
c
n
e

l
i

s

s

l
l

e
c
%

D

n
o
-
P
F
G

f
f
o
-
P
F
G

H

100

80

60

40

20

f
f
o

e
n
e
g

h
t
i

w
s

l
l

e
c
%

0

sgRNA abc

pool abc

pool abc

pool

50 days post-transfection
0
0

92.5% off

7.5% on

V2

V1

F

)

P
F
B

(

f
f
o
R
P
S
R
C

I

CRISPRoff
expression

10

20

40
Days post-transfection

30

50

H2B-GFP

126bp

126bp

30 days p.t.

single

double

J

d
e
c
n
e

l
i

s

s

l
l

e
c
%

100

80

60

40

20

100

80

60

40

20

0

ITGB1
ITGB1+CD81
ITGB1+CD151
CD81
ITGB1+CD151
CD151

0

CD81*

CD151*+CD81*

K

Population
of ITGB1
silenced cells

L

Triple gene targeting,
pre-selected for ITGB1-off

3.73

2.95

100

off
n=38

on
n=1

15 mos.
p.t.

x
a
M

f
o
%

80

60

40

20

0

14

1
8
D
C

79.3

CD151

2

0 10

3

10

4

10

5

10

CLTA

Figure 1. Durable and multiplexed gene silencing by CRISPRoff
(A) A schematic of dCas9 epigenetic editor fusion proteins that were tested for gene silencing activity. 3L denotes Dnmt3L.
(B) Plasmids encoding dCas9 fusions and sgRNAs were co-transfected into HEK293T cells stably expressing a DNA methylation-sensitive Snrpn-GFP reporter.
Transfected cells were sorted 2 days after transfection and GFP silencing was monitored over time.
(C) A time course comparing GFP silencing activities of CRISPRoff-V1, dCas9-3A-3L, and dCas9-KRAB.
(D) Bisulﬁte PCR analysis of the Snrpn locus before or after CRISPRoff targeting. The white circles indicate unmethylated CpG dinucleotides and black circles
represent methylated CpG dinucleotides. Each row represents one sequencing read. The red square denotes the sgRNA binding site.
(E) A comparison of CRISPRoff-V1 (black) and CRISPRoff-V2 (blue) editors in silencing the endogenously GFP-tagged H2B gene. The dotted lines represent
protein expression of CRISPRoff-V1 and -V2.
(F) A representative ﬂow cytometry plot of H2B-GFP expression of cells at 50 days post-transfection of CRISPRoff V2.
(G) Bisulﬁte sequencing analysis of a 126 bp region of the H2B CpG island. The red square denotes the sgRNA binding site.
(H) Quantiﬁcation of cells with ITGB1, CD81, or CD151 silenced 3 weeks post-transfection (p.t.) of CRISPRoff-V1 or -V2 with individual sgRNAs (a–c) or a pool of
three sgRNAs (a, b, c).
(I) Quantiﬁcation of cells with ITGB1, CD81, and CD151 silenced 30 days p.t. from single or double gene targeting experiments.
(J) Quantiﬁcation of multiplexed triple gene silencing by either gating on ITGB1-off cells then gating for CD81- and CD151-off cells (left bar) or by ﬁrst gating on
ITGB1-off cells, then CD151-off cells, and ﬁnally CD81-off cells (right bar). The asterisks denote the population of cells with the marked gene turned off.
(K) A representative ﬂow cytometry plot of cells targeted for ITGB1, CD81, and CD151 silencing. Cells were ﬁrst gated on ITGB1 silencing and the represented
population displays CD81 and CD151 silencing.
(L) A histogram plot of CLTA expression at 15 months p.t. showing 38 clones that retained CLTA repression and one clone that reactivated CLTA expression.
The mean values in (C), (E), and (H)–(J) were measured from three independent experiments. Error bars represent SD of the mean.
See also Figures S1 and S2 and Tables S6 and S7.

Cell 184, 2503–2519, April 29, 2021 2505

ll

A

12

) 14
M
P
T
2
g
o
l
(

10

d
e
t
c
e
f
s
n
a
r
t
n
U

8

6

4

2

0

B

)

M
P
T
2
g
o
l
(

A
N
R
g
s

1
B
G
T

I

14

12

10

8

6

4

2

0

0

C
) 14
M
P
T
2
g
o
l
(

10

12

8

6

4

2

0

A
N
R
g
s

1
8
D
C

ITGB1

Resource

D
) 14
M
P
T
2
g
o
l
(

10

12

A
N
R
g
s

1
5
1
D
C

CD81

8

6

4

2

CD151

0

0

0

2.5 5.0 7.5 10.0 12.5

Non-targeting sgRNA (log2 TPM)

2.5 5.0 7.5 10.0 12.5

0

2.5 5.0 7.5 10.0 12.5

2.5 5.0 7.5 10.0 12.5

Non-targeting sgRNA (log2 TPM) Non-targeting sgRNA (log2 TPM) Non-targeting sgRNA (log2 TPM)

l

e
u
a
v
-
p

0
1
g
o

l

-

300

250

200

150

100

50

0

CD81

250

CD151

200

150

l

e
u
a
v
-
p

0
1
g
o

100

l

-

50

0

–4

–2

2
0
log2 fold change

–6

–4

0
–2
log2 fold change

2

4

CLTA

100

l

e
u
a
v
-
p

0
1
g
o

l

-

80

60

40

20

0

–6

–4

ITGB1

120

100

l

e
u
a
v
-
p

0
1
g
o

l

-

80

60

40

20

0

–2

2
log2 fold change

0

4

–6

–2

2
–4
log2 fold change

0

E

l

)
e
u
a
v
-
p
(
0
1
g
o
l
-

0
4

0
2

0

0
2
-

0
4
-

higher in T

higher in NT

1
r
h
c

2
r
h
c

3
r
h
c

4
r
h
c

5
r
h
c

6
r
h
c

7
r
h
c

8
r
h
c

9
r
h
c

0
1
r
h
c

1
1
r
h
c

2
1
r
h
c

3
1
r
h
c

4
1
r
h
c

5
1
r
h
c

6
1
r
h
c

7
1
r
h
c

8
1
r
h
c

9
1
r
h
c

0
2
r
h
c

1
2
r
h
c

2
2
r
h
c

X
r
h
c

F

5 kb

Untr., R1

Untr., R2

f
f
o
R
P
S
R
C
+

I

NT, R1

NT, R2

T, R1

T, R2

CpG island

CCIN

G

10 kb

5

y
a
d

0
3

y
a
d

Targeting

Non-targeting

Input

Targeting

Non-targeting

Input

CpG island

Transcript
annotation

HIST2H2BE

2506 Cell 184, 2503–2519, April 29, 2021

sgRNA

HIST2H2AC, HIST2H2AB

BOLA1 (TSS2)

SV2A

BOLA1 (TSS1)

[0-1]

[0-1]

[0-1]

[0-1]

[0-1]

[0-1]

CLTA

GNE

H

l

e
u
a
v
-
p

d
e
t
s
u
d
a

j

0
1
g
o
l
-

6

5

4

3

2

1

0

30 days post-transfection
BOLA1 TSS1

HIST2H2BE

HIST2H2AC

HIST2H2AB

−4

BOLA1 TSS2

−2

0
2
log2 Fold Change

4

(legend on next page)

Resource

ll

CRISPRoff-V1 with one sgRNA silenced each target gene in a
fraction of cells and a pool of three sgRNAs improved silencing
ITGB1 and CD81 (Figure 1H). CRISPRoff-V2 improves
of
silencing of each gene, with at least 80% silencing at 3 weeks
post-transfection (Figure 1H).

Durable and multiplexed silencing of endogenous genes
We demonstrated the efﬁcacy of CRISPRoff-V2 in a variety of
cell
types, namely induced pluripotent stem cells (iPSCs),
HeLa, U2OS, and K562 (as a doxycycline-inducible system)
(Figures S2A–S2D). We further show that CRISPRoff can be
programmed by orthogonal DNA binding proteins: dCas9 from
S. aureus (dSauCas9) and dCas12a from Lachnospiracea
(dLbCas12a) (Figures S2E and S2F). Silencing with dLbCas12a
was improved when three crRNAs (CRISPR RNAs) were
that can be processed by
encoded as a single transcript
dLbCas12a into individual crRNAs, suggesting a route to multi-
plexed gene silencing.

To explore multiplexed silencing of endogenous human genes
with S. pyogenes-based CRISPRoff, we targeted ITGB1, CD81,
and CD151 in two, three, and four gene combinations (Figures
1I–1K and S1I–S1K). At 30 days post-transfection, we observed
robust multiplexed gene silencing of each gene combination
(Figure 1I). We observed that cells that silenced one gene have
a higher likelihood of silencing the other targeted genes (Figures
1I–1K, S1I, and S1K). For example, when co-targeting ITGB1 and
CD81, cells that successfully silenced ITGB1 had a 25-fold
higher percentage of cells that also silenced CD81 compared
to cells that failed to silence ITGB1 (Figure 1I).

To measure long-term maintenance of epigenetic memory,
we targeted the endogenous CLTA gene and followed CLTA
expression in single cell clones. Remarkably, at 15 months
post-transfection or after (cid:1)450 cell divisions, 38 out of 39 clones
maintained silencing of CLTA (Figure 1L).

Epigenome editing is highly speciﬁc
To assess the speciﬁcity of CRISPRoff, we performed RNA
sequencing (RNA-seq) of cells 33 days post-transfection of
CRISPRoff and sgRNAs targeting ITGB1, CD81, and CD151 or
a negative control sgRNA. Comparison of untransfected cells
with cells transfected with CRISPRoff show minimal off-target

gene knockdown (Figure 2A). CRISPRoff targeting of ITGB1,
CD81, and CD151 were highly speciﬁc and showed near com-
plete repression of the targeted gene (Figures 2B–2D and
S3A). RNA-seq analyses of three other cell lines with an endog-
enously GFP-tagged gene repressed by CRISPRoff (RAB11A,
CLTA, and H2B) also showed robust and highly speciﬁc tran-
script knockdown (Figures S3B–S3D). Analysis of neighboring
genes within a 1-Mb window from the target gene showed no
signiﬁcant changes in gene expression (Figures S3E and S3F).
When analyzing the datasets from CRISPRoff
targeting of
ITGB1, CD81, and CD151, we observed 1–3 non-target tran-
scripts with a log2 fold-change >2 and adjusted p value <0.5 in
each gene knockdown experiment, albeit at much lower magni-
tude compared to the targeted gene (Table S1). Differential
expression of non-targeted transcripts may be due to indirect ef-
fects associated with target gene knockdown or off-target
CRISPRoff activity.

We assessed CRISPRoff DNA methylation speciﬁcity by whole
genome bisulﬁte sequencing (WGBS) 30 days post-silencing of
CLTA (Figure S3G). We detected a single dominant gain in
DNA methylation at the CLTA promoter, in a 1.5-kb window
across the CLTA promoter, highlighting the high speciﬁcity of
CRISPRoff (Figure 2E). We did not detect spreading of DNA
methylation into the closest neighboring genes (Figure 2F).

Consistent with previous analyses of DNA methylation in cells
treated with DNMT-based epigenetic editors, we observed
modestly higher global DNA methylation in CRISPRoff-trans-
fected cells (<2%)
(Galonska et al.,
(Figures S3H and S3I)
2018; O’Geen et al., 2019). However, global DNA methylation
also varied between cell clones not exposed to CRISPRoff to a
similar degree, and the differences in local DNA methylation pat-
terns at non-target DNA sites between cell clones was greater
than any of the modest, non-speciﬁc changes in methylation
seen following expression of CRISPRoff (Figures S3I and S3J).
To examine whether possible CRISPRoff sgRNA-dependent or
-independent off-target DNA methylation could alter gene
expression, we inspected the top 10 most differentially methyl-
ated DNA regions (Table S2). We did not detect any transcrip-
tional differences for genes at or near the top 10 non-target
differentially methylated regions (Figures S3K and S3L; Table
that any off-target
S2). Thus, our WGBS data suggest

Figure 2. Highly speciﬁc and robust transcriptional silencing by CRISPRoff
(A–D) RNA-seq plots of HEK293T cells transfected with CRISPRoff and non-targeting (NT) sgRNAs compared to sgRNAs targeting (B) ITGB1, (C) CD81, or (D)
CD151. A comparison of untransfected cells and CRISPRoff with NT sgRNA is shown in (A). The volcano plots (bottom) display the targeted genes as the most
signiﬁcantly repressed transcripts globally. The data are representative of the average of two independent replicates.
(E) A Manhattan plot displaying differentially methylated CpGs between cells treated with CRISPRoff and CLTA-targeting or NT sgRNAs (30 days post-trans-
fection) analyzed by WGBS. Red dots represent CpGs that gained DNA methylation in targeting sgRNA cells and blue dots represent CpGs that gained DNA
methylation in NT sgRNA cells. The arrow denotes the genomic position of CLTA.
(F) A comparison of CpG methylation along a 55-kb window that includes the CLTA locus. Tracks labeled ‘‘Untr.’’ represent untransfected cells; the ‘‘NT’’ tracks
represent cells transfected with CRISPRoff and non-targeting sgRNA; and the ‘‘T’’ tracks represent cells transfected with CRISPRoff and targeting sgRNA. R1
and R2 represent two technical replicates. Red marks represent methylated (beta-value >0.5) and the blue marks represent unmethylated (<0.5) CpG di-
nucleotides. CpG islands are shown in green.
(G) A comparison of H3K9me3 ChIP-seq signal across the H2B gene in cells transfected with CRISPRoff and H2B-targeting (purple) or NT sgRNAs (blue) taken at
5 days and 30 days p.t. The sgRNA binding site is denoted along with the CpG islands and neighboring genes. The BOLA1 gene contains two annotated
transcriptional start sites, labeled TSS1 and TSS2.
(H) Volcano plot comparing H3K9me3 ChIP-seq data between CRISPRoff transfected with either H2B-targeting or NT sgRNAs. Red dots highlight the genes
proximal to the H2B target.
See also Figure S3 and Tables S1, S2, and S6.

Cell 184, 2503–2519, April 29, 2021 2507

ll

methylation differences are infrequent and unlikely to modulate
gene expression or cellular phenotypes.

Last, we used chromatin immunoprecipitation sequencing
(ChIP-seq) to proﬁle changes in repressive H3K9me3 modiﬁca-
tions after CRISPRoff targeting of the HIST2H2BE (H2B) gene.
We detected a strong increase in H3K9me3 within an (cid:1)5 kb re-
gion across the H2B promoter at 5 days post CRISPRoff trans-
fection that was maintained at 30 days, demonstrating the stable
propagation of H3K9me3 and DNA methylation as discussed
further below (Figure 2G). Comparing H2B-targeting and non-
targeting sgRNA conditions showed that the most signiﬁcant
gain of H3K9me3 occurred at the H2B locus and three neigh-
boring genes: HIST2H2AC, HIST2H2AB, and BOLA1 (Figure 2H).
We detected knockdown of HIST2H2AC expression whereas
sequencing reads mapping to HIST2H2AB were not detected
in our RNA-seq data (Table S1). We did not detect transcriptional
knockdown of BOLA1 (Table S1). These data, coupled with
whole genome bisulﬁte sequencing data that showed conﬁne-
ment of CpG methylation, highlight the transcriptional and epige-
nomic speciﬁcity of CRISPRoff, while also documenting local
epigenetic spreading and maintenance from the target site of
establishment.

Gene silencing is reversible by targeted DNA
demethylation
An attractive property of epigenome editing is the potential for
reversibility (Amabile et al., 2016; Holtzman and Gersbach,
2018; Liu et al., 2016; Xu and Qi, 2019). To test the reversibility
of CRISPRoff-mediated gene silencing, we used Cas9-medi-
ated gene editing to inactivate DNMT1—the main DNA
methylation maintenance enzyme in mammalian cells—in cells
where we had previously silenced H2B, CLTA, or the GAPDH-
Snrpn GFP reporter. At 9 days post DNMT1 knockout, 60%–
80% of cells reactivated gene expression (Figure S4A). Simi-
larly, treatment of cells with a small molecule inhibitor of
reactivated
DNMT1,
CLTA gene expression (Figure S4B). These results demon-
strate that depletion of DNA methylation is sufﬁcient
to
reverse CRISPRoff-mediated gene silencing and motivated
us to optimize programmable tools for
reactivation of
CRISPRoff-silenced genes.

5-aza-20-deoxycytidine

(5-aza-dC),

DNA methylation of a cytosine within a cytosine-guanine dyad
can be actively removed by the TET (ten-eleven translocation)
family enzymes, which have been repurposed for programmable
demethylation of human gene promoters for gene activation
(Holtzman and Gersbach, 2018; Maeder et al., 2013; Xu et al.,
2016). We tested whether we could reactivate CRISPRoff-
silenced genes by targeted DNA demethylation of CLTA. Initially,
we used a previously reported dCas9 fusion to the TET1 DNA de-
methylase catalytic domain (TETv1) (Liu et al., 2016). We co-
transfected plasmids expressing TETv1 and sgRNAs targeting
the CLTA promoter, measured GFP over time, and observed re-
activation of gene expression in 20% of cells (Figures 3A–3C and
S4C). To improve reactivation, we optimized the fusion protein
by repositioning TET1 at the N terminus of dCas9 and encoding
XTEN linkers between TET1 and dCas9. Separating TET1 and
dCas9 with an 80 amino acid XTEN80 linker (TETv4) resulted in
stable CLTA reactivation in more than 70% of cells (Figures 3C

2508 Cell 184, 2503–2519, April 29, 2021

Resource

and 3D). Gene reactivation was achieved in up to 60% of
TETv4-transfected cells with one sgRNA sequence and was
improved by pooling three sgRNAs across the promoter (Fig-
ure S4C). Bisulﬁte sequencing of the CLTA locus before and after
dCas9-TET-mediated reactivation showed that the CLTA CGI
was nearly completely demethylated after CLTA reactivation
(Figures 3E and S4D).

We observed that CLTA reactivation consistently peaks then
stabilizes starting at 9 days post-TET1 transfection (Figure 3C).
In an effort to modulate the kinetics of reactivation, we designed
a system called CRISPRon, composed of TETv4, a previously
reported modiﬁed sgRNA that encodes two MS2 stem loop
sequences, and the MS2 coat protein (MCP) fused to various
combinations of the transactivator domains VP64, p65-AD,
and Rta (Chavez et al., 2015; Konermann et al., 2015) (Figures
3F and S4E). We ﬁrst conﬁrmed that co-expression of dCas9
and MCP-transactivator fusion proteins could increase tran-
scription of the endogenously expressed CLTA gene, indicating
that these fusion proteins are functional for recruiting the tran-
scriptional machinery (Figure S4F).

We then expressed negative control (NT) or CLTA-targeting
sgRNAs with various CRISPRon combinations or TETv4 only in
CLTA silenced cells and monitored CLTA expression over time.
We observed that select CRISPRon combinations, such as
TETv4 with p65-Rta and TETv4 with VPR, robustly reactivated
CLTA expression within 2 days (Figure 3G). At later time points,
a CRISPRon combination of TETv4 and Rta reactivated CLTA
expression in a larger fraction of cells relative to TETv4 (Fig-
ure S4G). By 28 days post-transfection, the median ﬂuorescence
of reactivated CLTA-GFP was signiﬁcantly higher with CRISP-
Ron combinations of TETv4 with Rta and TETv4 with p65-Rta
compared to TETv4 only (Figure 3H). We did not detect TETv4
or MCP fusion protein expression at this time point. As a further
control, co-expressing the MCP transactivator fusions with
dCas9 (no TET), or a single fusion dCas9-VPR, showed only tran-
sient activation of CLTA and by 10 days post-transfection, CLTA
levels reverted to the silenced state (Figure S4H). Together,
these results show that our optimized TET1-dCas9 fusion pro-
teins can robustly reactivate CRISPRoff-silenced genes and
that co-recruitment of various transactivator domains modulates
the kinetics of reactivation.

Genome-wide targeting of CRISPRoff
The simple design of CRISPRoff motivated us to perform
pooled, genome-wide screens to determine its generalizability
for silencing genes in the human genome. We designed a sgRNA
library that targets over 20,000 protein-coding genes and in-
cludes (cid:1)1,000 non-targeting sgRNAs (Horlbeck et al., 2016a;
Replogle et al., 2020). We constructed the sgRNA library to
encode two unique protospacers targeting the same gene per
lentiviral vector, because our experiments show improvement
in CRISPRoff activity when using multiple sgRNAs targeting
the same gene (Replogle et al., 2020) (Figure 4A; Table S3).

We performed growth-based pooled screens because gene
essentiality datasets are available from previous functional ge-
nomics efforts, allowing us to compare the performance of
CRISPRoff to other genome-wide dropout screens. To perform
a CRISPRoff pooled screen, we packaged the sgRNA library

A

C

F

G

s

l
l

e
c
d
e
t
a
v
i
t
c
a
e
r

A
T
L
C
%

e
g
n
a
h
c

l

d
o
F

80

60

40

20

0

0

5

TETv4

)
s

l
l

t

e
c
d
e
a
v
i
t
c
a
e
r

A
T
L
C
%

(

60

40

20

0

Resource

ll

TETv1

TETv2

dCas9

TET1

dCas9

XTEN16

TET1

TETv3

TET1 XTEN16

dCas9

TETv4

TET1

XTEN80

dCas9

D

C
S
S

TETv4

TETv3

TETv2
TETv1

30

10

15

25
Days post-transfection

20

B

TET1 CD

CLTA-GFP
silenced

TETv4, 28d p.t.

74%
reactivated

dCas9

sgRNA

E

CLTA-GFP
reactivated

pre TET1-dCas9 treatment

post TET1-dCas9 treatment

CLTA expression

transactivator
domains

monopartite

bipartite

tripartite

VP64

VP64-p65

VP64-p65-Rta (VPR)

p65-Rta

**

n.s.

28d p.t.
*

***

**

****

Untr.
****

GFP-
GFP+

MS2 coat protein (MCP)
sgRNA + 2x MS2 aptamers

2d p.t.

NT
sgRNA-a

p65

Rta

H

)
.

.

u
a
(

e
c
n
e
c
s
e
r
o
u

l
f

-

P
F
G
A
T
L
C

6000

4000

2000

0

Untr.

TETv4

VP64

p65

VP64-p65

Rta

VPR
p65-Rta

+ TETv4

TETv4

VP64

p65

VP64-p65

Rta

VPR

p65-Rta

CLTAon

+ TETv4

Figure 3. CRISPRon reverses silenced genes by combining DNA demethylation and transcriptional activators
(A) A schematic of the four TET1 catalytic domain fusions to dCas9 (TETv1-v4) that were tested for reactivation of CRISPRoff-silenced genes.
(B) CRISPRoff-silenced CLTA-GFP cells were transfected with plasmids encoding TETv1-4 and targeting or NT sgRNAs to assess reactivation.
(C) A time course of CLTA reactivation after transfection of each of the four TET fusions in (A). The mean values were measured from three independent ex-
periments. Error bars represent SD.
(D) A representative ﬂow cytometry plot of CLTA reactivation measured at 28 days p.t. of TETv4 and targeting sgRNAs.
(E) Bisulﬁte-PCR analysis of the CLTA CGI after reactivation by TETv1 shows high levels of demethylated CpG cytosines (white circles) compared to CRISPRoff-
silenced cells.
(F) A schematic of the TETv4 and transactivator ribonucleoprotein complex mediated by a sgRNA encoding two MS2 RNA aptamers. Transactivator domains
include monopartite, bipartite, and tripartite architectures of VP64, p65, and Rta.
(G) Fold change in the fraction of CLTA-GFP reactivated cells compared to TETv4 alone, measured 2 days p.t. The data are calculated from the mean of eight
technical replicates from three independent experiments.
(H) Comparison of the expression of CLTA-GFP in single cells, measured by cytometry 28 days p.t. with CRISPRon. The data are aggregated from three technical
replicates. *p value <1e(cid:3)4, **p value <1e(cid:3)20, ***p value <1e(cid:3)100, and ****p value = 0, relative to the GFP-positive population in the TETv4 condition by the
Wilcoxon rank-sum test. Unsilenced CLTA-GFP cells are provided as a benchmark for wild-type expression levels.
See also Figure S4 and Tables S6 and S7.

into lentiviral particles then transduced and selected HEK293T
cells such that on average each cell expresses one sgRNA vec-
tor. We then transiently transfected this pool of cells with plas-
mids encoding CRISPRoff and sorted cells that expressed the
CRISPRoff protein. We harvested a population of CRISPRoff-

transfected cells as a time zero (T0) sample and continued to
passage a population of CRISPRoff-transfected cells for at least
10 cell doublings (T10), followed by deep sequencing of genomic
DNA at both time points to read out and quantify the sgRNA se-
quences as a proxy for cell count. We inferred that sgRNAs that

Cell 184, 2503–2519, April 29, 2021 2509

A

C

E

F

ll

dual sgRNA
vector

B

HEK293T

Resource

sgRNA-1

sgRNA-2

Infect
sgRNA
library

Transfect
CRISPRoff
or mutant

Sort
transfected
cells

Passage
for 10 cell
doublings

phenotype
score (γ)

=

log2sgRNA enrichment
doubling differences

f
f
o
-
A
T
L
C
h
t
i

w
s

l
l

e
c
%

80

60

40

20

0

)
γ
(
e
p
y
t
o
n
e
h
P

0.1

0.0

−0.1

−0.2

−0.3

−0.4

−0.5

−0.6

CRISPRoff
CRISPRoff-D3A mutant
dCas9-KRAB (CRISPRi)

0 2 4 6 8 10 12 14 16 18
Days

CRISPRoff

CRISPRoff mutant

Essential
genes

Nonessential
genes

Essential
genes

Nonessential
genes

all genes
negative control
olfactory genes

Y chromosome

D

)
γ
(

e
p
y
t
o
n
e
h
p

f
f

o
R
P
S
R
C

I

0.2

0.0

-0.2

-0.4

-0.6

-0.8

R1 R2 R1 R2

R1 R2

R1 R2

-0.8

-0.6

-0.4

-0.2

-0.0

0.2

CRISPRoff mutant phenotype (γ)

1.0

0.8

0.6

0.4

0.2

0.0

t

e
a
r
e
v
i
t
i
s
o
p
e
u
r
T

CRISPRoff
CRISPRoff mutant

0.0

0.2
0.4
False positive rate

0.6

0.8

1.0

G

)
γ
(
e
p
y
t

o
n
e
h
p

f
f

o
R
P
S
R
C

I

e
n
e
g
g
n
i
r
o
b
h
g
e
n

i

f

o

−0.2

−0.3

−0.4

−0.5

−0.6

−0.7

10 bp

100 bp

1 kb

10 kb

100 kb

1 Mb

10 Mb

Distance to neighbor essential gene

Figure 4. Genome-wide gene silencing by CRISPRoff
(A) A schematic of the dual sgRNA lentiviral vector used in the CRISPRoff genome-wide screens that contains two unique sgRNAs targeting the same gene.
(B) A schematic of a pooled genome-wide screen to determine the targeting landscape of CRISPRoff.
(C) A time course of CLTA expression in HEK293T after transfection of dCas9-KRAB (gray), CRISPRoff-V2 (black), or mutant CRISPRoff-D3AE765A (orange).
(D) A comparison of phenotype scores (g) between CRISPRoff (y axis) and CRISPRoff mutant (x axis) screens. Three types of expected negative controls are
highlighted as negative control pseudo-genes (blue), olfactory genes (orange), and Y chromosome genes (green).
(E) A violin plot of the phenotype scores (g) for genes deﬁned as essential or nonessential from DepMap. Each replicate screen is plotted for CRISPRoff (green)
and CRISPRoff mutant (orange).
(F) A plot of true and false positive rates of genes deﬁned as essential by DepMap.
(G) A plot illustrating the distance of an essential gene hit, deﬁned as having a g %(cid:3)0.2, from the nearest essential gene hit. Each dot corresponds to a gene hit’s
nearest neighboring essential gene, with the x axis showing the distance between the two genes and the y axis as the neighboring gene’s phenotype score.
See also Figure S5 and Tables S3 and S6.

were depleted in the T10 population relative to T0 are active,
because these sgRNAs effectively silenced the expression of
essential genes and drop out of the population (Figure 4B). As
a control, we performed in parallel an identical screen with a
CRISPRoff variant encoding the Dnmt3AE765A mutation, which
is catalytically inactive and thus unable to maintain durable

gene silencing and instead mirrors the transient silencing effect
of CRISPRi (Figure 4C). By comparing these two screens, we
identiﬁed sgRNAs in the CRISPRoff screen that silenced gene
expression in a manner that is DNA methylation-dependent.

Analysis of the phenotype score (g, with a more negative score
indicating a stronger growth defect) for each gene showed that

2510 Cell 184, 2503–2519, April 29, 2021

Resource

CRISPRoff expression reproducibly led to a more pronounced
growth defect phenotype compared to the CRISPRoff mutant
(Figures 4D, 4E, and S5A–S5C; Table S3). A large set of
genes showed drastic growth defects that were speciﬁc to
CRISPRoff-mediated knockdown, highlighting the durable
gene silencing effect of CRISPRoff. We also detected a subset
of genes with comparable phenotypes between the two screens,
likely due to their essentiality upon transient knockdown by the
CRISPRoff mutant (Figure 4D). We evaluated the speciﬁcity of
silencing across the screens by analyzing the phenotype scores
of control sgRNAs. Almost all negative control sgRNAs or
sgRNAs targeting unexpressed genes (olfactory or Y chromo-
some genes) had little to no measured phenotype (1% with
g <(cid:3)0.2) (Figure 4D).

To evaluate the generality of CRISPRoff for gene silencing, we
assessed the phenotype scores of genes that we expect to have
growth phenotypes upon knockdown. Analysis of genes associ-
ated with DNA replication and the ribosome, which are predicted
to be highly essential for cell proliferation, were among the most
severe growth phenotypes (Figures S5D and S5E). We then
analyzed the phenotypes for common essential genes that are
required for cell proliferation or survival in most cancer cell lines
(Meyers et al., 2017). The growth defects of these genes were far
more pronounced in CRISPRoff (median g = (cid:3)0.2) compared to
the CRISPRoff mutant (median g = (cid:3)0.05), whereas the majority
of nonessential genes did not produce growth phenotypes (Fig-
ure 4E). The CRISPRoff mutant resulted in weak phenotype
scores due to the lack of DNA methylation-dependent durable
gene silencing. Collectively, the CRISPRoff screen resulted in
high positive rate of calling essential genes with low false-posi-
tive gene hits, suggesting that CRISPRoff has the ability to
silence the majority of genes in the human genome (Figure 4F).
Programmable epigenome editors can initiate epigenetic
marks that spread from the site of establishment (Hathaway
et al., 2012; Stepper et al., 2017). We wondered whether some
CRISPRoff gene hits were due to a ‘‘neighboring gene effect’’
caused by DNA methylation spreading from a nearby essential
gene. We cataloged gene ‘‘hits’’ (deﬁned by genes with pheno-
type scores of (cid:3)0.2 or lower) and determined their linear dis-
tance on the genome from the nearest gene hit. Although a sub-
set of gene hits were within a 1-kb window distance, the majority
of CRISPRoff hits were over 10 kb from the nearest gene hit (Fig-
ure 4G). Because CpG islands are largely restricted within a 1- to
2-kb window (Deaton and Bird, 2011), we postulate that the ma-
jority of our observed gene hits are speciﬁc to the targeted gene
promoter, consistent with the speciﬁcity demonstrated in our
CRISPRoff RNA-seq, WGBS, and ChIP-seq experiments.

CRISPRoff silencing of genes that lack CGI annotations
It is estimated that (cid:1)30% of human genes are not associated
with a promoter CpG island (CGI) (Deaton and Bird, 2011). Given
the observed generality of CRISPRoff for gene silencing, we
wondered whether genes that lack CGI annotations can be
silenced durably by CRISPRoff. Surprisingly, we found over
300 genes without CGI annotations with growth defects upon
knockdown (g %(cid:3)0.1) by CRISPRoff, with 160 producing growth
phenotypes g %(cid:3)0.2 (Figure 5A). The majority of these genes
had weak to no phenotype in the CRISPRoff mutant screen, indi-

ll

cating that their knockdown is DNA methylation dependent
despite the absence of an annotated CGI.

To validate our observation that CRISPRoff can silence genes
without annotated CGIs, we endogenously tagged ﬁve genes
with no annotated CGI—CALD1, DYNC2LI1, LAMP2, MYL6,
and VPS25—in HEK293T with mNeonGreen (mNG) and as-
sessed durable silencing by CRISPRoff (Figure 5B). At 14 days
post-transfection of CRISPRoff, we detected a large percentage
of cells that turned off DYNC2LI1, LAMP2, MYL6, and VPS25
(Figure 5C). We did not detect stable silencing of CALD1 at
14 days, potentially due to its promoter being almost completely
devoid of CpG dinucleotides or non-optimal sgRNAs used in the
experiment (Figure 5C). Transfection of the CRISPRoff mutant
did not silence gene expression durably. Treatment of DYNC2LI1
and LAMP2-off cells with TETv4 led to reactivation of gene
expression in (cid:1)70% of cells (Figure 5D).

We isolated LAMP2, DYNC2LI1, and MYL6 silenced cells and
proﬁled the DNA methylation status of the gene promoter by
bisulﬁte sequencing. Cytosines within a CG context were
highly methylated in silenced cells (Figure 5E). We passaged
DYNC2LI1, LAMP2, and MYL6-silenced cells for 30 days and
observed stable silencing of DYNC2LI1 and LAMP2 (Figures
5F–5I). We also followed 33 single cell clones with DYNC2LI1
silenced and all clones repressed the gene by 50 days post-
transfection with CRISPRoff (Figure 5I). Although MYL6 under-
went silencing associated with DNA methylation at an early
time point, gene expression reactivated to near pre-CRISPRoff
level by day 30. Future studies are needed to understand biolog-
ical features associated with stable versus metastable epige-
netic memory for genes without annotated CGIs.

Last, to probe the extent of DNA methylation across a non-CGI
annotated gene, we performed WGBS of cells with DYNC2LI1
silenced after 30 days. We detected a single dominant gain in
DNA methylation at the DYNC2LI1 promoter (Figure 5J) consist-
ing of an (cid:1)1.2 kb region of the promoter (Figure 5K). Together,
these data establish that epigenetic editing using CRISPRoff is
not limited to genes with canonical CGI annotations and can
be targeted to most genes encoded in the human genome.
Moreover, based on these ﬁndings, we propose that the theoret-
ical framework of CGI gene annotation does not always predict
the presence of functional CpG sites, bolstering the power of
CRISPRoff and CRISPRon for functional testing of CpG methyl-
ation in modulating gene expression.

Targeting rules for CRISPRoff platform
We next explored the targeting landscape of CRISPRoff within
gene promoters. Previously, we and others used sgRNA tiling
screens and machine learning approaches to show that active
sgRNAs for CRISPRi are localized in a narrow window at gene
promoters, particularly at a nucleosome-depleted region imme-
diately downstream of the transcription start site (TSS) (Gilbert
et al., 2014). Despite successfully using these CRISPRi rules to
design the genome-wide CRISPRoff essentiality screens, it re-
mained untested whether the location of effective guides for
CRISPRoff was similarly limited to this narrow window.

To empirically determine the targeting window of CRISPRoff,
we designed a pooled sgRNA promoter tiling library against a
subset of genes that are essential for cell growth based on

Cell 184, 2503–2519, April 29, 2021 2511

ll

A

)
γ
(
e
p
y
t
o
n
e
h
p

f
f
o
R
P
S
R
C

I

0.2

0.0

−0.2

−0.4

−0.6

−0.8

E

n
o

i
t

100

l

t

a
y
h
e
m
%

50

0

F

f
f

o
e
n
e
g
h

t
i

w
s

l
l

e
c
%

80

60

40

20

0

J

l

)
e
u
a
v
-
p
(
0
1
g
o
l
-

0
4

0
2

0

0
2
-

0
4
-

all genes
non CGI genes

x
a
M

f
o
%

B

C

Resource

CALD1

DYNC2LI1

LAMP2

MYL6

VPS25

mNeonGreen

Parental line

mNG-tagged

80

60

40

20

0

f
f
o
e
n
e
g
h
t
i

w
s

l
l

e
c
%

CRISPRoff

mutant

NT

Targeting

D

80

60

40

20

d
e
t
a
v
i
t
c
a
e
r
s

l
l

e
c
%

CALD1

DYNC2LI1

LAMP2

MYL6

VPS25

0

DYNC2LI1

LAMP2

−0.8

−0.6

−0.4

−0.2

0.0

0.2

CRISPRoff mutant phenotype (γ)

Silenced cells

WT cells

DYNC2LI1

LAMP2

100

50

0

1 3 5 7 9 11 13 15 17

1 3 5 7 9111315171921232527

TSS

TSS

MYL6

100

50

0
1 3 5 7 9 11131517192123252729

CG site

G

100

80

60

40

20

0

DYNC2LI1

10 15 20 25 30

5
Days post-transfection

DYNC2LI1

LAMP2

10 15 20 25 30

5
Days post-transfection

H

80

60

40

20

0

MYL6

CRISPRoff
CRISPRoff mutant

10 15 20 25 30

5
Days post-transfection

I

100

x
a
M

f

o
%

80

60

40

20

0

higher
in T

higher
in NT

1
r
h
c

2
r
h
c

3
r
h
c

4
r
h
c

5
r
h
c

6
r
h
c

7
r
h
c

8
r
h
c

9
r
h
c

0
1
r
h
c

1
1
r
h
c

2
1
r
h
c

3
1
r
h
c

4
1
r
h
c

5
1
r
h
c

6
1
r
h
c

7
1
r
h
c

8
1
r
h
c

9
1
r
h
c

0
2
r
h
c

1
2
r
h
c

2
2
r
h
c

X
r
h
c

DYNC2LI1

TSS

50 days post-transfection

n=33

positive
control (on)

DYNC2LI1 expression

5 kb

5 kb

[0-1]

[0-1]

[0-1]

[0-1]

[0-1]

[0-1]

K
Untr., R1

Untr., R2

f
f

o
R
P
S
R
C
+

I

NT, R1

NT, R2

T, R1

T, R2

Figure 5. CRISPRoff-mediated silencing of genes without promoter CpG island annotations
(A) A plot comparing the phenotype score of genes between the CRISPRoff and CRISPRoff mutant screens with genes that lack a CGI annotation highlighted in red.
(B) Histograms of mNeonGreen ﬂuorescence of ﬁve HEK293T cell lines, each with the indicated gene endogenously tagged with split mNeonGreen.
(C) Quantiﬁcation of cells with CALD1, DYNC2LI1, LAMP2, MYL6, or VPS25 silenced after CRISPRoff or CRISPRoff mutant treatment. The data were measured at
14 days p.t., except for VPS25 that was collected at 11 days p.t. due to a growth defect upon gene knockdown.
(D) Quantiﬁcation of percent of cells with DYNC2LI1 or LAMP2 reactivated after TETv4 treatment with targeting or non-targeting sgRNAs, obtained at 14 days p.t.
(E) CpG methylation proﬁling within the LAMP2, DYNC2LI1, and MYL6 promoters after CRISPRoff treatments. White circles represent the CpG methylation status
of untransfected HEK293T cells. Each dot is an average of eight independent clones.
(F–H) Time course plots of DYNC2LI1 (F), LAMP2 (G), and MYL6 (H) expression after transfection of either CRISPRoff or CRISPRoff mutant. Error bars represent
the SD of three independent replicates.
(I) A histogram of DYNC2LI1 expression in 33 clonal lines, measured at 50 days p.t. A positive control of untransfected cells is labeled.
(J) A Manhattan plot displaying differentially methylated CpGs between cells treated with CRISPRoff and either DYNC2LI1-targeting (labeled T) or non-targeting
sgRNA (labeled NT), as analyzed by WGBS. The arrow points to the genomic location of DYNC2LI1.

(legend continued on next page)

2512 Cell 184, 2503–2519, April 29, 2021

Resource

ll

previous CRISPRi screens in K562 cells and our genome-scale
CRISPRoff screen (Figure S6A). The library tiles PAM-containing
sequences ±1 kb from the TSS of 520 genes (425 with one anno-
tated CGI, 56 with multiple CGIs, and 39 with no annotated CGI;
deﬁned by the presence of a CGI within 2.5 kb of the TSS),
totaling (cid:1)116,000 unique sgRNAs (Figures 6A and 6B; Table
S4). We performed the CRISPRoff screens in HEK293T cells us-
ing the same experimental workﬂow as the genome-wide
screens, in parallel with the CRISPRoff D3AE765A methyltransfer-
ase mutant. We also transduced the sgRNA tiling library into
K562 cells stably expressing dCas9-KRAB and performed a
CRISPRi screen to compare gene silencing mediated by
dCas9-KRAB alone.

To evaluate the screens, we calculated the phenotype score
(g) for the three most active sgRNAs per gene and compared
phenotypes across the three screens. We ﬁrst focused on the
425 genes with one annotated CGI, as these were predicted to
be canonical targets for CRISPRoff-mediated silencing. The
phenotypes for the CRISPRoff screen (median g = (cid:3)0.33) were
more pronounced compared to the CRISPRoff mutant screen
phenotypes (median g = (cid:3)0.15), establishing that strong pheno-
types observed in the CRISPRoff screen are DNA methylation-
dependent (Figure 6C).

To compare the optimal sgRNAs between CRISPRoff and
CRISPRi, we normalized the phenotypes across the screens
and generated an aggregate plot of sgRNA activities relative to
the TSS (Figure 6D). Consistent with our previous work, highly
active sgRNAs for CRISPRi were centered on a narrow window
((cid:1)75 bp) directly downstream of the TSS. Similarly, active
sgRNAs for the CRISPRoff mutant mirrored CRISPRi, which
we expected because the KRAB domain remains functional in
this fusion protein despite the lack of DNA methylation activity.
In contrast, the active CRISPRoff sgRNAs were broadly distrib-
uted across the TSS, notably within a 1-kb window centered
on the TSS. Representative gene analysis of DKC1, GPN2, and
ZCCHC9 shows that even within a single promoter, active
sgRNAs for CRISPRoff are distributed across –500 to +500 bp
from the TSS—a greatly widened targeting window for silencing
compared to CRISPRi (Figures 6E–6G). We also observed effec-
tive sgRNAs outside the CGI that were DNA methylation-depen-
dent (Figure 6G), suggesting that functional CpGs are not neces-
sarily conﬁned to canonical CGIs as observed in our WGBS data.
Our aggregate plot analysis of active sgRNAs targeting the 56
genes with multiple annotated CGIs also shows a broad target-
ing window, similar to genes with one annotated CGI, and
centered at the TSS (Figures S6B and S6C).

Analysis of the 39 genes without promoter CGIs showed many
highly active sgRNAs of comparable phenotype strength to
genes with annotated CGIs (Figure 6C, colored red) and the phe-
notypes were strongly diminished in the CRISPRoff mutant
screen. A representative gene plot of ORC5 shows that similarly
to genes with annotated CGIs, active CRISPRoff sgRNAs are
spread across (cid:3)500 to +500 bp from the TSS (Figure 6H). More-

over, we observed that CRISPRoff has a broadened targeting
window despite the lack of an annotated CGI for these 39 genes
(Figure 6I). Our experiments demonstrate that the optimal win-
dow for CRISPRoff gene silencing is similarly broad for genes
with and without annotated CGIs, likely due to low density
CpG sites that are functional for methylation-dependent gene
silencing as we demonstrated for DYNC2LI1, LAMP2, MYL6,
and VPS25 (Figure 5C).

We observed that active sgRNAs are not evenly distributed but
instead appear in a periodic pattern within the –500 to +500 bp
window, as shown for DKC1, GPN2, and ZCCHC9 (Figures
6E–6G). Overlaying nucleosome occupancy with CRISPRoff
sgRNA activity scores for all genes showed that the most active
sgRNAs are located in nucleosome-depleted regions of gene
promoters, as we and others have shown previously for Cas9
and dCas9-based tools (Figures 6J, 6K, S6D, and S6E) (Horlbeck
et al., 2016b; Isaac et al., 2016).

To validate that the CRISPRoff targeting window is similar for
genes that do not have a growth phenotype upon knockdown,
we designed tiling sgRNA libraries spanning ±2.5 kb from the
TSS to target four endogenous genes: CLTA, H2B, RAB11A,
and VIM. For each custom sgRNA library screen, we utilized
the corresponding HEK293T cell line that expresses the endog-
enously GFP-tagged gene (Leonetti et al., 2016). Each cell line
was transduced with the respective sgRNA library, transfected
with CRISPRoff, and the cells were passaged for 4 weeks to
ensure that gene silencing was durable (Figure S6F). We then
sorted GFP-positive and GFP-negative cell populations for
each screen and processed the samples as described above.
We calculated sgRNA efﬁcacy by identifying sgRNAs in the
gene-off (GFP(cid:3)) population compared to the gene-on (GFP+)
population (Table S5).

Similar to the growth screens, active sgRNAs for CLTA, H2B,
and VIM spanned a large window across the TSS (Figures 6L and
S6G–S6I). Active CRISPRoff sgRNAs for CLTA were within two
distinct regions, with one region upstream of the TSS outside
of the annotated CGI
(Figure S6G). Unexpectedly, sgRNAs
targeting (cid:1)2 kb upstream of the H2B TSS were highly active
(Figure 6L). Similarly, for VIM, active sgRNAs spanned a 2-kb
window ±1 kb from the TSS. By contrast, active sgRNAs for
RAB11A were constricted to a narrow window at the TSS. Over-
laying nucleosome occupancy with sgRNA activity showed that
the RAB11A promoter is nucleosome-dense (Figure S6H). From
these data, we interpret that CRISPRoff accessibility is restricted
by nucleosomes; however, once bound, CRISPRoff can silence
gene expression even when distal to the TSS.

Durable gene silencing is dependent on H3K9me3 and
DNA methylation maintenance
To explore the mechanism underlying CRISPRoff-mediated her-
itable memory, we made use of the wide targeting window across
the H2B promoter to investigate the establishment, spreading,
and maintenance of H3K9me3 histone modiﬁcations and CpG

(K) A view of a 10-kb genomic window containing the DYNC2LI1 locus, highlighting gain of CpG methylation (red) at the promoter in cells transfected with
CRISPRoff and DYNC2LI1-targeting sgRNAs. Tracks labeled ‘‘Untr.’’ represent untransfected cells, the ‘‘NT’’ tracks represent cells transfected with CRISPRoff
and non-targeting sgRNA, and the ‘‘T’’ tracks represent cells transfected with CRISPRoff and targeting sgRNA.
See also Tables S4 and S6.

Cell 184, 2503–2519, April 29, 2021 2513

A

B

E

H

J

f
f

o
R
P
S
R
C

I

i

R
P
S
R
C

I

)
γ
(

0.0

–0.2

–0.4

0.0

–0.2

–0.4

–1000

ll

sgRNA tiling screen

TSS

# guides 116,085

# NT guides 3,790

Total genes 520

One CGI 425

Multiple CGI 56

No CGI 39

C

)
γ
(

I

f
f
o
R
P
S
R
C
T
3
9
2

0.0

−0.1

−0.2

−0.3

−0.4

−0.5

−0.6

Resource

D

One CGI genes

all genes
non CGI genes

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

0.0

–0.2

–0.4

–0.6

–0.8

–1.0

293T CRISPRoff
293T CRISPRoff mutant
K562 CRISPRi

−0.5 −0.4 −0.3 −0.2 −0.1

0.0

293T CRISPRoff mutant (γ)

–1000

–500

0
Position relative to TSS (bp)

500

1000

DKC1

CGI

)
γ
(

0.0

–0.2

–0.4

0.0

–0.2

–0.4

0.0

–0.2

–0.4

GPN2

CGI

F

)
γ
(

0.0

–0.2

–0.4

0.0

–0.2
–0.4

0.0

–0.2
–0.4

G

)
γ
(

0.0

–0.2

–0.4

0.0

–0.2

–0.4

0.0

–0.2

–0.4

ZCCHC9

CGI

–1000

–500

500
0
Position relative to TSS (bp)

1000

–1000

–500

500
0
Position relative to TSS (bp)

1000

–1000

–500

500
0
Position relative to TSS (bp)

1000

f
f

o
R
P
S
R
C

I

t

t

n
a
u
m

i

R
P
S
R
C

I

ORC5

I

No CGI genes

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

0.0

–0.2

–0.4

–0.6

–0.8

–1.0

–1000

293T CRISPRoff
293T CRISPRoff mutant
K562 CRISPRi
–500

0

500

1000

1000

–500

0
Position relative to TSS (bp)

500

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

CGI aggregate

–1.0
–0.8
–0.6
–0.4
–0.2
0.0

MNase
sgRNA

1.0

0.8
0.6

0.4

0.2

M
N
a
s
e
s
g
n
a

i

l

–1000 –500

0

500

1000

Position relative to TSS (bp)

K

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

MNase
sgRNA

–1.0
–0.8
–0.6
–0.4
–0.2
0.0

No CGI genes

1.6

Position relative to TSS (bp)

H2B

CGI

0

–1

–2

L

n

i

e
g
n
a
h
c
d
o
f
2
g
o

l

l

e
c
n
a
d
n
u
b
a
A
N
R
g
s

M
N
a
s
e
s
g
n
a

i

l

1.2

0.8

0.4

1000

–1000 –500

0

500

Position relative to TSS (bp)

–2kb

–1kb

0

1kb

2kb

Position relative to TSS (bp)

Figure 6. Pooled sgRNA tiling screens reveal a wide targetable window of CRISPRoff-mediated gene repression
(A) A schematic of the sgRNA library that tiles PAM-containing sgRNAs within a ±1-kb window from annotated transcription start sites (TSS).
(B) A summary of the number of genes per indicated category that comprise the tiling sgRNA library.
(C) A comparison of the phenotype score (g) for genes with annotated CGI between CRISPRoff (y axis) and CRISPRoff mutant (x axis). Each dot is the average of
the three most active sgRNAs for each gene. The red dots highlight genes that lack a promoter CGI annotation.
(D) An aggregate plot comparing the normalized phenotype score for each sgRNA targeting genes with one annotated CGI. The green line represents screen data
from CRISPRoff in HEK293Ts, orange from CRISPRoff mutant in HEK293Ts, and purple from CRISPRi in K562s.
(E–G) Representative sgRNA activity score proﬁles for DKC1, GPN2, and ZCCHC9 from the indicated screen (y axis). The green bar depicts the annotated CGI
obtained from UCSC Genome Browser.

(legend continued on next page)

2514 Cell 184, 2503–2519, April 29, 2021

Resource

ll

methylation marks. We targeted CRISPRoff
to the TSS
(sgRNA-A) and to a distal site (cid:1)2 kb upstream of the TSS
(sgRNA-B) (Figure S7A). At 30 days post CRISPRoff transfection,
89% of cells maintained H2B silencing when sgRNA-A was deliv-
ered compared to 76% with sgRNA-B (Figure S7B). Using ChIP-
seq, we showed that both sgRNAs induced deposition at day 5
and maintenance at day 30 of H3K9me3 across the locus despite
the (cid:1)2 kb distance between the sgRNA binding sites (Fig-
ure S7C). The acquired H3K9me3 modiﬁcations in CRISPRoff-
treated cells overlapped with the unmethylated CpG region in un-
treated parental cells (bottom track in Figure S7C). In contrast,
deposition and maintenance of H3K9me3 was far weaker with
CRISPRoff bearing the D3A mutation, consistent with the failure
to sustain gene repression with the mutant (Figure S7D).

We next proﬁled CRISPRoff-mediated CpG methylation at the
targeted distal and TSS regions. At day 5, we detected establish-
ment and spreading of CpG methylation from the site of initiation
to a (cid:1)2 kb site from the sgRNA binding site (labeled site 1 and
site 3, Figures S7E and S7F). By day 30, we detected stable
maintenance of DNA methylation at both sgRNA binding sites
(Figures S7G and S7H). We also detected a high degree of
CpG methylation between the sgRNA binding sites, suggesting
a linear movement of spreading from the site of initiation (site
2, Figure S7I). These data, together with our WGBS data, high-
light the orchestration of histone and DNA methylation deposi-
tion, spreading, and maintenance and suggest that there are un-
derlying regulatory principles that likely depend on the genomic
context.

CRISPRoff gene silencing in iPSCs and iPSC-derived
neurons
Due to the utility of stem cells for studying the development and
function of speciﬁc cell types, we employed CRISPRoff
in
induced pluripotent stem cells. We transfected iPSCs with
CRISPRoff and sgRNAs targeting CD81 or a non-targeting con-
trol and found that at 30 days post-transfection, many iPSCs had
stably silenced CD81 (Figures 7A and 7B). Thus, CRISPRoff-en-
coded memory of silencing is stably maintained in stem cells.

We isolated CD81-off iPSCs and differentiated the cells into
neurons, as previously described (Tian et al., 2019) (Figure 7A).
We then measured CD81 protein levels at the neural precursor
cell stage (day 0 of differentiation) and after cells had differentiated
into neurons (8 days post-differentiation). We observed that CD81
remained silenced during and after neuronal differentiation in 90%
of cells (Figures 7C and 7D). A similar fraction of undifferentiated
iPSCs maintained CD81 silencing during the same time course,
suggesting that the reactivation of CD81 in (cid:1)10% of cells was
not due to the differentiation process. We harvested genomic
DNA from CD81-off neurons and detected heavily methylated

promoter CpG dinucleotides compared to neurons treated with
CRISPRoff and a non-targeting sgRNA (Figure 7E).

We next applied CRISPRoff-mediated editing of iPSC-derived
neurons to silence MAPT, a gene that encodes the Tau protein
and is implicated in various neurological diseases (Iqbal et al.,
2016). MAPT is transcriptionally repressed in iPSCs by
H3K27me3 rather than by DNA methylation and H3K9me3 and
its expression increases substantially during neuronal differenti-
ation (Guenther et al., 2010). We hypothesized that CRISPRoff
could write an epigenetic memory of silencing at the MAPT locus
that would persist through neuronal differentiation to silence
MAPT in neurons. We transiently transfected CRISPRoff into
iPSCs along with sgRNAs targeting MAPT or a non-targeting
control. At day 10 of the differentiation protocol, we measured
Tau protein levels and found (cid:1)30% of cells with reduced Tau
expression compared to a non-targeting control (Figures 7F–
H). Together, these data support CRISPRoff-mediated epige-
nome editing as an applicable technology for rewriting gene
expression programs in iPSC-derived cells, especially for modu-
lating gene expression in cells where delivery of gene editing
platforms remains a challenge.

CRISPRoff targeting of enhancer elements
Finally, we explored the potential utility of CRISPRoff
for
silencing promoter-distal elements by targeting enhancers that
control the expression of the PVT1 long noncoding RNA (Cho
et al., 2018; Fulco et al., 2016). We transiently expressed
CRISPRoff in the MDA-MB-231 breast cancer cell
line with
sgRNAs targeting either the PVT1 promoter or at four previously
identiﬁed enhancer elements downstream of the PVT1 promoter:
E1 (+15.5 kb), E2 (+60 kb), E3 (+105 kb), and E4 (+113 kb) (Fig-
ure 7I). We detected a signiﬁcant reduction of PVT1 transcript
levels with sgRNAs targeting E1, E3, and E4 ((cid:1)40%–60%)
compared to 80% knockdown with promoter-targeting sgRNAs
In contrast, parallel experiments using the
(Figure 7J,
CRISPRoff-Dnmt3AE765A mutant resulted in less robust knock-
down (Figure 7J, right). These results highlight the potential
use of CRISPRoff for mapping and dissecting the functions of
enhancer elements and noncoding regulatory elements in the
human genome.

left).

DISCUSSION

Here, we present CRISPRoff and CRISPRon, two technologies
for programmably writing and erasing epigenetic memories to
control gene expression programs. Transient expression of
CRISPRoff writes a robust, speciﬁc, and multiplexable gene
silencing program that is memorized by cells through cell division
and differentiation, which can be rapidly reversed by CRISPRon.

(H) Representative sgRNA activity score proﬁle for ORC5 from the indicated screen (y axis).
(I) An aggregate plot comparing the normalized phenotype score for each sgRNA for genes without annotated CGIs.
(J) An overlay of normalized sgRNA phenotype score from the CRISPRoff screen (green) with MNase signal that represents nucleosome occupancy (gray). The
plot is an aggregate of genes with one annotated CGI.
(K) An overlay of normalized sgRNA phenotype score from the CRISPRoff screen (green) with MNase signal that represents nucleosome occupancy (gray). The
plot is an aggregate of the 39 genes with no annotated CGI.
(L) A plot of sgRNA activity along with MNase signal for H2B, derived from the sgRNA tiling screen outlined in Figure S6F.
See also Figure S7 and Tables S5 and S6.

Cell 184, 2503–2519, April 29, 2021 2515

Tau protein
staining

G

f
f
o
u
a
T
h
t
i

w
s

l
l

e
c
%

40

30

20

10

0

NT MAPT

A

D

H

100

x
a
M

f
o
%

80

60

40

20

0

CD81

ll

Sort transfected cells
Transfect CRISPRoff

Sort CD81– cells

passage

NGN2 induction

Sub-plate neural
    precursor cells

Analyze neurons

Day

0

3

30

(9 days)

-3

0

8

iPSC

neuronal
differentiation

B

s

l
l

e
c
f
f
o
-
1
8
D
C
%

30

20

10

0

Resource

iPSC

Neuron

30d p.t.

C

s

l
l

e
c

f
f
o
-
1
8
D
C
%

100

80

60

40

20

NT

CRISPRi
CRISPRoff

0

Day -3

Day 0

Day 8

CD81–

parental

E

NT sgRNA

F

Non-targeting

MAPT-edited

CD81-targeting sgRNA

200 μm

140bp

I

CRISPRoff
+ NT sgRNA

CRISPRoff
+ MAPT sgRNA

PVT1

Tau-negative
cells

sgRNA

r
e
t
o
m
o
r
P

E1 E2 E3E4

b
k

5
.
5
1
+

b
k
0
6
+

b
k

5
0
1
+

b
k

3
1
1
+

C
S
S

Tau

J

)
d
e
z

i
l

a
m
r
o
n
(

1.4

1.2

1.0
0.8

0.6

0.4

A
N
R
m

0.2
0.0
sgRNA

l
r
t
c

1
E

2
E

3
E

4
E

.
r

P

l
r
t
c

1
E

2
E

3
E

4
E

.
r

P

CRISPRoff

CRISPRoff mut.

Figure 7. CRISPRoff gene silencing in iPSCs, iPSC-derived neurons, and enhancers
(A) An experimental workﬂow of CD81 knockdown by CRISPRoff in iPSCs, followed by NGN2-mediated differentiation of edited cells into neurons.
(B) Quantiﬁcation of cells with CD81 silenced by CRISPRi or CRISPRoff with CD81-targeting or NT sgRNAs, measured at 30 days p.t. The error bars represent SD
from three independent experiments.
(C) Quantiﬁcation of cells with CD81 silenced at the indicated time points from (A). The gray bars indicate the percent of iPSC-edited cells with CD81 silenced that
were not differentiated during the experiment. The red bars represent cells that were carried through the neuronal differentiation protocol. The error bars represent
SD from three independent experiments.
(D) A representative histogram of CD81 expression in iPSC-derived neurons at day 8 of neuronal differentiation of parental-unedited (gray) or CD81-edited
iPSCs (red).
(E) Bisulﬁte PCR of a 140-bp region of the CD81 promoter in neurons differentiated from iPSCs transfected with CRISPRoff and NT or CD81-targeting sgRNA.
(F) Representative bright ﬁeld microscopy images of differentiated neurons derived from iPSCs transfected with CRISPRoff and MAPT-targeting or NT sgRNA.
(G) Quantiﬁcation Tau expression in neurons differentiated from iPSCs transfected with CRISPRoff and NT or MAPT-targeting sgRNA, measured at 10 days post-
differentiation.
(H) Representative ﬂow cytometry plots of Tau protein staining in iPSC-derived neurons after CRISPRoff transfection with NT or MAPT-targeting sgRNA. The
gates are based on unperturbed iPSC-derived neurons.
(I) A schematic of the PVT1 locus with the promoter and four enhancer elements (E1–E4) labeled with the distance from the TSS.
(J) Plots of normalized PVT1 transcript levels from quantitative RT-qPCR of cells treated with CRISPRoff (left) or CRISPRoff D3A mutant (right) and sgRNAs
targeting either the promoter (Pr.) or the four enhancer elements (E1–E4), normalized to control sgRNAs. Asterisks denote statistical signiﬁcance by t test and
each technical replicate is shown as red dots.
See also Tables S6 and S7.

2516 Cell 184, 2503–2519, April 29, 2021

Resource

We show that CRISPRoff can speciﬁcally and robustly silence
the large majority of human genes. Our initial experiments
demonstrate CRISPRoff can perturb enhancers, opening the po-
tential to target genome elements that control tissue-speciﬁc
gene expression (Fulco et al., 2016; Tarjan et al., 2019).

Our ﬁnding that targeted DNA methylation outside of anno-
tated CGIs can lead to robust memorized gene silencing extends
the canonical model of methylation-based gene silencing, which
posits that a high density of CpG methylation is a requirement for
stable propagation of silencing (Boyes and Bird, 1992). Although
CRISPRoff-mediated writing of DNA methylation and histone
modiﬁcation are artiﬁcially programmed, our results motivate
the need to deﬁne functional DNA methylation and dissect regu-
latory DNA elements and other host factors that mediate initia-
tion, spreading, and maintenance of histone and DNA methyl-
ation marks. For example, targeting CRISPRoff 2 kb upstream
of
the H2B TSS leads to acquisition and maintenance of
H3K9me3 and DNA methylation marks at the same genomic po-
sitions as targeting CRISPRoff directly proximal to the TSS,
pointing to the existence of preexisting boundaries that restrict
epigenetic spreading. By allowing the initiation of silencing at a
deﬁned time and genomic location, CRISPRoff provides a
unique tool for addressing these and other fundamental ques-
tions regarding the mechanism and biological role of heritable
gene silencing in mammalian cells (Audergon et al., 2015; Igle-
sias et al., 2018; Ragunathan et al., 2015; Yu et al., 2018).

CRISPRoff provides a valuable complement

to existing
CRISPRi and CRISPR nuclease approaches (Doench, 2018;
Hanna and Doench, 2020; Shalem et al., 2015). CRISPRoff
gene silencing can lead to effectively complete nulls without
inducing a DNA damage response facilitating multigene target-
ing screens or therapeutic cell engineering (Ihry et al., 2018).
The ability to target CRISPRoff to a large window upstream of
the TSS allows access to promoter SNPs that could be utilized
for allele-speciﬁc targeting of disease-associated mutations.
This could broadly enable approaches to silence dominant nega-
tive alleles. Similarly, silencing of long noncoding RNAs and reg-
ulatory RNAs provides a new avenue for stable reprograming of
gene expression. Silencing of inhibitory elements such as anti-
sense transcripts, could result in a heritable increase in expres-
sion of some genes, potentially enabling therapeutic efforts
to mitigate haploinsufﬁciency or imprinting disorders (Buiting
et al., 2016). More broadly, heritable epigenetic silencing pro-
rewiring human gene expression
vides a general
programs.

tool

for

Limitations of study
Most of our CRISPRoff experiments, including the genome-wide
screens, were performed with sgRNAs previously predicted to
be optimal for CRISPRi (Horlbeck et al., 2016a; Replogle et al.,
2020). We envision that future efforts to design optimal sgRNAs
for CRISPRoff will further improve gene silencing activity. More-
lines,
over, we performed our experiments in polyclonal cell
which inherently have clonal variations in DNA methylation. It
will be valuable to explore potential clonal differences in methyl-
ation and the effects on CRISPRoff activity and potential off-
target sites. Last, we highlight MYL6 as a non-CGI gene that
has metastable silencing over time. It remains unknown exactly

ll

how many genes are amenable to stable versus metastable
silencing, and future efforts are needed to identify the regulatory
features that dictate the stability of programmed epigenetic
memory.

STAR+METHODS

Detailed methods are provided in the online version of this paper
and include the following:

d KEY RESOURCES TABLE
d RESOURCE AVAILABILITY

B Lead contact
B Materials availability
B Data and code availability

d EXPERIMENTAL MODEL AND SUBJECT DETAILS

B Cell culture, DNA transfections, and ﬂow cytometry

d METHOD DETAILS

B Plasmid Design and Construction
B CRISPRon and CRISPRoff transfections and analysis
B PVT1 enhancer targeting
B RNA sequencing
B Chromatin immunoprecipitation and analysis
B Western blotting
B Bisulﬁte sequencing PCR
B Whole genome bisulﬁte sequencing and analysis
B Cas9 genome editing and 5-aza-dC treatments
B Genome-wide CRISPRoff screen and analysis
B Tiling screen library design, experimental speciﬁca-

tions, and analysis

B GFP-tagged sgRNA tiling screen
B iPSC manipulation and neuronal differentiation
d QUANTIFICATION AND STATISTICAL ANALYSIS

SUPPLEMENTAL INFORMATION

Supplemental information can be found online at https://doi.org/10.1016/j.cell.
2021.03.025.

ACKNOWLEDGMENTS

We are grateful to Alex Ge, Matt Laurie, Christina Liem, Chris Hsiung, and Al-
bert Xu for technical assistance and Tessa Bertozzi, Bruce Conklin, Sandy
Johnson, Barbara Panning, Fyodor Urnov, and members of the Weissman
and Gilbert labs for helpful discussions. This work was funded by DARPA
Safe Genes and PREPARE programs (to L.A.G. and J.S.W.), the HHMI Hanna
H. Gray Fellows Program (to J.K.N.), the Jane Cofﬁn Childs Memorial Fund (to
J.C.), NIH (K99/R00 GM134154 to J.C., F31 NS115380 to J.M.R., F32
AG063487 to A.J.S., RM1-HG007735 to H.Y.C., DP1CA216873 to B.E.B.,
1RM1HG009490 to J.S.W., DP2 CA239597 to L.A.G., and DP2 GM119139
to M.K.), and NSF Graduate Research Fellowship (to G.N.R. and A.C.).
L.A.G. is supported by a Goldberg-Benioff Endowed Professorship. J.S.W.
and H.Y.C. are HHMI Investigators. B.E.B. is the Bernard and Mildred Kayden
Endowed MGH Research Institute Chair, and an American Cancer Society
Research Professor. This study was supported in part by UCSF HDFCCC Lab-
oratory for Cell Analysis Shared Resource Facility (NIH P30CA082103) and by
the Gene Regulation Observatory at the Broad Institute. The IGI supported
oligonucleotide pools.

Cell 184, 2503–2519, April 29, 2021 2517

ll

AUTHOR CONTRIBUTIONS

J.K.N., J.S.W., and L.A.G. led the conception, design, and interpretation of the
project as well as writing of the manuscript with the assistance of all of the co-
authors. J.K.N. led the design and conducting of the CRISPRoff experiments.
G.C.P. and L.A.G. led the design and conducting of the CRISPRon experi-
ments with assistance from A.C. J.C. designed the tiling sgRNA libraries and
analyzed screen, RNA-seq, and ChIP-seq datasets. J.Z.C., G.N.R., A.J.S.,
and M.K. led the iPSC and neuron experiments. J.M.R. designed and cloned
the genome-wide sgRNA library with assistance from A.N.P. J.Y.S.K. and
M.D.L. constructed the mNG-tagged cell
lines. C.A., V.H., and B.E.B. de-
signed, performed, and analyzed the WGBS experiments. Q.S., K.L.H., and
H.Y.C. designed, performed, and analyzed the PVT1 enhancer experiments.

DECLARATION OF INTERESTS

J.K.N., J.C., G.C.P., L.A.G., and J.S.W. have ﬁled patent applications related
to CRISPRoff, CRISPRon, and CRISPRi/a screening. J.M.R. consults for
Maze Therapeutics. L.A.G., J.S.W., H.Y.C., and B.E.B. consult for and hold eq-
uity in Chroma Medicine. J.S.W. declares outside interest in KSQ Therapeu-
tics, Maze Therapeutics, Amgen, and Tessera Therapeutics. M.K. serves on
the Scientiﬁc Advisory Boards of Engine Biosciences, Casma Therapeutics,
and Cajal Neuroscience. B.E.B. declares outside interests in Fulcrum Thera-
peutics, Arsenal Biosciences, HiFiBio, and Cell Signaling Technologies.
H.Y.C. is a co-founder of Accent Therapeutics, Boundless Bio, and is an
advisor for 10x Genomics, Arsenal Biosciences, and Spring Discovery.

INCLUSION AND DIVERSITY

One or more of the authors of this paper self-identiﬁes as an underrepresented
ethnic minority in science. One or more of the authors of this paper self-iden-
tiﬁes as a member of the LGBTQ+ community. One or more of the authors of
this paper received support from a program designed to increase minority rep-
resentation in science.

Received: August 30, 2020
Revised: January 28, 2021
Accepted: March 11, 2021
Published: April 9, 2021

REFERENCES

Adamson, B., Norman, T.M., Jost, M., Cho, M.Y., Nun˜ ez, J.K., Chen, Y., Vil-
lalta, J.E., Gilbert, L.A., Horlbeck, M.A., Hein, M.Y., et al. (2016). A Multiplexed
Single-Cell CRISPR Screening Platform Enables Systematic Dissection of the
Unfolded Protein Response. Cell 167, 1867–1882.e21.

Amabile, A., Migliara, A., Capasso, P., Bifﬁ, M., Cittaro, D., Naldini, L., and
Lombardo, A. (2016). Inheritable Silencing of Endogenous Genes by Hit-
and-Run Targeted Epigenetic Editing. Cell 167, 219–232.e14.

Anzalone, A.V., Koblan, L.W., and Liu, D.R. (2020). Genome editing with
CRISPR-Cas nucleases, base editors, transposases and prime. Nat. Bio-
technol. 38, 824–844.

Audergon, P.N.C.B., Catania, S., Kagansky, A., Tong, P., Shukla, M., Pidoux,
A.L., and Allshire, R.C. (2015). Epigenetics. Restricted epigenetic inheritance
of H3K9 methylation. Science 348, 132–135.

Bintu, L., Yong, J., Antebi, Y.E., McCue, K., Kazuki, Y., Uno, N., Oshimura, M.,
and Elowitz, M.B. (2016). Dynamics of epigenetic regulation at the single-cell
level. Science 351, 720–724.

Blomen, V.A., Ma´ jek, P., Jae, L.T., Bigenzahn, J.W., Nieuwenhuis, J., Staring,
J., Sacco, R., van Diemen, F.R., Olk, N., Stukalov, A., et al. (2015). Gene essen-
tiality and synthetic lethality in haploid human cells. Science 350, 1092–1096.

Boyes, J., and Bird, A. (1992). Repression of genes by DNA methylation de-
pends on CpG density and promoter strength: evidence for involvement of a
methyl-CpG binding protein. EMBO J. 11, 327–333.

2518 Cell 184, 2503–2519, April 29, 2021

Resource

Buiting, K., Williams, C., and Horsthemke, B. (2016). Angelman syndrome - in-
sights into a rare neurogenetic disorder. Nat. Rev. Neurol. 12, 584–593.

Chavez, A., Scheiman, J., Vora, S., Pruitt, B.W., Tuttle, M., P R Iyer, E., Lin, S.,
Kiani, S., Guzman, C.D., Wiegand, D.J., et al. (2015). Highly efﬁcient Cas9-
mediated transcriptional programming. Nat. Methods 12, 326–328.

Chen, S., Zhou, Y., Chen, Y., and Gu, J. (2018). fastp: an ultra-fast all-in-one
FASTQ preprocessor. Bioinformatics 34, i884–i890.

Cho, S.W., Xu, J., Sun, R., Mumbach, M.R., Carter, A.C., Chen, Y.G., Yost,
K.E., Kim, J., He, J., Nevins, S.A., et al. (2018). Promoter of lncRNA Gene
PVT1 Is a Tumor-Suppressor DNA Boundary Element. Cell 173, 1398–
1412.e22.

Deaton, A.M., and Bird, A. (2011). CpG islands and the regulation of transcrip-
tion. Genes Dev. 25, 1010–1022.

Doench, J.G. (2018). Am I ready for CRISPR? A user’s guide to genetic
screens. Nat. Rev. Genet. 19, 67–80.

Fulco, C.P., Munschauer, M., Anyoha, R., Munson, G., Grossman, S.R., Perez,
E.M., Kane, M., Cleary, B., Lander, E.S., and Engreitz, J.M. (2016). Systematic
mapping of functional enhancer-promoter connections with CRISPR interfer-
ence. Science 354, 769–773.

Galonska, C., Charlton, J., Mattei, A.L., Donaghey, J., Clement, K., Gu, H., Mo-
hammad, A.W., Stamenova, E.K., Cacchiarelli, D., Klages, S., et al. (2018).
Genome-wide tracking of dCas9-methyltransferase footprints. Nat. Commun.
9, 597.

Gilbert, L.A., Larson, M.H., Morsut, L., Liu, Z., Brar, G.A., Torres, S.E., Stern-
Ginossar, N., Brandman, O., Whitehead, E.H., Doudna, J.A., et al. (2013).
CRISPR-mediated modular RNA-guided regulation of transcription in eukary-
otes. Cell 154, 442–451.

Gilbert, L.A., Horlbeck, M.A., Adamson, B., Villalta, J.E., Chen, Y., Whitehead,
E.H., Guimaraes, C., Panning, B., Ploegh, H.L., Bassik, M.C., et al. (2014).
Genome-Scale CRISPR-Mediated Control of Gene Repression and Activation.
Cell 159, 647–661.

Guenther, M.G., Frampton, G.M., Soldner, F., Hockemeyer, D., Mitalipova, M.,
Jaenisch, R., and Young, R.A. (2010). Chromatin structure and gene expres-
sion programs of human embryonic and induced pluripotent stem cells. Cell
Stem Cell 7, 249–257.

Hanna, R.E., and Doench, J.G. (2020). Design and analysis of CRISPR-Cas ex-
periments. Nat. Biotechnol. 38, 813–823.

Hansen, K.D., Langmead, B., and Irizarry, R.A. (2012). BSmooth: from whole
genome bisulﬁte sequencing reads to differentially methylated regions.
Genome Biol. 13, R83.

Hart, T., Brown, K.R., Sircoulomb, F., Rottapel, R., and Moffat, J. (2014).
Measuring error rates in genomic perturbation screens: gold standards for hu-
man functional genomics. Mol. Syst. Biol. 10, 733.

Hathaway, N.A., Bell, O., Hodges, C., Miller, E.L., Neel, D.S., and Crabtree,
G.R. (2012). Dynamics and memory of heterochromatin in living cells. Cell
149, 1447–1460.

Hofacker, D., Broche, J., Laistner, L., Adam, S., Bashtrykov, P., and Jeltsch, A.
(2020). Engineering of Effector Domains for Targeted DNA Methylation with
Reduced Off-Target Effects. Int. J. Mol. Sci. 21, 502.

Holtzman, L., and Gersbach, C.A. (2018). Editing the Epigenome: Reshaping
the Genomic Landscape. Annu. Rev. Genomics Hum. Genet. 19, 43–71.

Horlbeck, M.A., Gilbert, L.A., Villalta, J.E., Adamson, B., Pak, R.A., Chen, Y.,
Fields, A.P., Park, C.Y., Corn, J.E., Kampmann, M., and Weissman, J.S.
(2016a). Compact and highly active next-generation libraries for CRISPR-
mediated gene repression and activation. eLife 5, e19760.

Horlbeck, M.A., Witkowsky, L.B., Guglielmi, B., Replogle, J.M., Gilbert, L.A.,
Villalta, J.E., Torigoe, S.E., Tjian, R., and Weissman, J.S. (2016b). Nucleo-
somes impede Cas9 access to DNA in vivo and in vitro. eLife 5, e12677.

Hovestadt, V., Jones, D.T.W., Picelli, S., Wang, W., Kool, M., Northcott, P.A.,
Sultan, M., Stachurski, K., Ryzhova, M., Warnatz, H.-J., et al. (2014). Decoding
the regulatory landscape of medulloblastoma using DNA methylation
sequencing. Nature 510, 537–541.

Resource

ll

Iglesias, N., Currie, M.A., Jih, G., Paulo, J.A., Siuti, N., Kalocsay, M., Gygi, S.P.,
and Moazed, D. (2018). Automethylation-induced conformational switch in
Clr4 (Suv39h) maintains epigenetic stability. Nature 560, 504–508.

Ihry, R.J., Worringer, K.A., Salick, M.R., Frias, E., Ho, D., Theriault, K., Kommi-
neni, S., Chen, J., Sondey, M., Ye, C., et al. (2018). p53 inhibits CRISPR-Cas9
engineering in human pluripotent stem cells. Nat. Med. 24, 939–946.

Iqbal, K., Liu, F., and Gong, C.-X. (2016). Tau and neurodegenerative disease:
the story so far. Nat. Rev. Neurol. 12, 15–27.

Isaac, R.S., Jiang, F., Doudna, J.A., Lim, W.A., Narlikar, G.J., and Almeida, R.
(2016). Nucleosome breathing and remodeling constrain CRISPR-Cas9 func-
tion. eLife 5, e13450.

Jost, M., Santos, D.A., Saunders, R.A., Horlbeck, M.A., Hawkins, J.S., Scaria,
S.M., Norman, T.M., Hussmann, J.A., Liem, C.R., Gross, C.A., and Weissman,
J.S. (2020). Titrating gene expression using libraries of systematically attenu-
ated CRISPR guide RNAs. Nat. Biotechnol. 38, 355–364.

Knott, G.J., and Doudna, J.A. (2018). CRISPR-Cas guides the future of genetic
engineering. Science 361, 866–869.

Konermann, S., Brigham, M.D., Trevino, A.E., Joung, J., Abudayyeh, O.O.,
Barcena, C., Hsu, P.D., Habib, N., Gootenberg, J.S., Nishimasu, H., et al.
(2015). Genome-scale transcriptional activation by an engineered CRISPR-
Cas9 complex. Nature 517, 583–588.

Langmead, B., and Salzberg, S.L. (2012). Fast gapped-read alignment with
Bowtie 2. Nat. Methods 9, 357–359.

Leonetti, M.D., Sekine, S., Kamiyama, D., Weissman, J.S., and Huang, B.
(2016). A scalable strategy for high-throughput GFP tagging of endogenous
human proteins. Proc. Natl. Acad. Sci. USA 113, E3501–E3508.

Li, X.-L., Li, G.-H., Fu, J., Fu, Y.-W., Zhang, L., Chen, W., Arakaki, C., Zhang,
J.-P., Wen, W., Zhao, M., et al. (2018). Highly efﬁcient genome editing via
CRISPR-Cas9 in human pluripotent stem cells is achieved by transient BCL-
XL overexpression. Nucleic Acids Res. 46, 10195–10215.

Liao, Y., Smyth, G.K., and Shi, W. (2014). featureCounts: an efﬁcient general
purpose program for assigning sequence reads to genomic features. Bioinfor-
matics 30, 923–930.

Liu, X.S., Wu, H., Ji, X., Stelzer, Y., Wu, X., Czauderna, S., Shu, J., Dadon, D.,
Young, R.A., and Jaenisch, R. (2016). Editing DNA Methylation in the Mamma-
lian Genome. Cell 167, 233–247.e17.

Love, M.I., Huber, W., and Anders, S. (2014). Moderated estimation of fold
change and dispersion for RNA-seq data with DESeq2. Genome Biol. 15, 550.

Maeder, M.L., Angstman, J.F., Richardson, M.E., Linder, S.J., Cascio, V.M.,
Tsai, S.Q., Ho, Q.H., Sander, J.D., Reyon, D., Bernstein, B.E., et al. (2013). Tar-
geted DNA demethylation and activation of endogenous genes using pro-
grammable TALE-TET1 fusion proteins. Nat. Biotechnol. 31, 1137–1142.

Meyers, R.M., Bryan, J.G., McFarland, J.M., Weir, B.A., Sizemore, A.E., Xu, H.,
Dharia, N.V., Montgomery, P.G., Cowley, G.S., Pantel, S., et al. (2017).
Computational correction of copy number effect improves speciﬁcity of
CRISPR-Cas9 essentiality screens in cancer cells. Nat. Genet. 49, 1779–1784.

Mlambo, T., Nitsch, S., Hildenbeutel, M., Romito, M., Mu¨ ller, M., Bossen, C.,
Diederichs, S., Cornu, T.I., Cathomen, T., and Mussolino, C. (2018). Designer
epigenome modiﬁers enable robust and sustained gene silencing in clinically
relevant human cells. Nucleic Acids Res. 46, 4456–4468.

O’Geen, H., Bates, S.L., Carter, S.S., Nisson, K.A., Halmai, J., Fink, K.D., Rhie,
S.K., Farnham, P.J., and Segal, D.J. (2019). Ezh2-dCas9 and KRAB-dCas9
enable engineering of epigenetic memory in a context-dependent manner.
Epigenetics Chromatin 12, 26.

Park, Y., and Wu, H. (2016). Differential methylation analysis for BS-seq data
under general experimental design. Bioinformatics 32, 1446–1453.

Park, M., Patel, N., Keung, A.J., and Khalil, A.S. (2019). Engineering Epigenetic
Regulation Using Synthetic Read-Write Modules. Cell 176, 227–238.e20.

Ragunathan, K., Jih, G., and Moazed, D. (2015). Epigenetics. Epigenetic inher-
itance uncoupled from sequence-speciﬁc recruitment. Science 348, 1258699.

Ramı´rez, F., Ryan, D.P., Gru¨ ning, B., Bhardwaj, V., Kilpert, F., Richter, A.S.,
Heyne, S., Du¨ ndar, F., and Manke, T. (2016). deepTools2: a next generation
web server for deep-sequencing data analysis. Nucleic Acids Res. 44 (W1),
W160-5.

Replogle, J.M., Norman, T.M., Xu, A., Hussmann, J.A., Chen, J., Cogan, J.Z.,
Meer, E.J., Terry, J.M., Riordan, D.P., Srinivas, N., et al. (2020). Combinatorial
single-cell CRISPR screens by direct guide RNA capture and targeted
sequencing. Nat. Biotechnol. 38, 954–961.

Robinson, J.T., Thorvaldsdo´ ttir, H., Winckler, W., Guttman, M., Lander, E.S.,
Getz, G., and Mesirov, J.P. (2011). Integrative genomics viewer. Nat. Bio-
technol. 29, 24–26.

Schellenberger, V., Wang, C.-W., Geething, N.C., Spink, B.J., Campbell, A.,
To, W., Scholle, M.D., Yin, Y., Yao, Y., Bogin, O., et al. (2009). A recombinant
polypeptide extends the in vivo half-life of peptides and proteins in a tunable
manner. Nat. Biotechnol. 27, 1186–1190.

Shalem, O., Sanjana, N.E., and Zhang, F. (2015). High-throughput functional
genomics using CRISPR-Cas9. Nat. Rev. Genet. 16, 299–311.

Stelzer, Y., Shivalila, C.S., Soldner, F., Markoulaki, S., and Jaenisch, R. (2015).
Tracing dynamic changes of DNA methylation at single-cell resolution. Cell
163, 218–229.

Stepper, P., Kungulovski, G., Jurkowska, R.Z., Chandra, T., Krueger, F., Rein-
hardt, R., Reik, W., Jeltsch, A., and Jurkowski, T.P. (2017). Efﬁcient targeted
DNA methylation with chimeric dCas9-Dnmt3a-Dnmt3L methyltransferase.
Nucleic Acids Res. 45, 1703–1713.

Tak, Y.E., Kleinstiver, B.P., Nun˜ ez, J.K., Hsu, J.Y., Horng, J.E., Gong, J.,
Weissman, J.S., and Joung, J.K. (2017). Inducible and multiplex gene regula-
tion using CRISPR-Cpf1-based transcription factors. Nat. Methods 14,
1163–1166.

Tarasov, A., Vilella, A.J., Cuppen, E., Nijman, I.J., and Prins, P. (2015). Sam-
bamba:
formats. Bioinformatics 31,
2032–2034.

fast processing of NGS alignment

Tarjan, D.R., Flavahan, W.A., and Bernstein, B.E. (2019). Epigenome editing
strategies for the functional annotation of CTCF insulators. Nat. Commun.
10, 4258.

Tian, R., Gachechiladze, M.A., Ludwig, C.H., Laurie, M.T., Hong, J.Y., Natha-
niel, D., Prabhu, A.V., Fernandopulle, M.S., Patel, R., Abshari, M., et al. (2019).
CRISPR Interference-Based Platform for Multimodal Genetic Screens in Hu-
man iPSC-Derived Neurons. Neuron 104, 239–255.e12.

Van, M.V., Fujimori, T., and Bintu, L. (2021). Nanobody-mediated control of
gene expression and epigenetic memory. Nat. Commun. 12, 537.

Xu, X., and Qi, L.S. (2019). A CRISPR-dCas Toolbox for Genetic Engineering
and Synthetic Biology. J. Mol. Biol. 431, 34–47.

Xu, X., Tao, Y., Gao, X., Zhang, L., Li, X., Zou, W., Ruan, K., Wang, F., Xu, G.L.,
and Hu, R. (2016). A CRISPR-based approach for targeted DNA demethyla-
tion. Cell Discov. 2, 16009.

Yeh, C.D., Richardson, C.D., and Corn, J.E. (2019). Advances in genome edit-
ing through control of DNA repair pathways. Nat. Cell Biol. 21, 1468–1478.

Yu, R., Wang, X., and Moazed, D. (2018). Epigenetic inheritance mediated by
coupling of RNAi and histone H3K9 methylation. Nature 558, 615–619.

Zhang, Z.-M., Lu, R., Wang, P., Yu, Y., Chen, D., Gao, L., Liu, S., Ji, D., Roth-
bart, S.B., Wang, Y., et al. (2018). Structural basis for DNMT3A-mediated de
novo DNA methylation. Nature 554, 387–391.

Cell 184, 2503–2519, April 29, 2021 2519

ll

STAR+METHODS

KEY RESOURCES TABLE

REAGENT or RESOURCE

Antibodies

Anti-H3K9me3

Anti-Cas9 (S. pyogenes)

Anti-human CD29

Anti-human CD81 (TAPA-1)

Anti-human CD151 (PETA-3)

Bacterial and virus strains

Stellar Competent Cells

Resource

SOURCE

abcam

Active Motif

BioLegend

BioLegend

BioLegend

IDENTIFIER

Cat#ab8898

Cat#61577

Cat#303004

Cat#349504, 349510

Cat#350405

Clontech

Cat#636766

Chemicals, peptides, and recombinant proteins

TransIT-LT1 Transfection Reagent

ROCK inhibitor

Recombinant Human NT-3

Recombinant BDNF

Mouse laminin

Critical commercial assays

Mirus

Selleck Chemicals

PeproTech

PeproTech

Thermo Fisher

TruSeq Stranded mRNA
NEBNext Ultra II DNA Library Prep Kit for Illumina(cid:2)

Illumina

NEB

Cat#MIR2306

Cat#S1049

Cat#450-03

Cat#450-02

Cat#23017015

Cat#20020594

Cat#E7645S

Deposited data

RNA-seq, ChIP-seq, WGBS

Experimental models: Cell lines

HEK293T

K562

WTC Gen1c iPSC

HeLa

U2OS

Oligonucleotides

This paper

GSE168012

Gilbert et al., 2013

Gilbert et al., 2013

Coriell Institute

ATCC

ATCC

N/A

N/A

Cat#GM25256
Cat#ATCC(cid:2) CC-2
Cat#ATCC(cid:2) HTB-96

Primers and oligonucleotides for sgRNA cloning

IDT; see Tables S6 and S7

Oligonucleotide libraries

Twist; See Tables S3, S4, and S5

N/A

N/A

Recombinant DNA

CRISPRoff-V2.1

CRISPRon

Software and algorithms

Prism

FlowJo 8.8.6

MACS3 Peak Analyzer

methylCtools 1.0.0

BWA-MEM version 0.7.17

bsseq 1.24.4

DSS

RESOURCE AVAILABILITY

This paper

This paper

GraphPad

FlowJo

MACS3

methylCtools

BWA-MEM

Addgene #167981

Addgene #167983

https://www.graphpad.com

https://www.ﬂowjo.com

https://github.com/macs3-project/MACS

https://github.com/hovestadt/methylCtools

arXiv: 1303.3997v1

Hansen et al., 2012

Park and Wu, 2016

N/A

N/A

Lead contact
Further information and requests for resources and reagents should be directed to and will be fulﬁlled by the Lead Contacts, Luke
Gilbert (luke.gilbert@ucsf.edu) and Jonathan Weissman (weissman@wi.mit.edu).

e1 Cell 184, 2503–2519.e1–e7, April 29, 2021

Resource

ll

Materials availability
The CRISPRoff and CRISPRon plasmids are available from Addgene: #167981 for CRISPRoff-V2.1 and #167983 for TETv4.

Data and code availability
The RNA-seq, ChIP-seq, and whole genome bisulﬁte sequencing data are available on GEO (GSE168012).

EXPERIMENTAL MODEL AND SUBJECT DETAILS

Cell culture, DNA transfections, and ﬂow cytometry
All cell lines were cultured at 37(cid:4)C with 5% CO2 in tissue culture incubators. HEK293T (female), HeLa (female), and U2OS (female)
cells were cultured in Dulbecco’s modiﬁed eagle medium (DMEM) in 10% FBS (HyClone or VWR), 100 units/mL streptomycin,
100 mg/ml penicillin, and 2 mM glutamine. K562 (female) cells were maintained in RPMI-1640 with 25 mM HEPES and 2.0 g/L NaHCo3
in 10% FBS, 2 mM glutamine, 100 units/mL streptomycin, and 100 mg/mL penicillin. WTC Gen1c iPSCs (male) were cultured in
mTESR media (STEMCELL Technologies) under feeder-free conditions on growth factor-reduced Matrigel (BD Biosciences). Cells
were passaged using Accutase (STEMCELL Technologies) and seeded on Matrigel coated plates with mTESR media supplemented
with p16-Rho-associated coiled-coil kinase (ROCK) inhibitor Y-27632 (10 mM; Selleckchem).

Lentiviral particles were produced by transfecting standard packaging vectors into HEK293T using TransIT-LT1 Transfection Re-
agent (Mirus, MIR2306). Media was changed 24 hours post-transfection with complete DMEM supplemented with 15 mM HEPES.
Viral supernatants were harvested 48-60 hours after transfection and ﬁltered through a 0.45 mm PVDF syringe ﬁlter. Lentiviral infec-
tions included polybrene (8 mg/ml).

METHOD DETAILS

Plasmid Design and Construction
The dCas9 and KRAB sequences were obtained from a previous CRISPRi construct (Gilbert et al., 2013). The D3A and D3L se-
quences, including the D3A-D3L fusion, originated from Stepper et al. (2017) and were assembled with dCas9 and KRAB DNA se-
quences into a CAG-expression plasmid using NEBuilder(cid:2) HiFi DNA Assembly (NEB). The D3A domain consists of N612-V912 of the
Mus musculus Dnmt3a protein and the D3L domain consists of G208-L421 of the Mus musculus Dnmt3l protein. The TETv1 design
was constructed by PCR ampliﬁcation of the dCas9-TET1CD sequence from Fuw-dCas9-Tet1CD (Addgene #84475) and assembled
into a CAG-expression plasmid. XTEN linker sequences were previously published (Schellenberger et al., 2009). All CRISPRoff and
TET1 fusion proteins include BFP as either a direct fusion or with a P2A-cleavage sequence to measure transfection efﬁciency by ﬂow
cytometry. The dSaCas9 (D10A, N508A) sequence was PCR ampliﬁed from pX603 (Addgene #61594) and the dLbCas12a sequence
was PCR ampliﬁed from Tak et al. (2017). VP64, p65, and Rta were PCR ampliﬁed from SP-dCas9-VPR (Addgene #63798). The
GAPDH-Snrpn-GFP lentiviral reporter originated from Addgene #70148 (Liu et al., 2016; Stelzer et al., 2015).

The sgRNA plasmids were constructed by restriction cloning of protospacers downstream of a U6 promoter using BstXI and BlpI
cut sites, as previously described. The sgRNA expression plasmids also express a T2A-mCherry marker to measure transfection ef-
ﬁciency. The sgRNA sequences used for CRISPRoff and CRISPRon experiments are listed in Table S6. The sgRNA sequences were
chosen based on our previous algorithm to predict active CRISPRi sgRNAs (Horlbeck et al., 2016a).

The MS2 plasmids were constructed by ﬁrst transferring the mU6 promoter-sgRNA-EF1a-puromycin-T2A-mCherry cassette into a
non-lentiviral vector by restriction cloning. The MCP-XTEN80-NLS-VPR-2xP2A cassette was ordered as four gBlocks (IDT) and
cloned into the aforementioned non-lentiviral plasmid by Gibson assembly. The sgRNA-MS2 loop sequence was designed based
on the SAM system (Konermann et al., 2015) with the BstXI and BlpI restriction sites incorporated from our previous mU6 sgRNA
expression design (Addgene #84832). The DNA sequence encoding the MS2-sgRNA scaffold is 50-GTTTAAGAGCTAaGCCAACAT
GAGGATCACCCATGTCTGCAGGGCaTAGCAAGTTTAAATAAGGCTAGTCCGTTATCAACTTGGCCAACATGAGGATCACC-
CATGTCTGCAGGGCCAAGTGGCACCGAGTCGGTGCTTTTTTT-30. For construction of the transactivator plasmids, each domain or
combination of domains was PCR ampliﬁed and cloned by Gibson assembly into a plasmid that encodes the sgRNA and MS2 coat
protein (MCP). Guide sequences were cloned by double digest of the vector and ligation of annealed oligos, as previously described.
All mRNA constructs were synthesized using the mMESSAGE mMachineTM T7 Ultra Transcription Kit (Thermo Fisher Scientiﬁc).
The T7 promoter sequence (50-TAATACGACTCACTATAGG-30) was ﬁrst cloned upstream of the CRISPRoff sequence. The T7-
CRISPRoff sequence was PCR ampliﬁed and used as template for in vitro synthesis reactions. Following the manufacturer protocol
for synthesis, the reactions were cleaned by chloroform extraction and isopropanol precipitation.

CRISPRon and CRISPRoff transfections and analysis
Transient transfection experiments in HEK293T were performed in 24-well plates using TransIT-LT1 Transfection Reagent (Mirus) and
Opti-MEMTM I Reduced Serum Medium (Thermo Fisher Scientiﬁc). Cells at 70%–80% conﬂuency were transfected with 300 ng of
plasmid encoding CRISPRoff, dCas9-KRAB, or dCas9-D3A-3L and 150 ng of plasmids encoding sgRNAs. CRISPRoff experiments
in HeLa and U2OS cells were performed by nucleofection of plasmids using the SE. Cell Line 96-well Nucleofector Kit (Lonza) and a
96-well ShuttleTM Device (Lonza), per manufacturer protocol. Transfected cells were sorted 2 days after transfection using a BD

Cell 184, 2503–2519.e1–e7, April 29, 2021 e2

ll

Resource

FACSAria II or FACSAria Fusion and sorted cells were passaged every 2-3 days to measure durability of gene silencing. Experiments
that compare the silencing activity of different CRISPRoff fusions (Figures 1E, 4C, S1B, and S1F) were performed in cells that stably
express the targeting sgRNA to normalize sgRNA expression. To generate cell lines stably expressing sgRNAs, cells were trans-
duced with lentiviral particles that express the sgRNAs and sorted for sgRNA-positive cells 2-3 days after transduction.

Quantiﬁcation of ITGB1, CD81, and CD151 protein levels were measured by cell surface antibody staining of live cells. Cells were
incubated with APC- or PE-labeled antibody (BioLegend) for (cid:1)30 min in the dark at RT, washed twice with PBS containing 10% FBS,
and protein expression was measured on a BD LSR II ﬂow cytometer.

For CRISPRon experiments, 1x105 CLTA-GFP-silenced HEK293T cells were seeded in each well of a 24-well plate. When cells
reached 60%–80% conﬂuency the next day, cells were transfected with 500 ng of dCas9 plasmid (dCas9 or TETv1-4) and 300 ng
of sgRNA-transactivator plasmid (sgRNA only, VP64, p65, Rta, VP64-p65, p65-Rta, or VPR) using TransIT-LT1 Transfection Reagent
(Mirus) and Opti-MEMTM I Reduced Serum Medium (Thermo Fisher Scientiﬁc). Cells were monitored for BFP (dCas9 or TETv1-4) and
mCherry (guide-transactivator) expression 24 hours after transfection. Two days post-transfection, 7.5x104 BFP and mCherry double
positive cells were sorted using a BD FACSAria Fusion. Cells were allowed to recover for 4 days after the sort and were subsequently
analyzed by ﬂow cytometry every 2-3 days on an Attune NxT cytometer (Thermo Fisher Scientiﬁc).

All ﬂow cytometry data were analyzed using FlowJo and the raw FACS plots presented in the ﬁgures are in log10 scale.

PVT1 enhancer targeting
Quantitative RT-PCR quantiﬁcation of PVT1 expression was done as described in Cho et al. (2018). Brieﬂy, MB-MDA-231 cells were
transfected with CRISPR DNA together with a sgRNA vector using Neon (1400 V, 10 ms, 4 pulse). Double positive cells were sorted
after 2 days and continued to culture for 3 days. RNA were extracted with Zymo spin column and gene expression was quantiﬁed with
SYBR qPCR mix (LightCycler 480) using 45 ng of RNA. The expression of PVT1 were normalized to GAPDH gene in ddCt method.
t test was used to calculate the statistical signiﬁcance based on 3-5 biological replicates per condition.

The primer sequence used are: PVT1 forward (CGAGCTGCGAGCAAAGAT), PVT1 reverse (CGTGTCTCCACAGGTCACAG),
GAPDH forward (GGGCTCTCCAGAACATCATC), GAPDH reverse (CCTGCTTCACCACCTTCTTG). The sgRNAs targeting PVT1 en-
hancers 1-4, promoter, and lambda (controls) were from Cho et al. (2018) and listed on Table S6.

RNA sequencing
HEK293T cells that have maintained stable silencing of target genes were harvested 33 days (ITGB1, CD81, and CD151) or 28 days
(CLTA, HIST2H2BE, RAB11A, and VIM) post CRISPRoff transfection. Cells were dislodged from plates with PBS, centrifuged at
500 3 g for 5 min and washed again with PBS. Total RNA was extracted using Direct-zol RNA MiniPrep (Zymo R2051). Library prep-
arations were carried out using TruSeq Stranded mRNA Library Preparation Kit (Illumina RS-111-2101), starting with 1000 ng total
RNA. Final libraries were assessed using a 2100 Bioanalyzer (Agilent), quantiﬁed using Qubit dsDNA HS Assay Kit (Thermo Fisher
Scientiﬁc), and sequenced as single end 50 base pair reads on a HiSeq 4000 (Illumina). For processing the sequencing reads, linker
sequences (AGATCGGAAGAGCACACGTCTGAACTC) were removed using FASTX-clipper (FASTX-Toolkit). The reads were then
aligned to the human genome (GRCh37) using the STAR (Spliced Transcripts Alignment to a Reference, version 2.5) aligner against
the Gencode Gene V24lift37 transcriptome annotation. Read quantiﬁcation was carried out with featureCounts (Liao et al., 2014). All
downstream analyses were performed with Python (version 2.7) using a combination of Numpy (v1.12.1), Pandas (v0.17.1), and Scipy
(v0.17.0) libraries. Knockdown efﬁciency was calculated by normalizing gene Transcripts per Million (TPM) for the experimental sam-
ples with the mean TPM of the control (non-targeting) samples. Differential expression analysis was performed using DESeq2 (Love
et al., 2014). We note that non-target differentially expressed transcripts are lowly expressed genes.

Chromatin immunoprecipitation and analysis
At 30 days post transfection, 10x106 cells were crosslinked with 1% formaldehyde for 10 min at room temperature and quenched with
1.25 M glycine. Crosslinked cells were washed twice with cold PBS containing 1% HaltTM protease inhibitors (Thermo Fisher Scien-
tiﬁc) and the cell pellets were ﬂash frozen at –80(cid:4)C until sample preparation. Cells were lysed in lysis buffer (5 mM PIPES pH 8, 85 mM
KCl, 1% Igepal, 1% protease inhibitors) for 10 min on ice. Nuclei were isolated after spinning the suspension at 2000 rpm at 4(cid:4)C for
5 min. Nuclei were lysed at 4(cid:4)C for 10 min in nuclei lysis buffer (50 mM Tris pH 8, 10 mM EDTA, 1% SDS, 1% protease inhibitors).
Chromatin shearing was performed at 4(cid:4)C using a Diagenode Bioruptor(cid:2) Pico sonication device in 1.5 mL Bioruptor(cid:2) Pico Micro-
tubes. The shearing program was optimized to obtain 200-700 bp fragments (30 s on, 30 s off for 10 cycles). The sonicated samples
were centrifuged at 13,000 rpm at 4(cid:4)C for 10 min and the supernatant was collected and diluted 5-fold in IP dilution buffer (50 mM Tris
pH 7.5, 150 mM NaCl, 1 mM EDTA, 1% Igepal, 0.25% deoxycholate, 1% protease inhibitors). A fraction of the input was saved and
frozen (4% of total) prior to proceeding to immunoprecipitation. Immunoprecipitations were performed overnight at 4(cid:4)C using 5 mg of
anti-H3K9me3 antibody (abcam ab8898). The washing steps were performed with PierceTM Protein A/G magnetic beads (Thermo
Fisher Scientiﬁc) using the following protocol: once with IP wash buffer 1 (20 mM Tris pH 8, 2 mM EDTA, 50 mM KCl, 1% Triton
X-100, 0.1% SDS), twice with high salt buffer (20 mM Tris pH 8, 2 mM EDTA, 500 mM NaCl, 1% Triton X-100, 0.01% SDS), once
with IP wash buffer 2 (10 mM Tris pH 8, 1 mM EDTA, 0.25 lithium chloride, 1% Igepal, 1% deoxycholate), and twice with TE buffer
(10 mM Tris pH 8, 1 mM EDTA). Samples were eluted in elution buffer (50 mM sodium bicarbonate, 1% SDS) at 65(cid:4)C for 1 hour and
reversed crosslinked initially in 300 mM NaCl and RNase A for 1 hour at 37(cid:4)C, followed by 63(cid:4)C overnight with Proteinase K

e3 Cell 184, 2503–2519.e1–e7, April 29, 2021

Resource

ll

(Thermo Fisher). The DNA samples were puriﬁed using a Zymo Clean & Concentrator kit and libraries were prepared using the NEB-
Next(cid:2) UltraTM II DNA Library Prep kit (NEB).

Reads were aligned to the human genome (hg19) using bowtie v2.3.2 (Langmead and Salzberg, 2012). Alignments were processed
using deepTools2 bamCoverage (Ramı´rez et al., 2016), normalizing reads to 1x average coverage. The resulting bigWig ﬁles were
visualized on the Integrative Genomics Viewer
(IGV). Peak analysis was performed using MACS (https://github.com/
macs3-project/MACS). Downstream analysis and enrichment at promoter regions, which were deﬁned as ± 2 kb of each TSS
(with the TSSs based on previously published annotations (Horlbeck et al., 2016a) were performed using Python 3.6 with the deep-
Tools2 package. Differential H3K9me3 enrichment was analyzed using DESeq2 (Love et al., 2014), treating distinct sgRNAs against
the same TSS as replicate samples. We note that BOLA1 contains two TSS annotations and our ChIP-seq data show enrichment for
H3K9me3 near TSS1, the closest to the H2B promoter, and no enrichment for TSS2 located 15 kb away (Figures 2G and 2H). We do
not detect transcriptional knockdown of BOLA1 in our RNA-seq data (Table S1).

Western blotting
Western blots of CRISPRoff constructs were performed by harvesting HEK293T cells 2 days post-transfection of CRISPRoff con-
structs. Cells were washed with cold PBS and lysed with RIPA buffer (Thermo Fisher Scientiﬁc) supplemented with Halt Protease
Inhibitor Cocktail (Thermo Fisher Scientiﬁc). After 30 min of lysis at 4(cid:4)C, the samples were centrifuged at 20,000 3 g for 20 min at
4(cid:4)C. The soluble fractions were collected and protein concentrations were quantiﬁed by Pierce BCA Protein Assay Kit (Thermo Fisher
Scientiﬁc). 40 mg of total protein was mixed and heated with SDS loading buffer, separated on Bolt 4%–12% Bis-Tris Plus Gels
(Thermo Fisher Scientiﬁc), and wet transferred into PVDF membrane in buffer containing 1 3 MOPS and 10% methanol. Membranes
were blocked with Odyssey(cid:2) Blocking Buffer (LI-COR), incubated with antibodies against S. pyogenes Cas9 (Active Motif 61577) and
calnexin (Abcam ab22595) at 4(cid:4)C overnight. Membranes were washed at least 3 times with blocking buffer before incubation with
IRDye(cid:2) secondary antibodies against Cas9 and calnexin. Blots were imaged using Odyssey(cid:2) CLx (LI-COR).

Bisulﬁte sequencing PCR
Genomic DNA was extracted from (cid:1)1-2x106 cells according to manufacturer’s instructions using the PureLink Genomic DNA Mini Kit
(Invitrogen). For each condition, 1 mg genomic DNA underwent bisulﬁte conversion and cleanup according to manufacturer’s instruc-
tions using the EpiTect Bisulﬁte kit (QIAGEN). Puriﬁed bisulﬁte-converted DNA was ampliﬁed using EpiMark Hot Start Taq (NEB).
Amplicons were gel puriﬁed using a Gel DNA Recovery Kit (Zymo) and PCR ampliﬁed again using EpiMark Hot Start Taq. Amplicons
were cloned into the pCR2.1 TOPO vector according to manufacturer’s instructions using the TOPO TA Cloning Kit (Invitrogen). Clon-
ing products were transformed into Stellar E. coli cells (Takara) and plated on carbenicillin plates with X-gal for blue-white screening.
Colonies were picked per condition and sequenced by Sanger sequencing. Primer sequences for bisulﬁte-PCR ampliﬁcation are
listed in Table S7. The primer sequences for amplifying the GAPDH-Snrpn fragment was obtained from Liu et al. (2016).

Whole genome bisulﬁte sequencing and analysis
We generated whole genome bisulﬁte sequencing (WGBS) libraries for 12 samples, corresponding to WT (untreated), NT (non-tar-
geting), and T (targeting) for CLTA and DYNC2LI1 experiments and proﬁled in two replicates. After DNA extraction and RNase A treat-
ment using the PureLink Genomic DNA Mini Kit (Invitrogen), 1 mg of DNA was diluted to 7.7 ng/mL in 130 uL and sheared to 450-550 bp
length using a Covaris E220 evolution with intensiﬁer for 50 s at 140V, 7(cid:4)C, 10% amplitude, 200 cycles. The sonicated DNA was
recovered and concentrated using Ampure XP beads and sizes of the sheared DNA were checked on an Agilent TapeStation device
with a D1000 HS DNA ScreenTape. Next, the sheared DNA was bisulﬁte converted using the EZ DNA Lightning kit (Zymo, Cat. No.
D5030) according to the manufacturer’s instructions and a desulphonation step of 16 minutes. Then, 500 ng of sheared and con-
verted DNA was subjected to library preparation using a Swift Accel(cid:2)-NGS Methyl-Seq DNA Library Kit (Cat. No. 30024) and
Methyl-Seq Unique Dual Indexing Primers (Cat. No. 39096). The prepared libraries were quantiﬁed using a KAPA Library Quantiﬁca-
tion kit (Roche, Cat. No. KK4873) and sequenced using paired-end 150bp reads (300 cycles) on an Illumina NovaSeq6000 instrument
with an S4 ﬂow cell and a 35% spike-in from another non-WGBS library to diversify the sample pools. We obtained on average 707M
paired-end reads (range 629-835M) across all 12 libraries.

Prior to alignment, sequencing reads were trimmed using fastp (version 0.21.0) (Chen et al., 2018) and the following parameters:
--adapter_sequence=AGATCGGAAGAGCACACGTCTGAACTCCAGTCA --adapter_sequence_r2=AGATCGGAAGAGCGTCGTGT
AGGGAAAGAGTGT --trim_front1=0- -trim_tail1=20 --trim_front2=20 --trim_tail2=0. Trimming is required to remove bases that
are added during the Adaptase reaction that could affect alignment and DNA methylation calling. Processed reads were aligned
to the hg38 reference genome using methylCtools (version 1.0.0, https://github.com/hovestadt/methylCtools) (Hovestadt et al.,
2014) and bwa mem (version 0.7.17, arXiv: 1303.3997v1) using default parameters. Over 98% of reads were aligned as proper pairs
across samples. After marking of PCR duplicates using sambamba (version 0.8.0) (Tarasov et al., 2015), genome-wide CpG methyl-
ation values were called using methylCtools using the–trimPE parameter. Average CpG coverage was (cid:1)25-fold across samples.
Bisulﬁte conversion efﬁciency was estimated to be greater than 99.5% based on non-CpG methylation.

Downstream analyses were performed in R (version 4.0.2, https://www.r-project.org/) using the bsseq (version 1.24.4) (Hansen
et al., 2012) and DSS (version 2.36.0) (Park and Wu, 2016) packages. Speciﬁcally, we applied the DMLtest function to ﬁrst call
differentially methylated loci (using 500bp smoothing windows) between treatments, and then the callDMR function to deﬁne

Cell 184, 2503–2519.e1–e7, April 29, 2021 e4

ll

Resource

differentially methylated regions. Results were visualized by plotting log10-transformed p values associated with individual loci (pos-
itive values for loci that gained methylation, negative values for loci that lost methylation). Loci were colored by their difference in
beta-values ((cid:3)1: blue, 0: white, +1: red). Close-ups of genomic regions were generated by visualizing beta-values of individual
loci in IGV (Robinson et al., 2011). Data was displayed as bar charts (min/0: blue, mid/0.5, max/1: red).

Cas9 genome editing and 5-aza-dC treatments
Lentiviral particles expressing Cas9 from S. pyogenes were transduced into HEK293T cells that have CRISPRoff-silenced Snrpn-
GFP or GFP-tagged CLTA and H2B. Cas9-expressing cells, marked by BFP ﬂuorescence in the lentivirus vector, were FACS-sorted.
To inactive DNMT1, lentiviral particles expressing a sgRNA that targets DNMT1 were infected into the cell lines. Reactivation of the
silenced genes was assessed by GFP expression, measured by ﬂow cytometry. The last time point was taken at 9 days post sgRNA
infection, as cell viability was severely reduced past this time point.

For 5-aza-dC treatment, 1x105 CRISPRoff-silenced CLTA-GFP HEK293T cells were seeded in each well of a 24-well plate. 24 hours
later, the media was replaced with media supplemented with aqueous 5-aza-20-deoxycytidine (5-aza-dC) (MP Biomedicals). The
following day, 5-aza-dC-containing media was aspirated, cells were detached and analyzed for viability and GFP expression on
an Attune NxT ﬂow cytometer (Thermo Fisher Scientiﬁc). Cells were subsequently passaged with fresh media every 2-3 days and
analyzed by ﬂow cytometry.

Genome-wide CRISPRoff screen and analysis
For genome-wide CRISPRoff screens, we constructed a compact library to maximize on-target knockdown while minimizing overall
library size. We targeted each gene in the human genome with two unique sgRNAs expressed from tandem U6 expression cassettes
in a single vector. To select the optimal sgRNAs targeting each gene, we relied on our previously published hCRISPRi v2.1 library
(Horlbeck et al., 2016a). A three tiered approach was used to balance empirical data with computational predictions and select
the most active sgRNA pair for each gene. First, for strong essential genes (p value < 0.001 and gamma < (cid:3)0.2 in hCRISPRi v2 growth
screen), sgRNAs were ranked by growth. Next, for genes that were identiﬁed as a signiﬁcant hit in previous CRISPRi screens, sgRNAs
were ranked by the sum of Z-scored phenotypes across screens. Finally, for all other genes, sgRNAs were ranked by the regression
scores in hCRISPRi v2.1. Using this ranking scheme, we designed a genome-wide library consisting of only 21378 elements (20360
targeting elements plus 1018 non-targeting controls). A list of protospacer sequences in the genome-wide library is available in
Table S3.

To clone our libraries, we began by generating a modiﬁed single sgRNA lentiviral expression vector, pJR104, from the parental
pJR85 (Addgene 140095) by: (i) replacing the BFP ﬂuorescent marker with a BsmBI-negative GFP, (ii) replacing the sgRNA constant
region with an unmodiﬁed constant region (i.e., without a Perturb-seq capture sequence), and (iii) incorporating a UCOE element
upstream of the EF1alpha promoter to prevent silencing. Dual-sgRNA oligos were synthesized as an oligonucleotide pool (Twist
Biosciences) with the structure: 50- PCR adaptor - CCACCTTGTTG - protospacer A - gtttcagagcgagacgtgcctgcaggatacgtctcagaaa
catg - protospacer B - GTTTAAGAGCTAAGCTG - PCR adaptor-30. Oligo pools were PCR-ampliﬁed, digested with BstXI/BlpI, gel
extracted, ligated into the sgRNA lentiviral vector pJR104, and transformed to generate an intermediate library as previously
described (Replogle et al., 2020). An insert, pJR98, consisting of a sgRNA constant region variant 3 (Adamson et al., 2016) and a
hU6 promoter was synthesized (IDT), BsmBI-digested, and ligated into the BsmBI-digested intermediate library. The ﬁnal dual-guide
library was then transformed for ampliﬁcation and sequenced by next-generation sequencing to ensure library representation and
uniformity.

Pooled tiling sgRNA screens in HEK293T cells were performed by ﬁrst transducing cells with lentiviral particles encoding the
sgRNA library. The infection efﬁciency was measured 2 days post-infection by ﬂow cytometry, aiming for 20%–30% sgRNA-positive
cells. The screens were performed with two technical replicates and each sgRNA was represented by at least 1000 cells throughout
the duration of the screens. Two days post transduction, cells were treated with puromycin until the cell population was 90% sgRNA
positive, as marked by mCherry encoded in the lentiviral vector. For transient transfection of CRISPRoff, (cid:1)8x106 cells were ﬁrst
seeded on 15 cm2 plates. About 20-24 hr later (70%–80% conﬂuency), each 15 cm2 plate of cells were transfected with 20 mg of
plasmids encoding CRISPRoff or CRISPRoff-Dnmt3AE765A catalytic mutant. Two days post-transfection, cells were sorted for
CRISPRoff expression (BFP) and plated on 15 cm2 plates. Four days post-sorting, cells were trypsinized and an aliquot of cells
((cid:1)110x106) was harvested as an initial time point T(0) and the rest of the cell population was passaged for at least 10 more cell dou-
blings. Cells were then collected as a ﬁnal time point (T10).

DNA libraries of T(0) and T(10) were prepared for deep sequencing essentially as previously described (Jost et al., 2020). Brieﬂy,
genomic DNA was isolated using a NucleoSpin Blood XL kit (Macherey–Nagel). Then, isolated gDNA was directly ampliﬁed by 23
cycles of PCR using NEBNext Ultra II Q5 PCR MasterMix (NEB), appending Illumina adaptors and unique sample indices (oJR234
forward primer: 50-AATGATACGGCGACCACCGAGATCTACACCGCGGTCTGTATCCCTTGGAGAACCACCT-30; index primers 50-
CAAGCAGAAGACGGCATACGAGATnnnnnGCGGCCGGCTGTTTCCA GCTTAGCTCTTAAA-30). Sequencing was performed on a
NovaSeq 6000 (Illumina) using a 19 bp read 1, 19 bp read 2, and 5 bp index read 1 with custom sequencing primers oJR326 (custom
read 1, 50- CGCGGTCTGTATCCCTTGGAGAACCACCTTGTTGG-30), oJR328 (custom read 2, 50- GCGGCCGGCTGTTTCCAGCT
TAGCTCTTAAAC-30), and oJR327 (custom index read 1, 50- GTTTAAGAGCTAAGCTGGAAACAGCCGGCCGC-30).

e5 Cell 184, 2503–2519.e1–e7, April 29, 2021

Resource

ll

Sequencing counts from CRISPR screens were processed to calculate gene phenotypes using a custom Python script, similar to
as previously described (Horlbeck et al., 2016a), except now two protospacer sequences are matched instead of just one. In this
case, gene phenotype is the same as sgRNA phenotype, and is deﬁned by log2 sgRNA enrichment / cell doublings. The calculated
phenotype scores are reported in Table S3. All additional CRISPR screen data analyses and plotting were performed in Python 3.6
using a combination of Numpy (v1.16.2), Pandas (v0.23.4), Scipy (v1.4.1), and sklearn (v0.22.2). The DepMap essential and nones-
sential genes were downloaded from DepMap Public 20Q2 at https://depmap.org/portal/download/ (Blomen et al., 2015; Hart et al.,
2014). Gene set enrichment analysis (GSEA) was performed using GSEAPY (v0.9.19) in Python using the 2019 Human KEGG
Pathway database.

Tiling screen library design, experimental speciﬁcations, and analysis
For the growth-based screen, a tiling sgRNA library targeting essential genes was designed based on our previously published
genome-wide CRISPRi screen in K562s. For genes with no canonical CGIs (as deﬁned by no CGIs within 2.5 kb of TSS, with the
TSSs based on previously published annotations (Horlbeck et al., 2016a) and CGI annotations from the UCSC Genome Browser),
all genes with an average growth phenotype score less than (cid:3)0.2 were picked. For genes with one or multiple CGIs (also deﬁned
as within 2.5 kb of TSS), genes with an average growth phenotype score between (cid:3)0.2 and (cid:3)0.4 were selected. In total, 39 genes
with no canonical CGIs, 425 genes with one annotated CGI, and 56 genes with multiple CGIs were chosen. A list of protospacer se-
quences comprising the library is available in Table S4.

For each gene, all sequences ± 2.5 kb (or ± 1 kb depending on the position and length of the CGI) of the TSS containing 19 bp
followed by an NGG PAM were extracted as potential sgRNAs. All sequences were prepended with a 50 G to enable robust transcrip-
tion from the U6 promoter, whether or not this base was present in the genomic sequence. The sgRNAs were scored for off-target
sites using weighted Bowtie, as previously described (Horlbeck et al., 2016a). Brieﬂy, sgRNAs were scored by uniqueness in the
genome, as determined by an empirically derived and experimentally veriﬁed scoring metric: PAM G1 = 40, PAM G2 = 19, PAM
N = 0, the next 7 bases from the PAM = 28, the next 5 bases = 19, and the last 7 bases = 10. A mismatch score was then calculated
by the sum of the mismatches with the scoring metric. This mismatch score was implemented using the Phred score threshold
feature of Bowtie using the –nomaqround, -n 3, -l 15, -a, and –best ﬂags. For the most stringent threshold, sgRNAs were required
to have no more than 1 alignment (the sgRNA target site itself) in the genome with a mismatch score of 39. Control non-targeting
sgRNAs were extracted from a previously tested list of control sgRNAs (Horlbeck et al., 2016a).

The tiling libraries for endogenously GFP-tagged CLTA, HIST2H2BE (H2B), RAB11A, and VIM were designed similarly, selecting for
sgRNAs ± 2.5 kb from the TSS and yielding (cid:1)600 sgRNAs per gene. The protospacer sequences for each GFP-tagged gene library
are available in Table S5.

Oligonucleotide pools were designed with ﬂanking PCR and restriction sites (BstXI and BlpI), synthesized by Agilent Technologies,
and cloned into the sgRNA expression vector pCRISPRia-v2 (Addgene #84832), as described previously (Horlbeck et al., 2016a). The
expression vector contains a U6 promoter driving the sgRNA expression, as well as an EF1a promoter driving puromycin T2A-
mCherry.

The tiling screens in HEK293Ts were performed in a similar workﬂow as the genome-wide CRISPRoff screens. To perform the tiling
screen in K562s, cells stably expressing dCas9-KRAB were ﬁrst transduced with lentiviral particles of the tiling sgRNA library. Two
days post transduction (20%–30% infection), cells were treated with puromycin until the population consisted of 90% sgRNA-ex-
pressing cells. A T(0) time point was then collected and cells were continued to passage for 10 more cell doublings to obtain the
T(10) time point.

Sequencing counts from CRISPR screens were processed using the Python-based ScreenProcessing pipeline (https://github.
com/mhorlbeck/ScreenProcessing), as previously described (Horlbeck et al., 2016a) to calculate sgRNA phenotypes. sgRNA pheno-
type score is deﬁned by log2 sgRNA enrichment / cell doublings. All additional CRISPR screen data analyses and plotting were per-
formed in Python 2.7 using a combination of Numpy (v1.12.1), Pandas (v0.17.1), and Scipy (v0.17.0). K562 and GM12878 MNase-seq
data was obtained from the ENCODE consortium as processed continuous signal data (BigWig ﬁle format; Michael Snyder lab, Stan-
ford University). The average of the K562 and GM12878 MNase-seq data was used. The sequencing counts of each protospacer are
available in Table S4 and the calculated phenotype scores are available in Table S4. We note that the phenotypes in K562 CRISPRi
(median g = (cid:3)0.46) are more pronounced compared to the HEK293T CRISPRoff screen (median g = (cid:3)0.33). However, as we have
previously demonstrated, because the genes were chosen based on essentiality in K562s, this difference likely can be attributed to
cell type variability between K562 and HEK293T.

GFP-tagged sgRNA tiling screen
The tiling sgRNA screens in HEK293T GFP-tagged cell lines were performed in a similar workﬂow as the growth-based screens
described above. The previously published endogenously GFP-tagged cell lines (CLTA, HIST2H2BE, RAB11A, VIM) were further
FACS sorted to yield > 99% GFP-positive cells to minimize background GFP-negative cells. After generating cell lines that stably
express the respective sgRNA library, plasmids expressing CRISPRoff were transfected. Two days later, the transfected cells
were sorted and subsequently passaged for 4 weeks by trypsinization every 2-3 days. At the 4 weeks time point, each cell line
had the following detectable GFP-silenced population: 21.8% CLTA, 22.7% HIST2H2BE, 3.05% RAB11A, and 24.7% VIM. The
GFP-on and GFP-off populations were FACS sorted into separate bins, collecting (cid:1)2x106 cells per population for each cell line.

Cell 184, 2503–2519.e1–e7, April 29, 2021 e6

ll

Resource

The log2 fold change in sgRNA abundance was quantiﬁed by the presence of each sgRNA in the GFP-off population compared to the
total population. Analysis was performed using Python 2.7, similar to the other tiling screens described previously. The deep
sequencing counts from each screen and the calculated phenotype scores are available in Table S5.

iPSC manipulation and neuronal differentiation
Transient transfections of iPSCs were performed in 6-well plates using TransIT-LT1 Transfection Reagent (Mirus). First, a mixture of
0.5 mL of mTeSR1 and 2 ml of 10 mM Y-27632 ROCK inhibitor were added to each well of a Matrigel coated 6-well plate. Then, a
mixture of plasmids encoding dCas9-KRAB or CRISPRoff (1 mg), 1 mg of sgRNA plasmids, and 200 ng of plasmid encoding BCL-
XL (Li et al., 2018) were added to 0.4 mL of Opti-MEM. TransIT-LT1 (12 ml) was added to the DNA-Opti-MEM mixture and added
to each well of a 6-well plate. Cells at 70%–80% conﬂuence were lifted with Accutase, washed with DPBS, and counted using a
Countess (Thermo Fisher AMQAX1000). About 1.5x106 cells were resuspended in 1 mL of mTeSR1 and added to each well contain-
ing the transfection mixtures. Transfected cells were sorted 3 days post-transfection on a BD FACS Fusion and plated in mTeSR
media supplemented with 10 mM Y-27632 ROCK inhibitor.

Neuronal differentiations were performed on passage number 46 iPSCs using doxycycline-inducible NGN2 (Tian et al., 2019). On
day (cid:3)3, cells at 70%–80% conﬂuency were lifted with Accutase and washed with DPBS. About 7.5x105 cells were resuspended in
2 mL of N2 Pre-differentiation Media each well of a Matrigel coated 6-well plate. On day 0, cells were lifted with Accutase and washed
with DPBS. About 5x105 cells were resuspended in 2 mL classic N2/B27 Differentiation Media and plated onto Poly-D-Lysine coated
plates (Corning 354413). On day 3, the media in each well were aspirated and replaced with 2 mL of fresh N2/B27 Differentiation
Media. On day 7, 1 mL of media was removed from each well and replaced with 1 mL of fresh N2/B27 Differentiation Media. N2
Pre-differentiation Media was made with 1X Knockout DMEM/F12 (Thermo Fisher 11320-033), 1X NEAA (Thermo Fisher 11140-
050), 1X N2 Supplement (Thermo Fisher 17502-048), 10 ng/ml NT-3 (PreproTech 450-03), 10 ng/ml BDNF (PreproTech 450-02),
1 mg/ml Mouse Laminin (Thermo Fisher 23017-015), 10 nM Y-27632 ROCK inhibitor, and 2 mg/ml doxycycline (Sigma-Aldrich
D3447-500MG). Classic N2/B27 Differentiation Media was made with 0.5X DMEM/F12 (Thermo Fisher 10888-033), 0.5X Neuro-
basal-A (10888-022), 1X NEAA, 0.5X GlutaMAX (Thermo Fisher 35050-061), 0.5X N2 Supplement, 0.5X B27-VA Supplement (Thermo
Fisher 12587010), 10 ng/ml NT-3, 10 ng/ml BDNF, 1 mg/ml Mouse Laminin, and 2 mg/ml doxycycline.

We used iNeuron RNA-Seq (https://kampmannlab.ucsf.edu/ineuron-rna-seq) to support the activation of MAPT gene expression

through neuronal differentiation of iPS cells.

QUANTIFICATION AND STATISTICAL ANALYSIS

The statistical tests and number of independent replicates per experiment are indicated in the ﬁgure legends. The statistical signif-
icance from RNA-seq, ChIP-seq, and whole genome bisulﬁte sequencing experiments are detailed in the Method details section.

e7 Cell 184, 2503–2519.e1–e7, April 29, 2021

Resource

Supplemental ﬁgures

ll

A

Linker
GGSGGGS
XTEN16

XTEN80

Linker

Gilbert et al., 2013

Cleavage
sequence

XTEN16
XTEN80

1×
2×

V1

KRAB

dCas9

HA NLS

3A

3L

NLS P2A BFP

Fusion design from
Stepper et al.

C

3A  3L dimer

3A  3L dimer

D

B

f
f
o
A
T
L
C
h
t
i

w
s

l
l

e
c
%

80

60

40

20

0

V1
variants

dCas9-3A-3L

dCas9-KRAB

0

2

4

6

8 10 12 14 16 18

Days post-transfection

V1

D3A

D3L

CpG
DNA

V2

V2.1

3A 3L

XTEN80

dCas9

HA

2×NLS

BFP

KRAB

V2.2

3A 3L

XTEN80

dCas9

HA

2×NLS

XTEN16

KRAB

P2A

BFP

V2.3

3A 3L

XTEN80

NLS

dCas9

NLS XTEN16

KRAB

P2A

BFP

V2.4

3A 3L

XTEN80

NLS

dCas9

NLS XTEN16

BFP

KRAB

F

d
e
t
c
e
f
s
n
a
r
t
n
U

B
A
R
K
-
9
s
a
C
d

9
s
a
C
d

CRISPRoff

1
.
2
V

2
.
2
V

3
.
2
V

4
.
2
V

1
V

anti-Cas9

anti-calnexin

Snrpn-GFP synthetic reporter

CRISPRoff-V2

CRISPRoff-V1

100

f
f
o
A
T
L
C
h
t
i

w
s

l
l

e
c
%

V1
V2.1

V2.3

V2.4

I

C
R
S
P
R
o
f
f

dCas9-KRAB

dCas9

12

14

6

8
Days post-transfection

10

75

50

25

0

2

4

H

0

10

20

30
Days post-transfection

40

dCas9-3A-3L
dCas9-KRAB

50

C
S
S

Double gene targeting

2.73

16.4

3.72

18.8

11.2

68.9

12

63.7

13.8

ITGB1–,CD81–

ITGB1

1
8
D
C

CD81–,CD151–

CD151

53.7

1
B
G
T

I

ITGB1–,CD151–

CD151

Untransfected

+ CRISPRoff mRNA

1.81% off

61.6% off

Four gene
targeting

CLTA

27.3

7.75

J

f
f
o
e
n
e
g
h
t
i

w
s

l
l

e
c
%

60

40

20

0

ITGB1

CLTA

CD151
CD81

K

100

f
f
o
e
n
e
g
h
t
i

w
s

l
l

e
c
%

80

60

40

20

0

ITGB1-off
ITGB1-on

CLTA

CD81

CD151

(legend on next page)

f
f
o
-
P
F
G
h
t
i

w
s

l
l

e
c
%

100

80

60

40

20

0

E

G

I

1
8
D
C

ll

Resource

Figure S1. Optimization of CRISPRoff design for durable gene silencing, related to Figure 1
(A) A schematic of the CRISPRoff-V1 construct and various linker sequences used to generate protein variants.
(B) A time course of CLTA-GFP silencing after transfection of CRISPRoff-V1 variants or controls dCas9-KRAB (gray) and dCas9-D3A-D3L (orange).
(C) A crystal structure of DNMT3A (orange) and DNMT3L (yellow) in complex with CpG-containing DNA (PDB 5YX2). The arrows point to the dCas9 attachment
positions for CRISPRoff-V1 and CRISPRoff-V2.
(D) A schematic of four CRISPRoff-V2 constructs that varies BFP as a linker between dCas9 and KRAB or separated from CRISPRoff by a P2A sequence. The
V2.3 and V2.4 constructs encode NLS sequences at the amino and carboxyl termini of dCas9.
(E) A western blot of dCas9, dCas9-KRAB, CRISPRoff construct protein expression.
(F) A time course of CLTA-GFP silencing after transfection of the V1 and V2.1, V2.3, V2.4 constructs, along with dCas9-KRAB and dCas9 only controls.
(G) A time course of Snrpn-GFP silencing after transfection of dCas9-D3A-3L (orange), dCas9-KRAB (gray), or CRISPRoff-V1 (black) and V2 (blue).
(H) A representative ﬂow cytometry plot of HEK293T CLTA-GFP cells 6 days after transfection of mRNA encoding CRISPRoff.
(I) Representative ﬂow cytometry plots of multiplexing gene targeting of two genes simultaneously, measured at 30 days post-transfection.
(J) Quantiﬁcation of gene silencing measured at 31 days post-transfection of CRISPRoff with four simultaneous sgRNAs targeting ITGB1, CLTA, CD81,
and CD151.
(K) Quantiﬁcation of cells with CLTA, CD81, and CD151 silenced in cells that have ITGB1 either silenced (blue) or unsilenced (gray) in the four gene knockdown
experiment.
The error bars in B, F, G, J, and K represent SD from three independent experiments.

Resource

A

K562

–dox

1d
+dox

1d

2d

post
dox-wash

CRISPRoff
expression (BFP)

B

f
f

o

1
8
D
C
h

t
i

w
s

l
l

e
c
%

100

80

60

40

20

0

+ dox (4d)
+ dox (3d)
– dox

E

CLTA

dSpyCas9

dSauCas9

dLbCas12a

100

80

60

40

20

f
f
o
A
T
L
C
h
t
i

w
s

l
l

e
c
%

0

sgRNA abc
NT

pool

abc

NT

pool

NT

abc

array

pool

ll

iPSC

Non-targeting sgRNA

CD81 sgRNA

5.4% off

37.8% off

D

6
10

5
10

P
F
G

4
10

3
10

0

0

103

104

105

106

0

103

104

105

106

18 days p.t.

100

80

60

40

20

0

ITGB1

CD81
CD151

ITGB1

CD81
CD151

HeLa

U2OS

CD81 expression

C

f
f

o

e
n
e
g

h

t
i

w
s

l
l

e
c
%

F

100

80

60

40

20

f
f
o
B
2
H
h
t
i

w
s

l
l

e
c
%

0
sgRNA

H2B

dSpyCas9

dSauCas9

dLbCas12a

abc

NT

pool

abc

NT

pool

NT

abc

array

pool

Figure S2. CRISPRoff is applicable in various cell lines and with orthogonal RNA-guided CRISPR proteins, related to Figure 1
(A) Flow cytometry histograms of CRISPRoff expression (BFP) before and after doxycycline (dox) treatment. After 24 hours of dox administration, the media was
replaced with media without doxycycline (1d and 2d post dox-wash) to turn off CRISPRoff expression.
(B) Quantiﬁcation of K562 cells with CD81 silenced 10 days after initial dox-induction of CRISPRoff expression. Doxycycline was included in the media for either
3 days (middle) or 4 days (right) prior to washing cells to remove doxycycline.
(C) Quantiﬁcation of cells with ITGB1, CD81, or CD151 silenced in HeLa and U2OS measured at 18 days post-CRISPRoff-V1 transfection with sgRNAs targeting
the indicated genes.
(D) A representative ﬂow cytometry plot of CD81 expression in iPS cells after transfection of CRISPRoff with either non-targeting sgRNAs or sgRNAs target-
ing CD81.
(E, F) A comparison of cells with CLTA (E) and H2B (F) silenced 10 days after transfection of CRISPRoff with dCas9 from S. pyogenes (dSpyCas9) or S. aureus
(dSauCas9) or dCas12a from Lachnospiraceae bacterium (dLbCas12a).
The error bars in B, C, E, and F are SD from three independent experiments.

ll

A

ITGB1

CD81

CD151

)

M
P
T
(

i

n
o
s
s
e
r
p
x
E

60

50

40

30

20

10

0

D
K
%
9
9

NT T

250

200

150

100

50

0

150

125

100

75

50

25

0

D
K
%
7
9

D
K
%
6
9

NT T

NT T

E

CD81

CD151

ITGB1

B

14

12

10

8

6

4

2

M
P
T
2
g
o

l

A
N
R
g
s
A
T
L
C

CLTA

0

2.5 5.0 7.5 10.0 12.5
Non-targeting sgRNA log2 TPM

F

RAB11A

HIST2H2BE

CLTA

C
M
P
T
2
g
o

l

A
N
R
g
s
E
B
2
H
2
T
S
H

I

14

12

10

8

6

4

2

0

HIST2H2BE

2.5 5.0 7.5 10.0 12.5
Non-targeting sgRNA log2 TPM

Resource

RAB11A

D

14

12

10

M
P
T
2
g
o

l

A
N
R
g
s
A
1
1
B
A
R

8

6

4

2

0

2.5 5.0 7.5 10.0 12.5
Non-targeting sgRNA log2 TPM

– 1000

– 500

0

500

1000

– 1000

– 500

Distance from target (kb)

0

500
Distance from target (kb)

1000

G

e
g
a
r
e
v
o
c
G
p
C
e
g
a
r
e
v
A

30

25

20

15

10

5

0

J

Rep. 1

Rep. 2

H

0.64

0.62

0.60

0.58

l

n
o
i
t
a
y
h
t
e
m
e
g
a
r
e
v
A

WTNTT

WTNTT
DYNC2LI1
CLTA

WTNTTWTNTT
DYNC2LI1
CLTA

0.56

WT, R1

WT, R2

NT, R1

NT, R2

T, R1

T, R2
WT, R1

WT, R2

NT, R1

NT, R2

T, R1

T, R2

CLTA

DYNC2LI1

K

1 kb

I

l

)
0
.
1
-
0
(
n
o
i
t
a
y
h
t
e
m
e
g
a
r
e
v
a

2
R

,

T
W

,

A
T
L
C

2
R

,

T
W

,
1
I
L
2
C
N
Y
D

Untr., R1
Untr., R2
NT, R1

NT, R2
T, R1
T, R2

f
f

o
R
P
S
R
C
+

I

DYNC2LI1, T, R1
DYNC2LI1, T, R2
DYNC2LI1, NT, R1
DYNC2LI1, NT, R2
DYNC2LI1, WT, R1
DYNC2LI1, WT, R2
CLTA, T, R1
CLTA, T, R2
CLTA, NT, R1
CLTA, NT, R2
CLTA, WT, R1
CLTA, WT, R2

1
R

2
R

,

T

,

T

,
1
I
L
2
C
N
Y
D

,
1
I
L
2
C
N
Y
D

1
R

,

T
N

,
1
I
L
2
C
N
Y
D

2
R

,

T
N

,
1
I
L
2
C
N
Y
D

1
R

,

T
W

,
1
I
L
2
C
N
Y
D

2
R

1
R

2
R

,

T

,

T

,

A
T
L
C

,

A
T
L
C

,

T
W

,
1
I
L
2
C
N
Y
D

1
R

,

T
N

,

A
T
L
C

2
R

,

T
N

,

A
T
L
C

1
R

,

T
W

,

A
T
L
C

2
R

,

T
W

,

A
T
L
C

1
R

,

T
N

,

A
T
L
C

CLTA, WT, R1

CLTA, WT, R1

1
R

,

T
N

,
1
I
L
2
C
N
Y
D

1
R

,

T

,

A
T
L
C

1
R

,

T

,
1
I
L
2
C
N
Y
D

average methylation (0-1.0)

L

10 kb

Untr., R1
Untr., R2
NT, R1

NT, R2
T, R1
T, R2

f
f

o
R
P
S
R
C
+

I

DYNC2LI1, WT, R1

DYNC2LI1, WT, R1

DYNC2LI1, WT, R1

CpG island

ZSCAN16

ZSCAN16-AS1

CpG island

RPS6KA6

Figure S3. Transcriptional speciﬁcity of CLTA, H2B, and RAB11A silencing, related to Figure 2
(A) An RNA-sequencing TPM (transcripts per kilobase million) plot for HEK293T cells transfected with CRISPRoff and NT (non-targeting) sgRNAs compared to
untransfected HEK293T cells.
(B, C, D) RNA-sequencing TPM (transcripts per kilobase million) are plotted for HEK293T cells transfected with CRISPRoff and either NT sgRNAs compared to
sgRNAs targeting CLTA (B), HIST2H2BE (C), or RAB11A (D). The data are representative of the average of two independent replicates.

(legend continued on next page)

100%
activation

0

100%
repression

CLTA, WT, R1

Resource

ll

(E, F) Representation of gene expression changes ± 1000 kb from the annotated targeted gene for CD81, CD151, ITGB1 (E) and RAB11, HIST2H2BE, CLTA (F).
Each box represents a gene.
(G) A barplot of genome-wide average CpG coverage obtained from whole genome bisulﬁte sequencing. WT indicates untransfected cells; NT indicates
CRISPRoff delivered with non-targeting sgRNAs; T indicates CRISPRoff delivered with sgRNAs targeting CLTA or DYNC2LI1. The experiments were performed in
two replicates. CLTA experiments are presented in Figure 2. DYNC2LI1 experiments are presented in Figure 5.
(H) A barplot of genome-wide average CpG methylation (beta-values) in the samples described in (G).
(I) Heatmap plots comparing average CpG methylation (beta-values) of 20-CpG sliding windows between untransfected (WT) replicates (left), WT and NT (middle),
and WT and targeting sgRNAs (right) for CLTA (top row) and DYNC2LI1 (bottom row) experiments. Red color indicates highest density and blue color indicates
lowest density. White areas indicate the absence of windows with the respective average methylation levels.
(J) A heatmap showing pairwise correlations between genome-wide CpG methylation proﬁles of the samples described in (G), including replicates. Samples are
sorted by unsupervised hierarchical clustering. Dark brown color indicates highest correlation, light yellow color indicates lowest correlation. This analysis
highlights the variations in global CpG methylation between samples for CLTA and DYNC2LI1 experiments.
(K) A close up of a 17 kb genomic region containing the ZSCAN16 gene. DNA methylation proﬁles for untransfected, NT, and targeting sgRNA cells from the CLTA
experiment are shown. The box highlights a differentially methylated region at the gene promoter, indicating a gain of CpG methylation in the targeting sgRNA
cells compared to the control cells.
(L) A close up of a 30 kb genomic region containing the RPS6KA6 gene. The box highlights a gain of CpG methylation at the promoter in the targeting sgRNA cells.
A CpG island located in the promoter of the gene is indicated in green.

A

D

E

B

DNMT1
KO

ll

100

80

60

40

20

d
e
t
a
v
i
t
c
a
e
r
s

l
l

e
c
%

0

Snrpn
H2B

CLTA

Resource

C

28d p.t.

80

60

40

20

s

l
l

e
c
d
e
t
a
v
i
t
c
a
e
r

A
T
L
C
%

0
abcNT

pool abcNT
TETv2

pool abcNT
TETv3

pool

abcNT

pool
TETv4

TETv1

[5-aza-dC]
10 μM
8 μM
6 μM
5 μM
4 μM
3 μM
1 μM
1.5 μM
1 μM
0.3 μM
0 μM

2

4

6

8

Days post-treatment

50

40

30

20

10

0

b

s

l
l

e
c
d
e
t
a
v
i
t
c
a
e
r

A
T
L
C
%

CGI

0 bp

promoter

a

exon 1

c

2x MS2 loops

no activator

mU6 sgRNA

EF1α MCP XTEN80

2xP2A

mCherry

VP64

mU6

sgRNA

EF1α MCP XTEN80 VP64

NLS

2xP2A

mCherry

p65

mU6

sgRNA

EF1α MCP XTEN80 p65

NLS

2xP2A

mCherry

Rta

mU6

sgRNA

EF1α MCP XTEN80 Rta

NLS

2xP2A

mCherry

VP64-p65

mU6

sgRNA

EF1α MCP XTEN80 VP64

NLS

p65

NLS

2xP2A

mCherry

p65-Rta

mU6

sgRNA

EF1α MCP XTEN80 p65 Rta

NLS

2xP2A

mCherry

VPR

mU6

sgRNA

EF1α MCP XTEN80 VP64

NLS

p65 Rta

NLS

2xP2A

mCherry

intron

483 bp

2d p.t.

F

)
.
u
.
a
(

e
c
n
e
c
s
e
r
o
u
l
f

A
T
L
C

10000

8000

6000

4000

1000

0

dCas9

Untr.

p65

VP64

Rta

VP64-p65

VPR
p65-Rta

G

s

l
l

e
c
n
o
-
A
T
L
C
%

50

40

30

20

10

0

0

Untr.

TETv4 only

Rta

p65-Rta

p65

VPR

VP64-p65

VP64

4
v
T
E
T
+

5

10

15

20

25

Days post transfection

H

15

MCP fusion

10

s

l
l

e
c
n
o
-
A
T
L
C
%

5

0

0

5

10

15

Days post transfection

Untr.
dCas9-VPR

p65-Rta

VPR
Rta

VP64-p65

p65

VP64

9
s
a
C
d
+

Figure S4. Reactivation of CRISPRoff-silenced genes by inhibition of DNMT1 and CRISPRon, related to Figure 3
(A) A bar plot of HEK293T cells reactivating CRISPRoff-silenced H2B (black), Snrpn-GFP (gray), or CLTA (blue) 9 days after Cas9-mediated knockout of DNMT1.
(B) Time course measurements of cells with reactivated CLTA expression after increasing doses of 5-aza-dC in HEK293T cells with CLTA silenced by CRISPRoff.
(C) A comparison of CLTA-GFP expression 28 days post transfection of the four TET fusions in Figure 3A co-transfected with one sgRNA sequence or a pool of
three sgRNAs. Error bars represent the range of two technical replicates.
(D) A schematic of the CLTA CGI (green) with sgRNA binding sites annotated (a, b, c). The lollipop plot shading represents the percent of CpG methylation, as
measured by bisulﬁte-PCR of CRISPRoff-silenced cells. Gene annotations were obtained from UCSC Genome Browser.
(E) A schematic of vectors that express a CLTA-targeting sgRNA and MS2 coat protein (MCP) fusion to various transcriptional activators.
(F) Violin plots that represent median CLTA-GFP ﬂuorescence 2 days post-transfection of sgRNAs targeting CLTA and either dCas9 or dCas9 and MCP-fused
transactivators into cells with endogenously expressed CLTA-GFP.
(G) A time course of HEK293T cells with CLTA-GFP reactivation after transfection of sgRNAs targeting CLTA and either TETv4 only, or TETv4 along with various
MCP-fused transactivator domains into cells with CRISPRoff-silenced CLTA. Untreated cells are represented in white circles.
(H) A time course of HEK293T cells with CLTA-GFP reactivation after transfection of sgRNAs targeting CLTA and either dCas9-VPR or dCas9 along with various
MCP-fused transactivator domains, or untransfected cells. The transfections were performed in the absence of TETv4 to measure persistent gene activation in
the absence of DNA demethylation.
The error bars in G and H are SD from three independent experiments.

Resource

A

)
γ
(
e
p
y
t
o
n
e
h
p
1

t

e
a
c

i
l

p
e
R

0.2

0.0

−0.2

−0.4

−0.6

−0.8

C

s
e
n
e
g

f
o

r
e
b
m
u
N

103

102

101

100

CRISPRoff

all genes
negative control

CRISPRoff mutant

all genes
negative control

0.2

0.0

)
γ
(
e
p
y
t
o
n
e
h
p
1

−0.2

−0.4

t

e
a
c

i
l

p
e
R

−0.6

−0.8 −0.6 −0.4 −0.2

0.0
Replicate 2 phenotype (γ)

0.2

−0.8 −0.6 −0.4 −0.2

0.0
Replicate 2 phenotype (γ)

0.2

−0.8

ll

All genes sgRNA phenotypes

B

)
γ
(

e
p
y
t

o
n
e
h
p

0.1

0.0

−0.1

−0.2

−0.3

−0.4

−0.5

−0.6

CRISPRoff rep1

CRISPRoff mutant rep1
CRISPRoff mutant rep2
CRISPRoff rep2

CRISPRoff
CRISPRoff negative controls
CRISPRoff mutant
CRISPRoff mutant negative controls

-0.8

-0.6

-0.4
Phenotype (γ)

-0.2

-0.0

0.2

D

e
r
o
c
S

t
n
e
m
h
c
i
r
n
E

0.8

0.6

0.4

0.2

0.0

DNA replication

Ribosome

E

e
r
o
c
S

t
n
e
m
h
c
i
r
n
E

0.6

0.4

0.2

0.0

Genes ranked by growth phenotype

Genes ranked by growth phenotype

Figure S5. Genome-wide silencing by CRISPRoff is reproducible and speciﬁc, related to Figure 4
(A) A plot comparing the phenotype score (g) of genes between technical replicates of the CRISPRoff (left) and CRISPRoff D3A methyltransferase mutant (right)
genome-wide screens. The negative control sgRNAs are highlighted in blue.
(B) Violin plots of the phenotype score (g) of all genes from each screen.
(C) A histogram of the number of genes with the indicated phenotype score (g) from the CRISPRoff and CRISPRoff mutant screens. The light green and light
orange lines correspond to the phenotype scores of negative control sgRNAs.
(D, E) Gene set enrichment analysis (GSEA) for genes associated with DNA replication and ribosome, conﬁrming enrichment of expected essential genes. Genes
are ranked from lowest (red) to highest (blue) phenotype scores.

ll

A

7

6

5

4

3

2

1

0

l

e
u
a
v
-
p
y
e
n
t
i
h
W
-
n
n
a
M
0
1
g
o
l
-

C

)
γ
(

0.0

–0.2

–0.4

f
f
o
R
P
S
R
C

I

0.0

t
n
a
t
u
m

–0.2

–0.4

Resource

B

Multiple CGI genes

e
r
o
c
s
e
p
y
t
o
n
e
h
p
d
e
z

i
l

a
m
r
o
N

0.0

–0.2

–0.4

–0.6

–0.8

–1.0

293T CRISPRoff
293T CRISPRoff mutant
K562 CRISPRi

–1000

–500

0

500

1000

all genes
picked genes with no CGI
picked genes with one CGI
picked genes with multiple CGI

–0.6

–0.4

–0.2

0.0

Phenotype, average of 3 strongest gammas

TBCD

CGI

GFER

D

e
p
y
t
o
n
e
h
P

e
r
o
c
s

)
γ
(

0.0

–0.2
–0.4

i

l 4
a
n
g
s
e
s
a
N
M

2

–1000

i

R
P
S
R
C

I

0.0

–0.2

–0.4

–2000

–1000
0
Position relative to TSS (bp)

1000

2000

Position relative to TSS (bp)

E

IMMT

CGI

)
γ
(

0.0

e
p
y
t
o
n
e
h
P

e
r
o
c
s

l

–0.2
–0.4
a
n
g
s
e
s
a
N
M

3
2

1

i

–500
500
0
Position relative to TSS (bp)

1000

–1000

–500
500
0
Position relative to TSS (bp)

1000

F

G

n

i

e
g
n
a
h
c
d
o

l

f

2
g
o

l

e
s
a
N
M

Infect
sgRNA library

Transfect
CRISPRoff

GFP-tagged
HEK293T

x
a
M

f
o
%

22%
off

Passage for
4 weeks and
sort GFP-off
cells

23%
off

3%
off

25%
off

CLTA

H2B

RAB11A

VIM

CLTA

CGI

0

–1

–2

3
2
1
0

H

0

–0.5

–1.0
4
3
2
1
0

protein expression

RAB11A

CGI

VIM

CGI

I

0

–1

–2

4
3
2
1
0

e
c
n
a
d
n
u
b
a
A
N
R
g
s

l

a
n
g
s

i

–2000

–1000

0

1000

2000

–2000

–1000

0

1000

2000

–2000

–1000

0

1000

2000

Position relative to TSS (bp)

Position relative to TSS (bp)

Position relative to TSS (bp)

Figure S6. Design and validation of tiling sgRNA screens show ﬂexible targeting genomic window of CRISPRoff activity, related to Figure 6
(A) The genes chosen for the sgRNA tiling screens are highlighted on a volcano plot depicting gene phenotype scores from previous genome-wide CRISPRi
screens in K562 cells (Horlbeck et al., 2016a). The colors represent genes with one (orange), multiple (purple), or no annotated CGI (green).
(B) An aggregate plot comparing the normalized phenotype score for each sgRNA for genes with multiple CGIs. The green line represents screen data from
CRISPRoff transfection into HEK293T cells, orange from CRISPRoff mutant into HEK293T, and purple from K562 CRISPRi.
(C) Representative sgRNA activity score proﬁle for TBCD from the three screens. The green bar depicts the annotated CGIs obtained from UCSC Genome
Browser.

(legend continued on next page)

Resource

ll

(D, E) Plots overlaying the sgRNA phenotype scores and MNase signals for GFER and IMMT.
(F) An experimental workﬂow of tiling sgRNA screens to determine optimal sgRNAs for four endogenously GFP-tagged genes: CLTA, H2B, RAB11A, and VIM.
The indicated population in the histograms represent the population of cells that have maintained gene silencing 4 weeks after CRISPRoff transfection.
(G, H, I) Overlay plots of sgRNA activity and MNase signal for CLTA, RAB11A, and VIM from the sgRNA tiling screen.

ll

A

C

sg-B

site 1

580 bp

1.4 kb

H2B CpG island

TSS

sg-A

site 2

site 3

B

100

80

60

40

20

f
f
o
B
2
H
h
t
i

w
s

l
l

e
c
%

0

0

sgRNA-A
sgRNA-B
NT sgRNA

5

10

15
Days post CRISPRoff delivery

20

25

Resource

30

CRISPRoff

5 kb

D

CRISPR D3A mutant

1 kb

5 kb

1 kb

5
y
a
d

0
3

y
a
d

sgRNA-A

sgRNA-B

[0-15]

[0-15]

NT

[0-15]

sgRNA-A

[0-15]

sgRNA-B

[0-15]

NT

[0-15]

[0-15]

[0-15]

[0-15]

[0-15]

[0-15]

[0-15]

HIST2H2BE

HIST2H2AC, HIST2H2AB

BOLA1

HIST2H2BE

HIST2H2AC, HIST2H2AB

BOLA1

sgRNA-B

sgRNA-A

sgRNA-B

sgRNA-A

Genes

CpG island

Parental
unmethylated
CpG region

E

site 1, day 5

F

site 3, day 5

l

n
o
i
t
a
y
h
t
e
m
G
p
C
%

100

75

50

25

0

l

n
o
i
t
a
y
h
t
e
m
G
p
C
%

100

75

50

25

0

G

1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16
CpG site

site 1, day 30

1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16
CpG site

100

l

n
o
i
t
a
y
h
t
e
m
G
p
C
%

75

50

25

0

1

2

3

4

5

7

6
CpG site

sgRNA-A

sgRNA-B

NT sgRNA

8

9 10

H

l

n
o
i
t
a
y
h
t
e
m
G
p
C
%

100

75

50

25

0

site 3, day 30

I

site 2, day 30

100

l

n
o
i
t
a
y
h
t
e
m
G
p
C
%

75

50

25

0

1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34
CpG site

1

2

3

4

7

5

6
CpG site

8

9 10

Figure S7. Conﬁnement of H3K9me3 and CpG methylation despite distal sites of epigenetic establishment, related to Figure 6
(A) A schematic of the H2B promoter with two sgRNA sites annotated: sg-A at the TSS and sg-B located (cid:1)2 kb upstream of the TSS. The CpG island spans 1.4 kb.
Sites 1, 2, and 3 represent regions probed for CpG methylation by bisulﬁte PCR as described in (E)–(I).
(B) A time course of H2B silencing after transfection of CRISPRoff with sg-A or sg-B.
(C) A comparison of H3K9me3 proﬁles at the H2B (HIST2H2BE, colored red) promoter at day 5 (green tracks) and day 30 (purple tracks) post-transfection of
CRISPRoff with sg-A, sg-B, or non-targeting (NT) sgRNA. The sgRNA binding sites are labeled, along with CpG island annotations (green), and the basal un-
methylated CpG region of the H2B promoter prior to transfection obtained from WGBS of WT untransfected cells in Figure 2.
(D) A comparison of H3K9me3 proﬁles at the H2B promoter, as described in C, except in experiments using CRISPRoff with a D3A methyltransferase mutation.
(E, F) Quantiﬁcation of CpG methylation at site 1 and site 3 of the H2B promoter (labeled in S7A) in cells transfected with CRISPRoff and either sg-A (blue), sg-B
(orange), or non-targeting (gray) sgRNA. The cells were harvested for bisulﬁte PCR at day 5 post transfection.
(G, H, I) Quantiﬁcation of CpG methylation at sites 1, 2, and 3 of the H2B promoter, obtained at 30 days post transfection.

