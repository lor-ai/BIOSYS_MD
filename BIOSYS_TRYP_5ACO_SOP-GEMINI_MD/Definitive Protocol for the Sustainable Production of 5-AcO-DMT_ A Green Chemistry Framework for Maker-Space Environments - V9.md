# **Protocol for the Sustainable Production of 5-AcO-DMT: Green Chemistry for Maker-Space Environments**

This Standard Operating Procedure (SOP) details the isolation of bufotenine (![][image1]) from *Anadenanthera* botanical sources and its subsequent covalent modification into 5-acetoxy-N,N-dimethyltryptamine (![][image2]). The framework utilizes a "Golden Path" of physical separation gaps, acoustic streaming, and selective adsorption to achieve research-grade purity using consumer-grade materials.1

## **1\. Fundamental Principles & Scientific Rationale**

### **1.1 The Log-P Separation Gap**

Purification relies on the partition coefficient (![][image3]) differential between the target tryptamine and the contaminant Gramine. Gramine is significantly more non-polar ("greasy"), providing the mechanism for trapping it on hydrophobic surfaces while polar bufotenine salts remain in the aqueous phase .

| Molecule | Molecular Formula | pKa​ | Log−P | Toxicity (LD50​ Rat) |
| :---- | :---- | :---- | :---- | :---- |
| Bufotenine (![][image1]) | ![][image4] | 9.67 | 1.69 | \~200 mg/kg |
| Gramine | ![][image5] | 8.85 | 1.95 | \~100 mg/kg 4 |

### **1.2 Thermal Ceiling and N-Oxide Prevention**

Bufotenine is susceptible to ![][image6]\-oxidation, forming inactive ![][image6]\-oxides in the presence of reactive oxygen species (ROS) or excessive thermal energy . This SOP enforces strict temperature ceilings to prevent "thermal lysis":

* **Extraction Ceiling**: ![][image7] (The sweet spot for tryptophan backbone solubility).1  
* **Finishing Ceiling**: ![][image8] (The limit for preventing oxidative browning during de-watering).1

### **1.3 Acoustic Physics: Damping & Streaming**

In the absence of a programmable pulse duty cycle on standard hardware, energy control is achieved through **Acoustic Attenuation**. Flexible silicone bags absorb 20-30% of ultrasonic power, suppressing violent "transient" cavitation (which creates oxidizing ![][image9] radicals) and promoting **Acoustic Streaming** . This produces a "microflow" scrubbing effect that releases alkaloids without the oxidative stress of high-power bubble collapse .

## ---

**2\. Overall Process Flow**

Code snippet

graph TD  
    A \--\>|Phase 1: Cold-Wash| B  
    B \--\>|Phase 2: Salt-Bath Indirect UAE| C  
    C \--\>|Phase 3: Magic Sand Pull| D  
    D \--\>|Phase 4: Resin Column| E  
    E \--\>|Phase 5: Photo or Sonic Weld| F  
    F \--\>|Phase 6: Finishing| G

## ---

**3\. Bill of Materials (BOM)**

### **3.1 Major Equipment**

* **Ultrasonic Cleaner**: Vevor 40kHz Stainless Steel unit (or equivalent) .  
* **Vacuum Filtration**: Hand-pump or electric vacuum pump \+ Buchner funnel / manifold .  
* **UV Light Source**: 10W 365nm UV LED (Required for Phase 5, Option A) .  
* **Magnetic Stirrer**: High-speed stirrer with PTFE-coated bars.2

### **3.2 Specific Reagents ("The Hacks")**

* **Interfacial Media**: DIY Magic Sand (Silica sand \+ Scotchgard spray) .  
* **Color Strip Resin**: Jorewood Aquarium Filter Resin (or Seachem Purigen) .  
* **Metal Strip Resin**: Seachem CupriSorb (Selective transition metal chelator) .  
* **Photo Catalyst**: Anatase ![][image10] powder (![][image11] preferred) .  
* **Sonic Catalyst**: Vanadyl Sulfate (![][image12]) (available as a high-purity dietary supplement) .  
* **Acetyl Donor**: Reagent-grade Ethyl Acetate (Photo) or Isopropenyl Acetate (Sonic) .

### **3.3 Consumables**

* **Extraction Bags**: 5-10 micron Nylon mesh filter bags (to retain seed fines) .  
* **Reaction Containers**: Heavy-duty silicone bags (to damp ultrasonic energy) .  
* **Absolute Filter**: 1.0µm Hydrophilic PTFE Membrane Discs (47mm) .  
* **Buffers**: Distilled water, Baking Soda (![][image13]), Table Salt (![][image14]).

## ---

**4\. Phase-by-Phase Standard Operating Procedure**

### **Phase 1: Lipid & Surface Cleaning (The Cold-Wash)**

**Goal**: Remove surface oils and waxy cuticles that would otherwise "poison" the catalysts.1

1. **Milling**: Coarsely grind seeds to coffee-ground consistency. **Note**: Over-milling to a fine flour will instantly blind the filters in later stages.1  
2. **Loading**: Place the grounds in a **5–10 micron Nylon Bag**. Nylon is mechanically strong and stable at ![][image7] .  
3. **Soaking**: Submerge in distilled water chilled to **exactly ![][image15]**.  
4. **Agitation**: Stir manually for 10 minutes.  
5. **Separation**: Discard the cloudy wash water (lipid-rich). Retain the cleaned seed mass in the bag.1

### **Phase 2: Salt-Bath Indirect Extraction (The "Baggie" Thumper)**

**Goal**: Anaerobic mass transfer via acoustic streaming.

1. **Bath Prep**: Fill the Vevor unit with a saturated saltwater solution (![][image14]). Salt increases density, improving acoustic impedance matching and energy transfer efficiency .  
2. **Thermal Setup**: Heat the bath to **exactly ![][image7]**.  
3. **Displacement Vacuum**: Place the filter bag into a heavy silicone bag. Fill with distilled water (pH 8.0–8.2 via baking soda). Submerge the open bag into the saltwater bath; the external pressure will displace air. Seal tightly when air-free .  
4. **Sonication**: Run continuously for 20 minutes. The silicone bag acts as an acoustic low-pass filter, preventing oxidative hot spots .

### **Phase 3: Interfacial Vacuum Polishing (Magic Sand)**

**Goal**: Trap Gramine and grease using hydrophobic interaction.1

1. **Setup**: Pack a 2-inch layer of DIY Magic Sand into a vacuum manifold. Ensure the sand is bone-dry before use to maintain the ![][image16] coating integrity .  
2. **The Pull**: Apply vacuum and pass the ![][image7] serum through the sand bed.  
3. **Verification**: The serum should transition from cloudy to a translucent, "tea-like" amber liquid.1

### **Phase 4: Selective Polishing (The Amazon Hack)**

**Goal**: Strip tannins and transition metals (![][image17]) that act as catalysts for ![][image6]\-oxidation .

1. **Column Setup**: Pack a small gravity column with **Jorewood Resin** on top and **Seachem CupriSorb** on the bottom.  
2. **The Drip**: Pass the serum through at a slow rate (1-2 drips per second).  
3. **Result**: Jorewood adsorbs organic pigments (Color Strip); CupriSorb chelates transition metals .  
4. **Visual Check**: If CupriSorb beads turn **blue-black**, they are successfully removing the oxidative "poisons" .

### **Phase 5: The Weld (Acetylation Pathways)**

**Goal**: Covalent modification of the 5-OH site into the 5-AcO group.1

#### **Option A: The Photochemical Weld (UV Pathway)**

1. **Mix**: Polished serum \+ Anatase ![][image10] (![][image18]) \+ 10% v/v high-purity Ethyl Acetate.  
2. **Cooling**: Place the beaker in an ice bath (![][image19]) to suppress ROS-driven ![][image6]\-oxidation .  
3. **Activation**: Shine a 10W 365nm UV LED directly above while stirring at high speed for 3 hours .  
4. **Monitoring**: Monitor the inherent fluorescence ("glow") shift of the indole ring under UV as it binds to the catalyst surface .

#### **Option B: The Sonochemical Weld (Ultrasonic Pathway)**

1. **Mix**: Polished serum \+ **Isopropenyl Acetate (IPA)** (10% v/v) \+ ![][image20] **Vanadyl Sulfate (![][image12])** .  
2. **Loading**: Place the mixture in a flexible silicone bag. Use the **Displacement Vacuum** (Step 2.3) to seal the bag air-free.  
3. **Sonication**: Submerge in the ![][image7] saltwater bath and sonicate for 50–60 minutes .  
4. **Rationale**: IPA ensures an irreversible reaction as its byproduct (acetone) keto-enol tautomerizes .

### **Phase 6: Absolute Filtration & Finishing**

**Goal**: Removal of sub-micron catalyst fines and low-temp de-watering.

1. **The Membrane Stack**: Set up a **1.0µm Hydrophilic PTFE Membrane Filter Disc** in a vacuum funnel. Place a coffee filter on top as a pre-filter, then add 1 inch of Magic Sand .  
2. **Recovery**: Pass the mixture through the stack. The sand traps bulk catalyst; the 1µm PTFE membrane ensures an absolute "absolute" barrier against fines.  
3. **Drying**: Pour the clear serum into a Pyrex tray. Evaporate using a fan at room temperature. **Warning**: Never exceed ![][image8].1  
4. **Harvest**: Scrape the resulting golden-amber "shatter" or crystalline crust with a razor blade. Store in an amber glass vial in the freezer.1

## ---

**5\. Troubleshooting and Safety**

* **Grey ![][image10]/Catalyst**: Evidence of lipid poisoning. Phase 3 failed to remove all oils. Re-purify through fresh Magic Sand.1  
* **Darkening Product**: Indication of ![][image6]\-oxidation. Ensure air is strictly excluded during sonication and drying temperatures stay below ![][image8].1  
* **Catalyst Breakthrough**: If the final product contains white grit, re-run through a fresh 1.0µm PTFE membrane stack.  
* **Safety Notice**: All chemical work must be performed in a well-ventilated space with appropriate gloves and eye protection. Ethyl Acetate and Isopropenyl Acetate are highly flammable .

#### **Works cited**

1. THREE STAGE AQUESOUS WASH ANANDATHERNA BUFOTENINE EXTRACTION.pdf  
2. THREE STAGE AQUESOUS WASH ANANDATHERNA BUFOTENINE EXTRACTION.pdf, [https://drive.google.com/open?id=1WscnSrSLP34mhClGus0vLL1wqCW8IaHr](https://drive.google.com/open?id=1WscnSrSLP34mhClGus0vLL1wqCW8IaHr)  
3. BIOSYS\_5-AcO-DMT, [https://drive.google.com/open?id=16YmvES1D341k1rv4DbDRwwX304zUajXp](https://drive.google.com/open?id=16YmvES1D341k1rv4DbDRwwX304zUajXp)  
4. DIY Air Force Activities: Magic Sand \- WPAFB STEM Outreach, accessed March 18, 2026, [https://wpafbstem.com/WOW/DIY/media/DIY\_MagicSand.pdf](https://wpafbstem.com/WOW/DIY/media/DIY_MagicSand.pdf)  
5. 5-ho-dmt-to-5-meo-dmt-conversion.pdf, [https://drive.google.com/open?id=1bSEs5DgEz3o0I31o-EnvkoPaenOE9zVA](https://drive.google.com/open?id=1bSEs5DgEz3o0I31o-EnvkoPaenOE9zVA)  
6. Photocatalytic kinetics of phenol and its derivatives over UV irradiated TiO2, accessed March 18, 2026, [https://www.eng.uwo.ca/people/aray/Ajay%20Publications%20PDF%20files/A17%20Dingwang%20Appl%20Cat%20B%201999.pdf](https://www.eng.uwo.ca/people/aray/Ajay%20Publications%20PDF%20files/A17%20Dingwang%20Appl%20Cat%20B%201999.pdf)  
7. Interfacial Separations by a Polydimethylsiloxane Layer. Molecular Modeling of Coated Stir Bar Extraction of Organics from Aqueous Solutions \- PMC, accessed March 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12044680/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12044680/)  
8. A rapid and efficient method for acetylation of phenols with acetic anhydride catalysed by Ti02/S04 \- SciSpace, accessed March 18, 2026, [https://scispace.com/pdf/a-rapid-and-efficient-method-for-acetylation-of-phenols-with-2o07up3qcp.pdf](https://scispace.com/pdf/a-rapid-and-efficient-method-for-acetylation-of-phenols-with-2o07up3qcp.pdf)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHoAAAAVCAYAAACJ+/prAAAC30lEQVR4Xu2YS6hNURjH//KIKETkUfcmEySKEmGEkkeKJMpEMVHKgO6diFJk4jWQkkeJgZKBSAY7JI8BA69kcJkYIcXAlcf/7zuLtdc+e7t1uvuec/b61a977v722Wfv/a31fXttIBKJRCKRpmQQnUzX0HW0s7atcnTSzXQqHUyH0zl0e+1zmYynd+kvz156DnYuh+kXL/aDPqOzkUXXspG+pufpJrqNPqH3YdddKRbRb0jf3K90lb9TyayEncfxMAAbDM9pD52SDv1lNL1MHyGbUMVu05ewwV0Z5tEX9BV9SvfTSak9yucgLNFrwwDsfDUQr9AhQUwokTdgM7kjiDmW0Z90ZxhoZ3TjToQbBxCV6Ov0PZ0WxMQW2CDYEQZgvfcorKQvD2I+Oq6Or98puz0NGM2WaJeEhI5Kh/4k8iz9ThcHMbEE1oZu0hFBzKfoN9oWJfoqvUDf0Hd0H4pvVH/iyupJWAvxnQVrMerR6tU+KuOXYLNds74IDRINlgQVS/RDOr32/zjYQ8xpOtTtVCKuP6vP6hx8b9Vi9fqzHsx66Ac6Ix3KoLKv41xEhZZaSubIYFs3rAQuDLb7qLeFMy5PDZ6+3NBG+rN7SKs3233cb+g4WnLlofsyEdlrqecE2HKu5dgLuxG7w4CHlkDhjMvzEB1jXyvE9U4tf8LB97/+7BKdoLgcu/20/laC8piL7HXkeQzZZVxToZn2GNmLdonW3zJx62eV75CxsHPNm7Eq1yrbCfITrVmqwaKn8npLt7ZFZectsonuRv46tj9pdP38APllX6yHVYQ96FsraRt0w07RBd423bA7sPKpz2WhWZggP1HuAaqonWiAaLZ2IZ1Ifd5KP9NdaNF+2igdsPfLR5B+F1zW60FVEv1+LyyRUu+zz9Bh9AD96MWkKtBMfTlACV1NP9Fr+Pd+W6uKe6j/nUqh3rWUboD1ulYf8bqe+bDrWQF7FolEIpFIpFX4DddnqR+w/4jrAAAAAElFTkSuQmCC>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJEAAAAYCAYAAAD6Zx8zAAAFZ0lEQVR4Xu2ZachtUxjH/zJkDJFZ3nRTRMiU8RMiQ6Zc3MsHMnwQReHe4h5JKSnTB1PuReIDSTJ0SceQayhTpgyFbilCCuXK8Pw8e7XXXmevfff79p5zXrX+9e+cvfa01vP8n2c9a22poKCgoKCgYILYyHiF8YD0xByxgXEX4ynG04wzVVvBHDFjPM+4m3FD46bG/Y2XVP8XAo42/mE8Iz0xSzC+s42fGx8ynmO8yPie8Q25LaaB7Y2vGP8y/lNxnXFt1PaR8Uy1i30T44Nq3n9p44omNjM+o/ran4z3G7/tyQ+N+ynCEXIHhQfC34wnxRdNEVsah/J+Xds8NStsbXzc+LZGxcK5l4yfyoNpWjhRPs6bk3acfp3xT+M1ahcS2FsuNvy5PDkXY7HxA/nzjpI//znjrcYdq2u2kNvkZ+O+VdvG8oTzhRI7HWT8xPiZ8X3jjcad4wumjMvkmaLNuH2BSJ6XZ6A9knMBxxr/Nl6enpggcDx9oC8pEM7dajo1xanya76SZ9o2zBhXGFfLr0M0PG+lXEwBexq/kwcwgRyANh41bhW1/Seiu+KGBYTdjU/KI5TsmDNMFzD+7fJUf1xyLkYw2rOazjTOO3k3faAvbaCG65qqBsbT5Y6HsfMBtSXZ/Ejj18YnqraL5QKMkcuK9O02JdlwoYqITpJeqYPoIyIKg24DqfZgeaGM+AJCPfWCmpGWIhd5k8Kucsd2iTiIqG2qos+PyMdOpghZJgYZjqksZN2rVItou+g6gHh4VyquveS1WQM46Cnjw8Yv5YUT6a7L4JMA/aLYQxyk0G/U7mDEhmHoO0bh/xp5AY2BHpMbY0m4IQNqA2qEoUbfMQkEx6aRH4Px5WpDggB7IcA7NZrREMlA7lfuD/VQG0I9lD4jC5z1lnFRdczLKD7vkztwGmCgq4wHVsdBRO8Yt63aAAK62viD8dCqjRUXhsaQIbp/lBedXWCK4D6iOFe4jhM4NlcPAfpE3ZILCDLGsuo/YvvdeEh1zL3UltgzTJttmSpg1lkZoaC8GKRLpoDDk/YYdAbn9iHCnI1jyCY3qL4H4SAghMTzAsI0N4jaMMD1xp2i8x/Ll9E5BMPiIESYA7bC8On42riDfEuhD/rUQ/SfceQCYqBagGHa4xcgHkSEPUNgdZUGCLKtHpoViAoegqJzoPAiW/XhLcZt/Lb1AuOzTOX9KVMDkm260nIQ0VDdERWu4728Pwc2O9Ox5XiHRrcScuhTD50gz1QPaNT5oR4Ky24yEJkI/5HVB6prnrgeyiFXD7WCBxPhqfGCiNrm3nGCSGE/ZGl6Qr4yw9E4HGC4obrTMoJDeEPlRUR2YZpg9dbLaGPA+uoh+r5a+S2KuB4Kx2Q1guxCNafI5eoOvGDXrqzYAGmXKSIVES/qrcR5BGl3ldqLekREn8iAIBR/Q40KhGlkc/n+0JvqNggrDYzatYk3bmDvXD2EyAfyXeVQ96XATzdFxwQVwfWufGoPmWss9RAPv8d4WNSG4V+VO4j/kwIiflm+qmrDCjXneUCmxFAhVQPEda/x/OoYA5NllqkpEv5fYPzFeKX61y/zDQKG7YdU6PRvH7nTWXnmvhuGRUj8SSjO0jNRexDIvNdDpMfX5Hsy8Xekxrb2GIEAEG1c+7BSCiA6icL4PDvri1R/ymALnzqE5fyLxmNUC4bfk+U7vU+r/l7GivR1uaOmAcZNX9epHtf38i2WtVU7MwRCb8vMZBXqoNgua1QvIFaqLgv4zsVXifha3nVudZ69NAT3a3INdieT99ICKRPDnyWvI6YVlXMFRTtTc1f6ZYxsRjLG4zW6uVZQUFBQUFBQUFBQUFBQ8D/Fv4i7VM8u8d3eAAAAAElFTkSuQmCC>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAD4AAAAVCAYAAAAeql2xAAACJ0lEQVR4Xu2WPUjcQRDFR/xAkWDE+EUQY1BEFAyolTYGE7SwSaNgYxUtxEJRWxHEWrEKiliIQgJWghALQZBACi2SRgmJwSRISKGghaLJe84ut67enaB45z/34Ae3M3N3u7MzuyuSUEIJ/U9qBL/BX4dj8B7kOHGB1RQ4A82+I8jKBh/BN/D4oivYqgB/wDuQ4vkCrQ7R3h7yHRGUD1rBS5Dp+axop78GJHu+uNAEOAENvuMKFYhWxiJoBwPgK6h1YrjIXrAJXoNRsGHiypy4mMr29xfRXYykYvAJvAGpxpYE5sAyyDDjQbALSk0M7fR/Bo+MLeaK1t9pooukjyf/TwktyGoW7IBCUCl6PU6KJoGyyWWCrM0X/4OJ529EI09uoXVsf/f5DtFJjoAqCZ+gdLAkoYUPi16LTU5MNTgAXY7N1zPRSroO4+DJ+bduIO5iuP7mzk6LlioPMibIn/xT8AvMi+4ad5Vj2q2Y3CNQ59hiqkj3NxfB7HLSVIvowpkAV92iiXthxiz7NfDAjFk1MxJn/c1r5lAuly9Llov+DkqMrQhsgx4bJNrPPBT7JdS7TARtTCRtbeBUIvf3nYn9x0PKvs05MZ7ChJ+tneXrJoS7zpi3BlbLc7m4IFbKGPgBtsCCaEX4LXLvZE/fh74jjNgqrCpWV2BVL3qq55oxq4VV8wFkGVvgxOfpCtgD5aLl3wn2watQWDDFd/k6WBV9rvI0ZxLiQv8A5D9xbG7wDU4AAAAASUVORK5CYII=>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFUAAAAVCAYAAAA3raI2AAAEfUlEQVR4Xu2YachtUxjH/0KZwjXfTNeUeShTxhCikAxlCB8RXygu0nW+yFDKFGWmcMm9EjJ+eA1R7jcRkVwSIUQos//vPGe979rrrH28ztnXF+dfv9591trvXns961nP86wtTTXVVFNVtZ45wpxmdjWrD9rXNVsNrqeap3Yzb5ofzWPmUvOQedHsbp4zR8/ePb6ONF+bvzK+NeeYTcwr5o+sj/dZqljUScSzX9Pcc78zezTukC4f9CU+M3s27pin1jRXm1/NFWbtZrcOMz8oBujSU+8xf6q+ULTRd79ZreibVCeZ7xVG6zW7+mKOb5hdyo75CoPeaX4zpxZ9SWuZZwdw3YUWmBVmpdmy2dXXYsWkzy47OlDPnK9wkvfM5o1eaW9zt1mjaB+lU/IfFyhe/kqN9ogHzVVl4wQiVn9jntDwy/Obdvq5r0sRQtgheOPtirmf0bgjFpLQN18RGglnfe1oPjcfmq1TY4t4kdo2HVe8OBPCI0vhuSsVnoxHd6ntFV7IjjvI/GKeVzPk3WAOzX6PEjv9cUWo6qunmNi1qWGENlA8oCvdan43J5uFBacrXpJ7utbx5rLBNYbEoBgWAyMWkSRdhoQ2pYXBAfpl04zaE8WqVIqnPymqi7sKPtaqjaf5fNn6jEUoIPwRbsgxZUhqU4r9fQfAIz4xXyi2xL8Rg+9vji3aiVN4/R3mcLXH6Eni6WbmXA0nzPUVE2T8Q4q+pBRP88SIR5KsSFrbaTieUqOTwFlscgrj5CLXYFQS36xRgetRIpkdPLg+yzxj3lUzHmLQaxRbaifzgeLemlI8rSWDtni6s3laMfaMYqclbWueUuSIY8zrqsfiPJ7m6ine52INx1OMxW+MS9nJszfO+pNRT+RH2oL/ZFQecJ/CQ3LxsNyoPJRalnIE4TEvq16w4y2UcLVkQBt9bfGUcWY0Z1R2A1sXgyAMx2KWOwBRn1LllEoJ+0vzguKQgFKI5H0Rz+Y+4nIS7zlrVHSTIqYelxoK8cJ4U61+LY2K8dh2KZkxWK2unbQ+LY3K9qV6uVBxGrpI9YVEPdXzR1oYxi1DEqcpdgIiHGHUWkyeTfbczDZ91WyRGgdiGy8xl6geG0uj5qI8e0fhGaX2VSSo8uVROmTkHl+qNCr3cdzEm1jQE8wyDZ8KN1V44V5Fe1LK4v3Y2CLmy5E9Dz1c0/ZR1qZFiiPZz+YBc565RXFGPkp1g6I2ozKxmxVlUf6/rC6rzKomvjJnKkLMS4pjcurj+mGzDv+cqWZUFiFtPxbt08FfRNh6S81xb9PcR6IkFmG56iEJHWAeMRuVHYo2atWGmPwiRc0IO2h40FI1o2JQMiSLgUhYpTdOqtKobH+8JDcqH2dq23xc7WOuU4QVDFjml85UGpWFIZ4xORIf2Zqk0Obp46o0Kov2qObO3hj1bUV51IUIkTeabRTz4ksa5WSnYtXuVdS375vrzYaK76/55zrAa7sSYzAWnybToYF3QfuZJ82BikqllljHETGe5+Zzop6lfPxfCAPgSXkS+U/1N1/l/s9D2GxCAAAAAElFTkSuQmCC>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEgAAAAVCAYAAADl/ahuAAADdElEQVR4Xu2YW4hNURjH/0K5FXIPGZeSSyghoowkHkihXEK88OAB5Zp0SooHDy6l3Cmh5AWNy8ugyOXBi0s8GCVCiFDu/v/97XVm7zXrHM2cPUY5//p19lnfnrXX/tb6LmeAssoqqwnVjkwks8kg0jweb0t6xdf/pQaTG+QjOUVWk2PkEhlCqsjk/N0NVyV5TX4leEsWks7kCvmRsGk9J2EbVIo09zXUzvuODE3dAayNbSm1JJvIV7KetE6bMYF8IM+Q7Qk6QH4i7HSNyXaYNPNspWoGeQ9zRC5tipR6RzlnL/lGZiUNCbUi52N0nYU6ktukhvRMmyKtg73AAt+QgXJkGWzDH5BuKSswPPllOWwhG1B8p46Sjf5gCVJue0NOkxaeTd81Lrvuy1IKU51cnZI9sHefm7ojsSkDyHPymPTOm8PSpKFQaKi0CC1OJ8WXTlQN7ITppGWpfmQ/LBLGki/kAtJpZbu7yMEWuTVvKqz2sHDMSrvIdzKT9PCYA8s/uidrTSNr4ms5Rc6Rk+QsSRuiAhWV8moUTpKNKZd/PsGq5D6PJ2jc/JN8X4WXnqVwU4pRSCsnRzv1lLyAHbv6SBONIlN8AyzGl5IOviGhUvJPV7II4WKhda1E4Q13+SdZFJSglaiVsPvCNkXtTd5BQtfFpEQ+Lr6eT86Re0jnj07kBDlL7qP4nC7/RAvxVCj/DITNrWdXwyLA1xjYqZzuG2Il809SOdh6VsDyz3gNumP+JwfpxQ/Bdi4pVbVQgh1J7qL4nNpFtRXRQjxpTLZC+UcvX426DlKO3ELuoLCD1P+oWvtyxeoluQhrKCPtgOWgqW7Ak46sdjnUHzXUQaX2PyEHaZ1LyOjYVshBOYTDT3/vSn4q7PuQR+Qq6e4GYynDbyarEO6PGuog2RUGofzjGlJ17almLaGQg3Svkq0rPCEHdYGdjmG+IZaqmKqZGsiUKsh18pkcIYvJTthvlkkIO0eqr4O0czrG2iXHKzIPFsaXYT91nE3Xx0kb/XFCvoP0qQZWnyEHKTXcQvq5u1H7A9xJB+IMwmEfOaEC1pOI/qg7ga/6Oigr+Q6qJDfjMW20HKsioWLSpPpXHJSUq8yhEPtrGkEOwvqnh2QbrOdR/lCHWgWrQsox6lqzkp6hZ+nfMa7B1FqcKmAlXHlE/57J8tll+foN5xnQ0OG0h8cAAAAASUVORK5CYII=>

[image6]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAYCAYAAAD3Va0xAAABGUlEQVR4Xu2TsWoCQRCGR7BRQRECYmkpCBZiIdgkWATsbJPeRhDyBNfaaKGVVlY2Yi15Ap/AvICdiI1NLEz+310ve3vkvKu9Dz5YdpbZmbk9kZioPMM9/NGuYcqIZ+GnEacrmDHOuCTgFJ7hN2x4w1c6cCneS3zk4Rz2Rd04EZXc5AO+WXs+qnAEi/AL7mDJiCfhTJ8LhDd19doRVVXPjYo8iaqYlQcyhDW9rsAj3MCc3mvCsV7/y20+vJWwjQW8wFe9x2pDz8ccLhMwERPyK0Wezw22xNbY4ouEmA+rYO91OwDeRQ19CwdWzIc9H5OCqKfAZHfnw7L53NN2QOPAAyxb+y4teJK/f4e/RdtzQsGnwH8vcD4xD8kvcTMzNIxbkGYAAAAASUVORK5CYII=>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAYCAYAAACMcW/9AAACoUlEQVR4Xu2WS6hNURjHP6HIu+tRHrlJiRTlMVAmXpmQPCKUgWKiKOWdlAyQ8khJCUl3cJMJGTA4MRETA48BYqAUSYmBgcf/d769zl57nb3vdU0M7H/96qy1vn32//vWa5vVqvXP1SGWiVWiU/SL+sdkv1saLDaKi+KYmFgcbmqaOGEeQyzPxOoU58UtsUb0L4wWhZlF4oX4IC6J3eKGuC5miftiengA0Xgi9psbXCceibFRDC9+LmaLoeKouCtGZOPE7rPc/ALzZMo0RFwWX81j0oQ2ix/igRgWOnnBU3OTZMmf3BPfxJwsZpJ4KTZlbTRKPBY7svYSsTwfbiZzQAyK+hCJ3RGfxfxkLGi0eCbOxp17xScrlnixFauDwdg4IimmqGFuijGqHsT62hm1Ec+cFj/F+mQsFv/XEKtDB9k9NK8MfwxUOJ0KMkuNoqvivZgiBohdYqt53EkxOQ9taqH4bnlyVWKs26Li8YNqYpZNcFCcMy87azEIQ1VG0/6RYpwYGPUhEukSv6y4hMpE5VlarYLxAl7EVIQyE3TcfDeyscI0pIZQmdEqTRBvrX2Z/ZGCUSrIAg5aYZ75divfXEF9MRrexTKjWn0SZ9UXa18zwShGUJWhqv4yBaMN63l9MqOHxdS4k7X02tofTo1yAZQZYvydlV8OqdhwbLyG9WwUgxcsuUzCAk+nI556tNL8AOasDOJ8vJ2RnpVlIuam+fk5MxkLYgOesorzdan4aHm10s2EOsxvqiNZG5E51dwQ9fUmDGD0mvnajzXc/GpunZ2pyOKQeCO2mR9PGJgbB2VtYvaIteazQELpMdSb5olX5vf7GbFFXDG/jmfkYdXimuTrha+YNNsg+sNXDvF/K85HjigSZpmNt/yLqVatWv+9fgNus4PYIWGU6QAAAABJRU5ErkJggg==>

[image8]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAYCAYAAACMcW/9AAACfUlEQVR4Xu2WzYvNYRTHv0KR97zlLTfZkAkJUbORpKTkpSmjJBvNBjMLLwv/gOS9xIiSlJdslIWFG8VCWZlsKCOlFDZoZjH4fuf8nubcc+9vfu5YKP2+9an7e87ze37nOec857lAqVL/XNPJJrKNVMgoNz4z+12nKeQaaQnju8h6MhG20Cyyh6xwcyrkInlAdpDRzhalNTaQ1+QTuUq6yD1ykywnT8iS9IKXXj5GvpNVbnwMuU1+Be7ANibJ8aNkfPasTe3OfkdNgAXjG2xO3JACMECekknBNqi15AvqHZW6ySvyntwlW1D7gY1ks3tW5I+TcW5M0sYekq9kTbAlzSA95Fw0SFrgCrmMxo6ebzDmJZvSnaT6OuieJWXsDPlJ2oLNS5usku1hfHCBTtiHjmBkjqo8DpH9sHknycKaGUAr6Yc5IWfyJJvKqq4+lYJTZCzyHb1ATpOX5AN5TlbWzDBNJbNha3lpI7dgtd0ebFEK3DSE2lXKle5K9pznqIpfBy29rIJXPefVWdQ88o58RoNIFUmeH4a1nqQ8R3X6/A7nwyKrKClaRdJ6WvcFLFpNSalLKU/KczRqDuklb2GpLlJytIrh61PBO0EW+8EDsHbjUW9THakJq4+pP+6DnVTNT0qOCv0u0iLyEcWOysFLGOrHuWoUUY3Jee9oSn0Vw384Sf30Pqx/Lgu2JGVWGf6juleT/kFWu7F1sFPvS0R9sA+1vbNIckCO3oDdTl6TYYe6rndG6WZRutP1qCvsGSz1qpsu8hjWJ3Vj6PR2ZLZmpAC8gX3rLNlLrpNHZOnQtL/TAtg/HP3TSXf8SKTuoRa1k2wlc9H8hkuVKvXf6jf8Ine1EQHLLAAAAABJRU5ErkJggg==>

[image9]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACYAAAAYCAYAAACWTY9zAAAB8UlEQVR4Xu2VyytFURTGlzwiIpJHlJshGXmlJAMDBgwwUP4ARhRhrgzMJCMRplIGkpLBLRNlSqSUgZKECfLI4/vsu+89Z7mHc6MM7vnqN7j3O4+11/rO3iKBkliZoAH0gtbI739VOVgCR2BITGGz4DryOzV2aVSFYBe8O3gGy2IWNA3uHN4rOAA14lMd4BIMy9cCesALGFX/O8X7+WIuRIvFH4IzUOa2vlc3eATjIEV5FFe+KaaTxcqzmhJTWJc2oFpwD9ZAmvI8VQ2uwAbIUp5TfPEbaNOGxAq/AJXKo/rFFD2gDS+lg1UxL2xXnpbtSKc2xBTDosIgx219ToC5ZRSaleepJvAE9kG+8pxi+zkGr8LYRS5uDpQqOJFjMRlj1nxpQrwD65QN7wOoVx5lu7kF5hXbEc8zX3XgVMxnb7Ui/mZvO7IH8pT363yNiLlgXWIbpi0s3nisuMoFMdcNKo+y+doB2crzlS9+cS0g1/EfR/hTYY1iPnWORAebsvsXx6nF3DK/CeWL6hPvh1IcGztxAiqUZ/Xn+xfFDrATzF7IbUmJmKK44pDbior3h8U7X8wVi2aMElaBmL3sVswDeD7OgHMwJvE33SIx5yPPRL6Y8DxcBBlgEtw4PMLzsYo3JyoeNcwaC+Pew803UKBASaUPc4R5aNcw1I0AAAAASUVORK5CYII=>

[image10]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACsAAAAYCAYAAABjswTDAAAChklEQVR4Xu2Wy6tNcRTHl1CIvG4eUc6EwkDSJY+4yYCBiUcpQ3kM5HHlMRETEyaSoZKEyEDJgPwBSplJibrJREIJkcL309q/e377d/Zvn03SVedbn+7Z67f3Peu31nev3zHrqad/rnFiudgmBorr39Z68VK8asgGf2xYs8SR4m+V5orL4pk4YJ7sBfGuuB7dvrVeo8RFcVO0imt0SfwQG4tr/uE6MST6i1hQuDfdBNok3oiD1pnUVvHdfKONNFPcEjOi2FTx2DyxOVF8orhqXqlY88Qqa280aIv4Ko5VrCFscM+84uTRVVTjcBJbIj6K22JMFGcTtG9SFMtpsXgr7orxyVqsM5bvSoe2iwVJbKf4KY4n8elij7WrNFasNd9cXDnidCu2UU4ky3dtTheaCg/ipTXpQqTJ4po4YW6XXdHaSvHN3Ep0Iye6Rvf+ONmcX1PtNe8A9wyJ09EaHSEBLFOnPvFUfLHOl7aRlonP1unXWMRPitlih/mXUc2gK+bJsqE64VOs8si8U2iR+SaBz7XK+bVKJH3Dyl+GQrJ1reVZ7MZ9+4rYUnHIfMStNp/pWSvykjC8u/k1aKH5YN+fxKlKt2RXmHfwgflIRBSIw4kxFvzMhirV1K9BJEmyJD1gPikQ1iBZ3vQq0YWH4rn5jA7CwxzHFC3M4Kzvm/g1aIK4b34vn8+az1ZEpagYVWoVsSCOZBKlKK3yUknkwvNYY1jM2CfivXk1Ap/MTxYeyolj8oW4Y35axZpmPms/iEHz3wPnxWtx1OoPCip/3cov7V/RFGt7rkr4D++SLJXnwKgTiZ4ztxbdnV9eHjliI6fMK8pYxL+7S3eMIHEKxlaE1F499fTf6BcPRoSl8o7l+gAAAABJRU5ErkJggg==>

[image11]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFsAAAAYCAYAAACV+oFbAAADp0lEQVR4Xu2XS6hNURjH//KIvKMk1CV5FCGPIukqzwEJAxET1zPyCsXkSPIoA8qADEgeAwOSCOmWiRhRTJBHYiQRCnn8/7617llnn7332Vf3HEftf/26d39n77W/9a1vfevbQK5cuXLl+p/VQJZEjYGGk0PkBFlKupT+XBP1IJtgPuwhw0i7kjtM9eBrmUaS9eQ2+UFOl/7cokXkMRlLupG95CbpGd5UZY0hzaSR9CZryDeyDaUBrwdfY6VgLyBTyGvEB3sQeUKWBTZN9j7ZENiqraOwhJjvrr0P72DzkOrF11T1Jy8RH2w5/pmMD2zKpLOwTFP21EKHyS+y0l13J3fIR1jWS/Xia6rSgq2Mik5A0r1vyZCIvVrqSPqS9u56FHmP0iBm9VW1fy5sJ0gaewKZR/o5m5feNxU2pv7X4jXAKoK3SX1gz0+DjZeotGDLljSBOHstpGApW1/BarNXkk+hXQtzHHbAqnQuJ1fIarKbfCAz7LE/2gi79yEpkGOwc2AFeep+07l3EtZgXCY3kLKLkoKtB5pReQK1UldyARbkZ2Q2ipmV1dc5sMNV/8t2C8XD08dhp7tWlh+B7Sjdp500yf0madyfZDuKh7SyO86HFiUFW5PTS+IerhRsvVxbS2NnobM9llkjyBtyBuZnVl9XwQ7UheQ7mR7cJ7sO3K3uWqWliQyE7YKDKAZV/l5F+VmghUotr0nBlpKCmmT36kUOwHrdLKiGtkaatEqJDs21zpbkU5xd9f0RLGu9VAa+wmp0KJUVtZlheRlAXpB9gc0vwHWk9PZpwdZgUUcl3avV1qpXWzpwtjjCw0dZpGB7v7P66juZi6SDs+nveXIX5T35LpRnqwIftqKSP7RT28y0YGswDRquql9B0drt/zfy9TUaSPmrYCtLpay+RsuFNBi2IAVYVu6HlUH/vEqUSpVXXLlQkBVsBX0yLDnK5IOtbantGUovvAdzwmsozLG0z/u2lP9YOYVi1nm/NLlxEVvBXUtxvvp6HZYLHWxfyEQyE5bNkq/XceUiXIBO5JKzq4bru6BkhykDNJCyQRkiPsHanNHBfToonpMdZDHsi0yHRWo/2cZSTVerpfcqcJqU2rRorc/ia4E8gC2OlzJU418j51BcVGWoFrTRXUvqUtQNFQKbtBmWFCpP61CeuJmlFZwFa+b9x0CtpYxqhAUx7eOhkq8aJ64P1njhh5Ok//XJHw2cFiPu/WoM4sbOlStXrly5cuX6R/oNeAroWXb4KwcAAAAASUVORK5CYII=>

[image12]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEIAAAAYCAYAAABOQSt5AAADuUlEQVR4Xu2XS6iNURTHlzwirzxyiXJISeSR9yt3IDFggKKIYsBAFCEyuJKBlIS6hUJCSRmIgQyOTBQDRIrUJZEkI/Jm/ayz7tnfPt/jXAMDzr/+3XP3c+31/kQaaKCBv4zuymnK5crmyv/1YIBygST3DFH29QUp6KocK3YXe/PWZmKg8pbyZ8AvyvnBmm7KC9GaHcF8iGHKU8rHys1iwh1Rvqv837m6NIGeYvvuKtcrdyvvK1uUN8XkjNFHeVD5TLlH7C7+chfjPapL68disQeeiScq4AHnxQTEAmlYpHyj3CK1D16m/KrcFo2DXsrryn2SPHuU8pWYgjoF42Ci8qnykNQ+GE98r2xVdonmCjFZ+UF5SdI3T1eeldpLHUuVn8Q8JRYa4OZXxTylKZpbqXyUMs4555QbovEpyrfK45JtFLwQZYyLJ4owUvlaWRazUAgef1o5KRp3EJ8IdkWyFQX2K39IMuxQOsonPHsH446jYkZyDFI+rJDfWVgl5uGxEguBNYi152LJKcRq5V5JtzQWuSj2wIXRXAwUgXCEoQOll5XflSuk9o7xUlUuc4QPZ2xqX5EOV8TOeKIILhCJZkwwXlJelmztz1R+Vt5R9ovmQrjlY0WAlsq4J2rWkfhi7xqhfCnmuXhwHlzpHVaEC/pRObUyhgUOKJf4ohRwERcSk3kg65MHwvMdlDtyQViV4DVJhilyME6uySvHno9YS+7qME5K0mJzlcckOyEBqkw9sUheIHxuS3ad554ZYkkQz4jzSb1Kx6PxbLwHLwrB3eSdLA//Db9oq9gGegdKWB5cEbG7h8DbXMkbg3Fcf3jwfwhyQHyuy1fk7r7usCRzDr93SXoeTAA34gDiC2UUWRlgnVjgGJReSjO9Qujqc8QaoDRwHn0HaxzIU6SIkljSp0zT3IWg7KKce1KgCHdfDqFniMtoGugBXHlpwLNuKJ9IrfV5UJqbe3UoS1IGT8xZvQ6hRVjRP9BUhUCO7WKKLVSEN1UQK9YDBMXSWKGUnJLBYkqgopSSU+3JOW3fLDHFxY9hT6uky+ctepvUJmOwRix38MZCRTBJ/GCNMLaK0F+sl8AShBSlDxckWWGFuAyCoWIKZH2bWMO2ViznUF3m+cIInMV3BNUHL/Tvixdi3sX3R4wJynWV33UpAteaLabdP0GTWGwjHN1mXrVBeSgDUO6axfYRx3n7HLg6X5rswXPyyikKo3MtKx8ov4kZYXSw5r8DhiqsGv86+DrGE0i4J6Q2NzXQQAMNpOIXzxPNh7sQc0IAAAAASUVORK5CYII=>

[image13]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFMAAAAYCAYAAACGLcGvAAAEc0lEQVR4Xu2Ya6hmYxTH1+R+iTQahBx8EDMMMaQkJJEIjXKZqfmmJFNqRsmHySWh3GY05ZJLuZVbySX5MPFF0Si55VJDapLMlJBLLv/fWXud8+z1Pvs9+5zXF9r/+ve+71772ft51rPWf63nNRswYMCA/xR2EY8WLxHPE/cvbEeKexS/M3YTl4orbXTsgnC2+L34d8M3xL0K+37im4UdvijuU9zTFweK71j7Wb+Lj4t7ineKPxW2P8WPxONtFMxxnfn9H4h3iTeJ74rXipeLL5g/N4M13S1+Jd5s7kw+f2iul+ufNxaJD5kv7Dfx9LZ5GpeJz9uEL2pwgbmzHsgGc4d/LG4TD22bZnCs+Km5E49LNqLtOfEvc+dmnCh+Id5jo2s5VdwpbhZ3TbbeOEB8QlxrvshN5g4ucYN4dbq2UNxu/p6Ls0E4WfzZfONqCzrFPJPesu60PNc8MPgsEWMJHJxeAxuMQ5dlQ18sF+8VDzHf8W/N9SbAoh5u7psUpN2r4nbxqGQDbBiOviYbhCXmaU96TrVNLbAhH4qHFddiLOR7F8a9vxd4QAzeYP6w62asnnpELhHchYPM0/fwbEjAgThyi7hv2zSdDY+Jf4hnVGy3ms/txmTLwJlP26xelmPLddUQzpzrHZ1AP5gAILwJc4Q80oiFbWy+Z1CIHhRfEa8wdzqaR9GqFSlSDz1DSsiEklTWz8zHs4ElyBQypiuiS5DCuar3HRsStCBnhl7G5EnpZ8wXfH5zjait6SWTRn/ettnJR+QRYVl3QUz2dfOxJaNrqOkl+ooNiahV6HHoOzYkiHspuPNG6GW5cJyIM3EqFa9LL3kh7QsRGeC+H62uOZPoJZGCjc2YL2JsrXsoQZdAe1TWDHSXtukO8UyrB8gMSr0MEGWkOel+jtX1sssxPI9qHLJRIqKWSpwlYJxegnDIXOmHXNwm7l5c6zs27rvPfD4UKrIExy4W37N24LTAALRwRTYIq8wf/Il5M53BpL+20dR5xOqaB6K/rEUXm8Vku8b2LQy14OD3XGOnzLsEupnoAo4QvxQvNS+WW6w+92lkvSxBdebBTKKml+FMnBcIhzzVfEc+OG0EJukvjxG/s9ETWokpc+3N/SeHEA4jXc8O7ScTadxroDB/Lp6UDQFSmKPh3tnQYIO5hqAlGSyIhZGaRDhcb7MRwALQmUDsbJaFQEQPh4Ma4vnIwJrmd4kTxJfMoykDB24236zTkg25YQ3brJ6h+OZ+8y5jtY2+d7o94UzL5CG7dmHrDge7gcOyXgY4mtEcP2l+31rzSH1ffNl8YegO53FOJPE+3v2oua7dIu4obJDGOh8TAX9qXC/+an6UxLmcw9FgdK7Mggw2n3P3L+YZstK8sHxjXpjGjQWMf838nSMO/bdAiiAJZYOMWI9rQSYFzz7L3CF85uZ/HJAA/iFiLCk9bp4Hi1fZbLFEErs0fcAcQHpo82j3CBJqQS64A3oCmXpWvEi8UtxqLm0DFgh0Gt1Hyrr+aRowYMD/F/8AWysCuD/5SDQAAAAASUVORK5CYII=>

[image14]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAYCAYAAAC8/X7cAAAC0ElEQVR4Xu2WS6hNURjHP6G8HxEpEpmIooSUcskzmchAMTNQUreIWzK4BpK3PCYoUVKSSAqjGyVFBgpjpQwkJQaUx/93v7XsddbZ+7jnmEj7X7/O3nuts/f6vvX/1lpmtWr9Nxoq5ohNoksMC88HiVlicLgfJyaE501aLt6Ln4F7YnjSPkY8SNrhphiZ9GlXvPO0+Cb6xAFxUDwX68Veccp8bJ/Mv3nXigCbRGTnzV/4VSxpbO7XRnHDGoPrRCvME3ZbTM3ayPJj8wHzPTRTvBP7YqcyjReXRbf5n89a83TtEluyZ+2KQZEkkoV9yrRdfBCzw/1K8//wW6l54qSYIl6Lt2JG0j5EXAj9OhVeJ/MPxdisLdUG8UiMDvdYixlgJipFZokc9ZrPws7frWYTzWeImarSZLFOTMsbzLN9XfywwhpVIgDqA+F5vN/S/+iEWBCu54qP4okVmVoqzoTrXBTzOXFHbDYP9KV54cdCp6aorafWOgmIgY4K19H/zEKlov/JMsIu18yztTY8Y3bK/E9m8XNqi/jRS1bUUY/5rMbMDlRt+T8tWgZOAATCqlPlf+zw3TzzUfRj6YuWRCSIAMqS0Ept+z+KbGIhrMSyV+b/6M/8A7zvixWWRDEA/N1KBL87XA/I/2Qdby/MG6St5h99JQ5nbYgV6401f+CieQ1ESyIy+acAGMt+sSrcd+T/VKwqLKlVUx8DYMBRvI9CvRqusSa7bpe51cr2l6jF4pgV+0Pq/2ViW3jeIOzBsWBE3hDUa42bSipqg2NHLFbgCEDAFC0rz6HQNxY7lswLkv+tMQ863R/YOJkBzkRHLDsd8JLPVpxtWOI4g+RiSWWQuf+j5osX4op5v27zGXkmbonpRdf+gI+az0Sf2GEeMJvWntCeiqQxw/fFcaveuf9avBi7pSdJzjRVhUeWV5ufQBdZdT9E2yQrTqW1atWq9Q/oFyKykwLjJspXAAAAAElFTkSuQmCC>

[image15]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAYCAYAAAB0kZQKAAABz0lEQVR4Xu2VSytFURTHl6QozxQTAwMGkiQhRpJXycBrQhkYIDPkmYmBEUoyYiADEzPlA9woE+VDGBImKMrj/797b3fffR73usrE+dWv7tnrnH3X3mufdUQi/hk5sBYOw3aYq8ezYBXM1tceiuAhrLPGePM4PIPbsMKK+VEId+EbjMF1uAGvYR9chDvmZhdmuAKfYaM1Pgrb9O88uAzLEuEkOuAdPBVvsqXwEn7CQSf2TQt8kOQkuIWrMN/cBHphp3Vt4MRc/b6oUvgxBe9hjRsgLMOBqAnsJLg7c6JWYRiA9dY1Ye25A+ei5gqiH17AAjdg/mgILom3HNVwT49NwElRzxi46hP4ISHbrGESPC8emkUdOE7mlwRhrBwWO+OkFb7CK1jixFxYXru0cbh1LEGlvg5KIgw+w8Pmu8JUcEtn4Yg1lkkSR6KSGHMD6dAgiTIYfpME6x0GD/O8OzgNbxyfRE14K+oUB/UDGzaiVElw19dglxvwI5OdaIfvot4g+62xYQ/akuD+kQQb0wtscgMhcGIe7kfxNjEm1QOPJbx/xOHDLAG3lXJlbLHplIOwnW+Kei4GZ0R9I1jSBR3/M7jablFfTvYf8+WMiIj4EV9pPlP1pI5K4wAAAABJRU5ErkJggg==>

[image16]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAD8AAAAYCAYAAABN9iVRAAADZUlEQVR4Xu2XS6hNURjHP0WRVx6FKMejhDvxGngVohiQDBjISGIgA+U5OiUDJe8RtyRJwowSkjKgFBMiJZc8ihChkMf/d9b5zt173bXPuabX/tcv5+611l7fc63NrFSpUj1MfcRUsVJURK/6swmZOQ0tFG/EnwwfxNv67y/ikBjkCzJab2Fudi3r/BlrT4iRviDSHMvv/VAMz83Ia4n4ZWEu/14XwzLji8QzcUSsFefFRXFObMzM66J28VPMi55Pt+DQVTEgGkP9LRiBE+OjsSnivngixkZjWe0Xr8RLMSYac+HkWfFZXBC988O2wsI+ZN1F1veIr2JG5nlOA8Ut8VSMiMZw+Kb4LRbnh2rCWIy+LPpGY6hNfBTHLBgTi/efFoet2EjWbRK7LNixNT9sg8UdsTl6jmaJ29akoiaL95aO6BBx19JVgQgIBu2NB+ry4BWVNNVCa6y2UM7L88M1TbPg/E5L28HfPF8VPUcEk8CmAl8TJcPGcUTRbPHdQmSJcKwdVlwVyJ0vKmn2JqNk6Jt1taGfqIrRFqorVZ0EDPtviKHRGH9PjJ7lxAGRiijO0s/vxMxoDFHmGJTqdxeGYvBzMSoaQ1ULgfPqiytojYVxnO+wdHWOsxBcPzgfW3hPU6eRZ4bsnhHH65wSr8VJS2cMuUFF/Y4oO3qZ1qGFsvJ+5/0eJGzwEq1YqCyc9faKK8O1zDpvKOeHpduoIY/4NQsnMtlxihxytep3xBWDIVRXLO939vEkAL9xGMcrYWrtd6o6YxFEruAHFvZtlphGv++OB7qhVv1Ov16x4lPc+x2RbbLuPc07KXnk7ZXqd6qG6zYW8x5ZZzCTIiPNHChSd/od58jWdkuftlXL70sFUYULxD4LwUN+ncb9zu+jlt7fKyle05Df7x0W+vdf1Op+p53IFOcHn5exMI6Plqzh9DMnPgZzvbmK+h2buYXYKxaHXYelr7+a2ix8gBQ50ExLLd3vlOAG8clC9lKOo7nikoUEuPzKohWylcIeqX73+z2eT8W0W0Hg51u4erInI9/jHBSttM7ypyon6os6vIPveW6ISb4gEnsT8Ox635dzgc9o/14/YOF92bmcIX6XbxMHLVTKPQvttcVCr9POqbOgx4gAk1myXrHwPzmqJz4US5UqVarUf6W/iVLbOiglYMMAAAAASUVORK5CYII=>

[image17]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADsAAAAYCAYAAABEHYUrAAADDklEQVR4Xu2XS6hNURjHP6HI+xGJAaUkykBIKTd5hEgeUYyJkdxQMrgGMvBIHil5ZGBAUgbKQDpRUmTEjAGJJJRQyOP/u99e7rrr7n32PeeeM7mdf/1q77XW2Wut77XWMWuppZaarMFiltgo2sSQrH2AmC4GZu91aaX42wu+ibnZb5qhkeKU+Ckq4pA4LJ6K1WKfOBkG91VXxC+xKGnHktvFWzEz6WuUlogP4paYkvSNEw/NDb4+6atLY8Rj8VJMTPrQeHFbTEo7GiA2gDfPm4dwnnaIj9YgY88RX8QNMShrI0eGZc9s9pwYnr03SuQmHr0vRiV9sdaIB2JE2lGPtpqHyZ6oDSseM9/0aLEpe47F+1SxzjyfaykeePG6+GPl4clmyecg5mE+Ui6dE6MVRUinLlj3fOUDR8zDp0iLxXNx2rxyspgT1tMgRVoofpinD2lUTVTkEFVshEJ1wDwijodB0gzxXmyJ2rop5CuepQh9zZ6/i3nRuFhYmnGbo7bZ4pp1hX6Z9pvPE3usN1omDpp7kNBmzuBdIpR0JC1zRThwrMT5SgjfNc/VVBPEM/HIfMJw/hGSG6JxZaL6s1kWWIt2mm+GyMAhsReJ0KqREvIVSwfF+ZoqnMt49rW5UTgT2XAtCpslSqqJjbWnjVKHeCOmZe8hQi9b/ro7G+lMz1fyoigcyePeLLJMXBjKvsP6CFlCNxb5W7Ge0cjxVFhnys7XPFE5i25TGChYFYMR8kWVsU38FmeswBPSAvMIS7/Bef/KukcjERrqzCqxLerrVF6+lomwIXziXGOxa8VZMTRro0riuY7sPRUb4CLxWSxN+vjeCnHV8s9fHIODqMiIMaQTBphsPuf/Cwgfp/KymMAncUeMDYOqiLx9YZ53F8UT87yKPbDb/AxlEUWXEQxz1NzDFbHL/A5Mld2b9ecJYzAfRmf+m+aF6524Z54iRdFSl9gYFubuWvRhqjnncFH+B+GZ5ebn9Xzr+qdTJozIGoKR+V219TRVHA94qt8Lq18yv//2e1EguFK21FJLfdM/t4KVxChNawAAAAAASUVORK5CYII=>

[image18]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFIAAAAYCAYAAABp76qRAAAER0lEQVR4Xu2YbcjeUxzHfzJF5nEyQhuJFosyamstStrKJCRhyxtb1l5N2BCL1tgiU0seIi9WXniHTSbueEGmNBllL4w8FJkSymTz/Tjn5/r9z33OdV9zXyXd17e+Xdd5uv7n/z2/p3OZjTDCVMUR4rFl5wiHjwvFhywJ+n/GkeKp4vRyoMRs8aaycwi4T1xcdlra2I2WnlvDMeLN4jPiJvH87vA/oJ9x5jGfdcPGZvFP8ZC4shj7G3PEVeJblia+2B2eNE4QnxdPyW1ecqm4RfxG/FW8JI9FsG6n+LAlC7hY/FS8Pk7KbfoZZx7zWcf6YeMW8Tfx0nIAIOS14gLxaxu+kFeK60MbIZeIl4sPWlvIe8Rd4kmhjxf5TJyZ22eJe3O/g/msWx36hoUnxT3WM4oqThe/tOEKSUzE5eaXAxmIVRPSxSj3giX8Il6T2whYrueZ28QxGyCWHQZ8Ty+L04qxDgYVko2eZ8k9ZxRjJbCcF6ztZi0h8ZIfbfxemMf8DbmNhdTWs+478ZzcPt6SF2DB4ChxniVP9D5/rxvyZ5kYfU/V+BgxiJCzxXfEZy1Zw5uW1jwS5kSQuIi/LbSEdMHKvZT9fNbWx36s8mnxAfErcZn4irjCUhL8QbzaUqK6X7xN3CfeaV3wvn+IC4v+cZhIyFni55aCuZ8Wmfig1U8J899qqfRpoSUk1k52LPcShUSgsdwu10ch2SP7u0j82dLhu4f4O38vXpb7AOvHrBsaBoqPoJ+QCPeE+JN1hemXxXArLPfociCgJSRuOJGQFPiIUlsfhbzDkojXWbKoK8I8d1f24fADirFw4PgI+gl5tqWM/pp1hXnO2qeEFcRsWkNLyNKFW/1RsIhaf82iSFq/W9ddXdyY9QeOj6CfkFgcludBHvgpkSGx2AhKHETmAPqhJSTWTLIo9+JC3pvb7Ke2nnUc/Jm5fZz4ro23KMTdJ54R+hCw5nkDxUfQT0h/Adyj7KudEmMU3KXAJVpCunuVHkBNeiB/AiyKS4S3AfNZF9e6Ra3xSVZ3YQzg9Uy+32UpdkZrXitekOdX4ULWLIz75SfWiyUnW7oJteIj2bB2JSzB77V+41ZLWdatmj2R6N63XrKYIX5g3YL/XEvWGK+6Hh9rLhzFpewhi2MclEV4Fe9OLEZwLLxZznGaPNjvkZCi92NxbpjHFewjS2LvtOTWZcwBPISH+e2jBEniJXG/9Z4HvxUfD/Oo9Z4S37ZU7yEiz2MfEdSDX4h3W6oB2dejltY71ou7rVv3ktA4xHhZwEq3i2+Ir1rvWbdbCjWMRa+cNDw+IlhpvZw69dgwwG97kbzIuuJEcDhXWbfAjsDFYykD+MOE9yj3Tz/GUT7rxMx/DTa5zlJt5+AUOc3aP0UbrX0lnNLwmu6x3D7N0u1mh42PFRNdCac0EGWr+J6lEuJDcbnV//PzW8QIkwT1FtlwhBFG+M/wF2AGAOTBas7zAAAAAElFTkSuQmCC>

[image19]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADQAAAAYCAYAAAC1Ft6mAAACrElEQVR4Xu2WS8hNURiG3z8UEbnkUuS451KUJIokAxKp3whloMTMT7nnkgyQgQxIEmZGRigUUa4DBm5hQmJkIhQK73u+tX5rf+fss/dhpv3U09lnrX1Z37e+vdYGKioqWtCPLqAr6WTaI7T3pSPDcTd96Cp6ih6mk7LdpanB7qMH6IG96XS6PhwLPWsLvUz30P6hPY8p9C79TC/QzfQ8vUqn0it0UffZZAC9Rg/AsjCDPqOd6UklmUu/0V+JX+jS0N9BN9EJ4f8gugsWpKcX3U2/0+1oPGce/UTfwc3QNvqQDkzaVtPndFjSVoaZsGS8oI/pfjoi6R9Cdyb/xTpYCaUomBP0B/ITqxm/FIyzXw9CwZyLDYFZsCle7tqLUEDHfWOCKmArbMBCM7YRjYnbAJvdHbBz8tC4MwlSZj6GjhQNTKVy0LUXURSQUKkcotNg1RHLMTKevqev6CjX5zkN9/7EgecF5NuL0HUXYS/ta/qW7kVj/atEVIqaMc8+2OyUSabe/zjbdZbBLvYD/5eA7sOyLAbTB7DVM/PgHBTgTfoTLvNlWYLigFSWWvtbqftoFjRo7QspqnGtfHNcezM0a2/oBzrW9ZUibybSdmVND2rlUPzZ6Dx6T5Q07R9FxIBkujo2QwuHtokMyoKykReQX2JbofLSivkEFmAkBqTfIuKqWxSQnnUG2efUiTWbWcth9asNrZ06jtn1ASkpCqjsFnAU9g4t9h2BDthsd/qOyBrYajQm/NcF+mq4B1tFytKTnqSzkzZdf4teD8dlGE1fwq4b7vr0nupzqQst9qe4K9+gK2DBPIV9ArWLBnObHoF9ATyid9Dk47GAGuy6r/QsXUuPwe69EC2CieiEibAVaz7KLbF56Frdw38Vt4vGVIMlWY7D39+roqKi4j/gN/JVgXYlfbUFAAAAAElFTkSuQmCC>

[image20]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAAAYCAYAAABKtPtEAAADjUlEQVR4Xu2WS6hNURjHP6HIO/IIcXUlIeRRJCMDBkpSiBFJifIqwgAlEYoieV5JSDEhoRATjwkGUlKUMsIEAyX+v7v2d/Y66+5zr3udM9A9v/p3zt5r7fX4XmuZ1anTXnpLg6WuaUMEbX3Sl1Wmi9QrfVlrFkuPpR3SdWloeXMzbH67tDltqDITpb0WDFFVRkvL0pdipPRCmpM9r5S+SLulsdIwab50V7pjIVJqyU4L81WF8dI66b70S7pQ3tzMAumDNCJ7HiMdkRqkJdIKaZGFyJia9akV/aRz0qC0oaNgABY/W/poxQbYZsEAeBr4pV/s6bVW+9CHeRYir+qwKTZZZADyPzYAkXBS6pE9T5AuWu1Dn5w/KM1KG6pBawYYJ72RZmTP5N+m7H9PqcnaDn3qCKk0MHlPNe+e/e8rzbUwZhFDpPMW0iCG7/lumpWfUPGJhPEmS415czmtGYCPt0iPpFXSTcvrAWHfVugTQYx7QHppuRGGS+8t//6Y9NtCTSmCAk29isEYl6St0mtpddRG6r6zYDhS/bP0XBoQ9SnRmgEcrLfQgqcAr1+xPPSJFEJ0ueVeZbNnsl+OUOqMG498/pn9wkzpqxUboJt03MIRGIND6M+YjM0cQHreysR/1nPK/tEAMWyazXvos/in2fMaaaOFyJluwSB46ol02cJmYJ+VG4T+hLgbJIaT57TldQcYBy9zOSM6flheH+j/yXKDACnM/PEYJdprgDj0WQgDsyEghymShLjDwlig3zNSD/k7vBx/53DKFEUG+PwY2OtDGl3+zmtXC9pjgDT0yTFyDW84GywUJYc2PIJnIA1ZaJCOWh4hDgYljWgvwmuJOwDSdANuqX6Za8HfGiANffBvYwOst/LjinG5SntVxjjfLdQUZ2mmFPpiGFKkCB+LYusw30PLnURkUGTTE6SEb4KKWmkiIOwJxxg2xebcAHx/yELldZg8LkBcp+OKT5E8kf2mtHX19Qofj/XMyuejrTCFyAtChWswC0LfpFfSpKgf4PUmKz6n2fwNC9W20UINiPuNsnAEYqhrFnL9sIW5z1o4WqeUeufgMQojaVYJDM4xjRHw/AMLhfitdFu6Ku2x/GTqEF6g2FwRbJZzng3es+LNsFC8gzzKCFE2V2lx5Oyu9GUFWCOR7EWVixAnRP9Sj/+Q/Vajq+//QKWrb6eBwpcW3E4FVTs+SerUqSJ/AN/joiqj7YjRAAAAAElFTkSuQmCC>