# BayesFinal
Bayesian final repository for all model code
Final Project for Bayesian Machine Learning

Using Bayesian methods to predict the exact moment at which a tackle occurs, based on defense players distance to ball carrier, momentum, force, defensive distance to ball, TME, and total energy. We conjectured a priori that defensive coordinators would be able to make more informed decisions about which play to call in a given situation by incorporating certain mechanics based  player attributes into the decision making process.

Code Instructions

To run the code for this assignment, use the jupyter notebooks attached in this repository. Notebook files will show data preprocessing, cleaning, creating of feature engineered variables, modeling, and model evaluation. 

In order for the code to work, you will need to download this dataset from Kaggle: 

- players.csv
- plays.csv
- tackles.csv
- tracking_week_1.csv

As well as our data set that includes the created feature variables which can be found in the repository: 

- merged4.csv

Additionally, here is the list of libraries and versions that you will need to have installed for the code to function properly:

- arviz
- matplotlib
- sklearn
- numpy
- pymc
- pymc_bart 
- scipy 
- pandas
- seaborn
