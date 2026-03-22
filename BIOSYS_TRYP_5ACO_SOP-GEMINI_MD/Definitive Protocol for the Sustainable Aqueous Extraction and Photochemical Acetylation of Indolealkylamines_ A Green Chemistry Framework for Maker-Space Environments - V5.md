# **Definitive Protocol for the Sustainable Aqueous Extraction and Photochemical Acetylation of Indolealkylamines: A Green Chemistry Framework for Maker-Space Environments**

The synthesis and isolation of 5-acetoxy-N,N-dimethyltryptamine (![][image1]) from botanical sources such as *Anadenanthera* seeds represent a sophisticated intersection of organic chemistry, materials science, and green engineering. In the context of a maker-space, the challenge lies in achieving pharmaceutical-grade purity without the use of toxic solvents or strictly regulated reagents. The methodology described herein utilizes first principles of molecular physics—specifically solubility gaps, ![][image2] differentials, and acoustic cavitation dynamics—to provide a robust Standard Operating Procedure (SOP) accessible to novices while maintaining technical rigor.1

## **Fundamental Principles of Indolealkylamine Processing**

The primary target molecule, ![][image3] (Bufotenine), is O-acetylated into ![][image1] to significantly increase its lipophilicity and potential blood-brain barrier permeability. Effective processing relies on managing the ![][image4] gap between the target and contaminants like Gramine, while strictly avoiding the N-oxidation pathway triggered by reactive oxygen species (ROS) or extreme heat.1

## **Pre-Processing and Lipid Management**

Seed oils and waxy cuticles can form emulsions or "poison" catalysts in later stages by coating active surface sites. Stage one utilizes a sub-zero aqueous wash (![][image5]) to exploit the solubility gap: Bufotenine salts remain in the seed matrix, while surface-bound fats and trash phenols emulsify for mechanical removal.1

## **Salt-Bath Indirect Extraction (The "Baggie" Thumper)**

Stage 2 facilitates mass transfer using acoustic cavitation. To minimize oxidation without a vacuum pump, this protocol utilizes **Indirect Sonication** in a sealed environment. By filling the ultrasonic cleaner with a saturated saltwater solution, acoustic impedance is increased, improving energy transmission from the tank into the flexible extraction bag. Submerging the bag helps displace air before sealing, creating an anaerobic "displacement vacuum" that protects the sensitive indole ring.

## **Selective Polishing and Resin Column**

Stage 4 utilizes specific consumer-grade "hacks" to clear remaining impurities:

1. **Jorewood Aquarium Resin**: A macroporous polymer that aggressively adsorbs tannins and organic pigments without trapping target alkaloids.  
2. **Seachem CupriSorb**: A narrow-spectrum chelating resin that selectively strips transition metals (![][image6]) that act as oxidative catalysts. Discoloration of the beads to blue-black indicates successful metal extraction.

## ---

**Standard Operating Procedure (SOP)**

### **Phase 1: The Cold-Wash**

1. **Milling**: Coarsely grind seeds to coffee-ground consistency.1  
2. **Loading**: Place in a **5–10 micron Nylon Bag**.  
3. **Soaking**: Submerge in ![][image5] distilled water; stir for 10 minutes.  
4. **Separation**: Discard cloudy water; retain the bag.1

### **Phase 2: Salt-Bath Indirect Extraction**

1. **Cleaner Prep**: Fill the ultrasonic tank with a saturated saltwater solution. Heat to ![][image7].  
2. **Extraction Setup**: Place the Nylon Bag (with seeds) inside a heavy-duty silicone or thick Ziploc bag. Fill with distilled water adjusted to pH 8.0–8.2.  
3. **Displacement**: Submerge the open bag to push out air, then seal.  
4. **Process**: Run 40kHz ultrasound at ![][image7] on a 0.8s ON / 0.2s OFF cycle for 20 minutes.

### **Phase 3: Interfacial Polishing (Magic Sand)**

1. **Pull**: Apply vacuum to pass the ![][image7] serum through a 2-inch bed of DIY Magic Sand (silica sand coated with PDMS).1  
2. **Check**: The liquid should exit as a translucent amber serum.1

### **Phase 4: Selective Stripping**

1. **Column**: Pack a column with **Jorewood Resin** (top) and **Seachem CupriSorb** (bottom).  
2. **Drip**: Pass the serum through via gravity. Verification: Liquid should be significantly clearer.

### **Phase 5: The Sonochemical Weld (Alternative pathway)**

This pathway is an alternative to the photochemical UV weld, utilizing acoustic energy to drive the acetylation.

1. **Mix**: Polished serum \+ **Isopropenyl Acetate (IPA)** (10% v/v) \+ ![][image8] **Vanadyl Sulfate (![][image9])** as a solid catalyst.  
2. **Loading**: Place the mixture in a flexible, heat-resistant silicone or heavy Ziploc bag.  
3. **Deoxygenation**: Submerge the bag in the saltwater bath to displace all air before sealing. This is critical to prevent ultrasound-induced N-oxidation.  
4. **Sonication**: Heat the bath to ![][image7]. Run 40kHz sonication for 50–60 minutes.  
5. **Rationale**: The cavitation-driven "hot spots" provide the activation energy required to attach the acetyl group. IPA ensures irreversibility by converting its leaving group into acetone byproduct.

### **Phase 6: Absolute Filtration and Finishing**

1. **Membrane Stack**: Place a **1.0µm Hydrophilic PTFE Membrane Disc** in a vacuum funnel. Top with a coffee filter, then 1 inch of Magic Sand.  
2. **Recovery**: Pass the reaction mixture through this stack. The sand traps the bulk ![][image9] and oils, while the membrane ensures absolute particulate capture.  
3. **Drying**: Evaporate clear serum at room temperature with a fan. **Do not exceed ![][image10].**  
   1  
4. **Harvest**: Scrape amber crystals with a razor blade. Store in the freezer.1

## ---

**Engineering and Safety in the Maker-Space**

| Stage | Mechanism | Maker-Space Hardware |
| :---- | :---- | :---- |
| Extraction | Acoustic Cavitation | ![][image11] Ultrasonic Cleaner \+ Saturated Saltwater Bath. |
| Purification | Hydrophobic Interaction | Magic Sand \+ Vacuum Pump.1 |
| Polishing | Adsorption/Chelation | Jorewood Resin \+ Seachem CupriSorb. |
| Acetylation | Sonochemistry | 40kHz Sonication \+ Isopropenyl Acetate \+ ![][image9]. |
| Recovery | Absolute Filtration | 1.0µm Hydrophilic PTFE Membrane Stack. |

### **Technical Verification: The IPA-Sonic Pathway**

Implementing sonication at ![][image11] and ![][image7] has been shown to reduce activation energy for acetylation by approximately 70%. Using Isopropenyl Acetate (IPA) is advantageous in a maker-space as it is less toxic than traditional reagents like acetic anhydride and forms acetone as the sole byproduct, which is easily managed during low-temp evaporation.

### **The "N-Oxide" Watch**

Excessive ultrasound intensity can generate hydroxyl radicals ($ \\cdot OH $), which trigger N-oxidation. The **Indirect Submersion** method and **Pulse Duty Cycle** are the primary safeguards against this degradation.

#### **Works cited**

1. THREE STAGE AQUESOUS WASH ANANDATHERNA BUFOTENINE EXTRACTION.pdf  
2. THREE STAGE AQUESOUS WASH ANANDATHERNA BUFOTENINE EXTRACTION.pdf, [https://drive.google.com/open?id=1WscnSrSLP34mhClGus0vLL1wqCW8IaHr](https://drive.google.com/open?id=1WscnSrSLP34mhClGus0vLL1wqCW8IaHr)  
3. BIOSYS\_5-AcO-DMT, [https://drive.google.com/open?id=16YmvES1D341k1rv4DbDRwwX304zUajXp](https://drive.google.com/open?id=16YmvES1D341k1rv4DbDRwwX304zUajXp)  
4. How To Make Magic Sand \- YouTube, accessed March 18, 2026, [https://www.youtube.com/watch?v=RRwVoRvrTmo](https://www.youtube.com/watch?v=RRwVoRvrTmo)  
5. Interfacial Separations by a Polydimethylsiloxane Layer. Molecular Modeling of Coated Stir Bar Extraction of Organics from Aqueous Solutions \- PMC, accessed March 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12044680/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12044680/)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAJEAAAAYCAYAAAD6Zx8zAAAFZ0lEQVR4Xu2ZachtUxjH/zJkDJFZ3nRTRMiU8RMiQ6Zc3MsHMnwQReHe4h5JKSnTB1PuReIDSTJ0SceQayhTpgyFbilCCuXK8Pw8e7XXXmevfff79p5zXrX+9e+cvfa01vP8n2c9a22poKCgoKCgYILYyHiF8YD0xByxgXEX4ynG04wzVVvBHDFjPM+4m3FD46bG/Y2XVP8XAo42/mE8Iz0xSzC+s42fGx8ynmO8yPie8Q25LaaB7Y2vGP8y/lNxnXFt1PaR8Uy1i30T44Nq3n9p44omNjM+o/ran4z3G7/tyQ+N+ynCEXIHhQfC34wnxRdNEVsah/J+Xds8NStsbXzc+LZGxcK5l4yfyoNpWjhRPs6bk3acfp3xT+M1ahcS2FsuNvy5PDkXY7HxA/nzjpI//znjrcYdq2u2kNvkZ+O+VdvG8oTzhRI7HWT8xPiZ8X3jjcad4wumjMvkmaLNuH2BSJ6XZ6A9knMBxxr/Nl6enpggcDx9oC8pEM7dajo1xanya76SZ9o2zBhXGFfLr0M0PG+lXEwBexq/kwcwgRyANh41bhW1/Seiu+KGBYTdjU/KI5TsmDNMFzD+7fJUf1xyLkYw2rOazjTOO3k3faAvbaCG65qqBsbT5Y6HsfMBtSXZ/Ejj18YnqraL5QKMkcuK9O02JdlwoYqITpJeqYPoIyIKg24DqfZgeaGM+AJCPfWCmpGWIhd5k8Kucsd2iTiIqG2qos+PyMdOpghZJgYZjqksZN2rVItou+g6gHh4VyquveS1WQM46Cnjw8Yv5YUT6a7L4JMA/aLYQxyk0G/U7mDEhmHoO0bh/xp5AY2BHpMbY0m4IQNqA2qEoUbfMQkEx6aRH4Px5WpDggB7IcA7NZrREMlA7lfuD/VQG0I9lD4jC5z1lnFRdczLKD7vkztwGmCgq4wHVsdBRO8Yt63aAAK62viD8dCqjRUXhsaQIbp/lBedXWCK4D6iOFe4jhM4NlcPAfpE3ZILCDLGsuo/YvvdeEh1zL3UltgzTJttmSpg1lkZoaC8GKRLpoDDk/YYdAbn9iHCnI1jyCY3qL4H4SAghMTzAsI0N4jaMMD1xp2i8x/Ll9E5BMPiIESYA7bC8On42riDfEuhD/rUQ/SfceQCYqBagGHa4xcgHkSEPUNgdZUGCLKtHpoViAoegqJzoPAiW/XhLcZt/Lb1AuOzTOX9KVMDkm260nIQ0VDdERWu4728Pwc2O9Ox5XiHRrcScuhTD50gz1QPaNT5oR4Ky24yEJkI/5HVB6prnrgeyiFXD7WCBxPhqfGCiNrm3nGCSGE/ZGl6Qr4yw9E4HGC4obrTMoJDeEPlRUR2YZpg9dbLaGPA+uoh+r5a+S2KuB4Kx2Q1guxCNafI5eoOvGDXrqzYAGmXKSIVES/qrcR5BGl3ldqLekREn8iAIBR/Q40KhGlkc/n+0JvqNggrDYzatYk3bmDvXD2EyAfyXeVQ96XATzdFxwQVwfWufGoPmWss9RAPv8d4WNSG4V+VO4j/kwIiflm+qmrDCjXneUCmxFAhVQPEda/x/OoYA5NllqkpEv5fYPzFeKX61y/zDQKG7YdU6PRvH7nTWXnmvhuGRUj8SSjO0jNRexDIvNdDpMfX5Hsy8Xekxrb2GIEAEG1c+7BSCiA6icL4PDvri1R/ymALnzqE5fyLxmNUC4bfk+U7vU+r/l7GivR1uaOmAcZNX9epHtf38i2WtVU7MwRCb8vMZBXqoNgua1QvIFaqLgv4zsVXifha3nVudZ69NAT3a3INdieT99ICKRPDnyWvI6YVlXMFRTtTc1f6ZYxsRjLG4zW6uVZQUFBQUFBQUFBQUFBQ8D/Fv4i7VM8u8d3eAAAAAElFTkSuQmCC>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACIAAAAYCAYAAACfpi8JAAACKElEQVR4Xu2VP0hVYRjGH1HBf5TZoKKShYtTRCgETiJKi0OTEIgt6RBBDQVZEESgiEt/EEVwUzF1ExocbpOimzQ0FohOIkRLieXz3Pf7Ot853KF778npPvDjnvN+3z3n+973+d4DlFRS+qohi+SU/HHoepNcdnM6yH5ivN+Npa7r5DvZIFWJsXLyjKzDFlUWH05Xd2G7fZqI15JZ8hC2oP+uN+Q36Qti7WSNdAWxvHSB3CZt7l67Uk1vIveuLpFd8pW0uFgvWSJN7j5vVZP3sJoekAmyCku9fudI5d/Zpk5yBBuXeZ+QEzIUTspXSu04oofPwxYnKcXHbk4o748psgDbiMr0EdF/89YI6SaDsGMWvrQHttPHQUySP7SQPdgGLpJt8pPcCuYVpNeI11wahb3wThDz/viGyFPSA9jcdyjiuMqcakiqeYWL6Vf3Kpd27eX7RzhXugprYkLXBekaOUS8J/gHzyD+Qu+PZLmUBWVDY8pOLrWSafKWDCCe/azkDz3gpbvXQ1+Rz+SKi/m4zCnfyD9JeU/tIGr3XjfIJ9jx1oK+IMcz5A+dDhnuA+wPSr3vCSrdMvmB6PvxC3ZKGtycMRcLx1+4MWVUPcZnSqXeIo3uPqs6koF9M3T0tBPF0lQz7IT5jqsKrCBe8pz+SFtaSMb9ei/JY/cQZOU+LJXDpN4HU5Z2Ls89J5OwMstrjxAcdbVwT1Et+h8kr/nPha4L7jclnZvOAMhdb/+zZlP0AAAAAElFTkSuQmCC>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIsAAAAYCAYAAADK6w4SAAAE/0lEQVR4Xu2ZW8htUxTH/3LJNdfc65wkhSPkFqHkUnJJCFE8KLeUksjx4FCKvLidSORS4kFJuR8POySXBx7cEp2PRClEhzpHLuPX2OPsueaec+3N+b69z8P81b/2XnOuNeccc8wxx1xLajQajUajscRsYdrXdI7pPNPy4bXG/2C56VLT/qYtTduaDjddNfw9S/YwvW36J9EG05PyvtxjWpeU/WX6xHSYxmEsF5m+ND1lusR0pekj07vycc+DU0w/qDvGn00/Dn8z3pdMB8UNGbuZ1mh079+m0zo1uuwpt1HU/970uunbKfWcaQcNOcG0Xt3O/246KyrMgTPl/XggL5A71KemBdN+3aKN7Cwf5AcadwrK3jR9Ll8g8+Ix05+mE7Pr9OlF0y+mY7OyFBxkrdxZzs/KAiLoTaav5Q56gGmFfAFdrFEwIDj8ZnrNtN3wGnZ63PSMkkh8lOkz0xemj013mPaJwjlxl9xZzs0L5P3FmZ83bZWVAYN8VW6QZVlZgKEx8vV5wYzYSR5BcXqcP2cvuTOnk5dzi9xOTDK/S+Bst8nbYYEQIa4zXZNWMi6T2zt/Dlv3yvQCxn8wvTBn8PaXNVoJOTGwq/MC+Qq4T749nZ6VpfBcnk87s95q4WDTT6o7PLB1Uoe6OdzzsOlU0zfyujk7mlbJ67C4cCzGulrjEbkW5bB1J2ptbs4SEzmQDzgFZ3hC5YHBSfIttW9FQl8bs4CIWXP4AAf4w3RMXiCf7KflWxYRKqJGyuVyG9EGbbG1k+hfoW6Cv6vpQ5W3dQ4EHWfFWV6QN/6VPKm5Xf3GXkpii3hIvh2mOlS+XZbCN6vtWblhWBF9YEQcbqD5OAu5WM3hgYnHAYgIzE8O95HsRxRmspn04ED5lkKSz+KqRWmIfKUvym2EzrwvbwB2lyeGj5q2jkozJPIV8g76kOqNYVlpYKyKBdVDd0qstk7yNiNwzoHKDh/EWGqTjCPE9sAW8p1GyTpzRp7B/zgMlCJPUMtXivDw/EE0Rjg/PrueglfnK78mHHCaSdmUfCUS375JgGiD53CcroFdSDTzsZTE8ZRVPA3T5CsRXUs5VeQrsSCY5DQCsd2wfUDYhAVYYtK2PhV0AGPemBck0Kl85dd0t2kXv62XyCVKK2HSwMIwA/VvLVGPdw9Mco0jND6Omu7X+BG9xqR8hXGyBdeOxJGvcKIC6kROwnhWabQjpPlKib58ZQxWPJVzw4WzTBWaFhEGRbullRADq0WOWLED1Z0FI+JwnJZKx/JZMClfOVL+jgUnLKUBka+k/3kex+GV8rwOcDq22VqUhkmvIToQQjl65c5Co0zarA26qe9X3lO/cS6QG/ZmTbctLjaT3q/sbXpLHlkZTwkWcJrAR4K6xnRtcn3R8xWM/ojpuOQanZzU4aUgEr/aZEdI7dsacTKixq3qOgO/OUr+arpB0+cXi80KedTIHZ4IQp6xIH/zXLM7r/pfUfc4HQueOUvvi4hTitIwaVsvskzu7feq++0ksuulhohG+xvkzoDWyV81b2O6U/7tJMoQkfAQbs7AAGfLJ4RX5vE9iNPeOyrfMwt4/8OERv9xaE4wvKbgm9B6+fcgFm0p4pEu4AypDXCq7eWLjESYNoDkOL4zhdbKP+sA9qRt+pDW4ZvRak2xkPDsk00Xyvf+iTds5jCeo+XjOUNu7Eaj0Wg0Go1Go9FoNP4j/wLHR1RZ6fC85AAAAABJRU5ErkJggg==>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEcAAAAYCAYAAACoaOA9AAACyUlEQVR4Xu2XS6hOURTH//LII6+8kzwieRTCQB5FiAEDE8rECIObAaHuSErGZCSSgSjKSAkDUlIUAyYklzySJIpy5fH/f2uvvn32Pfecb+B+N993/vUbnLX2952z1157rb2BSpUqVeo/rSUfyZ+IbnKTjIvG/a8aT+6QX8jO702wCfnn+w/ydIb8JptSR4toMywwxxL7KHKNfCZLEl9NY8kD0kWmZl0to05YcBSkVIdhvpOpQ5pHPpErZFDiawUNhWXHezIr8UnKprysqmknzKkINqpJZAvZSEYkPpfs8i8lAxNfM6Xd0EVuoee3jib3yQ+yIvHVpHT6SValjhxNhmXYVbKDHCQvybJojAKxjzwmu2Er8iiMmxONa5bWw+ppmhkDyKHgOxCeM/J68wKWDUWaTp6Q02RwsOkPL5DrZFh41gvVDWaHMbLL/xTWPZotryk3YN/uaMEekjXICYxUVm+GwAIhnzraO9Qn7TpPXpEpZAHsaHAK9Rf6AiiIuR8Be4cWR/9RxkQ0vk293qgbrUb2f8ZE43Ll9WZ/6oBN5ChZiN6D6C/34ByBpalS2bWIfCV7IluqxciuahEnyIzar8rl9eYuGZl1lUvZ0Fu9UYachW0LFV8FMZ2gqr+6wEXY6is70q6gBfhOlke2ZsnrTW6bLlLR+UYT1SppYpIfohSkWHthwd0QnrXF4lVS9p1D/9WbTth3b00dZVKL/YaeW0XbQ4F5TWYG2zTynHT4IFh9USGPK72CJZuCLdt22BG9qN70lbwRqByoLDQkpZoKq9819PHqLn7fcLu2Shw0ZY/GXA4o69YhO2ll3HHyljwjl2CZlW7HvpTuhLobdiN7n9ICDY/G/XN5Vymt9EHalspOZWlbayWsW00Iz8o6ZZ9OoDqJtq10LNfx/AOZC9tqu8gXsq0+rH2le9Q9cht2dVCXUqAqVarUvvoLYwmhi/gcypEAAAAASUVORK5CYII=>

[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAYCAYAAAB0kZQKAAABz0lEQVR4Xu2VSytFURTHl6QozxQTAwMGkiQhRpJXycBrQhkYIDPkmYmBEUoyYiADEzPlA9woE+VDGBImKMrj/797b3fffR73usrE+dWv7tnrnH3X3mufdUQi/hk5sBYOw3aYq8ezYBXM1tceiuAhrLPGePM4PIPbsMKK+VEId+EbjMF1uAGvYR9chDvmZhdmuAKfYaM1Pgrb9O88uAzLEuEkOuAdPBVvsqXwEn7CQSf2TQt8kOQkuIWrMN/cBHphp3Vt4MRc/b6oUvgxBe9hjRsgLMOBqAnsJLg7c6JWYRiA9dY1Ye25A+ei5gqiH17AAjdg/mgILom3HNVwT49NwElRzxi46hP4ISHbrGESPC8emkUdOE7mlwRhrBwWO+OkFb7CK1jixFxYXru0cbh1LEGlvg5KIgw+w8Pmu8JUcEtn4Yg1lkkSR6KSGHMD6dAgiTIYfpME6x0GD/O8OzgNbxyfRE14K+oUB/UDGzaiVElw19dglxvwI5OdaIfvot4g+62xYQ/akuD+kQQb0wtscgMhcGIe7kfxNjEm1QOPJbx/xOHDLAG3lXJlbLHplIOwnW+Kei4GZ0R9I1jSBR3/M7jablFfTvYf8+WMiIj4EV9pPlP1pI5K4wAAAABJRU5ErkJggg==>

[image6]: <data:image/png;base64,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>

[image7]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAYCAYAAACMcW/9AAACoUlEQVR4Xu2WS6hNURjHP6HIu+tRHrlJiRTlMVAmXpmQPCKUgWKiKOWdlAyQ8khJCUl3cJMJGTA4MRETA48BYqAUSYmBgcf/d769zl57nb3vdU0M7H/96qy1vn32//vWa5vVqvXP1SGWiVWiU/SL+sdkv1saLDaKi+KYmFgcbmqaOGEeQyzPxOoU58UtsUb0L4wWhZlF4oX4IC6J3eKGuC5miftiengA0Xgi9psbXCceibFRDC9+LmaLoeKouCtGZOPE7rPc/ALzZMo0RFwWX81j0oQ2ix/igRgWOnnBU3OTZMmf3BPfxJwsZpJ4KTZlbTRKPBY7svYSsTwfbiZzQAyK+hCJ3RGfxfxkLGi0eCbOxp17xScrlnixFauDwdg4IimmqGFuijGqHsT62hm1Ec+cFj/F+mQsFv/XEKtDB9k9NK8MfwxUOJ0KMkuNoqvivZgiBohdYqt53EkxOQ9taqH4bnlyVWKs26Li8YNqYpZNcFCcMy87azEIQ1VG0/6RYpwYGPUhEukSv6y4hMpE5VlarYLxAl7EVIQyE3TcfDeyscI0pIZQmdEqTRBvrX2Z/ZGCUSrIAg5aYZ75divfXEF9MRrexTKjWn0SZ9UXa18zwShGUJWhqv4yBaMN63l9MqOHxdS4k7X02tofTo1yAZQZYvydlV8OqdhwbLyG9WwUgxcsuUzCAk+nI556tNL8AOasDOJ8vJ2RnpVlIuam+fk5MxkLYgOesorzdan4aHm10s2EOsxvqiNZG5E51dwQ9fUmDGD0mvnajzXc/GpunZ2pyOKQeCO2mR9PGJgbB2VtYvaIteazQELpMdSb5olX5vf7GbFFXDG/jmfkYdXimuTrha+YNNsg+sNXDvF/K85HjigSZpmNt/yLqVatWv+9fgNus4PYIWGU6QAAAABJRU5ErkJggg==>

[image8]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAAAYCAYAAABKtPtEAAADjUlEQVR4Xu2WS6hNURjHP6HIO/IIcXUlIeRRJCMDBkpSiBFJifIqwgAlEYoieV5JSDEhoRATjwkGUlKUMsIEAyX+v7v2d/Y66+5zr3udM9A9v/p3zt5r7fX4XmuZ1anTXnpLg6WuaUMEbX3Sl1Wmi9QrfVlrFkuPpR3SdWloeXMzbH67tDltqDITpb0WDFFVRkvL0pdipPRCmpM9r5S+SLulsdIwab50V7pjIVJqyU4L81WF8dI66b70S7pQ3tzMAumDNCJ7HiMdkRqkJdIKaZGFyJia9akV/aRz0qC0oaNgABY/W/poxQbYZsEAeBr4pV/s6bVW+9CHeRYir+qwKTZZZADyPzYAkXBS6pE9T5AuWu1Dn5w/KM1KG6pBawYYJ72RZmTP5N+m7H9PqcnaDn3qCKk0MHlPNe+e/e8rzbUwZhFDpPMW0iCG7/lumpWfUPGJhPEmS415czmtGYCPt0iPpFXSTcvrAWHfVugTQYx7QHppuRGGS+8t//6Y9NtCTSmCAk29isEYl6St0mtpddRG6r6zYDhS/bP0XBoQ9SnRmgEcrLfQgqcAr1+xPPSJFEJ0ueVeZbNnsl+OUOqMG498/pn9wkzpqxUboJt03MIRGIND6M+YjM0cQHreysR/1nPK/tEAMWyazXvos/in2fMaaaOFyJluwSB46ol02cJmYJ+VG4T+hLgbJIaT57TldQcYBy9zOSM6flheH+j/yXKDACnM/PEYJdprgDj0WQgDsyEghymShLjDwlig3zNSD/k7vBx/53DKFEUG+PwY2OtDGl3+zmtXC9pjgDT0yTFyDW84GywUJYc2PIJnIA1ZaJCOWh4hDgYljWgvwmuJOwDSdANuqX6Za8HfGiANffBvYwOst/LjinG5SntVxjjfLdQUZ2mmFPpiGFKkCB+LYusw30PLnURkUGTTE6SEb4KKWmkiIOwJxxg2xebcAHx/yELldZg8LkBcp+OKT5E8kf2mtHX19Qofj/XMyuejrTCFyAtChWswC0LfpFfSpKgf4PUmKz6n2fwNC9W20UINiPuNsnAEYqhrFnL9sIW5z1o4WqeUeufgMQojaVYJDM4xjRHw/AMLhfitdFu6Ku2x/GTqEF6g2FwRbJZzng3es+LNsFC8gzzKCFE2V2lx5Oyu9GUFWCOR7EWVixAnRP9Sj/+Q/Vajq+//QKWrb6eBwpcW3E4FVTs+SerUqSJ/AN/joiqj7YjRAAAAAElFTkSuQmCC>

[image9]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADoAAAAVCAYAAAAXQf3LAAADaklEQVR4Xu2XS4iOURjHH7lEbrlkiDJkI3LJ/ZZZSCxYoCjKwoKFKELJYiQLKQk1JYWEkrIQC1mMbBQbRYrUjESSrMgll+c3z/fMnPd5z/vNZGXx/euX+c4577k857kcIg011FDQYGWhsklpqf3ui8Yoq6X4zQRlpA/IaKAyQ2wtvs2OHas8VP4k/FBWJWMGKdfDmINJf6pJykXlhbJHbPEzyqfa7/49QwsaKvbdE2WHclh5qrQqD8T2GTVCOam8Vo6IrcW/rEX7kJ6hPVondoDLsaMmNnhNbANYMKe1ygdlr5QPtFH5qewP7WiYck85JsW5pynvxAzQL2lHc5RXyikpHwhP+qy0KQNCn8xTvig3JdOpWqRckfKkrg3KN7GbjptCuOEdsZtuCn1blOeZdua5quwM7fOVj8p5qTY6XsRhZ8aOqcp7pV3Mwqk43CVlbmh3ER8sfFuqDYGOK7+lGBYYFeMSPsOTdtdZsUtwjVOe1eDvKm0V89BopC5r4uudYsGfaptyVPI3hUVviB1gTeiL4qAsTpi4MGq78kvZLOU1ZkmP8ejDvZljd/eIvPygh2KHL0ggT0/am5VbUm29Jcp35bEyKvSl8puLB0WttXZPhIwjsUTvmKK8FfM8PLCe3Kilg/pGvioLam1Y8ISy3gdlxERMSEzUE1mTOEznd1EOiMU0q8NdKYYR+6CdWK9XrjwfMJbcUdIFKVp8hXJOqgMekaWzsRBEXOLej6Sizomts1gsyXCzMZ77alQ8Es/k9vGCknyifWKboXaS4uvJDxrdMRXe4kbclbTjmpOT36mIwTiv76/kjkE+7rSUY75LXDMD8G8O29stIawbNxRFaaJ0UStTV1wuVuBzYj7qLmNc7Ke3gzaLJVXKGI+XrNy9GETNjGUmJ2qgGycnPOO+8lLKt8eGc27o2bVdinvwxFdV63F93J76yaOhUv5oAG6hL2Ij3BRWbC52yXixQ5KRm4td3ckv991SMcPEzfJNm+T350/IDiknu5Kon51i1sz6doVGi9VSLInLUxqID5LBASmXCTRRzECM7xB7kGwXi3my80ofGMRcvGPJ3niRv2/fiHkH79+o2bGBq18mZp1/UZNYbLE4r6V62RrjcFhEOWgR+47nXb3vXIQE/1PhG26+XrmpCquGGvrf9RcAKby0/1sN1AAAAABJRU5ErkJggg==>

[image10]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACoAAAAYCAYAAACMcW/9AAACfUlEQVR4Xu2WzYvNYRTHv0KR97zlLTfZkAkJUbORpKTkpSmjJBvNBjMLLwv/gOS9xIiSlJdslIWFG8VCWZlsKCOlFDZoZjH4fuf8nubcc+9vfu5YKP2+9an7e87ze37nOec857lAqVL/XNPJJrKNVMgoNz4z+12nKeQaaQnju8h6MhG20Cyyh6xwcyrkInlAdpDRzhalNTaQ1+QTuUq6yD1ykywnT8iS9IKXXj5GvpNVbnwMuU1+Be7ANibJ8aNkfPasTe3OfkdNgAXjG2xO3JACMECekknBNqi15AvqHZW6ySvyntwlW1D7gY1ks3tW5I+TcW5M0sYekq9kTbAlzSA95Fw0SFrgCrmMxo6ebzDmJZvSnaT6OuieJWXsDPlJ2oLNS5usku1hfHCBTtiHjmBkjqo8DpH9sHknycKaGUAr6Yc5IWfyJJvKqq4+lYJTZCzyHb1ATpOX5AN5TlbWzDBNJbNha3lpI7dgtd0ebFEK3DSE2lXKle5K9pznqIpfBy29rIJXPefVWdQ88o58RoNIFUmeH4a1nqQ8R3X6/A7nwyKrKClaRdJ6WvcFLFpNSalLKU/KczRqDuklb2GpLlJytIrh61PBO0EW+8EDsHbjUW9THakJq4+pP+6DnVTNT0qOCv0u0iLyEcWOysFLGOrHuWoUUY3Jee9oSn0Vw384Sf30Pqx/Lgu2JGVWGf6juleT/kFWu7F1sFPvS0R9sA+1vbNIckCO3oDdTl6TYYe6rndG6WZRutP1qCvsGSz1qpsu8hjWJ3Vj6PR2ZLZmpAC8gX3rLNlLrpNHZOnQtL/TAtg/HP3TSXf8SKTuoRa1k2wlc9H8hkuVKvXf6jf8Ine1EQHLLAAAAABJRU5ErkJggg==>

[image11]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADgAAAAYCAYAAACvKj4oAAADHklEQVR4Xu2XS6hOURiGP6Hcb0ck5BoZCLmVTOQyIeRSIhlIGUihiAmSgduAMnCpk0QGIgMSBqcUYiqK5E+iFEoYkMv7+PY6/zrrrE3nOANlv/Xk7G+tf+313dbazCpV+m/VSTSIfunAv6C+olFMTAek8eKgOClWi+4th3/pgPgifoityViqHuK8+GY+H/j7lnmA1ot30Ri8EvP4cXtE5HeKT2JqMrZcPBKTRS+xT9w0D0iqZeKrmJ0OlGiS+CCuim7JGM/Yc3tqs2aaRyxdbLh4KtZEtv7igdgU2YKOiZoYmtjLxLpkZ0c6YL5GzfxdvLPdIhOnzMsvdZANpDayfU40mWc0qLe4bflslImAlGUcG2PMabfYLP1CGRLF1BkWT23ojHgtRke2CeKt1bPB2uPEfMv3bKiEmuUzzjpkN66eoJ5irhhSPHc1b6EuzTMKzRBHzCfkHMSR1FZmZyPfzQ8C1tsrDokrlj90QkCumbcCmw2MMO9zxpkXi0Pwhbnz78UisVZsjichSpOyHFk8pw5Sfk2JLSjnYOi/MWK3eURxrOxUDf1313wfMZfNg5X2Hxk6bu4UgSCYN8x/Q1CbRflsESsjW+ogZcCxnTqCUgdDuT0UJ6wedUqU97BWqo7ov1niqGXWn2L10gxKHUSpI2X2UG4c+TXz8uxTjOUUAvJMDE7G0O/6L4jscTfn+ts2mtdxzEfzRd+Yn4aDxH4rd/ClGFY8x/ffWPHEvMzKTtNw/1201gcDz9hz/YeovhXmQWxRln9SLoOLzb8w4i+IcAFDcCC9/whA6J+FYl1hD2rv/YdztNU20TmybxBLouesdonPYnpkaxD3xZ7IRobI3qriORxGcTZwkGfK57AYVdgRm2y08v4jmBwwp9MB8+uMz0GcJ4NkkuDeM6+4rFiQsgzffGTsjtV/ME08F9vNF2RxvjtDeXCk850Yf9mwEYJwqbDjFAfBBau3ArDZ62KA+VEf7wO4a+eYi8CeLeZSuo+LOfybK+U2ic0tEEvN76xYbJ5SiksGkdmO/F8F7RD3NAEeaK3fW6lSpUqV/ko/AQCTyDq2w8J3AAAAAElFTkSuQmCC>