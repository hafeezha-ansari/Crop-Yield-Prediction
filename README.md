# Crop Yield Prediction Using Weather and Soil Conditions

## About the Project

This project uses Supervised Machine Learning to predict crop yield based on different weather and soil conditions.

The main goal is to understand how environmental factors and soil properties influence agricultural productivity and to identify the most important factors affecting crop yield.

A Random Forest Regression model is used to train the system and predict crop yield.

## Objectives

- Predict crop yield using Machine Learning.
- Analyse the impact of weather conditions on crop production.
- Understand the importance of soil nutrients and moisture.
- Identify the most influential features affecting crop yield.
- Evaluate the performance of the trained model.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Input Features

The model uses the following seven input features:

- Temperature (°C)
- Rainfall (mm)
- Soil Moisture (%)
- Soil pH
- Nitrogen (kg/ha)
- Phosphorus (kg/ha)
- Potassium (kg/ha)

## Machine Learning Algorithm

**Random Forest Regressor**

The dataset is divided into training and testing sets using an 80:20 split. The Random Forest model is trained using 100 decision trees to predict crop yield.

## Dataset Information

- Total Records: 400
- Total Features: 9
- Crop Types: Rice, Wheat, Maize, Cotton, and Soybean
- Missing Values: 0

## Model Performance

The model was evaluated using the following regression metrics:

| Evaluation Metric | Result |
| ----------------- | ------ |
| MAE               | 0.5024 |
| MSE               | 0.3784 |
| RMSE              | 0.6152 |
| R² Score          | 0.5758 |

## Feature Importance

Soil Moisture was the most influential feature in the trained Random Forest model, contributing approximately 51.2% of the total feature importance.

The next important factors were:

- Nitrogen
- Rainfall
- Phosphorus
- Potassium
- Soil pH
- Temperature

## Results and Visualisation

The project includes visualisations to understand model performance and feature importance:

- Actual vs Predicted Crop Yield
- Feature Importance Graph
- Model Evaluation Results

## Sample Prediction

The notebook includes an interactive prediction section where users can enter temperature, rainfall, soil moisture, soil pH, nitrogen, phosphorus, and potassium values to obtain a predicted crop yield.

## Future Improvements

- Use larger and more diverse agricultural datasets.
- Experiment with different Machine Learning algorithms.
- Improve prediction accuracy.
- Include additional environmental and agricultural factors.
- Develop a user-friendly crop yield prediction interface.

## Author

**Hafeezha Ansari**

B.Sc. Data Science Student
