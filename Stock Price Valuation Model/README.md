# Stock Price Valuation Model

<p align="center">
  <img src="/images/Pricing_Cover.png">
</p>

## Summary
 
**Determining Stock Price Based on Associated Financial Metrics**
- The aim of this project is to construct a model that would be able to take a given set of inputs (these being financial metrics) and then output the predicted price of the asset the metrics belong to. In order to do this, I used a multiple linear regression model where each variable was a different financial metric, and the response variable was the price of the underlying asset. In order to properly train and test the model as well as select which features went into its final result, a host of machine learning fundamentals were used such as Lasso Regression, Covariance Matrices, Learning Curves, and others.
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
