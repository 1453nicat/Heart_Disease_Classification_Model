# Heart_Disease_Classification_Model

Initially, this project implements a machine learning classification pipeline to predict heart disease using the UCI Heart Disease dataset. The pipeline includes data preprocessing (handling missing values and scaling), training multiple models (Logistic Regression, K-Nearest Neighbors, and Decision Tree), hyperparameter tuning, and performance evaluation using accuracy, confusion matrices, and classification reports. The project is implemented in Python and designed to run in Google Colab.
Dataset

# Features

- Preprocessing: Handles missing values using mean imputation and applies standard scaling to all features.
- Models: Logistic Regression, K-Nearest Neighbors (KNN), and Decision Tree.
- Hyperparameter Tuning: Uses GridSearchCV to optimize model parameters.
- Evaluation: Reports accuracy, confusion matrices, and classification reports for each model.

# Results

- KNN: Highest accuracy at 85%, indicating strong performance in capturing data patterns.
- Logistic Regression: Close second with 84% accuracy, suggesting linear separability in the preprocessed data.
- Decision Tree: Lowest at 74%, potentially due to sensitivity to numerical treatment of categorical features.

In conclusion, KNN is the best-performing model, but future improvements could involve one-hot encoding for categorical features like sex and cp to enhance performance.

# Dataset
UCI Heart Disease Dataset (Cleveland) that contains 303 instances with 13 features (e.g., age, sex, cholesterol, chest pain type) and a binary target variable (0 = no heart disease, 1 = heart disease).

MIT License
Copyright (c) 2025 *1453nicat*
