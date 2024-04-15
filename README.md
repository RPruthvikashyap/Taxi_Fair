Ethical Considerations
Request Review: Evaluate the ethical implications of alerting taxi drivers to customers who are unlikely to tip.
Potential Bias: Consider the risk of biases in the data and its impact on certain customer groups.
Objective Adjustment: Decide whether the model's objective should be adjusted for fairness.
Driver Safety: Examine how the model's predictions might affect driver-customer interactions and safety.
Feature Engineering
Feature Selection: Choose relevant features such as ride distance, time of day, and payment method.
Feature Extraction: Calculate new features like tip percentage based on provided data.
Data Cleaning: Handle missing values and remove irrelevant or redundant features.
Data Transformation: Convert categorical features into numerical format and standardize data.
Modeling
Random Forest:
Model: Use GridSearchCV to tune a Random Forest classifier (rf) with hyperparameters such as max_depth, n_estimators, and min_samples_leaf.
Scoring: Evaluate model performance using precision, recall, F1 score, and accuracy.
Cross-validation: Perform cross-validation to validate model performance.
Model Selection: Choose the best model based on the F1 score.
XGBoost:
Model: Use GridSearchCV to tune an XGBoost classifier (xgb) with parameters like max_depth, learning_rate, and n_estimators.
Scoring: Evaluate model performance using the same metrics as above.
Cross-validation: Perform cross-validation to validate model performance.
Model Selection: Choose the best model based on the F1 score.
