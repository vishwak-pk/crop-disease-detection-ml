# Crop Disease Detection Using Machine Learning

This project predicts crop disease categories using environmental,
soil and farm-management data.

## Problem Type
Multi-class Classification

## Target Classes
- Healthy
- Fungal
- Bacterial
- Pest Damage

## Workflow
- Exploratory Data Analysis
- Data Cleaning
- Missing Value Imputation
- Feature Engineering
- One-Hot Encoding
- Train/Test Split
- Feature Scaling for KNN
- Decision Tree
- K-Nearest Neighbours
- Random Forest
- Model Evaluation

## Feature Engineering
Three additional features were created:

- HTI — Heat-Humidity Index
- Drought Stress
- Plant Maturity Stage

## Models Evaluated

| Model | Test Accuracy | Macro F1 |
|---|---:|---:|
| Decision Tree | 60.2% | 0.595 |
| KNN | 49.4% | 0.479 |
| Random Forest | 68.0% | 0.665 |

Random Forest achieved the strongest test performance among the
three models evaluated.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
