# tipping_point-netlogo-

This code calculates the share of agents that end-up doing an activity for a given distribution of tipping points in the population.

Before starting a simulation, set the distribution of tipping points (in the code from line 21 to 25) 

As usual, in netlogo specify the set-up button and the infinite go button in the interface page.
In my interface page I set up three main sliders: revision_prob (from 0 to 1with 0.01 increments), prob_mist (from 0 to 1 with 0.01 increments) and rad-dim (from 0 to 20 with 1 increment).

The code generates a turtle for each patch such that the number of tutles depends on the world dimension.
Each turtle senses the neighbors in a radius of "rad-dim" dimension.
Each turtle decides which strategy to take based on her tipping point and on what her neighbors are doing. 
