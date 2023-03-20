# DAS-Group-18

Data visualiation is finished.

We can use GLM model for poisson response to fit the model in the formal analysis.

Modelling started, and we log-transformed the response variable to because the residuals are not normally distributed, also considered drop non-significant predictor variables and add interaction terms and quadratic terms.

Because the response variable is the number of days animal stay in the shelter, which is count data type, it's better to use negative binomial GLM model than poisson distribution here.

There are many outliers in this dataset. In that case, boxplots are better than scatter plots to demonstrate the outliers in data visualization part. We can draw the boxplots that each explanatory variables vs response variable.


