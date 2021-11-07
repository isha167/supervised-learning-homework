# Supervised Machine Learning Homework - Predicting Credit Risk

Building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

## Background

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API.

## Preprocessing: Convert categorical data to numeric

Created a training set from the 2019 loans using `pd.get_dummies()` to convert the categorical data to numeric columns. Similarly, created a testing set from the 2020 loans, also using `pd.get_dummies()`.There were categories in the 2019 loans that do not exist in the testing set.So found the column and added that dat.Also dropped some duplicated columns from the data.
## Considered the models
Considered two different models and did an educted guess and analysed that before working on the two models.

## Fit a LogisticRegression model and RandomForestClassifier model

Created a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. 

## Revisited the Preprocessing: Scale the data

The data going into these models was never scaled, an important step in preprocessing. Used `StandardScaler` to scale the training and testing sets. Before re-fitting the LogisticRegression and RandomForestClassifier models on the scaled data


