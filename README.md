# Regression and classification with Ames housing data

There are three components to the project:

1. Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. The goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
3. Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).

This project uses the [Ames housing data recently made available on kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

Please see "work_notebook" for all the work on this project done in the Jupyter notebook.

---
## Part 1
- **tools used:** Python, Scikit-learn, Pandas, Numpy, Matplotlib
- **models/techniques developed:** TrainTestSplit, GridSearchCV, Pipelines, StandardScaler, SelectKBest, SelectFromModel, ElasticNet with Lasso, RandomForest Regressor with Feature Selection, ExtraTrees Regressor

## Part 2
- **tools used:** Python, Scikit-learn, Pandas, Matplotlib
- **models/techniques developed:** TrainTestSplit, GridSearchCV, Pipelines, StandardScaler, SelectKBest, SelectFromModel, ElasticNet with Lasso, RandomForest Regressor with Feature Selection, ExtraTrees Regressor

## Part 3
- **tools used:** Python, Scikit-learn, Pandas, Matplotlib
- **models/techniques developed:** TrainTestSplit, GridSearchCV, Pipelines, StandardScaler, AdaBoostClassifier, GradientBoostingClassifier, XGBoostClassifier, Classification Report, Confusion Matrix, ROC curve

