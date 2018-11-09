# AI_Project 2018 : (Genetic Algorithm using Java)

In this project we provide an optimal solution for the Multiprocessor scheduling problem (MPSP). which means that for a given set of N jobs each with an associated completion time, and two identical processors, we divide the set of jobs into two subset such that the difference between their sums of processing time is minimum.

We are going to consider the Multiprocessor Scheduling Problem (MPSP) as an optimization problem, therefore the searching algorithm we choose to implement is the Genetic algorithm, it’s a local search algorithm with the objective function that we specified in Phase 1 that we now call the fitness function: F(n) = ∑S1 -∑S2.

In our program we have three classes: the main class, the gene class, and the population class.
The gene class which contains the array of gene, constructer, and the function that calculate the fitness of a gene. 
The population class contains a set of functions that calculate the most optimal gene, the second most optimal gene, and the least optimal index, also a function that calculate the fitness for each gene. 
The main class (Genetic Algorithm) contains three objects, an array list of jobs, and five other functions.


...One of my favourite projects!
