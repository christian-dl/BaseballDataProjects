# BaseballDataProjects
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
