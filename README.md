The "Functions" archive contains the functions and libraries that corresponds:
 - creating the geometry of the cavity consisting in 5 regions
 - Generating random points within each region
 - Genertaing a grid of points within each region
 - Generating a random direction for each point, which represents a gamma ray
 - Generating a grid of angles (solid angle) for each point, where every direction represents a gamma ray
 - Detection function, which counts if the gamma ray hits the detection zone
The idea is to compare the amount of detected rays against the total number of emitted rays. To corrborate the results
the probability by using a grid and random points should converge to the same value.
Finally, it is important to determine how the geometrical factors influence the probability of detection (maximization)

To be developed:
***************************
beta decay: emission of 2 gamma rays in opposite directions
***************************
- Function for Beta decay. Determine the probability of detect in both sides 2 gamma rays that come from a beta-decay
The Analysis is performed in the archive "Cavity Simulation"
