# Prediction-of-Fire-Weather-Index-using-linear-regression

# Project overview

-Using Data Science and Machine learning, we can build a model that takes in the detected fires dataset learns and detects future fires based on certain Weather report.
Storing the Sourced dataset to MongoDB.


-Building a Flask App hosted on Heroku.


-Sklearn for pre-processing and Model Building


-Pandas, Numpy, Matplotlib for csv reading, Data Processing, Data Cleaning, Visualization etc.



# About Data-set

Data Set Information:

The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the

Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.

122 instances for each region.

The period from June 2012 to September 2012.

The dataset includes 11 attribues and 1 output attribue (class)

The 244 instances have been classified into fire (138 classes) and not fire (106 classes) classes.

Attribute Information:

1. Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012)

Weather data observations

2. Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42

3. RH : Relative Humidity in %: 21 to 90

4. Ws : Wind speed in km/h: 6 to 29

5. Rain: total day in mm: 0 to 16.8

FWI Components

6. Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5

7. Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9

8. Drought Code (DC) index from the FWI system: 7 to 220.4

9. Initial Spread Index (ISI) index from the FWI system: 0 to 18.5

10. Buildup Index (BUI) index from the FWI system: 1.1 to 68

11. Fire Weather Index (FWI) Index: 0 to 31.1

12. Classes: two classes, namely Fire and not Fire


# EDA
In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Forest fire by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn.


It is always a good practice to understand the data first and try to gather as many insights from it.
Model BuildingFor Regression Problem algorithm decided to predict the feature FWI (Fire weather Index) which is 90%+ correlated to Classes Feature.


# Models used 

Linear regression, Lasso Regression, Ridge Regression ,ElaticNet Regression.


For Classification algorithm decided to predict the features Classes from the dataset which is Binary classification (fire, not fire).



# Model Selection

For Classification Stratified Kfold Cross-Validation metrics is used based best Mean CV Accuracy Model is used for Model Deployment.


For Regression R2 score metrics is used to select best model The R2 score is one of the performance evaluation measures for regression-based machine learning models.

# Result

We got mae = 0.56

r2 score = 0.9842

with RidgeRegression model

