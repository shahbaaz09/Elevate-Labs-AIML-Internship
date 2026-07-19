# Task 5: Decision Trees and Random Forests

## Objective
Learn and implement Decision Tree and Random Forest algorithms for classification, understand overfitting, control tree depth, evaluate model performance, and analyze feature importance.

---

## Dataset
**Heart Disease Dataset**

- Rows: 1025
- Columns: 14
- Target Column: `target`
- Missing Values: None

---
## Project Workflow

### 1. Data Loading
- Imported the Heart Disease dataset.
- Inspected the dataset using:
  - `head()`
  - `shape`
  - `info()`
  - `describe()`
  - `isnull().sum()`

### 2. Data Preparation
- Split features and target.
- Created training and testing datasets using `train_test_split()`.

### 3. Decision Tree Classifier
- Trained a Decision Tree model.
- Evaluated model accuracy.
- Generated Confusion Matrix.
- Generated Classification Report.
- Visualized the Decision Tree.

### 4. Controlling Overfitting
- Trained another Decision Tree using `max_depth=3`.
- Compared performance with the unrestricted tree.
- Observed the effect of limiting tree depth.

### 5. Random Forest Classifier
- Trained a Random Forest with 100 Decision Trees.
- Evaluated using Accuracy and Confusion Matrix.

### 6. Feature Importance
- Calculated feature importance.
- Visualized the importance using a bar chart.

---

## Results

### Decision Tree
- Successfully trained and visualized.
- Achieved high accuracy.
- Learned how unrestricted trees can overfit.

### Decision Tree (max_depth=3)
- Simpler and more interpretable.
- Lower accuracy but reduced overfitting.

### Random Forest
- Achieved excellent classification performance.
- Correctly classified almost all samples.
- Provided feature importance ranking.

---

## Feature Importance (Highest to Lowest)

1. Chest Pain (cp)
2. Number of Major Vessels (ca)
3. Maximum Heart Rate (thalach)
4. ST Depression (oldpeak)
5. Thalassemia (thal)
6. Age
7. Cholesterol
8. Resting Blood Pressure
9. Exercise Induced Angina
10. Slope
11. Sex
12. Rest ECG
13. Fasting Blood Sugar

---

## Key Learnings

- Working of Decision Trees
- Gini Impurity
- Tree Visualization
- Overfitting in Decision Trees
- Controlling Tree Depth
- Ensemble Learning
- Random Forest Classifier
- Majority Voting
- Feature Importance
- Model Evaluation

---


