# Statistical Models
This repository contains a variety of statistical modeling projects that leverage a host of machine learning methods in order to derive meaningful results from topics ranging from politics to finance. 

<p align="center">
  <img src="/images/Stats_Cover.png">
</p>

## Table of Contents

1. **Asset Pricing Model**
- The aim of this project is to construct a model that would be able to take a given set of inputs (these being financial metrics) and then output the predicted price of the asset the metrics belong to. In order to do this, I used a multiple linear regression model where each variable was a different financial metric, and the response variable was the price of the underlying asset. In order to properly train and test the model as well as select which features went into its final result, a host of machine learning fundamentals were used such as Lasso Regression, Covariance Matrices, Learning Curves, and others. 
2. **Predicting the Results of the 2020 Presidential Election**
- The aim of this project was very simple, it was to predict the winner of the 2020 presidential election. In order to accomplish this, I chose a Gaussian Process as the model due to its ability to adapt more naturally to the polling data, without having to make strong underlying assumptions about the relationship between time and presidential popularity. The Gaussian Process also has confidence intervals built into it, so this allows for a nice way of seeing the possibility of an upset election should the intervals overlap.
