# AQI_prediction
I have used 11 different regression models to analyse the data and estimate AQI. We used the city_day data available on Kagle. In this data, we have 16 features, which are city names and pollutant names.  We have multiple environmental variables in the dataset which consists of particulate matter (PM2.5, PM10), nitrogen oxides (NO2, NOx), carbon monoxide (CO), sulfur dioxide (SO2), ozone (O3), Benzene,toluene, and Xylene. 
The candidate models included in this study comprise of Linear Regression, Ridge, SGDRegressor, ElasticNet, Lasso, SVR, Gradient Boosting, XGBoost, Random Forest, and LightGBM. Evaluation is based on R2 score and the best Train, validation, and test   R2 score is of RandomForestRegressor which is 98.04% ,85.00% and  95.21%.
![image](https://github.com/user-attachments/assets/484f7890-98c2-47c0-9351-4b67fccb4375)
Train,Validation,Test R2 score :
![image](https://github.com/user-attachments/assets/43b107cb-42c3-41fc-8b77-ee108afe3cdf)
