# Diabetes_Analysis_ANN

Objective:
Required to model the progression of diabetes using the available independent
variables. This model will help healthcare professionals understand how different factors
influence the progression of diabetes and potentially aid in designing better treatment
plans and preventive measures. The model will provide insights into the dynamics of
diabetes progression in patients.

Dataset: Use the Diabetes dataset available in the sklearn library.

### What the Code Does
- Loads & Preprocesses Data: Pulls the Diabetes dataset, checks for missing data, splits it into training and testing sets, and standardizes the features.Exploratory - Data Analysis (EDA): Analyzes feature distributions and correlations before any scaling happens to keep the data pure.
- Builds & Trains the ANN: Sets up a tuned network with hidden layers, LeakyReLU activation to prevent dead nodes, and Dropout/L2 regularisation to stop overfitting.
- Evaluates & Benchmarks: Checks performance using R-squared (R²), MSE, MAE
- Saves for Future Use: Exports the finalized model and scaler assets to your disk so they can make predictions on new data later.

### Saved Models
- diabetes_ann_model.keras — Contains the neural network's architecture and weights.
- diabetes_scaler.joblib — Stores the exact mathematical scaling parameters from the training set.
