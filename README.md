# DataStorm-2.0

Day 1 - 

Descriptive analysis of the variables were conducted.PowerBI was used to conduct the descriptive analysis. An initial feature selection was carried out by fitting a random forest model and identifying the important features. 
Categorical variables were encoded using label encoder.
In addition 2 new features were created. 
Feature 1 - gives the number of days between the time of booking and the checkin date.
Feature 2 - gives the number of days the customer plans to stay at the hotel.
Decision tree classifier, random forest and XGboost models were fitted to the dataset.

Day 2 - 
Naive Bayes Algorithm, Adaboost and KNN classification was fitted to the dataset. 

Day 3 - 
A new feature was created which calculates the total charge for the stay.
The variables that were used to calculate the total charge was removed when fitting models. 
SMOTE resampling technique was applied to handle the imbalance in the dataset.
The numerical variables were standardised. 
Random forest and XGBoost models were fitted and the parameters were tuned using the GridSearchCV algorithm. 
