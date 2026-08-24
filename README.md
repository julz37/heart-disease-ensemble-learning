# heart-disease-ensemble-learning
Ensemble machine learning comparison for heart disease classification using Python, Scikit-learn, XGBoost, and LightGBM
# Heart Disease Classification with Ensemble Learning

An end-to-end supervised machine learning project comparing multiple ensemble learning algorithms for heart disease classification.

## View the Project

- [Interactive Kaggle Notebook](https://www.kaggle.com/code/julianchristianiii/heart-disease-ensemble-learning)
- [GitHub Repository](https://github.com/julz37/heart-disease-ensemble-learning)

## Project Overview

This project evaluates whether ensemble machine learning methods can improve predictive robustness and generalization over a single Decision Tree classifier.

The analysis compares seven supervised learning algorithms:

- Decision Tree
- Bagging
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM

The workflow includes exploratory data analysis, data preprocessing, model development, model comparison, feature importance analysis, hyperparameter optimization, and stratified cross-validation.

## Problem

The objective is to predict whether a patient has heart disease using demographic and clinical indicators.

The target variable is binary:

- `0` – No heart disease
- `1` – Heart disease present

## Dataset

Features include:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate
- Exercise-induced angina
- ST depression
- ST slope
- Number of major vessels
- Thalassemia status

After duplicate removal, the cleaned dataset contains 302 unique observations.

## Machine Learning Workflow

1. Data loading and validation
2. Exploratory data analysis
3. Missing-value and duplicate analysis
4. Data preprocessing
5. Train/test split
6. Baseline Decision Tree modeling
7. Bagging and Random Forest modeling
8. Boosting model development
9. Model performance comparison
10. Feature importance analysis
11. Five-fold stratified cross-validation
12. GridSearchCV hyperparameter optimization
13. Final model evaluation

## Models Evaluated

| Model | Category |
|---|---|
| Decision Tree | Baseline |
| Bagging | Ensemble |
| Random Forest | Ensemble |
| AdaBoost | Boosting |
| Gradient Boosting | Boosting |
| XGBoost | Gradient Boosting |
| LightGBM | Gradient Boosting |

## Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 score
- Confusion matrix
- Training accuracy
- Testing accuracy
- Training/testing performance gap
- Out-of-Bag score where applicable
- Cross-validation accuracy
- Training time

## Key Finding

The baseline Decision Tree achieved strong testing performance but also reached perfect training accuracy, indicating substantial overfitting.

After hyperparameter optimization and stratified cross-validation, the tuned Random Forest provided a better balance between predictive performance and generalization.

This illustrates an important machine learning principle: the model with the highest apparent accuracy is not necessarily the model most likely to generalize reliably to unseen data.

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

## Future Improvements

Future work could include:

- Larger and more diverse datasets
- SHAP model explainability
- LIME explanations
- CatBoost
- Extra Trees
- RandomizedSearchCV
- Bayesian hyperparameter optimization
- Repeated cross-validation

## Author

**Julian Christian III**

Artificial Intelligence | Machine Learning | Software Development | Cybersecurity

- GitHub: https://github.com/julz37
- Kaggle: https://www.kaggle.com/julianchristianiii
