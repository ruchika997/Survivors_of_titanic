# Survivors_of_titanic

## Overview
This is a tutorial in an IPython Notebook for the Kaggle competition, Titanic Machine Learning From Disaster. The goal of this repository is to provide an example of a competitive analysis for those interested in getting into the field of data analytics or using python for Kaggle's Data Science competitions.

## Data
The dataset used in this project is included as 
* training set (train.csv)
* test set (test.csv)
This dataset is provided by Kaggle and contains the following attributes:

* `survival` : Survival (0 = No; 1 = Yes)
* `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
* `name` : Name
* `sex` : Sex
* `age` : Age
* `sibsp` : Number of Siblings/Spouses Aboard
* `parch` : Number of Parents/Children Aboard
* `ticket` : Ticket Number
* `fare` : Passenger Fare
* `cabin` : Cabin
* `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## Libraries required
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [scikit-learn](https://scikit-learn.org/)

## Goal for this Notebook:
Show a simple example of an analysis of the Titanic disaster in Python. This is aimed for those looking to get into the field or those who are already in the field and looking to see an example of an analysis done with Python.

## This Notebook shows:
### Data Handling
* Importing Data with Pandas
* Cleaning Data
* Exploring Data through Visualizations with Matplotlib
### Cleaning Data
* Exploring Data through Visualizations with Matplotlib
### Data Analysis
* Supervised Machine learning Techniques: + Logit Regression Model + Plotting results + Support Vector Machine (SVM) + Basic Random Forest + Plotting results
### Valuation of the Analysis
* K-folds cross validation to valuate results locally
