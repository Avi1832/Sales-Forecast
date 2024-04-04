# Sales-Forecast
# Sales Forecast Data Analysis and Prediction

This repository contains code for analyzing sales forecast data and predicting future sales using linear regression model.

## Tools Used

- Python
- Pandas

- NumPy
- Matplotlib

- XGBoost
- Scikit-learn

- TensorFlow

## Data Preprocessing

- Loaded sales forecast data from a CSV file
- Converted date column to datetime format

- Grouped data by date and calculated monthly sales
- Calculated the difference in sales between consecutive months

## Data Modeling

- Created a supervised dataset for training the model
- Split the data into training and testing sets

- Applied MinMax scaling to normalize the data
- Trained a Linear Regression model on the training data

- Predicted sales for the test data using the trained model

## Evaluation

- Calculated Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score for the predictions
- Plotted the actual sales data and predicted sales for visualization

## Results

- The Linear Regression model achieved an MSE of 16221.27, MAE of 12433.18, and R2 score of 0.9906

For more details, refer to the code in the repository.
