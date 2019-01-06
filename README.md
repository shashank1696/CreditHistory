# CreditHistory
Prediction Model for Defaulters from Credit history dataset using DecisionTreeClassifier Algorithm.

## Variables:
1) Default(binary) : Default is the failure to pay interest or principal on a loan or security when due.
2) Amount(Integer) : customers amount
3) Grade(Categorical: A,B,C,D,E,F,G) 
4) Ownership(Categorical: 'mortgage','other','own','rent') : Property for mortgage
5) Income(Float) : Income of customers
6) Age(Integer) : Age of customers 

## Data Handling:
1) Importing Data with Pandas
2) Cleaning Data
3) Exploring Data through Visualizations with graphs
4) Data Prediction

## Packages required in Python:
1)  pandas
2)  numpy
3)  sklearn.tree
4)  sklearn.model_selection
5)  pydotplus
6)  os
7)  from IPython.display importing Image
8)  sklearn.metrics
9)  sklearn.ensemble
10) matplotlib.pyplot

## Conclusions:
1) Predictive Model is built with 98.3% accuracy and the depth of the tree for the model is 8 
   using Decision Tree Algorithm for classification.
2) The roc_auc score for the model is 98.7%.
