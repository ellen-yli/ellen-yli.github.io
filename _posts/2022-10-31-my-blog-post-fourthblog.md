## This is my fourth blog post (Variable Selection)

In real data set analysis process, when too many variables (predictors) in the model, It will cause the problems such as adding noise, collinearity, etc. As regarding a regression model, we need to find the as smallest model as possible that can fit the data.

My first step of doing variable selection will be “EDA”. I would like to study the overall structure of the data, where I can identify any linear correlations between predictors, possible outliers and also check regression model assumptions. 
After that I will use stepwise selection (either forward or backward) to get start. Forward stepwise selection actually can be used when the number of variables under consideration larger than the sample size. The good thing is stepwise method is easy to apply and interpret most of time. However, it does not consider all possible combination of potential predictors and yields biased R-squared values on the high side.  

Another method I will use is the “Best subsets regression”. The benefit of this method is to compare all possible models using a specified set of predictors. So basically, I can make my own decision of which one to use. Comparing with stepwise method, this method does not yield a single model. It provides more information and personal judgment is required. The computation time might be longer due to more models needs to be performed.
