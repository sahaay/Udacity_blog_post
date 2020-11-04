# Regression using Random Forest

### Project overview

This Project is towards a Data Science post as part of Udacity's Data Scientist Nanodegree.  The data used for this analysis is of real estate valuation collected from Sindian Dist., New Taipei City, Taiwan.  In this project, we would identify the most important factors which influence the house price. 

### Problem statement
Using the dataset we would identify the most important factors influencing the house prices. To solve this problem following steps were undertaken:

1. Loaded the packages for analysis (sklearn, numpy, seaborn, matplotlib etc.)
2. Read in the data file 
3. Split the dataset into train and test.  80% of the data was used for training and 20% was kept for testing.
4. Used Random Forest algorithm to Predict House Price
5. Compare the Actual House Price and Predicted House Price by creating a scatter plot.
6. Identifying the most important factors impacting the house price - this was a part of the Random Forest regression output, and something which is extremely helpful.

### Installations

### Required installations:
•	Jupyter Notebook
•	Python 

### Required packages:
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn

### Reflection
Random Forest regression performed very well on the data, resulting into a correlation of 0.97 between the actual house price and predicted house price. 
Hopefully this is a helpful introduction to a straightforward implementation of the Random Forest regression algorithm.  The result helps us to understand which features are the most important in explaining the variability of the dependent variable in the dataset.
