# Stock Price Valuation Model

<p align="center">
  <img src="/images/Pricing_Cover.png">
</p>

## Summary
 
1. **Determining Stock Price Based on Associated Financial Metrics**
- The aim of this project was very simple, it was to predict the winner of the 2020 presidential election. In order to accomplish this, I chose a Gaussian Process as the model due to its ability to adapt more naturally to the polling data, without having to make strong underlying assumptions about the relationship between time and presidential popularity. The Gaussian Process also has confidence intervals built into it, so this allows for a nice way of seeing the possibility of an upset election should the intervals overlap.
- The layout of the project is as follows.
  - Reading in the data. Data was EXTREMELY messy, since free and accurate financial data is hard to acquire I had to check each ticker symbol
    by hand and clean it so that it contained the appropriate information.
  - Building a Correlation Matrix to observe the relationship between various financial metrics
  - Establish Learning Curves to observe the balance between bias and variance
  - Implement Lasso Regression in order to select key features to the model
  - Further Learning Curves are created until error is irreducible
  - Graphing the final result of how well the model determines the price of training
    data that it has never seen
  - GUI portion created so that the user is able to plug in the selected financial metrics of any stock and 
    the output will be what the price should be as determined by the model
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here. So click the link to the code and enjoy.
