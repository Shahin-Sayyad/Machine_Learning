# Machine_Learning

Heart Disease Prediction Project
This project predicts the likelihood of heart disease using machine learning models. The dataset contains 303 records with 14 features including age, sex, cholesterol levels, and more.

Data Preprocessing
Feature Engineering: Categorical variables were converted into dummy variables to avoid treating them as ordinal data.
Feature Scaling: Continuous features were standardized using StandardScaler.
Train-Test Split: The dataset was split into independent features (X) and the target (y) for model training.
Models
K-Nearest Neighbors (KNN) Classifier:

Explored K values from 1 to 20.
Best accuracy (85.07%) was achieved with K = 12.
Decision Tree Classifier:

Tested max depths from 1 to 10.
Best accuracy (78.77%) was achieved with max depth = 3.
Random Forest Classifier:

Tested the number of estimators from 10 to 100.
Best accuracy (83.82%) was achieved with 90 estimators.
Visualization
Correlation Heatmap: Visualized the correlation between features to aid feature selection.
Accuracy Plots: Showed model performance across different parameter values.
These models can be used for early prediction of heart disease based on patient data.
