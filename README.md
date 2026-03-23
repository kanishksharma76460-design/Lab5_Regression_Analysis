# Lab5_Regression_Analysis
This lab focuses on regression analysis using Python, where relationships between variables are modeled and evaluated. It covers data preprocessing, model building, and performance metrics like R² and MSE to assess prediction accuracy.

Overview: 
This lab explores machine learning models to solve a structured dataset problem.
For classification tasks: Predict categorical outcomes (e.g., survival on Titanic).
For regression tasks: Predict continuous outcomes (e.g., temperature values).
The goal is to compare models, interpret results, and highlight trade-offs between accuracy, interpretability, and generalization.

Step 1: Import Libraries
{ pandas, numpy, matplotlib, seaborn }

scikit-learn (preprocessing, models, metrics)

Load Data:
Training and test datasets loaded from CSV file
Preview dataset shape and first few rows

Data Cleaning & Preprocessing:
Drop irrelevant columns (IDs, names, etc.).
Handle missing values (median for numeric, mode for categorical).
Encode categorical variables (for classification).
Align train and test columns.
Separate features (X_train, X_test) and target (y_train, y_test).

Feature Scaling:
StandardScaler applied to numerical features.
Ensures fair comparison across models.

Step 5: Train Models:
Classification::
KNN: Baseline model.
Logistic Regression: Highest accuracy, interpretable coefficients.
Decision Tree Classifier: Captures non-linear rules, feature importance.

Regression::
Linear Regression: Simple, interpretable baseline.
Decision Tree Regression: Captures non-linear relationships, stronger predictive power.

Evaluation:
Classification Metrics
Accuracy score

Classification report::

Confusion matrix

Regression Metrics
R² Score (goodness of fit)
RMSE (Root Mean Squared Error)

Conclusion:

Classification: Logistic Regression emerged as the best-performing model, balancing accuracy and interpretability.
Regression: Decision Tree Regression achieved higher R² and lower RMSE, showing stronger predictive power.
Trade-offs: Logistic Regression offers interpretability, Decision Trees capture complexity but risk overfitting, and KNN/Linear Regression provide baselines.

