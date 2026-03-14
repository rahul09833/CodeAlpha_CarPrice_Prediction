🚗 Car Price Prediction using Machine LearningThis project uses Machine Learning to predict the resale price of used cars based on several features such as the car's age, present price, kilometers driven, fuel type, and transmission.The goal is to provide a reliable estimate for sellers and buyers in the used car market using historical data.
📊 Project OverviewPredicting the price of a used car is a regression problem. I compared Linear Regression and Random Forest Regressor to determine which model provides the most accurate results.
Key Features used:
Present Price: Original price of the car.Car Age: Number of years since manufacture (calculated from the 'Year' column).Driven Kilometers: Total distance the car has traveled.Fuel Type: Petrol, Diesel, or CNG.Transmission: Manual or Automatic.Seller Type: Individual or Dealer.
🚀 Model PerformanceThe models were evaluated using $R^2$ Score and Mean Absolute Error (MAE).
The Random Forest Regressor significantly outperformed Linear Regression.ModelR2 ScoreMean Absolute ErrorLinear Regression$0.85$$1.21$Random Forest$0.96$$0.64$
