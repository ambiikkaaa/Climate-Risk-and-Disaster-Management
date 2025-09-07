This contains weekly progress for the project **Flood Prediction using Machine Learning**, focusing on analyzing flood datasets to identify risks, trends, and key predictive features.  

---

## Week 1: Understanding the Data  
In Week 1, the focus was on **getting familiar with the dataset**.  
The following steps were performed:  
- Imported necessary libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`).  
- Loaded the dataset (`flood.csv`).  
- Displayed the **first few rows** to understand structure.  
- Checked **data types, missing values, duplicates**, and **unique values**.  
- Generated **statistical summaries** for numerical columns.  
- Created **correlation matrix** to see relationships between numerical features.  

*Outcome:* Basic understanding of dataset, its quality, and relationships between variables.  

---

## Week 2: EDA, Data Transformation, and Feature Selection  
In Week 2, the project moved towards **data exploration and preparation** for modeling.  
The following steps were carried out:  
- **Distribution Plots:** Visualized the spread of numerical features.  
- **Correlation Heatmap:** Identified strong correlations between variables.  
- **Boxplots:** Detected outliers in the dataset.  
- **Skewness Analysis:** Checked imbalance in data distribution.  
- **Standard Scaling:** Normalized independent features for consistency.  
- **Feature Importance:** Used `RandomForestRegressor` to rank features based on their impact on predicting flood probability.  

*Outcome:* Clear insights on important features, data normalization, and handling skewness/outliers for future modeling.  

---
