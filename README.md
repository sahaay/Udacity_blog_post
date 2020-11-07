# Regression using Random Forest

### Project overview

This Project is towards a Data Science post as part of Udacity's Data Scientist Nanodegree.  The data used for this analysis is of real estate valuation collected from Sindian Dist., New Taipei City, Taiwan.  

Using this data there are a few questions which were looked at:

1. Understand the relationships existing between variables
2. Any particular trends between variables
3. Variables which impact the house price the most

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

#### The questions were answered by doing exploratory data analysis and data modeling.

#### Looking at the house price, we see that house age and distance to the nearest MRT station have a negative correlation with it, and number of convenience stores has a positive correlation.

#### It was evident by looking at the scatterplots between price and distance to the nearest MRT station, that the houses closer to the station were more expensive, which seems logical. Also, it looks like the houses are expensive when they have more convenience stores close by. There was no clear trend between house age and price.

#### With the help of Random Forest Regression algorithm, we concluded that distance to the nearest MRT station is the most important variable for house price, followed by the house age.

#### Random Forest regression performed very well on the data, resulting into a correlation of 0.97 between the actual house price and predicted house price. 

#### Hopefully this is a helpful introduction to a straightforward implementation of the Random Forest regression algorithm.  The result helps us to understand which features are the most important in explaining the variability of the dependent variable in the dataset.

#### A blog post detailing the approach and output is [here](http://kya-re.blogspot.com)


### Acknowledgements
#### Dataset was sourced from UCI Machine Learning Repository and can be accessed [here](http://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set).
