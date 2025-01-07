# Fraud Detection using Credit Card Transactions

## Project Overview

This project involves detecting fraudulent credit card transactions using machine learning techniques. The dataset contains information about various transactions, and the goal is to classify whether a transaction is fraudulent or legitimate. This can help financial institutions and credit card companies mitigate fraud risks and protect their users.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Methods Overview](#Methods-Overview)
- [Requirements](#requirements)
- [Final Model Scores](#Final-Model-Scores-(Observations))
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)

---

## Methods Overview

The project employed a structured approach that included the following steps:
1. **Data Preprocessing**: Cleaning and transforming raw data into a usable format.
2. **Feature Engineering**: Deriving meaningful features to improve model performance.
3. **Correlation Analysis**: Investigating feature relationships.
4. **Modeling**: Using Logistic Regression, Decision Trees, and various sampling techniques (SMOTE, undersampling, oversampling) to build models.
5. **Evaluation**: Comparing model performance using metrics like accuracy, AUC, and confusion matrix.


---

## Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - (Any additional libraries used in your notebook)

---

## Data Preprocessing

The preprocessing steps included:
- Handling missing values.
- Encoding categorical variables.
- Standardizing/normalizing numerical features.
- Splitting data into training and testing sets.

## Final Model Scores (Observations)

| Model/Sampling Method   | AUC |  Precision  |
|--------------------------|-----------|--------|
| Logistic Regression      | 0.500     | 0.005  |
| Decision Trees           | 0.891     | 0.744  |
| Random Forest            | 0.870     | 0.728  |
| SMOTE + Decision         | 0.9303    | 0.213  |
| Undersampling + Decision | 0.966     | 0.147  |
| Oversampling + Decision  | 0.968     | 0.244  |

The final model effectively distinguishes between fraudulent and legitimate transactions, as indicated by the metrics above.

---

## Future Improvements

- Incorporate deep learning techniques such as neural networks for potentially higher accuracy.
- Use real-time fraud detection techniques for live data streams.

---

## Acknowledgments

- The dataset used for this project is sourced from [kaggle](https://www.kaggle.com/code/mohamedalabasy/credit-card-transactions).
- Inspiration for the project was derived from the need for robust fraud detection systems in financial services.

---



