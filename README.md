# Wind-Forecasting-Using-LSTM-Models
This project shows an LSTM-based time-series forecasting model that predicts wind speed and direction from MAV (Micro Air Vehicle) attitude and wind data. The dataset was standardized using a rigorous preprocessing pipeline, and input-output pairs were produced by a sliding window approach. The model was created with TensorFlow and trained on a variety of window sizes and prediction horizons to adequately capture temporal relationships in the data. The project's goal is to improve situational awareness and decision-making by enabling accurate forecasting for real-time applications.
Comprehensive tests were carried out, comparing projected values to actual data to assess performance across various configurations. Visualizations demonstrate the model's ability to reliably forecast wind speed and direction across both short and long time intervals. The findings highlight the necessity of selecting the best window widths and horizons for efficient time-series forecasting. Future work might concentrate on integrating sophisticated structures, such as attention processes, as well as adding new environmental variables to boost prediction skills. This repository contains the dataset preparation, model training, evaluation scripts, and preserved model files for future experiments.
