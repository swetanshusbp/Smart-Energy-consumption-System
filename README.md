# Smart-Energy-consumption-System


We aim to predict smart energy consumption based on several factors:
Data Loading and Preprocessing

Mounting Google Drive to fetch data.
Importing necessary libraries.
Loading different datasets (Solar Generated Data, Energy Consumption Data).
Parsing and processing time-based data for analysis.
Data Analysis

Visualizing energy consumption data.
Resampling data at different time intervals (hourly, daily) and visualizing them.
Analyzing weather data and its effect on energy consumption.
Analyzing the employee count and correlating it with energy consumption.
Creating a combined dataset with features like energy consumed, temperature, and employee count.
Exploratory Data Analysis (EDA)

![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/607559ca-59eb-4668-ab44-1cfa1a65919c)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/e59ef617-741b-4eb9-9837-ea866f3e26ba)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/ed551e2e-b93a-4b16-80b0-dbce9e4ab59d)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/bf19675c-1d5d-4eae-a172-55385364be34)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/99cdf58f-7158-4c39-ab76-bcd3e74f13aa)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/f7e31393-720a-4479-a6c8-81df41d46e53)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/8d0573c0-ec27-4013-a687-904aca6562bf)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/a6d30fd3-c4b9-43df-9613-92b981b266b0)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/d62b6e48-25cb-4548-aaf6-9d0a130669fc)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/986896b1-5e14-4bc1-9bc4-e25c18adcdea)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/398a836b-b933-4e61-a59b-9343d337c52e)
![image](https://github.com/SAMUDRABAN/Smart-Energy-consumption-System/assets/97033991/1796e97d-d456-4e19-bed4-3b18e566ac17)

Looking at how the number of employees correlates with solar energy.
Investigating the relationship between temperature and solar energy.
Identifying holidays and creating day type features.
Building Machine Learning Models

Training a simple Linear Regression model on the dataset.
Training an XGBoost Regressor for predicting energy consumption.
Building Deep Learning Model

For deep learning (especially LSTM models), ensure you normalize the data before feeding it into the model.
Given that you're dealing with time series data, consider using models like ARIMA or Prophet which are specifically designed for time series forecasting.
Always ensure you have a validation set to validate your model's performance before testing it on the test set.
Consider using other features or external data (if available) to potentially improve the prediction performance.
