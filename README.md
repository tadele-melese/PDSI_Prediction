# PDSI Prediction Using Machine Learning

## Overview

The Palmer Drought Severity Index (PDSI) is a widely used measure of drought severity, providing insights into the moisture status of a region. This project focuses on predicting PDSI values using machine learning techniques, which can help in early drought detection and water resource management.

## Objectives

- **Develop a Machine Learning Model**: Create a predictive model to estimate PDSI values based on various climatic and environmental predictors.
- **Evaluate Model Performance**: Assess the accuracy and effectiveness of different machine learning algorithms in predicting PDSI.
- **Visualize Results**: Provide visual representations of predictions versus actual values to understand the model's performance.

## Methodology

1. **Data Collection**: 
   - Gather data from reliable sources, including meteorological data (precipitation, temperature, etc.) and soil moisture measurements.
   - Utilize the [TerraClimate](https://climateex.com/) dataset for comprehensive climate data.

2. **Data Preprocessing**: 
   - Clean and preprocess the data to handle missing values, normalize features, and create appropriate training and testing datasets.
   - Classify PDSI values into drought/wetness classes for better model training.

3. **Feature Selection**: 
   - Identify key predictors influencing PDSI, including:
     - Precipitation (`pr`)
     - Maximum and minimum temperatures (`tmmx`, `tmmn`)
     - Soil moisture (`soil`)
     - Evapotranspiration (`aet`, `pet`)
     - Solar radiation (`srad`)
     - Vapor pressure (`vap`)

4. **Model Development**: 
   - Implement various machine learning algorithms, including:
     - Decision Trees
     - Random Forest
     - Support Vector Machines (SVM)
     - Gradient Boosting Machines (GBM)
     - Neural Networks

5. **Model Evaluation**: 
   - Evaluate model performance using metrics such as:
     - Accuracy
     - Precision
     - Recall
     - F1 Score
     - Confusion Matrix
     - ROC Curve and AUC Score

6. **Deployment**: 
   - Develop a Streamlit dashboard to allow users to input predictor values and visualize PDSI predictions interactively.
   - Incorporate spatial mapping of PDSI predictions for geographic insights.

## Expected Outcomes

- A robust machine learning model capable of predicting PDSI values with high accuracy.
- Insights into the relationship between climate variables and drought severity.
- A user-friendly dashboard for stakeholders in agriculture, water management, and environmental planning.

## Conclusion

The successful implementation of this project can significantly contribute to effective drought management strategies, aiding in decision-making processes for sustainable resource utilization.
