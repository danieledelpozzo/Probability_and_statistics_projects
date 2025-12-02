# Probability & Statistics projects
A collection of university projects demonstrating applied probability, statistical modeling, simulations, and data analysis.



# Project 1 – Pseudo-Random Number Generators & Watts–Strogatz Model

This project was completed for the Probability and Statistics course at USI.
It explores pseudo-random number generation, Bernoulli trials, random adjacency matrices, and the Watts–Strogatz small-world model.


📌 Contents of the Notebook

1. Linear Congruential Generator (LCG)
	•	Implementation of LCG with different configurations
	•	Comparison of periodicity and distribution
	•	Histograms of generated values

2. Middle-Square Method
	•	Classic MSM implementation
	•	Demonstration of rapid cycle collapse
	•	Visualization of output distributions

3. Bernoulli Variable Simulation
	•	Generation of uniform random variables using LCG
	•	Transformation into Bernoulli(p) variables
	•	Construction of a symmetric 100×100 adjacency matrix

4. Random Graph Construction
	•	Building a graph in igraph from the adjacency matrix
	•	Analysis of connectivity and structure

5. Watts–Strogatz Model
	•	Generation of a small-world network
	•	Exploration of clustering and path length





# Project 2 - Knight’s Movement Markov Chain – Stationary Distribution & Return Times

This project models the movement of a knight on a standard 8×8 chessboard using a Markov Chain.
It was developed as part of the Probability and Statistics course at USI.

The notebook constructs adjacency, degree, transition, empirical distribution, and return-time matrices, and simulates random knight walks to approximate the stationary distribution.


📌 Contents of the Notebook

	•	Model knight moves as transitions in a Markov Chain
	•	Construct matrices that characterize the chain:
	•	Adjacency matrix (A)
	•	Degree matrix (D)
	•	Degree vector (d)
	•	Transition matrix (P)
	•	Move-count matrix (C)
	•	Simulate a long random walk to approximate the:
	•	Stationary distribution (S)
	•	Average return times (R)

