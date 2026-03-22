16/03/2026, 04:00

Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation exchange membrane | Chemisting

Chemisting

Home research by a solo chemist

Nafion equivalent permselectivity values using a DIY
PVA/Cellulose cation exchange membrane

During the past couple of weeks I have been working on cation exchange membranes using PVA/cellulose (see

here, here, here). The idea is to create a membrane that can replace Nafion in a pH neutral flow battery built

using an Fe anolyte and a Mn based catholyte. In this post I will share the first results that are up to par with

those of a Nafion membrane.

My initial idea was to both crosslink and add anionic sites to the PVA by using phosphoric acid with urea as a

catalyst, heating the membrane to >150C in order to perform the esterification process. This worked to a de-

cent degree, achieving membranes with permselectivity values above 80% with sheet resistance values around

10x those of Nafion membranes.

Membranes annealed at 150C (left) and 100C (right)

However there were some obvious issues with this process. The first is that the membranes produced had

some stability issues, their permselectivity would drop with time – due to lack of enough crosslinking – and the

https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-exchange-membrane/

1/5

16/03/2026, 04:00

Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation exchange membrane | Chemisting

mechanical stability of the membranes also left a lot to be desired. Both of these issues were likely due to lim-

ited crosslinking of the membranes, as forming a double phosphoric acid ester is not a very favorable process,

even in the presence of urea.

I would see Fe-EDDHA  leak across the membrane within around 24 hours of setting up my cells, with the

-1

transparent side turning a slight pink within that timeframe. The permselectivity would also drop from 80% to

around 40% within that timeframe. It was obvious that these membranes had components that were still dis-

solving or at least creating cavities that allowed too much water to flow through.

Thinking about this, I searched for possible crosslinking agents to enhance the issue. I also wanted to avoid us-

age of anything toxic, like glutaraldehyde, as the space where I carry out these experiments has limited ventila-

tion, plus I want to avoid exposing myself or my cats to harmful substances. Expensive substances were also

out of the question, like sulfosuccinic acid.

Multiple results of membranes being prepared using this method (each one is around the

diameter of a 25c US coin)

Reviewing papers on the subject, citric acid appeared to be a viable substance. It is a tricarboxylic acid, so it

would be able to crosslink cellulose with PVA, PVA or cellulose with themselves and also keep some exposed an-

ionic carboxylic groups to provide cation exchange capacity. Adding phosphoric acid would also catalyze the es-

terification reaction plus also provide some phosphorylated sites for enhanced permselectivity.

The process for preparing these membranes is as follows:

1. Prepare a solution by adding 15g of PVA to 200mL of water (solution A).

2. Place solution A in a fridge for 48 hours, with occasional stirring/shaking. Surprisingly, cold conditions are

much better for dissolving PVA because they discourage agglomeration.

https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-exchange-membrane/

2/5

16/03/2026, 04:00

Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation exchange membrane | Chemisting

3. Wait till solution A is fully homogeneous, keep longer in fridge and shake/stir as needed.

4. Prepare another solution by using 0.5mL of phosphoric acid (81%), 0.5g of citric acid and 15mL of solution

A. This solution is stirred until everything is completely homogeneous (solution B).

5. Dip a filter paper in Solution B. I used Stony Lab 101 but other fine grain filter papers should work just as

well. Make sure all excess has dripped off and tap with paper towels to remove any excess.

6. Place on a hot plate at 80C for 3min

7. Flip it to the other side for another 3 minute.

8. Use a brush to paint solution B on the filter paper while on the hot place.

9. Wait for 3 minutes.

10. Flip the filter paper and paint the other side, wait another 3 minutes.

11. Repeat steps 8-10 three times.

12. Increase the temperature to 150C.

13. Flip the membrane every 10 minutes for one hour or until the membranes appear fully black. Put a petri

dish on top if needed to keep the membrane flat.

14. Allow the membrane to cool to room temperature.

15. Place the membrane in a solution with 10g/L of potassium or sodium carbonate to neutralize any remain-

ing acid, they can be stored in a 0.5M NaCl solution.

The membranes that result from this process are black in nature. However they do not feel like charcoal and do

not crumb easily. Instead, they have the feeling of a piece of plastic film, which is exactly what we are looking

for. Several papers discussing citric acid crosslinking of different polymers do have resulting black films, so this

isn’t necessarily a bad thing.

I was also very pleasantly surprised by the permselectivity measurement for these membranes. Measuring the

potential across NaCl 0.1M | NaCl 0.5M using identical Ag/AgCl reference electrodes, the potential is 38-39mV,

meaning that these membranes have permselectivity values >99%, which is equivalent to that of the best

Nafion membranes. Adding 0.01g of NaFeEDDHA to the NaCl 0.5M side – which makes it dark red – I could see

absolutely no crossover of FeEDDHA  to the other side of the half-cell experiment within 48 hours of testing.

-1

There were also no drops in the permselectivity which remains extremely high. The sheet resistance measure-

ments are also very favorable, with in place sheet conductivity values now in the <50 ohm/cm  range.

2

Overall, I am pleased with this DIY membrane result. The crosslinking of PVA using citric acid and phosphoric

acid on a cellulose matrix provides you with a very robust membrane that has some wonderful characteristics.

This will be my base membrane for the construction of Fe-Mn flow batteries. This membrane is also very low

cost.

This entry was posted in Uncategorized and tagged CEM, citrc acid, DIY, PVA on December 15, 2022

[https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-

exchange-membrane/] .

https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-exchange-membrane/

3/5

16/03/2026, 04:00

Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation exchange membrane | Chemisting

6 thoughts on “Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation

exchange membrane”

Rahul Nana
May 11, 2023 at 5:33 pm

Hi,

Will this membrane work as a good cation membrane for reverse electrodialysis? I’m looking for high selectivity

and low resistance. Also do you have a good method/chemistry for an anion exchange membrane as well?

Silviu
May 31, 2023 at 4:09 am

I had a couple of ideas on potential ways to improve this.

1. use a regenerated cellulose substrate (cellophane). You may be able with this to make the membrane thinner

and yet more mechanically resistent.

2. use paraformaldehyde as a crosslinking agent. It is cheap, easily accessible and relatively safe – certainly

safer than glutaraldehyde.

danielfp
June 2, 2023 at 8:10 am

Post author

Thanks for posting!

1. Good idea on the cellophane, I will give it a shot.

2. Sadly too toxic still, I don’t want any aldehydes in my house (they are all very reactive and nasty in my

experience).

Silviu
June 2, 2023 at 7:13 pm

https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-exchange-membrane/

4/5

16/03/2026, 04:00

Nafion equivalent permselectivity values using a DIY PVA/Cellulose cation exchange membrane | Chemisting

I don’t know if you came across this paper but I found it interesting. They claim to have made a ion exchange

membrane equivalent to Nafion 117 made only from phosphorylated PVAl, without any cellulose or other sub-

strate.

https://www.researchgate.net/publication/257225463_Phosphorylated_polyvinyl_alcohol_membranes_for_redo

x_Fe3H2_flow_cells

They started with fairly diluted solutions which they cured in vacuum for 3 days at 40C. May be an interesting

avenue to explore, vacuum chambers are not that expensive. In fact it’s not even clearly stated in the paper that

the whole curing was done in vacuum, only that they degassed it in vacuum and cured at 40C for 3 days (I as-

sume though that since the starting solutions were so diluted and they ended up with a hard mass, they must

have maintained the vacuum for the duration; my experience with PVA is that it retains water fairly well and

would not get to a completely solid state in 3 days based on an experiment I’m running right now)

Pingback: An improved DIY cation exchange membrane with less degradation using a Daramic PE microporous

separator as base | Chemisting

Obiora Chukwuemeka Ejimofor
January 14, 2024 at 5:12 am

I have been following your work which is quite impressive. I was thinking starting a home hubby research on

Iron flow battery. I would like to try your membranes and that of aldehydes. Thanks for sharing

https://chemisting.com/2022/12/15/nafion-equivalent-permselectivity-values-using-a-diy-pva-cellulose-cation-exchange-membrane/

5/5

