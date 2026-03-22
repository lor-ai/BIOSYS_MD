 Research Proposal: Functional
 Validation of the Putative Ketamine
 Biosynthetic Gene Cluster (BGC) from
 Pochonia chlamydosporia

 Abstract

 Following the analytical identification of ketamine as a natural product of  Pochonia
 chlamydosporia  1  , this proposal outlines a systematic  approach to establish genetic causality.
 We describe the reconstruction of the putative 32kb biosynthetic gene cluster found on Scaffold
 14 in the heterologous host  Saccharomyces cerevisiae  .  This protocol provides detailed
 instructions for DNA synthesis, multi-gene assembly, bioreaction parameters—specifically the
 requirement for halogen supplementation—and analytical verification using LC-MS/MS.

 Phase 1: Genetic Design and DNA Synthesis

 Objective:  To adapt the fungal genomic sequence for  optimal protein production in a yeast host.

 Step 1: In-Silico Codon Optimization and Intron Removal

 ●

 ●

 Technical Explanation:  Fungal genes in  P. chlamydosporia  contain introns (non-coding
 regions) and utilize codon biases that are often incompatible with yeast translation
 machinery.  1  The five target genes (  PCH_10405, PCH_PKS7,  PCH_AAT1, PCH_CYP102,
 and PCH_NMT1  ) must be redesigned to match the tRNA  pool of  S. cerevisiae  while
 removing all native introns.  1
 Layman Explanation:  We are taking the fungal "instruction  manual," which is written in a
 complex regional dialect with many filler pages, and rewriting it into clear, standard English
 that the yeast can read and follow without getting confused.

 Step 2: Custom DNA Synthesis

 ●
 ●

 ●

 Vendor:  Twist Bioscience  or  GenScript  .
 Specifications:  Sequence-verified clonal DNA fragments.  Each gene should be flanked by
 specific BsaI or BsmBI restriction sites to facilitate Phase 2 assembly.
 Estimated Cost:  Approximately $0.09 per base pair  (bp). For the ~32kb cluster, the total
 synthesis cost is roughly  $2,880.00  .

 Phase 2: Vector Construction and Yeast
 Transformation

 Objective:  To package the synthetic genes into a single  expression system and insert them into
 the yeast.

 Step 3: Multi-Gene Operon Assembly (The "Nitrogen Weld")

 ●

 Technical Explanation:  Utilize  Golden Gate Assembly  (utilizing the BsaI-HFv2 enzyme)
 to link the five genes into a single high-copy pRS426-based yeast expression vector. Each

 gene is placed under its own strong constitutive promoter, such as

 or

 , and a corresponding terminator (e.g.,

 ) to ensure  synchronized

 ●

 ●

 expression without the need for chemical inducers.
 Layman Explanation:  We are using a molecular version  of LEGO bricks to snap the five
 rewritten gene sets together into one master manual. This manual is then tucked into a
 circular piece of DNA (a vector) that acts as the delivery vehicle.
 Vendor/Price:  New England Biolabs (NEB)  NEBridge Golden  Gate Assembly Kit
 (BsaI-HFv2):  $438.00  .

 Step 4: Yeast Transformation

 ●

 ●

 ●

 Technical Explanation:  The assembled vector is inserted  into a uracil-auxotrophic yeast
 strain, specifically  CEN.PK113-5D  , using the Lithium  Acetate/PEG method. This strain is
 preferred for its stability and high performance in small-to-medium-scale bioreactors.
 Layman Explanation:  We use a brief chemical and heat  "shock" to open the yeast cells,
 allowing our master manual to enter. We use a special strain that "starves" unless it keeps
 this manual, ensuring the new genes aren't discarded as the yeast grows.
 Vendor/Price:  Zymo Research  Frozen-EZ Yeast Transformation  II Kit:  $125.00  .

 Phase 3: Bioreaction and Metabolic Induction

 Objective:  To provide the optimal environment for  the enzymes to construct the ketamine
 molecule.

 Step 5: Fed-Batch Cultivation and Aeration

 ●

 Technical Explanation:  Inoculate transformants into  Synthetic Defined (SD)  medium
 lacking uracil (SD-Ura) with 2% glucose as the sole carbon source. Maintain a constant
 temperature of 30 °C. High-flux aeration (shaking at  250 RPM  ) is critical to satisfy the high
 oxygen demand of the  PCH_CYP102  Cytochrome P450 enzyme  responsible for the
 oxidative cyclization step.  1

 ●

 Layman Explanation:  We grow the modified yeast in a warm, nutrient-rich liquid. We
 shake it vigorously because one of the key steps in making ketamine requires a lot of
 oxygen—essentially letting the yeast "breathe" while it works.

 Step 6: Critical Halogen Supplementation

 ●

 ●

 ●

 Technical Explanation:  Supplement the medium with  25 mM NaCl  .  1  The  PCH_10405
 Flavin-dependent Halogenase requires a surplus of chloride ions to perform the
 regioselective ortho-chlorination of the aryl ring.  1  Without this, the pathway will yield
 Deschloroketamine (DCK), which lacks the characteristic chlorine isotope pattern of natural
 ketamine.  1
 Layman Explanation:  If we don't add salt to the broth,  the "chlorine installer" enzyme runs
 out of parts. It would end up making an unfinished, less effective version of the molecule
 instead of real ketamine.
 Vendor/Price:  Sigma-Aldrich  (Analytical Grade NaCl):  Approximately  $60.00  per 500g.

 Phase 4: Verification and Quality Control

 Objective:  To confirm the presence of ketamine and  its specific chemical signature.

 Step 7: Metabolite Extraction

 ●

 ●

 ●

 Technical Explanation:  Following 72 hours of incubation,  the yeast supernatant is
 collected. A liquid-liquid extraction is performed using  HPLC-grade Ethyl Acetate  at a 1:1
 ratio. The organic layer is recovered and evaporated to dryness under reduced pressure to
 concentrate the metabolites.
 Layman Explanation:  We use a chemical "magnet" (ethyl  acetate) to pull the ketamine out
 of the liquid broth. We then dry it down into a concentrated powder for testing.
 Vendor/Price:  Fisher Scientific  Ethyl Acetate (HPLC  Grade, 1L):  $162.79  .

 Step 8: Analytical Validation (LC-MS/MS)

 ●

 Technical Explanation:  Analyze the extract via Liquid  Chromatography-Tandem Mass

 Spectrometry (LC-MS/MS). The target signal is a peak with a mass-to-charge ratio (

 )

 of  238.17 Da

 , paired with a secondary isotopic peak  at  240.10 Da

 .  1  Further confirmation requires MS/MS fragmentation  to identify the

 125 fragment  , which represents the chlorobenzene  moiety unique to the

 diagnostic
 arylcyclohexylamine chassis.  1
 Layman Explanation:  We weigh the molecules in our  sample using a high-precision scale.
 If we find a molecule that weighs exactly 238.17 and breaks apart into a specific

 ●

 "fingerprint" fragment weighing 125, we have officially confirmed that the yeast produced
 real ketamine.
 Vendor/Price:  Cerilliant (Sigma)  Ketamine HCl Certified  Standard (1 mg/mL):  $29.60  .
 Commercial LC-MS/MS analysis fees: Approximately  $250.00  per sample.

 ●

 Summary of Estimated Costs

 Category

 Item

 Vendor

 Estimated Price (USD)

 DNA Synthesis

 32kb Synthetic BGC

 Twist Bioscience

 $2,880.00

 Cloning

 Golden Gate Kit
 (BsaI)

 NEB

 $438.00

 Transformation

 Frozen-EZ Yeast Kit

 Zymo Research

 $125.00

 Medium

 SD-Ura, NaCl, EtOAc

 Sigma / Fisher

 $350.00

 Validation

 Ketamine Standard +
 Fees

 Cerilliant / Core Lab

 $280.00

 Total

 Works cited

 $4,073.00

 1.   Ketamine_can_be_produced_by_Pochonia_chlamydospori.pdf

