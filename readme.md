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

## Topics Covered

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

### 4. Metadata Routing

### 5. Inspection

### 6. Visualizations

### 7. Dataset Transformations

### 8. Dataset Loading Utilities

### 9. Computing with Scikit-Learn

### 10. Model Persistence

### 11. Common Pitfalls and Best Practices

### 12. Dispatching

### 13. Choosing the Right Estimator

### 14. External Resources

---

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


