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
- ## Model Performance

Three machine learning models were evaluated on the test dataset.

| Model | Train Accuracy | Test Accuracy | Macro F1 |
|---|---:|---:|---:|
| Decision Tree | 100.0% | 60.2% | 0.595 |
| KNN | 67.1% | 49.4% | 0.479 |
| Random Forest | 100.0% | 68.0% | 0.665 |

Random Forest achieved the strongest test performance among the three models evaluated, with a test accuracy of 68.0% and a Macro F1-score of approximately 0.665.

## Key Findings

- Random Forest performed better than Decision Tree and KNN on the test dataset.
- Decision Tree and Random Forest both achieved 100% training accuracy, indicating possible overfitting.
- The Bacterial class had the lowest F1-score, at approximately 0.469.
- The most frequent misclassification was Bacterial cases being predicted as Healthy.
- Feature engineering included Heat-Humidity Index, Drought Stress and Plant Maturity Stage.

## Final Conclusion

The project demonstrates a complete machine learning workflow for crop disease classification, including exploratory data analysis, data cleaning, feature engineering, encoding, model training and evaluation.

Among the models tested, Random Forest provided the strongest overall test performance. However, the gap between training and test accuracy suggests that further model tuning would be useful before considering real-world deployment.

Future improvements could include:

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Testing additional models
- Improving class-wise performance, especially for Bacterial disease detection
