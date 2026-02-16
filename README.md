#Inventory Demand Forecasting Using Regression

##Project Overeview
This project predicts future inventory demand using Linear Regression in Python

##Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

##Project Overflow
1. Data Preprocessing
2. Weekly Aggregation by Product
3. Exploratory Data Analysis
4. Outlier Removal using IQR
5. Feature Engineering (Time Index, Month, Lag)
6. Linear Regression Model
7. Model Evaluation (MAE & RMSE)
8. Forecasting Next 4 Weeks

##Model Performance
- Mean Absolute Error (MAE): ~545 units
- Root Mean Squared Error (RMSE): ~777 units
- Average Demand: ~4019 units
- Error Rate: ~13.5%

##Forecast Included
The model predicts demand for the next four weeks and exports results to 'weekly_demand_forecast.csv'.

##Files Included
- `Inventory_Demand_Forecasting.ipynb`
- `sales_data.csv`
- `weekly_demand_forecast.csv`
