# Chennai-House-Sale-prediction
# Problem Statement
Real estate transactions are quite opaque sometimes and it may be  difficult for a newbie to know the fair price of any given home.
Thus, multiple real estate websites have the functionality to predict the prices of houses given different features regarding it.
Such forecasting models will help buyers to identify a fair price for the home and also give insights to sellers as to how to build
homes that fetch them more money.
It is expected to build a sale price prediction model that will aid the customers to find a fair price for their homes
and also help the sellers understand what factors are fetching more money for the houses.
# Variables In The DataSet
   ✤ PRT_ID : Project ID (object)
   ✤ AREA : Area where the house is located (object)
   ✤ INT_SQFT : Total area of the house in square-feet (int)
   ✤ DATE_SALE : Date on which the house got sold (object)
   ✤ DIST_MAINROAD : Distance from the house to the mainroad -in meters(int)
   ✤ N_BEDROOM : Number of Bedrooms (float)
   ✤ N_BATHROOM : Number of Bathrooms (float)
   ✤ N_ROOM : Number of Rooms (int)
   ✤ SALE_COND : Sale Conditions (object)
   ✤ PARK_FACIL : Parking Facility (object)
   ✤ DATE_BUILD : Date on which the house was built (object)
   ✤ BUILD_TYPE : Type of the house (object)
   ✤ UTILITY_AVAIL : Utilities available for the owner of the house (object)
   ✤ STREET : Street where the house is located (object)
   ✤ MZZONE : Chennai Regions are divided into multiple zones, MZZONE is nothing but the zone where the house belongs to (object)
   ✤ QS_ROOMS, QS_BATHROOM, QS_BEDROOM, QS_OVERALL : Masked Data (float)
   ✤ REG_FEE : Registration Fees (int)
   ✤ COMMIS : Commission (int)
   ✤ SALE_PRICE : Price at which the house got sold (int)

# Libraries Used
1.import numpy as np
2.import pandas as pd
3.import statistics as st
4.import matplotlib.pyplot as plt
5.import seaborn as sns
6.from sklearn.model_selection import train_test_split
7.from sklearn.model_selection import cross_val_score
8.from sklearn.preprocessing import StandardScaler
9.from sklearn.linear_model import LinearRegression

# Approches
1.Handling missing values
2.Imputation of missing data
3.Converting data types
4.Encoding categorical variables
5.Exploratory Data Analysis
