# Sensor Anomaly Detection for Predictive Maintenance

A machine learning based Python project to detect abnormal patterns in sensor readings for predictive maintenance and early fault detection.

## Project Overview

The **Sensor Anomaly Detection for Predictive Maintenance** project is a Python-based machine learning system that analyzes sensor data and identifies abnormal readings.

This project uses simulated sensor readings such as:

* Vibration
* Temperature
* Pressure
* Humidity
* Load

The model detects whether each sensor reading is normal or anomalous. It demonstrates practical usage of Python, data preprocessing, exploratory data analysis, anomaly detection, machine learning model evaluation, and visualization.

## Problem Statement

In industrial equipment, machines, bridges, and infrastructure systems, sensor readings are continuously generated to monitor performance and safety.

Sudden changes in vibration, temperature, pressure, or load may indicate abnormal behavior, equipment failure, or maintenance requirements.

Manual monitoring of such sensor data is time-consuming and error-prone. This project provides an automated machine learning solution to detect abnormal patterns in sensor data and support predictive maintenance.

## Objectives

* Load and analyze sensor-based time-series data
* Detect abnormal sensor readings using Machine Learning
* Identify unusual patterns in vibration, temperature, pressure, humidity, and load
* Apply Isolation Forest algorithm for anomaly detection
* Evaluate model performance using accuracy, confusion matrix, precision, recall, and F1-score
* Visualize sensor readings and detected anomalies
* Save final prediction results for further analysis

## Technologies Used

* Python – Core programming
* Pandas – Data handling and analysis
* NumPy – Numerical computation
* Matplotlib – Data visualization
* Scikit-learn – Machine learning model building
* Isolation Forest – Anomaly detection algorithm
* CSV – Dataset storage and prediction output

## Features

* Sensor data analysis
* Time-series data handling
* Anomaly detection using Isolation Forest
* Detection of abnormal vibration, temperature, pressure, humidity, and load patterns
* Model evaluation using classification metrics
* Graphical visualization of sensor readings
* Visualization of detected anomalies
* Final prediction file generation

## Demo

vibration_sensor_plot.png

anomaly_detection_plot.png

## Installation / Setup

Clone the repository:

```bash
git clone https://github.com/khushboo-datasci/Sensor-Anomaly-Detection-Predictive-Maintenance.git
```

Navigate to the project folder:

```bash
cd Sensor-Anomaly-Detection-Predictive-Maintenance
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python sensor_anomaly_detection.py
```

Or open the notebook:

```bash
jupyter notebook sensor_anomaly_detection.ipynb
```

## Usage

* Load the sensor dataset
* Analyze dataset information and summary statistics
* Visualize vibration sensor readings over time
* Train the Isolation Forest anomaly detection model
* Predict normal and abnormal sensor readings
* Evaluate the model using accuracy, confusion matrix, and classification report
* Visualize detected anomalies
* Save final predictions into a CSV file

## Step-by-Step Flow

**Import Libraries** – Load required Python libraries for data analysis, visualization, and machine learning.

**Load Dataset** – Read sensor data from CSV file and convert timestamp column into datetime format.

**Data Inspection** – Check dataset shape, column information, missing values, duplicate values, and statistical summary.

**Visualize Sensor Pattern** – Plot vibration sensor readings over time to understand normal and abnormal behavior.

**Feature Selection** – Select vibration, temperature, pressure, humidity, and load as input features.

**Train Model** – Apply Isolation Forest algorithm to detect anomalies in sensor data.

**Prediction Mapping** – Convert model output into normal and anomaly labels.

**Model Evaluation** – Evaluate results using accuracy, confusion matrix, precision, recall, and F1-score.

**Visualize Detected Anomalies** – Highlight detected abnormal sensor readings on the graph.

**Save Results** – Store final predictions in a CSV file for further use.

## Model Performance

The model achieved strong performance on the simulated sensor dataset.

**Accuracy:** 1.0

**Confusion Matrix:**

```text
[[1140    0]
 [   0   60]]
```

**Classification Report:**

```text
              precision    recall  f1-score   support

           0       1.00      1.00      1.00      1140
           1       1.00      1.00      1.00        60

    accuracy                           1.00      1200
   macro avg       1.00      1.00      1.00      1200
weighted avg       1.00      1.00      1.00      1200
```

## Note

This project uses a synthetic sensor dataset where anomalies were intentionally added to represent abnormal machine or infrastructure behavior.

Since the anomalies are clearly separated from normal readings, the model achieved very high accuracy. On real-world noisy sensor data, model performance may vary and further preprocessing, tuning, and validation would be required.

## Real-World Use Case

This type of anomaly detection system can be used in:

* Predictive maintenance
* Structural health monitoring
* Machine condition monitoring
* Industrial sensor analysis
* Early fault detection
* Equipment failure prevention

## Author

**Khushboo Kumari**
GitHub: https://github.com/khushboo-datasci

Confusion Matrix:

[[1140 0]
[ 0 60]]

Classification Report:

precision recall f1-score support

0 1.00 1.00 1.00 1140
1 1.00 1.00 1.00 60

accuracy 1.00 1200
macro avg 1.00 1.00 1.00 1200
weighted avg 1.00 1.00 1.00 1200

Note
This project uses a synthetic sensor dataset where anomalies were intentionally added to represent abnormal machine or infrastructure behavior.

Since the anomalies are clearly separated from normal readings, the model achieved very high accuracy. On real-world noisy sensor data, model performance may vary and further preprocessing, tuning, and validation would be required.

Real-World Use Case
This type of anomaly detection system can be used in:

Predictive maintenance
Structural health monitoring
Machine condition monitoring
Industrial sensor analysis
Early fault detection
Equipment failure prevention



Author
Khushboo Kumari
https://github.com/khushboo-datasci
