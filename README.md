# ⚡ Household Energy Consumption Forecasting

## Overview

This project predicts household energy consumption using Machine Learning and historical electricity usage data. The model analyzes electrical measurements and time-based features to estimate power consumption.

The project was developed as part of my Machine Learning and Data Analytics learning journey to gain practical experience with real-world datasets, data preprocessing, visualization, feature engineering, and predictive modeling.

---

## Objectives

* Analyze household electricity consumption patterns.
* Clean and preprocess a large real-world dataset.
* Create meaningful visualizations for data analysis.
* Build a Machine Learning model for energy consumption prediction.
* Evaluate model performance using regression metrics.
* Save preprocessing components for future predictions.

---

## Dataset

This project uses the **Individual Household Electric Power Consumption Dataset** from the UCI Machine Learning Repository.

Due to GitHub file size limitations, the dataset is not included in this repository.

### Download Dataset

Download the dataset from:

https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

After downloading, place the CSV file in the project directory before running the code.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib

---

## Features Used

The model uses:

* Voltage
* Global Reactive Power
* Global Intensity
* Sub Metering 1
* Sub Metering 2
* Sub Metering 3
* Hour
* Day
* Month

Target Variable:

* Global Active Power

---

## Project Workflow

### 1. Data Preprocessing

* Loaded the dataset
* Handled missing values
* Converted data types
* Created DateTime features
* Removed duplicates
* Prepared data for training

### 2. Exploratory Data Analysis

Visualizations created:

* Power Consumption Distribution
* Voltage vs Power Consumption
* Correlation Heatmap
* Actual vs Predicted Comparison
* Feature Importance Analysis

### 3. Model Training

Algorithm Used:

**Random Forest Regressor**

The model was trained to predict household energy consumption based on electrical and time-related features.

### 4. Model Evaluation

Evaluation metrics used:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Results

Model Performance:

| Metric   | Value  |
| -------- | ------ |
| MAE      | 0.0184 |
| RMSE     | 0.0362 |
| R² Score | 0.999  |

The model achieved excellent predictive performance on the test dataset.

---

## Visualizations

The project includes:

* Energy Consumption Distribution
* Voltage vs Power Consumption Scatter Plot
* Correlation Matrix Heatmap
* Actual vs Predicted Comparison
* Feature Importance Chart

Screenshots are available inside the **screenshots/** folder.

---

## Project Structure

```text
Household-Energy-Consumption-Forecasting/
│
├── Energy Consumption Forecasting.py
├── scaler.pkl
├── requirements.txt
├── README.md
├── .gitignore
│
└── screenshots/
    ├── power_distribution.png
    ├── voltage_vs_power.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── feature_importance.png
```

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

Or install from requirements.txt:

```bash
pip install -r requirements.txt
```

---

## Running the Project

```bash
python "Energy Consumption Forecasting.py"
```

The script will:

* Load and preprocess the dataset
* Train the model
* Generate visualizations
* Evaluate performance
* Create model files locally

---

## Note

The following files are excluded from this repository because of GitHub file size limitations:

* household_power_consumption.csv
* energy_model.pkl

The model can be retrained locally by running the project script.

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Machine Learning
* Regression Modeling
* Model Evaluation
* Model Persistence

---

## Future Improvements

* Time Series Forecasting
* XGBoost Regression
* LSTM Neural Networks
* Streamlit Dashboard
* Real-Time Energy Monitoring
* Cloud Deployment

---

## Author

**Gorle Jani Venkata Pavan Sai Jeevan**

Engineering Student | Python Developer | Machine Learning & Data Analytics Enthusiast

Always learning and building real-world data-driven solutions.
