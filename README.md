In this part a Metropolis-Hasting algorithm was simulated to generate random numbers for the 
given distribution using R and Python. In the beginning the simulation was run for a standard 
deviation of 1 and 10000 Monte Carlo steps. Here, loops were executed from 1 to 10000 to 
generate 10000 samples including the 1st one. The mean of the sample was 0.10746 and the 
standard deviation of the sample was 1.37297 as in figure 01. 

The program was then updated to generate more than one random number sequence. The newly 
given functions were defined and they were used to calculate the Ȓ value, which gives us an idea 
about the convergence of the solution. The simulation was run for standard deviation of 0.001 
and 2000 Monte Carlo steps. Ȓ was calculated as 2.772. Which means the solutions of the 
simulator does not converge. But when the standard deviation was increased to 1, the Ȓ value 
came to 1, which means the algorithm converges as in following figure.
