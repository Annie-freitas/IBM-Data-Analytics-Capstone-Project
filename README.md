# Regression on Housing Data

This project demonstrates the application of linear regression models to predict house prices based on selected features. 
The dataset contains information about various properties, including square footage, and target variable 'price'. 

In this project, I have implemented the following:

1. **Data Preparation:**
   - Loaded and cleaned the data (including handling missing values).
   - Performed feature selection and transformed data when necessary.

2. **Modeling:**
   - Fitted a **Linear Regression** model to predict the `price` using the feature `sqft_living`.
   - Evaluated the model using R² to measure the fit of the data.

3. **Validation:**
   - Split data into **train** and **test** sets.
   - Calculated the **R²** value to evaluate model performance.

## Project Details:

- **Feature** used for prediction: `sqft_living`.
- **Target variable**: `price`.
- **Model**: Linear Regression.
- **Evaluation metric**: R² (coefficient of determination).

## Tools Used:

To run this project locally, you will need the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib` (optional, for visualizations)
- `seaborn` (optional, for visualizations)

