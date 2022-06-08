# simulation-of-heterogeneous-catalysis
The simplest mechanism of the model reaction of heterogeneous oxidation of carbon monoxide
on platinum group metals includes three stages:
1. CO(g) + z = CO(ads)
2. O2(g) + 2z = 2O(ads)
3. CO(ads) + O(ads) = CO2(ads) + 2z
The space-time distribution of particles on the surface can be modeled using the following lattice model:
1. We choose a random lattice node and a random number in the interval (0,1) . If node is free and the random number does not exceed p CO , we adsorb the CO molecule (stage 1).
2. If the node is free, the random number exceeds p CO and is also free randomly selected neighboring site, we dissociatively adsorb an oxygen molecule (stage 2).
3. If the site is occupied by a CO molecule and a randomly chosen neighboring site is occupied by an O atom, particles react with instantaneous desorption of CO 2 into the gas phase (stage 3).
4. If the site is occupied by an O atom and a randomly selected neighboring site is occupied by a CO molecule, particles react with instantaneous desorption of CO 2 into the gas phase (stage 4)
