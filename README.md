# Crop Recommendation System

A machine learning project focused on analyzing soil measurements to identify the most predictive feature for crop selection using multi-class classification techniques.

## Project Overview

This project explores how soil nutrients and pH levels influence crop selection. Using machine learning and exploratory data analysis, the project evaluates which soil feature contributes most to predicting the optimal crop type.

The dataset contains agricultural soil measurements including nitrogen, phosphorus, potassium, and pH values for different crop categories.

---

## Dataset Features

The dataset includes the following features:

- `N` — Nitrogen content ratio in soil
- `P` — Phosphorous content ratio in soil
- `K` — Potassium content ratio in soil
- `ph` — Soil pH value

Target variable:

- `crop` — Recommended crop type

---

## Workflow

### 1. Data Loading and Exploration
- Loaded and explored the dataset using Pandas
- Checked dataset structure, statistics, and class distribution
- Verified balanced crop categories

### 2. Exploratory Data Analysis (EDA)
- Analyzed numerical feature distributions
- Reviewed dataset statistics and crop frequency distribution

### 3. Feature Evaluation
- Applied Logistic Regression for multi-class classification
- Evaluated each soil feature individually
- Measured predictive performance using weighted F1-score

### 4. Visualization
- Visualized feature performance using bar charts
- Compared predictive contribution of soil measurements

---

## Model Performance

### Best Predictive Feature
- Feature: `K` (Potassium)
- Weighted F1 Score: **0.25**

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Key Skills Demonstrated

- Multi-class Classification
- Logistic Regression
- Feature Evaluation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning Workflows
- Model Evaluation using F1-score

---

## Future Improvements

Possible future enhancements include:

- Training models using all features together
- Comparing multiple classification algorithms
- Hyperparameter tuning
- Confusion matrix visualization
- Cross-validation
- Feature importance analysis using advanced models

Youssef Issa
