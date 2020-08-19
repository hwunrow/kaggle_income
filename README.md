# kaggle_income
Course kaggle competition to income using US census data. Placed in top 10 out of 50 students.

Jupyter notebook contains EDA and feature engineering. Initially evaluated 5 models (logistic regression, k-nearest neighbors, decision trees, random forest, and gradient boosting) with sklearn. Used grid search for hyperparameter tuning for random forest and gradient boosting. The final model chosen was random forest since it had the highest 10-fold cross-validation accuracy and there was no need to consider a real-time prediction scenario.
