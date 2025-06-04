# Student Dropout Prediction using Deep Learning

This project aims to predict student academic outcomes (Dropout, Enrolled, Graduate) based on various academic, demographic, and financial features using deep learning techniques.

---

## Features

- Clean and preprocess real-world tabular data.
- Encode categorical features and scale numerical features.
- Train and evaluate a **Feedforward Neural Network (FNN)** model.
- Apply **regularization** (L1, L2, Dropout) to reduce overfitting.
- Test multiple **optimizers**: Adam, SGD, RMSprop.
- Tune hyperparameters using:
  - Grid Search
  - Random Search
  - Optuna Bayesian Optimization
- Perform **5-fold Stratified Cross-Validation** for robust evaluation.
- Visualize training and validation performance.
- Analyze results using classification reports and confusion matrices.

---

## Dataset

- Source: `data.csv`
- Format: CSV with semicolon delimiters (`;`), no headers
- Target column: `Target` (values: `Dropout`, `Enrolled`, `Graduate`)
- Features include:
  - Demographics (Age, Gender, Nationality)
  - Education background (Previous qualification, Grades)
  - Enrollment and performance metrics
  - Financial information (Tuition fees, Scholarship status)

---

## Model Evaluation

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- Cross-Validation Accuracy

---

## Results

- Achieved up to **76.67%** validation accuracy (based on best model)
- Best parameters found via Optuna or Random Search can be viewed in the notebook

---

