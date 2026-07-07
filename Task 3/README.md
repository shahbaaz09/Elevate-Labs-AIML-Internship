# Task 3 - Linear Regression

## Objective
Build and evaluate Simple and Multiple Linear Regression models for house price prediction.

## Steps Performed
1. Loaded the Housing dataset.
2. Explored the dataset using Pandas.
3. Checked for missing values.
4. Encoded categorical features using Label Encoding and One-Hot Encoding.
5. Split the dataset into training and testing sets.
6. Trained a Multiple Linear Regression model.
7. Predicted house prices on the test dataset.
8. Evaluated the model using MAE, MSE, RMSE, and R² Score.
9. Visualized Actual vs Predicted house prices.

## Model Performance
- MAE: 970043.40
- MSE: 1754318687330.66
- RMSE: 1324506.96
- R² Score: 0.6529

## Observation
 The scatter plot shows a positive relationship between the actual and predicted house prices. Although the predictions generally follow the actual values, some deviations are present, indicating prediction errors. The model captures the overall trend reasonably well, which is consistent with the obtained R² score of approximately 0.65.

## Conclusion
The Linear Regression model successfully learned the relationship between the input features and house prices. The model achieved an R² score of approximately 0.65, indicating a good fit for the dataset and providing reasonably accurate predictions.