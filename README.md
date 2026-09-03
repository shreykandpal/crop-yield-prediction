# Prediction of Agriculture Crop Production & Yield in India

## Project Overview :
This project builds a Machine Learning regression pipeline to predict agricultural **Crop Yield (Quintals per Hectare)** in India based on regional factors (State), crop varieties, and cultivation costs per hectare.

## Dataset
* **Source:** Open Government Data (OGD) Platform India (`data.gov.in`)
* **Primary Attributes:** `Crop`, `State`, `Cost of Cultivation (₹/Hectare) A2+FL`, `Cost of Cultivation (₹/Hectare) C2`, `Cost of Production (₹/Quintal) C2`, and `Yield (Quintal/Hectare)`.

## Workflow & Methodology
1. **Data Cleaning & Standardization:** Cleaned column headers and formatted state and crop names.
2. **Exploratory Data Analysis (EDA):** Evaluated crop-specific yield variations and cost-to-yield relationships using Seaborn and Matplotlib.
3. **Feature Engineering:** Applied One-Hot Encoding to categorical variables (`Crop`, `State`).
4. **Model Training:** Split data into 80% training and 20% testing sets. Trained a baseline **Linear Regression** model and an ensemble **Random Forest Regressor**.
5. **Model Evaluation:** Evaluated performance using $R^2$ Score, Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).



*Key Insight:* The Random Forest model achieved superior performance due to its ability to capture non-linear relationships and regional state-crop interaction effects.
