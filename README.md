# Fantasy-Football

This project takes stats from every running back in the 2020 NFL season.

Answers the question: which stat holds the most importance for a running back to get the most points in fantasy football?

Using three different models (LinearRegression, RandomForestRegressor, GradientBoostingRegressor) to predict which statistics hold the most importance for the running back's fantasy point total for that season.

Before transforming the data, one model resulted in containing the best mean absolute error.
Using that model's coefficients resulted in a feature importance chart showing which features hold the most importance for a running back's fantasy point total.

Repeated the same procedure but with the data transformed.
The model with the best mean absolute error resulted in different findings for the most important features for a running back's fantasy point total.
