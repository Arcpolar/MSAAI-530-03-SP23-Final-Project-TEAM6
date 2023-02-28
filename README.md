# MSAAI-503-03-SP23-Final-Project-TEAM6

This project aims to measure fish growth over time based on the water conditions of twelve ponds using machine learning. The project uses a gradient boosting model to predict fish growth based on water conditions, and LSTM to predict the reading expected in three minutes for each sensor attribute.

Table of Contents
Data
Data Cleaning
Documents
EDA
Time Series Model Data
Weight_prediction_Models
Data<a name="data"></a>
This folder contains the final csv files including the cleaned data pond, training and validation data, and combined dataset of the validation set with the predicted fish growth and predicted sensor data.

Data Cleaning<a name="data-cleaning"></a>
This folder contains all of the Jupyter notebooks used in the data cleaning process. The notebooks include data cleaning procedures such as removing duplicates, handling missing values, and transforming data into a suitable format for machine learning models.

Documents<a name="documents"></a>
This folder contains all the text documents for the sensor data and reports. These documents provide detailed descriptions of the sensor data and explain the methodology used in the project.

EDA<a name="eda"></a>
This folder contains all of the Jupyter notebooks for the initial data processing and visualization. The notebooks were used to determine the volume, consistency, missing data as well as obvious correlations in the data. These notebooks were used to gain insights into the data and inform further data cleaning and model building.

Time Series Model Data<a name="time-series-model-data"></a>
This folder contains the LSTM Jupyter notebook that creates all of the predictions for each individual sensor. The notebook contains the code for the LSTM model that was trained to predict the readings expected in three minutes for each sensor attribute.

Weight_prediction_Models<a name="weight-prediction-models"></a>
This folder contains the Jupyter notebooks and data for the fish weight prediction. The notebooks include the code for the gradient boosting model used to predict fish growth based on water conditions. The folder also contains the training and validation datasets used to train and test the model.
