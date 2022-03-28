# Data-Science_-Air-Quality-Index-Prediction-in-Bishkek
Projects aims at predicting air quality index, based on PM2.5 and PM10 levels, temperature, NO2 gas level on the air, atmospheric pressure and the humidity via different supervised Machine Learning algorithms (specifically, Artificial Neural Network, Linear Regression, KNNNeighbourRegression, Support Vector Regression, and XGBoost). 
Data for the project was taken from http://data.movegreen.kg/ , which is an open-source website that provides data for environmental research purposes. There are about 16000 rows incudings the observation from February 2020 to February 2022. 
The project considers two scenarios with different train and test splits. In the first scenario, data was split to train and test by random shufflign to 80% and 20%, respectively. In the second scenario, it was made sure that the data was stplit equally by every season: 80% of each season go to training data, while the remaning 20% of each season go to testing data.







Project process included data pre processing (missing values handling, to be specific), data splitting, model application, and accuracy evaluation. 
Findings of the project show that the XGBoost model has the higgest prediction accuracy, while ANN has the lowest. See the code for more details: each notebook contains the code with the necessary description. 
