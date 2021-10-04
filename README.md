# Credit Risk Evlauator

A machine learning model that attempts to predict whether a loan from the sample dataset will become high risk or not

## Instructions

In the `Generator` folder in `Resources`, there is a [GenerateData.ipynb](/Resources/Generator/GenerateData.ipynb) notebook that ~~will download data from LendingClub and~~ output two CSVs:

* `2019loans.csv`
* `2020Q1loans.csv`

Note: these two CSVs have been undersampled to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk

## Credit Risk Evaluator

Creates a Logistic Regression model and then a Random Forest model on the sample data using the [2019loans](Resources/Generator/2019loans.csv) file as training data and the [2020q1loans](Resources/Generator/2020Q1loans.csv) file as test data

Repeats this process after normalizing the data via scaling, then prints an analysis of the four sets of predictions
