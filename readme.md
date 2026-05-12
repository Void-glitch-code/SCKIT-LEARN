# 😎😎Scikit-Learn Learning Repository

A structured repository for learning and practicing machine learning using Scikit-Learn.

Official Documentation: https://scikit-learn.org/stable/

---

## ☠️☠️Overview

This repository is built to provide:

- Conceptual understanding of machine learning
- Hands-on implementation using Python
- End-to-end model building workflows
- Practical examples from official documentation
- Notes and experiments for deeper understanding

---

## 🤖🤖Topics Covered

### 1. Supervised Learning
- Linear Regression
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines
- K-Nearest Neighbors
- Gradient Boosting

### 2. Unsupervised Learning
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- PCA

### 3. Model Selection and Evaluation
- Train/Test Split
- Cross Validation
- GridSearchCV
- RandomizedSearchCV
- Performance Metrics

### 4. Metadata Routing
Passing metadata across estimators and pipelines.


### 5. Inspection
Understanding model behavior.

Includes:

-Feature Importance
-Partial Dependence Plots
-Permutation Importance


### 6. Visualizations
Model insights through plots.

Includes:

Confusion Matrix
ROC Curve
Precision-Recall Curve
Learning Curves

### 7. Dataset Transformations
Data preprocessing techniques.

Includes:

Scaling
Encoding
Normalization
Feature Engineering

### 8. Dataset Loading Utilities
Working with built-in datasets.

Examples:

Iris
Digits
Wine
Breast Cancer
California Housing

### 9. Computing with Scikit-Learn
Efficient computation strategies.

Includes:

Parallel Processing
Memory Optimization
Sparse Data Handling

### 10. Model Persistence
Saving and loading trained models.

Includes:

Pickle
Joblib

### 11. Common Pitfalls and Best Practices
Avoiding mistakes in ML workflows.

### 12. Dispatching
Advanced estimator behavior and routing.

### 13. Choosing the Right Estimator
Selecting models based on problem type.

Estimator Map:
Choosing the Right Estimator Guide(https://scikit-learn.org/stable/machine_learning_map.html)

## Repository Structure

```bash
scikit-learn-learning/
├── supervised_learning/
├── unsupervised_learning/
├── preprocessing/
├── model_evaluation/
├── visualization/
├── projects/
└── notes/
```

---

## Installation

```bash
pip install scikit-learn numpy pandas matplotlib seaborn jupyter
```

---

## Example

```python
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier

X, y = load_iris(return_X_y=True)

X_train, X_test, y_train, y_test = train_test_split(X, y)

model = RandomForestClassifier()
model.fit(X_train, y_train)

print(model.score(X_test, y_test))
```

---

## Resources

- https://scikit-learn.org/stable/
- https://scikit-learn.org/stable/user_guide.html
- https://scikit-learn.org/stable/tutorial/

License

Educational use only.
Based on examples and concepts from the official scikit-learn documentation.
