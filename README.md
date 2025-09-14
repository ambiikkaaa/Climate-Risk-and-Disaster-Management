# Flood Prediction Using Machine Learning

# Project Overview

Floods are among the most destructive natural disasters, affecting millions of people worldwide. Predicting floods in advance can help governments, disaster management authorities, and local communities prepare better and reduce damages.


# Dataset

- File: flood.csv
- Size: 50,000 rows × 21 columns
- Features :
  - MonsoonIntensity
  - TopographyDrainage
  - Urbanization
  - Deforestation
  - ClimateChange
  - DamsQuality
  - DrainageSystems
  - CoastalVulnerability
  - PopulationScore
  - FloodProbability (Target Variable)

All features are numeric (int64) with no missing values.

Source : https://www.kaggle.com/datasets/naiyakhalid/flood-prediction-dataset

# Objectives

1. Understand and preprocess real-world flood data.
2. Perform EDA with visualizations (heatmaps, histograms, boxplots).
3. Apply data transformation and feature selection techniques.
4. Train and evaluate a Random Forest Classifier for flood risk prediction.
5. Build a Streamlit web interface for easy user interaction and predictions.


# Tech Stack

- **Programming Language**: Python   
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib  
- **Machine Learning Model**: Random Forest Classifier  
- **Web Framework**: Streamlit  
- **Version Control**: Git & GitHub


# Methodology

1. **Data Collection** – Import flood dataset (CSV).  
2. **Data Understanding** – Explore dataset structure, missing values, summary stats.  
3. **EDA** – Distribution plots, correlation heatmap, outlier detection.  
4. **Data Preprocessing** – Scaling & transformation of features.  
5. **Feature Selection** – Identify most important predictors.  
6. **Model Training** – Train Random Forest Classifier on processed data.  
7. **Model Evaluation** – Accuracy, confusion matrix, feature importance.  
8. **Deployment** – Create a Streamlit app for real-time predictions.
