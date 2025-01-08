# Energy-Consumption-Prediction-in-Data-Centers
This project focuses on predicting energy consumption in data centers over a 12-hour period using a hybrid model that combines ARIMA (AutoRegressive Integrated Moving Average) for modeling linear trends and LSTM (Long Short-Term Memory) networks for capturing non-linear patterns. The model aims to forecast energy usage more accurately by leveraging the strengths of both approaches.

Key Features:
Data Preprocessing:
Cleaned and normalized the dataset consisting of hourly energy consumption data.
Handled missing values and ensured data consistency.

Hybrid Model Implementation:
ARIMA was used to model the linear components of the time series data.
Residuals from the ARIMA model were fed into the LSTM network to capture complex, non-linear patterns.

Integration of Results:
Combined predictions from both ARIMA and LSTM models by averaging their outputs to improve overall prediction accuracy.

Evaluation:
Evaluated the model's performance using metrics like Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).

Tools and Technologies:
Programming Language: Python
Libraries: Pandas, NumPy, TensorFlow, statsmodels, Matplotlib
Data Visualization: Matplotlib and Seaborn for trend analysis and evaluation.
Database: Data stored and processed locally.

Outcome:
The hybrid model demonstrated improved accuracy in forecasting energy consumption, offering potential benefits in optimizing energy management and reducing costs in data center operations.
