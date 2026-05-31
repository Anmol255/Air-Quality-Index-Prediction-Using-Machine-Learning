# Air Quality Index Prediction Using Machine Learning

## Overview
Air pollution is one of the most critical environmental challenges affecting human health and urban sustainability. Accurate prediction of air quality enables proactive decision-making and helps authorities implement effective pollution control measures.
This project focuses on predicting air quality indicators using Machine Learning techniques applied to environmental sensor data from the UCI Air Quality Dataset. A comparative study was performed using Linear Regression and Random Forest Regression models to evaluate their effectiveness in modeling complex air quality patterns.

## Problem Statement
Traditional air quality monitoring systems provide real-time measurements but often lack predictive capabilities.The objective of this project is to develop machine learning models capable of predicting air quality parameters based on sensor measurements and environmental conditions, enabling data-driven forecasting and analysis.

## Dataset-UCI Air Quality Dataset
The dataset contains atmospheric sensor measurements collected from an Italian city and includes:
- Carbon Monoxide (CO)
- Benzene Concentration
- Nitrogen Oxides
- Temperature
- Relative Humidity
- Absolute Humidity
- Various Air Quality Sensor Readings

## Project Workflow
### 1. Data Preprocessing
- Removed unnecessary attributes
- Handled missing values
- Replaced invalid sensor readings
- Cleaned feature names
- Converted data types for analysis

### 2. Exploratory Data Analysis
- Statistical analysis of features
- Correlation analysis
- Feature relationship visualization
- Data distribution assessment

### 3. Model Development
Two supervised machine learning models were implemented and compared:

#### Linear Regression
Used as a baseline model to capture linear relationships between environmental variables and air quality indicators.

#### Random Forest Regressor
An ensemble learning approach capable of modeling nonlinear patterns and complex interactions within the dataset.

### 4. Model Evaluation
Performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

## Machine Learning Concepts Applied
- Supervised Learning
- Regression Analysis
- Ensemble Learning
- Feature Engineering
- Data Preprocessing
- Model Evaluation
- Comparative Model Analysis
  
## Results
MODEL- LINEAR REGRESSION
1. MAE: nil
2. MSE: 0.057925294247378564
3. R2 Score: 0.9721733275987304

MODEL- RANDOM FOREST REGRESSOR
1. MAE: 0.26526908107372416
2. RMSE: 0.3853007587593442
3. R2 Score: 0.9286830510513921

### Key Findings
- Random Forest demonstrated improved performance due to its ability to model nonlinear relationships.
- Linear Regression provided an interpretable baseline for comparison.
- Proper data preprocessing significantly improved model reliability.

## Applications
Potential real-world applications include:
- Smart City Monitoring
- Environmental Risk Assessment
- Air Pollution Forecasting
- Public Health Analytics
- IoT-Based Environmental Monitoring Systems

## Future Scope
Future enhancements may include:
- XGBoost and Gradient Boosting models
- Deep Learning approaches
- Real-time AQI prediction dashboards
- IoT sensor integration
- Time-series forecasting using LSTM networks
- Deployment as a web application

## Repository Structure
├── AQI_Prediction.ipynb
├── requirements.txt
├── README.md
└── images/
