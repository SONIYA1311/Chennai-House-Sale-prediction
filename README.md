# Chennai-House-Sale-prediction
# Problem Statement
Real estate transactions are quite opaque sometimes and it may be  difficult for a newbie to know the fair price of any given home.
Thus, multiple real estate websites have the functionality to predict the prices of houses given different features regarding it.
Such forecasting models will help buyers to identify a fair price for the home and also give insights to sellers as to how to build
homes that fetch them more money.
It is expected to build a sale price prediction model that will aid the customers to find a fair price for their homes
and also help the sellers understand what factors are fetching more money for the houses.
# Variables In The DataSet
   ✤  PRT_ID : Project ID (object)
   ✤  AREA : Area where the house is located (object)
   ✤  INT_SQFT : Total area of the house in square-feet (int)
   ✤  DATE_SALE : Date on which the house got sold (object)
   ✤  DIST_MAINROAD : Distance from the house to the mainroad -in meters(int)
   ✤  N_BEDROOM : Number of Bedrooms (float)
   ✤  N_BATHROOM : Number of Bathrooms (float)
   ✤  N_ROOM : Number of Rooms (int)
   ✤  SALE_COND : Sale Conditions (object)
   ✤  PARK_FACIL : Parking Facility (object)
   ✤  DATE_BUILD : Date on which the house was built (object)
   ✤  BUILD_TYPE : Type of the house (object)
   ✤  UTILITY_AVAIL : Utilities available for the owner of the house (object)
   ✤  STREET : Street where the house is located (object)
   ✤  MZZONE : Chennai Regions are divided into multiple zones, MZZONE is nothing but the zone where the house belongs to (object)
   ✤  QS_ROOMS, QS_BATHROOM, QS_BEDROOM, QS_OVERALL : Masked Data (float)
   ✤  REG_FEE : Registration Fees (int)
   ✤  COMMIS : Commission (int)
   ✤  SALE_PRICE : Price at which the house got sold (int)

# Libraries Used
1. import numpy as np
2. import pandas as pd
3. import statistics as st
4. import matplotlib.pyplot as plt
5. import seaborn as sns
6. from sklearn.model_selection import train_test_split
7. from sklearn.model_selection import cross_val_score
8. from sklearn.preprocessing import StandardScaler
9. from sklearn.linear_model import LinearRegression

# Approches
1. Handling missing values
2. Imputation of missing data
3. Converting data types
4. Encoding categorical variables
5. Exploratory Data Analysis
6. Adding new column 
7. Checking for duplicates
8. Splliting the data
9. Model training
10. Feature importance
11. Getting Insights

# Implementing Machine Learning Models
 1. Linear Regression
 2. K Nearest Neighbour (KNN)
 3. Decision Tree
 4. Random Forest
 5. Extreme Gradient Boosting

# Evaluation
  Cross-validation scores for each model R2 scores for model evaluation Feature Importance

  Utilizing XGBoost for feature importance Visualizing feature importance


# Insights 
 Based on the feature importance given by Best Machine Learning Algorithm(Extreme Gradient Boosting)-Sellers should Focus on the features of order given below to build homes that fetch more money:

 1. Age of the building,
 2. Area(location) of the building,
 3. No. of Rooms present,
 4. Build_type(Commercial,House etc..)-Commercial is best,
 5. MZ Zone,
 6. Parking Facility,
 7. No. of Bedrooms,
 8. Area(SQFT) of the building,
 9. No. of Bathrooms,
 10. Street(Paved, Gravel, No access, etc.) of the building,
 11. Sales Condition,
 12. Utility available.


