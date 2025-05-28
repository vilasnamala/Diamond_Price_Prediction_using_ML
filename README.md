# Diamond_Price_Prediction_using_ML
This project predicts diamond prices based on features like carat, cut, color, and clarity using the Random Forest Regressor algorithm.
# Summary
This project aims to predict the price of diamonds based on various features such as carat, cut, color, clarity, depth, table, and dimensions using machine learning. The primary objective is to build a robust predictive model by employing different regression algorithms and selecting the one with the best performance.
**The project follows these steps:**
1. **Data Collection and Preprocessing:** The dataset is loaded and cleaned, with missing values handled and categorical features encoded using Label Encoding and One-Hot Encoding.
2. **Exploratory Data Analysis (EDA):** A thorough analysis of the dataset is conducted to understand feature distributions, correlations, and relationships between the target (price) and features. Visualizations like histograms, box plots, and pair plots are used to gain insights.
3. **Feature Scaling and Encoding:** Numerical features are scaled using StandardScaler, and categorical features are transformed into numerical format using label encoding and one-hot encoding to make the dataset ready for machine learning models.
4. **Model Evaluation:** Several regression algorithms, including Linear Regression, Decision Trees, Support Vector Regression, and Random Forest, are tested to evaluate their performance. Hyperparameter tuning and cross-validation are used to optimize the models.
5. **Model Selection:** After comparing the performance of various models using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²), Random Forest Regressor is selected as the best model due to its ability to handle complex non-linear relationships and prevent overfitting.
6. **Prediction on New Data:** A function is developed to predict the price of a new diamond based on input features. The model is then used to provide predictions for unseen data.
