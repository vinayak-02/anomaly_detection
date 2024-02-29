# anomaly_detection
Using Prophet model to identify the anomalies in detecting fraudulent transactions
# ABSTRACT:
The aim of this project is to enhance the EdgeDetect product by integrating an anomaly detection feature that utilizes time series analysis. This will be achieved by implementing the Prophet model, developed by Facebook, for time series forecasting. Additionally, a defined threshold will be established to effectively identify and flag anomalies.
# ALGORITHM:
• Cleaning the data by standardizing date and time format
• Renaming the columns
• Initiating prophet model, fitting it and forecasting the data
• Adding regressors to the model
• Custom score (Z-score) being calculated from the forecasted data column being analyzed.
• Setting a threshold for the custom score (Z score) to filter anomalies
• Determining outliers (or anomalies) and calculating outlier rate
# OUTPUT METRICS & VISUAL ANALYTICS:
• Outlier rate
• Range of the metric being analyzed
• Range of outliers.
• Confusion matrix and the corresponding metrics
• Dynamic graph - time series forecast with anomalies marked
