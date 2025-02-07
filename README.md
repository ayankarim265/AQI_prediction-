# AQI_prediction
I have used 11 different regression models to analyse the data and estimate AQI. We used the city_day data available on Kagle. In this data, we have 16 features, which are city names and pollutant names.  We have multiple environmental variables in the dataset which consists of particulate matter (PM2.5, PM10), nitrogen oxides (NO2, NOx), carbon monoxide (CO), sulfur dioxide (SO2), ozone (O3), Benzene,toluene, and Xylene. 
The candidate models included in this study comprise of Linear Regression, Ridge, SGDRegressor, ElasticNet, Lasso, SVR, Gradient Boosting, XGBoost, Random Forest, and LightGBM. Evaluation is based on R2 score and the best Train, validation, and test   R2 score is of RandomForestRegressor which is 98.04% ,85.00% and  95.21%.
![image](https://github.com/user-attachments/assets/484f7890-98c2-47c0-9351-4b67fccb4375)
Model	Train R2 Score	Validation  R2 Score  	Test R2 Score
0	LinearRegression  	0.711659	  0.703124  	0.708505
1	Ridge	              0.711659	  0.703125   	0.708505
2	SGDRegressor      	0.710294	  0.701467	  0.707256
3	ElasticNet         	0.644183	  0.632727	  0.641636
4	Lasso              	0.690668	  0.684295	  0.689288
5	SVR               	0.686724	  0.678345  	0.685713
6	GBoostingRegressor	0.844375	  0.827409   	0.844596
7	XGBoost           	0.936842   	0.841852	  0.915677
8	RandomForestRegressor	0.980491	0.850028	  0.952184
9	LightGBM	           0.892086	  0.847633	  0.882648
10	DecisionTreeRegressor	0.999872	0.722373	0.936378
