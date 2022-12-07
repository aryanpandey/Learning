# F- Statistics

F statistics can be used to find the joint significance of multiple independent variables. In general, it is used to compare two models' ability to explain the variance of the dependent variable. In other words, it helps us determine if we should choose a complex model for a task or if even a simpler version will do.

### Performing the F-Test
The Null Hypothesis H0 would be: All the Regression Coefficients are equal to 0 and the model cannot capture the variance of the dependent variable.

The Alternate Hypothesis H1 would be: Atleast one of the Regression Coefficients is not equal to zero.

This means that even if one of the coefficients is significant, then there is a high possibility of rejecting the null jypothesis as the coefficients are not jointly insignificant anymore. 

The two kind of models one could consider could be: First, an unrestricted model which has all the predictor variables and a restricted model which has only a subset of the predictor variables. 


