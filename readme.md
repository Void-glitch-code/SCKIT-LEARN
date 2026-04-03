# 🧠 Scikit-Learn Learning Project 

## 📌 Overview

This project is part of a structured journey to master **Scikit-learn** from basics to advanced level.
It covers:

* Day 1: Core ML pipeline
* Day 2: Real-world data preprocessing with pipelines

---

## 🚀 What This Project Demonstrates

### ✅ Day 1 — ML Pipeline Basics

* Loading dataset (Iris)
* Train-test split
* Feature scaling (StandardScaler)
* Model training (Logistic Regression, KNN)
* Prediction and evaluation

---

### ✅ Day 2 — Real-World Preprocessing

* Handling missing values
* Encoding categorical data
* Using `ColumnTransformer`
* Building full pipelines
* Training models on mixed data types

---

## ⚙️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn

---

## 📂 Project Structure

```
project/
│
├── day1_pipeline.ipynb
├── day2_preprocessing.ipynb
├── README.md
```

---

## 📊 Workflow (Core ML Loop)

```
Load Data → Preprocess → Split → Train → Predict → Evaluate
```

---

## 🔧 Installation

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## ▶️ How to Run

1. Open Jupyter Notebook or VS Code
2. Run:

   * `day1_pipeline.ipynb`
   * `day2_preprocessing.ipynb`
3. Execute cells step by step

---

## 🧪 Key Concepts Covered

### Day 1

* `train_test_split`
* `StandardScaler`
* `fit()` vs `transform()`
* Model training
* Accuracy evaluation

---

### Day 2

* `SimpleImputer`
* `OneHotEncoder`
* `ColumnTransformer`
* `Pipeline`

---

## ⚠️ Important Learnings

* Small datasets give unreliable accuracy
* Scaling affects distance-based models (KNN, SVM)
* Never fit preprocessing on test data (data leakage)
* Real ML = preprocessing + pipelines, not just models

---

## 📈 Sample Results

| Experiment                 | Accuracy        |
| -------------------------- | --------------- |
| Iris (Logistic Regression) | ~0.9–1.0        |
| Small Custom Dataset       | ~0.5 (unstable) |
| Larger Dataset             | ~0.75–0.9       |

---

## 🔥 Future Improvements

* Add hyperparameter tuning (GridSearchCV)
* Try advanced models (Random Forest, SVM)
* Build end-to-end ML app (Streamlit)
* Add model persistence (joblib)

---

## 🎯 Goal

Build a strong foundation in Scikit-learn by:

* Writing clean pipelines
* Understanding preprocessing deeply
* Learning through experimentation

---

## 📌 Author

Part of a structured ML learning roadmap (April 2026)

---
