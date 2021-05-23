# Predicting_Airbnb_Prices_In_Jersey_City_Using_MachineLearning

Introduction:
Real world problem: Airbnb has to set the right price for the property which satisfies not only the host but also is competitive enough for the market and demands of the customers.
Purpose: This projects aims at optimizing the pricing functionality. The model sets the right price according to the important features which seem to have affected the rate of the property over the years.


Exploratory data analysis:
Categorical features were explored and plotted, to gain insights and to determine whether or not they should be included in the final model.
According to the chart, we could know that the largest number and median price of Airbnb listing in Jersey city are both from Newport.



Preparing the data for modeling:
The features are assessed for multi-collinearity. The following heatmap is observed and accordingly redundant columns are eliminated



XGBoost model:
Training/ Test Spli t : 80%/20%
Training MSE: 0.0882, Validation MSE: 0.119 
Training R2: 0.8546,  Validation R2: 0.7907




Results:
This model guides Airbnb/Hosts to optimally set their rent and maximize their profits. Besides, the result helps them to understand the features that affect customer behavior and help them improve upon the customers overall experience.

Directions for future work
Find a way to incorporate image quality into the model
Augment the model with (NLP) of listing descriptions and/or reviews. Further the model improvised using hyper. Parameter tuning.
