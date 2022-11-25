# [Baseball Data Projects](https://github.com/christian-dl/BaseballMLWINSABOVEREPLACEMENT)
Chris' Portfolios

# Project Overview

In this project, I predict future season (next year) Wins Above Replacement (WAR) for baseball players using Python code.  I'll first download baseball season data using pybaseball and clean the data.  I'll do feature selection using a sequential feature selector to identify the most promising predictors for machine learning.  I'll then train a ridge regression model to predict future season WAR.  Finally I'll measure error and improve the model.

At the end, I'll have a model that can predict future season WAR, along with next steps to improve the model.

**Project Steps**

* Download baseball season data
* Clean the data and prepare it for ML
* Run feature selection
* Create a machine learning model and estimate accuracy
* Improve accuracy

## Code

You can find the code for this project [here](https://github.com/christian-dl/BaseballMLWINSABOVEREPLACEMENT)

File overview:

* `MLRidgeRegression.ipynb` - a Jupyter notebook that contains the code to predict next season WAR.

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pybaseball
    * pandas
    * scikit-learn
    * numpy

## Data

I'll download the data during this project, using the `pybaseball` package.

## Findings

The first model used 3 training sets using the first 5 years as test sets 2002-2006 to start the model. From the 2.76 root mean squared error the model is
predicting better than a random guess.

To imporve the prediction on the 2nd model, the algorithm is given the previous year's performance from a single player to predict the following year. The 2.67 root
mean squared error is better than the first model.


