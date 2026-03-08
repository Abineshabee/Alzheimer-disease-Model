# Machine Learning Model Comparison for Classification

## Overview

This project demonstrates a comparative study of multiple machine learning classification algorithms to evaluate their performance on a dataset. The objective is to train different models, tune their hyperparameters, and analyze their prediction accuracy.

Several classical and ensemble learning algorithms are implemented and compared to identify the best performing model.

The project is implemented using **Python and Jupyter Notebook**, making it easy to experiment with model training, parameter tuning, and performance evaluation.

---

# Algorithms Implemented

The following machine learning algorithms are implemented and evaluated:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* AdaBoost
* LightGBM
* XGBoost
* Voting Classifier (Ensemble Model)

Each model is trained with different hyperparameter configurations to determine the optimal settings.

---

# Hyperparameter Tuning

### Logistic Regression

Regularization parameter:

```
C = [0.001, 0.1, 1, 10, 100]
```

---

### Support Vector Machine (SVM)

Parameters tuned:

```
C = [0.001, 0.01, 0.1, 1, 10, 100, 1000]
gamma = [0.001, 0.01, 0.1, 1, 10, 100, 1000]
kernel = ['rbf', 'linear', 'poly', 'sigmoid']
```

---

### Decision Tree

Parameter tuned:

```
max_depth = [1 – 8]
```

---

### Random Forest

Parameters tuned:

```
n_estimators  → number of trees
max_features  → features considered for split
max_depth     → depth of trees
```

---

### Ensemble Models

The project also implements advanced ensemble models:

* AdaBoost
* LightGBM
* XGBoost

These algorithms combine multiple weak learners to produce stronger predictive performance.

---

# Ensemble Voting Classifier

A **Voting Classifier** is used to combine predictions from multiple models to improve overall accuracy and stability.

Voting strategies can include:

* Hard Voting
* Soft Voting

This approach often improves performance by leveraging the strengths of multiple algorithms.

---

# Project Structure

```
ML-Model-Comparison
│
├── demon233.ipynb      # Main Jupyter Notebook
├── dataset.csv            # Dataset used for training 
├── README.md           # Project documentation
```

---

# Installation

Clone the repository:

```
git clone https://github.com/Abineshabee/Alzheimer-disease-Model.git
```

Navigate to the project directory:

```
cd Alzheimer-disease-Model
```

Install required libraries:

```
pip install numpy pandas scikit-learn matplotlib seaborn xgboost lightgbm
```

---

# Running the Project

Open the notebook:

```
jupyter notebook demon233.ipynb
```

Run all cells to train models and compare results.

---

# Results

The project evaluates and compares models based on performance metrics such as:

* Accuracy
* Model efficiency
* Prediction performance

The final results section highlights which algorithm performs best for the dataset used.

---

# Applications

This project can be useful for:

* Learning machine learning model comparison
* Understanding ensemble learning techniques
* Practicing hyperparameter tuning
* Building classification pipelines

---

# Author

Abinesh N

---

