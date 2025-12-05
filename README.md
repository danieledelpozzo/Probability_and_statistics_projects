# Probability & Statistics projects
A collection of university projects demonstrating applied probability, statistical modeling, simulations, and data analysis.



# Project 1 – Pseudo-Random Number Generators & Watts–Strogatz Model

This project explores pseudo-random number generation, Bernoulli trials, random adjacency matrices, and the Watts–Strogatz small-world model.



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





📌 Contents of the Notebook

1. Knight Movement Model
	•	Representation of the chessboard as an 8×8 grid
	•	Definition of all legal knight moves
	•	Computation of the number of legal moves per square (Matrix C)

2. Adjacency Matrix Construction
	•	Creation of the 64×64 adjacency matrix (A)
	•	Encoding legal knight moves as directed edges
	•	Mapping chessboard coordinates to matrix indices

3. Degree and Transition Matrices
	•	Construction of the degree matrix (D) and degree vector (d)
	•	Definition of the transition matrix (P) with uniform move probabilities
	•	Verification of row-stochastic properties and connectivity

4. Random Walk Simulation
	•	Execution of a 100,000-step knight random walk
	•	Tracking visit counts to each square
	•	Normalization to obtain the empirical stationary distribution (S)

5. Stationary Distribution & Return Times
	•	Interpretation of S as the long-run occupation frequency
	•	Calculation of average return times (R) using reciprocity
	•	Comparison between board regions (corners, edges, center)





# Project 3 - Housing Price Prediction with Bootstrap Regression

This project focuses on predicting housing prices using a real dataset. It covers exploratory data analysis, train-test splitting, and statistical modeling using a bootstrap procedure to assess model variability and coefficient stability.


📌 Contents of the Notebook

1. Dataset Import & Preparation
	•	Loading the Boston Housing dataset from CSV
	•	Extracting predictors (X) and target variable (medv)
	•	Setting a deterministic random seed based on a student ID
	•	Splitting the dataset into 90% training and 10% test subsets

2. Exploratory Data Analysis (EDA)
	•	Scatterplot analysis of the relationship between average number of rooms (rm) and housing prices (medv)
	•	Preliminary inspection of dataset structure and descriptive patterns
	•	Identification of correlations useful for regression modeling

3. Train–Test Split Procedure
	•	Manual index-based sampling for the 90–10 split
	•	Verification of subset sizes and distribution of samples
	•	Alternative split using train_test_split() from scikit-learn

4. Bootstrap Estimation of Regression Coefficients
	•	Implementation of a bootstrap resampling procedure (1,000 iterations)
	•	Resampling of the training dataset with replacement
	•	Fitting linear regression models using statsmodels OLS
	•	Storage and aggregation of bootstrap-derived coefficient estimates

5. Model Interpretation & Stability Analysis
	•	Assessment of coefficient variability across bootstrap samples
	•	Evaluation of model robustness and sensitivity to sampling variation
	•	Preparation for confidence interval estimation (if extended)



# Project 4 — Diabetes Prediction Model with Logistic Regression and Neural Networks

This project focuses on predicting diabetes outcomes using clinical data. It combines classical logistic regression with a simple neural network model, including exploratory data analysis, dataset splitting, and model evaluation.

📌 Contents of the Notebook

1. Exploratory Analysis
	•	Importing and inspecting the dataset (diabetes.csv)
	•	Visualization of feature relationships using pair plots
	•	Identifying trends and patterns in predictors and the outcome

2. Data Preparation
	•	Splitting the dataset into training (90%) and test (10%) sets
	•	Ensuring reproducibility using student-specific random seed
	•	Defining predictors (X) and target variable (Outcome)

3. Logistic Regression Model
	•	Fitting a logistic regression model to predict diabetes outcomes
	•	Evaluating model performance and coefficients
	•	Comparing results with baseline expectations

4. Neural Network Model
	•	Defining a simple feed-forward neural network for binary classification
	•	Using sigmoid activation and binary cross-entropy loss
	•	Compiling with the Adam optimizer
	•	Training the network on the prepared dataset

5. Model Interpretation
	•	Comparing predictions from logistic regression and neural network
	•	Assessing model accuracy and suitability for clinical data
	•	Visualizing results to support insights and conclusions


