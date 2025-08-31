# Flood Prediction Using Machine Learning

# Project Overview

Floods are among the most destructive natural disasters, affecting millions of people worldwide. Predicting floods in advance can help governments, disaster management authorities, and local communities prepare better and reduce damages.


# Dataset

File: flood.csv
Size: 50,000 rows × 21 columns
Features :
1. MonsoonIntensity
2. TopographyDrainage
3. Urbanization
4. Deforestation
5. ClimateChange
6. DamsQuality
7. DrainageSystems
8. CoastalVulnerability
9. PopulationScore
10. FloodProbability (Target Variable)

All features are numeric (int64) with no missing values.


# Objectives

1. Perform EDA to understand key factors influencing floods.
2. Build ML models (Linear Regression, Random Forest, XGBoost) to predict Flood Probability.
3. Evaluate models using metrics like R², RMSE.
4. Identify the most important features contributing to floods.
5. Deploy an interactive app using Streamlit for real-time flood risk prediction.


# Tech Stack

Language: Python 
Libraries:
pandas, numpy (data handling)
seaborn, matplotlib (visualization)
scikit-learn (ML models)
xgboost / lightgbm (boosting models)
streamlit (deployment - optional)


# Methodology

1. Data Loading & Cleaning – Load dataset, check datatypes, null values.
2. Exploratory Data Analysis (EDA) – Correlation heatmaps, feature-target relationships.
3. Preprocessing – Scaling, train-test split.
4. Modeling – Train Linear Regression, Random Forest, XGBoost.
5. Evaluation – Compare models with R² and RMSE.
6. Feature Importance – Identify top contributors (e.g., MonsoonIntensity, Urbanization).
7. Deployment – Build an interactive prediction tool.
