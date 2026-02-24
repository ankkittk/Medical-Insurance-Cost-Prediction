# Medical-Insurance-Cost-Prediction

## --> Regression-Based Prediction System

## Overview

This project implements a Machine Learning regression model using Scikit-learn to predict numerical outcomes based on multiple input features. The system demonstrates a complete ML workflow including data preprocessing, model training, evaluation, and real-time prediction using user-provided inputs.

The objective of this project is to understand how regression models learn relationships between independent variables and a target variable and how trained models can be used for practical predictions.

---

## Project Objectives

* Perform data preprocessing and feature preparation
* Train a regression model using structured data
* Evaluate model performance using appropriate metrics
* Build a prediction pipeline for new input samples
* Understand model input shape requirements in Scikit-learn

---

## Machine Learning Concept Used

### Regression

Regression is a supervised learning technique used to predict continuous numerical values.

The model learns:

Target Variable = f(Feature₁, Feature₂, Feature₃, ...)

This project uses a Linear Regression model, which assumes a linear relationship between features and output.

---

## Technologies Used

* Python 3.10
* NumPy
* Pandas
* Scikit-learn
* Jupyter Notebook



## Workflow Pipeline

### 1️⃣ Data Loading

* Dataset imported using Pandas
* Features and target variable separated

### 2️⃣ Data Preprocessing

* Conversion to NumPy arrays
* Feature selection
* Train-test split

### 3️⃣ Model Training

* Linear Regression model initialized
* Model trained using training dataset

```
regressor.fit(X_train, Y_train)
```

### 4️⃣ Model Evaluation

Performance evaluated using prediction accuracy metrics.

### 5️⃣ Prediction Phase

New input data is reshaped and passed to the trained model:

```
input_data.reshape(1, -1)
```

This ensures compatibility with Scikit-learn’s required input format.

---

## 📈 Example Prediction

Input Features:

```
(31, 1, 25.74, 0, 1, 0)
```

Model Output:

```
Predicted Value → Numerical regression result
```


## Key Learnings

* Understanding regression modeling workflow
* Importance of data shape in ML pipelines
* Model training vs prediction phases
* Handling real-world prediction inputs
* Debugging common sklearn errors

---

## Future Improvements

* Add feature scaling (StandardScaler)
* Compare multiple regression models
* Hyperparameter tuning
* Model serialization using Pickle
* Build a simple prediction UI (Streamlit/Flask)

---

## Educational Purpose

This project is developed for academic learning and practical understanding of machine learning regression concepts and implementation using Python.

---

## Author

Developed as part of machine learning practice and academic coursework.
