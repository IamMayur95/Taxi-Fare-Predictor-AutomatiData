# Taxi-Fare-Predictor-AutomatiData

# Overview
The goal of this project is to create a multiple linear regression model to predict ride fares based on multiple variables. This project utilized yellow taxi trips taken in New York City during 2017. The final multiple linear regression model performed with R^2 of 0.868 indicating 86.8% variance being explained by the model.

# Business Understanding
Predicting taxi fares enhances the overall efficiency, competitiveness, and customer satisfaction of taxi businesses, making it a crucial aspect of their strategic decision-making process.

# Data Understanding
The NYC Taxi and Limousine Commission data came from NYC.gov (https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page). The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type.

# Modeling and Evaluation
A multiple linear regression model is built based on the data and the distribution of the data to estimate the taxi fares before the ride.Below plot shows that Mean Duration is the most important feature in estimating the fare. The overall model performed with R^2 of 0.868 , MAE of 2.13 , MSE of 14.33 and RMSE of 3.79
Final model:
predicted_fare = 0.030825*(passenger_count) + 1.995592*(mean_distance) + 2.812115*(mean_duration) + 0.110233*(rush_hour) - 0.054373*(VendorID_2)

![AutomatiData-3](https://github.com/IamMayur95/TaxiFarePredictor-AutomatiData/assets/67839699/0d813d54-ed99-4d89-b419-7ee8138a5a6d)


# Conclusion
The linear regression model provides a sound framework in estimating the fare amounts of the taxi rides.  Taxi fare prediction model can have a widespread positive impact on various stakeholders, promoting efficiency, transparency, and satisfaction in the transportation ecosystem. In order to indicate the efficacy of the linear regression model , below scatter plot is included to compare the predicted vs actual fares.

![AutomatiData-4](https://github.com/IamMayur95/TaxiFarePredictor-AutomatiData/assets/67839699/a5593484-4891-44d2-802c-cb17928dae79)
