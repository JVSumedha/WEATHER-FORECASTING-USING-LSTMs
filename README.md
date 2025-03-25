# 🌦️ Weather Forecasting using LSTMs
This project implements Long Short-Term Memory (LSTM) for weather forecasting using historical weather data. The model is built using TensorFlow to predict future weather conditions based on past trends.
The dataset is taken from kaggle. The dataset has around 8000 rows and 8 columns. The columns are Date/Time,Temp_C,Dew Point Temp_C,Rel Hum_%,Wind Speed_km/h, Visibility_km,Press_kPa,Weather.
The 'Weather'column has around 50 unique values which are Fog', 'Freezing Drizzle,Fog', 'Mostly Cloudy', 'Cloudy', 'Rain', 'Rain Showers',
'Mainly Clear', 'Snow Showers', 'Snow', 'Clear', 'Freezing Rain,Fog', 'Freezing Rain' etc...

🚀 Features : 
✔️ Data preprocessing & normalization
✔️ Exploratory Data Analysis
✔️ Model training & evaluation
✔️ Performance metrics (MSE, RMSE, MAE)
✔️ Visualization of predictions vs actual values

📊 Technologies Used : 
Python,TensorFlow,NumPy, Pandas,Matplotlib, Seaborn

📈 Results : 
The LSTM model predicts future weather conditions with reasonable accuracy. Further improvements can be made by fine-tuning hyperparameters and increasing dataset size.
