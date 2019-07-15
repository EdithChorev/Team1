# Rossman Store 

Welcome to Team One's Rossman Store Sales Model! This Repo allows you to take raw Rossman's sales data and output accurate
sales predictions for any given Rossman Store on any given day. Magic!

This Repo is split into two parts. Data Cleaning and Feature Engineering, where you will prepare your dataset for the 
models. And Model Execution, where you will estimate store sales using an ensemble of the following models:

* Random Forest
* Multivariate Regression
* Gradient Boosted Trees

So what are you waiting for? Clone this repositary to your local machine and then follow the steps below to output
sales predictions for Rossman Stores.


# Data Cleaning and Feature Engineering

In order to produce a cleaned dataset for execution, we must combine and clean the following files:

* A .csv file with characteristics of each Rossman store, this file is called: store.csv
* A .csv file with daily sales and activity data for each Rossman store, this file is called: test_set.csv

This step is executed in the Jupyter Notebook titled 'Rossman Dataset | Cleaning and Feature Engineering'. The specific
assumptions made, and engineering decisions executed are outlined throughout the notebook.

Once you've cloned this repo, simply open this Notebook and follow the instructions - ensure that you execute each cell 
in a linear order i.e. from the top of the notebook down.

You will finish this step with a cleaned dataset ready for model execution.


# Model Execution
