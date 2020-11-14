# Presidential Predictive Model 2020

<p align="center">
  <img src="/images/Presidential_Cover.png">
</p>

## Summary
 
1. **Predicting the Results of the 2020 Presidential Election**
- The aim of this project was very simple, it was to predict the winner of the 2020 presidential election. In order to accomplish this, I chose a Gaussian Process as the model due to its ability to adapt more naturally to the polling data, without having to make strong underlying assumptions about the relationship between time and presidential popularity. The Gaussian Process also has confidence intervals built into it, so this allows for a nice way of seeing the possibility of an upset election should the intervals overlap.
- The layout of the project is as follows.
  - Reading in the data
  - Setting up a Kernel Density Estimation to better visualize the data
  - Optimizing the bandwidth parameter of the Gaussian Kernel
  - Cleaning the data that will be used in the Gaussian Process
  - Optimizing the hyperparameters of the Gaussian Process
  - Graphing the final plot/prediction of who will win the 2020 Presidential Nomination
  using two distinct Gaussian Processes for both Trump and Biden
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here
