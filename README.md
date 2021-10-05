# Statistical Models
This repository contains a variety of statistical modeling projects that leverage a host of machine learning methods in order to derive meaningful results from topics ranging from politics to finance. 

<p align="center">
  <img src="/images/Stat_Cover.png">
</p>

## Table of Contents
 
1. **Predicting the Results of the 2020 Presidential Election**
- The aim of this project was very simple, it was to predict the winner of the 2020 presidential election. In order to accomplish this, I chose a Gaussian Process as the model due to its ability to adapt more naturally to the polling data, without having to make strong underlying assumptions about the relationship between time and presidential popularity. The Gaussian Process also has confidence intervals built into it, so this allows for a nice way of seeing the possibility of an upset election should the intervals overlap.

2. **Stock Price Valuation Model**
- The aim of this project is to construct a model that would be able to take a given set of inputs (these being financial metrics) and then output the predicted price of the asset the metrics belong to. In order to do this, I used a multiple linear regression model where each variable was a different financial metric, and the response variable was the price of the underlying asset. In order to properly train and test the model as well as select which features went into its final result, a host of machine learning fundamentals were used such as Lasso Regression, Covariance Matrices, Learning Curves, and others.

3. **Diabetes Classification Model**
- The aim of this project is to construct three different classification models (KNN, Decision Tree, Random Forest) and compare the accuracy and speed of each. The dataset used here can be found on the UCI Machine Learning Repository, and it consists of the answers to various yes/no questions that are meant to help the doctor determine whether or not a given patient has diabetes, as well as whether in fact the patient has diabetes or not. So the aim of the project is classifying patients as diabetic based on their answers to certain question. The tail end of the project also looks at Grid Search CV and compares its accuracy and speed to Bayesian Optimization when both are used on the computationally expensive Random Forest method. 

4. **Logistic Regression Survival Model**
- The aim of this project is to construct a Logistic Regression model that can be used to determine the survival chances of each passanger aboard the Titanic, using data about their age, ticket, price, and gender, among others. The model focuses solely on tuning the hyperparameter "C" which is a regularization parameter meant to prevent overfitting through the penalization of the coefficients. The project looks at the best value for "C", as well as the associated confusion matrix after optimization, maximizing precision as opposed to accuracy or recall, ROC and AUC curves, and even visualizing our model fit. Lastly, there is a brief write up detailing some of the real life stories behind a few members that were aboard the Titanic that fateful night.
