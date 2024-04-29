ML-Based system for Anomaly detection in network traffic
This repository contains code and visualizations for a time series analysis project focused on network traffic prediction.

Project Overview
The goal of this project is to develop a machine learning model that can predict Anomaly in future network traffic volume based on historical data. This model can be used for various purposes, such as:

  Security monitoring: Identifying unusual traffic patterns can aid in detecting suspicious activity or potential denial-of-service attacks.

Data and Preprocessing
The data used for this project is network traffic captured over a period of 20 days. 

The data preprocessing steps involve:

  Feature extraction: Selecting relevant features from the raw data, such as bytes transferred, packets sent/received, and timestamps.
  Data segmentation: Dividing the data into smaller time intervals (e.g., 5 minutes) to create samples for model training.
  Data cleaning: Handling missing values and outliers in the data. (Optional: Specify methods used for cleaning)
  Smoothing: Applying techniques like Gaussian filter (refer to separate documentation for details) to reduce noise in the data.

Contributing
We welcome contributions to this project. Feel free to submit pull requests with improvements to the code, documentation, or visualizations.
