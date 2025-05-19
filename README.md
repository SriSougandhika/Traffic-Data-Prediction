# Traffic-Data-Prediction
Using SimpleRNN, we are trying to predict the traffic on unseen data by training the model on the PeMS dataset. 
The dataset has been provided by the Caltrans official website: https://pems.dot.ca.gov/
To access the dataset, it requires a login. So do login and access the dataset for specific time interval.
Details of the project and how it has been performed can be found in the report attached.
The training dataset has been stored as mldata.xlsx
The unseen data for forecasting is set as forecast.xlsx
The main code and results can be found in ipynb file. 

## Problem statement
Use deep learning models (like LSTM, CNN, and more) to forecast short-term (next one hour, 3 hours, 6 hours, 12 hours, 24 hours) and long-term (next two days, one week, one month, 3/6/12 months) future traffic flow, speed, and occupancy based on analyzing past 3/4/5 years spatio-temporal data at any five consecutive vehicle detection sensor nodes (VDS) in any districts (Use PeMS User Guide attached to capture the required traffic dataset) . Finally, evaluate the models' performance using MSE, RMSE metrics or any appropriate metrics.

## 🙌 Credits
Project by Sri – an aspiring Data Scientist exploring AI in creative ways!
