# Estimation_of_Demand_Function_for_Train_Travel
Econometrics Project - identify instrumental variables and use 2SLS to train the linear model.

## Key words
2SLS, Instrumental Variables

## Context
The aim for this project is to estimate the demand function of train travel by using data on train ticket sales at a particular train station. The price, from experience, might be endogenous. The two-stage least squares method (2SLS) is used to handle this in a linear regression framework. Instrumental variables are identified and tested. 2SLS is applied to generate unbiased slope coefficients at a cost of variance increase.

## Dataset
There are 209,697 original data, and no missing values. Train_Number_All, Train_Number_All, isNormCabin, isReturn, isOneway, Customer_Cat are categorical variables; dept_datetime and purch_datetime are time series; other data are continuous variables.

## Insights
In terms of adjusted R2, OLS model performs better than 2SLS model in explaining the demand function with the given dataset. However, because of endogeneity the OLS model is biased in the first place. 2SLS helps to fix this problem, using exogenous predicted Price to estimate the demand.

## Collaborators
Ke Ma

Mingzhe Xu

Nanhai Zhong

Xiao Liang
