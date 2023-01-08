# The Conditional Breakdown Properties of LAD-LASSO Regression

#### Bernice Feng, advised by Professor Avi Giloni and Professor Jeffrey Simonoff

### Abstract

The breakdown point is a measure of the worst-case robustness properties of an estimator. It represents the smallest number of observations that can be sent to arbitrary values that will result in a parameter estimate becoming infinitely large in absolute value. In regression modeling, the meaningful measure is the conditional breakdown, in which predictor values are taken as given and fixed, and response values are sent to infinity. Least squares (LS)-based methods generally have a breakdown of 1 observation, the smallest possible value, reflecting their lack of robustness.

It is known that regression based on least absolute deviations (LAD) has higher conditional breakdown than do LS-based methods. In this paper, we examine the conditional breakdown properties of the robust regression method LAD-LASSO, a regularization method that effectively performs variable selection by setting specific slopes to zero based on a specified regularization parameter $\lambda$ while also attempting to be resistant to unusual observations. By formulating the LAD-LASSO problem as a linear program, we are able to use an enumerative algorithm to calculate the conditional breakdown of LAD-LASSO for a given data set. We find that the breakdown depends on several things, including $\lambda$ and the specific values of the predictors (as would be expected), but also on how and whether variables are centered and scaled. We also find that using LAD-LASSO to choose the predictors with nonzero slopes, and then fitting LAD on those predictors, can improve the breakdown considerably. 

### Article

The article can be accessed [here](./LAD_LASSO_Code.ipynb).

### Presentation

The presentation can be accessed [here](./The_Conditional_Breakdown_Properties_of_LAD_LASSO_Regression_Presentation.pdf).

### Code

The code can be accessed [here](./FengGiloniSimonoff.pdf).


