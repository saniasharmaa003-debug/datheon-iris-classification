# datheon-iris-classification
Multi-Class Benchmark Classification using Logistic Regression and Decision Tree
# Multi-Class Benchmark Classification Pipeline – Iris Dataset

## Project Overview
This project implements an end-to-end supervised machine learning classification pipeline using the Iris dataset.

The objective is to train and compare two classification algorithms:
- Logistic Regression
- Decision Tree Classifier

## Dataset
The Iris dataset contains three flower species:
- Setosa
- Versicolor
- Virginica

**Features:** Sepal Length, Sepal Width, Petal Length, Petal Width

**Target:** Species

**Dataset Source:** https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow
1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Class distribution visualization
4. Pairplot visualization
5. Duplicate detection and removal
6. Feature and target separation
7. Train-test split (80:20)
8. Feature scaling using StandardScaler
9. Model training using Logistic Regression and Decision Tree
10. Model evaluation
11. Confusion matrix visualization
12. Decision boundary visualization

## Model Performance

| Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 93.33% | 93.33% |
| Precision (Weighted) | 93.33% | 93.33% |
| Recall (Weighted) | 93.33% | 93.33% |
| F1-Score (Weighted) | 93.33% | 93.33% |

## Key Observations
- One duplicate record was identified and removed.
- Setosa was clearly separable from the other two species.
- Both models correctly classified 28 out of 30 test samples.
- Both models achieved an accuracy of 93.33%.

## Conclusion
Both Logistic Regression and Decision Tree performed well on the Iris dataset, achieving 93.33% accuracy. This project demonstrates a complete multiclass classification workflow, from data preprocessing to model evaluation.

## Author
Sania Sharma
