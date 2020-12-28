# COVID-ASSISTANT

HERE WE ARE CONSIDERING THE TOTAL CASES ACROSS THE WORLD FROM 13 MARCH 2020 TO 29 NOVEMBER 2020.

DATASET IS TAKEN OUR WORLD IN DATA FROM A GITHUB SOURCE - https://github.com/owid/covid-19-data/tree/master/public/data

OBJECTIVE: IT IS TO PREDICT THE LIFE EXPECTANCY

STEPS FOLLOWED:
1. Exploratory Data Analysis
   detailed visualisation of each and every column using seaborn and matplotlib
2. Feature Engineering
   null value treatment 
   ouliers treatment 
   merging of 2-3 columns into 1  
3. used stas module to pick top 10 features to remove curse of dimensionality
4. Training of model
   Linear Regression
   Ridge Regression
   Lasso Regressor
   KNN Regressor
   DT_Regression_Tree
   Random Forest Regressor
   Bagging Regressor
   ElasticNet Regressor
   Gradient Boosting Regressor
   Histogram-Based Gradient Boosting Regressor:
   Gradient Boosting With XGBoost Regressor
   Gradient Boosting With LightGBM Regressor
5. Deplyed on Heroku using Flask 
    
