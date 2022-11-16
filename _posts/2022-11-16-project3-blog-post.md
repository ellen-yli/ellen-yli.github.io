## This is my blog of third project

This project is a great practice of how to build and select models from data set with large number of predictors. In this project, we also used “automating R markdown” to apply same analysis methods on different parameters, which improves workflow a lot. 

In the modeling section, I have difficulty in fitting a linear regression model for those data. Since the data has so many predictors (almost 60), I thought it would be a good idea to perform a predictor selection procedure before fitting the linear model. I tried ‘regsubsets’ function to get the optimal number of predictors without realizing my data have significant collinearity problem. The method failed due to several variables are dependent to each other. Fortunately, Principal Component Analysis (PCA) is a better approach to eliminate multicollinearity between features. I finally fit my linear regression model successfully after performing PCA on the data set. Next time, I might want to exam the variable correlations before fitting the model. Removing high correlation variables is another effective way to reduce the complexity of a regression model.

Here are the [repo]( https://github.com/ambrinza/project3/tree/main) and [Project3](http://ambrinza.github.io/project3/)
