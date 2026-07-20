# Task 06 - K-Nearest Neighbors (KNN) Classification

## Objective

The objective of this task is to implement the K-Nearest Neighbors (KNN) classification algorithm on the Iris dataset, apply feature normalization, evaluate model performance, and analyze the effect of different values of K.

---

## Dataset

**Dataset:** Iris Flower Dataset

The dataset contains measurements of iris flowers belonging to three different species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target

- Species

---

## Workflow

1. Imported required libraries.
2. Loaded and explored the dataset.
3. Removed unnecessary columns.
4. Split features and target labels.
5. Performed train-test split.
6. Applied feature scaling using StandardScaler.
7. Built a K-Nearest Neighbors classifier.
8. Trained the model.
9. Made predictions on the test dataset.
10. Evaluated performance using:
    - Accuracy Score
    - Classification Report
    - Confusion Matrix
11. Experimented with different values of K.
12. Visualized Accuracy vs K.

---

## Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Key Learning Outcomes

- Understanding the K-Nearest Neighbors algorithm
- Importance of feature scaling in distance-based algorithms
- Effect of different K values on model performance
- Model evaluation using confusion matrix and accuracy
- Choosing an appropriate K value