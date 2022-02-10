# Predict prices for Airbnb rentals in NYC using Gradient Boost and NLP in R

The project was hosted on Kaggle. For this project, we were given a listing of over 40,000 Airbnb rentals in New York City. The goal of this competition was to predict the price for a rentals using 90 variables on the property, host, and past reviews. 

I transformed features which consisted of text data into 3-dimensional numerical data using NLP. I performed the feature selection using Lasso Regression. In addition, I adjusted outliers using quantiles and IQR. 

My implementation includes two models: Random Forest and Gradient Boost. The corresponding parameters were determined by hyperparameter tuning and the Gradient Boost model generated the lowest RMSE (59.25).

I reached the third place on the leaderboard. 
