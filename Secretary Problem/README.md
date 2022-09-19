# Secretary Problem Optimization
<p align="center">
  <img src="/images/Secretary_Problem.png">
</p>

## Summary
 
**New Optimal Stopping Solutions on a Classic Problem**
- The aim of this project was to find a solution to the classic Secretary Problem using computer hiring simulations, as opposed to simply solving the elegant analytical pencil and paper solution. Using the computer approach, this project was able to arrive at the same conclusion for optimal stopping threshold (37%) as well as find the optimal stopping thresholds if we change our search to look for best average candidate score, and various candidate perentiles.
- The layout of the project is as follows.
  - Problem Statement
  - Running 100,000 simulations of stopping at 99 different thresholds
  - Showing the classic solution to the problem where we see 37% success stopping 37% of the way through our set
  - Showing the solution when we want to find highest average candidate score (not just the best candidate)
  - Showing the solution when we want to find any candidate in the 95th percentile, 90th percentile, etc.
  - Looking at the decrease in success that comes with an increase in searching for candidates of a higher percentile
- The .ipynb file is done in Jupyter Notebook so it was easy to comment in cells between lines of code, as well as write up my thought process as I went along, so the code file itself will serve as a much better guide to the project than the bullet points that summarize it here. So click the link to the code and enjoy.

