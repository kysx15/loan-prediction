# Welcome to our loan-prediction repository!

## About
This is a mini project for SC1015 (Introduction to Data Science and Artificial Intelligence) on the time taken for people to pay off loans.

The database we used can be found here: https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction?select=credit_record.csv

For the detailed walkthrough, please view the source code in following order:

1. Data Cleaning
2. Data Visualization
3. Machine Learning

## Contributors
SC1015 Lab B137 Team 4

## Problem
Which variable affects a person’s ability to pay off loans on time the most?

## Models used
1. Decision Tree
2. Random Forest (+ GridSearch cross-validation)

## Conclusion
* Total income is the variable that affects a person's ability to pay off loans on time the most.
* Not many of the variables in the dataset are closely related to the ability to pay off loans on time.
* Random Forest with GridSearch cross-validation had higher accuracy, lower false positive rate and lower false negative rate.

## New things we learnt from this project
* Merging two csv files together
* Grouping several rows which have the same value in a column (ID) together and taking the average of a value
* Upscaling the data to make it more balanced
* Chi-squared test
* Random Forest
* GridSearchCV

## References
* https://towardsdatascience.com/how-to-export-pandas-dataframe-to-csv-2038e43d9c03
* 
