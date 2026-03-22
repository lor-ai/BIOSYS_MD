## **Friedberg Bufotenine Production System - Step-by-Step Protocol**

### **Phase 1: Gene Assembly and Strain Construction**

**Required Genes (from Friedberg thesis):**

1. **aromatic L-amino acid decarboxylase (AADC)** - converts tryptophan → tryptamine
2. **N-methyltransferase (NMT)** - converts tryptamine → DMT
3. **CYP2D6** - converts DMT → bufotenine
4. **cytochrome P450 reductase (CPR)** - provides electrons for CYP2D6

**Day 1-3: DNA Acquisition**

* Order codon-optimized genes from Twist Bioscience
* Request in pET28a+ backbone with His-tags
* Include strong promoters (T7) and ribosome binding sites
* Alternative: PCR amplify from existing sources

**Day 4-5: Competent Cell Preparation**

E. coli BL21(DE3) Competent Cell Protocol:

1. Grow overnight culture in LB broth

2. Dilute 1:100 in fresh LB, grow to OD600 = 0.5

3. Chill on ice 30 minutes

4. Pellet cells, resuspend in ice-cold 0.1M CaCl2

5. Incubate on ice 30 minutes

6. Aliquot and store at -80°C

**Day 6: Transformation**

Heat Shock Transformation:

1. Thaw competent cells on ice

2. Add 100ng plasmid DNA, mix gently

3. Incubate on ice 30 minutes

4. Heat shock 42°C for 90 seconds

5. Return to ice 5 minutes

6. Add 1mL LB, recover 37°C 1 hour

7. Plate on LB + kanamycin, incubate overnight

### **Phase 2: Strain Validation and Optimization**

**Day 7-8: Colony Screening**

* Pick 6-12 colonies per construct
* Confirm by colony PCR using gene-specific primers
* Sequence verify at least 2 colonies per gene

**Day 9-10: Expression Testing**

Small Scale Expression Test:

1. Grow overnight cultures (5mL LB + kan)

2. Dilute 1:100 in fresh media

3. Grow to OD600 = 0.6 at 37°C

4. Induce with 1mM IPTG

5. Sample at 0, 2, 4, 8 hours post-induction

6. Analyze by SDS-PAGE to confirm protein expression

**Day 11-12: Optimize Expression Conditions**

* Test temperature: 16°C, 25°C, 37°C
* Test IPTG concentration: 0.1mM, 0.5mM, 1mM
* Test induction timing and duration

### **Phase 3: Pathway Assembly and Testing**

**Day 13-14: Multi-Gene System Assembly** Option A: Co-transformation of separate plasmids Option B: Gibson assembly into single vector

Gibson Assembly Protocol (if building single construct):

1. Design overlapping primers (15-25bp overlaps)

2. PCR amplify each gene with overlaps

3. Mix equimolar amounts with Gibson Master Mix

4. Incubate 50°C for 1 hour

5. Transform and select

**Day 15-16: Pathway Validation**

Bufotenine Production Test:

1. Grow overnight culture of complete system

2. Dilute to OD600 = 0.1 in production medium:

- M9 minimal medium + 2% glucose

- Supplement with amino acids

3. Grow to OD600 = 0.6

4. Induce with IPTG

5. Add substrate: 1mM tryptophan

6. Incubate 16-24 hours at 25°C with shaking

### **Phase 4: Product Analysis and Optimization**

**Day 17-18: Product Extraction**

Extraction Protocol:

1. Centrifuge cultures, collect supernatant and pellet

2. Resuspend pellet in PBS + 0.1% Triton X-100

3. Sonicate or freeze-thaw to lyse cells

4. Extract with ethyl acetate (3x equal volumes)

5. Combine organic phases, dry over Na2SO4

6. Concentrate under nitrogen or rotovap

7. Redissolve in methanol for analysis

**Day 19-20: Analytical Confirmation**

LC-MS Analysis Protocol:

1. Prepare standards: tryptophan, tryptamine, DMT, bufotenine

2. Run samples on C18 column

3. Mobile phase: water/acetonitrile + 0.1% formic acid

4. Monitor by UV (280nm) and MS (positive mode)

5. Confirm bufotenine: m/z 205.1 [M+H]+

6. Quantify against authentic standards

### **Critical Success Factors**

**Media Optimization:**

* Use minimal medium to force metabolic channeling
* Supplement with cofactors: SAM precursors, NADPH regeneration
* Monitor pH (bufotenine is alkaline)

**Cofactor Management:**

* Add betaine for SAM regeneration
* Include glucose-6-phosphate dehydrogenase for NADPH
* Consider cofactor recycling systems

**Expression Balancing:**

* CYP2D6 + CPR should be 1:1 ratio
* AADC is typically the bottleneck - increase expression
* NMT needs adequate SAM supply

### **Troubleshooting Guide**

**No Product Formation:**

* Check protein expression by Western blot
* Verify cofactor availability
* Test individual pathway steps

**Low Yields:**

* Optimize enzyme ratios
* Improve cofactor recycling
* Consider fed-batch cultivation

**Side Products:**

* May see tryptamine or DMT accumulation
* Indicates pathway bottlenecks at later steps
* Adjust enzyme expression levels

### **Expected Timeline and Yields**

**Timeline:** 3 weeks from DNA to confirmed bufotenine production **Expected Yield:** 50-100 mg/L bufotenine (based on Friedberg data) **Scale-up:** 1L cultures should yield 50-100mg pure product

### **Extension to 5-AcO-DMT**

**Additional Component Needed:**

* O-acetyltransferase enzyme for bufotenine → 5-AcO-DMT conversion
* Can be added as 5th gene in the system
* Post-fermentation chemical acetylation also possible

This represents a proven, replicable system that multiple groups have successfully implemented. The key is careful attention to enzyme expression balancing and cofactor management.