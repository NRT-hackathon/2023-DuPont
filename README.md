# 2023-DuPont

Code is run in Jupyter notebook, with descriptions there. Below is the use for each file in this repository:

"Forward Model.ipynb" 
  Three methods to create a forward model (linear regression, Quadratic Scheffe model, and Gaussian process regression). This models are compared with kFold validation, leave one out, and a held out testing dataset.
  
"Particle Swarm Optimization.ipynb"
  This code remakes a Gaussian process regression model with all training data and uses this model for inverse design. The particle swarm optimizer is implemented with one repition for both the case with random initialization and known formulation initialization.
    
"Dual Annealing.ipynb"
  This code remakes a Gaussian process regression model with all training data and uses this model for inverse design. The dual annealing optimizer is implemented with one repition for both the case with random initialization and known formulation initialization.
    
"PSO_Iterations.ipynb"
  10 repetitions of particle swarm optimization to observe reproducibility.
  
"DA_Iterations.ipynb"
  10 repetitions of dual annealing optimization to observe reproducibility.
  
"DATA"
  This fold contains all the data from DuPont experiments. THis includes a training dataset and a testing dataset.
  
"ANALYSIS"
  This folder contains numerical results from our analyses such as metrics of kFold validation, leave one out validation, and inverse design cost function.
  
"FIGURES"
  This folder contains the figures as created in the scripts above.
