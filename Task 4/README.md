# Task 4 - Classification with Logistic Regression

## Objective
Build a binary classification model using Logistic Regression to classify breast tumors as Malignant or Benign.


## Steps Performed
1. Loaded the Breast Cancer Wisconsin dataset.
2. Removed unnecessary columns (`id` and `Unnamed: 32`).
3. Encoded the target variable (`M` → 1, `B` → 0).
4. Split the dataset into training and testing sets.
5. Standardized the numerical features using StandardScaler.
6. Trained a Logistic Regression model.
7. Predicted class labels and probabilities.
8. Evaluated the model using Accuracy, Precision, Recall, ROC-AUC, and Confusion Matrix.

## Model Performance
- Accuracy: 97.37%
- Precision: 97.62%
- Recall: 95.35%
- ROC-AUC: 99.74%

## Conclusion
The Logistic Regression model achieved excellent classification performance on the Breast Cancer Wisconsin dataset. It correctly classified most benign and malignant tumors, with very high precision and recall, making it an effective binary classification model.