# Task 07 - Support Vector Machine
## Objective

Implement Support Vector Machine (SVM) models for binary classification using both Linear and RBF kernels, evaluate their performance, tune hyperparameters, and validate the model using cross-validation.

---

## Dataset

Breast Cancer Wisconsin Diagnostic Dataset

### Target Variable

- diagnosis
  - M = Malignant
  - B = Benign

---

## Steps Performed

1. Loaded and explored the dataset.
2. Removed the unnecessary `id` column.
3. Separated features and target variable.
4. Split the dataset into training and testing sets.
5. Standardized the feature values using StandardScaler.
6. Trained an SVM model with a Linear kernel.
7. Trained an SVM model with an RBF kernel.
8. Compared model performance using:
   - Accuracy Score
   - Classification Report
   - Confusion Matrix
9. Tuned hyperparameters (`C` and `gamma`) for the RBF kernel.
10. Evaluated the final model using 5-Fold Cross Validation.

---

## Results

The SVM models successfully classified breast cancer tumors into benign and malignant categories. Performance was evaluated using Accuracy Score, Classification Report, Confusion Matrix, and Cross Validation to assess model reliability.

---

## Learning Outcomes

- Understanding Support Vector Machines (SVM)
- Difference between Linear and RBF kernels
- Importance of feature scaling
- Hyperparameter tuning using `C` and `gamma`
- Model evaluation using Cross Validation