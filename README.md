# Bulldozer-Prices-ML-Model
A Machine learning algorithm to predict the sale price of bulldozers based on historical data

Predicting the sale price of bulldozers
Problem definition

* How well can we predict the future sale price of bulldozers

Data

* Data is downloaded from kaggle bluebook for bulldosers competitions:
https://www.kaggle.com/c/bluebook-for-bulldozers/overview

The key fields are in train.csv are:

SalesID: the uniue identifier of the sale
MachineID: the unique identifier of a machine.  A machine can be sold multiple times
saleprice: what the machine sold for at auction (only provided in train.csv)
saledate: the date of the sale


Evaluation

RMSLE - Root mean squared log error between the actual and predicted aucton prices.

Our goal for this project will be to build a machine learning model which minimises RMSLE.


Features

Kaggle provides a data dictionary detailing all the features of the dataset.

