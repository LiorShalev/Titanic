# Titanic Case
Titanic - Machine Learning from Disaster

Titanic Survival Prediction Project
Goal:
Predict survival outcomes of passengers on the Titanic using machine learning models.

Dataset:
Source: Titanic dataset from Kaggle.

Details: Processed and split into training and test sets (80/20 split).

Key Steps:
Data Preprocessing:

Handled Missing Data: Filled missing values (e.g., median for Age, mode for Embarked).

Categorical Variables: Converted categorical features like Sex and Embarked into numeric values.

Feature Selection: Removed irrelevant features such as Ticket and Cabin.

Feature Engineering:

Created new features:
FamilySize: Combined SibSp and Parch to represent the total number of family members.
Feature Importance Analysis: Evaluated features' impact on model performance, guiding refinement steps.
Models Implemented:

Random Forest:
Accuracy: 88% on the test set.
Best Performing Model: Highest accuracy among all models tested.
Tuning: Hyperparameter tuning with RandomizedSearchCV led to further accuracy improvements.

XGBoost:
Accuracy: Reached ~86% after extensive hyperparameter tuning.
Despite strong performance, slightly behind the Random Forest model.
Gradient Boosting:
Accuracy: Achieved ~82% accuracy.
Less competitive than Random Forest and XGBoost.
Model Evaluation:

Metrics Used:
Accuracy, Confusion Matrix, and Classification Report for detailed model performance.
Model Comparisons: Random Forest consistently outperformed the other models across multiple evaluation metrics.
Hyperparameter Tuning:

RandomizedSearchCV: Used for both Random Forest and XGBoost to optimize parameters and boost accuracy.

Conclusion:
The Random Forest model achieved the best results with an accuracy of 88%, making it the model of choice for this project.
