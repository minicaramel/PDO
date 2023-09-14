# PDO
This code was developed for the paper "Machine Learning for Multiple Decade PDO Forecasts".
The goal is to use deep learning to predict PDO occurrences by using Keras and Tensorflow.

1. Data preprocessing.ipynb: Preparing the data before training the model
2. Example of the tuning process using ensemble CMIP6.ipynb: Determining the hyperparameters to employ for the subsequent training
3. Channel-wise-based CNN second trainning.ipynb: Training the model with the best architecture and predicting the PDO
4. Channel-wise-based CNN_all-season correlation.ipynb: Analyzing the correlation of our model compared with other methods
5. Channel-wise-based CNN predicted PDO for heat map analysis.ipynb: Predicting PDO in each target month by using different channel-wise-based CNN models
6. Channel-wise-based CNN predicted world SST for heat map analysis.ipynb: Training the model for analyzing heatmaps
7. Channel-wise-based CNN_the time series of PDO index.ipynb: Plotting the time series of the PDO index predicted from the model  
8. Correlation heat maps and RMSE maps.ipynb: Plotting the seasonal heatmap and RMSE maps during positive and negative phases
9. PDO type prediction-hit rate.ipynb: Evaluating the model's ability to predict PDO type
10. Heatmap interpretation.ipynb: Indicating how each predictor's impact on the predictand at each grid point
11. SSTA and wind anomaly correspond to PDO.ipynb: Plotting the SSTA and wind anomalies corresponds to the PDO events.
environment.yml: The Anaconda environment was used in this paper.
