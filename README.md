# multiobjectiveDataIJOC

***********************************************************
DATA AND RESULTS
***********************************************************

Network Models for Multiobjective Discrete Optimization
D. Bergman, M. Bodur, C. Cardonha, A.A. Cire
IJOC, 2020
***********************************************************


results\
:: Results for each problem class are in a separate text file
:: Time limit was set to 3,600s and memory limit to 16GB
:: Note: Aira refers to Ozlen et al. (2014) in the paper 


data\
:: Organized per objective and problem type
:: Each method has a different input based on the source code provided by the authors
   -- Two instances are the same when they have the same prefix prior to the last dash ("-")
   -- The format of each instance is based on the suffix after the last dash ("-") 
      -- Kirlik: "-kirlik.lp"
      -- Aira: "-aira.lp"
      -- tamby: "-tamby.dat"
      -- BDD: "-bdd.dat"
   -- For the input format, we refer to Kirlik's LP used in all problem classes, where:
      -  The "p" constraints refer to each objective function
      -  The "c" constraints refer to each problem constraint
:: The parameters of each instance are specified in the instance name prefix
