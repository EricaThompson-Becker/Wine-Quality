# Wine-Quality Prediction

## Author: E. Thompson-Becker 
### Date: 23/08/2022
**Project completed and slightly altered from an assignment for CMTH 642 Data Analytics: Advanced Methods at Toronto Metropolitan University in Winter 2022, for the Data Analytics, Predicitive Analytics and Big Data certificate.**

The goal of this assignment is to use binomial logistic regression to determine if a wine will pass or fail a quality test due to the physicochemical properties of the sample. The analysis will compare two models; one with a balananced training set and one with an unbalanced training set. The data is splitinto a train and test set using simple 70/30 split. To compare the models the accuracy, sensitivity, and specificity will be evaluated. 

The data is composed of 12 attributes including the quality score. The other attributes are based on 11 physicochemical tests preformed on each sample. There are a total of 4898 observations in the dataset. 

The attributes are:
  - fixed acidity
  - volatile acidity
  - citric acid
  - residual sugar
  - chlorides
  - free sulfur dioxide 
  - total sulfur dioxide
  - density
  - pH
  - sulphates
  - alcohol; and
  - quality (a score from 0-10)
