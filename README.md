# Crop Yield Prediction

## Project Overview
This repository contains a machine learning system for accurately predicting crop yields based on environmental factors and historical data specific to Indian conditions. The goal is to enhance agricultural productivity, resource management, and sustainability while ensuring food security.

## Objectives
- Accurately forecast crop yields in a given area.
- Inform decision-making for farmers and policymakers regarding planting, harvesting, and distribution.
- Improve crop yields, reduce waste, and increase profitability for farmers.
- Optimize resource management and adapt to changing environmental conditions.
- Promote sustainable agriculture and preserve natural resources.

## System Workflow

### Model Development
- Machine learning models are developed using regression algorithms such as Random Forest, Decision Tree, and Linear Regression.
- The models are trained on historical crop data from Indian regions to improve yield prediction accuracy.

### Experimentation and Result Analysis
- **Data Collection and Preprocessing**: 
  - The dataset consists of multiple features affecting crop yield:
    - **State_Name**
    - **Crop_Year**
    - **Crop_Name**
    - **Season**
    - **Area**
    - **Production**
    - **Rainfall**
    - **Minimum Selling Price**
    - **Yield**
  - Preprocessing steps include handling missing values, encoding categorical variables, and normalizing numerical features.

- **Model Selection and Training**:
  - The best-performing models are selected using k-fold cross-validation.
  - Evaluation metrics such as R2 score and Mean Absolute Error (MAE) are used to assess model performance.

- **Model Deployment**:
  - The trained models are saved as pickle (`.pkl`) files for easy reuse.
  - These models can be loaded and used for real-time predictions.


## Conclusion
The Crop Yield Prediction System provides farmers and policymakers with valuable insights to enhance agricultural productivity. By leveraging machine learning techniques on historical Indian crop data, the system aims to improve yield forecasts, optimize resource utilization, and support sustainable farming practices.


