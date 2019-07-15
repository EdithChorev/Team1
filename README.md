# How many sales will a Rossman Store have on any given day?

Welcome to Team One's Rossman Store Sales Model! This Repo allows you to take Rossman Store data and output accurate
sales predictions for any given Rossman Store on any given day. Magic!

This Repo is split in two parts. Data Cleaning and Feature Engineering, where you will prepare your data for predictive analysis. And Model Execution, where you will estimate store sales using an ensemble of the following models:

* Random Forest
* Multivariate Regression
* Gradient Boosted Trees

So what are you waiting for? Clone this repositary to your local machine and follow the steps below to output
sales predictions for Rossman Stores.



# Requirements

First, let's check you have everything you need! This project was developed using `Python 3.7.1` with the following requirements:

```
numpy==1.15.4
pandas==0.24.2
scikit-learn==0.20.1
tensorflow==1.13.1
```
The requirements.txt file is accesible [here](https://github.com/EdithChorev/Team1/blob/master/requirements.txt) also.



# Data Cleaning and Feature Engineering

In order to produce a cleaned dataset for execution, we combine and clean the following files:

* A .csv file with characteristics of each Rossman store, this file is called: `store.csv`
* A .csv file with daily sales and activity data for each Rossman store, this file is called: `test_set.csv`

This step is executed in the Jupyter Notebook titled `Rossman Dataset | Cleaning and Feature Engineering`. The specific
assumptions made, and engineering decisions executed are outlined throughout the notebook.

Once you've cloned this repo, simply open this Notebook and execute each cell 
in a linear order i.e. from the top of the notebook down. Just make sure you read the instructions!


<p align="center">
  <img src="https://i.chzbgr.com/full/8396877568/hDEBA606B/"/>
</p>


You should finish this step with a cleaned dataset called `cleaned_rossman_test_data.csv` ready for model execution.



# Model Execution

Now for the fun part! Open up the Jupyter Notebook titled `Rossman Dataset | Model Execution`. 

Models are executed, and results are aggregated, in an ensemble fashion - strength in numbers! And again, the process is outlined in the notebook, and can be executed by executing each cell in a linear fashion.

<p align="center">
  <img src="https://i.pinimg.com/originals/f0/d9/84/f0d984083416dedfa4e7501ce9b02296.jpg"/>
</p>

How'd we go? The results might be a tad off but at least we get meme points.. right?
