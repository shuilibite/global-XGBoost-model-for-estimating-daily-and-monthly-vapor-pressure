# global-XGBoost-model-for-estimating-daily-and-monthly-vapor-pressure
The global XGBoost model for estimating daily and monthly vapor pressure except for hyper-arid regions. 
The XGBoost model have been trained using data from 512 and 594 weather stations spanning from various climate zones.

to run the program, click the "Main_xgboost_ea_global_daily_pridiction" or "Main_xgboost_ea_global_monthly_pridiction"

notice
1. to run the model, make sure you have installed the package 
packages('openxlsx')
packages('xgboost')

2.to load the trained XGBoost model and xlsx file of testing data
please change the file path in the program

3. prepare your data of maximum temperature (Tmax), minimum temperature (Tmin) and aridity index (AI) as follows in excel
1         2              3
Tmax  Tmin and AI

4. please change the file path in the program for the output file.
